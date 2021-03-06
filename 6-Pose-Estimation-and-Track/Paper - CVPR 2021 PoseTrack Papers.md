
## 2D Human Pose Estimation CVPR 2021 

1. **Rethinking the Heatmap Regression for Bottom-up Human Pose Estimation**

   **[paper](https://arxiv.org/abs/2012.15175) [code](https://github.com/greatlog/SWAHR-HumanPose) [解读](https://mp.weixin.qq.com/s/lL1cz_L523TSdYJFfHA2lQ)**

   本文提出了一种尺度自适应热力图回归，可以根据人体大小自适应生成构造标签所需的标准差，从而使得模型对不同尺度的人体更加鲁棒；并提出权重自适应回归平衡正负样本，进一步挖掘尺度自适应热力图回归效果。最终在自底向上人体姿态估计中取得了目前最先进性能。

   https://blog.csdn.net/qq_19784349/article/details/115870451

2. **Bottom-Up Human Pose Estimation Via Disentangled Keypoint Regression** 

   **[paper](https://arxiv.org/abs/2012.15175) [code](https://github.com/HRNet/DEKR)**

   [解构式关键点回归 （DEKR）](https://blog.csdn.net/moxibingdao/article/details/118257186)

   密集关键点回归框架对于每个像素点都会通过回归一个 2K 维度的偏移值向量来估计一个姿态。这个偏移值向量图是通过一个关键点回归模块处理骨干网络得到的特征而获得的。将骨干网络生成的特征分为K份，每份送入一个单独的分支。每个分支用各自的自适应卷积去学习一种关键点的特征，最后用一个卷积输出一个这种关键点的二维偏移值向量。在图中，为了表示方便，假设了 K=3，事实上，在 COCO 数据集的实验中，K 为17。

3. **Lite-HRNet: A Lightweight High-Resolution Network** 

   **[paper](https://arxiv.org/abs/2104.06403) [code](https://github.com/HRNet/)**
   [Lite-HRNet：轻量级HRNet，FLOPs大幅下降](https://mp.weixin.qq.com/s/4V6EOYVSybMR9oxpcsWv9w)

   - 将Shuffle Block与Small HRNet融合，设计出Naive Lite-HRNet；
   - 提出了Conditional Channel Weighting操作，该操作能够以更小的计算量实现卷积的功能；
   - 在Naive Lite-HRNet基础上，使用Conditional Channel Weighting操作代替Shuffle Block中的卷积，得到Lite-HRNet；
   - 通过实验证明了在人体姿态估计、语义分割领域中，相比其他轻量级网络，Lite-HRNet有更低的计算量和更高的性能。

4. **Deep Dual Consecutive Network for Human Pose Estimation**

   **[paper](https://arxiv.org/abs/2103.07254) [code](https://github.com/Pose-Group/DCPose)**

5. **Body Meshes as Points**

   **[paper](https://arxiv.org/abs/2105.02467) [code](https://github.com/jfzhang95/BMP)**

6. **Unsupervised Human Pose Estimation through Transforming Shape Templates**

   **[paper](https://arxiv.org/abs/2105.04154) [project](https://infantmotion.github.io/)**

   基于形状模板变换的无监督人体姿态估计

7. **When Human Pose Estimation Meets Robustness: Adversarial Algorithms and Benchmark**

   **[paper](https://arxiv.org/abs/2105.06152)**

8. **Learning Dynamics via Graph Neural Networks for Human Pose Estimation and Tracking**

   **[paper](https://arxiv.org/abs/2106.03772)**

9. **FCPose: Fully Convolutional Multi-Person Pose Estimation with Dynamic Instance-Aware Convolutions**
   **[paper](https://arxiv.org/abs/2105.14185) [code](https://git.io/AdelaiDet)**
   FCPose，无 ROI 和无分组的端到端可训练人体姿势估计器可以达到更好的准确性和速度，在 COCO 数据集上，使用 DLA-34 主干的 FCPose 实时版本比 Mask R-CNN（ResNet-101）快 4.5 倍（41.67FPS vs. 9.26FPS)，同时实现了性能的提高。与最近的自上而下和自下而上的方法相比，FCPose 还实现了更好的速度/准确度权衡。

---

**人体关键点检测**

​	**Regressive Domain Adaptation for Unsupervised Keypoint Detection**

​	[paper](https://arxiv.org/abs/2103.06175) [code](https://github.com/thuml/Transfer-Learning-Library)

class="cm-formatting cm-formatting-list cm-formatting-list-ol cm-list-1"

