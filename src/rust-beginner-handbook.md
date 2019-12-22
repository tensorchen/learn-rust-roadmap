# Rust新人学习手册

你好，`Rustacean`。当你读到这里时你已经成为一名在Rust社区广泛使用称呼Rust开发者，爱好者的称呼`Rustacean`。下面开始Rust学习之旅。

[TOC]

## 概述

Rust是一种使每个人都可以构建可靠、高效软件的编程语言。

Rust是一种系统级编程语言，注重高性能、可靠性和生产力，支持结构化编程、函数式编程、面向对象编程等多种编程范式。

Rust是编译型语言，没有运行时(Runtime)和垃圾回收(Garbage Collector)。Rust使用所有权机制来实现自动内存管理，并以此来保证内存安全。Rust是开源项目，目前托管在Github上，Rust和所有其他官方项目都采用Apache许可证2.0和MIT许可证双重许可。

**2019年11月7日**
Rust发布了1.39.0版本，async-await语法稳定(stable)。

async-await是基于Future的异步编程方法，async-await语法稳定对Rust异步生态系统的发展影响巨大。

**2019年4月23日**
Rust核心团队(The Rust Core Team)发布2019年Rust路线图，主题：成熟(Maturity)。

简而言之，2019年将是Rust项目复兴和成熟的一年。重点主要放在加强基础、偿还技术和组织债务上。

**2018年12月6日**
Rust发布了1.31.0版本，交付Rust的第二个里程碑版本Rust 2018。

Rust以软件包为单位设置Rust版本，Rust 2018的软件包可以和Rust 2015的软件包无缝协同工作。Rust 2018引入了一些新特性，比如非词法生命周期(non-lexical lifetimes)，const fn，以及简化的模块系统等。

**2015年5月15日**
Rust正式发布1.0版本，这是Rust的第一个里程碑版本Rust 2015。

这意味着Rust的语法和标准库已经稳定，以后发布的新版本可以前向兼容。也代表Rust可以开始应用于生产环境。

## Rust语法篇

本篇内容主要提供Rust基础必要语法学习指引。涉及如下两本书籍。

