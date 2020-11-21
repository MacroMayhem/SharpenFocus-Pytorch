# Sharpen Focus: Learning With Attention Separability and Consistency
## A Pytorch implementation

```diff
- Unofficial repository
```

```diff
- Work in progress.
```
There might be errors in the code please use it with caution. I'll be updating the results on CIFAR-10, CIFAR-100 and STL-10 as I get some time.


## Results

| Dataset | CIFAR-10  | CIFAR-100  |  STL-10 |
|:-------:|:---------:|:----------:|:-------:|
|Resnet-18|   94.25   |     --     |  81.85  |
|SFocus-18|   94.16   |    71.3    |  82.77  |


### Requirements

`Pytorch`

### Usage

`python main.py --dataset cifar10 --batch-size 128 --prefix run0 --epochs 300 --milestones 75 150 225`


### Acknowledgement
This work is built upon the following repositories:

1. [CBAM](https://github.com/Jongchan/attention-module)
2. [GAIN](https://github.com/ngxbac/GAIN)

### Bibtex

Paper
```
@InProceedings{Wang_2019_ICCV,
author = {Wang, Lezi and Wu, Ziyan and Karanam, Srikrishna and Peng, Kuan-Chuan and Singh, Rajat Vikram and Liu, Bo and Metaxas, Dimitris N.},
title = {Sharpen Focus: Learning With Attention Separability and Consistency},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
} 
```
