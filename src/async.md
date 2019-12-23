# Asynchronous Programming in Rust

- 文档：<https://rust-lang.github.io/async-book/index.html>

目前Rust生态中主流的异步运行时有两个，分别是Tokio和async-std。

Tokio是Rust生态中主流的异步运行时，正在向使用新的async-await语法迁移。

Async-std是新出现(2019年9月26日发布1.0版本)的异步运行时实现，通过模仿标准库(std)实现相应的异步API来降低开发者的学习成本。

- 开源项目：tokio <https://tokio.rs/>
- 开源项目：async-std <https://async.rs/>

## 学习进度记录

- [ ] 1. Getting Started
  - [ ] 1.1. Why Async?
  - [ ] 1.2. The State of Asynchronous Rust
  - [ ] 1.3. async/.await Primer
  - [ ] 1.4. Applied: HTTP Server
- [ ] 2. Under the Hood: Executing Futures and Tasks
  - [ ] 2.1. The Future Trait
  - [ ] 2.2. Task Wakeups with Waker
  - [ ] 2.3. Applied: Build an Executor
  - [ ] 2.4. Executors and System IO
- [ ] 3. async/await
- [ ] 4. Pinning
- [ ] 5. Streams
  - [ ] 5.1. Iteration and Concurrency
- [ ] 6. Executing Multiple Futures at a Time
  - [ ] 6.1. join!
  - [ ] 6.2. select!
  - [ ] 6.3. TODO: Spawning
  - [ ] 6.4. TODO: Cancellation and Timeouts
  - [ ] 6.5. TODO: FuturesUnordered
- [ ] 7. Workarounds to Know and Love
  - [ ] 7.1. Return Type Errors
  - [ ] 7.2. ? in async Blocks
  - [ ] 7.3. Send Approximation
  - [ ] 7.4. Recursion
  - [ ] 7.5. async in Traits
- [ ] 8. TODO: I/O
  - [ ] 8.1. TODO: AsyncRead and AsyncWrite
- [ ] 9. TODO: Asynchronous Design Patterns: Solutions and Suggestions
  - [ ] 9.1. TODO: Modeling Servers and the Request/Response Pattern
  - [ ] 9.2. TODO: Managing Shared State
- [ ] 10. TODO: The Ecosystem: Tokio and More
  - [ ] 10.1. TODO: Lots, lots more?...
