# PigClaude 发布

本仓库只放 PigClaude 桌面端的安装包、更新清单和发布说明，不含源码。

- 安装包和更新清单由 `pigclaude/frontend` 推版本 tag 后自动构建，先以草稿上传到本仓库的 Releases，维护者确认后公开。
- 官网下载页和应用的更新检查都读取本仓库最新公开的 Release，不需要登录。
- 每个 Release 附带三个平台的更新清单（`latest-mac.yml`、`latest.yml`、`latest-linux.yml`），其中有每个安装包的 sha512。
- 三个平台的安装包都没有代码签名，已知限制见各版本的发布说明。

名字里带 `test` 的 Release 和 tag 只用于验证发布流程，不是正式版本，不要下载使用。
