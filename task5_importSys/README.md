# Task 5: Learn to use import

## os,sys
★★☆☆☆  
新建一个叫echo.py的文件，并在里面写一段代码，效果是：  
在当前目录打开命令提示符（linux下移动到当前目录），输入python echo.py xxx，输出xxx。xxx为任意字符  
提示：需要用到sys或os模块  
提示：sys.stdout.write; os.system，后者是个非常重要的函数，用以执行程序

## 引用其他文件
★☆☆☆☆  
新建一个叫methane.py的文件
```
#methane.py
atoms = [6,1,1,1,1]
bonds = [(0,1,1),(0,2,1),(0,3,1),(0,4,1)]
```
新建一个叫check.py的文件
要求引用methane文件并输出甲基的原子数量以及键的数量
```
5
4
```

# time,random
★★★☆☆  
输入一个叫randomGenerator.py的文件  
要求实现如下效果：  
每2秒产生一个1-n的随机数，共产生10次  
```
please input n
<<< 10
5
4
7
3
#以上四个数字皆随机产生
```
提示：需要用到的包为time和random，这两个包中有很多有用的函数，可以实现上述