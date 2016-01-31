# Task 4: Use function

## define a function 
★☆☆☆☆  
新建一个fc.py的文件  
新建一个叫get_atom_type的函数，函数的参数为原子序数，函数的返回值为该原子的类型
```
>>> 【your function code】
>>> print get_atom_type(6)
C
#尝试理解以下代码
>>> 【your function code】
>>> print get_atom_type(raw_input('please input the atom no. \n'))
please input the atom no.
<<< 6
C
```
提示，需要拥有原子序数->原子类型的字典，请参照task1_listAndDict

## Chemical informatics - calculating molecule weight  
★★☆☆☆  
新建一个叫mw.py的文件
新建一个叫get_mw的函数，参数为原子列表，函数的返回值为该分子的分子量
```
>>> atoms = [6,1,1,1,1] #methane
>>> 【your function code】
>>> print get_mw(atoms)
16
```
提示，由原子序数先要得到该原子的相对原子质量，可以用一个字典得到，然后将这些原子质量加到一起即分子量  
**尝试用两句话解决这个函数**：申明相对原子质量字典；计算相对原子质量并返回。  
★★★☆☆
