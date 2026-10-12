---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서 속성에 대한 접근을 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

문서 속성에 대한 접근을 제공합니다.


사용법에 대한 자세한 내용은 [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) 메서드 또는 [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/)에서 찾을 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFileType()](#getFileType--) | 파일을 나타내는 [FileType](../../com.groupdocs.comparison.result/filetype) 열거형의 유형을 가져옵니다. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | 파일 유형을 [FileType](../../com.groupdocs.comparison.result/filetype) 열거형을 사용하여 설정합니다. |
|
|  | [getPageCount()](#getPageCount--) | 파일의 개수를 가져옵니다. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | 파일의 개수를 설정합니다. |
|
|  | [getSize()](#getSize--) | 파일의 크기를 가져옵니다. |
|
|  | [setSize(long value)](#setSize-long-) | 파일의 크기를 설정합니다. |
|
|  | [getPagesInfo()](#getPagesInfo--) | 파일의 각 페이지에 대한 정보를 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 클래스를 사용하여 가져옵니다. |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | 파일의 각 페이지에 대한 정보를 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 클래스를 사용하여 설정합니다. |
|
|  | [close()](#close--) | 이 객체를 파괴하면 이 [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) 인스턴스를 사용하여 문서 정보를 가져올 수 없게 됩니다. |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


파일을 나타내는 [FileType](../../com.groupdocs.comparison.result/filetype) 열거형의 유형을 가져옵니다.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


파일 유형을 [FileType](../../com.groupdocs.comparison.result/filetype) 열거형을 사용하여 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | 파일의 유형 |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


파일의 개수를 가져옵니다.


**Returns:**
int - 파일의 개수

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


파일의 개수를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 파일의 개수 |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


파일의 크기를 가져옵니다.


**Returns:**
long - 파일의 크기

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


파일의 크기를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | long | 파일의 크기 |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


파일의 각 페이지에 대한 정보를 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 클래스를 사용하여 가져옵니다.


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - 파일의 각 페이지에 대한 정보

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


파일의 각 페이지에 대한 정보를 [PageInfo](../../com.groupdocs.comparison.result/pageinfo) 클래스를 사용하여 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | 파일의 각 페이지에 대한 정보 |
|

### close() {#close--}
```
public abstract void close()
```


이 객체를 파괴하면 이 [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) 인스턴스를 사용하여 문서 정보를 가져올 수 없게 됩니다.
임시 파일을 삭제하고 사용된 리소스를 해제합니다.


