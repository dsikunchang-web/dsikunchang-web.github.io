# 张子坤 · 个人介绍

macOS 液态玻璃 × HarmonyOS 7 沉浸光感风格的个人主页。

线上地址：https://dsikunchang-web.github.io/

## 特性

- 单文件、零依赖：`index.html` 内联 CSS / SVG / Canvas / 原生 JS
- 晨光 / 夜色双主题
- 光感三档：弱 / 均衡 / 强
- Canvas 光标拖尾：跟随鼠标的彗星头、光带与粒子，可在标题栏「拖尾」开关
- macOS 窗口、Dock、交通灯、联系弹窗、单文件下载

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://127.0.0.1:8000/
```

## 说明

页面使用系统字体与原生 CSS/Canvas，无外部 CDN 依赖。实时背景模糊在集成显卡上开销过高，因此采用清玻璃 + 高光/折射边的实现；「光感 · 弱」会关闭拖尾与背景动画。
