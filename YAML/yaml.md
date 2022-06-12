# YAML記法

Yamlとはデータ構造の一つで，JSONやXMLと同じくデータを構造で表現する

## データ型
様々なデータ型が存在する
<details>

#### 【YAML記法】
```YAML
# 文字列
name : "taro"
# 数値
age : 20
# float値
weight : 50.00
# Bool値
is-male : true
# null値
belong : null
# Date型
birthday : 2000-01-01 12:00:00
```
</details>

## ハッシュ
`key : value`のように記載することで，ハッシュ型（オブジェクト型）を定義できる<br>
<details>

#### 【YAML記法】
```YAML
name : taro
age : 20
```
#### 【JSON記法】
```JSON
{
    name : "taro",
    age : 20
}
```
</details>

## 配列
`-`を使うことで，配列を定義できる<br>
<details>

#### 【YAML記法】
```YAML
- aaa
- bbb
- ccc
```
#### 【JSON記法】
```JSON
["aaa", "bbb", "ccc"]
```
</details>

## ハッシュ構造のネスト
ハッシュの中にハッシュを定義できる
<details>

#### 【YAML記法】
```YAML
user :
    name : taro
    age : 20
```
#### 【JSON記法】
```JSON
{
    user : {
        name : "taro",
        age : 20
    }
}
```
</details>


## 配列構造のネスト
配列の中にも配列を定義できる
<details>

#### 【YAML記法】
```YAML
-
    - aaa
    - bbb
    - ccc
```
#### 【JSON記法】
```JSON
[ ["aaa", "bbb", "ccc"] ]
```
</details>


## ハッシュと配列の組み合わせ
<details>

#### 例1
```YAML
user :
    name : ichiro
    favorites :
        - apple
        - orange
```
```JSON
{
    user : {
        name : "ichiro",
        favorites : ["apple", "orange"]
    }
}
```

#### 例2
```YAML
members :
    - name : tanaka
      age : 20
    - name : saito
      age : 25
```
```JSON
{
    members : [{
        name : "tanaka",
        age : 20
    }, {
        name : "saito",
        age : 25
    }]
}
```
