# flexboxレイアウト

[サンプルページ](https://tomioka-k.github.io/html-css-basic/content/flex-layout.html)

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

