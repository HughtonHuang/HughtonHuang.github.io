---
title: Python filter()
date: 2020-04-02 09:35:42
categories:
  - Python
tags:
  - Python内置函数
---
# pyhton filters() 函数

+ filter()函数用于过滤序列，过滤掉不符合条件的元素，返回由符合条件元素组成的新列表。
+ 接收两个参数，第一个为函数，第二个为序列，序列的每个元素作为参数传递给函数进行判断，返回True或False，将返回True的元素放到新列表中。



```python
 shares={
	'IBM':36.6,
	'Lenovo':23.2,
	'oldboy':21.2,
	'ocean':10.2,
}
num = filter(lambda x:shares[x] > 20,shares)
print(list(num))
```