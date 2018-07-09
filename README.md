# vue-cli-xb

> vue基本cli

## author

> xb

## remark

> 仅供个人脚手架使用

## 项目目录
```
.
├── build -- 项目构建相关代码
│   ├── build.js -- 生产环境构建代码
│   ├── check-version.js -- 检查 node、npm 等版本
│   ├── utils.js
│   ├── vue-loader.conf.js
│   ├── webpack.base.conf.js
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
│
├── config
├── src
├── static
├── test
├── .babelrc
├── .editorconfig
├── .eslintignore
├── .eslintrc.js
├── .gitignore
├── .postcssrc.js
├── index.html
├── package.json
└── README.md -- 配置文件


```

## 依赖包

```
├── dependencies -- 生产环境依赖项
│   │
│   ├── axios -- http请求工具
│   ├── extend -- node深度拷贝工具库
│   ├── font-awesome -- font图标库
│   ├── lodash -- 数据类型处理工具库
│   └── mockjs -- mock模拟数据
│
│
└── devDependencies -- 开发环境依赖项
    │
    ├── node-sass -- 打包sass依赖包
    └── sass-loader

```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

