---
title: "Unity_ml_agents"
date: 2021-05-30T21:04:39+08:00
---


## Installation

vc2015:https://aka.ms/vs/16/release/vc_redist.x64.exe
cuda:可选 gpu

### Install Python

[Python](https://www.python.org/downloads/release/python-379/) (recommend installing Python 3.6 or 3.7)

If you are using Windows, please install the x86-64 version and not x86

Configuration:

    创建虚拟环境: py -m venv venv 
    进入虚拟环境: venv\Scripts\activate

#### Packages:

* 更新pip: _py -m pip install --upgrade pip_
* 安装pytorch: _pip install torch==1.8.1 -i http://pypi.douban.com/simple --trusted-host pypi.douban.com_
* 安装mlagents: _pip install mlagents_ (如果出2020问题加参数 _--use-feature=2020-resolver_ )




