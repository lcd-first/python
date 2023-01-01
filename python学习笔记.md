# 1.变量

![1662898514493](python学习笔记.assets/1662898514493.png)

## 1.下划线命名法

![1662898647207](python学习笔记.assets/1662898647207.png)

下划线命名法：

1. 字母全部小写
2. 不停单词用下划线分割



驼峰命名法

1. 单词首字母大写分割

   Userage

   UserGender





# 2. 条件判断：



 if [] :





![1662904296088](python学习笔记.assets/1662904296088.png)





![1662904319517](python学习笔记.assets/1662904319517.png)



4 个空格的缩进



![1662904466324](python学习笔记.assets/1662904466324.png)



![1662904528659](python学习笔记.assets/1662904528659.png)





and   &&

or || 

# 3. 列表

![1662904689815](python学习笔记.assets/1662904689815.png)



```python
shopping_list = ["'见面'"]
shopping_list.append("'牵手'")  # 添加元素
shopping_list.remove("见面")
```



![1662904859369](python学习笔记.assets/1662904859369.png)



同一个列表里面可以放不同的数据





## 1. 列表内置函数

![1662904923165](python学习笔记.assets/1662904923165.png)





## 2 实例操作，购物清单

![1662905092599](python学习笔记.assets/1662905092599.png)















## 3 函数和方法的区别

![1662904763518](python学习笔记.assets/1662904763518.png)

# 4. 字典

## 字典用于储存键值对

![1662905228452](python学习笔记.assets/1662905228452.png)



![1662905261015](python学习笔记.assets/1662905261015.png)



## 字典和列表都是可变的

![1662905384860](python学习笔记.assets/1662905384860.png)

## 增加元素

![1662905461445](python学习笔记.assets/1662905461445.png)



## 判断键是否存在



![1662905525311](python学习笔记.assets/1662905525311.png)

![1662905551931](python学习笔记.assets/1662905551931.png)



## 删除键值对



del  字典名 [ 键]

![1662905591312](python学习笔记.assets/1662905591312.png)



## 内置方法

![1662906011768](python学习笔记.assets/1662906011768.png)







## 元组

![1662905303530](python学习笔记.assets/1662905303530.png)



列表用方括号

元组用元括号，元组不可变，增删改都不能使用

# 5. for循环



![1662905828747](python学习笔记.assets/1662905828747.png)



## 1. 示例1

![1662905870972](python学习笔记.assets/1662905870972.png)



```python
temperature_list = [36.4,36.6,36.2]
for temperature in temperature_list:
    if temperature >=38:
        print(temperature)
        print("完球了")
```



## 2. 示例2

![1662906065433](python学习笔记.assets/1662906065433.png)





![1662906087612](python学习笔记.assets/1662906087612.png)



上面两个意思相同



## 3. range(a,b)

![1662906162332](python学习笔记.assets/1662906162332.png)



range(5,10)

结束值不在序列中



![1662906233493](python学习笔记.assets/1662906233493.png)





## 4. range(a,b,c)

![1662906280903](python学习笔记.assets/1662906280903.png)





# 6. while循环



## 1. 语法

![1662906507442](python学习笔记.assets/1662906507442.png)







![1662906587447](python学习笔记.assets/1662906587447.png)

## 2.while 和for 的区别

![1662906639539](python学习笔记.assets/1662906639539.png)

##  3. 实例

![1662906857535](python学习笔记.assets/1662906857535.png)



```python
print ("'此为一个求平均值的程序'")
total = 0
count = 0 
user_input = input ("请输入数字（完成所有数字输入后，请输入q结束程序）")
while user_input!="q" :
    num = float (user_input)
    total+=num
    count=count+1
    user_input = input ("请输入数字（完成所有数字输入后，请输入q结束程序）")

if count==0:
    result=0
    print("你输入的值的平均值为"+ str(result)) 
else:
    result=total/count
   print("你输入的值的平均值为"+ str(result)) 
    
    


```

# 7. 格式化字符串

## 1. format 方法

![1662907342842](python学习笔记.assets/1662907342842.png)





![1662907403735](python学习笔记.assets/1662907403735.png)

# 8. 函数

## 1. 格式

![1662907555034](python学习笔记.assets/1662907555034.png)

​	





# 9. 引入模块

​	

## 1. 书写规则

![1662908106647](python学习笔记.assets/1662908106647.png)



按住ctrl  点函数名，就可以查看函数内容



## 2. 引入第三方库

![1662908363348](python学习笔记.assets/1662908363348.png)

​	





# 10. 面向对象

![1662908608521](python学习笔记.assets/1662908608521.png)



## 1. 类方法和属性

![1662909221824](python学习笔记.assets/1662909221824.png)

## 2. 类继承



在 class 类上(父类)

![1662909650091](python学习笔记.assets/1662909650091.png)

