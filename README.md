# pymake
Compile a python project into .so files.
把一个python项目编译成若干.so文件。

# 2021.02.02
* One should provide a `main.py` to invoke .so files. 用户需要自己写一个main.py用来调用.so文件。
* One should set `PY_INCLUDE` environment variable to `<PythonInstallDir>/include/python3.x`. 用户需设定`PY_INCLUDE`环境变量为Python安装目录的`include/python3.x`目录。
* Compilation of packages is not supported yet. 尚不支持包的编译。
