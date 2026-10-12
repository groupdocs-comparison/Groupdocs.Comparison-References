---
title: "FileFormatException"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "異なる比較タイプでファイルを比較したときにスローされる例外です。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison.common.exceptions/fileformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.comparison.common.exceptions.ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception)
```
public class FileFormatException extends ComparisonException
```

異なる比較タイプでファイルを比較したときにスローされる例外です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FileFormatException(String sourceComparisonType, String targetComparisonType)](#FileFormatException-java.lang.String-java.lang.String-) | ソースとターゲットの比較タイプを使用して、FileFormatException クラスの新しいインスタンスを初期化します。 |
|
### FileFormatException(String sourceComparisonType, String targetComparisonType) {#FileFormatException-java.lang.String-java.lang.String-}
```
public FileFormatException(String sourceComparisonType, String targetComparisonType)
```


ソースとターゲットの比較タイプを使用して、FileFormatException クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | sourceComparisonType | java.lang.String | ソース比較タイプ |
|
|  | targetComparisonType | java.lang.String | ターゲット比較タイプ |
|

