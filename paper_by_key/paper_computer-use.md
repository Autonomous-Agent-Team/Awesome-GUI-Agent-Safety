# Papers with Keyword: computer-use

- [AgentHazard: A Benchmark for Evaluating Harmful Behavior in Computer-Use Agents](https://arxiv.org/pdf/2604.02947)
    -  Yunhao Feng, Yifan Ding, Yingshui Tan, Xingjun Ma, Yige Li, Yutao Wu, Yifeng Gao, Kun Zhai, Yanming Guo
    - 🏛️ Institutions: Alibaba, Fudan University, Hunan Institute of Advanced Technology, Deakin University, Singapore Management University
    - 📅 Date: Apr. 3, 2026
    - 📑 Publisher: arXiv
    - 💻 Env: [Desktop]
    - 🔑 Key: [Agent-Safety], [evaluation], [dataset], [benchmark], [computer-use]
    - 📖 TLDR: Computer-use agents extend language models from text generation to persistent action across tools, files, and execution environments, introducing new safety risks. Unlike chat systems, they maintain state across interactions, allowing harmful behavior to emerge through sequences of individually plausible but collectively unsafe actions. We present AgentHazard, a benchmark for evaluating harmful behavior in computer-use agents. AgentHazard contains 2,653 instances spanning diverse risk categories and attack strategies, where each instance combines a harmful objective with operational steps that appear locally legitimate but jointly induce unsafe behavior. We evaluate Claude Code, OpenClaw, and IFlow using mostly open or openly deployable models from the Qwen3, Kimi, GLM, and DeepSeek families. Results show that current systems remain highly vulnerable: notably, Claude Code powered by Qwen3-Coder achieves an attack success rate of 73.63%, highlighting that model alignment alone does not reliably ensure agent safety.
