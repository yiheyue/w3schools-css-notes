# CSS Position

CSS 的 `position` 属性用于指定 HTML 元素的定位方式。

## `position`

`position` 属性的可能值有：

- `static`

- `relative`

- `fixed`

- `absolute`

- `sticky`

### `position: static;`

所有 HTML 元素的 `position` 值默认为 `static`。它们的位置都是由页面流决定的，从而无法被改变。

### `position: relative;`

如果将元素设置为 `position: relative;`，则它的位置是相对的，参考其原位置。之后可以为其设置 `top`、`right`、`bottom` 和 `left` 属性。例如：

```css
div.relative {
  position: relative;
  top: 30px;
  left: 30px;
  border: 3px solid #73ad21;
}
```

### `position: fixed;`

如果将元素设置为 `position: fixed;`，则它的位置也是相对的，参考浏览器视口的位置。之后可以为其设置 `top`、`right`、`bottom` 和 `left` 属性。例如将下列的元素固定在右下角：

```css
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 300px;
  border: 3px solid #73ad21;
}
```

### `position: absolute;`

如果将元素设置为 `position: absolute;`，则它的位置也是相对的，参考其父元素的位置。且其父元素必须设置为 `position: relative;`。例子如下：

```css
div.relative {
  position: relative;
  width: 400px;
  height: 200px;
  border: 3px solid #73ad21;
}

div.absolute {
  position: absolute;
  width: 200px;
  height: 100px;
  top: 80px;
  right: 0;
  border: 3px solid #73ad21;
}
```

### `position: sticky;`

如果将元素设置为 `position: sticky;`，则它将粘在页面上。效果类似于便利贴：

```css
div.sticky {
  position: -webkit-sticky; /* safari */
  position: sticky;
  top: 0;
  background-color: Green;
  border: 2px solid #4caf50;
}
```