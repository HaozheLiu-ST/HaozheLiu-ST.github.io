## Haozhe Liu

Haozhe Liu is currently working towards the MS degree in Computer Vision Institute  Shenzhen University (CS Rank 68 in USNews2020). He had published several papers on top-tier journals/conferences, including ICCV, IEEE trans on Image Processing, IEEE trans on Cybernetics, etc.. Haozhe Liu won First-Class Excellent Academic Scholarship in 2020 and China National Scholarship (**Rate<0.02%, Rank 1** in College of Computer Science and Software Engineering, SZU) in 2021. Currently, he is a member (internship) of [Jarvis Lab](https://jarvislab.tencent.com/), Tencent and a visiting student at Norwegian Biometrics Laboratory, Norwegian University of Science and Technology (NTNU). His research interests include regularization, self-supervised learning and adversarial learning,  especially focus on their applications to computer vision. **He is looking for a Ph.D position (ML/CV-related, 22 Fall). Please email Haozhe Liu if you are interested. (Oct. 6, 2021)**

Email: liuhaozhe2019 AT email DOT szu DOT edu DOT cn   |  [Google Scholar Link](https://scholar.google.com/citations?user=QX51P54AAAAJ&hl=zh-CN)    |  [Github Page](https://haozheliu-st.github.io/)

### Selected Publications

**Liu, H.**, Wu, H., Xie, W., Liu, F., & Shen, L. (2021). Group-wise Inhibition based Feature Regularization for Robust Classification. _International Conference on Computer Vision (ICCV)_ 

**Liu, H.**, Liang, H., Hou, X., Wu, H., Liu, F., Shen, L. (2021) Manifold-preserved GANs. arXiv preprint arXiv:2109.08955. 

**Liu, H.**, Kong, Z., Ramachandra, R., Liu, F., Shen, L., & Busch, C. (2021). Taming Self-Supervised Learning for Presentation Attack Detection: In-Image De-Folding and Out-of-Image De-Mixing. arXiv preprint arXiv:2109.04100.

**Liu, H.**, Zhang, W., Liu, F., Wu, H.,& Shen, L. (2021). Fingerprint Presentation Attack Detector Using Global-Local Model. _IEEE Transactions on Cybernetics_.

Liu, F., **Liu, H**., Zhang, W., Liu, G., & Shen, L. (2021). One-Class Fingerprint Presentation Attack Detection Using Auto-Encoder Network. _IEEE Transactions on Image Processing, 30, 2394-2407_.

Liu, F., Shen, C., **Liu, H.**, Liu, G., Liu, Y., Guo, Z., & Wang, L. (2020). A flexible touch-based fingerprint acquisition device and a benchmark database using optical coherence tomography. _IEEE Transactions on Instrumentation and Measurement_, 69(9), 6518-6529.

Lin, L.\*, **Liu, H.** \*, Zhang, W., Liu, F., & Lai, Z. (2021, August). Finger Vein Verification using Intrinsic and Extrinsic Features. In 2021 _IEEE International Joint Conference on Biometrics (IJCB) (pp. 1-7)_. (* Equal Contribution)

Zhang, W., **Liu, H.**, & Liu, F. (2021, July). Fingerprint Presentation Attack Detection by Learning in Frequency Domain. In 2021 IEEE 2nd International Conference on Pattern Recognition and Machine Learning (PRML) (pp. 183-189). IEEE. (Best Oral Presentation)

Liu, F., **Liu, H.**, Zhang, W., Chen, J., Shen, L. & Wang, L. . A robust roi extraction method for biometrics using adversarial structure. _Acta Automatica Sinica_, 2020, 46(x): 1−14 doi: 10.16383/j.aas.c200156 

### Research Samples

#### Group-wise Inhibition based Feature Regularization for Robust Classification 

![](./fig/group.png)

The convolutional neural network (CNN) is vulnerable to degraded images with even very small variations (e.g. corrupted and adversarial samples). One of the possible reasons is that CNN pays more attention to the most discriminative regions, but ignores the auxiliary features when learning, leading to the lack of feature diversity for final judgment. In our method, we propose to dynamically suppress significant activation values of CNN by group-wise inhibition, but not fixedly or randomly handle them when training. The feature maps with different activation distribution are then processed separately to take the feature independence into account. CNN is finally guided to learn richer discriminative features hierarchically for robust classification according to the proposed regularization. Our method is comprehensively evaluated under multiple settings, including classification against corruptions, adversarial attacks and low data regime. Extensive experimental results show that the proposed method can achieve signifi- cant improvements in terms of both robustness and general- ization performances, when compared with the state-of-the-art methods. 

[Code](https://github.com/LinusWu/TENET_Training) 

[Arxiv](https://arxiv.org/abs/2103.02152) 

---

#### Manifold-preserved GANs 

![](./fig/gan.png)

Generative Adversarial Networks (GANs) have been widely adopted in various fields. However, existing GANs generally are not able to preserve the manifold of data space, mainly due to the simple representation of discriminator for the real/generated data. To address such open challenges, this paper proposes Manifold-preserved GANs (MaF-GANs), which generalize Wasserstein GANs into high-dimensional form. Specifically, to improve the representation of data, the discriminator in MaF-GANs is designed to map data into a high-dimensional manifold. Furthermore, to stabilize the training of MaF-GANs, an operation with precise and universal solution for any K-Lipschitz continuity, called Topological Consistency is proposed. The effectiveness of the proposed method is justified by both theoretical analysis and empirical results. When adopting DCGAN as the backbone on CelebA (256×256), the proposed method achieved 12.43 FID, which outperforms the state-of-the-art model like Realness GAN (23.51 FID) by a large margin. 

_Code will be made publicly available_. 

[Arxiv](https://arxiv.org/abs/2109.08955)

---

#### Taming Self-Supervised Learning for Presentation Attack Detection: In-Image De-Folding and Out-of-Image De-Mixing

![](./fig/ssl.png)

Biometric systems are vulnerable to the Presentation Attacks (PA) performed using various Presentation Attack Instruments (PAIs). Even though there are numerous Presentation Attack Detection (PAD) techniques based on both deep learning and hand-crafted features, the generalization of PAD for unknown PAI is still a challenging problem. The common problem with existing deep learning-based PAD tech- niques is that they may struggle with local optima, resulting in weak generalization against different PAs. In this work, we propose to use self-supervised learning to find a reasonable initialization against local trap, so as to improve the generalization ability in detecting PAs on the biometric system. The proposed method, denoted as IF-OM, is based on a global-local view coupled with De-Folding and De-Mixing to derive the task-specific representation for PAD.During De-Folding, the proposed technique will learn region-specific features to represent samples in a local pattern by explicitly maximizing cycle consistency. While, De-Mixing drives detectors to obtain the instance-specific features with global information for more comprehensive representation by maximizing topo- logical consistency. Extensive experimental results show that the proposed method can achieve significant improvements in terms of both face and fingerprint PAD in more complicated and hybrid datasets, when compared with the state-of- the-art methods. Specifically, when training in CASIA-FASD and Idiap Replay-Attack, the proposed method can achieve 18.60% Equal Error Rate (EER) in OULU-NPU and MSU-MFSD, exceeding baseline performance by 9.54%. 

_Code will be made publicly available_. 

[Arxiv](https://arxiv.org/abs/2109.04100) 

### Research Experience

#### Jarvis Lab (Tencent) 
Internship supervised by Mentor: [Dr. Nanjun He](https://scholar.google.ch/citations?user=w3iS1G0AAAAJ&hl=en) & [Dr. Yuexiang Li](https://scholar.google.com/citations?user=WsKu4EMAAAAJ&hl=en), Leader: [Dr. Kai Ma](https://scholar.google.ch/citations?user=FSSXeyAAAAAJ&hl=en) and Director: [Dr. Yefeng Zheng](https://scholar.google.ch/citations?user=vAIECxgAAAAJ&hl=en) 
  - Defense adversarial attacks from a view of interpolation.
  - Investigated the application of manifold theory in self-supervised learning.

---

#### Norwegian Biometrics Laboratory (NTNU)
Visiting student supervised by  [Prof. Raghavendra Ramachandra](https://scholar.google.com/citations?user=OIYIrmIAAAAJ&hl=en) and [Prof. Christoph Busch](https://scholar.google.com/citations?user=qsopcXIAAAAJ&hl=en)

- Proposed a self-supervised learning based method for face and fingerprint presentation attack detection, which is submitted to **AAAI 2021**.
- Proposed a face presentation attack detector based on the multimodal representation, which is prepared to submit to **CVPR 2022**.

---

#### Computer Vision Insitute (SZU)
M.S. supervised by [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?hl=zh-CN&user=AZ_y9HgAAAAJ)
- Proposed a regularization method to imporve the robustness of CNN based models, which is accepted by **ICCV 2021** and open source.
- Proposed a Manifold-preserved GANs to mitigate the mode collapse and gradient exploding, which is prepared to submit to **CVPR 2022**.
- Collected a famous presentation attack dataset based on OCT and **for the first time** established a one-class framework for OCT based PAD.
- Proposed a presentation attack detector using Global-Local model, which reaches over 90% in terms of TDR@FDR=1% on LivDet2017 **for the first time**.


### Education

B.S. in AI Lab, Shaanxi University of Science and Technology under the supervision of Dr. Yong Qi

- National University Big Data Application Innovation Competition in Northwest, First Place in 2018
- National University Big Data Application Innovation Competition, Second Place in 2018
- Undergraduate thesis was awarded the first prize of excellent graduation design (Thesis) of SUST in 2019

---

M.S. in Computer Vision Institute (CVI), Shenzhen University (SZU) under the supervision of [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?hl=zh-CN&user=AZ_y9HgAAAAJ)

- China National Scholarship (Rate<0.02%, Rank 1 in SZU) in 2021 
- Excellent Academic Scholarship, First Class in 2020
- Excellent Academic Scholarship, Second Class in 2020
