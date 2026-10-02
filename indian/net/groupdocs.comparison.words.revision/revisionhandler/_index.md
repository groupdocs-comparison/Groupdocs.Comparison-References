---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for .NET API संदर्भ"
description: "संशोधन हैंडलिंग को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।"
type: docs
weight: 540
url: /hi/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

संशोधन हैंडलिंग को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।

```csharp
public sealed class RevisionHandler : IDisposable
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | फ़ाइल स्ट्रीम के साथ संशोधनों के साथ [`RevisionHandler`](../revisionhandler) क्लास का नया उदाहरण प्रारंभ करता है। |
| [RevisionHandler](revisionhandler#constructor_2)(string) | संशोधनों वाली फ़ाइल के पथ के साथ [`RevisionHandler`](../revisionhandler) क्लास का नया उदाहरण प्रारंभ करता है। |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | संशोधनों के साथ फ़ाइल स्ट्रीम और स्पष्ट स्ट्रीम-स्वामित्व नियंत्रण के साथ [`RevisionHandler`](../revisionhandler) क्लास का नया उदाहरण प्रारंभ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | संशोधनों में परिवर्तन को प्रोसेस करता है और उन्हें उसी फ़ाइल पर लागू करता है जिससे संशोधन लिए गए थे। |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | संशोधनों में परिवर्तन को प्रोसेस करता है और परिणाम को दस्तावेज़ स्ट्रीम में लिखा जाता है। |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | संशोधनों में परिवर्तन को प्रोसेस करता है, और परिणाम निर्दिष्ट पथ वाली फ़ाइल में लिखा जाता है। |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | संसाधनों को मुक्त करता है। |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | सभी संशोधनों की सूची प्राप्त करता है। |

### साथ ही देखें

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Comparison.dll के लिए उत्पन्न किया गया -->
