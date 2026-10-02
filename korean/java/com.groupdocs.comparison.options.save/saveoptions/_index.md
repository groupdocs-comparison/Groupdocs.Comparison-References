---
title: "SaveOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서를 저장할 때 추가 옵션을 지정할 수 있습니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

문서를 저장할 때 추가 옵션을 지정할 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | SaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | 메타데이터 저장 결과 문서를 처리하는 전략을 가져옵니다. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | 메타데이터 저장 결과 문서를 처리하는 전략을 설정합니다. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | 결과 문서에 설정될 메타데이터 객체를 가져옵니다. [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 가 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 로 설정된 경우. |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | 결과 문서에 설정되어야 하는 메타데이터 객체를 설정합니다. [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 가 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 로 설정된 경우. |
|
|  | [getPassword()](#getPassword--) | 결과 문서의 비밀번호를 가져옵니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 결과 문서의 비밀번호를 설정합니다. |
|
|  | [getFolderPath()](#getFolderPath--) | 결과 이미지가 저장될 폴더 경로를 가져옵니다. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | 결과 이미지를 저장할 폴더 경로를 설정합니다. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | 결과 이미지를 저장할 폴더 경로를 설정합니다. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


SaveOptions 클래스의 새 인스턴스를 초기화합니다.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


메타데이터 저장 결과 문서를 처리하는 전략을 가져옵니다.
가능한 값은 enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) 에 있습니다.


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


메타데이터 저장 결과 문서를 처리하는 전략을 설정합니다.
가능한 값은 enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) 에 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | 메타데이터 처리 전략 |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


결과 문서에 설정될 메타데이터 객체를 가져옵니다. [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 가 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 로 설정된 경우.


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


결과 문서에 설정되어야 하는 메타데이터 객체를 설정합니다. [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) 가 [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) 로 설정된 경우.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | 메타데이터 객체 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


결과 문서의 비밀번호를 가져옵니다.


**Returns:**
java.lang.String - 비밀번호

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


결과 문서의 비밀번호를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 비밀번호 |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


결과 이미지가 저장될 폴더 경로를 가져옵니다.
이미징 비교에만 사용됩니다.


**Returns:**
java.lang.String - 결과 이미지를 저장할 폴더 경로

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


결과 이미지를 저장할 폴더 경로를 설정합니다.
이미징 비교에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 결과 이미지를 저장할 폴더 경로 |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


결과 이미지를 저장할 폴더 경로를 설정합니다.
이미징 비교에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.nio.file.Path | 결과 이미지를 저장할 폴더 경로 |
|

