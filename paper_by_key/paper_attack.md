# Papers with Keyword: attack

- [macOSWorld: A Multilingual Interactive Benchmark for GUI Agents](https://arxiv.org/abs/2506.04135)
    - Pei Yang, Hai Ci, and Mike Zheng Shou
    - 🏛️ Institutions: NUS
    - 📅 Date: Jun. 4, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Desktop]
    - 🔑 Key: [benchmark], [attack]
    - 📖 TLDR: Introduces macOSWorld, the first interactive benchmark for GUI agents on macOS, with 202 tasks across 30 apps (28 macOS-exclusive) in 5 languages plus a safety subset for deception attacks; evaluates 6 agents, showing proprietary CUAs outperform open-source and VLM-based agents, significant language gaps, and both grounding and safety challenges. [Github](https://macos-world.github.io/)

- [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024)
    - Maksym Andriushchenko, Alexandra Souly, Mateusz Dziemian, Derek Duenas, Maxwell Lin, Justin Wang, Dan Hendrycks, Andy Zou, Zico Kolter, Matt Fredrikson, Eric Winsor, Jerome Wynne, Yarin Gal, Xander Davies
    - 🏛️ Institutions: Gray Swan AI, UK AI Security Institute
    - 📅 Date: Apr. 18, 2025
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [attack], [jailbreaking]
    - 📖 TLDR: Research on LLM robustness to **jailbreak attacks** primarily focuses on chatbots, yet LLM agents, which use external tools for multi-stage tasks, pose greater misuse risks. This paper introduces **AgentHarm**, a benchmark of 110 malicious agent tasks (covering 11 harm categories) that tests whether agents retain capabilities post-jailbreak to complete harmful multi-step tasks. The evaluation found leading LLMs are surprisingly compliant with malicious agent requests even without jailbreaking. Simple universal jailbreak templates effectively jailbreak agents, enabling coherent, malicious, multi-step agent behavior. [Github](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/src/inspect_evals/agentharm)

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

- [Attacking Vision-Language Computer Agents via Pop-ups](https://arxiv.org/abs/2411.02391)
    - Yanzhe Zhang, Tao Yu, Diyi Yang
    - 🏛️ Institutions: Georgia Tech, HKU, Stanford
    - 📅 Date: Nov. 4, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web], [Desktop]
    - 🔑 Key: [risk], [pop-ups], [attack]
    - 📖 TLDR: This paper demonstrates that vision-language model (VLM) agents can be easily deceived by carefully designed adversarial pop-ups, leading them to perform unintended actions such as clicking on these pop-ups instead of completing their assigned tasks. Integrating these pop-ups into environments like OSWorld and VisualWebArena resulted in an average attack success rate of 86% and a 47% decrease in task success rate. Basic defense strategies, such as instructing the agent to ignore pop-ups or adding advertisement notices, were found to be ineffective against these attacks. [Github](https://github.com/SALT-NLP/PopupAttack)

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

- [Adversarial Attacks on Multimodal Agents](https://arxiv.org/pdf/2406.12814v1)
    - Chen Henry Wu, Jing Yu Koh, Ruslan Salakhutdinov, Daniel Fried, Aditi Raghunathan
    - 🏛️ Institutions: CMU
    - 📅 Date: Jun. 18, 2024
    - 📑 Publisher: NeurIPS 2024 Open-World Agents Workshop
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [attack], [evaluation]
    - 📖 TLDR: This paper investigates the safety risks posed by multimodal agents built on vision-enabled language models (VLMs). The authors introduce two adversarial attack methods: a captioner attack targeting white-box captioners and a CLIP attack that transfers to proprietary VLMs. To evaluate these attacks, they curated VisualWebArena-Adv, a set of adversarial tasks based on VisualWebArena. The study demonstrates that within a limited perturbation norm, the captioner attack can achieve a 75% success rate in making a captioner-augmented GPT-4V agent execute adversarial goals. The paper also discusses the robustness of agents based on other VLMs and provides insights into factors contributing to attack success and potential defenses. [Github](https://github.com/ChenWu98/agent-attack)

- [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208)
    - Wenkai Yang, Xiaohan Bi, Yankai Lin, Sishuo Chen, Jie Zhou, Xu Sun
    - 🏛️ Institutions: Renming University of China, PKU, Tencent
    - 📅 Date: Feb. 17, 2024
    - 📑 Publisher: NeurIPS 2024
    - 💻 Env: [Misc]
    - 🔑 Key: [backdoor], [attack], [risk]
    - 📖 TLDR: This paper investigates backdoor attacks on LLM-based agents, introducing a framework that categorizes attacks based on outcomes and trigger locations. The study demonstrates the vulnerability of such agents to backdoor attacks and emphasizes the need for targeted defenses. [Github](https://github.com/lancopku/agent-backdoor-attacks)

- [A Trembling House of Cards? Mapping Adversarial Attacks against Language Agents](https://arxiv.org/pdf/2402.10196)
    - Lingbo Mo, Zeyi Liao, Boyuan Zheng, Yu Su, Chaowei Xiao, Huan Sun
    - 🏛️ Institutions: OSU, UWM
    - 📅 Date: Feb. 15, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [attack], [framework], [evaluation]
    - 📖 TLDR: This paper introduces a conceptual framework to assess and understand adversarial vulnerabilities in language agents, dividing the agent structure into three components—Perception, Brain, and Action. It discusses 12 specific adversarial attack types that exploit these components, ranging from input manipulation to complex backdoor and jailbreak attacks. The framework provides a basis for identifying and mitigating risks before the widespread deployment of these agents in real-world applications. [Github](https://github.com/OSU-NLP-Group/AgentAttack)
