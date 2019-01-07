# adversarial robustness paper
近期顶会对抗样本相关论文列表
## Attack
- [ICLR19][STRUCTURED ADVERSARIAL ATTACK: TOWARDS GENERAL IMPLEMENTATION AND BETTER INTERPRETABILITY ](https://arxiv.org/abs/1808.01664) - Kaidi Xu, Sijia Liu, Pu Zhao, Pin-Yu Chen, Huan Zhang, Quanfu Fan, Deniz Erdogmus, Yanzhi Wang, Xue Lin
- [ICLR19][THE LIMITATIONS OF ADVERSARIAL TRAINING AND THE BLIND-SPOT ATTACK ](https://openreview.net/pdf?id=HylTBhA5tQ) - Huan Zhang, Hongge Chen, Zhao Song, Duane Boning, Inderjit S. Dhillon, Cho-Jui Hsieh
- [NeurIPS2018][Adversarial Attacks on Stochastic Bandits ](https://arxiv.org/abs/1810.12188) - Kwang-Sung Jun, Lihong Li, Yuzhe Ma, Xiaojin Zhu
- [NeurIPS2018][ConstructingUnrestrictedAdversarialExamples withGenerativeModels ](https://arxiv.org/abs/1805.07894) - Yang Song, Rui Shu, Nate Kushman, Stefano Ermon
### black-box
- [ICLR19][PRIOR CONVICTIONS: BLACK-BOX ADVERSARIAL ATTACKS WITH BANDITS AND PRIORS ](https://arxiv.org/abs/1807.07978) - Andrew Ilyas, Logan Engstrom, Aleksander Madry
### white-box
- [ICLR19][ADEF: AN ITERATIVE ALGORITHM TO CONSTRUCT ADVERSARIAL DEFORMATIONS ](https://arxiv.org/abs/1804.07729) - Rima Alaifari, Giovanni S. Alberti, Tandri Gauksson

## Defense
> Currently, the defenses against the adversarial attacks are being developed along three main directions: (for details,read [this paper](https://arxiv.org/pdf/1801.00553.pdf))
>   1) Using modified training during learning or modified input during testing. 
>   2) Modifying networks, e.g. by adding more layers/subnetworks, changing loss/activation functions etc.
>   3) Using external models as network add-on when classifying unseen examples.

<div align=center><img src="https://github.com/hfeng-xia/adversarial-robustness/blob/master/IMG/1.jpg"/></div>


> ###### <p align="right"> *Figure from "[Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey](https://arxiv.org/pdf/1801.00553.pdf)"*</p>

### Modified training / input
- [NeurIps2018][Thwarting Adversarial Examples: An L0-Robust Sparse Fourier Transform ](https://papers.nips.cc/paper/8211-thwarting-adversarial-examples-an-l_0-robust-sparse-fourier-transform.pdf) - Mitali Bafna, Jack Murtagh, Nikhil Vyas
- [NeurIps2018][Bayesian Adversarial Learning ](https://papers.nips.cc/paper/7921-bayesian-adversarial-learning) - Nanyang Ye, Zhanxing Zhu
### Modified networks
- [ICLR19][PEERNETS: EXPLOITING PEER WISDOM AGAINST ADVERSARIAL ATTACKS](https://arxiv.org/abs/1806.00088) - Jan Svoboda, Jonathan Masci, Federico Monti, Michael M. Bronstein, Leonidas Guibas
- [ICLR19][TRAINING FOR FASTER ADVERSARIAL ROBUSTNESS VERIFICATION VIA INDUCING RELU STABILITY](https://arxiv.org/abs/1809.03008) - Kai Y. Xiao, Vincent Tjeng, Nur Muhammad Shafiullah, Aleksander Madry
- [ICLR19][EVALUATING ROBUSTNESS OF NEURAL NETWORKS WITH MIXED INTEGER PROGRAMMING ](https://arxiv.org/abs/1711.07356) - Vincent Tjeng, Kai Xiao, Russ Tedrake
- [ICLR19][TOWARDS THE FIRST ADVERSARIALLY ROBUST NEURAL NETWORK MODEL ON MNIST](https://arxiv.org/abs/1805.09190) - Lukas Schott, Jonas Rauber, Matthias Bethge, Wieland Brendel
- [NeurIps2018][Efficient Neural Network Robustness Certification with General Activation Functions ](https://arxiv.org/abs/1811.00866?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%253A+arxiv%252FQSXk+%2528ExcitingAds%2521+cs+updates+on+arXiv.org%2529) - Huan Zhang, Tsui-Wei Weng, Pin-Yu Chen, Cho-Jui Hsieh, Luca Daniel
- [NeurIps2018][Semidefinite relaxations for certifying robustness to adversarial examples ](https://arxiv.org/abs/1811.01057) - Aditi Raghunathan, Jacob Steinhardt, Percy Liang
- [NeurIps2018][Efficient Formal Safety Analysis of Neural Networks ](https://arxiv.org/abs/1809.08098) - Shiqi Wang, Kexin Pei, Justin Whitehouse, Junfeng Yang, Suman Jana
- [NeurIps2018][Efficient Neural Network Robustness Certification with General Activation Functions ](http://web.cs.ucla.edu/~chohsieh/efficient-neural-network.pdf) - Huan Zhang, Tsui-Wei Weng, Pin-Yu Chen, Cho-Jui Hsieh, Luca Daniel

#### Adversarial Detecting

- [NeurIps2018][Towards Robust Detection of Adversarial Examples ](https://arxiv.org/abs/1706.00633) - Tianyu Pang, Chao Du, Yinpeng Dong, Jun Zhu
- [NeurIps2018][Robust Detection of Adversarial Attacks by Modeling the Intrinsic Properties of Deep Neural Networks ](https://papers.nips.cc/paper/8016-robust-detection-of-adversarial-attacks-by-modeling-the-intrinsic-properties-of-deep-neural-networks.pdf) - Zhihao Zheng, Pengyu Hong
- [NeurIps2018][Attacks Meet Interpretability: Attribute-steered Detection of Adversarial Samples ](https://arxiv.org/abs/1810.11580) - Guanhong Tao, Shiqing Ma, Yingqi Liu, Xiangyu Zhang


### Network add-on
- [NeurIps2018][Improved Network Robustness with Adversary Critic ](https://arxiv.org/abs/1810.12576) - Alexander Matyasko, Lap-Pui Chau

## Analysis of Adversarial Examples
- [ICLR19][ROBUSTNESS MAY BE AT ODDS WITH ACCURACY ](https://arxiv.org/abs/1805.12152) - Dimitris Tsipras, Shibani Santurkar, Logan Engstrom, Alexander Turner, Aleksander Madry
- [ICLR19][ARE ADVERSARIAL EXAMPLES INEVITABLE? ](https://arxiv.org/abs/1809.02104) - Ali Shafahi, W. Ronny Huang, Christoph Studer, Soheil Feizi, Tom Goldstein
- [NeurIps2018][Adversarial Examples that Fool both Computer Vision and Time-Limited Humans ](https://arxiv.org/abs/1802.08195) - Gamaleldin F. Elsayed, Shreya Shankar, Brian Cheung, Nicolas Papernot, Alex Kurakin, Ian Goodfellow, Jascha Sohl-Dickstein
## Model Compression And Adversarial Robustness
- [ICLR19][COMBINATORIAL ATTACKS ON BINARIZED NEURAL NETWORKS](https://arxiv.org/abs/1810.03538) - Elias B. Khalil, Amrita Gupta, Bistra Dilkina
- [ICLR19][DEFENSIVE QUANTIZATION: WHEN EFFICIENCY MEETS ROBUSTNESS](https://openreview.net/pdf?id=ryetZ20ctX) - Ji Lin, Chuang Gan, Song Han
- [NeurIps2018][Sparse DNNs with Improved Adversarial Robustness](https://arxiv.org/abs/1810.09619) - Yiwen Guo, Chao Zhang, Changshui Zhang, Yurong Chen
## Others
- [ICLR19][COST-SENSITIVE ROBUSTNESS AGAINST ADVERSARIAL EXAMPLES ](https://arxiv.org/abs/1810.09225) - Xiao Zhang, David Evans
- [ICLR19][BENCHMARKING NEURAL NETWORK ROBUSTNESS TO COMMON CORRUPTIONS AND PERTURBATIONS](https://arxiv.org/abs/1807.01697) - Dan Hendrycks, Thomas G. Dietterich
