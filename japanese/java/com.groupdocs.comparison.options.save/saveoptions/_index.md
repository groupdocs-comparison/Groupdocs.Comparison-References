---
title: "SaveOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ドキュメントを保存する際に追加オプションを指定できます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

ドキュメントを保存する際に追加オプションを指定できます。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | SaveOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | メタデータ保存結果ドキュメントの処理戦略を取得します。 |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | メタデータ保存結果ドキュメントの処理戦略を設定します。 |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | 結果ドキュメントに設定されるメタデータオブジェクトを取得します。 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) が [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) に設定されている場合。 |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | 結果ドキュメントに設定すべきメタデータオブジェクトを設定します。 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) が [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) に設定されている場合。 |
|
|  | [getPassword()](#getPassword--) | 結果ドキュメントのパスワードを取得します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 結果ドキュメントのパスワードを設定します。 |
|
|  | [getFolderPath()](#getFolderPath--) | 結果画像が保存されるフォルダー パスを取得します。 |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | 結果画像を保存すべきフォルダー パスを設定します。 |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | 結果画像を保存すべきフォルダー パスを設定します。 |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


SaveOptions クラスの新しいインスタンスを初期化します。


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


メタデータ保存結果ドキュメントの処理戦略を取得します。
可能な値は列挙型 [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) にあります。


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


メタデータ保存結果ドキュメントの処理戦略を設定します。
可能な値は列挙型 [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) にあります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | メタデータ処理の戦略 |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


結果ドキュメントに設定されるメタデータオブジェクトを取得します。 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) が [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) に設定されている場合。


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


結果ドキュメントに設定すべきメタデータオブジェクトを設定します。 [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) が [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) に設定されている場合。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | メタデータオブジェクト |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


結果ドキュメントのパスワードを取得します。


**Returns:**
java.lang.String - パスワード

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


結果ドキュメントのパスワードを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | パスワード |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


結果画像が保存されるフォルダー パスを取得します。
イメージ比較専用です。


**Returns:**
java.lang.String - 結果画像を保存するフォルダー パス

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


結果画像を保存すべきフォルダー パスを設定します。
イメージ比較専用です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 結果画像を保存するフォルダー パス |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


結果画像を保存すべきフォルダー パスを設定します。
イメージ比較専用です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.nio.file.Path | 結果画像を保存するフォルダー パス |
|

