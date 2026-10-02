---
title: "com.groupdocs.comparison.common.exceptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "GroupDocs.Comparison में तुलना प्रक्रिया के दौरान फेंके जा सकने वाले एक्सेप्शन प्रदान करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.comparison.common.exceptions/
---

GroupDocs.Comparison में तुलना प्रक्रिया के दौरान फेंके जा सकने वाले एक्सेप्शन प्रदान करता है।

इस पैकेज में मुख्य अपवाद वर्ग हैं:

* [ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception) - The base exception class for all exceptions related to document comparison.
* [InvalidPasswordException](../../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) - The exception that is thrown when an invalid password is provided for a password-protected document.
* [UnsupportedFileFormatException](../../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) - The exception that is thrown when file of this format is not supported by Comparison.


इस पैकेज में अपवाद सामान्य संचालन के लिए विशिष्ट त्रुटि संभाल और रिपोर्टिंग प्रदान करते हैं।
वे अधिक सूक्ष्म त्रुटि पहचान और संभाल की अनुमति देते हैं, जिससे डेवलपर्स विभिन्न त्रुटि परिदृश्यों पर उचित प्रतिक्रिया दे सकते हैं।


GroupDocs.Comparison for Java का उपयोग करके Word दस्तावेज़ों में संशोधन और ट्रैक्ड परिवर्तन के साथ काम करने के बारे में अधिक विवरण के लिए,
कृपया देखें [GroupDocs.Comparison दस्तावेज़ीकरण](../https://docs.groupdocs.com/comparison/java/).



## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [ComparisonException](../com.groupdocs.comparison.common.exceptions/comparisonexception) | Comparison API का उपयोग करते समय फेंके जाने वाले सभी अपवादों के लिए बेस क्लास। |
| [DocumentComparisonException](../com.groupdocs.comparison.common.exceptions/documentcomparisonexception) | दस्तावेज़ तुलना के दौरान त्रुटि होने पर फेंका गया अपवाद। |
| [FileFormatException](../com.groupdocs.comparison.common.exceptions/fileformatexception) | विभिन्न तुलना प्रकारों के साथ फ़ाइलों की तुलना करने पर फेंका गया अपवाद। |
| [InvalidPasswordException](../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) | निर्दिष्ट पासवर्ड गलत होने पर फेंका गया अपवाद। |
| [PasswordProtectedFileException](../com.groupdocs.comparison.common.exceptions/passwordprotectedfileexception) | दस्तावेज़ पासवर्ड द्वारा संरक्षित है लेकिन पासवर्ड प्रदान नहीं किया गया, इस स्थिति में फेंका गया अपवाद। |
| [UnsupportedFileFormatException](../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) | जब इस फ़ॉर्मेट की फ़ाइल Comparison द्वारा समर्थित नहीं होती है, तब फेंका गया अपवाद। |
