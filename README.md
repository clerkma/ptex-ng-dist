# 这里是干嘛的？
这里提供的是一个基于的ApTeX的迷你TeX发行版。供应急以及测试使用。
和完整的TeX Live或MikTeX相比，现在没有包管理器，所以一部分文档不一定能够顺利通过编译。
二进制文件都是静态编译出来的，所以基于`web2c`的TeX发行版都可以使用这些二进制文件。

# 设定环境变量
## Windows环境下设定环境变量
```
set PATH=YOUR_PATH/bin/win64;%PATH%
```

## Linux/Mac OS X下设定环境变量
```
export PATH=YOUR_PATH/bin/linux-x86_64:$PATH
```
或
```
export PATH=YOUR_PATH/bin/darwin-x86_64:$PATH
```
