---
title: "FileLogger"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ファイルにログを書き込むロガーです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

ファイルにログを書き込むロガーです。


[ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger) と一緒に使用する必要があります。


使用例:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | FileLogger クラスの新しいインスタンスをファイルパスで初期化します。 |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | FileLogger クラスの新しいインスタンスをファイルパスとログレベルの構成で初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | トレースメッセージをファイルに書き込みます。 |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | トレースメッセージをファイルに書き込みます。 |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | トレース ロギングが有効かどうかを確認します。 |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | デバッグメッセージをファイルに書き込みます。 |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | デバッグメッセージをファイルに書き込みます。 |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | デバッグ ロギングが有効かどうかを確認します。 |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 警告メッセージをファイルに書き込みます。 |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 警告メッセージをファイルに書き込みます。 |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 警告 ロギングが有効かどうかを確認します。 |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | エラーメッセージをファイルに書き込みます。 |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | エラーメッセージをファイルに書き込みます。 |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | エラー ロギングが有効かどうかを確認します。 |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


FileLogger クラスの新しいインスタンスをファイルパスで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ログを書き込むために使用されるファイルへのパス |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


FileLogger クラスの新しいインスタンスをファイルパスとログレベルの構成で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ログを書き込むために使用されるファイルへのパス |
|
|  | isTraceEnabled | boolean | トレース ロギングを有効にする場合は true、そうでない場合は false |
|
|  | isDebugEnabled | boolean | デバッグ ロギングを有効にする場合は true、そうでない場合は false |
|
|  | isWarningEnabled | boolean | 警告 ロギングを有効にする場合は true、そうでない場合は false |
|
|  | isErrorEnabled | boolean | エラー ロギングを有効にする場合は true、そうでない場合は false |
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


トレースメッセージをファイルに書き込みます。


トレースログメッセージは、アプリケーションのフローに関する最大限の詳細情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


トレースメッセージをファイルに書き込みます。


トレースログメッセージは、アプリケーションのフローに関する最大限の詳細情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト |
|
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


トレース ロギングが有効かどうかを確認します。


**Returns:**
boolean - 有効な場合は true、そうでない場合は false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


デバッグメッセージをファイルに書き込みます。


デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


デバッグメッセージをファイルに書き込みます。


デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト |
|
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


デバッグ ロギングが有効かどうかを確認します。


**Returns:**
boolean - 有効な場合は true、そうでない場合は false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


警告メッセージをファイルに書き込みます。


警告ログメッセージは、アプリケーションフローにおける予期しないかつ回復可能なイベントに関する情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


警告メッセージをファイルに書き込みます。


警告ログメッセージは、アプリケーションフローにおける予期しないかつ回復可能なイベントに関する情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト |
|
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


警告 ロギングが有効かどうかを確認します。


**Returns:**
boolean - 有効な場合は true、そうでない場合は false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


エラーメッセージをファイルに書き込みます。


エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


エラーメッセージをファイルに書き込みます。


エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。
メッセージには1つまたは少数の {} を含めることができ、対応する引数で置き換えられます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | スタックトレースを取得するために使用される throwable オブジェクト |
|
|  | メッセージ | java.lang.String | メッセージです。 |
|
|  | 引数 | java.lang.Object[] | 引数は、渡された順序でメッセージ内の {} を置き換えます。null は 'null' として書き込まれます。 |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


エラー ロギングが有効かどうかを確認します。


**Returns:**
boolean - 有効な場合は true、そうでない場合は false

