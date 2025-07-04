📌 项目名称

AdvFaceDefGAN：一种面向双身份冒充攻击的人脸识别对抗防御框架

这是我们论文 《AdvFaceDefGAN: A Study on Defense Methods for Face Recognition Against Dual-Identity Attacks》 的官方代码，用于验证实验结果，论文已投稿至 The Visual Computer（Springer，2025）。



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



pip install alibabacloud\_facebody20191230

pip install -i https://mirrors.tencent.com/pypi/simple/ --upgrade tencentcloud-sdk-python



2.数据集

您可以从以下链接下载我们预处理后的验证数据集和实验成果数据集：

https://huggingface.co/datasets/Evannoipnm0i0mo/AdvFaceDefGAN/tree/main



 📖 项目说明



本项目开源以下内容：



\- ✅ 防御框架的网络结构

\- ✅ 配置文件

\- ✅ 预训练模型权重

\- ✅ 评估指标计算方法



暂未开源：完整训练代码、部分损失函数实现与攻击模块。

