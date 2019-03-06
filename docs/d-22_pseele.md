# CSS Pseudo-elements

CSS 的伪元素用于指定 HTML 元素的特定部分。例如，元素的第一个字符或第一行。

## 语法

CSS 伪元素语法：
```
selector::pseudo-element {
  property: value;
}
```

## 所有的 CSS 伪元素

| Pseudo-element | Example         |
| -------------- | --------------- |
| ::after        | p::after        |
| ::before       | p::before       |
| ::first-letter | p::first-letter |
| ::first-line   | p::first-line   |
| ::selection    | p::selection    |

示例：
```css
p::first-letter {
  color: #ff0000;
}

h1::before {
  content: url("smile.gif");
}

p::selection {
  color: Red;
}
```