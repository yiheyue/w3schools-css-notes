# CSS 字体

本节出现的 CSS 属性有：

- `font-family`：字体种类

- `font-style`：字体样式

- `font-size`：字体大小

- `font-weight`：字体加粗

## 字体衬线

有衬线的字体更加适用于报纸杂志等媒体，而没有衬线的字体一般更适用于网页。

无衬线：Sans-serif

有衬线：Serif

## 字体种类

使用 `font-family` 属性可以设置字体的种类。总的来说，字体分为 3 大类：

- Sans-serif：无衬线字体

- Serif：有衬线字体

- Monospace：等宽字体

常用的英文字体有：

- Serif

    - Georgia, serif

    - "Palatino Linotype", "Book Antiqua", Palatino, serif

    - "Times New Roman", Times, serif

- Sans-serif

    - Arial, Helvetica, sans-serif

    - "Arial Black", Gadget, sans-serif

    - "Comic Sans MS", cursive, sans-serif

    - Impact, Charcoal, sans-serif

    - "Lucida Sans Unicode", "Lucida Grande", sans-serif

    - Tahoma, Geneva, sans-serif

    - "Trebuchet MS", Helvetica, sans-serif

    - Verdana, Geneva, sans-serif

- Monospace

    - "Courier New", Courier, monospace

    - "Lucida Console", Monaco, monospace

示例：
```css
p {
  font-family: "Courier New", Courier, monospace;
}
```

## 字体样式

`font-style` 属性用于设置字体样式，其可能的值有：

- `normal`：正常字体样式

- `italic`：倾斜字体样式

- `oblique`：非常类似于 `italic` 的字体样式

示例：
```css
p.normal {
  font-style: normal;
}

p.italic {
  font-style: italic;
}

p.oblique {
  font-style: oblique;
}
```

## 字体大小

`font-size` 属性用于设置字体的大小。字体大小的常用单位是 `px` 和 `em`（1em = 16px）。示例如下：

```css
body {
  font-size: 100%;
}

h1 {
  font-size: 2.5em;
}

h2 {
  font-size: 1.875em;
}

p {
  font-size: 0.875em;
}
```

## 字体加粗

使用 `font-weight` 属性可以将字体加粗，使用方法如下：

```css
p.normal {
  font-weight: normal;
}

p.thick {
  font-weight: bold;
}
```

## `vw` - viewport width

除了可以使用 `px` 和 `em` 设置字体大小外，我们还可以使用 `vw` 设置字体大小。使用 `vw` 单位设置的字体，其字体大小会随着浏览器窗口大小的变化而变化。

> 1vw = 1% viewport width