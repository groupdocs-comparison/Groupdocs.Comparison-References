---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "दस्तावेज़ लोड करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 300
url: /hi/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

दस्तावेज़ लोड करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public class LoadOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LoadOptions](loadoptions)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | तुलना के लिए फ़ाइल प्रकार को मैन्युअल रूप से सेट करें ताकि स्वचालित फ़ाइल प्रकार पहचान को ओवरराइड किया जा सके। |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | लोड करने के लिए फ़ॉन्ट निर्देशिकाओं की सूची। |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | यह संकेत देता है कि पास की गई स्ट्रिंग्स तुलना पाठ हैं, फ़ाइल पथ नहीं (केवल टेक्स्ट तुलना के लिए)। |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | दस्तावेज़ का पासवर्ड। |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | सभी बाहरी संसाधनों (जैसे रिमोट URL द्वारा संदर्भित छवियां) को लोड करने को निष्क्रिय करता है, सिवाय [`WhitelistedResources`](./whitelistedresources) के। |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | जब [`SkipExternalResources`](./skipexternalresources) को `true` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL फ्रैगमेंट की सूची। |

### साथ ही देखें

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
