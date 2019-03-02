# CSS 链接

## 样式链接

链接有 4 种状态可以指定：

- `a:link`：正常、未被浏览过的

- `a:visited`：被浏览过的

- `a:hover`：鼠标在链接上

- `a:active`：链接正在被点击

> `a:hover` 必须在 `a:link` 和 `a:visited` 之后。`a:active` 必须在 `a:hover` 之后。

示例：
```css
a:link {
  color: red;
}

a:visited {
  color: green;
}

a:hover {
  color: HotPink;
}

a.active {
  color: blue;
}
```

## 链接按钮

下列代码演示了如何将链接变成按钮。

```css
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
```