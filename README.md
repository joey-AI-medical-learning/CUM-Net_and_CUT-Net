# Semi-supervised Medical Image Segmentation based on Hidden Feature Discrepancy between Different Learning Paradigms
A novel semi-supervised Medical image segmentation method
### News
```
We provided our pre-trained models on the ISIC2017 and ISIC2018 datasets, see './CUM-Net_and_CUT-Net/Checkpoint/';
```
For example, in (Checkpoint/ISIC2017(224,224)-train2000-val150-test600), (224,224) represents the image size, 2000 represents the training set size, 150 represents the validation set size, and 600 represents the test set size.
```
We released the codes;
```

### Requirements
This repository is based on PyTorch 1.13.0, CUDA 11.7 and Python 3.8; All experiments in our paper were conducted on a single NVIDIA 3090 GPU.

### Usage
1. Clone the repo.;
```
git clone https://github.com/joey-AI-medical-learning/CUM-Net_and_CUT-Net.git
```
2. Put the data in './CUM-Net_and_CUT-Net/input';

3. Train the model;
```
Please modify train_ISIC.py and parameter_ISIC.py according to different data sets
```
4. Test the model;
```
Please modify test_ISIC.py according to different data sets
```
### Acknowledgements:
Our code is adapted from [SSL4MIS](https://github.com/HiLab-git/SSL4MIS), [Laplacian-Former](https://github.com/xmindflow/Laplacian-Former) and [VM-Unet](https://github.com/JCruan519/VM-UNet). Thanks for these authors for their valuable works and hope our model can promote the relevant research as well.

### Questions
If any questions, feel free to contact me at 'mengyijust@163.com'
