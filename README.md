# htc-study-666

# htc-study-666

## WSL 换源与基础配置

##WSL 装好了需要换源。  
源就是软件下载地址，换成国内的会更快，这样装软件会快。

Ubuntu 有一个包管理器 `apt`，一般安装软件就用：
```bash
sudo apt install xxx

##wsl装好了需要换源
  源就是TM下载地址，换到国内就行，这样装软件会快
  Ubuntu有个包管理器 apt 一般安装就sudo apt install xxx
  c++ C代码编译器：gcc,那么安装gcc就sudo apt install gcc g++ 
  除非涉及到需要修改源码二次开发调试需要从源码安装（特定的软件从源码安装需要查阅对应文档）
  
##anaconda3创建环境（如何指定python版本、pip安装软件：torch numpy ...）
  conda create -n htc666 python==3.11/3.12 -y
  conda actviate htc666
  这里就进去新创建的conda 环境了，你可以在这个环境内部安装需要的包
  pip install torch(这里需要去官网看看咋装，需要对应驱动乱七八糟)
  
vscode连接本地wsl2,作为基础开发环境
需要了解python的安装方式 pip install -e . 啥意思
以上做好，基础配置结束。
