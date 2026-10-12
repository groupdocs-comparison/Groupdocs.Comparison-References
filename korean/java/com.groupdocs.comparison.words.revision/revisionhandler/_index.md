---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "수정 처리를 제어하는 클래스를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

수정 처리를 제어하는 클래스를 나타냅니다.


RevisionHandler 클래스는 문서의 수정 작업을 처리할 수 있게 해줍니다.
이 클래스는 수정 목록을 가져오고, 수정에 변경을 적용하며, 수정된 문서를 저장하는 메서드를 제공합니다.


사용 예시:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | 수정이 포함된 파일 경로를 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | 수정이 포함된 파일 경로를 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | 수정이 포함된 파일 스트림을 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | 문서를 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | 모든 수정 목록을 가져옵니다. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 수정의 변경 사항을 처리하고 원본 파일에 적용합니다. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 수정의 변경 사항을 처리하고 결과를 지정된 파일에 씁니다. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 수정의 변경 사항을 처리하고 결과를 지정된 파일에 씁니다. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | 수정의 변경 사항을 처리하고 결과를 문서 스트림에 씁니다. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


수정이 포함된 파일 경로를 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 파일 경로. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


수정이 포함된 파일 경로를 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 파일 경로. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


수정이 포함된 파일 스트림을 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 파일 | java.io.InputStream | 소스 문서 스트림입니다. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | 파일 유형입니다. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


문서를 사용하여 RevisionHandler 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | com.aspose.words.Document | 문서입니다. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


모든 수정 목록을 가져옵니다.


리비전이 원래 그룹으로 정렬되었기 때문에, 리비전은 List에서 가져와야 합니다.
List에서 단일 리비전은 동일한 일반 텍스트를 가진 여러 리비전으로 분할될 수 있습니다.
List에 동일한 일반 텍스트를 가진 리비전이 포함될 수 있으므로, 사용자를 위한 리비전 목록을 만들 때 이를 제어해야 합니다.
여기서는 List\<RevisionGroup\> 그룹을 사용하여 제어합니다.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - 리비전 목록.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


수정의 변경 사항을 처리하고 원본 파일에 적용합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 변경된 리비전 목록입니다. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


수정의 변경 사항을 처리하고 결과를 지정된 파일에 씁니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 결과 파일 경로입니다. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 변경된 리비전 목록입니다. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


수정의 변경 사항을 처리하고 결과를 지정된 파일에 씁니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 결과 파일 경로입니다. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 변경된 리비전 목록입니다. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


수정의 변경 사항을 처리하고 결과를 문서 스트림에 씁니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | 결과 문서 스트림입니다. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | 변경된 리비전 목록입니다. |
|

### close() {#close--}
```
public void close()
```




