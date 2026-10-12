---
title: "ChangeInfo"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ChangeInfo クラスは、ドキュメント比較における特定の変更に関する情報を表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

ChangeInfo クラスは、ドキュメント比較における特定の変更に関する情報を表します。


変更の種類、影響を受けた領域、変更前後のコンテンツなどの詳細を提供します。
このクラスを使用して、比較結果内の個々の変更に関する情報を取得します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | 変更の一意の ID を取得します。 |
|
|  | [setId(int value)](#setId-int-) | 変更の一意の ID を設定します。 |
|
|  | [getComparisonAction()](#getComparisonAction--) | 変更に適用されるアクションを取得します。 |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | 変更に適用すべきアクションを設定します。 |
|
|  | [getPageInfo()](#getPageInfo--) | 現在の変更が見つかったページに関する情報を取得します。 |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | 現在の変更が見つかったページに関する情報を設定します。 |
|
|  | [getBox()](#getBox--) | ページ上の変更された要素の座標を取得します。 |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | ページ上の変更された要素の座標を設定します。 |
|
|  | [getText()](#getText--) | 変更のテキスト値を取得します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 変更のテキスト値を設定します。 |
|
|  | [getStyleChanges()](#getStyleChanges--) | スタイル変更の一覧を取得します。 |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | スタイル変更の一覧を設定します。 |
|
|  | [getAuthors()](#getAuthors--) | 著者の一覧を取得します。 |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | 著者の一覧を設定します。 |
|
|  | [getType()](#getType--) | 列挙型 [ChangeType](../../com.groupdocs.comparison.result/changetype) で表される変更のタイプを取得します。 |
|
|  | [getTargetText()](#getTargetText--) | 対象ドキュメントから変更されたテキストを取得します。 |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | 対象ドキュメントから変更されたテキストを設定します。 |
|
|  | [getSourceText()](#getSourceText--) | ソースドキュメントから変更されたテキストを取得します。 |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | ソースドキュメントから変更されたテキストを設定します。 |
|
|  | [getComponentType()](#getComponentType--) | 変更されたコンポーネントのタイプを取得します。 |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | 変更されたコンポーネントのタイプを設定します。 |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| row | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| column | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


変更の一意の ID を取得します。


**Returns:**
int - 変更の ID

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


変更の一意の ID を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | 変更の ID |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


変更に適用されるアクションを取得します。
アクション ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) または [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) は、この変更に対して比較が何をすべきかを示します。


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


変更に適用すべきアクションを設定します。
アクション ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) または [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) は、この変更に対して比較が何をすべきかを示します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | 変更に適用すべきアクション |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


現在の変更が見つかったページに関する情報を取得します。


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


現在の変更が見つかったページに関する情報を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | ページに関する情報 |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


ページ上の変更された要素の座標を取得します。


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


ページ上の変更された要素の座標を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | 変更された要素の座標（nullではありません） |
|

### getText() {#getText--}
```
public final String getText()
```


変更のテキスト値を取得します。


**Returns:**
java.lang.String - 変更のテキスト値

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


変更のテキスト値を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 変更のテキスト値 |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


スタイル変更の一覧を取得します。


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - スタイル変更のリスト

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


スタイル変更の一覧を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | スタイル変更のリスト |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


著者の一覧を取得します。


**Returns:**
java.util.List<java.lang.String> - 作者のリスト

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


著者の一覧を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.util.List<java.lang.String> | 作者のリスト |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


列挙型 [ChangeType](../../com.groupdocs.comparison.result/changetype) で表される変更のタイプを取得します。


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


対象ドキュメントから変更されたテキストを取得します。


**Returns:**
java.lang.String - 変更されたテキスト

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


対象ドキュメントから変更されたテキストを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 変更されたテキスト |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


ソースドキュメントから変更されたテキストを取得します。


**Returns:**
java.lang.String - 変更されたテキスト

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


ソースドキュメントから変更されたテキストを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 変更されたテキスト |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


変更されたコンポーネントのタイプを取得します。


**Returns:**
java.lang.String - 変更されたコンポーネントのタイプ

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


変更されたコンポーネントのタイプを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 変更されたコンポーネントのタイプ |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
