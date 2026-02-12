# dongabing.github.io 博客项目

这是一个基于 Jekyll 构建的静态博客项目，用于展示个人技术分享与学习笔记。

## 快速开始

### 环境准备

- **Ruby 版本要求**：建议使用 Ruby 2.7 或更高版本。
- 安装 Jekyll 和 Bundler：`gem install jekyll bundler`

### 安装依赖

在项目根目录下运行以下命令安装所需依赖：`bundle install`

### 运行项目

启动本地服务器以预览博客：`bundle exec jekyll serve`

默认访问地址为：[http://localhost:4000](http://localhost:4000)

## 常见问题排查

### 1. `bundle install` 失败
- 确保已正确安装 Ruby 和 Bundler。
- 尝试更换源：`bundle config mirror.https://rubygems.org https://gems.ruby-china.com`

### 2. 端口被占用
- 修改 Jekyll 启动端口：`bundle exec jekyll serve --port 4001`

### 3. 其他问题
- 查看官方文档获取更多帮助：[Jekyll 官方教程](https://jekyllrb.com/docs/)
