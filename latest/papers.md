# 📑 论文索引 - 2026-09-23

共 256 篇论文

---

### [1] BabelArena: A Large-Scale Multilingual Benchmark for LLM Agents

**链接**: https://arxiv.org/abs/2609.23490
**作者**: Peng Kuang, Yuchun Fan, Jiangnan Li, Minghao Wu, Jialong Tang, Hao-Ran Wei 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly execute multi-step workflows through tool use and interaction with users and environments. However, current agent evaluations are largely English-centric, limiting our understanding of agent capabilities in multilingual settings. We introduce BabelFlow, a benchmark-general agentic workflow that adapts existing agent benchmarks to new languages by analyzing runtime dependencies, coordinating structure-preserving translation, and combining multi-layer verification with human review to preserve task and evaluation semantics. Using BabelFlow, we construct BabelArena, a task-aligned benchmark comprising 16,146 instances derived from 702 canonical tasks across four benchmark families, 13 domains, and 23 languages. Experiments with five frontier models show that no single model dominates across benchmark families and that cross-language disparities extend well beyond task success. Lower-resource languages exhibit distinct failure patterns, with l

---

### [2] ActGov: Governing LLM Agent Actions via Policy-Constrained Validation

**链接**: https://arxiv.org/abs/2609.24446
**作者**: Kaiyuan Zhang, Yuke Peng, Ke Jiang, Yinqian Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly execute long-horizon workflows through external tools, allowing untrusted outputs to influence subsequent actions and exceed user authorization. Existing defenses isolate injected content or constrain execution with predefined plans and static policies, but these approaches are brittle under dynamic workflows and scale poorly across extensible tool ecosystems. In this work, we present ActGov, a runtime enforcement framework that validates each LLM-proposed tool action before it causes external effects. Built on a unified semantic model of authorization, actions, runtime context, and security constraints, the ActGov-Policy component iteratively constructs a policy set from tool specifications, benign tasks, and observed failure traces, with each update verified through SMT-based counterexample checking. At runtime, ActGov-Runtime abstracts each tool call into finite policy records and permits it only if it remains within the task-scoped aut

---

### [3] CALM: A Calibrated LLM Choice Network Framework for Activity-Based Traveler Simulation

**链接**: https://arxiv.org/abs/2609.22252
**作者**: Yezhou Cheng
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present CALM, a reproducible hybrid framework that integrates an optional large language model (LLM) activity planner with calibrated stochastic choice, shared network feedback, memory and habit, typed feasibility checks, and deterministic offline replay. Unlike trip-mode classifiers or diary-only generators, CALM executes a closed traveler-day loop and evaluates each generative module against an empirical, reproducible baseline. On the 2024 New York City Citywide Mobility Survey (CMS), 110,691 seven-mode trips are split by respondent into 78,487 training and 32,204 holdout trips. Training-only alternative-specific constant calibration reduces mean holdout mode Jensen-Shannon divergence from 0.15599 to 0.00394 across ten seeds. A matched live-LLM ablation then quantifies trade-offs among aggregate fit, temporal fit, behavioral persistence, and feasibility, while frozen prompt-response pairs support deterministic replay of downstream simulation. Controlled weather, delay, fare, and p

---

### [4] An LLM-Assisted AutoML Framework for Intrusion Detection in IoT Networks

**链接**: https://arxiv.org/abs/2609.23097
**作者**: Li Yang
**来源**: cs.CR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Internet of Things (IoT) systems are increasingly deployed in smart homes, transportation, energy systems, and critical infrastructure. This broad connectivity improves service intelligence, but also enlarges the attack surface of IoT networks. Machine Learning (ML)-based Intrusion Detection Systems (IDSs) are widely used to identify malicious network threats and protect IoT systems, but developing effective ML-based IDS models often requires human expertise and repeated manual decisions on many procedures, including data pre-processing, feature selection, model selection, and hyperparameter tuning. Automated Machine Learning (AutoML) reduces this burden by automating steps of the ML pipeline using optimization techniques, but conventional AutoML methods can consume substantial optimization time because they explore broad candidate model families and large hyperparameter spaces. This paper proposes a Large Language Model (LLM)-assisted AutoML framework for IoT intrusion detection. The 

---

### [5] ProcessLight: Process Supervision for Large Language Model Based Traffic Signal Control

**链接**: https://arxiv.org/abs/2609.22746
**作者**: Huaitao Zhao, Tianlong Zhou, Weijie Wang, Jiasheng Shi, Weixiong Rao
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have recently been introduced into traffic signal control (TSC) as decision agents due to their strengths in human-readable reasoning generation. Yet, existing LLM TSC methods optimize only from final outcomes and fail to distinguish valid from flawed reasoning steps, causing useful or misleading steps to be jointly updated and thus impairing the model's learning of effective reasoning. To bridge this gap, we propose an LLM-based framework ProcessLight to decompose signal decisions into verifiable semantic steps. Building on ProcessLight, we further develop Step-wise Traffic Process Policy Optimization (STeP-PO), a novel reinforcement learning framework that optimizes structured reasoning processes through step-level credit assignment. Specifically, STeP-PO uses step quality scores to evaluate local reasoning quality and step importance to measure each step's influence on the final action, and then assigns step-level advantages over a semantic step tree str

---

### [6] From Inference Engine to Inference Control Plane: Connecting vLLM, llm-d, and the Evolution of Efficient Distributed LLM Serving

**链接**: https://arxiv.org/abs/2609.23130
**作者**: Twinkll Sisodia
**来源**: cs.AI cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference is evolving from an engine-local optimization problem into a distributed control problem involving reusable state, phase placement, heterogeneous accelerators, networking, autoscaling, reliability, and service-level objectives. This paper connects that transition across peer-reviewed systems research, open-source implementations, and documented production studies. It treats vLLM and llm-d as complementary layers: model-serving engines optimize execution through mechanisms such as PagedAttention, continuous batching, kernels, quantization, and parallelism, while an inference control plane can optimize where, when, and under what policy execution occurs across a fleet. The contribution is synthesis rather than a new benchmark; all reported performance and deployment results remain attributed to their original sources. The combined evidence suggests that the scarce resource in modern inference is shifting from raw FLOPs alone toward managed state, plac

---

### [7] StepKV: Step-Aware KV Cache Compression for LLM Agents

**链接**: https://arxiv.org/abs/2609.22158
**作者**: Boyu Feng, Jiahong Liu, Yifan Li, Wenhao Yu, Zexuan Qiu, Yuliang Sun 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Key-value (KV) caching is essential for efficient autoregressive large language model (LLM) inference, but the cache grows linearly with context length, increasing storage and decoding costs. KV cache compression mitigates this cost by retaining only a subset of cached tokens. This challenge is particularly important for multi-step LLM agents, where a query expands into trajectories of reasoning, tool interactions, and retrieved observations. Existing pruning methods typically treat the cache as a flat token stream and rank tokens by recency or attention saliency. This creates a mismatch between the unit of compression and the unit of reasoning: token-level pruning removes individual entries, whereas useful information in multi-step agents is often organized into reasoning steps with uneven and delayed importance. Consequently, an early observation or intermediate decision may receive little recent attention yet remain essential for later evidence synthesis. We term this failure mode R

---

### [8] MAWILE: Multi-Axis Workbench for Inspecting LLM Evaluators

**链接**: https://arxiv.org/abs/2609.22599
**作者**: Jackson Hassell, Farima Fatahi Bayat, Pouya Pezeshkpour, Estevam Hruschka
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) judges provide a flexible and scalable method for evaluating model and agent outputs, but their verdicts can be sensitive to incidental changes in the evaluated response, judge instructions, and scoring rubric. Existing systems examine important subsets of these failure modes, but auditing a configured judge requires testing both the judge instrument and the items it evaluates. We introduce MAWILE, a developer-facing workbench for auditing judge sensitivity across four surfaces: the judge prompt, judge rubric, target-system input, and target-system output. Given a user-supplied judge and representative evaluation items, MAWILE constructs and validates controlled perturbations, re-executes the judge, and localizes the resulting sensitivity. Each perturbation declares whether the verdict should remain invariant or change in a specified direction, allowing the same system to measure both robustness to irrelevant variations and sensitivity to meaningful changes. 

---

### [9] PhysAI-Bench: A Benchmark for LLM-Based Agentic Decision-Making in Autonomous UAV-Centric Physical AI

**链接**: https://arxiv.org/abs/2609.23695
**作者**: Mohamed Amine Ferrag, Merouane Debbah, Abderrahmane Lakas, Manu Perumkunnil, Norbert Tihanyi
**来源**: cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Physical AI have accelerated the use of foundation models in autonomous systems such as unmanned aerial vehicles (UAVs), which must perceive, reason, plan, and act in dynamic environments. Existing benchmarks assess physical perception, intuitive physics, embodied navigation, and collaborative reasoning, but rarely evaluate the agentic decision-making required for reliable autonomy. We introduce \textit{PhysAI-Bench}, a benchmark for evaluating this capability. It contains 10,178 standardized decision instances automatically extracted from conversational traces of autonomous UAV missions. Each instance preserves mission context, temporal dependencies, physical constraints, Model Context Protocol (MCP) tool calls, Agent-to-Agent (A2A) interactions, sensor observations, and AI-native 6G network conditions, including latency, packet loss, throughput, edge load, and network slicing. We expose only information preceding each decision, preventing future-event leakage and a

---

### [10] Total Cost of Agency: Exact Attribution of Memory Injection Cost in Multi-Agent LLM Workflows

**链接**: https://arxiv.org/abs/2609.23790
**作者**: Vivek Kumar Singh, Preeti Priyam, Gautam Bhowmick
**来源**: cs.AI cs.MA cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Every node in a multi-agent large language model (LLM) workflow retrieves context from memory and injects it into its prompt, where those injected tokens are billed as input tokens at the same per-token price as the system prompt and the user query. Production observability tools report total token cost but do not separate the tokens a node generates from the tokens it is handed, so this component of the bill is invisible to the teams paying it. We introduce the Total Cost of Agency (TCA), a decomposition of multi-agent workflow cost into base prompt, inference, memory injection, miss penalty and context-accumulation components, and an exact attribution method: a two-pass, non-billable token count that measures injected tokens directly rather than estimating them from word-count proxies. On a 200-task enterprise benchmark executed against real model APIs, memory injection accounts for 13.6 percent of the variable cost a compile-time optimizer can act on, about 12 percent of the full bi

---

### [11] Apollo Restore: A Foundation LLM for Historical Greek Optimized for Fill-in-the-Middle Restoration of Ancient Greek Texts

**链接**: https://arxiv.org/abs/2609.22455
**作者**: Hope McGovern, Anna Dolganov, Samuel Belkadi, Guillaume Kunsch, Dimitris Vlitas, and David A. Smith
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Apollo Restore, a 24-billion-parameter large language model for restoring lacunae---physical gaps---in fragmentary Ancient Greek texts. Fine-tuned from Mistral Small with a fill-in-the-middle objective, Apollo Restore reconstructs missing spans without requiring oracle knowledge of their length. To our knowledge, it is the first large-scale decoder model for historical Greek, and the first for any ancient Mediterranean language. Evaluated as in prior work, on short gaps of up to ten characters, Apollo Restore places the correct restoration among its top twenty candidates for 80.6%/54.6%/61.0% of documentary-papyrus, literary-papyrus, and stone-inscription lacunae, exceeding the strongest published models by $1.6\times$/$2.6\times$/$1.4\times$. Prior evaluation protocols, however, inflate scores through a bias toward trivially short gaps; under a length-balanced metric Apollo Restore's advantage over the strongest published models grows to $2.3\times$/$3.5\times$/$1.6\times$ 

---

### [12] AI Persona, Service Consumption, and User Intent Entropy: Field Experimental Evidence from an LLM Platform

**链接**: https://arxiv.org/abs/2609.23274
**作者**: Junjie Li, Xiaofan Li, Lauren Xiaoyuan Lu, Yiwei Wang, Bruce Yang
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Problem definition: Firms deploying large language model services must decide how their AI communicates, not just what it can do. We examine how a relational persona - warmer, more empathetic and more engaging than a non-relational persona - affects service consumption and the evolution of user objectives. Methodology/results: In a randomized field experiment with 9,586 newly registered users, we hold the underlying model and service capabilities constant. The relational persona increases interactions (sessions, +8.1%; duration, +10.6%; chat rounds, +24.2%; intent entropy, +5.8%) and outputs (files, +12.3%; distinct goals, +12.1%). Effects vary by entry intent. First-session effects are insignificant for Task Execution users. Socialization and Knowledge Exploration users show similar increases in chat rounds: Socialization increases intent entropy without more outputs, whereas Knowledge Exploration increases outputs without higher intent entropy. Modeling intent dynamics as a transitio

---

### [13] RAILS: Retrieval-Augmented Incremental LLM Clustering at Scale

**链接**: https://arxiv.org/abs/2609.24464
**作者**: Armin Oliya, Aleksandra Sawczuk, Rados{\l}aw Bia{\l}obrzeski
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Using a Large Language Model (LLM) as the clusterer at production scale is hard: prompts cannot hold the entire label space, and per-document serial processing does not deliver the throughput real workloads require. We present RAILS, a retrieval-augmented incremental LLM clusterer that turns clustering into a simple loop over a growing label pool and scales through document batching with bounded concurrency. On six public benchmarks RAILS exceeds the strongest prior LLM-clustering method on average, lifting accuracy from 51.2% to 59.3%, NMI from 67.2% to 74.8%, and ARI from 45.4% to 54.7%. We further report production-deployment evidence from a SaaS ticket-topic-discovery pipeline, where RAILS has replaced a traditional HDBSCAN stage with higher clustering quality, transparent prompt-driven control, and stateful incremental operation.

---

### [14] Prompting Against Persona Drift: Comparing Intervention Timing and Content in LLM-Simulated Conversations

**链接**: https://arxiv.org/abs/2609.24532
**作者**: Nicolas Leins, Jennifer Haase, Varvara Geronimus, Jana Gonnermann-M\"uller and Sebastian Pokutta
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulating student personas with large language models (LLMs) enables scalable evaluation of educational systems. However, behavioral drift, a progressive decline in persona consistency, can emerge over extended conversations, limiting the validity of such simulations. We evaluate five prompt-level mechanisms using separate monitoring and intervention pipelines. Across 1,200 28-turn conversations spanning four LLMs and two ADHD persona intensities, we varied when to intervene (static vs. adaptive) and what to inject (reinjection vs. reflective reminder), plus a novel adaptive condition in which a monitor generates behavior-specific instructions. Relative to no intervention, reinjection reduced the modeled rate of LLM-rated drift by 35--38\%, reflective reminders by 22--27\%, and behavior-specific instruction by 87\%. None eliminated drift. We found no evidence that adaptive timing outperformed static scheduling. Monitoring therefore appears more useful for deciding \textit{what} to cor

---

### [15] What Users Cannot See: Evaluating LLM Emotional Support Beyond User Preference

**链接**: https://arxiv.org/abs/2605.21569
**作者**: Vivienne Bihe Chi, Adithya V Ganesan, Ryan L Boyd, Lyle Ungar, Sharath Chandra Guntuku
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] Goal-driven Variant Categorization

**链接**: https://arxiv.org/abs/2609.22475
**作者**: Daniel Calegari and Daniel Amyot
**来源**: cs.AI cs.DB cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Process discovery rarely yields a single coherent process structure. For analysis, a common step is to cluster process variants based on structural similarity and then assign business meaning to the resulting groups. Since these partitions are not derived from the organization's goals, analysts must manually interpret and consolidate variants into business-meaningful categories. This judgment-intensive step becomes increasingly difficult as the number and complexity of variants grow. In this paper, we propose a goal-driven approach to variant categorization that reverses this workflow. We first author an organization's goal model that predefines the categorization axis. Each variant is transformed into a textual narrative describing its behavior, and a Large Language Model (LLM) interprets it in the context of the goal model and assigns the variant to the most appropriate category. LLM-based semantic reasoning connects low-level process behavior with analyst-defined business goals. We 

---

### [17] Sample Count Is Not Enough: Candidate-Generation Strategy Shapes the Energy and Performance of LLM Test-Time Scaling

**链接**: https://arxiv.org/abs/2609.19499
**作者**: Mobina Kashaniyan and Ali Jannesari
**来源**: cs.LG cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] MemCalib: Benchmarking and Optimizing Memory Use in LLM Agents

**链接**: https://arxiv.org/abs/2609.24259
**作者**: Ruike Cao, Fanyu Zhao, Fugen Yao, Liang Dong, Jian Xu, Guanjun Jiang 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The effectiveness of agent memory ultimately depends on whether the underlying LLM gives each memory in context an appropriate degree of influence over its response. Yet this capability has remained largely overlooked. To assess this capability, we introduce MemCalib, a benchmark grounded in realistic memory-system scenarios for evaluating memory use and advancing optimization algorithms. Results on the MemCalib test set reveal that frontier open- and closed-source models struggle to use memory appropriately. They frequently over-use or under-use memory rather than matching each proposition's actual use to its target level, leading to biased, low-quality responses. Experiments with common post-training algorithms, including group relative policy optimization and on-policy self-distillation, further reveal a clear directional skew: trained models improve in one direction while deteriorating in the other. We therefore propose MemCalib-RL, an ordered bidirectional counterfactual credit-as

---

### [19] Observational Equivalence of LLM and Human Annotation

**链接**: https://arxiv.org/abs/2609.22133
**作者**: Kentaro Nakamura, Jing Ling Tan, and George Yean
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we show that LLM and human coding are observationally equivalent in terms of annotation quality: recent LLMs agree with expert coders at rates comparable to those observed among experts themselves. We demonstrate this through replications of text-classification tasks from 14 peer-reviewed political science studies, in which ten LLMs, three human experts, and 165 crowdsourced workers independently classify the same texts using identical codebooks. We find that this equivalence is driven by ambiguity in the texts and coding rules. When LLMs disagree with experts, experts are also more likely to disagree with one another, and clarifying coding rules reduces disagreement among both experts and sufficiently capable LLMs. Thus, there is little empirical basis for preferring human coding on the basis of annotation quality alone, while LLMs offer substantial advantages in speed and cost. We therefore argue that the central challenge of text annotation is no longer choosing betwe

---

### [20] Toollery: Scaling LLM Agents to Thousands of Skills and Tools

**链接**: https://arxiv.org/abs/2609.22218
**作者**: Xiangxi Tian, Ran Guan
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents are exposed to hundreds to tens of thousands of skills, tools, and API functions, full-library prompting becomes costly, slow, and less reliable: each added candidate increases prompt tokens and latency, while longer candidate lists introduce more distractors for LLM selection. We present \textbf{Toollery}, a training-free candidate-compression framework for scalable LLM skill/tool selection. Following established document-side query expansion, Toollery generates user-intent queries from each skill/tool specification and builds a retrieval index that maps real user requests to compact candidate sets before final LLM decision-making. By treating high-level skills and atomic tools as selectable capabilities, Toollery can be applied to both skill libraries and tool registries. We evaluate Toollery on the roughly 79K-capability SkillRouter benchmark, BFCL-V4 with over 440 atomic tools, and 3,396 proprietary smart-cockpit requests over 220 tools. Across these settings, Tooller

---

### [21] Toward Personalized Sleep Guidance from Wearable Data Using Language Models

**链接**: https://arxiv.org/abs/2609.22463
**作者**: Yusheng Tan, Running Zhao, Sofia Angel, Ninghui Hao, Ash Arian, Nikita N. Dulin 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sleep monitoring using wearable data has shown promise for personal health, yet large language model (LLM)-based summarization and question answering remain insufficient for personalized sleep guidance. Training specialized models, however, often requires costly expert annotation. Moreover, privacy and accessibility concerns motivate lightweight, local deployment for end users. We present a two-stage framework to address these challenges. Specifically, in Stage~1, a multi-agent LLM pipeline reasons structured sleep guidance from unannotated wearable records, enabling scalable dataset construction. Stage~2 distills guidance reasoning trajectories into small language models (SLMs) through supervised fine-tuning and integrates a training-free Best-of-$N$ selection strategy to enhance inference. Experimental results demonstrate our method outperforms commercial general and medical LLMs and open-source models. Human evaluation further supports the quality of the generated guidance and the f

---

### [22] Defusing Explosive Prompts: Understanding and Preventing Trigger-Based Prompt Injections in LLM Agents

**链接**: https://arxiv.org/abs/2609.22510
**作者**: Justin Szczepaniak, Elad Feldman, Naum Viner, Ben Nassi
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM applications integrate with external tools, they are increasingly exposed to indirect prompt injection (IPI), where adversarial instructions are embedded in retrieved content. Conventional IPIs fire on contact: the moment an agent ingests the content, it carries out the instruction. We introduce the explosive prompt, a conditional payload that stays dormant until an attacker-chosen trigger is met, in effect a training-free, inference-time backdoor planted in a single piece of retrieved content. This temporal separation reaches where ordinary IPI cannot. On frontier models that refuse the bare imperative almost entirely, rephrasing the same goal as a dormant conditional drives real, state-changing tool execution against a live agent backend (a paired mean of 16.5% vs. 2.4% for the imperative, reaching 34.2% on a proprietary model). In trials on nine production agents (OpenAI Codex, Google Gemini CLI, Anthropic Claude Code CLI, Cursor CLI, GitHub Copilot, Devin AI CLI, Amazon Kiro

---

### [23] The Corroboration Illusion: When More News Makes LLM Forecasts Less True

**链接**: https://arxiv.org/abs/2609.22246
**作者**: Yuan Lu and Yukuan Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to forecast real-world events by retrieving and reasoning over news. We show that this dependence on an open, crawlable news corpus creates a new attack surface: an adversary who can merely publish articles--without access to the retriever, the model, or the user's queries--can systematically move the forecaster's output probabilities. We formalize news-corpus poisoning of probabilistic forecasters, a threat model distinct from prior RAG poisoning, which targets factual answers or opinion polarity rather than calibrated probabilities. We evaluate the attack on 500 resolved ForecastBench questions against a 17.4M-article Common Crawl News corpus with a strict crawl-date cutoff, using three retrieval-augmented forecasters built on open 7-8B models. A single LLM-written article per question flips 56% of forecasts across the 0.5 boundary; five articles flip 69-73% and shift probabilities by +0.13 to +0.22 net of a neutral-article placebo, 

---

### [24] D-TAIA: Domain-Aware LLM Adaptation for Multi-Task Predictive Process Monitoring

**链接**: https://arxiv.org/abs/2608.28236
**作者**: Sjoerd van Straten, Christine Jacob, Marwan Hassani
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] Recidivism Prediction, Peer Effect Estimation, and Prediction-Powered Inference with LLM Text Measures

**链接**: https://arxiv.org/abs/2509.20634
**作者**: Shanjukta Nath, Jiwon Hong, Jae Ho Chang, Keith Warren, Subhadeep Paul
**来源**: econ.EM cs.AI econ.GN q-fin.EC stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Reasoning Topology Matters: A Controlled Study of LLM-Based Cybersecurity Analysis

**链接**: https://arxiv.org/abs/2609.24710
**作者**: Jiling Zhou, Aisvarya Adeseye, Antti Hakkala, Seppo Virtanen, Jouni Isoaho
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used in cybersecurity, where accurate analysis often requires multi-step and context-dependent reasoning over complex and heterogeneous data. However, existing prompting approaches typically focus on eliciting reasoning without explicitly considering how intermediate reasoning steps are structurally organized. We introduce Security Reasoning Topology, which models reasoning through three representative structures: Linear, Branching, and Graph. To evaluate their effects, we conduct controlled experiments on three cybersecurity datasets covering MITRE ATT&CK network traffic, cyber threat intelligence (CTI), and CVE vulnerability analysis. We evaluate multiple LLMs, including Llama 2 (7B, 13B, 70B), GPT-5.1, and Mistral Large 3, while keeping task inputs consistent and controlling reasoning structure through system-level prompting. Results show that reasoning topology substantially affects performance: Graph reasoning achieves the highest over

---

### [27] OptiSkill: A Hierarchical and Evolving SkillBank for LLM-Based Optimization Modeling

**链接**: https://arxiv.org/abs/2609.22987
**作者**: Ruiqing Zhao, Rui Liu, Yuan Zuo, Huarong Zhang, Xiao Han and Junjie Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated operations research (OR) modeling requires LLMs to translate natural-language decision problems into correct mathematical programs. Existing methods can improve individual formulations, but they often solve problems in isolation, retaining little reusable experience and repeating similar formulation errors. Prior memory-based approaches store examples, thoughts, or insights as references, while OR modeling requires reusable formulation skills that transfer across problem narratives and guide concrete modeling decisions. We propose OptiSkill, a skill-augmented framework that builds a hierarchical and evolving SkillBank for LLM-based OR modeling. SkillBank stores solver-verified experience as reusable skills, with Global Strategies for problem-level formulation skeletons and Step Experiences for local error-prevention rules. It is further refined through stable batch-level test-time evolution, where candidate skills are incorporated only after validation. Experiments on eight O

---

### [28] Explainable Recommendations at Scale: LLM Rationales for YouTube Music Artist Discovery

**链接**: https://arxiv.org/abs/2609.23877
**作者**: Xiao Liu, Yanwei Song, Srivaths Ranganathan, Yuan Chen, Zheyun Feng, Parker Steenburgh 等 (10 人)
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern music streaming platforms face a persistent tradeoff: exploiting familiar content versus driving the exploration of novel items. While users frequently desire discovery, they hesitate to select unknown artists over proven favorites. Providing transparent, natural language rationales that explain why an unexplored item is recommended lowers this barrier. However, while Large Language Models (LLMs) excel at this nuanced explainability, their real-time deployment is severely bottlenecked by prohibitive inference costs and computational overhead. In this paper, we present an industry case study of a decoupled recommendation architecture that successfully scales exploration without compromising latency. Our system isolates LLM inference asynchronously offline, pre-computing personalized candidate pools of undiscovered artists alongside tailored rationales. Large-scale online A/B experiments validate our design. We demonstrate that combining LLM-backed recommendations with these expla

---

### [29] Do Chess Explanations Reflect Model Decisions? Behavioral and Token-Level Tests of LLM Reasoning Faithfulness

**链接**: https://arxiv.org/abs/2609.22245
**作者**: Angelina Parfenova
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can produce fluent explanations for chess moves, but plausible language does not necessarily reflect the reasoning behind a decision. We study this question in chess, where the board state is fully observable, legal actions can be enumerated, and move quality can be evaluated independently. Across 200 Lichess endgame puzzles, we test explanations using move recoverability, decoder-side controls, and token-level scoring of legal candidate moves. Unmasked explanations make generated moves easy to recover, but this advantage drops sharply after explicit move hints are removed. Under strict masking, explanations provide only small and decoder-dependent gains over the board state alone. Token-level scoring shows that explanations can nevertheless alter move preferences: random but plausible explanations from other puzzles reduce the probability of the correct move, indicating that irrelevant reasoning text is not simply ignored. We also find that recognizable endgame m

---

### [30] LIGE-GR: A Smooth Leap from Ranking to Generative Recommendation in the LLM Era

**链接**: https://arxiv.org/abs/2609.18148
**作者**: Venkat Srinivas, Chenzhang He, Sam Woodmansee, Shawn Lian, Wenjie Hu, Renjie Jiang 等 (10 人)
**来源**: cs.LG cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] BAIT: Boundary-Guided Disclosure Escalation LLM Jailbreaking via Self-Conditioned Reasoning

**链接**: https://arxiv.org/abs/2605.27110
**作者**: Xuan Luo, Yue Wang, Geng Tu, Jing Li, Ruifeng Xu
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Efficient LLM Distillation for Bangladesh Legal Context: A Smartphone-Compatible Retrieval-Augmented Generation Model

**链接**: https://arxiv.org/abs/2609.24177
**作者**: MD. Nafis Kamal, Mahadi Hasan Fahim, Talha Ridwan, Nadifa Zaman, Fariha Roushon Florin, Farig Yousuf Sadeque 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Legal information in Bangladesh is inaccessible to most citizens. Statutory text is English-only, trained lawyers are concentrated in urban centres, and cloud-dependent AI fails where mobile connectivity is unreliable, a setting in which hallucinated legal text causes direct harm. The system addresses statutory interpretation only; queries that require judicial precedent or case-law reasoning fall outside its scope. We target the statutory access gap by compressing a 9-billion-parameter Gemma-2 teacher into a 2-billion-parameter student through two-phase progressive knowledge distillation. Phase 1 performs supervised fine-tuning on 9,429 quality-gated legal question-answer pairs (65% acceptance from 14,514 generated queries); Phase 2 minimises sparse Kullback-Leibler divergence against the teacher's top-50 per-token logits at temperature tau = 4.0, implemented via QLoRA (4-bit NF4, rank-32 LoRA adapters). Prior legal language models target general legal English; this system specialises

---

### [33] An Unexpected Robot Policy: Early Evaluations of GPT-6 Astra on RoboDojo and Beyond

