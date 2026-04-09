# Papers with Keyword: Agent-Safety

- [AgentHazard: A Benchmark for Evaluating Harmful Behavior in Computer-Use Agents](https://arxiv.org/pdf/2604.02947)
    -  Yunhao Feng, Yifan Ding, Yingshui Tan, Xingjun Ma, Yige Li, Yutao Wu, Yifeng Gao, Kun Zhai, Yanming Guo
    - 🏛️ Institutions: Alibaba, Fudan University, Hunan Institute of Advanced Technology, Deakin University, Singapore Management University
    - 📅 Date: Apr. 3, 2026
    - 📑 Publisher: arXiv
    - 💻 Env: [Desktop]
    - 🔑 Key: [Agent-Safety], [evaluation], [dataset], [benchmark], [computer-use]
    - 📖 TLDR: Computer-use agents extend language models from text generation to persistent action across tools, files, and execution environments, introducing new safety risks. Unlike chat systems, they maintain state across interactions, allowing harmful behavior to emerge through sequences of individually plausible but collectively unsafe actions. We present AgentHazard, a benchmark for evaluating harmful behavior in computer-use agents. AgentHazard contains 2,653 instances spanning diverse risk categories and attack strategies, where each instance combines a harmful objective with operational steps that appear locally legitimate but jointly induce unsafe behavior. We evaluate Claude Code, OpenClaw, and IFlow using mostly open or openly deployable models from the Qwen3, Kimi, GLM, and DeepSeek families. Results show that current systems remain highly vulnerable: notably, Claude Code powered by Qwen3-Coder achieves an attack success rate of 73.63%, highlighting that model alignment alone does not reliably ensure agent safety.

- [A Trajectory-Based Safety Audit of Clawdbot (OpenClaw)](https://www.arxiv.org/pdf/2602.14364)
    -  Tianyu Chen, Dongrui Liu, Xia Hu, Jingyi Yu, Wenjie Wang
    - 🏛️ Institutions:  ShanghaiTech University, Shanghai Artificial Intelligence Laboratory
    - 📅 Date: Feb. 16, 2026
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [Agent-Safety], [Clawdbot], [evaluation]
    - 📖 TLDR: This work evaluates Clawdbot using a trajectory-centric approach across six risk dimensions. The test suite adapts scenarios from prior agent-safety benchmarks and adds custom cases tailored to Clawdbot’s tools. Complete interaction trajectories—including messages, actions, and tool calls—are logged and assessed by an automated judge and human reviewers. Across 34 cases, results show uneven safety performance. Clawdbot performs well on reliability-focused tasks but struggles with underspecified instructions, open-ended goals, and seemingly harmless jailbreak prompts. Small misunderstandings in these situations can escalate into higher-risk tool actions. We analyze representative cases to identify common vulnerabilities and typical failure patterns in practice.

- [GUIGuard: Toward a General Framework for Privacy-Preserving GUI Agents](https://arxiv.org/pdf/2601.18842)
    -  Yanxi Wang, Zhiling Zhang, Wenbo Zhou, Weiming Zhang, Jie Zhang, Qiannan Zhu, Yu Shi, Shuxin Zheng, Jiyan He
    - 🏛️ Institutions: Beijing Normal University, Zhongguancun Academy, University of Science and Technology of China, A*STAR, Zhongguancun Institution of Artificial Intelligence
    - 📅 Date: Jan. 29, 2026
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [Desktop]
    - 🔑 Key: [Agent-Safety], [privacy], [evaluation], [dataset], [benchmark]
    - 📖 TLDR: GUI agents automate computer and mobile tasks by directly interacting with on-screen interfaces, but they pose serious privacy risks because screenshots may contain sensitive personal information and are often sent to remote models. These risks depend on interaction context and sequences. This work proposes GUIGuard, a three-stage framework including privacy recognition, protection, and protected task execution. They also introduce GUIGuard-Bench, a cross-platform benchmark with 630 trajectories and fine-grained privacy annotations. Results show current agents have weak privacy recognition, while proper protection can preserve task performance. Privacy recognition remains a key bottleneck for safe GUI agents.
