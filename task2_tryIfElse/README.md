# Task 2: Try If Else

## ��ͨ�÷�
������  
�½�һ����Ϊtryifelse.py���ļ�  
��Ȼ��ԭ����atoms�����������i��ԭ���Ƿ�Ϊ̼��������Ҫ�ж�i�Ƿ���Ч�������ַ����жϣ�
1. ֱ����try�����ж�i�Ƿ���Ч������ʹ�ӡ����
2. ���i�Ƿ�Ϊnumber��С��atoms�ĳ���
```
>>> atoms=[6,1,1,1,1] 
>>> ��your code here��
please input i
<<< 9
sorry, the i is invalid
>>> ��rerun the code��
please input i
<<< 3
The atom No. is 1
```
��ʾ������i�ǲ���number�ķ����� type ����
```
>>> type(1) == int
True
>>> type('1') == int
False
```  
## ��Ԫ�÷�
������  
### ��ֵ
��һ����ʵ�ָ�ֵ����atomType  
����û���������ַ�������C����ñ���Ϊ'including carbon',����ñ���Ϊ'excluding carbon'��  
### ��ӡ
��һ����ʵ������Ч��������������ֵ��Ϊ��ӡ
```
>>> ��your code here��
<<< CCCC
including carbon
>>> ��rerun code��
<<< SO2
excluding carbon
```
��ʾ���ַ����Ƿ���������� in��
```
>>> 'a' in 'ABC'
False
>>> 'x' in 'xyz'
True
```