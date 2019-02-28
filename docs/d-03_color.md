# CSS Colors

在 CSS 中，有很多种方式可以用来指定一种颜色，例如颜色名、RGB、HEX、HSL、RGBA 和 HSLA。

## 颜色名

HTML 支持 140 种标准颜色名。使用方法为——在属性名后直接接上颜色名：

```css
h1 {
  color: tomato;
}
```

常用的颜色名有：Tomato、Orange、DodgerBlue、MediumSeaGreen、Gray、SlateBlue、Violet 和 LightGray。

## 颜色值

除了指定颜色名这种方式外，我们还可以通过设置颜色值的方式来确定一种颜色。常用的颜色值有：RGB、HEX、HSL、RGBA 和 HSLA。

### RGB 值

RGB 即 Red、Green 和 Blue。使用 RGB 方式呈现出的颜色是 R、G、B 这 3 种颜色的混合色。我们可以为每种颜色指定一个特定的值，值的范围为 0～255。其使用方式如下：

```css
h1 {
  color: rgb(128, 128, 128);
}
```

- RGB 的一些特殊值

    - 白色：rgb(255, 255, 255)

    - 黑色：rgb(0, 0, 0)

    - 灰色：R、G、B 三种颜色值相同，值越大，颜色越接近白色；值越小，颜色越接近黑色

### HEX 值

这种方式就是将 RGB 值方式的每一种颜色的值转换成 16 进制。HEX 值的格式为 `#rrggbb`，使用方式如下：

```css
h1 {
  color: #eeaaaa;
}
```

### HSL 值

HSL 值的格式为 `hsl(hue, saturation, lightness)`。其中：

- `hue` 即色调的值，范围是 0～360，0 为 红色，120 为 绿色，240 为 蓝色

- `saturation` 即饱和度的值，范围是 0~100%

- `lightness` 即亮度的值，范围是 0~100%

示例：
```css
h1 {
  color: hsl(240, 50%, 60%);
}
```

### RGBA 值

RGBA 即 Red、Green、Blue 和 Alpha。其中的 Alpha 表示最后混合色的透明度。Alpha 值的范围是 0~1，数值越接近 0，颜色越浅。RGBA 的格式为 `rgba(red, green, blue, alpha)`，示例如下：

```css
h1 {
  color: rgba(128, 128, 128, 0.3);
}
```

### HSLA 值

HSLA 在 HSL 的方式上增加了一个 A，即 Alpha 值，这个值表示颜色的透明度，范围是 0～1，数值越接近 0，颜色越浅。HSLA 的格式为 `hsla(hue, saturation, lightness, alpha)`，示例如下：

```css
h1 {
  color: hsla(120, 50%, 30%, 0.4);
}
```

## 应用场景

CSS 颜色可以应用于 HTML 元素的背景色、字体颜色 和 边框颜色。

背景色（`background-color`）：
```css
h1 {
  background-color: DodgerBlue;
}
```

字体颜色（`color`）：
```css
p {
  color: tomato;
}
```

边框颜色（`border-color`）：
```css
h2 {
  border-color: MediumSeaGreen;
}
```