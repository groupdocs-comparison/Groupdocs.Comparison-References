---
title: "PasswordSaveOption"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較プロセス中に文書のパスワード情報を保存するオプションを列挙します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

比較プロセス中に文書のパスワード情報を保存するオプションを列挙します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NONE](#NONE) | パスワードを保存しません。 |
|
|  | [SOURCE](#SOURCE) | ソース文書からパスワードを使用します。 |
|
|  | [TARGET](#TARGET) | ターゲット文書からパスワードを使用します。 |
|
|  | [USER](#USER) | \* ユーザーが提供したパスワードを使用します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PasswordSaveOption の文字列表現を解析して列挙体定数を取得します。 |
|
|  | [toString()](#toString--) | PasswordSaveOption の文字列表現。 |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


パスワードを保存しません。


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


ソース文書からパスワードを使用します。


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


ターゲット文書からパスワードを使用します。


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* ユーザーが提供したパスワードを使用します。


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


PasswordSaveOption の文字列表現を解析して列挙体定数を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PasswordSaveOption の文字列表現 |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PasswordSaveOption の文字列表現。


**Returns:**
java.lang.String - 列挙定数の文字列値

