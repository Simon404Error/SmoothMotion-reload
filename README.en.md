# SmoothMotion-reload

**English** | [简体中文](README.md)

This repository is a fork of [pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version](https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version), maintained for personal use.

## What this is

The upstream project is a modified DLSSG (DLSS Frame Generation) build that brings Smooth Motion style AI frame interpolation to RTX 20-series and 30-series GPUs.
This fork is used to stay compatible with the *Helldivers 2* BOX trainer; the personal modifications are not open-sourced yet.

## Repository layout

- `src/`: Vulkan route, proxy, NGX loader and renderer sources
- `include/renderer/`: renderer headers (D3D9 / Vulkan)
- `vulkan/`: prebuilt Vulkan component DLLs and `SHA256SUMS.txt`
- `VULKAN_SUPPORT.md`: current Vulkan support notes
- `CMakeLists.txt`: CMake build entry point

## Getting and installing

Use the complete archives from the upstream Releases page; this repository does not publish install packages.
Fully exit the game first and back up any proxy DLL and INI files already present in the game folder.

## License

MIT, see [LICENSE](LICENSE).

## Links

- Upstream repository: <https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version>
- Upstream releases: <https://github.com/pipotoufikxyz-lgtm/dlssg_for_sm86-MFG-version/releases>
- Language: [简体中文](README.md)
