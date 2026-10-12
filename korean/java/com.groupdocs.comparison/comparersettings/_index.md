---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "클래스의 동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

클래스 [Comparer](../../com.groupdocs.comparison/comparer)의 동작을 사용자 정의하기 위한 설정을 정의합니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | ComparerSettings 클래스의 새 인스턴스를 생성합니다. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | ComparerSettings 클래스의 새 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getLogger()](#getLogger--) | 로깅에 사용되는 로거 구현을 가져옵니다. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 로깅을 위한 로거 구현을 설정합니다. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


ComparerSettings 클래스의 새 인스턴스를 생성합니다.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


ComparerSettings 클래스의 새 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 로거 | com.groupdocs.foundation.logging.ILogger | 사용될 로거 |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


로깅에 사용되는 로거 구현을 가져옵니다.


**Returns:**
com.groupdocs.foundation.logging.ILogger - 로거

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


로깅을 위한 로거 구현을 설정합니다.


로깅을 비활성화하려면 com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER를 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | com.groupdocs.foundation.logging.ILogger | 설정할 로거 구현 |
|

