---
title: vueDay2
tags: vue
abbrlink: 73a0a362
date: 2021-01-16 00:00:00
categories: vue
---

一. 计算属性

#### 1.1. 计算属性的本质

- fullname:(set(), get())

#### 1.2. 计算属性和methods对比

- 计算属性在多次使用时，只会调用一次
- 它是有缓存的

### 二. 事件监听

#### 2.1. 事件监听基本使用

- btnClick
- btnClick(enent)
- btnCLick(abc, event) -> $event

#### 2.3. 修饰符

- stop
- prevent
- .enter
- .once
- .native

### 三. 条件判断

#### 3.1. v-if/v-else-if/v-else

#### 3.2. 登陆小案例

#### 3.3. v-show

- v-show 和 v-if的区别

### 四. 循环遍历

#### 4.1. 遍历数组

#### 4.2 遍历对象

- value
- value, key
- value, key, index

#### 4.3. 数组哪些方法是响应式的

#### 4.4. 作业完成

### 五. 书籍案例

### 六. v-model的使用

#### 6.1. v-model的基本使用

- v-model=>v-bind:value v-on:input

#### 6.2 v-model和radio/checkbox/select

#### 6.3. 修饰符

- lazy
- number
- trim

### 七. 组件化开发

#### 7.1. 认识组件化

#### 7.2. 组件的基本使用

#### 7.3. 全局组件和局部组件

#### 7.4. 父组件和子组件

#### 7.5. 注册的语法糖

#### 7.6. 模板的分离写法

- script
- template

#### 7.7. 数据的存放

- 子组件不能直接访问父组件
- 子组件中有自己的data ,而且必须是一个函数
- 为什么必须是一个函数

#### 7.8. 父子间组件的通信

- 父传子：props
- 子传父：$emit

#### 7.9. 项目

- npm install
- npm run serve

