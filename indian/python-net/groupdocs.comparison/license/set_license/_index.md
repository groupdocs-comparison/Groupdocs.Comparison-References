---
title: "set_license विधि"
second_title: "GroupDocs.Comparison Python के लिए .NET API संदर्भ"
description: 
type: docs
url: /hi/python-net/groupdocs.comparison/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

वर्तमान प्रक्रिया में एक लाइसेंस लागू करें।

```python
def set_license(self, license_source):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| license_source |  | या तो एक स्ट्रिंग पथ जो ``.lic`` फ़ाइल की ओर इशारा करता है या एक पठनीय फ़ाइल-समरूप वस्तु जो लाइसेंस बाइट्स प्रदान करती है। फ़ाइल-समरूप इनपुट को अस्थायी फ़ाइल में लिखा जाता है इससे पहले कि उन्हें ब्रिज को पास किया जाए। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `TypeError` | यदि ``license_source`` न तो एक स्ट्रिंग पथ है और न ही एक पठनीय फ़ाइल-समरूप वस्तु है। |

### संबंधित देखें
* class [`License`](/comparison/python-net/groupdocs.comparison/license/)
