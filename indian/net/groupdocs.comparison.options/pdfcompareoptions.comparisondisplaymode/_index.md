---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "नियंत्रित करता है कि PDF तुलना परिणाम दस्तावेज़ कैसे व्यवस्थित किया जाता है।"
type: docs
weight: 370
url: /hi/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

नियंत्रित करता है कि PDF तुलना परिणाम दस्तावेज़ कैसे व्यवस्थित किया जाता है।

```csharp
public enum ComparisonDisplayMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Inline | `0` | डिफ़ॉल्ट मोड। एक एकल संयुक्त PDF दस्तावेज़ बनाता है जहाँ हटाए गए सामग्री को एक रंग में और डाले गए सामग्री को दूसरे रंग में हाइलाइट किया जाता है। स्रोत और लक्ष्य दोनों सामग्री एक ही पृष्ठों पर साथ-साथ मौजूद रहती हैं, जिससे दस्तावेज़ों में काफी अंतर होने पर ओवरलैप हो सकता है। |
| SideBySide | `1` | प्रत्येक परिणाम पृष्ठ स्रोत पृष्ठ और उसके संबंधित लक्ष्य पृष्ठ को साथ-साथ दिखाता है। हटाए गए भाग बाएँ (स्रोत पक्ष) पर और जोड़े गए भाग दाएँ (लक्ष्य पक्ष) पर दिखाई देते हैं। दो दस्तावेज़ों की सामग्री कभी ओवरलैप नहीं करती, जिससे यह मोड उन दस्तावेज़ों के लिए उपयुक्त है जो बहुत अधिक भिन्न होते हैं। |
| Interleaved | `2` | एक दस्तावेज़ बनाता है जिसमें पृष्ठ वैकल्पिक रूप से होते हैं: विषम-संख्या वाले पृष्ठ स्रोत दस्तावेज़ से आते हैं (हटाए गए भाग दिखाते हुए) और सम-संख्या वाले पृष्ठ लक्ष्य दस्तावेज़ से आते हैं (जोड़े गए भाग दिखाते हुए)। परिणाम को PDF व्यूअर में "Two Page View" सक्षम करके खोलें ताकि प्रत्येक स्रोत/लक्ष्य जोड़ी स्क्रीन पर साथ-साथ देखी जा सके। SideBySide की तरह, यह मोड सामग्री ओवरलैप को रोकता है और अत्यधिक भिन्न दस्तावेज़ों के लिए सबसे उपयुक्त है। |

### साथ ही देखें

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
