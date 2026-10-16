# GlassDesk 更新

[下载 GlassDesk 1.3.5](https://github.com/everlosttime/glassdesk-updates/releases/tag/v1.3.5)

1.3.5 修复两项问题：

- 兼容 CC Switch 等快捷方式引用的无扩展名安装器图标资源，保留高分辨率原图，并改进失效图标路径的回退。
- 修复关闭 Wallpaper 等动态壁纸后，任务栏显隐等场景变化期间，静态采集像素被误判过期而导致 Dock 玻璃背景短暂闪暗的问题。

包含快捷方式、图标缓存、玻璃背景及场景有效性回归测试。升级保留设置、布局、应用库、用户自定义图标及启动配置，保持原有玻璃效果和采集质量。

此仓库提供公开安装包、SHA256SUMS.txt 和更新说明。设置 → 关于 → 检查更新可获取最新稳定版；安装包不包含用户 Data。适用于 Windows 11 x64 Build 22000 及以上，内置 .NET 10。

[最新更新 API](https://api.github.com/repos/everlosttime/glassdesk-updates/releases/latest)
