---
title: "MetadataType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "निर्धारित करता है कि परिणाम दस्तावेज़ मेटाडेटा जानकारी कहाँ से लेगा।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

निर्धारित करता है कि परिणाम दस्तावेज़ मेटाडेटा जानकारी कहाँ से लेगा।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Metadata जैसा का वैसा रहेगा। |
|
|  | [SOURCE](#SOURCE) | Metedata स्रोत दस्तावेज़ से लिया जाएगा। |
|
|  | [TARGET](#TARGET) | Metedata लक्ष्य दस्तावेज़ से लिया जाएगा। |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata उपयोगकर्ता द्वारा सेट किया जाएगा। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | MetadataType की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [toString()](#toString--) | MetadataType का स्ट्रिंग प्रतिनिधित्व। |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Metadata जैसा का वैसा रहेगा।


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata स्रोत दस्तावेज़ से लिया जाएगा।


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata लक्ष्य दस्तावेज़ से लिया जाएगा।


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata उपयोगकर्ता द्वारा सेट किया जाएगा।


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


MetadataType की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | MetadataType का स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


MetadataType का स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

