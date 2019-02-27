# CSS 简介

CSS 全称 Cascading Style Sheets（层叠样式表），它是一门描述 HTML 文档样式的语言。它还描述了应该如何显示 HTML 元素。

## CSS 语法

一条 CSS 规则由一个**选择器**（selector）和一组**声明块**（declaration block）组成。

```css
h1 { color: blue; font-size: 12px; }
```

选择器（上例 `h1`）指向被上样式的 HTML 元素。

声明块（上例 `{ color: blue; font-size: 12px; }`）由若干条声明组成，每一条声明由分号（`;`）分隔开。

每一条声明包含一个 **CSS 属性名**（CSS property name）和它对应的**CSS 属性值**（CSS property value），它们之间用冒号（`:`）分隔开。

## CSS 选择器

CSS 选择器用于指定 HTML 元素（一个或多个）。它包含以下几种：

- 元素选择器（element selector）

- id 选择器（id selector）

- 类选择器（class selector）

- 组选择器（grouping selector）

### 元素选择器

元素选择器基于 HTML 元素的名字。例如选中页面中所有的 `<p>` 元素：

```css
p {
  text-align: center;
  color: red;
}
```

### id 选择器

id 选择器基于 HTML 元素的 id 属性。由于页面中所有 HTML 元素 id 都是唯一的，所以 id 选择器只指向页面的一个 HTML 元素。其格式为一个井号（`#`）加上 id 的属性值。

```css
#para1 {
  text-align: center;
  color: red;
}
```

### 类选择器

类选择器基于 HTML 元素的 class 属性。其格式为一个点号（`.`）加上 class 的属性值。

例如：指定页面中所有 class 为 center 的 HTML 元素：
```css
.center {
  text-align: center;
  color: red;
}
```

又例如：指定页面中所有 class 为 center 的 `<p>` 元素：
```css
p.center {
  text-align: center;
  color: red;
}
```

### 组选择器

组选择器用于将一些样式相同的 HTML 元素的 CSS 代码集中到一起。其格式为在每一个选择器之间加一个逗号（`,`）。

不使用组选择器：
```css
h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
```

使用组选择器：
```css
h1, h2, p {
  text-align: center;
  color: red;
}
```

## CSS 注释

在 CSS 中，注释以 `/*` 开始，以 `*/` 结束。

示例：
```css
/* 这是一条注释 */
p {
  text-align: center;
  color: red;
}
```