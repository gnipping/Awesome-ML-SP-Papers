# Awesome-ML-Security-and-Privacy-Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of Meachine learning Security & Privacy papers published in security top-4 conferences (IEEE S&P, ACM CCS, USENIX Security and NDSS).

### Contents:

* [1. Security Papers](#1-security-papers)
* [2. Privacy Papers](#2-privacy-papers)
* [Contributing](#contributing)

## 1. Security Papers

### 1.1 Adversarial Attack & Defense

#### 1.1.1 Image

1. **Hybrid Batch Attacks: Finding Black-box Adversarial Examples with Limited Queries**. USENIX Security 2020. `Transferability + Query. Black-box Attack ` [[pdf](https://www.usenix.org/system/files/sec20-suya.pdf)] [[code](https://github.com/suyeecav/Hybrid-Attack)]

1. **Adversarial Preprocessing: Understanding and Preventing Image-Scaling Attacks in Machine Learning**. USENIX Security 2020. `Defense of Image Scaling Attack` [[pdf](https://www.usenix.org/system/files/sec20fall_quiring_prepub.pdf)] [[code](https://scaling-attacks.net/)]

1. **HopSkipJumpAttack: A Query-Efficient Decision-Based Attack**. IEEE S&P 2020. `Query-based Black-box Attack` [[pdf](https://arxiv.org/pdf/1904.02144.pdf)] [[code](https://github.com/Jianbo-Lab/HSJA)]

1. **PatchGuard: A Provably Robust Defense against Adversarial Patches via Small Receptive Fields and Masking**. USENIX Security 2021. `Adversarial Patch Defense` [[pdf](https://www.usenix.org/system/files/sec21fall-xiang.pdf)] [[code](https://github.com/inspire-group/PatchGuard)]

1. **Gotta Catch'Em All: Using Honeypots to Catch Adversarial Attacks on Neural Networks**. ACM CCS 2020. `Build an trap in model to induce specific adversarial perturbation` [[pdf](https://people.cs.uchicago.edu/~ravenben/publications/pdf/trapdoor-ccs20.pdf)] [[code](https://github.com/Shawn-Shan/trapdoor)]

1. **A Tale of Evil Twins: Adversarial Inputs versus Poisoned Models**. ACM CCS 2020. `Perturbate both input and model` [[pdf](https://arxiv.org/pdf/1911.01559.pdf)] [[code](https://github.com/alps-lab/imc)]

1. **Feature-Indistinguishable Attack to Circumvent Trapdoor-Enabled Defense**. ACM CCS 2021. `A new attack method can break TeD defense mechanism` [[pdf](https://dl.acm.org/doi/pdf/10.1145/3460120.3485378)] [[code](https://github.innominds.com/CGCL-codes/FeatureIndistinguishableAttack)]

1. **DetectorGuard: Provably Securing Object Detectors against Localized Patch Hiding Attacks**. ACM CCS 2021. `Provable robustness for patch hiding in object detection` [[pdf](https://arxiv.org/pdf/2102.02956.pdf)] [[code](https://github.com/inspire-group/DetectorGuard)]

1. **RamBoAttack: A Robust and Query Efficient Deep Neural Network Decision Exploit**. NDSS 2022. `Query-based black box attack` [[pdf](https://arxiv.org/pdf/2112.05282.pdf)] [[code](https://github.com/RamBoAttack/RamBoAttack.github.io)]

1. **What You See is Not What the Network Infers: Detecting Adversarial Examples Based on Semantic Contradiction**. NDSS 2022. `Generative-based AE detection` [[pdf](https://arxiv.org/pdf/2201.09650.pdf)] [[code](https://github.com/cure-lab/ContraNet)]

#### 1.1.2 Text

1. **TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation**. USENIX Security 2020. `Defense in preprossing` [[pdf](https://www.usenix.org/system/files/sec20-li-jinfeng.pdf)]

1. **Bad Characters: Imperceptible NLP Attacks**. IEEE S&P 2022. `Use unicode to conduct human imperceptible attack` [[pdf](https://arxiv.org/pdf/2106.09898.pdf)] [[code](https://github.com/nickboucher/imperceptible)]

#### 1.1.3 Audio

1. **WaveGuard: Understanding and Mitigating Audio Adversarial Examples**. USENIX Security 2021. `Defense in preprossing` [[pdf](https://www.usenix.org/system/files/sec21fall-hussain.pdf)] [[code](https://github.com/shehzeen/waveguard_defense)]

2. **Dompteur: Taming Audio Adversarial Examples**. USENIX Security 2021. `Defense in preprossing. Preprocessing the audio to make the noise human noticeable` [[pdf](https://www.usenix.org/system/files/sec21-eisenhofer.pdf)] [[code](https://github.com/RUB-SysSec/dompteur)]

3. **Who is Real Bob? Adversarial Attacks on Speaker Recognition Systems**. IEEE S&P 2021. `Attack` [[pdf](https://arxiv.org/pdf/1911.01840.pdf)] [[code](https://github.com/FAKEBOB-adversarial-attack/FAKEBOB)]

4. **Hear "No Evil", See "Kenansville": Efficient and Transferable Black-Box Attacks on Speech Recognition and Voice Identification Systems**. IEEE S&P 2021. `Black-box Attack` [[pdf](https://arxiv.org/pdf/1910.05262.pdf)]

5. **SoK: The Faults in our ASRs: An Overview of Attacks against Automatic Speech Recognition and Speaker Identification Systems**. IEEE S&P 2021. `Survey` [[pdf](https://arxiv.org/pdf/2007.06622.pdf)]

6. **AdvPulse: Universal, Synchronization-free, and Targeted Audio Adversarial Attacks via Subsecond Perturbations**. ACM CCS 2020. `Attack` [[pdf](http://www.winlab.rutgers.edu/~yychen/papers/li2020advpulse.pdf)]

7. **Black-box Adversarial Attacks on Commercial Speech Platforms with Minimal Information**. ACM CCS 2021. `Black-box Attack. Physical World` [[pdf](https://arxiv.org/pdf/2110.09714.pdf)]

#### 1.1.4 Video

1. **Universal 3-Dimensional Perturbations for Black-Box Attacks on Video Recognition Systems**. IEEE S&P 2022. `Adversarial attack in video recognition` [[pdf](https://arxiv.org/pdf/2107.04284.pdf)]

#### 1.1.5 Graph

1. **A Hard Label Black-box Adversarial Attack Against Graph Neural Networks**. ACM CCS 2021. `Graph Classification` [[pdf](https://arxiv.org/pdf/2108.09513.pdf)]

#### 1.1.6 Software

1. **Intriguing Properties of Adversarial ML Attacks in the Problem Space**. IEEE S&P 2020. `Attack Malware Classification` [[pdf](https://arxiv.org/pdf/1911.02142.pdf)]

2. **Structural Attack against Graph Based Android Malware Detection**. IEEE S&P 2020. `Perturbed function call graph` [[pdf](https://www4.comp.polyu.edu.hk/~csxluo/HRAT.pdf)]

#### 1.1.7 Interpret Method

1. **Interpretable Deep Learning under Fire**. USENIX Security 2020. `Attack both image classification and interpret method` [[pdf](https://www.usenix.org/system/files/sec20spring_zhang_prepub.pdf)]

#### 1.1.8 Physical World

1. **SLAP: Improving Physical Adversarial Examples with Short-Lived Adversarial Perturbations**. USENIX Security 2021. `Projector light causes misclassification` [[pdf](https://www.usenix.org/system/files/sec21fall-lovisotto.pdf)] [[code](https://github.com/ssloxford/short-lived-adversarial-perturbations)]

#### 1.1.9 Reinforcement Learning

1. **Adversarial Policy Training against Deep Reinforcement Learning**. USENIX Security 2021. `Weird behavior to trigger opposite abnormal action. Two-agent competitor game` [[pdf](https://www.usenix.org/system/files/sec21summer_wu-xian.pdf)] [[code](https://github.com/psuwuxian/rl_attack)]

#### 1.1.10 Robustness

1. **Cost-Aware Robust Tree Ensembles for Security Applications**. USENIX Security 2021. `Propose Cost of feature to certify the model robustness` [[pdf](https://www.usenix.org/system/files/sec21-chen-yizheng.pdf)] [[code](https://github.com/surrealyz/growtrees)]

1. **CADE: Detecting and Explaining Concept Drift Samples for Security Applications**. USENIX Security 2021. `Detect Concept shift` [[pdf](https://www.usenix.org/system/files/sec21-yang-limin.pdf)] [[code](https://github.com/whyisyoung/CADE)]

2. **Learning Security Classifiers with Verified Global Robustness Properties**. ACM CCS 2021. `Train a classifier with global robustness` [[pdf](https://arxiv.org/pdf/2105.11363.pdf)] [[code](https://github.com/surrealyz/verified-global-properties)]

3. **On the Robustness of Domain Constraints**. ACM CCS 2021. `Domain constraints. Input space robustness` [[pdf](https://arxiv.org/pdf/2105.08619.pdf)]

4. **Cert-RNN: Towards Certifying the Robustness of Recurrent Neural Networks**. ACM CCS 2021. `Certify robustness in RNN` [[pdf](https://nesa.zju.edu.cn/download/dty_pdf_cert_rnn.pdf)]

5. **TSS: Transformation-Specific Smoothing for Robustness Certification**. ACM CCS 2021. `Certify robustness about transformation` [[pdf](https://arxiv.org/pdf/2002.12398.pdf)][[code](https://github.com/AI-secure/semantic-randomized-smoothing)]

#### 1.1.11 Network Traffic

1. **Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations**. USENIX Security 2021. `Adversarial attack to defeat DNN-based traffic analysis` [[pdf](https://www.usenix.org/system/files/sec21fall-nasr.pdf)][[code](https://github.com/SPIN-UMass/BLANKET)]

#### 1.1.12 Wireless Communication System

1. **Robust Adversarial Attacks Against DNN-Based Wireless Communication Systems**. ACM CCS 2021. `Attack` [[pdf](https://arxiv.org/pdf/2102.00918.pdf)]

### 1.2 Distributed Machine Learning

#### 1.2.1 Federated Learning

1. **Local Model Poisoning Attacks to Byzantine-Robust Federated Learning**. USENIX Security 2020. `Poisoning Attack`

1. **Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses for Federated Learning**. NDSS 2021. `Poisoning Attack`

1. **DeepSight: Mitigating Backdoor Attacks in Federated Learning Through Deep Model Inspection**. NDSS 2022. `Backdoor defense` [[pdf](https://arxiv.org/pdf/2201.00763.pdf)]

#### 1.2.2 Normal Distributed Learning

1. **Justinian's GAAvernor: Robust Distributed Learning with Gradient Aggregation Agent**. USENIX Security 2020. `Defense in Gradient Aggregation. Reinforcement learning`

### 1.3 Data Poisoning

#### 1.3.1 Hijack Embedding

1. **Humpty Dumpty: Controlling Word Meanings via Corpus Poisoning**. IEEE S&P 2020. `Hijack Word Embedding`

#### 1.3.2 Hijack Autocomplete Code

1. **You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion**. USENIX Security 2021. `Hijack Code Autocomplete`

#### 1.3.3 Semi-Supervised Learning

1. **Poisoning the Unlabeled Dataset of Semi-Supervised Learning**. USENIX Security 2021. `Hijack Code Autocomplete`

#### 1.3.4 Recommender Systems

1. **Data Poisoning Attacks to Deep Learning Based Recommender Systems**. NDSS 2021. `The attacker chosen items are recommended as much as possible`

1. **Reverse Attack: Black-box Attacks on Collaborative Recommendation**. ACM CCS 2021. `Black-box setting. Surrogate model. Collaborative Filtering. Demoting and Promoting`

#### 1.3.5 Classification

1. **Subpopulation Data Poisoning Attacks**. ACM CCS 2021. `Poisoning to flip a group of data samples`

1. **Get a Model! Model Hijacking Attack Against Machine Learning Models**. NDSS 2022. `Fusing dataset to hijacking model` [[pdf](https://arxiv.org/pdf/2111.04394.pdf)] [[code](https://github.com/AhmedSalem2/Model-Hijacking)]

### 1.4 Backdoor

#### 1.4.1 Image

1. **Demon in the Variant: Statistical Analysis of DNNs for Robust Backdoor Contamination Detection**. USENIX Security 2021. `Class-specific Backdoor. Defense by decomposition`

1. **Double-Cross Attacks: Subverting Active Learning Systems**. USENIX Security 2021. `Active Learning System. Backdoor Attack`

1. **Detecting AI Trojans Using Meta Neural Analysis**. IEEE S&P 2021. `Meta Neural Classifier`

1. **BadEncoder: Backdoor Attacks to Pre-trained Encoders in Self-Supervised Learning**. IEEE S&P 2022. `Backdoor attack in image-text pretrained model`

1. **Composite Backdoor Attack for Deep Neural Network by Mixing Existing Benign Features**. ACM CCS 2020. `Composite backdoor. Image & text tasks`

1. **AI-Lancet: Locating Error-inducing Neurons to Optimize Neural Networks**. ACM CCS 2021. `Locate neural location and finetuning it`

#### 1.4.2 Text

1. **T-Miner: A Generative Approach to Defend Against Trojan Attacks on DNN-based Text Classification**. USENIX Security 2021. `Backdoor Defense. GAN to recover trigger`

1. **Hidden Backdoors in Human-Centric Language Models**. ACM CCS 2021. `Novel trigger`

1. **Backdoor Pre-trained Models Can Transfer to All**. ACM CCS 2021. `Backdoor in pre-trained to poison the down stream task`

#### 1.4.3 Graph

1. **Graph Backdoor**. USENIX Security 2021. `Classification`

#### 1.4.4 Software

1. **Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers**. USENIX Security 2021. `Explanation Method. Evade Classification`

### 1.5 ML Library Security

#### 1.5.1 Loss

1. **Blind Backdoors in Deep Learning Models**. USENIX Security 2021. `Loss Manipulation. Backdoor`

### 1.6 AI4Security

#### 1.6.1 Cyberbullying

1. **Towards Understanding and Detecting Cyberbullying in Real-world Images**. NDSS 2021. `Detect image cyberbully`

#### 1.6.2 Label Complete

1. **FARE: Enabling Fine-grained Attack Categorization under Low-quality Labeled Data**. NDSS 2021. `Clustering Method to complete the dataset label`

#### 1.6.3 Advertisement detection

1. **WtaGraph: Web Tracking and Advertising Detection using Graph Neural Networks**. IEEE S&P 2022. `GNN`

#### 1.6.4 CAPTCHA

1. **Text Captcha Is Dead? A Large Scale Deployment and Empirical Studys**. ACM CCS 2020. `Adversarial CAPTCHA`

#### 1.6.5 Code embedding

1. **PalmTree: Learning an Assembly Language Model for Instruction Embedding**. ACM CCS 2021. `Pre-trained model to generate code embedding`

#### 1.6.6 Survey

1. **Dos and Don'ts of Machine Learning in Computer Security**. USENIX Security 2022. `Survey pitfalls in ML4Security`

### 1.7 AutoML Security

#### 1.7.1 Security Analysis

1. **On the Security Risks of AutoML**. USENIX Security 2022. `Adversarial evasion. Model poisoning. Backdoor. Functionality stealing. Membership Inference`

### 1.8 Hardware Related Security 

#### 1.8.1 Verification

1. **DeepDyve: Dynamic Verification for Deep Neural Networks**. ACM CCS 2020.

### 1.9 Security Related Interpreting Method

#### 1.9.1 Unsupervised Learning

1. **DeepAID: Interpreting and Improving Deep Learning-based Anomaly Detection in Security Applications**. ACM CCS 2021. `Anomaly detection`

## 2. Privacy Papers

### 2.1 Training Data

#### 2.1.1 Data Recovery

1. **Updates-Leak: Data Set Inference and Reconstruction Attacks in Online Learning**. USENIX Security 2020. `Online Learning. Model updates`

1. **Extracting Training Data from Large Language Models**. USENIX Security 2021. `Membership inference attack. GPT-2`

1. **Analyzing Information Leakage of Updates to Natural Language Models**. ACM CCS 2020. `data leakage in model changes`

1. **TableGAN-MCA: Evaluating Membership Collisions of GAN-Synthesized Tabular Data Releasing**. ACM CCS 2021. `Membership collision in GAN`

1. **DataLens: Scalable Privacy Preserving Training via Gradient Compression and Aggregation**. ACM CCS 2021. `DP to train an privacy preserving GAN`

2. **Property Inference Attacks Against GANs**. NDSS 2022. `Property Inference Attacks Against GAN`  [[pdf](https://yangzhangalmo.github.io/papers/NDSS22-PIAGAN.pdf)] [[code](https://github.com/Zhou-Junhao/PIA_GAN)]

#### 2.1.2 Membership Inference Attack

1. **Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference**. USENIX Security 2020. `White-box Setting`

1. **Systematic Evaluation of Privacy Risks of Machine Learning Models**. USENIX Security 2020. `Metric-based Membership inference Attack Method. Define Privacy Risk Score`

1. **Practical Blind Membership Inference Attack via Differential Comparisons**. NDSS 2021. `Use non-member data to replace shadow model`

1. **GAN-Leaks: A Taxonomy of Membership Inference Attacks against Generative Models**. ACM CCS 2020. `Membership inference attack in Generative model. Member has small reconstruction error`

1. **Quantifying and Mitigating Privacy Risks of Contrastive Learning**. ACM CCS 2021. `Membership inference attack. Property inference attack. Contrastive learning in classification task`

1. **Membership Inference Attacks Against Recommender Systems**. ACM CCS 2021. `Recommender System`

1. **EncoderMI: Membership Inference against Pre-trained Encoders in Contrastive Learning**. ACM CCS 2021. `Contrastive learning in pre-trained model. Data augmentation has higher similarity`

#### 2.1.3 Information Leakage in Distributed ML System

1. **Label Inference Attacks Against Vertical Federated Learning**. USENIX Security 2022. `Label Leakage. Federated Learning`

1. **The Value of Collaboration in Convex Machine Learning with Differential Privacy**. IEEE S&P 2020. `DP as Defense`

1. **Leakage of Dataset Properties in Multi-Party Machine Learning**. USENIX Security 2021. `Dataset Properties Leakage`

1. **Unleashing the Tiger: Inference Attacks on Split Learning**. ACM CCS 2021. `Split learning. Feature-space hijacking attack`

2. **Local and Central Differential Privacy for Robustness and Privacy in Federated Learning**. NDSS 2022. `DP in federated learning` [[pdf](https://arxiv.org/pdf/2009.03561.pdf)]

#### 2.1.4 Information Leakage in Embedding

1. **Privacy Risks of General-Purpose Language Models**. IEEE S&P 2020. `Pretrained Language Model`

1. **Information Leakage in Embedding Models**. ACM CCS 2020. `Exact Word Recovery. Attribute inference. Membership inference`

1. **Honest-but-Curious Nets: Sensitive Attributes of Private Inputs Can Be Secretly Coded into the Classifiers' Outputs**. ACM CCS 2021. `Infer privacy information in classification output`

#### 2.1.5 Graph Leakage

1. **Stealing Links from Graph Neural Networks**. USENIX Security 2021. `Inference Graph Link`

1. **Inference Attacks Against Graph Neural Networks**. USENIX Security 2022. `Property inference: number of nodes. Subgraph inference. Graph reconstruction`

1. **LinkTeller: Recovering Private Edges from Graph Neural Networks via Influence Analysis**. IEEE S&P 2022. `Use node connection influence to infer graph edges`

1. **Locally Private Graph Neural Networks**. IEEE S&P 2022. `LDP as defense for node privacy`

#### 2.1.6 Unlearning

1. **Machine Unlearning**. IEEE S&P 2020. `Shard and isolate the training dataset`

1. **When Machine Unlearning Jeopardizes Privacy**. ACM CCS 2021. `Membership inference attack in unlearning setting`

### 2.2 Model

#### 2.2.1 Model Extraction

1. **Exploring Connections Between Active Learning and Model Extraction**. USENIX Security 2020. `Active Learning`

1. **High Accuracy and High Fidelity Extraction of Neural Networks**. USENIX Security 2020. `Fidelity`

1. **DRMI: A Dataset Reduction Technology based on Mutual Information for Black-box Attacks**. USENIX Security 2021. `Query Data Selection Method to reduce the query`

1. **Entangled Watermarks as a Defense against Model Extraction**. USENIX Security 2021. `Backdoor as watermark against model extraction`

1. **CloudLeak: Large-Scale Deep Learning Models Stealing Through Adversarial Examples**. NDSS 2020. `Adversarial Example to strengthen model stealing`

#### 2.2.2 Watermarking Model Outputs

1. **Adversarial Watermarking Transformer: Towards Tracing Text Provenance with Data Hiding**. IEEE S&P 2021. `Encode secret message into LM`

#### 2.2.3 Model Owenership

1. **Proof-of-Learning: Definitions and Practice**. IEEE S&P 2021. `Proof the ownership of model parameters`

1. **SoK: How Robust is Image Classification Deep Neural Network Watermarking?**. IEEE S&P 2022. `Survey of DNN watermarking`

1. **Copy, Right? A Testing Framework for Copyright Protection of Deep Learning Models**. IEEE S&P 2022. `Calculate model similarity by generating test examples`

### 2.3 User Related Privacy

#### 2.3.1 Image

1. **Fawkes: Protecting Privacy against Unauthorized Deep Learning Models**. USENIX Security 2022. `Protect Face Privacy`

2. **Automatically Detecting Bystanders in Photos to Reduce Privacy Risks**. IEEE S&P 2020. `Detecting bystanders`

### 2.4 MPC ML Protocols

#### 2.4.1 3PC

1. **SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning**. USENIX Security 2021.

1. **BLAZE: Blazing Fast Privacy-Preserving Machine Learning**. NDSS 2020.

#### 2.4.2 4PC

1. **Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning**. NDSS 2020.

#### 2.4.3 SMPC

1. **Cerebro: A Platform for Multi-Party Cryptographic Collaborative Learning**. USENIX Security 2021.

### 2.5 Platform

#### 2.5.1 Inference Attack Measurement

1. **ML-Doctor: Holistic Risk Assessment of Inference Attacks Against Machine Learning Models**. USENIX Security 2022. `Membership inference attack. Model inversion. Attribute inference. Model stealing`

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
