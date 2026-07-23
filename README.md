# 泰语词域

面向中文学习者的 B1–C1 泰语词汇网站，包含 6000 个词条、例句、中文拆解、分页搜索、收藏与学习进度。

## 跨平台发音

- 优先使用浏览器检测到的自然泰语系统音色。
- Windows 没有安装泰语语音时，自动加载随网站发布的 eSpeak NG 浏览器语音组件。
- 所有内置语音合成都在用户浏览器内完成，不上传学习内容，也不需要 API 密钥。

首次使用内置语音需要下载约 9 MB 的压缩组件，之后浏览器可从缓存中复用。

## 开源组件

内置语音使用 [eSpeak NG](https://github.com/espeak-ng/espeak-ng) 的 WebAssembly 构建，按 GPL-3.0-or-later 分发。许可证文本见 `LICENSE-espeak-ng.txt`，使用的浏览器构建来源见 [espeak-ng.js](https://github.com/ianmarmour/espeak-ng.js)。
