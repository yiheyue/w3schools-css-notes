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

## 内部样式表

这种方式就是在页面中加入一个 `<style>` 元素（要在 `<head>` 元素中），将 CSS 样式写在其中。

例如：
```html
<head>
  <style>
  body {
    background-color: linen;
  }

  h1 {
    color: maroon;
    margin-left: 40px;
  }
  </style>
</head>
```

## 行内样式

行内样式使用于一个特定的 HTML 元素中，将样式写在其 style 属性中。

例如：
```html
<h1 style="color:blue; margin-left:30px;">This is a heading</h1>
```

## 属性覆盖以及优先级

当一个 HTML 元素的某个 CSS 属性被多次定义时，前面定义的属性值将被后定义的属性值覆盖。

CSS 样式优先级：

    1. 行内样式（优先级最高）

    2. 外部样式表 和 内部样式表

    3. 浏览器默认样式（优先级最低）