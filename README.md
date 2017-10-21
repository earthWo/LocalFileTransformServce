### ZFLocalFileTransferService

本地文件传输软件

软件基于java编写，使用swing界面，可以运行在所有的有java环境的机器上。

#### 截图：

![](http://7xjrms.com1.z0.glb.clouddn.com/QQ20171021-204205@2x.png)

### 简单介绍：

首先有一个开启服务的按钮，点击后会开启服务，这下面有按钮可以设置接收的文件的保存地址，不设置的话为保存在项目的根目录。在下面有一个简单的文本框，会显示一些文本信息，如是否在接收文件等。右边会显示所有的连接者，双击连接者可以传输文件。

目前支持所有的文件的传输。

### 存在的问题：

1.传输的速度比较慢，只适合小文件的传输。

2.传输大文件时可能会保存（之前测试时传输较大的歌曲就报错了，主要原因是数据使用json，导致解析时过大报错）

### 客户端和底层socket库

客户端：https://github.com/earthWo/ZFLocalFileTransfer

底层库：https://github.com/earthWo/ZFSocketLibrary

### License

BSD, part MIT and Apache 2.0. See the [LICENSE](https://github.com/bumptech/glide/blob/master/LICENSE) file for details.

## 