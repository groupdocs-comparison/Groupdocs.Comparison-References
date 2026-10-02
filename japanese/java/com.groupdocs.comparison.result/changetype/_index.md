---
title: "ChangeType"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ChangeType 列挙型は、ドキュメント比較プロセス中に発生し得る変更の種類を表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

ChangeType 列挙型は、ドキュメント比較プロセス中に発生し得る変更の種類を表します。


この列挙型の各定数は、特定の変更タイプを表し、人間が読める説明と数値を提供します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NONE](#NONE) | 変更なしを表します。 |
|
|  | [MODIFIED](#MODIFIED) | 修正された変更を表します。 |
|
|  | [INSERTED](#INSERTED) | 挿入された変更を表します。 |
|
|  | [DELETED](#DELETED) | 削除された変更を表します。 |
|
|  | [ADDED](#ADDED) | 追加された変更を表します。 |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | 未変更の変更を表します。 |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | スタイルが変更された変更を表します。 |
|
|  | [RESIZED](#RESIZED) | サイズ変更された変更を表します。 |
|
|  | [MOVED](#MOVED) | 移動された変更を表します。 |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | 移動およびサイズ変更された変更を表します。 |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | シフトされ、サイズ変更された変更を表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ChangeType の文字列表現を解析して列挙定数を取得します。 |
|
|  | [fromInt(int intValue)](#fromInt-int-) | 提供された数値を使用して ChangeType 列挙型の新しい定数を作成します。 |
|
|  | [toString()](#toString--) | ChangeType の文字列表現。 |
|
|  | [toInt()](#toInt--) | ChangeType の数値表現。 |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


変更なしを表します。


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


修正された変更を表します。


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


挿入された変更を表します。


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


削除された変更を表します。


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


追加された変更を表します。


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


未変更の変更を表します。


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


スタイルが変更された変更を表します。


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


サイズ変更された変更を表します。


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


移動された変更を表します。


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


移動およびサイズ変更された変更を表します。


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


シフトされ、サイズ変更された変更を表します。


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


ChangeType の文字列表現を解析して列挙定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ChangeType の文字列表現 |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


提供された数値を使用して ChangeType 列挙型の新しい定数を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | intValue | int | ChangeType の数値表現 |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ChangeType の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

### toInt() {#toInt--}
```
public int toInt()
```


ChangeType の数値表現。


**Returns:**
int - 列挙定数の数値