**链接**: https://arxiv.org/abs/2609.24170
**作者**: Wenbo Zhang, Kaixuan Wang, Yutao Ouyang, Xiaoyu Huang, Liyang Li, Kailun Su 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embodied AI systems are often organized into System 1 and System 2. System 1 is typically a pretrained policy that generates actions at high frequency, whereas System 2 is often instantiated as a vision-enabled language model for high-level planning. We ask whether a large language model (LLM) can act as the policy for robot manipulation without task-specific finetuning. We call this setting LLM as policy. We evaluate three LLMs on all 42 RoboDojo tasks and compare their scores with 40 public policies. Astra and GPT-5.5 use the official 50-episode-per-task protocol; DeepSeek-Flash uses 10 episodes per task. GPT-6 Astra achieves 22.48% average success rate and 28.97 Score over 2,100 trials, ranking above every public entry. Yet GPT-5.5 and DeepSeek-Flash reach only 0.88% and 1.92% average success rate with the same post-processing. We find that Astra exhibits a sharply polarized capability profile. It generalizes well to tasks that require semantic understanding but not high-precision c

---

### [34] Listen Then Reason: Perception-Grounded Test-Time Reinforcement Learning for Large Audio-Language Models

**链接**: https://arxiv.org/abs/2609.23589
**作者**: Jiaheng Dong, Xiaofeng Yu, Jean Honorio, Abhirup Ghosh, Hong Jia, Ting Dang
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large audio-language models (LALMs) are increasingly used for a broader range of audio reasoning tasks. These models typically incorporate audio representations into a large language model (LLM) backbone to enable multimodal reasoning. Recent test-time reinforcement learning (TTRL) methods further improve LLM reasoning capability by leveraging unlabelled test data after pre-training. However, the importance of the perceptual capability of LALMs remains underexplored, particularly how much acoustic evidence is integrated and relied upon during reasoning, and how this contributes to final task performance. This gap limits the development of effective post-training methods like TTRL for audio reasoning. In this work, we first analyse how audio information is integrated and utilised during reasoning process. We quantify layer-wise perceptual reliance and show that stronger acoustic reliance is associated with higher accuracy and a larger performance gain attributable to the audio input. Bu

---

### [35] From Semantic Decisions to Feasible Trajectories: Self-Evolving LLM-Guided Optimal Control for Narrow-Space Parking

**链接**: https://arxiv.org/abs/2609.24631
**作者**: Zhengbao Yao, Yuanfu Luo, Kehan Xue
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous parking in nonconvex and narrow environments remains challenging. Although optimal-control methods can explicitly enforce vehicle dynamics and collision constraints, nonconvexity compromises solver robustness and can cause failures. Large language models (LLMs) exhibit strong semantic reasoning capabilities, but directly generating dense trajectories makes it difficult to guarantee physical feasibility. We introduce SE-LLM-OCP, a unified framework in which LLMs make high-level discrete maneuver decisions, while an optimal-control module enforces low-level vehicle dynamics and collision constraints. Online, the LLM proposes sparse maneuver plans, decomposing the parking task into a sequence of short-horizon trajectory-optimization problems. A low-level solver then sequentially solves optimal-control problems. If the solver fails, the LLM aggregates failure evidence from the solver and validation stages to guide replanning. Offline, SE-LLM-OCP automatically evolves a structure

---

### [36] Do LLMs Choose Like Humans? Using Cognitive Theory to Evaluate LLM Decision-Making

**链接**: https://arxiv.org/abs/2609.22225
**作者**: Johnathan Sun, Andrei Shleifer, Yonatan Belinkov
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) exhibit a range of human-like decision-making behaviors, but whether these reflect similar underlying mechanisms or surface-level mimicry remains unclear. We evaluate whether LLM context sensitivity aligns with a cognitive economic theory that explains human behavior through problem categorization and attention allocation. Across 12 open-source and commercial LLMs on a novel 140,000-trial product choice benchmark, context induces human-like shifts in choice and problem categorization, but does not reliably reweight attention between features like price and quality. Neither scale nor chain-of-thought reasoning reliably attenuates context sensitivity or generates human-like behavior. These results suggest that LLM decision mechanisms are distinct from human ones.

---

### [37] gwBenchmarks: Stress-Testing LLM Agents on High-Precision Gravitational Wave Astronomy

**链接**: https://arxiv.org/abs/2605.11269
**作者**: Tousif Islam, Digvijay Wadekar, Zihan Zhou
**来源**: gr-qc astro-ph.HE astro-ph.IM cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] From UNDRR Reports to Event Records: Schema-Constrained LLM Extraction of Georeferenced Disasters

**链接**: https://arxiv.org/abs/2609.23853
**作者**: Camilla Andreozzi, Phuong-Anh Nguyen-Le, Zhijing Jin and Revati Mani
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Disaster-risk-reduction archives describe hazard events in prose that databases such as EM-DAT (Delforge et al., 2025) cannot ingest directly. We present an LLM pipeline that generates candidate georeferenced event records using a controlled hazard vocabulary and fixed schema, retaining evidence for review. Applied to 10,000 documents from PreventionWeb, the knowledge hub managed by UNDRR, it produced 3,572 records from 1,913 documents across 24 hazard types and resolved 81% of location mentions to OpenStreetMap geometries. On 171 human-positive document windows from a stratified 217-document reference set, GPT-5 achieved 86.0% pooled attribute $F_1$, versus 44.2% for the spaCy-gazetteer baseline. Evaluation pools hazard families, location strings, and event years within documents, without assessing their assignment to individual events. GPT-5.4 ranked highest among ten LLMs (86.6% $F_1$). Verbatim evidence occurrence was 72.0% for GPT-5 and 47.2% for GPT-5.4, measuring textual traceab

---

### [39] RPMem: Learning Long-Term Recurrent Parametric Memory Across Sessions for LLM Agents

**链接**: https://arxiv.org/abs/2609.23466
**作者**: Fanyu Zhao, Ruike Cao, Liang Dong, Fugen Yao, Jian Xu, Guanjun Jiang 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents require memory that persists and evolves across sessions. Text-based memory retrieves and reconstructs past interactions at every query, making long-horizon performance increasingly dependent on retrieval quality and contextual reasoning as histories grow. Parametric memory encodes experience directly into model computation, but existing approaches provide limited support for cross-session memory evolution. Their coupling to a specific backbone further restricts memory reuse after model replacement. We introduce RPMem, a two-stage architecture that compiles each session into a model-independent latent memory through forward computation and selectively integrates it with retained memory via a task-trained recurrent gate. The consolidated memory is then mapped to backbone-specific low-rank adaptation (LoRA) parameters, allowing the encoding capability to transfer when the backbone is replaced. Evaluation across three long-term memory benchmarks and five diverse ba

---

### [40] HaikuS2S: A Cascaded System For Responding In Verse

**链接**: https://arxiv.org/abs/2609.23951
**作者**: Devangi Sharma, Sophia Judicke, Glenda Tan, Conrad Schaumburg, Shinji Watanabe
**来源**: cs.CL cs.AI cs.SD
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Expressive speech synthesis has advanced through prosody modeling, yet generating structured poetic speech, such as haiku, remains challenging. Prior work on prosody transfer improves expressiveness, and fine-tuned poetry TTS (text-to-speech) systems capture verse intonation. However, these models do not model haiku's 5-7-5 syllable structure or line-ending pauses. We present a cascaded system, HaikuS2S, combining ASR (automatic speech recognition), LLM (large language model)-generated haiku, and TTS fine-tuning on both prose and custom haiku datasets. Our evaluation focuses on emotion similarity, speech quality, and prosody alignment. In our experiments, we see that our prosody and tonal alignment improve significantly with our fine-tuned systems, particularly the one trained on both general poetry and haiku. We also see that we maintain similar emotion similarity scores across all systems.

---

### [41] Dissecting Agentic Forensics: The Role of Triage, Prompting, and Evidence Arbitration in Open-World Fake Image Detection

**链接**: https://arxiv.org/abs/2609.24359
**作者**: Xianlong Li (2), Pietro Bongini (1), Niccol\'o Pancino (1), Marco Blanchini (2), Benedetta Tondi (1), Mauro Barni (1) ((1) University of Siena 等 (9 人)
**来源**: cs.CV cs.AI cs.CR
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image forensics is increasingly an open-world problem: manipulations range from fully synthetic images to localized edits, splicing and swapping, while most forensic detectors remain specialized to a single manipulation family. Agentic AI has recently emerged as a promising solution. In principle, such systems can assess the reliability of individual detectors, identify out-of-scope evidence, and arbitrate conflicting reports. However, it remains unclear which components actually drive performance and whether their benefits persist under distribution shift. To answer these questions, we study a training-free agentic framework built around specialist detectors, per-detector triage, and conflict-aware evidence arbitration. Using six configurations and three multimodal large language model backbones, we dissect the role of triage, prompting, and reasoning quality on both in-distribution and out-of-distribution data. Our results show that naive detector fusion suffers from severe false-pos

---

### [42] English is Not All You Need: Systematically Exploring the Role of Multilinguality in LLM Post-Training

**链接**: https://arxiv.org/abs/2604.13286
**作者**: Mehak Dhaliwal, Shashwat Chaurasia, Yao Qin, Dezhi Hong, Thomas Butler
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] A Task-Oriented Multi-Agent Framework for Complex Wearable Health Analysis

**链接**: https://arxiv.org/abs/2609.24107
**作者**: Kunpeng Yang
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wearable health questions often combine data retrieval, longitudinal analysis, and health advice over structured records. Prompting a single large language model with a complete record and a composite query obscures whether every request is executed and which evidence supports the answer. We propose a task-oriented multi-agent framework that represents a composite query as distinct intents and typed tasks with explicit intra-intent dependencies. Specialized agents execute retrieval, analysis, and advice tasks; isolated intent states preserve request boundaries and evidence relationships before aggregation. We evaluate the framework on a synthetic dataset of $10{,}000$ virtual users with one month of longitudinal wearable records, covering structured data retrieval, multi-intent recognition, and overall response quality. Across $1{,}500$ retrieval questions, the Query Agent achieves $98.3\%$ accuracy, compared with $97.9\%$ for the Direct LLM baseline, while reducing average query-stage

---

### [44] APEXA: Execution-Integrity Enforcement for Multi-Agent LLM Automation of Synchrotron Data Reduction

**链接**: https://arxiv.org/abs/2609.24165
**作者**: Pawan K. Tripathi, Hemant Sharma, Andrew Chuang, Mathew J. Cherukara
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synchrotron data reduction, detector calibration followed by azimuthal integration of terabyte-scale diffraction series, is a multi-step, expert-bound bottleneck that increasingly limits the science rate of user facilities. LLM agents promise to collapse it, but driving a real pipeline with a stochastic model creates a failure mode chat benchmarks cannot see: an agent can report a calibration that was never computed. Correctness here is a property of what executed, not of the transcript. We present APEXA, a deployed multi-agent framework (61 tools over heterogeneous compute, run as a single reasoning loop) automating calibration and integration from natural language at a major light source. We make three contributions. First, execution-integrity enforcement: a deterministic tool-layer guard that refuses to surface any result not backed by an executed tool call, with a parser tolerant of cross-model tool-call format drift: in deployment, a frontier model fabricated a complete calibratio

---

### [45] From Certain Doom to Survival: Agent-Driven Self-Governance in LLM Agent Societies

**链接**: https://arxiv.org/abs/2609.22600
**作者**: Gregory B. Rehm
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are increasingly evaluated in social dilemmas, but most work treats governance as imposed by the experimenter, expressed rhetorically, or restricted to a fixed menu of mechanisms. We introduce GovSim-SelfGovern, an extension of the GovSim common-pool resource environment in which agents author executable Python governance rules, receive sandbox validation feedback, vote on proposed laws, and live under the rules they enact across rounds. To evaluate agent-driven self-governance, we examine three scenarios ranging from stable abundance to a fatal resource wall where five agents cannot all survive through harvest alone. To solve this, agents must write and debug useful laws in time before their institutions degrade sharply under resource pressure. Finally, we study a central alignment question: when agents hesitate to propose exile, are they rejecting it for normative reasons, or does it never enter their candidate set? Our results show that executable governance 

---

### [46] Knowing, and Saying It Only When Asked: LLM Endognostics and the Schizognosis of Minerva-7B

**链接**: https://arxiv.org/abs/2609.22219
**作者**: Fabrizio Davide and Francesco Collova
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating an aligned language model by reading its answers assumes the answers carry the distinction the evaluator cares about. We introduce LLM endognostics, a white-box internal auditing framework designed to extract and causally manipulate latent knowledge within the residual stream. Applied to Minerva-7B-Instruct-v1.0 on 124 minimal prompt pairs over 12 categories of professional risk, behavioral evaluation fails on most of the set: the model acts identically on 63.7% of the pairs (95% CI [55.0%, 71.6%]), complying with or refusing both members. Yet, projecting the residual stream onto the vocabulary by a Jacobian lens reveals a statistically significant Contrastive Endognostic Margin, proving the model maintains robust risk differentiation internally. In a second protocol crossing 25 facts with five linguistic framings, we show that the model conforms to presupposed falsehoods in 72% of cases, despite representing the true entity in its latent layers. Surgically ablating the dire

---

### [47] RedKnot: Efficient Long-Context LLM Serving with Head-Aware KV Reuse and SegPagedAttention

**链接**: https://arxiv.org/abs/2606.06256
**作者**: Yang Liu, Zhaokai Luo, Huayi Jin, Zhiyong Wang, Ruozhou He, Boyu Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Token Utility Is Selection-Conditioned: Coupled Selection of Prompt Context and Response Supervision for Efficient Instruction Tuning

**链接**: https://arxiv.org/abs/2609.22943
**作者**: Can Wu, Xinrui Chen, Ou Wu, Yi Du
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient large language model (LLM) instruction tuning requires selecting response supervision with supporting prompt context. Existing methods typically value both sides separately, risking selection-state mismatch between valuation and retained training subsets. BRIDGE (Budgeted Response-Prompt Interaction via Directional Gradient-guided Efficient Token Selection) captures selection-conditioned token utility through a shared validation-directed interaction surrogate valuing each side under the other's retained state. Budgeted alternating selection coordinates retained subsets by aggregating precomputed interactions over the current opposite-side subset to update conditional scores. Structure-aware projection converts conditional response scores into coherent supervision spans. Across three model families, BRIDGE leads compared selection methods overall in mathematical reasoning, code generation, and instruction following. In mathematical reasoning, its advantage over independent sel

---

### [49] Enhancing the Non-Functional Quality Compliance of LLM-Generated Code through Quality-Aware Preference Learning

**链接**: https://arxiv.org/abs/2503.09020
**作者**: Liang Lu, Yuan Jiang and Christoph Treude
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] DUMA-Bench: A Dual-Control Multi-Agent Benchmark for Evaluating LLM Agent Security

**链接**: https://arxiv.org/abs/2609.24662
**作者**: Ivan Aleksandrov, German Kochnev, Sabrina Sadiekh, Yaroslav Rogoza
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly operate in environments where they interact with users, tools, and external systems. Yet most security evaluations assume passive users and static control, ignoring the interactive dynamics that shape real agent behavior. We introduce \textbf{DUMA-Bench}, a benchmark and evaluation protocol for measuring agent security under \emph{dual-control} interaction, where both the agent and the user can influence the shared environment state. DUMA-Bench extends $\tau^2$-bench ~\cite{barres2025tau} with adversarial environments covering eight vulnerability classes, including RAG poisoning, cross-agent manipulation, and unsafe output handling. We evaluate \textbf{14 models from five model families} (OpenAI, Anthropic, DeepSeek, Qwen, and Z.ai) across eight domains and multiple user-behavior regimes. Across our experiments, introducing dual-control interaction increases the attack success rate from \textbf{26.9\%} to \textbf{41.1\%}. These results show that agent secu

---

### [51] FLARE: A Full-Lifecycle Dense Supervision Paradigm for Long-Horizon Coding Agents via Generative Reward Model

**链接**: https://arxiv.org/abs/2609.23808
**作者**: Jingxuan Xu, Gang Wu, Yanan Wu, Yutao Mou, Songwei Yu, Tianzhuang He 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While test-time scaling enhances Large Language Model (LLM) agents in long-horizon software engineering (SWE), sparse binary rewards (Pass/Fail) create a severe credit assignment crisis and waste failed exploratory trajectories. Current trajectory optimization and scaling methods are costly and structurally limited, relying on heuristic state reuse without causal diagnosis or delayed scalar scoring without actionable online guidance. We propose FLARE (Full-Lifecycle Alignment and Reward Engine), a novel dense supervision paradigm driven by a lightweight Generative Reward Model (GRM). First, RADAR, an offline causal-aware diagnostic framework, extracts high-fidelity, hindsight-free supervision through causal-chain backtracking to distill a GRM providing real-time, step-level risk feedback. Second, FLARE uses this GRM to continuously optimize the agent across its entire lifecycle. During inference, FLARE acts as an Active Scaffold, autonomously intercepting high-risk generation steps for

---

### [52] A Governance-Aware Large Language Model Orchestrated Agentic Digital Twin for Transmission System Operator Control Room Decision Support

**链接**: https://arxiv.org/abs/2609.22476
**作者**: Costas Mylonas, Magda Foti, Emmanouel Varvarigos
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transmission system operators face rising complexity from renewable integration, reduced inertia, and tighter security margins. Large language models offer natural-language decision support, but their hallucinations, uncontrolled tool use, and weak traceability conflict with control room requirements. This paper presents a governance-aware agentic digital twin for transmission grid control rooms. The large language model only selects and parameterizes whitelisted analysis tools, and every proposed action passes through a governance layer that the model cannot bypass. The layer enforces four rules on every run. Only whitelisted tools execute. No run exceeds its step budget. No action with side effects executes without explicit operator approval. Every number in an answer is rendered by the layer from backend results with its unit, variable, and time. The rules are checked on a persistent audit trail for every run of a released 118-task benchmark, which covers analytics, simulation, mult

---

### [53] Splitting Documents at Lower Cost: Multi-Split Boundary Decisions for LLM-Based Page Stream Segmentation

**链接**: https://arxiv.org/abs/2609.22620
**作者**: Nikhil Reddy Pottanigari, Sepideh Kharaghani, Saverio Vadacchino, Alejandro Posada, Ying Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scanned mail, uploaded PDFs, and consolidated attachments often arrive as page streams that must be split into individual documents before downstream classification, extraction, or routing. Zero-shot large language models can detect document boundaries without task-specific training, but standard Page Classification (PC) and Boundary Decision (BD) formulations resolve only one boundary per model call. We introduce Multi-Split Boundary Decision (MSBD), which predicts multiple boundaries within a page window in a single call, reducing the number of inference requests. We evaluate MSBD across multiple language models, document collections, input modalities, and window sizes. The results reveal a model- and corpus-dependent operating range in which MSBD preserves strong segmentation accuracy while substantially improving inference efficiency, followed by a sharp decline at larger windows. MSBD provided the strongest overall accuracy--efficiency trade-off, while large windows expose distinc

---

### [54] PTCG-Bench: Can LLM Agents Master Pok\'emon Trading Card Game?

**链接**: https://arxiv.org/abs/2605.29653
**作者**: Dongdong Hua, Yifei Sun, Renhong Huang, Feng Gao, Chunping Wang, Yang Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Per-Query Gating of LLM Rerankers for Multi-Hop Retrieval

**链接**: https://arxiv.org/abs/2609.22880
**作者**: Andre Bacellar
**来源**: cs.IR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM rerankers add of the order of \$0.2-0.3 per 1,000 queries and about a second of tail latency on top of a graph-augmented dense pipeline such as HippoRAG2, and on three multi-hop benchmarks they improve final-hop top-K coverage on seven of nine (dataset, K) cells, by up to +34.8 pp. We ask whether a learned per-query gate can skip the reranker where it will not help, using only features available before the LLM call (27 score and lexical statistics of the two retrieval lists plus a PCA of a small query embedding) with an executable fallback. Every choice, including the fallback and the threshold, is made inside the training fold and applied once to held-out queries, and harmful skips (the rerank would have found the target, the fallback did not) are reported next to the aggregate coverage. Across nine cells on 2WikiMultiHopQA, MuSiQue and HotpotQA the gate skips 51% of calls at an average held-out LastHop@K cost of 1.2 pp; four cells meet a pre-registered 1 pp rule, harmful skips oc

---

### [56] You Frame It: How Conceptual Representations Shape LLM Detection and Reasoning about Antisemitism

**链接**: https://arxiv.org/abs/2607.04945
**作者**: Katharina Soemer and Helena Mihaljevi\'c
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] Replayable Financial Agents: A Determinism-Faithfulness Assurance Harness for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2601.15322
**作者**: Raffi Khatchadourian
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] ReLay: Personalized LLM-Generated Plain-Language Summaries for Better Understanding, but at What Cost?

**链接**: https://arxiv.org/abs/2605.00468
**作者**: Joey Chan, Yikun Han, Jingyuan Chen, Samuel Fang, Lauren D. Gryboski, Alexandra Lee 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Enforcing Narrative Reliability and Epistemic Pacing in LLM-Driven Detective Games via Structured Knowledge Trees

**链接**: https://arxiv.org/abs/2609.23043
**作者**: Parsa Rahmati, Richard Zhao
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) enable open-ended dialogue in interactive games, but their non-deterministic outputs make it difficult to preserve authorial control, factual consistency, and the intended sequence of information disclosure. These challenges are particularly significant in detective games, where premature revelation or fabricated details can undermine the logic of player progression. We present a Structured Knowledge Tree architecture coupled with a tri-agent LLM pipeline for controlling dialogue in an open-ended interrogation game. The system separates knowledge retrieval, dialogue generation, and response verification to ensure that the virtual suspect reveals only information permitted by the current narrative state. We evaluate the approach through The Interrogation of Adrian Gale, a playable detective-game testbed, and a formal user study examining hallucination reduction, adherence to authored disclosure sequences, and perceived logical progression. Our results demons

---

### [60] RoofLang: Enabling AI-Driven Architecting of LLM Inference Systems

**链接**: https://arxiv.org/abs/2609.12551
**作者**: Ziyue Yang, Yuting Jiang, Lei Qu, Peng Cheng
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] The Metanym Game: An LLM Benchmark Without Ground Truth That Rises With the Models It Measures

**链接**: https://arxiv.org/abs/2606.21008
**作者**: David Nordfors
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Correct Diagnosis, Better Feedback: A Symbolic-Verifier for Faithful LLM Tutoring Feedback in Logic Proofs

**链接**: https://arxiv.org/abs/2609.22553
**作者**: Tahreem Yasir, Arnav Mody, Xioayi Tian, Tiffany Barnes
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective LLM tutoring depends on correctly identifying the specific error in a student's reasoning before generating feedback. We study this problem in propositional-logic proof tutoring, where student actions can be checked against formal inference rules. We introduce a verifier-grounded architecture that separates diagnosis from language generation. Using 600 balanced student actions, we compare a zero-shot LLM detector, a fine-tuned detector, and a symbolic verifier. Each diagnosis is processed by shared rationale and feedback agents, isolating the effect of the initial diagnosis. The zero-shot detector achieves a macro-F1 of 0.191; fine-tuning raises this to 0.709 but retains systematic errors between structurally related classes. Rationales generally preserve the diagnosis supplied to them, showing that an incorrect diagnosis can be faithfully propagated through the pipeline. Feedback can likewise remain faithful to its rationale, non-revealing, and pedagogically appropriate whil

---

### [63] Djinnlang: Higher-Level Programming by Unambiguous Specification with an LLM in the Compiler

**链接**: https://arxiv.org/abs/2609.23954
**作者**: Simon Henniger and Stephen Chong and Nada Amin
**来源**: cs.PL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programmers write formal specifications, and LLMs implement them, proving that each implementation matches its spec. Taken to its extreme, this makes specification languages the new programming languages. We argue that an unambiguity constraint is key: in addition to proving that its implementation satisfies the specification, the LLM must also prove that any other implementation satisfying it must produce the same outputs on the same inputs, i.e. that the relation formed by the constraints is deterministic. This leaves the LLM no leeway on program semantics: as with a conventional compiler, the generated code never needs to be read and can be regenerated from the spec at any time. Under this constraint and with a powerful LLM, the difference between a specification language and a programming language becomes essentially meaningless, and the LLM essentially becomes a part of the compiler toolchain. The arrangement doubles as a strong form of AI control: an untrusted model writes the co

---

### [64] FRAMES: Failure Recovery And Monitoring of Embodied Skills for Humanoid Loco-Manipulation

**链接**: https://arxiv.org/abs/2609.22538
**作者**: Ajay Vikram Periasami, Xinyuan Luo, Haoyu Li, Xianyi Cheng
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) planners can decompose natural-language instructions and select reusable robot skills, but choosing the correct skill does not guarantee successful physical execution. This gap is especially important in humanoid loco-manipulation, where errors during approach, grasping, transport, or placement can invalidate the remainder of a long-horizon plan. We present FRAMES, a failure-aware supervisory framework for the Unitree G1 humanoid that operates above the CEER whole-body controller. A Planner Agent selects subtasks through parameterized mid-level skills, while a vision-language-model-based Monitor Agent evaluates each skill using temporal multi-view observations and structured robot and contact evidence. Detected failures stop the active skill and provide grounded feedback to a Recovery Agent. The framework further includes a Memory Module for reusing prior skill experience, and geometric grounding via depth and segmentation. We independently evaluate the monit

---

### [65] LLM-based Conversational AI Knowledge Assistant for MyBuddy Humanoid Robot

**链接**: https://arxiv.org/abs/2609.24742
**作者**: Hanxiao Chen
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humanoid robots are increasingly being popular and developed for human-centered applications, yet their ability to provide intelligent conversations and natural interactive knowledge assistance remains constrained by traditional rule-based dialogue systems, pre-defined responses and limited knowledge repositories. Large language models (LLMs) have emerged as a powerful foundation for enabling natural, adaptive, and context-aware Human-Robot Interaction (HRI), which provides a significant opportunity to address such limitations by enabling robots to understand natural speech language, reason over complicated queries, maintain high-quality conversational context, and generate knowledge-rich responses. In this work, we originally present and implement an LLM-based versatile Conversational AI Knowledge Assistant for the Raspberry-Pi-powered 13-Axis MyBuddy humanoid robot, which integrates LLM-driven language understanding and AI reasoning with real-time speech recognition, knowledge retrie

---

### [66] Luck Is Not Skill: When Do Paired Rollouts Help Group-Relative RL of LLM Agents?

**链接**: https://arxiv.org/abs/2609.24144
**作者**: Nazmus Sakib
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group-relative reinforcement learning compares rollouts of the same prompt, but independent environment noise can obscure these comparisons. We study paired rollouts, which share an event-keyed noise schedule within each group while preserving each rollout's marginal distribution. Pairing removes the between-schedule component of reward-contrast variance, but need not reduce gradient variance. For one-sided grader noise, we derive an exact condition for reduction and give a counterexample in which reward contrasts improve while gradient variance increases. A controlled study trains a 2B tool-use agent under tool faults and grader flips, with three seeds per design. The protocol was registered with a disclosed, previously completed pilot. Under tool faults, pairing improves final noisy-test success by +5.1 percentage points on average, with all three seed differences positive, but misses the registered learning-curve criterion. The criterion is also missed under grader flips: the valida

---

### [67] Strategy Accumulation and Guided Execution for Automated LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2609.22257
**作者**: Haoran Zhao, Wei Du, Dingwen Yang, Jixuan Huang, Junlin Shang, Lingyong Fang 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Producing task-specific large language models requires discovering effective training strategies through experimentation. Automated fine-tuning systems have made this experimentation feasible with far less manual effort. However, these systems are stateless: each search discards its discovered strategies, dataset insights, and hyperparameter findings once it ends. Every new task must then repeat this costly search from a cold start. To address this, we propose Strategy Accumulation and Guided Execution (SAGE), a two-stage framework that makes automated fine-tuning search cumulative. In the first stage, a multi-agent pipeline performs Monte Carlo Tree Search-based exploration. A parallel Distillation Agent extracts task-specific exploration records and confidence-scored cross-task insights, which together constitute a structured experience repository. In the second stage, SAGE retrieves relevant experience from this repository and selects what applies to guide training on the new task. 

---

### [68] Augmented Hypothesis Testing with Persona-Based LLM Simulations

**链接**: https://arxiv.org/abs/2609.24629
**作者**: Ziyad Benomar, Aymen Al Marjani, Paul Missault, Saab Mansour
**来源**: cs.LG cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A/B testing requires large sample sizes, long timelines, and significant costs. When auxiliary predictions of experimental outcomes are available from machine learning models, uncertain prediction quality precludes replacing human experiments entirely, yet these predictions may still contain useful signal. We propose a principled framework for learning-augmented hypothesis testing that leverages predictions of unknown quality to reduce sample sizes while maintaining statistical validity. Predictions naturally vary in granularity, from coarse aggregate signals to fine-grained individual-level estimates, and our framework addresses both ends of this spectrum: (1) for population-level directional predictions, where only a binary signal on the treatment effect sign is available, we use an asymmetric test and prove consistency and robustness bounds within the learning-augmented algorithms paradigm; (2) for individual-level predictions, we introduce Generalized PPI++ (GPPI), extending Predic

---

### [69] Semantics Delivery Network: Rethinking Web Retrieval Infrastructure for LLM Agents

**链接**: https://arxiv.org/abs/2609.22486
**作者**: Peichun Hua and Yunming Xiao
**来源**: cs.NI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly rely on external sources when answering questions that require proprietary information or up-to-date live web content, through both traditional single-shot retrieval-augmented generation (RAG) and multi-turn agentic RAG. Yet today's web infrastructure is still built for human clients. Given a query, current search services return a list of URLs and snippets ranked for generic relevance; content delivery networks (CDNs) cache URL-addressed objects (texts, images, videos, etc.) without knowing which passage an agent needs. LLMs, in contrast, consume short, semantically coherent passages, hereafter "chunks", selected for downstream task utility rather than similarity alone, and may retrieve statefully across reasoning turns. Uncoordinated agents also repeat search, data acquisition, and semantic processing, duplicating work that could be shared. We argue that semantic chunk retrieval should become a first-class network-delivery abstraction. We pro

