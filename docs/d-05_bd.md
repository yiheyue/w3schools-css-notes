# CSS 边框

通过设置 CSS 的 `border` 属性，我们可以改变 HTML 元素边框的大小和颜色。

## `border-style`

`border-style` 用于设置边框的样式。其可能的值有：`dotted`、`dashed`、`solid`、`double`、`groove`、`ridge`、`inset`、`outset`、`none` 和 `hidden`。

示例：
```css
p.dotted {
  border-style: dotted;
}
p.dashed {
  border-style: dashed;
}
```

## `border-width`

`border-width` 用于设置边框的宽度。指定边框的宽度有 2 种方式：

1. 指定一个确定的大小（单位是：px、pt、cm 等）

2. 使用预定义的值：`thin`、`medium` 和 `thick`

示例：
```css
p.one {
  border-style: solid;
  border-width: 5px;
}

p.two {
  border-style: solid;
  border-width: medium;
}

p.three {
  border-style: solid;
  border-width: 2px 10px 4px 2px;
}
```

## `border-color`

`border-color` 用于设置边框的颜色。示例如下：

```css
p.one {
  border-style: solid;
  border-color: Orange;
}

p.two {
  border-style: solid;
  border-color: SlateBlue;
}
```

## `border` 缩写

`border` 属性可以一次性表示下列 3 个属性：

- `border-width`

- `border-style`（必须的）

- `border-color`

## `border-radius`

使用 `border-radius` 属性可以将边框设置成圆角。示例如下：

```css
p {
  border: 2px solid SlateBlue;
  border-radius: 3px;
}
```