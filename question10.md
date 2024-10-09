# 練習問題10：線形探索と二分探索

## 問題1: オーダーの理解
線形探索と二分探索の計算量を示し、なぜそうなるかを説明してください。
```
```

## 問題2: 線形探索
与えられた配列 `arr` から特定の要素 `target` を探し出す線形探索関数 `linearSearch` を実装してください。見つかればその要素のインデックスを、見つからなければ -1 を返すようにしてください。

```javascript
function linearSearch(arr, target) {
    // ここにコードを追加
}

// 例
const array1 = [1, 2, 3, 4, 5];
const target1 = 3;
console.log(linearSearch(array1, target1)); // 2
```

## 問題3: 二分探索
昇順に並んだ配列 `arr` から特定の要素 `target` を探し出す二分探索関数 `binarySearch` を実装してください。見つかればその要素のインデックスを、見つからなければ -1 を返すようにしてください。

```javascript
function binarySearch(arr, target) {
    // ここにコードを追加
}

// 例
const array2 = [1, 2, 3, 4, 5];
const target2 = 3;
console.log(binarySearch(array2, target2)); // 2
```

## 問題4: 線形探索の応用
文字列の配列 `strArr` から特定の文字列 `targetStr` を探し出す線形探索関数 `stringLinearSearch` を実装してください。見つかればその要素のインデックスを、見つからなければ -1 を返すようにしてください。

```javascript
function stringLinearSearch(strArr, targetStr) {
    // ここにコードを追加
}

// 例
const array3 = ["apple", "banana", "orange", "grape"];
const target3 = "orange";
console.log(stringLinearSearch(array3, target3)); // 2
```

## 問題5: 二分探索の応用
オブジェクトの配列 `objArr` から特定のオブジェクト `targetObj` を探し出す二分探索関数 `objectBinarySearch` を実装してください。見つかればその要素のインデックスを、見つからなければ -1 を返すようにしてください。

```javascript
function objectBinarySearch(objArr, targetObj) {
    // ここにコードを追加
}

// 例
const array4 = [
    { id: 1, name: "Alice" },
    { id: 2, name: "Bob" },
    { id: 3, name: "Charlie" },
];
const target4 = { id: 2, name: "Bob" };
console.log(objectBinarySearch(array4, target4)); // 1
```

## 最終問題: 二分探索の優位性
線形探索と二分探索のそれぞれの特徴と、どのような場面で二分探索が有利なのかを説明してください。

```

```