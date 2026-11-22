# ProjectAlaska 笔记本连线原型（网页版）

**▶ 直接游玩：https://anarchy0316.github.io/ProjectAlaska-web/**

（仓库页面只是构建产物；点上面的链接或右侧「Visit site」进入游戏。）

首次加载约 56MB（wasm 39.5MB + pck 16.5MB），耐心等 Godot 进度条走完。

## 操作
- 自由拖动：默认模式，拖肖像移动
- 点名字牌：改姓名（名/姓分两列，每列 6 条翻页）
- 杀害了 / 伴侣 / 是其父、母：按住一张肖像拖到另一张松手成线
- 橡皮擦：点虚线擦除（实线不可擦）
- 滚轮缩放，中键/空白处拖动平移
- F2：显示所有正确答案（紫色姓名 + 淡色关系虚线）
- 底部「控制台」：reset / add / pool / arrange ring|grid / help

## 说明
- Godot 4.7.2 导出，单线程 Web 版；无存档，刷新会重置
- 字体：霞鹜文楷（SIL OFL）