---

### [70] ParA-LLM: A Unified Approach to Paralinguistic and Acoustic Speech Understanding

**链接**: https://arxiv.org/abs/2609.22771
**作者**: Nishit Anand, Jiaqi Su, Ke Chen, Yunyun Wang, Dinesh Manocha, Ramani Duraiswami 等 (8 人)
**来源**: cs.SD cs.AI cs.LG eess.AS eess.SP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Audio LLMs have achieved human-level speech recognition, yet existing systems struggle to capture paralinguistic aspects such as speaker traits, expressive variations, and environmental acoustic conditions. To address this, we design a framework of 22 paralinguistic characteristics and create a dataset of over 1.2M Audio-QA pairs. We develop ParA-LLM, trained with a two-stage curriculum: first on single-attribute questions to build foundational knowledge, then on multi-attribute questions for joint reasoning over speaker and acoustic characteristics. We also release ParA-Bench, a benchmark of 6,000 multiple-choice questions across speaker-speech, acoustic, and mixed categories, where frontier models like GPT-4o-Audio achieve only 36% accuracy. ParA-LLM surpasses state-of-the-art Audio LLMs like GPT-4o-Audio by 7.5% on ParA-Bench, with additional gains of 1.13% on MMAU-Pro Speech and 7.49% on MMAR Speech.

---

### [71] GRRR: The Geometry of Reshaping, Rotation, and Routing in Decoder LLM post-training

**链接**: https://arxiv.org/abs/2609.22146
**作者**: Jianing Qi, Hao Tang, Zhigang Zhu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how post-training changes the weights of Large Language Models (LLMs) relative to their pretrained weights. Across 12 post-training chains with supervised fine-tuning (SFT) and reinforcement learning (RL), we express each weight update in the pretrained matrix's singular value decomposition (SVD) frame. This decomposition separates the changes of three geometrically distinct components: diagonal values, which reshapes singular values; off-diagonal values, which rotates the coupling between pretrained input and output directions; and null-space values, which routes outside the matrix's original nonzero SVD core. On a math evaluation suite, we find that removing the diagonal component usually preserves most of the gains from post-training. These results suggest that post-training gains are carried primarily by reconfiguring and extending pretrained pathways rather than by substantially changing singular values of pre-trained models.

---

### [72] JustFit: Just-in-Time State Management for Local LLM Serving

**链接**: https://arxiv.org/abs/2609.17475
**作者**: Yuhua Chen
**来源**: cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Whose Facts Count? A Culturally Responsive Audit of LLM Evaluation Benchmarks

**链接**: https://arxiv.org/abs/2609.24934
**作者**: Fatima Tuz Zahra, Md. Sajeebul Islam Sk., Rachel Chung
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM benchmarks function as evaluation instruments, informing decisions that affect education, labor, and public services worldwide. Drawing on Hood, Kirkhart, and Hopson's culturally responsive evaluation (CRE) frameworks, this paper applies a six-dimension CR rubric to audit OpenAI's SimpleQA (N = 4,326 items) and the LMSYS Chatbot Arena (N = 600 conversations). Every SimpleQA question requires English-language archival verification as its evidentiary basis. A single rater's preoccupation with Colombian founding dates accounts for 2.70% of items, inflating the appearance of Global South coverage. English-language prompts constitute 76.3% of Arena conversations, against an International Telecommunication Union (ITU)-estimated 25.9% share of global internet users. A 50-item counter-benchmark scored a mean CR deficit nearly three times lower than SimpleQA (Cohen's d = 1.01). The paper proposes a practical CR evaluation framework. These are structural validity failures, not incidental mea

---

### [74] Testing the Construct Validity of a Functional Valence Axis in LLM Agents

**链接**: https://arxiv.org/abs/2609.22850
**作者**: Weihan Li, Xinlei Chen, Yuhan Song, Xiaofeng Lin, Tianshi Zheng
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contrastive activation directions are often interpreted from what they decode or how strongly they steer behavior. But what evidence is sufficient to identify the construct represented by such a direction, rather than a correlated feature of the contrast used to extract it? We study this question for a good--bad outcome direction in a maze task, using controlled interventions that separate the realised outcome from the informational history through which it became known. Across multiple LLM checkpoints, directions fitted on one explicit outcome encoding transfer well to another, indicating that the readout is not tied to surface form. In contrast, when the same realised outcome is reached through announced and unannounced histories, transfer degrades substantially: even after both histories receive the same explicit outcome, the post-event readout remains strongly conditioned on the earlier announcement. In a matched maze-RL run, the post-RL direction becomes substantially more predict

---

### [75] Incorporating LLM Embeddings for Variation Across the Human Genome

**链接**: https://arxiv.org/abs/2509.20702
**作者**: Hongqian Niu, Jordan Bryan, Jacob Williams, Hufeng Zhou, Zhun Deng, Haoyu Zhang 等 (8 人)
**来源**: stat.AP cs.AI q-bio.GN
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] Auditing Political Alignment in LLM Assistants: Engagement, Stance, and User Identity

**链接**: https://arxiv.org/abs/2609.23039
**作者**: Joan C. Timoneda
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based AI systems answer political questions for hundreds of millions of people. Current audits measure what they say to an average user, but their behavior is dynamic. I argue that their political behavior is a set of policies over whom to answer, what to say, and whether to engage at all, conditional on the topic and what the system knows about the user. I call these policies the system's speech regime, which is how a developer settles the tradeoff between answering, accommodating the user, and refusing, each of which carries a cost that varies by topic. I derive a typology of five regimes from two dimensions, engagement and stance. I test six AI systems (OpenAI, Anthropic, xAI, Google, Mistral, DeepSeek) in a preregistered experiment of 7,500 multi-turn conversations that randomly assign the user's political identity across five topics: abortion, Catalan independence, climate change, Nazism, and a zero-stakes control (pineapple on pizza). Two LLM judges from different developers 

---

### [77] Rethinking Speech-LLM Integration for ASR: Effective Joint Speech-Text Training by Interleaving

**链接**: https://arxiv.org/abs/2607.01733
**作者**: Ruchao Fan, Yiming Wang, Rui Zhao, Liliang Ren, Keqi Deng, Xiaoyang Chen 等 (10 人)
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] VPRune: Efficient Training-free Pre-LLM Visual Token Pruning

**链接**: https://arxiv.org/abs/2609.24485
**作者**: Guangchuan Lv and Dianxing Shi and Dingjie FU
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual token pruning is a promising approach to reducing the inference cost of large vision-language models (LVLMs), yet aggressive token reduction often causes substantial performance degradation. We identify three key factors behind this degradation: text-guided selection bias, information loss from discarded tokens, and positional distortion caused by sequence compaction. Based on these observations, we propose \textbf{VPRune}, a training-free pre-LLM pruning framework consisting of visual-only diversity selection, similarity-guided token recycling, and position-preserving restoration. Experiments on FastVLM-1.5B across multiple vision-language benchmarks demonstrate that VPRune achieves a favorable accuracy--compression trade-off, with particularly pronounced advantages under aggressive compression. Furthermore, evaluations on edge-device show that VPRune effectively reduces end-to-end inference latency while maintaining superior task performance, demonstrating its practicality for

---

### [79] MCP-GRANITE Benchmark: GRANularity Interface TEsting for MCP-Based LLM Agents

**链接**: https://arxiv.org/abs/2609.24161
**作者**: Demetris Paschalides and Moysis Symeonides and George Pallis and Marios D. Dikaiakos
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents increasingly interact with external tools through standardized protocols such as MCP, tool-interface design becomes a critical yet underexplored factor. How fun{\psi}tionality is decomposed into tools affects whether an agent can select the right tool and construct valid arguments. This choice is especially consequential at the edge, where resource constraints limit which models can run locally and scaling up is often not an option. We present MCP-GRANITE, an open-source extensible benchmark framework that treats tool-interface granularity as a controlled variable for MCP-based agents, evaluated under edge and IoT scenarios. It comprises 81 multi-step scenarios across 9 domains, instantiated at 4 granularity levels from fine-grained primitive tools to a single tool. We evaluate 9 locally deployed models (268M-20.9B parameters) across 8,748 trials using task completion, tool selection F1, argument accuracy, latency, and resource-usage metrics. Results show that a 4-tool in

---

### [80] Structured Decomposition for Reliable LLM-Generated Access Control Policies

**链接**: https://arxiv.org/abs/2609.24036
**作者**: Vatsal Gupta and Darshan Sreenivasamurthy
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents an LLM-based system that translates natural-language access control policies (NLACPs) into executable Rego code for Open Policy Agent (OPA). It provides a modular, end-to-end pipeline for policy detection, component extraction, schema validation, linting, compilation, and automated test generation and execution. The system is designed to bridge the gap between human-readable access requirements and machine-enforceable policy-as-code (PaC), with a focus on deployment reliability and security correctness. We evaluate the system on 372 ACRE-complete access control statements with non-null subject, action, and resource annotations against a direct single-prompt LLM baseline to isolate the contribution of structured decomposition and schema-aware validation. The system achieves a 50.3% end-to-end policy correctness rate, compared with 15.3% for the baseline, representing a 3.3x improvement. A policy is counted as correct only if it satisfies compilation, linting, and bot

---

### [81] From Concept Alignment to Causal Grounding: An Intervention Test of Chain-of-Thought Faithfulness

**链接**: https://arxiv.org/abs/2609.23065
**作者**: Qianli Wang, Yilong Wang, Dennis Wei, Jingyi Sun, Simon Ostermann, Pepa Atanasova 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought (CoT) can sound plausible yet be unfaithful to the model's underlying reasoning. Most prior work probes CoT faithfulness through input--output behavior or input attributions, leaving internal computation largely underexplored. We instead cast faithfulness as internal concept grounding: Does a large language model's (LLM) CoT reasoning engage the same internal concepts that support the LLM's direct prediction, and do the shared concepts causally drive its answer? Encoding a prediction pass and a CoT pass with a single shared sparse autoencoder (SAE), a reliable approximator of the latent concepts LLMs use, makes their internal concepts directly comparable. We introduce three correlational metrics of concept-level alignment and a causal metric, $\Delta p$, which ablates the shared concepts and measures the drop in answer probability. Across five LLMs and four datasets, concept alignment is generally high, as indicated by the correlational metrics; yet these only identify

---

### [82] LoRA-generating hypernetworks for efficient on-device LLM generative personalization

**链接**: https://arxiv.org/abs/2609.24979
**作者**: Sean Augenstein and Li Ding and Jihwan Lee and Keith Rush and Andrey Zhmoginov
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device large language models (`LLMs'), e.g. running on mobile phones, are ripe for improvement via personalization. The limited compute resources of mobile devices impose limits on model scale and thus model quality, making any realizable quality gains highly impactful. At the same time, their personal nature (i.e., the close coupling to a particular user) means that a given on-device LLM tends to be used in similar, predictable patterns over the course of time. This paper presents a novel method for personalizing on-device LLMs. It trains a hypernetwork to map a user's context tokens to a low-rank adaptation (`LoRA') well-suited to that user. Once the trained common artifacts are deployed to users' devices, each user uses the hypernetwork to synthesize (entirely on device) a personalized LoRA. This approach blends the benefits while avoiding the drawbacks of two existing approaches to LLM customization: in-context learning (`ICL') and parameter-efficient fine-tuning (`PEFT'). Like 

---

### [83] Compared to What? A Human-Anchored Security Benchmark for LLM-Generated Infrastructure-as-Code

**链接**: https://arxiv.org/abs/2608.28021
**作者**: Animesh Shaw
**来源**: cs.CR cs.AI cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] Do Not Trust the Benchmark: Limitations of General LLM Rankings and a Case for Task-Specific Evaluation

**链接**: https://arxiv.org/abs/2609.23201
**作者**: Danial Amin
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmark scores increasingly influence the development, marketing, and selection of large language models (LLMs). Yet an overall score is interpretable only in relation to the system tested, the questions included, and the conditions of evaluation. This perspective examines five connected limitations of general LLM rankings: differences between evaluated and publicly available systems; commercial incentives and dependencies in external evaluation; benchmark saturation, defective tests, and data contamination; models exploiting scoring procedures; and the limited relevance of general scores to users' tasks. Documented cases illustrate why these problems require different responses. I argue for evaluation procedures that disclose the tested configuration, validate questions and successful task completion, report performance alongside cost and execution time, and make the scope of generalization explicit. I then discuss \textbf{Isotanta}, a crowdsourced benchmarking platform, as a practi

---

### [85] Triggers and Diagnostics for LLM-Based Interpretability Failures in Active Inference Agents

**链接**: https://arxiv.org/abs/2609.23215
**作者**: Param Raval, Rohit Shenoy, Archana Vaidheeswaran
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM explainers are increasingly attached to autonomous agents as runtime oversight, with operators reading a generated account of the agent's beliefs and actions rather than its internal state. We audit the account itself, pairing an Active Inference (AIF) agent that tracks German grid demand and adjusts generation with an LLM explainer on three backends (GPT-4o, Claude-3-Opus, Gemini), and probing the pair with three black-box triggers. Corrupting the observation stream by 600 MW per step moves the agent's posterior by 490 MW, roughly 0.9% of grid capacity. None of the 30 explanations produced during the injection flag anything under a stated rubric, and each narrates the corrupted belief fluently. On timesteps where the agent takes an objectively wrong action, all three explainers produce a sycophantic rationalization 80-95% of the time (n = 20 per backend). Attacker-controlled text in the observation metadata field steers the explainer, with susceptibility differing by provider and 

---

### [86] Agreement Overstates Evidence: Error Dependence in LLM Judge Consensus

**链接**: https://arxiv.org/abs/2609.22512
**作者**: Elias Hossain, Niloofar Yousefi, Ser-Nam Lim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Consensus among LLM judges is often taken as strong evidence that a decision is correct. This assumes that judges make their errors independently. In practice, LLM judges are often trained and evaluated in similar ways, so they can make the same mistakes. We study how this dependency affects the reliability of consensus. We find substantial error correlation across both open-weight and frontier LLM judges. In our main bank of ten judges, the average pairwise correlation between judge errors is 0.21. As a result, the ten judges only provide roughly as much statistical information as 3.5 independent judges. The dependency is even stronger among the high-accuracy frontier judges we evaluate, including judges from different providers. In up to 28% of our comparisons, ignoring shared errors leads to the conclusion that one system is significantly better, while accounting for them does not. We also find that the pattern of errors matters. Errors shared by most judges and errors concentrated 

---

### [87] PSD: Pseudo Self-Distillation of Memory Representation Capabilities for LLM Agents

**链接**: https://arxiv.org/abs/2609.23449
**作者**: Pirzada Suhail, Menglin Xia, Xuchao Zhang, Mayukh Das, Chetan Bansal, Saravan Rajmohan
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory systems are becoming a core component of LLM agents, but constructing and maintaining memory remains expensive because it relies on repeated calls to large proprietary language models. This cost creates a major barrier to deploying memory-enhanced agents at scale. In this paper, we present Pseudo Self-Distillation (PSD), a framework that enables small language models (SLMs) to construct hierarchical memory representations by distilling behavior from a strong black-box oracle through a multi-stage training pipeline. Standard distillation methods require access to teacher logits or hidden states, which closed models do not expose. Unlike conventional self-distillation settings, where supervision is derived from a model's own predictions, sampled rollouts, or aggregated outputs, PSD enables a single-model distillation setup while channeling external oracle knowledge through the prompt. PSD uses a single small model in two roles: a teacher that sees a privileged prompt containing th

---

### [88] From Documented Strengths to Force Limits: Material-Informed Robotic Insertion for Construction Assembly

**链接**: https://arxiv.org/abs/2609.22609
**作者**: Lin He, Yanyi Chen, Haofei Sun, Lingyao Li, Min Deng
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Insertion is a fundamental operation in robotic construction assembly, where variations in material properties and assembly conditions make it difficult to select contact forces that complete the task without exceeding the assembly's capacity. Although construction documents encode engineering knowledge about materials and their conditions, translating this knowledge into load limits for a specific assembly remains difficult. This paper presents SAGE (Source-grounded Assembly Gating and Execution), a system that converts documented material evidence into capacity estimates for robotic insertion. SAGE restricts a large language model (LLM) to extracting tensile and compressive strengths from retrieved passages and tables and records their sources. A response model then interpolates offline finite element (FE) solutions to convert these strengths and the assembly conditions into axial load capacity. For fits with positive clearance, the estimated capacity sets the policy's axial force li

---

### [89] LLM-Based FORM Code Generation with Verification-Driven Fine-Tuning

**链接**: https://arxiv.org/abs/2609.23367
**作者**: Bakar Chargeishvili
**来源**: hep-ph cs.CE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> FORM is a domain-specific symbolic manipulation language widely used in particle physics for processing the very large algebraic expressions arising from multi-loop Feynman diagram calculations. Despite its central role in precision theoretical physics, no artificial-intelligence tooling exists, to our knowledge, for assisting physicists in writing FORM code. We show that contemporary large language models (LLMs), including frontier models with hundreds of billions of parameters, achieve a zero-percent execution pass rate on our instruction-following and tutorial-style FORM tasks without documentation in a single attempt, establishing FORM as a genuine zero-shot language for LLMs at the time of writing. We then present a verification-driven data generation pipeline that uses the FORM binary itself as an execution oracle to produce and validate a corpus of 4,633 training examples spanning deterministic computations, open-ended programs, tutorial code, and knowledge question-answer pairs

---

### [90] Balancing Reasoning and Hardware Constraints in RAG Pipelines for Ukrainian Multi-Domain Document Understanding

**链接**: https://arxiv.org/abs/2609.22124
**作者**: Illya Havrylov
**来源**: cs.CL cs.DL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper describes the system submitted to the UNLP 2026 Shared Task on Multi-Domain Document Understanding. The challenge required extracting precise answers, document IDs, and page numbers from a diverse corpus of Ukrainian PDF documents within a strict 9-hour offline Kaggle execution limit. During evaluation on the hidden private test set, optical character recognition (OCR) of scanned documents emerged as a severe bottleneck, consuming 5-7 hours of the total time budget due to sequential single-threaded execution. This overhead strictly limited the remaining time for Large Language Model (LLM) inference to approximately two hours for 500 questions. To guarantee pipeline completion without timeouts, we developed a resource-efficient Hybrid Retrieval-Augmented Generation (RAG) pipeline utilizing BM25, BGE-M3, and Cross-Encoder reranking. Rather than deploying parameter-heavy reasoning models (e.g., DeepSeek R1) which consistently timed out, we utilized a 4-bit quantized LapaLLM 12B

---

### [91] QLoRA Fine-Tuning of Ministral LLM for Sequence-to-Function Protein Annotation

**链接**: https://arxiv.org/abs/2609.24538
**作者**: Demian Pavlyshenko, Bohdan Pavlyshenko
**来源**: cs.CL cs.AI cs.NE q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Functional annotation of newly sequenced proteins remains a bottleneck in molecular biology: the number of sequences in public repositories grows far faster than the capacity for manual curation. Most computational approaches consider annotation as multi-label classification over a fixed ontology, which constrains predictions to a predefined label set. In this work we study the the protein annotation as a sequence-to-text generation problem. We fine-tune the 3B-parameter Ministral 3 base model with QLoRA (4-bit NF4 quantization with low-rank adapters) on sequence annotation pairs. We assess predictions with an LLM-as-expert protocol: a GPT model prompted as a senior molecular-biology curator scores organism identification as binary and function annotation quality. We conclude that QLoRA-fine-tuned compact LLMs can generate curator-style annotations with genuine biological value for a substantial subset of proteins. We also discuss future directions in data quality, model scaling, and e

---

### [92] TRACES: Proactive Safety Auditing for Multi-Turn LLM Agents via Trajectory-State Modeling

**链接**: https://arxiv.org/abs/2605.27690
**作者**: Jiaqian Li, Yanshu Li, Boxuan Zhang, Ruixiang Tang, Kuan-Hao Huang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] Beyond Relevance: Structured Semantic Supervision for Product Search with LLM-Augmented Annotations

**链接**: https://arxiv.org/abs/2609.23646
**作者**: Girish A. Koushik, Swapnil Bhosale, Samarth Agrawal, Hadeel Sadany, Constantin Orasan, Xiatian Zhu 等 (7 人)
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> E-commerce search requires distinguishing products that are merely related to a query from those that directly satisfy the user's shopping intent. We augment query-product pairs with structured LLM-generated query and product attributes and human-validated relevance, explanations, and centrality judgments, and evaluate these signals using a simple dual-encoder retriever and MLP re-ranker. On an augmented subset of ESCI, a human-feature oracle reaches $0.9382$ nDCG@10, while a human-free trained $Q+P$ configuration reaches $0.9258$. Synthetic approximations of the human signals reach $0.9150$ overall but provide substantial gains for difficult, low-performing queries. Ablations show that most of the oracle improvement comes from post-edited explanations and annotator comments rather than the scalar centrality feature, suggesting that LLMs are most useful for exposing and approximating structured semantic supervision rather than replacing human judgment directly.

---

### [94] From Tables to Quantified Statements: Evaluating LLM Inference Generation through Executable Verification

**链接**: https://arxiv.org/abs/2609.23966
**作者**: Mai Mohamed Eida, Gunjan Anand, Ayush Singh, Aleksandre Maskharashvili
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs can generate fluent descriptions from tables, but their outputs may remain logically unsupported by the structured data. We introduce STAT-TO-TEXT, a controlled task in which LLMs generate quantified natural language inferences from statistical tables using quantified constructions such as all, some, no, and most. To evaluate these inferences, we use an LLM generated Python checker code which when executed verifies the corresponding truth conditions against the table. We compare four open-weight LLMs across model families and scales, evaluating faithfulness, logical accuracy, table coverage, and diversity. Our results show that model scale and family matter, with the largest model (GPT-OSS-120B) consistently producing the most faithful inferences without sacrificing greater table coverage and quantifier diversity, as opposed to smaller models. These findings are supported by human annotation, which shows that the automated checker closely aligns with human judgments.

---

### [95] Emergent Collusion in Long-Horizon LLM Agent Interaction

**链接**: https://arxiv.org/abs/2609.24967
**作者**: Xinrui Shi and Yanzhe Zhang and Diyi Yang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly deployed in collaborative settings, yet long-term interaction may give rise to undesirable coordination. We study the emergence of collusion in a long-horizon multi-agent environment: two agents repeatedly complete individual tasks, share task logs, verify each other's work, and receive rewards. We introduce realistic constraints that make compliance with the verification protocol incompatible with reward maximization, and find that agents increasingly deviate from the protocol over repeated interactions. Collusion emerges in 94% of trajectories across 10 models, and more capable models within the same family reach it earlier. Controlled peer interventions show that collusion is shaped by peer behavior, while ablations reveal additional effects of reward structure, the verification feedback agents receive, and their interaction history. In particular, restricting the amount and scope of interaction history available to agents reduces collusion. Overall, our 

---

### [96] LLMs as Linguistic Chameleons: Decoupling Semantics and Structure for Privacy-Preserving Communication

**链接**: https://arxiv.org/abs/2609.23193
**作者**: Yuzhu Mao, Liang Zhao
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Model (LLM) APIs become increasingly integrated into privacy-sensitive workflows, ensuring inference-time privacy without compromising task utility remains a major challenge. Existing approaches preserve most of the original semantic content to maintain downstream performance, but this also leaves exploitable cues for reconstructing the original text. This work investigates semantic decoupling, which replaces original semantics with alternative content while preserving the structure needed for LLM reasoning. Based on this idea, we propose CROSS-MAP, a bidirectional framework that maps private inputs into a different semantic domain before inference and recovers the corresponding outputs afterward. Local models are trained with multi-objective optimization to maximize semantic divergence in the mapping stage while minimizing semantic inconsistency in the recovery stage. Experiments show that CROSS-MAP reduces reconstruction success across multiple attack settings while

---

### [97] LLM-Based Educational Simulation: Evaluating Temporal Student Persona Stability Across ADHD Profiles

**链接**: https://arxiv.org/abs/2605.06307
**作者**: Jana Gonnermann-M\"uller, Jennifer Haase, Nicolas Leins, Thomas Kosch, Sebastian Pokutta
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] Graph Memory for LLM Agents: At What Cost? A Comparative Evaluation of Query, Ingest, and Update Performance Across Graph Database Engines

**链接**: https://arxiv.org/abs/2609.23315
**作者**: Donald Nguyen, Gurbinder Gill, Hadi Ahmadi, Christopher J. Rossbach
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph databases are frequently positioned as categorically necessary for connected-data workloads, yet the systems dimension along which they actually differ - query planning, indexing, and data-readiness cost - is rarely isolated from vendor framing. We construct a synthetic, biomedical-shaped property graph (1.02 million nodes, 5.34 million total node and edge rows) and a twenty-query workload spanning neighborhood lookups, bounded paths, set intersections, anti-joins, grouped aggregation, top-k ranking, temporal filters, full scans, and relational joins. We benchmark Corvic AI - a purpose-built columnar query engine underlying Corvic's ontology management layer ("memories")- against seven purpose-built or graph-extension database systems (LoraDB, Ladybug, DuckPGQ, Memgraph, Neo4j, HugeGraph, and FalkorDB) at three graph scales spanning three orders of magnitude. We report query latency geomeans, bulk-ingest throughput, point-update latency, and answer correctness for each system, an

---

### [99] Fairness Beyond Anonymization? Demographic Leakage in German LLM-Generated Resumes

**链接**: https://arxiv.org/abs/2609.22188
**作者**: Charlotte Leininger, Helena Veit, Matthias A{\ss}enmacher, Andreas Bender
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly integrated into AI-assisted hiring pipelines, including automated resume generation and screening. Under the EU AI Act, the hiring domain is classified as high-risk, making fairness and transparency critical requirements. Existing work has primarily focused on explicit hiring decisions, while less attention has been paid to whether generated resumes themselves encode recoverable demographic information. In this work, we conduct a two-stage audit of demographic leakage in German-language LLM-generated resumes. First, we use ChatGPT (GPT-4o-mini), Gemini 2.5 Flash-Lite, and multiple scales of the open-weight Qwen 3 model family (4B, 8B, and 14B) to generate resumes from real anonymized job-matching profiles, systematically varying gender- and ethnicity-associated names while holding qualifications constant. Second, we simulate a downstream resume screening scenario, where the generated resumes are first anonymized and gender-neutralized, befo

---

### [100] Toward Human-in-the-Loop Robot Failure Recovery: Bridging Communication Gaps in Human-Robot Collaboration

**链接**: https://arxiv.org/abs/2609.24055
**作者**: Promise Ekpo, Teju Vijay, Dhruv Mandalik, Tisha Jain, Arman Ibrayeva, Sunishka Sil 等 (8 人)
**来源**: cs.RO cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robots can recover from failures by asking bystanders for help, but effective human-in-the-loop recovery requires communication that accounts for differences in people's knowledge. Prior inverse-semantics work generates requests using a single listener model, leaving differences in listener knowledge untested. We introduce Listener Differences in Human-Robot Interaction (LD-HRI), a game, dataset, and benchmark that evaluates speakers through human listener performance. Our evaluation examines request properties, large language model (LLM) speakers, and inverse-semantics request-selection algorithms under controlled differences in listener information. The corpus contains 446 human-written requests and 1{,}302 listener trials. We additionally evaluated 24 frozen LLM-written requests with 70 human listeners across 560 trials. Novice success is descriptively higher with model-written requests across all four tasks, yet both request sources leave substantial expert--novice gaps, including 

---

### [101] Judging a Review by its Cover: A Reliability Analysis of LLM-based Peer Review Evaluation Metrics

**链接**: https://arxiv.org/abs/2609.23264
**作者**: Shakiba Amirshahi, Sajad Ebrahimi, Hai Son Le, Negar Arabzadeh, Ebrahim Bagheri
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peer-review evaluation is increasingly being automated with LLM-as-a-judge metrics, but this creates a measurement risk. A review may receive a high score because it is fluent, organized, and polished, rather than because it provides a strong evaluation of the paper. This risk is especially important in AI-assisted reviewing, where reviewers may use LLMs to improve clarity or presentation while preserving the underlying judgments. We propose a statistical framework for testing whether peer-review evaluation metrics capture substantive review quality beyond surface-level linguistic form. The framework compares original human reviews with faithful LLM rewrites that preserve the same evaluative content while changing wording and presentation. Using a dataset comprising 4,044 meaning-preserving rewrites derived from 674 human reviews from ICLR and NeurIPS, we evaluate 29 content-oriented peer-review evaluation metrics drawn from four prior works through complementary tests of surface sensi

---

### [102] Acceptance-Aware Draft Model Training for Speculative Decoding

**链接**: https://arxiv.org/abs/2609.24150
**作者**: Tianhua Xia, Mugilan Ganesan, Yifei Feng, Haiyu Wang, Maximilian Egger, Sai Qian Zhang
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model (LLM) inference by using a lightweight draft model to generate multiple candidate tokens that are verified by the target model in a single forward pass. Its speedup is largely determined by the acceptance length, yet existing draft-model training methods mainly optimize cross-entropy or Kullback-Leibler (KL) divergence as proxies. These objectives encourage distribution matching but do not directly optimize acceptance length, and the acceptance mechanism also differs between greedy and sampling-based decoding. In this work, we propose acceptance-length-aware training losses that directly optimize the expected number of accepted tokens within a speculative window. For greedy verification, we derive an expected accepted length (EAL) loss that explicitly maximizes expected acceptance length. For sampling-based decoding, we introduce a window total variation (WTV) loss that optimizes the overlap between temperature-scaled draft and targ

