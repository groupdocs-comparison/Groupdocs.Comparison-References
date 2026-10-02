---
title: "FileAuthorMetadata"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ドキュメントの作成者メタデータ情報の設定を許可します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

ドキュメントの作成者メタデータに関する情報の構成を可能にします。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | FileAuthorMetadata クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | ドキュメントの作成者を取得します。 |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | ドキュメントの作成者を設定します。 |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | 最後にドキュメントを保存した人物の名前を取得します。 |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | 最後にドキュメントを保存した人物の名前を設定します。 |
|
|  | [getCompany()](#getCompany--) | ドキュメントの所属会社名を取得します。 |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | ドキュメントの所属会社名を設定します。 |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


FileAuthorMetadata クラスの新しいインスタンスを初期化します。


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


ドキュメントの作成者を取得します。


**Returns:**
java.lang.String - 作成者

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


ドキュメントの作成者を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 作成者 |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


最後にドキュメントを保存した人物の名前を取得します。


**Returns:**
java.lang.String - 名前

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


最後にドキュメントを保存した人物の名前を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 人物の名前 |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


ドキュメントの所属会社名を取得します。


**Returns:**
java.lang.String - 会社の名前

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


ドキュメントの所属会社名を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 会社の名前 |
|

