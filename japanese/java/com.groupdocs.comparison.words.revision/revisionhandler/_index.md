---
title: "RevisionHandler"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "改訂の処理を制御するクラスを表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

改訂の処理を制御するクラスを表します。


RevisionHandler クラスは、ドキュメント内のリビジョンを操作できるようにします。
リビジョンのリストを取得し、リビジョンに変更を適用し、変更されたドキュメントを保存するためのメソッドを提供します。


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


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | リビジョンを含むファイルへのパスを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。 |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | リビジョンを含むファイルへのパスを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。 |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | リビジョンを含むファイルストリームを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。 |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | ドキュメントを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | すべてのリビジョンのリストを取得します。 |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | リビジョンの変更を処理し、元のファイルに適用します。 |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | リビジョンの変更を処理し、結果を指定されたファイルに書き込みます。 |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | リビジョンの変更を処理し、結果を指定されたファイルに書き込みます。 |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | リビジョンの変更を処理し、結果をドキュメントストリームに書き込みます。 |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


リビジョンを含むファイルへのパスを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ファイルへのパス。 |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


リビジョンを含むファイルへのパスを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | ファイルへのパス。 |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


リビジョンを含むファイルストリームを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ファイル | java.io.InputStream | ソースドキュメントストリーム。 |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | ファイルのタイプ。 |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


ドキュメントを使用して、RevisionHandler クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | com.aspose.words.Document | ドキュメント。 |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


すべてのリビジョンのリストを取得します。


リビジョンは元々グループでソートされていたため、リビジョンは List から取得しなければなりません。
List 内では、単一のリビジョンが同じ一般テキストを持つ複数のリビジョンに分割されることがあります。
リストに同じ一般的なテキストを持つリビジョンが含まれる可能性があるため、ユーザー向けにリビジョンのリストを作成する際にこれを制御する必要があります。
ここでは List\<RevisionGroup\> グループを使用して制御しています。


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - リビジョンのリスト。

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


リビジョンの変更を処理し、元のファイルに適用します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 変更されたリビジョンのリスト。 |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


リビジョンの変更を処理し、結果を指定されたファイルに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 結果ファイルのパス。 |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 変更されたリビジョンのリスト。 |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


リビジョンの変更を処理し、結果を指定されたファイルに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 結果ファイルのパス。 |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 変更されたリビジョンのリスト。 |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


リビジョンの変更を処理し、結果をドキュメントストリームに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 結果ドキュメントのストリーム。 |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 変更されたリビジョンのリスト。 |
|

### close() {#close--}
```
public void close()
```




