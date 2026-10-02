---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "डायग्राम मास्टर तुलना के लिए सेटिंग्स को दर्शाता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

डायग्राम मास्टर तुलना के लिए सेटिंग्स को दर्शाता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | DiagramMasterSetting क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि स्रोत मास्टर पाथ उपयोग किया जाएगा। |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि स्रोत मास्टर पाथ उपयोग किया जाना चाहिए। |
|
|  | [getMasterPath()](#getMasterPath--) | दस्तावेज़ों को रेंडर करने के लिए उपयोग किया जाने वाला मास्टर पाथ प्राप्त करता है। |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | दस्तावेज़ों को रेंडर करने के लिए उपयोग किया जाना चाहिए ऐसा मास्टर पाथ सेट करता है। |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


DiagramMasterSetting क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि स्रोत मास्टर पाथ उपयोग किया जाएगा।


**Returns:**
boolean - यदि स्रोत मास्टर पाथ दिखाया जाएगा तो true, अन्यथा false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि स्रोत मास्टर पाथ उपयोग किया जाना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि स्रोत मास्टर पाथ दिखाया जाना चाहिए तो true, अन्यथा false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


दस्तावेज़ों को रेंडर करने के लिए उपयोग किया जाने वाला मास्टर पाथ प्राप्त करता है। परिणाम दस्तावेज़ बनाने के लिए डिफ़ॉल्ट शैप्स के सेट से MasterPath आवश्यक है।


**Returns:**
java.lang.String - यदि सेट किया गया हो तो मास्टर दस्तावेज़ का पाथ, अन्यथा डिफ़ॉल्ट मास्टर पाथ

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


दस्तावेज़ों को रेंडर करने के लिए उपयोग किया जाना चाहिए ऐसा मास्टर पाथ सेट करता है। परिणाम दस्तावेज़ बनाने के लिए डिफ़ॉल्ट शैप्स के सेट से MasterPath आवश्यक है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | यदि सेट किया गया हो तो मास्टर दस्तावेज़ का पाथ, अन्यथा डिफ़ॉल्ट मास्टर पाथ |
|

