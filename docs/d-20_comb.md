# CSS Combinators

CSS 的 combinators 用于描述选择器之间的关系。combinators 一共有 4 种：

- descendant selector(space)

- child selector(>)

- adjacent sibling selector(+)

- general sibling selector(~)

## Descendant Selector

格式为：`elem1 elem2`。这种方式将匹配 `elem1` 元素下的所有 `elem2` 元素，例如匹配 `<div>` 中的所有 `<p>` 元素：

```css
div p {
  background-color: yellow;
}
```

## Child Selector

格式为：`elem1 > elem2`。这种方式将匹配 `elem1` 元素下紧接着的所有 `elem2` 元素，示例如下：

```css
div > p {
  background-color: yellow;
}
```

## Adjacent Sibling Selector

格式为：`elem1 + elem2`。这种方式将匹配所有与 `elem1` 元素互为兄弟元素的 `elem2` 元素，且 `elem1` 下一个元素必须是 `elem2`，示例如下：

```css
div + p {
  background-color: yellow;
}
```

## General Sibling Selector

格式为：`elem1 ~ elem2`。这种方式将匹配所有 `elem1` 元素之后与 `elem1` 元素互为兄弟元素的 `elem2` 元素，示例如下：

```css
div ~ p {
  background-color: yellow;
}
```