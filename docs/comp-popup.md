---
id: comp-popup
title:  Popup
---

`Popup` 屏幕上下左右的弹出组件

## 代码演示

## Api

### 属性

| 属性 | 说明 | 类型 | 默认值 | 版本 |
|-----| ----| ---- | -----| ----|
| place | 位置 | 'r', 'l', 't', 'b' | b | |
| offset | 偏移量 | number | 80 | |
| title | 标题 | string | | |
| showClose| 关闭按钮 | boolean | false | |
| size | 大小 | number, string | | |
| hand | 是否显示拖动按钮(目前只针对 b ) | boolean | false | |
| mask | 遮罩层 | boolean | false | |
| visible | 是否显示 | boolean | false | |

### 事件

| 属性 | 说明 | 类型 | 默认值 | 版本 |
| -----| ----| ---- | -----| ----|
| onClose | 关闭回调 | () => void| | |
