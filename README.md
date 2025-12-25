# AI 实习日志 | AI Internship Logs

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/) [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)

**大一升大二暑期实习 | AI研发工程师 | 智能广告审核系统**

[中文](#项目简介) | [English](#project-overview)

---

## 项目简介

这是我作为 **AI研发工程师** 实习期间的技术学习与实践记录，共计 **46篇** 技术日志，涵盖：

| 领域 | 内容 |
|------|------|
| **AI/LLM** | 多模态模型、ReAct架构、提示词工程、工具调用 |
| **Docker** | 容器化部署、显存优化、镜像配置 |
| **Python** | FastAPI开发、异步编程、性能优化 |
| **系统设计** | 智能审核系统、规则解析器、数据验证 |

---

## 实习项目概述

在为期三个月的实习期间，我参与了企业级智能审核系统的研发工作，旨在重构传统的广告审核流程。

### 项目背景

在医疗器械、保健食品等特殊领域，广告内容的合规性审核具有很强的专业性和复杂性。传统的人工审核模式面临着：

- **效率低下**：人工逐条审核耗时耗力
- **标准不统一**：不同审核员判断标准存在差异
- **难以规模化**：业务增长时审核能力无法快速扩展

### 技术架构演进

项目经历了三个关键阶段：

**阶段一：基础功能构建**
- 实现 OCR 和基础图像分析功能
- 遇到显存管理、准确率和性能问题

**阶段二：架构重构与优化**
- 设计智能显存管理系统
- 引入多模态 AI 模型
- 实现异步处理框架

**阶段三：智能化升级**
- 实现基于 ReAct 的决策系统
- 模拟人类专家思维方式进行多步推理和验证

### 核心成果

| 指标 | 成果 |
|------|------|
| 显存使用峰值 | ↓ 75% |
| 处理成功率 | 99.9% |
| 系统准确率 | ↑ 95%+ |
| 响应时间 | 小时级 → 分钟级 |

### 技术亮点

- **智能显存管理**：通过实时监控和动态调整，显存使用峰值降低 75%，处理成功率达 99.9%
- **多模态 AI 集成**：结合视觉和语言模型，系统准确率提升至 95% 以上
- **异步处理框架**：通过并行处理和资源池化，响应时间从小时级降至分钟级
- **ReAct 决策机制**：结合思维链和工具调用，实现复杂场景下的多步推理，模拟人类专家决策过程

---

## 核心技术实践

### 大语言模型应用

- **提示词工程**：设计结构化提示模板，实现精确的指令控制和输出格式化
- **工具调用**：构建可靠的工具调用机制，处理边缘情况和容错机制
- **多模态分析**：实现图文一体化分析，提取关键信息并进行交叉验证

### 规则处理与验证

- **规则解析器**：设计高效灵活的规则解析系统，将法规文本转化为结构化数据
- **大文本处理**：实现智能分段算法，处理超长文本的内容理解和上下文维护
- **规则模型设计**：基于 Pydantic 构建类型安全的数据模型，实现自动验证

### 系统优化

- **性能调优**：实现多级缓存、并行处理和资源池化
- **错误处理**：设计多层次异常捕获和优雅降级策略
- **数据迁移**：设计数据结构优化和迁移方案，降低存储空间并提升处理速度

---

## 目录

### 按主题浏览

<details>
<summary><b>Docker 与环境配置</b> (8篇)</summary>

| # | 标题 |
|---|------|
| 2 | [Docker与Conda环境配置](实习日志/2.md) |
| 3 | [Docker生态系统与开发环境配置](实习日志/3.md) |
| 4 | [Docker环境配置优化：镜像源与网络配置](实习日志/4.md) |
| 5 | [Docker环境配置与最佳实践](实习日志/5.md) |
| 6 | [Langchain-Chatchat项目的Docker化部署](实习日志/6.md) |
| 7 | [Docker容器化部署实践](实习日志/7.md) |
| 17 | [Docker显存优化与异步编程实践](实习日志/17.md) |
| 27 | [Docker性能调优实践](实习日志/27.md) |

</details>

<details>
<summary><b>Python 工程实践</b> (8篇)</summary>

| # | 标题 |
|---|------|
| 8 | [Python虚拟环境与开发环境配置](实习日志/8.md) |
| 9 | [Python跨平台开发与依赖管理](实习日志/9.md) |
| 10 | [Mac环境下的Python虚拟环境与FastAPI部署](实习日志/10.md) |
| 18 | [API服务器配置与版本控制](实习日志/18.md) |
| 20 | [Python企业级应用开发实践](实习日志/20.md) |
| 28 | [Python数据分析与自动化](实习日志/28.md) |
| 29 | [实时数据处理与优化实践](实习日志/29.md) |
| 30 | [异步操作与资源管理优化](实习日志/30.md) |

</details>

<details>
<summary><b>AI/LLM 应用开发</b> (12篇)</summary>

| # | 标题 |
|---|------|
| 0 | [深度学习模型优化实践：显存管理与动态批处理](实习日志/0.md) |
| 19 | [AI场景开发与性能优化](实习日志/19.md) |
| 24 | [视觉识别与LLM优化：多模态分析](实习日志/24.md) |
| 31 | [多模态模型与广告分析](实习日志/31.md) |
| 33 | [ReAct架构与推理实践](实习日志/33.md) |
| 34 | [GPU资源管理与优化](实习日志/34.md) |
| 35 | [ReAct技术选择指南](实习日志/35.md) |
| 36 | [智能法规审核系统：模块化设计](实习日志/36.md) |
| 37 | [基于LLM的广告审核系统](实习日志/37.md) |
| 40 | [保健食品广告智能审核系统](实习日志/40.md) |
| 41 | [构建可靠的LLM工具调用系统](实习日志/41.md) |
| 44 | [基于Pydantic的规则模型设计](实习日志/44.md) |

</details>

<details>
<summary><b>广告审核系统</b> (6篇)</summary>

| # | 标题 |
|---|------|
| 21 | [保健食品广告自动审查系统](实习日志/21.md) |
| 22 | [数据验证与模型优化实践](实习日志/22.md) |
| 25 | [广告审核与模型训练](实习日志/25.md) |
| 26 | [多模态广告审核系统：ReAct架构](实习日志/26.md) |
| 42 | [规则解析器的设计与演进](实习日志/42.md) |
| 43 | [大规模法规文本的智能分段处理](实习日志/43.md) |

</details>

<details>
<summary><b>虚拟化与环境</b> (7篇)</summary>

| # | 标题 |
|---|------|
| 11 | [虚拟化技术与系统架构选择](实习日志/11.md) |
| 13 | [VMware Fusion虚拟机的创建与管理](实习日志/13.md) |
| 14 | [网络配置与远程开发环境](实习日志/14.md) |
| 15 | [虚拟机网络配置与开发工具链整合](实习日志/15.md) |
| 16 | [ARM虚拟机部署与PDF处理优化](实习日志/16.md) |
| 23 | [Mac开发环境与网络配置](实习日志/23.md) |
| 32 | [网络代理技术解析：TUN模式](实习日志/32.md) |

</details>

<details>
<summary><b>图像处理与其他</b> (5篇)</summary>

| # | 标题 |
|---|------|
| 1 | [图像对比系统优化](实习日志/1.md) |
| 12 | [图像对比系统的自适应内存管理](实习日志/12.md) |
| 38 | [Python与百度地图API集成](实习日志/38.md) |
| 39 | [自动化小区分析实践](实习日志/39.md) |
| 45 | [规则结构的优化与简化](实习日志/45.md) |

</details>

<details>
<summary><b>完整日志列表</b> (46篇)</summary>

| # | 中文 | English |
|---|------|---------|
| 0 | [深度学习模型优化实践](实习日志/0.md) | [Deep Learning Model Optimization](English_Internship_Logs/0.md) |
| 1 | [图像对比系统优化](实习日志/1.md) | [Image Comparison System Optimization](English_Internship_Logs/1.md) |
| 2 | [Docker与Conda环境配置](实习日志/2.md) | [Docker and Conda Environment Configuration](English_Internship_Logs/2.md) |
| 3 | [Docker生态系统与开发环境配置](实习日志/3.md) | [Docker Ecosystem and Development Environment](English_Internship_Logs/3.md) |
| 4 | [Docker环境配置优化](实习日志/4.md) | [Docker Configuration Optimization](English_Internship_Logs/4.md) |
| 5 | [Docker环境配置与最佳实践](实习日志/5.md) | [Docker Environment Best Practices](English_Internship_Logs/5.md) |
| 6 | [Langchain-Chatchat的Docker化部署](实习日志/6.md) | [Docker Deployment of Langchain-Chatchat](English_Internship_Logs/6.md) |
| 7 | [Docker容器化部署实践](实习日志/7.md) | [Docker Containerization Practices](English_Internship_Logs/7.md) |
| 8 | [Python虚拟环境与开发环境配置](实习日志/8.md) | [Python Virtual Environments Configuration](English_Internship_Logs/8.md) |
| 9 | [Python跨平台开发与依赖管理](实习日志/9.md) | [Python Cross-Platform Development](English_Internship_Logs/9.md) |
| 10 | [Mac环境下的FastAPI部署](实习日志/10.md) | [FastAPI Deployment on Mac](English_Internship_Logs/10.md) |
| 11 | [虚拟化技术与系统架构选择](实习日志/11.md) | [Virtualization Technology and Architecture](English_Internship_Logs/11.md) |
| 12 | [图像对比系统的自适应内存管理](实习日志/12.md) | [Adaptive Memory Management](English_Internship_Logs/12.md) |
| 13 | [VMware Fusion虚拟机管理](实习日志/13.md) | [VMware Fusion VM Management](English_Internship_Logs/13.md) |
| 14 | [网络配置与远程开发环境](实习日志/14.md) | [Network Configuration](English_Internship_Logs/14.md) |
| 15 | [虚拟机网络与工具链整合](实习日志/15.md) | [VM Network and Toolchain Integration](English_Internship_Logs/15.md) |
| 16 | [ARM虚拟机部署与PDF处理](实习日志/16.md) | [ARM VM Deployment and PDF Processing](English_Internship_Logs/16.md) |
| 17 | [Docker显存优化与异步编程](实习日志/17.md) | [Docker Memory Optimization](English_Internship_Logs/17.md) |
| 18 | [API服务器配置与版本控制](实习日志/18.md) | [API Server Configuration](English_Internship_Logs/18.md) |
| 19 | [AI场景开发与性能优化](实习日志/19.md) | [AI Scenario Development](English_Internship_Logs/19.md) |
| 20 | [Python企业级应用开发](实习日志/20.md) | [Python Enterprise Development](English_Internship_Logs/20.md) |
| 21 | [保健食品广告自动审查系统](实习日志/21.md) | [Health Food Ad Review System](English_Internship_Logs/21.md) |
| 22 | [数据验证与模型优化](实习日志/22.md) | [Data Verification and Optimization](English_Internship_Logs/22.md) |
| 23 | [Mac开发环境与网络配置](实习日志/23.md) | [Mac Dev Environment](English_Internship_Logs/23.md) |
| 24 | [视觉识别与LLM多模态分析](实习日志/24.md) | [Visual Recognition and LLM](English_Internship_Logs/24.md) |
| 25 | [广告审核与模型训练](实习日志/25.md) | [Ad Review and Model Training](English_Internship_Logs/25.md) |
| 26 | [多模态广告审核系统](实习日志/26.md) | [Multimodal Ad Review System](English_Internship_Logs/26.md) |
| 27 | [Docker性能调优实践](实习日志/27.md) | [Docker Performance Tuning](English_Internship_Logs/27.md) |
| 28 | [Python数据分析与自动化](实习日志/28.md) | [Python Data Analysis](English_Internship_Logs/28.md) |
| 29 | [实时数据处理与优化](实习日志/29.md) | [Real-Time Data Processing](English_Internship_Logs/29.md) |
| 30 | [异步操作与资源管理](实习日志/30.md) | [Async Operations and Resource Management](English_Internship_Logs/30.md) |
| 31 | [多模态模型与广告分析](实习日志/31.md) | [Multimodal Model and Ad Analysis](English_Internship_Logs/31.md) |
| 32 | [网络代理技术：TUN模式](实习日志/32.md) | [Network Proxy: TUN Mode](English_Internship_Logs/32.md) |
| 33 | [ReAct架构与推理实践](实习日志/33.md) | [ReAct Architecture and Reasoning](English_Internship_Logs/33.md) |
| 34 | [GPU资源管理与优化](实习日志/34.md) | [GPU Resource Management](English_Internship_Logs/34.md) |
| 35 | [ReAct技术选择指南](实习日志/35.md) | [ReAct Technology Guide](English_Internship_Logs/35.md) |
| 36 | [智能法规审核系统](实习日志/36.md) | [Intelligent Regulatory Review System](English_Internship_Logs/36.md) |
| 37 | [基于LLM的广告审核系统](实习日志/37.md) | [LLM-Based Ad Review System](English_Internship_Logs/37.md) |
| 38 | [Python与百度地图API集成](实习日志/38.md) | [Python and Baidu Map API](English_Internship_Logs/38.md) |
| 39 | [自动化小区分析实践](实习日志/39.md) | [Automated Community Analysis](English_Internship_Logs/39.md) |
| 40 | [保健食品广告智能审核系统](实习日志/40.md) | [Health Food Ad Intelligent Review](English_Internship_Logs/40.md) |
| 41 | [构建可靠的LLM工具调用系统](实习日志/41.md) | [Reliable LLM Tool Calling System](English_Internship_Logs/41.md) |
| 42 | [规则解析器的设计与演进](实习日志/42.md) | [Rule Parser Design and Evolution](English_Internship_Logs/42.md) |
| 43 | [大规模法规文本的智能分段](实习日志/43.md) | [Intelligent Text Segmentation](English_Internship_Logs/43.md) |
| 44 | [基于Pydantic的规则模型设计](实习日志/44.md) | [Pydantic Rule Model Design](English_Internship_Logs/44.md) |
| 45 | [规则结构的优化与简化](实习日志/45.md) | [Rule Structure Optimization](English_Internship_Logs/45.md) |

</details>

---

## 阅读指南

本仓库中的日志按时间顺序编号，但可以根据以下主题分类阅读：

### Docker 与环境配置
- [Docker与Conda环境配置](实习日志/2.md)
- [Docker生态系统与开发环境配置](实习日志/3.md)
- [Docker环境配置优化](实习日志/4.md)
- [Docker环境配置与最佳实践](实习日志/5.md)

### FastAPI 应用开发
- [图像对比系统优化](实习日志/1.md)
- [Mac环境下的Python虚拟环境与FastAPI部署](实习日志/10.md)
- [多模态广告审核系统：ReAct架构](实习日志/26.md)
- [实时数据处理与优化实践](实习日志/29.md)

### LLM 与智能系统
- [智能法规审核系统：模块化设计](实习日志/36.md)
- [基于LLM的广告审核系统](实习日志/37.md)
- [保健食品广告智能审核系统](实习日志/40.md)
- [构建可靠的LLM工具调用系统](实习日志/41.md)

### 数据处理与优化
- [规则解析器的设计与演进](实习日志/42.md)
- [大规模法规文本的智能分段处理](实习日志/43.md)
- [基于Pydantic的规则模型设计](实习日志/44.md)
- [规则结构的优化与简化](实习日志/45.md)

---

## 知识图谱

本仓库使用知识图谱组织技术内容，帮助在不同概念和技术之间建立连接，覆盖以下核心领域：

### 1. 技术架构与框架
- ReAct 架构
- 模块化系统设计
- FastAPI 应用开发

### 2. 大语言模型应用
- 提示词工程
- 工具调用
- 多模态分析
- LLM 输出解析与后处理

### 3. 数据处理与验证
- 规则解析
- 数据模型
- 文本处理
- JSON 处理

### 4. 系统优化与最佳实践
- 性能优化
- 错误处理
- 缓存策略
- 数据迁移与重构
- 异步编程模式

### 5. 测试与监控
- 测试策略
- 日志与监控

### 6. 工程实践与项目管理
- 代码组织与设计模式
- 版本管理与演进

**详细内容：**
- [中文知识图谱](知识图谱.md)
- [English Knowledge Map](Knowledge_Map.md)

---

## 技能成长

通过这段实习经历，我的技术能力得到了显著提升：

### 技术深度

| 方向 | 成长 |
|------|------|
| **AI应用开发** | 从基础模型应用到复杂系统集成 |
| **系统架构设计** | 从单一功能实现到模块化、可扩展架构 |
| **性能优化** | 掌握内存管理、并发控制、资源调度等核心技术 |

### 工程实践

- **开发流程**：掌握需求分析、架构设计、开发测试的完整流程
- **质量保障**：建立健全的测试、日志和监控体系
- **持续优化**：通过数据驱动的方法持续改进系统性能

### 业务理解

- **领域知识**：深入理解广告审核领域的专业知识和法规要求
- **价值转化**：将技术创新转化为业务价值，提升效率和准确率
- **用户视角**：从用户需求出发，优化系统交互和体验

---

## Project Overview

Technical learning records from my internship as an **AI Development Engineer**, containing **46 technical logs**.

### Background

During a three-month internship, I participated in developing an enterprise-level intelligent review system for advertisement compliance in specialized fields like medical devices and health foods.

### Technical Evolution

| Phase | Focus |
|-------|-------|
| **Phase 1** | Basic OCR and image analysis, facing memory and accuracy challenges |
| **Phase 2** | Architecture restructuring with intelligent memory management and multimodal AI |
| **Phase 3** | Intelligence upgrade with ReAct-based decision system |

### Key Achievements

| Metric | Result |
|--------|--------|
| Peak Memory Usage | ↓ 75% |
| Processing Success Rate | 99.9% |
| System Accuracy | ↑ 95%+ |
| Response Time | Hours → Minutes |

### Core Technical Practices

**LLM Applications**
- Prompt engineering with structured templates
- Reliable tool calling mechanisms with fault tolerance
- Multimodal analysis for text-image integration

**Rule Processing**
- Efficient rule parsing system for regulatory texts
- Intelligent segmentation for large text handling
- Type-safe data models with Pydantic

**System Optimization**
- Multi-level caching and parallel processing
- Graceful degradation strategies
- Data structure optimization and migration

---

## Contact

- **Email**: 1436286758@qq.com
- **GitHub**: [PDGGK](https://github.com/PDGGK)
