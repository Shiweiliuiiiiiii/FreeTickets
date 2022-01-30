# [ICLR 2022] Deep Ensembling with No Overhead for either Training or Testing: The All-Round Blessings of Dynamic Sparsity

<img src="https://github.com/Shiweiliuiiiiiii/FreeTickets/blob/main/FreeTickets.png" width="800" height="300">


**Deep Ensembling with No Overhead for either Training or Testing: The All-Round Blessings of Dynamic Sparsity**<br>
Shiwei Liu, Tianlong Chen, Zahra Atashgahi, Xiaohan Chen, Ghada Sokar, Elena Mocanu, Mykola Pechenizkiy, Zhangyang Wang, Decebal Constantin Mocanu<br>

https://openreview.net/forum?id=RLtqs6pzj1-

Abstract: *The success of deep ensembles on improving predictive performance, uncertainty, and out-of-distribution robustness has been extensively demonstrated in the machine learning literature. Albeit the promising results, naively training multiple deep neural networks and combining their predictions at test lead to prohibitive computational costs and memory requirements. Recently proposed efficient ensemble approaches reach the performance of the traditional deep ensembles with significantly lower costs. However, the training resources required by these approaches are still at least the same as training a single dense model. In this work, we draw a unique connection between sparse neural network training and deep ensembles, yielding a novel efficient ensemble learning framework called $FreeTickets$. Instead of training multiple dense networks and averaging them, we directly train sparse subnetworks from scratch and extract diverse yet accurate subnetworks during this efficient, sparse-to-sparse training. Our framework, $FreeTickets$, is defined as the ensemble of these relatively cheap sparse subnetworks. Despite being an ensemble method, $FreeTickets$ has even fewer parameters and training FLOPs compared to a single dense model. This seemingly counter-intuitive outcome is due to the ultra training efficiency of dynamic sparse training. $FreeTickets$ improves over the dense baseline in the following criteria: prediction accuracy, uncertainty estimation, out-of-distribution (OoD) robustness, and training/inference efficiency. Impressively, $FreeTickets$ outperforms the naive deep ensemble with ResNet50 on ImageNet using around only $1/5$ training FLOPs required by the latter.*

This code base is created by Shiwei Liu s.liu3@tue.nl during his Ph.D. at Eindhoven University of Technology.

## Requirements
Python 3.6, PyTorch v1.5.1, and CUDA v10.2.

