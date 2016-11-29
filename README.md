# 在Ubuntu系统下-安装机器学习包Scikit-learn
## 验证Python环境
使用Ubuntu 14.04 自带了Python 2.7 和Python 3.4，默认使用Python 2.7。以下指令看看python是否安装正确。

1.验证python安装位置
```bash
which python
```
Ubuntu 14.04输出
```bash
/usr/bin/python
```

2.验证python版本
```bash
python --version
```

Ubuntu 14.04输出
```bash
Python 2.7.6
```
## 安装scikit-learn依赖包

1.输入命令如下
```bash
sudo apt-get install build-essential python-dev python-setuptools python-numpy python-scipy python-matplotlib ipython ipython-notebook python-pandas python-sympy python-nose
```
