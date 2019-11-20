## opencv的api文档（国内可以访问）
http://www.opencv.org.cn/opencvdoc/2.3.2/html/index.html

## python的第三方库
https://pypi.org/

## 使用python版本号
3.5.0 ~ 3.7.0
原因：
numpy: Python version >= 3.5 required

## python3.5.0
+ 创建并激活虚拟环境
virtualenv -p C:\Users\ASUS\AppData\Local\Programs\Python\Python35\python.exe env350
env350/scripts/activate

+ 安装依赖包
pip install pipreqs
pipreqs ./ --encoding=utf8 --force
pip install -r requirements.txt
pip install opencv-python 

+ 运行
py ./get_answer.py -i .//images//test_01.png