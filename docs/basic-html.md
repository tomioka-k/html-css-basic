
# HTML文書構造

[サンプルページ](../source/basic-html.html)

## 見出し

階層構造を表現する方法として`<h1-h6>`を設定する

```html

<h1>見出し1</h1>
<h1>見出し1</h1>

```

## 段落

`<p>`タグで段落を記述する。`</p>`で閉じれば、自動的に改行される

```html

<p>段落</p>

```

## 箇条書き

- `ul`: 順不同
- `ol`: 順番

```html

<ul>
        <li>li</li>
        <li>li</li>
        <li>li</li>
    </ul>
    <ol>
        <li>d</li>
        <li>d</li>
        <li>d</li>
    </ol>
    <ol>
        <li>d</li>
        <ol>
            <li>d</li>
            <li>d</li>
            <li>d</li>
        </ol>
        <li>d</li>
    </ol>

```

## 記述リスト

`dl`,`dt`,`dd`がセット

```html

<dl>
    <dt>aaa</dt>
    <dd>bbb</dd>
</dl>

```

## セクション構造

セクション毎の塊を`section`でまとめる

```html

<section> Area </section>

```

## 段落内の改行

`<br>`タグで段落内を改行

```html

<p>こんにちはこんにちはこんにちはこんにち<br>
        はこんにちはこんにちは
    </p>

```

## 重要な語句を強調

`<strong>`で語句を強調

> 太字にする意味ではなく、文章として重要な語句を表す

```html

 <p>これから<strong>ここを強調</strong>します</p>

```

## 注釈・細めを明示

`<small>`

```html

  <p><small>tomioka-k </small></p>

```

## 画像を挿入

`<img src="./image.png" width="300" height="300" alt="sample-image" >`

- src: イメージのパス
- width/height: 横縦幅
- alt: 表示されなかったときの代替文字

```html

<img src="sample.jpg" width="150" height="150" alt="sample-image">


```

## リンク設定

`<a href="">`

> 外部サイトに移動する際に別タブで開く場合にはtarget=_blankとする

```html
 <p><a href="https://www.google.com/?hl=ja">google</a></p>
```

