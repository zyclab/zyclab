+++
title = "2024 13th International Conference on Computing and Pattern Recognition"
date = 2024-10-25
tags = ["计算科学与人工智能"]
categories = ["学术会议"]
authors = ["郑礼东","朱起峰"]
banner = "img/banners/ICCPR.png"
+++

石河子大学模式识别与机器学习实验室在 ICCPR2024 国际会议上取得重要学术成果，实验室两篇创新性论文被会议录用并作报告，展现了团队在离线签名验证领域的深入研究。硕士研究生郑礼东、朱起峰在导师郑煜辰副教授指导下，分别围绕签名局部特征建模与深度特征子空间优化展开探索。

郑礼东提出的签名局部特征重建模块（SLFRM）创新性地设计了局部空间特征单元（LSFU）与局部空间注意力单元（LSAU），通过动态加权机制强化签名图像中判别性局部差异的学习，解决了传统方法对细微特征捕捉不足的难题。朱起峰的研究则聚焦于深度架构中最优子空间的发现，通过随机高维投影与线性判别分析（LDA）的协同优化，实现了签名特征在任意子空间下的判别性缩放，为复杂场景下的身份认证提供了新思路。

会议期间，实验室成员与国内外学者就深度学习、特征表示等前沿问题展开深入交流，充分展示了团队严谨的学术态度与创新活力。此次成果不仅体现了实验室在模式识别领域的科研实力，也为后续跨模态生物特征识别研究奠定了重要基础。

---

## 会议发表内容

### SLFRM: A Novel Signature Local Feature Reconstruction Module for Offline Signature Verification

硕士研究生 **郑礼东** 在会议中报告其论文 **《SLFRM: A Novel Signature Local Feature Reconstruction Module for Offline Signature Verification》** 相关内容。在他的报告中提出了一种新颖的签名局部特征重建模块（SLFRM），该模块为特征图分配权重，以便捕捉并强调不同签名在局部空间区域内的细微差异。具体而言，所提出的签名局部特征重建模块由两个单元组成：局部空间特征单元（LSFU）和局部空间注意力单元（LSAU）。局部空间特征单元用于提取签名的感受野空间特征，而局部空间注意力单元则用于获取签名的感受野空间注意力图。基于上述两个单元，然后通过标准的卷积操作，生成最终的局部重建特征。因此，所提出的签名局部特征重建模块会对输入特征进行权重重新分配，将更高的权重赋予那些具有更强判别力的特征。这一策略确保了模型在特征学习阶段优先学习细微差异特征。

{{< figure src="/img/posts/ICCPR2024/lidong.png"
           title="郑礼东"
           caption="参会人员"
           width="60%"
           class="caption-center" >}}
<!-- ![郑礼东](/img/posts/ICCPR2024/lidong.png) -->

### Discovering Optimal Subspaces in Deep Architectures for Offline Signature Verification

硕士研究生 **朱起峰** 在会议中报告其论文 **《Discovering Optimal Subspaces in Deep Architectures for Offline Signature Verification》** 相关内容。在他的报告中提出了一种新颖的框架，该框架通过拉伸和降维深度特征来控制特征的维度，以获取最佳特征。具体来说，深度特征可以通过一个高维投影矩阵进行拉伸，该矩阵的元素是从标准正态分布中随机采样得到的，以此获得更具判别性的表示，然后进一步通过线性判别分析（LDA）进行降维，从而更有效地捕捉不同签名者之间的细微差异。通过这种方式，所学习到的特征可以被缩放至任何最优子空间。

{{< figure src="/img/posts/ICCPR2024/qifeng.png" 
           title="朱起峰" 
           caption="参会人员" 
           width="60%" 
           class="caption-center" >}}
<!-- ![朱起峰](/img/posts/ICCPR2024/qifeng.png) -->

## 会议收获

在参会过程中实验室参会人员积极与其他参会人员交流，充分展现了石河子大学模式识别与机器学习实验室的优良学风和学术氛围。