- [Rust程序设计语言](https://doc.rust-lang.org/book/) ([中文译本](https://kaisery.github.io/trpl-zh-cn/))
- [Rust异步编程](https://rust-lang.github.io/async-book/index.html) ([中文译本](https://github.com/chinanf-boy/async-book-zh))

如下为提取后书籍重点章节（使用markdown多选框语法），推荐你阅读每个章节后调整`[ ]`为`[x]`，即将空格替换为x，记录自己的学习进度。

### Rust程序设计语言

如下《Rust程序设计语言》相较于原生章节，删除了各种高级特性，删除了示例程序，删除了crate发布到crate.io等相关内容。**此外请不要忽略附录章节**。

- [ ] Rust 程序设计语言
- [ ] 前言
- [ ] 介绍
- [ ] 1. 入门指南
  - [ ] 1.1 安装
  - [ ] 1.2 Hello, World!
  - [ ] 1.3 Hello, Cargo!
- [ ] 3. 常见编程概念
  - [ ] 3.1 变量与可变性
  - [ ] 3.2 数据类型
  - [ ] 3.3 函数如何工作
  - [ ] 3.4 注释
  - [ ] 3.5 控制流
- [ ] 4. 认识所有权
  - [ ] 👍4.1 什么是所有权
  - [ ] 4.2 引用与借用
  - [ ] 4.3 Slices
- [ ] 5. 使用结构体组织相关联数据
  - [ ] 5.1 定义并实例化结构体
  - [ ] 5.3 方法语法
- [ ] 6. 枚举与模式匹配
  - [ ] 6.1 定义枚举
  - [ ] 6.2 match 控制流运算符
  - [ ] 6.3 if let 简洁控制流
- [ ] 7. 使用包, Crate和模块管理不断增长的项目
  - [ ] 7.1 包和Crate
  - [ ] 7.2 定义模块来控制作用域与私有性
- [ ] 7. 使用包、Crate 和模块管理不断增长的项目
  - [ ] 7.1. 包和 crate
  - [ ] 7.2. 定义模块来控制作用域与私有性
  - [ ] 7.3. 路径用于引用模块树中的项
  - [ ] 7.4. 使用 use 关键字将名称引入作用域
  - [ ] 7.5. 将模块分割进不同文件
- [ ] 8. 常见集合
  - [ ] 8.1. vector
  - [ ] 8.2. 字符串
- [ ] 9. 错误处理
  - [ ] 9.1. panic! 与不可恢复的错误
  - [ ] 9.2. Result 与可恢复的错误
  - [ ] 9.3. panic! 还是不 panic!
- [ ] 10. 泛型、trait 与生命周期
  - [ ] 10.1. 泛型数据类型
  - [ ] 10.2. trait：定义共享的行为
  - [ ] 10.3. 生命周期与引用有效性
- [ ] 13. Rust 中的函数式语言功能：迭代器与闭包
  - [ ] 13.1. 闭包：可以捕获其环境的匿名函数
  - [ ] 13.2. 使用迭代器处理元素序列
- [ ] 15. 智能指针
  - [ ] 15.1. Box 指向堆上数据，并且可确定大小
  - [ ] 15.2. 通过 Deref trait 将智能指针当作常规引用处理
  - [ ] 15.3. Drop Trait 运行清理代码
  - [ ] 15.4. Rc 引用计数智能指针
- [ ] 16. 无畏并发
  - [ ] 16.1. 线程
  - [ ] 16.2. 消息传递
  - [ ] 16.3. 共享状态
  - [ ] 16.4. 可扩展的并发：Sync 与 Send
- [ ] 17. Rust 的面向对象编程特性
  - [ ] 17.1. 面向对象语言的特点
  - [ ] 17.2. 为使用不同类型的值而设计的 trait 对象
  - [ ] 17.3. 面向对象设计模式的实现
- [ ] 19. 高级特征
  - [ ] 19.5. 宏
- [ ] 21. 附录
  - [ ] 21.1. A - 关键字
  - [ ] 21.2. B - 运算符与符号
  - [ ] 21.3. C - 可派生的 trait
  - [ ] 21.4. D - 实用开发工具
  - [ ] 21.5. E - 版本
  - [ ] 21.7. G - Rust 是如何开发的与 “Nightly Rust”

### Rust异步编程

《Rust异步编程》（__注：本书籍官方尚未完整编辑完成__）对于新人来说，需要学习的章节非常少，但都是非常重要的，建议必读。

- [ ] 1. Getting Started
  - [ ] 1.1. Why Async?
  - [ ] 1.2. The State of Asynchronous Rust
  - [ ] 1.3. async/.await Primer

## Rust文档篇

新人加入一个开发团队时，要干五件事。前面四件事是了解技术架构、了解开发流程、补强基础知识、从微小的改善入手（比如关掉几个 issue）。这些都是常识，但是第五件事，很多新人都没意识到，你应该要去做，而且完全有能力做，那就是 **你要写文档** 。

- 1.可以熟悉项目；
- 2.可以提高表达能力；
- 3.可以提高技术能力，因为只有理解了代码才能表达出来，文档越清晰，就代表思路越清晰；
- 4.可以提高个人影响力，文档写得越好，看的人就越多。久而久之，你就会成为项目的代言人，别人有问题就会来找你。

文档编写

- [Rustdoc](https://doc.rust-lang.org/rustdoc/index.html)

书籍编写（注：本手册同样使用mdbook编写完成）

- [mdBook](http://rust-lang.github.io/mdBook/index.html)

## Rust工程篇

本篇主要指引你了解Rust的工具链生态，工程组织，单元测试，集成测试，Benchmark等工程相关内容。

### 工程组织

<https://doc.rust-lang.org/cargo/guide/project-layout.html>

### 测试

**单元测试** <https://doc.rust-lang.org/book/ch11-01-writing-tests.html>
**集成测试** <https://doc.rust-lang.org/book/ch11-03-test-organization.html#integration-tests>
**Benchmark** <https://doc.rust-lang.org/unstable-book/library-features/test.html>
