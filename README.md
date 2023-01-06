## start-application
**生成`.exe`文件， 执行一些命令， 如一键启动多个应用程序。**

## 使用  
1. 编写代码  
编写`start-application.py`， 执行一些命令， 如启动应用。 
   
2. 安装`pyinstaller`  
`pip install pyinstaller` 或 `pycharm`内`python interpreter`内安装

3. 打包生成可执行文件  
`pycharm`的`Terminal`内执行`pyinstaller -F -w -i start.ico main.py`命令， 打包生成`.exe`文件， 位置在项目dist文件夹下
   
4. 双击运行生成的可执行文件
