# Seekfree_RT1064_Opensource_Library
# 根据ARM官方指导手册修改了部分库文件，目前他已经支持LLVM编译器（armclang）
# 在同样打开 browse information的情况下
# v6编译器的仅需要22秒就可以完成（配置为i5 7300hq）
![Image text](https://raw.githubusercontent.com/LIGHT1213/picture/master/3.jpg)
# 但是v5的编译器需要超过5分钟的时间
![Image text](https://raw.githubusercontent.com/LIGHT1213/picture/master/2.jpg)
# 由于本人精力有限，此库所使用的逐飞库的版本通常落后于逐飞官方的版本
=======================================================================
~~# 注意如果出现如图所示的错误~~

![Image text](https://raw.githubusercontent.com/LIGHT1213/picture/master/1.jpg)

~~# 请切换回v5完全编译一次（此次编译无需开启browse information），再切换回来即可。~~
~~# 此种情况出现的原因可能是scf分散加载文件导致的~~
# 该问题目前已经修复
