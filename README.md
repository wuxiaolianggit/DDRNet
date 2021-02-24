# The official implementation of "Deep Dual-resolution Networks for Real-time and Accurate Semantic Segmentation of Road Scenes"
 
![avatar](./figs/performance.png)
**Achieve state-of-the-art trade-off between accuracy and speed on cityscapes and camvid, without using inference acceleration and extra data!** 

![avatar](./figs/DDRNet_seg.png)
The overall architecture of our methods.

![avatar](./figs/DAPPM.png)
The details of "Deep Aggregation Pyramid Pooling Module(DAPPM)".

# Usage

Currently, this repo contains the model codes and pretrained models for classification and semantic segmentation. You can refer to [
HRNet-Semantic-Segmentation-pytorch-v1.1](https://github.com/HRNet/HRNet-Semantic-Segmentation/tree/pytorch-v1.1) for training and testing our models locally. We will release the whole train and test codes based on it later.

# Notice

There are some basic training tricks you should employ to reproduce our results including class balance sample, ohem, crop size of 1024x1024. More details can be found in the [paper](https://arxiv.org/abs/2101.06085).

# Pretrained models

DDRNet_23_slim on ImageNet(top-1 error:29.8):

DDRNet_23 on ImageNet(top-1 error:24.1):

DDRNet_39 on ImageNet(top-1 error:22.7):

DDRNet_23_slim on Cityscapes(val mIoU:77.8): [link](https://drive.google.com/file/d/1d_K3Af5fKHYwxSo8HkxpnhiekhwovmiP/view?usp=sharing)

DDRNet_23 on Cityscapes(val mIoU:79.5): [link](https://drive.google.com/file/d/16viDZhbmuc3y7OSsUo2vhA7V6kYO0KX6/view?usp=sharing)

## Citation
If you find this repo is useful for your research, Please consider citing our paper:

```
@article{hong2021deep,
  title={Deep Dual-resolution Networks for Real-time and Accurate Semantic Segmentation of Road Scenes},
  author={Hong, Yuanduo and Pan, Huihui and Sun, Weichao and Jia, Yisong and others},
  journal={arXiv preprint arXiv:2101.06085},
  year={2021}
}
```
