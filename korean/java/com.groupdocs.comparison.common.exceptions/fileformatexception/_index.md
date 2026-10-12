---
title: "FileFormatException"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "다른 비교 유형으로 파일을 비교할 때 발생하는 예외입니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison.common.exceptions/fileformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.comparison.common.exceptions.ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception)
```
public class FileFormatException extends ComparisonException
```

다른 비교 유형으로 파일을 비교할 때 발생하는 예외입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileFormatException(String sourceComparisonType, String targetComparisonType)](#FileFormatException-java.lang.String-java.lang.String-) | 소스 및 대상 비교 유형과 함께 FileFormatException 클래스의 새 인스턴스를 초기화합니다. |
|
### FileFormatException(String sourceComparisonType, String targetComparisonType) {#FileFormatException-java.lang.String-java.lang.String-}
```
public FileFormatException(String sourceComparisonType, String targetComparisonType)
```


소스 및 대상 비교 유형과 함께 FileFormatException 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | sourceComparisonType | java.lang.String | 소스 비교 유형 |
|
|  | targetComparisonType | java.lang.String | 대상 비교 유형 |
|

