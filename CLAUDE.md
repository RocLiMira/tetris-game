# Tetris Game - AI 项目说明书

## 项目概述

经典俄罗斯方块游戏，使用纯 HTML5 Canvas + 原生 JavaScript 实现，零框架依赖。
目标是提供流畅的游戏体验，代码结构清晰易维护。

## 构建与运行

- 无构建步骤，直接打开 `index.html` 即可运行
- 本地开发可用 `npx serve .` 启动静态服务器
- 无需安装任何 npm 依赖

## 项目结构

```
tetris-game/
├── index.html      # 入口页面
├── style.css       # 样式文件
├── game.js         # 游戏主逻辑
├── README.md
├── CLAUDE.md
├── LICENSE
└── .gitignore
```

## 代码规范

- 使用 ES6+ 语法（const/let、箭头函数、模板字符串等）
- 缩进：2 个空格
- 命名：变量和函数使用 camelCase，常量使用 UPPER_SNAKE_CASE
- 文件命名：kebab-case
- 所有字符串使用单引号
- 语句末尾加分号
- 注释使用中文

## 分支命名规范

- 功能开发：`feat/<功能名>`
- 缺陷修复：`fix/<问题描述>`
- 重构：`refactor/<重构内容>`
- 文档：`docs/<文档内容>`
