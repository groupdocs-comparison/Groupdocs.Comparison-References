---
title: "PdfCompareOptions"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "PDF दस्तावेज़ के विशिष्ट तुलना विकल्प। सामान्य विकल्पों को विरासत में लेता है CompareOptions./compareoptions."
type: docs
weight: 360
url: /hi/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

PDF दस्तावेज़ के विशिष्ट तुलना विकल्प। सामान्य विकल्पों को विरासत में लेता है [`CompareOptions`](../compareoptions).

```csharp
public class PdfCompareOptions : CompareOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | नया उदाहरण प्रारंभ करता है [`PdfCompareOptions`](../pdfcompareoptions) वर्ग का। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | जब [`DisplayMode`](./displaymode) को Interleaved पर सेट किया जाता है, तो एनोटेशन के लिए उपयोग किया जाने वाला लेखक नाम प्राप्त करता है या सेट करता है। |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | यह दर्शाता है कि बदलें घटकों के लिए निर्देशांक की गणना करनी है या नहीं। |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | बदलें घटकों मोड के लिए निर्देशांक गणना को निर्दिष्ट करता है। |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | बदलें घटकों के लिए शैली का वर्णन करता है। |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | PDF दस्तावेज़ों में छवियों की तुलना करनी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | हटाए गए घटकों के लिए शैली का वर्णन करता है। |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | तुलना विवरण स्तर को प्राप्त करता है या सेट करता है। |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | यह संकेत करता है कि शैली परिवर्तन का पता लगाना है या नहीं। |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | मास्टर के पथ मान को प्राप्त करता है या सेट करता है या मास्टर के पथ के बिना तुलना का उपयोग करता है। यह विकल्प केवल डायग्राम के लिए है। |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | फ़ोल्डरों की तुलना को चालू करने के लिए नियंत्रण। |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | तुलना परिणाम दस्तावेज़ कैसे व्यवस्थित है, यह प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान Inline है। |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | यह संकेत करता है कि सारांश पृष्ठ में विस्तारित फ़ाइल तुलना जानकारी जोड़नी है या नहीं। |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | परिणामी फ़ोल्डर तुलना फ़ाइल के स्वरूप को प्राप्त करता है या सेट करता है। |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में पता लगाए गए परिवर्तन सांख्यिकी के साथ सारांश पृष्ठ जोड़ना है या नहीं। |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | हेडर/फ़ूटर सामग्री की तुलना को चालू करने के लिए नियंत्रण। |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | समानता के आधार पर परिवर्तन को अनदेखा करने की सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | जब छवि तुलना अक्षम हो, तो छवियों की विरासत का स्रोत निर्दिष्ट करता है। |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | डाले गए घटकों के लिए शैली का वर्णन करता है। |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | यह संकेत करता है कि वर्ड प्रोसेसिंग में आकारों के लिए फ्रेम और इमेज दस्तावेज़ों में आयतों के लिए फ्रेम का उपयोग करना है या नहीं। |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | हटाए या डाले गए तत्व के बच्चों को हटाए या डाले के रूप में चिह्नित करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | तुलना किए गए दस्तावेज़ों के मूल आकार को प्राप्त करता है या सेट करता है। |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | तुलना करने के लिए पृष्ठ सीमा प्राप्त करता है या सेट करता है। जब null होता है, तो सभी पृष्ठों की तुलना की जाती है। |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | परिणाम दस्तावेज़ के कागज़ आकार को प्राप्त करता है या सेट करता है। |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | पासवर्ड सहेजने विकल्प को प्राप्त करता है या सेट करता है। |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | तुलना की संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | टेबलों के लिए तुलना की संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में हटाए गए घटकों को दिखाना है या नहीं। |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में डाले गए घटकों को दिखाना है या नहीं। |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | केवल बदले हुए आइटमों को प्रदर्शित करने के लिए नियंत्रण। |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | यह संकेत करता है कि परिणाम दस्तावेज़ में केवल पता लगाए गए परिवर्तनों के आँकड़े वाला पृष्ठ छोड़ना है या नहीं। |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | डायग्राम के लिए उपयोगकर्ता मास्टर टेम्पलेट का पथ। |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | पाठ को शब्दों में विभाजित करने के लिए डिलिमिटर की एक सरणी प्राप्त करता है या सेट करता है। |

### साथ ही देखें

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
