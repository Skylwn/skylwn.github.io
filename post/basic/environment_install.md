## 安装miniconda
miniconda下载地址：[清华大学开源软件镜像站](https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/)<br>
miniconda安装教程：[Miniconda软件安装教程（Windows）](https://blog.csdn.net/qq_42951560/article/details/109035229)

## Anaconda Powershell Prompt创建虚拟环境
以**管理员身份**运行"Anaconda Powershell Prompt(miniconda3)"，然后在命令框下输入如下命令：
```Anaconda Powershell Prompt(miniconda3)
conda create -n ctbuProject python=3.7
```
出现类似如下说明时，键盘输入"y"，然后回车
```Anaconda Powershell Prompt(miniconda3)
The following packages will be downloaded:

    package                    |            build
    ---------------------------|--------------------------------
    setuptools-65.6.3          |     pyhd8ed1ab_0         619 KB  conda-forge
    sqlite-3.46.0              |       h2466b09_0         865 KB  conda-forge
    wheel-0.34.2               |           py37_0          60 KB  conda-forge
    ------------------------------------------------------------
                                           

The following NEW packages will be INSTALLED:

  ca-certificates    conda-forge/win-64::ca-certificates-2024.6.2-h56e8100_0
  libsqlite          conda-forge/win-64::libsqlite-3.46.0-h2466b09_0
  openssl            conda-forge/win-64::openssl-3.3.1-h2466b09_0
  pip                conda-forge/noarch::pip-24.0-pyhd8ed1ab_0
  python             conda-forge/win-64::python-3.7.12-h900ac77_100_cpython
  setuptools         conda-forge/noarch::setuptools-65.6.3-pyhd8ed1ab_0
  sqlite             conda-forge/win-64::sqlite-3.46.0-h2466b09_0
  ucrt               conda-forge/win-64::ucrt-10.0.22621.0-h57928b3_0
  vc                 conda-forge/win-64::vc-14.3-h8a93ad2_20
  vc14_runtime       conda-forge/win-64::vc14_runtime-14.40.33810-ha82c5b3_20
  vs2015_runtime     conda-forge/win-64::vs2015_runtime-14.40.33810-h3bf8584_20
  wheel              conda-forge/win-64::wheel-0.34.2-py37_0


Proceed ([y]/n)?
```

出现类似如下说明时，代表虚拟环境创建成功
```Anaconda Powershell Prompt(miniconda3)
# To activate this environment, use
#
#     $ conda activate ctbuProject
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```

## 安装PyCharm并配置解释器路径
下载专业版PyCharm：[PyCharm Professional 2024.1.3](https://www.jetbrains.com.cn/en-us/pycharm/download/?section=windows)<br>
PyCharm安装教程：[PyCharm专业版下载与安装教程](https://blog.csdn.net/qq_43629857/article/details/116092397)<br>
PyCharm配置基于conda环境的解释器：[PyCharm新建项目，配置解释器——基于Conda环境](https://blog.csdn.net/qq_45777045/article/details/104731444)
