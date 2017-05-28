---
### 从零开始
> 注：备份了可能用到的.sql，在目录中，以便专注python，
#### 基本环境
> python-2.7.9.msi （移步搜狐镜像）

> MySQL-python-1.2.5.win32-py2.7.exe（source net中有下载）

> mysql 5.5版本（注意慕课网中是5.6版本，此项目无差距，配置请看预备知识）

> eclipse PyDev插件（help中安装插件，具体自行）

> sql可视化工具 SQLyog Ultimate

#### 预备知识
> [MySQL基本操作-windows平台-慕课网免费视频][1]

#### 可能出现的问题

  - 1. SyntaxError: Non-ASCII character '\xe4' in file
  -  2. 安装MySQL-python过程中， Python version 2.7 required, which was not found in the registry
  - 3. python版本过高，MySQL不支持Python 3.x版本
  -  4. PyDev插件版本过高，eclipse安装pydev后不出现
  -  5. import MySQL失败，print失败
  -  欢迎添加问题等，：)如果有你的 star那就再好不过了

#### 问题解决
- 1. 编码问题：在编写代码页面的**第一行**加如下注释：

``` python?linenums
#-*- coding: UTF-8 -*-  `
```

- 2. 下载Python2.7版本，详见`基本环境`
- 3. 下载低版本
	- 4. 支持Java 7的最后一个版本是pydev 4.5.5，Install New Software中，输入地址 http://www.pydev.org/update_sites/4.5.5/  

- 5. 多个python造成，windows->Preferences->PyDev->Interpreter - Python，New一个Python解释器，填上解释器名字和路径，路径选相应的2.7版本python.exe。


  [1]: http://www.imooc.com/video/2007
