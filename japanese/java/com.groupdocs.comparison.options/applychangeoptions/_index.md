---
title: "ApplyChangeOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "結果のドキュメントに適用する前に、変更リストを更新できるようにします。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

結果のドキュメントに適用する前に、変更リストを更新できるようにします。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | ApplyChangeOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 変更のリストで ApplyChangeOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | 変更の配列で ApplyChangeOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getChanges()](#getChanges--) | 結果のドキュメントに適用する必要がある変更の配列を取得します。 |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | 結果のドキュメントに適用する必要がある変更の配列を設定します。 |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | 結果のドキュメントに適用する必要がある変更のリストを設定します。 |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | 元の状態を保存すべきかを決定するフラグを取得します。 |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | 元の状態を保存すべきかを決定するフラグを設定します。 |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


ApplyChangeOptions クラスの新しいインスタンスを初期化します。


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


変更のリストで ApplyChangeOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 変更 | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 適用される変更のリスト |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


変更の配列で ApplyChangeOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | 適用される変更のリスト |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


結果のドキュメントに適用する必要がある変更の配列を取得します。


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - 適用される変更の配列

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


結果のドキュメントに適用する必要がある変更の配列を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | 適用される変更の配列 |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


結果のドキュメントに適用する必要がある変更のリストを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | 適用される変更のリスト |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


元の状態を保存すべきかを決定するフラグを取得します。デフォルト値: false。


**Returns:**
boolean - 元の状態を保存する場合は true、そうでない場合は false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


元の状態を保存すべきかを決定するフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | saveOriginalState | boolean | 元の状態を保存する場合は true、そうでない場合は false |
|

