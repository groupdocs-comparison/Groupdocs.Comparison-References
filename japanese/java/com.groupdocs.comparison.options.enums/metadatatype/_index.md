---
title: "MetadataType"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "結果ドキュメントがメタデータ情報を取得する場所を決定します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

結果ドキュメントがメタデータ情報を取得する場所を決定します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | メタデータはそのまま残されます。 |
|
|  | [SOURCE](#SOURCE) | Metedata はソース ドキュメントから取得されます。 |
|
|  | [TARGET](#TARGET) | Metedata はターゲット ドキュメントから取得されます。 |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Metedata はユーザーによって設定されます。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 文字列表現の MetadataType を解析して列挙定数を取得します。 |
|
|  | [toString()](#toString--) | MetadataType の文字列表現。 |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


メタデータはそのまま残されます。


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata はソース ドキュメントから取得されます。


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata はターゲット ドキュメントから取得されます。


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata はユーザーによって設定されます。


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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


文字列表現の MetadataType を解析して列挙定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | MetadataType の文字列表現 |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


MetadataType の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

