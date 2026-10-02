---
title: "तुलनाकार"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "दस्तावेज़ तुलना प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।"
type: docs
weight: 100
url: /hi/net/groupdocs.comparison/comparer/
---
## Comparer class

दस्तावेज़ तुलना प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।

```csharp
public sealed class Comparer : IDisposable
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | स्रोत दस्तावेज़ स्ट्रीम के साथ [`Comparer`](../comparer) क्लास का नया उदाहरण प्रारम्भ करता है। |
| [Comparer](comparer#constructor_4)(string) | स्रोत फ़ाइल पथ के साथ [`Comparer`](../comparer) क्लास का नया उदाहरण प्रारम्भ करता है। |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | स्रोत दस्तावेज़ स्ट्रीम और [`ComparerSettings`](../comparersettings) के साथ [`Comparer`](../comparer) क्लास का नया उदाहरण प्रारम्भ करता है। |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | स्रोत दस्तावेज़ स्ट्रीम और [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) के साथ [`Comparer`](../comparer) का नया उदाहरण प्रारम्भ करता है। |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | स्रोत फ़ोल्डर पथ और [`CompareOptions`](../../groupdocs.comparison.options/compareoptions) के साथ [`Comparer`](../comparer) का नया उदाहरण प्रारम्भ करता है। |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | स्रोत फ़ाइल पथ और [`ComparerSettings`](../comparersettings) के साथ [`Comparer`](../comparer) क्लास का नया उदाहरण प्रारम्भ करता है। |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | स्रोत फ़ाइल पथ और [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) के साथ [`Comparer`](../comparer) का नया उदाहरण प्रारंभ करता है। |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | दस्तावेज़ स्ट्रीम, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) और [`ComparerSettings`](../comparersettings) के साथ [`Comparer`](../comparer) क्लास का नया उदाहरण प्रारंभ करता है। |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | स्रोत फ़ाइल पथ, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) और [`ComparerSettings`](../comparersettings) के साथ [`Comparer`](../comparer) क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | परिणाम दस्तावेज़। |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | जिस स्रोत फ़ाइल की तुलना की जा रही है। |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | जिस स्रोत फ़ोल्डर की तुलना की जा रही है। |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | जिस लक्ष्य फ़ोल्डर की तुलना की जा रही है। |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | स्रोत फ़ाइल के साथ तुलना करने के लिए लक्ष्य फ़ाइलों की सूची। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | तुलना में दस्तावेज़ स्ट्रीम जोड़ता है। |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | तुलना में फ़ाइल जोड़ता है। |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | निर्दिष्ट लोडिंग विकल्पों के साथ तुलना में दस्तावेज़ स्ट्रीम जोड़ता है। |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | तुलना में फ़ोल्डर जोड़ता है। |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | निर्दिष्ट लोडिंग विकल्पों के साथ तुलना में फ़ाइल जोड़ता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | डिफ़ॉल्ट विकल्पों के साथ परिणाम को सहेजे बिना दस्तावेज़ों की तुलना करता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | परिणाम को सहेजे बिना दस्तावेज़ों की तुलना करता है। |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल स्ट्रीम में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल पथ पर सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | परिणाम को सहेजे बिना दस्तावेज़ों की तुलना करता है। |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल स्ट्रीम में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल स्ट्रीम में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल पथ पर सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल पथ पर सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | दस्तावेज़ों की तुलना करता है और परिणाम को स्ट्रीम में सहेजता है। |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | दस्तावेज़ों की तुलना करता है और परिणाम को फ़ाइल पथ पर सहेजता है |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | डायरेक्टरी की तुलना करता है और परिणाम को फ़ाइल पथ पर सहेजता है |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | संसाधनों को मुक्त करता है। |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | स्रोत और लक्ष्य फ़ाइल(ओं) के बीच परिवर्तन की सूची प्राप्त करता है। |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | स्रोत और लक्ष्य फ़ाइल(ओं) के बीच परिवर्तन की सूची प्राप्त करता है। |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | स्रोत और लक्ष्य फ़ाइल(ओं) के बीच परिवर्तन की सूची प्राप्त करता है। |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | परिणाम दस्तावेज़ की स्ट्रीम प्राप्त करता है, यदि स्ट्रीम मौजूद नहीं है तो null लौटाता है |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | तुलना के बाद परिणाम स्ट्रिंग प्राप्त करें (केवल टेक्स्ट तुलना के लिए)। |

### साथ ही देखें

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
