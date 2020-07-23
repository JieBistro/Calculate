# Calculate

###### 用WPF编程实现一个简单代数运算系统，具体要求如下：
（1）用户通过输入任意表达式，计算出结果，如：asin(bx+c) + x^2 + sqrt(a);  
（2）表达式中若出现未申明变量，则给该变量初始化一个随机值，如：a = random(0,10);  
（3）支持常用数学函数，包括（不限于）如下函数：sin, cos, tan, floor, random, abs, sqrt, ^…  
（4）可以设置变量动画，表达式根据变量的变化自动更新计算结果  

###### 输入框内操作
可以输入一个新的变量，并且为它赋值。如输入  x=1  
可以处理一个表达式，当表达式中的变量已经创建时，使用已经创建的变量的值，如果还没创建，就随机化生成一个值带进去运算。如 x+y-sin(x)中x=1,y随机初始化  
可以改变已经创建的变量的值。 如 x=4  

https://blog.csdn.net/weixin_43644231/article/details/107475426
