# Rime Theme 懒猫微服打包

上游：https://github.com/tom2almighty/rime-theme （AGPL-3.0）

可视化制作 Rime 输入法主题：预设多种配色，支持一键导入导出。纯静态网页应用。

## 打包说明

- 镜像：`ghcr.io/tom2almighty/rime-theme`（nginx 静态站，amd64/arm64），由 [ca-x/lazycat-github-action](https://github.com/ca-x/lazycat-github-action) 镜像模式自动同步
- 版本源：SemVer tag（如 0.0.1），定时 + 手动触发发布喵喵商店
- 无状态应用：无账号、无持久数据，配置导出的主题文件由用户下载到本地
