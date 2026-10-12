---
title: "ComparisonAction"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ComparisonAction 列挙型は、ドキュメント比較プロセス中に変更に適用できるアクションを表します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

ComparisonAction 列挙型は、ドキュメント比較プロセス中に変更に適用できるアクションを表します。


この列挙型の各定数は特定のアクションを表し、人間が読みやすい説明と数値を提供します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NONE](#NONE) | アクションなしを表します。 |
|
|  | [ACCEPT](#ACCEPT) | 受諾アクションを表します。 |
|
|  | [REJECT](#REJECT) | 拒否アクションを表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonAction の文字列表現を解析して列挙定数を取得します。 |
|
|  | [fromInt(int intValue)](#fromInt-int-) | 提供された数値を使用して ComparisonAction 列挙型の新しい定数を作成します。 |
|
|  | [toString()](#toString--) | ComparisonAction の文字列表現。 |
|
|  | [toInt()](#toInt--) | ComparisonAction の数値表現。 |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


アクションなしを表します。変更は効果を持ちません。


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


受諾アクションを表します。変更は結果ファイルに表示されます。


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


拒否アクションを表します。変更は結果ファイルに表示されません。


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


ComparisonAction の文字列表現を解析して列挙定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonAction の文字列表現 |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


提供された数値を使用して ComparisonAction 列挙型の新しい定数を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | intValue | int | ComparisonAction の数値表現 |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ComparisonAction の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

### toInt() {#toInt--}
```
public int toInt()
```


ComparisonAction の数値表現。


**Returns:**
int - 列挙定数の数値

