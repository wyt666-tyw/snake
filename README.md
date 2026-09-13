# 贪吃蛇 Snake

一个基于 HTML5 Canvas 的经典贪吃蛇网页小游戏。

## 快速开始

无需安装任何依赖，直接用浏览器打开 `index.html` 即可：

```bash
# 方式一：直接双击 index.html
# 方式二：命令行打开（Windows）
start index.html
```

## 操作方式

- 方向键 ↑ ↓ ← → 或 W A S D：控制蛇的移动方向
- 开始 / 暂停：使用页面上的按钮

## 项目结构

```
.
├── index.html   # 页面结构、画布与基础样式
├── LICENSE      # MIT 许可证
└── README.md    # 项目说明
```

## 技术栈

- HTML5
- CSS3
- HTML5 Canvas

## 游戏规则

- 使用方向键或 WASD 控制蛇的移动方向（不能直接 180° 掉头）
- 吃到红色食物：蛇身变长一节，得分 +10
- 撞到墙壁或自己的身体：游戏结束
- 最高分通过浏览器 localStorage 本地保存

## 开发状态

手动游玩版已完成（键盘控制、食物、计分、碰撞结束、暂停 / 重新开始）。

## 许可证

本项目基于 [MIT License](LICENSE) 开源。
