---
title: "com.groupdocs.comparison.common.exceptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "GroupDocs.Comparison에서 비교 프로세스 중에 발생할 수 있는 예외를 제공합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.comparison.common.exceptions/
---

GroupDocs.Comparison에서 비교 프로세스 중에 발생할 수 있는 예외를 제공합니다.

이 패키지의 주요 예외 클래스는 다음과 같습니다:

* [ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception) - The base exception class for all exceptions related to document comparison.
* [InvalidPasswordException](../../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) - The exception that is thrown when an invalid password is provided for a password-protected document.
* [UnsupportedFileFormatException](../../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) - The exception that is thrown when file of this format is not supported by Comparison.


이 패키지의 예외는 GroupDocs.Comparison의 일반 작업에 대한 특정 오류 처리 및 보고를 제공합니다.
이들은 보다 세분화된 오류 감지 및 처리를 가능하게 하여 개발자가 다양한 오류 시나리오에 적절히 대응할 수 있도록 합니다.


Java용 GroupDocs.Comparison을 사용하여 Word 문서의 수정 및 추적 변경 작업에 대한 자세한 내용은
다음 [GroupDocs.Comparison Documentation](../https://docs.groupdocs.com/comparison/java/)을 참조하십시오.



## 클래스

| 클래스 | 설명 |
| --- | --- |
| [ComparisonException](../com.groupdocs.comparison.common.exceptions/comparisonexception) | Comparison API를 사용할 때 발생하는 모든 예외의 기본 클래스입니다. |
| [DocumentComparisonException](../com.groupdocs.comparison.common.exceptions/documentcomparisonexception) | 문서를 비교하는 동안 오류가 발생했을 때 발생하는 예외입니다. |
| [FileFormatException](../com.groupdocs.comparison.common.exceptions/fileformatexception) | 다른 비교 유형으로 파일을 비교할 때 발생하는 예외입니다. |
| [InvalidPasswordException](../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) | 지정된 비밀번호가 올바르지 않을 때 발생하는 예외입니다. |
| [PasswordProtectedFileException](../com.groupdocs.comparison.common.exceptions/passwordprotectedfileexception) | 문서가 비밀번호로 보호되어 있지만 비밀번호가 제공되지 않았을 때 발생하는 예외입니다. |
| [UnsupportedFileFormatException](../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) | 이 형식의 파일이 Comparison에서 지원되지 않을 때 발생하는 예외입니다. |
