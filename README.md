# CLLR
Contrastive Learning with Low-Dimensional Reconstruction

## Installation
- Python 3.8 
- PyTorch 1.13
- OpenCV

## Training
Run the following command to train a low-dimensional encoder
```
python cl_train.py
```

## Test
Run the following command to evaluate the model by (fine-tuning) a linear classifier
```
python cl_test.py --model_path results/xxx.pth
```

A pretrained model can be downloaded from [here](https://drive.google.com/file/d/1a443-NqMlZpq0hlIoGuTDcpqPxtouFY1/view?usp=sharing)

This code is mainly inspired by [SimCLR](https://github.com/leftthomas/SimCLR)
