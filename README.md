# nice-router
多端统一开发方式

满足前端页面驱动和后端路由驱动的需求

给予后端开发页面控制权（方便实现客CS程序的千人千面，业务变更）

Taro: https://github.com/kala888/nice-router-taro

RN: https://github.com/kala888/nice-router-react-native


nice-router

#### 目标功能

- [x] 全局的NavigationService: 基础配置完成以后，随地享用
- [x] 无脑执行Action，支持不同的schema: 后端控制的页面跳转，H5 Webview, 静态前端页面跳转 
- [x] 前台路由驱动开发方式，例如点击button先跳转页面，再在didmount的时候，发送请求获取数据
- [x] 后端路由，可渐进式缓存为前端路由，例如后端请求和前端路由同时发起
- [x] 传递统一参数，语义化请求类型，支持 ajax, get, post, post form, navigate
- [ ] 并行请求，归并结果save2Store。扩展属性 + transformer
- [ ] 轻松的注册基础版的dva model
- [x] 基础版model可被代码复写（客户化定制）
- [x] 标准分页处理
- [x] 服务端控制消息（Toast处理）
- [x] 服务端控制popup(带action)
- [x] 请求结果缓存, hash校验更新(需要后端支持)
- [x] API认证接口，兼容登录，退出的场景（处理token和session问题）
- [ ] 静态的global配置 + 远程的global配置
- [ ] 异常日志上报
- [ ] 多请求可被中断
- [ ] 支持RX
- [ ] 生命周期接口（ETL），分为公共和私有，onStart, onSuccess, onFail, onComplete,
- [ ] 统一的异常处理，断网以及服务端异常
- [ ] 路由请求重放（断网重放）, 部分路由支持失败自动重连
- [x] ServiceImage， 依赖于AliyunOSS的一个图片组件
- [x] Listof 支持
 
 ###  2. generic page

一个数据驱动的页面体系，目标请轻松的由运营人员动态构建页面。

#### 目标功能


- [x] Text
- [x] Button
- [x] Image
- [ ] RichText
- [x] Carousel
- [x] FooterTab

- [ ] generic form
- [ ] popup
- [ ] listof
- [x] Flex
- [ ] 自由面板
- [ ] H5

base biz elements
- [x] listof
- [x] StoreLocation
- [x] BoxBar

biz page
- [ ] 集赞


