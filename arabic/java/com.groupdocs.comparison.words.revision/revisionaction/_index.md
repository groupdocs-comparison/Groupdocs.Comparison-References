---
title: "RevisionAction"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل إجراءً يمكن تطبيقه على مراجعة."
type: docs
weight: 13
url: /ar/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

يمثل إجراءً يمكن تطبيقه على مراجعة.


مثال على الاستخدام:

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


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NONE](#NONE) | يشير إلى عدم اتخاذ أي إجراء. |
|
|  | [ACCEPT](#ACCEPT) | يشير إلى أن المراجعة ستُعرض إذا كانت من النوع INSERTION، أو ستُحذف إذا كان النوع DELETION. |
|
|  | [REJECT](#REJECT) | يشير إلى أن المراجعة ستُحذف إذا كانت من النوع INSERTION، أو ستُعرض إذا كان النوع DELETION. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


يشير إلى عدم اتخاذ أي إجراء.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


يشير إلى أن المراجعة ستُعرض إذا كانت من النوع INSERTION، أو ستُحذف إذا كان النوع DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


يشير إلى أن المراجعة ستُحذف إذا كانت من النوع INSERTION، أو ستُعرض إذا كان النوع DELETION.


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
