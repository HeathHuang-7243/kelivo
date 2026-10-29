# Kelivo 1.3.2 · WebDAV 定时备份测试版

[下载安卓安装包](./Kelivo-WebDAV-Test-1.3.2-arm64.apk?raw=true) · [SHA-256 校验文件](./SHA256SUMS)

- 适用设备：ARM64，Android 7.0 及以上。
- 应用名称：**Kelivo WebDAV Test**。
- 使用原测试签名与包名，可覆盖安装旧测试版；应用数据与正式版独立。
- 已同步上游更新，并保留 WebDAV 定时备份与手机、桌面设置入口。
- 首次打开后检查 **设置 → 备份 → WebDAV 定时备份**，建议先运行一次立即备份。
- 如开启上游新增的备份加密，需手动输入密码备份；自动任务会暂停，防止上传明文。
- Android 的省电和网络限制可能推迟后台执行。

此安装包为预编译的 profile 测试版。源代码与构建记录见随附的 `build-info.json`。

本分支只提供安装包下载。应用源码保存在仓库 `feature/webdav-scheduled-backup` 分支；[PR #1](https://github.com/HeathHuang-7243/kelivo/pull/1) 待合并到 `master`。

构建源码：[提交 6ebd2fcd](https://github.com/HeathHuang-7243/kelivo/commit/6ebd2fcd8ae7a4f92547b0fc7b0864d6b5f6ca60)。
