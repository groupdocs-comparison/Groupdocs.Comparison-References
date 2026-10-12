---
title: "Comparer"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Comparer क्लास दस्तावेज़ों की तुलना करने और तुलना परिणाम उत्पन्न करने की कार्यक्षमता प्रदान करती है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Comparer क्लास दस्तावेज़ों की तुलना करने और तुलना परिणाम उत्पन्न करने की कार्यक्षमता प्रदान करती है।


यह आपको विभिन्न प्रकार के दस्तावेज़, जैसे PDF, Word, Excel, PowerPoint, आदि की तुलना करने की अनुमति देता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | निर्दिष्ट स्रोत फ़ाइल पथ के साथ Comparer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ोल्डर पथ और तुलना विकल्पों के साथ Comparer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | निर्दिष्ट स्रोत फ़ाइल पथ के साथ Comparer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट स्रोत फ़ाइल पथ और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट स्रोत फ़ाइल पथ और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट स्रोत फ़ाइल पथ और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट स्रोत फ़ाइल पथ और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट स्रोत फ़ाइल पथ और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | निर्दिष्ट स्रोत दस्तावेज़ स्ट्रीम के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट स्रोत दस्तावेज़ स्ट्रीम और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट स्रोत दस्तावेज़ स्ट्रीम और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट दस्तावेज़ स्ट्रीम, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | निर्दिष्ट [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है। |
|
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSource()](#getSource--) | उस स्रोत दस्तावेज़ को प्राप्त करता है जिसे तुलना किया जा रहा है। |
|
|  | [getTargets()](#getTargets--) | स्रोत फ़ाइल के साथ तुलना करने के लिए लक्ष्य दस्तावेज़ों की सूची। |
|
|  | [compare()](#compare--) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ डिफ़ॉल्ट विकल्पों के साथ परिणाम सहेजे बिना तुलना करता है। |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम उत्पन्न करता है। |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम उत्पन्न करता है। |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को आउटपुट स्ट्रीम में लिखता है। |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को आउटपुट स्ट्रीम में लिखता है। |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ परिणाम सहेजे बिना तुलना करता है। |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ परिणाम सहेजे बिना तुलना करता है। |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए आउटपुट स्ट्रीम में लिखता है। |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट डायरेक्टरी को लक्ष्य डायरेक्टरी के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर सहेजता है। |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट डायरेक्टरी को लक्ष्य डायरेक्टरी के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर सहेजता है। |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है। |
|
|  | [add(String filePath)](#add-java.lang.String-) | निर्दिष्ट लक्ष्य दस्तावेज़ को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट लक्ष्य दस्तावेज़ या फ़ोल्डर को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | निर्दिष्ट लक्ष्य दस्तावेज़ को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | निर्दिष्ट लक्ष्य दस्तावेज़ों को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | निर्दिष्ट लक्ष्य दस्तावेज़ों को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | निर्दिष्ट लक्ष्य दस्तावेज़ को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | निर्दिष्ट लक्ष्य दस्तावेज़ों को तुलना प्रक्रिया में जोड़ता है। |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है। |
|
|  | [getChanges()](#getChanges--) | तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की एक एरे प्राप्त करता है। |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की एक एरे प्राप्त करता है। |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणाम दस्तावेज़ पर लागू करता है। |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
|
|  | [getResultString()](#getResultString--) | तुलना के बाद परिणाम स्ट्रिंग प्राप्त करता है (केवल टेक्स्ट तुलना के लिए)। |
|
|  | [getSourceFolder()](#getSourceFolder--) | उस स्रोत फ़ोल्डर को लौटाता है जिसे तुलना किया जा रहा है। |
|
|  | [getTargetFolder()](#getTargetFolder--) | तुलना किए जा रहे लक्ष्य फ़ोल्डर को लौटाता है। |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | स्व-तुलना जाँच (e498c23)। |
|
|  | [close()](#close--) | संसाधनों को मुक्त करता है। |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


निर्दिष्ट स्रोत फ़ाइल पथ के साथ Comparer क्लास का नया इंस्टेंस प्रारंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का पथ |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


निर्दिष्ट फ़ोल्डर पथ और तुलना विकल्पों के साथ Comparer क्लास का नया इंस्टेंस प्रारंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ या फ़ोल्डर का पथ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | फ़ोल्डर तुलना के लिए तुलना विकल्प |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


निर्दिष्ट स्रोत फ़ाइल पथ के साथ Comparer क्लास का नया इंस्टेंस प्रारंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | स्रोत दस्तावेज़ का पथ |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


निर्दिष्ट स्रोत फ़ाइल पथ और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया इंस्टेंस प्रारंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


निर्दिष्ट स्रोत फ़ाइल पथ और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया इंस्टेंस प्रारंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | स्रोत दस्तावेज़ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


निर्दिष्ट स्रोत फ़ाइल पथ और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया इंस्टेंस प्रारंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | स्रोत दस्तावेज़ का पथ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | फ़ोल्डर तुलना के लिए तुलना विकल्प |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़, फ़ोल्डर या तुलना किए जाने वाले पाठ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | फ़ोल्डर तुलना के लिए तुलना विकल्प |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


निर्दिष्ट स्रोत फ़ाइल पथ और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का पथ |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


निर्दिष्ट स्रोत फ़ाइल पथ और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | स्रोत दस्तावेज़ का पथ |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | स्रोत दस्तावेज़ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


निर्दिष्ट स्रोत फ़ाइल पथ, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | स्रोत दस्तावेज़ या फ़ोल्डर का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | फ़ोल्डर तुलना के लिए तुलना विकल्प |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


निर्दिष्ट स्रोत दस्तावेज़ स्ट्रीम के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | स्रोत दस्तावेज़ का इनपुट स्ट्रीम |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


निर्दिष्ट स्रोत दस्तावेज़ स्ट्रीम और [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) के साथ Comparer का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | स्रोत दस्तावेज़ का इनपुट स्ट्रीम |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


निर्दिष्ट स्रोत दस्तावेज़ स्ट्रीम और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | स्रोत दस्तावेज़ का इनपुट स्ट्रीम |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


निर्दिष्ट दस्तावेज़ स्ट्रीम, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) और [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | तुलना किए जाने वाले दस्तावेज़ के डेटा वाला स्ट्रीम |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना सेटिंग्स |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


निर्दिष्ट [ComparerSettings](../../com.groupdocs.comparison/comparersettings) के साथ Comparer क्लास का नया उदाहरण आरंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | सेटिंग्स |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


उस स्रोत दस्तावेज़ को प्राप्त करता है जिसे तुलना किया जा रहा है।


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


स्रोत फ़ाइल के साथ तुलना करने के लिए लक्ष्य दस्तावेज़ों की सूची।


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - लक्ष्य दस्तावेज़

### compare() {#compare--}
```
public final Path compare()
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ डिफ़ॉल्ट विकल्पों के साथ परिणाम सहेजे बिना तुलना करता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - परिणाम दस्तावेज़ का पथ या null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम उत्पन्न करता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम दस्तावेज़ पथ |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ या null। कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम उत्पन्न करता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम दस्तावेज़ पथ |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को आउटपुट स्ट्रीम में लिखता है।


नोट: जब रिटर्न वैल्यू null हो, तो outputStream में लिखे गए डेटा का उपयोग करें

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | परिणाम दस्तावेज़ स्ट्रीम |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ या null जब outputStream से डेटा उपयोग करना आवश्यक हो। कुछ स्थितियों में परिणाम फ़ाइल का एक्सटेंशन बदला जा सकता है

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को आउटपुट स्ट्रीम में लिखता है।


नोट: यदि रिटर्न वैल्यू null है, तो outputStream में लिखे गए डेटा का उपयोग करें।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.OutputStream | परिणाम दस्तावेज़ स्ट्रीम |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ या null जब outputStream से डेटा उपयोग करना आवश्यक हो। कुछ स्थितियों में परिणाम फ़ाइल का एक्सटेंशन बदला जा सकता है

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ परिणाम सहेजे बिना तुलना करता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | सेव विकल्प |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम दस्तावेज़ का पथ या null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | सेव विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | सेव विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।


नोट: यदि रिटर्न वैल्यू null है, तो outputStream में लिखे गए डेटा का उपयोग करें

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.OutputStream | परिणाम दस्तावेज़ स्ट्रीम |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | सेव विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ या null जब outputStream से डेटा उपयोग करना आवश्यक हो। कुछ स्थितियों में परिणाम फ़ाइल का एक्सटेंशन बदला जा सकता है

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ परिणाम सहेजे बिना तुलना करता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल का पथ या null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए आउटपुट स्ट्रीम में लिखता है।


नोट: यदि रिटर्न वैल्यू null है, तो outputStream में लिखे गए डेटा का उपयोग करें

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | परिणाम दस्तावेज़ स्ट्रीम |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | परिणाम दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले सहेजने विकल्प |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ या null जब outputStream से डेटा उपयोग करना आवश्यक हो। कुछ स्थितियों में परिणाम फ़ाइल का एक्सटेंशन बदला जा सकता है

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | परिणाम दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले सहेजने विकल्प |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


निर्दिष्ट डायरेक्टरी को लक्ष्य डायरेक्टरी के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर सहेजता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल पथ जहाँ तुलना परिणाम सहेजा जाएगा। |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | डायरेक्टरी तुलना प्रक्रिया के लिए उपयोग किए जाने वाले विकल्प। |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


निर्दिष्ट डायरेक्टरी को लक्ष्य डायरेक्टरी के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर सहेजता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | फ़ाइल पथ जहाँ तुलना परिणाम सहेजा जाएगा। |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | डायरेक्टरी तुलना प्रक्रिया के लिए उपयोग किए जाने वाले विकल्प। |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


निर्दिष्ट फ़ाइल को लक्ष्य दस्तावेज़ों के साथ तुलना करता है और तुलना परिणाम को प्रदान किए गए फ़ाइल पथ पर लिखता है।

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | परिणाम दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले सहेजने विकल्प |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना प्रक्रिया के लिए उपयोग किए जाने वाले तुलना विकल्प |
|

**Returns:**
java.nio.file.Path - परिणाम फ़ाइल पथ, कुछ स्थितियों में इसका एक्सटेंशन बदला जा सकता है

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को तुलना प्रक्रिया में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | जोड़ने के लिए लक्ष्य दस्तावेज़ का पथ |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


निर्दिष्ट लक्ष्य दस्तावेज़ या फ़ोल्डर को तुलना प्रक्रिया में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | जोड़ने के लिए लक्ष्य दस्तावेज़ या फ़ोल्डर का पथ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना के विकल्प |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को तुलना प्रक्रिया में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | जोड़ने के लिए लक्ष्य दस्तावेज़ का पथ |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


निर्दिष्ट लक्ष्य दस्तावेज़ों को तुलना प्रक्रिया में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | जोड़ने के लिए लक्ष्य दस्तावेज़ों के पथ |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


निर्दिष्ट लक्ष्य दस्तावेज़ों को तुलना प्रक्रिया में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | जोड़ने के लिए लक्ष्य दस्तावेज़ों के पथ |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है।

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | जोड़ने के लिए लक्ष्य दस्तावेज़ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है।

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | जोड़ने के लिए लक्ष्य दस्तावेज़ का पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है।

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | जोड़ने के लिए लक्ष्य दस्तावेज़ या फ़ोल्डर का पथ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | तुलना के विकल्प |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को तुलना प्रक्रिया में जोड़ता है।

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | तुलना किए जाने वाले दस्तावेज़ के डेटा वाला स्ट्रीम |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


निर्दिष्ट लक्ष्य दस्तावेज़ों को तुलना प्रक्रिया में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream[] | तुलना किए जाने वाले दस्तावेज़ों के डेटा वाले स्ट्रीम |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


निर्दिष्ट लक्ष्य दस्तावेज़ को लोडिंग विकल्पों के साथ तुलना प्रक्रिया में जोड़ता है।

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | तुलना किए जाने वाले दस्तावेज़ के डेटा वाला स्ट्रीम |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | दस्तावेज़ पर लागू करने के लिए कस्टम लोड विकल्प |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की एक एरे प्राप्त करता है।


इस विधि का उपयोग स्रोत दस्तावेज़ और लक्ष्य दस्तावेज़(ओं) के बीच हुए परिवर्तनों के बारे में विस्तृत जानकारी प्राप्त करने के लिए करें।
प्रत्येक [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट में परिवर्तन प्रकार, प्रभावित क्षेत्र आदि जैसी जानकारी होती है,
और परिवर्तन से पहले और बाद की सामग्री।

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की एक array

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की एक एरे प्राप्त करता है।


इस विधि का उपयोग स्रोत दस्तावेज़ और लक्ष्य दस्तावेज़(ओं) के बीच हुए परिवर्तनों के बारे में विस्तृत जानकारी प्राप्त करने के लिए करें।
प्रत्येक [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट में परिवर्तन प्रकार, प्रभावित क्षेत्र आदि जैसी जानकारी होती है,
और परिवर्तन से पहले और बाद की सामग्री।


पैरामीटर [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) विभिन्न तरीके से परिवर्तनों को फ़िल्टर करने की अनुमति देता है।

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | वह ऑब्जेक्ट जो परिवर्तनों को फ़िल्टर करने की अनुमति देता है |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की एक array

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणाम दस्तावेज़ पर लागू करता है।

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | परिवर्तनों को लागू करने की प्रक्रिया को कॉन्फ़िगर करने के लिए कस्टम लागू परिवर्तन विकल्प |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है।

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | परिवर्तनों को लागू करने की प्रक्रिया को कॉन्फ़िगर करने के लिए कस्टम लागू परिवर्तन विकल्प |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है।

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | परिणाम दस्तावेज़ आउटपुट स्ट्रीम |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | परिवर्तनों को लागू करने की प्रक्रिया को कॉन्फ़िगर करने के लिए कस्टम लागू परिवर्तन विकल्प |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है।

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | परिणाम दस्तावेज़ को सहेजने को कॉन्फ़िगर करने के लिए सहेजने विकल्प |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | परिवर्तनों को लागू करने की प्रक्रिया को कॉन्फ़िगर करने के लिए कस्टम लागू परिवर्तन विकल्प |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है।

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम दस्तावेज़ फ़ाइल पथ |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | परिणाम दस्तावेज़ को सहेजने को कॉन्फ़िगर करने के लिए सहेजने विकल्प |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | परिवर्तनों को लागू करने की प्रक्रिया को कॉन्फ़िगर करने के लिए कस्टम लागू परिवर्तन विकल्प |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है।

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | परिणाम दस्तावेज़ आउटपुट स्ट्रीम |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | परिणाम दस्तावेज़ को सहेजने को कॉन्फ़िगर करने के लिए सहेजने विकल्प |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | परिवर्तनों को लागू करने की प्रक्रिया को कॉन्फ़िगर करने के लिए कस्टम लागू परिवर्तन विकल्प |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


तुलना के बाद परिणाम स्ट्रिंग प्राप्त करता है (केवल टेक्स्ट तुलना के लिए)।


**Returns:**
java.lang.String - परिणाम स्ट्रिंग

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


उस स्रोत फ़ोल्डर को लौटाता है जिसे तुलना किया जा रहा है।


**Returns:**
java.lang.String - स्रोत फ़ोल्डर

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


तुलना किए जा रहे लक्ष्य फ़ोल्डर को लौटाता है।


**Returns:**
java.lang.String - लक्ष्य फ़ोल्डर

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


स्व-तुलना जांच (e498c23). C# 7a7668c internal; सार्वजनिक रखा गया ताकि core.common परीक्षण कॉल कर सकें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


संसाधनों को मुक्त करता है।


