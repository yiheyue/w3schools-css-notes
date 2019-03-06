# CSS Overflow

在一块级元素内，若其中的内容过多而导致溢出时，我们应当使用 CSS 的 `overflow` 属性为其添加滚动条。

以下是 `overflow` 属性的可能值：

- `visible`：默认值，元素中的内容将被全部渲染出来（包括溢出的部分）

- `hidden`：溢出的部分将不被渲染

- `scroll`：添加滚动条

- `auto`：在需要时添加滚动条

示例如下：
```css
div.visible {
  overflow: visible;
}

div.hidden {
  overflow: hidden;
}

div.scroll {
  overflow: scroll;
}

div.auto {
  overflow: auto;
}
```

此外，该属性还有 2 个子属性：`overflow-x` 和 `overflow-y`，用于分别设置 x 和 y 方向上的溢出处理。