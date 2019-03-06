# CSS Align

CSS 的水平 & 垂直方向对齐

## 水平居中块级元素

要使得块级元素居中，我们可以使用 `margin: auto;`。

示例：
```css
.center {
  margin: auto;
  width: 50%;
  border: 3px solid DodgerBlue;
  padding: 10px;
}
```

## 水平居中文字

如果要让 HTML 元素中文字居中，我们可以使用 `text-align: center;`。

示例：
```css
.center {
  text-align: center;
  border: 3px solid MediumSeaGreen;
}
```

## 让图片水平居中

先将图片转化成块级元素，之后在设置 `margin: auto`。

示例：
```css
img {
  display: block;
  margin: auto;
}
```

## 垂直居中文字

方法1：为元素设置 `padding` 将可以使得文本垂直居中。

示例：
```css
.center {
  padding: 20px 0;
  border: 3px solid Blue;
}
```

方法2：设置 `line-height` 的值，使其等于 `height` 的值。

示例：
```css
.center {
  height: 300px;
  line-height: 300px;
  border: 3px solid Blue;
}
```