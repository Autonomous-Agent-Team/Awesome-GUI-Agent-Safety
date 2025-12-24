# Papers with Keyword: jailbreaking

- [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024)
    - Maksym Andriushchenko, Alexandra Souly, Mateusz Dziemian, Derek Duenas, Maxwell Lin, Justin Wang, Dan Hendrycks, Andy Zou, Zico Kolter, Matt Fredrikson, Eric Winsor, Jerome Wynne, Yarin Gal, Xander Davies
    - 🏛️ Institutions: Gray Swan AI, UK AI Security Institute
    - 📅 Date: Apr. 18, 2025
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [attack], [jailbreaking]
    - 📖 TLDR: Research on LLM robustness to **jailbreak attacks** primarily focuses on chatbots, yet LLM agents, which use external tools for multi-stage tasks, pose greater misuse risks. This paper introduces **AgentHarm**, a benchmark of 110 malicious agent tasks (covering 11 harm categories) that tests whether agents retain capabilities post-jailbreak to complete harmful multi-step tasks. The evaluation found leading LLMs are surprisingly compliant with malicious agent requests even without jailbreaking. Simple universal jailbreak templates effectively jailbreak agents, enabling coherent, malicious, multi-step agent behavior. [Github](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/src/inspect_evals/agentharm)

- [Improved Large Language Model Jailbreak Detection via Pretrained Embeddings](https://arxiv.org/pdf/2412.01547)
    - Erick Galinkin, Martin Sablotny
    - 🏛️ Institutions: NVIDIA,
    - 📅 Date: Dec. 2, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [method], [risk], [injection], [jailbreaking]
    - 📖 TLDR: The adoption of LLMs requires robust security against attacks like prompt injection and jailbreaking, which aim to bypass safety policies. To prevent LLMs from generating harmful content or taking undesirable actions, owners must implement safeguards during training and use additional blocking tools. Detecting jailbreaking prompts is crucial. This work proposes a novel and superior approach for jailbreak detection by combining text embeddings optimized for retrieval with traditional machine learning classification algorithms.
