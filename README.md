## 个人学习 Tensorflow 的 Jupyter Notebook

### 环境

* Anaconda: conda v22.9.0
* Python: v3.8.15
* Tensorflow: v2.3.1 - Apple M1

### 推荐运行方式

* VS Code
* Jupyter Notebook

### 环境配置

#### 创建 Conda 环境

```shell
conda creaet -n tensorflow python=3.8
```

#### 激活 Conda 环境

```shell
conda activate tensorflow
```

#### 安装 Tensorflow

因为我用的是 M1 MBP， M1版本的 Tensorflow 没法通过 pip 直接安装。

先下载[安装包🔗](https://drive.google.com/drive/folders/1oSipZLnoeQB0Awz8U68KYeCPsULy_dQ7)。

然后执行：

```shell
pip install tensorflow-2.4.1-py3-none-any.whl
```

AMD64 平台可以通过 pip 正常安装即可。