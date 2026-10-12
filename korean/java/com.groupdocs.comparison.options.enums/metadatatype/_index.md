---
title: "MetadataType"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "결과 문서가 메타데이터 정보를 가져올 위치를 결정합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

결과 문서가 메타데이터 정보를 가져올 위치를 결정합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | 메타데이터는 그대로 유지됩니다. |
|
|  | [SOURCE](#SOURCE) | Metedata는 소스 문서에서 가져옵니다. |
|
|  | [TARGET](#TARGET) | Metedata는 대상 문서에서 가져옵니다. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata는 사용자가 설정합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | MetadataType의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다. |
|
|  | [toString()](#toString--) | MetadataType의 문자열 표현. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


메타데이터는 그대로 유지됩니다.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata는 소스 문서에서 가져옵니다.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata는 대상 문서에서 가져옵니다.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata는 사용자가 설정합니다.


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


MetadataType의 문자열 표현을 구문 분석하여 열거형 상수를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | MetadataType의 문자열 표현 |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


MetadataType의 문자열 표현.


**Returns:**
java.lang.String - enum 상수의 문자열 값

