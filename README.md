# Vue3 Start
> 本项目演示多种方式创建Vue3项目，并对比差异性

## 创建方式

### create-vue
已安装 16.0 或更高版本的 Node.js
**默认是 构建默认是vite，且只有vite**
```shell
npm create vue@latest
```

参考:
- [创建你的第一个 Vue3 项目——Vue 教程](https://juejin.cn/post/7222092486667845693)
- [cn.vuejs.org](https://cn.vuejs.org/guide/quick-start.html#creating-a-vue-application)

### Vue CLI
https://cli.vuejs.org/zh/guide/
⚠️ Vue CLI 现已处于维护模式!
现在官方推荐使用 create-vue 来创建基于 Vite 的新项目。 另外请参考 Vue 3 工具链指南 以了解最新的工具推荐。

```shell

npm install -g @vue/cli

vue --version
# @vue/cli 5.0.8

vue create hello-world
```

参考:
- [cli.vuejs.org](https://cli.vuejs.org/zh/guide/installation.html)


### Vite
```shell
vite --version

npm create vite@latest
```

参考:
- [cn.vitejs.dev](https://cn.vitejs.dev/guide/)
- [Svelte小试——Svelte+Vite+TypeScript实现ToDoList](https://juejin.cn/post/7204635326559322170)



# TODO
- Vite目前支持的模板预设
- webpack 对比 vite
    - [vite和webpack的区别](https://worktile.com/kb/p/52284)
    - [vite多久后能干掉webpack？](https://www.zhihu.com/question/477139054?utm_division=hot_list_page)

