在编译QT程序的过程中遇到的问题：
Warning: File `main.cpp' has modification time 2.1e+04 s in the future

在虚拟机中使用QT在构建的时候提示这样的信息。
原因是:
虚拟机的时间没有和主机同步。
在虚拟机的设置界面的选项处的vmware tools 这个地方设置时间同步。

由于我的本身就是点了时间同步的，所以我直接重启了虚拟机。
这样操作以后问题就解决了。