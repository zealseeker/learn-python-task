# learn-python-task
some basic tasks for python learner
# 介绍
本教程是希望通过任务的方式来作为Python学习者的tutorial或者说example，让大家在枯草的学习外，通过实践的方式对python有更深刻的了解。教程中举例主要会围绕化学信息学，所以对相关领域的学者可能会有更大的帮助，而对于非该专业的小伙伴来说，这只是让代码更富有意义而已，只需要初高中的化学知识就能理解其含义，没有高深的学历要求。也欢迎其他有兴趣的专家设计其他领域的“题目”。  

# 布局框架
主目录下放置最简单的一些任务，任务名字为task**n**\_taskname即第几个任务，为一个文件夹，里面README.md是markdown说明文件，
即任务详细内容，文件夹里面存放参考代码，参考代码的prefix即写代码的人自取的名字，filename为要求的文件名。
以module\_为前缀的文件夹是模块，里面有子任务，为单独训练某一特殊模块而拓展，比如将来可以学习numpy等扩展包。  
```
root
|-- README.md #介绍
|-- task1_taskname #任务1
|-- |-- README.md #任务1内容
|-- |-- prefix_filename.py #参考代码
|-- module_modulename #模块
|-- |-- README.md #模块介绍
|-- |-- task1_taskname # 模块中任务1
|-- |-- |-- README.me #模块中任务1内容
|-- |-- |-- prefix_filename.py #参考代码
```
# 语法说明
```
>>> 这里表示python文件中的代码
<<< 这表示用户输入内容
这表示标准输出
```
以下是例子：  
```
>>> name = raw_input('please input your name \n')  #定义name为用户输入内容
please input your name  #输出：输入名字
<<< zealseeker          #输入
>>> print name          #打印用户名字
zealseeker              #输出
```
以上执行顺序与交互式python程序相同，而我们通常会把所有代码写进一个文件并按F5执行，那么就这样表达：
```
>>> name = raw_input('please input your name \n')
>>> print name
>>> 【your code here】 #其实这里意味着该脚本文件的终点，以下则是输入、输出的内容
please input your name
<<< zealseeker
zealseeker
```

# 参考教程
## Git教程
Git教程可参见：[Pro Git（中文版）](http://git.oschina.net/progit/index.html)  
至少要学会最基础的一些知识，比如版本控制的概念，最主要的几个命令：commit, push/pull等
也欢迎各位利用Git，一起帮助构建learn-python-task，让里面教程更佳丰富。

## Python教程
对于未学过python，甚至没有太多编程知识的小伙伴，推荐以下教程：
- [交互式Python学习](http://www.hubwiz.com/course/55068d37e564e51d743af52a/)
- [Python 教学视频](http://www.fenby.com/courses/pythonyu-yan-ji-chu-ke-cheng/)
- [零基础学Python](https://github.com/qiwsir/StarterLearningPython)  

对于有过编程知识的小伙伴，可以学习稍微简单一点的教材，比如：
- [简明Python教程](http://old.sebug.net/paper/python/index.html)  

会了基本的Python操作以后，在日常使用中需要用到一些Python手册，里面介绍的更佳丰富，这里也推荐几个教材：
- [Python官方教材(英文)](https://docs.python.org/2/)
- [廖雪峰的python教程](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)  
