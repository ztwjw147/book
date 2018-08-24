## python 的内置函数

- filter(function, iterable) 函数用于过滤序列，过滤掉不符合条件的元素，返回由符合条件元素组成的新列表。iterable可迭代对象，返回值是个列表
- getattr(object, name[, default]) 用于返回一个对象属性值。
- isinstance(object, classinfo) 判断一个对象是否是一个已知的类型
- map() 会根据提供的函数对指定序列做映射。返回值，Python2列表 python3迭代器  例如：
  ```python
  map(lambda x, y: x + y, [1, 3, 5, 7, 9], [2, 4, 6, 8, 10])
  输出[3, 7, 11, 15, 19]
  ```
- range() 返回一个整数列表
- slice() 函数实现切片对象，主要用在切片操作函数里的参数传递。
- type()  返回对象类型，或者创建元类
- zip() 函数用于将可迭代的对象作为参数，将对象中对应的元素打包成一个个元组，然后返回由这些元组组成的列表。
