---
title: "Compare"
second_title: "GroupDocs.Comparison .NET용 API 참조"
description: "기본 옵션으로 결과를 저장하지 않고 문서를 비교합니다."
type: docs
weight: 90
url: /ko/net/groupdocs.comparison/comparer/compare/
---
## Compare() {#compare}

기본 옵션으로 결과를 저장하지 않고 문서를 비교합니다.

```csharp
public Document Compare()
```

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또 보기

* class [Document](../../document)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string) {#compare_7}

문서를 비교하고 결과를 파일 경로에 저장합니다.

```csharp
public Document Compare(string filePath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 경로 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또 보기

* class [Document](../../document)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream) {#compare_3}

문서를 비교하고 결과를 파일 스트림에 저장합니다.

```csharp
public Document Compare(Stream stream)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 스트림 | Stream | 결과 문서 스트림 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또 보기

* class [Document](../../document)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string, CompareOptions) {#compare_8}

문서를 비교하고 결과를 파일 경로에 저장합니다.

```csharp
public Document Compare(string filePath, CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 파일 경로 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또 보기

* class [Document](../../document)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream, CompareOptions) {#compare_4}

문서를 비교하고 결과를 파일 스트림에 저장합니다.

```csharp
public Document Compare(Stream document, CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 결과 문서 스트림 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또 보기

* class [Document](../../document)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(SaveOptions, CompareOptions) {#compare_2}

결과를 저장하지 않고 문서를 비교합니다.

```csharp
public Document Compare(SaveOptions saveOptions, CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| saveOptions | SaveOptions | 저장 옵션 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또 보기

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string, SaveOptions) {#compare_9}

문서를 비교하고 결과를 파일 경로에 저장합니다.

```csharp
public Document Compare(string filePath, SaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 파일 경로 |
| saveOptions | SaveOptions | 저장 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또 보기

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream, SaveOptions) {#compare_5}

문서를 비교하고 결과를 파일 스트림에 저장합니다.

```csharp
public Document Compare(Stream document, SaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 결과 문서 스트림 |
| saveOptions | SaveOptions | 저장 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또 보기

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(CompareOptions) {#compare_1}

결과를 저장하지 않고 문서를 비교합니다.

```csharp
public Document Compare(CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또 보기

* class [Document](../../document)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(Stream, SaveOptions, CompareOptions) {#compare_6}

문서를 비교하고 결과를 스트림에 저장합니다.

```csharp
public Document Compare(Stream stream, SaveOptions saveOptions, CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 스트림 | Stream | 결과 문서 스트림 |
| saveOptions | SaveOptions | 저장 옵션 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또 보기

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

---

## Compare(string, SaveOptions, CompareOptions) {#compare_10}

문서를 비교하고 결과를 파일 경로에 저장합니다.

```csharp
public Document Compare(string filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 파일 경로 |
| saveOptions | SaveOptions | 저장 옵션 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**Learn more**

* More about how to compare documents: [How to compare documents in C#](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* More about how to compare contracts, drafts and legal documents in C#: [How to compare contracts, drafts and legal documents](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또 보기

* class [Document](../../document)
* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* namespace [GroupDocs.Comparison](../../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Comparison.dll용으로 생성됨 -->
