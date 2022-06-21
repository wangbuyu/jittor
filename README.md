### 计图挑战热身赛
## 简介
本赛题将会提供数字图片数据集 MNIST，参赛选手需要训练一个将随机噪声和类别标签映射为数字图片的Conditional GAN模型，并生成注册时绑定的手机号（如果没有绑定手机号请先绑定再进行提交）。

```
git clone https://github.com/wangbuyu/jittor.git
cd jittor/
sudo python3.7 -m pip install -r requirements.txt

修改 CGAN.py 使其运行
```
#### 运行环境
- ubuntu 18.04 LTS
- python >= 3.7
- jittor >= 1.3.0
#### 安装依赖
```
python3.7 -m pip install jittor 
sudo python3.7 -m pip install -r requirements.txt
```
### 训练
```
python CGAN.py
```
### 结果
```
number="18272400481"
```
最后生成的手机号：
![result](https://user-images.githubusercontent.com/75471795/174740852-d331bb59-8ec5-4819-86dd-818e16886939.png)
