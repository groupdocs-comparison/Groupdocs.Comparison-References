---
title: "PaperSize"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ तुलना के लिए कागज़ आकार विकल्पों को दर्शाता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

दस्तावेज़ तुलना के लिए कागज़ आकार विकल्पों को दर्शाता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | डिफ़ॉल्ट कागज़ का आकार। |
|
|  | [A0](#A0) | मानक कागज़ का आकार A0 (841mm x 1189mm)। |
|
|  | [A1](#A1) | मानक कागज़ का आकार A1 (594mm x 841mm)। |
|
|  | [A2](#A2) | मानक कागज़ का आकार A2 (420mm x 594mm)। |
|
|  | [A3](#A3) | मानक कागज़ का आकार A3 (297mm x 420mm)। |
|
|  | [A4](#A4) | मानक कागज़ का आकार A4 (210mm x 297mm)। |
|
|  | [A5](#A5) | मानक कागज़ का आकार A5 (148mm x 210mm)। |
|
|  | [A6](#A6) | मानक कागज़ का आकार A6 (105mm x 148mm)। |
|
|  | [A7](#A7) | मानक कागज़ का आकार A7 (74mm x 105mm)। |
|
|  | [A8](#A8) | मानक कागज़ का आकार A8 (52mm x 74mm)। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PaperSize की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [toString()](#toString--) | PaperSize की स्ट्रिंग प्रतिनिधित्व। |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


डिफ़ॉल्ट कागज़ का आकार।


### A0 {#A0}
```
public static final PaperSize A0
```


मानक कागज़ का आकार A0 (841mm x 1189mm)।


### A1 {#A1}
```
public static final PaperSize A1
```


मानक कागज़ का आकार A1 (594mm x 841mm)।


### A2 {#A2}
```
public static final PaperSize A2
```


मानक कागज़ का आकार A2 (420mm x 594mm)।


### A3 {#A3}
```
public static final PaperSize A3
```


मानक कागज़ का आकार A3 (297mm x 420mm)।


### A4 {#A4}
```
public static final PaperSize A4
```


मानक कागज़ का आकार A4 (210mm x 297mm)।


### A5 {#A5}
```
public static final PaperSize A5
```


मानक कागज़ का आकार A5 (148mm x 210mm)।


### A6 {#A6}
```
public static final PaperSize A6
```


मानक कागज़ का आकार A6 (105mm x 148mm)।


### A7 {#A7}
```
public static final PaperSize A7
```


मानक कागज़ का आकार A7 (74mm x 105mm)।


### A8 {#A8}
```
public static final PaperSize A8
```


मानक कागज़ का आकार A8 (52mm x 74mm)।


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


PaperSize की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | यह PaperSize की स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PaperSize की स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

