# GlassDesk 更新

[下载 GlassDesk 1.0.7](https://github.com/everlosttime/glassdesk-updates/releases/tag/v1.0.7)

1.0.7 优化鼠标快速扫过 Dock 时的放大动画，跟随渲染帧更新并减少重复布局和内存分配。启动台应用改为仅鼠标打开，移除点击后持续显示的蓝色边框，并提供短暂的图标按压反馈。

此仓库提供公开安装包、SHA256SUMS.txt 和更新说明。0.2.9 及之后的安装版可以从关于页检查更新；1.0.6 可以升级到此版本。升级保留配置、应用库、布局和图标缓存，安装包不包含用户 Data。

适用于 Windows 11 x64 Build 22000 及以上版本，内置 .NET 10 运行时，安装包未签名。Build 26100 使用已验证的背景采集路径；其他构建尝试完整桌面场景，不兼容时回退到系统窗口缩略图与静态壁纸背景，兼容路径不保证呈现第三方动态壁纸。

[最新更新 API](https://api.github.com/repos/everlosttime/glassdesk-updates/releases/latest)
