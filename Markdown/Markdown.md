# Markdown記法

拡張子：.md<br>
半角空白2つで改行，`<br>`でも改行可能

## 目次
- [見出し](#見出し)
- [太字・斜体・訂正線](#太字・斜体・訂正線)
- [テキストカラー](#テキストカラー)
- [コメントアウト](#コメントアウト)
- [箇条書きリスト](#箇条書きリスト)
- [番号付きリスト](#番号付きリスト)
- [テーブル](#テーブル)
- [コード](#コード)
- [数式](#数式)
- [URLリンク](#URLリンク)
- [ファイルの挿入](#ファイルの挿入)
- [水平線](#水平線)
<br>

## 見出し
<details>
<summary>詳細</summary>

```
# レベル1見出し
## レベル2見出し
### レベル3見出し
#### レベル4見出し
##### レベル5見出し
###### レベル6見出し
```
</details>
<br>

## 太字・斜体・訂正線
<details>

```
**太字**
*斜体*
~~訂正線~~
```
【表示例】<br>
**太字**<br>
*斜体*<br>
~~訂正線~~<br>
</details>
<br>

## テキストカラー
<details>

```
<span style="color: red;">赤文字</span>
```
【表示例】<br>
<span style="color: red;">赤文字</span>
</details>
<br>

## コメントアウト
<details>

```
<!-- テキスト -->
```
</details>
<br>

## 箇条書きリスト
<details>

```
- リスト
```
【表示例】<br>
- リスト1
- リスト2
  - サブリスト2.1
</details>
<br>

## 番号付きリスト
<details>
番号を統一することで，リスト要素の順番の変更が簡単になる

```
1. リスト1
1. リスト2
    1. サブリスト1
```
【表示例】<br>
1. リスト1
1. リスト2
    1. サブリスト1
</details>
<br>

## テーブル
<details>

```
|名前|年齢|住所|
|--|--|--|
|田中|20|東京|
|斎藤|25|大阪|
```
【表示例】<br>
|名前|年齢|住所|
|--|--|--|
|田中|20|東京|
|斎藤|25|大阪|

[テーブルの詳細について](https://www.sejuku.net/blog/49377)
</details>
<br>

## コード
<details>

```python
print("Hello World")
```
</details>
<br>


## 数式
<details>

```
$x=\dfrac{-b \pm \sqrt{b^2-4ac}}{2a}$

$\tan(\theta) = \dfrac{\sin(\theta)}{\cos(\theta)}$
```

$x=\dfrac{-b \pm \sqrt{b^2-4ac}}{2a}$<br>
<br>
$\tan(\theta) = \dfrac{\sin(\theta)}{\cos(\theta)}$<br>
[数式の詳細について](https://hwb.ecc.u-tokyo.ac.jp/wp/applications-2/latex/math)
</details>
<br>

## URLリンク
<details>

```
[表示テキスト](URL)
```
【表示例】<br>
[Google](https://google.com)
</details>
<br>

## ファイルの挿入
<details>

```
![代替テキスト](URL)
```
![画像](icon_image.png)
</details>
<br>

## 水平線
<details>

```
---
```

---
</details>