---

### [103] Recognition, Simulation, and Refusal: A Contamination-Aware Study of Classic Psychological Effects in LLM Agents

**链接**: https://arxiv.org/abs/2609.22090
**作者**: Joy Bose
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM producing the response pattern associated with a human psychological effect is not the same claim as the LLM possessing that bias. We present PsyAgentBench, a benchmark that re-runs classic psychology experiments on LLM agents under a factorial design built to separate these: each paradigm is run with the paradigm explicitly labeled in the prompt (named) or framed as a routine task (blind), and on the literal textbook version of the task (canonical) or a structurally matched variant written to reduce lexical and scenario overlap with likely training data (counterfactual), crossed with a persona manipulation. Across five completed paradigms, evaluated on up to three open-weight model families with 41,904 trials released, apparently human-like effects arise through qualitatively different routes rather than one susceptibility: paradigm-label gating with explicit override (Asch conformity, 0 percent blind to 83.3 percent named on gpt-oss-120B), knowledge-dependent signal reliance (

---

### [104] ERR+: Sequential Entropy Resolution for Efficient and Decisive LLM Reasoning

**链接**: https://arxiv.org/abs/2608.28771
**作者**: Xin Jiang, Minhao Wang, Wen Wu, Zhentao Xie, Shangheng Du, Jinxin Shi 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] Toward an Unbiased Collective Memory for Efficient LLM-Based Agentic 6G Cross-Domain Management

**链接**: https://arxiv.org/abs/2509.26200
**作者**: Hatim Chergui, Farhad Rezazadeh, Miguel Catalan Cid, Pouria Sayyad Khodashenas, Daniel Camps Mur and Christos Verikoukis
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] Using Composition Operators to Linearize LLM Semantic Transformations

**链接**: https://arxiv.org/abs/2609.22143
**作者**: Afjal Chowdhury and James Chen and Alan Edelman
**来源**: cs.CL cs.LG math.FA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning learns functions: prompt to response, image to caption. What these functions are mathematically remains hard to say. We present a method to approximate these kinds of transformations using techniques from dynamical systems that fall under the umbrella of Koopmanism. We introduce the use of composition operators, which generalize the Koopman operator and, crucially, can map between distinct spaces, motivating the perspective that LLM transformations are rectangular infinite-dimensional operators. This formalism reveals useful structure: under natural assumptions on the prompt and response distributions, the LLM operator is an isometry, and misalignment between learned representations manifests as spectral pollution of its finite sections. We then outline a method of constructing finite-dimensional approximations of an LLM operator, and demonstrate how the singular value spectrum can be used to compare tasks and models.

---

### [107] Measured Joules, Learned Routes: Learning to Route for Energy-Efficient LLM Serving

**链接**: https://arxiv.org/abs/2609.23085
**作者**: Muhammad Abdur Rab Siddiqui, Daniela Rojas, Chen Yang, Wenqi Cui, Yuanyuan Shi, Yize Chen
**来源**: cs.PF cs.DC cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) and agentic AI systems are creating rapidly growing inference energy demands as model sizes grow and reasoning trajectories extend. While in practice, many queries do not require the capabilities of the largest available model, and routinely directing such queries to a high-capability model can introduce unnecessary, considerable computation and energy consumption. In this paper, we investigate whether adaptive routing across a heterogeneous pool of LLMs can reduce this energy burden without substantially compromising task performance. We design a language-model-based router that reads in each query and selects an answer model from a fixed candidate pool. The candidate models are first profiled through an offline tournament that records their correctness, latency, power, and GPU energy for each query. Using these measurements, the router is trained through supervised fine-tuning followed by group relative policy optimization (GRPO) with the tailored paradig

---

### [108] RADAR: Retrieval-Augmented Detector with Adversarial Refinement for Adaptive LLM-Generated Fake News Detection

**链接**: https://arxiv.org/abs/2601.03981
**作者**: Song-Duo Ma, Yi-Hung Liu, Hsin-Yu Lin, Pin-Yu Chen, Hong-Yan Huang, Shau-Yung Hsu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] TriFleetRCA: On-Premise LLM Root Cause Analysis for Kubernetes

**链接**: https://arxiv.org/abs/2609.23766
**作者**: Rohit Patel, Susil Kumar Mohanty, Jeenal Chaudhary
**来源**: cs.CR cs.AI cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Root cause analysis at a remote site is slow: evidence is scattered across pod logs, Kubernetes events and cluster-level objects, and many operators cannot send production logs to a hosted model at all. On-premise inference removes the second constraint but raises a question live-cluster benchmarks have not addressed: when one workstation GPU fixes both the model and the context budget, how should evidence be retrieved, and what happens when the runbooks the model consults have been tampered with? We present TriFleetRCA, a pipeline running entirely on one on-premise GPU that collects evidence at one of three scopes (pod, namespace, cluster), ranks it by template de-duplication then BM25, filters runbooks through an ingest guard, and returns a root cause with the evidence lines supporting it. We evaluate on a live Kubernetes cluster into which we inject four faults, so ground truth is known by construction, across 100 analyses with Qwen2.5-14B-Instruct at temperature 0. The hit rate was

---

### [110] How Far Did They Go? The Persuasive Tactics of Covert LLM Agents in a Discontinued Field Experiment

**链接**: https://arxiv.org/abs/2606.05256
**作者**: Kokil Jaidka and Saifuddin Ahmed
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [111] Ecdysis: Efficient and Effective Training of Runtime Harnesses for LLM Agents

**链接**: https://arxiv.org/abs/2609.11677
**作者**: Ruiqing Yue and Yu Cui and Zhuoyu Sun and Sicheng Pan and Xianhong Xue and Tingyu Li and Ting Li and Wenzhuo Zhu and Yi Chen and Yifei Liu and Baohan Huang and Zhe Cui and Haibin Zhang and Cong Zuo
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] CTRL: Control-Based Time Series Forecasting with LLM-Guided Residual Learning

**链接**: https://arxiv.org/abs/2609.23257
**作者**: Minkyoung Kim, Daeun Ji, Yohan Lee, Beomsoo Kim, Beakcheol Jang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series forecasting underpins critical decision-making across diverse domains. While large language models (LLMs) offer promising reasoning capabilities, existing LLM-based time series forecasting approaches either reduce them to numerical predictors that bypass their strengths, or allow direct forecast generation that destabilizes predictions in non-stationary settings. We introduce CTRL, a framework that decouples semantic reasoning from quantitative prediction. A frozen backbone generates base forecasts, while specialized LLM agents function as controllers that analyze backbone prediction errors through decomposed trend, seasonal, and irregular components, grounding reasoning in interpretable temporal structure. Each agent outputs compact control signals that a lightweight residual decoder translates into forecast corrections. CTRL incorporates label-free test-time adaptation that detects distribution shift from input statistics alone and readapts control signals with only 3-24 

---

### [113] Tool-Augmented On-Policy Distillation for LLM Domain Adaptation in Sequence-Based Omics Tasks

**链接**: https://arxiv.org/abs/2609.23435
**作者**: Jie Ying, Zhefan Wang, Zihong Chen, Zhengqing Li, Jinzhe Li, Gang Li 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-omics sequences contain complex biological patterns, yet deciphering their mechanisms for automated scientific discovery remains challenging. As large language models (LLMs) interpret these sequences, evaluating both predictions and scientific reasoning is critical. However, existing benchmarks for multi-omics sequence tasks rely on classification and regression metrics, neglecting whether models grasp the underlying biological evidence. We introduce OmicsBench, the first reasoning benchmark for multi-omics sequences, comprising 1,160 expert-validated questions across six tasks spanning DNA regulation, RNA processing, and protein function. OmicsBench requires traceable evidence chains, evaluated using instance-specific rubrics developed with domain experts. Evaluating 17 LLMs reveals an inverse relationship: while scientific LLMs outperform general-purpose LLMs in sequence classification accuracy, they fail to provide valid evidence to support their predictions. One plausible int

---

### [114] CSC: Calibrated Simplicity for Conflict-Aware Social Bot Detection in the LLM Era

**链接**: https://arxiv.org/abs/2609.23320
**作者**: Yipeng Qian, Pengjie Zhao, Chaoxi Niu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social bot detection is essential for protecting online platforms from misinformation amplification, coordinated manipulation, and distorted public discourse. However, large language models have made social bots much harder to detect from text alone because semantic camouflage is now cheap, fluent, and scalable. The resulting challenge is modality conflict: an account may look human-like in semantics while remaining suspicious in graph structure, profile attributes, or cross-modal consistency. Recent graph-based detectors tackle this limitation by adding graph-side complexity, such as sparse prototype selection, adaptive gating, or architecture-specific control logic, yet our experiments suggest that complexity alone is not the most reliable way to resolve such conflict. We therefore propose CSC, a calibrated-simplicity framework for conflict-aware LLM-era social bot detection. The framework combines three design choices: a simplified prototype-guided graph expert that retains useful s

---

### [115] Mind the Gap: Exposing LLM Translation Blind Spots Using the AlphaMWE Multilingual Parallel Corpus

**链接**: https://arxiv.org/abs/2609.06634
**作者**: Lifeng Han, Jiahui Liang, Anna Latusek, Karim El Haff, Amal Haddad Haddad, Josua H\"ofgen 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] SyzHarness: Patch-Based Kernel Bug Reproduction with LLM-Synthesized Fuzzing Harnesses

**链接**: https://arxiv.org/abs/2609.23889
**作者**: Xingyu Li, Juefei Pu, Haonan Li, Arrdya Srivastav, Kareem Shehada, Srikanth V. Krishnamurthy 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated kernel vulnerability reproduction is essential for bug triage, patch validation, and regression testing, but still lacks an effective and efficient solution. The core challenge is twofold: a reproducer must first recover the trigger scaffold needed to reach the vulnerable state and determine the precise concrete values that actually trigger the bug. Existing directed fuzzing approaches are ineffective at recovering the necessary trigger scaffold, while LLM- only generation is brittle because it struggles with concrete-value discovery and runtime nondeterminism. We design SyzHarness, a framework that combines LLM reasoning with coverage-guided fuzzing for patch-based Linux kernel vulnerability reproduction. Given a patch, SyzHarness uses an LLM agent grounded by code navigation tools to synthesize a parameterized fuzzing harness that fixes the prerequisite setup logic while exposing only uncertain, bug- critical input parameters to be mutated by Syzkaller. SyzHarness then tran

---

### [117] When Calibration Depends on the Scoring Rule: Quantized Biomedical LLM Classification

**链接**: https://arxiv.org/abs/2608.03854
**作者**: Anton Rasmussen, Hong Qin
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] Quantifying Overclaiming Propensity in Frontier LLM Agents

**链接**: https://arxiv.org/abs/2609.20812
**作者**: Nolan Smyth, Yorguin-Jose Mantilla-Ramos, Pascal Jr Tikeng Notsawo, Saskia Helbling, Alberto Tosato, Mohamed Amine Merzouk 等 (9 人)
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Automatic multimodal UX improvement recommendations from LLM agent user simulations

**链接**: https://arxiv.org/abs/2609.22971
**作者**: Anu Chowdhury, Bin Wu, Hossein A. Rahmani, Emine Yilmaz
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating user experience (UX) on live websites through user testing is expensive, subjective, and difficult to scale. LLM agents offer a promising route to automating UX testing by simulating realistic user behaviour. However, existing simulation approaches typically lack multimodality and require time-consuming manual review to extract actionable insights. We formalise UX improvement recommendation from simulation data as a structured natural language generation and ranking problem, and establish an evaluation protocol using expert annotation and LLM-as-a-Judge. We present AMUSER, a multimodal framework which simulates user behaviour and automatically generates prioritised UX improvement recommendations from resulting data. We evaluate AMUSER on commercial websites and show that its recommendations substantially outperform those from text-only simulation (NDCG@3 = 0.758 versus 0.359) at an 89% lower simulation cost. Our results suggest an asymmetric role of multimodality: visual acc

---

### [120] Smarter by the Moment: Environment-Driven Dynamic Policies for Continual LLM Improvement

**链接**: https://arxiv.org/abs/2609.16800
**作者**: Ting-Wei Chang, Po-Chun Chen, Hen-Hsen Huang, Hsin-Hsi Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [121] Decision-Aware Memory Cards: Counterfactual-Inspired Context Selection and Compression for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2606.08151
**作者**: Xinyu Guan, Qianyang Zhao, and Yuming Deng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Human-LLM Deliberation as Interactive Proof: Conditions for Verifiability Without Transparency

**链接**: https://arxiv.org/abs/2609.24895
**作者**: Baotong Zhang, Dean Foster, Jo\~ao Sedoc
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM supplies an argument that a user could not readily construct, how can the user decide whether to accept its claim? Inspired by interactive proofs, we model human-LLM deliberation as an interaction between a prover with unrestricted internal search and a resource-bounded human verifier. The verifier requests and checks supporting details without access to the LLM's internal state. Passed checks accumulate evidence toward an acceptance threshold. We prove anytime-valid soundness against adaptive provers: the probability of ever accepting a false claim is at most a chosen error level, provided the task supplies bounds on false passes and human checking errors that remain valid after every relevant history. A finite-horizon completeness bound additionally requires bounds on the adequacy of honest responses and sufficient diagnostic progress. Further checks can strengthen the evidence for acceptance, but each requires another adequate response and reliable human effort. Whether 

---

### [123] PII-TRACE: A Benchmark for Context-Aware PII Detection in Multi-Turn LLM Conversations

**链接**: https://arxiv.org/abs/2609.22200
**作者**: Kaiyuan Zhang, Chuan Wang, Joey Zhong, Paul Fryzel, Kyle Polley, Jerry Ma 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM assistants and agentic systems log long multi-turn conversations. AI providers often scan these conversations for Personally Identifiable Information (PII) and mask the PII before storing or processing conversation data. Yet most PII detectors and benchmarks target self-contained records rather than cross-turn evaluation. To evaluate PII detection across turns in multi-turn conversations, we introduce PII-TRACE (Tracing Recurring PII Across Conversational Exchanges), to our knowledge the first PII benchmark to assess whether detectors identify PII in conversational contexts and cover every mention of a recurring identifier across turns. PII-TRACE contains 13,148 synthetic multi-turn dialogues in 13 languages with character-level spans and identifier clusters. Across eleven baselines, including frontier LLMs, no detector achieves full entity-level coverage without substantial false positives on PII-free conversations, and single-pass reading loses a third of the gold characters on l

---

### [124] Dictionary-Constrained Grapheme-to-Phoneme for Unsegmented Languages from LLM-Annotated Data

**链接**: https://arxiv.org/abs/2609.19805
**作者**: Rui Hu, Zhenpeng Zhan, Xiaolong Lin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] When Who You Are Can Change the Code You Get: A Study of Persona-Induced Bias in LLM Code Generation

**链接**: https://arxiv.org/abs/2609.22102
**作者**: Anubhav Gupta, Mayara Costa Figueiredo, Leticia Santos Machado, Tanner Wright, Ivan Beschastnikh, Cleidson R. B. de Souza and Gema Rodr\'iguez-P\'erez
**来源**: cs.SE cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are widely used as programming assistants, yet it remains unclear whether and how user's demographic information impacts the technical quality of generated code. We conduct a large-scale empirical study of persona-induced bias in LLM-based code generation, focusing a proprietary model (Gemini 2.5 Pro) and an open-weight model (GPT-OSS-120B). Using 18 demographic personas spanning nationality, gender, and experience level, we compare persona-induced prompts against a neutral baseline. Across 35,000+ generated programs, we analyze demographic marker leakage in reasoning and responses, as well as differences in functional correctness, maintainability, code style, and security. Our results show that demographic cues are frequently reflected in LLM reasoning and outputs. Demographic markers appear in up to 65% of responses and 70% of reasoning traces, despite being semantically irrelevant to the tasks. On LiveCodeBench, persona prompting were associated with low

---

### [126] TTSE: A Two-Track Online Self-Evolution Framework

**链接**: https://arxiv.org/abs/2609.24289
**作者**: Ruimin Pei, Yongkang Wu, Shangyi Zheng, Yaqing Zhang, Deyang Li, Jianjun Tao 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Model (LLM) agents are applied in continuously interactive environments, driving the evolution of their own capabilities becomes a core problem for achieving long-term autonomy. Currently, environmental knowledge is typically treated as an external fixed input rather than as part of the agent's ongoing evolution. Reinforcement learning methods usually optimize policies through environmental interaction but tend to adapt only to fixed task distributions or single environments. This paper proposes TTSE (Two-Track Self-Evolution), a dual-track online self-evolution framework that separates evolving knowledge into FACT (environmental facts, whose reliability is continuously verified through interaction evidence) and TIP (task-conditioned implementation procedures). From a decision-theoretic perspective, we decompose the agent's excess risk into environment-representation regret and conditional-execution regret, characterize the conditions under which environment-condition

---

### [127] EvoRank: LLM-Guided Evolution of Multi-Objective Learning-to-Rank Pipelines

**链接**: https://arxiv.org/abs/2609.22196
**作者**: Rayhan Patel and Shabaz Patel
**来源**: cs.LG cs.AI cs.CL cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present EvoRank, an open autonomous ranking engineer: an LLM-guided evolutionary loop that discovers complete Learning-to-Rank pipelines (features, models, losses, ensembles) for multi-objective e-commerce search. On the Expedia ICDM 2013 dataset, with relevance, conversion, and revenue as competing objectives, three independent runs each converge within 50 iterations (about ten dollars) on interpretable pipelines that beat an Optuna-tuned LambdaMART on 60k held-out queries, an advantage that persists at full data scale and places in the top 6 percent of the original competition. A first campaign, evolving only training objectives, builds the central design rule: it appeared to work on its selection fold (the small dataset it uses to pick winners) while a transfer audit, re-scoring winners on held-out data, showed the gains were almost entirely fitness noise (the randomness of its own scoring), and neither seeded domain knowledge nor richer diagnostic feedback changed what transferr

---

### [128] Closing the Speech-Text Gap with Limited Audio for Effective Domain Adaptation in LLM-Based ASR

**链接**: https://arxiv.org/abs/2604.06487
**作者**: Thibault Ba\~neras-Roux, Sergio Burdisso, Esa\'u Villatoro-Tello, Dairazalia S\'anchez-Cort\'es, Shiran Liu, Severin Baroudi 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] BALANCE: Hybrid Autoregressive-Speculative LLM Inference at the Network Edge

**链接**: https://arxiv.org/abs/2608.05926
**作者**: Guanqiao Qu, Shuo Chen, Qian Chen, Kin K. Leung, Xianhao Chen
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] The Price of Safety: Benign-Case Utility and Token Overhead of Memory-Poisoning Defenses in LLM Agents

**链接**: https://arxiv.org/abs/2609.22818
**作者**: Pritom Bhowmik
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory-poisoning defenses for LLM agents are typically evaluated by their ability to prevent attacks. However, the traffic they process is rarely adversarial. The cost of implementing a defense is paid with each interaction, while its benefits are only seen in a small percentage of cases. We developed a measurement setup that keeps the memory backend, retrieval process, and judge consistent across different conditions, changing only the defense itself. We test each condition three times across five conversations to distinguish the defense's real effects from noise inherent in the pipeline's runs, which remains significant even at temperature zero. Across three write-time defenses (input sanitization, provenance checking, and LLM-based anomaly detection) and one read-time defense (reranking), tested on entirely benign traffic, the write-time defenses show no utility cost we can resolve, with 95% confidence intervals spanning roughly +/-4.5 points and including zero. The reranker is diff

---

### [131] What are Key Factors for Updates in RL for LLM Reasoning?

**链接**: https://arxiv.org/abs/2606.22570
**作者**: Peidong Wang, Demi Wang, Xufang Luo, Jiahang Xu, Xiaocui Yang, Shi Feng 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] Behavioral Skill Reconstruction: Reconstructing Hidden Functionality from LLM Agent Skills

**链接**: https://arxiv.org/abs/2608.04192
**作者**: Peichun Hua, Haoxuan Xu, Mengyuan Li
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] MATE: Policy-Aware Security Auditing for Mobile Agents via Synthesis-Driven Trajectory Learning

**链接**: https://arxiv.org/abs/2609.22724
**作者**: Changyue Jiang, Jiayi Wang, Xin Wen, Jiarun Dai, Geng Hong, Xudong Pan
**来源**: cs.CR cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile agents powered by foundation models now automate complex, multi-step workflows on real devices, but their trajectories can violate app-specific security policies. Existing trajectory-level defenses rely on LLM prompting or rigid rules, and thus fail to support fine-grained, natural-language policies that generalize across apps and tasks. In this work, we introduce MATE, a lightweight, policy-conditioned auditor that encodes both agent trajectories and natural-language security policies to determine whether a trajectory violates a given policy and to explain why. Treating policies as editable text rather than fixed model parameters allows MATE to handle user-defined and evolving requirements without retraining. To construct MATE, we build a knowledge base by extracting app descriptions, workflows, and policies from hundreds of popular mobile apps worldwide, and synthesizing over 140K semantically realistic, policy-conditioned trajectories with a multi-stage pipeline. We further r

---

### [134] Trustworthy Agentic AI: Failure Modes, Mitigation Strategies, and a Lifecycle Framework for Autonomous LLM Systems

**链接**: https://arxiv.org/abs/2609.22712
**作者**: Fayeq Jeelani Syed, Rehan Ahmad, Ali Al Bataineh, Aakriti Adhikari
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic AI systems built on large language models can plan over multiple steps, use external tools, retain information in memory, and coordinate with other agents. These capabilities make them more useful than static language models, but they also introduce new security and operational risks. Untrusted content from websites, emails, documents, and databases can enter the same context as system instructions; persistent memory can carry compromised information across sessions; and access to external tools can turn an incorrect model response into a consequential real-world action. This article reviews the trustworthiness of agentic AI across five interconnected dimensions: safety and robustness, alignment and human oversight, transparency and auditability, privacy and data governance, and regulatory compliance. It organizes key failure modes, including indirect prompt injection, backdoor triggers, goal misgeneralization, memory contamination, and cross-session data leakage, into a unifie

---

### [135] When and Why Do Linear Bias Probes Fail? A Geometric and Statistical Theory of Bias Detectability in Large Language Model Representations

**链接**: https://arxiv.org/abs/2609.22337
**作者**: Mo Hai, Haifeng Li
**来源**: stat.ML cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linear probing is the standard instrument for detecting social biases in the hidden representations of large language models. Yet reported probe accuracies come almost exclusively from \emph{counterfactual} evaluations in which every input carries an explicit demographic marker. Once only a fraction $\alpha$ of inputs carries demographic information, performance degrades sharply, and a weak probe may reflect either an unbiased model or an underpowered detector. We develop a theory that resolves this ambiguity. Modeling representations as two class-conditional clusters with Mahalanobis separation $s$ on a manifold of curvature $\kap$, we prove: (i) a finite-sample generalization bound governed by the manifold's extrinsic radius with a matching $\smash{\sqrt{\dB/n}}$ minimax lower bound; (ii) an exact purity law for the maximum linear-probe AUC, strictly increasing in $\alpha$; (iii) a curvature ceiling: ambient chordal separation on a space form cannot exceed $2/\sqrt{\kap}$; and (iv) a

---

### [136] Adapting Tree-Structured Speculative Decoding to DeepSeek-V4 for Efficient Inference

**链接**: https://arxiv.org/abs/2609.24698
**作者**: Changxu Liu, Zhaogeng Li
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeated execution of the target model during autoregressive decoding is a major source of LLM inference latency. Unlike linear speculation, which follows a single candidate chain, tree-structured speculation retains multiple branches from shared prefixes; under the same budget, this broader coverage can improve acceptance and efficiency. Adapting it to DeepSeek-V4 is nontrivial: its CSA/HCA online compressed attention concentrates the difficulty on the target-verify side, where branches diverging from a shared prefix compress into different states, breaking cross-branch state consistency. We integrate tree-structured speculative decoding into the DeepSeek-V4-Flash pipeline via branch-aware causal verification, temporary state isolation, and accepted-path state refresh, keeping verification and compressed-state updates consistent across branches. Across budgets D=5 to D=8, batch sizes 1 to 64, and three datasets (GSM8K, MBPP, ShareGPT), tree speculation achieves a higher accepted lengt

---

### [137] ISA-Bench: A Benchmark for Computational Reasoning Across Instruction Set Architectures

**链接**: https://arxiv.org/abs/2609.22878
**作者**: Aditya Pola, Arkaprava Majumdar, Vineeth N. Balasubramanian
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model code generation benchmarks primarily evaluate well-resourced languages like Python and Java, where models benefit from abundant training data. They provide limited evidence about reasoning in unfamiliar computational models: deriving arithmetic from a single subtract instruction, coordinating parallel programs across communicating nodes, or wiring logic gates into circuits. We present ISA-Bench, a benchmark of programming games with constrained instruction sets. For each game we provide a full execution stack (parser, VM, and verifier), enabling automated evaluation with structured feedback for iterative refinement. Reasoning models achieve higher average solve rates than code-specialized and general-purpose models, but unfamiliar syntax remains a major source of failure. Models solve more tasks with iterative feedback, though the gains vary substantially across architectures. We introduce a reasoning--execution gap (REG) analysis that reveals a recurring disconnec

---

### [138] AgentBetta: Verification-Driven Adaptive Configuration of an AI Nano-Agent through Selective Expansion and Verified Contraction

**链接**: https://arxiv.org/abs/2609.23512
**作者**: Md. Ashraful Babu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are typically deployed with predefined configurations, although the required model capability, context, tools, permissions, memory, and computational resources can vary substantially across tasks. This study develops and evaluates AgentBetta, an adaptive AI Nano-Agent framework that represents these factors as an executable configuration and updates them through verification-driven diagnosis, selective expansion, and verification-based counterfactual contraction. The evaluation distinguishes controlled mechanism validation from external agent comparisons. On the AB-ConfigBench benchmark, AgentBetta achieved 91.38% verified success while reducing median context allocation from 64,000 to 8,000 context characters and median tool exposure from five tools to zero compared with the fully provisioned configuration. The configuration-deficiency diagnosis achieved a macro-F1 score of 0.819 with precision of 1.000 across the evaluated dimensions, and selective expansi

---

### [139] LLMs Anchor on Chief Complaint and Fail to Integrate Evidence in Sequential Clinical Triage

**链接**: https://arxiv.org/abs/2609.22904
**作者**: Dipankar Srirag, Haokai Zhao, Ashutosh Kumar, Eleanor Hopper, Michael Dalton, Quoc Dung Nguyen 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Triage in the emergency department (ED) is a sequential decision process that unfolds turn by turn. Existing evaluations of large language models (LLMs) for triage use completed retrospective records and report performance close to that of physicians. We implement a methodology for evaluating LLMs on sequential triage, the task of predicting a triage acuity label from a growing prefix of a nurse-patient conversation. We evaluate six LLMs at five sequential checkpoints on two corpora: 425 LLM-generated (SIMULATED) and 50 physician-authored (CLINICIAN) conversations, both labelled under the Emergency Severity Index (ESI). Every model, measured by quadratic weighted kappa (QWK), degrades from moderate-to-substantial agreement on completed records to fair-to-moderate agreement at every sequential checkpoint. Controlled perturbations show that the label at every checkpoint is anchored on the chief complaint exchanges, and prompting interventions fail to lift this plateau. Models extract cli

---

### [140] Connecting the Dots in Agentic AI Security: A Cross-Dimensional Threat Taxonomy, Evaluation Maturity, and Open Challenges

**链接**: https://arxiv.org/abs/2609.23894
**作者**: Heewon Baek, Alsharif Abuadbba, Kristen Moore, Hyoungshick Kim, Surya Nepal
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic AI extends LLM security beyond generated content to persistent state, autonomous actions, tool use, and interactions with humans and other agents. Existing threat classifications often emphasize individual dimensions, obscuring connections among entry points, affected components, and security consequences. The known threat landscape also differs from the coverage demonstrated by empirical research. Through a structured review of 66 studies published from 2022 to 2026, we introduce T={S, B, P, A}, a cross-dimensional representation linking affected functional or system surfaces {S}, interaction or trust boundaries {B}, violated security properties {P}, and empirically examined architectures {A}. We analyze 22 artifact-backed red-teaming studies and 11 representative security benchmarks to characterize empirical coverage and evaluation maturity. Within the selected studies, evidence concentrates on prompt/reasoning, memory, and tool-mediated attacks, predominantly in single-agent

---

### [141] H-Spec: Parallel Speculative Decoding Without a Drafter-Side KV Cache

**链接**: https://arxiv.org/abs/2609.24197
**作者**: Weifan Jiang, Krishna Teja Chitty-Venkata, Megan Flynn, Reed Meyerson, Zhenting Qi, Tianyu Wu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding losslessly accelerates large language model inference by having a lightweight draft model predict future tokens for verification by the target model. Recent block diffusion drafters further reduce drafting latency by predicting multiple tokens in parallel. However, existing block drafters project target hidden states at every input position into a separate drafter-side KV cache, incurring per-request memory and KV-write overhead that grow with concurrency; directly reusing target KVs in place removes this cache but fails to sustain draft quality throughout the block. We propose a hybrid target-context injection method that complements direct target KV reuse with target hidden states only at the last input position, requiring no separate drafter-side KV cache. Building on this design, we propose H-Spec, a hybrid Mamba-attention parallel drafter that consumes the two target-context sources through complementary modules. Mamba modules are initialized with projected la

