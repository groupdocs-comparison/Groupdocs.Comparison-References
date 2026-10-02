---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "क्लास के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

[Comparer](../../com.groupdocs.comparison/comparer) क्लास के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | ComparerSettings क्लास का नया उदाहरण बनाता है। |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | ComparerSettings क्लास का नया उदाहरण बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getLogger()](#getLogger--) | लॉगिंग के लिए उपयोग किए जाने वाले लॉगर कार्यान्वयन को प्राप्त करता है। |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | लॉगिंग के लिए लॉगर कार्यान्वयन को सेट करता है। |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


ComparerSettings क्लास का नया उदाहरण बनाता है।


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


ComparerSettings क्लास का नया उदाहरण बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | उपयोग करने के लिए लॉगर |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


लॉगिंग के लिए उपयोग किए जाने वाले लॉगर कार्यान्वयन को प्राप्त करता है।


**Returns:**
com.groupdocs.foundation.logging.ILogger - लॉगर

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


लॉगिंग के लिए लॉगर कार्यान्वयन को सेट करता है।


लॉगिंग को निष्क्रिय करने के लिए com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER का उपयोग करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | com.groupdocs.foundation.logging.ILogger | सेट करने के लिए लॉगर कार्यान्वयन |
|

