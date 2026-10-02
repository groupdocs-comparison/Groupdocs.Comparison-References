---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "다이어그램 마스터 비교에 대한 설정을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

다이어그램 마스터 비교에 대한 설정을 나타냅니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | DiagramMasterSetting 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | 소스 마스터 경로가 사용될지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | 소스 마스터 경로를 사용해야 하는지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [getMasterPath()](#getMasterPath--) | 문서를 렌더링하는 데 사용될 마스터 경로를 가져옵니다. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | 문서를 렌더링하는 데 사용해야 하는 마스터 경로를 설정합니다. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


DiagramMasterSetting 클래스의 새 인스턴스를 초기화합니다.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


소스 마스터 경로가 사용될지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 소스 마스터 경로가 표시되는 경우 true, 그렇지 않으면 false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


소스 마스터 경로를 사용해야 하는지 여부를 나타내는 플래그를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 소스 마스터 경로가 표시되어야 하는 경우 true, 그렇지 않으면 false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


문서를 렌더링하는 데 사용될 마스터 경로를 가져옵니다. MasterPath는 기본 도형 집합으로부터 결과 문서를 생성하는 데 필요합니다.


**Returns:**
java.lang.String - 설정된 경우 마스터 문서의 경로, 그렇지 않으면 기본 마스터 경로

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


문서를 렌더링하는 데 사용해야 하는 마스터 경로를 설정합니다. MasterPath는 기본 도형 집합으로부터 결과 문서를 생성하는 데 필요합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 설정된 경우 마스터 문서의 경로, 그렇지 않으면 기본 마스터 경로 |
|

