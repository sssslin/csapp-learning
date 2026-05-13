# csapp-learning


## 简单说明

- sample目录用来存放书里涉及到的示例代码

- exercise用来存放我自己的补充练习代码

- labs目录用来存放lab相关的代码

  

## Labs 完整清单 (CS:APP 官网全部 11 个)

| # | Lab 名称 | 版本 | 对应章节 | 内容简介 | Self-Study Handout |
|---|---------|------|---------|---------|-------------------|
| 1 | Data Lab | 3e | 第2章 信息的表示和处理 | 用极有限的位运算实现整数和浮点函数 | `datalab-handout.tar` |
| 2 | Bomb Lab | 3e | 第3章 程序的机器级表示 | 逆向一个二进制炸弹，找出6个正确输入 | `bomb.tar` |
| 3 | Attack Lab | 3e（新） | 第3章 程序的机器级表示 | 对64位程序实施代码注入和ROP攻击 | `target1.tar` |
| 4 | Buffer Lab (IA32) | 2e（旧） | 第3章 程序的机器级表示 | 对32位程序实施缓冲区溢出攻击 | `buflab32-handout.tar` |
| 5 | Architecture Lab | 3e（新） | 第4章 处理器体系结构 | 优化Y86-64处理器流水线和程序 | `archlab-handout.tar` |
| 6 | Architecture Lab (Y86) | 2e（旧） | 第4章 处理器体系结构 | 同上，但基于旧的Y86指令集（32位） | `archlab32-handout.tar` |
| 7 | Cache Lab | 3e | 第6章 存储器层次结构 | 实现缓存模拟器 + 优化矩阵转置 | `cachelab-handout.tar` |
| 8 | Performance Lab | 2e | 第5章 优化程序性能 | 优化图像处理内核函数（卷积、旋转等） | `perflab-handout.tar` |
| 9 | Shell Lab | 通用 | 第8章 异常控制流 | 实现支持作业控制的Unix Shell | `shlab-handout.tar` |
| 10 | Malloc Lab | 通用 | 第9章 虚拟内存 | 实现malloc/free/realloc | `malloclab-handout.tar` |
| 11 | Proxy Lab | 3e | 第10-12章 网络编程/并发 | 实现并发缓存HTTP代理服务器 | `proxylab-handout.tar` |

### 版本替代关系

- **Attack Lab ↔ Buffer Lab (IA32)**：做同一件事（缓冲区溢出），Attack Lab 是64位新版并加入ROP攻击，Buffer Lab 是32位旧版。选 Attack Lab。
- **Architecture Lab ↔ Architecture Lab (Y86)**：新版用Y86-64指令集（64位），旧版用Y86（32位）。选新版。
- **Cache Lab ↔ Performance Lab**：CMU 官方用 Cache Lab 取代了 Performance Lab，Cache Lab 更全面。选 Cache Lab。

### 自学者实际要做的 8 个

Data Lab → Bomb Lab → Attack Lab → Architecture Lab（可选）→ Cache Lab → Shell Lab → Malloc Lab → Proxy Lab

Bomb Lab 和 Attack Lab 运行时需加 `-q` 参数跳过评分服务器连接。
