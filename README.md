
# IEC 61850 Rust 实现

本项目是 IEC 61850 协议的 Rust 实现，受 [libiec61850](https://github.com/mz-automation/libiec61850) 启发。

## 项目描述

该项目使用 Rust 语言实现 IEC 61850 标准，为电力系统设备间的通信提供高性能、内存安全的解决方案。IEC 61850 是国际电工委员会制定的变电站自动化系统通信协议标准。

## 特性

- 🦀 **Rust 实现**: 提供内存安全和高性能
- ⚡ **异步支持**: 基于 Tokio 的异步网络通信
- 🔒 **TLS 支持**: rustls 支持/native-tls
- 📡 **完整协议**: 支持 IEC 61850 的主要功能模块
- 🎯 **类型安全**: 利用 Rust 的类型系统确保协议正确性

## 架构

该库的架构分为以下几个主要模块：

- **common**: 包含共享类型、错误处理和实用工具
- **model**: 定义 IEC 61850 数据模型（逻辑设备、逻辑节点等）
- **client**: 提供客户端功能，用于连接和与 IEC 61850 服务器交互
- **server**: 提供服务器功能，用于实现 IEC 61850 服务器
- **mms**: 实现 MMS (Manufacturing Message Specification) 协议
- **goose**: 实现 GOOSE (Generic Object Oriented Substation Event) 协议
- **sv**: 实现 SV (Sampled Values) 协议


## 许可证

本项目使用 GNU General Public License v3.0 许可证。详见 [LICENSE](LICENSE) 文件。
