# Ghostty 终端配置

深色半透明主题 + Bloom 辉光 + 光标拖影特效，基于 JetBrainsMono Nerd Font。

## 安装

### 1. 安装 Ghostty

从 [ghostty.org](https://ghostty.org/) 下载安装。

### 2. 安装字体

```bash
brew install --cask font-jetbrains-mono-nerd-font
```

### 3. 部署配置

```bash
# 备份已有配置
mv ~/.config/ghostty ~/.config/ghostty.bak 2>/dev/null

# 克隆到配置目录
git clone <本仓库地址> ~/.config/ghostty
```

重启 Ghostty 即可生效。

## 快捷键

### 窗口管理

| 操作 | 快捷键 |
|------|--------|
| 新建窗口 | `Cmd+N` |
| 关闭窗口 | `Cmd+Shift+W` |

### Tab 页

| 操作 | 快捷键 |
|------|--------|
| 新建 Tab | `Cmd+T` |
| 关闭 Tab | `Cmd+W` |
| 切换到上一个 Tab | `Cmd+Shift+[` |
| 切换到下一个 Tab | `Cmd+Shift+]` |
| 切换到第 N 个 Tab | `Cmd+1` ~ `Cmd+9` |

### 分屏 (Split)

| 操作 | 快捷键 |
|------|--------|
| 左右分屏 | `Cmd+D` |
| 上下分屏 | `Cmd+Shift+D` |
| 切换到上/下/左/右分屏 | `Cmd+Alt+方向键` |
| 关闭当前分屏 | `Cmd+W` |
| 等分所有分屏 | `Cmd+Shift+Enter` |

### 自定义快捷键

| 操作 | 快捷键 |
|------|--------|
| 快速终端 (Quick Terminal) | `Cmd+S` |
| 重载配置 | `Cmd+R` |
| 检查器 | `Cmd+I` |

## 着色器

当前启用了 `bloom1`（辉光）、`cursor_blaze_no_trail`（光标闪烁）、`cursor_smear`（光标拖影）。

`shaders/` 目录下还有 30+ 个可选着色器（CRT、矩阵雨、星空、烟花等），编辑 `config` 文件注释/取消注释对应行即可切换。

更多社区着色器：[ghostty-shaders](https://github.com/hackrmomo/ghostty-shaders)
