# Papers with Keyword: tool

- [Progent: Programmable Privilege Control for LLM Agents](https://arxiv.org/abs/2504.11703)
    - Tianneng Shi, Jingxuan He, Zhun Wang, Hongwei Li, Linyu Wu, Wenbo Guo, Dawn Song
    - 🏛️ Institutions: UC Berkeley, UC Santa Barbara, National University of Singapore
    - 📅 Date: Aug. 30, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [injection], [tool]
    - 📖 TLDR: LLM agents use LLMs and tools to perform user tasks but face security risks from external environments, like prompt injection and malicious tools, enabling dangerous actions such as financial fraud or data leakage. The core vulnerability is **over-privileged tool access**. This work introduces **Progent**, the first privilege control framework for securing LLM agents. Progent enforces tool-level security by restricting agents to necessary tool calls while blocking malicious ones, using a domain-specific language for fine-grained policy control. Progent operates deterministically at runtime, offering provable security without altering agent internals.
