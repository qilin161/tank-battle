# 坦克大战 Tank Battle

一个纯 HTML + JavaScript + Canvas 实现的坦克大战小游戏，无需任何依赖，单文件即可运行。

![Tank Battle](https://img.shields.io/badge/%E6%B8%B8%E6%88%8F-%E5%9D%A6%E5%85%8B%E5%A4%A7%E6%88%98-e94560)

## 🎮 玩法

- 消灭每一关的全部敌人即可过关
- 小心保护底部的基地 ⌂，被敌方子弹击中即告失败
- 击毁砖墙开辟通路，钢墙无法被摧毁
- 敌人有三种类型：普通（灰）、快速（橙）、重型（紫，3 点血量）

## ⌨️ 操作

| 按键 | 功能 |
|------|------|
| `W A S D` / 方向键 | 移动 |
| `空格` / `J` | 开火 |

## 🎁 道具

击毁敌人有几率掉落道具：

| 道具 | 效果 |
|------|------|
| ★ 星星 | 火力升级（最多 3 级，可炸穿更大范围砖墙、加快射速） |
| ❤ 生命 | 生命 +1 |
| 🛡 护盾 | 短时间无敌 |
| 💣 炸弹 | 消灭场上所有敌人 |

## 🚀 运行

直接用浏览器打开 `index.html` 即可，或者：

```bash
# 克隆仓库
git clone https://github.com/<你的用户名>/tank-battle.git
cd tank-battle
# 用任意静态服务器运行
npx serve .
```

也可以在线体验（开启 GitHub Pages 后）：`https://<你的用户名>.github.io/tank-battle/`

## 🛠️ 技术栈

- 原生 JavaScript（零依赖）
- HTML5 Canvas 渲染
- Web Audio API 合成音效（无外部音频文件）
- 内置 3 张关卡地图，可轻松在 `index.html` 中的 `LEVELS` 数组扩展新关卡

## 📄 License

MIT
