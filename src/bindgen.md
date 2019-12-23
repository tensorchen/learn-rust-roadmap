# The bindgen User Guide

[`bindgen`](https://rust-lang.github.io/rust-bindgen/introduction.html) 自动生成调用C/C++库Rust文件。

## 学习进度记录

- [ ] 1. Introduction
- [ ] 2. Requirements
- [ ] 3. Library Usage with build.rs
  - [ ] 3.1. Tutorial
    - [ ] 3.1.1. Add bindgen as a Build Dependency
    - [ ] 3.1.2. Create a wrapper.h Header
    - [ ] 3.1.3. Create a build.rs File
    - [ ] 3.1.4. Include the Generated Bindings in src/lib.rs
    - [ ] 3.1.5. Write a Sanity Test
    - [ ] 3.1.6. Publish Your Crate!
- [ ] 4. Command Line Usage
- [ ] 5. Customizing the Generated Bindings
  - [ ] 5.1. Whitelisting
  - [ ] 5.2. Blacklisting
  - [ ] 5.3. Treating a Type as an Opaque Blob of Bytes
  - [ ] 5.4. Replacing One Type with Another
  - [ ] 5.5. Preventing the Derivation of Copy and Clone
- [ ] 6. Generating Bindings to C++
- [ ] 7. Using Unions
- [ ] 8. Using Bitfields
- [ ] 9. FAQ
