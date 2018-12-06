#### 迭代器模式

> 迭代器模式：提供一种方法顺序访问一个聚合对象中各种元素，而又不暴漏该对象的内部表示。

当你需要访问一个聚集对象，而且不管这些对象是什么都需要遍历的时候，你就应该考虑用迭代器模式，或者对聚集有多种方式遍历时，也可以用迭代器模式。

也就是说为遍历不同的聚集结构提供入开始，下一个，是否结束，当前哪一个等统一的接口。

迭代器模式就是分离了集合对象的遍历行为，抽象出一个迭代器类来负责，这样既可以做到不暴漏集合的内部结构，又可让外部代码透明地访问集合内部的数据，迭代器模式在访问数组、集合、列表等数据时，尤其是数据库操作时，是非常普遍的应用，但是由于太普遍了，所以各种高级语言都对它进行了封装，所以给人感觉此模式不常用了。