---
id: install
title: 如何开始
---

# nice-router-taro

#### 基础知识：React + Taro

Taro是京东家的小程序开发框架，基于react的语法。

目前来说个人感觉综合评分最高的第三方小程序开发框架（相比wepy和mpvue）

### 如何开始

##### 1.环境与知识准备

1. 下载安装 [Taro]([https://github.com/NervJS/taro](https://github.com/NervJS/taro) 

2. 成为开发者（找到您的小程序应用的管理员，把你的微信添加到开发者列表里就行）

3. 下载 nice-router-taro

```
git clone https://github.com/kala888/nice-router-taro
```

4. 修改小程序AppId(project.config.json)

```textile
    "appid": "wxff........07",
```

5. 修改 默认title和theme ***(可选)***

通过[https://nervjs.github.io/taro-ui-theme-preview/](https://nervjs.github.io/taro-ui-theme-preview/) 填入主色后下载文件，
 修改src/styles.theme.scss中的三个值就行了，

```scss
  $color-brand: #6dbb4d;  
  $color-brand-light: #92cc7a; 
  $color-brand-dark: #57963e;
```

修改navigationBarBackgroundColor和tabBar的颜色（app.js中）

6. 修改后端服务地址 (**可选**，默认可以连接demo服务器)

./src/utils/config.js

```
const baseURL = 'https://demo2.doublechaintech.com/storedev/wxappService/'
```

7. 编译，启动开发环境

```shell
#下载相关的依赖，可以用npm install或者yarn
yarn
#启动小程序 可以用npm run dev:weapp或者yarn dev:weapp
yarn dev:weapp
```

8. 微信开发者工具中，导入项目
   查看效果

> **小提示:**
> 1.提交代码前，先 'yarn format' 一道，有助于团队成员间代码merge.

##### 

##### 2.我需要一个后端服务，最好搭配一个中台

- 这里使用自动代码生成框架Daas Start Kit（TODO应该有一个链接），可以与nice-router-taro完美配合。

##### 3.新增简单页面

##### 4.让页面与后端进行数据交互

##### 5.来几个概念和约定

##### 6.简单使用listof组件

###### 7.实用listofpage

##### 8.图片上传

##### 9.提交一个Form

##### 10.使用后端驱动Toast消息

##### 11.使用后端驱动的Popup消息

##### 12.使用后端驱动的跳转登录

##### 13.混搭H5页面

##### 14.页面路由

##### 15.几个默认的页面

##### 16.使用generic-page页面

##### 17.NavigationService

##### 18.内置的listof lineitem

##### 19.内置的UI Element

##### ......

##### 100. Tips
