# Instant Adversarial Purification with Adversarial Consistency Distillation (CVPR2025)
## [Paper (arXiv)](https://arxiv.org/abs/2408.17064) 

Official Implementation for CVPR 2025 paper Instant Adversarial Purification with Adversarial Consistency Distillation.

![teaser](asset/teaser.png)


**Stable Diffusion:** Our model is developed by distilling Stable Diffusion v1.5 with a special LCM LoRA objective.
## Training objective
![obj](asset/pipeline_l.png)

---
## Train
Once you have prepared the data, you can train the model using the following command. 

```
bash train_lora.sh
```
---
## Evaluation
Evaluation code for ImageNet is provided.

```
bash test.sh
```
---
## Purification pipeline
![more](asset/pipeline_r.png)

All code run on NVIDIA L40 with cuda 12.4

## Checkpoint

https://drive.google.com/drive/folders/1bemjyZ4NyTeh9-0awkYdJ1jKH712LJ5y?usp=share_link

## Citation
Consider cite us if you find our paper is useful in your research :).
```
@InProceedings{Lei_2025_CVPR,
    author    = {Lei, Chun Tong and Yam, Hon Ming and Guo, Zhongliang and Qian, Yifei and Lau, Chun Pong},
    title     = {Instant Adversarial Purification with Adversarial Consistency Distillation},
    booktitle = {Proceedings of the Computer Vision and Pattern Recognition Conference (CVPR)},
    month     = {June},
    year      = {2025},
    pages     = {24331-24340}
}
```
