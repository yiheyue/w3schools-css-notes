# CSS 内填充

使用 CSS 的 `padding` 属性，我们可以在 HTML 元素内增加一些空间。

## 单独设置 `padding` 属性

CSS 为我们提供了 4 个属性用于单独设置各个方向的内填充：

- `padding-top`

- `padding-right`

- `padding-bottom`

- `padding-left`

示例：
```css
p {
  padding-top: 100px;
  padding-right: 20px;
  padding-bottom: 120px;
  padding-left: 30px;
}
```

## `padding` 缩写

我们也可以一次性设置 `margin` 属性各个方向的值。4 个值表示方向依次是 上、右、下和左。

示例：
```css
p {
  padding: 20px 30px 40px 50px;
}
```