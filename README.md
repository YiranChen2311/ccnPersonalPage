# 个人网页

这是一个简洁美观的个人介绍网站，包含个人简介和作品集展示功能。

## 文件结构

```
.
├── index.html          # 主页面
├── style.css           # 样式文件
├── script.js           # JavaScript 交互功能
├── images/             # 图片文件夹
│   ├── profile.jpg     # 个人照片
│   ├── work1.png       # 作品 1
│   ├── work2.png       # 作品 2
│   └── work3.png       # 作品 3
└── README.md           # 说明文档
```

## 使用步骤

### 1. 准备图片

创建 `images` 文件夹，并将你的图片放入：
- `profile.jpg` - 你的个人照片
- `work1.png`, `work2.png`, `work3.png` 等 - 你的作品集图片（PNG 长图）

### 2. 修改内容

编辑 `index.html` 文件，替换以下内容：
- 将 `[你的名字]` 替换为你的真实姓名
- 修改"关于我"部分的个人介绍
- 更新作品集的标题和描述
- 修改联系方式信息

### 3. 添加更多作品

如果你有更多作品，可以在 `index.html` 的作品集部分复制以下代码：

```html
<div class="portfolio-item">
    <img src="images/work4.png" alt="作品 4">
    <div class="portfolio-overlay">
        <h3>作品标题 4</h3>
        <p>作品描述</p>
    </div>
</div>
```

### 4. 本地预览

直接双击 `index.html` 文件，或使用本地服务器：

```bash
# 使用 Python 3
python3 -m http.server 8000

# 使用 Node.js (需要安装 http-server)
npx http-server
```

然后在浏览器中访问 `http://localhost:8000`

## 部署到网上

### 方式 1: GitHub Pages（免费）

1. 在 GitHub 创建一个新仓库
2. 将所有文件上传到仓库
3. 在仓库设置中启用 GitHub Pages
4. 你的网站将在 `https://你的用户名.github.io/仓库名` 访问

### 方式 2: Netlify（免费）

1. 访问 [netlify.com](https://www.netlify.com)
2. 注册账号
3. 将整个文件夹拖拽到 Netlify 的部署区域
4. 获得一个免费的网址

### 方式 3: Vercel（免费）

1. 访问 [vercel.com](https://vercel.com)
2. 注册账号
3. 导入你的项目
4. 自动部署并获得网址

## 功能特点

- ✅ 响应式设计，支持手机、平板、电脑
- ✅ 平滑滚动导航
- ✅ 作品集图片悬停效果
- ✅ 点击图片放大查看（适合长图展示）
- ✅ 现代化的设计风格
- ✅ 无需后端，纯静态网站

## 自定义样式

如果你想修改颜色、字体等样式，可以编辑 `style.css` 文件中的以下变量：

- 主色调：搜索 `#3498db` 并替换为你喜欢的颜色
- 深色背景：搜索 `#2c3e50` 并替换
- 字体：修改 `font-family` 属性

## 技术栈

- HTML5
- CSS3
- JavaScript (原生)
- 无需任何框架或库

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

## 许可

可自由使用和修改。