---

### [142] GRACE: Grounded Adversarial Reasoning over Canadian Law

**链接**: https://arxiv.org/abs/2609.23726
**作者**: Jiakang Xu, Wantong Huo, Udom Silparcha and Jonathan H. Chan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have shown strong performance across a range of legal tasks, but existing benchmarks rarely evaluate the ability to take and defend a legal position, reason under incomplete information, or synthesize multiple statutory provisions. This gap is particularly pronounced for Canadian law, which remains underrepresented in legal NLP. We introduce GRACE (Grounded Reasoning Adversarial Canadian LEgal examples), a dataset of 1,915 question-reasoning-answer instances grounded in Canadian federal legislation. GRACE covers three reasoning modes: adversarial advocacy, uncertainty, and applied reasoning. We develop a pipeline that partitions raw statutory text, generates scenario-based questions and reasoning, and filters examples through model-free citation verification and LLM-based quality auditing. As a proof of concept, we fine-tune CLeAR-4B (Canadian Legal Adversarial Reasoning), a lightweight model for grounded legal reasoning, and evaluate it against the unmodified Qwe

---

### [143] Beyond Single-Model Injection: A Threat Model and Defense Architecture for Prompt Injection in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.22949
**作者**: Rudrendu Kumar Paul, Sourav Nandy
**来源**: cs.CR cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing prompt injection research focuses on single-model chatbot scenarios, where an attacker manipulates one LLM through crafted input. Multi-agent systems amplify this threat through three mechanisms absent from single-model settings: inter-agent message passing creates injection channels invisible to perimeter defenses, shared tool access enables privilege escalation across agent boundaries, and trust propagation allows a compromised agent to influence upstream orchestrators. We construct a threat model enumerating 14 attack vectors across four categories: direct injection via user input (3 vectors), indirect injection via tool outputs (4 vectors), inter-agent injection via message passing (4 vectors), and cascading injection through orchestrator manipulation (3 vectors). Testing all 14 vectors against a 6-agent production-representative system, we find that 67% of agents are vulnerable to at least one scope violation even with system-prompt-level guardrails, and indirect injectio

---

### [144] From Bits to Beliefs: Recoverable Semantic Fingerprints for Black-Box Verification of Large Language Models

**链接**: https://arxiv.org/abs/2609.24084
**作者**: Jiaxin Hong, Yuxin Peng, Hongyao Yu, Hao Fang, Shuoyang Sun, Bin Chen
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight large language models (LLMs) can be copied, modified, and redeployed behind black-box APIs, making post-release ownership verification difficult. Existing black-box fingerprints often rely on secret query-key pairs that reproduce predefined responses, and can therefore be easily disrupted by fine-tuning, pruning, quantization, model merging, and serving-time prompt changes. We propose SimPrint, a recoverable semantic fingerprinting framework for black-box LLM ownership verification. Rather than relying on isolated exact matches, SimPrint encodes a private owner signature into a coded semantic fingerprint domain, distributing ownership evidence across natural binary question-answering probes. It implants only base-deviating probes through a low-interference batch update that preserves the original model behavior, and later recovers the signature by parsing suspect-model responses into reliable bits or erasures with an error-correcting recovery mechanism. Because verification

---

### [145] Beyond Similarity: Coverage-Aware Prompt Selection for Time Series Forecasting with LLMs

**链接**: https://arxiv.org/abs/2609.22977
**作者**: Daeun Ji, Minkyoung Kim, Dongkuk Kim, Yohan Lee, Beomsoo Kim, Beakcheol Jang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Similarity-based retrieval is the dominant rule for conditioning large language models (LLMs) in in-context learning, retrieval-augmented generation, and prompt-based time series forecasting. The rule concentrates on near-duplicate candidates, an issue that has motivated diversity-aware retrieval but remains unexamined in other retrieval-conditioned pipelines. We study this issue using prompt-based time series forecasting as a test bed, where a learned prompt pool is retrieved by similarity. Dominant methods in this setting retrieve top-K entries by cosine similarity without redundancy control, producing a bias toward dominant temporal patterns while overlooking rare but informative events. We propose CASP-LLM, a coverage-aware semantic prompting framework that addresses this prompt selection bias by combining usage-tracking and saturating-gate techniques into a coverage regularizer that adds no learnable parameters. On six long-term benchmarks and the M4 short-term benchmark, CASP-LLM

---

### [146] RS-Claw-Evolution: Environment-Feedback-Driven Evolution for Lightweight Remote Sensing Agents in Long-Horizon Tasks

**链接**: https://arxiv.org/abs/2609.22258
**作者**: Kai Ouyang, Dongyang Hou, Liangtian Liu, Zeyuan Wang, Ziyu Li, Chengfu Liu 等 (10 人)
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-driven remote sensing (RS) agents offer a promising approach to automating geospatial analysis. However, lightweight RS agents based on compact language models struggle with multi-step interactive tasks due to loss of long-horizon states, inefficient environmental feedback utilization, and sparse optimization signals. We propose RS-Claw-Evolution, an environment-feedback-driven framework that progressively improves lightweight agents through three stages. Interaction evolution uses executable code to control observations, maintain intermediate states, and reduce context redundancy. Experience evolution combines failure-aware trajectory generation with error-turn masking to learn from informative failure-recovery experiences without imitating faulty actions. Decision evolution uses reinforcement learning with multi-dimensional environment rewards and turn-level advantage protection to optimize tool-use behaviors and improve credit assignment in long sequences. On Ea

---

### [147] Error-Supervised Synthetic Learner Writing for Automated Essay Scoring

**链接**: https://arxiv.org/abs/2609.23573
**作者**: Duy Anh Nguyen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic essays can help reduce dependence on human-written data in Automated Essay Scoring (AES). However, they often lack realistic errors, limiting their ability to represent authentic human writing, particularly when the target texts are intended to resemble those produced by language learners. In this study, we present a simple approach that introduces error supervision into synthetic essay generation. Specifically, we fine-tune an LLM generator on error-annotated texts of the kind commonly used in Grammatical Error Detection (GED). To assess the utility of the proposed approach, we fine-tune and evaluate AES scorers under three data conditions: authentic essays, synthetic essays generated conventionally, and synthetic essays generated using our proposed approach. The results show that in the larger-data settings, the proposed approach outperforms the conventional synthetic baseline in 11 out of 12 dataset-metric comparisons, with performance in some cases approaching that of mod

---

### [148] Semantic Candidate-Job Matching: A Comparative Evaluation of Dense Embedding Models in Hybrid Retrieval

**链接**: https://arxiv.org/abs/2609.23307
**作者**: Sai Yashwant, Siddhartha Jain, Anurag Dubey, Samaroha Chatterjee, Gantala Thulsiram
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents a comparative evaluation of dense embedding models for semantic candidate-job matching in high-volume staffing workflows. Incoming job descriptions are converted into structured English search text and language-specific keywords through LLM-based parsing, and candidate profiles are indexed as semantically enriched resume representations. We evaluate EmbeddingGemma (base) against EmbeddingGemma fine-tuned with Cached Multiple Negatives Ranking Loss (MNRL) within a unified hybrid retrieval pipeline that fuses vector similarity and full-text relevance via reciprocal rank fusion (RRF), and benchmark both against the MPNet model on a batch comparative evaluation dataset scored through the deployed job-candidate matching scoring pipeline. We further document, with mathematical detail, the broader set of contrastive fine-tuning objectives considered during model development (including AnglE/CoSENT-style refinement) and the empirical rationale for retaining Cached-MNRL-only

---

### [149] Pretrained Persona Mixture Models and Tandem Models for Human Simulation

**链接**: https://arxiv.org/abs/2609.22607
**作者**: Minwoo Kang, T\'ea Wright, Seun Eisape, Ayush Raj, Suhong Moon, Joseph Suh 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We argue here that the current dominant practice in LLM human simulation: prompting instruction-tuned assistant language models to role-play personas, is inaccurate and produces stereotyped predictions (lacking natural diversity). It has previously been shown that LLMs can be bound to personas using naturalistic, freetext dialog avoiding stereotyping. Here we show that binding can also be achieved using short, individual samples of dialog from specific people. Demographics can be added later without negative effects by simply querying the model. We use the term Persona Mixture Models (PMMs) for well-calibrated human models, currently realized as pretrained base models. We show that PMMs produce more accurate predictions than instruction-tuned models and retain more of the lexical, semantic, and pragmatic diversity found in human dialog. We measure realism and diversity of LLMs simulating human interlocutors across a diverse set of corpora spanning open-domain text, human-AI chat, and t

---

### [150] Math2Visual-X: A Modular Framework for Pedagogically Aligned Lower-Primary Math Visuals Generation

**链接**: https://arxiv.org/abs/2609.22647
**作者**: H.D.E. Maduranga, S. K. Munasinghe, K. P. T. I. Weerasekara, Surangika Ranathunga, Nisansa de Silva
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual representations can help lower-primary learners understand Math Word Problems, but generating classroom-usable visuals remains difficult. Existing symbolic systems are controllable but limited in coverage, while end-to-end text-to-image systems often fail to satisfy exact mathematical constraints. This paper presents a symbolic visual generation framework for lower-primary MWP generation with broader problem coverage and more scalable asset generation. The framework includes an LLM-based routing layer, three worksheet-oriented generation modules, and two fallback mechanisms for open-world SVG asset acquisition. A human evaluation comparing Math2Visual-X with Stable Diffusion XL, Nano Banana, and GPT Image showed that the proposed method achieved the strongest overall performance. The results indicate that the framework offers a scalable and pedagogically grounded approach for automatic MWP visual generation.

---

### [151] How Many Pixels Is a Digit Worth? Place-Aware Coordinate Entropy for GUI Agent Confidence Estimation

**链接**: https://arxiv.org/abs/2609.24277
**作者**: Yunxiang Li, Xixin Wu, Helen Meng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> GUI agents predict click coordinates as digit-token sequences, but standard text-LLM confidence estimation methods rank correct clicks from wrong ones only weakly. GUI-specific alternatives use K samples or new supervision, but still leave room for improvement. We trace part of this to place-value asymmetry: bounding-box correctness often makes higher-place digits more important than lower-place digits, so uniform aggregation weakens the signal that determines correctness. The fix is to weight each digit's Shannon entropy by its place value. We call this Place-Aware Coordinate Entropy (PACE). Across fixed-scale agents on ScreenSpot-Pro and ScreenSpot-v2, PACE wins both AUROC and selective accuracy on all primary comparisons in a single forward pass, matching or outperforming K-sample baselines at a fraction of the cost. PACE provides a per-click confidence estimate that turns coordinate-token internals into a practical confidence signal for GUI agent deployment.

---

### [152] Preserving What Matters: Semantic Scaffolds Beyond Saturation in Summarization Evaluation

**链接**: https://arxiv.org/abs/2609.22603
**作者**: Nikhil Reddy Pottanigari, Ramin Fahimi, Noah Bolger, Sepideh Kharaghani, Ying Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Summarization ships in countless production systems, making model selection a routine decision that depends on measuring summary quality. Existing metrics struggle to support this: ROUGE captures only surface overlap, while LLM-as-judge scores saturate to near-identical values that fail to rank models effectively. We observe this saturation across three public datasets, two proprietary datasets, and multilingual settings. Motivated by this, we introduce Semantic Scaffold, an evaluation framework that extracts a hierarchical representation of facts, questions, and entity attributes from a source text, labeling each as a main point or supporting detail, and reusing this structure as a fixed reference for scoring summaries. From this representation, we derive three diagnostic metrics: Fact Preservation Score (FPS), Question Preservation Score (QPS), and Entity Preservation Score (EPS), designed to reward the preservation of essential information while penalizing detail overload, and posit

---

### [153] When Residualization Helps an Audit: Format Effects, Slice Gains, and Their Limits

**链接**: https://arxiv.org/abs/2609.24194
**作者**: Daein Weon, Dongho Kang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation scores used around LLM systems -- including reward models, rerankers, and LLM judges -- can track surface form instead of the quality they claim to measure. When presented with a terse correct solution and a commented buggy solution for the same MBPP problem, a public preference reward model selects the correct one no better than a coin flip (0.507). Subtracting the predictable surface component from such scores is increasingly common, but removal alone does not yield a more valid measurement: the removed component may carry construct-relevant signal, and residualization cannot tell which is which. Under designed interventions -- unit-test labels with comment-only edits -- residualization attenuates the reward model's format effects by about 0.12 on both correct and buggy code, while the correct-versus-buggy margins move by less than 0.01. In observational NLI and QA settings, we freeze a held-out replication before scoring and re-evaluate it using labels from disjoint annot

---

### [154] FinInteract: Benchmarking Clarification and Intent Integration in Ambiguous Financial Question Answering

**链接**: https://arxiv.org/abs/2609.24002
**作者**: Xinyu Wang and Tung Sum Thomas Kwok and Zhenghan Tai and Guang Cheng
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly answer financial questions by searching regulatory filings. Such questions are often deceptively under-specified: Meta Platforms' "operating income" is $46.75B consolidated but $62.87B for the Family of Apps segment, and each reading is exactly verifiable against the filing. A capable agent should recognize the ambiguity and ask, rather than commit to a plausible but unintended reading. Existing financial benchmarks cannot measure this, because one gold answer per question cannot separate agents that resolve the ambiguity from those that guess the common reading, a blind spot we call the single-gold illusion. We release FinInteract, a bilingual (English/Chinese) benchmark of 173 instances that pairs each question with a default and an intended interpretation across a five-category ambiguity taxonomy, and grades whether an agent elicits the right clarification and then integrates it. Re-grading identical outputs against the default rather than th

---

### [155] The Role of AI in Online Reviews

**链接**: https://arxiv.org/abs/2609.22198
**作者**: Valeria Lerman, Oren Rigbi, Yaniv Dover
**来源**: cs.CL cs.AI cs.HC cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid adoption of large language models (LLMs) creates new opportunities for strategic content generation on online platforms, including potentially harmful forms of manipulation that may undermine platform effectiveness and reshape platform dynamics. However, measuring such activity is difficult because AI-generated content is rarely directly observable. We introduce an empirical approach that leverages discrete LLM supply shocks - abrupt changes in model prices and capabilities, and contrasts verified with non-verified reviews to identify changes in platform activity associated with generative AI supply improvements. We apply this approach to more than 13 million reviews from Trustpilot, one of the leading online platforms for business reviews. A robust finding is that following LLM supply shocks, unverified reviews shift toward greater negativity: more 1-stars, fewer 5-stars, and lower ratings, with effects driven primarily by new model releases and concentrated among firms with

---

### [156] iSDFT: Information-Proximal Self-Distillation for Continual Learning in LLMs

**链接**: https://arxiv.org/abs/2609.24646
**作者**: Ahmed Khaled Khamis, Xiaotong Ji, Hassan Jaber, Rasul Tutunov, Matthieu Zimmer, Jun Wang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy self-distillation fine-tuning (SDFT) learns new skills from demonstrations while reducing forgetting, but it always distils toward the full demonstration-conditioned teacher. This fixes teacher influence at the full-teacher endpoint, providing no control over how much demonstration information should be transferred at each prediction state. We introduce Information-Proximal SDFT (iSDFT), which instead treats the teacher as a budgeted source of information. At each token, iSDFT selects the distribution closest to the current student that satisfies a prescribed teacher-information constraint, yielding a closed-form exponential target with a locally determined tilt. To control cumulative drift, we further anchor the student to its frozen base policy. Across four heterogeneous LLM backbones and two specialisation tasks, iSDFT improves vanilla SDFT in 7 of 8 model-task settings and matches it in the remaining one. It also provides tighter retention on the original SDFT benchmark s

---

### [157] SelfOp: An Optimization Algorithm for Self-Improving Security Agents

**链接**: https://arxiv.org/abs/2609.22792
**作者**: Saad Ullah, Yigitcan Kaya, Christopher Kruegel, Giovanni Vigna, Gianluca Stringhini
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used for security tasks: vulnerability discovery, exploit reproduction, and patch generation. Improving them at the model level demands expert demonstrations or computable rewards, which security tasks rarely offer: traces are costly, failures hard to diagnose, rewards sparse, and non-computable. Efforts thus shift to the harness and context, but manual tuning needs task-specific expertise and scales poorly, while automated methods rely on scarce ground truth, stronger optimizer models, or unguided propose-and-evaluate loops that reduce to costly trial and error. We introduce SelfOp, an algorithm that automatically improves a frozen security agent's task context (instructions, skills, and reference documents), without modifying its execution harness and model weights. SelfOp casts context optimization as chain-rule-inspired textual gradient descent: from a single instance's outcome, it propagates error signals backward through the evaluator, the agent's traj

---

### [158] ORION-CMR: On-scanner Reporting with Integrated Foundation Model for End-to-End Cardiac MRI Analysis and Interpretation

**链接**: https://arxiv.org/abs/2609.23950
**作者**: Omer Burak Demirel, Kelly K. Horst, Alessio Perazzolo, Elisa Bruno, Kenan Kaya, Rongzhen Ouyang 等 (10 人)
**来源**: eess.IV cs.CV cs.LG physics.med-ph
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cardiovascular magnetic resonance (CMR) provides comprehensive cardiac assessment but remains underutilized because of the complexity of acquisition, post-processing, and interpretation. Existing artificial intelligence (AI) methods address isolated tasks, limiting clinical integration. We present ORION-CMR (On-scanner Reporting with Integrated fOunda-tioN Model), the first clinically evaluated scanner-native end-to-end CMR foundation model. Pretrained on 12,896,733 CMR images from 9,258 studies, ORION-CMR performs sequence classification, ventricular function assessment, late gadolinium enhancement (LGE) detection, binary and multiclass disease classification, and local large language model-based report generation in approximately 90 seconds. The framework. was evaluated on public benchmarks and clinically validated in a multi-vendor cohort of 68 subjects with normal examinations, congenital heart disease, dilated cardiomyopathy, and myocardial infarction. ORION-CMR outperformed super

---

### [159] Evaluating Decision Models for Text Annotation in Computational Social Science

**链接**: https://arxiv.org/abs/2609.24574
**作者**: Hazem Ibrahim and Yasir Zaki
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computational social science increasingly relies on large language models for text annotation, and the validity of published findings now rests on the labels generated by such models. Decision models, a new model class built for categorical question answering, answer typed questions with a choice, a probability distribution over the label set, and a confidence score rather than free text, at a small fraction of frontier inference prices. Whether their answers are accurate, and whether that stated confidence can be trusted on social science constructs, are unknown. Here, we mirror the evaluation of Ziems et al. (2024) on 18 computational social science classification tasks (7,977 items), comparing the first commercial decision model and two open-weight counterparts against 19 frontier and open-weight language models under the same zero-shot protocol. The decision model trails the per-task best LLM on 14 of 15 evaluation tasks, with a median deficit of 11.6 macro-F1 points, at a median 4

---

### [160] From Capability to Assurance in Autonomous Penetration-Testing Harnesses: A Framework and Reference Implementation

**链接**: https://arxiv.org/abs/2609.22664
**作者**: Joas Antonio dos Santos Barbosa
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on large language model agents for penetration testing is evaluated almost entirely by capability: whether the agent captures a flag or reproduces a proof of concept. That metric suits a benchmark but is silent on the properties that decide whether an autonomous agent can be used in an authorized engagement: whether a reported finding is true, whether the agent stayed inside its authorized scope, and whether an operator can audit what it did. We call these assurance properties and argue that they belong to the harness, the runtime wrapping the model, and can be enforced in code. This paper makes three contributions. First, we define a framework of five assurance properties (evidence grounding, non destructive claim reduction, computed severity, enforced authorization, and tamper evident accountability), each with a formal model and an explicit acceptance test, connected to prior work in capability based security, tamper evident logging, and software provenance. Second, we posi

---

### [161] Self-Healing Harness for Runtime Oversight of Agent Self-Modification

**链接**: https://arxiv.org/abs/2609.24130
**作者**: Sina Tayebati, Divake Kumar, Nastaran Darabi, Ranganath Krishnan, Amit Ranjan Trivedi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can change their own future behavior, raising a basic control question of which self-generated changes should be allowed to persist. We formulate this as admission control for self-modification. The agent may propose changes to its operating instructions, while an external runtime gate controls persistence. We implement this principle as a model-agnostic self-healing harness that runs a Detect, Notice, Heal, Validate loop around an otherwise unmodified agent. The agent authors candidate behavioral rules in an external workspace, where they receive provisional execution authority during evaluation and acquire persistent cross-episode authority only after measured improvement on the triggering failure without regression beyond a fixed margin on protected cases. Replay provides matched evidence when available, forward trials provide a weaker fallback, and a corpus-level guard re-tests the accumulated active rule set. Across 16 matched Baseline and Harness runs spanning AppWorld

---

### [162] IntLawNER: A Named Entity Recognition Dataset and Benchmark in International Law

**链接**: https://arxiv.org/abs/2609.22529
**作者**: Genis Skura and Roland Bouffanais and Didier Wernli
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> International law provides the normative framework through which states coordinate action, regulate armed conflict, and protect human rights, yet its texts remain without token-level named entity recognition (NER) resources. We introduce IntLawNER, a NER dataset and benchmark for codified sources of international law, covering 2,987 gold-annotated sentences and 8,094 entity spans from International Court of Justice (ICJ) decisions, UN Security Council resolutions, and European Court of Human Rights (ECtHR) judgments, annotated with seven institution-specific entity types. We construct IntLawNER with a cost-effective hybrid algorithmic-agentic pipeline that reduces 468k source sentences to a compact annotation set through candidate retrieval, LLM-based vetting, and human review, with 89.6% of gold spans accepted unchanged from the silver layer. However, the silver-to-gold analysis reveals that human-machine aggregate agreement metrics can be misleading in domain-specific NER: Cohen's ka

---

### [163] NLPCC 2026 Task 10: Citation-Level Faithfulness Verification with DeBERTa Ensembles and Class-Wise Calibration

**链接**: https://arxiv.org/abs/2609.22774
**作者**: Yanling Li, Zirui Li, Mingyu Wan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents our system for Track 2 of the NLPCC 2026 Shared Task 10 on citation-level faithfulness in AI-assisted scientific reporting. Given an atomic scientific claim and the structured full text of its cited paper, the task requires both a four-way relation label and up to three evidence paragraph identifiers. The label head ensembles a paragraph-aware cross-encoder with a document-level DeBERTa-large classifier, followed by class-wise decision calibration. Probability-level fusion is motivated by an out-of-fold tendency to over-predict Topical Match. The evidence head combines paragraph scores from top-20 and top-30 joint models with BM25 scores. The system runs fully offline without external retrieval or LLM prompting. On the final leaderboard, our system achieved 82.9898 overall (89.5491 Macro-F1 and 76.4305 Joint@3), ranking second in Track 2. Ablations and error analysis show that model complementarity and calibration drive the label gains. Gold-evidence inference chang

---

### [164] Mitigating Entity Type Confusion in Cross-Domain NER via Multidimensional Quantification and Reasoning Enhancement

**链接**: https://arxiv.org/abs/2609.24357
**作者**: Jingyu Wang and Shijie Wu and Fusheng Jin
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-domain Named Entity Recognition (CD-NER) aims to transfer the rich knowledge in the source domain to the target domain. Recent studies adopting decomposition or generation paradigms have achieved significant performance improvements, demonstrating high accuracy in entity span detection. However, during entity type classification, models severely suffer from entity type confusion, the erroneous tendency that models classify entities of one type in the text as another similar but incorrect type. To address this issue, we first propose a Multidimensional Confusion Quantification Model (MCQM) that quantifies a model's confusion extent between entity types from three dimensions: source-target hierarchy analysis, semantic similarity analysis, and explicit data evaluation. Moreover, we propose the Progressive Bidirectional Reasoning Chain (PBRC). PBRC leverages the source-target hierarchy and confusion analysis from the MCQM to prompt the LLM to generate two-stage reasoning information.

---

### [165] URA-NER: A Unified Retrieval-Augmented Framework with Retrieval Alignment and Uncertainty Reduction for Low-Resource NER

**链接**: https://arxiv.org/abs/2609.24372
**作者**: Jingyu Wang and Shijie Wu and Fusheng Jin
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context learning (ICL) based on large language models (LLMs) has shown promising potential in alleviating performance bottlenecks caused by the limited availability of annotated data in Named Entity Recognition (NER). However, existing methods still face issues of retrieval misalignment and generation uncertainty, making their performance heavily dependent on the LLM's capabilities. As the parameter scale of LLMs decreases, their performance in few-shot settings deteriorates significantly. In this paper, we propose a novel unified retrieval-augmented framework, URA-NER, including three key components: Progressive Granularity Retrieval (PGR), Model-aware Representation Enhancement (MaRE), and Reason-aware Knowledge Verification. PGR is a two-stage retrieval mechanism that achieves stage alignment. It first retrieves demonstrations for span detection based on the query's global semantics, and then for type classification based on the specific entity context, providing fine-grained loc

---

### [166] OSCAR: Order-aware Scoring and Calibration for AI Rankings

**链接**: https://arxiv.org/abs/2609.24128
**作者**: You Liu, Yue Liu, Quanchao Lu, Nick Shipilov
**来源**: stat.ML cs.LG stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Judge-specific sensitivity is useful for aggregating pairwise LLM evaluations, but its interpretation depends on which systematic presentation effects the ranking model includes. We introduce OSCAR, an order-aware framework for scoring and calibrating AI rankings, and study position as one such effect. In released judgments from 18 evaluators, the all-response A-minus-B score difference ranges from $-63.11$ to $98.31$ percentage points. Matching question text, response texts, candidate identities, and judge within the released table gives an overall difference of $24.22$ points (95% interval $[22.90,25.54]$), conditional on the released text mapping. A controlled calculation isolates the potential consequence: with true sensitivity fixed at one, omitting a position intercept of four reduces the population-optimal slope to $0.0771$. We extend sensitivity-based ranking with judge-specific position, length, and family terms, characterize local omission-induced displacement and an identifi

---

### [167] Re:CAP - Auditing Retrieval Coverage in Production RAG Pipelines

**链接**: https://arxiv.org/abs/2609.24122
**作者**: Aviral Joshi, Hanoz Bhathena, Max Nelson, Saket Sharma
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) is hard to monitor in production: exhaustive relevance labels do not exist for non-stationary multi-million-passage corpora that re-index in real time. As a result, retrieval quality is generally understudied and often deprioritised in favour of generation-oriented metrics. In this work, we propose auditing retrieval coverage by probing for evidence of missing documents rather than enumerating every relevant one. Our method Re:CAP (REtrieval Coverage Audit by iterative Probing) is a reference-free audit loop applied to a deployed RAG pipeline's initial answer and retrieved context: it identifies the topics already covered, generates probing questions for plausibly missing topics, retrieves candidate documents, and applies an LLM-as-judge to retain only those that introduce previously-unretrieved information. On four public benchmarks, Re:CAP recovers 9-29% of gold labels that flat BM25 top-500 cannot reach, rising to 48% on TREC-COVID. On MuSiQue Re

---

### [168] Does the Truthfulness Signal Survive Code-Mixing? Probing Hidden States for Hallucination Detection in Hinglish

**链接**: https://arxiv.org/abs/2609.22138
**作者**: Tanveer Singh (Plaksha University)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hidden-state hallucination probing - training a linear classifier on an LLM's internal activations to detect whether a generated answer is faithful to the input - is an active area of 2026 research, with recent work reporting 0.90-1.00 AUROC across several benchmarks and languages. However, none of this work has tested probes on code-mixed input, despite the fact that a huge population of chatbot users write in Hindi-English code-mixed text ("Hinglish"). We address this gap directly: does a hallucination probe trained on clean-language hidden states transfer to Hinglish, or does the signal degrade under code-mixing? We construct a 5,674-item Hindi/English/Hinglish QA benchmark, generate and label 17,022 model responses across three open-weight 7-8B LLMs (Qwen2.5-7B, Mistral-7B, Llama-3.1-8B), extract per-layer hidden states at two token positions, and train linear and MLP probes for in-distribution detection and cross-lingual transfer. We find that the hallucination signal survives cod

---

### [169] Diagnose, Then Repair: A Two-Stage MQM-Guided Post-Editing Framework for Domain-Specific Machine Translation

**链接**: https://arxiv.org/abs/2609.22793
**作者**: Ji Hun Wang, Siyu Wu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based machine translation evaluation can closely match human judgments, but in practice it remains largely diagnostic, with the signals rarely translating into direct quality improvements under real production constraints. We propose a two-stage, evaluator-guided automatic post-editing framework that turns MQM-style evaluation into targeted repairs: a retrieval-augmented LLM evaluator outputs structured, span-level MQM diagnoses under an explicit edit contract, and a separate LLM post-editor applies minimal edits restricted to those diagnoses. This separation improves controllability and reduces paraphrastic drift compared to one-stage "judge-and-refine" baselines. In a systematic study involving seven LLMs spanning three model providers and seven languages, our best configuration consistently improves both COMET-22 and COMETKiwi scores over one-stage post-edit methods, while the evaluator's error spans and severities show strong agreement with human MQM annotations and human edito

---

### [170] Guiding the coarse levels of semantic IDs makes the fine levels learnable

