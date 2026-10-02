---
title: "MemoryCleaner"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "विभिन्न संसाधनों को साफ़ करता है ताकि मेमोरी मुक्त हो सके।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.common/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

विभिन्न संसाधनों को साफ़ करता है ताकि मेमोरी मुक्त हो सके।


यह क्लास हीप मेमोरी को साफ करने, टेम्प फ़ाइलों को हटाने और फ़ॉन्ट रजिस्ट्री जानकारी को साफ करने के लिए मेथड्स प्रदान करती है।
यह वर्तमान थ्रेड के लिए थ्रेड-लोकल इंस्टेंसेस को सुरक्षित रूप से साफ करने के लिए एक मेथड भी शामिल करती है।


उदाहरण उपयोग:

````

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | स्थैतिक PDF इंस्टेंसेस (static और threadLocal) से हीप मेमोरी को साफ करता है और सभी टेम्प फ़ाइलों को हटाता है। |
|
|  | [clear()](#clear--) | स्थैतिक PDF इंस्टेंसेस (static और threadLocal) से हीप मेमोरी को साफ करता है और सभी टेम्प फ़ाइलों को हटाता है। |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | स्थैतिक PDF इंस्टेंसेस से हीप मेमोरी को साफ करता है। |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | सिस्टम टेम्प डायरेक्टरी में GroupDocs.Comparison द्वारा बनाई गई टेम्प फ़ाइलों को साफ करता है। |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | हीप मेमोरी से फ़ॉन्ट रजिस्ट्री जानकारी को साफ करता है। |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | वर्तमान थ्रेड के लिए थ्रेड-लोकल इंस्टेंसेस से हीप मेमोरी को सुरक्षित रूप से साफ करता है। |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


स्थैतिक PDF इंस्टेंसेस (static और threadLocal) से हीप मेमोरी को साफ करता है और सभी टेम्प फ़ाइलों को हटाता है।
यह विधि फ़ॉन्ट सेटिंग्स को प्रभावित नहीं करती है।


### clear() {#clear--}
```
public static void clear()
```


स्थैतिक PDF इंस्टेंसेस (static और threadLocal) से हीप मेमोरी को साफ करता है और सभी टेम्प फ़ाइलों को हटाता है।


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


स्थैतिक PDF इंस्टेंसेस से हीप मेमोरी को साफ करता है।


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


सिस्टम टेम्प डायरेक्टरी में GroupDocs.Comparison द्वारा बनाई गई टेम्प फ़ाइलों को साफ करता है।


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


हीप मेमोरी से फ़ॉन्ट रजिस्ट्री जानकारी को साफ करता है।


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


वर्तमान थ्रेड के लिए थ्रेड-लोकल इंस्टेंसेस से हीप मेमोरी को सुरक्षित रूप से साफ करता है।


