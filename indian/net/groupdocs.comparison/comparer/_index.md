---
title: Comparer
second_title: .NET API संदर्भ के लिए GroupDocs.Comparison
description: दस्तवेज़ तुलन प्रक्रय क नयंत्रत करने वले मुख्य वर्ग क प्रतनधत्व करत है
type: docs
weight: 100
url: /hi/net/groupdocs.comparison/comparer/
---
## Comparer class

दस्तावेज़ तुलना प्रक्रिया को नियंत्रित करने वाले मुख्य वर्ग का प्रतिनिधित्व करता है।

```csharp
public class Comparer : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) स्रोत दस्तावेज़ स्ट्रीम के साथ वर्ग. |
| [Comparer](comparer#constructor_4)(string) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) स्रोत फ़ाइल पथ के साथ वर्ग. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer)स्रोत दस्तावेज़ धारा के साथ वर्ग और[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) स्रोत दस्तावेज़ स्ट्रीम के साथ और[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) स्रोत फ़ाइल पथ के साथ वर्ग और[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) स्रोत फ़ाइल पथ के साथ और[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) दस्तावेज़ धारा के साथ वर्ग,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) और[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | का नया उदाहरण शुरू करता है[`Comparer`](../comparer) स्रोत फ़ाइल पथ के साथ वर्ग,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) और[`ComparerSettings`](../comparersettings) . |

## गुण

| नाम | विवरण |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | स्रोत फ़ाइल जिसकी तुलना की जा रही है. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | स्रोत फ़ाइल के साथ तुलना करने के लिए लक्षित फ़ाइलों की सूची. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | दस्तावेज़ स्ट्रीम को तुलना में जोड़ता है. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | फ़ाइल को तुलना में जोड़ता है. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | निर्दिष्ट लोडिंग विकल्पों के साथ तुलना करने के लिए दस्तावेज़ स्ट्रीम जोड़ता है। |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | निर्दिष्ट लोडिंग विकल्पों के साथ तुलना करने के लिए फ़ाइल जोड़ता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | परिवर्तनों को स्वीकार या अस्वीकार करता है और उन्हें परिणामी दस्तावेज़ पर लागू करता है। |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | परिणाम सहेजे बिना डिफ़ॉल्ट विकल्पों के साथ दस्तावेज़ों की तुलना करता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | परिणामों को सहेजे बिना दस्तावेज़ों की तुलना करता है. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | दस्तावेज़ों की तुलना करता है और परिणाम फ़ाइल स्ट्रीम में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | दस्तावेज़ों की तुलना करता है और फ़ाइल पथ में परिणाम सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | परिणामों को सहेजे बिना दस्तावेज़ों की तुलना करता है. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | दस्तावेज़ों की तुलना करता है और परिणाम फ़ाइल स्ट्रीम में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | दस्तावेज़ों की तुलना करता है और परिणाम फ़ाइल स्ट्रीम में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | दस्तावेज़ों की तुलना करता है और फ़ाइल पथ में परिणाम सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | दस्तावेज़ों की तुलना करता है और परिणाम फ़ाइल पथ में सहेजता है |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | दस्तावेजों की तुलना करता है और परिणाम को स्ट्रीम में सहेजता है। |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | दस्तावेज़ों की तुलना करता है और फ़ाइल पथ में परिणाम सहेजता है |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | संसाधन जारी करता है। |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | स्रोत और लक्ष्य फ़ाइल (फाइलों) के बीच परिवर्तनों की सूची प्राप्त करता है। |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | स्रोत और लक्ष्य फ़ाइल (फाइलों) के बीच परिवर्तनों की सूची प्राप्त करता है। |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | तुलना के बाद परिणाम स्ट्रिंग प्राप्त करें (केवल पाठ तुलना के लिए). |

### यह सभी देखें

* नाम स्थान [GroupDocs.Comparison](../../groupdocs.comparison)
* सभा [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