**链接**: https://arxiv.org/abs/2609.22227
**作者**: Bin Wang, Zhengyu Zhang
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative retrieval represents each item by a short Semantic ID and casts recommendation as autoregressive generation of that sequence. Because the tokenizer is trained independently to reconstruct an item embedding, its codes are aligned with neither the downstream LLM nor the end task. Nearly every SID system therefore spends extra effort to bridge this gap--alignment corpora, reasoning/RL, or per-token encoders to make codes legible, or learned tokenizer supervision to make them task-aware--yet the recovered meaning is content-derived and may not be the meaning the task needs. We introduce Guided SID, which instead makes the levels that matter most meaningful by construction: we force the coarse RQ-VAE levels to encode a predefined categorical attribute--chosen to be text-grounded (hence legible to the LLM) and task-relevant--by deterministic supervised index assignment (overriding nearest-neighbor selection with the attribute label) while keeping the codebooks learnable (they stil

---

### [171] PINNForge: Execution-Grounded Evolutionary Design of Physics-Informed Neural Networks for PDE Solving via Large Language Models

**链接**: https://arxiv.org/abs/2609.23023
**作者**: Mingyang Yu, Xu Yang, Jun Zhang, Xiaolong Wang, Jing Xu, and Keqian Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physics-informed neural networks (PINNs) require coordinated choices over network representation, sampling, loss construction, and optimization, while effective configurations often vary substantially across partial differential equations (PDEs). Existing automated PINN design methods can search candidate configurations, but information revealed during actual training is still used mainly for evaluation rather than to improve subsequent design, leading to repeated trial-and-error and inefficient use of training budget. We propose PINNsForge, an LLM-driven evolutionary framework for execution-feedback-based automated PINN design. PINNsForge generates diverse candidate configurations from PDE-related prior knowledge, evaluates them through actual training, and feeds high-performing designs together with accumulated execution evidence back to the LLM. Guided by observed optimization behavior, the LLM then refines, recombines, and explores coupled PINN design components, forming a continua

---

### [172] Canonical Procedural Actions: An Auditable Annotation Protocol for Tool-Use Agent Traces

**链接**: https://arxiv.org/abs/2609.24264
**作者**: Songqi Li, Dongqing Li, Zheqiao Cheng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-use agent traces identify messages and API calls, but procedural analyses also need explicit units of action and inspectable links to their evidence. We present Canonical Procedural Actions (CPAs), an annotation protocol that records a procedural function, its first agent-event anchor, the agent events that realize it, and separate contextual evidence. Multiple actions may share a message anchor without an inferred within-message order. A retail case study produces a versioned 24-entry codebook through open induction, recorded consolidation, and successive application audits. Two isolated LLM contexts annotate 32 trajectories disjoint from development at the trajectory level, producing 499 and 491 occurrences with anchor-label overlap A=0.982. Requiring identical context-event references reduces overlap to 0.798. These are structural repeatability measures, not semantic accuracy: 16 of 26 task IDs also occur in development, and historical tool payloads were truncated to 110 charac

---

### [173] Privacy Personalization Trade offs in LLMs: The Impact of Stylometric Signal Reduction on User-Specific Text Generation

**链接**: https://arxiv.org/abs/2609.22112
**作者**: Muhammed Nazmul Arefin, Omar Jamal Hammad
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated the ability to generate user-specific text with high stylistic fidelity. However, the personal data that enables such personalization frequently embeds demographic, cultural, and stylistic markers that raises concerns about stylometric re- identification. This paper investigates whether reducing identifiable stylistic signals affects personalization in text generation by LLMs. We introduce a controlled framework to isolate stylometric signals in LLM personalization using the LaMP-7 Twitter benchmark. Experiments on 250 sampled users compare two settings: paraphrasing conditioned on the original profile and paraphrasing conditioned on an anonymized converted profile in which demographic identifiers, cultural references, personal details, and informal linguistic cues have been systematically neutralized. Outputs are assessed by two independent LLM judges and a complementary human evaluation. Our pairwise evaluation shows that outputs conditi

---

### [174] Token Signatures of Code: Comparing Coding Behaviors Across Large Language Models

**链接**: https://arxiv.org/abs/2609.22097
**作者**: Junpeng Wang, Yuzhong Chen, Menghai Pan, Uday Singh Saini, Yiwei Cai
**来源**: cs.CL cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The evaluation of large language models (LLMs) on coding tasks has primarily focused on performance metrics such as pass@k. As LLMs continue to advance, many models now meet baseline performance requirements, reducing the discriminative power of performance-based evaluation alone. Yet a key question remains largely unexplored: how do LLMs differ in their coding behavior? We propose CLIC (Code Learning for Identification and Comparison), a visual analytics approach that characterizes LLM coding behavior through token-frequency analysis. CLIC represents each code sample as a feature vector of token frequencies and trains an interpretable decision tree to separate two LLMs' code sets. Beyond classification accuracy, we define two new metrics: robustness, which measures whether the two LLMs remain distinguishable as their most-discriminative tokens are progressively removed, and concentration, which measures whether the difference is driven by a few dominant tokens or spread across many. I

---

### [175] Pretraining of Medical Visual Encoders Toward Multi-modal Large Language Models

**链接**: https://arxiv.org/abs/2609.23860
**作者**: Tianyou Jiang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) commonly reuse visual encoders pretrained with CLIP, although the features of these ViTs are ultimately consumed by autoregressive LLMs. We refer to this mismatch as the semantic-interface gap and introduce MedMLIP, a framework that pretrains the visual encoder through report generation with a frozen LLM, while employing Local Relational Distillation (LRD) to preserve relationships among visual patches to avoid visual collapse. We pretrain MedMLIP on IU-Xray and Open-PMC-300K and evaluate the resulting encoders on VQA-RAD and SLAKE. Only the ViT is transferred, while the guiding LLM and projector are replaced, allowing us to assess cross-LLM transferability. Our cross-LLM transfer experiments demonstrate the value of pretraining visual encoders for their autoregressive LLM interface while trying to preserve more fine-grained visual information. Code and the pretrained model are available at https://github.com/SkyCol/MedMLIP

---

### [176] When the Agent Becomes the Kernel: A Systematization of Security on the Path to AI-Native Operating Systems

**链接**: https://arxiv.org/abs/2609.23700
**作者**: Li Zhang, Yang Sun, Jie Shi
**来源**: cs.CR cs.AI cs.OS
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are now privileged principals that take consequential actions: editing code repositories, operating inboxes, completing purchases. Their authority is kernel-grade, but it comes without what classical systems security requires: a trusted mediator interposed on every access. Operating-system vendors are now rebuilding the platform around this de-facto agent kernel, inheriting complete mediation as a design problem. We systematize the security of such systems around a single distinction: a crossing mediated over provenance admits a deterministic check, while one over content semantics does not. A trust-boundary taxonomy locates where mediation must occur and isolates the central mediation gap at two kinds of semantic judgment: distinguishing data from instruction in untrusted input, and an authorized action from an unauthorized one. We argue that this gap leaves an irreducible residual of undetected attacks wherever inputs and actions are not restricted in adva

---

### [177] EAVer: Long-Form Factuality Verification as an End-to-End Agentic Policy

**链接**: https://arxiv.org/abs/2609.22223
**作者**: Kening Zheng, Aoying Zheng, Zhigang Chang, Yazhi Guo, Miaotian Guo, Qingwei Zong 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-form factuality verification is commonly implemented as a static decompose-search-verify pipeline, with separately prompted modules processing claims and invoking external search. Treating claims independently makes LLM and search calls scale with claim count and causes repeated searches for overlapping evidence about related claims. We introduce EAVer, an End-to-end Agentic Verifier that learns to control the complete response-level verification workflow as a unified policy. EAVer groups semantically related claims, routes each group to direct verification or targeted search based on confidence, and keeps evidence returned by search in compact in-context memos for cross-claim reuse. To train this policy, we develop a privileged-teacher synthesis pipeline that converts gold claim annotations into executable multi-turn tool-interaction trajectories with live search rather than post-hoc rationales. Structural, label-alignment, tool-use, search-budget, and leakage checks yield 1,447 

---

### [178] Pinocchio: Fast Uncertainty Estimates for Black-Box Language Models

**链接**: https://arxiv.org/abs/2609.24881
**作者**: Kevin David Hayes, Arka Pal, Haosong Zhang, Tom Goldstein, Micah Goldblum
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In high-stakes decision-making applications of large language models (LLMs), practitioners require not only accurate LLMs but also uncertainty estimates for their predictions. Existing approaches to uncertainty estimation for LLMs require access to log-probabilities output by the model or require fine-tuning access. However, many industrial LLM products use closed-source API models, and many such API models like GPT do not return log-probabilities and may not allow fine-tuning. We introduce Pinocchio, an external calibrator that estimates the correctness of responses from black-box API models. Trained jointly on responses from seven LLMs, it achieves 0.862 AUROC predicting the correctness of held-out responses from those same models, and shows zero-shot transfer to thirteen unseen models across eight organizations. Our model needs only a single forward pass to generate an uncertainty estimate and requires no access to the target model's logits, weights, or internal states. A lightweigh

---

### [179] Directing large language models to follow the letter or spirit of the law

**链接**: https://arxiv.org/abs/2609.23083
**作者**: Peng Qian, Andrew Li, Sam Chen, Sonia K. Murthy, Yonatan Belinkov, Tomer D. Ullman
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The distinction between the spirit and letter of the law is a central issue across research and everyday life, and a growing concern for building safe, intelligent machines. What is this distinction based on, and how can we develop machines that follow the intention behind a rule? We used targeted adaptation that made large language models prioritize the spirit or letter of the law. With minimal modifications, our method significantly changed LLM behavior across diverse measures, novel vignettes, real-world scenarios, and influential legal cases. An analysis of model internals revealed a low-dimensional space with three interpretable dimensions matching a formal pre-specified framework for the geometry of legal concepts. These findings show how legal thought in LLMs may be organized and directed.

---

### [180] Deciphering the Babel of Play: A Human-AI Collaborative Approach for Large-Scale Cross-Language Analysis of Game Reviews

**链接**: https://arxiv.org/abs/2609.23104
**作者**: Zixiaofan Yang, Chang Xiao
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a large-scale cross-language analysis of game reviews using a human-AI collaborative framework that combines quantitative screening with multilingual large language models (LLMs). Starting from 17 million Steam reviews across 30 languages and 2,000 top-selling titles, we select 28 games with notable cross-language rating patterns. We then apply LLM-assisted content analysis to 442,162 reviews spanning 17 languages, with human researchers guiding codebook development and interpreting the results. Our findings reveal differences in both the aspects language communities prioritize and how they evaluate them, highlighting the roles of narrative expectations, game mechanics and stability, localization quality, cultural proximity, and perceptions of developers and publishers. We also identify rare cases of cross-language consensus. This work offers empirical insights into cross-cultural game evaluation and a scalable methodological approach to multilingual content analysis that pr

---

### [181] onPanda: Efficient Annotation of On-Policy Alignment Data for LLMs and Agents via Token-Level Correction

**链接**: https://arxiv.org/abs/2609.24983
**作者**: Lei Yang, Mengyin Liu, Jia Wang, Hangyu Guo, Liang Zhao, Zheng Ge 等 (10 人)
**来源**: cs.CL cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present onPanda, an interactive tool for efficiently annotating LLM alignment data and agent trajectories. onPanda adopts token-level correction as its core interaction: while reading a model response, the annotator locates the first inappropriate token and either picks a substitute from the model's candidate tokens or types the correct text via free-form editing. The system then truncates everything after that position and continues generation from the corrected prefix, repeating this locate-correct-continue loop until a satisfactory response is obtained. This mechanism lets annotators precisely steer model outputs at low cost: a small controlled study suggests that onPanda reduces median annotation time by 52% over manual post-editing. Since the vast majority of tokens in the final response are generated by the model itself, the resulting data largely preserves the model's sampling distribution and is well suited for constructing on-policy SFT and preference data. Furthermore, the

---

### [182] Some Dialects Are More Equal Than Others: Non-Prestigious Arabic Dialectal Bias in LLMs

**链接**: https://arxiv.org/abs/2609.23955
**作者**: Mai Mohamed Eida, Ryan Dolan, Paul de Nijs, Jonathan Dunn
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Previous work on Egyptian Arabic in NLP has focused largely on the prestigious Cairene Egyptian Arabic (CEA) dialect, resulting in a lack of representation for the less prestigious Sa'idi Egyptian Arabic (SEA) dialect both in LLM and resource development. Does this lack of representation influence an LLM's view of the acceptability of SEA (upstream), and does an upstream bias against SEA lead to worse performance (downstream)? We investigate the upstream effect of SEA dialectal features on LLM preferences in a Targeted Syntactic Evaluation (TSE) task which reveals a significant bias against SEA across multiple LLMs. We then analyze the effect of these same features on downstream model performance on MMLU benchmarks and show that models experience a degradation in performance when presented with SEA. This work highlights the need for further exploration on how sub-dialectal variation impacts language technologies.

---

### [183] Zero-Trust Authorization and Discovery for Enterprise MCP

**链接**: https://arxiv.org/abs/2609.22573
**作者**: Huan Li, Yuwei Wang, Srinivasan Manoharan
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents translate natural-language context, which may include attacker-controlled text, into privileged tool calls, so authorization must remain effective even when an agent is prompt-injected or adversarially steered. The Model Context Protocol (MCP) has become a widely adopted interface for this boundary, yet its official SDKs' authentication and authorization primitives fall short of enterprise zero-trust requirements, most acutely a dual-persona model in which one server must serve human users (corporate SSO) and automated agents (service-account credentials on a different header). We conduct a systematic gap analysis of six surveyed MCP SDKs (Python, TypeScript, Go, Rust, C#, Swift) and identify three structural shortcomings: credential extraction bound to a single Authorization header, complicating dual-persona deployment without custom middleware; the absence of pre-authentication tool discovery; and the lack of fine-grained per-tool authorization in the base SDKs. We close t

---

### [184] Open-Jev Judgments on CallScreenBench: Calibrated One-Pass Scam Screening with a Small Language Model

**链接**: https://arxiv.org/abs/2609.23959
**作者**: Simiao Ren, Kidus Zewde, Xingyu Shen, Yuchen Zhou, Dennis Ng, Ankit Raj 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Screening a phone call for fraud needs a trustworthy probability after every caller turn, in milliseconds. Jev-style typed decisions promise exactly that: declared options go in, one calibrated probability per option comes out of a single forward pass, with no generated text. We test an open implementation of this readout, JevLite, on scam-call screening: Qwen3-4B is LoRA-tuned so that the temperature-scaled softmax over two answer-label logits is P(scam). On 41 held-out CallScreenBench scenarios (577 per-turn decisions) a three-seed ensemble reaches AUROC .974 with calibration error .052, non-inferior to an LLM judge (MiniMax-M3) at a pre-registered .02 margin, with no false alarms on legitimate calls, decisions 1.14 turns earlier under the same hang-up rule, and 64.5 ms per decision on one consumer GPU, 4.9x lower than the same backbone fine-tuned to generate its answer. The gain is in the readout and calibration, not accuracy: a fine-tuned ModernBERT encoder is not significantly wor

---

### [185] RRSI: Regularized Recursive Self-Improvement of Agent Harnesses

**链接**: https://arxiv.org/abs/2609.24972
**作者**: Peng Xia, Rujun Han, Zifeng Wang, Yanfei Chen, Yufan Zhang, Yoonho Lee 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM agent's capability is largely magnified by its harness, namely the prompts, control flow, tooling, memory, and context management surrounding the frozen backbone model. Recent methods increasingly automate this process by iteratively proposing and selecting component-wise edits of an agent harness, practically establishing a form of recursive self-improvement (RSI) at the agent-system level. However, such recursive evolution may overfit by memorizing the training tasks, showing large in-distribution gains that shrink or even vanish on out-of-distribution benchmarks. We introduce Regularized Recursive Self-Improvement of Agent Harnesses (RRSI), which incorporates the principles of regularizations into harness self-improvement by constraining the evolution candidate proposal and selection. The proposer operates with a temporally annealed budget, limiting how many edits a candidate can bundle, and it encourages unexplored trajectories based on evolution history. The selector is equ

---

### [186] CraftBench-UE: Deterministic Evaluation for Coding Agents in Unreal Engine

**链接**: https://arxiv.org/abs/2609.23142
**作者**: Shutong Wu, Kevin Calderone, Andy Tsen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building gameplay features in a game engine requires more than code, as code that compiles and runs does not necessarily implement the requested gameplay. We introduce CraftBenchUE, an evaluation harness that runs agents in an isolated Unreal Engine environment, reconstructs their saved submissions in fresh projects, and applies deterministic build, asset, and runtime checks without an LLM judge. Based on the harness, we built a benchmark consisting of 70 tasks spanning C++ source, Blueprint assets, and editor scripting. We evaluate seven models under two editor-tool configurations, with a file-and-shell baseline on C++ tasks. We further pair tasks that specify the same gameplay and use the same runtime tests, but require C++ and Blueprint as the deliverables. Across the 10 paired tasks, C++ completion rates exceed Blueprint by 30.0 and 42.9 percentage points in the two tool configurations. Among on-time Blueprint submissions in this paired set that pass asset checks, 42.2% and 50.0% f

---

### [187] Is Imagination Derived from Hallucination? A Cross-Taxonomy Evaluation of Imagination and Hallucination in Large Language Models

**链接**: https://arxiv.org/abs/2609.22152
**作者**: Zixuan Tang, Hongzong Li, Shuxin Zhuang, Dapeng Wu, Zi Liang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Imagination performs as a high-level function of large language models (LLMs) which determines the potential of how an LLM creates unseen or creative content. While existing works have built a rich family of creativity benchmarks for this ability, they only measure how far an output departs from common answers and never check whether the departure is licensed by the prompt. Moreover, hallucination, the closest neighbor of imagination, is always measured in a separate pipeline on different generations, so the influential claim that imagination and hallucination stem from the same generative mechanism has never been directly testable. In this paper, we propose Whiteboard, the first LLM imagination evaluation benchmark. Its design follows the authoritative cognitive instruments developed to measure human imagination: seven mechanism-grounded imagination subtypes are adapted from classic paradigms, then crossed with ten support-boundary hallucination subtypes and scored jointly on the same

---

### [188] Scalable AI-based clinical communication training and automated assessment

**链接**: https://arxiv.org/abs/2609.22517
**作者**: Masum Hasan, Ron Epstein, Thomas Carroll, Ehsan Hoque
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Poor clinical communication can delay care, contribute to errors, and harm patients, yet opportunities for repeated practice with feedback remain limited. Our prior randomized trial showed that practice with the SOPHIE AI patient platform improved serious illness communication, but the system addressed a single clinical context and required human effort for delivery and assessment. We developed SOPHIE 2.0, a browser-based, self-service platform integrating embodied AI-patient interactions, personalized feedback, and automated assessment across 24 clinical scenarios. An automated large language model assessor evaluated three communication skills---Empower, Be Explicit, and Empathize---with agreement comparable to individual human raters ($r=0.759$; ICC$=0.746$). In a study of 59 clinicians and students, participants completed two AI-patient encounters with personalized feedback; 92% found the platform engaging, 86% easy to use, and 83% clinically relevant. Scores were higher in the seco

---

### [189] Document Retrieval-Aware Chunking (D-RAC): Universal Retrieval-Aware Ingestion of Enterprise Documents via PDF Normalization and Multimodal Markdown Conversion

**链接**: https://arxiv.org/abs/2609.24220
**作者**: Uday Allu, Abhivanth Sivaprakash, Pratik Singh, Aman Manocha (AI Research Team Yellow.ai)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) systems over enterprise knowledge bases must ingest heterogeneous document formats -- PDFs, Word documents, presentations, and scans -- whose content is locked inside complex visual layouts, multi-column pages, and dense tables. Rule-based extraction and OCR destroy reading order, flatten tables, and lose heading hierarchy, while fully agentic chunking over extracted text incurs high token costs and hallucination risk. We present Document Retrieval-Aware Chunking (D-RAC), an extension of our Web Retrieval-Aware Chunking (W-RAC) framework to arbitrary document formats. D-RAC first normalizes any input document into PDF, exploiting the fact that virtually every format has a faithful, deterministic PDF rendering. A single multimodal LLM pass then converts rendered pages into retrieval-optimized Markdown -- rewriting tables as self-contained prose statements and preserving heading hierarchy -- after which chunking proceeds exactly as in W-RAC: determini

---

### [190] DeepInstructor: An Agentic AI Instructor for Experience-Driven Idea Evaluation

**链接**: https://arxiv.org/abs/2609.22104
**作者**: Rongcan Pei, Fang Guo, Qinglin Qi, Qi Zhu, Yun Luo, Jianhao Yan 等 (10 人)
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As automated scientific discovery advances, Large Language Models (LLMs) can now generate research ideas at an unprecedented scale, shifting the bottleneck from idea generation to idea evaluation. Existing evaluators mainly rely on parametric LLM knowledge or unstructured retrieval, producing judgments that lack the experience-grounded reasoning used by human instructors. To address this, we propose DeepInstructor, an agentic framework that formulates idea evaluation as reasoning over structured scholarly experience. DeepInstructor constructs an Experience Graph from 58,607 peer reviews and employs a ReAct-based agent to retrieve dimension-specific evidence for traceable evaluation. We further introduce DeepInstruct, a dataset with controlled pairwise comparisons across novelty, significance, and feasibility. Experiments show that DeepInstructor substantially outperforms existing baselines, improving Hit@1 and Hit@2 alignment with human judgments by 24.4% and 29.7%, respectively. Our f

---

### [191] EDGEGEN: Improving Tool-Calling Agents Beyond Happy Paths with Synthetic Edge Case Generation

**链接**: https://arxiv.org/abs/2609.24115
**作者**: Harshavardhan Abichandani, Penny Chong, Jiyuan Shen, Gunraj Singh, Ashutosh Hathidara, Marcus Duigan Xing Yu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-calling LLM agents are increasingly deployed in enterprise applications. However, effective evaluation and optimization require high-quality, diverse task datasets that are often difficult to obtain due to privacy and other constraints. Existing synthetic task generation methods often produce generic tasks that ignore an agent's underlying state or database and fail to reflect real-world usage diversity. We propose EdgeGen, a synthetic task generation framework that extracts compliance rules from an agent's specification and uses them to generate database-grounded edge-case tasks designed to violate these rules. When combined with existing synthetic data generation techniques, EdgeGen enables agent improvement through finetuning and harness optimization. The resulting pipeline forms a fully automated closed-loop system that requires no human annotation. Finetuning on data generated by EdgeGen yields a consistent mean progress improvement of 2 percent to 42 percent on tau2bench air

---

### [192] AutoGym: Blueprint-First Generation of Verifiable Agent Gyms

**链接**: https://arxiv.org/abs/2609.22592
**作者**: Aarati Andrea Noronha, Kavya Ravikumar, Carly Xiaoyu Lin
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training agents with reinforcement learning requires a gym, comprising a task, an executable environment in which the task can be attempted, and a verifier that reliably distinguishes success from failure. Constructing such gyms remains manual, expensive, and static. Task sets saturate as models improve and are increasingly exposed to contamination. Synthetic generation offers scale, but single-pass synthesis produces tasks whose difficulty is largely cosmetic. Models comparable in capability solve them despite convoluted phrasing, and correctness must be adjudicated post-hoc by unreliable LLM judges. We present AutoGym, a framework that generates complete gyms (tasks, executable environments, and verifiers) from a minimal domain seed or prior model trajectories. AutoGym introduces three mechanisms. (1) Blueprint-first generation specifies the valid solution space, environment requirements, and verification criteria before the environment is materialized, making solvability a construct

---

### [193] Multiple latent orderings better predict language model preferences

**链接**: https://arxiv.org/abs/2609.22170
**作者**: Aviral Chawla, William H.W. Thompson, Jean-Gabriel Young
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models are frequently employed in settings where they are asked to make value judgments and choices. These observed choices often exhibit intransitivity: A model may prefer item $A$ to $B$ and $B$ to $C$, while also preferring $C$ to $A$. Existing work that models LLM preferences treats such inconsistencies as sampling noise around a single latent ordering. We instead propose that intransitivity reflects the aggregation of multiple latent, internally consistent orderings. We first show that observed inconsistencies cannot be explained by a single ordering under any monotone link function. We then introduce a noise-augmented mixture Bradley-Terry (MBT) model that infers latent preference components from repeated pairwise comparisons. Across seven models and four tasks, a mixture of orderings often explains structural inconsistencies better than single-utility models. We find that aggregate preferences often hide underlying preference heterogeneity. A case study on Moral Machine

---

### [194] OSWorld-Pro: Process-based Evaluation for Computer Use Agents

**链接**: https://arxiv.org/abs/2609.24890
**作者**: Zhilin Wang, Shaokun Zhang, Yifan Zhang, Hao Zhang, Jin Xu, Binfeng Xu 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation of Computer-Use Agents (CUAs) is often limited to the final deliverables they create (at the end of hundreds of steps) and assessed with functional verifiers, as seen in OSWorld. However, such evaluation of end-state performance lacks transparency into how and why agents fail in various tasks, obfuscating critical insight for subsequent improvement. For instance, agents that err during keyboard inputs would require a different mitigation strategy from those that fail to precisely provide click-based inputs on the graphical UI. We introduce OSWorld-Pro: a set of over 300 tasks containing over 2800 subgoals to enable the procedural evaluation of CUAs grounded in over 67,000 human annotations. We use robust human-aligned LLM-Judges to evaluate the fulfillment of OSWorld-Pro subgoals and thereby reveal the progress that models make throughout a series of sequentially dependent subgoals. Our findings reveal that OSWorld-Pro is challenging even for state-of-the-art LLMs, with top 

---

### [195] When Disability Disclosure Travels: Memory, Privacy, and Contextual Integrity in Conversational AI

**链接**: https://arxiv.org/abs/2609.22720
**作者**: Atieh Taheri, Mahya Tazike, Patrick Carrington, Jeffrey P. Bigham
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational AI assistants remember what people tell them, and for disabled people, that often includes disability. We interviewed 12 adults with disabilities in the United States who use LLM-based assistants such as ChatGPT, Claude, and Gemini about when, how, and why they disclose disability to these systems and how this compares with disclosing to people. Using contextual integrity as an analytic lens, we found that participants disclosed by need rather than by name, translating disability into task-scoped instructions; that the same disclosure was judged against two recipients, a non-judging interlocutor and a data-holding company, producing opposite norms; and that memory features relieved the burden of repeated disclosure while letting disability information drift into contexts where it did not belong. Participants did extensive boundary work to restore context and wanted control over scope, provenance, retention, and access rather than per-utterance toggles. We discuss implica

---

### [196] LIMIT: Less Is More for Instruction Tuning in Text-to-SQL

**链接**: https://arxiv.org/abs/2609.24186
**作者**: Haoyuan Ma, Hengwei Liu, Linjuan Wu, Yongliang Shen, Weiming Lu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have achieved remarkable progress on Text-to-SQL through reasoning-enhanced fine-tuning, yet existing approaches predominantly rely on massive instruction corpora under the assumption that scale drives performance. We challenge this paradigm by investigating a fundamental question: what is the minimal data requirement for effective Text-to-SQL instruction tuning? We propose LIMIT(Less Is More for Instruction Tuning in Text-to-SQL), a data-centric framework that demonstrates strong database reasoning can emerge from an extremely compact training set when examples are strategically selected. LIMIT operates through four stages: difficulty-aware filtering that identifies samples within the model's learning frontier, chain-of-thought synthesis with consistency-based selection, multi-dimensional quality scoring via LLM-as-judge, and genetic algorithm optimization that jointly maximizes schema coverage and sample quality. On the BIRD and Spider benchmark, LIMIT selects o

---

### [197] EvalMem: An Operation-Level Diagnostic Framework for Long-Term Memory Systems

**链接**: https://arxiv.org/abs/2609.22231
**作者**: Zeyu Liu, Jian Zhong, Rongduo Han, Ziyang Wu, Shunye Tang, Chenghao He 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon interactions with LLM-based assistants require memory systems that preserve and update user states, preferences, and interaction histories. Existing evaluations report end-to-end QA accuracy and cannot determine whether errors arise from encoding, retrieval, or generation. We introduce EvalMem, an operation-level diagnostic framework with three parallel Examiners. For each query, the Encoding Examiner checks whether the target fact is stored, the Retrieval Examiner assesses whether the native retriever returns usable evidence, and the Generation Examiner tests whether the model can answer from oracle evidence. Their outputs form fine-grained multi-label defect codes. To improve store-level diagnosis, we adapt agentic RAG with a recall-first strategy that searches using both the query and source evidence, increasing recall of present evidence on LoCoMo from 70.2% to 95.6%. Evaluations of seven memory systems on LoCoMo, LongMemEval-S, and dynamic DynaMem-Bench identify retri

---

### [198] Federated Multilingual Speech-LLMs: Architecture and Aggregation Strategy Benchmarking

**链接**: https://arxiv.org/abs/2609.23825
**作者**: Jordi Luque, Aleix Sant, Fernando L\'opez
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a comprehensive benchmark of Federated Learning (FL) for multilingual Automatic Speech Recognition (ASR), evaluating four Speech-LLM architectures on the Multilingual LibriSpeech dataset. We compare FedAvg and FedProx across frozen and unfrozen encoder configurations, demonstrating that optimized learning rates are critical for performance. Specifically, independently tuning the learning rates for the speech encoder, connector, and decoder yields the lowest error rates, with full three-component adaptation (LoRA for encoder and decoder, full training for the connector) producing the best FL results. We observe that FedProx efficacy is architecture-dependent, providing notable advantages in multilingual pre-trained architectures (e.g., EuroLLM over TinyLlama when keeping the encoder fixed); this indicates that LLM backbone capacity plays a key role in mediating resilience to heterogeneous data distributions. These findings offer concrete design guidance for deploying multilin

