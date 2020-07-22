# Python-diary
Python 学习日记
print("Hello 天下第一 !") 
'''
（多行注释）这是易涛正式学习Python的第一个文档，希望能有所长进
'''
# 单行注释
print((((1+1)*2-3)**3)/2)#运算符
'''
+ 加
- 减
* 乘
/ 除
//整除
% 取余
**幂
'''
print(43%5)#取余，余数为3
print(43//5)#整除，整数项为8
#与或非 ：and/or/not->结果为True/false
'''
位运算是二进制下对数进行操作
取二进制的函数为bin()
~ 取反、& 与、| 或、^ 异或、<< 左移、>> 右移
'''
'''三位运算符'''
x,y=3,4
if x<y:#不要忘记 “：”
    sm=x
else:
    sm=y
print(sm)
'''简略版为'''
x,y=3,4
sm=x if x<y else y
print(sm)
'''
is, is not 对比的是两个变量的内存地址
==, != 对比的是两个变量的值
in /not in
'''
'''运算符优先级排序
二元运算符（**等）>一元运算符（+-*/等）>移位运算>位运算>逻辑运算
'''
#需要注意，Python大小写敏感
shoplist = ['apple', 'mango', 'carrot', 'banana']
for item in shoplist:#item是字符串里的每个字符的代写，for……in……循环即是循环执行以下操作
    print(item)
'''练习题
1.怎样对python中的代码进行注释？
    答：利用''' '''或者""" """可以实现多行行注释，利用# 可以实现单行注释
2.python有哪些运算符，这些运算符的优先级是怎样的？
    答：二元运算符（**等）>一元运算符（+-*/等）>移位运算>位运算>逻辑运算
3.python 中 is, is not 与 ==, != 的区别是什么？
    答：is, is not 对比的是两个变量的内存地址；==, != 对比的是两个变量的值
4.python 中包含哪些数据类型？这些数据类型之间如何转换？
    答：包括整型、浮点型、布尔型；类型转换可以通过函数来实现：转换为整型int()；转换为浮点型float()；转换为字符串str()
