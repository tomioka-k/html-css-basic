# CSS基礎

## CSSをhtmlに組み込む方法

- インライン
- 内部参照
- 外部参照

### インライン

可読性が悪いので基本的に使わない

```html
<h1 style="color:darkblue">darkblue</h1>
```

### 内部参照
こちらも基本的に使用しない

```html
<h1>内部参照</h1>

<style>
    h1{color: aquamarine;}
</style>
```

### 外部参照
こちらがメイン

```html
<link rel="stylesheet" href="/css/basic-css.css">

or

@import url (外部ファイルのパス)

```

## 基本プロパティ

### 背景色

```css
body {
    background-color:azure;
}
```

### 文字色

```css
a {
    color: red;
}
```

### 境界線・余白

- border: 境界
- padding: 内側の余白
- margin: 外側の余白

```css
h2 {
    color: brown;
    background-color: blue;
    border: 5px solid;
    padding: 1rem;
    margin: 1rem;
}
```

## 基本セレクタ

### id

ページの中で一箇所しない要素に名前を付ける

```html
<main id="main-content">main</main>
```

#### idをセレクタにしてスタイルを記述

```css
#main-content {
    background-color: black;
    color: white;
    margin: 1rem;
    padding: 1rem;
}
```

### class

idと異なり、複数要素につけられる

```html
<p class="detail">detail</p>
```

#### classをセレクタにスタイルを記述

```css
.detail {
    font: bold;
    color: blueviolet;
}
```

### セレクタを細かく指定

セレクタを細かく指定する場合には
`.h2 detail`などツナテテ記載する

