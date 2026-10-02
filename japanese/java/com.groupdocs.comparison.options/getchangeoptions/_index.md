---
title: "GetChangeOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較結果から特定の変更タイプを取得するためのフィルタリングの構成を可能にします。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

比較結果から特定の変更タイプを取得するためのフィルタリングの構成を可能にします。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | GetChangeOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | 指定されたフィルタータイプ用に GetChangeOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFilter()](#getFilter--) | 比較結果から特定の変更タイプを取得するためのフィルターを取得します。 |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | 比較結果から特定の変更タイプを取得するためのフィルターを設定します。 |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


GetChangeOptions クラスの新しいインスタンスを初期化します。


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


指定されたフィルタータイプ用に GetChangeOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


比較結果から特定の変更タイプを取得するためのフィルターを取得します。


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


比較結果から特定の変更タイプを取得するためのフィルターを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | 取得する変更タイプを指定するフィルターです。 |
|

