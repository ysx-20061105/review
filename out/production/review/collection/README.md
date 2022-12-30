## 集合

数组存储的特点：

一旦初始化后，其长度就确定啦。  数组一旦定义好，其元素的类型就确定啦。

数组存储的弊端：

1. 一旦初始化后，其长度就不可修改
2. 数组中提供的方法非常有限，对于添加、删除、插入数据等操作，非常不便，效率不高
3. 获取数组中实际元素的个数的需求，数组没有现成的属性或方法可用
4. 数组存储数据的特点：有序、可重复。对于无序、不可重复的需求不能满足

集合存储的优点：

解决数组存储数据方面的弊端。

### Collection
用于存储一个一个的对象

常用方法：
1. add()/addAll() 添加数据
2. size() 获取元素个数
3. clear() 清空集合
4. isEmpty() 是否是空集合
5. contains()/containsAll() 是否包含某个元素，或某个集合的元素 对象比较调用对象的equals方法
6. remove()/removeAll() 删除
7. retainAll() 取两个集合的交集
8. toArray() 转成数组
9. iterator() 返回迭代器对象，用于遍历集合


#### List
用于存储有序的、可重复的数据

实现类：ArrayList、LinkedList、Vector

#### Set
用于存储无序的、不可重复的数据

实现类：HashSet、LinkedHashSet、TreeSet

### Map
用于存储一对(key,value)的数据

实现类：HashMap、LinkedHashMap、TreeMap、Hashtable、Properties













