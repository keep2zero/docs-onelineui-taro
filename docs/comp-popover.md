---
id: comp-popover
title: Popover
---

`Popover` 一个提示组件

## 代码演示

## Api

### 属性

| 属性 | 说明 | 类型 | 默认值 | 版本 |
|-----| ----| ---- | -----| ----|
| place | 位置 | PopoverPlace |  b | |
| rect | 触发组件的边界数据 | PopoverRect | | |

#### PopoverPlace

```js
 type PopoverPlace = 'r' | 'rt' | 'rb' | 'l' | 'lt' | 'lb' | 't' | 'tl' | 'tr' | 'b' | 'bl' | 'br';
```

#### PopoverRect

```js
 interface PopoverRect { left: number, top: number, width: number, height: number }
```

### 事件

| 属性 | 说明 | 类型 | 默认值 | 版本 |
| -----| ----| ---- | -----| ----|
| onClose | 关闭回调 | () => void| | |
