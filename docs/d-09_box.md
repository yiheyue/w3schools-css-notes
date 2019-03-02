# CSS 盒模型

我们可以把所有的 HTML 元素想象成一个盒子。这个盒子由以下的部分组成：

1. 内容（content）：盒子的最内部，负责呈现文本和图片

2. 内填充（padding）：内容的外一层，包裹着内容，这一层是透明的

3. 边距（border）：内填充的外一层，包裹着内填充

4. 外边距（margin）：盒子的最外层，包裹着边框，这一层也是透明的

盒模型示意：
```
（外边距  （边距  （内填充  （内容）  内填充）  边距）  外边距）
```

## HTML 元素的宽度和高度

虽然 CSS 中有 `width` 和 `height` 属性，但是它们是用来定义**内容**的宽和高的（即不包括内填充、边距和外边距）。所以，计算 HTML 元素的大小时，应当采用如下的计算公式：

```
元素的总宽度 = width + left padding + right padding + left border + right border + left margin + right margin

元素的总高度 = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin
```