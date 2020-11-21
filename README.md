# Anaconda-Pycharm-
本说明为Anaconda和Pycharm安装及配置教程，参考《搭建 Python 高效开发环境： Pycharm + Anaconda》(https://zhuanlan.zhihu.com/p/140485845)，
## 目录
1. 文件说明
1. Pycharm安装
1. Jetbrain教育账号申请(包含Pycharm专业版)
1. Anaconda安装
1. 配置Anaconda下的Pycharm
1. conda常用命令
1. conda配置清华源 

## 文件说明
文件夹下包含有以下安装包和本说明，本说明最后编辑于 _2020年11月19日_ ，如安装包版本有更新，可点击下面相应的安装包名称进入官网下载页。
1. [Anaconda 最新64位Windows安装程序](https://www.anaconda.com/products/individual)
1. [Pycharm_Community 最新社区版](https://www.jetbrains.com/pycharm/download/#section=windows)
1. [Pycharm_Professional 最新专业版](https://www.jetbrains.com/pycharm/download/#section=windows)

## Pycharm安装
### 专业版与社区版的区别
- Pycharm Professional：收费，专业版会提供扩展，比如远程调试，插件支持，版本控制等
- Pycharm Community：免费，会包含常用的基础功能
下面的安装步骤将以Pycharm专业版安装为例
### 安装
1. 打文件夹中的Pycharm安装程序，点击next <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/1.png)
1. 选择安装位置 <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/2.png)
1. 根据需要来选择配置，建议全选<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/3.png)
1. 安装<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/4.png)<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/5.png)
1. 安装完成后打开Pycharm，同意协议<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/6.png)
1. 数据是否分享，根据情况来看<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/7.png)
1. 选择深色或浅色为主题颜色<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/8.png)
1. 根据需要安装插件（有一个spark插件，但是我还没用过不知道什么意思:cry:）<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/9.png)
1. 激活专业版账号（可通过下文教育账号方式激活）<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/10.png)
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/11.png)

## Jetbrain教育账号申请
1. 点击进入[Jetbrain教育账号申请网址](https://www.jetbrains.com/shop/eform/students?_ga=2.39145643.967103931.1605955561-1201956854.1605955561)
1. 选择通过学校邮箱地址的方式申请,并填入申请的中南大学校邮<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/邮箱1.png)
1. 点击申请<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/邮箱2.png)
1. 在邮箱中检查收到的邮件，并点击相应的注册和确认链接<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/邮箱3.png)<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/邮箱4.png)
1. 完成上述步骤之后即可使用自己的账号登录并激活Pycharm专业版


## Anaconda安装
1. 打开文件夹中的Anaconda安装程序 <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/12.png)
1. 同意协议 <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/13.png)
1. 为本用户安装 <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/14.png)
1. 选择安装路径 <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/16.png)
1. 开始安装 <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/17.png)
1. 选择Next <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/18.png)
1. 选择next <br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/19.png)

## 配置Anaconda base环境下的Pycharm
1. 新建项目<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/20.png)
1. 配置项目路径和解释器，选择已存在的解释器，点击右方的三个点<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/21.png)
1. 切换到conda环境，点击解释器右方的三个点，找到anaconda3的安装路径<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/22.png)
1. 配置完成后，解释器被 Pycharm 识别，点击创建<br>
![](https://github.com/LumosLovegood/Anaconda-Pycharm-/blob/main/attachments/23.png)

## conda常用命令
```
conda list        //列出当前环境下所有包及其版本号
conda env list    //列出所有存在的环境及其状态（当前处于哪一个环境）
conda install (包名{=版本号})   //安装特定版本包（版本号可不写）
conda update (包名)   //更新包
conda update (conda/anaconda)   //更新canda/anaconda
conda update --all   //更新所有包
```

## conda配置清华源
1. 用户根目录产生.condarc文件
`conda config --set show_channel_urls yes`
1. 配置 .condarc文件
```
channels:
  - conda-forge
  - defaults
show_channel_urls: true
channel_alias: https://mirrors.tuna.tsinghua.edu.cn/anaconda
default_channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/pro
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
custom_channels:
  conda-forge: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  msys2: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  menpo: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  simpleitk: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
ssl_verify: true
```
