---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "통합 로거를 구성하거나 사용자 정의 로거를 설정할 수 있는 로깅 메서드를 구현합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

통합 로거를 구성하거나 사용자 정의 로거를 설정할 수 있는 로깅 메서드를 구현합니다.


이 클래스는 통합 또는 사용자 지정 로거를 설정하고 로그 메시지를 기록할 수 있게 합니다.


사용 예시:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 추적 메시지를 기록합니다. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 추적 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 사전 구성된 로거에서 추적 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 디버그 메시지를 기록합니다. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 디버그 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 사전 구성된 로거에서 디버그 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 경고 메시지를 기록합니다. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 경고 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 사전 구성된 로거에서 경고 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 오류 메시지를 기록합니다. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 사전 구성된 로거에 오류 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 사전 구성된 로거에서 오류 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [getLogger()](#getLogger--) | 모든 유형의 로그를 기록하는 데 사용될 사전 구성된 로거를 가져옵니다. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 모든 유형의 로그를 기록하는 데 사용될 로거를 설정합니다. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


사전 구성된 로거에 추적 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


사전 구성된 로거에 추적 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


사전 구성된 로거에서 추적 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 사전 구성된 로거에서 활성화된 경우 true, 그렇지 않으면 false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


사전 구성된 로거에 디버그 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


사전 구성된 로거에 디버그 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


사전 구성된 로거에서 디버그 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 사전 구성된 로거에서 활성화된 경우 true, 그렇지 않으면 false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


사전 구성된 로거에 경고 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


사전 구성된 로거에 경고 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


사전 구성된 로거에서 경고 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 사전 구성된 로거에서 활성화된 경우 true, 그렇지 않으면 false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


사전 구성된 로거에 오류 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


사전 구성된 로거에 오류 메시지, 스택 트레이스 및 예외의 메시지를 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | message | java.lang.String | 메시지, null인 경우 동작은 로거에 따라 달라집니다. |
|
|  | arguments | java.lang.Object[] | 메시지에 삽입될 인수, null인 경우 동작은 로거에 따라 달라집니다. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


사전 구성된 로거에서 오류 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 사전 구성된 로거에서 활성화된 경우 true, 그렇지 않으면 false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


모든 유형의 로그를 기록하는 데 사용될 사전 구성된 로거를 가져옵니다.


**Returns:**
com.groupdocs.foundation.logging.ILogger - 로거

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


모든 유형의 로그를 기록하는 데 사용될 로거를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 로거 | com.groupdocs.foundation.logging.ILogger | 해당 로거 |
|

