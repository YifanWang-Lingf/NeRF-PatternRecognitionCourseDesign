# 一 环境配置

（1）！！！原作者使用的pytorch1.11貌似已经无法安装，源代码中的requirements.txt已经不能正常使用

（2）在终端依次键入以下指令来创建虚拟环境

`conda create --name NeRF python=3.11`

`conda activate NeRF`

（3）然后安装依赖库

`pip install numpy==1.25.0`

`pip install matplotlib`

`pip install imageio`

`pip install imageio-ffmpeg`

`pip install imgaug`

`pip install configargparse`

`pip install tensorboard`

`pip install opencv-python`

`pip install tqdm`

（4）然后安装CUDA和对应的Pytorch库

# 二 代码运行

（1）在终端中打开文件夹nerf-pytorch或者使用cd命令进入文件夹nerf-pytorch

（2）在终端中输入

`python run_nerf.py --config configs/fern.txt`

即可开始模型训练

# 三 训练结果获取

在nerf-pytorch\logs\fern_test文件下面找到mp4视频文件即为训练结果
