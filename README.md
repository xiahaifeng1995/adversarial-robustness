# adversarial robustness paper
本文档主要收集近期顶会上有关对抗样本的论文。
## Attack
- [ICLR19][A Frank-Wolfe Framework For Efficient And Effective Adversarial Attacks](https://arxiv.org/abs/1811.10828) - Jinghui Chen, Jinfeng Yi, Quanquan Gu
### Benchmarking
- [ICLR19][BENCHMARKING NEURAL NETWORK ROBUSTNESS TO COMMON CORRUPTIONS AND PERTURBATIONS](https://arxiv.org/abs/1807.01697) - Dan Hendrycks, Thomas G. Dietterich
## Defense
> Currently, the defenses against the adversarial attacks are being developed along three main directions: (for details,read [this paper](https://arxiv.org/pdf/1801.00553.pdf))
>   1) Using modified training during learning or modified input during testing. 
>   2) Modifying networks, e.g. by adding more layers/subnetworks, changing loss/activation functions etc.
>   3) Using external models as network add-on when classifying unseen examples.

<div align=center><img src="https://github.com/hfeng-xia/adversarial-robustness/blob/master/IMG/1.jpg"/></div>

### Modified training / input
- [ICLR19][EFFICIENT TWO-STEP ADVERSARIAL DEFENSE FOR DEEP NEURAL NETWORKS](https://openreview.net/pdf?id=BklpOo09tQ) - Ting-Jui Chang, Yukun He, Peng Li
- [ICLR19][FEATURE PRIORITIZATION AND REGULARIZATION IMPROVE STANDARD ACCURACY AND ADVERSARIAL ROBUSTNESS](https://openreview.net/pdf?id=ryG2Cs09Y7) - Chihuang Liu, Joseph JaJa
- [ICLR19][IMPROVED ROBUSTNESS TO ADVERSARIAL EXAMPLES USING LIPSCHITZ REGULARIZATION OF THE LOSS](https://arxiv.org/abs/1810.00953) - Chris Finlay, Adam Oberman, Bilal Abbasi
- [ICLR19][IMPROVING THE GENERALIZATION OF ADVERSARIAL TRAINING WITH DOMAIN ADAPTATION](https://arxiv.org/abs/1810.00740) - Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft
- [ICLR19][PLAYING THE GAME OF UNIVERSAL ADVERSARIAL PERTURBATIONS](https://arxiv.org/abs/1809.07802) - Julien Perolat, Mateusz Malinowski, Bilal Piot, Olivier Pietquin
### Modified networks
- [ICLR19][UNIFYING BILATERAL FILTERING AND ADVERSARIAL TRAINING FOR ROBUST NEURAL NETWORKS](https://arxiv.org/abs/1804.01635) - Neale Ratzlaff, Li Fuxin
- [ICLR19][A STUDY OF ROBUSTNESS OF NEURAL NETS USING APPROXIMATE FEATURE COLLISIONS](https://openreview.net/pdf?id=H1gDgn0qY7) - Ke Li, Tianhao Zhang, Jitendra Malik
- [ICLR19][DETECTING ADVERSARIAL EXAMPLES VIA NEURAL FINGERPRINTING](https://arxiv.org/abs/1803.03870) - Sumanth Dathathri, Stephan Zheng, Richard M. Murray, Yisong Yue
- [ICLR19][PEERNETS: EXPLOITING PEER WISDOM AGAINST ADVERSARIAL ATTACKS](https://arxiv.org/abs/1806.00088) - Jan Svoboda, Jonathan Masci, Federico Monti, Michael M. Bronstein, Leonidas Guibas
- [ICLR19][TRAINING FOR FASTER ADVERSARIAL ROBUSTNESS VERIFICATION VIA INDUCING RELU STABILITY](https://arxiv.org/abs/1809.03008) - Kai Y. Xiao, Vincent Tjeng, Nur Muhammad Shafiullah, Aleksander Madry
- [ICLR19][RANDOM MASK: TOWARDS ROBUST CONVOLUTIONAL NEURAL NETWORKS](https://openreview.net/pdf?id=SkgkJn05YX) - Tiange Luo, Tianle Cai, Mengxiao Zhang, Siyu Chen, Liwei Wang
### Network add-on
- [ICLR19][TOWARDS THE FIRST ADVERSARIALLY ROBUST NEURAL NETWORK MODEL ON MNIST](https://arxiv.org/abs/1805.09190) - Lukas Schott, Jonas Rauber, Matthias Bethge, Wieland Brendel
### Analysis of Adversarial Examples
- [ICLR19][ROBUSTNESS MAY BE AT ODDS WITH ACCURACY ](https://arxiv.org/abs/1805.12152) - Dimitris Tsipras, Shibani Santurkar, Logan Engstrom, Alexander Turner, Aleksander Madry
## Model Compression And Adversarial Robustness
- [ICLR19][COMBINATORIAL ATTACKS ON BINARIZED NEURAL NETWORKS](https://arxiv.org/abs/1810.03538) - Elias B. Khalil, Amrita Gupta, Bistra Dilkina
- [ICLR19][DEFENSIVE QUANTIZATION: WHEN EFFICIENCY MEETS ROBUSTNESS](https://openreview.net/pdf?id=ryetZ20ctX) - Ji Lin, Chuang Gan, Song Han
- [NeurIps2018][Sparse DNNs with Improved Adversarial Robustness](https://arxiv.org/abs/1810.09619) - Yiwen Guo, Chao Zhang, Changshui Zhang, Yurong Chen
