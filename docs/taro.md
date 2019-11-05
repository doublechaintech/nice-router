# nice-router-taro

第二适合后端程序员的前端小程序开发框架

#### 基础知识：React +DVA+Taro+TaroUI

[Taro](https://github.com/NervJS/taro)是京东家的小程序开发框架，基于react的语法。

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

5. 修改 默认title和theme  (**可选**)

通过[https://nervjs.github.io/taro-ui-theme-preview/](https://nervjs.github.io/taro-ui-theme-preview/) 填入主色后下载文件，
 修改src/styles.theme.scss中的三个值就行了，

```scss
  $color-brand: #6dbb4d;  
  $color-brand-light: #92cc7a; 
  $color-brand-dark: #57963e;
```

修改navigationBarBackgroundColor和tabBar的颜色（app.js中）

6. 修改服务端地址  (**可选**)

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
> 
> 2.文档中提到的“服务端”是指供前端开发使用**Façade**层，根据项目架构不同可能指代的是后台或者中台应用。（Façade 读音： 法萨）

##### 

##### 2.我需要一个后端服务，最好搭配一个中台

- 这里使用自动代码生成框架Daas Start Kit（TODO应该有一个链接），可以与nice-router-taro完美配合。

#### 

### 开发手册

- [x] 新增简单页面

- [x] 让页面与后端进行数据交互

- [x] 来几个概念和约定

- [x] 简单使用listof组件

- [x] 如何创建新的line-item

- [ ] 图片上传

- [x] 提交一个Form

- [ ] Step-Form

- [x] ServerImage

- [x] 使用后端驱动Toast消息

- [x] 使用后端驱动的Popup消息

- [x] 使用后端驱动的登录跳转

- [x] NavigationService

- [x] view-mapping

- [x] nice-router.model

### 几个内置页面

- [x] 混搭H5页面

- [x] 断网重试network-exception-page

- [x] 使用LoginPage

- [x] 使用Listofpage

- [x] 使用generic-page

- [ ] 内置的Genericpage UI Element

- [ ] 内置的Listof lineitem

##### ......

##### 100. Tips
