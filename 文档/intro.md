---
sidebar_position: 1
---

# 简介123

[![](https://img.shields.io/github/release/Xhofe/alist?style=flat-square)](https://github.com/Xhofe/alist/releases/latest)
[![GitHub Discussions](https://img.shields.io/github/discussions/Xhofe/alist?color=%23ED8936&style=flat-square)](https://github.com/Xhofe/alist/discussions)
[![](https://img.shields.io/github/workflow/status/Xhofe/alist/build?style=flat-square)](https://github.com/Xhofe/alist/actions?query=workflow%3ABuild)
[![](https://img.shields.io/github/downloads/Xhofe/alist/total?style=flat-square&color=%239F7AEA)](https://github.com/Xhofe/alist/releases)
[![](https://data.jsdelivr.com/v1/package/gh/Xhofe/alist-web/badge)](https://www.jsdelivr.com/package/gh/Xhofe/alist-web)
[![](https://img.shields.io/badge/%24-donate-ff69b4.svg?style=flat-square)](https://pay.xhofe.top)

### 是什么？

一款支持多种存储的目录文件列表程序，支持 web 浏览与 webdav（只读），后端基于`gin`，前端使用`react`。

## 讨论

一般问题请到[讨论论坛](https://github.com/Xhofe/alist/discussions) ，**issue 仅针对错误报告。**

### 支持的存储

- [x] 本地存储
- [x] [阿里云盘](https://www.aliyundrive.com/)
- [x] OneDrive / Sharepoint（[国际版](https://www.office.com/), [世纪互联](https://portal.partner.microsoftonline.cn),de,us）
- [x] [天翼云盘](https://cloud.189.cn)
- [x] [GoogleDrive](https://drive.google.com/)
- [x] [123 云盘](https://www.123pan.com/)
- [x] [蓝奏云](https://pc.woozooo.com/)
- [x] [Alist](https://github.com/Xhofe/alist)
- [x] FTP
- [x] [PikPak](https://www.mypikpak.com/)
- [x] [闪电盘](https://shandianpan.com/)
- [x] [S3](https://aws.amazon.com/cn/s3/)
- [x] WebDav

### WebDav 支持

| 存储策略    | 列表 | 下载 | 创建文件夹 | 重命名 | 移动 | 复制 | 上传 |
| ----------- | :--: | :--: | :--------: | :----: | :--: | :--: | :--: |
| 本地存储    |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ✅  |  ✅  |
| 阿里云盘    |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ❌  |  ✅  |
| Onedrive    |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ✅  |  ✅  |
| 天翼云盘    |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ✅  |  ❌  |
| GoogleDrive |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ❌  |  ✅  |
| 123 云盘    |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ❌  |  ❌  |
| 蓝奏云      |  ✅  |  ✅  |     ❌     |   ❌   |  ❌  |  ❌  |  ❌  |
| Alist       |  ✅  |  ✅  |     ❌     |   ❌   |  ❌  |  ❌  |  ❌  |
| FTP         |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ❌  |  ✅  |
| PikPak      |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ✅  |  ✅  |
| 闪电盘      |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ❌  |  ✅  |
| S3          |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ✅  |  ✅  |
| WebDav      |  ✅  |  ✅  |     ✅     |   ✅   |  ✅  |  ✅  |  ✅  |

### 演示

- https://alist.nn.ci

![preview](https://store.heytapimage.com/cdo-portal/feedback/202111/03/695ef77854a144e928518efde38db97a.png)

### License

The `AList` is open-source software licensed under the MIT license.
