---
title: "com.groupdocs.comparison.common.function"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ तुलना प्रक्रिया के दौरान पेज डेटा तक पहुँचने के लिए फ़ंक्शनल इंटरफ़ेस प्रदान करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.comparison.common.function/
---

दस्तावेज़ तुलना प्रक्रिया के दौरान पेज डेटा तक पहुँचने के लिए फ़ंक्शनल इंटरफ़ेस प्रदान करता है।

इस पैकेज में फ़ंक्शनल इंटरफ़ेस का उपयोग पृष्ठों के डेटा तक पहुँचने के लिए किया जाता है जब GroupDocs.Comparison का उपयोग करके दस्तावेज़ तुलना की जाती है।

इस पैकेज में मुख्य फ़ंक्शनल इंटरफ़ेस हैं:

* [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - Allows handling creating output stream used by Comparison to save pages data.
* [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - Allows handling releasing output stream used by Comparison to save pages data.


इन फ़ंक्शनल इंटरफ़ेस का उपयोग दस्तावेज़ पृष्ठों के साथ काम करते समय कस्टम लॉजिक और व्यवहार को परिभाषित करने के लिए किया जा सकता है।
वे पृष्ठों को कैसे और कहाँ सहेजा जाए, इसे प्रोसेस करने में लचीलापन प्रदान करते हैं।


GroupDocs.Comparison for Java का उपयोग करके Word दस्तावेज़ों में संशोधन और ट्रैक्ड परिवर्तन के साथ काम करने के बारे में अधिक विवरण के लिए,
कृपया देखें [GroupDocs.Comparison दस्तावेज़ीकरण](../https://docs.groupdocs.com/comparison/java/).



## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [CreatePageStreamFunction](../com.groupdocs.comparison.common.function/createpagestreamfunction) | फ़ंक्शनल इंटरफ़ेस जो Comparison द्वारा प्रीव्यू इमेज सहेजने के लिए उपयोग किए जाने वाले आउटपुट स्ट्रीम को बनाने के लिए उपयोग किया जाता है। |
| [ReleasePageStreamFunction](../com.groupdocs.comparison.common.function/releasepagestreamfunction) | फ़ंक्शनल इंटरफ़ेस जो Comparison द्वारा प्रीव्यू इमेज सहेजने के लिए उपयोग किए गए आउटपुट स्ट्रीम को बंद करने के लिए उपयोग किया जाता है। |
