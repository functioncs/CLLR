# CLLR
Contrastive Learning with Low-Dimensional Reconstruction

## Installation
- Python 3.8 
- PyTorch 1.13
- PIL

## Training
Run the following command to train a low-dimensional encoder
```
python cl_train.py
```

## Test
Run the following command to evaluate the model by (training) a linear classifier
```
python linear.py --model_path results/xxx.pth
```

A pretrained model can be downloaded from [here](https://drive.google.com/file/d/1d8nfGHsHIuJYjU7mHtCtSXf98IbWMFAa/view?usp=sharing)

This code is mainly inspired by [leftthomas/SimCLR](https://github.com/leftthomas/SimCLR).
