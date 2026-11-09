# COS10026 Assignment 1

[English](README.md) | [简体中文](README.zh-CN.md)

## 项目简介

本仓库是为 COS10026 Computing Technology Inquiry Project 创建的静态仙人掌与多肉植物商店网站。网站展示仙人掌相关商品、顾客注册与订单表单、团队成员资料，以及 HTML5 和 CSS 增强效果。

网站使用 HTML5 和 CSS 构建，不需要软件包管理器、构建流程、数据库或服务器端程序。

## 主要页面

- `index.html` - 首页，包含自动播放的背景视频和精选商品
- `product.html` - 商品分类总览
- `succulent.html` - 仙人掌与多肉植物目录
- `pots.html` - 花盆目录
- `tools.html` - 园艺工具目录
- `others.html` - 土壤、肥料、装饰品和其他种植用品
- `registration.html` - 顾客注册表单
- `order.html` - 商品选择与订单表单
- `aboutus.html` - 小组介绍
- `profile_1.html` 至 `profile_5.html` - 小组成员个人资料
- `enhancement.html` - 悬停效果、下拉菜单、HTML5 视频和 figure 元素示例

注册和订单表单通过 `mailto:` 调用用户的电子邮件客户端提交。本项目没有后端或数据库，因此网站不会储存提交的信息。

## 项目结构

```text
COS10026-Assignment-1/
|-- index.html              # 网站入口
|-- product.html            # 商品分类总览
|-- succulent.html          # 仙人掌目录
|-- pots.html               # 花盆目录
|-- tools.html              # 园艺工具目录
|-- others.html             # 其他商品目录
|-- registration.html       # 顾客注册表单
|-- order.html              # 订单表单
|-- aboutus.html            # 小组介绍
|-- profile_1.html ...      # 小组成员资料
|-- enhancement.html        # HTML5 与 CSS 增强效果
|-- style.css               # 所有页面共用的样式
|-- images/                 # 商品、成员、标志和界面图片
|-- videos/
|   `-- video.mp4           # 首页和增强页面使用的视频
|-- README.md               # 英文说明
`-- README.zh-CN.md         # 简体中文说明
```

## 克隆仓库

```bash
git clone https://github.com/print1Username/COS10026-Assignment-1.git
cd COS10026-Assignment-1
```

## 运行网站

### 方法一：直接打开文件

使用现代浏览器打开 `index.html`，不需要安装任何依赖。

### 方法二：启动本地服务器

如果电脑已安装 Python 3，请在项目文件夹中运行：

```bash
python -m http.server 8000
```

然后在浏览器中打开 [http://localhost:8000](http://localhost:8000)。

如需停止服务器，请在终端中按 `Ctrl+C`。

## 使用技术

- HTML5
- CSS3
- 本地图片与 MP4 视频资源

## 注意事项

- 请保留现有文件夹结构，因为 HTML 文件通过相对路径读取 `style.css`、`images/` 和 `videos/`。
- 只有打开外部链接时才需要网络连接；网站的主要内容使用本地文件。
- 本网站仅用于教学和非商业用途。
