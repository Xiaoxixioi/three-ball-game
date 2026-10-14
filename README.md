# 三球游戏 · Three Ball Game

基于 Three.js 的 HTML5 3D 小游戏：无限轨道、球体跳跃、星云背景、陨石障碍、护盾与触控支持。

## 在线游玩（固定域名 · GitHub Pages）

- 入口（裸域名直达）：https://xiaoxixioi.github.io/three-ball-game/
- 直链：https://xiaoxixioi.github.io/three-ball-game/three-ball.html

## 本地运行

由于使用了 ES Module + importmap，需通过 HTTP 服务打开（不能直接双击 `file://`）：

- 在本目录运行 `PlayGame.bat`（或任意静态服务器）后访问 `three-ball.html`。

## 目录结构

- `three-ball.html` — 游戏主程序
- `vendor/three/` — 本地 Three.js 模块（离线可用，无 CDN 依赖）
- `assets/nebula/` — NASA 星云背景贴图
- `index.html` — 裸域名跳转入口

## 技术要点

- 陨石对象池、星空软精灵、面光补光、轨道分道安全门、触控框架（点击 / 滑动 / 虚拟按键）。
