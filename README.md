# Kaia 发布

Kaia 的公开下载与更新分发仓库。这里提供发布说明和安装文件；应用源码保存在独立的私有仓库。下载公开文件无需 GitHub 登录或 GH_TOKEN。

## 当前版本

[Kaia v0.32.0 · 聊天界面与卡片交互更新](https://github.com/alexyutao/kaia-releases/releases/tag/v0.32.0)

**[下载 Windows x64 完整安装包](https://github.com/alexyutao/kaia-releases/releases/download/v0.32.0/Kaia_0.32.0_x64-setup.exe)**

本次提供完整 NSIS / MSI 安装器，包含程序及所需资源，支持新安装和覆盖升级。2026-11-09 已使用原更新私钥重新打包并补齐更新签名与清单。安装步骤见发布附件 `README-Windows.txt`，文件校验值见 `SHA256SUMS-0.32.0.txt`。

主要更新：统一聊天卡片，压缩引用与发送队列预览，整理消息操作与模型设置，完善能力选择的键盘高亮及窄屏交互。

## 从旧版升级

先从系统托盘退出 Kaia，再运行安装包。已有用户选择原安装目录即可升级，应用标识与用户数据目录保持不变；无需手动替换单个主程序。

其他版本及附件见 [Releases](https://github.com/alexyutao/kaia-releases/releases)。旧的 v0.31.1 主程序手动替换版仍保留供历史查阅。

## 在线更新

v0.32.0 已使用与客户端内置公钥匹配的原私钥签名，附带 EXE / MSI 更新签名和 `latest.json`，并设为 Latest。已使用公开更新源的较旧版本可在「设置 → 通用 → 应用更新」检查、下载并验证更新。

已经安装 0.32.0 的用户如需本次重新打包的文件，请从上面的固定版本链接手动下载安装；同版本不会再次提示升级。仍使用私有更新源的旧版也需先手动安装一次。

更新签名用于验证来源与完整性；本版未配置 Windows Authenticode 发布者证书，系统仍可能显示 SmartScreen 提示。

本仓库使用独立的提交历史与版本标签，应用源码不在此仓库分发。
