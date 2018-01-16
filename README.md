# multi-pages-demo

> 基于 `vue-cli` 的多页demo
> `src`文件夹目录结构如下

```shell
├─src
  ├─assets # 组件依赖静态资源
  ├─components # 公用组件
  ├─modules   # 公用模块
  │  └─test
  └─pages     # 页面文件夹
      ├─404   # 404页
      ├─index # 首页
      └─test  # 测试页
```

**`pages` 文件夹下 每个文件夹对应每个页面，文件夹名称即为页面名称，内部html、js均需统一名称**

前端路由：`webpack.dev.conf.js` 的 `historyApiFallback` 中配置 ([更多配置点击](https://github.com/bripkens/connect-history-api-fallback))，或者直接访问 `localhost:8080/index.html`(对应pages文件夹下每个文件夹对应一个 `HTML` 页面)

> 其他配置 可查看 webpack 配置，并定制

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
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
