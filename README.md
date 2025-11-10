# Awesome-ML-Security-and-Privacy-Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS).

### Contents:

- [Awesome-ML-Security-and-Privacy-Papers](#awesome-ml-security-and-privacy-papers)
    - [Contents:](#contents)
  - [1. Security Papers](#1-security-papers)
    - [1.1 Adversarial Attack \& Defense](#11-adversarial-attack--defense)
      - [1.1.1 Image](#111-image)
      - [1.1.2 Text](#112-text)
      - [1.1.3 Audio](#113-audio)
      - [1.1.4 Video](#114-video)
      - [1.1.5 Graph](#115-graph)
      - [1.1.6 Software](#116-software)
      - [1.1.7 Hardware](#117-hardware)
      - [1.1.8 Interpret Method](#118-interpret-method)
      - [1.1.9 Physical World](#119-physical-world)
      - [1.1.10 Reinforcement Learning](#1110-reinforcement-learning)
      - [1.1.11 Robust Defense](#1111-robust-defense)
      - [1.1.12 Network Traffic](#1112-network-traffic)
      - [1.1.13 Wireless Communication System](#1113-wireless-communication-system)
      - [1.1.14 Tabular Data](#1114-tabular-data)
    - [1.2 Distributed Machine Learning](#12-distributed-machine-learning)
      - [1.2.1 Federated Learning](#121-federated-learning)
      - [1.2.2 Normal Distributed Learning](#122-normal-distributed-learning)
    - [1.3 Data Poisoning](#13-data-poisoning)
      - [1.3.1 Hijack Embedding](#131-hijack-embedding)
      - [1.3.2 Hijack Autocomplete Code](#132-hijack-autocomplete-code)
      - [1.3.3 Semi-Supervised Learning](#133-semi-supervised-learning)
      - [1.3.4 Recommender Systems](#134-recommender-systems)
      - [1.3.5 Classification](#135-classification)
      - [1.3.6 Constractive Learning](#136-constractive-learning)
      - [1.3.7 Privacy](#137-privacy)
      - [1.3.8 Test-Time Poisoning](#138-test-time-poisoning)
      - [1.3.9 Defense](#139-defense)
    - [1.4 Backdoor](#14-backdoor)
      - [1.4.1 Image](#141-image)
      - [1.4.2 Text](#142-text)
      - [1.4.3 Graph](#143-graph)
      - [1.4.4 Software](#144-software)
      - [1.4.5 Audio](#145-audio)
      - [1.4.6 Multimedia](#146-multimedia)
      - [1.4.7 Neuromorphic Data](#147-neuromorphic-data)
    - [1.5 ML Library Security](#15-ml-library-security)
      - [1.5.1 Loss](#151-loss)
    - [1.6 AI4Security](#16-ai4security)
      - [1.6.1 Cyberbullying](#161-cyberbullying)
      - [1.6.2 Security Applications](#162-security-applications)
      - [1.6.3 Advertisement Detection](#163-advertisement-detection)
      - [1.6.4 CAPTCHA](#164-captcha)
      - [1.6.5 Code Analysis](#165-code-analysis)
      - [1.6.6 Chatbot](#166-chatbot)
      - [1.6.7 Side Channel Attack](#167-side-channel-attack)
      - [1.6.8 Guidline](#168-guidline)
      - [1.6.9 Security Event](#169-security-event)
      - [1.6.10 Vulnerability Discovery](#1610-vulnerability-discovery)
    - [1.7 AutoML Security](#17-automl-security)
      - [1.7.1 Security Analysis](#171-security-analysis)
    - [1.8 Hardware Related Security](#18-hardware-related-security)
      - [1.8.1 Verification](#181-verification)
    - [1.9 Security Related Interpreting Method](#19-security-related-interpreting-method)
      - [1.9.1 Anomaly Detection](#191-anomaly-detection)
      - [1.9.2 Faithfulness](#192-faithfulness)
      - [1.9.3 Security Applications](#193-security-applications)
    - [1.10 Face Security](#110-face-security)
      - [1.10.1 Deepfake Detection](#1101-deepfake-detection)
      - [1.10.2 Face Impersonation](#1102-face-impersonation)
      - [1.10.3 Face Verification Systems](#1103-face-verification-systems)
    - [1.10 AI Generation Security](#110-ai-generation-security)
      - [1.10.1 Text Generation Detection](#1101-text-generation-detection)
      - [1.10.2 Deepfake](#1102-deepfake)
    - [1.11 LLM Security](#111-llm-security)
      - [1.11.1 Code Analysis](#1111-code-analysis)
      - [1.11.2 Vision-Language Model](#1112-vision-language-model)
      - [1.11.3 Jailbreaking](#1113-jailbreaking)
      - [1.11.4 Robustness](#1114-robustness)
      - [1.11.5 Generated Concent](#1115-generated-concent)
      - [1.11.6 Backdoor](#1116-backdoor)
      - [1.11.7 Agent Security](#1117-agent-security)
      - [1.11.8 Prompt Injection](#1118-prompt-injection)
      - [1.11.9 Hallucination](#1119-hallucination)
  - [2. Privacy Papers](#2-privacy-papers)
    - [2.1 Training Data](#21-training-data)
      - [2.1.1 Data Recovery](#211-data-recovery)
      - [2.1.2 Membership Inference Attack](#212-membership-inference-attack)
      - [2.1.3 Information Leakage in Distributed ML System](#213-information-leakage-in-distributed-ml-system)
      - [2.1.4 Information Leakage in Embedding](#214-information-leakage-in-embedding)
      - [2.1.5 Graph Leakage](#215-graph-leakage)
      - [2.1.6 Unlearning](#216-unlearning)
      - [2.1.7 Attribute Inference Attack](#217-attribute-inference-attack)
      - [2.1.7 Property Inference Attack](#217-property-inference-attack)
      - [2.1.8 Data Synthesis](#218-data-synthesis)
      - [2.1.8 Dataset Auditing](#218-dataset-auditing)
    - [2.2 Model](#22-model)
      - [2.2.1 Model Extraction](#221-model-extraction)
      - [2.2.2 Model Watermark](#222-model-watermark)
      - [2.2.3 Model Owenership](#223-model-owenership)
      - [2.2.4 Model Integrity](#224-model-integrity)
    - [2.3 LLM Privacy](#23-llm-privacy)
      - [2.3.1 Prompt Privacy](#231-prompt-privacy)
      - [2.3.2 Model Privacy](#232-model-privacy)
      - [2.3.3 Data Privacy](#233-data-privacy)
    - [2.4 User Related Privacy](#24-user-related-privacy)
      - [2.4.1 Image](#241-image)
    - [2.5 Private ML Protocols](#25-private-ml-protocols)
      - [2.5.1 3PC](#251-3pc)
      - [2.5.2 4PC](#252-4pc)
      - [2.5.3 SMPC](#253-smpc)
      - [2.5.4 Cryptographic NN Computation](#254-cryptographic-nn-computation)
      - [2.5.5 Secure Aggregation](#255-secure-aggregation)
    - [2.6 Platform](#26-platform)
      - [2.6.1 Inference Attack Measurement](#261-inference-attack-measurement)
      - [2.6.2 Survey](#262-survey)
    - [2.7 Differential Privacy](#27-differential-privacy)
      - [2.7.1 Tree Model](#271-tree-model)
      - [2.7.2 DP](#272-dp)
      - [2.7.3 LDP](#273-ldp)
    - [2.7 LLM Privacy](#27-llm-privacy)
      - [2.7.1 Prompt Privacy](#271-prompt-privacy)
  - [Contributing](#contributing)
  - [Licenses](#licenses)

## 1. Security Papers

### 1.1 Adversarial Attack & Defense

#### 1.1.1 Image

1. **Hybrid Batch Attacks: Finding Black-box Adversarial Examples with Limited Queries**. USENIX Security 2020. `Transferability + Query. Black-box Attack ` [[pdf](https://www.usenix.org/system/files/sec20-suya.pdf)] [[code](https://github.com/suyeecav/Hybrid-Attack)]

2. **Adversarial Preprocessing: Understanding and Preventing Image-Scaling Attacks in Machine Learning**. USENIX Security 2020. `Defense of Image Scaling Attack` [[pdf](https://www.usenix.org/system/files/sec20fall_quiring_prepub.pdf)] [[code](https://scaling-attacks.net/)]

3. **HopSkipJumpAttack: A Query-Efficient Decision-Based Attack**. IEEE S&P 2020. `Query-based Black-box Attack` [[pdf](https://arxiv.org/pdf/1904.02144.pdf)] [[code](https://github.com/Jianbo-Lab/HSJA)]

4. **PatchGuard: A Provably Robust Defense against Adversarial Patches via Small Receptive Fields and Masking**. USENIX Security 2021. `Adversarial Patch Defense` [[pdf](https://www.usenix.org/system/files/sec21fall-xiang.pdf)] [[code](https://github.com/inspire-group/PatchGuard)]

5. **Gotta Catch'Em All: Using Honeypots to Catch Adversarial Attacks on Neural Networks**. ACM CCS 2020. `Build an trap in model to induce specific adversarial perturbation` [[pdf](https://people.cs.uchicago.edu/~ravenben/publications/pdf/trapdoor-ccs20.pdf)] [[code](https://github.com/Shawn-Shan/trapdoor)]

6. **A Tale of Evil Twins: Adversarial Inputs versus Poisoned Models**. ACM CCS 2020. `Perturbate both input and model` [[pdf](https://arxiv.org/pdf/1911.01559.pdf)] [[code](https://github.com/alps-lab/imc)]

7. **Feature-Indistinguishable Attack to Circumvent Trapdoor-Enabled Defense**. ACM CCS 2021. `A new attack method can break TeD defense mechanism` [[pdf](https://dl.acm.org/doi/pdf/10.1145/3460120.3485378)] [[code](https://github.innominds.com/CGCL-codes/FeatureIndistinguishableAttack)]

8. **DetectorGuard: Provably Securing Object Detectors against Localized Patch Hiding Attacks**. ACM CCS 2021. `Provable robustness for patch hiding in object detection` [[pdf](https://arxiv.org/pdf/2102.02956.pdf)] [[code](https://github.com/inspire-group/DetectorGuard)]

9.  **It's Not What It Looks Like: Manipulating Perceptual Hashing based Applications**. ACM CCS 2021. `Adversarial Attack against PHash` [[pdf](https://gangw.cs.illinois.edu/PHashing.pdf)] [[code](https://github.com/gyNancy/phash_public)]

10. **RamBoAttack: A Robust and Query Efficient Deep Neural Network Decision Exploit**. NDSS 2022. `Query-based black box attack` [[pdf](https://arxiv.org/pdf/2112.05282.pdf)] [[code](https://github.com/RamBoAttack/RamBoAttack.github.io)]

11. **What You See is Not What the Network Infers: Detecting Adversarial Examples Based on Semantic Contradiction**. NDSS 2022. `Generative-based AE detection` [[pdf](https://arxiv.org/pdf/2201.09650.pdf)] [[code](https://github.com/cure-lab/ContraNet)]

12. **AutoDA: Automated Decision-based Iterative Adversarial Attacks**. USENIX 2022. `Program Synthesis for Adversarial Attack` [[pdf](https://www.usenix.org/system/files/sec22_slides-fu-qi.pdf)]

13. **Blacklight: Scalable Defense for Neural Networks against Query-Based Black-Box Attacks**. USENIX Security 2022. `AE Detection using probabilistic fingerprints based on hash of input similarity` [[pdf](https://www.usenix.org/system/files/sec22-li-huiying.pdf)] [[code](https://sandlab.cs.uchicago.edu/blacklight)]

14. **Physical Hijacking Attacks against Object Trackers**. ACM CCS 2022. `Adversarial Attacks on Object Trackers` [[pdf](https://dl.acm.org/doi/10.1145/3548606.3559390)] [[code](https://github.com/purseclab/AttrackZone)]

15. **Post-breach Recovery: Protection against White-box Adversarial Examples for Leaked DNN Models**. ACM CCS 2022. `Adversarial Attacks on Object Trackers` [[pdf](https://arxiv.org/pdf/2205.10686.pdf)]

16. **Squint Hard Enough: Attacking Perceptual Hashing with Adversarial Machine Learning**. USENIX Security 2023. `Adversarial Attacks against PhotoDNA and PDQ` [[pdf](https://www.usenix.org/system/files/sec23summer_146-prokos-prepub.pdf)]

17. **The Space of Adversarial Strategies**. USENIX Security 2023. `Decompose the Adversarial Attack Components and combine them together` [[pdf](https://www.usenix.org/system/files/sec23summer_256-sheatsley-prepub.pdf)]

18. **Stateful Defenses for Machine Learning Models Are Not Yet Secure Against Black-box Attacks**. ACM CCS 2023. `Attack strategy to enhance the query-based attack against the stateful defense` [[pdf](https://arxiv.org/pdf/2303.06280.pdf)] [[code](https://github.com/purseclab/AttrackZone)]

19. **BounceAttack: A Query-Efficient Decision-based Adversarial Attack by Bouncing into the Wild**. IEEE S&P 2024. `Query-based hard label attack` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a068/1RjEaEvldVS)]

20. **Sabre: Cutting through Adversarial Noise with Adaptive Spectral Filtering and Input Reconstruction**. IEEE S&P 2024. `Filter-based adversarial perturbation defense` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a076/1RjEaLx3uAU)] [[code](https://github.com/Mobile-Intelligence-Lab/SABRE)]

21. **Sabre: Cutting through Adversarial Noise with Adaptive Spectral Filtering and Input Reconstruction**. IEEE S&P 2024. `Adversarial attack against face recognization system` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a161/1Ub24A2RzHi)] [[code](https://github.com/Cryptology-Algorithm-Lab/Scores_Tell_Everything_about_Bob)]

22. **Why Does Little Robustness Help? A Further Step Towards Understanding Adversarial Transferability**. IEEE S&P 2024. `Exploring the transferability of adversarial examples` [[pdf](https://arxiv.org/pdf/2307.07873.pdf)] [[code](https://github.com/CGCL-codes/TransferAttackSurrogates)]

23. **Group-based Robustness: A General Framework for Customized Robustness in the Real World**. NDSS 2024. `New metrics to measure adversarial examples` [[pdf](https://arxiv.org/pdf/2306.16614.pdf)]

24. **DorPatch: Distributed and Occlusion-Robust Adversarial Patch to Evade Certifiable Defenses**. NDSS 2024. `Adversarial path against certified robustness` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-920-paper.pdf)] [[code](https://github.com/CGCL-codes/DorPatch)]

25. **UniID: Spoofing Face Authentication System by Universal Identity**. NDSS 2024. `Face apoofing attack` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-1036-paper.pdf)]

26. **Enhance Stealthiness and Transferability of Adversarial Attacks with Class Activation Mapping Ensemble Attack**. NDSS 2024. `Enhancing transferability of adversarial examples` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-164-paper.pdf)] [[code](https://github.com/DreamyRainforest/Class_Activation_Mapping_Ensemble_Attack)]

27. **Neural Invisibility Cloak: Concealing Adversary in Images via Compromised AI-driven Image Signal Processing**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhu-wenjun.pdf)]

28. **Self-interpreting Adversarial Images**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-tingwei.pdf)]

#### 1.1.2 Text

1. **TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation**. USENIX Security 2020. `Defense in preprossing` [[pdf](https://www.usenix.org/system/files/sec20-li-jinfeng.pdf)]

2. **Bad Characters: Imperceptible NLP Attacks**. IEEE S&P 2022. `Use unicode to conduct human imperceptible attack` [[pdf](https://arxiv.org/pdf/2106.09898.pdf)] [[code](https://github.com/nickboucher/imperceptible)]

3. **Order-Disorder: Imitation Adversarial Attacks for Black-box Neural Ranking Models**. ACM CCS 2022. `Attack Neural Ranking Models` [[pdf](https://arxiv.org/pdf/2209.06506.pdf)]

4. **No more Reviewer #2: Subverting Automatic Paper-Reviewer Assignment using Adversarial Learning**. USENIX Security 2023. `Adversarial Attack on Paper Assignment` [[pdf](https://arxiv.org/pdf/2303.14443.pdf)]

#### 1.1.3 Audio

1. **WaveGuard: Understanding and Mitigating Audio Adversarial Examples**. USENIX Security 2021. `Defense in preprossing` [[pdf](https://www.usenix.org/system/files/sec21fall-hussain.pdf)] [[code](https://github.com/shehzeen/waveguard_defense)]

2. **Dompteur: Taming Audio Adversarial Examples**. USENIX Security 2021. `Defense in preprossing. Preprocessing the audio to make the noise human noticeable` [[pdf](https://www.usenix.org/system/files/sec21-eisenhofer.pdf)] [[code](https://github.com/RUB-SysSec/dompteur)]

3. **EarArray: Defending against DolphinAttack via Acoustic Attenuation**. NDSS 2021. `Defense` [[pdf](https://www.ndss-symposium.org/ndss-paper/eararray-defending-against-dolphinattack-via-acoustic-attenuation/)]

4. **Who is Real Bob? Adversarial Attacks on Speaker Recognition Systems**. IEEE S&P 2021. `Attack` [[pdf](https://arxiv.org/pdf/1911.01840.pdf)] [[code](https://github.com/FAKEBOB-adversarial-attack/FAKEBOB)]

5. **Hear "No Evil", See "Kenansville": Efficient and Transferable Black-Box Attacks on Speech Recognition and Voice Identification Systems**. IEEE S&P 2021. `Black-box Attack` [[pdf](https://arxiv.org/pdf/1910.05262.pdf)]

6. **SoK: The Faults in our ASRs: An Overview of Attacks against Automatic Speech Recognition and Speaker Identification Systems**. IEEE S&P 2021. `Survey` [[pdf](https://arxiv.org/pdf/2007.06622.pdf)]

7. **AdvPulse: Universal, Synchronization-free, and Targeted Audio Adversarial Attacks via Subsecond Perturbations**. ACM CCS 2020. `Attack` [[pdf](http://www.winlab.rutgers.edu/~yychen/papers/li2020advpulse.pdf)]

8. **Black-box Adversarial Attacks on Commercial Speech Platforms with Minimal Information**. ACM CCS 2021. `Black-box Attack. Physical World` [[pdf](https://arxiv.org/pdf/2110.09714.pdf)]

9. **Perception-Aware Attack: Creating Adversarial Music via Reverse-Engineering Human Perception**. ACM CCS 2022. `Adversarial Audio with human-aware noise` [[pdf](https://arxiv.org/pdf/2207.13192.pdf)]

10. **SpecPatch: Human-in-the-Loop Adversarial Audio Spectrogram Patch Attack on Speech Recognition**. ACM CCS 2022. `Adversarial Patch for audio` [[pdf](https://cse.msu.edu/~qyan/paper/SpecPatch_CCS22.pdf)]

11. **Learning Normality is Enough: A Software-based Mitigation against Inaudible Voice Attacks**. USENIX Security 2023. `Unsupervised learning-based defense` [[pdf](https://www.usenix.org/conference/usenixsecurity23/presentation/li-xinfeng)]

12. **Understanding and Benchmarking the Commonality of Adversarial Examples**. IEEE S&P 2024. `Common features of adversarial audio examples` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a111/1Ub23jYBBHa)]

13. **ALIF: Low-Cost Adversarial Audio Attacks on Black-Box Speech Platforms using Linguistic Features**. IEEE S&P 2024. `Black-box adverarial audio attack` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a056/1RjEav0Daa4)] [[code](https://github.com/TASER2023/TASER)]

12. **Parrot-Trained Adversarial Examples: Pushing the Practicality of Black-Box Audio Attacks against Speaker Recognition Models**. NDSS 2024. `Black-box adverarial audio attack using parrot` [[pdf](https://arxiv.org/pdf/2311.07780.pdf)]

13. **When Translators Refuse to Translate: A Novel Attack to Speech Translation Systems**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wu-haolin.pdf)]

#### 1.1.4 Video

1. **Universal 3-Dimensional Perturbations for Black-Box Attacks on Video Recognition Systems**. IEEE S&P 2022. `Adversarial attack in video recognition` [[pdf](https://arxiv.org/pdf/2107.04284.pdf)]

2. **StyleFool: Fooling Video Classification Systems via Style Transfer**. IEEE S&P 2023. `Style Transfer to conduct adversarial attack` [[pdf](https://arxiv.org/pdf/2203.16000.pdf)] [[code](https://github.com/JosephCao0327/StyleFool)]

#### 1.1.5 Graph

1. **A Hard Label Black-box Adversarial Attack Against Graph Neural Networks**. ACM CCS 2021. `Graph Classification` [[pdf](https://arxiv.org/pdf/2108.09513.pdf)]

#### 1.1.6 Software

1. **Evading Classifiers by Morphing in the Dark**. ACM CCS 2017. `Morpher and search to generate adversarial PDF` [[pdf](https://arxiv.org/pdf/1705.07535.pdf)]

2. **Misleading Authorship Attribution of Source Code using Adversarial Learning**. USENIX Security 2019. `Adversarial attack in source code, MCST` [[pdf](https://arxiv.org/pdf/1905.12386.pdf)] [[code](http://www.tu-braunschweig.de/sec/research/code/imitator)]

3. **Intriguing Properties of Adversarial ML Attacks in the Problem Space**. IEEE S&P 2020. `Attack Malware Classification` [[pdf](https://arxiv.org/pdf/1911.02142.pdf)]

4. **Structural Attack against Graph Based Android Malware Detection**. IEEE S&P 2020. `Perturbed function call graph` [[pdf](https://www4.comp.polyu.edu.hk/~csxluo/HRAT.pdf)]

5. **URET: Universal Robustness Evaluation Toolkit (for Evasion)**. USENIX Security 2023. `General Toolbox to select the perdefined perturbations` [[pdf](https://www.usenix.org/system/files/sec23summer_347-eykholt-prepub.pdf)] [[code](https://github.com/IBM/URET)]

6. **Adversarial Training for Raw-Binary Malware Classifiers**. USENIX Security 2023. `Adversarial Training for Windows PE malware` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-146-lucas.pdf)]

7. **PELICAN: Exploiting Backdoors of Naturally Trained Deep Learning Models In Binary Code Analysis**. USENIX Security 2023. `Reverse engineering natural backdoor in transformer-based x86 binary code analysis task` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-493-zhang-zhuo.pdf)]

8. **Black-box Adversarial Example Attack towards FCG Based Android Malware Detection under Incomplete Feature Information**. USENIX Security 2023. `Black-box Android Adversarial Malware against the FCG-based ML classifier` [[pdf](https://arxiv.org/pdf/2303.08509.pdf)]

9.  **Efficient Query-Based Attack against ML-Based Android Malware Detection under Zero Knowledge Setting**. ACM CCS 2023. `Semantic similar perturbations are more likely to have similar evasion effectiveness` [[pdf](https://arxiv.org/pdf/2309.01866.pdf)] [[code](https://github.com/gnipping/AdvDroidZero-Access-Instructions)]

10. **Make a Feint to the East While Attacking in the West: Blinding LLM-Based Code Auditors with Flashboom Attacks**. IEEE S&P 2025.  [[pdf](https://ieeexplore.ieee.org/document/11023369)]


#### 1.1.7 Hardware

1. **ATTRITION: Attacking Static Hardware Trojan Detection Techniques Using Reinforcement Learning**. ACM CCS 2022. `Attack Hardware Trojan Detection` [[pdf](https://arxiv.org/pdf/2208.12897.pdf)]

2. **DeepShuffle: A Lightweight Defense Framework against Adversarial Fault Injection Attacks on Deep Neural Networks in Multi-Tenant Cloud-FPGA**. IEEE S&P 2024. `Adversarial defense against adversarial fault injection` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a034/1RjEa9WUlPi)]

#### 1.1.8 Interpret Method

1. **Interpretable Deep Learning under Fire**. USENIX Security 2020. `Attack both image classification and interpret method` [[pdf](https://www.usenix.org/system/files/sec20spring_zhang_prepub.pdf)]

2. **“Is your explanation stable?”: A Robustness Evaluation Framework for Feature Attribution**. ACM CCS 2022. `Hypothesis Testing to increasing the robustness of explaination methods` [[pdf](https://arxiv.org/pdf/2209.01782.pdf)]

3. **AIRS: Explanation for Deep Reinforcement Learning based Security Applications**. USENIX Security 2023. `DRL Interpertation Method to pinpoint the most influence step` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-36-yu-jiahao.pdf)] [[code](https://github.com/sherdencooper/AIRS)]

4. **SoK: Explainable Machine Learning in Adversarial Environments**. IEEE S&P 2024. `Adversarial Explaination SoK`  [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a021/1RjE9XVNjnW)

#### 1.1.9 Physical World

1. **SLAP: Improving Physical Adversarial Examples with Short-Lived Adversarial Perturbations**. USENIX Security 2021. `Projector light causes misclassification` [[pdf](https://www.usenix.org/system/files/sec21fall-lovisotto.pdf)] [[code](https://github.com/ssloxford/short-lived-adversarial-perturbations)]

2. **Understanding Real-world Threats to Deep Learning Models in Android Apps**. ACM CCS 2022. `Adversarial Attack in real-world models` [[pdf](https://arxiv.org/pdf/2209.09577.pdf)]

3. **X-Adv: Physical Adversarial Object Attacks against X-ray Prohibited Item Detection**. USENIX Security 2023. `Adversarial Attack on X-ray Images` [[pdf](https://arxiv.org/pdf/2302.09491.pdf)] [[code](https://github.com/DIG-Beihang/X-adv)]

4. **That Person Moves Like A Car: Misclassification Attack Detection for Autonomous Systems Using Spatiotemporal Consistency**. USENIX Security 2023. `Robust OD in Autonomous System using spatiotemporal information` [[pdf](https://www.usenix.org/system/files/sec23summer_278-man-prepub.pdf)]

5. **You Can't See Me: Physical Removal Attacks on LiDAR-based Autonomous Vehicles Driving Frameworks**. USENIX Security 2023. `Adversarial attack against Autonomous Vehicles using Laser` [[pdf](https://www.usenix.org/system/files/sec23summer_349-cao-prepub.pdf)] [demo](https://cpseclab.github.io/youcantseeme/)]

6. **CAPatch: Physical Adversarial Patch against Image Captioning Systems**. USENIX Security 2023. `Physical Adversarial Patch against the image caption system` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-121-zhang-shibo.pdf)] [[code](https://github.com/USSLab/CAPatch)]

7. **Exorcising "Wraith": Protecting LiDAR-based Object Detector in Automated Driving System from Appearing Attacks**. USENIX Security 2023. `Defend the appearing attack in autonomous system using local objectness predictor` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-190-xiao-qifan.pdf)] [[code](https://github.com/USSLab/CAPatch)]

8. **Invisible Reflections: Leveraging Infrared Laser Reflections to Target Traffic Sign Perception**. NDSS 2024. `Adversarial attacks on automous vehicles using infrared laser reflections` [[pdf](https://arxiv.org/pdf/2401.03582.pdf)]

9.  **Avara: A Uniform Evaluation System for Perceptibility Analysis Against Adversarial Object Evasion Attacks**. CCS 2024. `Adversarial Object Evasion attack evaluation system` [[pdf](https://drive.google.com/file/d/16qfqZpOED2W3wXmGibdDOIK5ctboend7/view)] [[code](https://sites.google.com/view/avara-artifacts)]

10. **VisionGuard: Secure and Robust Visual Perception of Autonomous Vehicles in Practice**. CCS 2024. `Adversarial Patch detection` [[pdf](hhttps://tianweiz07.github.io/Papers/24-ccs1.pdf)] [[demo](https://sites.google.com/view/visionguard)]

11. **Invisible but Detected: Physical Adversarial Shadow Attack and Defense on LiDAR Object Detection**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-kobayashi.pdf)]

12. **From Threat to Trust: Exploiting Attention Mechanisms for Attacks and Defenses in Cooperative Perception**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-chenyi.pdf)]

#### 1.1.10 Reinforcement Learning

1. **Adversarial Policy Training against Deep Reinforcement Learning**. USENIX Security 2021. `Weird behavior to trigger opposite abnormal action. Two-agent competitor game` [[pdf](https://www.usenix.org/system/files/sec21summer_wu-xian.pdf)] [[code](https://github.com/psuwuxian/rl_attack)]

2. **SUB-PLAY: Adversarial Policies against Partially Observed Multi-Agent Reinforcement Learning Systems**. CCS 2024. `Adversarial policy against the reinforcement learning system` [[pdf](https://arxiv.org/pdf/2402.03741)] [[code](https://github.com/maoubo/SUB-PLAY)]

3. **CAMP in the Odyssey: Provably Robust Reinforcement Learning with Certified Radius Maximization**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-derui.pdf)]

#### 1.1.11 Robust Defense

1. **Cost-Aware Robust Tree Ensembles for Security Applications**. USENIX Security 2021. `Propose Cost of feature to certify the model robustness` [[pdf](https://www.usenix.org/system/files/sec21-chen-yizheng.pdf)] [[code](https://github.com/surrealyz/growtrees)]

2. **CADE: Detecting and Explaining Concept Drift Samples for Security Applications**. USENIX Security 2021. `Detect Concept shift` [[pdf](https://www.usenix.org/system/files/sec21-yang-limin.pdf)] [[code](https://github.com/whyisyoung/CADE)]

3. **Learning Security Classifiers with Verified Global Robustness Properties**. ACM CCS 2021. `Train a classifier with global robustness` [[pdf](https://arxiv.org/pdf/2105.11363.pdf)] [[code](https://github.com/surrealyz/verified-global-properties)]

4. **On the Robustness of Domain Constraints**. ACM CCS 2021. `Domain constraints. Input space robustness` [[pdf](https://arxiv.org/pdf/2105.08619.pdf)]

5. **Cert-RNN: Towards Certifying the Robustness of Recurrent Neural Networks**. ACM CCS 2021. `Certify robustness in RNN` [[pdf](https://nesa.zju.edu.cn/download/dty_pdf_cert_rnn.pdf)]

6. **TSS: Transformation-Specific Smoothing for Robustness Certification**. ACM CCS 2021. `Certify robustness about transformation` [[pdf](https://arxiv.org/pdf/2002.12398.pdf)][[code](https://github.com/AI-secure/semantic-randomized-smoothing)]

7. **Transcend: Detecting Concept Drift in Malware Classification Models**. USENIX Security 2017. `Conformal evaluators` [[pdf](https://s2lab.cs.ucl.ac.uk/downloads/sec17-jordaney.pdf)] [[code](https://s2lab.cs.ucl.ac.uk/projects/transcend/)]

8. **Transcending Transcend: Revisiting Malware Classification in the Presence of Concept Drift**. IEEE S&P 2022. `New conformal evaluators` [[pdf](https://s2lab.cs.ucl.ac.uk/downloads/transcending.pdf)][[code](https://s2lab.cs.ucl.ac.uk/projects/transcend/)]

9.  **Transferring Adversarial Robustness Through Robust Representation Matching**. USENIX Security 2022. `Robust Transfer Learning` [[pdf](https://www.usenix.org/system/files/sec22-vaishnavi.pdf)]

10. **DiffSmooth: Certifiably Robust Learning via Diffusion Models and Local Smoothing**. USENIX Security 2023. `Diffusion Model Improve Certified Robustness` [[pdf](https://www.usenix.org/system/files/sec22-vaishnavi.pdf)]

12. **Anomaly Detection in the Open World: Normality Shift Detection, Explanation, and Adaptation**. NDSS 2023. `Concept Drift Detection using unsupervised approch` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f830_paper.pdf)] [[code](https://github.com/dongtsi/OWAD)]

13. **BARS: Local Robustness Certification for Deep Learning based Traffic Analysis Systems**. NDSS 2023. `Certified Robustness for Traffic Analysis Systems` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f508_paper.pdf)] [[code](https://github.com/KaiWangGitHub/BARS)]

14. **REaaS: Enabling Adversarially Robust Downstream Classifiers via Robust Encoder as a Service**. NDSS 2023. `Build a certificable EaaS model` [[pdf](https://arxiv.org/pdf/2301.02905.pdf)]

15. **Continuous Learning for Android Malware Detection**. USENIX Security 2023. `New Continual Learning Paridigram for Malware detection` [[pdf](https://arxiv.org/pdf/2302.04332.pdf)] [[code](https://github.com/wagner-group/active-learning)]

16. **ObjectSeeker: Certifiably Robust Object Detection against Patch Hiding Attacks via Patch-agnostic Masking**. IEEE S&P 2023. `Certified robustness of object detection` [[pdf](https://arxiv.org/pdf/2202.01811.pdf)] [[code](https://github.com/inspire-group/ObjectSeeker)]

17. **On The Empirical Effectiveness of Unrealistic Adversarial Hardening Against Realistic Adversarial Attacks**. IEEE S&P 2023. `Adversarial attacks on feature space may enhance the robustness in problem space` [[pdf](https://arxiv.org/pdf/2202.03277.pdf)] [[code](https://github.com/serval-uni-lu/realistic_adversarial_hardening)]

18. **Text-CRS: A Generalized Certified Robustness Framework against Textual Adversarial Attacks**. IEEE S&P 2024. `Certified robustness on adversarial text` [[pdf](https://arxiv.org/pdf/2307.16630.pdf)] [[code](https://github.com/Eyr3/TextCRS?tab=readme-ov-file)]

19. **It's Simplex! Disaggregating Measures to Improve Certified Robustness**. IEEE S&P 2024. `Disagreement to improve the certified robustness` [[pdf](https://arxiv.org/pdf/2309.11005.pdf)] [[code](https://github.com/andrew-cullen/ensemble-simplex-certifications)]

20. **SoK: Efficiency Robustness of Dynamic Deep Learning Systems**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-rathnasuriya.pdf)]

21. **AGNNCert: Defending Graph Neural Networks against Arbitrary Perturbations with Deterministic Certification**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-li-jiate.pdf)]

22. **Robustifying ML-powered Network Classifiers with PANTS**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-jin-minhao.pdf)]

23. **CertTA: Certified Robustness Made Practical for Learning-Based Traffic Analysis**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-yan-jinzhu.pdf)]

#### 1.1.12 Network Traffic

1. **Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations**. USENIX Security 2021. `Adversarial attack to defeat DNN-based traffic analysis` [[pdf](https://www.usenix.org/system/files/sec21fall-nasr.pdf)] [[code](https://github.com/SPIN-UMass/BLANKET)]

2. **Pryde: A Modular Generalizable Workflow for Uncovering Evasion Attacks Against Stateful Firewall Deployments**. IEEE S&P 2024. `Evasion attack against Firewalls` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a144/1Ub242nYFoY)]

3. **Multi-Instance Adversarial Attack on GNN-Based Malicious Domain Detection**. IEEE S&P 2024. `Adversarial attack on GNN-based malicious domain detection` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a006/1RjE9LaYR0c)] [[code](https://github.com/mahmoudkanazzal/MintA)]

#### 1.1.13 Wireless Communication System

1. **Robust Adversarial Attacks Against DNN-Based Wireless Communication Systems**. ACM CCS 2021. `Attack` [[pdf](https://arxiv.org/pdf/2102.00918.pdf)]

#### 1.1.14 Tabular Data

1. **Adversarial Robustness for Tabular Data through Cost and Utility Awareness**. NDSS 2023. `Adversarial Attack & Defense on tabular data` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f924_paper.pdf)]

### 1.2 Distributed Machine Learning

#### 1.2.1 Federated Learning

1. **Local Model Poisoning Attacks to Byzantine-Robust Federated Learning**. USENIX Security 2020. `Poisoning Attack` [[pdf](https://www.usenix.org/system/files/sec20summer_fang_prepub.pdf)]

2. **Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses for Federated Learning**. NDSS 2021. `Poisoning Attack` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6C-3_24498_paper.pdf)]

3. **DeepSight: Mitigating Backdoor Attacks in Federated Learning Through Deep Model Inspection**. NDSS 2022. `Backdoor defense` [[pdf](https://arxiv.org/pdf/2201.00763.pdf)]

4. **FLAME: Taming Backdoors in Federated Learning**. USENIX Security 2022. `Backdoor defense` [[pdf](https://www.usenix.org/system/files/sec22-nguyen.pdf)]

5. **EIFFeL: Ensuring Integrity for Federated Learning**. ACM CCS 2022. `New FL Protocol to guarteen integrity` [[pdf](https://arxiv.org/pdf/2112.12727.pdf)]

6. **Eluding Secure Aggregation in Federated Learning via Model Inconsistency**. ACM CCS 2022. `Model inconsistency to break the secure aggregation` [[pdf](https://arxiv.org/pdf/2111.07380.pdf)]

7. **FedRecover: Recovering from Poisoning Attacks in Federated Learning using Historical Information**. IEEE S&P 2023. `Poisoned Model Recovery Algorithm` [[pdf](https://arxiv.org/pdf/2210.10936.pdf)]

8. **Every Vote Counts: Ranking-Based Training of Federated Learning to Resist Poisoning Attacks**. USENIX Security 2023. `Discrete the model updates and purning the model to defense the poisoning attack` [[pdf](https://arxiv.org/pdf/2110.04350.pdf)] [[code](https://github.com/SPIN-UMass/FRL)]

9.  **Securing Federated Sensitive Topic Classification against Poisoning Attacks**. NDSS 2023. `Robust Aggregation against the poisoning attack` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s112_paper.pdf)]

10. **BayBFed: Bayesian Backdoor Defense for Federated Learning**. IEEE S&P 2023. `Purify the model updates using bayesian` [[pdf](https://arxiv.org/pdf/2301.09508.pdf)]

11. **ADI: Adversarial Dominating Inputs in Vertical Federated Learning Systems**. IEEE S&P 2023. `Poisoning the vertical federated learning system` [[pdf](https://arxiv.org/pdf/2201.02775.pdf)] [[code](https://github.com/Qi-Pang/ADI)]

12. **3DFed: Adaptive and Extensible Framework for Covert Backdoor Attack in Federated Learning**. IEEE S&P 2023. `Convert normal backdoor into the federated learning scenario` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b893/1NrbZhCP5ao)]

13. **FLShield: A Validation Based Federated Learning Framework to Defend Against Poisoning Attacks**. IEEE S&P 2023. `Data poisoning defense` [[pdf](https://arxiv.org/pdf/2308.05832.pdf)]

14. **BadVFL: Backdoor Attacks in Vertical Federated Learning**. IEEE S&P 2023. `Backdoor attacks against vertical federated learning` [[pdf](https://arxiv.org/pdf/2304.08847.pdf)]

15. **CrowdGuard: Federated Backdoor Detection in Federated Learning**. NDSS 2024. `Backdoor detection in federated learning leveraging hidden layer outputs` [[pdf](https://arxiv.org/pdf/2210.07714.pdf)] [[code](https://github.com/TRUST-TUDa/crowdguard)]

16. **Automatic Adversarial Adaption for Stealthy Poisoning Attacks in Federated Learning**. NDSS 2024. `Adaptative poisoning attacks in FL` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-1366-paper.pdf)]

17. **FreqFed: A Frequency Analysis-Based Approach for Mitigating Poisoning Attacks in Federated Learning**. NDSS 2024. `Mitigate poisoning attack in FL using frequency analysis techniques` [[pdf](https://arxiv.org/pdf/2312.04432.pdf)]

18. **Dealing Doubt: Unveiling Threat Models in Gradient Inversion Attacks under Federated Learning – A Survey and Taxonomy**. CCS 2024. `Mitigate poisoning attack in FL using frequency analysis techniques` [[pdf](https://arxiv.org/pdf/2312.04432.pdf)]

19. **Byzantine-Robust Decentralized Federated Learning**. CCS 2024. `Byzantine robust federated learning` [[pdf](https://arxiv.org/pdf/2406.10416)]

20. **PoiSAFL: Scalable Poisoning Attack Framework to Byzantine-resilient Semi-asynchronous Federated Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-pang-xiaoyi.pdf)]

21. **DeBackdoor: A Deductive Framework for Detecting Backdoor Attacks on Deep Models with Limited Data**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-popovic.pdf)]

#### 1.2.2 Normal Distributed Learning

1. **Justinian's GAAvernor: Robust Distributed Learning with Gradient Aggregation Agent**. USENIX Security 2020. `Defense in Gradient Aggregation. Reinforcement learning` [[pdf](https://www.usenix.org/system/files/sec20-pan.pdf)]

### 1.3 Data Poisoning

#### 1.3.1 Hijack Embedding

1. **Humpty Dumpty: Controlling Word Meanings via Corpus Poisoning**. IEEE S&P 2020. `Hijack Word Embedding` [[pdf](https://www.cs.cornell.edu/~shmat/shmat_oak20.pdf)]

#### 1.3.2 Hijack Autocomplete Code

1. **You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion**. USENIX Security 2021. `Hijack Code Autocomplete` [[pdf](https://www.usenix.org/system/files/sec21-schuster.pdf)]

2. **TROJANPUZZLE: Covertly Poisoning Code-Suggestion Models**. IEEE S&P 2024. `Hijack Code Autocomplete` [[pdf](https://arxiv.org/pdf/2301.02344.pdf)] [[code](https://github.com/microsoft/CodeGenerationPoisoning)]

#### 1.3.3 Semi-Supervised Learning

1. **Poisoning the Unlabeled Dataset of Semi-Supervised Learning**. USENIX Security 2021. `Poisoning semi-supervised learning` [[pdf](https://www.usenix.org/system/files/sec21-carlini-poisoning.pdf)]

#### 1.3.4 Recommender Systems

1. **Data Poisoning Attacks to Deep Learning Based Recommender Systems**. NDSS 2021. `The attacker chosen items are recommended as much as possible` [[pdf](https://arxiv.org/pdf/2101.02644.pdf)]

1. **Reverse Attack: Black-box Attacks on Collaborative Recommendation**. ACM CCS 2021. `Black-box setting. Surrogate model. Collaborative Filtering. Demoting and Promoting` [[pdf](https://dl.acm.org/doi/abs/10.1145/3460120.3484805)]

#### 1.3.5 Classification

1. **Subpopulation Data Poisoning Attacks**. ACM CCS 2021. `Poisoning to flip a group of data samples` [[pdf](https://arxiv.org/pdf/2006.14026.pdf)]

1. **Get a Model! Model Hijacking Attack Against Machine Learning Models**. NDSS 2022. `Fusing dataset to hijacking model` [[pdf](https://arxiv.org/pdf/2111.04394.pdf)] [[code](https://github.com/AhmedSalem2/Model-Hijacking)]


#### 1.3.6 Constractive Learning

1. **PoisonedEncoder: Poisoning the Unlabeled Pre-training Data in Contrastive Learning**. USENIX Security 2022. `Poison attack in constractive learning` [[pdf](https://www.usenix.org/system/files/sec22-liu-hongbin.pdf)]

1. **Preference Poisoning Attacks on Reward Model Learning**. IEEE S&P 2025. `Poison attack in reward model learning` [[pdf](https://arxiv.org/pdf/2402.01920)]

#### 1.3.7 Privacy

1. **Truth Serum: Poisoning Machine Learning Models to Reveal Their Secrets**. ACM CCS 2022. `Poison attack to reveal sensitive information` [[pdf](https://arxiv.org/pdf/2204.00032.pdf)]


#### 1.3.8 Test-Time Poisoning

1. **Test-Time Poisoning Attacks Against Test-Time Adaptation Models**. IEEE S&P 2024. `Poisoning attack at test time` [[pdf](https://arxiv.org/pdf/2308.08505.pdf)] [[code](https://github.com/tianshuocong/TePA)]

#### 1.3.9 Defense

1. **Poison Forensics: Traceback of Data Poisoning Attacks in Neural Networks**. USENIX Security 2022. `Identify poisioned subset by clustering and purning benign set` [[pdf](https://www.usenix.org/system/files/sec22-shan.pdf)]

2. **Understanding Implosion in Text-to-Image Generative Models**. CCS 2024. `Analytic framework for the poisoning attack against T2I model` [[pdf](https://arxiv.org/pdf/2409.12314)]

### 1.4 Backdoor

#### 1.4.1 Image

1. **Demon in the Variant: Statistical Analysis of DNNs for Robust Backdoor Contamination Detection**. USENIX Security 2021. `Class-specific Backdoor. Defense by decomposition` [[pdf](https://www.usenix.org/system/files/sec21-tang-di.pdf)]

2. **Double-Cross Attacks: Subverting Active Learning Systems**. USENIX Security 2021. `Active Learning System. Backdoor Attack` [[pdf](https://www.usenix.org/system/files/sec21-vicarte.pdf)] 

3. **Detecting AI Trojans Using Meta Neural Analysis**. IEEE S&P 2021. `Meta Neural Classifier` [[pdf](https://arxiv.org/pdf/1910.03137.pdf)] [[code](https://github.com/AI-secure/Meta-Nerual-Trojan-Detection)]

4. **BadEncoder: Backdoor Attacks to Pre-trained Encoders in Self-Supervised Learning**. IEEE S&P 2022. `Backdoor attack in image-text pretrained model` [[pdf](https://arxiv.org/pdf/2108.00352.pdf)] [[code](https://github.com/jjy1994/BadEncoder)]

5. **Composite Backdoor Attack for Deep Neural Network by Mixing Existing Benign Features**. ACM CCS 2020. `Composite backdoor. Image & text tasks` [[pdf](https://dl.acm.org/doi/10.1145/3372297.3423362)] [[code](https://github.com/TemporaryAcc0unt/composite-attack)]

6. **AI-Lancet: Locating Error-inducing Neurons to Optimize Neural Networks**. ACM CCS 2021. `Locate neural location and finetuning it` [[pdf](https://dl.acm.org/doi/pdf/10.1145/3460120.3484818)]

7. **LoneNeuron: a Highly-Effective Feature-Domain Neural Trojan Using Invisible and Polymorphic Watermarks**. ACM CCS 2022. `Backdoor attack by modifying neuros` [[pdf](https://www.ittc.ku.edu/~bluo/download/liu2022ccs.pdf)]

8. **ATTEQ-NN: Attention-based QoE-aware Evasive Backdoor Attacks**. NDSS 2022. `Backdoor attack by attention techniques` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2022-12-paper.pdf)]

9. **RAB: Provable Robustness Against Backdoor Attacks**. IEEE S&P 2023. `Backdoor Cetrification` [[pdf](https://arxiv.org/pdf/2003.08904.pdf)]

10. **A Data-free Backdoor Injection Approach in Neural Networks**. USENIX Security 2023. `Data free backdoor injection` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-573-lv.pdf)] [[code](https://github.com/lvpeizhuo/Data-free_Backdoor)]

11. **Backdoor Attacks Against Dataset Distillation**. NDSS 2023. `Backdoor attack against dataset istillation` [[pdf](https://arxiv.org/pdf/2301.01197.pdf)] [[code](https://github.com/liuyugeng/baadd)]

12. **BEAGLE: Forensics of Deep Learning Backdoor Attack for Better Defense**. NDSS 2023. `Backdoor Forensics` [[pdf](https://arxiv.org/pdf/2301.06241.pdf)] [[code](https://github.com/Megum1/BEAGLE)]

13. **Disguising Attacks with Explanation-Aware Backdoors**. IEEE S&P 2023. `Backdoor to mislead the explaination method` [[pdf](https://intellisec.de/pubs/2023-ieeesp.pdf)]

14. **Selective Amnesia: On Efficient, High-Fidelity and Blind Suppression of Backdoor Effects in Trojaned Machine Learning Models**. IEEE S&P 2023. `Finetuning to remove backdoor` [[pdf](https://arxiv.org/pdf/2212.04687.pdf)]

15. **AI-Guardian: Defeating Adversarial Attacks using Backdoors**. IEEE S&P 2023. `using backdoor to detect adversarial example. Backdoor with all-to-all mapping and reverse the mapping` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a701/1NrbXZPyl7W)]

16. **REDEEM MYSELF: Purifying Backdoors in Deep Learning Models using Self Attention Distillation**. IEEE S&P 2023. `Purifying backdoor using model distillation` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a755/1NrbYbKqcHS)]

17. **NARCISSUS: A Practical Clean-Label Backdoor Attack with Limited Information**. ACM CCS 2023. `Clean label backdoor attack` [[pdf](https://arxiv.org/pdf/2204.05255.pdf)] [[code](https://github.com/ruoxi-jia-group/Narcissus-backdoor-attack)]

18. **ASSET: Robust Backdoor Data Detection Across a Multiplicity of Deep Learning Paradigms**. USENIX Security 2023. `Backdoor Defense works in Different Learning Paradigms` [[pdf](https://www.usenix.org/system/files/usenixsecurity23-pan.pdf)] [[code](https://github.com/ruoxi-jia-group/ASSET)]

19. **ODSCAN: Backdoor Scanning for Object Detection Models**. IEEE S&P 2024. `Backdoor defense by model dynamics` [[pdf](https://arxiv.org/pdf/2312.02673.pdf)] [[github](https://github.com/tedbackdoordefense/ted)]

20. **MM-BD: Post-Training Detection of Backdoor Attacks with Arbitrary Backdoor Pattern Types Using a Maximum Margin Statistic**. IEEE S&P 2024. `Backdoor defense using maximum margin statistic in classification layer` [[pdf](https://arxiv.org/pdf/2205.06900.pdf)] [[github](https://github.com/wanghangpsu/MM-BD)]

21. **Distribution Preserving Backdoor Attack in Self-supervised Learning**. IEEE S&P 2024. `Backdoor attack in contrastive learning by improving the distribution` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a029/1RjEa5rjsHK)] [[github](https://github.com/Gwinhen/DRUPE?tab=readme-ov-file)]

22. **Backdooring Bias (B^2) into Stable Diffusion Models**. USENIX Security 2025. `Backdoor attack in stable diffusion model` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-naseh.pdf)]

23. **Watch the Watchers! On the Security Risks of Robustness-Enhancing Diffusion Models**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-li-changjiang.pdf)]

24. **Pretender: Universal Active Defense against Diffusion Finetuning Attacks**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-sun-zekun.pdf)]

25. **Rowhammer-Based Trojan Injection: One Bit Flip Is Sufficient for Backdooring DNNs**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-li-xiang.pdf)]

26. **From Purity to Peril: Backdooring Merged Models From "Harmless" Benign Components**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-lijin.pdf)]

27. **Revisiting Training-Inference Trigger Intensity in Backdoor Attacks**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-lin-chenhao.pdf)]

28. **Persistent Backdoor Attacks in Continual Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-guo-zhen.pdf)]

#### 1.4.2 Text

1. **T-Miner: A Generative Approach to Defend Against Trojan Attacks on DNN-based Text Classification**. USENIX Security 2021. `Backdoor Defense. GAN to recover trigger` [[pdf](https://www.usenix.org/system/files/sec21fall-azizi.pdf)] [[code](https://github.com/reza321/T-Miner)]

2. **Hidden Backdoors in Human-Centric Language Models**. ACM CCS 2021. `Novel trigger` [[pdf](https://arxiv.org/pdf/2105.00164.pdf)] [[code](https://github.com/lishaofeng/NLP_Backdoor)]

3. **Backdoor Pre-trained Models Can Transfer to All**. ACM CCS 2021. `Backdoor in pre-trained to poison the down stream task` [[pdf](https://arxiv.org/pdf/2111.00197.pdf)] [[code](https://github.com/lishaofeng/NLP_Backdoor)]

4. **Hidden Trigger Backdoor Attack on NLP Models via Linguistic Style Manipulation**. USENIX Security 2022. `Backdoor via linguistic style manipulation` [[pdf](https://www.usenix.org/system/files/sec22-pan-hidden.pdf)]

5. **TextGuard: Provable Defense against Backdoor Attacks on Text Classification**. NDSS 2024. `Provable backdoor defense by spliting the sentence and ensumble learning` [[pdf](https://arxiv.org/pdf/2311.11225.pdf)] [[code](https://github.com/AI-secure/TextGuard)]

#### 1.4.3 Graph

1. **Graph Backdoor**. USENIX Security 2021. `Classification` [[pdf](https://arxiv.org/pdf/2006.11890.pdf)] [[code](https://github.com/HarrialX/GraphBackdoor)]

2. **Distributed Backdoor Attacks on Federated Graph Learning and Certified Defenses**. CCS 2024. `Distributed Backdoor attacks on federated graph learning` [[pdf](https://arxiv.org/pdf/2407.08935)] [[code](https://github.com/Yuxin104/Opt-GDBA)]

#### 1.4.4 Software

1. **Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers**. USENIX Security 2021. `Explanation Method. Evade Classification` [[pdf](https://www.usenix.org/system/files/sec21fall-severi.pdf)] [[code](https://github.com/ClonedOne/MalwareBackdoors)]

#### 1.4.5 Audio

1. **TrojanModel: A Practical Trojan Attack against Automatic Speech Recognition Systems**. IEEE S&P 2023. `Backdoor attack in speech recognition systems` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a906/1Js0DtfUrKw)]

2. **MagBackdoor: Beware of Your Loudspeaker as Backdoor of Magnetic Attack for Malicious Command Injection**. IEEE S&P 2023. `Backdoor attack in audio using magentic trigget` [[pdf](https://huskyachao.github.io/publication/magbackdoor-oakland23/)]

#### 1.4.6 Multimedia

1. **Backdooring Multimodal Learning**. IEEE S&P 2024. `Backdoor attack in multimedia learning` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a031/1RjEa7rmaxW)] [[code](https://github.com/multimodalbags/BAGS_Multimodal)]

#### 1.4.7 Neuromorphic Data

1. **Sneaky Spikes: Uncovering Stealthy Backdoor Attacks in Spiking Neural Networks with Neuromorphic Data**. NDSS 2024. `Backdoor attack in neuromorphic data` [[pdf](https://arxiv.org/pdf/2302.06279.pdf)] [[code](https://github.com/GorkaAbad/Sneaky-Spikes)]

### 1.5 ML Library Security

#### 1.5.1 Loss

1. **Blind Backdoors in Deep Learning Models**. USENIX Security 2021. `Loss Manipulation. Backdoor` [[pdf](https://www.cs.cornell.edu/~shmat/shmat_usenix21blind.pdf)] [[code](https://github.com/ebagdasa/backdoors101)]

2. **IvySyn: Automated Vulnerability Discovery in Deep Learning Frameworks**. USENIX Security 2023. `Automatic Bug Discovery in ML libraries` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-125-christou.pdf)]

### 1.6 AI4Security

#### 1.6.1 Cyberbullying

1. **Towards Understanding and Detecting Cyberbullying in Real-world Images**. NDSS 2021. `Detect image cyberbully` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_7C-4_24260_paper.pdf)]

2. **You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content**. IEEE S&P 2024. `Using LLM for toxic content detection` [[pdf](https://arxiv.org/pdf/2308.05596.pdf)] [[code](https://github.com/xinleihe/toxic-prompt)]

3. **HateBench: Benchmarking Hate Speech Detectors on LLM-Generated Content and Hate Campaigns**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-shen.pdf)] [[code](https://github.com/TrustAIRLab/HateBench)]

#### 1.6.2 Security Applications

1. **FARE: Enabling Fine-grained Attack Categorization under Low-quality Labeled Data**. NDSS 2021. `Clustering Method to complete the dataset label` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_5C-4_24403_paper.pdf)] [[code](https://github.com/junjieliang672/FARE)]

2. **From Grim Reality to Practical Solution: Malware Classification in Real-World Noise**. IEEE S&P 2023. `Noise Learning method for malware detection` [[pdf](https://henrygwb.github.io/publications/sp23.pdf)] [[code](https://github.com/gnipping/morse)]

3. **Decoding the Secrets of Machine Learning in Windows Malware Classification: A Deep Dive into Datasets, Features, and Model Performance**. ACM CCS 2023. `static features are better than dynamic feature in WindowsPE malware detection` [[pdf](https://arxiv.org/pdf/2307.14657.pdf)]

4. **KAIROS: Practical Intrusion Detection and Investigation using Whole-system Provenance**. IEEE S&P 2024. `GNN-based intrusion detection method` [[pdf](https://arxiv.org/pdf/2308.05034.pdf)] [[code](https://github.com/ProvenanceAnalytics/kairos)]

5. **FLASH: A Comprehensive Approach to Intrusion Detection via Provenance Graph Representation Learning**. IEEE S&P 2024. `GNN-based intrusion detection method` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a139/1Ub23WQw20U)] [[code](https://github.com/DART-Laboratory/Flash-IDS)]

6. **Understanding and Bridging the Gap Between Unsupervised Network Representation Learning and Security Analytics**. IEEE S&P 2024. `Unsupervised graph learning for graph-based security applications` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a012/1RjE9Q5gQrm)] [[code](https://github.com/C0ldstudy/Argus)]

7. **FP-Fed: Privacy-Preserving Federated Detection of Browser Fingerprinting**. NDSS 2024. `Federated learning for browser fingerprinting` [[pdf](https://arxiv.org/pdf/2311.16940.pdf)]

8. **GNNIC: Finding Long-Lost Sibling Functions with Abstract Similarity**. NDSS 2024. `GNN for static analysis` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-492-paper.pdf)]

9.  **Experimental Analyses of the Physical Surveillance Risks in Client-Side Content Scanning**. NDSS 2024. `Attack client scanning systems` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-1401-paper.pdf)]

10. **Attributions for ML-based ICS Anomaly Detection: From Theory to Practice**. NDSS 2024. `Evaluating attribution methods for industrial control systems` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-216-paper.pdf)] [[code](https://github.com/pwwl/ics-anomaly-attribution)]

11. **DRAINCLoG: Detecting Rogue Accounts with Illegally-obtained NFTs using Classifiers Learned on Graphs**. NDSS 2024. `Detecting rogue accounts in NFTs using GNN` [[pdf](https://arxiv.org/pdf/2301.13577.pdf)]

12. **Low-Quality Training Data Only? A Robust Framework for Detecting Encrypted Malicious Network Traffic**. NDSS 2024. `Training ML-based traffic detection using low-quality data` [[pdf](https://arxiv.org/pdf/2309.04798.pdf)] [[code](https://github.com/XXnormal/RAPIER)]

13. **SafeEar: Content Privacy-Preserving Audio Deepfake Detection**. ACM CCS 2024. `Speech content privacy-preserving deepfake detection`  [[pdf](https://arxiv.org/pdf/2409.09272)] [[website](https://safeearweb.github.io/Project/)] [[code](https://github.com/LetterLiGo/SafeEar)] [[dataset](https://zenodo.org/records/11229569)]

14. **USD: NSFW Content Detection for Text-to-Image Models via Scene Graph**. USENIX Security 2025. `NSFWE image detection`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-yuyang.pdf)] 

14. **On the Proactive Generation of Unsafe Images From Text-To-Image Models Using Benign Prompts**. USENIX Security 2025. `NSFWE image defense`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wu-yixin-generation.pdf)]

15. **VoiceWukong: Benchmarking Deepfake Voice Detection**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-yan-ziwei.pdf)]

16. **SafeSpeech: Robust and Universal Voice Protection Against Malicious Speech Synthesis**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-zhisheng.pdf)]

#### 1.6.3 Advertisement Detection

1. **WtaGraph: Web Tracking and Advertising Detection using Graph Neural Networks**. IEEE S&P 2022. `GNN` [[pdf](https://zhiju.me/assets/files/WtaGraph_SP22.pdf)]

#### 1.6.4 CAPTCHA

1. **Text Captcha Is Dead? A Large Scale Deployment and Empirical Studys**. ACM CCS 2020. `Adversarial CAPTCHA` [[pdf](https://nesa.zju.edu.cn/download/Text%20Captcha%20Is%20Dead%20A%20Large%20Scale%20Deployment%20and%20Empirical%20Study.pdf)]

2. **Attacks as Defenses: Designing Robust Audio CAPTCHAs Using Attacks on Automatic Speech Recognition Systems**. NDSS 2023. `Adversarial Audio CAPTCHA` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f243_paper.pdf)] [[demo](https://sites.google.com/view/attacksasdefenses/home)]

3. **A Generic, Efficient, and Effortless Solver with Self-Supervised Learning for Breaking Text Captchas**. IEEE S&P 2023. `Text CAPTCHA Solver` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b524/1Js0E2VGRhe)]

#### 1.6.5 Code Analysis

1. **PalmTree: Learning an Assembly Language Model for Instruction Embedding**. ACM CCS 2021. `Pre-trained model to generate code embedding` [[pdf](https://arxiv.org/pdf/2103.03809.pdf)] [[code](https://github.com/palmtreemodel/PalmTree)]

2. **CALLEE: Recovering Call Graphs for Binaries with Transfer and Contrastive Learning**. IEEE S&P 2023. `Recovering call graph from binaries using transfer and contrastive learning` [[pdf](https://arxiv.org/pdf/2111.01415.pdf)] [[code](https://github.com/vul337/Callee)]

3. **Examining Zero-Shot Vulnerability Repair with Large Language Models**. IEEE S&P 2023. `Zero-short vulnerability repair using large language model` [[pdf](https://arxiv.org/pdf/2112.02125.pdf)]

4. **Raconteur: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer**. NDSS 2025. `LLM-powered malicious code analysis` [[pdf](https://arxiv.org/pdf/2409.02074)] [[website](https://raconteur-ndss.github.io/)]

#### 1.6.6 Chatbot

1. **Why So Toxic? Measuring and Triggering Toxic Behavior in Open-Domain Chatbots**. ACM CCS 2022. `Measuring Chatbot Textico behavior` [[pdf](https://arxiv.org/pdf/2209.03463.pdf)]

#### 1.6.7 Side Channel Attack

1. **Towards a General Video-based Keystroke Inference Attack**. USENIX Security 2023. `Self Supervised Learning to recover the keybroad input` [[pdf](https://www.usenix.org/system/files/sec23summer_338-yang_zhuolin-prepub.pdf)]

2. **Deep perceptual hashing algorithms with hidden dual purpose: when client-side scanning does facial recognition**. IEEE S&P 2023. `Manipulate deep phash algorithm to conduct specific person inference` [[pdf](https://arxiv.org/pdf/2306.11924.pdf)] [[code](https://github.com/computationalprivacy/dual-purpose-client-side-scanning)]


#### 1.6.8 Guidline

1. **Dos and Don'ts of Machine Learning in Computer Security**. USENIX Security 2022. `Survey pitfalls in ML4Security` [[pdf](https://www.usenix.org/system/files/sec22summer_arp.pdf)]

2. **“Security is not my field, I’m a stats guy”: A Qualitative Root Cause Analysis of Barriers to Adversarial Machine Learning Defenses in Industry**. USENIX Security 2023. `Survey AML Application in Industry` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-324-mink.pdf)]

3. **Everybody’s Got ML, Tell Me What Else You Have: Practitioners’ Perception of ML-Based Security Tools and Explanations**. IEEE S&P 2023. `Explainable AI in practice` [[pdf](https://gangw.cs.illinois.edu/Security_ML-user.pdf)]


#### 1.6.9 Security Event

1. **CERBERUS: Exploring Federated Prediction of Security Events**. ACM CCS 2022. `Federated Learning to predict security event` [[pdf](https://arxiv.org/pdf/2209.03050.pdf)]

#### 1.6.10 Vulnerability Discovery

1. **VulChecker: Graph-based Vulnerability Localization in Source Code**. USENIX Security 2023. `Detecting Bugs using GCN` [[pdf](https://www.usenix.org/conference/usenixsecurity23/presentation/mirsky)] [[code](https://github.com/ymirsky/VulChecker)]

### 1.7 AutoML Security

#### 1.7.1 Security Analysis

1. **On the Security Risks of AutoML**. USENIX Security 2022. `Adversarial evasion. Model poisoning. Backdoor. Functionality stealing. Membership Inference` [[pdf](https://www.usenix.org/system/files/sec22summer_pang.pdf)]

### 1.8 Hardware Related Security 

#### 1.8.1 Verification

1. **DeepDyve: Dynamic Verification for Deep Neural Networks**. ACM CCS 2020. [[pdf](https://arxiv.org/pdf/2009.09663.pdf)]

2. **NeuroPots: Realtime Proactive Defense against Bit-Flip Attacks in Neural Networks**. USENIX Security 2023. `Honey Pot to trap the bitflip attacks` [[pdf](https://www.usenix.org/system/files/sec23summer_334-liu_qi-prepub.pdf)]

3. **Aegis: Mitigating Targeted Bit-flip Attacks against Deep Neural Networks**. USENIX Security 2023. `Train multi classifer to defend the BFA` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-246-wang-jialai.pdf)] [[code](https://github.com/vul337/Aegis)]

### 1.9 Security Related Interpreting Method

#### 1.9.1 Anomaly Detection

1. **DeepAID: Interpreting and Improving Deep Learning-based Anomaly Detection in Security Applications**. ACM CCS 2021. `Anomaly detection`  [[pdf](https://arxiv.org/pdf/2109.11495.pdf)] [[code](https://github.com/dongtsi/DeepAID)]

#### 1.9.2 Faithfulness

1. **Good-looking but Lacking Faithfulness: Understanding Local Explanation Methods through Trend-based Testing**. ACM CCS 2023. `Trend-based faithfulness testing`  [[pdf](https://arxiv.org/pdf/2309.05679.pdf)] [[code](https://github.com/JenniferHo97/XAI-TREND-TEST)]

#### 1.9.3 Security Applications

1. **FINER: Enhancing State-of-the-art Classifiers with Feature Attribution to Facilitate Security Analysis**. ACM CCS 2023. `Ensumble explaination for different stakeholder`  [[pdf](https://arxiv.org/pdf/2308.05362.pdf)] [[code](https://github.com/E0HYL/FINER-explain)]

### 1.10 Face Security

#### 1.10.1 Deepfake Detection

1. **Who Are You (I Really Wanna Know)? Detecting Audio DeepFakes Through Vocal Tract Reconstruction**. USENIX Security 2022. `deepfake detection using vocal tract reconstruction`  [[pdf](https://www.usenix.org/system/files/sec22fall_blue.pdf)]

#### 1.10.2 Face Impersonation

1. **ImU: Physical Impersonating Attack for Face Recognition System with Natural Style Changes**. IEEE S&P 2023. `StyleGAN to impersonate persion`  [[pdf](https://kaiyuanzhang.com/publications/SP23_ImU.pdf)] [[code](https://github.com/njuaplusplus/imu)]

2. **DepthFake: Spoofing 3D Face Authentication with a 2D Photo**. IEEE S&P 2023. `Adversarial image to attack 3D photos`  [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b710/1Js0EgNcf8A)] [[demo](https://sites.google.com/view/depthfake)]

#### 1.10.3 Face Verification Systems

1. **Understanding the (In)Security of Cross-side Face Verification Systems in Mobile Apps: A System Perspective**. IEEE S&P 2023. `Measurement study of the security risks of cross-side face verification systems.`  [[pdf](https://yinzhicao.org/xfvschecker/XFVSChecker.pdf)]

### 1.10 AI Generation Security

#### 1.10.1 Text Generation Detection

1. **Deepfake Text Detection: Limitations and Opportunities**. IEEE S&P 2023. `Detecting the machine generated text`  [[pdf](https://arxiv.org/pdf/2210.09421.pdf)] [[code](https://github.com/jmpu/DeepfakeTextDetection)]

2. **MGTBench: Benchmarking Machine-Generated Text Detection**. CCS 2024. `Benchmarking machine generated text detection`  [[pdf](https://arxiv.org/pdf/2303.14822)] [[code](https://github.com/xinleihe/MGTBench)]

#### 1.10.2 Deepfake

1. **SoK: The Good, The Bad, and The Unbalanced: Measuring Structural Limitations of Deepfake Media Datasets**. USENIX Security 2024. `Issues in deepfake media dataset`  [[pdf](https://www.usenix.org/system/files/usenixsecurity24-layton.pdf)] [[website](https://sites.google.com/view/thegoodthebadandtheunbalanced)]

2. **SafeEar: Content Privacy-Preserving Audio Deepfake Detection**. ACM CCS 2024. `Speech content privacy-preserving deepfake detection`  [[pdf](https://arxiv.org/pdf/2409.09272)] [[website](https://safeearweb.github.io/Project/)] [[code](https://github.com/LetterLiGo/SafeEar)] [[dataset](https://zenodo.org/records/11229569)]

3. **"Better Be Computer or I’m Dumb": A Large-Scale Evaluation of Humans as Audio Deepfake Detectors**. ACM CCS 2024. `Huamn in deepfake detection`  [[pdf](https://cise.ufl.edu/~butler/pubs/ccs24-warren-deepfake.pdf)]

### 1.11 LLM Security

#### 1.11.1 Code Analysis

1. **Large Language Models for Code: Security Hardening and Adversarial Testing**. ACM CCS 2023. `Prefix tuning for secure code generation`  [[pdf](https://arxiv.org/pdf/2302.05319.pdf)] [[code](https://github.com/eth-sri/sven)]

2. **DeGPT: Optimizing Decompiler Output with LLM**. NDSS 2024. `LLM-enhanced reverse engineering`  [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-401-paper.pdf)] [[code](https://github.com/PeiweiHu/DeGPT)]

3. **Raconteur: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer**. NDSS 2025. `LLM-powered malicious code analysis` [[pdf](https://arxiv.org/pdf/2409.02074)] [[website](https://raconteur-ndss.github.io/)]

4. **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with Large Language Models (LLMs)**. CCS 2024. `Black-box LLM secure code generation` [[pdf](https://arxiv.org/pdf/2409.12699)] [[code](https://github.com/mahmoudkanazzal/PromSec)]

5. **We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-spracklen.pdf)]

#### 1.11.2 Vision-Language Model

1. **Transferable Multimodal Attack on Vision-Language Pre-training Models**. IEEE S&P 2024. `Transferable adversarial attack on VLM`  [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a102/1Ub239H4xyg)]

2. **SneakyPrompt: Jailbreaking Text-to-image Generative Models**. IEEE S&P 2024. `Jailbreaking text-to-image generative model using reinforcement-learning adversarial NLP methods`  [[pdf](https://arxiv.org/pdf/2305.12082.pdf)] [[code](https://github.com/Yuchen413/text2image_safety)]
  
3. **SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models**. ACM CCS 2024. `defending against unsafe content generation in text-to-image models`  [[pdf](https://arxiv.org/pdf/2404.06666)] [[code](https://github.com/LetterLiGo/SafeGen_CCS2024)] [[model](https://huggingface.co/LetterJohn/SafeGen-Pretrained-Weights)]

4. **SurrogatePrompt: Bypassing the Safety Filter of Text-to-Image Models via Substitution**. ACM CCS 2024. `Bypassing the safety filter of T2I model` [[pdf](https://arxiv.org/pdf/2309.14122)]

5. **Moderator: Moderating Text-to-Image Diffusion Models through Fine-grained Context-based Policies**. ACM CCS 2024. `Content moderating for T2I model` [[pdf](https://arxiv.org/pdf/2408.07728)] [[code](https://github.com/DataSmithLab/Moderator)]

6. **Bridging the Gap in Vision Language Models in Identifying Unsafe Concepts Across Modalities**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-qu-yiting.pdf)]

7. **Are CAPTCHAs Still Bot-hard? Generalized Visual CAPTCHA Solving with Agentic Vision Language Model**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-teoh.pdf)]

8. **From Meme to Threat: On the Hateful Meme Understanding and Induced Hateful Content Generation in Open-Source Vision Language Models**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-ma-yihan.pdf)]

#### 1.11.3 Jailbreaking

1. **MASTERKEY: Automated Jailbreaking of Large Language Model Chatbots**. NDSS 2024. `LLM jailbreaking`  [[pdf](https://arxiv.org/pdf/2307.08715.pdf)]

2. **Mind the Inconspicuous: Revealing the Hidden Weakness in Aligned LLMs' Refusal Boundaries**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-yu-jiahao.pdf)]

3. **Refusal Is Not an Option: Unlearning Safety Alignment of Large Language Models**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-song-minkyoo.pdf)] [[code](https://doi.org/10.5281/zenodo.15628860)]

4. **Activation Approximations Can Incur Safety Vulnerabilities in Aligned LLMs: Comprehensive Analysis and Defense**. USENIX Security 2025. `LLM jailbreaking defense`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-jiawen.pdf)]

5. **Exposing the Guardrails: Reverse-Engineering and Jailbreaking Safety Filters in DALL·E Text-to-Image Pipelines**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-villa.pdf)]

6. **TwinBreak: Jailbreaking LLM Security Alignments based on Twin Prompts**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-krauss.pdf)]

7. **Exploiting Task-Level Vulnerabilities: An Automatic Jailbreak Attack and Defense Benchmarking for LLMs**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-lan.pdf)]

8. **PAPILLON: Efficient and Stealthy Fuzz Testing-Powered Jailbreaks for LLMs**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-gong-xueluan.pdf)]

9.  **Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack**. USENIX Security 2025. `LLM jailbreaking`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-russinovich.pdf)]

10. **SelfDefend: LLMs Can Defend Themselves against Jailbreaking in a Practical Manner**. USENIX Security 2025. `LLM jailbreaking defense` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-xunguang.pdf)]

11. **JBShield: Defending Large Language Models from Jailbreak Attacks through Activated Concept Analysis and Manipulation**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-shenyi.pdf)]

#### 1.11.4 Robustness

1. **Improving the Robustness of Transformer-based Large Language Models with Dynamic Attention**. NDSS 2024. `Improving the robustness of LLM by dynamic attention`  [[pdf](https://arxiv.org/pdf/2311.17400.pdf)]

#### 1.11.5 Generated Concent

1. **DEMASQ: Unmasking the ChatGPT Wordsmith**. NDSS 2024. `Generated text detection`  [[pdf](https://arxiv.org/pdf/2311.05019.pdf)]

2. **Organic or Diffused: Can We Distinguish Human Art from AI-generated Images?**. CCS 2024. `Human arts and the AI-generated image detection`  [[pdf](https://arxiv.org/pdf/2402.03214)]

3. **On the Detectability of ChatGPT Content: Benchmarking, Methodology, and Evaluation through the Lens of Academic Writing**. CCS 2024. `LLM generated concent detection`  [[pdf](https://arxiv.org/pdf/2306.05524v2)]

3. **GradEscape: A Gradient-Based Evader Against AI-Generated Text Detectors**. USENIX Security 2025. `evade LLM generated concent detection`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-meng.pdf)] [[code](https://zenodo.org/records/15807727)]

4. **Data-Free Model-Related Attacks: Unleashing the Potential of Generative AI**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-ye-attacks.pdf)] [[code](https://zenodo.org/records/14737003)]

5. **"I Cannot Write This Because It Violates Our Content Policy": Understanding Content Moderation Policies and User Experiences in Generative AI Products**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-gao-lan.pdf)]

6. **Generated Data with Fake Privacy: Hidden Dangers of Fine-tuning Large Language Models on Generated Data**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-akkus.pdf)]

#### 1.11.6 Backdoor

1. **LMSanitator: Defending Prompt-Tuning Against Task-Agnostic Backdoors**. NDSS 2024. `Task-agnostic backdoor detection`  [[pdf](https://arxiv.org/pdf/2308.13904.pdf)] [[code](https://github.com/meng-wenlong/LMSanitator)]

2. **EmbedX: Embedding-Based Cross-Trigger Backdoor Attack Against Large Language Models**. USENIX Security 2025. `Backdoor attack in LLM`  [[pdf](https://www.usenix.org/system/files/usenixsecurity25-yan-nan.pdf)]

#### 1.11.7 Agent Security

1. **When LLMs Go Online: The Emerging Threat of Web-Enabled LLMs**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-kim-hanna.pdf)]

2. **Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-liu-fengyu.pdf)]

3. **TracLLM: A Generic Framework for Attributing Long Context LLMs**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-yanting.pdf)] [[code](https://github.com/Wang-Yanting/TracLLM)]

4. **Unsafe LLM-Based Search: Quantitative Analysis and Mitigation of Safety Risks in AI Web Search**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-luo-zeren.pdf)]

5. **Cloak, Honey, Trap: Proactive Defenses Against LLM Agents**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-ayzenshteyn.pdf)]

6. **Big Help or Big Brother? Auditing Tracking, Profiling, and Personalization in Generative AI Assistants**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-vekaria.pdf)]

#### 1.11.8 Prompt Injection

1. **StruQ: Defending Against Prompt Injection with Structured Queries**. USENIX Security 2025. `Prompt Injection Defense` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-chen-sizhe.pdf)]

2. **Machine Against the RAG: Jamming Retrieval-Augmented Generation with Blocker Documents**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-shafran.pdf)]

#### 1.11.9 Hallucination

1. **Mirage in the Eyes: Hallucination Attack on Multi-modal Large Language Models with Only Attention Sink**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-yining.pdf)]

## 2. Privacy Papers

### 2.1 Training Data

#### 2.1.1 Data Recovery

1. **Updates-Leak: Data Set Inference and Reconstruction Attacks in Online Learning**. USENIX Security 2020. `Online Learning. Model updates` [[pdf](https://www.usenix.org/system/files/sec20summer_salem_prepub.pdf)]

2. **Extracting Training Data from Large Language Models**. USENIX Security 2021. `Membership inference attack. GPT-2` [[pdf](https://www.usenix.org/system/files/sec21-carlini-extracting.pdf)]

3. **Analyzing Information Leakage of Updates to Natural Language Models**. ACM CCS 2020. `data leakage in model changes` [[pdf](https://www.microsoft.com/en-us/research/uploads/prod/2020/09/ccs20.pdf)]

4. **TableGAN-MCA: Evaluating Membership Collisions of GAN-Synthesized Tabular Data Releasing**. ACM CCS 2021. `Membership collision in GAN` [[pdf](https://arxiv.org/pdf/2107.13190.pdf)]

5. **DataLens: Scalable Privacy Preserving Training via Gradient Compression and Aggregation**. ACM CCS 2021. `DP to train an privacy preserving GAN` [[pdf](https://arxiv.org/pdf/2103.11109.pdf)]

6. **Property Inference Attacks Against GANs**. NDSS 2022. `Property Inference Attacks Against GAN`  [[pdf](https://yangzhangalmo.github.io/papers/NDSS22-PIAGAN.pdf)] [[code](https://github.com/Zhou-Junhao/PIA_GAN)]

7. **MIRROR: Model Inversion for Deep Learning Network with High Fidelity**. NDSS 2022. `Model inversion attack using GAN`  [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2022-335-paper.pdf)] [[code](https://model-inversion.github.io/mirror/)]

8. **Analyzing Leakage of Personally Identifiable Information in Language Models**. IEEE S&P 2023. `Personally identifiable information leakage in language model`  [[pdf](https://arxiv.org/pdf/2302.00539.pdf)] [[code](https://github.com/microsoft/analysing_pii_leakage)]

9.  **Timing Channels in Adaptive Neural Networks**. NDSS 2024. `Infer input of adaptive NN using timing information`  [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-125-paper.pdf)] [[code](https://github.com/akinsanyaayomide/ADNNTimeLeaks)]

10. **Crafter: Facial Feature Crafting against Inversion-based Identity Theft on Deep Models**. NDSS 2024. `Protect model inversion attack`  [[pdf](https://arxiv.org/pdf/2401.07205.pdf)] [[code](https://github.com/ShimingWang98/Facial_Feature_Crafting_against_Inversion_based_Identity_Theft/tree/main)]

11. **Transpose Attack: Stealing Datasets with Bidirectional Training**. NDSS 2024. `Stealing dataset in bidirectional models`  [[pdf](https://arxiv.org/pdf/2311.07389.pdf)] [[code](https://github.com/guyAmit/Transpose-Attack-paper-NDSS24-/tree/main)]

12. **SafeEar: Content Privacy-Preserving Audio Deepfake Detection**. ACM CCS 2024. `Speech content privacy-preserving deepfake detection`  [[pdf](https://arxiv.org/pdf/2409.09272)] [[website](https://safeearweb.github.io/Project/)] [[code](https://github.com/LetterLiGo/SafeEar)] [[dataset](https://zenodo.org/records/11229569)]

13. **Dye4AI: Assuring Data Boundary on Generative AI Services**. ACM CCS 2024. `Dye testing system in LLM`  [[pdf](https://arxiv.org/pdf/2406.14114)]

14. **Evaluations of Machine Learning Privacy Defenses are Misleading**. ACM CCS 2024. `Evaluation DP defense`  [[pdf](https://arxiv.org/pdf/2404.17399)] [[code](https://github.com/ethz-spylab/misleading-privacy-evals?tab=readme-ov-file)]

15. **Towards a Re-evaluation of Data Forging Attacks in Practice**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-suliman.pdf)]

16. **SoK: Data Reconstruction Attacks Against Machine Learning Models: Definition, Metrics, and Benchmark**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wen.pdf)]

#### 2.1.2 Membership Inference Attack

1. **Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference**. USENIX Security 2020. `White-box Setting` [[pdf](https://www.usenix.org/system/files/sec20-leino.pdf)]

2. **Systematic Evaluation of Privacy Risks of Machine Learning Models**. USENIX Security 2020. `Metric-based Membership inference Attack Method. Define Privacy Risk Score` [[pdf](https://www.usenix.org/system/files/sec21fall-song.pdf)] [[code](https://github.com/inspire-group/membership-inference-evaluation)]

3. **Practical Blind Membership Inference Attack via Differential Comparisons**. NDSS 2021. `Use non-member data to replace shadow model` [[pdf](https://arxiv.org/pdf/2101.01341.pdf)] [[code](https://github.com/hyhmia/BlindMI)]

4. **GAN-Leaks: A Taxonomy of Membership Inference Attacks against Generative Models**. ACM CCS 2020. `Membership inference attack in Generative model. Member has small reconstruction error` [[pdf](https://arxiv.org/pdf/1909.03935.pdf)]

5. **Quantifying and Mitigating Privacy Risks of Contrastive Learning**. ACM CCS 2021. `Membership inference attack. Property inference attack. Contrastive learning in classification task` [[pdf](https://yangzhangalmo.github.io/papers/CCS21-ContrastivePrivacy.pdf)] [[code](https://github.com/xinleihe/ContrastiveLeaks)]

6. **Membership Inference Attacks Against Recommender Systems**. ACM CCS 2021. `Recommender System` [[pdf](https://yangzhangalmo.github.io/papers/CCS21-RecommenderMIA.pdf)] [[code](https://github.com/minxingzhang/MIARS)]

7. **EncoderMI: Membership Inference against Pre-trained Encoders in Contrastive Learning**. ACM CCS 2021. `Contrastive learning in pre-trained model. Data augmentation has higher similarity` [[pdf](https://arxiv.org/pdf/2108.11023.pdf)] [[code](https://github.com/minxingzhang/MIARS)]

8. **Auditing Membership Leakages of Multi-Exit Networks**. ACM CCS 2022. `Membership inference attack in multi-exit networks` [[pdf](https://arxiv.org/pdf/2208.11180.pdf)]

9.  **Membership Inference Attacks by Exploiting Loss Trajectory**. ACM CCS 2022. `Membership inference attack, knowledge distillation` [[pdf](https://arxiv.org/pdf/2208.14933.pdf)]

10. **On the Privacy Risks of Cell-Based NAS Architectures**. ACM CCS 2022. `Membership inference attack in NAS` [[pdf](https://arxiv.org/pdf/2209.01688.pdf)]

12. **Membership Inference Attacks and Defenses in Neural Network Pruning**. USENIX Security 2022. `Membership inference attack in Neural Network Pruning` [[pdf](https://www.usenix.org/system/files/sec22-yuan-xiaoyong.pdf)]

13. **Mitigating Membership Inference Attacks by Self-Distillation Through a Novel Ensemble Architecture**. USENIX Security 2022. `Membership inference defense by ensemble` [[pdf](https://www.usenix.org/system/files/sec22-yuan-xiaoyong.pdf)]

14. **Enhanced Membership Inference Attacks against Machine Learning Models**. USENIX Security 2022. `Membership inference attack with hypothesis testing` [[pdf](https://arxiv.org/pdf/2111.09679.pdf)] [[code](https://github.com/privacytrustlab/ml_privacy_meter/tree/master/research/2022_enhanced_mia)]

15. **Membership Inference Attacks and Generalization: A Causal Perspective**. ACM CCS 2022. `Membership inference attack with casual reasoning` [[pdf](https://arxiv.org/pdf/2209.08615.pdf)]

16. **SLMIA-SR: Speaker-Level Membership Inference Attacks against Speaker Recognition Systems**. NDSS 2024. `Membership inference attack in speaker recongization` [[pdf](https://arxiv.org/pdf/2309.07983.pdf)] [[code](https://github.com/S3L-official/SLMIA-SR)]

17. **Overconfidence is a Dangerous Thing: Mitigating Membership Inference Attacks by Enforcing Less Confident Prediction**. NDSS 2024. `The defense of membership inference attack` [[pdf](https://arxiv.org/pdf/2307.01610.pdf)] [[code](https://github.com/DependableSystemsLab/MIA_defense_HAMP)]

18. **Membership Inference Attacks Against Vision-Language Models**. USENIX Security 2025. `Membership inference attack in vision language model` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-hu-yuke.pdf)]

19. **Towards Label-Only Membership Inference Attack against Pre-trained Large Language Models**. USENIX Security 2025. `Membership inference attack in LLM` [[pdf](https://www.usenix.org/conference/usenixsecurity25/presentation/he-yu)]

20. **Enhanced Label-Only Membership Inference Attacks with Fewer Queries**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-li-hao.pdf)]

21. **SOFT: Selective Data Obfuscation for Protecting LLM Fine-tuning against Membership Inference Attacks**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zhang-kaiyuan.pdf)]

#### 2.1.3 Information Leakage in Distributed ML System

1. **Label Inference Attacks Against Vertical Federated Learning**. USENIX Security 2022. `Label Leakage. Federated Learning` [[pdf](https://www.usenix.org/system/files/sec22summer_fu.pdf)] [[code](https://github.com/minxingzhang/MIARS)]

2. **The Value of Collaboration in Convex Machine Learning with Differential Privacy**. IEEE S&P 2020. `DP as Defense` [[pdf](https://arxiv.org/pdf/1906.09679.pdf)]

3. **Leakage of Dataset Properties in Multi-Party Machine Learning**. USENIX Security 2021. `Dataset Properties Leakage` [[pdf](https://www.usenix.org/system/files/sec21-zhang-wanrong.pdf)]

4. **Unleashing the Tiger: Inference Attacks on Split Learning**. ACM CCS 2021. `Split learning. Feature-space hijacking attack` [[pdf](https://arxiv.org/pdf/2012.02670.pdf)] [[code](https://github.com/pasquini-dario/SplitNN_FSHA)]

5. **Local and Central Differential Privacy for Robustness and Privacy in Federated Learning**. NDSS 2022. `DP in federated learning` [[pdf](https://arxiv.org/pdf/2009.03561.pdf)]

6. **Gradient Obfuscation Gives a False Sense of Security in Federated Learning**. USENIX Security 2023. `Data Recovery in federated learning` [[pdf](https://www.usenix.org/system/files/sec23summer_372-yue-prepub.pdf)]

7. **PPA: Preference Profiling Attack Against Federated Learning**. NDSS 2023. `Preference Leakage in federated learning` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s171_paper.pdf)] [[code](https://github.com/PPAattack/PPAattack)]

8. **On the (In)security of Peer-to-Peer Decentralized Machine Learning**. IEEE S&P 2023. `Information leakage in peer-to-peer decentralized machine learning system` [[pdf](https://arxiv.org/pdf/2205.08443.pdf)]

9.  **RoFL: Robustness of Secure Federated Learning**. IEEE S&P 2023. `Robust Federated Learning Framework using Secuire Aggregation` [[pdf](https://arxiv.org/pdf/2107.03311.pdf)] [[code](https://github.com/pps-lab/rofl-project-code)]

10. **Scalable and Privacy-Preserving Federated Principal Component Analysis**. IEEE S&P 2023. `Privacy preserving feaderated PCA algorithm` [[pdf](https://arxiv.org/pdf/2304.00129.pdf)]

11. **Protecting Label Distribution in Cross-Silo Federated Learning**. IEEE S&P 2024. `Priveacy-preserving SGD to protect label distribution` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a113/1Ub23mqt0hG)]

12. **LOKI: Large-scale Data Reconstruction Attack against Federated Learning through Model Manipulation**. IEEE S&P 2024. `Dataset reconstruction attack in fedearted learning by sending customized convoluational kernel` [[pdf](https://arxiv.org/pdf/2303.12233.pdf)]

13. **Analyzing Inference Privacy Risks Through Gradients In Machine Learning**. CCS 2024. `information leakage through gradients` [[pdf](https://arxiv.org/pdf/2408.16913)]

14. **Boosting Gradient Leakage Attacks: Data Reconstruction in Realistic FL Settings**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-fan-boosting.pdf)]

15. **Refiner: Data Refining against Gradient Leakage Attacks in Federated Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-fan-boosting.pdf)]

16. **Aion: Robust and Efficient Multi-Round Single-Mask Secure Aggregation Against Malicious Participants**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-liu-yizhong.pdf)]

17. **SoK: On Gradient Leakage in Federated Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-du.pdf)]

18. **DP-BREM: Differentially-Private and Byzantine-Robust Federated Learning with Client Momentum**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-gu-xiaolan.pdf)]

19. **SLOTHE : Lazy Approximation of Non-Arithmetic Neural Network Functions over Encrypted Data**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-nam-slothe.pdf)]

20. **Sharpness-Aware Initialization: Improving Differentially Private Machine Learning from First Principles**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-zihao.pdf)]

21. **Task-Oriented Training Data Privacy Protection for Cloud-based Model Training**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-zhiqiang.pdf)]

22. **From Risk to Resilience: Towards Assessing and Mitigating the Risk of Data Reconstruction Attacks in Federated Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-xu-xiangrui.pdf)]

23. **SoK: Gradient Inversion Attacks in Federated Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-carletti.pdf)]

#### 2.1.4 Information Leakage in Embedding

1. **Privacy Risks of General-Purpose Language Models**. IEEE S&P 2020. `Pretrained Language Model` [[pdf](https://nesa.zju.edu.cn/download/Privacy%20Risks%20of%20General-Purpose%20Language%20Models.pdf)]

1. **Information Leakage in Embedding Models**. ACM CCS 2020. `Exact Word Recovery. Attribute inference. Membership inference` [[pdf](https://arxiv.org/pdf/2004.00053.pdf)]

1. **Honest-but-Curious Nets: Sensitive Attributes of Private Inputs Can Be Secretly Coded into the Classifiers' Outputs**. ACM CCS 2021. `Infer privacy information in classification output` [[pdf](https://arxiv.org/pdf/2105.12049.pdf)] [[code](https://github.com/mmalekzadeh/honest-but-curious-nets)]

#### 2.1.5 Graph Leakage

1. **Stealing Links from Graph Neural Networks**. USENIX Security 2021. `Inference Graph Link` [[pdf](https://arxiv.org/pdf/2105.12049.pdf)]

2. **Inference Attacks Against Graph Neural Networks**. USENIX Security 2022. `Property inference: number of nodes. Subgraph inference. Graph reconstruction` [[pdf](https://www.usenix.org/system/files/sec22summer_zhang-zhikun.pdf)] [[code](https://github.com/Zhangzhk0819/GNN-Embedding-Leaks)]

3. **LinkTeller: Recovering Private Edges from Graph Neural Networks via Influence Analysis**. IEEE S&P 2022. `Use node connection influence to infer graph edges` [[pdf](https://arxiv.org/pdf/2108.06504.pdf)]

4. **Locally Private Graph Neural Networks**. IEEE S&P 2022. `LDP as defense for node privacy` [[pdf](https://arxiv.org/pdf/2006.05535.pdf)] [[code](https://github.com/sisaman/LPGNN)]

5. **Finding MNEMON: Reviving Memories of Node Embeddings**. ACM CCS 2022. `Graph recovery attack through node embedding` [[pdf](https://arxiv.org/pdf/2204.06963.pdf)]

6. **Group Property Inference Attacks Against Graph Neural Networks**. ACM CCS 2022. `Group Property inference attack on GNN` [[pdf](https://arxiv.org/pdf/2209.01100.pdf)]

7. **LPGNet: Link Private Graph Networks for Node Classification**. ACM CCS 2022. `DP to build private GNN` [[pdf](https://arxiv.org/pdf/2205.03105.pdf)]

8. **GraphGuard: Detecting and Counteracting Training Data Misuse in Graph Neural Networks**. MDSS 2024. `Mitigate data misuse issues in GNN` [[pdf](https://arxiv.org/pdf/2312.07861.pdf)] [[code](https://github.com/GraphGuard/GraphGuard-Proactive)]

8. **GRID: Protecting Training Graph from Link Stealing Attacks on GNN Models**. IEEE S&P 2025. `Link stealing defense` [[pdf](https://arxiv.org/pdf/2501.10985)] [[code](https://github.com/GraphGuard/GraphGuard-Proactive)]

#### 2.1.6 Unlearning

1. **Machine Unlearning**. IEEE S&P 2020. `Shard and isolate the training dataset` [[pdf](https://arxiv.org/pdf/1912.03817.pdf)] [[code](https://github.com/cleverhans-lab/machine-unlearning)]

2. **When Machine Unlearning Jeopardizes Privacy**. ACM CCS 2021. `Membership inference attack in unlearning setting` [[pdf](https://arxiv.org/pdf/2005.02205.pdf)] [[code](https://github.com/MinChen00/UnlearningLeaks)]

3. **Graph Unlearning**. ACM CCS 2022. `Graph Unlearning` [[pdf](https://arxiv.org/pdf/2103.14991.pdf)] [[code](https://github.com/MinChen00/Graph-Unlearning)]

4. **On the Necessity of Auditable Algorithmic Definitions for Machine Unlearning**. ACM CCS 2022. `Auditable Unlearning` [[pdf](https://www.usenix.org/system/files/sec22fall_thudi.pdf)]

5. **Machine Unlearning of Features and Labels**. NDSS 2023. `Influence Function to achieve unlearning` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s87_paper.pdf)] [[code](https://github.com/alewarne/MachineUnlearning)]

6. **A Duty to Forget, a Right to be Assured? Exposing Vulnerabilities in Machine Unlearning Services**. NDSS 2024. `The vulnerabilities in machine unlearning` [[pdf](https://arxiv.org/pdf/2309.08230.pdf)] [[code](https://github.com/TASI-LAB/Over-unlearning)]

7. **ERASER: Machine Unlearning in MLaaS via an Inference Serving-Aware Approach**. CCS 2024. `Machine unlearning as a inferencing-aware approach` [[pdf](https://arxiv.org/pdf/2311.16136)]

8. **Rectifying Privacy and Efficacy Measurements in Machine Unlearning: A New Inference Attack Perspective**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-naderloui.pdf)]

9.  **Data Duplication: A Novel Multi-Purpose Attack Paradigm in Machine Unlearning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-ye-duplication.pdf)]

10. **Towards Lifecycle Unlearning Commitment Management: Measuring Sample-level Unlearning Completeness**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wang-cheng-long.pdf)]

#### 2.1.7 Attribute Inference Attack

1. **Are Attribute Inference Attacks Just Imputation?**. ACM CCS 2022. `Attribute Inference Attack by identified neuro with data` [[pdf](https://arxiv.org/pdf/2209.01292.pdf)] [[code](https://github.com/bargavj/EvaluatingDPML)]

2. **Feature Inference Attack on Shapley Values**. ACM CCS 2022. `Attribute Inference Attack using shapley values` [[pdf](https://dl.acm.org/doi/abs/10.1145/3548606.3560573)]

3. **QuerySnout: Automating the Discovery of Attribute Inference Attacks against Query-Based Systems**. ACM CCS 2022. `Attribute Inference detection` [[pdf](https://arxiv.org/pdf/2211.05249.pdf)]

4. **Disparate Privacy Vulnerability: Targeted Attribute Inference Attacks and Defenses**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-kabir.pdf)]

#### 2.1.7 Property Inference Attack

1. **SNAP: Efficient Extraction of Private Properties with Poisoning**. IEEE S&P 2023. `Stronger Property Inference Attack by poisoning the data` [[pdf](https://arxiv.org/pdf/2208.12348.pdf)] [[code](https://github.com/johnmath/snap-sp23)]

#### 2.1.8 Data Synthesis

1. **SoK: Privacy-Preserving Data Synthesis**. IEEE S&P 2024. `Privacy-Preserving Data Synthesis` [[pdf](https://arxiv.org/pdf/2307.02106.pdf)] [[website](https://sok-ppds.github.io/)]

#### 2.1.8 Dataset Auditing

1. **ORL-AUDITOR: Dataset Auditing in Offline Deep Reinforcement Learning**. NDSS 2024. `Dataset auditing in deep reinforcement learning` [[pdf](https://arxiv.org/pdf/2309.03081.pdf)] [[code](https://github.com/link-zju/ORL-Auditor)]

1. **SoK: Dataset Copyright Auditing in Machine Learning Systems**. IEEE S&P 2025. `Dataset copyright` [[pdf](https://arxiv.org/pdf/2410.16618)]

### 2.2 Model

#### 2.2.1 Model Extraction

1. **Exploring Connections Between Active Learning and Model Extraction**. USENIX Security 2020. `Active Learning` [[pdf](https://www.usenix.org/system/files/sec20-chandrasekaran.pdf)]

2. **High Accuracy and High Fidelity Extraction of Neural Networks**. USENIX Security 2020. `Fidelity` [[pdf](https://arxiv.org/pdf/1909.01838.pdf)]

3. **DRMI: A Dataset Reduction Technology based on Mutual Information for Black-box Attacks**. USENIX Security 2021. `Query Data Selection Method to reduce the query` [[pdf](https://www.usenix.org/system/files/sec21-he-yingzhe.pdf)]

4. **Entangled Watermarks as a Defense against Model Extraction**. USENIX Security 2021. `Backdoor as watermark against model extraction` [[pdf](https://www.usenix.org/system/files/sec21fall-jia.pdf)]

5. **CloudLeak: Large-Scale Deep Learning Models Stealing Through Adversarial Examples**. NDSS 2020. `Adversarial Example to strengthen model stealing` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24178.pdf)]

6. **Teacher Model Fingerprinting Attacks Against Transfer Learning**. USENIX Securiy 2022. `Teacher model fingerprinting` [[pdf](https://www.usenix.org/system/files/sec22-chen-yufei.pdf)]

7. **StolenEncoder: Stealing Pre-trained Encoders in Self-supervised Learning**. ACM CCS 2022. `Model Stealing attack in encoder` [[pdf](https://arxiv.org/pdf/2201.05889.pdf)]

8. **D-DAE: Defense-Penetrating Model Extraction Attacks**. IEEE S&P 2023. `Meta classifier to classify the defense and generator model to reduce the noise` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a432/1He7YbsiH4c)]

9.  **SoK: Neural Network Extraction Through Physical Side Channels**. USENIX Security 2024. `Physical Side Channel-based model extraction` [[pdf](https://www.usenix.org/system/files/usenixsecurity24-horvath.pdf)]

10. **SoK: All You Need to Know About On-Device ML Model Extraction - The Gap Between Research and Practice**. USENIX Security 2024. `on device model extraction` [[pdf](https://www.usenix.org/system/files/usenixsecurity24-nayan.pdf)]

#### 2.2.2 Model Watermark

1. **Adversarial Watermarking Transformer: Towards Tracing Text Provenance with Data Hiding**. IEEE S&P 2021. `Encode secret message into LM` [[pdf](https://arxiv.org/pdf/2009.03015.pdf)]

2. **Rethinking White-Box Watermarks on Deep Learning Models under Neural Structural Obfuscation**. USENIX Security 2023. `Inject dummy neurons into the model to break the white-box model watermark` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-444-yan-yifan.pdf)]

3. **MEA-Defender: A Robust Watermark against Model Extraction Attack**. IEEE S&P 2024. `Backdoor as watermark` [[pdf](https://arxiv.org/pdf/2401.15239.pdf)] [[code](https://github.com/lvpeizhuo/MEA-Defender)]

4. **SSL-WM: A Black-Box Watermarking Approach for Encoders Pre-trained by Self-Supervised Learning**. NDSS 2024. `Watermark on self-supervised learning` [[pdf](https://arxiv.org/pdf/2209.03563.pdf)] [[code](https://github.com/lvpeizhuo/SSL-WM)]

5. **Watermarking Language Models for Many Adaptive Users**. IEEE S&P 2025. `Watermark on LLM` [[pdf](https://arxiv.org/pdf/2209.03563.pdf)] [[code](https://arxiv.org/pdf/2405.11109)]

6. **SoK: Watermarking for AI-Generated Content**. IEEE S&P 2025. [[pdf](https://arxiv.org/pdf/2411.18479)]

7. **Provably Robust Multi-bit Watermarking for AI-generated Text**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-qu-watermarking.pdf)] [[code](https://arxiv.org/pdf/2405.11109)]

8. **AUDIO WATERMARK: Dynamic and Harmless Watermark for Black-box Voice Dataset Copyright Protection**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-guo-hanqing.pdf)]

9.  **AudioMarkNet: Audio Watermarking for Deepfake Speech Detection**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-zong.pdf)]

10. **Towards Understanding and Enhancing Security of Proof-of-Training for DNN Model Ownership Verification**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-chang-yijia-verification.pdf)]

11. **LightShed: Defeating Perturbation-based Image Copyright Protections**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-foerster.pdf)]

12. **A Crack in the Bark: Leveraging Public Knowledge to Remove Tree-Ring Watermarks**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-lin-junhua.pdf)]

#### 2.2.3 Model Owenership

1. **Proof-of-Learning: Definitions and Practice**. IEEE S&P 2021. `Proof the ownership of model parameters` [[pdf](https://arxiv.org/pdf/2103.05633.pdf)]

2. **SoK: How Robust is Image Classification Deep Neural Network Watermarking?**. IEEE S&P 2022. `Survey of DNN watermarking` [[pdf](https://arxiv.org/pdf/2108.04974.pdf)]

3. **Copy, Right? A Testing Framework for Copyright Protection of Deep Learning Models**. IEEE S&P 2022. `Calculate model similarity by generating test examples` [[pdf](https://nesa.zju.edu.cn/download/cjl_pdf_sp22.pdf)] [[code](https://github.com/Testing4AI/DeepJudge)]

4. **SSLGuard: A Watermarking Scheme for Self-supervised Learning Pre-trained Encoders**. ACM CCS 2022. `Watermarking in encoder` [[pdf](https://arxiv.org/pdf/2201.11692.pdf)]

5. **RAI2: Responsible Identity Audit Governing the Artificial Intelligence**. NDSS 2023. `Model and Data auditing in AI` [[pdf](https://arxiv.org/pdf/2201.11692.pdf)] [[code](https://github.com/chichidd/RAI2)]

6. **ActiveDaemon: Unconscious DNN Dormancy and Waking Up via User-specific Invisible Token**. NDSS 2024. `Protecting DNN models by specific user tokens` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-588-paper.pdf)] [[code](https://github.com/LANCEREN/ActiveDaemon)]

7. **THEMIS: Towards Practical Intellectual Property Protection for Post-Deployment On-Device Deep Learning Models**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-huang-yujin.pdf)]

#### 2.2.4 Model Integrity

1. **PublicCheck: Public Integrity Verification for Services of Run-time Deep Models**. IEEE S&P 2023. `Model verification via crafted query` [[pdf](https://arxiv.org/pdf/2203.10902.pdf)]

### 2.3 LLM Privacy

#### 2.3.1 Prompt Privacy

1. **Prompt Inversion Attack against Collaborative Inference of Large Language Models**. IEEE S&P 2025. `Prompt inversion attack` [[pdf](https://arxiv.org/pdf/2503.09022)]

2. **On the Effectiveness of Prompt Stealing Attacks on In-the-Wild Prompts**. IEEE S&P 2025. `Prompt stealing attack` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a392/26hiTFMb8eQ)]

3. **PRSA: Prompt Stealing Attacks against Real-World Prompt Services**. USENIX Security 2025. `Prompt stealing attack` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-yang-yong.pdf)]

4. **Cross-Modal Prompt Inversion: Unifying Threats to Text and Image Generative AI Models**. USENIX Security 2025. `Prompt inversion attack` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-ye-inversion.pdf)]

5. **Prompt Obfuscation for Large Language Models**. USENIX Security 2025. `Prompt defense` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-pape.pdf)]

#### 2.3.2 Model Privacy

1. **Codebreaker: Dynamic Extraction Attacks on Code Language Models**. IEEE S&P 2025. `Personal Information Extraction in code llm` [[pdf](https://ieeexplore.ieee.org/document/11023359)]

2. **LLMmap: Fingerprinting for Large Language Models**. USENIX Security 2025. `LLM fingerprinting` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-pasquini.pdf)]

3. **Unlocking the Power of Differentially Private Zeroth-order Optimization for Fine-tuning LLMs**. USENIX Security 2025. `LLM DP` [[pdf](https://www.usenix.org/system/files/usenixsecurity25-bao-ergute.pdf)]

4. **Depth Gives a False Sense of Privacy: LLM Internal States Inversion**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-dong-tian.pdf)]

5. **Evaluating LLM-based Personal Information Extraction and Countermeasures**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-liu-yupei.pdf)]

6. **PrivacyXray: Detecting Privacy Breaches in LLMs through Semantic Consistency and Probability Certainty**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-he-jinwen.pdf)]

#### 2.3.3 Data Privacy

1. **Synthetic Artifact Auditing: Tracing LLM-Generated Synthetic Data Usage in Downstream Applications**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-wu-yixin-auditing.pdf)]

2. **Whispering Under the Eaves: Protecting User Privacy Against Commercial and LLM-powered Automatic Speech Recognition Systems**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-jin-weifei.pdf)]

3. **Effective PII Extraction from LLMs through Augmented Few-Shot Learning**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-cheng-shuai.pdf)]

4. **Private Investigator: Extracting Personally Identifiable Information from Large Language Models Using Optimized Prompts**. USENIX Security 2025. [[pdf](https://www.usenix.org/system/files/usenixsecurity25-keum.pdf)]

### 2.4 User Related Privacy

#### 2.4.1 Image

1. **Fawkes: Protecting Privacy against Unauthorized Deep Learning Models**. USENIX Security 2020. `Protect Face Privacy` [[pdf](https://people.cs.uchicago.edu/~ravenben/publications/pdf/fawkes-usenix20.pdf)] [[code](https://github.com/Shawn-Shan/fawkes)]

2. **Automatically Detecting Bystanders in Photos to Reduce Privacy Risks**. IEEE S&P 2020. `Detecting bystanders` [[pdf](http://vision.soic.indiana.edu/papers/bystander2020oakland.pdf)]

3. **Characterizing and Detecting Non-Consensual Photo Sharing on Social Networks**. IEEE S&P 2020. `Detecting Non-Consensual People in a photo` [[pdf](https://dl.acm.org/doi/abs/10.1145/3548606.3560571)]

4. **Fairness Properties of Face Recognition and Obfuscation Systems**. USENIX Security 2023. `Fairness in Face related models` [[pdf](https://www.usenix.org/conference/usenixsecurity23/presentation/rosenberg)] [[code](https://github.com/wi-pi/fairness_face_obfuscation)]

### 2.5 Private ML Protocols

#### 2.5.1 3PC

1. **SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning**. USENIX Security 2021. [[pdf](https://arxiv.org/pdf/2005.10296.pdf)]

2. **BLAZE: Blazing Fast Privacy-Preserving Machine Learning**. NDSS 2020. [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24202-paper.pdf)]

3. **Bicoptor: Two-round Secure Three-party Non-linear Computation without Preprocessing for Privacy-preserving Machine Learning**. IEEE S&P 2023. [[pdf](https://arxiv.org/pdf/2210.01988.pdf)]

3. **Ents: An Efficient Three-party Training Framework for Decision Trees by Communication Optimization**. CCS 2024. [[pdf](https://arxiv.org/pdf/2406.07948)]

#### 2.5.2 4PC

1. **Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning**. NDSS 2020. [[pdf](https://arxiv.org/pdf/1912.02631.pdf)]

#### 2.5.3 SMPC

1. **Cerebro: A Platform for Multi-Party Cryptographic Collaborative Learning**. USENIX Security 2021. [[pdf](https://www.usenix.org/system/files/sec21-zheng.pdf)] [[code](https://github.com/mc2-project/cerebro)]

2. **Private, Efficient, and Accurate: Protecting Models Trained by Multi-party Learning with Differential Privacy**. IEEE S&P 2023. [[pdf](https://arxiv.org/pdf/2208.08662.pdf)]

3. **MPCDiff: Testing and Repairing MPC-Hardened Deep Learning Models**. NDSS 2023. [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-380-paper.pdf)] [[code](https://github.com/Qi-Pang/MPCDiff)]

4. **Pencil: Private and Extensible Collaborative Learning without the Non-Colluding Assumption**. NDSS 2024. [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-512-paper.pdf)] [[code](https://github.com/lightbulb128/Pencil)]

5. **Securely Training Decision Trees Efficiently**. CCS 2024. [[pdf](https://eprint.iacr.org/2024/1077.pdf)]

6. **CoGNN: Towards Secure and Efficient Collaborative Graph Learning**. CCS 2024. [[pdf](https://eprint.iacr.org/2024/987.pdf)]

#### 2.5.4 Cryptographic NN Computation

1. **SoK: Cryptographic Neural-Network Computation**. IEEE S&P 2023. [[pdf](https://sokcryptonn.github.io/)]

2. **From Individual Computation to Allied Optimization: Remodeling Privacy-Preserving Neural Inference with Function Input Tuning**. IEEE S&P 2024. [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a101/1Ub238IknIs)]

3. **BOLT: Privacy-Preserving, Accurate and Efficient Inference for Transformers**. IEEE S&P 2024. [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a130/1Ub23O2X00U)] [[code](https://github.com/Clive2312/BOLT)]

#### 2.5.5 Secure Aggregation

1. **Flamingo: Multi-Round Single-Server Secure Aggregation with Applications to Private Federated Learning**. IEEE S&P 2023. [[pdf](https://sokcryptonn.github.io/)] [[code](https://github.com/eniac/flamingo)]

2. **ELSA: Secure Aggregation for Federated Learning with Malicious Actors**. IEEE S&P 2023. [[pdf](https://eprint.iacr.org/2022/1695.pdf)] [[code](https://github.com/ucbsky/elsa)]

### 2.6 Platform

#### 2.6.1 Inference Attack Measurement

1. **ML-Doctor: Holistic Risk Assessment of Inference Attacks Against Machine Learning Models**. USENIX Security 2022. `Membership inference attack. Model inversion. Attribute inference. Model stealing` [[pdf](https://www.usenix.org/system/files/sec22summer_liu-yugeng.pdf)] 

#### 2.6.2 Survey

1. **SoK: Let the Privacy Games Begin! A Unified Treatment of Data Inference Privacy in Machine Learning**. IEEE S&P 2023. `Systematizing privacy risks using game framework` [[pdf](https://arxiv.org/pdf/2212.10986.pdf)]

### 2.7 Differential Privacy

#### 2.7.1 Tree Model

1. **Federated Boosted Decision Trees with Differential Privacy**. ACM CCS 2022. `Federated Learning with Tree Model in DP` [[pdf](http://dimacs.rutgers.edu/~graham/pubs/papers/dpxgboost.pdf)] 

#### 2.7.2 DP

1. **Spectral-DP: Differentially Private Deep Learning through Spectral Perturbation and Filtering**. IEEE S&P 2023. `Spectral DP` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b944/1NrbZkrFZi8)]

2. **Spectral-DP: Differentially Private Deep Learning through Spectral Perturbation and Filtering**. IEEE S&P 2024. `Spectral DP` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a088/1Ub22UPYcsU)]

3. **Bounded and Unbiased Composite Differential Privacy**. IEEE S&P 2024. `Composite DP` [[pdf](https://arxiv.org/pdf/2311.02324.pdf)] [[code](https://github.com/CompositeDP/CompositeDP)]

4. **Cohere: Managing Differential Privacy in Large Scale Systems**. IEEE S&P 2024. `Unified DP in large system` [[pdf](https://arxiv.org/pdf/2301.08517.pdf)] [[code](https://github.com/pps-lab/cohere)]

5. **You Can Use But Cannot Recognize: Preserving Visual Privacy in Deep Neural Networks**. NDSS 2024. `DP in image recognization` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2024-1361-paper.pdf)] [[code](https://github.com/Edison9419/ndss)]

#### 2.7.3 LDP

1. **Locally Differentially Private Frequency Estimation Based on Convolution Framework**. IEEE S&P 2023. [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600c208/1NrbZx7nFkI)]

2. **Data Poisoning Attacks to Locally Differentially Private Frequent Itemset Mining Protocols**. CCS 2024. [[pdf](https://arxiv.org/pdf/2406.19466)]

### 2.7 LLM Privacy

#### 2.7.1 Prompt Privacy

1. **PLeak: Prompt Leaking Attacks against Large Language Model Applications**. CCS 2024. `Stealing system prompts` [[pdf](https://arxiv.org/pdf/2405.06823)] [[code](https://github.com/BHui97/PLeak)]

## Contributing

This list is mainly maintained by Ping He from [NESA Lab](https://nesa.zju.edu.cn/index.html).

We are very much welcome contributors for contributing this repository!

**Markdown format**
```markdown
**Paper Name**. Conference Year. `Keywords` [[pdf](pdf_link)] [[code](code_link)]
```

## Licenses

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [gnipping](https://github.com/gnipping) holds all copyright and related or neighboring rights to this repository.
