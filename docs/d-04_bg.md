# CSS 背景

CSS 背景属性包括：

- `background-color`

- `background-image`

- `background-repeat`

- `background-attachment`

- `background-position`

## `background-color`

`background-color` 用于设置 HTML 元素的背景颜色，例如：

```css
h1 {
  background-color: Orange;
}
```

## `background-image`

`background-image` 用于设置 HTML 元素的背景图片，默认情况下，背景图片会铺满整个 HTML 元素，使用方式如下：

```css
body {
  background-image: url("bg.png");
}
```

`background-repeat` 用于设置 HTML 元素背景图片的平铺方式。

```css
body {
  background-image: url("bg.png");
  background-repeat: repeat-x;
}
```

`background-position` 用于设置 HTML 元素背景图片的定位。

```css
body {
  background-image: url("bg.png");
  background-repeat: no-repeat;
  background-position: right top;
}
```

`background-attachment` 用于设置 HTML 元素背景图片位置是否固定。

```css
body {
  background-image: url("bg.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```

## `background` 缩写

我们可以将上述的属性写在一起，它们的排列顺序为：

- `background-color`

- `background-image`

- `background-repeat`

- `background-attachment`

- `background-position`

例如：
```css
body {
  background: #eeaaaa url("bg.png") no-repeat fixed right top;
}
```