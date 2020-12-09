# GaintPandaSR
A Image Super-Resolution Codebase which implements all sota approaches.

## 1. Dataset
    Public Datasets:
       |- DIV2K
       |- Flicker2K
       |- DIV8K
       |- Set5

## 2. Code Role
We use the PEP8 style and we should add docstring to every new function. 

## 3. Folder structure
.
├── data
│   └── __init__.py
├── log
│   └── __init__.py
├── metrics
│   └── __init__.py
├── model
│   └── __init__.py
├── README.md
├── requirements.txt
├── tools
│   ├── demo.py
│   ├── test.py
│   └── train.py
└── utils
    └── __init__.py

## 4. Papers & Codes
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

