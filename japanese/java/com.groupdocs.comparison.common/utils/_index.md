---
title: "Utils"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "Comparison API を使用する際に役立つ一般的なヘルパーメソッドを提供するユーティリティクラスです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Comparison API を使用する際に役立つ一般的なヘルパーメソッドを提供するユーティリティクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Utils()](#Utils--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | 提供されたすべてのオブジェクトを静かに閉じ、すべての IOException を捕捉してログに記録します。 |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | 指定されたストリームを閉じ、発生する例外（IOException のロギングまたは処理）を抑制します |
|
|  | [isText(String data)](#isText-java.lang.String-) | 入力文字列が任意の言語の通常の文字列で許可される文字のみで構成されているか確認します |
|
| [containsOnlyLatinCharsAndPunctuation(String data)](#containsOnlyLatinCharsAndPunctuation-java.lang.String-) |  |
| [toString(TextStyle textStyle)](#toString-com.aspose.note.TextStyle-) |  |
### Utils() {#Utils--}
```
public Utils()
```


### getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter) {#getMethodByTag-java.lang.Class----java.lang.String-boolean-}
```
public static Optional<Method> getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| clazz | java.lang.Class<?> |  |
| methodTag | java.lang.String |  |
| isGetter | boolean |  |

**Returns:**
java.util.Optional<java.lang.reflect.Method>
### closeStreams(Closeable[] closeables) {#closeStreams-java.io.Closeable...-}
```
public static boolean closeStreams(Closeable[] closeables)
```


提供されたすべてのオブジェクトを静かに閉じ、すべての IOException を捕捉してログに記録します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Closeable インターフェイスを実装する任意のオブジェクト（null でも可） |
|

**Returns:**
boolean - すべての closeable オブジェクトが例外なしで閉じられた場合は true、そうでない場合は false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


指定されたストリームを閉じ、発生する例外（IOException のロギングまたは処理）を抑制します
ストリームのいずれかが null であるか、クローズ時に例外が発生した場合は、無視されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | クローズ時に例外がスローされる closeable と IOException の各ペアに対して呼び出されます。null になる可能性があります。 |
|
|  | closeables | java.io.Closeable[] | Closeable インターフェイスを実装する任意のオブジェクト（null でも可） |
|

**Returns:**
boolean - すべての closeable オブジェクトが例外なしで閉じられた場合は true、そうでない場合は false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


入力文字列が任意の言語の通常の文字列で許可される文字のみで構成されているか確認します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |

