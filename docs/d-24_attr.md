# CSS Attribute Selectors

CSS 属性选择器可以用来指定拥有特定属性的 HTML 元素。

## CSS [attribute] Selector

示例：选择所有带有 `target` 属性的 `<a>` 元素
```css
a[target] {
  background-color: yellow;
}
```

## CSS [attribute="value"] Selector

示例：选择所有带有 `target` 属性且值为 `_blank` 的 `<a>` 元素
```css
a[target="_blank"] {
  background-color: yellow;
}
```

## CSS [attribute~="value"] Selector

示例：选择所有带有 `title` 属性且值中包含 `flower` 的元素（"one flower", "flowers"）
```css
[title~="flower"] {
  border: 5px solid yellow;
}
```

## CSS [attribute|="value"] Selector

示例：选择所有带有 `class` 属性且值中包含 `top` 的元素（"top", "one-top"）
```css
[class|="top"] {
  background: yellow;
}
```

## CSS [attribute^="value"] Selector

示例：选择所有带有 `class` 属性且值中以 `top` 开头的元素
```css
[class^="top"] {
  background: yellow;
}
```

## CSS [attribute$="value"] Selector

示例：选择所有带有 `class` 属性且值中以 `test` 结尾的元素
```css
[class$="test"] {
  background: yellow;
}
```

## CSS [attribute*="value"] Selector

示例：选择所有带有 `class` 属性且值中包含 `te` 的元素
```css
[class*="te"] {
  background: yellow;
}
```