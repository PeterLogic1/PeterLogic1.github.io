# Peter Logic Blog

> 一个基于 Jekyll 的个人博客网站

这是我的个人博客，基于 Jekyll 构建，使用 Hux Blog 主题。

## 网站地址

🌐 [PeterLogic1.github.io](https://PeterLogic1.github.io)

## 技术栈

- **Jekyll** - 静态网站生成器
- **Bootstrap** - 前端框架
- **GitHub Pages** - 网站托管

## 本地开发

### 环境要求

1. 安装 [Ruby](https://www.ruby-lang.org/en/)
2. 安装 [Bundler](https://bundler.io/)

### 运行步骤

1. 克隆仓库：
```bash
git clone https://github.com/PeterLogic1/PeterLogic1.github.io.git
cd PeterLogic1.github.io
```

2. 安装依赖：
```bash
bundle install
```

3. 启动本地服务器：
```bash
bundle exec jekyll serve
```

4. 访问 `http://localhost:4000` 查看网站

## 项目结构

```
├── _config.yml          # Jekyll 配置文件
├── _includes/           # 可重用的模板片段
├── _layouts/            # 页面布局模板
├── _posts/              # 博客文章
├── css/                 # 样式文件
├── js/                  # JavaScript 文件
├── img/                 # 图片资源
└── about.html           # 关于页面
```

## 自定义配置

主要配置文件是 `_config.yml`，你可以修改：

- 网站标题和描述
- 个人信息和联系方式
- 社交网络链接
- 主题设置

## 许可证

Apache License 2.0

## 致谢

感谢 [Hux](https://github.com/Huxpro) 提供的优秀 Jekyll 主题！
