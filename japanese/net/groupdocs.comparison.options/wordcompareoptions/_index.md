---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "Word ドキュメント固有の比較オプション。CompareOptions から共通オプションを継承します。/compareoptions。"
type: docs
weight: 440
url: /ja/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word ドキュメント固有の比較オプション。[`CompareOptions`](../compareoptions) から共通オプションを継承します。

```csharp
public class WordCompareOptions : CompareOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | 新しい [`WordCompareOptions`](../wordcompareoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | 変更されたコンポーネントの座標を計算するかどうかを示します。 |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | 変更されたコンポーネントモードの座標計算を指定します。 |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | 変更されたコンポーネントのスタイルを記述します。 |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | ソースおよびターゲット文書のブックマークが比較され、差分が結果に含まれるかどうかを取得または設定します。 |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | 組み込みおよびカスタム文書プロパティが比較され、差分が結果に含まれるかどうかを取得または設定します（例：プロパティ概要ページ上）。 |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | 文書変数プロパティ（例：DOCVARIABLE フィールド）が比較され、差分が結果に含まれるかどうかを取得または設定します。 |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | 削除されたコンポーネントのスタイルを記述します。 |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | 比較の詳細レベルを取得または設定します。 |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | スタイルの変更を検出するかどうかを示します。 |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | マスターのパス値を取得または設定するか、マスターのパスなしで比較を使用します。このオプションは Diagram のみ対象です。 |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | フォルダーの比較を有効にするコントロールです。 |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | 比較結果の表示方法を取得または設定します：変更履歴モード（Track Changes）での Word のリビジョンとして（Revisions）または文書に直接ハイライトされた変更として（Highlight）。 |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | 要約ページに拡張ファイル比較情報を追加するかどうかを示します。 |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | 結果のフォルダー比較ファイルの形式を取得または設定します。 |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | 検出された変更統計を含む要約ページを結果文書に追加するかどうかを示します。 |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | ヘッダー/フッターの内容の比較を有効にするコントロールです。 |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | 類似性に基づく変更を無視する設定を取得または設定します。 |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | 挿入されたコンポーネントのスタイルを記述します。 |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | 挿入または削除されたコンテンツの代わりに空行を残してレイアウトと行数を保持するかどうかを取得または設定します；[`ShowInsertedContent`](../compareoptions/showinsertedcontent) および [`ShowDeletedContent`](../compareoptions/showdeletedcontent) と共に使用します。 |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Word 処理でのシェイプにフレームを使用し、Image 文書での矩形にフレームを使用するかどうかを示します。 |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | 文書間で異なる段落（行）改行が結果に視覚的にマークされるかどうかを取得または設定します。 |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | 削除または挿入された要素の子要素を削除または挿入としてマークするかどうかを示す値を取得または設定します。 |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | 比較対象文書の元のサイズを取得または設定します。 |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | 結果文書の用紙サイズを取得または設定します。 |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | パスワード保存オプションを取得または設定します。 |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | !:WordTrackChanges が有効なときにリビジョンで使用される作者名を取得または設定します。設定した場合、この名前は結果文書のリビジョンマークアップに適用されます。 |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | 比較の感度を取得または設定します。 |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | テーブルの比較感度を取得または設定します。 |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | 結果文書に削除されたコンポーネントを表示するかどうかを示します。 |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | 結果文書に挿入されたコンポーネントを表示するかどうかを示します。 |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | 変更された項目のみを表示できるようにするコントロールです。 |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | 結果文書に検出された変更の統計ページのみを残すかどうかを示します。 |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | 結果ドキュメントが改訂マークアップを表示したままにするかどうかを取得または設定します。false の場合、すべての改訂が受け入れられ、結果は最終テキストとして表示されます。この設定は [`DisplayMode`](./displaymode) が Highlight に設定されている場合にのみ意味があります。デフォルト値は true です。 |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | ダイアグラム用のユーザーマスター テンプレートへのパス。 |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | テキストを単語に分割するための区切り文字の配列を取得または設定します。 |

### 関連項目

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
