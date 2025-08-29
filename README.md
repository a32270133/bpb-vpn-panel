# BPB VPN Panel - 个人专属免费VPN订阅节点

这个项目用于自动生成混淆的 BPB Worker Panel 代码，避免 Cloudflare 1101 报错。

## 功能特点

- 自动拉取最新的 BPB Panel 源代码
- 使用 JavaScript Obfuscator 进行代码混淆
- 每日自动更新，确保代码的独特性
- 支持 Cloudflare Pages 部署

## 文件说明

- `_worker.js` - 混淆后的 Worker 代码，用于 Cloudflare Pages 部署
- `origin.js` - 原始的 BPB Panel 代码（临时文件）

## 使用方法

1. Fork 此仓库
2. 等待 GitHub Actions 自动运行生成混淆代码
3. 下载生成的 `_worker.js` 文件
4. 按照教程部署到 Cloudflare Pages

## 注意事项

- 不要与他人分享您的混淆代码
- 定期更新以保持代码的独特性
- 遵守当地法律法规
