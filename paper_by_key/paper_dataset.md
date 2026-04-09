# Papers with Keyword: dataset

- [GUIGuard: Toward a General Framework for Privacy-Preserving GUI Agents](https://arxiv.org/pdf/2601.18842)
    -  Yanxi Wang, Zhiling Zhang, Wenbo Zhou, Weiming Zhang, Jie Zhang, Qiannan Zhu, Yu Shi, Shuxin Zheng, Jiyan He
    - 🏛️ Institutions: Beijing Normal University, Zhongguancun Academy, University of Science and Technology of China, A*STAR, Zhongguancun Institution of Artificial Intelligence
    - 📅 Date: Jan. 29, 2026
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [Desktop]
    - 🔑 Key: [Agent-Safety], [privacy], [evaluation], [dataset], [benchmark]
    - 📖 TLDR: GUI agents automate computer and mobile tasks by directly interacting with on-screen interfaces, but they pose serious privacy risks because screenshots may contain sensitive personal information and are often sent to remote models. These risks depend on interaction context and sequences. This work proposes GUIGuard, a three-stage framework including privacy recognition, protection, and protected task execution. They also introduce GUIGuard-Bench, a cross-platform benchmark with 630 trajectories and fine-grained privacy annotations. Results show current agents have weak privacy recognition, while proper protection can preserve task performance. Privacy recognition remains a key bottleneck for safe GUI agents.

- [VeriOS: Query-Driven Proactive Human-Agent-GUI Interaction for Trustworthy OS Agents](https://arxiv.org/pdf/2509.07553)
    - Zheng Wu, Heyuan Huang, Xingyu Lou, Xiangmou Qu, Pengzhou Cheng, Zongru Wu, Weiwen Liu, Weinan Zhang, Jun Wang, Zhaoxiang Wang, Zhuosheng Zhang
    - 🏛️ Institutions: Shanghai Jiao Tong University, OPPO
    - 📅 Date: Sept. 17, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [web]
    - 🔑 Key: [framework], [untrustworthy], [dataset]
    - 📖 TLDR: Most existing OS agents are designed for idealized settings, whereas real-world environments often present untrustworthy conditions. To mitigate risks of over-execution in such scenarios, this work proposes a query-driven human-agent-GUI interaction framework that enables OS agents to decide when to query humans for more reliable task completion. This work also introduce VeriOS-Agent trained with a two-stage learning paradigm that falicitate the decoupling and utilization of meta-knowledge. Concretely, VeriOS-Agent autonomously executes actions in normal conditions while proactively querying humans in untrustworthy scenarios. [Github](https://github.com/Wuzheng02/VeriOS)

- [WebGuard: Building a Generalizable Guardrail for Web Agents](https://arxiv.org/abs/2507.14293)
    - Boyuan Zheng, Zeyi Liao, Scott Salisbury, Zeyuan Liu, Michael Lin, Qinyuan Zheng, Zifan Wang, Xiang Deng, Dawn Song, Huan Sun, Yu Su
    - 🏛️ Institutions: OSU; Scale AI; UCB
    - 📅 Date: Jul. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [dataset], [evaluation], [benchmark]
    - 📖 TLDR: WebGuard is the first comprehensive dataset designed for evaluating web agent action risks and developing necessary guardrails for real-world online environments. It contains 4,939 human-annotated, state-changing actions sourced from 193 websites across 22 domains, including various long-tail sites. The actions are categorized into a novel three-tier risk schema: SAFE, LOW, and HIGH, and the dataset includes training and test splits for evaluating generalization. The creators demonstrate that fine-tuning specialized guardrail models, such as the Qwen2.5VL-7B, using WebGuard significantly boosts performance, raising accuracy from 37% to 80% and increasing the recall of HIGH-risk actions from 20% to 76%. [Github](https://github.com/OSU-NLP-Group/WebGuard)

- [From Interaction to Impact: Towards Safer AI Agents Through Understanding and Evaluating Mobile UI Operation Impacts](https://arxiv.org/abs/2410.09006)
    - Zhuohao Jerry Zhang, Eldon Schoop, Jeffrey Nichols, Anuj Mahajan, Amanda Swearngin
    - 🏛️ Institutions: University of Washington, Apple
    - 📅 Date: Mar. 22, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [dataset], [risk], [evaluation]
    - 📖 TLDR: With the rise of generative AI, autonomous agents for managing daily tasks via user interfaces are advancing. Prior work focuses on UI navigation mechanics, but the real-world impacts of agents' potentially risky actions are understudied. This research investigates the consequences of AI agents' mobile UI actions. They developed an impact taxonomy through expert workshops, synthesized realistic mobile UI data, and annotated it with our categories. Evaluating various LLMs, this work shows the proposed taxonomy improves their reasoning about action impacts. However, significant gaps remain in reliably classifying nuanced or complex impacts.

- [Privacy-Enhancing Paradigms within Federated Multi-Agent Systems](https://arxiv.org/pdf/2503.08175)
    - Zitong Shi, Guancheng Wan, Wenke Huang, Guibin Zhang, Jiawei Shao, Mang Ye, Carl Yang
    - 🏛️ Institutions: National Engineering Research Center for Multimedia Software, Wuhan University, National University of Singapore, TeleAI, Emory University
    - 📅 Date: Mar. 11, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [multi-agent], [evaluation], [dataset], [privacy]
    - 📖 TLDR: This paper identified three key challenges in Federated Multi-Agent Systems (MAS): heterogeneous privacy, structural conversational differences, and dynamic network topologies. To solve these, they introduce Embedded Privacy-Enhancing Agents (EPEAgent). EPEAgent seamlessly integrates into the Retrieval-Augmented Generation (RAG) and context retrieval phases, minimizing data sharing to only task-relevant information. They also created a comprehensive evaluation dataset. Experiments confirm EPEAgent significantly enhances privacy protection while maintaining high system performance.

- [AEGIS2.0: A Diverse AI Safety Dataset and Risks Taxonomy for Alignment of LLM Guardrails](https://arxiv.org/pdf/2501.09004)
    -  Shaona Ghosh, Prasoon Varshney, Makesh Narsimhan Sreedhar, Aishwarya Padmakumar, Traian Rebedea, Jibin Rajan Varghese, Christopher Parisien
    - 🏛️ Institutions:  Nvidia
    - 📅 Date: Jan. 15, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [dataset], [evaluation], [AI-Safety]
    - 📖 TLDR: To address the lack of high-quality, commercially usable safety datasets for LLMs, we created Aegis 2.0. This dataset features a novel, fine-grained taxonomy (12 main hazard categories, 9 subcategories) for classifying risks. It contains over 34,000 human-LLM interactions, annotated via a hybrid human+LLM jury pipeline. Crucially, lightweight models fine-tuned on Aegis 2.0 match the performance of models trained on much larger, non-commercial datasets. We also introduce a safety+topic training blend that improves model adaptability to new risks. All data and models will be open-sourced to advance LLM safety research.
