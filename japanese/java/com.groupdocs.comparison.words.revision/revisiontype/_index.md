---
title: "RevisionType"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ドキュメント内のリビジョンの種類を表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

ドキュメント内のリビジョンの種類を表します。


使用例:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [INSERTION](#INSERTION) | ドキュメントに新しいコンテンツが挿入されたときのタイプを表します。 |
|
|  | [DELETION](#DELETION) | ドキュメントからコンテンツが削除されたときのタイプを表します。 |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | 親ノードに書式変更が適用されたときのタイプを表します。 |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | 親スタイルに書式変更が適用されたときのタイプを表します。 |
|
|  | [MOVING](#MOVING) | ドキュメント内でコンテンツが移動されたときのタイプを表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | 提供された数値を使用して enum RevisionType の新しい定数を作成します。 |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | RevisionType の文字列表現を解析して enum 定数を取得します。 |
|
|  | [toInt()](#toInt--) | RevisionType の数値表現。 |
|
|  | [toString()](#toString--) | RevisionType の文字列表現。 |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


ドキュメントに新しいコンテンツが挿入されたときのタイプを表します。


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


ドキュメントからコンテンツが削除されたときのタイプを表します。


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


親ノードに書式変更が適用されたときのタイプを表します。


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


親スタイルに書式変更が適用されたときのタイプを表します。


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


ドキュメント内でコンテンツが移動されたときのタイプを表します。


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


提供された数値を使用して enum RevisionType の新しい定数を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toIntValue | int | RevisionType の数値表現 |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


RevisionType の文字列表現を解析して enum 定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | RevisionType の文字列表現 |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


RevisionType の数値表現。


**Returns:**
int - 列挙定数の数値

### toString() {#toString--}
```
public String toString()
```


RevisionType の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

