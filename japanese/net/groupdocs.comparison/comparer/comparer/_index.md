---
title: "比較ツール"
second_title: "GroupDocs.Comparison for .NET API リファレンス"
description: "ソースファイルパスで Comparergroupdocs.comparison/comparer クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.comparison/comparer/comparer/
---
## Comparer(string) {#constructor_4}

ソースファイルパスで [`Comparer`](../../comparer) クラスの新しいインスタンスを初期化します。

```csharp
public Comparer(string filePath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 関連項目

* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, CompareOptions) {#constructor_6}

ソースフォルダーパスと [`CompareOptions`](../../../groupdocs.comparison.options/compareoptions) を使用して [`Comparer`](../../comparer) の新しいインスタンスを初期化します。

```csharp
public Comparer(string folderPath, CompareOptions compareOptions)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| folderPath | String | フォルダーパス |
| compareOptions | CompareOptions | 比較オプション |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 関連項目

* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, LoadOptions) {#constructor_7}

ソースファイルパスと [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions) を使用して [`Comparer`](../../comparer) の新しいインスタンスを初期化します。

```csharp
public Comparer(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス |
| loadOptions | LoadOptions | ロードオプション |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, ComparerSettings) {#constructor_5}

ソースファイルパスと [`ComparerSettings`](../../comparersettings) を使用して [`Comparer`](../../comparer) クラスの新しいインスタンスを初期化します。

```csharp
public Comparer(string filePath, ComparerSettings settings)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス |
| settings | ComparerSettings | 比較設定 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 関連項目

* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, LoadOptions, ComparerSettings) {#constructor_8}

ソースファイルパス、[`LoadOptions`](../../../groupdocs.comparison.options/loadoptions)、および [`ComparerSettings`](../../comparersettings) を使用して [`Comparer`](../../comparer) クラスの新しいインスタンスを初期化します。

```csharp
public Comparer(string filePath, LoadOptions loadOptions, ComparerSettings settings)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス |
| loadOptions | LoadOptions | ロードオプション |
| settings | ComparerSettings | 比較設定 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream) {#constructor}

ソースドキュメントストリームで [`Comparer`](../../comparer) クラスの新しいインスタンスを初期化します。

```csharp
public Comparer(Stream document)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ソースドキュメントストリーム |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 関連項目

* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, LoadOptions) {#constructor_2}

ソースドキュメントストリームと[`LoadOptions`](../../../groupdocs.comparison.options/loadoptions)を使用して[`Comparer`](../../comparer)の新しいインスタンスを初期化します。

```csharp
public Comparer(Stream document, LoadOptions loadOptions)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ソースドキュメントストリーム |
| loadOptions | LoadOptions | ロードオプション |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, ComparerSettings) {#constructor_1}

ソースドキュメントストリームと[`ComparerSettings`](../../comparersettings)を使用して[`Comparer`](../../comparer)クラスの新しいインスタンスを初期化します。

```csharp
public Comparer(Stream document, ComparerSettings settings)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ソースドキュメントストリーム |
| settings | ComparerSettings | 比較設定 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 関連項目

* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, LoadOptions, ComparerSettings) {#constructor_3}

ドキュメントストリーム、[`LoadOptions`](../../../groupdocs.comparison.options/loadoptions)および[`ComparerSettings`](../../comparersettings)を使用して[`Comparer`](../../comparer)クラスの新しいインスタンスを初期化します。

```csharp
public Comparer(Stream document, LoadOptions loadOptions, ComparerSettings settings)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | Stream | ソースドキュメントストリーム |
| loadOptions | LoadOptions | ロードオプション |
| settings | ComparerSettings | 比較設定 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Comparison.dll 用に生成されました -->
