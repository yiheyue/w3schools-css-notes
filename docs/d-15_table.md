# CSS 表格

## 表格边框

设置表格的边框：
```css
table, th, td {
  border: 1px solid Black;
}
```

由于上述的代码会产生间隙，为了让间隙消失，我们使用 `border-collapse` 属性：
```css
table {
  border-collapse: collapse;
}

table, th, td {
  border: 1px solid black;
}
```

## 表格的宽度和高度

下例将设置表格宽度为父元素的 100%，th 高度为 50px：
```css
table {
  width: 100%;
}

th {
  height: 50px;
}
```

## 水平对齐

下例将设置表格 th 为左对齐（th 默认为居中）：
```css
th {
  text-align: left;
}
```

## 垂直对齐

下例将设置表格 td 为靠下对齐：
```css
td {
  height: 50px;
  vertical-align: bottom;
}
```