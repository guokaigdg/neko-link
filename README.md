# NekoLink

> 原生 macOS 代理客户端 · 基于 Mihomo 内核

NekoLink 是一款用 SwiftUI 构建的原生 macOS 代理客户端，基于 [Mihomo](https://github.com/MetaCubeX/mihomo) 内核。菜单栏即开即用，支持一键订阅、系统代理、实时流量、连接管理等功能，为 macOS 用户提供纯净、流畅的代理体验。

## 特性

- **菜单栏原生** — 点击图标即开即用，不打断当前工作流
- **订阅与节点** — 一键导入订阅，自动刷新，延迟实时可视
- **系统代理免密** — 切换系统代理不再弹密码框，权限一次授予
- **实时流量** — 上下行速率实时滚动，曲线流畅不卡顿
- **连接管理** — 看清当前每一条连接，一键断开异常会话
- **自启与更新** — 开机自启，新版本后台自动装好
- **TUN 模式** — 基于 NetworkExtension 实现全流量代理

## 系统要求

- macOS 14+
- Apple Silicon 或 Intel

## 开发路线

| 里程碑 | 状态 | 说明 |
|--------|------|------|
| M0 | ✅ 完成 | 原型 · 内核跑通 |
| M1 | ✅ 完成 | MVP UI · 菜单栏 + 节点 |
| M2 | ✅ 完成 | 系统集成 · Helper + 自启 |
| M3 | ✅ 完成 | TUN 模式 · NetworkExtension |
| M4 | 🚧 进行中 | 打磨 · 动画与主题 |
| M5 | ⏳ 待开始 | 公证发布 · GitHub Release |

## 当前状态

**v0.1.0 · 开发者预览** — 核心功能已就绪，TUN 模式已支持，打磨与公证发布在路上。

## 相关仓库

- [NekoLink App](https://github.com/guokaigdg/NekoLink) — macOS 客户端主仓库
- [NekoLink Website](https://github.com/guokaigdg/neko-link-website) — 本项目，产品落地页

## 许可

MIT License