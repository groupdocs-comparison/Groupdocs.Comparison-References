---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "Word दस्तावेज़ के विशिष्ट तुलना विकल्प। CompareOptions./compareoptions से सामान्य विकल्पों को विरासत में प्राप्त करता है।"
type: docs
weight: 440
url: /hi/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word दस्तावेज़ के विशिष्ट तुलना विकल्प। सामान्य विकल्पों को [`CompareOptions`](../compareoptions) से विरासत में प्राप्त करता है।

```csharp
public class WordCompareOptions : CompareOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | [`WordCompareOptions`](../wordcompareoptions) क्लास की एक नई instance को प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | यह दर्शाता है कि बदलें घटकों के लिए निर्देशांक की गणना करनी है या नहीं। |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | बदलें घटकों मोड के लिए निर्देशांक गणना को निर्दिष्ट करता है। |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | बदलें घटकों के लिए शैली का वर्णन करता है। |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | स्रोत और लक्ष्य दस्तावेज़ों में बुकमार्क की तुलना की जाती है और अंतर परिणाम में शामिल होते हैं, यह निर्धारित करने के लिए प्राप्त करता है या सेट करता है। |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | निर्मित और कस्टम दस्तावेज़ गुणों की तुलना की जाती है और अंतर परिणाम में शामिल होते हैं (जैसे गुण सारांश पृष्ठ पर), इसे प्राप्त करता है या सेट करता है। |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | दस्तावेज़ वैरिएबल गुणों (जैसे DOCVARIABLE फ़ील्ड) की तुलना की जाती है और अंतर परिणाम में शामिल होते हैं, इसे प्राप्त करता है या सेट करता है। |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | हटाए गए घटकों के लिए शैली का वर्णन करता है। |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | तुलना विवरण स्तर को प्राप्त करता है या सेट करता है। |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | यह संकेत करता है कि शैली परिवर्तन का पता लगाना है या नहीं। |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | मास्टर के पथ मान को प्राप्त करता है या सेट करता है या मास्टर के पथ के बिना तुलना का उपयोग करता है। यह विकल्प केवल डायग्राम के लिए है। |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | फ़ोल्डरों की तुलना को चालू करने के लिए नियंत्रण। |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | तुलना परिणामों को कैसे प्रदर्शित किया जाए, इसे प्राप्त करता है या सेट करता है: ट्रैक चेंजेज मोड (Revisions) में Word संशोधन के रूप में या दस्तावेज़ में सीधे रेंडर किए गए हाइलाइटेड परिवर्तन (Highlight) के रूप में। |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | यह संकेत करता है कि सारांश पृष्ठ में विस्तारित फ़ाइल तुलना जानकारी जोड़नी है या नहीं। |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | परिणामी फ़ोल्डर तुलना फ़ाइल के स्वरूप को प्राप्त करता है या सेट करता है। |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में पता लगाए गए परिवर्तन सांख्यिकी के साथ सारांश पृष्ठ जोड़ना है या नहीं। |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | हेडर/फ़ूटर सामग्री की तुलना को चालू करने के लिए नियंत्रण। |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | समानता के आधार पर परिवर्तन को अनदेखा करने की सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | डाले गए घटकों के लिए शैली का वर्णन करता है। |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | डाले या हटाए गए सामग्री की जगह खाली पंक्तियों को छोड़ना है या नहीं, ताकि लेआउट और पंक्ति गिनती बनी रहे; इसे [`ShowInsertedContent`](../compareoptions/showinsertedcontent) और [`ShowDeletedContent`](../compareoptions/showdeletedcontent) के साथ उपयोग किया जाता है। |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | यह संकेत करता है कि वर्ड प्रोसेसिंग में आकारों के लिए फ्रेम और इमेज दस्तावेज़ों में आयतों के लिए फ्रेम का उपयोग करना है या नहीं। |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | दस्तावेज़ों के बीच अलग-अलग पैराग्राफ (लाइन) ब्रेक को परिणाम में दृश्य रूप से चिह्नित करना है या नहीं, इसे प्राप्त करता है या सेट करता है। |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | हटाए या डाले गए तत्व के बच्चों को हटाए या डाले के रूप में चिह्नित करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | तुलना किए गए दस्तावेज़ों के मूल आकार को प्राप्त करता है या सेट करता है। |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | परिणाम दस्तावेज़ के कागज़ आकार को प्राप्त करता है या सेट करता है। |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | पासवर्ड सहेजने विकल्प को प्राप्त करता है या सेट करता है। |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | !:WordTrackChanges सक्षम होने पर संशोधनों के लिए उपयोग किए जाने वाले लेखक नाम को प्राप्त करता है या सेट करता है। यदि सेट किया गया है, तो यह नाम परिणाम दस्तावेज़ में संशोधन मार्कअप पर लागू होता है। |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | तुलना की संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | टेबलों के लिए तुलना की संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में हटाए गए घटकों को दिखाना है या नहीं। |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में डाले गए घटकों को दिखाना है या नहीं। |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | केवल बदले हुए आइटमों को प्रदर्शित करने के लिए नियंत्रण। |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में केवल पता लगाए गए परिवर्तनों के आँकड़े वाला पृष्ठ छोड़ना है या नहीं। |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | परिणाम दस्तावेज़ में संशोधन मार्कअप को दृश्यमान रखने के लिए प्राप्त करता है या सेट करता है। यदि false हो, तो सभी संशोधन स्वीकार कर लिए जाते हैं और परिणाम अंतिम पाठ के रूप में दिखता है। यह सेटिंग केवल तब अर्थपूर्ण होती है जब [`DisplayMode`](./displaymode) को Highlight पर सेट किया गया हो। डिफ़ॉल्ट मान true है। |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | डायग्राम के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ। |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | पाठ को शब्दों में विभाजित करने के लिए डिलिमिटर की एक सरणी प्राप्त करता है या सेट करता है। |

### साथ ही देखें

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
