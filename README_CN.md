<div align="center">

<h1 align="center">AfterChat</h1>

[English](./README.md) / 简体中文

部署你自己的跨平台私人大型语言模型应用, 支持 GPT3、GPT4、Gemini Pro 等模型。

![Web][Web-image]
[![Windows][Windows-image]][download-url]
[![MacOS][MacOS-image]][download-url]
[![Linux][Linux-image]][download-url]

[download-url]: https://github.com/WindSpiritSR/AfterChat/releases
[Web-image]: https://img.shields.io/badge/Web-PWA-orange?logo=microsoftedge
[Windows-image]: https://img.shields.io/badge/-Windows-blue?logo=windows
[MacOS-image]: https://img.shields.io/badge/-MacOS-black?logo=apple
[Linux-image]: https://img.shields.io/badge/-Linux-333?logo=debian

</div>

## 主要功能

- 支持用户授权、API 管理等后台功能
- 提供体积极小（~5MB）的跨平台客户端（Linux/Windows/MacOS）, [下载地址](https://github.com/WindSpiritSR/AfterChat/releases)
- 完整的 Markdown 支持：LaTex 公式、Mermaid 流程图、代码高亮等等
- 精心设计的 UI，响应式设计，支持深色模式，支持 PWA
- 极快的首屏加载速度（~100kb），支持流式响应
- 预制角色功能（面具），方便地创建、分享和调试你的个性化对话
- 海量的内置 prompt 列表，来自[中文](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)和[英文](https://github.com/f/awesome-chatgpt-prompts)
- 自动压缩上下文聊天记录，在节省 Token 的同时支持超长对话

## 环境需求

NodeJS >= 18, Golang >= 1.22, Docker >= 20

## 文档

> 请查阅 [docs][./docs] 目录来获得更详细的文档指引

- [常见问题](./docs/faq-cn.md)
- [如何添加翻译](./docs/translation.md)
- [用户手册（仅中文，WIP）](./docs/user-manual-cn.md)

## 特别鸣谢

### 原始项目

[![ChatGPTNextWeb/ChatGPT-Next-Web](https://gh-card.dev/repos/ChatGPTNextWeb/ChatGPT-Next-Web.svg)](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)

### 原始项目捐赠者

[原始项目捐赠者名单](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web?tab=readme-ov-file#sponsor)

### 贡献者

[![贡献者](https://contrib.rocks/image?repo=WindSpiritSR/AfterChat)](https://github.com/WindSpiritSR/AfterChat/graphs/contributors)

### 相关项目

- [one-api](https://github.com/songquanpeng/one-api): 一站式大模型额度管理平台，支持市面上所有主流大语言模型

## 开源协议

[AGPLv3](https://opensource.org/license/agpl-v3)
