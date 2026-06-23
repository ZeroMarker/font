# Nerd Fonts

Nerd Fonts 不是单一字体，而是一个面向开发者的字体补丁和聚合项目。它会在常见编程字体中加入大量图标字形，使终端、状态栏、文件树、提示符和命令行工具可以直接显示图标。

## 定位

Nerd Fonts 适合终端和开发工具生态。它解决的不是正文阅读问题，而是“开发者字体需要图标”的问题。很多命令行主题、Neovim 插件、状态栏工具和 shell prompt 都依赖 Nerd Fonts 中的图标码位。

## 风格特征

- 聚合和补丁项目，不是独立字体风格。
- 给现有编程字体加入图标字形。
- 适合终端、编辑器、文件树和状态栏。
- 字体数量和变体很多，选择时需要确认基础字体。
- 图标显示依赖终端和应用对字体宽度的处理。

## 适用场景

- Powerlevel10k、Starship 等终端提示符。
- Neovim、VS Code 终端、Tmux 状态栏和文件图标。
- 需要 Font Awesome、Devicons、Octicons 等图标字形的命令行环境。
- 开发者个性化桌面环境。

## 不适合场景

- 普通正文、品牌视觉和印刷排版。
- 不需要图标码位的简洁开发环境。
- 对字体文件体积敏感的 Web 正文加载。
- 需要严格控制所有图标授权来源的商业产品内嵌场景。

## 排版建议

选择 Nerd Fonts 时，应先选基础字体，例如 JetBrains Mono、Fira Code、Hack、Maple Mono 或更纱黑体相关补丁版本。图标显示异常时，问题常见于字体没有正确安装、终端没有选择 Nerd Font 版本、图标码位变化或 fallback 字体抢占。

不建议把 Nerd Fonts 用作网页正文。若 Web 项目只需要少量图标，应优先使用 SVG 图标或图标组件库，而不是加载完整补丁字体。

## 授权注意

Nerd Fonts 项目包含不同来源的字体、图标和补丁工具，许可证并不只有一种。项目许可证说明中区分了字体、补丁工具和各类来源资源。商业产品内嵌或再分发时，应检查所选具体补丁字体、基础字体和图标来源的许可证。

## 参考链接

- 官方网站：<https://www.nerdfonts.com/>
- GitHub: <https://github.com/ryanoasis/nerd-fonts>
- 许可证说明：<https://github.com/ryanoasis/nerd-fonts/blob/master/LICENSE>
