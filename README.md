# Kaia 发布

Kaia 的公开下载与更新分发仓库。这里提供发布说明和安装文件；应用源码保存在独立的私有仓库。下载公开文件无需 GitHub 登录或 GH_TOKEN。

## 当前版本

[Kaia v0.32.0 · 聊天界面与卡片交互更新](https://github.com/alexyutao/kaia-releases/releases/tag/v0.32.0)

**[下载 Windows x64 完整安装包](https://github.com/alexyutao/kaia-releases/releases/download/v0.32.0/Kaia_0.32.0_x64-setup.exe)**

本次提供真正的 NSIS 安装器，包含程序及所需资源，支持新安装和覆盖升级。安装步骤见发布附件 `README-Windows.txt`，文件校验值见 `SHA256SUMS-0.32.0.txt`。

主要更新：统一聊天卡片，压缩引用与发送队列预览，整理消息操作与模型设置，完善能力选择的键盘高亮及窄屏交互。

## 从旧版升级

先从系统托盘退出 Kaia，再运行安装包。已有用户选择原安装目录即可升级，应用标识与用户数据目录保持不变；无需手动替换单个主程序。

其他版本及附件见 [Releases](https://github.com/alexyutao/kaia-releases/releases)。旧的 v0.31.1 主程序手动替换版仍保留供历史查阅。

## 在线更新

v0.32.0 通过上面的固定版本链接手动下载安装。原在线更新签名私钥暂不可用，因此本次没有更新签名或 `latest.json`，也不变更现有 Latest 自动更新入口。

应用继续保留原更新公钥；后续完整在线更新需要使用原私钥签发安装包与更新清单。请以上面的“当前版本”下载链接获取这次安装包。

本仓库使用独立的提交历史与版本标签，应用源码不在此仓库分发。
