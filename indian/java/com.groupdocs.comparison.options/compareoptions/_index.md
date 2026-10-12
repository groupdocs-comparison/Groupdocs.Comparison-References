---
title: "CompareOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ तुलना प्रक्रिया को कॉन्फ़िगर करने की अनुमति देता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

दस्तावेज़ तुलना प्रक्रिया को कॉन्फ़िगर करने की अनुमति देता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | CompareOptions क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | विभिन्न शैलियों के लिए सेटिंग्स के साथ CompareOptions क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | समानता के आधार पर परिवर्तन को अनदेखा करने के लिए सेटिंग्स प्राप्त करें। |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | समानता के आधार पर परिवर्तन को अनदेखा करने के लिए सेटिंग्स सेट करता है। |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | डायग्राम के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ प्राप्त करता है। |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | डायग्राम के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ सेट करता है। |
|
|  | [getComparisonType()](#getComparisonType--) | स्रोत और लक्ष्य दस्तावेज़ों के प्रकार को [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ऑब्जेक्ट के रूप में प्राप्त करता है ताकि Comparison को पता चल सके कि उन्हें कैसे तुलना करना है। |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | स्रोत और लक्ष्य दस्तावेज़ों के प्रकार को [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ऑब्जेक्ट के रूप में सेट करता है ताकि Comparison को पता चल सके कि उन्हें कैसे तुलना करना है। |
|
|  | [getPaperSize()](#getPaperSize--) | परिणाम दस्तावेज़ में कागज का आकार [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) ऑब्जेक्ट के रूप में प्राप्त करता है। |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | परिणाम दस्तावेज़ में कागज का आकार [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) ऑब्जेक्ट के रूप में सेट करता है। |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | गणना निर्देशांक मोड को [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) ऑब्जेक्ट के रूप में प्राप्त करता है। |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | गणना निर्देशांक मोड को [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) ऑब्जेक्ट के रूप में सेट करता है। |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | एक फ़्लैग प्राप्त करता है जो दर्शाता है कि परिणाम दस्तावेज़ में हटाए गए घटकों को दिखाना है या नहीं। |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | एक फ़्लैग सेट करता है जो दर्शाता है कि परिणाम दस्तावेज़ में हटाए गए घटकों को दिखाना है या नहीं। |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में सम्मिलित घटकों को दिखाया जाए या नहीं। |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में सम्मिलित घटकों को दिखाया जाए या नहीं। |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में पता लगाए गए परिवर्तन सांख्यिकी के साथ सारांश पृष्ठ जोड़ा जाए या नहीं। |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में पता लगाए गए परिवर्तन सांख्यिकी के साथ सारांश पृष्ठ जोड़ा जाए या नहीं। |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि सारांश पृष्ठ में विस्तारित फ़ाइल तुलना जानकारी जोड़ी जाए या नहीं। |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि सारांश पृष्ठ में विस्तारित फ़ाइल तुलना जानकारी जोड़ी जाए या नहीं। |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि परिणामस्वरूप दस्तावेज़ में केवल पता लगाए गए परिवर्तनों के सांख्यिकी वाला पृष्ठ छोड़ा जाए या नहीं। |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि परिणामस्वरूप दस्तावेज़ में केवल पता लगाए गए परिवर्तनों के सांख्यिकी वाला पृष्ठ छोड़ा जाए या नहीं। |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि शैली परिवर्तन का पता लगाया जाए या नहीं। |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि शैली परिवर्तन का पता लगाया जाए या नहीं। |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि हटाए गए या सम्मिलित तत्वों के बच्चों को हटाए गए या सम्मिलित के रूप में चिह्नित किया जाए। |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि हटाए गए या सम्मिलित तत्वों के बच्चों को हटाए गए या सम्मिलित के रूप में चिह्नित किया जाए। |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि बदले गए घटकों के लिए निर्देशांक गणना किए जाएँ। |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि बदले गए घटकों के लिए निर्देशांक गणना किए जाएँ। |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि हेडर/फ़ूटर सामग्री की तुलना की जाए। |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि हेडर/फ़ूटर सामग्री की तुलना की जाए। |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | एक तुलना विवरण स्तर प्राप्त करता है जो [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) के रूप में दर्शाया गया है। |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | एक तुलना विवरण स्तर सेट करता है जो [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) के रूप में दर्शाया गया है। |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि वर्ड प्रोसेसिंग में आकारों के लिए और इमेज दस्तावेज़ों में आयतों के लिए फ्रेम उपयोग किए जाएँगे। |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | एक फ़्लैग सेट करता है जो यह दर्शाता है कि वर्ड प्रोसेसिंग में आकारों के लिए और इमेज दस्तावेज़ों में आयतों के लिए फ्रेम उपयोग किए जाएँगे। |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | एक शैली सेटिंग प्राप्त करता है जो सम्मिलित आइटमों पर लागू होगी। |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | एक शैली सेटिंग सेट करता है जो सम्मिलित आइटमों पर लागू होगी। |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | एक शैली सेटिंग प्राप्त करता है जो हटाए गए आइटमों पर लागू होगी। |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | एक शैली सेटिंग सेट करता है जो हटाए गए आइटमों पर लागू होगी। |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | एक शैली सेटिंग प्राप्त करता है जो बदले गए आइटमों पर लागू होगी। |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | बदलाव किए गए आइटमों पर लागू होने वाली शैली सेटिंग्स निर्धारित करता है। |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | तुलना की संवेदनशीलता प्राप्त करता है। |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | तुलना की संवेदनशीलता निर्धारित करता है। |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | टेबलों के लिए तुलना की संवेदनशीलता निर्धारित करता है। |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | टेबलों के लिए तुलना की संवेदनशीलता प्राप्त करें। |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | पाठ को शब्दों में विभाजित करने के लिए उपयोग किए जाने वाले विभाजकों की एक सरणी निर्धारित करता है। |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) ऑब्जेक्ट द्वारा दर्शाए गए पासवर्ड सहेजने विकल्प को प्राप्त करता है। |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) ऑब्जेक्ट द्वारा दर्शाए गए पासवर्ड सहेजने विकल्प को निर्धारित करता है। |
|
|  | [getOriginalSize()](#getOriginalSize--) | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) ऑब्जेक्ट द्वारा दर्शाए गए तुलना किए गए दस्तावेज़ों के मूल आकार को प्राप्त करता है। |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) ऑब्जेक्ट द्वारा दर्शाए गए तुलना किए गए दस्तावेज़ों के मूल आकार को निर्धारित करता है। |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) ऑब्जेक्ट द्वारा दर्शाए गए डायग्राम दस्तावेज़ों के मास्टर पेज की सेटिंग को प्राप्त करता है। |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) ऑब्जेक्ट द्वारा दर्शाए गए डायग्राम दस्तावेज़ों के मास्टर पेज की सेटिंग को निर्धारित करता है। |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | एक फ़्लैग लौटाता है जो दर्शाता है कि डायरेक्टरी तुलना सक्षम है या नहीं। |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | एक फ़्लैग निर्धारित करता है जो दर्शाता है कि डायरेक्टरी तुलना सक्षम की जानी चाहिए या नहीं। |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | एक बूलियन मान लौटाता है जो दर्शाता है कि केवल बदलें हुए आइटम दिखाए जाने चाहिए या नहीं। |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | एक मान निर्धारित करता है जो दर्शाता है कि केवल बदलें हुए आइटम दिखाए जाने चाहिए या नहीं। |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | परिणामी फ़ोल्डर तुलना फ़ाइल का फ़ॉर्मेट प्राप्त करता है। |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | परिणामी फ़ोल्डर तुलना फ़ाइल का फ़ॉर्मेट निर्धारित करता है। |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


CompareOptions क्लास का एक नया उदाहरण प्रारंभ करता है।


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


विभिन्न शैलियों के लिए सेटिंग्स के साथ CompareOptions क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | डाली गई वस्तुओं के लिए शैली सेटिंग्स |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | हटाई गई वस्तुओं के लिए शैली सेटिंग्स |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | बदले हुए शैली वस्तुओं के लिए शैली सेटिंग्स |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


समानता के आधार पर परिवर्तन को अनदेखा करने के लिए सेटिंग्स प्राप्त करें।


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - परिवर्तनों को अनदेखा करने के लिए सेटिंग्स।

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


समानता के आधार पर परिवर्तन को अनदेखा करने के लिए सेटिंग्स सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | परिवर्तनों को अनदेखा करने के लिए सेटिंग्स। |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


डायग्राम के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ प्राप्त करता है।


**Returns:**
java.lang.String - Diagrams के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ।

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


डायग्राम के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Diagrams के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ। |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


स्रोत और लक्ष्य दस्तावेज़ों के प्रकार को [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ऑब्जेक्ट के रूप में प्राप्त करता है ताकि Comparison को पता चल सके कि उन्हें कैसे तुलना करना है।
जब यह विकल्प सेट किया जाता है, [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) विकल्प को छोड़ दिया जाएगा।


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


स्रोत और लक्ष्य दस्तावेज़ों के प्रकार को [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) ऑब्जेक्ट के रूप में सेट करता है ताकि Comparison को पता चल सके कि उन्हें कैसे तुलना करना है।
जब यह विकल्प सेट किया जाता है, [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) विकल्प को छोड़ दिया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | स्रोत और लक्ष्य दस्तावेज़ों का प्रकार |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


परिणाम दस्तावेज़ में कागज का आकार [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) ऑब्जेक्ट के रूप में प्राप्त करता है।


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


परिणाम दस्तावेज़ में कागज का आकार [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) ऑब्जेक्ट के रूप में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | परिणाम दस्तावेज़ में कागज़ का आकार |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


गणना निर्देशांक मोड को [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) ऑब्जेक्ट के रूप में प्राप्त करता है।


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


गणना निर्देशांक मोड को [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) ऑब्जेक्ट के रूप में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | निर्देशांक गणना मोड |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


एक फ़्लैग प्राप्त करता है जो दर्शाता है कि परिणाम दस्तावेज़ में हटाए गए घटकों को दिखाना है या नहीं।


**Returns:**
boolean - true यदि परिणाम दस्तावेज़ में हटाए गए घटक दिखाए जाएंगे, अन्यथा false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


एक फ़्लैग सेट करता है जो दर्शाता है कि परिणाम दस्तावेज़ में हटाए गए घटकों को दिखाना है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि परिणाम दस्तावेज़ में हटाए गए घटक दिखाए जाने चाहिए, अन्यथा false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में सम्मिलित घटकों को दिखाया जाए या नहीं।


**Returns:**
boolean - true यदि परिणाम दस्तावेज़ में सम्मिलित घटक दिखाए जाने चाहिए, अन्यथा false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में सम्मिलित घटकों को दिखाया जाए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि परिणाम दस्तावेज़ में सम्मिलित घटक दिखाए जाने चाहिए, अन्यथा false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में पता लगाए गए परिवर्तन सांख्यिकी के साथ सारांश पृष्ठ जोड़ा जाए या नहीं।


**Returns:**
boolean - true यदि सारांश पृष्ठ जोड़ा जाएगा, अन्यथा false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि परिणामी दस्तावेज़ में पता लगाए गए परिवर्तन सांख्यिकी के साथ सारांश पृष्ठ जोड़ा जाए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि सारांश पृष्ठ जोड़ा जाना चाहिए, अन्यथा false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि सारांश पृष्ठ में विस्तारित फ़ाइल तुलना जानकारी जोड़ी जाए या नहीं।


**Returns:**
boolean - true यदि विस्तारित फ़ाइल तुलना जानकारी सारांश पृष्ठ में जोड़ी जाएगी, अन्यथा false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि सारांश पृष्ठ में विस्तारित फ़ाइल तुलना जानकारी जोड़ी जाए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि विस्तारित फ़ाइल तुलना जानकारी सारांश पृष्ठ में जोड़ी जानी चाहिए, अन्यथा false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि परिणामस्वरूप दस्तावेज़ में केवल पता लगाए गए परिवर्तनों के सांख्यिकी वाला पृष्ठ छोड़ा जाए या नहीं।


**Returns:**
boolean - true यदि परिणाम दस्तावेज़ में केवल पहचाने गए परिवर्तन की सांख्यिकी वाला पृष्ठ रहेगा, अन्यथा false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि परिणामस्वरूप दस्तावेज़ में केवल पता लगाए गए परिवर्तनों के सांख्यिकी वाला पृष्ठ छोड़ा जाए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि परिणाम दस्तावेज़ में केवल पहचाने गए परिवर्तन की सांख्यिकी वाला पृष्ठ रहना चाहिए, अन्यथा false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि शैली परिवर्तन का पता लगाया जाए या नहीं।


**Returns:**
boolean - true यदि शैली परिवर्तन का पता लगाया जाएगा, अन्यथा false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि शैली परिवर्तन का पता लगाया जाए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि शैली परिवर्तन का पता लगाया जाना चाहिए, अन्यथा false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि हटाए गए या सम्मिलित तत्वों के बच्चों को हटाए गए या सम्मिलित के रूप में चिह्नित किया जाए।


**Returns:**
boolean - true यदि हटाए या सम्मिलित तत्वों के बच्चों को हटाए या सम्मिलित के रूप में चिह्नित किया जाएगा, अन्यथा false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि हटाए गए या सम्मिलित तत्वों के बच्चों को हटाए गए या सम्मिलित के रूप में चिह्नित किया जाए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि हटाए या सम्मिलित तत्वों के बच्चों को हटाए या सम्मिलित के रूप में चिह्नित किया जाना चाहिए, अन्यथा false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि बदले गए घटकों के लिए निर्देशांक गणना किए जाएँ।


**Returns:**
boolean - true यदि बदलें घटकों के निर्देशांक की गणना की जाएगी, अन्यथा false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि बदले गए घटकों के लिए निर्देशांक गणना किए जाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि बदलें घटकों के निर्देशांक की गणना की जानी चाहिए, अन्यथा false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि हेडर/फ़ूटर सामग्री की तुलना की जाए।


**Returns:**
boolean - true यदि हेडर/फ़ूटर सामग्री की तुलना की जाएगी, अन्यथा false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि हेडर/फ़ूटर सामग्री की तुलना की जाए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि हेडर/फ़ूटर सामग्री की तुलना की जानी चाहिए, अन्यथा false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


एक तुलना विवरण स्तर प्राप्त करता है जो [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) के रूप में दर्शाया गया है।
डिफ़ॉल्ट मान है [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW).


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


एक तुलना विवरण स्तर सेट करता है जो [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) के रूप में दर्शाया गया है।
डिफ़ॉल्ट मान है [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | तुलना विवरण का स्तर |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


एक फ़्लैग प्राप्त करता है जो यह दर्शाता है कि वर्ड प्रोसेसिंग में आकारों के लिए और इमेज दस्तावेज़ों में आयतों के लिए फ्रेम उपयोग किए जाएँगे।


**Returns:**
boolean - true यदि फ्रेम्स का उपयोग किया जाएगा, अन्यथा false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


एक फ़्लैग सेट करता है जो यह दर्शाता है कि वर्ड प्रोसेसिंग में आकारों के लिए और इमेज दस्तावेज़ों में आयतों के लिए फ्रेम उपयोग किए जाएँगे।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि फ्रेम्स का उपयोग किया जाना चाहिए, अन्यथा false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


एक शैली सेटिंग प्राप्त करता है जो सम्मिलित आइटमों पर लागू होगी।


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


एक शैली सेटिंग सेट करता है जो सम्मिलित आइटमों पर लागू होगी।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | डाले गए आइटम्स की शैली सेटिंग्स |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


एक शैली सेटिंग प्राप्त करता है जो हटाए गए आइटमों पर लागू होगी।


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


एक शैली सेटिंग सेट करता है जो हटाए गए आइटमों पर लागू होगी।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | हटाए गए आइटम्स की शैली सेटिंग्स |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


एक शैली सेटिंग प्राप्त करता है जो बदले गए आइटमों पर लागू होगी।


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


बदलाव किए गए आइटमों पर लागू होने वाली शैली सेटिंग्स निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | बदले गए आइटम्स की शैली सेटिंग्स |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


तुलना की संवेदनशीलता प्राप्त करता है।
दो तुलना किए गए वस्तुओं के सभी तत्वों के संबंध में हटाए और डाले गए तत्वों का प्रतिशत

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - तुलना की संवेदनशीलता

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


तुलना की संवेदनशीलता निर्धारित करता है।
दो तुलना किए गए वस्तुओं के सभी तत्वों के संबंध में हटाए और डाले गए तत्वों का प्रतिशत

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | तुलना की संवेदनशीलता |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


टेबलों के लिए तुलना की संवेदनशीलता निर्धारित करता है।
यदि मान null है, तो SensitivityOfComparison का उपयोग किया जाता है। दो तुलना किए गए वस्तुओं के सभी तत्वों के संबंध में हटाए और डाले गए तत्वों का प्रतिशत।

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Integer | टेबल्स के लिए तुलना की संवेदनशीलता |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


टेबलों के लिए तुलना की संवेदनशीलता प्राप्त करें।
यदि मान null है, तो SensitivityOfComparison का उपयोग किया जाता है। दो तुलना किए गए वस्तुओं के सभी तत्वों के संबंध में हटाए और डाले गए तत्वों का प्रतिशत।

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - टेबल्स के लिए तुलना की संवेदनशीलता

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


पाठ को शब्दों में विभाजित करने के लिए उपयोग किए जाने वाले विभाजकों की एक सरणी निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | char[] | पाठ को शब्दों में विभाजित करने के लिए विभाजकों की सरणी |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) ऑब्जेक्ट द्वारा दर्शाए गए पासवर्ड सहेजने विकल्प को प्राप्त करता है।


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) ऑब्जेक्ट द्वारा दर्शाए गए पासवर्ड सहेजने विकल्प को निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | पासवर्ड सहेजने का विकल्प |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


[OriginalSize](../../com.groupdocs.comparison.options/originalsize) ऑब्जेक्ट द्वारा दर्शाए गए तुलना किए गए दस्तावेज़ों के मूल आकार को प्राप्त करता है।


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


[OriginalSize](../../com.groupdocs.comparison.options/originalsize) ऑब्जेक्ट द्वारा दर्शाए गए तुलना किए गए दस्तावेज़ों के मूल आकार को निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | दस्तावेज़ों का मूल आकार |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) ऑब्जेक्ट द्वारा दर्शाए गए डायग्राम दस्तावेज़ों के मास्टर पेज की सेटिंग को प्राप्त करता है।


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) ऑब्जेक्ट द्वारा दर्शाए गए डायग्राम दस्तावेज़ों के मास्टर पेज की सेटिंग को निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | डायग्राम मास्टर पेज सेटिंग |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


एक फ़्लैग लौटाता है जो दर्शाता है कि डायरेक्टरी तुलना सक्षम है या नहीं।


**Returns:**
boolean - true यदि डायरेक्टरी तुलना सक्षम है, अन्यथा false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


एक फ़्लैग निर्धारित करता है जो दर्शाता है कि डायरेक्टरी तुलना सक्षम की जानी चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | directoryCompare | boolean | true यदि डायरेक्टरी तुलना सक्षम की जानी चाहिए, अन्यथा false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


एक बूलियन मान लौटाता है जो दर्शाता है कि केवल बदलें हुए आइटम दिखाए जाने चाहिए या नहीं।


**Returns:**
boolean - true यदि केवल बदले गए आइटम्स दिखाए जाने चाहिए, अन्यथा false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


एक मान निर्धारित करता है जो दर्शाता है कि केवल बदलें हुए आइटम दिखाए जाने चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | showOnlyChanged | boolean | केवल बदले गए आइटम्स दिखाए जाने चाहिए या नहीं, यह दर्शाने वाला boolean मान |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


परिणामी फ़ोल्डर तुलना फ़ाइल का फ़ॉर्मेट प्राप्त करता है।


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - परिणामस्वरूप फ़ोल्डर तुलना फ़ाइल के स्वरूप का प्रतिनिधित्व करने वाला FolderComparisonExtension

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


परिणामी फ़ोल्डर तुलना फ़ाइल का फ़ॉर्मेट निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | परिणामस्वरूप फ़ोल्डर तुलना फ़ाइल के स्वरूप का प्रतिनिधित्व करने वाला FolderComparisonExtension |
|

