### gitbook 本地搭建

#### 在 Windows 上环境

1.安装Nodejs

安装Nodejs，可以到 [Node官网](https://nodejs.org/en/download/) 下载 LTS 稳定版的 Windows Installer 进行安装。
安装完成后在命令行以下命令来检测是否安装成功。
```
node -v
```        

2.安装gitbook
在Nodejs安装目录下打开命令控制台，输入以下命令行
```
npm install gitbook -g
npm install gitbook-cli -g
```

安装完成后使用以下命令查看是否安装成功
```
gitbook -V
```

3.初始化自己的项目

在命令行模式下，选择自己的目录，使用以下命令来创建自己的gitbook文件夹，并初始化项目。
```
mkdir direName //创建自己的文件夹目录
cd direName    //进入到自己的gitbook文件夹目录
gitbook init   //初始化gitbook项目
```

4.启动文档

下载当前gitbook项目文档压缩文件，并解压出来。进入到文档解压的文件夹内，执行以下命令。
```
gitbook serve
```

5.阅读文档

本地浏览器访问 ```http://127.0.0.1:4000``` 即可正式访问当前教程文档。 

---

#### 在 Mac OS X 上搭建环境

1. 安装Nodejs

安装Nodejs，可以到 [Node官网](https://nodejs.org/en/download/) 下载 LTS 稳定版的 macOs Installer 进行安装。
安装完成后在命令行以下命令来检测是否安装成功。

安装完成后在命令行以下命令来检测是否安装成功。
```
node -v
```

2. 安装gitbook

打开终端
> - 点按程序坞中的“启动台”图标 <img with="20px;" height="20px;" src="../../APIOAK-images/qidongtai.png">，在搜索栏中键入“终端”，然后点按“终端”。
> - 在“访达” <img with="20px;" height="20px;" src="../../APIOAK-images/fangda.png"> 中，打开“/应用程序/实用工具”文件夹，然后连按“终端”。

打开命令行输入以下命令行

```angular2
sudo npm install gitbook -g
sudo npm install -g gitbook-cli
```

安装完成后使用以下命令查看是否安装成功
```
gitbook -V
```

3.初始化自己的项目

在命令行模式下，选择自己的目录，使用以下命令来创建自己的gitbook文件夹，并初始化项目。
```
mkdir direName //创建自己的文件夹目录
cd direName    //进入到自己的gitbook文件夹目录
gitbook init   //初始化gitbook项目
```

4.启动文档

下载当前gitbook项目文档压缩文件，并解压出来。进入到文档解压的文件夹内，执行以下命令。
```
gitbook serve
```

5.阅读文档

本地浏览器访问 ```http://127.0.0.1:4000``` 即可正式访问当前教程文档。 


