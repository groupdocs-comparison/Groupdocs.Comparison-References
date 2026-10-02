---
title: "Comparer"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "Comparer 클래스는 문서를 비교하고 비교 결과를 생성하는 기능을 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Comparer 클래스는 문서를 비교하고 비교 결과를 생성하는 기능을 제공합니다.


PDF, Word, Excel, PowerPoint 등 다양한 유형의 문서를 비교할 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | 지정된 소스 파일 경로로 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 지정된 폴더 경로와 비교 옵션으로 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | 지정된 소스 파일 경로로 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | 지정된 소스 파일 경로와 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | 지정된 소스 파일 경로와 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | 지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | 지정된 소스 문서 스트림을 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 소스 문서 스트림과 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | 지정된 소스 문서 스트림과 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | 지정된 문서 스트림, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | 지정된 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSource()](#getSource--) | 비교 중인 소스 문서를 가져옵니다. |
|
|  | [getTargets()](#getTargets--) | 소스 파일과 비교할 대상 문서 목록입니다. |
|
|  | [compare()](#compare--) | 기본 옵션으로 결과를 저장하지 않고 지정된 파일을 대상 문서와 비교합니다. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 생성합니다. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 생성합니다. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 출력 스트림에 씁니다. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 출력 스트림에 씁니다. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 결과를 저장하지 않고 지정된 파일을 대상 문서와 비교합니다. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | 결과를 저장하지 않고 지정된 파일을 대상 문서와 비교합니다. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 출력 스트림에 씁니다. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 지정된 디렉터리를 대상 디렉터리와 비교하고 비교 결과를 제공된 파일 경로에 저장합니다. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 지정된 디렉터리를 대상 디렉터리와 비교하고 비교 결과를 제공된 파일 경로에 저장합니다. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | 지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다. |
|
|  | [add(String filePath)](#add-java.lang.String-) | 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | 지정된 대상 문서 또는 폴더를 비교 프로세스에 추가합니다. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | 지정된 대상 문서들을 비교 프로세스에 추가합니다. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | 지정된 대상 문서들을 비교 프로세스에 추가합니다. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | 지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | 지정된 대상 문서들을 비교 프로세스에 추가합니다. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다. |
|
|  | [getChanges()](#getChanges--) | 비교 프로세스 중 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 배열을 검색합니다. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | 비교 프로세스 중 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 배열을 검색합니다. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | 변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다. |
|
|  | [getResultString()](#getResultString--) | 비교 후 결과 문자열을 가져옵니다 (텍스트 비교 전용). |
|
|  | [getSourceFolder()](#getSourceFolder--) | 비교 중인 소스 폴더를 반환합니다. |
|
|  | [getTargetFolder()](#getTargetFolder--) | 비교 중인 대상 폴더를 반환합니다. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | 자체 비교 검사 (e498c23). |
|
|  | [close()](#close--) | 리소스를 해제합니다. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


지정된 소스 파일 경로로 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 원본 문서의 경로 |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


지정된 폴더 경로와 비교 옵션으로 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 원본 문서 또는 폴더의 경로 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 폴더 비교를 위한 비교 옵션 |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


지정된 소스 파일 경로로 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 원본 문서의 경로 |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 원본 문서의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 원본 문서의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 원본 문서의 경로 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 폴더 비교를 위한 비교 옵션 |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 원본 문서의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 비교할 원본 문서, 폴더 또는 텍스트의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 폴더 비교를 위한 비교 옵션 |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


지정된 소스 파일 경로와 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 원본 문서의 경로 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


지정된 소스 파일 경로와 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 원본 문서의 경로 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 원본 문서의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


지정된 소스 파일 경로와 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 원본 문서 또는 폴더의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 폴더 비교를 위한 비교 옵션 |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


지정된 소스 문서 스트림을 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 원본 문서의 입력 스트림 |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


지정된 소스 문서 스트림과 [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions)를 사용하여 Comparer의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 원본 문서의 입력 스트림 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


지정된 소스 문서 스트림과 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 원본 문서의 입력 스트림 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


지정된 문서 스트림, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) 및 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 비교할 문서 데이터가 포함된 스트림 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 비교 프로세스에 사용될 비교기 설정 |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


지정된 [ComparerSettings](../../com.groupdocs.comparison/comparersettings)를 사용하여 Comparer 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | 설정 |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


비교 중인 소스 문서를 가져옵니다.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


소스 파일과 비교할 대상 문서 목록입니다.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - 대상 문서

### compare() {#compare--}
```
public final Path compare()
```


기본 옵션으로 결과를 저장하지 않고 지정된 파일을 대상 문서와 비교합니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - 결과 문서의 경로나 null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 생성합니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 문서 경로 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로나 null. 일부 상황에서는 확장자를 변경할 수 있습니다

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 생성합니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 문서 경로 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 출력 스트림에 씁니다.


참고: 반환값이 null인 경우, outputStream에 기록된 데이터를 사용하십시오

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 결과 문서 스트림 |
|

**Returns:**
java.nio.file.Path - outputStream에서 데이터를 사용해야 할 때 결과 파일 경로나 null. 일부 상황에서는 결과 파일의 확장자를 변경할 수 있습니다

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 문서 파일 경로 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 문서 파일 경로 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 출력 스트림에 씁니다.


참고: 반환값이 null인 경우, outputStream에 기록된 데이터를 사용하십시오.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.OutputStream | 결과 문서 스트림 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - outputStream에서 데이터를 사용해야 할 때 결과 파일 경로나 null. 일부 상황에서는 결과 파일의 확장자를 변경할 수 있습니다

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


결과를 저장하지 않고 지정된 파일을 대상 문서와 비교합니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 저장 옵션 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 문서의 경로나 null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 문서 파일 경로 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 저장 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 문서 파일 경로 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 저장 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.


참고: 반환 값이 null인 경우, outputStream에 기록된 데이터를 사용하십시오.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.OutputStream | 결과 문서 스트림 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 저장 옵션 |
|

**Returns:**
java.nio.file.Path - outputStream에서 데이터를 사용해야 할 때 결과 파일 경로나 null. 일부 상황에서는 결과 파일의 확장자를 변경할 수 있습니다

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


결과를 저장하지 않고 지정된 파일을 대상 문서와 비교합니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로나 null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 출력 스트림에 씁니다.


참고: 반환 값이 null인 경우, outputStream에 기록된 데이터를 사용하십시오.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 결과 문서 스트림 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 결과 문서를 저장하는 데 사용될 저장 옵션 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - outputStream에서 데이터를 사용해야 할 때 결과 파일 경로나 null. 일부 상황에서는 결과 파일의 확장자를 변경할 수 있습니다

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 문서 파일 경로 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 결과 문서를 저장하는 데 사용될 저장 옵션 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


지정된 디렉터리를 대상 디렉터리와 비교하고 비교 결과를 제공된 파일 경로에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 비교 결과가 저장될 파일 경로. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 디렉터리 비교 프로세스에 사용될 옵션. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


지정된 디렉터리를 대상 디렉터리와 비교하고 비교 결과를 제공된 파일 경로에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 비교 결과가 저장될 파일 경로. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 디렉터리 비교 프로세스에 사용될 옵션. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


지정된 파일을 대상 문서와 비교하고 비교 결과를 제공된 파일 경로에 씁니다.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 문서 파일 경로 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 결과 문서를 저장하는 데 사용될 저장 옵션 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 프로세스에 사용될 비교 옵션 |
|

**Returns:**
java.nio.file.Path - 결과 파일 경로, 일부 상황에서는 확장자를 변경할 수 있습니다

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


지정된 대상 문서를 비교 프로세스에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 추가될 대상 문서의 경로 |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


지정된 대상 문서 또는 폴더를 비교 프로세스에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 추가될 대상 문서 또는 폴더의 경로 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 옵션 |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


지정된 대상 문서를 비교 프로세스에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 추가될 대상 문서의 경로 |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


지정된 대상 문서들을 비교 프로세스에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | 추가될 대상 문서들의 경로 |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


지정된 대상 문서들을 비교 프로세스에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | 추가될 대상 문서들의 경로 |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 추가될 대상 문서의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 추가될 대상 문서의 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 추가될 대상 문서 또는 폴더의 경로 |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | 비교 옵션 |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


지정된 대상 문서를 비교 프로세스에 추가합니다.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 비교할 문서 데이터가 포함된 스트림 |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


지정된 대상 문서들을 비교 프로세스에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | 비교될 문서들의 데이터를 포함하는 스트림 |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


지정된 로드 옵션과 함께 지정된 대상 문서를 비교 프로세스에 추가합니다.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 비교할 문서 데이터가 포함된 스트림 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 문서에 적용될 사용자 지정 로드 옵션 |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


비교 프로세스 중 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 배열을 검색합니다.


이 메서드를 사용하여 원본 문서와 대상 문서 간의 변경 사항에 대한 자세한 정보를 얻을 수 있습니다.
각 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체는 변경 유형, 영향을 받은 영역과 같은 정보를 포함합니다,
그리고 변경 전후의 내용도 포함합니다.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 비교 프로세스 중 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 배열

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


비교 프로세스 중 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 배열을 검색합니다.


이 메서드를 사용하여 원본 문서와 대상 문서 간의 변경 사항에 대한 자세한 정보를 얻을 수 있습니다.
각 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체는 변경 유형, 영향을 받은 영역과 같은 정보를 포함합니다,
그리고 변경 전후의 내용도 포함합니다.


매개변수 [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) 은(는) 변경 사항을 다양한 방식으로 필터링하도록 허용합니다.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | 변경 사항을 필터링하도록 허용하는 객체 |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 비교 프로세스 중 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 배열

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 문서 파일 경로 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 변경 적용 프로세스를 구성하기 위한 사용자 지정 적용 변경 옵션 |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 문서 파일 경로 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 변경 적용 프로세스를 구성하기 위한 사용자 지정 적용 변경 옵션 |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 결과 문서 출력 스트림 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 변경 적용 프로세스를 구성하기 위한 사용자 지정 적용 변경 옵션 |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 문서 파일 경로 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 결과 문서 저장을 구성하기 위한 저장 옵션 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 변경 적용 프로세스를 구성하기 위한 사용자 지정 적용 변경 옵션 |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 문서 파일 경로 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 결과 문서 저장을 구성하기 위한 저장 옵션 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 변경 적용 프로세스를 구성하기 위한 사용자 지정 적용 변경 옵션 |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


변경 사항을 수락하거나 거부하고 결과 문서에 적용합니다.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 결과 문서 출력 스트림 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | 결과 문서 저장을 구성하기 위한 저장 옵션 |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | 변경 적용 프로세스를 구성하기 위한 사용자 지정 적용 변경 옵션 |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


비교 후 결과 문자열을 가져옵니다 (텍스트 비교 전용).


**Returns:**
java.lang.String - 결과 문자열

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


비교 중인 소스 폴더를 반환합니다.


**Returns:**
java.lang.String - 소스 폴더

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


비교 중인 대상 폴더를 반환합니다.


**Returns:**
java.lang.String - 대상 폴더

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


셀프 비교 검사 (e498c23). C# 7a7668c 내부; core.common 테스트가 호출할 수 있도록 public으로 유지되었습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


리소스를 해제합니다.


