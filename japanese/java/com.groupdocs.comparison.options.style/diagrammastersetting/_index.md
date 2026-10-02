---
title: "DiagramMasterSetting"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "図マスタ比較の設定を表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

図マスタ比較の設定を表します。


使用例:

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


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | DiagramMasterSetting クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | ソースマスターパスが使用されるかどうかを示すフラグを取得します。 |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | ソースマスターパスを使用すべきかどうかを示すフラグを取得します。 |
|
|  | [getMasterPath()](#getMasterPath--) | 文書のレンダリングに使用されるマスターパスを取得します。 |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | 文書のレンダリングに使用すべきマスターパスを設定します。 |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


DiagramMasterSetting クラスの新しいインスタンスを初期化します。


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


ソースマスターパスが使用されるかどうかを示すフラグを取得します。


**Returns:**
boolean - ソースマスターパスが表示される場合は true、そうでなければ false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


ソースマスターパスを使用すべきかどうかを示すフラグを取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | ソースマスターパスを表示すべき場合は true、そうでなければ false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


文書のレンダリングに使用されるマスターパスを取得します。MasterPath はデフォルト形状のセットから結果文書を作成するために必要です。


**Returns:**
java.lang.String - 設定されている場合のマスタードキュメントのパス、設定されていない場合はデフォルトのマスターパス。

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


文書のレンダリングに使用すべきマスターパスを設定します。MasterPath はデフォルト形状のセットから結果文書を作成するために必要です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 設定されている場合のマスタードキュメントのパス、設定されていない場合はデフォルトのマスターパス。 |
|

