# AureliAxis Pharmaceuticals 虚拟网站

![AureliAxis Logo](images/logo.svg)

## 项目简介

AureliAxis Pharmaceuticals 是一个虚拟的医药公司网站项目，专为个人学习和前端开发练习而设计。该项目模拟了一个现代化的医药企业网站，包含公司概述、产品管线、组织架构、KPI体系、管理系统等完整功能模块。

## 技术栈

- **前端框架**：纯HTML5 + CSS3 + JavaScript
- **CSS框架**：Tailwind CSS v3
- **图标库**：Font Awesome 4.7.0
- **字体**：Inter + Noto Sans SC
- **数据可视化**：原生SVG
- **响应式设计**：支持桌面端、平板和移动端

## 功能特性

- **完整的网站结构**：公司概述、产品管线、组织架构、KPI体系、管理系统、联系我们
- **交互式组织架构**：点击团队卡片可展开查看详细架构
- **产品展示**：三款虚拟药物的详细介绍，包含定制SVG logo
- **管理系统**：Insight 360和REP360的独立页面
- **响应式设计**：适配各种屏幕尺寸
- **专业的视觉设计**：医疗科技蓝色主题，现代化UI
- **SVG图标和插图**：自定义的产品logo和网站banner

## 如何运行

### 方法一：本地服务器（推荐）

1. 克隆或下载本项目到本地
2. 进入项目目录
3. 启动本地服务器

   ```bash
   # 使用Python 3
   python3 -m http.server 8000
   
   # 或使用Python 2
   python -m SimpleHTTPServer 8000
   
   # 或使用Node.js
   npx http-server -p 8000
   ```

4. 在浏览器中访问：`http://localhost:8000`

### 方法二：直接打开

- 直接在浏览器中打开 `index.html` 文件
- 注意：部分功能可能因跨域限制无法正常工作

## 项目结构

```
AureliAxis_Website/
├── index.html          # 主页面
├── insight360.html     # Insight 360系统页面
├── rep360.html         # REP360系统页面
├── images/             # 图片和SVG资源
│   ├── logo.svg        # 公司logo
│   ├── logo-white.svg  # 白色版本logo
│   ├── banner.svg      # 网站banner
│   ├── product-aurelimab.svg    # AureliMab™产品logo
│   ├── product-lymphoaxis.svg   # LymphoAxis™产品logo
│   └── product-cardioaureli.svg # CardioAureli™产品logo
└── README.md           # 项目说明文档
```

## 虚拟数据说明

本项目中的所有数据均为虚拟数据，包括：
- 公司信息和组织架构
- 产品信息和功能描述
- KPI指标体系
- 管理系统功能
- 联系信息

这些数据仅用于学习和展示目的，不代表任何真实公司或产品。

## 学习价值

- **前端开发**：学习HTML5、CSS3、JavaScript的综合应用
- **响应式设计**：掌握Tailwind CSS的响应式布局技巧
- **SVG应用**：学习SVG图标和插图的设计与使用
- **用户交互**：实现交互式组织架构和页面跳转
- **项目结构**：了解现代网站的基本结构和组织方式
- **视觉设计**：学习医疗行业网站的设计风格和配色方案

## 注意事项

1. 本项目仅用于个人学习和前端开发练习
2. 所有数据均为虚拟，请勿用于商业用途
3. 如需部署到生产环境，请确保替换为真实数据
4. 部分功能可能需要本地服务器环境才能正常运行

## 许可证

本项目采用 MIT 许可证，详见 [LICENSE](LICENSE) 文件。

## 贡献

欢迎提交问题和改进建议！如果您有任何想法或建议，欢迎在项目中创建 issue 或提交 pull request。

---

**享受学习过程，构建精彩项目！** 🚀