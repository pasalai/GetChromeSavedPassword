# 获取谷歌浏览器保存的密码
获取谷歌浏览器本地保存过的Url、账号、密码等信息

项目变异自[DeEpinGh0st
/
Browser-cookie-steal](https://github.com/DeEpinGh0st/Browser-cookie-steal)的Chrome80.x，所以需要遵循的特性基本相同。

项目基于Python3编写，基本原理为读取本地的Chrome的sqlite文件，并使用本地的私钥做解密（所以你从别人那里拖出来的sqlite数据库文件是无法解密的）

你可以直接用Python3运行源码，若本地无python3环境，也可以直接下载编译好的exe文件。