```yaml
changelog: true
```

## 2.22.1

`2022-04-02`

### 🐛 问题修复

- 修复虚拟列表和滚动一起使用的问题 ([#926](https://github.com/arco-design/arco-design-vue/pull/926))


## 2.22.0

`2022-04-01`

### 🆕 新增功能

- 增加 `selectAll` 方法 ([#920](https://github.com/arco-design/arco-design-vue/pull/920))

### 🐛 问题修复

- 修复某些情况下虚拟列表宽度错误的问题 ([#920](https://github.com/arco-design/arco-design-vue/pull/920))


## 2.21.0

`2022-03-25`

### 🆕 新增功能

- 增加总结行功能 ([#877](https://github.com/arco-design/arco-design-vue/pull/877))


## 2.20.2

`2022-03-24`

### 🐛 问题修复

- 修复 `table-column` 组件在模板中直接书写对象参数时导致不断更新的问题 ([#861](https://github.com/arco-design/arco-design-vue/pull/861))
- 修复仅有一个 `table-column` 时没有列数据的问题 ([#861](https://github.com/arco-design/arco-design-vue/pull/861))
- 修复 `table-column` 的排序问题，可通过 `index` 参数解决 ([#861](https://github.com/arco-design/arco-design-vue/pull/861))


## 2.20.0

`2022-03-18`

### 🆕 新增功能

- 使用 Context 方式重构组件，`table-colum` 支持二次封装 ([#845](https://github.com/arco-design/arco-design-vue/pull/845))
- scroll 属性增加 `maxHeight`, `minWidth` 属性 ([#845](https://github.com/arco-design/arco-design-vue/pull/845))

### 💅 样式更新

- 修复开启排序后，表头文字不能居中的问题 ([#845](https://github.com/arco-design/arco-design-vue/pull/845))

## 2.19.0

`2022-03-11`

### ⚠️ 重点注意

- 修改排序函数 sorter 的传出数据，增强使用 ([#810](https://github.com/arco-design/arco-design-vue/pull/810))


## 2.18.0

`2022-03-04`

### 🆕 新增功能

- 滚动模式支持设置高度百分比 ([#780](https://github.com/arco-design/arco-design-vue/pull/780))
- column 数据增加 slotName 属性，允许指定渲染插槽 ([#780](https://github.com/arco-design/arco-design-vue/pull/780))
- 增加 `pagination-left` 和 `pagination-right` 插槽 ([#780](https://github.com/arco-design/arco-design-vue/pull/780))


## 2.18.0-beta.2

`2022-02-25`

### 🆕 新增功能

- 增加 `span-all`  属性 ([#735](https://github.com/arco-design/arco-design-vue/pull/735))

### 🐛 问题修复

- 修复 table-column 嵌套使用时，v-for 不能渲染的问题 ([#734](https://github.com/arco-design/arco-design-vue/pull/734))


## 2.18.0-beta.1

`2022-02-18`

### 💎 功能优化

- 在数据为空时，不展示分页组件 ([#684](https://github.com/arco-design/arco-design-vue/pull/684))


## 2.16.2

`2022-01-24`

### 🐛 问题修复

- 修复阻止冒泡导致懒加载失效的问题 ([#641](https://github.com/arco-design/arco-design-vue/pull/641))
- **table:** 修复在展开行展开时，删除后显示空行的问题


## 2.16.0

`2022-01-21`

### 💎 功能优化

- 内部按钮不再触发 `row-click` 事件 ([#630](https://github.com/arco-design/arco-design-vue/pull/630))

### 🆕 新增功能

- 增加拖拽排序的支持（实验性） ([#619](https://github.com/arco-design/arco-design-vue/pull/619))
- 增加调整列宽的支持（实验性） ([#619](https://github.com/arco-design/arco-design-vue/pull/619))
- 增加 `tbody`、`tr`、`td` 插槽 ([#619](https://github.com/arco-design/arco-design-vue/pull/619))


## 2.15.0

`2022-01-14`

### 🆕 新增功能

- `sortable.sorter` 增加 boolean 类型，支持服务器端排序 ([#575](https://github.com/arco-design/arco-design-vue/pull/575))


## 2.14.2

`2022-01-10`

### 🐛 问题修复

- 修复 table 内容超出容器，导致某些情况下边框不显示的问题 ([#536](https://github.com/arco-design/arco-design-vue/pull/536))


## 2.14.0

`2022-01-07`

### 🆕 新增功能

- 增加 hideExpandButtonOnEmpty 属性 ([#520](https://github.com/arco-design/arco-design-vue/pull/520))

### 🐛 问题修复

- 修复 x 轴 resize 问题 ([#519](https://github.com/arco-design/arco-design-vue/pull/519))
- 修复存在固定列时，展开行宽度设置错误的问题 ([#519](https://github.com/arco-design/arco-design-vue/pull/519))
- 修复存在子树时，复选框全选设置错误的问题 ([#519](https://github.com/arco-design/arco-design-vue/pull/519))


## 2.13.0

`2021-12-31`

### 🆕 新增功能

- 增加 `loadMore` 属性，支持子树懒加载 ([#485](https://github.com/arco-design/arco-design-vue/pull/485))
- 增加 `filterIconAlignLeft` 属性 ([#485](https://github.com/arco-design/arco-design-vue/pull/485))
- 增加 `change` 事件，可获取处理后数据 ([#485](https://github.com/arco-design/arco-design-vue/pull/485))

### 🐛 问题修复

- 修复 `sortOrder ` 置空失效的问题 ([#478](https://github.com/arco-design/arco-design-vue/pull/478))
- 修复 `expand-icon` 插槽在子树中不生效的问题 ([#478](https://github.com/arco-design/arco-design-vue/pull/478))
- 修复固定列在表格尺寸动态变化时阴影不显示的问题 ([#478](https://github.com/arco-design/arco-design-vue/pull/478))


## 2.12.0

`2021-12-24`

### 💅 样式更新

- 修复 table 滚动模式下最后一行多余边框的问题 ([#456](https://github.com/arco-design/arco-design-vue/pull/456))


## 2.11.0

`2021-12-17`

### 🆕 新增功能

- `columns` 新增 cellStyle 属性 ([#411](https://github.com/arco-design/arco-design-vue/pull/411))

### 🐛 问题修复

- 修复固定列模式下，表格尺寸变化导致表头和主体宽度不一致问题 ([#410](https://github.com/arco-design/arco-design-vue/pull/410))


## 2.10.0

`2021-12-10`

### 🆕 新增功能

- 增加 span-method 属性 ([#360](https://github.com/arco-design/arco-design-vue/pull/360))


## 2.9.0

`2021-12-03`

### 🐛 问题修复

- 修复树形展开按钮触发表单提交的问题 ([#321](https://github.com/arco-design/arco-design-vue/pull/321))


## 2.7.0

`2021-11-26`

### 🆕 新增功能

- 增加 `footer` 插槽 ([#266](https://github.com/arco-design/arco-design-vue/pull/266))
- 常规模式下表格宽度大于容器时会开启滚动条 ([#266](https://github.com/arco-design/arco-design-vue/pull/266))


## 2.6.1

`2021-11-24`

### 💎 功能优化

- 数据为空时不展示滚动 ([#245](https://github.com/arco-design/arco-design-vue/pull/245))

### 🐛 问题修复

- 修复展开行按钮触发表单提交的问题 ([#210](https://github.com/arco-design/arco-design-vue/pull/210))


## 2.3.0

`2021-11-12`

### 🐛 问题修复

- 修复 `<table-column>` 在分组表头错误的问题 ([#151](https://github.com/arco-design/arco-design-vue/pull/151))


## 2.2.0

`2021-11-10`

### 🆕 新增功能

- 增加 `row-key` 属性 ([#128](https://github.com/arco-design/arco-design-vue/pull/128))
- 增加 `expandable` 中的 `expandedRowRender ` 和 `icon` 属性 ([#128](https://github.com/arco-design/arco-design-vue/pull/128))
- 增加 `expand-icon` 和 `expand-row` 插槽 ([#128](https://github.com/arco-design/arco-design-vue/pull/128))

### 🐛 问题修复

- 修复表头分组中表格操作项占位错误的问题 ([#127](https://github.com/arco-design/arco-design-vue/pull/127))


## 2.1.0

`2021-11-05`

### 🆕 新增功能

- 添加 `table-column` 中的 `#title` 插槽 ([#95](https://github.com/arco-design/arco-design-vue/pull/95))

### 🐛 问题修复

- 修复 `#column` 插槽不能支持Fragment的问题 ([#83](https://github.com/arco-design/arco-design-vue/pull/83))
- 修复 `scroll.x` 单独使用不生效的问题 ([#83](https://github.com/arco-design/arco-design-vue/pull/83))


## 2.0.3

`2021-10-29`

### 🐛 问题修复

- 修复 `scroll` 模式下，滚动条的显隐导致单元格错位 ([#29](https://github.com/arco-design/arco-design-vue/pull/29))

