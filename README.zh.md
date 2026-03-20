# OpenClaw Killer - 龙虾卸载工具 🦞

一键完美卸载 OpenClaw，让这只龙虾体面告别。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux%20%7C%20Windows-lightgrey.svg)](https://github.com)
[![Languages](https://img.shields.io/badge/languages-16-blue.svg)](https://github.com)

**🌍 多语言支持**: [English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Türkçe](README.tr.md) | [Nederlands](README.nl.md) | [Português](README.pt.md) | [العربية](README.ar.md) | [Tiếng Việt](README.vi.md) | [Русский](README.ru.md) | [Bahasa Indonesia](README.id.md) | [ไทย](README.th.md) | [Italiano](README.it.md)

![OpenClaw Killer Cover](cover.png)

---

## 📢 推文

> 🦞 最近被龙虾轰炸太多了？玩腻了？想卸载？
>
> 等一下！听说最近卸载小龙虾服务越来越火了，上门服务一次收费 500 块。
>
> 但卸载 OpenClaw 不是拖进废纸篓就完事，需要至少 5 个复杂步骤：停服务、清配置、删状态、处理多 profile...
>
> 我把这套流程打包好了，写成完全开源免费的工具 —— OpenClaw Killer
>
> **为你劲省 500 💰**
>
> 支持 macOS/Linux/Windows，一键搞定

更多推文模板和配图 prompt 请查看 [tweet.md](tweet.md)

---

## 为什么要卸载 OpenClaw？

如果你想了解为什么越来越多人选择卸载 OpenClaw，请阅读 [WHY.md](WHY.md)。

简单来说：

- 💰 **成本高昂**：月费可能破千美元
- 🔒 **安全风险**：十几万实例暴露在公网
- 🧠 **AI 脑过载**：工具太多反而降低生产力
- ⚠️ **失控风险**：连专家都可能踩不住刹车

## 快速开始

### 方式 1: 作为 OpenClaw Skill 使用

如果你还安装着 OpenClaw，可以将其作为 Skill 使用：

```bash
# 安装 Skill
./install-skill.sh

# 然后在 OpenClaw 中说
"卸载 OpenClaw" 或 "uninstall OpenClaw"
```

### 方式 2: 直接运行脚本

#### macOS / Linux

```bash
# 下载脚本
curl -O https://raw.githubusercontent.com/orange2ai/openclaw-killer/main/openclaw-killer.sh

# 添加执行权限
chmod +x openclaw-killer.sh

# 运行
./openclaw-killer.sh
```

### Windows

```powershell
# 下载脚本
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/orange2ai/openclaw-killer/main/openclaw-killer.ps1" -OutFile "openclaw-killer.ps1"

# 如果遇到执行策略限制，先运行
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

# 运行
.\openclaw-killer.ps1
```

## 功能特点

✓ 支持三大平台（macOS / Linux / Windows）
✓ 自动检测 CLI 是否可用
✓ 智能选择卸载路径
✓ 清理所有残留文件
✓ 支持多 profile 配置
✓ 清晰的进度提示
✨ **v1.1 新功能**：脚本执行完毕后自动删除自身，无毒副作用
🎯 **Skill 支持**：可作为 OpenClaw Skill 使用，在 OpenClaw 内部卸载自己

## 它会做什么

这个工具会自动完成以下所有步骤：

1. 停止网关服务
2. 卸载网关服务
3. 删除状态和配置文件
4. 删除 workspace
5. 卸载 CLI（npm/pnpm/bun）
6. 删除 macOS 桌面版
7. 清理多 profile 残留

## 安全说明

- 所有操作都在用户目录下进行
- 不需要 sudo 权限
- 删除前会检查文件是否存在
- 提供清晰的操作反馈

## 致谢

本项目的 WHY 文档内容参考自 AppSo 的深度报道：[《月薪两万，养不起一只 OpenClaw》](https://mp.weixin.qq.com/s/WLgbbLsyR8FZaVXNI0ROyQ)

感谢 AppSo 团队对 OpenClaw 成本和安全问题的深入分析。

## Star History

<a href="https://star-history.com/#orange2ai/openclaw-killer&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=orange2ai/openclaw-killer&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=orange2ai/openclaw-killer&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=orange2ai/openclaw-killer&type=Date" width="100%" />
 </picture>
</a>

## 许可证

[MIT License](LICENSE)

---

让 OpenClaw 体面告别，就这么简单。
