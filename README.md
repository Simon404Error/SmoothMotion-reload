# SmoothMotion-reload

[English](README.en.md) | **简体中文**

本仓库是 [pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version](https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version) 的 fork，自用维护。

## 这是什么

上游项目是一个 DLSSG（DLSS 帧生成）修改版，为 RTX 20 系 / 30 系显卡提供 Smooth Motion 风格的 AI 插帧。
本 fork 的实际用途是兼容《绝地潜兵2》(Helldivers 2) 的 BOX 修改器；自用修改部分暂未开源。

## 仓库内容

- `src/`：Vulkan 路由 / 代理 / NGX 加载器与渲染器源码
- `include/renderer/`：渲染器头文件（D3D9 / Vulkan）
- `vulkan/`：预编译 Vulkan 组件 DLL 及 `SHA256SUMS.txt`
- `VULKAN_SUPPORT.md`：Vulkan 支持现状说明
- `CMakeLists.txt`：CMake 构建入口

## 获取与安装

请使用上游仓库 Releases 中的完整压缩包；本仓库不单独提供安装包。
安装前请完全退出游戏，并备份游戏目录中已有的代理 DLL 与 INI 文件。

## 许可

MIT，详见 [LICENSE](LICENSE)。

## 链接

- 上游仓库：<https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version>
- 上游 Releases：<https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version/releases>
- 语言：[English](README.en.md)
