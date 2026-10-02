---
title: "DetalisationLevel"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較詳細のレベルを指定します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

比較詳細のレベルを指定します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [LOW](#LOW) | 低比較レベルを表します。 |
|
|  | [MIDDLE](#MIDDLE) | 中比較レベルを表します。 |
|
|  | [HIGH](#HIGH) | 高比較レベルを表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | DetalisationLevel の文字列表現を解析して列挙定数を取得します。 |
|
|  | [toString()](#toString--) | DetalisationLevel の文字列表現。 |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


低比較レベルを表します。


\"Low\" レベルは比較の速度が最速ですが、比較品質を犠牲にします。
比較は単語単位で実行されます。


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


中比較レベルを表します。


\"Middle\" レベルは比較速度と品質のバランスが取れた妥当なレベルです。
比較は文字単位で実行されますが、文字の大文字小文字とスペース数は無視されます。


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


高比較レベルを表します。


\"High\" レベルは最高の比較品質ですが、速度は最も遅くなります。
比較は文字単位で実行され、文字の大文字小文字とスペース数を考慮します。


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


DetalisationLevel の文字列表現を解析して列挙定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | DetalisationLevel の文字列表現 |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


DetalisationLevel の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

