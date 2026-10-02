---
title: "com.groupdocs.comparison.common.exceptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "提供在 GroupDocs.Comparison 比较过程中可能抛出的异常。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.comparison.common.exceptions/
---

提供在 GroupDocs.Comparison 比较过程中可能抛出的异常。

此包中的主要异常类有：

* [ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception) - The base exception class for all exceptions related to document comparison.
* [InvalidPasswordException](../../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) - The exception that is thrown when an invalid password is provided for a password-protected document.
* [UnsupportedFileFormatException](../../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) - The exception that is thrown when file of this format is not supported by Comparison.


此包中的异常为 GroupDocs.Comparison 中的常见操作提供特定的错误处理和报告。
它们允许更细粒度的错误检测和处理，使开发人员能够对不同的错误场景作出适当响应。


欲了解更多关于在 Java 中使用 GroupDocs.Comparison 处理 Word 文档的修订和修订痕迹的细节，
请参阅 [GroupDocs.Comparison Documentation](../https://docs.groupdocs.com/comparison/java/)。



## 类

| 类 | 描述 |
| --- | --- |
| [ComparisonException](../com.groupdocs.comparison.common.exceptions/comparisonexception) | 所有在使用 Comparison API 时抛出的异常的基类。 |
| [DocumentComparisonException](../com.groupdocs.comparison.common.exceptions/documentcomparisonexception) | 在比较文档时发生错误时抛出的异常。 |
| [FileFormatException](../com.groupdocs.comparison.common.exceptions/fileformatexception) | 在比较具有不同比较类型的文件时抛出的异常。 |
| [InvalidPasswordException](../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) | 指定的密码不正确时抛出的异常。 |
| [PasswordProtectedFileException](../com.groupdocs.comparison.common.exceptions/passwordprotectedfileexception) | 文档受密码保护但未提供密码时抛出的异常。 |
| [UnsupportedFileFormatException](../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) | 当 Comparison 不支持此格式的文件时抛出的异常。 |