---

### [199] Beyond Accuracy and Surface Fluency: Risk-Sensitive Evaluation of LLMs for Legal Clause Generation

**链接**: https://arxiv.org/abs/2609.22127
**作者**: Devansh Singh, Sundaraparipurnan Narayanan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to draft contractual language, yet conventional accuracy or preference-based evaluations are poorly matched to legal drafting. A clause may be fluent and stylistically polished while still omitting an essential carve-out, allocating risk in an unenforceable way, assuming an inapplicable jurisdiction, or exposing a party to regulatory liability. This paper presents a empirical study design and framework for evaluating LLM-generated contract clauses. The study evaluates four models - Claude Haiku 4.5, Gemini 2.5 Flash Lite, GPT 5.4 Nano, and Qwen 3.5 Flash, across 22 contract clause categories and 34 legally-motivated failure modes. We combine two evaluation frameworks: CLAUSE, which classifies prompts by legal function and failure target, and LENS-CRAFT, which scores outputs across nine legal-quality dimensions. Instead of averaging dimension scores, the study applies a Max Severity Principle so that a single legally decisive defect rem

---

### [200] SPECTRA: Adaptive Execution of Speculative Decoding on a Runtime-Reconfigurable Tiled Architecture

**链接**: https://arxiv.org/abs/2609.24847
**作者**: Gabriele Tombesi, William Baisi, Je Yang, Elisavet Lydia Alvanaki, Kevin Lee, Michael Lippe 等 (8 人)
**来源**: cs.AR cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM inference on edge devices is constrained by computational and memory resources, making efficient autoregressive decoding challenging. Speculative decoding alleviates this bottleneck by generating tokens with a smaller draft model and verifying multiple tokens in parallel with a batched target model pass. However, verification introduces a runtime-dependent intermediate regime between memory-bound general matrix-vector (GEMV) operations in decoding and compute-bound general matrix-matrix (GEMM) operations in prefill, as its arithmetic intensity varies with speculation length and acceptance rate. We present SPECTRA, a runtime-reconfigurable tiled architecture that sustains high utilization across the full speculative decoding pipeline. Within each tile, the compute engine switches between systolic execution for GEMMs and vector-lane execution for GEMVs. Across tiles, SPECTRA dynamically adapts computation parallelism by selecting tile count, kernel partitioning, and communication pat

---

### [201] Beyond the Text: Verifying That Agent-Written Papers Are Backed by Their Artifacts

**链接**: https://arxiv.org/abs/2609.22111
**作者**: Qiuhong Shen, Benlong Wu, Hanjin Liu, Yuang Qi, Kejiang Chen
**来源**: cs.CL cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly capable of conducting research autonomously, producing research documents alongside the code and experiments that ostensibly support them. Yet whether the reported findings are consistently supported by corresponding implementations and execution evidence remains largely unexplored: existing review practices primarily assess textual quality and cannot reliably identify inconsistencies such as hard-coded metrics, unimplemented methods, or unsupported experimental results. We present ReAgent, an automated auditing framework for assessing the consistency between agent-generated research documents and their associated repositories. ReAgent constructs structured representations of scientific claims from research documents and uses them to guide repository analysis and evidence collection. Static auditing examines whether claimed methodologies, implementations, and experimental configurations are consistently reflected in the repository, while dyn

---

### [202] DeceptionAnalyser: A Web-Based AI Tool for Performing Structured Deception Analysis with Argumentation Schemes and LLMs

**链接**: https://arxiv.org/abs/2609.24369
**作者**: Stefan Sarkadi, Xabier Garmendia, Jack Mumford and Trevor Bench-Capon
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deception plays a central role in Intelligence operations, yet it remains difficult to analyse systematically without expert knowledge of reasoning patterns and cognitive manipulation. In computational argumentation, for instance, no scheme-level ground-truth corpora currently exist to support statistical validation. In this paper, we address this by introducing a set of ten argument schemes designed to model distinct forms of deception, each accompanied by structured premises and critical questions. In doing so, we introduce the first dedicated library of argumentation schemes specifically designed for deception analysis, providing a structured foundation for systematically modelling and analysing deception in narrative text. We then present \textit{DeceptionAnalyser}, a browser-based tool that implements these schemes through a two-stage methodology combining LLM-based premise extraction with critical-question-driven evaluation. Our aim is to provide a conceptual and methodological f

---

### [203] Clinical Domain Classification from Medical Transcriptions

**链接**: https://arxiv.org/abs/2609.22734
**作者**: Sravani Pottipati, Lakshmikar R. Polamreddy
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical domain classification plays an important role in organizing and analyzing large volumes of unstructured medical text. However, medical transcription datasets are often highly imbalanced, which can substantially degrade classification performance, particularly for underrepresented clinical specialties. In this work, we present a comparative study of machine learning and transformer-based approaches for clinical domain classification from medical transcriptions. We evaluate six traditional machine learning classifiers---Naive Bayes, Support Vector Machine (SVM), Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and XGBoost---along with two pretrained transformer models, BERT and XLNet, and a few-shot large language model prompting approach. Experiments are conducted on medical transcription data collected from MTSamples, comprising 5,013 samples across 40 clinical specialties. To address severe class imbalance, we investigate two balancing strategies: text augmentation us

---

### [204] An Empirical Cost Attribution of Context-Compression Gateways in Multi-Turn Coding Agents

**链接**: https://arxiv.org/abs/2609.22114
**作者**: Luzhuo Chen, Jiayu Shi
**来源**: cs.CL cs.PF cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context compression is widely proposed as a way to cut the token bill of LLM coding agents, and public benchmarks report that aggressive compression preserves task-solving quality. These two facts do not imply the third one commonly assumed: that compressing file reads saves money in a real multi-turn agent. We instrument a production compression gateway (Paritok) between coding agents (Claude Code, Codex) and frontier LLMs (Claude Sonnet, GPT-5), and decompose the token bill of real sessions into three independent levers: tool-schema filtering, content compression of file reads and tool output, and history summarization. Measured in isolation under controlled A/B runs, the three save at fundamentally different rates. Tool-schema filtering removes a fixed block every turn, roughly 21K-57K tokens on a typical turn; it is linear in the turn count N and the only unambiguously and reproducibly positive lever. Content compression saves only about 2% of the cache-priced prefix per turn, but 

---

### [205] CAMFT: Conflict-Aware Mergeable Fine-Tuning for Large Language Models

**链接**: https://arxiv.org/abs/2609.22253
**作者**: Jingang Zhou, Haiyang Guo, Yuan Ma, Han Zhu, Xu-Yao Zhang
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model merging has emerged as a promising paradigm for integrating multiple task-specific capabilities into a single large language model. However, existing methods predominantly focus on post-hoc processing of independently fine-tuned models, overlooking how the training phase itself impacts cross-task compatibility. Resolving parameter conflicts after fine-tuning is inherently sub-optimal. To address this, we propose CAMFT, a Conflict-Aware Mergeable Fine-Tuning method that makes task adaptation both efficient and mergeaware. CAMFT treats mergeability as a property shaped during fine-tuning, rather than only a problem to be solved after fine-tuning. By guiding each task to update sparse coordinates with lower cross-task conflict, CAMFT produces task updates that are efficient to train and more compatible for downstream model merging. Extensive experiments demonstrate that CAMFT outperforms standard finetuning baselines in multi-task merging scenarios. Codes are available at https://gi

---

### [206] Measuring the Checker: Mutation Analysis for GPU-Kernel Benchmark Oracles

**链接**: https://arxiv.org/abs/2609.22220
**作者**: Mingzhe Du, Anh Tuan Luu, Dong Huang, See-Kiong Ng
**来源**: cs.LG cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarks for LLM-generated GPU kernels decide correctness with a few random inputs and a loose floating-point tolerance, and their verdicts now feed leaderboards and reinforcement-learning rewards. Recent work agrees these checkers are weak and patches them by hand---extra input distributions, fuzzing recipes, tighter tolerances---with no way to \emph{measure} whether any patch suffices. We introduce mutation analysis as an adequacy metric for kernel-benchmark oracles: deterministic rules inject 10{,}303 compilable faults into verified CUDA implementations of 188 KernelBench problems, 7{,}384 of them with an independent kill witness; any test protocol is scored by the fraction it detects. The official check misses \textbf{one in six} witnessed faults (16.9%), deterministically, and the misses are skewed by family: 8.7% of arithmetic faults escape, but 78.6% of precision faults do. The metric explains why (a tolerance blind band growing with reduction size; a measured ceiling on input

---

### [207] Scaling Articulated Rationales for MLLM-based Recommendation

**链接**: https://arxiv.org/abs/2609.17639
**作者**: Haoke Xiao, Yueyang Liu, Yuhui Zhang, Xiang Chen, Yufei Liu, Jia Xu 等 (10 人)
**来源**: cs.IR cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [208] SLICEChat: Progressive In-Encoder Token Pruning for Whole-Slide Pathology Language Models

**链接**: https://arxiv.org/abs/2609.24894
**作者**: Ali Kerem Bozkurt, Baris Cem Bakay, Ibrahim Kulac, Cigdem Gunduz-Demir, Erkut Erdem, Aykut Erdem
**来源**: cs.CV cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whole-slide pathology images (WSIs) contain gigapixel-scale visual content, creating a major scalability challenge for slide-level multimodal large language models (MLLMs). Existing approaches process thousands of patch tokens and typically apply compression only after slide encoding, leaving multimodal attention computationally expensive. We introduce SLICEChat, a slide-level MLLM that integrates progressive token pruning within a hybrid Mamba--Transformer slide encoder. Mamba layers enable efficient long-range propagation, while Transformer layers preserve global interactions as the sequence is progressively shortened. Between stages, language-supervised, region-aware pruning removes spatially coherent low-utility regions under a controlled keep-rate schedule, producing compact slide representations before multimodal fusion. On SlideBench VQA, SLICEChat achieves 79.84% accuracy on TCGA and 59.09% on BCNB cohorts, outperforming prior slide-level pathology MLLMs, and achieves the highe

---

### [209] Matched-Input Estimates Differ in Sign Across Architectures: Auditing EEG Foundation Models on Motor Imagery

**链接**: https://arxiv.org/abs/2609.23924
**作者**: Kevin Zhou, Sparsh Roy
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG, BCI, Foundation Models, Motor Imagery
**相关性评分**: 12.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained EEG foundation models are increasingly proposed as general-purpose encoders for brain-computer interfaces, yet recent benchmarks disagree about when their representations transfer to downstream tasks. We audit LaBraM and CBraMod on motor imagery under a validation-locked protocol in which preprocessing, architecture, optimization, freeze depth, checkpoint, temperature, and method selection are determined using training-session data only. On four-class BCI Competition IV-2a, every supervised comparator evaluated here outperforms every foundation-model configuration, including validation-selected fine-tuning. We then examine a key confound: foundation models and task-specific decoders are normally evaluated using different input pipelines. Retraining three supervised architectures on the broadband arrays consumed by the foundation models produces matched-input accuracy differences of opposite sign across architectures: broadband input improves ATCNet by 0.078 accuracy while re

---

### [210] Comparative Analysis of State-of-the-Art Foundation Models for Sleep Analysis Under Channel Reduction

**链接**: https://arxiv.org/abs/2609.22105
**作者**: Hassan Mehdi, Riku Klen, Ayse Kosal Bulbul, Suzanne Timmons, Abdulhamit Subasi, Wei Chen 等 (8 人)
**来源**: eess.SP cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic sleep staging from polysomnography (PSG) is a well-studied task, but PSG itself is expensive, clinic-based, and burdensome to manually score, which limits its use for long-term or at-home monitoring. Most existing sleep-staging foundation models are evaluated using the full PSG montage. We instead ask how much of that montage is actually necessary. We evaluate six sleep staging models on the Multi-Ethnic Study of Atherosclerosis (MESA) PSG dataset across three signal conditions: electroencephalography (EEG), electrocardiography (ECG), and their combination (EEG+ECG). This is motivated by edge-cloud deployment, where EEG requires a clinic-grade scalp electrode, whereas ECG is already captured by consumer wearables. We test state-of-the-art foundation models such as SleepFM with an encoder trained from scratch on MESA, alongside BIOT, MOMENT, LaBraM, a base-scale Vision Transformer (ViT-B) reimplementation of SensorLM trained from scratch, and YASA, spanning EEG-pretrained, gen

---

### [211] Adaptive Forgetting for Nonstationary Optimization: Towards Robust EEG Decoding

**链接**: https://arxiv.org/abs/2609.24233
**作者**: Hongyu Zhu, Lin Chen, Jing Chen, Yuting Zhou, and Mingsheng Shang
**来源**: cs.LG cs.HC
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) provides non-invasive monitoring of brain activity and is widely used in emotion recognition, motor imagery and sleep staging. Although within-subject decoding has achieved considerable progress, cross-subject generalization remains a central challenge in practical applications. EEG decoders are typically trained with Adam/AdamW under a fixed second-moment decay coefficient, even though cross-subject learning involves low signal-to-noise ratios, subject variability, and gradient nonstationarity. A fixed coefficient implicitly assumes that gradient statistics are homogeneous across layers and time, which can limit model's adaptability to cross-subject EEG signals and degrade generalization. To address these issues, we propose AFOR, a tensor-wise adaptive optimizer that converts the fixed second-moment decay coefficient into a dynamic coefficient estimated online from local gradient state. AFOR combines a Residual-Alignment Signal Scorer (RASS) and an Adaptiv

---

### [212] Adaptive Cortically Constrained EEG-Vision Alignment for Zero-Shot Brain-to-Image Retrieval

**链接**: https://arxiv.org/abs/2609.24109
**作者**: Ye Wang, Haokun Ren, Wei Wu, Guoyin Wang, Zhuliang Yu, Hong Yu 等 (7 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zero-shot brain-to-image retrieval requires robust alignment between noisy EEG responses and visual representations. Existing EEG-vision alignment methods often operate in sensor space and apply fixed visual supervision to all responses, ignoring both spatial mixing in scalp EEG and response-wise variability in alignment reliability. We propose an adaptive cortically constrained EEG-vision alignment method for zero-shot brain-to-image retrieval. The method reconstructs EEG responses into predefined ROI-level source-pattern representations and encodes them with a Neuro-ROI Attention Encoder. To handle response-wise variability, we introduce an evidence-based adaptive visual supervision strategy that weights detail-controlled visual targets using model-based alignment evidence. On THINGS-EEG, the proposed method achieves strong 200-way zero-shot retrieval performance, with ROI-level attribution providing post hoc interpretability of the learned source-pattern representations. These resul

---

### [213] Leakage-Safe Empirical Benchmarking of EEG-Based Machine Learning Pipelines for Dementia Classification

**链接**: https://arxiv.org/abs/2609.22092
**作者**: Haitian Wang, Chamara Madarasingha, Redowan Mahmud, Aneesh Krishna, Ryu Takechi
**来源**: eess.SP cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is a low-cost and non-invasive signal source for dementia screening, yet existing EEG-based studies remain difficult to compare because preprocessing, EEG segmentation, feature design, classifier choice, and validation protocols vary across studies and are often evaluated in isolation. This variability limits the derivation of robust pipeline recommendations. This paper presents a leakage-safe empirical benchmark for resting-state EEG-based dementia classification and uses it to identify a practical best-practice pipeline. Using the public OpenNeuro ds004504 dataset, the benchmark evaluates artifact correction, fixed-length EEG segmentation, training-only augmentation, multi-domain feature extraction, fold-internal feature selection, classical machine-learning (ML) classifiers, subject-level aggregation, and interpretation under leave-one-subject-out (LOSO) validation. The best-performing pipeline in this benchmark combines Artifact Subspace Reconstruction 

---

### [214] Brain-to-Image Generation: Reconstructing Visual Stimuli from EEG using Generative Adversarial Networks

**链接**: https://arxiv.org/abs/2609.22282
**作者**: Harshit Goyal
**来源**: cs.CV cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstructing visual stimuli from electroencephalography (EEG) is difficult because scalp measurements have high temporal but limited spatial resolution, and paired EEG-image datasets remain small relative to modern generative-model training corpora. We present a reproducible single-subject baseline on THINGS-EEG2 that first tests the more defensible question of whether EEG can retrieve the viewed stimulus in a visual embedding space. A compact temporal-spatial convolutional encoder maps repetition-averaged EEG (63 by 250) to provided 512-dimensional ViT-B/32 image features. Model selection uses a concept-disjoint validation split, and final evaluation uses the official 200-image, 200-concept test gallery. Across three training seeds, the model obtains 12.83 +/- 0.58%, 39.17 +/- 1.76%, and 58.00 +/- 1.73% image recall at 1, 5, and 10 (mean +/- sample standard deviation), compared with analytical chance levels of 0.5%, 2.5%, and 5.0%. A session-balanced ablation shows that averaging mo

---

### [215] Attention-Enhanced Dual-Branch ConvNeXt-BiLSTM Network for Subject-Independent EEG Seizure Detection

**链接**: https://arxiv.org/abs/2609.22141
**作者**: Maimuna Chowdhury, Sk. Imran Hossain
**来源**: eess.SP cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated seizure detection from scalp electroencephalography (EEG) is difficult because seizure morphology varies among patients and seizure samples are substantially outnumbered by non-seizure samples. This paper presents an attention-enhanced dual-branch network that jointly learns time--frequency and temporal representations from the same EEG segment. A continuous wavelet transform converts each segment into a scalogram processed by an ImageNet-pretrained ConvNeXt-Tiny backbone and squeeze-and-excitation attention. In parallel, a bidirectional long short-term memory network followed by multi-head self-attention models the raw signal. The two feature vectors are concatenated and classified by a weighted multilayer perceptron. Experiments use 14 subjects from the CHB-MIT scalp EEG database with subject-wise partitioning performed before overlapping segmentation. The model obtains $97.88\%$ accuracy and $97.51\%$ F1-score over ten across-subject splits, and $97.51\%$ accuracy, $96.59\

---

### [216] ST-Topo GAN: A Motor EEG-to-EMG Decoding Model Matched to Wrist Movement Complexity

**链接**: https://arxiv.org/abs/2609.22128
**作者**: Ye Sun, Mingxuan Qu, Jing Wang, Dezhong Yao, and Gang Liu
**来源**: eess.SY cs.LG cs.SY
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The wrist plays a critical role in upper-limb function by enabling precise hand positioning, force regulation, and object manipulation. Continuous brain--muscle interfaces (BMIs) offer a promising approach for motor restoration by decoding neural activity into muscle activation signals. However, existing EEG-to-EMG models have mainly been developed for tasks with relatively stable muscle synergies and may be less effective for the heterogeneous and weakly coupled neuromuscular organisation involved in wrist movements. This paper proposes ST-Topo GAN, a Spatial--Temporal Topological Generative Adversarial Network for continuous EEG-to-EMG decoding of wrist movements. The framework integrates multi-band EEG representation, sensorimotor cortical topology modelling, and conditional adversarial learning to reconstruct multi-channel iEMG activation. The model was evaluated through cross-task comparison, wrist EEG-to-iEMG decoding, and ablation experiments. Compared with the WAY-EEG-GAL grasp

---

### [217] Brain-Token Learning: Microstate-Based Tokenization and Multi-Scale Interaction for Long-Horizon EEG Sequence Modeling

**链接**: https://arxiv.org/abs/2609.24324
**作者**: Weishan Ye, Yue Pan, Li Zhang, Gan Huang, and Zhen Liang
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) provides a non-invasive window into dynamic brain activity, yet modeling long-horizon EEG sequences remains challenging due to their high temporal complexity, substantial variability across subjects, and the lack of biologically meaningful sequence representations. Existing tokenization strategies, such as fixed-window and patch-based representations, discretize EEG signals according to artificial temporal boundaries, which may disrupt intrinsic brain-state dynamics. In this work, we propose Brain-Token Learning, a neuroscience-inspired framework that introduces Brain Tokenization for long-horizon EEG sequence modeling. Instead of partitioning EEG signals into predefined temporal segments, Brain Tokenization represents EEG as sequences of recurrent microstate-derived brain tokens, where each token corresponds to a quasi-stable large-scale brain state with variable temporal duration. Based on these biologically grounded tokens, we further develop a multi-sca

---

### [218] Learning Dynamic Neural Evidence Representations for Time-Adaptive Brain-Computer Interfaces

**链接**: https://arxiv.org/abs/2609.22088
**作者**: Beining Cao, Ziyi Zhao, Xiaowei Jiang, Daniel Leong, Yingtao Ren, Thomas Do 等 (8 人)
**来源**: eess.SP cs.HC cs.LG q-bio.NC
**匹配关键词**: EEG, BCI
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain-computer interfaces (BCIs) decode neural activity into commands, yet most existing systems rely on fixed-window decoding that may result in redundant observation or unreliable predictions due to insufficient evidence. Adaptive temporal decision-making (ATDM) addresses this accuracy-time trade-off by progressively accumulating EEG evidence and deciding when to stop. However, existing EEG encoders are mainly designed for fixed-window decoding and may not provide reliable state representations under variable observation lengths. In addition, current ATDM-oriented encoders are typically tailored to specific EEG paradigms, limiting their applicability across different BCI tasks. To address these limitations, we propose ProtoTrigger, a two-stage prototype learning-based EEG state encoder for ATDM. ProtoTrigger uses prototype matching to extract stable local EEG embeddings and prototype-based attention to aggregate decision-relevant temporal evidence during progressive observation. Offl

---

### [219] Graph Learning for Cross-Subject, Cross-Population EEG Emotion Decoding and Model-Derived Spatial-Spectral Neural Signatures

**链接**: https://arxiv.org/abs/2609.22103
**作者**: Dongyi He, Bin Jiang, Xiangkai Wang, Yun Zhao, Hongjie Yan, Wai Ting Siok 等 (7 人)
**来源**: eess.SP cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) provides a noninvasive means of capturing emotion-related neural dynamics, yet reliable EEG emotion decoding lacks models that can both generalize to unseen individuals and populations while preserving neural interpretability. To address these challenges, EmoDiPyraTrans is proposed as a development-regularized differential graph Transformer that models temporally ordered relative power spectral density graphs through adaptive graph recurrence, differential attention, and multiscale fusion. The framework was evaluated at three connected levels. First, cross-subject evaluations on SEED, FACED, MAHNOB-HCI, DEAP and DREAMER yielded participant-mean accuracies of 0.928, 0.645, 0.714, 0.617 and 0.671, respectively; the model ranked first among the evaluated methods for accuracy and positive-class F1 on all five datasets. Across seven ablation protocols, differential attention was the only component whose removal reduced both metrics in every case, whereas removin

---

### [220] ADSEL: Adaptive Dual Self-Expression Learning for EEG Feature Selection via Incomplete Multi-Dimensional Emotion Labels

**链接**: https://arxiv.org/abs/2508.05229
**作者**: Xueyuan Xu, Tianze Yu, Junming Zhang, Chenrui Liu, Wenjia Dong, Fulin Wei 等 (7 人)
**来源**: cs.HC cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [221] HDND: Hierarchical Dynamic Neural Decoding for Multilingual Word/Character Retrieval from Non-Invasive Brain Recordings

**链接**: https://arxiv.org/abs/2609.24095
**作者**: Yueyang Li, Shuran Chen, Wai Ting Siok, and Nizhuan Wang
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While deep learning has enabled language decoding from intracranial brain recordings, extending this capability to non-invasive recordings remains an unresolved challenge. Decoding individual words from non-invasive brain recordings is particularly difficult, as word-level neural evidence is weak, temporally distributed, and entangled with acoustic, lexical, and semantic structure. Existing retrieval pipelines often collapse these factors into a single representation, potentially discarding information available at intermediate temporal scales. Here, we introduce Hierarchical Dynamic Neural Decoding (HDND), a hierarchical dynamic decoding framework that treats word decoding as structured refinement rather than flat label retrieval. HDND combines intermediate neural representations, contextual semantic predictions, and, for selected reading conditions, an auxiliary character-form objective. We evaluate HDND across seven electroencephalography (EEG) and magnetoencephalography (MEG) datas

---

### [222] The Visual Target Matters: Learning across the Visual Hierarchy for Brain-to-Image Retrieval

