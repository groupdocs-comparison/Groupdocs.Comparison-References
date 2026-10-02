---
title: "RevisionAction"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Bir revizyona uygulanabilecek bir eylemi temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Bir revizyona uygulanabilecek bir eylemi temsil eder.


Örnek kullanım:

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


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NONE](#NONE) | Herhangi bir eylemin alınmayacağını gösterir. |
|
|  | [ACCEPT](#ACCEPT) | Revizyonun INSERTION türündeyse gösterileceğini, DELETION türündeyse kaldırılacağını gösterir. |
|
|  | [REJECT](#REJECT) | Revizyonun INSERTION türündeyse kaldırılacağını, DELETION türündeyse gösterileceğini gösterir. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Herhangi bir eylemin alınmayacağını gösterir.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Revizyonun INSERTION türündeyse gösterileceğini, DELETION türündeyse kaldırılacağını gösterir.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Revizyonun INSERTION türündeyse kaldırılacağını, DELETION türündeyse gösterileceğini gösterir.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
