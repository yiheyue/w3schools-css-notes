# CSS Pseudo-classes

CSS 伪类用于定义 HTML 元素的一种特殊状态。例如，当元素被聚焦时。

## 语法

CSS 伪类的语法：
```
selector:pseudo-class {
  property: value;
}
```

## 常用的 CSS 伪类

### `<a>` 元素

- `:active`

- `:hover`

- `:link`

### `<input>` 元素

- `:checked`

- `:disabled`

- `:enabled`

- `:focus`

示例：
```css
a:hover {
  color: red;
  background-color: SlateBlue;
}
```