---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서 작성자 메타데이터에 대한 정보를 구성할 수 있습니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

문서 작성자 메타데이터에 대한 정보를 구성할 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | FileAuthorMetadata 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | 문서의 작성자를 가져옵니다. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | 문서의 작성자를 설정합니다. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | 문서를 마지막으로 저장한 사람의 이름을 가져옵니다. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | 문서를 마지막으로 저장한 사람의 이름을 설정합니다. |
|
|  | [getCompany()](#getCompany--) | 문서가 속한 회사의 이름을 가져옵니다. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | 문서가 속한 회사의 이름을 설정합니다. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


FileAuthorMetadata 클래스의 새 인스턴스를 초기화합니다.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


문서의 작성자를 가져옵니다.


**Returns:**
java.lang.String - 작성자

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


문서의 작성자를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 작성자 |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


문서를 마지막으로 저장한 사람의 이름을 가져옵니다.


**Returns:**
java.lang.String - 이름

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


문서를 마지막으로 저장한 사람의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 사람의 이름 |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


문서가 속한 회사의 이름을 가져옵니다.


**Returns:**
java.lang.String - 회사의 이름

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


문서가 속한 회사의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 회사의 이름 |
|

