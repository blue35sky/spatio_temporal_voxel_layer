# Maple Mono 字体版本对比 / Maple Mono Font Comparison

## 概述 / Overview

Maple Mono 是一款专为编程设计的等宽字体，具有多个变体版本。本文档说明了三个主要版本之间的区别。

Maple Mono is a monospace font designed for programming, available in multiple variants. This document explains the differences between the three main versions.

---

## 版本对比 / Version Comparison

### 1. **Maple Mono** (基础版本 / Base Version)

**特点 / Features:**
- 原始的 Maple Mono 字体，包含基本的拉丁字符集
- 专为代码编辑器和终端优化
- 包含常见的编程连字（ligatures）
- 清晰的字符区分（如 0/O, 1/l/I）
- 适合英文编程环境

**用途 / Use Cases:**
- 英文代码编辑
- 英文文档编写
- 不需要图标或中文支持的场景

---

### 2. **Maple Mono NF** (Nerd Fonts 版本)

**特点 / Features:**
- 基于 Maple Mono，通过 [Nerd Fonts](https://www.nerdfonts.com/) 项目打补丁
- 包含大量额外的图标字形（glyphs）
- 支持开发者常用的图标字体，如：
  - Font Awesome
  - Devicons
  - Octicons
  - Material Design Icons
  - Weather Icons
  - 等等
- 保持原有 Maple Mono 的所有特性
- 字体文件较大（因为包含额外的图标）

**与 Maple Mono 的区别 / Differences from Maple Mono:**
- ✅ 新增：数千个图标和符号
- ✅ 新增：支持 Powerline、vim-devicons 等工具
- ⚠️ 文件更大：约 4-5 倍于基础版本
- ✅ 兼容性：完全向后兼容基础版本

**用途 / Use Cases:**
- 使用 Vim/Neovim 配合插件（如 NERDTree, vim-airline）
- 使用终端提示符美化工具（如 Oh My Zsh, Starship）
- 需要在终端或编辑器中显示文件类型图标
- 使用现代化的开发工具和 IDE

---

### 3. **Maple Mono NF CN** (Nerd Fonts 中文版本)

**特点 / Features:**
- 基于 Maple Mono NF
- 新增完整的中文字符支持（简体中文、繁体中文）
- 包含 Nerd Fonts 的所有图标
- 中英文混排时保持美观
- 中文字符采用等宽设计，与英文字符对齐

**与 Maple Mono NF 的区别 / Differences from Maple Mono NF:**
- ✅ 新增：完整的中日韩（CJK）字符集
- ✅ 新增：中文标点符号
- ✅ 优化：中英文混合显示效果
- ⚠️ 文件更大：因为包含 CJK 字形
- ✅ 兼容性：完全兼容 Maple Mono NF 的所有功能

**用途 / Use Cases:**
- 中文注释的代码编写
- 中英文混合的文档编辑
- 需要同时显示中文和图标的场景
- 中文本地化的开发环境

---

## 快速选择指南 / Quick Selection Guide

### 选择 Maple Mono 如果 / Choose Maple Mono if:
- ✅ 只编写英文代码
- ✅ 不需要图标支持
- ✅ 希望字体文件尽可能小
- ✅ 使用基础的代码编辑器

### 选择 Maple Mono NF 如果 / Choose Maple Mono NF if:
- ✅ 使用 Vim/Neovim 配合图标插件
- ✅ 使用美化的终端提示符
- ✅ 需要文件类型图标
- ✅ 主要使用英文，偶尔需要中文（使用系统后备字体）

### 选择 Maple Mono NF CN 如果 / Choose Maple Mono NF CN if:
- ✅ 经常编写中文注释
- ✅ 需要中英文混合显示
- ✅ 希望中文字符与代码保持一致的风格
- ✅ 需要图标 + 中文的完整支持

---

## 技术规格对比 / Technical Specifications

| 特性 / Feature | Maple Mono | Maple Mono NF | Maple Mono NF CN |
|----------------|------------|---------------|------------------|
| 拉丁字符 / Latin Characters | ✅ | ✅ | ✅ |
| 编程连字 / Programming Ligatures | ✅ | ✅ | ✅ |
| Nerd Fonts 图标 / Icons | ❌ | ✅ | ✅ |
| 中文支持 / Chinese Support | ❌ | ❌ | ✅ |
| Powerline 符号 / Symbols | ❌ | ✅ | ✅ |
| 文件大小 / File Size | 小 / Small | 中 / Medium | 大 / Large |
| 最佳用途 / Best For | 纯英文 / Pure English | 英文+图标 / English+Icons | 中英文+图标 / CN+EN+Icons |

---

## 安装建议 / Installation Recommendations

1. **开发环境配置 / Development Environment:**
   - 如果主要使用英文编程：Maple Mono 或 Maple Mono NF
   - 如果需要中文注释：Maple Mono NF CN

2. **终端配置 / Terminal Configuration:**
   - 如果使用美化工具（Oh My Zsh, Starship）：Maple Mono NF 或 NF CN
   - 如果只需要基础功能：Maple Mono

3. **IDE 配置 / IDE Configuration:**
   - VSCode, IntelliJ 等：根据是否需要中文选择 NF 或 NF CN
   - Vim/Neovim 配合插件：必须使用 NF 或 NF CN

---

## 总结 / Summary

- **Maple Mono**: 轻量级基础版本，适合纯英文环境
- **Maple Mono NF**: 增加图标支持，适合现代化开发工具
- **Maple Mono NF CN**: 完整的中文+图标支持，适合中文开发者

选择哪个版本取决于你的具体需求：语言支持、图标需求和文件大小考虑。

The choice between versions depends on your specific needs: language support, icon requirements, and file size considerations.

---

## 参考链接 / References

- [Maple Mono Official Repository](https://github.com/subframe7536/maple-font)
- [Nerd Fonts Project](https://www.nerdfonts.com/)
- [Programming Fonts](https://www.programmingfonts.org/)
