# Python-14-
Python学习笔记(14)
# p47 对象列表的创建
'''创建列表的第一种方式,使用[]'''
lst=['hello','world',98]
print(lst)
print(lst[0],lst[-3])  #列表中的索引是从0开始的，输出到一个元素hello、括号内为负数的话就是从右往左数

‘’‘创建列表的第二种方式，使用内置函数list()’‘’
lst2=list(['hello','world',98])



# p48 列表的特点
#列表可以储存重复的数据，同时也可以混存，啥类型都可以存
#根据需要动态分配和回收内存



# p49 获取指定元素的索引
lst=['hello','world',98,'hello']
print(lst,index('hello')) #输出为0，因为如果列表当中存在N个相同元素，只返回相同元素中的第一个元素的索引
print(lst,index('Python')) #输出为：ValueError：‘Python’ is not in list
print(lst,index('hello',1,3)) #输出为：'hello' is nit in list

print(lst,index('hello',1,4)) #3
