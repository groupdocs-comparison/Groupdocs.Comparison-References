---
title: "StyleChangeInfo"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "StyleChangeInfo クラスは、比較されたドキュメントにおけるスタイル変更に関する情報を表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

StyleChangeInfo クラスは、比較されたドキュメントにおけるスタイル変更に関する情報を表します。


変更されたプロパティ名や変更前後の値などの詳細を提供します。
このクラスを使用して、文書比較プロセス中のスタイル変更に関する情報を取得します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | 変更されたプロパティの名前を取得します。 |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | 変更されたプロパティの名前を設定します。 |
|
|  | [getNewValue()](#getNewValue--) | プロパティの新しい値を取得します。 |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | プロパティの新しい値を設定します。 |
|
|  | [getOldValue()](#getOldValue--) | プロパティの古い値を取得します。 |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | プロパティの古い値を設定します。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


変更されたプロパティの名前を取得します。


**Returns:**
java.lang.String - プロパティ名

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


変更されたプロパティの名前を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | プロパティ名 |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


プロパティの新しい値を取得します。


**Returns:**
java.lang.Object - プロパティの新しい値

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


プロパティの新しい値を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Object | プロパティの新しい値 |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


プロパティの古い値を取得します。


**Returns:**
java.lang.Object - プロパティの古い値

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


プロパティの古い値を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Object | プロパティの古い値 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
