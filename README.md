# altfork Brand Assets

altfork.dev 的品牌标志与网站图标资源，由 Arvin 维护。本仓库用于集中管理设计原稿、不同尺寸的图标及使用说明。

![altfork 标志](logo/altfork-mark.svg)

## 设计说明

标志将 Git 提交图与轨道分岔结合：橙色路径从主线分出，灰色节点与断开的旧线路形成对照，表达 altfork 对独立探索和新方向的关注。

- 主色：橙色 `#ED653B`
- 辅色：灰色 `#7A8499`
- 应用图标底色：`#16181F`
- SVG 原稿采用 `256 × 256` 的 viewBox，可按需缩放。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `logo/altfork-mark.svg` | 品牌标志原稿，可用于网页页头、页脚和品牌展示 |
| `icons/favicon.svg` | 支持 SVG 的浏览器标签页图标 |
| `icons/favicon.ico` | 浏览器兼容图标 |
| `icons/favicon-16.png`、`icons/favicon-32.png` | 16 / 32 像素标签页图标 |
| `icons/apple-touch-icon.png` | 180 像素 Apple 触摸图标 |
| `icons/icon-192.png`、`icons/icon-512.png` | 192 / 512 像素应用图标 |
| `icons/app-icon.svg` | 带深色底的应用图标矢量版本 |
| `icons/safari-pinned-tab.svg` | Safari 固定标签页单色图标 |
| `icons/site.webmanifest` | 应用名称、图标路径及显示配置 |

## 网站接入

将 `logo/altfork-mark.svg` 复制到网站的 `/assets/altfork-mark.svg`，即可引用：

```html
<img src="/assets/altfork-mark.svg" width="34" height="34" alt="altfork.dev">
```

将 `icons/` 内的文件复制到网站根目录，再在 HTML 的 `<head>` 中加入：

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png" sizes="180x180">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#ED653B">
<link rel="manifest" href="/site.webmanifest">
```

`site.webmanifest` 使用从网站根目录开始的图标路径。如果部署在子目录，请同步调整 HTML 和清单中的路径。

## 版权与使用许可

Copyright © 2026 Arvin.

除另有说明外，本仓库中本人有权授权的设计资源采用 **Creative Commons 署名—非商业性使用 4.0 国际许可协议（CC BY-NC 4.0）** 公开。

你可以在遵守许可的前提下，为非商业目的分享、复制或修改这些资源；使用时须保留适当署名、提供许可链接，并标明是否修改。商业使用请先联系 Arvin，取得另行授权。

署名示例：

> altfork 品牌标志，由 Arvin 提供，来源：https://github.com/Arvin-work/altfork-brand-assets ，采用 CC BY-NC 4.0（https://creativecommons.org/licenses/by-nc/4.0/）。修改情况：未修改（如有修改，请据实说明）。

本仓库是公开的设计资源仓库。许可不表示 Arvin 或 altfork 对使用者及其项目的背书，也不授予商标权。不得以使用这些资源为由暗示官方关联或授权。

许可摘要：[CC BY-NC 4.0 中文说明](https://creativecommons.org/licenses/by-nc/4.0/deed.zh-hans)。完整条款以 [Creative Commons 官方许可全文](https://creativecommons.org/licenses/by-nc/4.0/legalcode) 为准；本说明不增加或替代该许可的条款。

## 联系与权利反馈

如需商业授权、反馈设计问题，或认为本仓库中的内容侵犯了你的著作权或其他合法权益，请通过以下任一方式与我联系：

- 在本仓库提交 [Issue](https://github.com/Arvin-work/altfork-brand-assets/issues)。
- 通过当前 GitHub 账户的邮箱联系我；账户入口：[Arvin-work](https://github.com/Arvin-work)。

提交权利反馈时，请说明涉及的文件、权利依据及相关材料。我会核实，并根据核实结果及时采取更正、替换或移除等措施。请勿在公开 Issue 中提交身份证件或其他敏感个人信息；如需提供非公开材料，可通过账户邮箱联系。
