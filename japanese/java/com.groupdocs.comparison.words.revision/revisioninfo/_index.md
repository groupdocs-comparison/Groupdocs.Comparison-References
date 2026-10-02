---
title: "RevisionInfo"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "文書内の改訂を表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

文書内の改訂を表します。


リビジョンは、ドキュメントに対して行われた変更情報をカプセル化します。
このクラスは、リビジョンのタイプなど、リビジョンに関する情報を取得するメソッドを提供します、
コンテンツ、作者など。

使用例:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAction()](#getAction--) | リビジョンに関連付けられたアクション（受諾または却下）を取得します。 |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | リビジョンに関連付けられた値（受諾または却下）を設定します。 |
|
|  | [getText()](#getText--) | リビジョンのテキストコンテンツを取得します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | リビジョンの値コンテンツを設定します。 |
|
|  | [getAuthor()](#getAuthor--) | リビジョンの作者を取得します。 |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | リビジョンの値を設定します。 |
|
|  | [getType()](#getType--) | リビジョンのタイプを取得します。タイプに応じて、アクション（受け入れまたは拒否）のロジックが変わります。 |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | リビジョンの値を設定します。値に応じて、アクション（受け入れまたは拒否）のロジックが変わります。 |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


リビジョンに関連付けられたアクション（受け入れまたは拒否）を取得します。このフィールドはリビジョンの表示に影響を与えることができます。


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


リビジョンに関連付けられた値（受け入れまたは拒否）を設定します。このフィールドはリビジョンの表示に影響を与えることができます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | リビジョンに関連付けられた値です。 |
|

### getText() {#getText--}
```
public String getText()
```


リビジョンのテキストコンテンツを取得します。


**Returns:**
java.lang.String - リビジョンのテキストコンテンツ。

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


リビジョンの値コンテンツを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | リビジョンの値コンテンツです。 |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


リビジョンの作者を取得します。


**Returns:**
java.lang.String - リビジョンの作成者。

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


リビジョンの値を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | リビジョンの値です。 |
|

### getType() {#getType--}
```
public RevisionType getType()
```


リビジョンのタイプを取得します。タイプに応じて、アクション（受け入れまたは拒否）のロジックが変わります。


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


リビジョンの値を設定します。値に応じて、アクション（受け入れまたは拒否）のロジックが変わります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | リビジョンの値です。 |
|

