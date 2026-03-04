# NEON REMNANT - BONUS TURN v8.5

一个基于网页的回合制策略游戏。

## 📁 项目结构

```
neon_remnant_game/
│
├── index.html                    # 游戏主文件（直接打开即可运行）
│
├── assets/                       # 资源文件夹
│   ├── textures/                # 材质文件夹（用于未来的3D材质）
│   ├── audio/                   # 音频文件夹（用于自定义背景音乐）
│   └── images/                  # 图像文件夹（用于游戏UI/背景等）
│
├── js/                          # JavaScript 脚本文件夹（可选扩展）
├── css/                         # CSS 样式表文件夹（可选扩展）
│
└── README.md                    # 本文件
```

## 🚀 运行游戏

### 方法一：直接打开（推荐）
1. 找到 `index.html` 文件
2. 双击打开或右键选择「用浏览器打开」
3. 游戏将在浏览器中加载并运行

### 方法二：使用本地服务器（推荐用于添加外部资源）
如果你计划添加外部资源（如音频、图像等），建议使用本地服务器：

**Windows 用户（使用 Python）：**
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

**Windows 用户（使用 Node.js）：**
```bash
# 安装 http-server
npm install -g http-server

# 运行服务器
http-server
```

然后在浏览器中访问：`http://localhost:8000`

## 🎮 游戏说明

### 基本按键
- **标准打擊** - 基础攻击，恢复 EN
- **戰術強擊** - 强力打击，消耗 EN 进行破防
- **精準打擊** - 精确打击，消耗 10 EN
- **系統駭入** - 黑客干扰，消耗 EN
- **能量防禦** - 防守，恢复少量 EN

### 游戏目标
- 击败敌人并升级
- 在补给站购买升级模组
- 每 5 关会遇到 BOSS
- 尽可能地活下去

## 📦 资源文件夹说明

### `assets/textures/`
用于存放三维模型材质文件（.png, .jpg, .obj, .mtl 等）

### `assets/audio/`
用于存放背景音乐和音效文件（.mp3, .wav, .ogg 等）

### `assets/images/`
用于存放 UI 图片、背景、角色立绘等（.png, .jpg, .svg 等）

## 💡 扩展建议

1. **添加自定义音乐**
   - 在 `assets/audio/` 中放置 MP3 文件
   - 在代码中添加音频控制

2. **添加背景图像**
   - 在 `assets/images/` 中放置背景图
   - 修改 CSS 的 `background` 属性

3. **分离代码**
   - 将 JavaScript 代码提取到 `js/` 文件夹
   - 将 CSS 提取到 `css/` 文件夹
   - 在 HTML 中使用外部引用

## 🌐 浏览器兼容性

- Chrome / Chromium （推荐）
- Firefox
- Safari
- Edge

## 📝 许可证

此游戏为个人项目。

---

**提示：** 游戏完全基于 HTML5 + JavaScript，不需要额外安装任何软件，直接在浏览器中运行即可！
