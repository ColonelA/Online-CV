# 夏玉龙 - 前端工程师

::: left
男 / 2000
东北林业大学 / 艺术设计 / 专科 
工作年限 / 3年
在线简历：[https://github.com/ColonelA/Online-CV](https://github.com/ColonelA/Online-CV)
:::

::: right
icon:phone  13143686668
icon:weixin 13143686668
icon:email  xiacakl@gmail.com 
[icon:github https://github.com/ColonelA](https://github.com/ColonelA)
:::

## 介绍

于2019年开始前端开发工作，热爱编程，对代码优化写法有自己追求，喜欢接触前沿技术。希望能够通过学习成为一名软件工程师

## 工作

### 浩鲸云计算科技股份有限公司 （2020.7-2023.3）

`项目需求开发`  `基础中台维护` `用户使用体验优化` 

数据智能中台业务组-前端
- 数据智能中台系统菜单准入系统
  - 采用TypeScript+ES6/7+React开发
  - 账号 + 角色配置，可快速度拔插，查看功能系统
  - 基本多层级树形结构的黑名单/白名单控制组件 
- 数据智能中台项目基础包大小优化
  - webpack插件(webpack-plugin-inner-script)
  - 自动将外链形式改写成内敛形式。


## 项目

### 数据智能中台项目

框架选型: `React16` `antd` `Node.JS` 
解决问题API，框架选型: `jsPlumbIn` `Worker`
项目文件切片上传-实践 Github地址：[https://github.com/ColonelA/sliceUpload/tree/master](https://github.com/ColonelA/sliceUpload/tree/master) 
负责前端业务逻辑优化, 前端开发, 现场问题解决
- 采用了ES6/ES7的语法，采用axios请求统一处理
- 问题: 需要在项目中，上传大文件，但是发现等待时间长，且使用体验差，无法看到上传进度
  通过，对湖南电信现场需求的分析。
  实现，项目中对大文件切片上传功能的支撑。
  成果，解决了现场上传大文件需要等待过长的问题。
  
- 问题：需要在大屏首页，直接观察到数据表，之间的依存关系
  通过，jsPlumbIn 框架进行调研，可以通过线段链接的形式来表达A，B表之间的依赖关系
  实现， 表关系的动态关转换的可视化功能开发
  成果， 直观展示多表关系图线段，快速，准确展示了依赖逻辑关系。
  
 
 
### 数据开放项目（2020-3 - 2022.12）
  框架选型: `React16` `Antd` 
  解决问题API: `PostMessage` `VirtualList`
  虚拟列表（无限滚动）Github地址: [https://github.com/ColonelA/VirtualList](https://github.com/ColonelA/VirtualList)
项目依托中台项目部署，在使用中是通过 iframe 标签 来进行使用

负责各现场的首页开发，以及UI优化，
- 采用了独立部署，然后使用 `postMessage` 来进行上级项目对该项目内的操作
- 湖南长沙电信，云南昆明移动，内蒙古。数据开放首页开发，骨架屏开发，以及交互优化 
  通过， 讨论实际需求，指定了初次加载的UI方式
  实现， 对首页异步请求数据`loading`问题的优化。
  成果， 解决了，初次渲染高度塌陷，以及界面短暂无响应的使用缺点。
- 湖南长沙要求首页不能出现分页器，改为列表滚动的形式
  通过，所内开发使用现场提供环境自测，发现一旦界面数据突破了 `5k` 条。交互会略有卡顿，最后确认是节点渲染问题导致
  实现，长列表的动态优化渲染，以及每条数据的自适应高度。
  成果，节省浏览器性能从 每次渲染 `5K` 数据，降低为 实际渲染 = 可视化区域 `+` 上缓冲区  `+` 下缓存区 共计 `15` 条的量级
  
  

## 技能

### Web基础
- 了解ES6/ES7,Webpack
- 有Antd Design,Element UI,Muse UI搭建项目经验
-  有独立思考解决问题的能力，对于暂时无法解决的疑难问题会汇总列表，会及时沟通，提前提出问题

### 前端框架
- 熟悉使用React以及周边生态进行项目开发
- React开发过大型的应用,了解React原理与技术栈
- 使用过Vue2以及Vue2相关技术栈

### 后端相关

- 了解常用的Node模块
- 小型Node框架的搭建

