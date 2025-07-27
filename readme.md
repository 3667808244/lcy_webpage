# lcy-lang Webpage

lcy-lang 是一种强类型的数据交换语言，适用于配置文件。本项目为 lcy-lang 的网页文档，介绍其语法、类型系统和用法。

## 项目简介

本网页旨在为 lcy-lang 用户提供详细的语法说明、类型系统介绍及常用示例，帮助开发者快速上手和查阅相关资料。

## 主要特性

- 详细的 lcy-lang 语法说明
- 类型系统与注解示例
- 支持多种注释与数据结构
- 转换标记（change_sign）机制说明
- 响应式、简洁的网页界面

## 目录结构

```
.
├── index.html           # 项目入口
├── readme.md            # 项目说明文档
├── css/
│   ├── main.css         # 主样式表
│   └── lcy-lang.css     # lcy-lang 专用样式
├── font/                # 字体文件
├── html/
│   └── index.html       # 主要内容页面
├── img/                 # 图片资源
├── js/                  # 预留 JS 目录
```

## 快速预览

1. 克隆或下载本项目到本地
2. 用浏览器打开 `html/index.html` 即可查看文档页面

## lcy-lang 语法简介

- 基本格式：`key : type = value @change_sign ;`
- 支持单行注释（`#`、`//`）和块注释（`/* ... */`）
- 静态类型系统，支持 int、float、bool、str、arr、tup、opt、ret、obj 等类型
- 支持 change_sign 转换标记机制，内置多种常用转换

## 贡献

欢迎提交 issue 或 PR 改进文档内容和样式。

## License

MIT
