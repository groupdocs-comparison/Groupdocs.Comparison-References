---
title: "Сравнитель"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Инициализирует новый экземпляр класса Comparergroupdocs.comparison/comparer с путем к исходному файлу."
type: docs
weight: 10
url: /ru/net/groupdocs.comparison/comparer/comparer/
---
## Comparer(string) {#constructor_4}

Инициализирует новый экземпляр класса [`Comparer`](../../comparer) с путем к исходному файлу.

```csharp
public Comparer(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### См. также

* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, CompareOptions) {#constructor_6}

Инициализирует новый экземпляр [`Comparer`](../../comparer) с путем к исходной папке и [`CompareOptions`](../../../groupdocs.comparison.options/compareoptions).

```csharp
public Comparer(string folderPath, CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderPath | String | Путь к папке |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### См. также

* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, LoadOptions) {#constructor_7}

Инициализирует новый экземпляр [`Comparer`](../../comparer) с путем к исходному файлу и [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions).

```csharp
public Comparer(string filePath, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу |
| loadOptions | LoadOptions | Параметры загрузки |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### См. также

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, ComparerSettings) {#constructor_5}

Инициализирует новый экземпляр класса [`Comparer`](../../comparer) с путем к исходному файлу и [`ComparerSettings`](../../comparersettings).

```csharp
public Comparer(string filePath, ComparerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу |
| настройки | ComparerSettings | Настройки сравнения |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### См. также

* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, LoadOptions, ComparerSettings) {#constructor_8}

Инициализирует новый экземпляр класса [`Comparer`](../../comparer) с путем к исходному файлу, [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions) и [`ComparerSettings`](../../comparersettings).

```csharp
public Comparer(string filePath, LoadOptions loadOptions, ComparerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу |
| loadOptions | LoadOptions | Параметры загрузки |
| настройки | ComparerSettings | Настройки сравнения |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### См. также

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream) {#constructor}

Инициализирует новый экземпляр класса [`Comparer`](../../comparer) с потоком исходного документа.

```csharp
public Comparer(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток исходного документа |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### См. также

* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, LoadOptions) {#constructor_2}

Инициализирует новый экземпляр [`Comparer`](../../comparer) с потоком исходного документа и [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions).

```csharp
public Comparer(Stream document, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток исходного документа |
| loadOptions | LoadOptions | Параметры загрузки |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### См. также

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, ComparerSettings) {#constructor_1}

Инициализирует новый экземпляр класса [`Comparer`](../../comparer) с потоком исходного документа и [`ComparerSettings`](../../comparersettings).

```csharp
public Comparer(Stream document, ComparerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток исходного документа |
| настройки | ComparerSettings | Настройки сравнения |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### См. также

* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, LoadOptions, ComparerSettings) {#constructor_3}

Инициализирует новый экземпляр класса [`Comparer`](../../comparer) с потоком документа, [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions) и [`ComparerSettings`](../../comparersettings).

```csharp
public Comparer(Stream document, LoadOptions loadOptions, ComparerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток исходного документа |
| loadOptions | LoadOptions | Параметры загрузки |
| настройки | ComparerSettings | Настройки сравнения |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### См. также

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
