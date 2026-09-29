# 敦煌 · Holographic Candlestick

3D 全息烛台手势交互界面 — 使用 MediaPipe Hands 计算机视觉 + Three.js + 纯 JavaScript。

## 交互方式

- **张合手掌 → 缩放烛台**：握拳缩小，完全张开放大
- **移动手掌 → 平移烛台**：张开手左右上下移动，烛台实时跟随

## 技术栈

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) — 21 关键点手部追踪
- [Three.js](https://threejs.org/) — 3D 渲染（LatheGeometry 车削体建模黄铜烛台）
- 纯原生 JavaScript，无构建工具，单文件即可运行

## 使用方法

1. 克隆仓库后用浏览器打开 `index.html`
2. 允许摄像头权限
3. 对着摄像头张合/移动手掌即可交互

> 注意：摄像头 API 需要 HTTPS 或 localhost 环境。

## 功能

- 摄像头全屏镜像显示
- 视频可见度滑块调节（黑底遮罩）
- 烛火实时闪烁动画
- 全息扫描线 + 地面光环呼吸效果
- 手部骨架可视化叠加
- 复位按钮
