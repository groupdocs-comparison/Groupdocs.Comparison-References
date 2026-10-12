---
title: "com.groupdocs.comparison.common.function"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "文書比較プロセス中にページデータにアクセスできる関数型インターフェイスを提供します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.comparison.common.function/
---

文書比較プロセス中にページデータにアクセスできる関数型インターフェイスを提供します。

このパッケージの関数型インターフェイスは、GroupDocs.Comparison を使用して文書比較を行う際にページデータにアクセスするために使用されます。

このパッケージの主な関数型インターフェイスは次のとおりです：

* [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - Allows handling creating output stream used by Comparison to save pages data.
* [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - Allows handling releasing output stream used by Comparison to save pages data.


これらの関数型インターフェイスは、文書ページを操作する際にカスタムロジックや動作を定義するために使用できます。
ページが処理され保存される方法や場所をカスタマイズする柔軟性を提供します。


GroupDocs.Comparison for Java を使用した Word 文書の改訂と変更履歴の操作に関する詳細は、
以下の [GroupDocs.Comparison ドキュメント](../https://docs.groupdocs.com/comparison/java/) を参照してください。



## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [CreatePageStreamFunction](../com.groupdocs.comparison.common.function/createpagestreamfunction) | Comparison がプレビュー画像を保存するために使用する出力ストリームを作成するために使用される関数型インターフェイスです。 |
| [ReleasePageStreamFunction](../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Comparison がプレビュー画像を保存するために使用した出力ストリームを閉じるために使用される関数型インターフェイスです。 |
