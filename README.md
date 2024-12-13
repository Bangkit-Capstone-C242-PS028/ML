# DermaScan Lesion Recognition 

## Dependency
- python
- numpy
- matplotlib
- pytorch
- torchvision
- opencv
- tensorflow
- joblib

## Workflow
<div align="center">
  <img src="https://raw.githubusercontent.com/Bangkit-Capstone-C242-PS028/.github/refs/heads/main/profile/assets/Dermascan_ML_Workflow.png" alt="ML Workflow" style="width: 100%;">
</div>

## Dataset Preparation
| Dataset | Download |
| ---     | ---   |
| HAM10000 | [https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000]() |


## Use
- open jupyter notebook or google colab
- run train.ipynb to train the lesion classification model or to tune hyperparameter
- run grad_cam_ready.ipynb to classify skin lesion and show GradCAM

## Directory Hierarchy
```
|—— Assets
|    |—— Dermascan_ML_Workflow.png
|—— best_xgb_model_r50.pkl
|—— final_model.h5
|—— grad_cam_ready.ipynb
|—— LICENSE
|—— resnet50v2_test.ipynb
|—— train.ipynb
```
## Code Details
### Tested Platform
- software
  ```
  OS: Ubuntu (google colab)
  Python: 3.10 (google colab)
  ```
- hardware
  ```
  GPU: NVIDIA A1000 (google colab)
  ```
  
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
