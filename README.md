## What is carbon-element?
An easy to use [IBM Carbon](https://carbondesignsystem.com/components/button/usage/) Style UI component library, with the same components of famous [Element](https://element.eleme.cn/#/en-US/component/button) for VueJS projects

## Who need this?
- If you love (or had to) use [IBM Carbon Design System](https://carbondesignsystem.com/)
- If [@carbon/vue](https://github.com/carbon-design-system/carbon-components-vue) ![Github stars](https://img.shields.io/github/stars/carbon-design-system/carbon-components-vue.svg) is not enough (or easy) for you
- If you like the components of [Element](https://github.com/ElemeFE/element) ![Github stars](https://img.shields.io/github/stars/ElemeFE/element.svg)

## How to use?
- Install
```
npm install element-ui @carbon/themes carbon-element
```
or
```
yarn add element-ui @carbon/themes carbon-element
```
- Import into `src/main.js`

```js
import ElementUI from 'element-ui'
import 'element-ui/lib/theme-chalk/index.css'
import 'carbon-element/lib/index.scss'

Vue.use(ElementUI)
```

- Use `Element` components and preview with `IBM Carbon` styles
```js
// In your components
<el-button type="primary">Carbon style Button</el-button>
```