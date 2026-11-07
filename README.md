# Kaia 发布

Kaia 的公开安装包与更新分发仓库。这里提供发布说明、安装包、更新签名和更新清单；应用源码保存在独立的私有仓库。

## 下载安装

前往 [Releases](https://github.com/alexyutao/kaia-releases/releases) 查看已发布的版本及其附件。下载公开安装包无需 GitHub 登录或 GH_TOKEN。仓库正在准备首次公开发布，可下载文件以已发布版本为准。

Windows x64 用户可选择版本附件中的 EXE 安装包。发布时会同时提供更新签名、latest.json 清单及 SHA-256 校验文件；Windows 应用内更新会验证安装包签名。其他平台的安装包以具体版本附件为准。

## 从旧版迁移

v0.31.0、v0.31.1 等旧安装包的更新源仍指向私有仓库。首次迁移时，请从本仓库手动安装一次包含公开更新源的新版本，之后即可在“设置 → 通用 → 应用更新”检查和下载更新，无需配置 GitHub token。

## 发布内容

本仓库使用独立的提交历史和版本标签，仅用于分发。正式更新清单地址为：

https://github.com/alexyutao/kaia-releases/releases/latest/download/latest.json
