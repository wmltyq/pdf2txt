# pdf2txt
## 安装模块
在使用pip命令安装模块时，建议修改pip源以提升下载速度。在用户文件夹下创建pip目录，并在pip目录下创建pip.ini文件（%HOMEPATH%\pip\pip.ini），文件中添加如下内容：
> [global]  
> trusted-host=mirrors.aliyun.com  
> index-url=http://mirrors.aliyun.com/pypi/simple/

使用以下命令安装程序所需模块：
> pip install pdfminer3k

## 使用说明
将需要提取内容的PDF文件名修改成test.pdf放到pdf2txt.py的同级目录下，或者在parse方法中找到test.pdf替换成相应的文件名，运行程序即可。

## 适用场景
本程序只是对PDF文档内容做一个简单的提取，然后根据需要复制粘贴提取到的文本。
