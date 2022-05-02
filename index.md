## Haozhe Liu

Haozhe Liu is working towards the MS degree in Computer Vision Institute, Shenzhen University (CS Rank 68 in USNews2020). He had published several papers on top-tier journals/conferences, including ICCV, IEEE trans on Image Processing, IEEE trans on Cybernetics, etc.. Haozhe Liu won First-Class Excellent Academic Scholarship in 2020 and China National Scholarship (**Rate<0.02%, Rank 1** in College of Computer Science and Software Engineering, SZU) in 2021. Currently, he is a member (internship) of [Jarvis Lab](https://jarvislab.tencent.com/), Tencent and a visiting student at AI Initiative, KAUST (supervised by Prof.[Juergen Schmidhuber](https://scholar.google.com/citations?user=gLnCTgIAAAAJ&hl=en)). He serves as a reviewer of the top-tier conferences, e.g. CVPR'2022, ICML'2022, ECCV'2022 and MICCAI'2022. His research interests include regularization, self-supervised learning, adversarial learning and reinforcement learning. 

---

\[Email\]:  haozhe.liu@kaust.edu.sa; liuhaozhe2019@email.szu.edu.cn

\[Google Scholar\] : https://scholar.google.com/citations?user=QX51P54AAAAJ

\[Curriculum Vitae (CV) \] :  [Download Link](./haozheliu.pdf) 

\[GitHub Page\]: https://github.com/HaozheLiu-ST

---
### News

**He will join AI Initiative, KAUST to pursue the PhD degree under the supervision of Juergen Schmidhuber!**

Our paper

He is invited as a reviewer for CVPR'2022, ICML'2022, ECCV'2022 and MICCAI'2022! 

[Our method (Group-wise Inhibition)](https://github.com/LinusWu/TENET_Training) is merged into the official benchmark of [ImageNet-C](https://github.com/hendrycks/robustness)! 

1 paper is submitted to ICML'2022, 2 papers are submitted to MICCAI'2022 and 3 papers are submitted to ECCV'2022. Best wishes for them!  

Our paper (Scene Consistency Representation Learning for Video Scene Sgementation) is accepted by CVPR'2022!

Our paper (Group-wise Inhibition based Feature Regularization for Robust Classification) is accepted by ICCV'2021!

---

### Selected Publications

**Liu, H.**, Wu, H., Xie, W., Liu, F., & Shen, L. (2021). Group-wise Inhibition based Feature Regularization for Robust Classification. _International Conference on Computer Vision (ICCV)_ 

**Liu, H.**, Liang, H., Hou, X., Wu, H., Liu, F., Shen, L. (2021) Manifold-preserved GANs. _arXiv preprint arXiv:2109.08955_. 

**Liu, H.**, Kong, Z., Ramachandra, R., Liu, F., Shen, L., & Busch, C. (2021). Taming Self-Supervised Learning for Presentation Attack Detection: In-Image De-Folding and Out-of-Image De-Mixing. _arXiv preprint arXiv:2109.04100_.

**Liu, H.**, Zhang, W., Liu, F., Wu, H.,& Shen, L. (2021). Fingerprint Presentation Attack Detector Using Global-Local Model. _IEEE Transactions on Cybernetics_.

Liu, F., **Liu, H**., Zhang, W., Liu, G., & Shen, L. (2021). One-Class Fingerprint Presentation Attack Detection Using Auto-Encoder Network. _IEEE Transactions on Image Processing, 30, 2394-2407_.

Zhang, W.\*, **Liu, H.**\*, Ramachandra, R.\*, Liu, F., Shen, L., & Busch, C. (2021). Face Presentation Attack Detection using Taskonomy Feature. _arXiv preprint arXiv:2111.11046_.(**\* Equal Contribution**)


### Research Samples

#### Group-wise Inhibition based Feature Regularization for Robust Classification 

![](./fig/group.png)

The convolutional neural network (CNN) is vulnerable to degraded images with even very small variations (e.g. corrupted and adversarial samples). One of the possible reasons is that CNN pays more attention to the most discriminative regions, but ignores the auxiliary features when learning, leading to the lack of feature diversity for final judgment. In our method, we propose to dynamically suppress significant activation values of CNN by group-wise inhibition, but not fixedly or randomly handle them when training. The feature maps with different activation distribution are then processed separately to take the feature independence into account. CNN is finally guided to learn richer discriminative features hierarchically for robust classification according to the proposed regularization. Our method is comprehensively evaluated under multiple settings, including classification against corruptions, adversarial attacks and low data regime. Extensive experimental results show that the proposed method can achieve signifi- cant improvements in terms of both robustness and generalization performances, when compared with the state-of-the-art methods. 

Accepted by _ICCV-2021_

[Code](https://github.com/LinusWu/TENET_Training) 

[Arxiv](https://arxiv.org/abs/2103.02152) 

[ICCV-Link](https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Group-Wise_Inhibition_Based_Feature_Regularization_for_Robust_Classification_ICCV_2021_paper.html)

---

#### Manifold-preserved GANs 

![](./fig/gan.png)

Generative Adversarial Networks (GANs) have been widely adopted in various fields. However, existing GANs generally are not able to preserve the manifold of data space, mainly due to the simple representation of discriminator for the real/generated data. To address such open challenges, this paper proposes Manifold-preserved GANs (MaF-GANs), which generalize Wasserstein GANs into high-dimensional form. Specifically, to improve the representation of data, the discriminator in MaF-GANs is designed to map data into a high-dimensional manifold. Furthermore, to stabilize the training of MaF-GANs, an operation with precise and universal solution for any K-Lipschitz continuity, called Topological Consistency is proposed. The effectiveness of the proposed method is justified by both theoretical analysis and empirical results. When adopting DCGAN as the backbone on CelebA (256×256), the proposed method achieved 12.43 FID, which outperforms the state-of-the-art model like Realness GAN (23.51 FID) by a large margin. 

_Code will be made publicly available_. 

[Arxiv](https://arxiv.org/abs/2109.08955)

---

### Research Experience

#### AI Initiative (KAUST) 
Visiting Student / Prospective PhD Student supervised by Prof. [Juergen Schmidhuber](https://scholar.google.com/citations?user=gLnCTgIAAAAJ&hl=en).

- Research Field:Reinforcement Learning; Upside-Down Reinforcement Learning; Generative Adversarial Task; Self-supervised Learning; Regularization

---

#### Jarvis Lab (Tencent) 
Internship supervised by Mentor: [Dr. Nanjun He](https://scholar.google.ch/citations?user=w3iS1G0AAAAJ&hl=en) & [Dr. Yuexiang Li](https://scholar.google.com/citations?user=WsKu4EMAAAAJ&hl=en), Leader: [Dr. Kai Ma](https://scholar.google.ch/citations?user=FSSXeyAAAAAJ&hl=en) and Director: [Dr. Yefeng Zheng](https://scholar.google.ch/citations?user=vAIECxgAAAAJ&hl=en) 
  
- Proposed Dynamic Feature Aggregation to improve the robustness against adversarial attacks, which is submitted to **ICML'2022**.

- Proposed offline entropy estimation to combat mode collapse, which is submitted to **ECCV'2022**. (This project is cooperated with AI Initiative, KAUST.)  

---

#### Norwegian Biometrics Laboratory (NTNU)
Visiting student supervised by  [Prof. Raghavendra Ramachandra](https://scholar.google.com/citations?user=OIYIrmIAAAAJ&hl=en) and [Prof. Christoph Busch](https://scholar.google.com/citations?user=qsopcXIAAAAJ&hl=en)

- Proposed a self-supervised learning based method for face and fingerprint presentation attack detection, which is submitted to **TIFS**.
- Proposed a face presentation attack detector based on the taskonomy features, which is submitted to **ECCV'2022**.

---

#### Computer Vision Insitute (SZU)
M.S. supervised by [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?hl=zh-CN&user=AZ_y9HgAAAAJ)
- Proposed a regularization method to imporve the robustness of CNN based models, which is accepted by **ICCV'2021** and open source.
- Proposed a Manifold-preserved GANs to mitigate the mode collapse and gradient exploding.
- Collected a famous presentation attack dataset based on OCT and **for the first time** established a one-class framework for OCT based PAD. This work is accepted by **IEEE TIP**
- Proposed a presentation attack detector using Global-Local model, which reaches over 90% in terms of TDR@FDR=1% on LivDet2017 **for the first time**. (Accepted by **IEEE TCYB**)
