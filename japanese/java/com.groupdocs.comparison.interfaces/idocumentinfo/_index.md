---
title: "IDocumentInfo"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "文書プロパティへのアクセスを提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

文書プロパティへのアクセスを提供します。


その使用法の詳細は、[Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) メソッドまたは [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/) にあります。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFileType()](#getFileType--) | ファイルの種類を取得します。これは [FileType](../../com.groupdocs.comparison.result/filetype) 列挙型で表されます。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | [FileType](../../com.groupdocs.comparison.result/filetype) 列挙型を使用してファイルの種類を設定します。 |
|
|  | [getPageCount()](#getPageCount--) | ファイルの件数を取得します。 |
|
|  | [setPageCount(int value)](#setPageCount-int-) | ファイルの件数を設定します。 |
|
|  | [getSize()](#getSize--) | ファイルのサイズを取得します。 |
|
|  | [setSize(long value)](#setSize-long-) | ファイルのサイズを設定します。 |
|
|  | [getPagesInfo()](#getPagesInfo--) | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) クラスを使用して、ファイルの各ページの情報を取得します。 |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) クラスを使用して、ファイルの各ページの情報を設定します。 |
|
|  | [close()](#close--) | [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) オブジェクトのインスタンスを使用してドキュメント情報を取得できなくなるように、オブジェクトを破棄します。 |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


ファイルの種類を取得します。これは [FileType](../../com.groupdocs.comparison.result/filetype) 列挙型で表されます。


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


[FileType](../../com.groupdocs.comparison.result/filetype) 列挙型を使用してファイルの種類を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | ファイルの種類 |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


ファイルの件数を取得します。


**Returns:**
int - ファイルの件数

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


ファイルの件数を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ファイルの件数 |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


ファイルのサイズを取得します。


**Returns:**
long - ファイルのサイズ

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


ファイルのサイズを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | long | ファイルのサイズ |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


[PageInfo](../../com.groupdocs.comparison.result/pageinfo) クラスを使用して、ファイルの各ページの情報を取得します。


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - ファイルの各ページの情報

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


[PageInfo](../../com.groupdocs.comparison.result/pageinfo) クラスを使用して、ファイルの各ページの情報を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | ファイルの各ページの情報 |
|

### close() {#close--}
```
public abstract void close()
```


[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) オブジェクトのインスタンスを使用してドキュメント情報を取得できなくなるように、オブジェクトを破棄します。
また、一時ファイルを削除し、使用されたリソースを解放します。


