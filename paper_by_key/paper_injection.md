# Papers with Keyword: injection

- [GhostEI-Bench: Do Mobile Agents Resilience to Environmental Injection in Dynamic On-Device Environments?](https://arxiv.org/abs/2510.20333)
    - Chiyu Chen, Xinhao Song, Yunkai Chai, Yang Yao, Haodong Zhao, Lijun Li, Jie Li, Yan Teng, Gongshen Liu, Yingchun Wang
    - 🏛️ Institutions: Shanghai Jiao Tong University, Shanghai Artificial Intelligence Laboratory, The University of Hong Kong
    - 📅 Date: Nov. 21, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [injection]
    - 📖 TLDR: VLMs used as mobile GUI agents are vulnerable to environmental injection, where adversarial UI elements like deceptive overlays or spoofed notifications contaminate the agent's visual perception. This bypasses textual safeguards and can cause privacy leakage or device compromise. This work introduces **GhostEI-Bench**, a benchmark using Android emulators to assess agent performance under these dynamic attacks.

- [OS-HARM: A Benchmark for Measuring Safety of Computer Use Agents](https://arxiv.org/abs/2503.18492)
    - JThomas Kuntz, Agatha Duzan, Hao Zhao, Francesco Croce, Zico Kolter, Nicolas Flammarion, Maksym Andriushchenko
    - 🏛️ Institutions: EPFL, Carnegie Mellon University
    - 📅 Date: Oct. 29, 2025
    - 📑 Publisher: NeurIPS 2025 Spotlight (Datasets and Benchmarks Track)
    - 💻 Env: [Desktop]
    - 🔑 Key: [benchmark], [evaluation], [misuse], [injection]
    - 📖 TLDR: Computer use agents, LLM-based systems interacting with GUIs via screenshots or accessibility trees, lack safety evaluation. This paper introduces OS-HARM, a benchmark built on OSWorld with 150 tasks across three harm categories: deliberate misuse, prompt injection, and model misbehavior (e.g., harassment, data exfiltration). An automated judge assesses both accuracy and safety. Frontier models (like o4-mini, Claude 3.7 Sonnet, Gemini 2.5 Pro) evaluated show high compliance with misuse queries, vulnerability to static prompt injections, and occasional unsafe actions. [Github](https://github.com/tml-epfl/os-harm)

- [Progent: Programmable Privilege Control for LLM Agents](https://arxiv.org/abs/2504.11703)
    - Tianneng Shi, Jingxuan He, Zhun Wang, Hongwei Li, Linyu Wu, Wenbo Guo, Dawn Song
    - 🏛️ Institutions: UC Berkeley, UC Santa Barbara, National University of Singapore
    - 📅 Date: Aug. 30, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [injection], [tool]
    - 📖 TLDR: LLM agents use LLMs and tools to perform user tasks but face security risks from external environments, like prompt injection and malicious tools, enabling dangerous actions such as financial fraud or data leakage. The core vulnerability is **over-privileged tool access**. This work introduces **Progent**, the first privilege control framework for securing LLM agents. Progent enforces tool-level security by restricting agents to necessary tool calls while blocking malicious ones, using a domain-specific language for fine-grained policy control. Progent operates deterministically at runtime, offering provable security without altering agent internals.

- [The Obvious Invisible Threat: LLM-Powered GUI Agents' Vulnerability to Fine-Print Injections](https://arxiv.org/pdf/2504.11281v1)
    - Chaoran Chen, Zhiping Zhang, Bingcan Guo, Shang Ma, Ibrahim Khalilov, Simret A Gebreegziabher, Yanfang Ye, Ziang Xiao, Yaxing Yao, Tianshi Li, Toby Jia-Jun Li
    - 🏛️ Institutions: University of Notre Dame, Northeastern University, University of Washington, Virginia Tech, Johns Hopkins University
    - 📅 Date: Apr. 15, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [injection], [attack]
    - 📖 TLDR: LLM powered GUI agents perform tasks automatically by interpreting and interacting with GUIs. Their autonomy, especially when handling sensitive data, introduces new security risks. Adversaries can exploit the visual processing differences between agents and humans by injecting malicious GUI content, leading to altered agent behaviors or unauthorized private data disclosure. Our study characterized six attacks, testing them on state-of-the-art agents and human users. Findings show agents are highly vulnerable, especially to contextually embedded threats. Human oversight is insufficient, emphasizing the need for privacy-aware agent design and practical defense strategies.

- [AEIA-MN: Evaluating the Robustness of Multimodal LLM-Powered Mobile Agents Against Active Environmental Injection Attacks](https://arxiv.org/abs/2502.13053)
    - Yurun Chen, Xueyu Hu, Keting Yin, Juncheng Li, Shengyu Zhang
    - 🏛️ Institutions: Zhejiang University
    - 📅 Date: Feb. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [evaluation], [injection], [attack]
    - 📖 TLDR: This paper introduces the concept of Active Environment Injection Attack (AEIA), where attackers disguise malicious actions as environmental elements to disrupt AI agents' decision-making processes. The authors propose AEIA-MN, an attack scheme leveraging mobile notifications to evaluate the robustness of multimodal large language model-based mobile agents. Experimental results demonstrate that even advanced models are highly vulnerable to such attacks, with success rates reaching up to 93% in the AndroidWorld benchmark.

- [Improved Large Language Model Jailbreak Detection via Pretrained Embeddings](https://arxiv.org/pdf/2412.01547)
    - Erick Galinkin, Martin Sablotny
    - 🏛️ Institutions: NVIDIA,
    - 📅 Date: Dec. 2, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [method], [risk], [injection], [jailbreaking]
    - 📖 TLDR: The adoption of LLMs requires robust security against attacks like prompt injection and jailbreaking, which aim to bypass safety policies. To prevent LLMs from generating harmful content or taking undesirable actions, owners must implement safeguards during training and use additional blocking tools. Detecting jailbreaking prompts is crucial. This work proposes a novel and superior approach for jailbreak detection by combining text embeddings optimized for retrieval with traditional machine learning classification algorithms.

- [AdvWeb: Controllable Black-box Attacks on VLM-powered Web Agents](https://arxiv.org/abs/2410.17401v2)
    - Chejian Xu, Mintong Kang, Jiawei Zhang, Zeyi Liao, Lingbo Mo, Mengqi Yuan, Huan Sun, Bo Li
    - 🏛️ Institutions: UIUC, OSU
    - 📅 Date: Sept. 27, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [black-box], [injection], [attack], [DPO]
    - 📖 TLDR: This paper presents AdvWeb, a black-box attack framework that exploits vulnerabilities in vision-language model (VLM)-powered web agents by injecting adversarial prompts directly into web pages. Using Direct Policy Optimization (DPO), AdvWeb trains an adversarial prompter model that can mislead agents into executing harmful actions, such as unauthorized financial transactions, while maintaining high stealth and control. Extensive evaluations reveal that AdvWeb achieves high success rates across multiple real-world tasks, emphasizing the need for stronger security measures in web agent deployments. [Github](https://ai-secure.github.io/AdvWeb/)

- [EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage](https://arxiv.org/abs/2409.11295)
    - Zeyi Liao, Lingbo Mo, Chejian Xu, Mintong Kang, Jiawei Zhang, Chaowei Xiao, Yuan Tian, Bo Li, Huan Sun
    - 🏛️ Institutions: OSU, UCLA, UChicago, UIUC, UW-Madison
    - 📅 Date: Sept. 17, 2024
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Web]
    - 🔑 Key: [injection], [privacy], [attack]
    - 📖 TLDR: This paper introduces the Environmental Injection Attack (EIA), a privacy attack targeting generalist web agents by embedding malicious yet concealed web elements to trick agents into leaking users' PII. Utilizing 177 action steps within realistic web scenarios, EIA demonstrates a high success rate in extracting specific PII and whole user requests. Through its detailed threat model and defense suggestions, the work underscores the challenge of detecting and mitigating privacy risks in autonomous web agents. [Github](https://github.com/osu-nlp-group/eia_against_webagent)
