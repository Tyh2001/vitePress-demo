# Hello

## 前言

在这里编写你的内容吧

示例代码

```ts
const getType = (target: unknown): string => {
  return Object.prototype.toString.call(target)
}
```

## 官方资源

- [vitepress 文档](https://vitepress.vuejs.org)
- [仓库地址](https://github.com/vuejs/vitepress)

## 组件库使用

以 [Fighting Design](https://github.com/FightingDesign/fighting-design) 为演示

**Alert**

<f-alert type="default" title="默认提示信息"></f-alert>
<f-alert type="primary" title="主要提示信息"></f-alert>
<f-alert type="success" title="成功提示信息"></f-alert>
<f-alert type="danger" title="危险提示信息"></f-alert>
<f-alert type="warning" title="警告提示信息"></f-alert>

**Button**

<f-button type="primary">主要按钮</f-button>
<f-button type="success" ripples>涟漪效果</f-button>
<f-button type="warning" ripples>点我试试</f-button>
<f-button type="danger" ripples simple>看看我</f-button>
<f-button type="success" text ripples ripples-color="green">自定义涟漪颜色</f-button>

## 贡献者

该仓库由 [Tyh2001](https://github.com/Tyh2001) 提供。

![](https://tianyuhao.cn/images/weixin2.png)
