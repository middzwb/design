
**红黑树 vs hash table**

如何选型？

hash优点：平均的查询、插入、删除时间复杂度为常数级O（1）。

红黑树的特性：有排序功能、如果需要排序或范围查询等，需要选择树；
树的key需要实现排序功能、而hash表需要实现hash函数、如果hash实现较为复杂，更推荐树。

[tree vs hash](https://www.geeksforgeeks.org/advantages-of-bst-over-hash-table/)
