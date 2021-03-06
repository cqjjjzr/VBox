---
pageIndex: 1
title: VBox 文档
---

::: tip

请注意：这是有关 VBox 本身的文档。如果您在寻找其他产品的文档，请返回[首页](/)。

:::

确实会有这样的情况——在经过了漫长的浏览文档的时间之后，你可能突然对这个统一文档网站——VBox 产生了兴趣。是的，作为一个人人可以参与贡献的在线文档平台，VBox 也是我们众多产品其中的一项。在这里，你可以了解到更多关于 VBox 的信息。

## 在 VBox 背后……

### VBox 由 VuePress 驱动

VBox 使用 [VuePress](https://vuepress.vuejs.org/zh/) 作为文档框架。VuePress 提供了一个及其精简而又及其快速的静态网站生成器用来在快速生成静态页面的同时保持对 Vue 组件和功能的良好支持，这使得我们在书写文档的时候可以随意使用自定义的 Vue 组件来使我们的文档变得更加丰富；它还提供了许多基于 Markdown 的扩展功能，使得在不增加文档编写难度的同时维护者可以灵活使用这些功能来让文档的结构和逻辑更加清晰。

### VBox 使用了许多 VuePress 插件

VBox 添加了许多 VuePress 插件，使得您可以更加轻松地浏览文档，如「放大图片」插件和「返回顶部」插件等等。

### VBox 由「VBox 主题」扩展

VBox 中含有许多 VuePress 提供的默认主题中所没有的功能，如自动生成文档目录和就地编辑等。这些功能和 VBox 关联较为紧密，因此我们并没有使用插件的方式加载它们，而是使用了由 VuePress 的默认主题派生而来的[「VBox 主题」（vuepress-theme-vbox）](https://github.com/vbox-moe/vuepress-theme-vbox)。许多 VBox 的核心功能都在这个主题内提供。有关 VBox 主题的更多详细信息请转到[这里](./Theme)。

## 我想参与贡献！

这非常好，我们非常欢迎您能够参与到 VBox 托管的众多文档的编辑、修改和维护当中。请查看[这里](./Contribute)了解更多信息。
