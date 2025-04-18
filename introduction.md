# CVs

## 个人简介

充满激情、注重细节的开发者，拥有扎实的 C++ 和 Python 编程基础，对后端开发充满热情。 具备良好的问题解决能力和团队合作精神。 积极探索新技术，致力于构建高性能、可扩展的应用程序。 期望在充满挑战的环境中不断成长，为团队做出贡献。

## 教育背景

**相关课程:** 数据结构、操作系统、计算机网络、数据库原理、算法设计与分析、C++程序设计与应用、计算机组成原理、Java 程序设计基础、计算机图形学

## 技能

### 编程语言

- **C++:** 熟练掌握 C++ 语言特性（C++11/14/17/20 标准），理解 STL 库 (容器、算法、迭代器、函数对象)。 具备使用 AddressSanitizer 和 MemorySanitizer 进行内存问题检测的经验。熟悉数据结构与算法，了解操作系统原理。 熟练掌握并发与多线程编程 (Thread, Mutex, Condition Variable, Atomic)， 熟练使用智能指针管理内存，避免内存泄漏。 熟练使用 CMake 构建项目，使用 GDB 进行调试，并利用 Valgrind 进行内存泄漏检测。 熟悉 Boost.Asio 库，理解异步 I/O 和多线程编程模型。
- **Python:** 熟悉 Python 编程，能够熟练运用 Pandas、Scikit-learn、NumPy 等库进行数据分析、机器学习和科学计算任务。具备使用 Python 进行脚本编写和自动化处理的能力。 熟悉 Django/Flask Web 框架，能快速开发 RESTful API.
- **Rust:** 了解 Rust 编程语言的基本概念，包括所有权系统、借用规则和生命周期等，并进行过初步的实践。

### 后端技术

- 熟悉 C++ 后端开发，包括 TCP/IP 网络编程、HTTP 协议、多线程并发处理、Socket 编程、进程间通信(IPC)。 熟悉 MySQL 数据库，能够进行 SQL 查询优化 (索引优化、查询语句优化) 和数据库设计。 了解常用的设计模式 (单例模式、工厂模式、观察者模式)，并能够灵活运用到实际开发中。 熟悉 RESTful API 设计， 了解 gRPC 框架。 了解微服务架构设计原则和实践.
- 熟悉 NoSQL 数据库 (Redis, MongoDB)，了解其适用场景和优缺点.

### 开发工具/技术栈

- **工具:** CMake, GDB, Valgrind, AddressSanitizer, MemorySanitizer, Git, Docker, Docker Compose, Wireshark, Android Studio, Visual Studio Code, CLion
- **技术栈:** Boost.Asio, Protocol Buffers, gRPC, MySQL, Redis, Linux Shell Scripting, Nginx, Docker, Kubernetes
- 熟悉 Linux 操作系统，能够在 Linux 环境下进行开发和调试。 熟练掌握 Linux 常用命令，能够进行系统管理和故障排查。 精通 Shell 脚本编程，能够编写复杂的自动化脚本.
- 熟练使用 Git 进行版本控制，熟悉 Gitflow 工作流程， 能够进行代码合并、分支管理和冲突解决。 熟悉 GitHub Actions/GitLab CI， 具备持续集成/持续部署(CI/CD)经验.
- 熟悉 Docker 容器技术，能够使用 Docker 进行应用镜像制作、部署和管理。 了解 Kubernetes 容器编排，能够进行应用部署、扩容和监控.

## 项目经验

### C++ 服务器框架 (Boost.Asio)

开发了一个基于 Boost.Asio 构建的轻量级、高性能服务器框架，旨在提供一个易于扩展和定制的服务器端解决方案。

- **技术栈：** C++, Boost.Asio, CMake, Linux, Protocol Buffers, gRPC, Docker

- **职责：**独立设计并实现了框架的核心组件，包括 Server, Connection, IOContext, ThreadPool, RequestHandler, ProtocolHandler。 深入研究 Boost.Asio 的异步非阻塞 I/O 操作，并将其应用于框架中，实现了高并发连接处理能力。 采用 Protocol Buffers 进行数据序列化和反序列化，提高了数据传输效率和安全性。 采用模块化设计思想，支持自定义协议和请求处理程序，提高了框架的灵活性和可扩展性。 实现了多线程处理机制，使用线程池管理连接和请求，有效提高了服务器的吞吐量。 为了方便用户使用，提供了一个 HTTP 服务器示例，演示了框架的基本功能和使用方法。 使用 Docker 进行了应用容器化部署，方便快速部署和迁移。

- **关键成果：**构建了一个高性能、可扩展的服务器框架，并成功部署到 Linux 环境中。 实现了可配置的线程池，能够根据硬件资源和实际工作负载动态调整线程数量，优化资源利用率。 完善了错误处理和日志记录机制（使用 spdlog），提高了框架的健壮性和可维护性。 通过性能测试 (使用 wrk)，该框架能够支持每秒数千个并发连接，平均响应时间低于 1ms，满足了高并发应用的需求。

### Android 视频播放器 (C++工程师训练营结营项目)

开发了一款跨平台的 Android 视频播放器应用，旨在提供流畅、高效的视频播放体验。

- **技术栈：** Java, C++, JNI, FFmpeg, OpenSL ES, ANativeWindow, Android SDK, CMake

- **职责：**负责使用 FFmpeg (C++) 进行多种视频格式的解码工作，并将解码后的视频帧转换为 YUV 格式。 利用 OpenSL ES 实现了低延迟的音频播放功能，保证音视频同步。 熟练使用 C++ 和 JNI 进行原生开发，实现了性能关键型任务，例如视频解码和渲染。 通过 ANativeWindow 将 YUV 帧直接渲染到 SurfaceView 上，有效优化了视频显示效率，提升了播放流畅度。 采用 ExecutorService 管理并发任务 (解码、渲染、音频播放)，有效防止阻塞 UI 线程，保证了应用界面的响应速度。 使用 CMake 构建 C++ 代码，方便跨平台编译和部署。

- **关键成果：**实现了播放速度控制（通过原生代码跳帧实现）、暂停/恢复功能、音视频同步等核心功能。 通过 C++ 原生开发和深度优化，成功实现了一个高效且可定制的多媒体播放器，能够满足用户对高质量视频播放的需求。 显著优化了视频显示效率，保证了在低端设备上也能获得流畅的播放体验。 通过该项目，深入掌握了 Android 平台的多媒体开发技术，为后续的音视频相关项目打下了坚实的基础。 使用了 logcat 进行调试，并使用 Android Profiler 进行性能分析.

## 奖项荣誉及证书

- 英语六级证书 (500+)
- 全国大学生数学竞赛二等奖
