# aikan-release

爱看 App 的安装包与更新清单，**公开仓库**，供 App 内匿名检查更新使用。

- `version.json`：更新清单，App 启动时读取并比对 `versionCode`
- `aikan-<版本号>.apk`：安装包

源码仓库为私有的 `aikan`，本仓库只存放发布物。

> 注意：本仓库必须保持公开。私有仓库的 raw 地址不接受匿名请求，App 将无法检查更新。
