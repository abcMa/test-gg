# fe_pmp_v3

> 基于vue2.x+elementUI的智能园区软件管理系统

## 安装步骤

``` bash
git clone 'http://192.168.0.50:28080/git/r/fe_pmp_v3.git'
```

## 项目启动

``` bash
npm install
npm run dev
```
## 相关目录及文件说明

``` bash
	|-- build                            // webpack配置文件
	|-- config                           // 项目打包路径
	|-- src                              // 源码目录
	|   |-- assets                       // 资源文件
	|       |-- images                   // 图片文件
	|       |-- scss                     // sass文件 
	|          |-- variables.scss        // 样式变量定义表
	|          |-- base.scss             // 基础样式
	|   |-- components                   // 组件
	|       |-- XXX.vue                  // 共用页面
	|   |-- pages                        // 主要页面
  |       |--common                    // 公共页
  |           |-- 404                  // 404页面
  |           |-- empty                // 空警告
	|       |-- login                    // 登录页
	|   |-- router                       // 路由
	|       |-- index.js                 // 路由设置文件
	|   |-- utils                        // 工具类
	|       |-- api.js                   // 接口调用
	|       |-- tools.js                 // 工具类
	|   |-- App.vue                      // 页面入口文件
	|   |-- main.js                      // 程序入口文件，加载各种公共组件
	|-- .babelrc                         // ES6语法编译配置
	|-- .editorconfig                    // 代码编写规格
	|-- .gitignore                       // 忽略的文件
	|-- index.html                       // 入口html文件
	|-- element-varibles.scss            // element主题样式文件
	|-- CHANGELOG.md                    // 项目变更日志（随着版本发布进行维护）
	|-- package.json                     // 项目及工具的依赖配置文件
	|-- README.md                        // 说明
	
```
## 项目依赖插件概览

### elementUI
基于vueJS的一款UI组件库。访问地址：[Element](http://element-cn.eleme.io/#/zh-CN/component/installation)

### 阿里图标库 
可以自定义icon，且提供丰富的图标库。访问地址:[阿里图标](https://www.iconfont.cn/manage/index?manage_type=myprojects&projectId=1006905
) 

### sass 
世界上最成熟、最稳定、最强大的css扩展语言，有定义变量、嵌套等特性。访问地址：[sass](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)

### axios
基于 promise 的 HTTP 库，可以用在浏览器和 node.js 中。
[github地址](https://github.com/axios/axioss)


## 项目打包
``` bash
npm run build
```






