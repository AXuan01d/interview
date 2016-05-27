
##personal interview (个人面试总结)
### 实习期间研发工程师面试总结
* map的实现原理和红黑树（关联容器和顺序容器的区别）
* vector和map迭代器失效的问题（map需要一个额外的迭代器赋值对象记录下一个位置(erase(it++)，vector则不要在it++,注意erase在for循环使用啊 啊）
* string的三种实现方式
* 虚函数的实现机制（虚函数表，时间和内存开销），多重继承下的虚函数表
* 重载的实现原理（函数的改名机制）：返回类型+函数名+参数
* 构造函数不能是虚函数
* C++ static ，指针和引用
* strcpy和memcpy的功能和区别是什么？
* 内存泄露的定位
* ISO七层简介
* c++的动态绑定
* extern修饰符可用于指示C或者C＋＋函数的调用规范。比如在C＋＋中调用C库函数，就需要在C＋＋程序中用extern “C”声明要引用的函数。这是给链接器用的，告诉链接器在链接的时候用C函数规范来链接。主要原因是C＋＋和C程序编译完成后在目标代码中命名规则不同.
* Rule of three （析构函数、拷贝构造函数和重载赋值函数），如果成员有指针，那么多个指针指向同一块内存，防止浅拷贝在析构时同一块内存区将被释放多次。
* 为什么要使用构造函数初始化表
* STL中存储auto_ptr，不支持拷贝赋值，转移所有权，p1=p2后p2失效
* new的时候虚拟内存和物理内存
* vector和map使用erase迭代器失效的问题（v: it=v.erase; m: m.erase(it++)）
* sizeof和strlen的区别，（sizeof编译时，strlen运行时）
* 快排，桶排序，基数排序
* 稳定排序和不稳定排序
* 反转单词，两次翻转解决；先反转单词，再逆序输出
* new和malloc的区别，这部分仔细看下，主要区别：
* C++内存分配，linux内存分配，虚拟内存①new 是c++中的操作符，malloc是c 中的一个函数
②new 不止是分配内存，而且会调用类的构造函数，同理delete会调用类的析构函数，而malloc则只分配内存，不会进行初始化类成员的工作，同样free也不会调用析构函数
* 服务端常用游戏框架，skynet，U3D，Polemo，KBengine，Cocos2d
* sed,awk的使用
* STL内存分配和traits技法
* C++四大类型强制转换
* 了解boost库
* Linux进程调度采用的是抢占式多任务处理（优先级调度），所以进程之间的挂起和继续运行无需彼此之间的协作。
* SYN Flood攻击，TCP三次握手的漏洞：修改半连接时间；IP cookie；更改DNS解析获得新的IP
* 读写锁和互斥锁
* 协程，CAS无锁队列，Retry_loop(可以理解为锁的粒度变小，只锁head和tail)
* strlen的递归实现和strcpy的代码
* 搜索引擎的工作原理
* 动态链接库，布隆过滤器
* 内存池的实现
* KV存储系统，redis
* cache的典型实现：双向链表套map，hash表是用来访问数据的，因为hash的查找速度快，O(1)。双向链表是用来记录最近访问情况的，因为Hash做不到排序
 
