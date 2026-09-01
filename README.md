# JC无限画布 Windows 独立版

这是 JC无限画布的公开发布与自动更新仓库。仓库不包含用户画布、账号数据、浏览器配置或本地源代码。

## 下载

请从 [Releases](https://github.com/xjc991114xjc520cjq-source/JC-Infinite-Canvas-Releases/releases/latest) 下载最新版 `JC.exe`，下载后可改名为 `JC无限画布.exe`。

## 自动更新

- 程序启动后会匿名读取公开的 `update.json`。
- 只有检测到更高的正式版本时才会提示。
- 用户二次确认并保存画布后，独立更新器会关闭旧程序、下载并校验 SHA-256、在原目录以原文件名替换，然后自动重启。
- 检查和下载均不需要 GitHub 账号或令牌。
