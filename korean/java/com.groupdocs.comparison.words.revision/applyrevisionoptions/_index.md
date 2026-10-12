---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "ApplyRevisionOptions 클래스는 최종 문서에 적용되기 전에 수정의 상태를 업데이트할 수 있게 해줍니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

ApplyRevisionOptions 클래스는 최종 문서에 적용되기 전에 수정의 상태를 업데이트할 수 있게 해줍니다.


수정 적용 프로세스를 사용자 정의하기 위한 다양한 생성자와 속성을 제공합니다.


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
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | ApplyRevisionOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | 지정된 수정 목록으로 새 ApplyRevisionOptions 객체를 인스턴스화합니다. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | 지정된 수정 목록과 공통 수정 작업을 사용하여 새로운 ApplyRevisionOptions 객체를 인스턴스화합니다. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | 공통 수정 작업을 사용하여 새로운 ApplyRevisionOptions 객체를 인스턴스화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 적용될 수정 목록을 가져옵니다. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | 적용될 수정 목록을 설정합니다. |
|
|  | [getCommonHandler()](#getCommonHandler--) | 모든 수정에 적용될 공통 수정 작업을 가져옵니다. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | 모든 수정에 적용될 공통 수정 작업을 설정합니다. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


ApplyRevisionOptions 클래스의 새 인스턴스를 초기화합니다.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


지정된 수정 목록으로 새 ApplyRevisionOptions 객체를 인스턴스화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 변경 사항 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 적용될 수정 목록 |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


지정된 수정 목록과 공통 수정 작업을 사용하여 새로운 ApplyRevisionOptions 객체를 인스턴스화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 변경 사항 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 적용될 수정 목록 |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 모든 수정에 적용될 공통 수정 작업 |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


공통 수정 작업을 사용하여 새로운 ApplyRevisionOptions 객체를 인스턴스화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 모든 수정에 적용될 공통 수정 작업 |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


적용될 수정 목록을 가져옵니다.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - 수정 목록

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


적용될 수정 목록을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 변경 사항 | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | 수정 목록 |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


모든 수정에 적용될 공통 수정 작업을 가져옵니다.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


모든 수정에 적용될 공통 수정 작업을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | 공통 수정 작업 |
|

