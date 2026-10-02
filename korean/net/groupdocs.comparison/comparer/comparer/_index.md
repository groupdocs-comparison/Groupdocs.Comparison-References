---
title: "비교기"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "소스 파일 경로와 함께 Comparergroupdocs.comparison/comparer 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.comparison/comparer/comparer/
---
## Comparer(string) {#constructor_4}

소스 파일 경로와 함께 [`Comparer`](../../comparer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Comparer(string filePath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 또 보기

* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, CompareOptions) {#constructor_6}

소스 폴더 경로와 [`CompareOptions`](../../../groupdocs.comparison.options/compareoptions)를 사용하여 [`Comparer`](../../comparer)의 새 인스턴스를 초기화합니다.

```csharp
public Comparer(string folderPath, CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| folderPath | String | 폴더 경로 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 또 보기

* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, LoadOptions) {#constructor_7}

소스 파일 경로와 [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions)를 사용하여 [`Comparer`](../../comparer)의 새 인스턴스를 초기화합니다.

```csharp
public Comparer(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로 |
| loadOptions | LoadOptions | 로드 옵션 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, ComparerSettings) {#constructor_5}

소스 파일 경로와 [`ComparerSettings`](../../comparersettings)를 사용하여 [`Comparer`](../../comparer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Comparer(string filePath, ComparerSettings settings)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로 |
| 설정 | ComparerSettings | 비교 설정 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 또 보기

* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(string, LoadOptions, ComparerSettings) {#constructor_8}

소스 파일 경로, [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions) 및 [`ComparerSettings`](../../comparersettings)를 사용하여 [`Comparer`](../../comparer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Comparer(string filePath, LoadOptions loadOptions, ComparerSettings settings)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로 |
| loadOptions | LoadOptions | 로드 옵션 |
| 설정 | ComparerSettings | 비교 설정 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream) {#constructor}

소스 문서 스트림과 함께 [`Comparer`](../../comparer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Comparer(Stream document)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 소스 문서 스트림 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 또 보기

* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, LoadOptions) {#constructor_2}

`[`Comparer`](../../comparer)`의 새 인스턴스를 소스 문서 스트림 및 [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions)와 함께 초기화합니다.

```csharp
public Comparer(Stream document, LoadOptions loadOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 소스 문서 스트림 |
| loadOptions | LoadOptions | 로드 옵션 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, ComparerSettings) {#constructor_1}

`[`Comparer`](../../comparer)` 클래스의 새 인스턴스를 소스 문서 스트림 및 [`ComparerSettings`](../../comparersettings)와 함께 초기화합니다.

```csharp
public Comparer(Stream document, ComparerSettings settings)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 소스 문서 스트림 |
| 설정 | ComparerSettings | 비교 설정 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)

### 또 보기

* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Comparer(Stream, LoadOptions, ComparerSettings) {#constructor_3}

`[`Comparer`](../../comparer)` 클래스의 새 인스턴스를 문서 스트림, [`LoadOptions`](../../../groupdocs.comparison.options/loadoptions) 및 [`ComparerSettings`](../../comparersettings)와 함께 초기화합니다.

```csharp
public Comparer(Stream document, LoadOptions loadOptions, ComparerSettings settings)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 소스 문서 스트림 |
| loadOptions | LoadOptions | 로드 옵션 |
| 설정 | ComparerSettings | 비교 설정 |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* More about GroupDocs.Comparison for .NET features: [Developer Guide](https://docs.groupdocs.com/display/comparisonnet/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](https://docs.groupdocs.com/display/comparisonnet/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3, Azure Blob Storage and others: [Open and compare documents from third-party storages](https://docs.groupdocs.com/display/comparisonnet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.comparison.options/loadoptions)
* class [ComparerSettings](../../comparersettings)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
