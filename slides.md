---
layout: image
image: 0.jpeg
class: myHome
---

# 演示文稿

## 应聘者：吴伟
## 应聘岗位：前端开发

<style>
.myHome {
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
   color: #000 !important;
}
</style>

---
layout: image-left
image: 1.jpeg
---
# 个人资料

#### 姓名： 吴伟
#### 性别： 男
#### 院校： 湘潭大学
#### 学历： 本科
#### 专业： 计算机软件工程
#### 籍贯： 湖南益阳
#### 职业： 前端开发

---
layout: two-cols
class: twoPage
---


## 华为三朵云体验平台
类似商城平台，管理项目部上线的所有case的平台

<img src="/2.png" width="300" />

::right::

## 技术要求
- 基于vue脚手架，开发vue2项目

- 使用原生css构建符合ui需求的组件，不使用第三方库

- 国际化

- 支持路由快照

- 适配平台要求的几种主流分辨率

-  手动部署前端项目

- 带团队新人上手项目


<style>
.myFlexCenter {
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
}
</style>


---

## 亮点

- 除正常的case开发任务外需要维护一个基线项目

> 虽然平台不允许使用第三方UI库，需要根据每个case的UI设计进行定制组件，但是基本功能和规范是一致的，因此我们整合一些基本组件维护一套基线case，这样不用每次有开发需求的时候都需要重新创建项目及复制已有case实现的功能。如按钮组件，翻页组件。

<br/>

- 多项目单项目库管理
> 随着case数量的增加，创建多个codehub库显得繁琐且不利于本地代码库管理,且借鉴monorepe形式配合pnpm可以减少本地依赖包过多占用磁盘空间。

<br/>

- 资源托管问题解决
> 为了减少项目体积，平台上线了一个资源托管平台，每个资源的id是唯一的但是资源由于可修改链接是不唯一的，因此在项目style中使用url()存在问题，解决方案是使用全局变量,在进入系统时使用id作为变量名称，资源链接作为值。


---
layout: two-cols
class: twoPage
---


## 华为产品生命周期管理系统
正常的后台管理系统


<img src="/3.jpg" width="400" />

::right::

## 技术要求

- vue2 + element-ui + vuex + axios

- 根据需求串讲和设计文档进行系统增量开发

- 自动化部署

- 清除codecheck问题使其符合平台eslint规范

- 页面埋点，分析页面性能

---
layout: two-cols
---

## 仿博客系统

- 仿vuepress

- 解析markdown文件

- 自定义解析样式文件

- 高亮代码块


::right::
## 仿后台管理系统

- vite + vue3 + pinia + qiankun

- 尝试vue3 steup写法

- 使用qiankun微服务集成vue和react项目


---
layout: image-right
image: 4.png
---

## 个人优势

- 为人诚恳，人际关系良好

- 对技术保持热情，会积极拓展自己的技术，关注前端技术的发展

- 不限制工作所需，重实践，react、小程序、uniapp、node等都会学习和关注

- 比较专业，对技术不限制前端方向，数据库、后台等都有一定的基础

- 工作时间相对长，可以快速上手新项目

- 比较熟悉管理系统类型的开发，可以从0开始搭建，能独立承担任务

- 对应聘岗位的技能要求符合

---
class: myEnd
---

# 感谢观看

<style>
.myEnd {
  background: #2b2b2b;
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
   color: #fff !important;
}
  </style>






