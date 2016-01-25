# Task 3: Learn For and While
## For loop  
新建一个名为forloop.py的文件  
仍然是原来的atoms变量，记录原子序数小于10的不同原子出现的个数，原子以原子序数的形式表示  
```
>>> atoms=[6,1,1,17,1] #chloromethane
>>> 【your code here】
 {1: 3, 6: 1}
```
提示：输出结果用字典表示，检验字典中是否存在某个key用if ... in ...
```
>>> d = {'a':'b',1:'c'}
>>> print 'a' in d
True
>>> print 'b' in d
False
```

## While loop
新建一个名为whileloop.py的文件
用一个变量s表示分子量。s=atoms[0]+atoms[1]+...一个个加，当s大于等于14后停止并输出加第几个原子的时候分子量达到了8。注意原子序数和相对原子质量是不一样的，碳的相对原子质量是12，氢是1，可以用字典来记录他们的关系。
```
12
13
14
End when adding the 3rd atom.
```
**注意第几个原子这里需要考虑st, nd, rd三种情况，建议用字典，也可以用条件判断**