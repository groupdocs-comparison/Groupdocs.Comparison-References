---
title: "RevisionAction"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет действие, которое может быть применено к ревизии."
type: docs
weight: 13
url: /ru/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Представляет действие, которое может быть применено к ревизии.


Пример использования:

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


## Поля

| Поле | Описание |
| --- | --- |
|  | [NONE](#NONE) | Указывает, что действие не требуется. |
|
|  | [ACCEPT](#ACCEPT) | Указывает, что ревизия будет отображена, если её тип INSERTION, или будет удалена, если тип DELETION. |
|
|  | [REJECT](#REJECT) | Указывает, что ревизия будет удалена, если её тип INSERTION, или будет отображена, если тип DELETION. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Указывает, что действие не требуется.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Указывает, что ревизия будет отображена, если её тип INSERTION, или будет удалена, если тип DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Указывает, что ревизия будет удалена, если её тип INSERTION, или будет отображена, если тип DELETION.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
