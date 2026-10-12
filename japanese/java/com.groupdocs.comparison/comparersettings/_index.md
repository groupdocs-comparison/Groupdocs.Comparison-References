---
title: "ComparerSettings"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "クラスの動作をカスタマイズするための設定を定義します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

[Comparer](../../com.groupdocs.comparison/comparer) クラスの動作をカスタマイズするための設定を定義します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | ComparerSettings クラスの新しいインスタンスを生成します。 |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | ComparerSettings クラスの新しいインスタンスを生成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getLogger()](#getLogger--) | ロギングに使用されるロガー実装を取得します。 |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | ロギング用のロガー実装を設定します。 |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


ComparerSettings クラスの新しいインスタンスを生成します。


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


ComparerSettings クラスの新しいインスタンスを生成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ロガー | com.groupdocs.foundation.logging.ILogger | 使用するロガー |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


ロギングに使用されるロガー実装を取得します。


**Returns:**
com.groupdocs.foundation.logging.ILogger - ロガー

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


ロギング用のロガー実装を設定します。


ロギングを無効にするには com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER を使用します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | com.groupdocs.foundation.logging.ILogger | 設定するロガー実装 |
|

