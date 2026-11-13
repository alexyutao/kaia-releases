# Kaia 发布

Kaia 的公开下载与更新分发仓库。这里提供发布说明和安装文件；应用源码保存在独立的私有仓库。下载公开文件无需 GitHub 登录或 GH_TOKEN。

## 当前版本

[Kaia v0.34.0 · 衣橱与功能模块开关](https://github.com/alexyutao/kaia-releases/releases/tag/v0.34.0)

**[下载 Windows x64 完整安装包](https://github.com/alexyutao/kaia-releases/releases/download/v0.34.0/Kaia_0.34.0_x64-setup.exe)**

本次提供完整 NSIS / MSI 安装器，包含程序及所需资源，支持新安装和覆盖升级，并附更新签名与清单。安装说明见本版 Release，文件校验值见 `SHA256SUMS-0.34.0.txt`。

主要更新：新增衣橱管理、商品页与交易快照链接，支持截图识别、按购买尺码匹配尺寸和封面选择。“设置 → 功能模块”可关闭或恢复衣橱，已有数据保留。增量导入保留手动资料与图片；同时修复开关圆点对齐、商品链接重复打开，以及语音被打断后的续聊问题。

## 从旧版升级

先从系统托盘退出 Kaia，再运行安装包。已有用户选择原安装目录即可升级，应用标识与用户数据目录保持不变；无需手动替换单个主程序。

其他版本、平台及附件见 [Releases](https://github.com/alexyutao/kaia-releases/releases)。旧的 v0.31.1 主程序手动替换版仍保留供历史查阅。

## 在线更新

本版使用与客户端内置公钥匹配的原私钥签名，附带 EXE / MSI 更新签名和 `latest.json`，并设为 Latest。已使用公开更新源的旧版可在「设置 → 通用 → 应用更新」检查、下载并验证更新。

仍使用私有更新源的旧版需先从上面的链接手动安装一次，之后即可使用公开更新源。

更新签名用于验证来源与完整性；本版未配置 Windows Authenticode 发布者证书，系统仍可能显示 SmartScreen 提示。

本仓库使用独立的提交历史与版本标签，应用源码不在此仓库分发。
