# BaiNiaoGKD 问题反馈仓库

[English](README_EN.md) | 简体中文

---

### 仓库说明

长期以来，BaiNiaoGKD 主要在中国地区社区交流。由于我大部分时间专注于核心功能开发，精力有限，较少涉足大规模的社区运营，因此设立本公开仓库，主要用于方便海外用户及习惯使用 GitHub 的用户集中提交 Bug 与需求反馈。

---

### 建议与问题反馈指南

您可以在本仓库的 [Issues](../../issues) 中提交使用过程中遇到的问题或改进建议。

为便于快速定位与验证，建议在提交 Issue 时附带以下信息：

- **运行平台**：操作系统（Windows / Linux / Android）及版本；
- **软件版本**：BaiNiaoGKD 客户端版本（Android 端建议附带 System WebView 版本）；
- **问题描述**：涉及的具体模块或相册，以及清晰、可复现的操作步骤；
- **辅助信息**：相关的控制台报错日志、截图或录屏（如有）。

> **处理流程**：我会定期梳理与评估 Issues，针对确认的缺陷与有价值的功能建议，将在后续版本发布计划中统筹安排与实现。

---

### 源码说明

BaiNiaoGKD 始终遵循开源与免费的原则。

- 由于项目工程体量庞大、涉及较多子模块及特殊的分发机制，主项目仓库暂未直接在 GitHub 公开；
- **获取完整源代码**：每个正式发布的版本安装包中均附带完整源代码（请参阅发布包内的 `源代码/appOriginal` 目录）；
- **独立开源子项目**：项目中的部分底层引擎与工具链已作为独立仓库在 GitHub 持续维护，欢迎查阅：
    - [unityfs-js](https://github.com/bainiao404/unityfs-js) / [unityfs-js-gui](https://github.com/bainiao404/unityfs-js-gui)：高性能纯 JavaScript / WASM Unity AssetBundle 解析与提取套件
    - [simple-pixi-spine](https://github.com/bainiao404/simple-pixi-spine)：基于 PixiJS 的轻量 Spine 运行时适配库
    - [FennecView](https://github.com/bainiao404/FennecView)：多格式动图与骨骼动画（Spine / Live2D）预览与转换工具

---

### 如何参与开发

随着 BaiNiaoGKD 功能的持续增加，仅凭我个人的精力维护整个体系覆盖面较为有限。若您有意愿长期参与项目的协同维护、代码提交或功能迭代，欢迎通过 Issue 与我联系，交流后将为您开通项目协作与维护权限。

---

### 免责声明与使用条款

1. 本项目仅供技术研究、学习与交流使用，请勿用于任何商业目的；
2. 本软件完全免费，严禁任何形式的倒卖、转售或收费捆绑行为。
