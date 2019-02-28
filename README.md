# vue-ecology
**本项目模仿vue-element-admin**
- [vue-element-admin地址](http://panjiachen.github.io/vue-element-admin)
**原页面：**
 <p align="center">
  <img width="900" src="https://wpimg.wallstcn.com/a5894c1b-f6af-456e-82df-1151da0839bf.png">
</p>

# vue-ecology安装和初始化项目
```bash
## Project setup
yarn install

### Compiles and hot-reloads for development
yarn run serve

### Compiles and minifies for production
yarn run build

### Run your tests
yarn run test

### Lints and fixes files
yarn run lint
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 说明（项目涉及的资源学习链接,自己学习时候的参考）

- [国际化：i18n实现多语言](https://www.jianshu.com/p/b10b971a887e)

- [Vue.filter()方法的使用](https://blog.csdn.net/csl125/article/details/80563046)

- [js-cookie的用法](https://www.cnblogs.com/xuyan1/p/8421284.html)

- [require.context()动态批量引入文件](https://webpack.docschina.org/guides/dependency-management/#require-context)(https://www.cnblogs.com/ympjsc/p/10049943.html)

- [vue-cli3中路径别名如何配置](https://segmentfault.com/a/1190000016135314)

- []

*********************

## 知识点总结
1. Vue.nextTick()
```js
// 修改数据
vm.msg = 'Hello'
// DOM 还没有更新
Vue.nextTick(function () {
  // DOM 更新了
})
```

2. Vue.config.errorHandler
```js
Vue.config.errorHandler = function (err, vm, info) {
  // handle error
  // `info` 是 Vue 特定的错误信息，比如错误所在的生命周期钩子
  // 只在 2.2.0+ 可用
}
```