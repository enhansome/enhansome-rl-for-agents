# Awesome RL for Agents with stars

A curated list of reinforcement learning (RL) for agents.

> This list collects papers, tools, and demos that demonstrate how reinforcement learning can be applied to train or tune LLM/MLLM agents, with a focus on research-driven, computer-using, and tool-integrated agent behaviors. It is not associated with any survey or review — just a personal, living collection of resources on RL for agents. I’ll keep updating it as long as I’m still working in this area.

***

## Table of Contents

* [📚 Papers & Research](#-papers--research)
* [🕹️ Benchmarks](#-benchmarks)
* [🧪 Demos & Projects](#-demos--projects)
* [🧰 Toolkits & Frameworks](#-toolkits--frameworks)
* [📄 Tutorials & Blog Posts](#-tutorials--blog-posts)
* [🔗 Related Awesome Lists](#-related-awesome-lists)
* [🤝 Contributing](#-contributing)

***

## 📚 Papers & Research

### Survey & Review

* The Landscape of Agentic Reinforcement Learning for LLMs: A Survey [\[Preprint'25\]](https://arxiv.org/abs/2509.02547) [\[AwesomeList\]](https://github.com/xhyumiracle/Awesome-AgenticLLM-RL-Papers) ⭐ 1,874 | 🐛 7 | 📅 2026-06-18
* **Deep Research Agents**: A Systematic Examination And Roadmap [\[Preprint'25\]](https://arxiv.org/abs/2506.18096) [\[AwesomeList\]](https://github.com/ai-agents-2030/awesome-deep-research-agent) ⭐ 638 | 🐛 10 | 📅 2025-09-18
* A Survey of LLM-based Deep Search Agents: Paradigm, Optimization, Evaluation, and Challenges [\[Preprint'25\]](https://arxiv.org/abs/2508.05668) [\[AwesomeList\]](https://github.com/YunjiaXi/Awesome-Search-Agent-Papers) ⭐ 188 | 🐛 2 | 📅 2026-08-13

### RL for Computer-using Agents

* **UI-TARS-2 Technical Report**: Advancing GUI Agent with Multi-Turn Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2509.02544) [\[Code\]](https://github.com/bytedance/UI-TARS) ⭐ 11,376 | 🐛 56 | 🌐 Python | 📅 2026-01-27
* **AutoWebGLM**: A Large Language Model-based Web Navigating Agent [\[KDD'24\]](https://dl.acm.org/doi/10.1145/3637528.3671620) [\[Preprint'24\]](https://arxiv.org/abs/2404.03648) [\[Code\]](https://github.com/THUDM/AutoWebGLM) ⭐ 930 | 🐛 14 | 🌐 Python | 📅 2024-09-27
* **OPENCUA**: OpenFoundations for Computer-Use Agents [\[Preprint'25\]](https://arxiv.org/abs/2508.09123) [\[Code\]](https://github.com/xlang-ai/OpenCUA) ⭐ 825 | 🐛 15 | 🌐 Python | 📅 2026-05-25
* **TMax**: A Simple Recipe for Terminal Agents [\[Preprint'26\]](https://arxiv.org/abs/2606.23321) [\[Code\]](https://github.com/hamishivi/tmax) ⭐ 283 | 🐛 2 | 🌐 Python | 📅 2026-08-13 [\[Blog\]](https://wai-org.com/blog/tmax/#training-tmax-with-rl)
* **ARPO**: End-to-End Policy Optimization for GUI Agents with Experience Replay [\[Preprint'25\]](https://arxiv.org/abs/2505.16282) [\[Code\]](https://github.com/dvlab-research/ARPO) ⭐ 163 | 🐛 9 | 🌐 Python | 📅 2025-05-29
* **UI-R1**: Enhancing Action Prediction of GUI Agents by Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs//2503.21620) [\[Code\]](https://github.com/lll6gg/UI-R1) ⭐ 160 | 🐛 0 | 🌐 Python | 📅 2025-11-24
* **Digi-Q**: Learning Q-Value Functions for Training Device-Control Agents [\[Preprint'25\]](https://arxiv.org/abs/2502.15760) [\[Code\]](https://github.com/DigiRL-agent/digiq) ⭐ 121 | 🐛 0 | 🌐 Python | 📅 2025-04-08
* **InfiGUI-R1**: Advancing Multimodal GUI Agents from Reactive Actors to Deliberative Reasoners [\[Preprint'25\]](https://arxiv.org/abs/2504.14239) [\[Code\]](https://github.com/Reallm-Labs/InfiGUI-R1) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2025-12-04
* **Cracking the Code of Action**: a Generative Approach to Affordances for Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2504.17282)

### RL for Research Agents

* **Tongyi DeepResearch**: A New Era of Open-Source AI Researchers [\[Blog\]](https://tongyi-agent.github.io/blog/introducing-tongyi-deep-research/) [\[Code\]](https://github.com/Alibaba-NLP/DeepResearch) ⭐ 19,870 | 🐛 92 | 🌐 Python | 📅 2026-02-27
* **WebShaper**: Towards Autonomous Information Seeking Agency [\[Preprint'25\]](https://arxiv.org/abs/2507.15061) [\[Code\]](https://github.com/Alibaba-NLP/WebAgent) ⭐ 19,870 | 🐛 92 | 🌐 Python | 📅 2026-02-27
* **WebSailor**: Navigating Super-human Reasoning for Web Agent [\[Preprint'25\]](https://arxiv.org/abs/2507.02592) [\[Code\]](https://github.com/Alibaba-NLP/WebAgent) ⭐ 19,870 | 🐛 92 | 🌐 Python | 📅 2026-02-27
* **Search-R1**: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning [\[COLM'25\]](https://arxiv.org/abs/2503.09516) [\[Code\]](https://github.com/petergriffinjin/search-r1) ⭐ 5,325 | 🐛 36 | 🌐 Python | 📅 2025-11-13
* **ReCall**: Learning to Reason with Tool Call for LLMs via Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2503.19470) [\[Code\]](https://github.com/Agent-RL/ReCall) ⭐ 1,431 | 🐛 30 | 🌐 Python | 📅 2025-05-16
* **ZeroSearch**: Incentivize the Search Capability of LLMs without Searching [\[Preprint'25\]](https://arxiv.org/abs/2505.04588) [\[Code\]](https://github.com/Alibaba-nlp/ZeroSearch) ⭐ 1,306 | 🐛 0 | 🌐 Python | 📅 2025-08-16
* **ARPO**: Agentic Reinforced Policy Optimization [\[Preprint'25\]](https://arxiv.org/abs/2507.19849) [\[Code\]](https://github.com/dongguanting/ARPO) ⭐ 1,109 | 🐛 1 | 🌐 Python | 📅 2026-08-20
* **DeepResearcher**: Scaling Deep Research via Reinforcement Learning in Real-world Environments [\[EMNLP'25\]](https://arxiv.org/abs/2504.03160) [\[Code\]](https://github.com/GAIR-NLP/DeepResearcher) ⭐ 797 | 🐛 9 | 🌐 Python | 📅 2026-05-10
* **R1-Searcher**: Incentivizing the Search Capability in LLMs via Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2503.05592) [\[Code\]](https://github.com/RUCAIBox/R1-Searcher) ⭐ 723 | 🐛 21 | 🌐 Python | 📅 2025-08-05
* Beyond Ten Turns: Unlocking Long-Horizon Agentic Search with Large-Scale Asynchronous RL [\[Preprint'25\]](https://arxiv.org/abs/2508.07976v2) [\[Code\]](https://github.com/inclusionAI/ASearcher) ⭐ 608 | 🐛 14 | 🌐 Python | 📅 2025-11-26
* **Cognitive Kernel-Pro**: A Framework for Deep Research Agents and Agent Foundation Models Training [\[Preprint'25\]](https://arxiv.org/abs/2508.00414) [\[Code\]](https://github.com/Tencent/CognitiveKernel-Pro) ⭐ 530 | 🐛 3 | 🌐 Python | 📅 2026-04-29
* **SSRL**: Self-Search Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2508.10874) [\[Code\]](https://github.com/TsinghuaC3I/SSRL) ⭐ 210 | 🐛 0 | 🌐 Python | 📅 2025-08-20
* **REDSearcher**: A Scalable and Cost-Efficient Framework for Long-Horizon Search Agents [\[Preprint'26\]](https://arxiv.org/abs/2602.14234) [\[Code\]](https://github.com/RedSearchAgent/REDSearcher) ⭐ 141 | 🐛 7 | 📅 2026-02-26
* **R1-Searcher++**: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2505.17005) [\[Code\]](https://github.com/RUCAIBox/R1-Searcher-plus) ⭐ 82 | 🐛 5 | 🌐 Python | 📅 2025-05-25
* **R-Search**: Empowering LLM Reasoning with Search via Multi-Reward Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2506.04185) [\[Code\]](https://github.com/QingFei1/R-Search) ⭐ 35 | 🐛 3 | 🌐 Python | 📅 2026-08-11
* **ArenaRL**: Scaling RL for Open-Ended Agents via Tournament-based Relative Ranking [\[Preprint'26\]](https://arxiv.org/abs/2601.06487)
* **IterResearch**: Rethinking Long-Horizon Agents via Markovian State Reconstruction [\[Preprint'25\]](https://arxiv.org/abs/2511.07327)
* Tree Search for LLM Agent Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2509.21240)
* **MiroMind Open Deep Research** [\[Blog\]](https://miromind.ai/blog/miromind-open-deep-research) [\[Code\]](https://github.com/MiroMindAI)
* **Kimi-Researcher**: End-to-End RL Training for Emerging Agentic Capabilities [\[Blog\]](https://moonshotai.github.io/Kimi-Researcher/)
* **Agentic Reasoning**: Reasoning LLMs with Tools for the Deep Research [\[Preprint'25\]](https://arxiv.org/abs/2502.04644) [\[Code\]](https://github.com/theworldofagents/Agentic-Reasoning)

### RL for Tool-using Problem Solver

* **VerlTool**: Towards Holistic Agentic Reinforcement Learning with Tool Use [\[Preprint'25\]](https://arxiv.org/abs/2509.01055) [\[Code\]](https://github.com/TIGER-AI-Lab/verl-tool) ⭐ 1,034 | 🐛 9 | 🌐 Python | 📅 2026-07-15
* **ToolRL**: Reward is All Tool Learning Needs [\[Preprint'25\]](https://arxiv.org/abs/2504.13958) [\[Code\]](https://github.com/qiancheng0/ToolRL) ⭐ 515 | 🐛 2 | 🌐 Python | 📅 2025-10-16
* **TORL**: Scaling Tool-Integrated RL [\[Preprint'25\]](https://arxiv.org/pdf/2503.23383) [\[Code\]](https://github.com/GAIR-NLP/ToRL) ⭐ 352 | 🐛 24 | 🌐 Python | 📅 2025-05-24
* **Agent models**: Internalizing Chain-of-Action Generation into Reasoning models [\[Preprint'25\]](https://arxiv.org/abs/2503.06580) [\[Code\]](https://github.com/ADaM-BJTU/AutoCoA) ⭐ 134 | 🐛 4 | 🌐 Python | 📅 2025-03-18
* **VisualToolAgent (VisTA)**: A Reinforcement Learning Framework for Visual Tool Selection [\[Preprint'25\]](https://arxiv.org/abs/2505.20289) [\[Code\]](https://github.com/OoDBag/VisTA) ⭐ 27 | 🐛 4 | 🌐 Python | 📅 2025-05-31
* Incentivizing Agentic Reasoning in LLM Judges via Tool-Integrated Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2510.23038)
* **OTC**: Optimal Tool Calls via Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2504.14870)
* **ReTool**: Reinforcement Learning for Strategic Tool Use in LLMs [\[Preprint'25\]](https://arxiv.org/abs/2504.11536)

### Self-Playing Agent with RL

* **Agent0-VL**: Exploring Self-Evolving Agent for Tool-Integrated Vision-Language Reasoning [\[Preprint'25\]](https://arxiv.org/abs/2511.19900) [\[Code\]](https://github.com/aiming-lab/Agent0) ⭐ 1,254 | 🐛 12 | 🌐 Python | 📅 2026-07-10
* **Agent0**: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning [\[Preprint'25\]](https://arxiv.org/abs/2511.16043) [\[Code\]](https://github.com/aiming-lab/Agent0) ⭐ 1,254 | 🐛 12 | 🌐 Python | 📅 2026-07-10
* **Search Self-play**: Pushing the Frontier of Agent Capability without Supervision [\[ICLR'26\]](https://arxiv.org/abs/2510.18821) [\[Code\]](https://github.com/Alibaba-Quark/SSP) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2026-07-23
* Toward Training Superintelligent Software Agents through Self-Play SWE-RL [\[Preprint'25\]](https://arxiv.org/abs/2512.18552)

### RL for Agent Memory

* **MemAgent**: Reshaping Long-Context LLM with Multi-Conv RL based Memory Agent [\[Preprint'25\]](https://arxiv.org/abs/2507.02259) [\[Code\]](https://github.com/BytedTsinghua-SIA/MemAgent) ⭐ 1,100 | 🐛 18 | 🌐 Python | 📅 2026-05-12
* **MEM1**: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents [\[Preprint'25\]](https://arxiv.org/abs/2506.15841)

### RL for Multi-Modal Agent (Thinking w Image / MMSearch)

* **DeepEyes**: Incentivizing "Thinking with Images" via Reinforcement Learning [\[ICLR'26\]](https://arxiv.org/abs/2505.14362) [\[Code\]](https://github.com/Visual-Agent/DeepEyes) ⭐ 1,269 | 🐛 93 | 🌐 Python | 📅 2025-11-20
* **DeepEyesV2**: Toward Agentic Multimodal Model [\[ICLR'26\]](https://arxiv.org/abs/2511.05271v1) [\[Code\]](https://github.com/Visual-Agent/DeepEyesV2) ⭐ 633 | 🐛 32 | 🌐 Python | 📅 2026-02-26
* **MMSearch-R1**: Incentivizing LMMs to Search [\[Preprint'25\]](https://arxiv.org/abs/2506.20670) [\[Code\]](https://github.com/EvolvingLMMs-Lab/multimodal-search-r1) ⭐ 479 | 🐛 3 | 🌐 Python | 📅 2026-04-07
* **Zooming without Zooming**: Region-to-Image Distillation for Fine-Grained Multimodal Perception [\[Preprint'26\]](https://arxiv.org/abs/2602.11858) [\[Code\]](https://github.com/inclusionAI/Zooming-without-Zooming) ⭐ 187 | 🐛 1 | 🌐 Python | 📅 2026-05-04

### RL with Agent Skills

* **SkillRL**: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning [\[Preprint'26\]](https://arxiv.org/abs/2602.08234) [\[Code\]](https://github.com/aiming-lab/SkillRL) ⭐ 945 | 🐛 0 | 🌐 Python | 📅 2026-05-17

### Reinforcement Learning Scaling

* **DAPO**: An Open-Source LLM Reinforcement Learning System at Scale [\[Preprint'25\]](https://arxiv.org/abs/2503.14476v1) [\[Code\]](https://github.com/BytedTsinghua-SIA/DAPO) ⭐ 1,861 | 🐛 25 | 🌐 Python | 📅 2025-05-11
* **Skywork-OR1 (Open Reasoner 1)** [\[Blog\]](https://capricious-hydrogen-41c.notion.site/Skywork-Open-Reaonser-Series-1d0bc9ae823a80459b46c149e4f51680) [\[Code\]](https://github.com/SkyworkAI/Skywork-OR1) ⭐ 738 | 🐛 17 | 🌐 Python | 📅 2025-06-06
* **LIMR**: Less is More for RL Scaling [\[Preprint'25\]](https://arxiv.org/abs/2502.11886) [\[Code\]](https://github.com/GAIR-NLP/LIMR) ⭐ 222 | 🐛 15 | 🌐 Python | 📅 2025-02-20
* The Art of Scaling Reinforcement Learning Compute for LLMs [\[Preprint'25\]](https://arxiv.org/abs/2510.13786)
* Group Sequence Policy Optimization [\[Preprint'25\]](https://arxiv.org/abs/2507.18071)
* **Skywork R1V2**: Multimodal Hybrid Reinforcement Learning for Reasoning [\[Preprint'25\]](https://arxiv.org/abs/2504.16656) [\[Model\]](https://huggingface.co/Skywork/Skywork-R1V2-38B)
* A Minimalist Approach to LLM Reasoning: from Rejection Sampling to Reinforce [\[Preprint'25\]](https://arxiv.org/abs/2504.11343)
* **o3 & o4-mini**: Introducing OpenAI o3 and o4-mini [\[Blog\]](https://openai.com/index/introducing-o3-and-o4-mini/)
* **VAPO**: Efficient and Reliable Reinforcement Learning for Advanced Reasoning Tasks [\[Preprint'25\]](https://arxiv.org/abs/2504.05118)
* **DeepSeek-R1**: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning [\[Preprint'25\]](https://arxiv.org/abs/2501.12948)
* **Kimi k1.5**: Scaling Reinforcement Learning with LLMs [\[Preprint'25\]](https://arxiv.org/abs/2501.12599)

### Others

* Seed-1.8 [\[Code\]](https://github.com/ByteDance-Seed/Seed-1.8) ⭐ 220 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-12-19
* **dots3-note Preview**: A Small but Mighty Step Toward Long-Horizon Agency in Real Life [\[Blog\]](https://studio.dots.ai/dots/dots3-en.html) [\[Code\]](https://github.com/studio-dots-ai/dots3-note-prev) ⭐ 112 | 🐛 0 | 📅 2026-08-14
* **MPO**: Boosting LLM Agents with Meta Plan Optimization [\[Preprint'25\]](https://arxiv.org/abs/2503.02682) [\[Code\]](https://github.com/WeiminXiong/MPO) ⭐ 82 | 🐛 7 | 🌐 Python | 📅 2025-08-20
* **UFO**: A Simple "Try Again" Can Elicit Multi-Turn LLM Reasoning [\[Preprint'25\]](https://arxiv.org/abs/2507.14295) [\[Code\]](https://github.com/lichengliu03/unary-feedback) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2026-03-31
* Self-Challenging Language Model Agents [\[Preprint'25\]](https://arxiv.org/abs/2506.01716v1)

## 🕹 Benchmarks

### CLI

* **Terminal-Bench**: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces [\[Preprint'26\]](https://arxiv.org/abs/2601.11868) [\[Website\]](https://www.tbench.ai/) [\[Code\]](https://github.com/harbor-framework/terminal-bench) ⭐ 536 | 🐛 241 | 🌐 Python | 📅 2026-08-23

### Deep research

* **BrowseComp**: a benchmark for browsing agents [\[Blog\]](https://openai.com/index/browsecomp/) [\[Paper\]](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) [\[Code\]](https://github.com/openai/simple-evals) ⭐ 4,610 | 🐛 60 | 🌐 Python | 📅 2026-04-22
* **Vision-DeepResearch Benchmark**: Rethinking Visual and Textual Search for Multimodal Large Language Models [\[Preprint'26\]](https://arxiv.org/abs/2602.02185) [\[Code\]](https://github.com/Osilly/Vision-DeepResearch) ⭐ 677 | 🐛 5 | 🌐 Python | 📅 2026-08-08
* **Marco Search Agent**: Towards Real‑World and Challenging Agentic Search (including HSCodeComp and DeepWideSearch) [\[Preprint'25(1)\]](https://arxiv.org/abs/2510.19631) [\[Preprint'25(2)\]](https://arxiv.org/abs/2510.20168) [\[Code\]](https://github.com/AIDC-AI/Marco-Search-Agent) ⭐ 328 | 🐛 4 | 🌐 Python | 📅 2026-08-09
* Watching, Reasoning, and Searching: A Video Deep Research Benchmark on Open Web for Agentic Video Reasoning [\[Preprint'26\]](https://arxiv.org/abs/2601.06943) [\[Code\]](https://github.com/QuantaAlpha/VideoDR-Benchmark) ⭐ 161 | 🐛 0 | 🌐 Python | 📅 2026-05-19
* **BrowseComp-ZH**: Benchmarking the Web Browsing Ability of Large Language Models in Chinese [\[Preprint'25\]](https://arxiv.org/abs/2504.19314) [\[Code\]](https://github.com/PALIN2018/BrowseComp-ZH) ⭐ 161 | 🐛 6 | 🌐 Python | 📅 2025-05-14
* **OmniGAIA**: Towards Native Omni-Modal AI Agents [\[Preprint'26\]](https://arxiv.org/abs/2602.22897) [\[Code\]](https://github.com/RUC-NLPIR/OmniGAIA) ⭐ 145 | 🐛 1 | 🌐 Python | 📅 2026-04-02
* **AgentVista**: Evaluating Multimodal Agents in Ultra-Challenging Realistic Visual Scenarios [\[Preprint'26\]](https://arxiv.org/abs/2602.23166) [\[Code\]](https://github.com/hkust-nlp/AgentVista) ⭐ 72 | 🐛 0 | 🌐 Python | 📅 2026-03-10
* **MM-BrowseComp**: A Comprehensive Benchmark for Multimodal Browsing Agents [\[ICLR'26\]](https://arxiv.org/abs/2508.13186) [\[Code\]](https://github.com/MMBrowseComp/MM-BrowseComp) ⭐ 71 | 🐛 2 | 🌐 Python | 📅 2026-01-04
* **MMSearch-Plus**: Benchmarking Provenance-Aware Search for Multimodal Browsing Agents [\[Preprint'25\]](https://arxiv.org/abs/2508.21475) [\[Code\]](https://github.com/mmsearch-plus/MMSearch-Plus) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2026-02-06
* **FinSearchComp**: Towards a Realistic, Expert-Level Evaluation of Financial Search and Reasoning [\[Preprint'25\]](https://arxiv.org/abs/2509.13160) [\[Code\]](https://randomtutu.github.io/FinSearchComp/)
* **BrowseComp-Plus**: A More Fair and Transparent Evaluation Benchmark of Deep-Research Agent [\[Preprint'25\]](https://arxiv.org/abs/2508.06600v1) [\[Huggingface\]](https://huggingface.co/datasets/Tevatron/browsecomp-plus)
* **xbench**: Tracking Agents Productivity Scaling With Profession-Aligned Real-World Evaluations [\[Preprint'25\]](https://arxiv.org/abs/2506.13651) [\[Website\]](https://xbench.org/)

### Computer Use

* **OSWorld**: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments [\[NeurIPS'24\]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5d413e48f84dc61244b6be550f1cd8f5-Abstract-Datasets_and_Benchmarks_Track.html) [\[Code\]](https://github.com/xlang-ai/OSWorld) ⭐ 3,102 | 🐛 197 | 🌐 Python | 📅 2026-08-21
* **Agents' Last Exam** [\[Preprint'26\]](https://arxiv.org/abs/2606.05405) [\[Code\]](https://github.com/rdi-berkeley/agents-last-exam) ⭐ 967 | 🐛 22 | 🌐 Python | 📅 2026-08-21 [\[Website\]](https://agents-last-exam.org/)
* **ClawBench**: Can AI Agents Complete Everyday Online Tasks? [\[Preprint'26\]](https://arxiv.org/abs/2604.08523) [\[Code\]](https://github.com/TIGER-AI-Lab/ClawBench) ⭐ 581 | 🐛 59 | 🌐 Python | 📅 2026-08-22 [\[Website\]](https://claw-bench.com/)
* **SeeClick**: Harnessing GUI Grounding for Advanced Visual GUI Agents [\[ACL'24\]](https://aclanthology.org/2024.acl-long.505.pdf) [\[Code\]](https://github.com/njucckevin/SeeClick) ⭐ 495 | 🐛 3 | 🌐 HTML | 📅 2025-07-13
* **ScreenSpot-Pro**: GUI Grounding for Professional High-Resolution Computer Use [\[Paper\]](https://likaixin2000.github.io/papers/ScreenSpot_Pro.pdf) [\[Code\]](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) ⭐ 390 | 🐛 6 | 🌐 Python | 📅 2026-06-17
* **OSWorld 2.0**: Benchmarking Computer Use Agents on Long-Horizon Real-World Tasks [\[Preprint'26\]](https://arxiv.org/abs/2606.29537) [\[Code\]](https://github.com/xlang-ai/OSWorld-V2) ⭐ 256 | 🐛 8 | 🌐 Python | 📅 2026-08-19
* **Computer Agent Arena**: Compare & Test AI Agents on Crowdsourced Real-World Computer Use Tasks [\[Platform\]](https://arena.xlang.ai/) [\[Code\]](https://github.com/xlang-ai/computer-agent-arena) ⭐ 67 | 🐛 2 | 🌐 HTML | 📅 2026-02-26

## 🧪 Demos & Projects

### RL-based LLM agent tuning

* **OpenManus-RL** [\[Code\]](https://github.com/OpenManus/OpenManus-RL) ⭐ 4,153 | 🐛 27 | 🌐 Python | 📅 2026-05-05 & **OpenManus** [\[Code\]](https://github.com/mannaandpoem/OpenManus) ⭐ 639 | 🐛 24 | 📅 2025-06-21
* **RAGEN**: Training Agents by Reinforcing Reasoning [\[Code\]](https://github.com/ZihanWang314/ragen) ⭐ 2,775 | 🐛 29 | 🌐 Python | 📅 2026-08-23
* **SkyRL-v0**: Train Real-World Long-Horizon Agents via Reinforcement Learning [\[Blog\]](https://novasky-ai.notion.site/skyrl-v0) [\[Code\]](https://github.com/NovaSky-AI/SkyRL) ⭐ 2,190 | 🐛 436 | 🌐 Python | 📅 2026-08-22
* **Agent-R1**: Training Powerful LLM Agents with End-to-End Reinforcement Learning [\[Code\]](https://github.com/0russwest0/Agent-R1) ⭐ 1,628 | 🐛 43 | 🌐 Python | 📅 2026-08-17
* **VAGEN**: Training VLM Agents with Multi-Turn Reinforcement Learning [\[Code\]](https://github.com/RAGEN-AI/vagen) ⭐ 493 | 🐛 5 | 🌐 Python | 📅 2026-08-23
* **Terminal-Bench-RL**: Training Long-Horizon Terminal Agents with Reinforcement Learning [\[Code\]](https://github.com/Danau5tin/terminal-bench-rl) ⭐ 409 | 🐛 1 | 🌐 Python | 📅 2025-08-24
* **Claw-R1**: Empowering OpenClaw with Advanced Agentic RL [\[Page\]](https://agentr1.github.io/Claw-R1/) [\[Code\]](https://github.com/AgentR1/Claw-R1) ⭐ 195 | 🐛 1 | 🌐 Python | 📅 2026-08-22

### RL-based LLM tuning

* **Open-Reasoner-Zero**: An Open Source Approach to Scaling Up Reinforcement Learning on the Base Model [\[Preprint'25\]](https://arxiv.org/abs/2503.24290) [\[Code\]](https://github.com/Open-Reasoner-Zero/Open-Reasoner-Zero) ⭐ 2,099 | 🐛 21 | 🌐 Python | 📅 2025-06-02
* **simple\_GRPO** [\[Code\]](https://github.com/lsdefine/simple_GRPO) ⭐ 1,701 | 🐛 38 | 🌐 Python | 📅 2025-11-21

### MCP Agents

* **Agent2Agent (A2A) protocol** [\[Code\]](https://github.com/google/A2A) ⭐ 25,479 | 🐛 242 | 🌐 Shell | 📅 2026-08-21
* **mcp-agent** [\[Code\]](https://github.com/lastmile-ai/mcp-agent) ⭐ 8,518 | 🐛 135 | 🌐 Python | 📅 2026-01-25

## 🧰 Toolkits & Frameworks

* **verl**: Volcano Engine Reinforcement Learning for LLM [\[Code\]](https://github.com/volcengine/verl) ⭐ 23,107 | 🐛 1,152 | 🌐 Python | 📅 2026-08-24
* **slime**: An SGLang-Native Post-Training Framework for RL Scaling [\[Code\]](https://github.com/THUDM/slime) ⭐ 8,230 | 🐛 445 | 🌐 Python | 📅 2026-08-24
* **rLLM**: Reinforcement Learning for Language Agents [\[Code\]](https://github.com/rllm-org/rllm) ⭐ 5,797 | 🐛 152 | 🌐 Python | 📅 2026-08-24
* **Harbor**: A framework for evaluating and optimizing agents and models in container environments [\[Code\]](https://github.com/harbor-framework/harbor) ⭐ 4,574 | 🐛 724 | 🌐 Python | 📅 2026-08-24
* **ROLL**: Reinforcement Learning Optimization for Large-Scale Learning [\[Code\]](https://github.com/alibaba/ROLL) ⭐ 3,371 | 🐛 126 | 🌐 Python | 📅 2026-08-24
* **HUD**: A toolkit for building RL environments with verifiable, task-based rewards for LLM agents (coding, browser, computer-use, robotics), runnable as evals and RL training [\[Code\]](https://github.com/hud-evals/hud-python) ⭐ 294 | 🐛 7 | 🌐 Python | 📅 2026-08-24

## 📄 Tutorials & Blog Posts

* **Forge**: Scalable Agent RL Framework and Algorithm [\[Blog\]](https://www.minimax.io/news/forge-scalable-agent-rl-framework-and-algorithm)
* **Cut the Bill, Keep the Turns**: Affordable Multi-Turn Search RL [\[Blog\]](https://agate-slipper-ef0.notion.site/Cut-the-Bill-Keep-the-Turns-Affordable-Multi-Turn-Search-RL-003f78214a4d451fb06f453d084e666c)
* **Introducing ChatGPT agent**: bridging research and action [\[Blog\]](https://openai.com/index/introducing-chatgpt-agent/)
* **Context Engineering** [\[Github\]](https://github.com/davidkimai/Context-Engineering) ⭐ 9,225 | 🐛 3 | 🌐 Python | 📅 2026-02-27
* **The Second Half** [\[Blog\]](https://ysymyth.github.io/The-Second-Half/)

## 🔗 Related Awesome Lists

* **Agent-Memory-Paper-List** [\[List\]](https://github.com/Shichun-Liu/Agent-Memory-Paper-List) ⭐ 2,332 | 🐛 12 | 📅 2026-03-04 - covering agent memory papers
* **Awesome-AgenticLLM-RL-Papers** [\[List\]](https://github.com/xhyumiracle/Awesome-AgenticLLM-RL-Papers) ⭐ 1,874 | 🐛 7 | 📅 2026-06-18 - covering Agentic RL papers in both agentic capabilities and applications
* **Awesome Deep Research Agent** [\[List\]](https://github.com/ai-agents-2030/awesome-deep-research-agent) ⭐ 638 | 🐛 10 | 📅 2025-09-18 - covering deep research agents and benchmark results
* **Awesome-Agent-RL** [\[List\]](https://github.com/0russwest0/Awesome-Agent-RL) ⭐ 511 | 🐛 1 | 📅 2025-10-11 - covering RL for research agents
* **Awesome RL-based Agentic Search Papers** [\[List\]](https://github.com/ventr1c/Awesome-RL-based-Agentic-Search-Papers) ⭐ 290 | 🐛 2 | 📅 2026-07-30 - covering Agentic RL papers in agentic search systems
* **Awesome-Search-Agent-Papers** [\[List\]](https://github.com/YunjiaXi/Awesome-Search-Agent-Papers) ⭐ 188 | 🐛 2 | 📅 2026-08-13 - covering search agent papers
* **awesome-ml-agents** [\[List\]](https://github.com/tokarev-i-v/awesome-llm-rl-agents) ⭐ 1 | 🐛 0 | 📅 2023-08-27 - covering rl and agents before 2023

## 🤝 Contributing

Contributions are warmly welcome!

If you know a paper, tool, environment, or demo relevant to **RL for Agents**, feel free to open a pull request.

### Guidelines:

* Make sure the resource is publicly accessible and active.
* Use the same format as existing entries: `- **Name**: Title [Paper](link) [Code](link) – short description (optional).`
* Add entries under the most appropriate section.
* Avoid duplicates or resources that are already well-covered elsewhere.

We aim to keep this list high-quality, practical, and focused. Thank you for helping improve it! ✨

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
