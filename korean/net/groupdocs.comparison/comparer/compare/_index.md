---
title: Compare
second_title: .NET API 참조용 GroupDocs.Comparison
description: 기본 옵션으로 결과를 저장하지 않고 문서를 비교합니다
type: docs
weight: 60
url: /ko/net/groupdocs.comparison/comparer/compare/
---
## Compare() {#compare}

기본 옵션으로 결과를 저장하지 않고 문서를 비교합니다

```csharp
public void Compare()
```

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또한보십시오

* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(string) {#compare_7}

문서를 비교하고 결과를 파일 path 에 저장합니다.

```csharp
public void Compare(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 경로 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또한보십시오

* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(Stream) {#compare_3}

문서를 비교하고 결과를 stream 파일에 저장합니다.

```csharp
public void Compare(Stream document)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 결과 문서 스트림 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또한보십시오

* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(string, CompareOptions) {#compare_8}

문서를 비교하고 결과를 파일 path 에 저장합니다.

```csharp
public void Compare(string filePath, CompareOptions compareOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 파일 경로 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* 고급 비교 옵션에 대한 추가 정보 - 감지된 변경 수락 및 거부, 비교 민감도 조정 등: [고급 비교 옵션 가이드](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또한보십시오

* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(Stream, CompareOptions) {#compare_4}

문서를 비교하고 결과를 stream 파일에 저장합니다.

```csharp
public void Compare(Stream document, CompareOptions compareOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 결과 문서 스트림 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* 고급 비교 옵션에 대한 추가 정보 - 감지된 변경 수락 및 거부, 비교 민감도 조정 등: [고급 비교 옵션 가이드](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또한보십시오

* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(SaveOptions, CompareOptions) {#compare_2}

결과를 저장하지 않고 문서를 비교합니다.

```csharp
public void Compare(SaveOptions saveOptions, CompareOptions compareOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| saveOptions | SaveOptions | 저장 옵션 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* 고급 비교 옵션에 대한 추가 정보 - 감지된 변경 수락 및 거부, 비교 민감도 조정 등: [고급 비교 옵션 가이드](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또한보십시오

* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(string, SaveOptions) {#compare_9}

문서를 비교하고 결과를 파일 path 에 저장

```csharp
public void Compare(string filePath, SaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 파일 경로 |
| saveOptions | SaveOptions | 저장 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또한보십시오

* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(Stream, SaveOptions) {#compare_5}

문서를 비교하고 결과를 stream 파일에 저장합니다.

```csharp
public void Compare(Stream document, SaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 결과 문서 스트림 |
| saveOptions | SaveOptions | 저장 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또한보십시오

* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(CompareOptions) {#compare_1}

결과를 저장하지 않고 문서를 비교합니다.

```csharp
public void Compare(CompareOptions compareOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)

### 또한보십시오

* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(Stream, SaveOptions, CompareOptions) {#compare_6}

문서를 비교하고 결과를 스트림에 저장합니다.

```csharp
public void Compare(Stream document, SaveOptions saveOptions, CompareOptions compareOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 결과 문서 스트림 |
| saveOptions | SaveOptions | 저장 옵션 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* 고급 비교 옵션에 대한 추가 정보 - 감지된 변경 수락 및 거부, 비교 민감도 조정 등: [고급 비교 옵션 가이드](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또한보십시오

* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

---

## Compare(string, SaveOptions, CompareOptions) {#compare_10}

문서를 비교하고 결과를 파일 path 에 저장합니다.

```csharp
public void Compare(string filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 결과 문서 파일 경로 |
| saveOptions | SaveOptions | 저장 옵션 |
| compareOptions | CompareOptions | 비교 옵션 |

### 비고

**더 알아보기**

* 문서 비교 방법에 대한 추가 정보: [C#에서 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)
* C#에서 계약, 초안 및 법적 문서를 비교하는 방법에 대한 추가 정보: [계약서, 초안 및 법적 문서를 비교하는 방법](https://docs.groupdocs.com/display/comparisonnet/How+to+Compare+Contracts%2C+Drafts+and+Legal+Documents)
* 고급 비교 옵션에 대한 추가 정보 - 감지된 변경 수락 및 거부, 비교 민감도 조정 등: [고급 비교 옵션 가이드](https://docs.groupdocs.com/display/comparisonnet/Compare+documents)

### 또한보십시오

* class [SaveOptions](../../../groupdocs.comparison.options/saveoptions)
* class [CompareOptions](../../../groupdocs.comparison.options/compareoptions)
* class [Comparer](../../comparer)
* 네임스페이스 [GroupDocs.Comparison](../../comparer)
* 집회 [GroupDocs.Comparison](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
