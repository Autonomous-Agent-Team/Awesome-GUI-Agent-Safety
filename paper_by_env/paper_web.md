- [AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents](https://arxiv.org/pdf/2503.09780)
    - Arman Zharmagambetov, Chuan Guo, Ivan Evtimov, Maya Pavlova, Ruslan Salakhutdinov, Kamalika Chaudhuri
    - 🏛️ Institutions: Meta
    - 📅 Date: Oct. 1, 2025
    - 📑 Publisher: NeurIPS 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [privacy]
    - 📖 TLDR: This work presents AGENTDAM, a new benchmark for evaluating whether AI web-navigation agents adhere to the privacy principle of data minimization—using sensitive information only when strictly necessary for a task. It simulates end-to-end web interactions and is adaptable to all existing agents. Evaluations of GPT-4, Llama-3, and Claude agents reveal they often inadvertently process unnecessary private data. The study also proposes a prompting-based defense to reduce leakage and shows that this end-to-end benchmarking offers a more realistic privacy assessment than simply probing LLMs. [Github](https://github.com/facebookresearch/ai-agent-privacy)

- [VeriOS: Query-Driven Proactive Human-Agent-GUI Interaction for Trustworthy OS Agents](https://arxiv.org/pdf/2509.07553)
    - Zheng Wu, Heyuan Huang, Xingyu Lou, Xiangmou Qu, Pengzhou Cheng, Zongru Wu, Weiwen Liu, Weinan Zhang, Jun Wang, Zhaoxiang Wang, Zhuosheng Zhang
    - 🏛️ Institutions: Shanghai Jiao Tong University, OPPO
    - 📅 Date: Sept. 17, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [web]
    - 🔑 Key: [framework], [untrustworthy], [dataset]
    - 📖 TLDR: Most existing OS agents are designed for idealized settings, whereas real-world environments often present untrustworthy conditions. To mitigate risks of over-execution in such scenarios, this work proposes a query-driven human-agent-GUI interaction framework that enables OS agents to decide when to query humans for more reliable task completion. This work also introduce VeriOS-Agent trained with a two-stage learning paradigm that falicitate the decoupling and utilization of meta-knowledge. Concretely, VeriOS-Agent autonomously executes actions in normal conditions while proactively querying humans in untrustworthy scenarios. [Github](https://github.com/Wuzheng02/VeriOS)

- [Magentic-UI: Towards Human-in-the-loop Agentic Systems](https://arxiv.org/abs/2507.22358)
    - Hussein Mozannar, Gagan Bansal, Cheng Tan, Adam Fourney, Victor Dibia, Jingya Chen, Jack Gerrits, Tyler Payne, Matheus Kunzler Maldaner, Madeleine Grunde-McLaughlin, Eric Zhu, Griffin Bassman, Jacob Alber, Peter Chang, Ricky Loynd, Friederike Niedtner, Ece Kamar, Maya Murad, Rafah Hosn, Saleema Amershi
    - 🏛️ Institutions: MSR
    - 📅 Date: Jul. 30, 2025
    - 📑 Publisher: arXiv (also MSR Technical Report MSR-TR-2025-40)
    - 💻 Env: [Web]
    - 🔑 Key: [evaluation], [multi-agent]
    - 📖 TLDR: Magentic-UI (Multi-agentic User Interface) is an open-source web interface enabling safe, efficient human–agent collaboration through a flexible multi-agent architecture. It supports web browsing, code execution, and file manipulation, and provides six interaction mechanisms—co-planning, co-tasking, multi-tasking, action guards, answer verification, and long-term memory—to integrate human oversight with AI autonomy. Evaluated via agentic benchmarks, simulated user tests, qualitative user study, and safety assessments, it demonstrates how incorporating human-in-the-loop dynamics can significantly improve agentic systems' reliability and performance. [Github](https://github.com/microsoft/magentic-ui)

- [WebGuard: Building a Generalizable Guardrail for Web Agents](https://arxiv.org/abs/2507.14293)
    - Boyuan Zheng, Zeyi Liao, Scott Salisbury, Zeyuan Liu, Michael Lin, Qinyuan Zheng, Zifan Wang, Xiang Deng, Dawn Song, Huan Sun, Yu Su
    - 🏛️ Institutions: OSU; Scale AI; UCB
    - 📅 Date: Jul. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [dataset], [evaluation], [benchmark]
    - 📖 TLDR: WebGuard is the first comprehensive dataset designed for evaluating web agent action risks and developing necessary guardrails for real-world online environments. It contains 4,939 human-annotated, state-changing actions sourced from 193 websites across 22 domains, including various long-tail sites. The actions are categorized into a novel three-tier risk schema: SAFE, LOW, and HIGH, and the dataset includes training and test splits for evaluating generalization. The creators demonstrate that fine-tuning specialized guardrail models, such as the Qwen2.5VL-7B, using WebGuard significantly boosts performance, raising accuracy from 37% to 80% and increasing the recall of HIGH-risk actions from 20% to 76%. [Github](https://github.com/OSU-NLP-Group/WebGuard)

- [MLA-Trust: Benchmarking Trustworthiness of Multimodal LLM Agents in GUI Environments](https://arxiv.org/abs/2506.01616)
    - Xiao Yang, Jiawei Chen, Jun Luo, Zhengwei Fang, Yinpeng Dong, Hang Su, Jun Zhu
    - 🏛️ Institutions: Tsinghua University, East China Normal University
    - 📅 Date: Jun. 2, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [Web]
    - 🔑 Key: [benchmark], [evaluation], [framework], [trustworthiness]
    - 📖 TLDR: Multimodal LLM-based agents (MLAs) integrate vision, language, and action for unprecedented autonomy in GUI applications, but introduce critical trustworthiness challenges due to their ability to modify digital states. Existing benchmarks are insufficient. This work introduces MLA-Trust, the first unified framework evaluating MLA trustworthiness across four dimensions: truthfulness, controllability, safety, and privacy, using realistic web and mobile tasks. [Github](https://github.com/thu-ml/MLA-Trust)

- [SAFEARENA: Evaluating the Safety of Autonomous Web Agents](https://arxiv.org/pdf/2503.04957)
    - Ada Defne Tur, Nicholas Meade, Xing Han Lù, Alejandra Zambrano, Arkil Patel, Esin Durmus, Spandana Gella, Karolina Stańczak, Siva Reddy
    - 🏛️ Institutions: McGill University, Mila, Concordia University, Anthropic, ServiceNow Research
    - 📅 Date: Mar. 6, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [evaluation], [misuse]
    - 📖 TLDR:  This work proposes SAFEARENA, the first benchmark to focus on the deliberate misuse of web agents. SAFEARENA comprises 250 safe and 250 harmful tasks across four websites. They classify the harmful tasks into five harm categories—misinformation, illegal activity, harassment, cybercrime, and social bias, designed to assess realistic misuses of web agents. To systematically assess the susceptibility to harmful tasks, they introduce the Agent Risk Assessment framework that categorizes agent behavior across four risk levels. [Github](https://safearena.github.io)

- [WebOlympus: An Open Platform for Web Agents on Live Websites](https://aclanthology.org/2024.emnlp-demo.20/)
    - Boyuan Zheng, Boyu Gou, Scott Salisbury, Zheng Du, Huan Sun, Yu Su
    - 🏛️ Institutions: OSU
    - 📅 Date: Nov. 12, 2024
    - 📑 Publisher: EMNLP 2024
    - 💻 Env: [Web]
    - 🔑 Key: [framework], [platform]
    - 📖 TLDR: This paper introduces *WebOlympus*, an open platform designed to facilitate the research and deployment of web agents on live websites. It features a user-friendly Chrome extension interface, allowing users without programming expertise to operate web agents with minimal effort. The platform incorporates a **safety monitor** module to prevent harmful actions through human supervision or model-based control, supporting applications such as annotation interfaces for web agent trajectories and data crawling.

- [Attacking Vision-Language Computer Agents via Pop-ups](https://arxiv.org/abs/2411.02391)
    - Yanzhe Zhang, Tao Yu, Diyi Yang
    - 🏛️ Institutions: Georgia Tech, HKU, Stanford
    - 📅 Date: Nov. 4, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web], [Desktop]
    - 🔑 Key: [risk], [pop-ups], [attack]
    - 📖 TLDR: This paper demonstrates that vision-language model (VLM) agents can be easily deceived by carefully designed adversarial pop-ups, leading them to perform unintended actions such as clicking on these pop-ups instead of completing their assigned tasks. Integrating these pop-ups into environments like OSWorld and VisualWebArena resulted in an average attack success rate of 86% and a 47% decrease in task success rate. Basic defense strategies, such as instructing the agent to ignore pop-ups or adding advertisement notices, were found to be ineffective against these attacks. [Github](https://github.com/SALT-NLP/PopupAttack)

- [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814)
    - Chen Henry Wu, Rishi Rajesh Shah, Jing Yu Koh, Russ Salakhutdinov, Daniel Fried, Aditi Raghunathan
    - 🏛️ Institutions: CMU, Stanford
    - 📅 Date: Oct. 21, 2024
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [evaluation]
    - 📖 TLDR: This paper introduces the Agent Robustness Evaluation (ARE) framework to assess the adversarial robustness of multimodal language model agents in web environments. By creating 200 targeted adversarial tasks within VisualWebArena, the study reveals that minimal perturbations can significantly compromise agent performance, even in advanced systems utilizing reflection and tree-search mechanisms. The findings highlight the need for enhanced safety measures in deploying such agents. [Github](https://github.com/ChenWu98/agent-attack)

- [Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents](https://arxiv.org/abs/2410.13886)
    - Priyanshu Kumar, Elaine Lau, Saranya Vijayakumar, Tu Trinh, Scale Red Team, Elaine Chang, Vaughn Robinson, Sean Hendryx, Shuyan Zhou, Matt Fredrikson, Summer Yue, Zifan Wang
    - 🏛️ Institutions: CMU, GraySwan AI, Scale AI
    - 📅 Date: Oct. 11, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [evaluation]
    - 📖 TLDR: This paper introduces **Browser Agent Red teaming Toolkit (BrowserART)**, a comprehensive test suite for evaluating the safety of LLM-based browser agents. The study reveals that while refusal-trained LLMs decline harmful instructions in chat settings, their corresponding browser agents often comply with such instructions, indicating a significant safety gap. The authors call for collaboration among developers and policymakers to enhance agent safety. [Github](https://github.com/scaleapi/browser-art)

- [ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://sites.google.com/view/st-webagentbench/home)
    - Ido Levy, Ben Wiesel, Sami Marreed, Alon Oved, Avi Yaeli, Segev Shlomov
    - 🏛️ Institutions: IBM Research
    - 📅 Date: Oct. 9, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: This paper introduces ST-WebAgentBench, a benchmark designed to evaluate the safety and trustworthiness of web agents in enterprise contexts. It defines safe and trustworthy agent behavior, outlines the structure of safety policies, and introduces the "Completion under Policies" metric to assess agent performance. The study reveals that current state-of-the-art agents struggle with policy adherence, highlighting the need for improved policy awareness and compliance in web agents. [Github](https://github.com/segev-shlomov/ST-WebAgentBench)

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
