---
title: "CompareOptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "ドキュメント比較プロセスの構成を可能にします。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

ドキュメント比較プロセスの構成を可能にします。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | CompareOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | CompareOptions クラスの新しいインスタンスを、さまざまなスタイルの設定とともに初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | 類似性に基づく変更を無視する設定を取得します。 |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | 類似性に基づく変更を無視する設定を設定します。 |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | ダイアグラム用のユーザーマスター テンプレートへのパスを取得します。 |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | ダイアグラム用のユーザーマスター テンプレートへのパスを設定します。 |
|
|  | [getComparisonType()](#getComparisonType--) | ソースおよびターゲット文書のタイプを [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) オブジェクトとして取得し、Comparison がそれらを比較する方法を認識できるようにします。 |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | ソースおよびターゲット文書のタイプを [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) オブジェクトとして設定し、Comparison がそれらを比較する方法を認識できるようにします。 |
|
|  | [getPaperSize()](#getPaperSize--) | 結果文書の用紙サイズを [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) オブジェクトとして取得します。 |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | 結果文書の用紙サイズを [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) オブジェクトとして設定します。 |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | 座標計算モードを [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) オブジェクトとして取得します。 |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | 座標計算モードを [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) オブジェクトとして設定します。 |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | 結果文書に削除されたコンポーネントを表示するかどうかを示すフラグを取得します。 |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | 結果文書に削除されたコンポーネントを表示するかどうかを示すフラグを設定します。 |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | 結果文書に挿入されたコンポーネントを表示するかどうかを示すフラグを取得します。 |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | 結果文書に挿入されたコンポーネントを表示するかどうかを示すフラグを設定します。 |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | 検出された変更統計情報を含むサマリーページを結果文書に追加するかどうかを示すフラグを取得します。 |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | 検出された変更統計情報を含むサマリーページを結果文書に追加するかどうかを示すフラグを設定します。 |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | サマリーページに拡張ファイル比較情報を追加するかどうかを示すフラグを取得します。 |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | サマリーページに拡張ファイル比較情報を追加するかどうかを示すフラグを設定します。 |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | 結果文書に検出された変更の統計のみのページだけを残すかどうかを示すフラグを取得します。 |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | 結果文書に検出された変更の統計のみのページだけを残すかどうかを示すフラグを設定します。 |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | スタイル変更を検出するかどうかを示すフラグを取得します。 |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | スタイル変更を検出するかどうかを示すフラグを設定します。 |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | 削除または挿入された要素の子を削除または挿入としてマークするかどうかを示すフラグを取得します。 |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | 削除または挿入された要素の子を削除または挿入としてマークするかどうかを示すフラグを設定します。 |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | 変更されたコンポーネントの座標を計算するかどうかを示すフラグを取得します。 |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | 変更されたコンポーネントの座標を計算するかどうかを示すフラグを設定します。 |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | ヘッダー/フッターの内容を比較するかどうかを示すフラグを取得します。 |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | ヘッダー/フッターの内容を比較するかどうかを示すフラグを設定します。 |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | 比較詳細化のレベルを取得します。表現は [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) です。 |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | 比較詳細化のレベルを設定します。表現は [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) です。 |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Word Processing のシェイプと Image ドキュメントの矩形のフレームを使用するかどうかを示すフラグを取得します。 |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Word Processing のシェイプと Image ドキュメントの矩形のフレームを使用するかどうかを示すフラグを設定します。 |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | 挿入された項目に適用されるスタイル設定を取得します。 |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 挿入された項目に適用されるスタイル設定を設定します。 |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | 削除された項目に適用されるスタイル設定を取得します。 |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 削除された項目に適用されるスタイル設定を設定します。 |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | 変更された項目に適用されるスタイル設定を取得します。 |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 変更された項目に適用されるスタイル設定を設定します。 |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | 比較の感度を取得します。 |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | 比較の感度を設定します。 |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | テーブルの比較感度を設定します。 |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | テーブルの比較感度を取得します。 |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | テキストを単語に分割するために使用される区切り文字の配列を設定します。 |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | パスワード保存オプションを取得します。表現は [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) オブジェクトです。 |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | パスワード保存オプションを設定します。表現は [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) オブジェクトです。 |
|
|  | [getOriginalSize()](#getOriginalSize--) | 比較対象ドキュメントの元サイズを取得します。表現は [OriginalSize](../../com.groupdocs.comparison.options/originalsize) オブジェクトです。 |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | 比較対象ドキュメントの元サイズを設定します。表現は [OriginalSize](../../com.groupdocs.comparison.options/originalsize) オブジェクトです。 |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Diagram ドキュメントのマスターページ設定を取得します。 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) オブジェクトで表されます。 |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Diagram ドキュメントのマスターページ設定を設定します。 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) オブジェクトで表されます。 |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | ディレクトリ比較が有効かどうかを示すフラグを返します。 |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | ディレクトリ比較を有効にすべきかどうかを示すフラグを設定します。 |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | 変更された項目のみを表示すべきかどうかを示すブール値を返します。 |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | 変更された項目のみを表示すべきかどうかを示す値を設定します。 |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | 結果のフォルダー比較ファイルの形式を取得します。 |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | 結果のフォルダー比較ファイルの形式を設定します。 |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


CompareOptions クラスの新しいインスタンスを初期化します。


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


CompareOptions クラスの新しいインスタンスを、さまざまなスタイルの設定とともに初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 挿入された項目のスタイル設定 |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 削除された項目のスタイル設定 |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 変更されたスタイル項目のスタイル設定 |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


類似性に基づく変更を無視する設定を取得します。


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - 変更を無視する設定。

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


類似性に基づく変更を無視する設定を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | 変更を無視する設定。 |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


ダイアグラム用のユーザーマスター テンプレートへのパスを取得します。


**Returns:**
java.lang.String - Diagram のユーザーマスター テンプレートへのパス。

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


ダイアグラム用のユーザーマスター テンプレートへのパスを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Diagram のユーザーマスター テンプレートへのパス。 |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


ソースおよびターゲット文書のタイプを [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) オブジェクトとして取得し、Comparison がそれらを比較する方法を認識できるようにします。
このオプションが設定されている場合、[LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) オプションは省略されます。


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


ソースおよびターゲット文書のタイプを [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) オブジェクトとして設定し、Comparison がそれらを比較する方法を認識できるようにします。
このオプションが設定されている場合、[LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) オプションは省略されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | ソースおよびターゲット文書のタイプ |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


結果文書の用紙サイズを [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) オブジェクトとして取得します。


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


結果文書の用紙サイズを [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) オブジェクトとして設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | 結果文書の用紙サイズ |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


座標計算モードを [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) オブジェクトとして取得します。


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


座標計算モードを [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) オブジェクトとして設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | 座標計算モード |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


結果文書に削除されたコンポーネントを表示するかどうかを示すフラグを取得します。


**Returns:**
boolean - 結果文書で削除されたコンポーネントが表示される場合は true、そうでない場合は false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


結果文書に削除されたコンポーネントを表示するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 結果文書で削除されたコンポーネントを表示すべき場合は true、そうでない場合は false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


結果文書に挿入されたコンポーネントを表示するかどうかを示すフラグを取得します。


**Returns:**
ブール - 結果文書で挿入されたコンポーネントを表示する場合は true、そうでなければ false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


結果文書に挿入されたコンポーネントを表示するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 結果文書で挿入されたコンポーネントを表示する場合は true、そうでなければ false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


検出された変更統計情報を含むサマリーページを結果文書に追加するかどうかを示すフラグを取得します。


**Returns:**
ブール - 要約ページを追加する場合は true、そうでなければ false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


検出された変更統計情報を含むサマリーページを結果文書に追加するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 要約ページを追加する場合は true、そうでなければ false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


サマリーページに拡張ファイル比較情報を追加するかどうかを示すフラグを取得します。


**Returns:**
ブール - 拡張ファイル比較情報を要約ページに追加する場合は true、そうでなければ false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


サマリーページに拡張ファイル比較情報を追加するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 拡張ファイル比較情報を要約ページに追加する場合は true、そうでなければ false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


結果文書に検出された変更の統計のみのページだけを残すかどうかを示すフラグを取得します。


**Returns:**
ブール - 結果文書で検出された変更の統計ページだけを残す場合は true、そうでなければ false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


結果文書に検出された変更の統計のみのページだけを残すかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 結果文書で検出された変更の統計ページだけを残す場合は true、そうでなければ false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


スタイル変更を検出するかどうかを示すフラグを取得します。


**Returns:**
ブール - スタイル変更を検出する場合は true、そうでなければ false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


スタイル変更を検出するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | スタイル変更を検出する場合は true、そうでなければ false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


削除または挿入された要素の子を削除または挿入としてマークするかどうかを示すフラグを取得します。


**Returns:**
ブール - 削除または挿入された要素の子要素が削除または挿入としてマークされる場合は true、そうでなければ false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


削除または挿入された要素の子を削除または挿入としてマークするかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 削除または挿入された要素の子要素を削除または挿入としてマークする場合は true、そうでなければ false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


変更されたコンポーネントの座標を計算するかどうかを示すフラグを取得します。


**Returns:**
ブール - 変更されたコンポーネントの座標が計算される場合は true、そうでなければ false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


変更されたコンポーネントの座標を計算するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 変更されたコンポーネントの座標を計算する場合は true、そうでなければ false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


ヘッダー/フッターの内容を比較するかどうかを示すフラグを取得します。


**Returns:**
ブール - ヘッダー/フッターの内容が比較される場合は true、そうでなければ false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


ヘッダー/フッターの内容を比較するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | ヘッダー/フッターの内容を比較する場合は true、そうでなければ false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


比較詳細化のレベルを取得します。表現は [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) です。
デフォルト値は [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW) です。


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


比較詳細化のレベルを設定します。表現は [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) です。
デフォルト値は [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW) です


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | 比較の詳細化レベル |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Word Processing のシェイプと Image ドキュメントの矩形のフレームを使用するかどうかを示すフラグを取得します。


**Returns:**
ブール - フレームを使用する場合は true、そうでなければ false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Word Processing のシェイプと Image ドキュメントの矩形のフレームを使用するかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | フレームを使用する場合は true、そうでなければ false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


挿入された項目に適用されるスタイル設定を取得します。


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


挿入された項目に適用されるスタイル設定を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 挿入された項目のスタイル設定 |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


削除された項目に適用されるスタイル設定を取得します。


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


削除された項目に適用されるスタイル設定を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 削除された項目のスタイル設定 |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


変更された項目に適用されるスタイル設定を取得します。


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


変更された項目に適用されるスタイル設定を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 変更された項目のスタイル設定 |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


比較の感度を取得します。
比較対象の2つのオブジェクトにおける削除および挿入された要素の割合（全要素に対する比率）です。

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - 比較の感度

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


比較の感度を設定します。
比較対象の2つのオブジェクトにおける削除および挿入された要素の割合（全要素に対する比率）です。

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | 比較の感度 |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


テーブルの比較感度を設定します。
値が null の場合、SensitivityOfComparison が代わりに使用されます。2 つの比較対象オブジェクトの削除および挿入された要素の割合を、これらのオブジェクトの全要素に対して示します。

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Integer | テーブルの比較感度 |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


テーブルの比較感度を取得します。
値が null の場合、SensitivityOfComparison が代わりに使用されます。2 つの比較対象オブジェクトの削除および挿入された要素の割合を、これらのオブジェクトの全要素に対して示します。

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - テーブルの比較感度

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


テキストを単語に分割するために使用される区切り文字の配列を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | char[] | テキストを単語に分割するための区切り文字の配列 |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


パスワード保存オプションを取得します。表現は [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) オブジェクトです。


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


パスワード保存オプションを設定します。表現は [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) オブジェクトです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | パスワード保存オプション |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


比較対象ドキュメントの元サイズを取得します。表現は [OriginalSize](../../com.groupdocs.comparison.options/originalsize) オブジェクトです。


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


比較対象ドキュメントの元サイズを設定します。表現は [OriginalSize](../../com.groupdocs.comparison.options/originalsize) オブジェクトです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | ドキュメントの元のサイズ |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Diagram ドキュメントのマスターページ設定を取得します。 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) オブジェクトで表されます。


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Diagram ドキュメントのマスターページ設定を設定します。 [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) オブジェクトで表されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | 図のマスターページ設定 |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


ディレクトリ比較が有効かどうかを示すフラグを返します。


**Returns:**
boolean - ディレクトリ比較が有効な場合は true、そうでない場合は false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


ディレクトリ比較を有効にすべきかどうかを示すフラグを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | directoryCompare | boolean | ディレクトリ比較を有効にする場合は true、そうでない場合は false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


変更された項目のみを表示すべきかどうかを示すブール値を返します。


**Returns:**
boolean - 変更された項目のみを表示する場合は true、そうでない場合は false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


変更された項目のみを表示すべきかどうかを示す値を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | showOnlyChanged | boolean | 変更された項目のみを表示するかどうかを示すブール値 |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


結果のフォルダー比較ファイルの形式を取得します。


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - 結果として得られるフォルダー比較ファイルの形式を表す FolderComparisonExtension

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


結果のフォルダー比較ファイルの形式を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | 結果として得られるフォルダー比較ファイルの形式を表す FolderComparisonExtension |
|

