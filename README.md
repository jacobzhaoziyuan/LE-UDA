

<div align="center">

# LE-UDA: Label-efficient unsupervised domain adaptation for medical image segmentation

[![MICCAI2022](https://img.shields.io/badge/arXiv-2203.12454-blue)](https://ieeexplore.ieee.org/document/9919170)
[![MICCAI2022](https://img.shields.io/badge/Journal-TMI2022-green)](https://ieeexplore.ieee.org/document/9919170)



</div>

Pytorch implementation of our method for IEEE TMI 2022 paper: "LE-UDA: Label-efficient unsupervised domain adaptation for medical image segmentation". (Our code will be release soon.)

## Abstract
While deep learning methods hitherto have achieved considerable success in medical image segmentation, they are still hampered by two limitations: (i) reliance on large-scale well-labeled datasets, which are difficult to curate due to the expert-driven and time-consuming nature of pixel-level annotations in clinical practices, and (ii) failure to generalize from one domain to another, especially when the target domain is a different modality with severe domain shifts. Recent unsupervised domain adaptation (UDA) techniques leverage abundant labeled source data together with unlabeled target data to reduce the domain gap, but these methods degrade significantly with limited source annotations. In this study, we address this underexplored UDA problem, investigating a challenging but valuable realistic scenario, where the source domain not only exhibits domain shift w.r.t. the target domain but also suffers from label scarcity. In this regard, we propose a novel and generic framework called “Label-Efficient Unsupervised Domain Adaptation” (LE-UDA). In LE-UDA, we construct self-ensembling consistency for knowledge transfer between both domains, as well as a self-ensembling adversarial learning module to achieve better feature alignment for UDA. To assess the effectiveness of our method, we conduct extensive experiments on two different tasks for cross-modality segmentation between MRI and CT images. Experimental results demonstrate that the proposed LE-UDA can efficiently leverage limited source labels to improve cross-domain segmentation performance, outperforming state-of-the-art UDA approaches in the literature.

<p align="center">
<img src="https://github.com/jacobzhaoziyuan/Meta-Hallucinator/blob/main/assets/archi.png" width="700">
</p>







## Citation
If you find the codebase useful for your research, please cite the paper:
```
@inproceedings{zhao2022meta,
  title={Meta-hallucinator: Towards Few-Shot Cross-Modality Cardiac Image Segmentation},
  author={Zhao, Ziyuan and Zhou, Fangcheng and Zeng, Zeng and Guan, Cuntai and Zhou, S. Kevin},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={128--139},
  year={2022},
  organization={Springer}
}
```
