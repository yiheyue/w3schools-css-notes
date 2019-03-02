# CSS 文本

本节出现的 CSS 属性有：

- `color`：设置文本颜色

- `text-align`：设置文本的对齐方式

- `text-decoration`：设置如何修饰文本

- `text-transform`：文本中英文的大小写转换

- `text-indent`：文本缩进

- `letter-spacing`：设置文本字母间距

- `line-height`：行高

- `direction`：文本排列方向

- `word-spacing`：文本中英文单词间距

- `text-shadow`：文本阴影

## 文本颜色

使用 `color` 属性可以设置文本的颜色。示例：

```css
body {
  color: blue;
}

h1 {
  color: green;
}
```

## 文本对齐

使用 `text-align` 属性可以设置文本在水平方向上的对齐方式。这个属性的可能值有：

- `left`：使文本左对齐

- `right`：使文本右对齐

- `center`：使文本居中

- `justify`：使每一行的文本都等长（效果类似与杂志和报纸）

示例：
```css
h1 {
  text-align: center;
}

h2 {
  text-align: left;
}

p {
  text-align: justify;
}
```

## 文本修饰

使用 `text-decoration` 属性可以修饰文本。这个属性的可能值有：

- `none`：无修饰

- `overline`：在文本上方增加一条线

- `line-through`：给文本添加一条删除线

- `underline`：在文本下方增加一条线

示例：
```css
h1 {
  text-decoration: overline;
}

h2 {
  text-decoration: line-through;
}

h3 {
  text-decoration: underline;
}

a {
  text-decoration: none;
}
```

## 文本转换

`text-transform` 属性可以转换英文字母的大小写。该属性的可能值有：

- `uppercase`：转换成大写

- `lowercase`：转换成小写

- `capitalize`：转换成大写字母开头

示例：
```css
p.uppercase {
  text-transform: uppercase;
}

p.lowercase {
  text-transform: lowercase;
}

p.capitalize {
  text-transform: capitalize;
}
```

## 文本缩进

`text-indent` 属性用于设置文本的缩进。示例如下：

```css
p {
  text-indent: 50px;
}
```

## 字母间距

`letter-spacing` 属性用于设置文本中字母间的间距。示例如下：

```css
h1 {
  letter-spacing: 3px;
}
```

## 行高

`line-height` 属性用于设置文本行的行高。示例如下：

```css
p.small {
  line-height: 0.8;
}

p.big {
  line-height: 1.7;
}
```

## 文本排列

使用 `direction` 属性可以设置文本的排列方向。示例如下：

```css
h1 {
  direction: ltr;
}

p {
  direction: rtl;
}
```

## 单词间距

使用 `word-spacing` 属性设置文本中单词的间距。示例如下：

```css
h1 {
  word-spacing: 10px;
}
```

## 文本阴影

使用 `text-shadow` 属性可以为文本设置阴影。示例如下：

```css
h1 {
  text-shadow: 3px 2px Tomato;
}
```