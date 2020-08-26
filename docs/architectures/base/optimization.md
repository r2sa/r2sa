# 性能优化

### 代码优化层次 (java为例，其他语言类比)
- 循环遍历是否合理
	- 不要在循环里调用RPC接口、查询分布式缓存、执行sql等
	- 先调批量接口组装好数据，再循环处理
- 代码逻辑避免生成过多对象或无效对象
	- 输出log时候的log级别判断，避免new无效对象
- ArrayList、HashMap 初始容量是否合理
	- 扩容代价
- 对数据对象是否合理重用，比如通过RPC查到的数据能复用择必须复用
- 根据数据访问特性选择合适的数据结构
	- 比如读多写少，考虑CopyOnWriteArrayList(写时拷贝副本)
- 拼接字符串时是使用String相加还是使用StringBuilder进行append
	- 在StringBuilder的容量预分配的情况下比String相加快5倍
- 是否正确初始化数据
	- 有些全局共享的数据，饿汉式模式，在用户访问之前先初始化好
- 局部性原理
	- CPU cache结构
	- [如何理解计算机操作系统中的局部性原理？](https://www.zhihu.com/question/25142664)
- 缓存

### 数据库代码优化层次
- 数据库建表选择尽量小的数据结构
	- eg:代表状态的字段，使用unsigned tinyint; IP使用int而非varchar
- 使用enum的场景用tinyint替代，enum修改需要改表
- 避免select * ，只查询需要的字段，避免浪费IO、内存等