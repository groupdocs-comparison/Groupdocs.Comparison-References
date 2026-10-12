---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서를 로드할 때 추가 옵션을 지정할 수 있습니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

문서를 로드할 때 추가 옵션을 지정할 수 있습니다.


사용 예시:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | 입력 문자열이 경로가 아니라 비교할 텍스트임을 나타내는 플래그와 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 문서를 로드하기 위한 비밀번호와 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | 입력 문자열이 비교할 텍스트이며 문서를 로드하기 위한 비밀번호임을 나타내는 플래그와 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | 파일 유형과 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | 문자열이 [Comparer](../../com.groupdocs.comparison/comparer) 생성자 또는 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 메서드에 전달될 때 파일 경로가 아니라 비교 텍스트임을 나타내는 플래그를 가져옵니다 (텍스트 비교 전용). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | 문자열이 [Comparer](../../com.groupdocs.comparison/comparer) 생성자 또는 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 메서드에 전달될 때 파일 경로가 아니라 비교 텍스트임을 나타내는 플래그를 설정합니다 (텍스트 비교 전용). |
|
|  | [getPassword()](#getPassword--) | 문서를 로드하는 데 사용될 비밀번호를 가져옵니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 문서를 로드하는 데 사용될 비밀번호를 설정합니다. |
|
|  | [getFontDirectories()](#getFontDirectories--) | 문서를 로드하기 위해 폰트 파일이 배치된 디렉터리 목록을 가져옵니다. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | 문서를 로드하기 위해 폰트 파일이 배치된 디렉터리 목록을 설정합니다. |
|
|  | [getFileType()](#getFileType--) | 로드 중인 파일의 유형을 가져옵니다. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | 로드 중인 파일의 유형을 설정합니다. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions 클래스의 새 인스턴스를 초기화합니다.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


입력 문자열이 경로가 아니라 비교할 텍스트임을 나타내는 플래그와 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | isLoadText | boolean | 입력 문자열이 경로가 아니라 비교할 텍스트임을 의미하는 플래그 |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


문서를 로드하기 위한 비밀번호와 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 비밀번호 | java.lang.String | 문서를 로드하기 위한 비밀번호 |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


입력 문자열이 비교할 텍스트이며 문서를 로드하기 위한 비밀번호임을 나타내는 플래그와 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | isLoadText | boolean | 입력 문자열이 경로가 아니라 비교할 텍스트임을 의미하는 플래그 |
|
|  | 비밀번호 | java.lang.String | 문서를 로드하기 위한 비밀번호 |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


파일 유형과 함께 LoadOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | 파일의 유형 |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


문자열이 [Comparer](../../com.groupdocs.comparison/comparer) 생성자 또는 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 메서드에 전달될 때 파일 경로가 아니라 비교 텍스트임을 나타내는 플래그를 가져옵니다 (텍스트 비교 전용).


**Returns:**
boolean - 입력 문자열이 비교할 텍스트이면 true, 그렇지 않으면 false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


문자열이 [Comparer](../../com.groupdocs.comparison/comparer) 생성자 또는 [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) 메서드에 전달될 때 파일 경로가 아니라 비교 텍스트임을 나타내는 플래그를 설정합니다 (텍스트 비교 전용).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 입력 문자열이 비교할 텍스트이면 true, 그렇지 않으면 false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


문서를 로드하는 데 사용될 비밀번호를 가져옵니다.


**Returns:**
java.lang.String - 문서를 로드하기 위한 비밀번호

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


문서를 로드하는 데 사용될 비밀번호를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 문서를 로드하기 위한 비밀번호 |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


문서를 로드하기 위해 폰트 파일이 배치된 디렉터리 목록을 가져옵니다.


**Returns:**
java.util.List<java.lang.String> - 폰트 파일이 포함된 디렉터리 목록

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


문서를 로드하기 위해 폰트 파일이 배치된 디렉터리 목록을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<java.lang.String> | 폰트 파일이 포함된 디렉터리 목록 |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


로드 중인 파일의 유형을 가져옵니다.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


로드 중인 파일의 유형을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | 파일의 유형 |
|

