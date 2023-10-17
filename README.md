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
      - [1.3.8 Defense](#138-defense)
    - [1.4 Backdoor](#14-backdoor)
      - [1.4.1 Image](#141-image)
      - [1.4.2 Text](#142-text)
      - [1.4.3 Graph](#143-graph)
      - [1.4.4 Software](#144-software)
      - [1.4.5 Audio](#145-audio)
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
      - [1.9.1 Unsupervised Learning](#191-unsupervised-learning)
    - [1.10 Face Security](#110-face-security)
      - [1.10.1 Deepfake Detection](#1101-deepfake-detection)
      - [1.10.2 Face Impersonation](#1102-face-impersonation)
      - [1.10.3 Face Verification Systems](#1103-face-verification-systems)
    - [1.10 AI Generation Detection](#110-ai-generation-detection)
      - [1.10.1 Text](#1101-text)
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
    - [2.2 Model](#22-model)
      - [2.2.1 Model Extraction](#221-model-extraction)
      - [2.2.2 Model Watermark](#222-model-watermark)
      - [2.2.3 Model Owenership](#223-model-owenership)
      - [2.2.4 Model Integrity](#224-model-integrity)
    - [2.3 User Related Privacy](#23-user-related-privacy)
      - [2.3.1 Image](#231-image)
    - [2.4 Private ML Protocols](#24-private-ml-protocols)
      - [2.4.1 3PC](#241-3pc)
      - [2.4.2 4PC](#242-4pc)
      - [2.4.3 SMPC](#243-smpc)
      - [2.4.4 Cryptographic NN Computation](#244-cryptographic-nn-computation)
      - [2.4.5 Secure Aggregation](#245-secure-aggregation)
    - [2.5 Platform](#25-platform)
      - [2.5.1 Inference Attack Measurement](#251-inference-attack-measurement)
      - [2.5.2 Survey](#252-survey)
    - [2.6 Differential Privacy](#26-differential-privacy)
      - [2.6.1 Tree Model](#261-tree-model)
      - [2.6.2 DP](#262-dp)
      - [2.6.3 LDP](#263-ldp)
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

#### 1.1.2 Text

1. **TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation**. USENIX Security 2020. `Defense in preprossing` [[pdf](https://www.usenix.org/system/files/sec20-li-jinfeng.pdf)]

2. **Bad Characters: Imperceptible NLP Attacks**. IEEE S&P 2022. `Use unicode to conduct human imperceptible attack` [[pdf](https://arxiv.org/pdf/2106.09898.pdf)] [[code](https://github.com/nickboucher/imperceptible)]

3. **Order-Disorder: Imitation Adversarial Attacks for Black-box Neural Ranking Models**. ACM CCS 2022. `Attack Neural Ranking Models` [[pdf](https://arxiv.org/pdf/2209.06506.pdf)]

4. **No more Reviewer #2: Subverting Automatic Paper-Reviewer Assignment using Adversarial Learning**. USENIX Security 2023. `Adversarial Attack on Paper Assignment` [[pdf](https://arxiv.org/pdf/2303.14443.pdf)]

#### 1.1.3 Audio

1. **WaveGuard: Understanding and Mitigating Audio Adversarial Examples**. USENIX Security 2021. `Defense in preprossing` [[pdf](https://www.usenix.org/system/files/sec21fall-hussain.pdf)] [[code](https://github.com/shehzeen/waveguard_defense)]

2. **Dompteur: Taming Audio Adversarial Examples**. USENIX Security 2021. `Defense in preprossing. Preprocessing the audio to make the noise human noticeable` [[pdf](https://www.usenix.org/system/files/sec21-eisenhofer.pdf)] [[code](https://github.com/RUB-SysSec/dompteur)]

3. **Who is Real Bob? Adversarial Attacks on Speaker Recognition Systems**. IEEE S&P 2021. `Attack` [[pdf](https://arxiv.org/pdf/1911.01840.pdf)] [[code](https://github.com/FAKEBOB-adversarial-attack/FAKEBOB)]

4. **Hear "No Evil", See "Kenansville": Efficient and Transferable Black-Box Attacks on Speech Recognition and Voice Identification Systems**. IEEE S&P 2021. `Black-box Attack` [[pdf](https://arxiv.org/pdf/1910.05262.pdf)]

5. **SoK: The Faults in our ASRs: An Overview of Attacks against Automatic Speech Recognition and Speaker Identification Systems**. IEEE S&P 2021. `Survey` [[pdf](https://arxiv.org/pdf/2007.06622.pdf)]

6. **AdvPulse: Universal, Synchronization-free, and Targeted Audio Adversarial Attacks via Subsecond Perturbations**. ACM CCS 2020. `Attack` [[pdf](http://www.winlab.rutgers.edu/~yychen/papers/li2020advpulse.pdf)]

7. **Black-box Adversarial Attacks on Commercial Speech Platforms with Minimal Information**. ACM CCS 2021. `Black-box Attack. Physical World` [[pdf](https://arxiv.org/pdf/2110.09714.pdf)]

8. **Perception-Aware Attack: Creating Adversarial Music via Reverse-Engineering Human Perception**. ACM CCS 2022. `Adversarial Audio with human-aware noise` [[pdf](https://arxiv.org/pdf/2207.13192.pdf)]

9. **SpecPatch: Human-in-the-Loop Adversarial Audio Spectrogram Patch Attack on Speech Recognition**. ACM CCS 2022. `Adversarial Patch for audio` [[pdf](https://cse.msu.edu/~qyan/paper/SpecPatch_CCS22.pdf)]

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

#### 1.1.7 Hardware

1. **ATTRITION: Attacking Static Hardware Trojan Detection Techniques Using Reinforcement Learning**. ACM CCS 2022. `Attack Hardware Trojan Detection` [[pdf](https://arxiv.org/pdf/2208.12897.pdf)]

#### 1.1.8 Interpret Method

1. **Interpretable Deep Learning under Fire**. USENIX Security 2020. `Attack both image classification and interpret method` [[pdf](https://www.usenix.org/system/files/sec20spring_zhang_prepub.pdf)]

2. **“Is your explanation stable?”: A Robustness Evaluation Framework for Feature Attribution**. ACM CCS 2022. `Hypothesis Testing to increasing the robustness of explaination methods` [[pdf](https://arxiv.org/pdf/2209.01782.pdf)]

3. **AIRS: Explanation for Deep Reinforcement Learning based Security Applications**. USENIX Security 2023. `DRL Interpertation Method to pinpoint the most influence step` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-36-yu-jiahao.pdf)] [[code](https://github.com/sherdencooper/AIRS)]

#### 1.1.9 Physical World

1. **SLAP: Improving Physical Adversarial Examples with Short-Lived Adversarial Perturbations**. USENIX Security 2021. `Projector light causes misclassification` [[pdf](https://www.usenix.org/system/files/sec21fall-lovisotto.pdf)] [[code](https://github.com/ssloxford/short-lived-adversarial-perturbations)]

2. **Understanding Real-world Threats to Deep Learning Models in Android Apps**. ACM CCS 2022. `Adversarial Attack in real-world models` [[pdf](https://arxiv.org/pdf/2209.09577.pdf)]

3. **X-Adv: Physical Adversarial Object Attacks against X-ray Prohibited Item Detection**. USENIX Security 2023. `Adversarial Attack on X-ray Images` [[pdf](https://arxiv.org/pdf/2302.09491.pdf)] [[code](https://github.com/DIG-Beihang/X-adv)]

4. **That Person Moves Like A Car: Misclassification Attack Detection for Autonomous Systems Using Spatiotemporal Consistency**. USENIX Security 2023. `Robust OD in Autonomous System using spatiotemporal information` [[pdf](https://www.usenix.org/system/files/sec23summer_278-man-prepub.pdf)]

5. **You Can't See Me: Physical Removal Attacks on LiDAR-based Autonomous Vehicles Driving Frameworks**. USENIX Security 2023. `Adversarial attack against Autonomous Vehicles using Laser` [[pdf](https://www.usenix.org/system/files/sec23summer_349-cao-prepub.pdf)] [demo](https://cpseclab.github.io/youcantseeme/)]

6. **CAPatch: Physical Adversarial Patch against Image Captioning Systems**. USENIX Security 2023. `Physical Adversarial Patch against the image caption system` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-121-zhang-shibo.pdf)] [[code](https://github.com/USSLab/CAPatch)]

7. **Exorcising "Wraith": Protecting LiDAR-based Object Detector in Automated Driving System from Appearing Attacks**. USENIX Security 2023. `Defend the appearing attack in autonomous system using local objectness predictor` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-190-xiao-qifan.pdf)] [[code](https://github.com/USSLab/CAPatch)]

#### 1.1.10 Reinforcement Learning

1. **Adversarial Policy Training against Deep Reinforcement Learning**. USENIX Security 2021. `Weird behavior to trigger opposite abnormal action. Two-agent competitor game` [[pdf](https://www.usenix.org/system/files/sec21summer_wu-xian.pdf)] [[code](https://github.com/psuwuxian/rl_attack)]

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

#### 1.1.12 Network Traffic

1. **Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations**. USENIX Security 2021. `Adversarial attack to defeat DNN-based traffic analysis` [[pdf](https://www.usenix.org/system/files/sec21fall-nasr.pdf)] [[code](https://github.com/SPIN-UMass/BLANKET)]

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



#### 1.2.2 Normal Distributed Learning

1. **Justinian's GAAvernor: Robust Distributed Learning with Gradient Aggregation Agent**. USENIX Security 2020. `Defense in Gradient Aggregation. Reinforcement learning` [[pdf](https://www.usenix.org/system/files/sec20-pan.pdf)]

### 1.3 Data Poisoning

#### 1.3.1 Hijack Embedding

1. **Humpty Dumpty: Controlling Word Meanings via Corpus Poisoning**. IEEE S&P 2020. `Hijack Word Embedding` [[pdf](https://www.cs.cornell.edu/~shmat/shmat_oak20.pdf)]

#### 1.3.2 Hijack Autocomplete Code

1. **You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion**. USENIX Security 2021. `Hijack Code Autocomplete` [[pdf](https://www.usenix.org/system/files/sec21-schuster.pdf)]

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

#### 1.3.7 Privacy

1. **Truth Serum: Poisoning Machine Learning Models to Reveal Their Secrets**. ACM CCS 2022. `Poison attack to reveal sensitive information` [[pdf](https://arxiv.org/pdf/2204.00032.pdf)]


#### 1.3.8 Defense

1. **Poison Forensics: Traceback of Data Poisoning Attacks in Neural Networks**. USENIX Security 2022. `Identify poisioned subset by clustering and purning benign set` [[pdf](https://www.usenix.org/system/files/sec22-shan.pdf)]

2. **Meta-Sift: How to Sift Out a Clean Subset in the Presence of Data Poisoning?**. USENIX Security 2023. `Obtain a clean subset from the poisoned set` [[pdf](https://arxiv.org/pdf/2210.06516.pdf)] [[code](https://github.com/ruoxi-jia-group/Meta-Sift)]

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

#### 1.4.2 Text

1. **T-Miner: A Generative Approach to Defend Against Trojan Attacks on DNN-based Text Classification**. USENIX Security 2021. `Backdoor Defense. GAN to recover trigger` [[pdf](https://www.usenix.org/system/files/sec21fall-azizi.pdf)] [[code](https://github.com/reza321/T-Miner)]

1. **Hidden Backdoors in Human-Centric Language Models**. ACM CCS 2021. `Novel trigger` [[pdf](https://arxiv.org/pdf/2105.00164.pdf)] [[code](https://github.com/lishaofeng/NLP_Backdoor)]

1. **Backdoor Pre-trained Models Can Transfer to All**. ACM CCS 2021. `Backdoor in pre-trained to poison the down stream task` [[pdf](https://arxiv.org/pdf/2111.00197.pdf)] [[code](https://github.com/lishaofeng/NLP_Backdoor)]

2. **Hidden Trigger Backdoor Attack on NLP Models via Linguistic Style Manipulation**. USENIX Security 2022. `Backdoor via linguistic style manipulation` [[pdf](https://www.usenix.org/system/files/sec22-pan-hidden.pdf)]

#### 1.4.3 Graph

1. **Graph Backdoor**. USENIX Security 2021. `Classification` [[pdf](https://arxiv.org/pdf/2006.11890.pdf)] [[code](https://github.com/HarrialX/GraphBackdoor)]

#### 1.4.4 Software

1. **Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers**. USENIX Security 2021. `Explanation Method. Evade Classification` [[pdf](https://www.usenix.org/system/files/sec21fall-severi.pdf)] [[code](https://github.com/ClonedOne/MalwareBackdoors)]

#### 1.4.5 Audio

1. **TrojanModel: A Practical Trojan Attack against Automatic Speech Recognition Systems**. IEEE S&P 2023. `Backdoor attack in speech recognition systems` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a906/1Js0DtfUrKw)]

2. **MagBackdoor: Beware of Your Loudspeaker as Backdoor of Magnetic Attack for Malicious Command Injection**. IEEE S&P 2023. `Backdoor attack in audio using magentic trigget` [[pdf](https://huskyachao.github.io/publication/magbackdoor-oakland23/)]

### 1.5 ML Library Security

#### 1.5.1 Loss

1. **Blind Backdoors in Deep Learning Models**. USENIX Security 2021. `Loss Manipulation. Backdoor` [[pdf](https://www.cs.cornell.edu/~shmat/shmat_usenix21blind.pdf)] [[code](https://github.com/ebagdasa/backdoors101)]

2. **IvySyn: Automated Vulnerability Discovery in Deep Learning Frameworks**. USENIX Security 2023. `Automatic Bug Discovery in ML libraries` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-125-christou.pdf)]

### 1.6 AI4Security

#### 1.6.1 Cyberbullying

1. **Towards Understanding and Detecting Cyberbullying in Real-world Images**. NDSS 2021. `Detect image cyberbully` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_7C-4_24260_paper.pdf)]

#### 1.6.2 Security Applications

1. **FARE: Enabling Fine-grained Attack Categorization under Low-quality Labeled Data**. NDSS 2021. `Clustering Method to complete the dataset label` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_5C-4_24403_paper.pdf)] [[code](https://github.com/junjieliang672/FARE)]

2. **From Grim Reality to Practical Solution: Malware Classification in Real-World Noise**. IEEE S&P 2023. `Noise Learning method for malware detection` [[pdf](https://henrygwb.github.io/publications/sp23.pdf)] [[code](https://github.com/gnipping/morse)]

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

#### 1.9.1 Unsupervised Learning

1. **DeepAID: Interpreting and Improving Deep Learning-based Anomaly Detection in Security Applications**. ACM CCS 2021. `Anomaly detection`  [[pdf](https://arxiv.org/pdf/2109.11495.pdf)] [[code](https://github.com/dongtsi/DeepAID)]

### 1.10 Face Security

#### 1.10.1 Deepfake Detection

1. **Who Are You (I Really Wanna Know)? Detecting Audio DeepFakes Through Vocal Tract Reconstruction**. USENIX Security 2022. `deepfake detection using vocal tract reconstruction`  [[pdf](https://www.usenix.org/system/files/sec22fall_blue.pdf)]

#### 1.10.2 Face Impersonation

1. **ImU: Physical Impersonating Attack for Face Recognition System with Natural Style Changes**. IEEE S&P 2023. `StyleGAN to impersonate persion`  [[pdf](https://kaiyuanzhang.com/publications/SP23_ImU.pdf)] [[code](https://github.com/njuaplusplus/imu)]

2. **DepthFake: Spoofing 3D Face Authentication with a 2D Photo**. IEEE S&P 2023. `Adversarial image to attack 3D photos`  [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b710/1Js0EgNcf8A)] [[demo](https://sites.google.com/view/depthfake)]

#### 1.10.3 Face Verification Systems

1. **Understanding the (In)Security of Cross-side Face Verification Systems in Mobile Apps: A System Perspective**. IEEE S&P 2023. `Measurement study of the security risks of cross-side face verification systems.`  [[pdf](https://yinzhicao.org/xfvschecker/XFVSChecker.pdf)]

### 1.10 AI Generation Detection

#### 1.10.1 Text

1. **Deepfake Text Detection: Limitations and Opportunities**. IEEE S&P 2023. `Detecting the machine generated text`  [[pdf](https://arxiv.org/pdf/2210.09421.pdf)] [[code](https://github.com/jmpu/DeepfakeTextDetection)]


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

#### 2.1.6 Unlearning

1. **Machine Unlearning**. IEEE S&P 2020. `Shard and isolate the training dataset` [[pdf](https://arxiv.org/pdf/1912.03817.pdf)] [[code](https://github.com/cleverhans-lab/machine-unlearning)]

2. **When Machine Unlearning Jeopardizes Privacy**. ACM CCS 2021. `Membership inference attack in unlearning setting` [[pdf](https://arxiv.org/pdf/2005.02205.pdf)] [[code](https://github.com/MinChen00/UnlearningLeaks)]

3. **Graph Unlearning**. ACM CCS 2022. `Graph Unlearning` [[pdf](https://arxiv.org/pdf/2103.14991.pdf)] [[code](https://github.com/MinChen00/Graph-Unlearning)]

4. **On the Necessity of Auditable Algorithmic Definitions for Machine Unlearning**. ACM CCS 2022. `Auditable Unlearning` [[pdf](https://www.usenix.org/system/files/sec22fall_thudi.pdf)]

5. **Machine Unlearning of Features and Labels**. NDSS 2023. `Influence Function to achieve unlearning` [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s87_paper.pdf)] [[code](https://github.com/alewarne/MachineUnlearning)]


#### 2.1.7 Attribute Inference Attack

1. **Are Attribute Inference Attacks Just Imputation?**. ACM CCS 2022. `Attribute Inference Attack by identified neuro with data` [[pdf](https://arxiv.org/pdf/2209.01292.pdf)] [[code](https://github.com/bargavj/EvaluatingDPML)]

2. **Feature Inference Attack on Shapley Values**. ACM CCS 2022. `Attribute Inference Attack using shapley values` [[pdf](https://dl.acm.org/doi/abs/10.1145/3548606.3560573)]

3. **QuerySnout: Automating the Discovery of Attribute Inference Attacks against Query-Based Systems**. ACM CCS 2022. `Attribute Inference detection` [[pdf](https://arxiv.org/pdf/2211.05249.pdf)]

#### 2.1.7 Property Inference Attack

1. **SNAP: Efficient Extraction of Private Properties with Poisoning**. IEEE S&P 2023. `Stronger Property Inference Attack by poisoning the data` [[pdf](https://arxiv.org/pdf/2208.12348.pdf)] [[code](https://github.com/johnmath/snap-sp23)]

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

#### 2.2.2 Model Watermark

1. **Adversarial Watermarking Transformer: Towards Tracing Text Provenance with Data Hiding**. IEEE S&P 2021. `Encode secret message into LM` [[pdf](https://arxiv.org/pdf/2009.03015.pdf)]

2. **Rethinking White-Box Watermarks on Deep Learning Models under Neural Structural Obfuscation**. USENIX Security 2023. `Inject dummy neurons into the model to break the white-box model watermark` [[pdf](https://www.usenix.org/system/files/sec23fall-prepub-444-yan-yifan.pdf)]

#### 2.2.3 Model Owenership

1. **Proof-of-Learning: Definitions and Practice**. IEEE S&P 2021. `Proof the ownership of model parameters` [[pdf](https://arxiv.org/pdf/2103.05633.pdf)]

2. **SoK: How Robust is Image Classification Deep Neural Network Watermarking?**. IEEE S&P 2022. `Survey of DNN watermarking` [[pdf](https://arxiv.org/pdf/2108.04974.pdf)]

3. **Copy, Right? A Testing Framework for Copyright Protection of Deep Learning Models**. IEEE S&P 2022. `Calculate model similarity by generating test examples` [[pdf](https://nesa.zju.edu.cn/download/cjl_pdf_sp22.pdf)] [[code](https://github.com/Testing4AI/DeepJudge)]

4. **SSLGuard: A Watermarking Scheme for Self-supervised Learning Pre-trained Encoders**. ACM CCS 2022. `Watermarking in encoder` [[pdf](https://arxiv.org/pdf/2201.11692.pdf)]

5. **RAI2: Responsible Identity Audit Governing the Artificial Intelligence**. NDSS 2023. `Model and Data auditing in AI` [[pdf](https://arxiv.org/pdf/2201.11692.pdf)] [[code](https://github.com/chichidd/RAI2)]

#### 2.2.4 Model Integrity

1. **PublicCheck: Public Integrity Verification for Services of Run-time Deep Models**. IEEE S&P 2023. `Model verification via crafted query` [[pdf](https://arxiv.org/pdf/2203.10902.pdf)]

### 2.3 User Related Privacy

#### 2.3.1 Image

1. **Fawkes: Protecting Privacy against Unauthorized Deep Learning Models**. USENIX Security 2020. `Protect Face Privacy` [[pdf](https://people.cs.uchicago.edu/~ravenben/publications/pdf/fawkes-usenix20.pdf)] [[code](https://github.com/Shawn-Shan/fawkes)]

2. **Automatically Detecting Bystanders in Photos to Reduce Privacy Risks**. IEEE S&P 2020. `Detecting bystanders` [[pdf](http://vision.soic.indiana.edu/papers/bystander2020oakland.pdf)]

3. **Characterizing and Detecting Non-Consensual Photo Sharing on Social Networks**. IEEE S&P 2020. `Detecting Non-Consensual People in a photo` [[pdf](https://dl.acm.org/doi/abs/10.1145/3548606.3560571)]

4. **Fairness Properties of Face Recognition and Obfuscation Systems**. USENIX Security 2023. `Fairness in Face related models` [[pdf](https://www.usenix.org/conference/usenixsecurity23/presentation/rosenberg)] [[code](https://github.com/wi-pi/fairness_face_obfuscation)]

### 2.4 Private ML Protocols

#### 2.4.1 3PC

1. **SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning**. USENIX Security 2021. [[pdf](https://arxiv.org/pdf/2005.10296.pdf)]

2. **BLAZE: Blazing Fast Privacy-Preserving Machine Learning**. NDSS 2020. [[pdf](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24202-paper.pdf)]

3. **Bicoptor: Two-round Secure Three-party Non-linear Computation without Preprocessing for Privacy-preserving Machine Learning**. IEEE S&P 2023. [[pdf](https://arxiv.org/pdf/2210.01988.pdf)]

#### 2.4.2 4PC

1. **Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning**. NDSS 2020. [[pdf](https://arxiv.org/pdf/1912.02631.pdf)]

#### 2.4.3 SMPC

1. **Cerebro: A Platform for Multi-Party Cryptographic Collaborative Learning**. USENIX Security 2021. [[pdf](https://www.usenix.org/system/files/sec21-zheng.pdf)] [[code](https://github.com/mc2-project/cerebro)]

2. **Private, Efficient, and Accurate: Protecting Models Trained by Multi-party Learning with Differential Privacy**. IEEE S&P 2023. [[pdf](https://arxiv.org/pdf/2208.08662.pdf)] 

#### 2.4.4 Cryptographic NN Computation

1. **SoK: Cryptographic Neural-Network Computation**. IEEE S&P 2023. [[pdf](https://sokcryptonn.github.io/)]

#### 2.4.5 Secure Aggregation

1. **Flamingo: Multi-Round Single-Server Secure Aggregation with Applications to Private Federated Learning**. IEEE S&P 2023. [[pdf](https://sokcryptonn.github.io/)] [[code](https://github.com/eniac/flamingo)]

2. **ELSA: Secure Aggregation for Federated Learning with Malicious Actors**. IEEE S&P 2023. [[pdf](https://eprint.iacr.org/2022/1695.pdf)] [[code](https://github.com/ucbsky/elsa)]

### 2.5 Platform

#### 2.5.1 Inference Attack Measurement

1. **ML-Doctor: Holistic Risk Assessment of Inference Attacks Against Machine Learning Models**. USENIX Security 2022. `Membership inference attack. Model inversion. Attribute inference. Model stealing` [[pdf](https://www.usenix.org/system/files/sec22summer_liu-yugeng.pdf)] 

#### 2.5.2 Survey

1. **SoK: Let the Privacy Games Begin! A Unified Treatment of Data Inference Privacy in Machine Learning**. IEEE S&P 2023. `Systematizing privacy risks using game framework` [[pdf](https://arxiv.org/pdf/2212.10986.pdf)]

### 2.6 Differential Privacy

#### 2.6.1 Tree Model

1. **Federated Boosted Decision Trees with Differential Privacy**. ACM CCS 2022. `Federated Learning with Tree Model in DP` [[pdf](http://dimacs.rutgers.edu/~graham/pubs/papers/dpxgboost.pdf)] 

#### 2.6.2 DP

1. **Spectral-DP: Differentially Private Deep Learning through Spectral Perturbation and Filtering**. IEEE S&P 2023. `Spectral DP` [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b944/1NrbZkrFZi8)] 

#### 2.6.3 LDP

1. **Locally Differentially Private Frequency Estimation Based on Convolution Framework**. IEEE S&P 2023. [[pdf](https://www.computer.org/csdl/proceedings-article/sp/2023/933600c208/1NrbZx7nFkI)]

## Contributing

This list is mainly maintained by Ping He from [NESA Lab](https://nesa.zju.edu.cn/index.html).

We are very much welcome contributors for contributing this repository!

**Markdown format**
```markdown
**Paper Name**. Conference Year. `Keywords` [[pdf](pdf_link)] [[code](code_link)]
```

## Licenses

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [gnipping](https://github.com/gnipping) all copyright and related or neighboring rights to this repository.
