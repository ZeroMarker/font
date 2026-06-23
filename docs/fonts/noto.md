# Noto

Noto 是 Google 推出的多文字系统字体项目，目标是覆盖全球大量语言和文字系统，减少系统缺字时出现的“豆腐块”问题。它不是单一字体，而是一组庞大的字体家族，包含 Sans、Serif、Mono、CJK、Emoji 等多个方向。

## 定位

Noto 适合作为多语言产品的基础字体或 fallback 字体。对于需要跨地区、跨平台、跨文字系统显示的应用，Noto 的价值在于覆盖广、风格统一、授权清晰，并且有持续维护的项目生态。

## 风格特征

- 覆盖语言和文字系统广，适合作为兜底字体。
- 字体家族庞大，可按 Sans、Serif、Mono、CJK 等分类选择。
- 风格相对中性，强调可读性和兼容性。
- CJK 字体适合中文、日文、韩文场景，但不同地区字形需选择对应版本。
- 文件体积可能较大，Web 使用时需要子集化或按需加载。

## 适用场景

- 多语言网站、App 和桌面软件。
- 国际化产品的 fallback 字体链。
- 需要统一覆盖多文字系统的设计系统。
- 中文、日文、韩文和少数文字系统混合显示场景。

## 不适合场景

- 需要强品牌个性的标题或 logo。
- 对 Web 首屏体积极敏感且没有子集化方案的页面。
- 只需要单一语言、且已有更合适品牌字体的项目。
- 对某地区标准字形要求严格但未选择对应 CJK 区域版本的项目。

## 排版建议

多语言产品建议把 Noto 作为 fallback，而不是无差别加载全部字体。Web 场景应按语言、页面和字符集拆分加载，例如只加载 Noto Sans SC 的常用中文子集，而不是完整 CJK 文件。

中文项目使用 Noto CJK 时，应区分 SC、TC、JP、KR 等版本，避免中文简体界面中出现日文字形偏好。Emoji 场景也应单独处理 Noto Color Emoji 或系统 emoji 字体。

## 授权注意

Noto 官方文档说明 Noto 字体采用 Open Font License。商用、App 打包和数字产品使用通常可行，但不能单独出售字体文件；改作和再分发需要遵守 OFL 条款。正式项目应以具体字体仓库和许可证文件为准。

## 参考链接

- Noto 官方站：<https://notofonts.github.io/>
- Noto 使用说明：<https://notofonts.github.io/noto-docs/website/use/>
- Noto CJK: <https://github.com/notofonts/noto-cjk>
