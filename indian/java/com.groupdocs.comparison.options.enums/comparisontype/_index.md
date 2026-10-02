---
title: "ComparisonType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "प्रदर्शित करता है वह तुलना प्रकार जिसे किया जाना है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

प्रदर्शित करता है वह तुलना प्रकार जिसे किया जाना है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [TEXT](#TEXT) | फ़ाइलों की तुलना टेक्स्ट दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [SLIDES](#SLIDES) | फ़ाइलों की तुलना प्रेज़ेंटेशन दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [WORDS](#WORDS) | फ़ाइलों की तुलना वर्ड्स दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [CELLS](#CELLS) | फ़ाइलों की तुलना एक्सेल दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [PDF](#PDF) | फ़ाइलों की तुलना PDF दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [IMAGING](#IMAGING) | फ़ाइलों की तुलना इमेज दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [EMAIL](#EMAIL) | फ़ाइलों की तुलना ईमेल दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [NOTE](#NOTE) | फ़ाइलों की तुलना नोट दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [HTML](#HTML) | फ़ाइलों की तुलना HTML दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [DIAGRAM](#DIAGRAM) | फ़ाइलों की तुलना डायग्राम दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [DIFFERENT](#DIFFERENT) | फ़ाइलों की तुलना विभिन्न फ़ॉर्मैटों में दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [SVG](#SVG) | फ़ाइलों की तुलना SVG दस्तावेज़ों के रूप में की जानी चाहिए। |
|
|  | [UNDEFINED](#UNDEFINED) | आंतरिक उपयोग के लिए। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonType की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [toString()](#toString--) | ComparisonType का स्ट्रिंग प्रतिनिधित्व। |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


फ़ाइलों की तुलना टेक्स्ट दस्तावेज़ों के रूप में की जानी चाहिए।


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


फ़ाइलों की तुलना प्रेज़ेंटेशन दस्तावेज़ों के रूप में की जानी चाहिए।


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


फ़ाइलों की तुलना वर्ड्स दस्तावेज़ों के रूप में की जानी चाहिए।


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


फ़ाइलों की तुलना एक्सेल दस्तावेज़ों के रूप में की जानी चाहिए।


### PDF {#PDF}
```
public static final ComparisonType PDF
```


फ़ाइलों की तुलना PDF दस्तावेज़ों के रूप में की जानी चाहिए।


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


फ़ाइलों की तुलना इमेज दस्तावेज़ों के रूप में की जानी चाहिए।


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


फ़ाइलों की तुलना ईमेल दस्तावेज़ों के रूप में की जानी चाहिए।


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


फ़ाइलों की तुलना नोट दस्तावेज़ों के रूप में की जानी चाहिए।


### HTML {#HTML}
```
public static final ComparisonType HTML
```


फ़ाइलों की तुलना HTML दस्तावेज़ों के रूप में की जानी चाहिए।


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


फ़ाइलों की तुलना डायग्राम दस्तावेज़ों के रूप में की जानी चाहिए।


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


फ़ाइलों की तुलना विभिन्न फ़ॉर्मैटों में दस्तावेज़ों के रूप में की जानी चाहिए।


### SVG {#SVG}
```
public static final ComparisonType SVG
```


फ़ाइलों की तुलना SVG दस्तावेज़ों के रूप में की जानी चाहिए।


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


आंतरिक उपयोग के लिए।


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


ComparisonType की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonType का स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


ComparisonType का स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

