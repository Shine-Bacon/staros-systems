# StarOS Installer

这是 StarOS 的自动化安装脚本。它旨在提供一个简单、快速且可定制的方式来将 StarOS 部署到你的电脑上。

> **警告：** 此项目正处于早期开发阶段，绝对不适用于生产环境。它可能会擦除你的硬盘数据。仅在测试虚拟机或你愿意承担风险的设备上使用。

## 目标

*   提供一个交互式、用户友好的安装流程。
*   自动化分区、文件系统创建、基础系统安装和引导程序配置。
*   支持多种桌面环境和硬件配置。

## 开发

（此处待补充具体的开发环境和构建指令）

## 贡献

请参阅主仓库的 [CONTRIBUTING.md]
# StarOS Packages & Configs

这个仓库包含了用于构建 StarOS 镜像的软件包列表、默认配置文件、桌面主题和启动脚本。

## 结构

*   `pkglists/` - 包含不同场景的软件包列表 (e.g., `base.txt`, `developer.txt`, `security.txt`)
*   `configs/` - 系统的默认配置文件 (e.g., 针对 `fwupd`, `docker`, `ufw` 的配置)
*   `themes/` - 自定义的 GTK、图标和 KDE 主题。
*   `scripts/` - 在构建或安装后运行的各种脚本。

## 使用

这些资源和 `staros-installer` 以及镜像构建流水线紧密结合。

## 贡献

欢迎提交Pull Request来优化我们的默认配置或增删软件包。请参阅主仓库的 [CONTRIBUTING.md]
