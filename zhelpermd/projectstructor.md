# helloworld(通过vue-cli脚手架初始化)的项目结构
[参考文档](https://segmentfault.com/a/1190000017828766)
├─build                 // 保存一些webpack的初始化配置,项目构建
│ ├─build.js            // 生产环境构建
│ ├─check-version.js    // 检查npm、node版本
│ ├─vue-loader.conf.js  // webpack loader配置
│ ├─webpack.base.conf.js// webpack基础配置
│ ├─webpack.dev.conf.js // 开发环境配置，构建本地开发服务器
│ ├─webpack.prod.conf.js// 生产环境的配置
│
├─config                // config文件夹保存一些项目初始化的配置
│ ├─dev.env.js          // 开发环境的配置
│ ├─index.js            // 项目一些配置变量
│ ├─prod.env.js         // 生产环境的配置
│
├─dist                  // 打包后的项目
├─node_modules          // 依赖包
│
├─src                   // 源码目录
│ ├─assets              // 静态文件目录
│ ├─components          // 组件文件
│ ├─router              // 路由
│ ├─App.vue             // 是项目入口文件
│ ├─main.js             // 是项目的核心文件，入口
├─static                // 静态资源目录 
│
├─test
├─zhelpermd
│ ├─综述.md             // 综述
│ ├─projectstructor.md  // 结构说明
│
├─.babelrc              // Babel的配置文件
├─.editorconfig         // 代码规范配置文件
├─.gitignore            // git忽略配置文件
├─.postcssrc.js         // postcss插件配置文件
├─index.html            // 页面入口文件
├─package-lock.json     // 项目包管控文件
├─package.json          // 项目配置
└─README.md             // 项目说明书

# index.js
页面入口文件
# src/App.vue
可以认为是主组件，可以通过<rounter-view />开放入口让其他组件得以显示
# src/main.js
初始化vue实例并使用需要的插件。
