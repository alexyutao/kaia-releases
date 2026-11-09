# Kaia 发布

Kaia 的公开下载与更新分发仓库。这里提供发布说明和安装文件；应用源码保存在独立的私有仓库。下载公开文件无需 GitHub 登录或 GH_TOKEN。

## 当前版本

[Kaia v0.33.0 · 今天首页与生活建议](https://github.com/alexyutao/kaia-releases/releases/tag/v0.33.0)

**[下载 Windows x64 完整安装包](https://github.com/alexyutao/kaia-releases/releases/download/v0.33.0/Kaia_0.33.0_x64-setup.exe)**

本次提供完整 NSIS / MSI 安装器，包含程序及所需资源，支持新安装和覆盖升级，并附更新签名与清单。安装说明见本版 Release，文件校验值见 `SHA256SUMS-0.33.0.txt`。

主要更新：新增“今天”首页，提供真实天气、全天整合穿衣建议与五行参考配色，连接最近对话、资料库、浏览找回、友人帐和待确认记忆。支持短记录与提问草稿、首页模块定制，并修复双层滚动。原功能页面沿用现有设计和交互。

## 从旧版升级

先从系统托盘退出 Kaia，再运行安装包。已有用户选择原安装目录即可升级，应用标识与用户数据目录保持不变；无需手动替换单个主程序。

其他版本及附件见 [Releases](https://github.com/alexyutao/kaia-releases/releases)。旧的 v0.31.1 主程序手动替换版仍保留供历史查阅。

## 在线更新

本版使用与客户端内置公钥匹配的原私钥签名，附带 EXE / MSI 更新签名和 `latest.json`，并设为 Latest。已使用公开更新源的旧版可在「设置 → 通用 → 应用更新」检查、下载并验证更新。

仍使用私有更新源的旧版需先从上面的链接手动安装一次，之后即可使用公开更新源。

更新签名用于验证来源与完整性；本版未配置 Windows Authenticode 发布者证书，系统仍可能显示 SmartScreen 提示。

本仓库使用独立的提交历史与版本标签，应用源码不在此仓库分发。
