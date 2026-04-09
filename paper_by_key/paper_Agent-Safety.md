# Papers with Keyword: Agent-Safety

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
