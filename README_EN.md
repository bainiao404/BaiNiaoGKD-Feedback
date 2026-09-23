# BaiNiaoGKD Issue Tracker

English | [简体中文](README.md)

---

### Repository Description

Historically, BaiNiaoGKD has primarily been shared and discussed within the Chinese community. As I spend most of my time focusing on core feature development and have limited energy for extensive community management, this public repository has been established mainly to allow international users and GitHub users to submit bug reports and feature requests in a centralized space.

---

### Feedback & Issue Guidelines

You can submit bug reports or suggestions for improvement in the [Issues](../../issues) section of this repository.

To facilitate fast reproduction and troubleshooting, please include the following details when opening an Issue:

- **Platform**: Operating system (Windows / Linux / Android) and its version;
- **App Version**: BaiNiaoGKD release version (on Android, please also include your System WebView version);
- **Description**: The specific module or gallery involved, along with clear and reproducible steps;
- **Supporting Media**: Console error logs, screenshots, or screen recordings (if applicable).

> **Triage Process**: I regularly review and triage Issues. Confirmed bugs and valuable feature suggestions will be scheduled and implemented in future releases.

---

### Source Code Notice

BaiNiaoGKD always adheres to the principles of open source and free sharing.

- Due to the large codebase size, multiple independent submodules, and specific distribution mechanisms, the main project is not hosted publicly on GitHub as a monorepo;
- **Access to Full Source Code**: Complete source code is included with every officially released version (please refer to the `源代码/appOriginal` directory in the release archive);
- **Standalone Open-Source Subprojects**: Core underlying engines and toolchains from the project are actively maintained as independent repositories on GitHub:
    - [unityfs-js](https://github.com/bainiao404/unityfs-js) / [unityfs-js-gui](https://github.com/bainiao404/unityfs-js-gui): High-performance pure JavaScript / WASM Unity AssetBundle parsing and extraction suite
    - [simple-pixi-spine](https://github.com/bainiao404/simple-pixi-spine): Lightweight PixiJS runtime wrapper for Spine animations
    - [FennecView](https://github.com/bainiao404/FennecView): Multi-format animation and skeletal model (Spine / Live2D) preview and conversion tool

---

### How to Contribute

As BaiNiaoGKD continues to expand, maintaining the entire system single-handedly has limited coverage. If you are interested in long-term collaboration, submitting code, or driving feature iterations, please feel free to reach out by opening an Issue. Collaborator and maintainer permissions can be granted after initial communication.

---

### Disclaimer & Terms of Use

1. This project is intended solely for technical research, study, and educational exchange. It may not be used for any commercial purposes;
2. This software is **completely free of charge**. Any form of resale, commercial bundling, or paid redistribution is strictly prohibited.
