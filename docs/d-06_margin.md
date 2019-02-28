# CSS 外外边距

使用 CSS 的 `margin` 属性，我们可以为 HTML 元素外增加一些空间，使得元素与元素之间可以拉开一定的距离。

## 单独设置 `margin` 属性

CSS 为我们提供了 4 个属性用于单独设置各个方向的外边距：

- `margin-top`

- `margin-right`

- `margin-bottom`

- `margin-left`

示例：
```css
p {
  margin-top: 100px;
  margin-right: 100px;
  margin-bottom: 40px;
  margin-left: 25px;
}
```

## `margin` 缩写

我们也可以一次性设置 `margin` 属性各个方向的值。4 个值表示方向依次是 上、右、下和左。

示例：
```css
p {
  margin: 5px 6px 7px 8px;
}
```

## `auto`

我们可以通过将 `margin` 属性的值设置为 `auto` 使得被设置的元素在其父容器中水平居中。

示例：
```css
div {
  width: 300px;
  margin: auto;
}
```

## 外边距塌陷

当两个 HTML 元素上下排列时，他们中间夹着的边距的大小取决于他们之间外边距较大的一方的值。

例如，下方的 `div1` 和 `div2` 夹着的边距大小为 `50px`：
```
     10px

4px  div1  6px

     20px

--------------

     50px

4px  div2  6px

     10px
```