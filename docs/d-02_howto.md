# CSS 使用

有 3 种方式可以在页面中插入 CSS：

1. 外部样式表（External Style Sheet）

2. 内部样式表（Internal Style Sheet）

3. 行内样式（Inline Style）

## 外部样式表

这种方式就是在页面中加入一个 `<link>` 元素（要在 `<head>` 元素中），这个元素链接着一个外部的 CSS 文件。

例如，引入当前目录下的 css 目录中的 style.css 文件：
```html
<head>
  <link rel="stylesheet" href="/css/style.css">
</head>
```