# 项目运行
npm install
npm run dev demo 调试demo项目
npm run dev index 调试index项目
npm run build index 发布index项目


# demo项目布局

```
.
├── build                                       // webpack配置文件
├── config                                      // 项目配置文件
│   ├── dev.env.js                              // 开发环境配置信息
│   ├── index.js                                // 基础配置信息
│   └── prod.env.js                             // 线上环境配置信息
├── node_modules                                // node依赖包
├── src                                         // 源码目录
│   ├── assets                                  // 图片资源
│   │   ├── styles                              // 公共组件
│   │   │   ├── iconfont                        // icon字体存放
│   │   │   ├── iconfont.css                    // iconfont样式
│   │   │   └── border.css                      // 公共圆角
│   │   │   └── reset.css                       // 统一样式
│   │   │   └── varibles.styl                   // 定义变量样式
│   ├── pages								 // 页面存放
│   │   ├── home                                // 首页
│   │   │   └── componets                       // 子组件存放
│   │   │   │     └── Header.vue                // 头部子组件
│   │   │   │     └── Swiper.vue                // 轮播子组件
│   │   │   └──  Home.vue                       // 首页组件
│   ├── router
│   │   └── index.js                            // 路由配置
│   ├── App.vue                                 // 根组件文件
│   ├── main.js                                 // 程序入口文件，加载各种公共组件
├── static                                      // 静态资源存放
│   ├── ***                              	    // 
├── .babelrc                                    // 语法编译转换文件
├── .editorconfig                               // 编辑器语法文件
├── .eslintignore                               // eslint排除不受规范文件
├── .eslintrc.js                                // eslint规范文件
├── .gitignore                                  // 提交排除文件
├── .postcssrc.js                               // postcss文件
├── index.html                                  // 首页模板文件
├── LICENSE                                     // 开源协议文件
├── package-lock.json                           // 包依赖锁文件
├── package.json                                // 包依赖文件
├── README.md                                   // 说明文件
.

56 directories, 203 files
```


