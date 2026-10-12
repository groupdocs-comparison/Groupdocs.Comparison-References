---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना विवरणों के स्तर को निर्दिष्ट करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

तुलना विवरणों के स्तर को निर्दिष्ट करता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [LOW](#LOW) | निम्न तुलना स्तर को दर्शाता है। |
|
|  | [MIDDLE](#MIDDLE) | मध्यम तुलना स्तर को दर्शाता है। |
|
|  | [HIGH](#HIGH) | उच्च तुलना स्तर को दर्शाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | enum स्थिरांक प्राप्त करने के लिए DetalisationLevel की स्ट्रिंग प्रतिनिधित्व को पार्स करता है। |
|
|  | [toString()](#toString--) | DetalisationLevel की स्ट्रिंग प्रतिनिधित्व। |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


निम्न तुलना स्तर को दर्शाता है।


यह "Low" स्तर तुलना के लिए सर्वोत्तम गति प्रदान करता है, लेकिन तुलना की गुणवत्ता का बलिदान करता है।
तुलना शब्द-प्रति की जाती है।


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


मध्यम तुलना स्तर को दर्शाता है।


यह "Middle" स्तर तुलना गति और गुणवत्ता के बीच एक उचित समझौता है।
तुलना अक्षर-प्रति की जाती है, लेकिन अक्षर केस और स्पेस की गिनती को अनदेखा किया जाता है।


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


उच्च तुलना स्तर को दर्शाता है।


यह "High" स्तर सबसे अच्छी तुलना गुणवत्ता है, लेकिन सबसे कम गति।
तुलना अक्षर-प्रति की जाती है, जिसमें अक्षर केस और स्पेस की गिनती को ध्यान में रखा जाता है।


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


enum स्थिरांक प्राप्त करने के लिए DetalisationLevel की स्ट्रिंग प्रतिनिधित्व को पार्स करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | DetalisationLevel की स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


DetalisationLevel की स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

