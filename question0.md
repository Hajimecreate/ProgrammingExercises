# 0. プログラミング基礎：変数
`Javascript`というプログラミング言語で練習問題にチャレンジしてもらいます。  
適宜、分からない部分は`javascript ○○`とググりながらやってみてください！

## 変数とは
変数とは、プログラムにおいて、利用するデータを入れる箱のようなものです。
この中にデータを入れることで自由にデータの取り出しや変更が行えるようになります。

## 変数の宣言
変数の宣言は次のような構文を使用します。

```javascript=
// [変数のタイプ]　[変数名]; という文法
var count; // 変数の宣言
let age; // 変数の宣言
const name = "John"; // 定数の宣言と初期化
```

`var`や`let`、`const`とは宣言する変数のタイプを表しています。

:::success
**重要**
`const`は再代入/再宣言不可という特徴があります。
→ `const name = "John;"`と宣言すると、`name`という変数は他で宣言できず、`John`以外の値は入らないことを明示できます。つまり、`const` = `constant` = `定数`です。

そして、`let`は再代入は可能ですが再宣言が不可能です。
`let name = "John";`とすると、`name`という変数は他で宣言できませんが、`name`に入る値は自由に変更可能です。
:::

ひとまず、基本は`let`を使うと思っておいてください。


## 変数へのデータの格納
変数にはさまざまなデータ型の値を格納(代入)することができます。
例えば、数値、文字列、真偽値、配列、オブジェクトなどがあります。

変数にデータを代入することを、**初期化する**という言い方をしたりします。

```javascript
let age = 25; // 数値
let name = "John"; // 文字列
let isChild = true; // 真偽値
let numbers = [1, 2, 3, 4, 5]; // 配列
let person = { name: "John", age: 25 }; // オブジェクト
```
:::danger
**Point！**
数学では、`a = 7`は`a と 7 は等しい`という意味でしたが、
プログラミングの世界では、`a = 7` が`a に 7 を代入する`という意味になります。
:::


変数は値を代入することで値を更新できます。

```javascript
let count = 0;
count = count + 1; // countの値は1になる
```

変数は他の変数の値を参照することもできます。

```javascript
let x = 5;
let y = x + 2; // yの値は7
```

## 四則演算
数学と同じように、`JavaScript`では以下のような演算子を使って計算ができます。

| 演算子 | 名前 | 使用例 |
| -------- | -------- | -------- |
| `+`     | 加算     | `6 + 9`     |
| `-`     | 減算     | `20 - 15`     |
| `*`     | 乗算     | `3 * 7`     |
| `/`     | 除算     | `10 / 5`     |
| `％`     | 剰余（左項を右項で割った余りを求める。）     | `8 % 3`     |
| `**`    | 指数    | `5 ** 2` （5の2乗のこと）    |

## 検証ツールの使い方
1. Chromeの検証ツールを開きます。
2. `Console`タブに以下のプログラムをペーストします。
3. プログラムの実行結果が表示されます。
```javascript=
let count = 0;
count = count + 1;

// 検証ツールに変数の値を表示させる命令は `console.log()`
console.log(count);

// 画面に出したい時は `document.write()`
document.write(count);
```

## 練習問題

以下は、JavaScriptの変数に関する練習問題です。

### 1. 変数の宣言と初期化
`name`という変数を宣言し、自分の名前で初期化してください。

```javascript=
// ここに回答をかいてね

```

### 2. 変数の再代入

`year`という変数を宣言し、現在の西暦で初期化してください。
その後、変数の値を1つ増やしてください。

```javascript=
// ここに回答をかいてね

```

### 3. 変数のデータ型
`isStudent`という変数を宣言し、自身が学生であるかどうかを**真偽値**で初期化してください。

```javascript=
// ここに回答をかいてね

```

### 4. 変数の演算
`x`と`y`という2つの変数を宣言し、それぞれ好きな数値で初期化してください。
その後、これらの変数の合計を計算し、結果を新しい変数`sum`に代入してください。

```javascript=
// ここに回答をかいてね

```

### 5. 変数の連結
`firstName`と`lastName`という2つの変数を宣言し、それぞれ自分の名前の苗字と名前で初期化してください。
次に、これらの変数を連結してフルネームを表示するコードを書いてください。

```javascript=
// ここに回答をかいてね

```

### 最終問題
円の半径を表す**定数**`radius`を宣言し、適当な数値で初期化してください。
次に、円の面積を計算し、結果を表示するコードを書いてください。

```javascript=
// ここに回答をかいてね

```