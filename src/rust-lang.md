# Rust 程序设计语言

- [ ] Rust 程序设计语言
- [ ] 前言
- [ ] 介绍
- [ ] 1. 入门指南
  - [ ] 1.1 安装
  - [ ] 1.2 Hello, World!
  - [ ] 1.3 Hello, Cargo!
- [ ] 2. 猜猜看游戏教程
- [ ] 3. 常见编程概念
  - [ ] 3.1 变量与可变性
  - [ ] 3.2 数据类型
  - [ ] 3.3 函数如何工作
  - [ ] 3.4 注释
  - [ ] 3.5 控制流
- [ ] 4. 认识所有权
  - [ ] 4.1 什么是所有权（3遍）
  - [ ] 4.2 引用与借用（2遍）
  - [ ] 4.3 Slices
- [ ] 5. 使用结构体组织相关联数据
  - [ ] 5.1 定义并实例化结构体
  - [ ] 5.2 一个使用结构体的示例程序
  - [ ] 5.3 方法语法
- [ ] 6. 枚举与模式匹配
  - [ ] 6.1 定义枚举（2遍）
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
  - [ ] 8.3. 哈希 map
- [ ] 9. 错误处理
  - [ ] 9.1. panic! 与不可恢复的错误
  - [ ] 9.2. Result 与可恢复的错误
  - [ ] 9.3. panic! 还是不 panic!
- [ ] 10. 泛型、trait 与生命周期
  - [ ] 10.1. 泛型数据类型
  - [ ] 10.2. trait：定义共享的行为
  - [ ] 10.3. 生命周期与引用有效性
- [ ] 11. 测试
  - [ ] 11.1. 编写测试
  - [ ] 11.2. 运行测试
  - [ ] 11.3. 测试的组织结构
- [ ] 12. 一个 I/O 项目：构建命令行程序
  - [ ] 12.1. 接受命令行参数
  - [ ] 12.2. 读取文件
  - [ ] 12.3. 重构以改进模块化与错误处理
  - [ ] 12.4. 采用测试驱动开发完善库的功能
  - [ ] 12.5. 处理环境变量
  - [ ] 12.6. 将错误信息输出到标准错误而不是标准输出
- [ ] 13. Rust 中的函数式语言功能：迭代器与闭包
  - [ ] 13.1. 闭包：可以捕获其环境的匿名函数
  - [ ] 13.2. 使用迭代器处理元素序列
  - [ ] 13.3. 改进之前的 I/O 项目
  - [ ] 13.4. 性能比较：循环对迭代器
- [ ] 14. 更多关于 Cargo 和 Crates.io 的内容
  - [ ] 14.1. 采用发布配置自定义构建
  - [ ] 14.2. 将 crate 发布到 Crates.io
  - [ ] 14.3. Cargo 工作空间
  - [ ] 14.4. 使用 cargo install 从 Crates.io 安装二进制文件
  - [ ] 14.5. Cargo 自定义扩展命令
- [ ] 15. 智能指针
  - [ ] 15.1. Box 指向堆上数据，并且可确定大小
  - [ ] 15.2. 通过 Deref trait 将智能指针当作常规引用处理
  - [ ] 15.3. Drop Trait 运行清理代码
  - [ ] 15.4. Rc 引用计数智能指针
  - [ ] 15.5. RefCell 与内部可变性模式
  - [ ] 15.6. 引用循环与内存泄漏是安全的
- [ ] 16. 无畏并发
  - [ ] 16.1. 线程
  - [ ] 16.2. 消息传递
  - [ ] 16.3. 共享状态
  - [ ] 16.4. 可扩展的并发：Sync 与 Send
- [ ] 17. Rust 的面向对象编程特性
  - [ ] 17.1. 面向对象语言的特点
  - [ ] 17.2. 为使用不同类型的值而设计的 trait 对象
  - [ ] 17.3. 面向对象设计模式的实现
- [ ] 18. 模式用来匹配值的结构
  - [ ] 18.1. 所有可能会用到模式的位置
  - [ ] 18.2. Refutability：何时模式可能会匹配失败
  - [ ] 18.3. 模式的全部语法
- [ ] 19. 高级特征
  - [ ] 19.1. 不安全的 Rust
  - [ ] 19.2. 高级 trait
  - [ ] 19.3. 高级类型
  - [ ] 19.4. 高级函数与闭包
  - [ ] 19.5. 宏
- [ ] 20. 最后的项目: 构建多线程 web server
  - [ ] 20.1. 单线程 web server
  - [ ] 20.2. 将单线程 server 变为多线程 server
  - [ ] 20.3. 优雅停机与清理
- [ ] 21. 附录
  - [ ] 21.1. A - 关键字
  - [ ] 21.2. B - 运算符与符号
  - [ ] 21.3. C - 可派生的 trait
  - [ ] 21.4. D - 实用开发工具
  - [ ] 21.5. E - 版本
  - [ ] 21.6. F - 本书译本
  - [ ] 21.7. G - Rust 是如何开发的与 “Nightly Rust”