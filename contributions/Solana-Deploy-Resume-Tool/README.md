## 贡献仓库

 [baiqi-2019/Solana-Deploy-Resume-Tool](https://github.com/baiqi-2019/Solana-Deploy-Resume-Tool)

## 贡献概述

SolanaDeployResumeTool是一个智能的Solana程序部署续传工具，实现了断点续传、状态管理、费用优化、智能重试等功能，具有用户友好的可视化界面，提供友好的Web UI和实时监控。旨在解决Solana程序部署过程中存在的核心痛点，包括程序部署需要分批上传Buffer，消耗大量手续费，网络拥堵或其他原因导致上传失败时，已消耗的手续费无法返还，需要从头开始重新部署，造成经济损失和时间浪费等。让Solana程序部署更可靠、更经济、更方便、更快捷！

#### 🚀 核心功能

- 断点续传: 支持中断后从上次停止的位置继续部署，避免重复费用
- 智能分析: 实时网络状况分析，推荐最佳部署策略
- 费用优化: 根据网络拥堵程度动态调整费用策略，最大化成本效益
- 多版本支持: 同时支持BPF Loader v3和v4
- 可视化界面: 现代化Web界面，实时监控部署进度
- 状态管理: 持久化部署状态，支持多任务管理
- 智能重试: 自适应重试机制，提高部署成功率

#### 快速开始

前置要求

- Rust 1.70+

- Solana CLI工具

- 测试网SOL代币

#### 安装步骤

- 克隆项目: git clone https://github.com/baiqi-2019/Solana-Deploy-Resume-Tool
- cd Solana-Deploy-Resume-Tool
- 编译项目:  cargo build --release

cargo run --example demo
🌐 Web界面
启动Web服务器:

cargo run -- server --port 8080
然后打开浏览器访问: http://localhost:8080

## 贡献人联系方式:

Github: https://github.com/baiqi-2019
Telegram: @zhmzwsovo