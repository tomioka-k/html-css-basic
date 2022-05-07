# 【CSS】flexboxレイアウト

# flexboxレイアウト

- [サンプルページ](https://tomioka-k.github.io/html-css-basic/content/flex-layout.html)
- [サンプルコード](https://github.com/tomioka-k/html-css-basic/blob/master/css/flex-layout.css)

`flexbox`を使用する際には親要素に`display: flex`を指定する。

```css
.main {
  display: flex;
}
```

## justify-content

横方向の位置の調整には、`justify-content`を使用します。

- flex-start
- flex-end
- center
- space-around
- space-between

```css
.wrapper {
    justify-content: flex-start;
    justify-content: flex-end;    
    justify-content: center;
    justify-content: space-around;
    justify-content: space-between;
}

```

![flex-start.png](/docs/img/jL0y41JUh-clipboard.png)
![flex-end.png](/docs/img/IULYWN7Y7-clipboard.png)
![center.png](/docs/img/jxGI8F7ZZ-clipboard.png)
![space-around.png](/docs/img/yX_RwUHao-clipboard.png)
![space-between.png](/docs/img/3FBrCOrKc-clipboard.png)

## align-items

縦方向の位置の調整には、`align-items`を使用します。

- stretch
- flex-start
- flex-end
- center
- baseline

```css
.wrapper {
  align-items: stretch;
  align-items: flex-start;
  align-items: flex-end;
  align-items: center;
  align-items: baseline;
}

```

![stretch.png](/docs/img/RLTfOlWuX-clipboard.png)
![flex-start.png](/docs/img/64UoWDCb1-clipboard.png)
![flex-end.png](/docs/img/8jISkYN6Q-clipboard.png)
![center.png](/docs/img/vXlZqJw7M-clipboard.png)
![baseline.png](/docs/img/e-fJaubwm-clipboard.png)

## flex-wrap

通常`flexbox`は要素の中にできるだけ入るようにしますが、折り返したりする場合には`flex-wrap`を使用します。

- nowrap: 初期値
- wrap: 折り返し
- wrap-reverse: 逆に折り返し

```css
.wrapper {
    flex-wrap: nowrap;
    flex-wrap: wrap;
    flex-wrap: wrap-reverse;
}

```

![nowrap.png](/docs/img/WnjkdUYpi-clipboard.png)
![wrap.png](/docs/img/6z29Rr2GL-clipboard.png)
![wrap-reverse.png](/docs/img/oB-anDson-clipboard.png)

## flex-direction

方向についてです。`row`か`column`かを`flex-direction`を指定します。

- row
- row-reverse
- column
- column-reverse

```css
.wrapper {
  flex-direction: row;
  flex-direction: row-reverse;
  flex-direction: column;
  flex-direction: column-reverse;
}
```

![row.png](/docs/img/kknbGZMB9-clipboard.png)
![row-reverse.png](/docs/img/FWOBUR5QV-clipboard.png)
![column.png](/docs/img/NT6rMUjBH-clipboard.png)
![column-reverse.png](/docs/img/mhfi81iX1-clipboard.png)