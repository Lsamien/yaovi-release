# Yaovi 客户端发行

此公开仓库分发 Yaovi 客户端安装包、版本说明和更新文件。应用源码单独维护。

## 下载

当前正式版本：[Yaovi 0.1.1](https://github.com/Lsamien/yaovi-release/releases/tag/v0.1.1)。

适用 macOS Apple Silicon（arm64），纯客户端 Bundle ID 为 `cn.samien.yaovi.agent`，连接独立 Yaovi Host。
首次安装使用 DMG，可通过同一 Release 的 `SHA256SUMS.txt` 校验附件。

## 升级

- 旧 0.1.0 / build 343 需手动安装一次 0.1.1。
- 0.1.1 起后台自动检查，用户点击下载；系统完成签名验证和准备后，可重启更新或正常退出后安装。
- 升级源固定为本公开库，无需 GitHub 账号或 Token；更新不重装独立 Host。
- 正式版本包含 DMG、ZIP、两份 blockmap、`latest-mac.yml` 和 `SHA256SUMS.txt`。

0.1.1 已完成签名、公证、包体验证与本机真实原生升级维护验收；隔离 macOS 系统升级验收尚未完成，详见版本说明。

不在此仓库保存账号凭据、签名私钥或私有应用源码。
