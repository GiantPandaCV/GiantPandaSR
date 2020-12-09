# GaintPandaSR
A Image Super-Resolution Codebase which implements all sota approaches.

## 1. Dataset
    Public Datasets:
       |- DIV2K
       |- Flicker2K
       |- DIV8K
       |- Set5

## 2. Code Role
This project follows the PEP8 and every function should have their own docstring-like annotations. 

## 3. TODO
Limited by the computational ability of existing devices, we trained our network on DIV2K and we present all the results. 

## 4. Folder structures

├── data
├── log
├── metrics
├── model
├── README.md
├── requirements.txt
└── tools
    ├── demo.py
    ├── test.py
    └── train.py

## 5. paper list

*Name* | *Summary* | *Paper* | *Code*
:---: | :---: | :---: | :---:
**2015**    | | |
 SRCNN      | *Image Super-Resolution Using Deep Convolutional Networks* | [[arXiv]](https://arxiv.org/abs/1501.00092) | [[~~code~~]](./models/SRCNN)
**2016**    | | |
 SRGAN      | *Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network* | [[arXiv]](https://arxiv.org/abs/1609.04802) | [[~~code~~]](./models/SRGAN)
 FSRGAN     | *Accelerating the Super-Resolution Convolutional Neural Network* | [[arXiv]](https://arxiv.org/abs/1608.00367) | [[~~code~~]](./models/FSRGAN)
 EnhanceNet | *Single Image Super-Resolution Through Automated Texture Synthesis* | [[arXiv]](https://arxiv.org/abs/1612.07919) | [[~~code~~]](./models/ENet)
**2017**    | | |
 LapSRN     | *Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution* | [[arXiv]](https://arxiv.org/abs/1704.03915) | [[~~code~~]](./models/LapSRN)
 EDSR       | *Enhanced Deep Residual Networks for Single Image Super-Resolution* | [[arXiv]](https://arxiv.org/abs/1707.02921) | [[~~code~~]](./models/EDSR)
**2018**    | | |
 RCAN       | *Image Super-Resolution Using Very Deep Residual Channel Attention Networks* | [[arXiv]](https://arxiv.org/abs/1807.02758) | [[~~code~~]](./models/RCAN)
 ESRGAN     | *Enhanced SRGAN. Champion PIRM Challenge on Perceptual Super-Resolution* | [[arXiv]](https://arxiv.org/abs/1809.00219) | [[~~code~~]](./models/ESRGAN/)
 FEQE       | *Fast and Efficient Image Quality Enhancement via Desubpixel Convolutional Neural Networks* | [[ECCV]](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Vu_Fast_and_Efficient_Image_Quality_Enhancement_via_Desubpixel_Convolutional_Neural_ECCVW_2018_paper.pdf) | [[~~code~~]](./models/FEQE)
 IDN        | *Fast and Accurate Single Image Super-Resolution via Information Distillation Network* | [[ECCV]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hui_Fast_and_Accurate_CVPR_2018_paper.pdf) | [[~~code~~]](./models/IDN)
**2019**    | | |
 NNTSR      | *Image Super-Resolution by Neural Texture Transfer* | [[arXiv]](https://arxiv.org/abs/1903.00834) | [[~~code~~]]()
