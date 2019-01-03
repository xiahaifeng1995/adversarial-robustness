# adversarial robustness paper
本文档主要收集近期顶会上有关对抗样本的论文。
## Attack
- [ICLR19][A Frank-Wolfe Framework For Efficient And Effective Adversarial Attacks](https://arxiv.org/abs/1811.10828) - Jinghui Chen, Jinfeng Yi, Quanquan Gu
## Defense
> Currently, the defenses against the adversarial attacks are being developed along three main directions: (for details,read [this paper](https://arxiv.org/pdf/1801.00553.pdf))
>   1) Using modified training during learning or modified input during testing. 
>   2) Modifying networks, e.g. by adding more layers/subnetworks, changing loss/activation functions etc.
>   3) Using external models as network add-on when classifying unseen examples.
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
- [ICLR10][PEERNETS: EXPLOITING PEER WISDOM AGAINST ADVERSARIAL ATTACKS](https://arxiv.org/abs/1806.00088) - Jan Svoboda, Jonathan Masci, Federico Monti, Michael M. Bronstein, Leonidas Guibas
- [ICLR19)[TRAINING FOR FASTER ADVERSARIAL ROBUSTNESS VERIFICATION VIA INDUCING RELU STABILITY](https://arxiv.org/abs/1809.03008) - Kai Y. Xiao, Vincent Tjeng, Nur Muhammad Shafiullah, Aleksander Madry




### Network add-on
