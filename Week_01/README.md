学习笔记

数组和链表都属于基本数据结构；
数组内存地址为连续的，链表内存地址为非连续性；
数组的时间复杂度：
  插入、删除都是O(n), 查询为O(1)；
链表的时间复杂度：
  插入、删除都是O(1), 查询为O(n)；
  
Array.sort() 的时间复杂度是O(n*logn);  
  
ArrayList 动态数组，大小可变；需要扩容是使用System.arraycopy方法；  
Vector可以实现可增长的对象数组；
Vector是线程安全的，ArrayList是线程非安全的；
Stack继承Vector；是Vector的子类，Stack的底层数据结构是数组
public class Stack<E> extends Vector<E> 
protected Object[] elementData;


一维数据加速处理，可以变成二维来提速操作；

跳表 skip list：
    只能用于元素有序的链表情况；
    插入、删除、搜索都是O(logn);
    如redis，levelDB都是此技术；
    
LRU cache 使用的LinkedList 双向链表；

算法的思想：就是找重复性，计算机最终只会if，else，for，loop，和recursion;

动态规划：对每个问题直接依次，然后将其保存在一个表格中。再次需要解决此问题时，只需要用常数时间查看一下结果；

栈：LIFO 后进先出
队列：FIFO 先进先出

Deque : Double end queue 双端队列
    两边都可以插入删除操作；
    
Priority Queue ： 优先队列
    取优先级最高的，用comparator方法定义优先级；

如何在Google上搜索API：
    关键字：stack java 12， java source code， java source code github

对于学习算法：
    五毒神掌真的好用，多练习，多做题，在次数下一些算法自然就记住了，题做多了，之前一些不清楚的算法，
    在做其他的题目的时候会突然豁然开朗。


对于基础差的，就要多看视频，多做题，不理解的先死记硬背，做多了自然就会理解了；
最最重要的一点：一定要动手、动手、动手，最好用文本写程序，每个关键字都手打；

目前不足：
时间复杂的理解及判断； 
双指针的方式仍然需要再练习加理解，目前仍处在迷糊阶段；             
