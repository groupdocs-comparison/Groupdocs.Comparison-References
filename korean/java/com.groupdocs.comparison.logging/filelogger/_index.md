---
title: "FileLogger"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "파일에 로그를 기록하는 로거."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

파일에 로그를 기록하는 로거.


함께 사용해야 합니다 [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


사용 예시:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | 파일 경로를 사용하여 FileLogger 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | 파일 경로와 로그 수준 구성을 사용하여 FileLogger 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 파일에 추적 메시지를 기록합니다. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 파일에 추적 메시지를 기록합니다. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 추적 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 파일에 디버그 메시지를 기록합니다. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 파일에 디버그 메시지를 기록합니다. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 디버그 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 파일에 경고 메시지를 기록합니다. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 파일에 경고 메시지를 기록합니다. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 경고 로깅이 활성화되어 있는지 확인합니다. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 파일에 오류 메시지를 기록합니다. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 파일에 오류 메시지를 기록합니다. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 오류 로깅이 활성화되어 있는지 확인합니다. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


파일 경로를 사용하여 FileLogger 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 로그를 기록하는 데 사용될 파일의 경로 |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


파일 경로와 로그 수준 구성을 사용하여 FileLogger 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 로그를 기록하는 데 사용될 파일의 경로 |
|
|  | isTraceEnabled | boolean | 추적 로깅을 활성화하려면 True, 그렇지 않으면 false |
|
|  | isDebugEnabled | boolean | 디버그 로깅을 활성화하려면 True, 그렇지 않으면 false |
|
|  | isWarningEnabled | boolean | 경고 로깅을 활성화하려면 True, 그렇지 않으면 false |
|
|  | isErrorEnabled | boolean | 오류 로깅을 활성화하려면 True, 그렇지 않으면 false |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


파일에 추적 메시지를 기록합니다.


추적 로그 메시지는 애플리케이션 흐름에 대한 최대 상세 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


파일에 추적 메시지를 기록합니다.


추적 로그 메시지는 애플리케이션 흐름에 대한 최대 상세 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체 |
|
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


추적 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 활성화된 경우 true, 그렇지 않으면 false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


파일에 디버그 메시지를 기록합니다.


디버그 로그 메시지는 애플리케이션 흐름의 다양한 프로세스에 대한 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


파일에 디버그 메시지를 기록합니다.


디버그 로그 메시지는 애플리케이션 흐름의 다양한 프로세스에 대한 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체 |
|
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


디버그 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 활성화된 경우 true, 그렇지 않으면 false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


파일에 경고 메시지를 기록합니다.


경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


파일에 경고 메시지를 기록합니다.


경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체 |
|
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


경고 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 활성화된 경우 true, 그렇지 않으면 false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


파일에 오류 메시지를 기록합니다.


오류 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


파일에 오류 메시지를 기록합니다.


오류 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.
메시지는 하나 또는 몇 개의 {}를 포함할 수 있으며, 해당 인수로 대체됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 스택 트레이스를 가져오는 데 사용될 throwable 객체 |
|
|  | message | java.lang.String | 메시지. |
|
|  | arguments | java.lang.Object[] | 인수는 전달 순서대로 메시지의 {}를 교체하며, null은 'null'로 기록됩니다. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


오류 로깅이 활성화되어 있는지 확인합니다.


**Returns:**
boolean - 활성화된 경우 true, 그렇지 않으면 false

