# Pyinstaller 打包Django服务

本项目包含了一个django的demo, 以及通过pyinstaller打包django的示例

## 1. 依赖安装
```shell script
pip3 install -r requiremnts.txt
```

## 2. Django服务启动, 确保服务可正常运行
```shell script
python manage.py runserver
```
通过浏览器访问 http://localhost:8000/demo/hello能够正常访问页面

## 3. 进入pack目录, 打包项目
```shell script
cd ./pack
python pack_util.py
```

## 4. 打包成功, 运行可执行文件(windows)
```shell script
cd ./dist/manage/
manage.exe runserver --noreload 
```
通过浏览器访问 http://localhost:8000/demo/hello能够正常访问页面
