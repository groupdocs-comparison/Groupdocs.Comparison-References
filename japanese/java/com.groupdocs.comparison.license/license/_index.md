---
title: "ライセンス"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "License クラスは、GroupDocs.Comparison 用のライセンスを設定および適用するメソッドを提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

License クラスは、GroupDocs.Comparison 用のライセンスを設定および適用するメソッドを提供します。


適用されたライセンスに基づいて、ライブラリの特定の機能を有効化または無効化できます。

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


使用例:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | ライセンスが設定されたかどうかを示す値を取得します。 |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 入力ストリームを使用して Comparison にライセンスを設定します。 |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | ライセンスファイルのパスを使用して Comparison にライセンスを設定します。 |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | ライセンスファイルのパスを使用して Comparison にライセンスを設定します。 |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


ライセンスが設定されたかどうかを示す値を取得します。


**Returns:**
boolean - ライセンスが正常に設定された場合は true、そうでない場合は false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


入力ストリームを使用して Comparison にライセンスを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | ライセンスストリーム。null を指定するとライセンスが解除されます。 |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


ライセンスファイルのパスを使用して Comparison にライセンスを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | ライセンスファイルのパス |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


ライセンスファイルのパスを使用して Comparison にライセンスを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | licensePath | java.lang.String | ライセンスファイルのパス |
|

