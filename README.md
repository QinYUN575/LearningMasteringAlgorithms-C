# LearningMasteringAlgorithms-C

Mastering Algorithms With C: 《算法精解：C 语言描述》

<img src="./book/logo.png" 
    alt="Mastering Algorithms C book logo"
    title="Mastering Algorithms C"
    style="padding-right:100px;" align="right" width="30%" high="" />

## 目录说明

- book: 电子书及原书代码

  - [./book/examples_pc](./book/examples_pc)
  - [./book/examples_unix](./book/examples_unix)

  - [./book/Oreilly.Mastering.Algorithms.with.C.pdf](./book/Oreilly.Mastering.Algorithms.with.C.pdf)
    原书英文版 PDF 格式

  - [./book/算法精解：C 语言描述(中文版).pdf](<./book/算法精解：C语言描述(中文版).pdf>)
    原书中文影印版 PDF 格式

  - [./book/README.md](./book/README.md)
  - [./book/logo.png](./book/logo.png)

- learning_src: 学习代码(中文注释)

  - [./learning_src/examples](./learning_src/examples)
  - [./learning_src/include](./learning_src/include)
  - [./learning_src/source](./learning_src/source)

- learning_notes: 学习笔记

  - [./image](./image)
  - [./Google C++ Style Guide.pdf](./learning_notes/Google%20C++%20Style%20Guide.pdf)
    Google C++ 编程风格指南
  - [《跟我一起写 Makefile (PDF 重制版)》](./learning_notes/Makefile.pdf)
  - ...


## 编程规范 && 辅助文档

- 代码规范&&参考

  [《Google 开源项目风格指南 (中文版)》](https://zh-google-styleguide.readthedocs.io/en/latest/)

* 源码构建&&测试

  examples 测试环境: linux GCC/CC

  Makefile 语法&&规则 : [《跟我一起写 Makefile》(在线)](https://seisman.github.io/how-to-write-makefile/index.html)

## Mastering Algorithms C

### 预备知识

- 概述

  - 数据结构概述
  - 算法概述
  - 小酌软件工程
  -

- 指针操作

- 递归

  - 迭代
  - 递归
  - 尾递归

- 算法分析
  - 时间复杂度/空间复杂度
  - 最好情况 |平均情况 |最坏情况
  - 大 O 分析法

### 数据结构

### 链表

链表的一些应用:

> 滚动列表
>
> 多项式计算
>
> 内存管理
>
> LISP(人工智能领域中一种非常重要的编程语言)
>
> 文件链式分配
>
> 其他数据结构(栈、队列、集合、哈希表、图等一些数据结构的实现依赖于链表)

- 单链表
  - 页帧管理
- 双向链表

- 循环链表
  - 单向循链表
  - 双向循环链表
  - 第二次机会置换法 |LUR 页面置换法
    - 最少使用算法 (LRU: Least Recently Used)

相关主题:

> 双向循环链表
>
> 链表数组
>
> 广义表
>
> 游标

### 栈和队列

- 栈 (LIFO)

  typedef Stack of List

- 队列 (FIFO)

  typdef Queue of List

  typdef Queue of Array | 循环队列

  应用例子: 事件处理机制

相关主题:

> 多态
>
> 双向队列
>
> 循环队列

### 集合

- 集合的基本定义

- 集合的基本操作

- 集合的特性

- 集合的抽象数据类型设计分析与实现
  typedef Set of List

- 集合覆盖

### 哈希表

> 最有效的检索方法: 散列

应用: 数据库系统, 符号表, 标签缓冲区, 数据字典, 关联数组

- 哈希函数

  选择一个好的哈希函数旨在近似均匀散列

  取余法

  乘法

  均匀散列

* 链式哈希表

  冲突解决: 链式桶 - bucket

* 链式哈希表的实现与分析

* 开地址哈希表

  冲突解决: 探查

    - 线性探查

    - 双散列

* 开地址哈希表的实现与分析

相关主题

> 直接寻址哈希表
>
> 线性同余发生器
>
> 二次探查法
>
> 通用散列
>



扩展: 解决哈希冲突的方法

  - 链地址法(链式哈希表)

  - 开放定址法(开地址哈希表)

    - 线性探查法
  
    - 平方探查法
  
    - 双散列函数探查法

  - 再哈希法

  - 建立公共溢出区


### 树

  - 二叉树

  - 树的周游算法
    - 遍历思想:
      - 深度优先
      - 广度优先
    - 遍历算法:
      - 先序遍历
      - 中序遍历
      - 后序遍历
      - 层级遍历
  - 树的平衡算法
  - 二叉搜索树
  - 树的旋转

应用:
  - 霍夫曼编码
  - 用户界面
  - 数据库系统
  - 表达式处理
  - 人工智能
  - 事件调度
  - 优先级队列



