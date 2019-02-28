# CSS 高度/宽度

CSS 的 `height` 和 `width` 属性用于设置 HTML 元素的高度和宽度。例如：

```css
div {
  width: 500px;
  height: 300px;
}
```

CSS `height` 和 `width` 指的是元素内容的大小，不包括元素的内填充、边框和外边距。

## `max-width`

通常我们不给 HTML 元素指定一个固定的 `width`，因为当浏览器变更大小时，若元素宽度过长，则页面上将会出现水平滚动条，这将影响用户的体验。

而使用 `max-width` 可以解决这个问题：
```css
div {
  max-width: 500px;
  height: 100px;
}
```