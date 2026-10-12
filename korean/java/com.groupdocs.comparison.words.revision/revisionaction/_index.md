---
title: "RevisionAction"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "수정에 적용될 수 있는 작업을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

수정에 적용될 수 있는 작업을 나타냅니다.


사용 예시:

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


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NONE](#NONE) | 동작이 수행되지 않음을 나타냅니다. |
|
|  | [ACCEPT](#ACCEPT) | 리비전이 INSERTION 유형이면 표시되고, DELETION 유형이면 제거됨을 나타냅니다. |
|
|  | [REJECT](#REJECT) | 리비전이 INSERTION 유형이면 제거되고, DELETION 유형이면 표시됨을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


동작이 수행되지 않음을 나타냅니다.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


리비전이 INSERTION 유형이면 표시되고, DELETION 유형이면 제거됨을 나타냅니다.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


리비전이 INSERTION 유형이면 제거되고, DELETION 유형이면 표시됨을 나타냅니다.


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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
