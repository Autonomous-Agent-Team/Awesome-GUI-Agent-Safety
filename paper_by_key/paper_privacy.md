# Papers with Keyword: privacy

- [AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents](https://arxiv.org/pdf/2503.09780)
    - Arman Zharmagambetov, Chuan Guo, Ivan Evtimov, Maya Pavlova, Ruslan Salakhutdinov, Kamalika Chaudhuri
    - 🏛️ Institutions: Meta
    - 📅 Date: Oct. 1, 2025
    - 📑 Publisher: NeurIPS 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [privacy]
    - 📖 TLDR: This work presents AGENTDAM, a new benchmark for evaluating whether AI web-navigation agents adhere to the privacy principle of data minimization—using sensitive information only when strictly necessary for a task. It simulates end-to-end web interactions and is adaptable to all existing agents. Evaluations of GPT-4, Llama-3, and Claude agents reveal they often inadvertently process unnecessary private data. The study also proposes a prompting-based defense to reduce leakage and shows that this end-to-end benchmarking offers a more realistic privacy assessment than simply probing LLMs. [Github](https://github.com/facebookresearch/ai-agent-privacy)

- [Toward a Human-Centered Evaluation Framework for Trustworthy LLM-Powered GUI Agents](https://arxiv.org/abs/2504.17934)
    - Chaoran Chen, Zhiping Zhang, Ibrahim Khalilov, Bingcan Guo, Simret A Gebreegziabher, Yanfang Ye, Ziang Xiao, Yaxing Yao, Tianshi Li, Toby Jia-Jun Li
    - 🏛️ Institutions: University of Notre Dame, Virginia Tech, University of Washington, Northeastern University
    - 📅 Date: Jun. 5, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [framework], [risk], [survey], [privacy]
    - 📖 TLDR: This paper identifies three key risks, distinguishing them from traditional automation and general autonomous agents. Current evaluations prioritize performance, largely overlooking privacy and security. We review existing metrics and outline five challenges in using human evaluators. To address this, we advocate for a human-centered evaluation framework. This framework must incorporate risk assessments, enhance user awareness via in-context consent, and embed privacy and security considerations directly into agent design and evaluation.

- [Privacy-Enhancing Paradigms within Federated Multi-Agent Systems](https://arxiv.org/pdf/2503.08175)
    - Zitong Shi, Guancheng Wan, Wenke Huang, Guibin Zhang, Jiawei Shao, Mang Ye, Carl Yang
    - 🏛️ Institutions: National Engineering Research Center for Multimedia Software, Wuhan University, National University of Singapore, TeleAI, Emory University
    - 📅 Date: Mar. 11, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [multi-agent], [evaluation], [dataset], [privacy]
    - 📖 TLDR: This paper identified three key challenges in Federated Multi-Agent Systems (MAS): heterogeneous privacy, structural conversational differences, and dynamic network topologies. To solve these, they introduce Embedded Privacy-Enhancing Agents (EPEAgent). EPEAgent seamlessly integrates into the Retrieval-Augmented Generation (RAG) and context retrieval phases, minimizing data sharing to only task-relevant information. They also created a comprehensive evaluation dataset. Experiments confirm EPEAgent significantly enhances privacy protection while maintaining high system performance.

- [EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage](https://arxiv.org/abs/2409.11295)
    - Zeyi Liao, Lingbo Mo, Chejian Xu, Mintong Kang, Jiawei Zhang, Chaowei Xiao, Yuan Tian, Bo Li, Huan Sun
    - 🏛️ Institutions: OSU, UCLA, UChicago, UIUC, UW-Madison
    - 📅 Date: Sept. 17, 2024
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Web]
    - 🔑 Key: [injection], [privacy], [attack]
    - 📖 TLDR: This paper introduces the Environmental Injection Attack (EIA), a privacy attack targeting generalist web agents by embedding malicious yet concealed web elements to trick agents into leaking users' PII. Utilizing 177 action steps within realistic web scenarios, EIA demonstrates a high success rate in extracting specific PII and whole user requests. Through its detailed threat model and defense suggestions, the work underscores the challenge of detecting and mitigating privacy risks in autonomous web agents. [Github](https://github.com/osu-nlp-group/eia_against_webagent)
