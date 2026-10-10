---
permalink: /
title: ""
excerpt: "About me"
author_profile: false
# classes: wide
redirect_from: 
  - /about/
  - /about.html
footer_text: |
  Last Updated: October 11, 2026
---

<div class="home-profile">
  <img
    class="home-profile__photo"
    src="{{ '/images/yuanyuan.png' | relative_url }}"
    alt="{{ site.author.name | escape }}"
  >

  <div class="home-profile__summary">
    <h1>{{ site.author.name }} <span class="home-profile__name-zh" lang="zh-CN">(袁渊源)</span></h1>

    <p>
      Assistant Professor<br>
      School of Software, Tsinghua University<br>
      E-mail: yyyuan@tsinghua.edu.cn<br>
      <span lang="zh-CN">国家级青年人才</span>
    </p>

    <div class="home-profile__links">
      {% if site.author.email %}
      <a href="mailto:{{ site.author.email }}" aria-label="Email">
        <i class="fas fa-envelope" aria-hidden="true"></i>
      </a>
      {% endif %}
      {% if site.author.googlescholar %}
      <a href="{{ site.author.googlescholar }}" aria-label="Google Scholar">
        <i class="ai ai-google-scholar" aria-hidden="true"></i>
      </a>
      {% endif %}
      {% if site.author.github %}
      <a href="https://github.com/{{ site.author.github }}" aria-label="GitHub">
        <i class="fab fa-github" aria-hidden="true"></i>
      </a>
      {% endif %}
      {% if site.author.orcid %}
      <a href="{{ site.author.orcid }}" aria-label="ORCID">
        <i class="ai ai-orcid" aria-hidden="true"></i>
      </a>
      {% endif %}
    </div>
  </div>
</div>

My research focuses on the safety and security of AI systems, both in the digital and the physical worlds. 

