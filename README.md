

<div align="center">

# LE-UDA: Label-efficient unsupervised domain adaptation for medical image segmentation

[![MICCAI2022](https://img.shields.io/badge/arXiv-2203.12454-blue)](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_13)
[![MICCAI2022](https://img.shields.io/badge/Journal-TMI2022-green)](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_13)



</div>

Pytorch implementation of our method for IEEE TMI 2022 paper: "LE-UDA: Label-efficient unsupervised domain adaptation for medical image segmentation". (Our code will be release soon.)

## Abstract
Domain shift and label scarcity heavily limit deep learning applications to various medical image analysis tasks. Unsupervised domain adaptation (UDA) techniques have recently achieved promising cross-modality medical image segmentation by transferring knowledge from a label-rich source domain to an unlabeled target domain. However, it is also difficult to collect annotations from the source domain in many clinical applications, rendering most prior works suboptimal with the label-scarce source domain, particularly for few-shot scenarios, where only a few source labels are accessible. To achieve efficient few-shot cross-modality segmentation, we propose a novel transformation-consistent meta-hallucination framework, meta-hallucinator, with the goal of learning to diversify data distributions and generate useful examples for enhancing cross-modality performance. In our framework, hallucination and segmentation models are jointly trained with the gradient-based meta-learning strategy to synthesize examples that lead to good segmentation performance on the target domain. To further facilitate data hallucination and cross-domain knowledge transfer, we develop a self-ensembling model with a hallucination-consistent property. Our meta-hallucinator can seamlessly collaborate with the meta-segmenter for learning to hallucinate with mutual benefits from a combined view of meta-learning and self-ensembling learning. Extensive studies on MM-WHS 2017 dataset for cross-modality cardiac segmentation demonstrate that our method performs favorably against various approaches by a lot in the few-shot UDA scenario.

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
