---
title: "Compare"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Сравнивает документы без сохранения результата с параметрами по умолчанию"
type: docs
weight: 90
url: /ru/net/groupdocs.comparison/comparer/compare/
---
## Compare() {#compare}

Сравнивает документы без сохранения результата с параметрами по умолчанию

```csharp
public Document Compare()
```

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### См. также

* class [Document](../../document)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string) {#compare_7}

Сравнивает документы и сохраняет результат по пути к файлу

```csharp
public Document Compare(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к результирующему документу |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### См. также

* class [Document](../../document)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream) {#compare_3}

Сравнивает документы и сохраняет результат в поток файла

```csharp
public Document Compare(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Поток результирующего документа |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### См. также

* class [Document](../../document)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string, CompareOptions) {#compare_8}

Сравнивает документы и сохраняет результат по пути к файлу

```csharp
public Document Compare(string filePath, CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу результирующего документа |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### См. также

* class [Document](../../document)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream, CompareOptions) {#compare_4}

Сравнивает документы и сохраняет результат в поток файла

```csharp
public Document Compare(Stream document, CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток результирующего документа |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### См. также

* class [Document](../../document)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(SaveOptions, CompareOptions) {#compare_2}

Сравнивает документы без сохранения результата.

```csharp
public Document Compare(SaveOptions saveOptions, CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| saveOptions | SaveOptions | Параметры сохранения |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### См. также

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string, SaveOptions) {#compare_9}

Сравнивает документы и сохраняет результат по пути к файлу

```csharp
public Document Compare(string filePath, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу результирующего документа |
| saveOptions | SaveOptions | Параметры сохранения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### См. также

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream, SaveOptions) {#compare_5}

Сравнивает документы и сохраняет результат в поток файла

```csharp
public Document Compare(Stream document, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток результирующего документа |
| saveOptions | SaveOptions | Параметры сохранения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### См. также

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(CompareOptions) {#compare_1}

Сравнивает документы без сохранения результата.

```csharp
public Document Compare(CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### См. также

* class [Document](../../document)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream, SaveOptions, CompareOptions) {#compare_6}

Сравнивает документы и сохраняет результат в поток.

```csharp
public Document Compare(Stream stream, SaveOptions saveOptions, CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Поток результирующего документа |
| saveOptions | SaveOptions | Параметры сохранения |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### См. также

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string, SaveOptions, CompareOptions) {#compare_10}

Сравнивает документы и сохраняет результат по пути к файлу

```csharp
public Document Compare(string filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу результирующего документа |
| saveOptions | SaveOptions | Параметры сохранения |
| compareOptions | CompareOptions | Параметры сравнения |

### Примечания

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### См. также

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
