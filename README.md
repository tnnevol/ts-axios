# TypeScript 从零到axios的封装

这个项目是基于[TypeScript library starter](https://github.com/alexjoverm/typescript-library-starter)的脚手架开发

## 目录文件介绍
_TypeScript library starter_  生成的目录结构如下：

```
├── CONTRIBUTING.md
├── LICENSE 
├── README.md
├── code-of-conduct.md
├── node_modules
├── package-lock.json
├── package.json
├── rollup.config.ts // rollup 配置文件
├── src // 源码目录
├── test // 测试目录
├── tools // 发布到 GitHup pages 以及 发布到 npm 的一些配置脚本工具
├── tsconfig.json // TypeScript 编译配置文件
└── tslint.json // TypeScript lint 文件
```

## axios分析

* 在浏览器端使用 XMLHttpRequest 对象通讯
* 支持 Promise API
* 支持请求和响应的拦截器
* 支持请求数据和响应数据的转换
* 支持请求的取消
* JSON 数据的自动转换
* 客户端防止 XSRF
