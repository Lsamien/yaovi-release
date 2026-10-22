# Yaovi 客户端发行

此公开仓库用于分发 Yaovi 客户端安装包、版本说明和更新文件。应用源码单独维护。

## 下载

请前往 [Releases](https://github.com/Lsamien/yaovi-release/releases) 查看安装包与签名、验收说明。

当前分发范围为 macOS Apple Silicon（arm64）纯客户端，Bundle ID 为 `cn.samien.yaovi.agent`。客户端连接独立 Yaovi Host。

首次安装使用 DMG。下载后可通过同一 Release 的 `SHA256SUMS.txt` 校验文件。

## 升级说明

- 0.1.0 / build 343 为已签名、公证的手动安装版，使用新 DMG 手动升级。
- 带应用内自动升级能力的新客户端正在准备；公开库建立或旧安装包上传本身不代表该功能已经接通。
- 后续正式更新以对应 Release 的完整附件和实际验证说明为准。

不在此仓库保存账号凭据、签名私钥或私有应用源码。
