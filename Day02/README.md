# 学习要点

- MVVM
- Vue的生命周期
- 模板语法

## MVVM
<https://zh.wikipedia.org/wiki/MVVM>

## Vue的生命周期
<https://cn.vuejs.org/v2/guide/instance.html>

## 模板语法

Mustache 语法（双大括号）
{{}}

指令
v-bind
v-if
v-on
v-for

修饰符 Modifiers
.

v-bind 缩写 && v-on 缩写
```html
<!-- 完整语法 -->
<a v-bind:href="url">...</a>

<!-- 缩写 -->
<a :href="url">...</a>

<!-- 完整语法 -->
<a v-on:click="doSomething">...</a>

<!-- 缩写 -->
<a @click="doSomething">...</a>
```
