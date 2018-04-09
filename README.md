数字识别程序
===========
配置环境
---------
相关环境版本：

    python==3.6
    numpy==1.14.1
    opencv-python==3.4.0.12
    PyQt5==5.10.1
    pyqt5-tools==5.9.0.1.2
    torch==0.3.0
    torchvision==0.1.8

可使用requirements.txt快速安装相关包：<br>
执行命令：<br>
pip install -r requirements.txt

提供一些深度学习框架相应的安装教程：
[PyTorch: win10](https://blog.csdn.net/xiangxianghehe/article/details/73500031)、
[PyTorch: Ubuntu](https://blog.csdn.net/yucicheung/article/details/79094657)、
[Tensorflow](https://blog.csdn.net/baobei0112/article/details/79041706)、
[Keras](http://keras-cn.readthedocs.io/en/latest/for_beginners/keras_windows)

必要目录结构
------------

    * ./data      # Mnist 数据集
    * model.py    # 数字识别神经网络程序
    * ui.py       # 可视化界面程序
    * model.pkl   # 预训练模型文件
    * empty.bmp   # 可视化界面使用图片
    
使用方法
--------

配置好环境后直接python运行ui.py，进入界面程序<br>
流程：
    
    * 点击“打开文件”选择手写数字图片（黑底白字或深色底浅色字）
    * 点击“预测结果”运行模型的预测功能
    * 预测完成后会在下方显示预测的结果（即预测的数字）
