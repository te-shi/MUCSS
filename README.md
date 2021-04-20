# MUCSS
Multiple Unsupervised Constraints for cross-domain remote sensing image Semantic Segmentation(MUCSS)

## Title
Learning deep semantic segmentation network under multiple weakly-supervised constraints for cross-domain remote sensing image semantic segmentation [\[link\]](https://www.sciencedirect.com/science/article/pii/S0924271621000423)

## Abstract

Due to its wide applications, remote sensing (RS) image semantic segmentation has attracted increasing research interest in recent years. Benefiting from its hierarchical abstract ability, the deep semantic segmentation network (DSSN) has achieved tremendous success on RS image semantic segmentation and has gradually become the mainstream technology. However, the superior performance of DSSN highly depends on two conditions: (I) massive quantities of labeled training data exist; (II) the testing data seriously resemble the training data. In actual RS applications, it is difficult to fully meet these conditions due to the RS sensor variation and the distinct landscape variation in different geographic locations. To make DSSN fit the actual RS scenario, this paper exploits the cross-domain RS image semantic segmentation task, which means that DSSN is trained on one labeled dataset (i.e., the source domain) but is tested on another varied dataset (i.e., the target domain). In this setting, the performance of DSSN is inevitably very limited due to the data shift between the source and target domains. To reduce the disadvantageous influence of data shift, this paper proposes a novel objective function with multiple weakly-supervised constraints to learn DSSN for cross-domain RS image semantic segmentation. Through carefully examining the characteristics of cross-domain RS image semantic segmentation, multiple weakly-supervised constraints include the weakly-supervised transfer invariant constraint (WTIC), weakly-supervised pseudo-label constraint (WPLC) and weakly-supervised rotation consistency constraint (WRCC). Specifically, DualGAN is recommended to conduct unsupervised style transfer between the source and target domains to carry out WTIC. To make full use of the merits of multiple constraints, this paper presents a dynamic optimization strategy that dynamically adjusts the constraint weights of the objective function during the training process. With full consideration of the characteristics of the cross-domain RS image semantic segmentation task, this paper gives two cross-domain RS image semantic segmentation settings: (I) variation in geographic location and (II) variation in both geographic location and imaging mode. Extensive experiments demonstrate that our proposed method remarkably outperforms the state-of-the-art methods under both of these settings.

## Dataset

The RS image dataset for cross-domain semantic segmentation can be downloaded via [Google Drive](https://drive.google.com/file/d/1amV--tjtjBMUscUVBqXxXws_vBCo-QdV/view?usp=sharing) or [BaiduDisk (Acess Code: vaam)](https://pan.baidu.com/s/1Ob12TozQ2Xjcm3rcv7LuRA).

Label mapping:

| Id | Category            | R,G,B         |
|----|---------------------|---------------|
| 1  | Clutter background  | 255, 0, 0     |
| 2  | Impervious surfaces | 255, 255, 255 |
| 3  | Car                 | 255, 255, 0   |
| 4  | Tree                | 0, 255, 0     |
| 5  | Low vegetation      | 0, 255, 255   |
| 6  | Building            | 0, 0, 255     |

## Citation

If our work has any help to you, please cite as follows:

```
@article{li2021learning,
  title={Learning deep semantic segmentation network under multiple weakly-supervised constraints for cross-domain remote sensing image semantic segmentation},
  author={Li, Yansheng and Shi, Te and Zhang, Yongjun and Chen, Wei and Wang, Zhibin and Li, Hao},
  journal={ISPRS Journal of Photogrammetry and Remote Sensing},
  volume={175},
  pages={20--33},
  year={2021},
  publisher={Elsevier}
}
```

## Contact

te.shi1997@gmail.com

