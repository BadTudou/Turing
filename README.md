#Turing#
**Turing**是一个用**C++**编写的模拟**图灵机**运行过程的小程序。

![演示图片][img-demo]

##编译##
```
gcc turing.cpp -o turing
```
##运行##
```
./turing
```
##初始化##
###流程###
1.初始化存储带上的符号
2.初始化控制器当前状态
3.初始化读写头起始位置
4.设置工作程序
###示例###
1.输入数据符号：1111B111
2.输入控制器初始状态：1
3.输入控制器初始位置：1
4.输入工作程序(可手动输入工作程序，不输入时默认为以下程序)：
```
	111R1
	1b1R2
	211R2
	2bbL3
	31bH3
	3bbH3
```
##版权信息##
本软件遵循**[GPL][txt-GPL]**。

[img-demo]: demo.png "图灵机演示图片"
[txt-GPL]: ./LICENSE "GPL"