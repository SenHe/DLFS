# Disentangled Lifespan Face Synthesis
### [Project Page](https://senhe.github.io/projects/iccv_2021_lifespan_face/) | [Paper](https://arxiv.org/pdf/2108.02874.pdf)
<div align="center">
<img src=./fig/archi.png width="1200">
</div>

## Demo on Colab
[![Explore in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fgVAoxCSaqPkj0rUK4RmBh7GTQRqLNpE?usp=sharing)<br>

## Preparation

Please follow [this github](https://github.com/royorel/Lifespan_Age_Transformation_Synthesis) to prepare the environments and dataset.

## Training and Testing (link to the pretrained models in the colab)
training (please modify `--dataroot`, `--name`):
```
sh train_distan.sh
```
testing (please modify `--dataroot`, `--name`, `--which_epoch`, and `--checkpoing_dir`):
```
sh test_distan.sh
```

## Reference

If you find this repo helpful, please consider citing:

```
@inproceedings{he2021dlfs,
  title={Disentangled Lifespan Face Synthesis},
  author={He, Sen and Liao, Wentong and Yang, Michael and Song, Yi-Zhe and Rosenhahn, Bodo and Xiang, Tao},
  booktitle={ICCV},
  year={2021}
}
```

## Acknowledgements

This repository is based on [LFS](https://github.com/royorel/Lifespan_Age_Transformation_Synthesis).
