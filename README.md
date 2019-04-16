# adversarial robustness paper
近期顶会对抗样本相关论文列表
## Attack
- [ICLR19][STRUCTURED ADVERSARIAL ATTACK: TOWARDS GENERAL IMPLEMENTATION AND BETTER INTERPRETABILITY ](https://arxiv.org/abs/1808.01664) - Kaidi Xu, Sijia Liu, Pu Zhao, Pin-Yu Chen, Huan Zhang, Quanfu Fan, Deniz Erdogmus, Yanzhi Wang, Xue Lin
- [ICLR19][THE LIMITATIONS OF ADVERSARIAL TRAINING AND THE BLIND-SPOT ATTACK ](https://openreview.net/pdf?id=HylTBhA5tQ) - Huan Zhang, Hongge Chen, Zhao Song, Duane Boning, Inderjit S. Dhillon, Cho-Jui Hsieh
- [NeurIPS2018][Adversarial Attacks on Stochastic Bandits ](https://arxiv.org/abs/1810.12188) - Kwang-Sung Jun, Lihong Li, Yuzhe Ma, Xiaojin Zhu
- [NeurIPS2018][ConstructingUnrestrictedAdversarialExamples withGenerativeModels ](https://arxiv.org/abs/1805.07894) - Yang Song, Rui Shu, Nate Kushman, Stefano Ermon
### black-box
- [ICLR19][PRIOR CONVICTIONS: BLACK-BOX ADVERSARIAL ATTACKS WITH BANDITS AND PRIORS ](https://arxiv.org/abs/1807.07978) - Andrew Ilyas, Logan Engstrom, Aleksander Madry
- [arxiv2017][ZOO: Zeroth Order Optimization based Black-box Attacks to Deep Neural Networks without Training Substitute Models.](https://arxiv.org/pdf/1708.03999.pdf) - 	Pin-Yu Chen, Huan Zhang, Yash Sharma, Jinfeng Yi, Cho-Jui Hsieh
- [arxiv2019][Boundary Attack++: Query-Efficient Decision-Based Adversarial Attack](https://arxiv.org/pdf/1904.02144v1.pdf) - Jianbo Chen,Michael I. Jordan
- [cvpr19][Efficient Decision-based Black-box Adversarial Attacks on Face Recognition](https://arxiv.org/abs/1904.04433) - Yinpeng Dong, Hang Su, Baoyuan Wu, Zhifeng Li, Wei Liu, Tong Zhang, Jun Zhu
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
- [ICLR19] [IMPROVING THE GENERALIZATION OF ADVERSARIAL TRAINING WITH DOMAIN ADAPTATION](https://arxiv.org/pdf/1810.00740v5.pdf) - Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft
- [NeurIps2018][Thwarting Adversarial Examples: An L0-Robust Sparse Fourier Transform ](https://papers.nips.cc/paper/8211-thwarting-adversarial-examples-an-l_0-robust-sparse-fourier-transform.pdf) - Mitali Bafna, Jack Murtagh, Nikhil Vyas
- [NeurIps2018][Bayesian Adversarial Learning ](https://papers.nips.cc/paper/7921-bayesian-adversarial-learning) - Nanyang Ye, Zhanxing Zhu
- [arxiv2018][Adversarial Logit Pairing](https://arxiv.org/pdf/1803.06373v1.pdf) - Harini Kannan, Alexey Kurakin, Ian Goodfellow
- [AAAL2018][Improving the Adversarial Robustness and Interpretability of Deep Neural Networks by Regularizing their Input Gradients](https://arxiv.org/pdf/1711.09404.pdf) - Andrew Slavin Ross,  Finale Doshi-Velez
- [ICLR2018][Cascade Adversarial Machine Learning Regularized with a Unified Embedding ](https://arxiv.org/abs/1708.02582) - Taesik Na, Jong Hwan Ko, Saibal Mukhopadhyay
- [IJCAL2018][Curriculum Adversarial Training](https://web.kamihq.com/web/viewer.html?state=%7B%22ids%22%3A%5B%221qW8LCY-BXiZh0_H0riwvy8aBltjKBse7%22%5D%2C%22action%22%3A%22open%22%2C%22userId%22%3A%22104130955753285146508%22%7D&filename=undefined) - Qi-Zhi Cai, Min Du , Chang Liu , Dawn Song 
- [ICLR19][THE LIMITATIONS OF ADVERSARIAL TRAINING AND THE BLIND-SPOT ATTACK](https://arxiv.org/pdf/1901.04684v1.pdf) - Huan Zhang
, Hongge Chen, Zhao Song, Duane Boning, Inderjit Dhillon, Cho-Jui Hsieh
- [AAAL18][Regularizing deep networks using efficient layerwise adversarial training](https://arxiv.org/abs/1705.07819) - Swami Sankaranarayanan, Arpit Jain, Rama Chellappa, Ser Nam Lim
- [NeurIps2018][Hessian-based Analysis of Large Batch Training and Robustness to Adversaries](https://arxiv.org/pdf/1802.08241v4.pdf) - Zhewei Yao1, Amir Gholami1, Qi Lei, Kurt Keutzer, Michael W. Mahoney



### Modified networks
- [ICLR19][PEERNETS: EXPLOITING PEER WISDOM AGAINST ADVERSARIAL ATTACKS](https://arxiv.org/abs/1806.00088) - Jan Svoboda, Jonathan Masci, Federico Monti, Michael M. Bronstein, Leonidas Guibas
- [ICLR19][TRAINING FOR FASTER ADVERSARIAL ROBUSTNESS VERIFICATION VIA INDUCING RELU STABILITY](https://arxiv.org/abs/1809.03008) - Kai Y. Xiao, Vincent Tjeng, Nur Muhammad Shafiullah, Aleksander Madry
- [ICLR19][EVALUATING ROBUSTNESS OF NEURAL NETWORKS WITH MIXED INTEGER PROGRAMMING ](https://arxiv.org/abs/1711.07356) - Vincent Tjeng, Kai Xiao, Russ Tedrake
- [ICLR19][TOWARDS THE FIRST ADVERSARIALLY ROBUST NEURAL NETWORK MODEL ON MNIST](https://arxiv.org/abs/1805.09190) - Lukas Schott, Jonas Rauber, Matthias Bethge, Wieland Brendel
- [NeurIps2018][Efficient Neural Network Robustness Certification with General Activation Functions ](https://arxiv.org/abs/1811.00866?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%253A+arxiv%252FQSXk+%2528ExcitingAds%2521+cs+updates+on+arXiv.org%2529) - Huan Zhang, Tsui-Wei Weng, Pin-Yu Chen, Cho-Jui Hsieh, Luca Daniel
- [NeurIps2018][Semidefinite relaxations for certifying robustness to adversarial examples ](https://arxiv.org/abs/1811.01057) - Aditi Raghunathan, Jacob Steinhardt, Percy Liang
- [NeurIps2018][Efficient Formal Safety Analysis of Neural Networks ](https://arxiv.org/abs/1809.08098) - Shiqi Wang, Kexin Pei, Justin Whitehouse, Junfeng Yang, Suman Jana
- [ICLR18][STOCHASTIC ACTIVATION PRUNING FOR ROBUST ADVERSARIAL DEFENSE](https://arxiv.org/pdf/1803.01442.pdf) - Guneet S. Dhillon, Kamyar Azizzadenesheli, Zachary C. Lipton, Jeremy Bernstein, Jean Kossaifi, Aran Khanna, Anima Anandkumar


#### Adversarial Detecting

- [NeurIps2018][Towards Robust Detection of Adversarial Examples ](https://arxiv.org/abs/1706.00633) - Tianyu Pang, Chao Du, Yinpeng Dong, Jun Zhu
- [NeurIps2018][Robust Detection of Adversarial Attacks by Modeling the Intrinsic Properties of Deep Neural Networks ](https://papers.nips.cc/paper/8016-robust-detection-of-adversarial-attacks-by-modeling-the-intrinsic-properties-of-deep-neural-networks.pdf) - Zhihao Zheng, Pengyu Hong
- [NeurIps2018][Attacks Meet Interpretability: Attribute-steered Detection of Adversarial Samples ](https://arxiv.org/abs/1810.11580) - Guanhong Tao, Shiqing Ma, Yingqi Liu, Xiangyu Zhang
- [AAAL2019][Resisting Adversarial Attacks Using Gaussian Mixture Variational Autoencoders](https://arxiv.org/pdf/1806.00081v2.pdf) - Partha Ghosh, Arpan Losalka, Michael J Black



### Network add-on
- [NeurIps2018][Improved Network Robustness with Adversary Critic ](https://arxiv.org/abs/1810.12576) - Alexander Matyasko, Lap-Pui Chau

## Analysis of Adversarial Examples
- [ICLR19][ROBUSTNESS MAY BE AT ODDS WITH ACCURACY ](https://arxiv.org/abs/1805.12152) - Dimitris Tsipras, Shibani Santurkar, Logan Engstrom, Alexander Turner, Aleksander Madry
- [ICLR19][ARE ADVERSARIAL EXAMPLES INEVITABLE? ](https://arxiv.org/abs/1809.02104) - Ali Shafahi, W. Ronny Huang, Christoph Studer, Soheil Feizi, Tom Goldstein
- [NeurIps2018][Adversarial Examples that Fool both Computer Vision and Time-Limited Humans ](https://arxiv.org/abs/1802.08195) - Gamaleldin F. Elsayed, Shreya Shankar, Brian Cheung, Nicolas Papernot, Alex Kurakin, Ian Goodfellow, Jascha Sohl-Dickstein
- [airxiv2019][Towards Understanding Adversarial Examples Systematically: Exploring Data Size, Task and Model Factors](https://arxiv.org/abs/1902.11019) - Ke Sun, Zhanxing Zhu, Zhouchen Lin

## Model Compression And Adversarial Robustness
- [ICLR19][COMBINATORIAL ATTACKS ON BINARIZED NEURAL NETWORKS](https://arxiv.org/abs/1810.03538) - Elias B. Khalil, Amrita Gupta, Bistra Dilkina
- [ICLR19][DEFENSIVE QUANTIZATION: WHEN EFFICIENCY MEETS ROBUSTNESS](https://openreview.net/pdf?id=ryetZ20ctX) - Ji Lin, Chuang Gan, Song Han
- [NeurIps2018][Sparse DNNs with Improved Adversarial Robustness](https://arxiv.org/abs/1810.09619) - Yiwen Guo, Chao Zhang, Changshui Zhang, Yurong Chen
- [arxiv2018][TO COMPRESS OR NOT TO COMPRESS: UNDERSTANDING THE INTERACTIONS BETWEEN ADVERSARIAL ATTACKS AND NEURAL NETWORK COMPRESSION ](https://arxiv.org/pdf/1810.00208v1.pdf) - Yiren Zhao, Ilia Shumailov, Robert Mullins, Ross Anderson

## Others
- [ICLR19][COST-SENSITIVE ROBUSTNESS AGAINST ADVERSARIAL EXAMPLES ](https://arxiv.org/abs/1810.09225) - Xiao Zhang, David Evans
- [ICLR19][BENCHMARKING NEURAL NETWORK ROBUSTNESS TO COMMON CORRUPTIONS AND PERTURBATIONS](https://arxiv.org/abs/1807.01697) - Dan Hendrycks, Thomas G. Dietterich

## blogs
- [Adversarial Robustness - Theory and Practice](https://adversarial-ml-tutorial.org/)