Before joining Tsinghua University, I was a post-doc researcher at ETH Zurich (2024-2025), working with Prof. [Zhendong Su](https://people.inf.ethz.ch/suz/). I obtained my Ph.D. degree from HKUST in 2024 under the supervision of Prof. [Shuai Wang](https://www.cse.ust.hk/~shuaiw/), and my B.S. degree from Fudan University in 2020.

 
> **Openings:** I am always looking for self-motivated students (Post-doc, PhD, Master, and Undergraduate). If you are interested in joining my group, please drop me an email with your CV and transcripts.

# Team
{: #team }

- Tianyi Wei (Incoming Ph.D. student, 2027 Fall); currently 4th-year UG @ THU

- Xi Xiang (Incoming Master student, 2027 Fall); currently 4th-year UG @ THU

- Xin Ma (Incoming Master student, 2027 Fall); co-advised with Prof. [Yu Jiang](https://sites.google.com/site/jiangyu198964); currently 4th-year UG @ THU


# Teaching
{: #teaching }

- *Data Structure*, Fall 2026.

# Services
{: #services }

### Program Committee:

- **2027:** IEEE S&P, USENIX Security, FSE, ICSE
- **2026:** USENIX Security, CCS, ICSE, ISSTA
- **2025:** LMPL@SPLASH, LAMPS@CCS, DeepTest@ICSE
- **2023:** USENIX Security (AE)
- **2022:** OSDI (AE), ATC (AE), ISSTA (AE)

### Reviewer:

- **2027:** ICLR
- **2026:** TOSEM, TDSC, TCAD
- **2025:** TOSEM, TDSC, TSE

# Selected Awards
{: #awards }

- 🏆 **Distinguished Paper Award**, IEEE Symposium on Security and Privacy (S&P), 2025.

- 🏆 **Best PhD Dissertation Award** (one awardee per year), Department of CSE, HKUST, 2024.


# Selected Projects
{: #projects }

- **Semantic Side-Channel Analysis for Large Model Systems.**  
 *NSFC General Program* --- PI

- **Attack and Defense for Embodied AI Systems in Open Physical Environments.**  
*BJNSF Joint Fund (Key Project)* --- PI

- **AI Systems Security.**  
*NSFC Excellent Young Scientists Fund (Overseas)* --- PI


# Selected Publications
{: #publications }
*$^\dagger$ indicates (co-)corresponding authors.*


- [**IEEE S&P**] <u>SEED: Eliciting Internal Safety for Jailbreak Defense in Large Reasoning Models via Exploratory Decoding</u>.  
Yujue Wang, Quan Zhang$^\dagger$, Gwihwan Go, Chijin Zhou, **Yuanyuan Yuan**$^\dagger$, Heyuan Shi, Yu Jiang.  
In *48th IEEE Symposium on Security and Privacy*, 2027.

- [**Black Hat EU**] <u>Rooting Your Robots: Breaking Authentication Across Quadruped and Humanoid Robots</u>.  
Yuqiao Yang, Fuchen Ma, Ting Chen, Yu Jiang, **Yuanyuan Yuan**, Yuanming Xie, Minglang Li, Xinnuo Ying, Ao Wang, and Jiaxin Dong.  
In *26th Black Hat Europe*, 2026.  

- [**CCS**] <u>PathMark: Protecting Intellectual Property of Mixture-of-expert LLMs via Path Watermarks</u>.  
Yudong Gao, Qingyue Wang$^\dagger$, **Yuanyuan Yuan**$^\dagger$, Ruixuan Huang, Linghan Chen, Zimo Ji, and Shuai Wang.  
In *33rd ACM Conference on Computer and Communications Security*, 2026.

- [**TOSEM**] <u>How Multi-Modal LLMs Reshape Visual Deep Learning Testing: A Comprehensive Study Through the Lens of Image Mutation</u>.  
Liwen Wang, **Yuanyuan Yuan**$^\dagger$, Ao Sun, Zongjie Li, Pingchuan Ma, Daoyuan Wu, and Shuai Wang$^\dagger$.  
In *ACM Transactions on Software Engineering and Methodology*, 2026. 

- [**DL4C@NeurIPS**] <u>Is Your Benchmark (Still) Useful? Dynamic Benchmarking for Code Language Models</u>.  
Batu Guan, Xiao Wu, **Yuanyuan Yuan**, and Shaohua Li.  
In *4th Deep Learning for Code Workshop @ NeurIPS*, 2025.  
[[preprint]](https://arxiv.org/pdf/2503.06643)

- [**NDSS**] [BitShield: Defending Against Bit-Flip Attacks on DNN Executables](https://www.ndss-symposium.org/wp-content/uploads/2025-1463-paper.pdf).  
Yanzuo Chen, **Yuanyuan Yuan**$^\dagger$, Zhibo Liu, Sihang Hu, Tianxiang Li, and Shuai Wang$^\dagger$.  
In *32nd Network and Distributed System Security Symposium*, 2025.  
[[preprint]](https://yuanyuan-yuan.github.io/files/ndss25-BitShield.pdf), [[code]](https://github.com/yanzuochen/bitshield)

- [**IEEE S&P**] <u>CipherSteal: Stealing Input Data from TEE-Shielded Neural Networks with Ciphertext Side Channels</u>.  
**Yuanyuan Yuan**, Zhibo Liu, Sen Deng, Yanzuo Chen, Shuai Wang, Yinqian Zhang, and Zhendong Su.  
In *46th IEEE Symposium on Security and Privacy*, 2025.   
🏆 <span style="color:red">**Distinguished Paper Award**</span>  
[[preprint]](https://yuanyuan-yuan.github.io/files/sp25-Cipher-Steal.pdf)

- [**NDSS**] [Compiled Models, Built-In Exploits: Uncovering Pervasive Bit-Flip Attack Surfaces in DNN Executables](https://www.ndss-symposium.org/wp-content/uploads/2025-419-paper.pdf).  
Yanzuo Chen, Zhibo Liu, **Yuanyuan Yuan**$^\dagger$, Sihang Hu, Tianxiang Li, and Shuai Wang$^\dagger$.  
In *32nd Network and Distributed System Security Symposium*, 2025.  
🏅 **Presented at Black Hat Europe.**  
[[preprint]](https://yuanyuan-yuan.github.io/files/ndss25-exe-BFA.pdf), [[code]](https://github.com/yanzuochen/debfa)

- [**Thesis**] [Side Channel Analysis for AI Infrastructures](https://yuanyuan-yuan.github.io/files/phd-thesis.pdf).  
**Yuanyuan Yuan**.  
*Ph.D. Thesis*, 2024.  
🏆 <span style="color:red">**Best PhD Dissertation Award 2024**</span> (one awardee per year), CSE, HKUST

- [**Black Hat EU**] [The Devil is in the (Micro-) Architectures: Uncovering New Side-Channel and Bit-Flip Attack Surfaces in DNN Executables](https://www.blackhat.com/eu-24/briefings/schedule/#the-devil-is-in-the-micro--architectures-uncovering-new-side-channel-and-bit-flip-attack-surfaces-in-dnn-executables-42018).  
Yanzuo Chen, Zhibo Liu, **Yuanyuan Yuan**, Sihang Hu, Tianxiang Li, and Shuai Wang.  
In *24th Black Hat Europe*, 2024.  
[[white paper]](https://yanzuo.ch/bh24), [[slides]](https://i.blackhat.com/EU-24/Presentations/EU-24-Chen-DevilIsInMicroArchitectures.pdf?_gl=1*24s182*_gcl_au*MTQwNjU0NDMyMC4xNzQ2MjAwMzk0*_ga*OTY3NjE1NDM4LjE3NDYyMDAzOTE.*_ga_K4JK67TFYV*czE3NDc5MTEyMzEkbzMkZzEkdDE3NDc5MTEzMzckajE5JGwwJGgwJGRHemlOQnB0alM1TnVnQ3hCZW9ROWo0T0xmUk5tZW5peXFR&_ga=2.31782843.489905144.1747903663-967615438.1746200391)

- [**CCS**] [DeepCache: Revisiting Cache Side-Channel Attacks in Deep Neural Networks Executables](https://yuanyuan-yuan.github.io/files/ccs24-DeepCache.pdf).  
Zhibo Liu, **Yuanyuan Yuan**, Yanzuo Chen, Sihang Hu, Tianxiang Li, and Shuai Wang.  
In *31st ACM Conference on Computer and Communications Security*, 2024.  
🏅 **Presented at Black Hat Europe.**  
[[code]](https://github.com/monkbai/DeepCache)

- [**CCS**] [HyperTheft: Thieving Model Weights from TEE-Shielded Neural Networks via Ciphertext Side Channels](https://dl.acm.org/doi/pdf/10.1145/3658644.3690317).  
**Yuanyuan Yuan**, Zhibo Liu, Sen Deng, Yanzuo Chen, Shuai Wang, Yinqian Zhang, and Zhendong Su.  
In *31st ACM Conference on Computer and Communications Security*, 2024.  
[[extended version]](https://yuanyuan-yuan.github.io/files/ccs24-HyperTheft-full.pdf)

- [**ISSTA**] [See the Forest, not Trees: Unveiling and Escaping the Pitfalls of Error-Triggering Inputs in Neural Network Testing](https://dl.acm.org/doi/abs/10.1145/3650212.3680385).  
**Yuanyuan Yuan**, Shuai Wang, and Zhendong Su.  
In *33rd International Symposium on Software Testing and Analysis*, 2024.  

- [**TSE**] [Provably Valid and Diverse Mutations of Real-World Media Data for DNN Testing](https://ieeexplore.ieee.org/document/10462634).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *IEEE Transactions on Software Engineering*, 2024.  
[[preprint]](https://arxiv.org/abs/2112.01956)

- [**IEEE S&P**] [No Privacy Left Outside: On the (In-)Security of TEE-Shielded DNN Partition Defenses](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a052/1RjEarlPFew).  
Ziqi Zhang, Chen Gong, Yifeng Cai, **Yuanyuan Yuan**, Bingyan Liu, Ding Li, Yao Guo, and Xiangqun Chen.  
In *45th IEEE Symposium on Security and Privacy*, 2024.  
[[code]](https://github.com/ziqi-zhang/TEESlice-artifact)

- [**NDSS**] [MPCDiff: Testing and Repairing MPC-Hardened Deep Learning Models](https://www.ndss-symposium.org/ndss-paper/mpcdiff-testing-and-repairing-mpc-hardened-deep-learning-models/).  
Qi Pang, **Yuanyuan Yuan**, and Shuai Wang.  
In *31st Network and Distributed System Security Symposium*, 2024.  
[[code]](https://github.com/Qi-Pang/MPCDiff)


- [**NeurIPS**] [Explain Any Concept: Segment Anything Meets Concept-Based Explanation](https://openreview.net/pdf?id=X6TBBsz9qi).  
Ao Sun, Pingchuan Ma, **Yuanyuan Yuan**, and Shuai Wang.  
In *37th Conference on Neural Information Processing Systems*, 2023.  
[[code]](https://github.com/Jerry00917/samshap)

- [**Black Hat USA**] [BTD: Unleashing the Power of Decompilation for x86 Deep Neural Network Executables](https://www.blackhat.com/us-23/briefings/schedule/index.html#btd-unleashing-the-power-of-decompilation-for-x-deep-neural-network-executables-33028).  
Zhibo Liu, **Yuanyuan Yuan**, Xiaofei Xie, Tianxiang Li, Wenqiang Li, and Shuai Wang.  
In *26th Black Hat USA*, 2023.  
[[white paper]](https://yuanyuan-yuan.github.io/files/BH23-decompielr.pdf), [[slides]](https://i.blackhat.com/BH-US-23/Presentations/US-23-ZhiboLiu-BTD-Unleashing-the-Power.pdf)

- [**IEEE S&P**] [ADI: Adversarial Dominating Inputs in Vertical Federated Learning Systems](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b875/1NrbZgBwxa0).  
Qi Pang, **Yuanyuan Yuan**, Shuai Wang, and Wenting Zheng.  
In *44th IEEE Symposium on Security and Privacy*, 2023.  
[[extended version]](https://arxiv.org/pdf/2201.02775.pdf)

- [**NDSS**] [OBSan: An Out-Of-Bound Sanitizer to Harden DNN Executables](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f103_paper.pdf).  
Yanzuo Chen, **Yuanyuan Yuan**$^\dagger$, and Shuai Wang$^\dagger$.  
In *30th Network and Distributed System Security Symposium*, 2023.  
[[project page]](https://sites.google.com/view/oob-sanitizer/), [[code]](https://github.com/yanzuochen/obsan)

- [**USENIX Security**] [Precise and Generalized Robustness Certification for Neural Networks](https://www.usenix.org/conference/usenixsecurity23/presentation/yuan-yuanyuan-certification).  
**Yuanyuan Yuan**, Shuai Wang, and Zhendong Su.  
In *32nd USENIX Security Symposium*, 2023.  
[[extended version]](https://arxiv.org/pdf/2306.06747.pdf), [[code]](https://github.com/Yuanyuan-Yuan/GCert)

- [**USENIX Security**] [CacheQL: Quantifying and Localizing Cache Side-Channel Vulnerabilities in Production Software](https://www.usenix.org/conference/usenixsecurity23/presentation/yuanyuanyuan).  
**Yuanyuan Yuan**, Zhibo Liu, and Shuai Wang.  
In *32nd USENIX Security Symposium*, 2023.  
[[extended version]](https://arxiv.org/pdf/2209.14952.pdf), [[findings]](https://sites.google.com/view/cache-ql#h.pgsarsaxsdsv), [[code]](https://github.com/Yuanyuan-Yuan/CacheQL)

- [**USENIX Security**] [Decompiling x86 Deep Neural Network Executables](https://www.usenix.org/conference/usenixsecurity23/presentation/liuzhibo).  
Zhibo Liu, **Yuanyuan Yuan**, Shuai Wang, Xiaofei Xie, and Lei Ma.  
In *32nd USENIX Security Symposium*, 2023.  
🏅 **Artifact Evaluation Badges**: Available; Functional; Reproduced.  
🏅 **Presented at Black Hat USA.**  
[[extended version]](https://arxiv.org/pdf/2210.01075.pdf), [[code]](https://github.com/monkbai/DNN-decompiler) <a href="https://github.com/monkbai/DNN-decompiler" target="_blank"><img src="https://img.shields.io/github/stars/monkbai/DNN-decompiler.svg?style=social&label=Star&maxAge=180"></a>

- [**ICSE**] [CC: Causality-Aware Coverage Criterion for Deep Neural Networks](https://dl.acm.org/doi/pdf/10.1109/ICSE48619.2023.00153).  
Zhenlan Ji, Pingchuan Ma$^\dagger$, **Yuanyuan Yuan**$^\dagger$, and Shuai Wang.  
In *45th IEEE/ACM International Conference on Software Engineering*, 2023.  
[[code]](https://github.com/ZhenlanJi/DL_CC)

- [**ICSE**] [Revisiting Neuron Coverage for DNN Testing: A Layer-Wise and Distribution-Aware Criterion](https://dl.acm.org/doi/pdf/10.1109/ICSE48619.2023.00107).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *45th IEEE/ACM International Conference on Software Engineering*, 2023.  
[[extended version]](https://arxiv.org/abs/2112.01955), [[code]](https://github.com/Yuanyuan-Yuan/NeuraL-Coverage) <a href="https://github.com/Yuanyuan-Yuan/NeuraL-Coverage" target="_blank"><img src="https://img.shields.io/github/stars/Yuanyuan-Yuan/NeuraL-Coverage.svg?style=social&label=Star&maxAge=180"></a>


- [**ASE**] [Unveiling Hidden DNN Defects with Decision-Based Metamorphic Testing](https://dl.acm.org/doi/abs/10.1145/3551349.3561157).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *37th IEEE/ACM International Conference on Automated Software Engineering*, 2022.  
[[extended version]](https://arxiv.org/pdf/2210.04942.pdf), [[code]](https://github.com/Yuanyuan-Yuan/Decision-Oracle)

- [**ISSTA**] [MDPFuzz: Testing Models Solving Markov Decision Processes](https://dl.acm.org/doi/abs/10.1145/3533767.3534388).  
Qi Pang, **Yuanyuan Yuan**, and Shuai Wang.  
In *31st International Symposium on Software Testing and Analysis*, 2022.  
[[code]](https://github.com/Qi-Pang/MDPFuzz)

- [**TIFS**] [NeuralD: Detecting Indistinguishability Violations of Oblivious RAM with Neural Distinguishers](https://ieeexplore.ieee.org/document/9722877).  
Pingchuan Ma, Zhibo Liu, **Yuanyuan Yuan**, and Shuai Wang.  
In *IEEE Transactions on Information Forensics and Security*, 2022.  
[[code]](https://github.com/pckennethma/NeuralD)

- [**TSE**] [Enhancing DNN-Based Binary Code Function Search With Low-Cost Equivalence Checking](https://ieeexplore.ieee.org/document/9707874).  
Huaijin Wang, Pingchuan Ma, **Yuanyuan Yuan**, Zhibo Liu, Shuai Wang, Qiyi Tang, Sen Nie, and Shi Wu.  
In *IEEE Transactions on Software Engineering*, 2022.  
[[code]](https://github.com/computer-analysis/BinUSE)

- [**SIGMETRICS**] [Metamorphic Testing of Deep Learning Compilers](https://dl.acm.org/doi/abs/10.1145/3508035).  
Dongwei Xiao, Zhibo Liu, **Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *ACM Sigmetrics/Performance*, 2022.  
[[code]](https://github.com/Wilbur-Django/Testing-DNN-Compilers)

- [**USENIX Security**] [Automated Side Channel Analysis of Media Software with Manifold Learning](https://www.usenix.org/conference/usenixsecurity22/presentation/yuan).  
**Yuanyuan Yuan**, Qi Pang, and Shuai Wang.  
In *31st USENIX Security Symposium*, 2022.  
🏅 **Artifact Evaluation Badges**: Available; Functional; Reproduced.    
[[extended version]](https://arxiv.org/pdf/2112.04947.pdf), [[code]](https://github.com/Yuanyuan-Yuan/Manifold-SCA) <a href="https://github.com/Yuanyuan-Yuan/Manifold-SCA" target="_blank"><img src="https://img.shields.io/github/stars/Yuanyuan-Yuan/Manifold-SCA.svg?style=social&label=Star&maxAge=180"></a>

- [**IEEE S&P**] [SoK: Demystifying Binary Lifters Through the Lens of Downstream Applications](https://www.computer.org/csdl/proceedings-article/sp/2022/131600a453/1wKCev3wlbO).  
Zhibo Liu, **Yuanyuan Yuan**, Shuai Wang, and Yuyan Bao.  
In *43rd IEEE Symposium on Security and Privacy*, 2022.  
[[code]](https://github.com/monkbai/ir_lifting_data)

- [**CVPR**] [Perception Matters: Detecting Perception Failures of VQA Models Using Metamorphic Testing](https://openaccess.thecvf.com/content/CVPR2021/html/Yuan_Perception_Matters_Detecting_Perception_Failures_of_VQA_Models_Using_Metamorphic_CVPR_2021_paper.html).  
**Yuanyuan Yuan**, Shuai Wang, Mingyue Jiang, and Tsong Yueh Chen.  
In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2021.  
[[code]](https://github.com/MetaVQA/MetaVQA)

- [**ICLR**] [Private Image Reconstruction from System Side Channels Using Generative Models](https://openreview.net/forum?id=y06VOYLcQXa).  
**Yuanyuan Yuan**, Shuai Wang, and Junping Zhang.  
In *International Conference on Learning Representations*, 2021.  
[[code]](https://github.com/genSCA/genSCA)

