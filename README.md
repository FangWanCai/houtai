# demo

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

<!-- 项目笔记 -->

一.前期项目搭建
1.vue create demo
2.cd demo
3.npm run serve

二.下载 element-ui 
1.下载 element-ui
npm i element-ui -S 2.在 main.js 中引入并注册 elementui
// 引入 element-ui
import ElementUI from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';
// 将 ElementUI 挂载到 vue 实例上
Vue.use(ElementUI);

三.使用 git 对项目进行版本控制
1.git init
2.git status
3.git add .
4.git commit -m "feat(新功能):描述"
5.git remote add origin 远程仓库地址
6.git remote -v
7.git push origin master
