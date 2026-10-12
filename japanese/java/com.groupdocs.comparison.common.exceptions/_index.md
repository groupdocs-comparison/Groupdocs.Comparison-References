---
title: "com.groupdocs.comparison.common.exceptions"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "GroupDocs.Comparison の比較プロセス中にスローされる可能性のある例外を提供します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.comparison.common.exceptions/
---

GroupDocs.Comparison の比較プロセス中にスローされる可能性のある例外を提供します。

このパッケージの主な例外クラスは次のとおりです：

* [ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception) - The base exception class for all exceptions related to document comparison.
* [InvalidPasswordException](../../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) - The exception that is thrown when an invalid password is provided for a password-protected document.
* [UnsupportedFileFormatException](../../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) - The exception that is thrown when file of this format is not supported by Comparison.


このパッケージの例外は、GroupDocs.Comparison の一般的な操作に対する特定のエラーハンドリングとレポートを提供します。
これにより、より細かいエラー検出と処理が可能になり、開発者はさまざまなエラーシナリオに適切に対応できます。


GroupDocs.Comparison for Java を使用した Word 文書の改訂と変更履歴の操作に関する詳細は、
以下の [GroupDocs.Comparison ドキュメント](../https://docs.groupdocs.com/comparison/java/) を参照してください。



## クラス

| クラス | 説明 |
| --- | --- |
| [ComparisonException](../com.groupdocs.comparison.common.exceptions/comparisonexception) | Comparison API を使用中にスローされるすべての例外の基底クラスです。 |
| [DocumentComparisonException](../com.groupdocs.comparison.common.exceptions/documentcomparisonexception) | 文書を比較中にエラーが発生したときにスローされる例外です。 |
| [FileFormatException](../com.groupdocs.comparison.common.exceptions/fileformatexception) | 異なる比較タイプでファイルを比較したときにスローされる例外です。 |
| [InvalidPasswordException](../com.groupdocs.comparison.common.exceptions/invalidpasswordexception) | 指定されたパスワードが正しくないときにスローされる例外です。 |
| [PasswordProtectedFileException](../com.groupdocs.comparison.common.exceptions/passwordprotectedfileexception) | 文書がパスワードで保護されているがパスワードが提供されていないときにスローされる例外です。 |
| [UnsupportedFileFormatException](../com.groupdocs.comparison.common.exceptions/unsupportedfileformatexception) | この形式のファイルが Comparison でサポートされていないときにスローされる例外です。 |
