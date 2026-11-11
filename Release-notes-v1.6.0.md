# GlassDesk 1.6.0

本次更新汇总 1.5.9 之后的功能、修复与性能优化。适用于 Windows 10 Build 19041 及以上、Windows 11 的 x64 系统。

## 新功能与体验改进

- 日历面板右上角新增“公历 / 农历”切换，自动保存选择；农历模式显示农历日期，并保留小号公历数字供对照，支持闰月。
- 信息栏外设电量摘要支持鼠标、耳机、键盘等类别，最多选择三项；支持自动选择和手动绑定，并包含独立离线电量读取组件。具体支持取决于设备型号、连接方式与固件，无法取得读数时显示 `--`。
- 关于页的“网盘下载”改为“下载入口”，点击显示单个官网二维码；二维码可离线显示，扫码访问 [GlassDesk 官网](https://glassdesk.cn/)。点击外部或按 Esc 关闭。
- 新增由 GlassDesk 设置管理、默认关闭的可选奶蛙回收站组件。

## 修复与性能优化

- 修复使用键盘快捷键打开启动台时，页面容器出现整页虚线焦点框的问题，保留搜索、滚动与翻页操作。
- 延续 1.5.11 的主屏壁纸读取优化，符合条件时只读取主屏所需范围。
- 包含 1.5.12 的玻璃滤镜采样范围优化，减少实时背景计算与临时内存分配，保持原像素输出、动态背景和现有动画曲线。
- 保留 Dock、启动台、附近传输、分区材质、信息栏、控制中心等现有功能。覆盖升级保留用户设置、应用库、布局与自定义图标。

## 下载与安装

- [Windows x64 安装包](https://github.com/everlosttime/glassdesk-updates/releases/download/v1.6.0/GlassDesk-1.6.0-win-x64-Setup.exe)
- [Windows x64 便携 ZIP](https://github.com/everlosttime/glassdesk-updates/releases/download/v1.6.0/GlassDesk-1.6.0-win-x64.zip)
- [SHA-256 校验文件](https://github.com/everlosttime/glassdesk-updates/releases/download/v1.6.0/SHA256SUMS.txt)

安装包自带 .NET 10。已有版本可运行安装包覆盖升级；便携版解压到单独目录使用，迁移时请保留原有 Data。客户端更新检查提供新版本提示，下载安装仍由用户确认和执行。

网盘入口继续保留：[夸克网盘](https://pan.quark.cn/s/037d0cd5080b)、[百度网盘](https://pan.baidu.com/s/1X_TFD0GMp8RJsRLNISjy_w?pwd=0a53)（提取码 `0a53`）。网盘文件由作者单独上传，本次 GitHub 发布不代表网盘文件已替换。

## 完整功能源码

[GlassDesk 1.6.0 源码 Release](https://github.com/everlosttime/glassdesk-open-source/releases/tag/v1.6.0) 包含全部产品功能源码，包括信息栏、农历日历、控制中心、设备与媒体控制、外设电量组件和固定依赖；保留现有分范围许可、历史 Apache 权利与第三方授权。
