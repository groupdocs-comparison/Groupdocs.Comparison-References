---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना प्रक्रिया के दौरान दस्तावेज़ में पासवर्ड जानकारी सहेजने के विकल्पों को सूचीबद्ध करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

तुलना प्रक्रिया के दौरान दस्तावेज़ में पासवर्ड जानकारी सहेजने के विकल्पों को सूचीबद्ध करता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [NONE](#NONE) | पासवर्ड को सहेजें नहीं। |
|
|  | [SOURCE](#SOURCE) | स्रोत दस्तावेज़ से पासवर्ड का उपयोग करें। |
|
|  | [TARGET](#TARGET) | लक्ष्य दस्तावेज़ से पासवर्ड का उपयोग करें। |
|
|  | [USER](#USER) | \* उपयोगकर्ता द्वारा प्रदान किया गया पासवर्ड उपयोग करें। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PasswordSaveOption की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [toString()](#toString--) | PasswordSaveOption का स्ट्रिंग प्रतिनिधित्व। |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


पासवर्ड को सहेजें नहीं।


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


स्रोत दस्तावेज़ से पासवर्ड का उपयोग करें।


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


लक्ष्य दस्तावेज़ से पासवर्ड का उपयोग करें।


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* उपयोगकर्ता द्वारा प्रदान किया गया पासवर्ड उपयोग करें।


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


PasswordSaveOption की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PasswordSaveOption का स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PasswordSaveOption का स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