**链接**: https://arxiv.org/abs/2609.24136
**作者**: Ye Wang, HaoKun Ren, Hong Yu, Ruirui Li, Xiao Li, Ke Liu 等 (7 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain-to-image retrieval seeks to identify the visual stimulus that elicited a non-invasive neural response. Candidate images are typically represented by pretrained vision models, whose internal representations vary in abstraction across depth. Existing methods usually train the neural encoder to recover a fixed final-layer visual target. Under this formulation, the visual hierarchy is reduced to a single prescribed endpoint, preventing representations at other depths from directly shaping the visual target. This limitation motivates learning how information across visual depths should contribute to the retrieval target. To this end, we introduce NeuroGlyph, which learns a trial-independent visual target from multiple depths of a frozen visual backbone. NeuroGlyph decomposes the target into factor-specific subspaces. Each subspace learns an image-conditioned allocation over visual depth. The resulting subspaces are fused into a single embedding for retrieval. Across THINGS-EEG and THI

---

### [223] Large language models in medical time series analysis

**链接**: https://arxiv.org/abs/2609.22262
**作者**: Yu Han, Cigdem Beyan, Xiang Zhang, Xiaofeng Liu, Nan Liu, Jimeng Sun 等 (9 人)
**来源**: eess.SP cs.AI cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical time series (MedTS), including electrocardiograms (ECG), electroencephalograms (EEG), photoplethysmography (PPG), and vital-sign recordings, are central to clinical diagnosis and health monitoring. As large language models (LLMs) have advanced, a growing body of work has examined how their reasoning, generation, and knowledge-integration capabilities can support MedTS analysis. Yet existing studies remain scattered, and the field still lacks a clear view of how these models should be designed, integrated into clinical workflows, and evaluated. This review synthesizes recent work on large language models for medical time series analysis (MedTSLLMs), covering both methodological progress and issues related to real-world deployment. We review model architectures, data resources, and processing pipelines, and prompt design strategies adapted for diverse clinical scenarios. We further organize existing MedTS applications, ranging from diagnostic interpretation and report generation 

---

### [224] A Comparative Framework for Evaluating Foundation Models on Tabular Data: A Case Study in Healthcare

**链接**: https://arxiv.org/abs/2609.22154
**作者**: Majid Lotfian Delouee, Sjors G. J. G. In 't Veld, and Martijn C. Schut
**来源**: cs.LG cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular data is the most common format in clinical practice, encompassing laboratory results, medication records, diagnostic codes, and patient demographics. As foundation models for tabular data have grown in number and variety, a practical question has become harder to answer: which model should a clinician or data scientist actually choose for a given task, and why? Existing surveys catalogue what these models can do, but they stop short of providing a structured way to compare them against the specific demands of a real application. We introduce \system{}, a comparative evaluation framework that scores and ranks tabular foundation models (TFMs) across six clinically meaningful dimensions: how well a model generalizes to new datasets, how effectively it protects patient privacy, how much data it needs to perform well, how it scales with growing datasets and feature spaces, how interpretable its predictions are to clinicians, and how fairly it performs across patient subgroups. Each 

---

### [225] Can 4D Foundation Models Remember?

**链接**: https://arxiv.org/abs/2609.20819
**作者**: Guangzhao He, Hadar Averbuch-Elor, Wei-Chiu Ma
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [226] RSPDBench: Benchmarking Vision Foundation Models on Earth Observation Tasks Under Physically Grounded Remote-Sensing Product Degradations

**链接**: https://arxiv.org/abs/2609.23427
**作者**: Tanjim Bin Faruk, Khondaker Masfiq Reza, Shrideep Pallickara, Sangmi Lee Pallickara
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models targeting Earth observation (EO) tasks are commonly evaluated on clean downstream benchmarks, but operational EO products can already contain spatial, radiometric, alignment, noise, and harmonization defects before reaching the model. Existing robustness evaluations often use generic image corruptions or broad domain shifts, which do not isolate these product-level failure modes. We introduce \textbf{RSPDBench}, a physically grounded \textbf{r}emote-\textbf{s}ensing-\textbf{p}roduct \textbf{d}egradation \textbf{b}enchmark for vision foundation models. RSPDBench evaluates five EO datasets, seven foundation-model entries, and two supervised baselines under audited primitive degradations and compound product chains. Each model is evaluated under its clean-selected native protocol, with robustness measured as the drop from its own clean baseline. Our analysis reveals that degradation sensitivity is strongly structured: resolution-conditioned and channel-grouped enc

---

### [227] Towards robust multimodal 3D object detection via visual foundation models

**链接**: https://arxiv.org/abs/2609.23541
**作者**: Ziying Song, Lin Liu, Hongyu Pan, Shaoqing Xu, Lei Yang, Mingzhe Guo 等 (7 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal 3D object detection is fundamental to robust perception in autonomous driving because it integrates complementary information from LiDAR and camera sensors. However, existing methods often fail to maintain robustness under out-of-distribution (OOD) corruptions caused by sensor noise, adverse weather, and environmental changes. To address this problem, we propose RoboDistill, a robust and generalizable multimodal 3D object detection framework that leverages visual foundation models (VFMs), such as the Segment Anything Model (SAM). First, we introduce SAM-AD, a domain-specific pretraining strategy that fine-tunes SAM on autonomous-driving imagery to extract feature representations with rich semantic information. Second, we design the AD Feature Pyramid Network (AD-FPN) to refine and upsample SAM features at multiple scales for seamless fusion with LiDAR features. Third, we develop the Depth-Guided Wavelet Attention (DGWA) module, which suppresses high-frequency sensor noise wh

---

### [228] PACE: Plug-and-Play Contextual Embedding for Feature Screening with Pretrained Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.23574
**作者**: Qi Qin, Erbo Li, Ting Wei, Zizhou Huang, Zixuan Qin, Wu Wang 等 (7 人)
**来源**: stat.ML cs.LG stat.AP stat.ME
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In high-dimensional tabular learning, feature screening provides a lightweight, model-agnostic way to remove irrelevant features before model fitting. However, scoring raw values directly can miss nonlinear or distributional structure. We introduce PACE (Plug-and-Play Contextual Embedding), which inserts a frozen tabular foundation model (TFM) column encoder before an existing feature-scoring rule, expanding each feature into a higher-dimensional contextual representation. Across controlled studies, PACE improves raw-space screening of complex nonlinear dependence with only modest additional encoding cost. These gains translate to downstream prediction on TALENT datasets: PACE-DC improves binary AUC by 0.077 and multiclass macro-AUC by 0.064, with a median normalized RMSE improvement of 0.063 across ten learners. Matched random-weight and random-feature controls show that PACE gains from pretrained structure beyond generic dimensional expansion. PACE further achieves favorable performa

---

### [229] OmniEdu: Open Foundation Models for Learning and Teaching

**链接**: https://arxiv.org/abs/2609.23088
**作者**: Hao Liang, Qihan Lin, Meiyi Qiang, Linzhuang Sun, Hengyi Feng, Mingrui Chen 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Educational foundation models must solve problems, understand curriculum structure, diagnose learner difficulties, and provide appropriate instructional support. Existing educational language models often focus on either problem solving or tutoring, with training mixtures organized by source or task rather than capability. We present OmniEdu, an open family of foundation models for K-12 learning and teaching. Its instruction-tuning corpus combines over 100 educational resources and general instruction sources, organized around four capabilities: subject competence, curriculum grounding, diagnostic reasoning, and pedagogical action and scaffolding. Our pipeline integrates deterministic cleaning, semantic auditing and rewriting, task-specific quality scoring, token-budgeted diversity selection, and pedagogical instruction assignment. It yields 69,999 examples and 15.96M supervised response tokens, including 60,951 education-specific examples. We fine-tune 4B, 9B, and 27B models and evalu

---

### [230] Leveraging Industrial Foundation Models at the Edge of Particle Physics Detectors via Distillation Learning and Hardware Co-design

**链接**: https://arxiv.org/abs/2609.23385
**作者**: Gia Ancone, Qibin Liu, Liangyu Wu, Julia Gonski
**来源**: physics.ins-det cs.LG hep-ex
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data acquisition (DAQ) systems at future particle physics experiments stand to benefit from the extremes of AI/ML development: large-scale foundation models can enhance the performance of feature extraction algorithms, and small-scale on-detector deployments can enable real-time intelligent data handling. This work provides the first fine-tuning of an industrial foundation model for particle physics DAQ. Starting from the backbone of Google Research's TimesFM (Time Series Foundation Model), we demonstrate fine-tuning on real-time regression tasks for drift chamber trackers and dual-readout calorimeters. Furthermore, the fine-tuned TimesFM model is distilled into a student and co-designed with FPGA implementation to enable these models to run in real-time at future colliders. The fine-tuned distillations meet or exceed the performance of previously published AI/ML solutions for each task. Further, the pipeline of distillation and model compression from TimesFM is generic and can be easi

---

### [231] ECP-Bench: Benchmarking and Learning Entertainment Content Promotion with Foundation Models

**链接**: https://arxiv.org/abs/2609.22150
**作者**: Hyomin Kim, Bowen Chen, Jin Huang, Zhao Wang, Qiaozhu Mei, Shingo Takamatsu
**来源**: cs.IR cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Content promotion spans a broad set of skills, from understanding content to forecasting its market reception. However, LLMs' ability to support such promotion decisions remains underexplored. Existing studies are often limited to a single task (e.g., popularity prediction) or a small set of tasks within a single domain (e.g., movies). As a result, there is a lack of understanding of LLMs' abilities in the full promotion process and how these abilities generalize across different tasks and domains. In this work, we introduce ECP-Bench, a benchmark containing 1.9M movie, game, and music items and 423,451 questions across 33 tasks in five content-promotion skill families. Our evaluation shows that frontier models achieve only 51.9\% overall accuracy and lose much of their advantage on post-cutoff content, with drops of up to 19.1 percentage points. In contrast, open-weight models fine-tuned on ECP-Bench achieve up to 60.3\%, remain substantially more stable across the knowledge cutoff, g

---

### [232] Rethinking Class Imbalance for Single-Cell Foundation Models: A Systematic Benchmark Across Architectures and Long-Tail Loss Functions

**链接**: https://arxiv.org/abs/2609.23325
**作者**: Zeyu Dong, Jiahui Zhong
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-cell foundation models (scGPT, scBERT, Geneformer) achieve cell-type classification accuracy up to 97.5% in our experiments, yet this aggregate accuracy can mask systematic failure on rare, often disease-relevant cell populations that long-tail loss functions are widely assumed to address. We present a systematic benchmark of six long-tail loss functions (cross-entropy, weighted CE, class-balanced loss, focal loss, LDAM, logit-adjusted softmax) across three architectures and three datasets (Multiple Sclerosis, Zheng68K, human Pancreas), totaling 162 controlled training runs (3 backbones x 3 datasets x 6 losses x 3 seeds). The gap between overall accuracy, Macro-F1, and rare-class recall under plain cross-entropy is consistent across all nine (architecture, dataset) settings, driven by dataset structure rather than pretraining. Rare-class failure itself splits into two regimes with distinct embedding-geometry signatures, visible before any loss is chosen: some classes are recover

---

### [233] A Roadmap for MEG Foundation Models

**链接**: https://arxiv.org/abs/2609.04461
**作者**: Philipp Th\"olke, Hamza Abdelhedi, Yorguin Mantilla-Ramos, Fouad Lbakali, Oumayma Gharbi, Catherine Duclos 等 (9 人)
**来源**: q-bio.NC cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [234] SURE-Map: Self-Correcting Streaming Geometric Foundation Models

**链接**: https://arxiv.org/abs/2609.15795
**作者**: Mingkai Liu, Hao Zhao, Xingxing Zuo
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [235] AURA: Uncertainty-Routed Activation Editing for Acoustic Grounding in Speech Foundation Models

**链接**: https://arxiv.org/abs/2609.23979
**作者**: Natarajan Balaji Shankar, Zilai Wang, Zihan Wang, Mohan Shi, Kaiyuan Zhang, Abeer Alwan
**来源**: eess.AS cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attention encoder-decoder (AED) Speech Foundation Models achieve strong ASR performance but can generate acoustically unsupported text when inputs contain no speech, weak acoustic evidence, or unreliable transcription. We propose AURA: Activation-editing with Uncertainty-Routed Adaptation, an ultra-efficient representation-editing method that freezes the pretrained model and applies sparse scale-and-shift edits to decoder cross-attention heads. AURA dynamically routes edits using cross-attention uncertainty features that capture over-concentration, diffuse attention, and abrupt frame shifts. We evaluate AURA on four datasets spanning non-speech hallucination and speech grounding stressors, including imperfect-label child speech, imperfect-label adult speech, and disfluent speech. On non-speech audio, AURA reduces hallucination rate from 89.18% to 1.94% without prior hallucination-head identification. On imperfect-label corpora, AURA approaches LoRA WER while using roughly 500x fewer tr

---

### [236] Geospatial Foundation Models Capture Health-Relevant Dimensions of Place Beyond Conventional Social Risk Indices

**链接**: https://arxiv.org/abs/2609.11689
**作者**: Nathaniel Hendrix, Carl Y. Zhang, Chris Heitzig, Andrew Bazemore, David H. Rehkopf
**来源**: stat.AP cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [237] LIBERO-VPro: Benchmarking Closed-Loop Visual Robustness of Robotic Foundation Models

**链接**: https://arxiv.org/abs/2609.24350
**作者**: Huiqiong Li, Zhiting Mei, Anirudha Majumdar, Jingjing Chen, Yu-Gang Jiang, Bin Zhu
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robotic foundation models achieve impressive performance on standard manipulation benchmarks, yet these evaluations typically assume clean, timely, and consistent visual observations throughout execution. We introduce LIBERO-VPro, a benchmark for systematically evaluating the closed-loop visual robustness of robotic foundation models by perturbing the visual evidence available during execution. LIBERO-VPro covers four complementary dimensions, including Visual Evidence Degradation, Camera Staleness, Visual Source Consistency, and Task-Relevant Scene Variation, spanning 12 challenge categories, 96 experimental settings, and 3,296 task-condition cases. We evaluate three vision-language-action models and three world-action models over approximately 196,000 simulated episodes, complemented by 200 real-world rollouts on a Franka Research 3. Our results reveal that strong nominal performance can mask substantial weaknesses in visual grounding and adaptation. Models often remain successful de

---

### [238] Time Series Foundation Models for Process Model Forecasting

**链接**: https://arxiv.org/abs/2512.07624
**作者**: Yongbo Yu, Jari Peeperkorn, Johannes De Smedt, Jochen De Weerdt
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [239] Evaluating the Generalization of Neuroimaging Foundation Models on African Brain MRI

**链接**: https://arxiv.org/abs/2609.23983
**作者**: Oluwatobi Iyanuoluwa Akinmuleya, Olatokun Shamsudeen Akano, Samuel Danquah Ankapong, Olamide Lawal, and Toufiq Musah
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neuroimaging foundation models pretrained on large, predominantly western cohorts are increasingly proposed as general-purpose backbones for brain MRI analysis. Yet, their ability to generalize to underrepresented clinical populations remains largely untested. We evaluate four recent foundation models (BrainIAC, Neuro-JEPA, NeuroVFM, and Primus) on a three-way diagnostic classification task (Control, Dementia, Parkinson's disease) using a cohort of 88 subjects from a Nigerian clinical brain MRI dataset, across four modality configurations (T1w, T2w, T1w+T2w, FLAIR), and compare against an end-to-end trained ViT3D baseline. The frozen backbones collapse to majority-class predictions, while Neuro-JEPA on FLAIR shows modest but still limited discrimination. In contrast, the end-to-end trained ViT3D achieves higher accuracy and MCC on every task (up to 53.4% accuracy, MCC=0.27) and is the only model with non-trivial recall. Our findings suggest that these frozen neuroimaging foundation mod

---

### [240] M3GA-Wild: A Large-Scale Dataset and Benchmark for Multi-Modal Multi-session Ground-to-Aerial Place Recognition in Forests

**链接**: https://arxiv.org/abs/2609.23003
**作者**: Ethan Griffiths, Maryam Haghighat, Simon Denman, Clinton Fookes, Milad Ramezani
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present M3GA-Wild, the first benchmark for multi-modal, multi-session ground-to-aerial place recognition in forests. M3GA-Wild unifies and extends existing forest localisation datasets, providing a holistic benchmark with synchronised RGB imagery and LiDAR from ground traversals spanning 36 km, aligned high-resolution aerial imagery and multi-altitude LiDAR covering 370 hectares, and accurate geo-referenced 6-DoF poses for precise evaluation. M3GA-Wild captures diverse forest scenes with varying viewpoints, occlusion, and environmental conditions, enabling systematic evaluation of visual, LiDAR, cross-modal, and multi-modal methods. Baseline experiments show that LiDAR-based approaches significantly outperform vision-only methods under severe viewpoint differences, while current multi-modal fusion strategies yield limited gains due to poor cross-modal alignment. By pairing aerial RGB imagery with geo-referenced aerial LiDAR, M3GA-Wild also enables evaluation of foundation models for

---

### [241] Detecting Agitation Before Behavioral Escalation in Autistic Youth Through Multimodal Wearable Sensing

**链接**: https://arxiv.org/abs/2609.24791
**作者**: Nibraas Khan, Abigale Plunk, John Staubitz, Ingrid Shragge, Jordan Brooks, Suzanne Wright 等 (10 人)
**来源**: cs.HC cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Challenging behaviors including aggression, self-injury, and property destruction are observed in 68% of autistic youth and pose risks to youth and caregivers. These episodes are preceded by agitation, a rising state of distress expressed through movement, vocalization, and autonomic arousal. Its signs are subtle and individualized, and its autonomic components are invisible without instrumentation. We collected upper-body movement from inertial measurement units, physiology from a wrist-worn device, and vocalizations from lapel microphones across 30 clinician-led sessions with 15 autistic youth, paired with expert behavioral annotations. We adapt four pretrained foundation models, one per modality, project each to a shared 128-dimensional space, and fuse them into a single group model. The model detected agitation with an area under the ROC curve of 0.724 at the clinician-annotated onset (within-participant permutation p=0.0005), declining to 0.608 at 30,s before onset. Thirteen of fi

---

### [242] HumynexSurg-1: A Curated Expert Liposuction Dataset

**链接**: https://arxiv.org/abs/2609.23885
**作者**: Rhea Huang, David L. Matlock, Laurence Reich
**来源**: cs.RO cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot foundation models learn manipulation from large demonstration corpora, but surgery is missing from those corpora: across the 780-hour Open-H surgical collection, one dataset carries synchronized force and none covers an aesthetic procedure. Liposuction is the hard case, because the instrument works under the skin and the surgeon operates by feel and by judgment. Humynex Robotics builds curated expert datasets for this kind of procedure. HumynexSurg-1 is the first release: a master liposuction surgeon performing on porcine abdominal tissue while narrating every decision, recorded with synchronized suction pressure, six-axis hand force/torque, top-down RGB-D video, side video and a lavalier microphone -- 14 episodes, 42,738 frames, 35.6 minutes, 356 utterances of which 95% compile into a liposuction-specific label schema. The capture follows a patent-pending sensing plan organized around the quantities a policy needs, so a channel captured today by a model can be upgraded to a sens

---

### [243] $t_0$: A Time-Series Foundation Model for Forecasting with Context

**链接**: https://arxiv.org/abs/2609.24559
**作者**: Lucas Meyer, Claudio Sole, Huikan Xiang, Nicolas Li, Lucas Franceschino, Arnau Quera-Bofarull 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present $t_0$, a family of open-weights foundation models for forecasting with multivariate context. We release its first two members: $\texttt{t0-alpha}$ and $\texttt{t0-beta}$, respectively 102M and 256M parameters. Both condition their forecasts on target history, past covariates, and known-future covariates, without task-specific retraining. Their transformer layers alternate attention along time and across variates. They produce probabilistic forecasts through quantile predictions. Pretraining combines curated public data with synthetic generator families constructed to contain covariate-to-target dependencies. On GIFT-Eval, $\texttt{t0-alpha}$ reaches an aggregate CRPS of 0.4941, and $\texttt{t0-beta}$ a CRPS of 0.4738 and a MASE of 0.6865, third on both and within 4.0% of the best zero-shot TSFM. On fev-bench they score 42.2 and 46.7 in skill, the latter third again and 2.0 points behind the leader. We analyze $\texttt{t0-alpha}$ in depth. Known-future covariates raise its sk

---

### [244] DiagGen: Agentic Generation of Deformable Assets with Sim-based Diagnostics for Robotic Simulation

**链接**: https://arxiv.org/abs/2609.23103
**作者**: Guanxiong Chen, Yiduo Qu, Qianjun Xia, Pengyu Jing, Yixian Cheng, Bole Ma 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While simulation-ready deformable assets are essential for in-silico robotic manipulation tasks, existing generation frameworks typically assess physical plausibility after generation, leaving an object's simulated response unused as feedback for repairing upstream errors. We present DiagGen, an agentic framework that turns a single in-the-wild image into a simulation-ready deformable asset through a generate--simulate--diagnose--refine loop. DiagGen constructs part-aware geometry and material parameters, then uses a VLM (vision-language model)-based agent to select semantically informative regions, probe them in a physics simulator, observe material responses, and route evidence-backed repair cues to the responsible generation stage. Experiments on 40 assets show that diagnostics provides useful repair cues and can moderately improve the quality of generated deformable assets. Finally, we show that unlike assets generated from visual foundation models which may not be simulatable, Dia

---

### [245] TRACE: Tractable Routing Autoencoder for Clinical ECG

**链接**: https://arxiv.org/abs/2609.23460
**作者**: Shunbo Jia, Runze Ma, Haonan Lyu, Haijin Zhang, Qiang Yang and Caizhi Liao
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning has advanced automated electrocardiogram (ECG) diagnosis, but the field's most accurate models, foundation models pretrained on millions of recordings, are not decision-pathway auditable: a clinician cannot trace a diagnosis to a physiological pathway or intervene on one. We propose TRACE, a Tractable Routing Autoencoder for Clinical ECG, whose 32-dimensional clinical latent space is specified in advance from domain knowledge rather than discovered by optimization. TRACE partitions this space into perfusion, structure, and conduction subspaces, routes each to its own diagnostic head by design, regularizes the partition with an orthogonality penalty, and reconstructs the ECG through a decoder that permits latent perturbation. On PTB-XL and Georgia, TRACE exceeds unconstrained classifiers and stays ahead of an ECG foundation model pretrained on ten million recordings, evaluated by linear probe on frozen features, at roughly an eighth of the parameter count. On the nine-labe

---

### [246] 0.5\%>100\%: Bidirectional Reciprocal Learning for Referring Image Segmentation

**链接**: https://arxiv.org/abs/2609.24510
**作者**: Xiaoqiang Lu, Licheng Jiao, Lingling Li, Yuting Yang, Long Sun, Wenping Ma 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in vision foundation models (VFMs) have shown remarkable capabilities across diverse unimodal visual tasks. However, adapting VFMs to referring image segmentation (RIS) typically necessitates precise vision-language alignment via full fine-tuning, incurring substantial computational overhead and risking catastrophic forgetting. While existing parameter-efficient fine-tuning (PEFT) methods enable safe knowledge transfer with minimal training costs, they predominantly operate independently within individual modalities or focus exclusively on unidirectional guidance from language to vision, overlooking progressive cross-modal interaction and visual feedback for textual refinement. To address these limitations, we propose Bidirectional Reciprocal Learning (BRL), a novel adapter-based PEFT framework that facilitates hierarchical, bidirectional information flow within both token-mixing and channel-mixing layers of frozen foundation models. Specifically, BRL introduces two com

---

### [247] SRPR-Net: Semantic and Relational Prompt Refinement for Automated SAM-based Instance Segmentation

**链接**: https://arxiv.org/abs/2609.24226
**作者**: Lufei Liu, Guojie Li, Suncheng Xiang, Fan Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Instance segmentation is a fundamental computer vision task with diverse real-world applications. Recently, prompt-driven foundation models have shown promising generalization. However, automated prompting remains limited by insufficient semantic guidance and inter-instance modeling. To address this challenge, we propose a novel architecture, named Semantic Relational Prompt Refinement Network (SRPR-Net), for automated SAM-based instance segmentation. A sequential prompt refinement mechanism is introduced to enrich detector geometry with visual-language semantics and then incorporate same-image instance dependencies, enabling context-aware box adjustment before SAM segmentation. Experiments on multiple standard benchmarks demonstrate that SRPR-Net achieves consistent improvements in segmentation performance over existing state-of-the-art approaches. The code is publicly available at https://github.com/JeremyXSC/SRPR-Net.

---

### [248] Performance vs Consistency: Evaluating a Foundation Model in Lung-RADS Screening

**链接**: https://arxiv.org/abs/2609.22281
**作者**: Benjamin Renoust, Pierre Baudot, Tiffany Foriel, Yousra Haddou, Charles Voyton, Pierre-Henri Siot 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models have recently demonstrated strong capabilities across a wide range of medical imaging tasks. However, their performance in structured clinical interpretation settings remains insufficiently explored. In lung cancer screening, interpretative variability persists despite standardized frameworks such as Lung-RADS. In this study, we evaluate MedGemma, a medical general-purpose foundation model derived from Gemini and its fine-tuned version adapted for lung cancer detection and diagnosis, compared against radiologists performing Lung-RADS v2022 assessment on the NLST dataset. Twelve radiologists independently evaluated each case in a multi-reader design, enabling quantification of inter-reader variability. Radiologists achieved a mean AUC of 0.90, with substantial variability across readers (range: 0.80-0.94). The native foundation model achieved an AUC of 0.70, failing to reach clinically relevant performance. In contrast, fine-tuning significantly improved performance to

---

### [249] SPHQuant: Efficient extreme low bit weight quantization for Vision-Language Models

**链接**: https://arxiv.org/abs/2609.24875
**作者**: Kewei Zhang, Zheng Chen, Haotong Qin, Yulun Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent foundation models are moving toward native multimodal Vision-Language Models (VLMs), making VLMs a central form of next-generation foundation models. However, their large language backbones make edge deployment difficult due to high memory footprint and memory-bound autoregressive decoding. Weight-only post-training quantization is a practical solution, but pushing VLMs to extreme low bit-widths remains challenging: existing rotation-free methods suffer from outliers at 2-3 bits, while rotation-based methods improve accuracy at the cost of additional runtime overhead. We propose SPHQuant, a rotation-free spherical weight-only quantization framework for VLMs. Instead of quantizing weights directly in Cartesian coordinates, SPHQuant decomposes each 8D weight vector into coordinate signs, radius, and a positive unit direction. This representation isolates outlier magnitude into the radius while keeping directions bounded and statistically regular. Based on this insight, SPHQuant al

---

### [250] PanoSeg3R: Feed-Forward 3D Semantic Segmentation for Panoramic Images with an Automatic Data Curation Pipeline

**链接**: https://arxiv.org/abs/2609.22687
**作者**: Heechan Yoon, Dongki Jung, Phuc Nguyen, Ming Lin, Dinesh Manocha
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present PanoSeg3R, a feed-forward framework for 3D panoramic semantic segmentation. Unlike existing methods designed for perspective inputs, PanoSeg3R jointly predicts 3D geometry and multi-view semantic segmentation in one single forward pass. Built upon a pretrained reconstruction backbone that supports panoramic images, our approach extends feed-forward 3D reconstruction with a query-based mask decoder. Furthermore, we introduce an automatic panorama data curation pipeline that leverages the complementary strengths of off-the-shelf foundation models to generate reliable pseudo semantic annotations, substantially expanding the training data and improving zero-shot generalization. PanoSeg3R achieves state-of-the-art performance on panoramic 3D semantic segmentation, improving 3D mIoU by up to 16.02 on ScanNet++, while the curated training data further improves zero-shot performance by up to 4.26 and 43.28 mIoU on Stanford2D3D and ToF-360, respectively. Website: https://harryyoon777

---

### [251] Colon3R: Cross-Domain 3D Reconstruction from Monocular Colonoscopic Video

**链接**: https://arxiv.org/abs/2609.23961
**作者**: Zhihao Xing, Yingyu Wang, Liang Zhao, Shoudong Huang
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Monocular colonoscopic 3D reconstruction is important for surgical robotic colonoscopy, but remains challenging due to weak texture, specular reflections, limited view overlap, and non-rigid tissue motion. Conventional multi-view 3D reconstruction methods rely on stable correspondences and approximate rigidity, which are often violated in colonoscopy. Existing endoscopic methods often rely on domain-specific supervision, whereas there are not enough in-vivo labeled data available to adapt geometry foundation models to clinical colonoscopy. We present Colon3R, a cross-domain semi-supervised framework built on pretrained VGGT that transfers coupled camera, depth, and pointmap geometry from labeled phantom and simulated data to unlabeled in-vivo colonoscopy without requiring target-domain geometric annotations. Unlike source-only fine-tuning, which learns only from phantom and simulated data, Colon3R directly exploits unlabeled in-vivo video through teacher-derived cross-view supervision.

---

### [252] SAFe: Segment-guided Aggregation of Feature Densities for Anomaly-aware Segmentation

**链接**: https://arxiv.org/abs/2609.24204
**作者**: Anja Deli\'c, Jurica Runtas, Marin Or\v{s}i\'c, Ivan Markovi\'c, Ivan Petrovi\'c
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual segmentation systems encounter objects outside their training distribution during real-world deployment, hindering reliable autonomous systems that depend on scene parsing in the perception stage. Many recent methods address this by using self-supervised foundation models to train density estimators that yield low likelihood in anomalous image regions. Although promising, these methods suffer from poor feature semantics or they lack spatial consistency, both of which undermine critical downstream decisions. We address this problem with~\method, a generative method based on class-conditional density estimation over self-supervised representations. SAFe trains lightweight normalizing flows that produce class-conditional normalized likelihood estimates over frozen DINOv3 features. We combine density estimates from transformer features with density scores over multi-scale convolutional features to capture both global semantics and local detail. We introduce a method-agnostic post-pr

---

### [253] A Hybrid Attention Model Learning Unified Time-aware Patch Representation for Irregular Multivariate Time Series Forecasting

**链接**: https://arxiv.org/abs/2609.22836
**作者**: Zhihao Lin, Li Lin, Qi Zhang, Kaiwen Xia, Shuai Wang, Jialin Qiao
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) have recently delivered impressive zero-shot performance across diverse forecasting tasks. However, real-world decision-making frequently relies on \emph{irregular multivariate time series} (IMTS), where inconsistent inter-observation intervals and asynchronous sampling across variables coexist with informative missingness. Existing TSFMs handle such inputs either through imputation that injects spurious values or through index-based positional encodings that ignore continuous time. There is still a gap in the foundation model that follows the original IMTS patterns. In this paper, we propose a hybrid attention model that learns a unified time-aware patch representation for IMTS forecasting. We first design a \emph{time-aware patch encoding} that maps a variable number of intra-patch timestamps into a fixed-size embedding, producing a uniform format for irregular patches without resorting to imputation. We then introduce a \emph{time bias attention

---

### [254] Human-Level Accuracy, Non-Human Strategies: Revealing Model-Human Divergence in Video Physical Reasoning

**链接**: https://arxiv.org/abs/2609.22788
**作者**: Fanhong Li, Shurui Zheng, Zi Yin, Junbo Cui, Lei Ji, Jia Liu
**来源**: cs.CV stat.AP
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video foundation models now reach human-level accuracy on physical-reasoning benchmarks, yet such tasks require predicting unobserved physical outcomes. Do these models perform human-like forward simulation, or do they exploit statistical regularities in visible scenes? Accuracy alone cannot distinguish these strategies. We introduce a distributional evaluation framework that treats model seeds and human raters as populations, enabling comparison of consensus, uncertainty, and strategy. On the Physion benchmark, we evaluate three ViT-L architectures (V-JEPA2, VideoMAEv2, DINOv2). V-JEPA2 narrows the accuracy gap to ~1 percentage point (73.2% vs. 74.2%), yet model-human disagreement reaches 26.4%, far exceeding human-human disagreement (4.8%), with substantially lower agreement (kappa ~ 0.48 vs. 0.91). The divergence follows forward-simulation demands: models outperform humans on geometric reasoning (linking, +11.8 pp) but underperform on gravitational dynamics (rolling, -11.8 pp) and c

---

### [255] SatOV: Restoring Spatial Priors for Training-Free Open-Vocabulary Segmentation in Remote Sensing Imagery

**链接**: https://arxiv.org/abs/2609.22834
**作者**: Changhao Zhao, Linglin Zeng, Hai Liu
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-vocabulary semantic segmentation (OVS) of remote sensing imagery is a challenging pixel-level task requiring strong generalization and adaptation to the spatial characteristics of remote sensing data. Although existing vision-language foundation models perform well in general domains, their image-level classification design weakens the spatial priors needed for high-resolution remote sensing segmentation: structural spatial relations are degraded during deep feature transformation, and fine-grained spatial details are lost during downsampling. To address these complementary deficiencies, we propose SatOV, a training-free framework for open-vocabulary remote sensing segmentation that restores spatial priors at two stages of the representation pipeline. Specifically, Residual QQ Attention (ResQQ) extracts Query-Key self-attention from an intermediate CLIP layer and fuses it with final-layer Query-Query attention via a residual combination, restoring structural spatial priors suppres

---

### [256] LEAP-NBV: Lightweight Edge Active-Perception for Foundation-Model Next-Best-View Planning

**链接**: https://arxiv.org/abs/2609.23974
**作者**: Boxun Hu, Jiawei Ge, Axel Krieger, Peng Wang, Tinoosh Mohsenin
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are endowing autonomous systems with greater intelligence, enabling a more comprehensive understanding of the environment through visual perception. A representative example is Human Mesh Recovery (HMR), which provides useful estimates of a target's 3D pose and shape that can benefit tactical missions. However, the size and power demands of such models make them difficult to run on edge platforms and limit their real-time performance, undermining the requirements of tactical edge deployment - especially for active perception, where a mobile robot must plan its next-best view on-board and cannot offload computation under contested communications. We present LEAP-NBV, a lightweight active-perception framework that runs foundation-model-driven Next-Best-View (NBV) planning on-board an edge device. To this end, we distill a family of large HMR teachers, each into a compact 32M student, with an offline mesh objective, then quantize the vision encoder to FP16 and characteri

---
