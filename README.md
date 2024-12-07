# Tailscale 基础教程：Headscale 的部署方法和使用教程

## 在Linux上部署
首先需要到其 GitHub 仓库的 Release 页面下载最新版的二进制文件。
[https://github.com/juanfont/headscale/releases/](https://github.com/juanfont/headscale/releases/)
```
wget --output-document=/usr/local/bin/headscale \
   https://github.com/juanfont/headscale/releases/download/v0.23.0/headscale_0.23.0_linux_amd64
chmod +x /usr/local/bin/headscale
```

## Tailscale 客户端接入
