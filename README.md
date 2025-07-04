📌 Project Title
AdvFaceDefGAN: A GAN-based Defense Framework for Face Recognition Against Dual-Identity Impersonation Attacks

This repository provides the official code for the paper:

"AdvFaceDefGAN: A Study on Defense Methods for Face Recognition Against Dual-Identity Attacks", submitted to The Visual Computer (Springer, 2025). The released code supports verification of experimental results.

1.Conda 环境：
conda deactivate
conda remove -n AdvFaceDefGAN --all -y
conda create -n AdvFaceDefGAN -y
conda activate AdvFaceDefGAN
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia -y
conda install torchmetrics tqdm tensorboard multiprocess  -y
conda install -c conda-forge jupyter -y
conda install matplotlib -y
conda install ipykernel -y
python -m ipykernel install --user --name=AdvFaceDefGAN --display-name "AdvFaceDefGAN"

pip install alibabacloud_facebody20191230
pip install -i https://mirrors.tencent.com/pypi/simple/ --upgrade tencentcloud-sdk-python

2. Dataset
You can download the preprocessed validation datasets and experiment results from the link below:
https://huggingface.co/datasets/Evannoipnm0i0mo/AdvFaceDefGAN/tree/main

Project Overview
This repository includes the following components:

✅ Network architecture of the defense framework

✅ Configuration files

✅ Pretrained model weights

✅ Evaluation metric scripts

Note: The full training code, part of the loss function implementations, and adversarial attack modules are not released.
