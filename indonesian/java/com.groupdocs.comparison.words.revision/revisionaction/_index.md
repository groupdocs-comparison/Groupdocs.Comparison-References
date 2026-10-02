---
title: "RevisionAction"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili tindakan yang dapat diterapkan pada revisi."
type: docs
weight: 13
url: /id/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

Mewakili tindakan yang dapat diterapkan pada revisi.


Contoh penggunaan:

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


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NONE](#NONE) | Menunjukkan bahwa tidak ada tindakan yang harus dilakukan. |
|
|  | [ACCEPT](#ACCEPT) | Menunjukkan bahwa revisi akan ditampilkan jika bertipe INSERTION, atau akan dihapus jika bertipe DELETION. |
|
|  | [REJECT](#REJECT) | Menunjukkan bahwa revisi akan dihapus jika bertipe INSERTION, atau akan ditampilkan jika bertipe DELETION. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


Menunjukkan bahwa tidak ada tindakan yang harus dilakukan.


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


Menunjukkan bahwa revisi akan ditampilkan jika bertipe INSERTION, atau akan dihapus jika bertipe DELETION.


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


Menunjukkan bahwa revisi akan dihapus jika bertipe INSERTION, atau akan ditampilkan jika bertipe DELETION.


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
