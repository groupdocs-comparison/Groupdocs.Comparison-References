---
title: "ComparisonLogger"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ロギングメソッドを実装し、統合ロガーまたはユーザー定義ロガーを設定する方法を提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

ロギングメソッドを実装し、統合ロガーまたはユーザー定義ロガーを設定する方法を提供します。


このクラスは、統合ロガーまたはカスタムロガーの設定とログメッセージの書き込みを可能にします。


使用例:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | トレースメッセージを事前構成されたロガーに書き込みます。 |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 例外からのトレースメッセージ、スタックトレース、およびメッセージを事前構成されたロガーに書き込みます。 |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 事前構成されたロガーでトレースロギングが有効かどうかを確認します。 |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | デバッグメッセージを事前構成されたロガーに書き込みます。 |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 例外からのデバッグメッセージ、スタックトレース、およびメッセージを事前構成されたロガーに書き込みます。 |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 事前構成されたロガーでデバッグロギングが有効かどうかを確認します。 |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 警告メッセージを事前構成されたロガーに書き込みます。 |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 例外からの警告メッセージ、スタックトレース、およびメッセージを事前構成されたロガーに書き込みます。 |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 事前構成されたロガーで警告ロギングが有効かどうかを確認します。 |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 事前設定されたロガーにエラーメッセージを書き込みます。 |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 事前設定されたロガーにエラーメッセージ、スタックトレース、および例外からのメッセージを書き込みます。 |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 事前設定されたロガーでエラーロギングが有効かどうかを確認します。 |
|
|  | [getLogger()](#getLogger--) | すべての種類のログを書き込むために使用される事前設定されたロガーを取得します。 |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | すべての種類のログを書き込むために使用されるロガーを設定します。 |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


トレースメッセージを事前構成されたロガーに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


例外からのトレースメッセージ、スタックトレース、およびメッセージを事前構成されたロガーに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト、null の場合の動作はロガーに依存します |
|
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


事前構成されたロガーでトレースロギングが有効かどうかを確認します。


**Returns:**
boolean - 事前設定されたロガーで有効な場合は true、そうでない場合は false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


デバッグメッセージを事前構成されたロガーに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


例外からのデバッグメッセージ、スタックトレース、およびメッセージを事前構成されたロガーに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト、null の場合の動作はロガーに依存します |
|
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


事前構成されたロガーでデバッグロギングが有効かどうかを確認します。


**Returns:**
boolean - 事前設定されたロガーで有効な場合は true、そうでない場合は false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


警告メッセージを事前構成されたロガーに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


例外からの警告メッセージ、スタックトレース、およびメッセージを事前構成されたロガーに書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト、null の場合の動作はロガーに依存します |
|
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


事前構成されたロガーで警告ロギングが有効かどうかを確認します。


**Returns:**
boolean - 事前設定されたロガーで有効な場合は true、そうでない場合は false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


事前設定されたロガーにエラーメッセージを書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


事前設定されたロガーにエラーメッセージ、スタックトレース、および例外からのメッセージを書き込みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト、null の場合の動作はロガーに依存します |
|
|  | メッセージ | java.lang.String | メッセージ、null の場合の動作はロガーに依存します |
|
|  | 引数 | java.lang.Object[] | メッセージに埋め込まれる引数、null の場合の動作はロガーに依存します |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


事前設定されたロガーでエラーロギングが有効かどうかを確認します。


**Returns:**
boolean - 事前設定されたロガーで有効な場合は true、そうでない場合は false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


すべての種類のログを書き込むために使用される事前設定されたロガーを取得します。


**Returns:**
com.groupdocs.foundation.logging.ILogger - ロガー

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


すべての種類のログを書き込むために使用されるロガーを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ロガー | com.groupdocs.foundation.logging.ILogger | ロガー |
|

