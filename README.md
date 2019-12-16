# Vusion VSCode Extension

Vusion VSCode Extension

[![NPM Version][version-img]][vscode-url]
[![Dependencies][download-img]][vscode-url]
[![NPM Download][rating-img]][vscode-url]

[circleci-img]: https://img.shields.io/circleci/project/github/vusion/vusion-vscode.svg?style=flat-square
[circleci-url]: https://circleci.com/gh/necfe/ts-repo-boilerplate
[version-img]: https://img.shields.io/visual-studio-marketplace/v/vusion.vusion-vscode.svg?style=flat-square
[download-img]: https://img.shields.io/visual-studio-marketplace/d/vusion.vusion-vscode.svg?style=flat-square
[rating-img]: https://img.shields.io/visual-studio-marketplace/r/vusion.vusion-vscode.svg?style=flat-square
[vscode-url]: https://marketplace.visualstudio.com/items?itemName=vusion.vusion-vscode

## Features

### 页面栏

聚集项目中的页面，方便添加删除，以及管理路由。

![Preview](https://github.com/vusion/vusion-vscode/raw/master/assets/screenshot-1.png)

- 页面列表
    - 添加枝页面...
        - 添加包裹页 LWrapper
        - 添加空页面
        - 从区块添加
    - 添加子页面...
        - 添加空页面
        - 从区块添加
        - 添加 Markdown 页面
    - 查看路由配置
    - 复制 Hash 路由
    - 复制 History 路由
- 选中页面的区块
    - 添加区块
    - 删除区块

### 组件栏

![Preview](https://github.com/vusion/vusion-vscode/raw/master/assets/screenshot-2.png)

- 显示项目中组件列表
    - 新建文件夹
    - 从模板创建...
        - 创建区块包
        - 创建组件包
        - 创建单文件组件
        - 创建多文件组件
        - 创建含有文档的多文件组件
    - 添加组件功能...
        - 添加模块 CSS
        - 添加 YAML API
        - 添加文档
        - 添加 package.json
    - 删除组件
    - 编写组件文档
    - 查看 API
- 显示组件库组件列表
    - 快速扩展组件...
        - 扩展样式（JS+CSS）
        - 仅扩展逻辑（JS）
        - 覆盖模板（JS+HTML）
        - 全部（JS+CSS+HTML）
    - 扩展组件为...
        - 扩展样式（JS+CSS）
        - 仅扩展逻辑（JS）
        - 覆盖模板（JS+HTML）
        - 全部（JS+CSS+HTML）
- 显示散装组件列表
    - 安装组件
- 预览组件文档页

### Explorer 菜单扩展

- 从模板创建...
    - 同上
- 添加组件功能...
    - 同上
- 快速扩展组件...
    - 同上
- 扩展组件为...
    - 同上
- 单/多文件组件互转
- 安装与运行

## Develop

### install

``` shell
npm install
```

### watch

直接使用 Webpack 的 watch 模式，这样只需要 Reload VSCode 调试窗口。

``` shell
npm run dev
```

### package

For localization, use gulp to package.

``` shell
gulp package
```

### test

``` shell
npm run test
```
