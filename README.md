# regular-expressions-2022-03-06

[オンラインツール](https://php-regexp.a-zumi.net/preg_replace)
[ASCIIコード表](https://www.k-cube.co.jp/wakaba/server/ascii_code.html)
[基本的な正規表現一覧](https://murashun.jp/article/programming/regular-expression.html)

![image](https://user-images.githubusercontent.com/1501327/156913342-c4637e46-ea3f-4937-a680-a786d8689ec5.png)
```
,.+?,
```

### 正規表現の置換( あ に置換 )

```
regular-expressions-2022-03-06
```
```
-.+?-
```
```
regularあ2022あ06
```

. : 任意の文字

\+ : 直前の文字が1文字以上

? : 最初に一致した文字列を対象とする

### 文字の範囲指定

```
-[0-9]+?-
```
```
regular-expressionsあ03-06
```

### 文字集合の否定

```
-[^a-z]+?-
```
```
regular-expressionsあ03-06
```
