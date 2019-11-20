# 目录 
```
answer-card  
├─.vscode vscode配置  
|   ├─launch.json 运行配置文件  
|   └─settings.json 当前项目的vscode配置  
├─images 存储图像  
|   ├─result 识别处理后得出的图像  
|   |   └─test_01_result.png test_01.png识别处理后得出的图像  
|   ├─example_test.png 待识别图像模板  
|   ├─test_01.jpg 待识别图像  
|   ├─test_01.png 待识别图像  
|   ├─test_02.png 待识别图像  
|   ├─test_03.png 待识别图像  
|   ├─test_04.png 待识别图像  
|   └─test_05.png 待识别图像  
├─.gitignore git忽略配置文件  
├─get_answer.py 主程序代码  
├─README.md 项目说明文本  
└─requirements.txt python第三方包清单  
```
<br/>


# 开始使用

## 使用python版本号  
此项目使用3.5.0，建议范围：3.5.0 ~ 3.7.0    
 
## 创建并激活虚拟环境  
```shell  
virtualenv -p C:\Users\ASUS\AppData\Local\Programs\Python\Python35\python.exe env350  
env350/scripts/activate  
```  
## 安装依赖包  
```shell  
pip install pipreqs  
pipreqs ./ --encoding=utf8 --force  
pip install -r requirements.txt  
pip install opencv-python  
```  

## 项目运行  
+ 手动命令运行  
```shell  
py ./get_answer.py -i .//images//test_01.png  
```  
+ Vscode运行  
可以通过.vscode的lauch.json配置运行及调试。  
<br/>

# 帮助与支持
## opencv的api文档（国内可以访问）  
http://www.opencv.org.cn/opencvdoc/2.3.2/html/index.html 

## python的第三方库  
https://pypi.org/  