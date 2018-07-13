# Vue.js 学习示例及笔记

## 快速示例

- [hello vue](example/1.html)
- [hover title tips:v-bind](example/2.html)
- [seen:v-if](example/3.html)
- [todos:v-for](example/4.html)
- [reverse message:v-on](example/5.html)
- [two-way binding:v-model](example/6.html)
- [component](example/7.html)
- [object freeze](example/8.html)

## 一个简单的 TODO APP

[todo app](example/todo-app.html)

## 组件

- [全局组件:Global Registration](example/c1.html)
- [局部组件:Local Registration](example/c2.html)

## 使用 `vue-cli` 脚手架生成示例项目

安装 `vue-cli` 之后，可以使用快捷命令生成 `vue` 示例项目。

```bash
# 请根据项目需求选择 `webpack` 或 `webpack-simple` 命令来创建示例项目或初始化新项目
vue init webpack my-project
vue init webpack-simple my-project
```

上面命令会生成基于 `webpack` 配置的项目，其中带 `simple` 的命令提供更简单配置和更少的依赖（后续 `browserify-simple` 命令亦是如此）。当然，您也可以生成基于 `browserify` 配置的项目，使用下面命令即可。

```bash
# 请根据项目需求选择 `browserify` 或 `browserify-simple` 命令来创建示例项目或初始化新项目
vue init browserify my-project
vue init browserify-simple my-project
```

更多请参考 [vuejs-templates](https://github.com/vuejs-templates) 组织相关代码库。

本仓库使用 `vue init webpack-simple simple-vue2-webpack-project` 命令生成了一个示例项目。

## 组件 `prop`

- [prop 基础示例](example/cp_1.html)
- `prop` 单向数据流： 所有的 `prop` 都使得其父子 `prop` 之间形成了一个单向下行绑定：父级 `prop` 的更新会向下流动到子组件中，但是反过来则不行。这样会防止从子组件意外改变父级组件的状态，从而导致你的应用的数据流向难以理解。
- [prop 使用事件实现双向绑定](example/cp_2.html)
- [prop sync 使用示例](example/cp_3.html) （来源：[Vue’s new and improved prop.sync](https://medium.com/front-end-hacking/vues-v-model-directive-vs-sync-modifier-d1f83957c57c) )




