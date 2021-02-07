# comment-message-editor

[A refined, customizable comment editor based on Vue](一个基于Vue的精炼的、可定制的评论编辑器)

> **作者** [konglingwen94](https://github.com/konglingwen94)
> 
> **官网** [comment-message-editor](https://github.com/konglingwen94/comment-message-editor)

## 安装

> npm install comment-message-editor

## 引入

### 注册组件
```javascript
import Vue from 'vue'
import CommentEditor from 'comment-message-editor'

Vue.component(CommentEditor.name, CommentEditor)
```

### 使用组件
```HTML
<template>
  <comment-editor></comment-editor>

</template>

```


## Attributes

|    Name    | Description  |  Type   | Default |
| :--------: | :----------: | :-----: | :-----: |
|   inline   | 是否横向显示 | Boolean |  false  |
| buttonText | 提交按钮文案 | String  |  发送   |


## Methods

| Name  | Description | Parameter |
| :---: | :---------: | :-------: |
| focus | 激活输入框  |     -     |

## Events

|  Name  |     Description      |    Parameter     |
| :----: | :------------------: | :--------------: |
| submit | 输入框内容提交后触发 | 输入框写入的内容 |


