# CSS 列表

HTML 中有 2 种常用列表：无序列表（unordered list）和有序列表（ordered list）。无序列表的每一项前一般都带有一个小点，而有序列表的每一项前一般是有序的数字或是字母。

## `list-style-type`

CSS 的 `list-style-type` 用于改变每一项前的小标记。例如：

```css
/* unordered list */
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

/* ordered list */
ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
```

如果不想要每一项前的小标记，可以将该属性设置为 `none`，即 `list-style-type: none;`。

## `list-style-image`

`list-style-image` 属性给每一项前添加一个小图片，例如：

```css
ul {
  list-style-image: url("square.gif");
}
```

## `list-style-position`

`list-style-position` 属性用于定位每一项之前的小标记，小标记在外则为 `outside`，小标记在内则为 `inside`。

```css
ul.outside {
  list-style-position: outside;
}

ul.inside {
  list-style-position: inside;
}
```

## `list-style` 缩写

我们可以将上述的属性写在一起，例如：

```css
ul {
  list-style: square inside url("square.gif");
}
```