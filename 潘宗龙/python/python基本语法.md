# python基本语法

### 1. 注释与缩进

```python
# 这是单行注释

'''
这是三个单引号的多行注释
'''

"""
这是三个双引号的多行注释
"""


```

**<font color="red">因为python中不使用{}，所以通过严格的缩进进行代码结构的组织</font>**

### 2. 基本数据类型

* Python3 中有六个标准的数据类型：

  - Number（数字）

    Python3 支持 **int、float、bool、complex（复数）**。

    在Python 3里，只有一种整数类型 int，表示为长整型，没有 python2 中的 Long。

    像大多数语言一样，数值类型的赋值和计算都是很直观的

  - String（字符串）

    Python中的字符串用单引号 **'** 或双引号 **"** 括起来，同时使用反斜杠 \转义特殊字符

    ```python
  str='hello world'
    str2="hello world"
    ```
  - List（列表）
  
  List（列表） 是 Python 中使用最频繁的数据类型。
  
    列表可以完成大多数集合类的数据结构实现。列表中元素的类型可以不相同，它支持数字，字符串甚至可以包含列表（所谓嵌套）。
  
  列表是写在方括号 **[]** 之间、用逗号分隔开的元素列表。
  
  ```python
  list=[1,2,3,'a','b','c']
  # 列表的索引从0开始
  print(list[0])
  #倒数第一个索引为-1，依次类推
  print(list[-1])
  #范围索引为  变量[头下标:尾下标]
  print(list[1:4])
  ```
  
  - Tuple（元组）
  
    元组（tuple）与列表类似，不同之处在于元组的元素不能修改。元组写在小括号 **()** 里，元素之间用逗号隔开。
  
  ```python
  #空元组
  tulpe_empty=()
  #只有一个元素
  tulpe_onlyone=(10,)
  
  tuple = (1,2,3,'a','b','c')
  #元组的索引类似列表
  # 从0开始
  print(tuple[0])
  #倒数第一个索引为-1，依次类推
  print(tuple[-1])
  #范围索引为  变量[头下标:尾下标]
  print(tuple[1:4])
  ```
  
  - Set（集合）
  
    集合（set）是由一个或数个形态各异的大小整体组成的，构成集合的事物或对象称作元素或是成员。
  
    基本功能是进行成员关系测试和删除重复元素。
  
    可以使用大括号 **{ }** 或者 **set()** 函数创建集合，注意：创建一个空集合必须用 **set()** 而不是 **{ }**，因为 **{ }** 是用来创建一个空字典。
  
    ```python
    '''
    创建格式为
    parame = {value01,value02,...}
    set(value)
    '''
    sites = {'Google', 'Taobao', 'Runoob', 'Facebook', 'Zhihu', 'Baidu'}
    a = set('abracadabra')
    ```
  
  - Dictionary（字典）
  
    字典（dictionary）是Python中另一个非常有用的内置数据类型。
  
    列表是有序的对象集合，字典是无序的对象集合。两者之间的区别在于：字典当中的元素是通过键来存取的，而不是通过偏移存取。
  
    字典是一种映射类型，字典用 **{ }** 标识，它是一个无序的 **键(key) : 值(value)** 的集合。
  
    键(key)必须使用不可变类型。
  
    在同一个字典中，键(key)必须是唯一的。
    
    ```python
    dict = {'name': 'runoob','code':1, 'site': 'www.runoob.com'}
    ```

### 3. 输入输出

   - 输入：input()函数

     函数等待用户使用键盘输入并按下回车键，该函数返回值即为用户输入的<font color="red">字符串</font>

   - 输出：print()函数

     该函数将括号内的字符输出到屏幕上，如：

     ```python
     print('Hello world')
     ```
### 4. 条件语句

 * if语句

   ```python
   # 示例
   a=10
   if a==10:
   	print('a等于10')
   ```

 * if else语句

  ```python
# 示例
a=20
if a>10:
    print('a>10')
else:
    print('a<10')
  ```

 * if elif语句

  ```python
# 示例
a=10
if a>10:
  	print('a>10')
elif a<10:
  	print('a<10')
else:
  	print('a等于10')
  ```
### 5. 循环语句

 * while语句

   ```python
   # 示例
   a=0 
   while a<6:
   	print('Hello World')
   	a+=1
   ```

 * for语句

   ```python
   # 示例
   a=['a','b','c','d','e']
   
   for i in a:
   	print(i)
   
   for i in range(0,6):
   	print(i)
   ```
### 6. 导入模块

   使用import关键字导入模块，例如我们无法在python中直接进行三角函数的运算，需要导入math模块，如下：

```python
import math
print(math.cos(45*pi/180.0))
```

如果觉得math太长，可以给他起个别名

```python
import math as mt
print(mt.cos(45*pi/180.0))
```

如果还是觉得长，可以用以下方法导入，可以直接省略前缀，但是并不推荐，因为导入的模块之间可能会存在同名的函数等

```python
from math import *
print(cos(45*pi/180.0))
```

```python
from math import cos,pi
print(cos(45*pi/180.0))
```
### 7. 函数

​	函数定义的格式如下：

```python
def 函数名(参数):
	......
	return 返回值
```

```python
# 示例
def mySum(a,b):
	return a+b
```

