# GlassDesk 公开更新

## 最新版本：GlassDesk 1.4.4

本次从公开版 1.4.0 更新至 1.4.4，汇总此前版本改进，并降低静止桌面时的后台 CPU 与内存占用。

- 玻璃背景在静止时低频更新；动态桌面在非交互时约 30Hz，交互动画期间按需提高刷新率。
- 缩短启动台后台进程保留时间，降低 .NET 内存驻留。
- 优化状态栏、控制中心、媒体播放和音频设备选择。
- 新增首次启动引导，并将更新说明检查与安装包下载分开。
- 设置中可选择夸克或百度网盘下载；升级保留用户设置、应用库、布局和自定义图标。

### 下载渠道

安装程序由作者上传到网盘。本仓库发布更新说明和版本信息，不托管安装程序。

夸克网盘：https://pan.quark.cn/s/037d0cd5080b
百度网盘：https://pan.baidu.com/s/1X_TFD0GMp8RJsRLNISjy_w?pwd=0a53
百度网盘提取码：0a53

如果网盘分享页还没有出现 GlassDesk-1.4.4-win-x64-Setup.exe，请等作者上传完成后再下载。

### 版本说明与校验

- [GlassDesk 1.4.4 更新说明](Release-notes-v1.4.4.txt)
- [安装包 SHA-256](SHA256SUMS-v1.4.4.txt)
- [GitHub 公开更新页](https://github.com/everlosttime/glassdesk-updates/releases/tag/v1.4.4)

适用于 Windows 11 x64，Build 22000 及以上，安装包自带 .NET 10。升级不会覆盖个人 Data。安装包未签名；安装前可用 SHA256 校验。

### 历史版本

- [GlassDesk 1.4.0](https://github.com/everlosttime/glassdesk-updates/releases/tag/v1.4.0)

### 更新检查接口

https://api.github.com/repos/everlosttime/glassdesk-updates/releases/latest
