---
title: "RevisionAction"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "एक कार्रवाई को दर्शाता है जिसे संशोधन पर लागू किया जा सकता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.comparison.words.revision/revisionaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionAction extends Enum<RevisionAction>
```

एक कार्रवाई को दर्शाता है जिसे संशोधन पर लागू किया जा सकता है।


उदाहरण उपयोग:

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


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [NONE](#NONE) | इसे दर्शाता है कि कोई कार्रवाई नहीं की जानी चाहिए। |
|
|  | [ACCEPT](#ACCEPT) | इसे दर्शाता है कि यदि संशोधन INSERTION प्रकार का है तो उसे प्रदर्शित किया जाएगा, या यदि प्रकार DELETION है तो उसे हटा दिया जाएगा। |
|
|  | [REJECT](#REJECT) | इसे दर्शाता है कि यदि संशोधन INSERTION प्रकार का है तो उसे हटा दिया जाएगा, या यदि प्रकार DELETION है तो उसे प्रदर्शित किया जाएगा। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final RevisionAction NONE
```


इसे दर्शाता है कि कोई कार्रवाई नहीं की जानी चाहिए।


### ACCEPT {#ACCEPT}
```
public static final RevisionAction ACCEPT
```


इसे दर्शाता है कि यदि संशोधन INSERTION प्रकार का है तो उसे प्रदर्शित किया जाएगा, या यदि प्रकार DELETION है तो उसे हटा दिया जाएगा।


### REJECT {#REJECT}
```
public static final RevisionAction REJECT
```


इसे दर्शाता है कि यदि संशोधन INSERTION प्रकार का है तो उसे हटा दिया जाएगा, या यदि प्रकार DELETION है तो उसे प्रदर्शित किया जाएगा।


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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction)
