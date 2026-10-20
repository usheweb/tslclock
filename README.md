# 唐三浪学习时钟 · 客户端安装包

本仓库**只存放打包产物，不含任何源码**，方便用户直接下载安装。

| 平台 | 文件 | 体积 | 说明 |
|---|---|---|---|
| Android | `android/tslclock_1.1.0_32.apk` | 28.35 MB | armeabi-v7a（32 位），适用于老旧设备 |
| Android | `android/tslclock_1.1.0_64.apk` | 32.01 MB | arm64-v8a（64 位），适用于绝大多数机型 |
| Windows | `windows/tslclock_0.1.0_windows_x64_setup.exe` | 2.64 MB | 64 位安装包（NSIS），双击安装 |
| macOS | `macos/tslclock_0.1.0_macos_arm64.dmg` | 3.98 MB | Apple Silicon（M 系列）安装包 |

## 安装提示

- **Android**：优先下载 `tslclock_1.1.0_64.apk`；若设备较旧（32 位）再下载 `_32.apk`。
  安装时系统可能提示「未知来源应用」，需在设置中允许后继续。
- **Windows**：安装包依赖系统的 **WebView2 运行时**（Win10 1803 及以上、Win11 已内置）。
  若系统缺少，安装程序会提示并引导安装。
- **macOS**：仅支持 Apple Silicon（M 系列芯片）。首次打开若提示「已损坏」或「无法验证开发者」，
  在「系统设置 → 隐私与安全性」中点「仍要打开」，或执行
  `xattr -dr com.apple.quarantine /Applications/唐三浪学习时钟.app`。

## 版本对应

| 仓库 | 版本 |
|---|---|
| Android（Flutter） | 1.1.0 |
| Windows / macOS（Tauri 桌面端） | 0.1.0 |

安装包的品牌、图标等资产不随源码开源许可（MIT）授权，详见各客户端源码仓库的说明。
