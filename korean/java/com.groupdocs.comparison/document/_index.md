---
title: "문서"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "비교 프로세스에 사용할 문서를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

비교 프로세스에 사용할 문서를 나타냅니다.


Document 클래스는 로드, 미리 보기 이미지 생성 및 비교 과정 중 문서를 조작하는 메서드를 제공합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | 지정된 문서 스트림으로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | 지정된 문서 경로로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | 지정된 문서 경로로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | 지정된 문서 경로와 비밀번호로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 문서 경로와 로드 옵션으로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | 지정된 문서 경로와 비밀번호로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 문서 경로와 로드 옵션으로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | 지정된 문서 스트림과 비밀번호로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | 지정된 문서 경로나 텍스트 내용과 전달된 항목을 나타내는 플래그로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | 지정된 문서 스트림과 로드 옵션으로 Document 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 비교 과정에서 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 목록을 가져옵니다. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 비교 과정에서 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 목록을 설정합니다. |
|
|  | [getName()](#getName--) | 문서의 이름을 가져옵니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 문서의 이름을 설정합니다. |
|
|  | [getFileType()](#getFileType--) | 문서의 유형을 가져옵니다. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | 문서의 유형을 설정합니다. |
|
|  | [createStream()](#createStream--) | 문서 내용을 포함한 새 스트림을 생성합니다. |
|
|  | [getStreamLength()](#getStreamLength--) | 문서의 크기를 가져옵니다. |
|
|  | [getPassword()](#getPassword--) | 문서의 비밀번호를 가져옵니다. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | 제공된 [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions)를 기반으로 문서 미리 보기를 생성합니다. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | 문서 유형, 페이지 수, 페이지 크기 등 문서에 대한 정보를 가져옵니다. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


지정된 문서 스트림으로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 문서 스트림 |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


지정된 문서 경로로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서 경로 |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


지정된 문서 경로로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 문서 경로 |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


지정된 문서 경로와 비밀번호로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 문서 경로 |
|
|  | 비밀번호 | java.lang.String | 문서 비밀번호 |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


지정된 문서 경로와 로드 옵션으로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 문서 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 로드 옵션 |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


지정된 문서 경로와 비밀번호로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서 경로 |
|
|  | 비밀번호 | java.lang.String | 문서 비밀번호 |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


지정된 문서 경로와 로드 옵션으로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서 경로 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 로드 옵션 |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


지정된 문서 스트림과 비밀번호로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 문서 스트림 |
|
|  | 비밀번호 | java.lang.String | 문서 비밀번호 |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


지정된 문서 경로나 텍스트 내용과 전달된 항목을 나타내는 플래그로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | 파일 경로 |
|
|  | isLoadText | boolean | 로드된 텍스트 여부 |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


지정된 문서 스트림과 로드 옵션으로 Document 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | 문서 스트림 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | 로드 옵션 |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


비교 과정에서 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 목록을 가져옵니다.


이 메서드를 사용하여 원본 문서와 대상 문서 간의 변경 사항에 대한 자세한 정보를 얻을 수 있습니다.
각 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체는 변경 유형, 영향을 받은 영역과 같은 정보를 포함합니다,
그리고 변경 전후의 내용도 포함합니다.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - 비교 과정에서 감지된 변경을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 목록

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


비교 과정에서 감지된 변경 사항을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 목록을 설정합니다.


이 메서드를 사용하여 원본 문서와 대상 문서 간의 변경 사항에 대한 자세한 정보를 얻을 수 있습니다.
각 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체는 변경 유형, 영향을 받은 영역과 같은 정보를 포함합니다,
그리고 변경 전후의 내용도 포함합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 비교 과정에서 감지된 변경을 나타내는 [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) 객체 목록 |
|

### getName() {#getName--}
```
public final String getName()
```


문서의 이름을 가져옵니다.


**Returns:**
java.lang.String - 문서 이름

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


문서의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 문서 이름 |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


문서의 유형을 가져옵니다.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


문서의 유형을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | 문서 유형 |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


문서 내용을 포함한 새 스트림을 생성합니다.


**Returns:**
java.io.InputStream - 문서 내용을 포함하는 스트림

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


문서의 크기를 가져옵니다.


**Returns:**
long - 문서 크기

### getPassword() {#getPassword--}
```
public String getPassword()
```


문서의 비밀번호를 가져옵니다.


**Returns:**
java.lang.String - 문서 비밀번호

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


제공된 [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions)를 기반으로 문서 미리 보기를 생성합니다.


이 메서드는 지정된 옵션(예: 미리보기 형식)에 따라 문서 페이지의 미리보기를 생성합니다,
페이지 번호 및 출력 스트림 제공자. 생성된 미리보기는 필요에 따라 저장하거나 추가로 처리할 수 있습니다.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | 형식, 페이지 번호 등을 지정하는 미리보기 옵션 |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


문서 유형, 페이지 수, 페이지 크기 등 문서에 대한 정보를 가져옵니다.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```




