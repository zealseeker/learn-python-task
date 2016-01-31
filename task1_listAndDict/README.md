# Task 1: Learn List and Dict

## List/Tuple    
★☆☆☆☆  
1. 添加一个叫molecules.py的文件 （注意文件名前面要加入前缀，参考README.md）
2. 文件中完成两个变量的赋值，分别是atoms, bonds  
 **atoms**用以描述原子，假设一个化合物里有五个原子，分别是碳，氢，氢，氢，氢，他们的原子序数分别是6,1,1,1,1。
所以atoms变量就应该是含有这五个数字的列表。  
 - 赋值完atoms后分别打印第一个原子和第三个原子的原子序数。最终要求输出得到
 ```
 The atoms are:
 6
 1
 ```
 
 **bonds**用以描述化学键，从上述原子的描述中我们可以看出想要描述的内容是甲烷，自然甲烷含有4根碳氢。
每个键需要用三个数字来描述，前两个数字表示两个原子的原子序号
（不是原子序数，序号是唯一的，而原子序数只是表征原子类型，并不知道是“哪个”），第三个数字表示键的类型。
我们定义单键为1，双键为2，三键为3。暂时不考虑其他键的形式。  
那么比如说第一个碳氢键，就应该是(0,1,1)。其中括号表示是元组（tuple），第一个元素0表示碳，第二个元素1表示氢，
第三个元素1表示是单键。

## Dict  
★☆☆☆☆  
1. 添加一个叫element.py的文件
2. 在文件中完成两个变量的赋值，atomType以及bondType  
**atomType**用以描述原子类型，key是原子序数，value是原子类型，即：  
1:H , 2:He, 3:Li, 4:Be, 5:B, 6:C, 7:N, 8:O, 9:F, 10:Ne
暂时只需要这几个
**bondType**用以描述化学键类型，key是类型编号（请参考bonds），value是类型，即：  
1:single bond, 2: double bond, 3: triple bond  
 - 赋值完后打印第5号元素的原子类型  
 ```
 The 5th chemical element is:
 B
 ```

3. 将molecules.py文件中的atoms同样在element.py中赋值定义  

 - 赋值完后打印atoms第一个原子的原子类型 
 ```
 The 1st atom is:
 C
 ```
