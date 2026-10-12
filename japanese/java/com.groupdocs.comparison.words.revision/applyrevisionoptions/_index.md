---
title: "ApplyRevisionOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ApplyRevisionOptions クラスは、改訂が最終文書に適用される前にその状態を更新できるようにします。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

ApplyRevisionOptions クラスは、改訂が最終文書に適用される前にその状態を更新できるようにします。


リビジョン適用プロセスをカスタマイズするためのさまざまなコンストラクタとプロパティを提供します。


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
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | ApplyRevisionOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | 指定されたリビジョンのリストで新しい ApplyRevisionOptions オブジェクトをインスタンス化します。 |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | 指定されたリビジョンのリストと共通リビジョンアクションで新しい ApplyRevisionOptions オブジェクトをインスタンス化します。 |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | 共通リビジョンアクションで新しい ApplyRevisionOptions オブジェクトをインスタンス化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 適用されるリビジョンのリストを取得します。 |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | 適用されるリビジョンのリストを設定します。 |
|
|  | [getCommonHandler()](#getCommonHandler--) | すべてのリビジョンに適用される共通リビジョンアクションを取得します。 |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | すべてのリビジョンに適用される共通リビジョンアクションを設定します。 |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


ApplyRevisionOptions クラスの新しいインスタンスを初期化します。


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


指定されたリビジョンのリストで新しい ApplyRevisionOptions オブジェクトをインスタンス化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 変更 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 適用されるリビジョンのリスト |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


指定されたリビジョンのリストと共通リビジョンアクションで新しい ApplyRevisionOptions オブジェクトをインスタンス化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 変更 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 適用されるリビジョンのリスト |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | すべてのリビジョンに適用される共通リビジョンアクション |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


共通リビジョンアクションで新しい ApplyRevisionOptions オブジェクトをインスタンス化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | すべてのリビジョンに適用される共通リビジョンアクション |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


適用されるリビジョンのリストを取得します。


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - リビジョンのリスト

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


適用されるリビジョンのリストを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 変更 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | リビジョンのリスト |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


すべてのリビジョンに適用される共通リビジョンアクションを取得します。


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


すべてのリビジョンに適用される共通リビジョンアクションを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 共通のリビジョンアクション |
|

