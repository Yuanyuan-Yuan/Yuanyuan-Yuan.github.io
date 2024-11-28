---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher in the [Advanced Software Technologies (AST) lab](https://ast.ethz.ch/) at ETH Zurich, mentored by Prof. [Zhendong Su](https://people.inf.ethz.ch/suz/). 
I obtained my Ph.D. in Computer Science and Engineering from The Hong Kong University of Science and Technology (HKUST) in 2024 under the supervision of Prof. [Shuai Wang](https://www.cse.ust.hk/~shuaiw/).
Prior to that, I received my B.S. in Computer Science from Fudan University in 2020.

*E-mail: yuanyuan.yuan [at] inf.ethz.ch*

### Research Interests

My research focuses on the ***safety*** (i.e., addressing *unintentional* defects and ensuring reliable behaviors) and ***security*** (i.e., uncovering and mitigating *intentional* attacks and privacy breaches) of ***AI systems***. My long-term goal is to strengthen AI systems' safety and security across a range of conventional and emerging scenarios. Over the past several years, I have been pursuing this goal primarily from ***software*** and ***hardware*** perspectives.

From the software perspective, I employ software ***testing*** and ***verification***, two fundamental and complementary techniques, to enhance the safety of AI systems. My research has redefined the entire testing framework for AI systems, including the testing input generation [[TSE 24](https://ieeexplore.ieee.org/document/10462634)], testing objectives [[ICSE 23a](https://dl.acm.org/doi/pdf/10.1109/ICSE48619.2023.00107), [ICSE 23b](https://dl.acm.org/doi/pdf/10.1109/ICSE48619.2023.00153)], testing oracles [[ASE 22](https://dl.acm.org/doi/abs/10.1145/3551349.3561157), [CVPR 21](https://openaccess.thecvf.com/content/CVPR2021/html/Yuan_Perception_Matters_Detecting_Perception_Failures_of_VQA_Models_Using_Metamorphic_CVPR_2021_paper.html)], and the follow-up repairing [[ISSTA 24](https://dl.acm.org/doi/abs/10.1145/3650212.3680385)]. It has also bridged different verification techniques to real-world applications of AI systems [[USENIX Security 23b](https://www.usenix.org/conference/usenixsecurity23/presentation/yuan-yuanyuan-certification)].


From the hardware perspective, I analyze hardware activities in AI systems to uncover new attack vectors. Specifically, my research has revealed different hardware side channels that compromise ***data privacy***, such as input leakages to malicious users [[USENIX Security 22](https://www.usenix.org/conference/usenixsecurity22/presentation/yuan), [ICLR 21](https://openreview.net/forum?id=y06VOYLcQXa)], input and AI model leakages to untrusted hosts in TEE-protected AI systems [[IEEE S&P 25](https://yuanyuan-yuan.github.io/files/sp25-Cipher-Steal.pdf), [CCS 24](https://yuanyuan-yuan.github.io/files/ccs24-HyperTheft.pdf)]. It has also identified pervasive and stealthy hardware ***fault injections*** that manipulate AI system's outputs [[NDSS 25a](https://yuanyuan-yuan.github.io/files/ndss25-exe-BFA.pdf)]. To defend against these attacks, my research has proposed universal detections for the leakages [[USENIX Security 23a](https://www.usenix.org/conference/usenixsecurity23/presentation/yuanyuanyuan)] and injections [[NDSS 25b](), [NDSS 23](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f103_paper.pdf)].

## Education & Experience

- **Postdoctoral Researcher**. [AST lab](https://ast.ethz.ch/), ETH Zurich. *Oct. 2024 - present*.

- **Ph.D. in Computer Science and Engineering**. HKUST. *Sep. 2020 - Sep. 2024*.  
🎓 **Thesis:** [Side Channel Analysis for AI Infrastructures](https://yuanyuan-yuan.github.io/files/phd-thesis.pdf)  
🏆 **Best PhD Dissertation Award 2024** (one awardee per year), CSE, HKUST

- **Visiting Researcher**. [AST lab](https://ast.ethz.ch/), ETH Zurich. *Sep. 2022 - Sep. 2023*.

- **B.S. in Computer Science**. Fudan University. *Sep. 2016 - July 2020*.

## Selected Publications ([full list](https://yuanyuan-yuan.github.io/publications/))

*$^\dagger$ indicates corresponding authors, i.e., first-author works of junior students I mentored.*

- [**IEEE S&P 25**] <u>CipherSteal: Stealing Input Data from TEE-Shielded Neural Networks with Ciphertext Side Channels</u>.  
**Yuanyuan Yuan**, Zhibo Liu, Sen Deng, Yanzuo Chen, Shuai Wang, Yinqian Zhang, and Zhendong Su.  
In *46th IEEE Symposium on Security and Privacy*, 2025.   
[[preprint]](https://yuanyuan-yuan.github.io/files/sp25-Cipher-Steal.pdf)

- [**CCS 24**] <u>HyperTheft: Thieving Model Weights from TEE-Shielded Neural Networks via Ciphertext Side Channels</u>.  
**Yuanyuan Yuan**, Zhibo Liu, Sen Deng, Yanzuo Chen, Shuai Wang, Yinqian Zhang, and Zhendong Su.  
In *31st ACM Conference on Computer and Communications Security*, 2024.  
[[preprint]](https://yuanyuan-yuan.github.io/files/ccs24-HyperTheft.pdf)

- [**ISSTA 24**] [See the Forest, not Trees: Unveiling and Escaping the Pitfalls of Error-Triggering Inputs in Neural Network Testing](https://dl.acm.org/doi/abs/10.1145/3650212.3680385).  
**Yuanyuan Yuan**, Shuai Wang, and Zhendong Su.  
In *33rd International Symposium on Software Testing and Analysis*, 2024.  
[[preprint]](https://yuanyuan-yuan.github.io/files/issta24-EP.pdf)

- [**TSE 24**] [Provably Valid and Diverse Mutations of Real-World Media Data for DNN Testing](https://ieeexplore.ieee.org/document/10462634).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *IEEE Transactions on Software Engineering*, 2024.  
[[preprint]](https://arxiv.org/abs/2112.01956)

- [**USENIX Security 23b**] [Precise and Generalized Robustness Certification for Neural Networks](https://www.usenix.org/conference/usenixsecurity23/presentation/yuan-yuanyuan-certification).  
**Yuanyuan Yuan**, Shuai Wang, and Zhendong Su.  
In *32nd USENIX Security Symposium*, 2023.  
[[extended version]](https://arxiv.org/pdf/2306.06747.pdf), [[code]](https://github.com/Yuanyuan-Yuan/GCert)

- [**USENIX Security 23a**] [CacheQL: Quantifying and Localizing Cache Side-Channel Vulnerabilities in Production Software](https://www.usenix.org/conference/usenixsecurity23/presentation/yuanyuanyuan).  
**Yuanyuan Yuan**, Zhibo Liu, and Shuai Wang.  
In *32nd USENIX Security Symposium*, 2023.  
[[extended version]](https://arxiv.org/pdf/2209.14952.pdf), [[findings]](https://sites.google.com/view/cache-ql#h.pgsarsaxsdsv), [[code]](https://github.com/Yuanyuan-Yuan/CacheQL)

- [**ICSE 23a**] [Revisiting Neuron Coverage for DNN Testing: A Layer-Wise and Distribution-Aware Criterion](https://dl.acm.org/doi/pdf/10.1109/ICSE48619.2023.00107).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *45th IEEE/ACM International Conference on Software Engineering*, 2023.  
[[extended version]](https://arxiv.org/abs/2112.01955), [[code]](https://github.com/Yuanyuan-Yuan/NeuraL-Coverage) <a href="https://github.com/Yuanyuan-Yuan/NeuraL-Coverage" target="_blank"><img src="https://img.shields.io/github/stars/Yuanyuan-Yuan/NeuraL-Coverage.svg?style=social&label=Star&maxAge=180"></a>

- [**ASE 22**] [Unveiling Hidden DNN Defects with Decision-Based Metamorphic Testing](https://dl.acm.org/doi/abs/10.1145/3551349.3561157).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *37th IEEE/ACM International Conference on Automated Software Engineering*, 2022.  
[[extended version]](https://arxiv.org/pdf/2210.04942.pdf), [[code]](https://github.com/Yuanyuan-Yuan/Decision-Oracle)

- [**USENIX Security 22**] [Automated Side Channel Analysis of Media Software with Manifold Learning](https://www.usenix.org/conference/usenixsecurity22/presentation/yuan).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *31st USENIX Security Symposium*, 2022.  
🏅 **Artifact Evaluation Badges**: Available; Functional; Reproduced.    
[[extended version]](https://arxiv.org/pdf/2112.04947.pdf), [[code]](https://github.com/Yuanyuan-Yuan/Manifold-SCA) <a href="https://github.com/Yuanyuan-Yuan/Manifold-SCA" target="_blank"><img src="https://img.shields.io/github/stars/Yuanyuan-Yuan/Manifold-SCA.svg?style=social&label=Star&maxAge=180"></a>

- [**CVPR 21**] [Perception Matters: Detecting Perception Failures of VQA Models Using Metamorphic Testing](https://openaccess.thecvf.com/content/CVPR2021/html/Yuan_Perception_Matters_Detecting_Perception_Failures_of_VQA_Models_Using_Metamorphic_CVPR_2021_paper.html).  
**Yuanyuan Yuan**, Shuai Wang, Mingyue Jiang, and Tsong Yueh Chen.  
In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2021.  
[[code]](https://github.com/MetaVQA/MetaVQA)

- [**ICLR 21**] [Private Image Reconstruction from System Side Channels Using Generative Models](https://openreview.net/forum?id=y06VOYLcQXa).  
**Yuanyuan Yuan**, Shuai Wang, and Junping Zhang.  
In *International Conference on Learning Representations*, 2021.  
[[code]](https://github.com/genSCA/genSCA)

- [**NDSS 25b**] <u>BitShield: Defending Against Bit-Flip Attacks on DNN Executables</u>.  
Yanzuo Chen, **Yuanyuan Yuan**$^\dagger$, Zhibo Liu, Sihang Hu, Tianxiang Li, and Shuai Wang$^\dagger$.  
In *32nd Network and Distributed System Security Symposium*, 2025.  
$^\dagger$ Corresponding authors.  

- [**NDSS 25a**] <u>Compiled Models, Built-In Exploits: Uncovering Pervasive Bit-Flip Attack Surfaces in DNN Executables</u>.  
Yanzuo Chen, Zhibo Liu, **Yuanyuan Yuan**$^\dagger$, Sihang Hu, Tianxiang Li, and Shuai Wang$^\dagger$.  
In *32nd Network and Distributed System Security Symposium*, 2025.  
$^\dagger$ Corresponding authors.  
[[preprint]](https://yuanyuan-yuan.github.io/files/ndss25-exe-BFA.pdf)

- [**NDSS 23**] [OBSan: An Out-Of-Bound Sanitizer to Harden DNN Executables](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f103_paper.pdf).  
Yanzuo Chen, **Yuanyuan Yuan**$^\dagger$, and Shuai Wang$^\dagger$.  
In *30th Network and Distributed System Security Symposium*, 2023.  
$^\dagger$ Corresponding authors.  
[[project page]](https://sites.google.com/view/oob-sanitizer/), [[code]](https://github.com/yanzuochen/obsan)

- [**ICSE 23b**] [CC: Causality-Aware Coverage Criterion for Deep Neural Networks](https://dl.acm.org/doi/pdf/10.1109/ICSE48619.2023.00153).  
Zhenlan Ji, Pingchuan Ma$^\dagger$, **Yuanyuan Yuan**$^\dagger$, and Shuai Wang.  
In *45th IEEE/ACM International Conference on Software Engineering*, 2023.  
$^\dagger$ Corresponding authors.  
[[code]](https://github.com/ZhenlanJi/DL_CC)


## Academic Services

- **Program Committee**: DeepTest 2025, USENIX Security 2023 (Artifact Evaluation), OSDI 2022 and USENIX ATC 2022 (Artifact Evaluation), ISSTA 2022 (Artifact Evaluation).

- **External Reviewer**: IEEE S&P 2024, USENIX Security 2024, ISSTA 2024, FSE 2024, USENIX Security 2023, ISSTA 2023, FSE 2023, ASE 2022, CCS 2022.
<!-- POPL 2020 Artifact Evaluation, ICICS 2020, ICICS 2021, AsiaCCS 2021, AsiaCCS 2022, Journal of System and Software.  -->

## Teaching Experience

- **Guest Lecturer**: *Automated Software Testing*. ETH Zurich, Spring 2023.
- **Teaching Assistant**: *COMP3632: Principles of Cybersecurity*. HKUST, Fall 2021.
- **Teaching Assistant**: *COMP3632: Principles of Cybersecurity*. HKUST, Spring 2021.
- **Teaching Assistant**: *Introduction to Computer System*. Fudan University, Fall 2018.


<!-- <p align="center">
  <script type="text/javascript" src="//rf.revolvermaps.com/0/0/8.js?i=58fqm6u2ofs&amp;m=0&amp;c=ff0000&amp;cr1=ffffff&amp;f=arial&amp;l=33&amp;s=200" async="async"></script>
</p> -->

*<font size="2"><u>Last updated: 27 Nov. 2024</u></font>*