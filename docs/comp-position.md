---
id: comp-position
title: Position
---

`Position` 是最基本的定位组件

## 代码演示

## Api

### 属性

| 属性 | 说明 | 类型 | 默认值 | 版本 |
| -----| ----| ---- | -----| ----|
| place | 位置 |   PositionPlace  | b | |
| mask | 遮罩层 | boolean | false | |
| visible | 是否显示 | boolean | false | |
| animate | 显示动画 | string |  | |
| contentStyle | 主体内容样式 | string, object | | |

#### PositionPlace

```js
type PositionPlace = 'l' | 'r' | 't' | 'b' | 'f' | 'c'
```

#### animate

默认对应的动画, 对应的是PositionPlace

```js
   r -> slideInRight;
   l -> slideInLeft;
   t -> slideInTop;
   b -> slideInBottom;
```

自定义动画的动画值,参考 [animate.style](https://animate.style) 这个网站

### 事件

| 属性 | 说明 | 类型 | 默认值 | 版本 |
| -----| ----| ---- | -----| ----|
| onRect | 主体内容的边界回调 | (value: {width, height, top, left}) => void    |  | |
| onClose | 关闭回调 | () => void| | |
