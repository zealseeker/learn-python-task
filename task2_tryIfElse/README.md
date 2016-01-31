# Task 2: Try If Else

## 普通用法
★☆☆☆☆  
新建一个名为tryifelse.py的文件  
仍然是原来的atoms变量，检验第i个原子是否为碳，首先先要判断i是否有效，有两种方法判断：
1. 直接用try，不判断i是否有效，出错就打印错误
2. 检查i是否为number且小于atoms的长度
```
>>> atoms=[6,1,1,1,1] 
>>> 【your code here】
please input i
<<< 9
sorry, the i is invalid
>>> 【rerun the code】
please input i
<<< 3
The atom No. is 1
```
提示：检验i是不是number的方法是 type 函数
```
>>> type(1) == int
True
>>> type('1') == int
False
```  
## 三元用法
★★★☆☆  
### 赋值
在一行内实现赋值变量atomType  
如果用户输入的是字符串包含C，则该变量为'including carbon',否则该变量为'excluding carbon'。  
### 打印
在一行内实现如下效果，即将上述赋值改为打印
```
>>> 【your code here】
<<< CCCC
including carbon
>>> 【rerun code】
<<< SO2
excluding carbon
```
提示：字符串是否包含可以用 in，
```
>>> 'a' in 'ABC'
False
>>> 'x' in 'xyz'
True
```