---
title: "RevisionAction"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "リビジョンに適用できるアクションを表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

リビジョンに適用できるアクションを表します。


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
|  | [NONE](#NONE) | アクションが取られないことを示します。 |
|
|  | [ACCEPT](#ACCEPT) | リビジョンが INSERTION タイプの場合は表示され、DELETION タイプの場合は削除されることを示します。 |
|
|  | [REJECT](#REJECT) | リビジョンが INSERTION タイプの場合は削除され、DELETION タイプの場合は表示されることを示します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


アクションが取られないことを示します。


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


リビジョンが INSERTION タイプの場合は表示され、DELETION タイプの場合は削除されることを示します。


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


リビジョンが INSERTION タイプの場合は削除され、DELETION タイプの場合は表示されることを示します。


### values() {#values--}
```
public static RevisionAction[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionAction valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
