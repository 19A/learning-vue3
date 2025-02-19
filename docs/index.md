---
outline: 'deep'
---

# 前言

Vue 3.0 从 2020 年 9 月份中旬正式发布，到 2022 年 2 月份代替 Vue 2 成为 Vue 的默认版本，经过长达一年半的市场验证，已经证明了它可以完美地支持常见的企业需求，适合投产使用，未来会被越来越多的企业所采用，只掌握 Vue 2 将远远不能满足企业的技能要求。

本书以 Vue.js 的 3.0 版本为核心技术栈，围绕 “前端工程化” 和 TypeScript 的知识点展开讲解，读者可以收获到：

1. 了解如何入门前端工程化开发，掌握 Node.js 和 npm 的使用
2. 掌握前端领域多年来趋势走高、带有类型支持的 TypeScript 语言
3. 上手主流前端框架 Vue.js 的全新版本，并且在遇到常见问题时知道如何解决

本书的每一个小节都融入了笔者多年的开发实践经验，大部分知识点都搭配了通俗易懂的讲解和可实现的代码案例，在阅读的过程中可以亲自敲代码加强学习印象，毕竟上手一个新技术栈最快的方法，就是一边 Reading 一边 Coding 。

## 适合人群

本书作为一本入门类教程，主要面向以下读者人群：

1. 掌握了基础的 HTML 页面编写知识，想学习一个主流前端框架的新手前端工程师
2. 已经学会了 Vue 2 ，面对 Vue 3 的大版本更新，想快速上手使用的前端工程师
3. 非职业前端开发，但涉及前端的工作，需要掌握一个主流前端框架的全栈工程师

## 内容说明

本书根据笔者多年的前端开发经验和一线团队管理经验，将 Vue 3 的知识点按照工程师做项目的顺序梳理成章，一步一步帮助工程师入门前端工程化和 Vue 3 的开发。

书中包含了很多在构建项目过程中容易遇到的问题点和解决方案，对 Vue 3 和 Vue 2 差异化较大的功能点还进行了版本之间的写法对比。

这一点和各个技术栈的官方文档有比较大的不同，官方文档更适合作为一本工具书，方便在需要的时候对 API 进行检索查询。

目前笔者所带领的前端团队已经全员使用 TypeScript 和 Vue 3 进行日常的开发工作，团队成员的学习过程都非常顺利，各位开发者可放心阅读。

:::tip
对于从 Vue 2 升级到 Vue 3 之后变化很大的内容，文档的侧边栏添加了<i class="sidebar__icon--default sidebar__icon--new"></i>图标，如果对 Vue 2 版本已经很熟悉，可以针对带有<i class="sidebar__icon--default sidebar__icon--new"></i>图标的地方单独查阅。

注：当<i class="sidebar__icon--default sidebar__icon--new"></i>出现在二级标题时，说明这一节都是新的，如果只出现在三级标题，说明只有那一小部分变化比较大。
:::

## 学习顺序

推荐按照本书章节的顺序学习，从前端工程化开始上手，到 TypeScript 语言的学习，再到使用 TypeScript 开发 Vue 3 项目，这是一个循序渐进的学习过程。

Vue.js 是一个 “渐进式” 的框架，它可以只用最基础的组件来开发一个小项目，也可以把相关生态引入进来组合成一个大项目（例如 Vue Router 、 Vuex 、 Pinia 等等），本书和 Vue.js 框架一样，也是一个 “渐进式” 的教程，对于本身已经有一定基础的开发者，也可以在遇到具体问题的时候，只阅读对应的部分内容。

在学习的过程中，推荐将已有的其他技术栈项目，使用 Vue 3 重写，使其可以复刻原来的功能，比如一个使用 jQuery 或者是 Vue 2 编写的活动页面或小工具，用 Vue 3 重新实现一遍，看看能否还原出原来的功能，如果能够成功实现，那么说明已经能够掌握 Vue 3 的使用了。

## 疑惑解答

在学习的过程中如果遇到什么问题无法解决，可以通过以下途径反馈：

1. 在仓库里提 [Issue](https://github.com/chengpeiquan/learning-vue3/issues) 或者 [Discussions](https://github.com/chengpeiquan/learning-vue3/discussions) 
2. 发送邮件到笔者的邮箱 chengpeiquan@chengpeiquan.com

如果阅读本书的内容觉得有帮助，[欢迎到仓库给个 Star 鼓励](https://github.com/chengpeiquan/learning-vue3) 。

## 赏个罐头

如果觉得本书的内容有帮助，欢迎捐赠一个猫罐头给作者家的三只猫猫，感恩！

<ClientOnly>
  <ImgWrap
    src="/assets/img/donate.jpg"
    dark="/assets/img/donate-dark.jpg"
    alt="请打开微信扫描二维码"
  />
</ClientOnly>

作者养了一只黑色英短、一只红虎斑缅因和一只棕虎斑美短，欢迎在线吸猫：

<ClientOnly>
  <ImgWrap
    src="/assets/img/cats.jpg"
    alt="从左到右：黑妹、小朋友、弟弟"
  />
</ClientOnly>

## 版权许可

MIT License © 2020 [chengpeiquan](https://github.com/chengpeiquan)
