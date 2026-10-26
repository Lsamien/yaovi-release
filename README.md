# Yaovi 客户端发行

此公开仓库分发 Yaovi 客户端安装包、版本说明和更新文件。应用源码单独维护。

## 下载

当前正式版本：[Yaovi 0.1.3](https://github.com/Lsamien/yaovi-release/releases/tag/v0.1.3)。

适用 macOS Apple Silicon（arm64），纯客户端 Bundle ID 为 `cn.samien.yaovi.agent`，连接独立 Yaovi Host。
首次安装使用 DMG，可通过同一 Release 的 `SHA256SUMS.txt` 校验附件。

## 升级

- 旧 0.1.0 / build 343 需手动安装一次当前正式版。
- 0.1.1 起后台自动检查，用户点击下载；系统完成签名验证和准备后，可重启更新或正常退出后安装。
- 升级源固定为本公开库，无需 GitHub 账号或 Token；更新不重装独立 Host。
- 正式版本包含 DMG、ZIP、两份 blockmap、`latest-mac.yml` 和 `SHA256SUMS.txt`。
- 0.1.2 完善全目录文件访问；旧版文件与命令授权需要重新同意一次，屏幕授权独立保留。
- 0.1.3 更新统一账号入口、可信设备局域网接入和连接恢复，并修复账号页更新操作；相关远程能力需要配套 Host 支持。

0.1.3 已完成正式签名、公证与包体验证。0.1.1 的本机真实原生升级维护验收作为历史记录保留；此前取消的隔离 macOS 系统升级验收仍未完成，详见版本说明。

不在此仓库保存账号凭据、签名私钥或私有应用源码。
