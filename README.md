# SmoothMotion-reload

English users please translate into English by yourselves

本仓库是 [pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version](https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version) 的 fork

## 这是什么

上游项目是一个 DLSSG（DLSS 帧生成）修改版，为 RTX 20 系 / 30 系显卡提供 Smooth Motion AI 插帧

## 与上游仓库的区别

1.兼容《绝地潜兵2》(Helldivers 2) 的 BOX 修改器，这部分修改暂未开源。
2.为 Manager 添加了启动时是否扫描游戏的开关

## 仓库内容

- `src/`：Vulkan 路由 / 代理 / NGX 加载器与渲染器源码
- `include/renderer/`：渲染器头文件（D3D9 / Vulkan）
- `vulkan/`：预编译 Vulkan 组件 DLL 及 `SHA256SUMS.txt`
- `VULKAN_SUPPORT.md`：Vulkan 支持现状说明
- `CMakeLists.txt`：CMake 构建入口

## 获取与安装

你可以直接下载本仓库的发行版

也可以访问上游仓库获取你的工具

## 鸣谢

- 上游仓库：<https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version>

## 许可

MIT，详见 [LICENSE](LICENSE)。
