# 这里是干嘛的？
这里提供的是一个基于的ApTeX的迷你TeX发行版。供应急以及测试使用。
和完整的TeX Live或MikTeX相比，现在没有包管理器，所以一部分文档不一定能够顺利通过编译。
二进制文件都是静态编译出来的，所以基于`web2c`的TeX发行版都可以使用这些二进制文件。

# 设定环境变量
## Windows环境下设定环境变量
注意：现在只提供Win64版本，Win32版本可从W32TeX种获取。
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
## Android下设定环境变量
由于Android平台的ABI比较多，所以在`bin/android`文件夹下还有一层文件夹用来存放不同ABI的二进制文件。
在使用的时候需要先确定所使用的机型的ABI，然后将该ABI文件夹下的可执行文件提取到`bin/android`文件夹下。
同时，需要更改一下texmf.cnf文件内的`OSFONTDIR`变量的值。Android下面的Terminal模拟器推荐使用Android
Terminal Emulator或者Termux。
```
export PATH=YOUR_PATH/bin/android:$PATH
```
