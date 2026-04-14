# 📱 预览页面生成器 (app-showcase-iphone-skill)

已创建 `app-showcase-iphone-skill` Skill，包含以下文件：

```
skills/app-showcase-iphone-skill/
├── README.md      # 本说明文档
├── SKILL.md       # Skill 元数据定义
└── template.html  # HTML 模板（带深色模式支持）
```

**核心功能：**

- 📱 iPhone 16 Pro 框架 + 灵动岛
- 🌙 深色/浅色模式切换（localStorage 记忆）
- ⏰ 动态状态栏（实时时间、信号、WiFi、电量）
- 📐 自适应缩放 iframe
- 📱 响应式设计

---

## 🧑‍💻 给开发者使用

**激活 Skill：**
用户说"生成预览页面" → 自动激活 Skill → 自动检测 → (若失败)询问应用信息 → 生成 `preview.html`

**模板变量：**

- `{APP_NAME}` - 应用名称
- `{LOGO_PATH}` - Logo 图片路径
- `{SUBTITLE}` - 副标题
- `{BASE_URL}` - 基础 URL
- `{PAGES_JSON}` - 页面列表 JSON

---

## 👤 用户使用

**使用流程：**

1. **找到预览文件**开发者生成 `preview.html` 后，双击文件在浏览器中打开
2. **查看效果**

   - 自动显示 5 个 iPhone 框架页面预览
   - 点击右上角 ☀️/🌙 切换深色/浅色模式
3. **分享链接**

   - 可以截屏或录屏分享给其他人
   - 点击底部"打开完整应用 →"直接体验

**无需安装任何东西**，只需一个浏览器即可查看。

**常见问题：**

| 问题         | 解决                               |
| ------------ | ---------------------------------- |
| 预览页面空白 | 确保应用已启动（运行 npm run dev） |
| 想添加新页面 | 联系开发者修改 pages 数组          |

---

## 📦 交付物

生成的文件：

| 文件                         | 说明           |
| ---------------------------- | -------------- |
| `preview.html`             | 预览页面主文件 |
| `preview.html 使用说明.md` | 用户使用指南   |

## 📃 示例

![1776144391926](https://p9-juejin-sign.byteimg.com/tos-cn-i-k3u1fbpfcp/2609a82aa92a440a92f9160b007b26d3~tplv-k3u1fbpfcp-jj-mark-v1:0:0:0:0:5o6Y6YeR5oqA5pyv56S-5Yy6IEAg56qX6L6555qEYW5pbmk=:q75.awebp?rk3s=f64ab15b&x-expires=1776749848&x-signature=rxbjnNXccronyHEhkWCkuzs0rDE%3D)

![1776144429720](https://p9-juejin-sign.byteimg.com/tos-cn-i-k3u1fbpfcp/2832f7fa27ae4d188c3d3d5f4fd1ed47~tplv-k3u1fbpfcp-jj-mark-v1:0:0:0:0:5o6Y6YeR5oqA5pyv56S-5Yy6IEAg56qX6L6555qEYW5pbmk=:q75.awebp?rk3s=f64ab15b&x-expires=1776749848&x-signature=ci4vE3GwSuGL6BpW6voc%2FiAosNg%3D)

![1776144450694](https://p9-juejin-sign.byteimg.com/tos-cn-i-k3u1fbpfcp/08f259756fbb4e8481ab093453ae5037~tplv-k3u1fbpfcp-jj-mark-v1:0:0:0:0:5o6Y6YeR5oqA5pyv56S-5Yy6IEAg56qX6L6555qEYW5pbmk=:q75.awebp?rk3s=f64ab15b&x-expires=1776749848&x-signature=9AkHBgO66kcBICl8TtOSCxS6Ht0%3D)