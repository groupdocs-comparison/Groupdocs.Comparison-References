---
title: "CompareOptions"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "문서 비교 프로세스를 구성할 수 있습니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

문서 비교 프로세스를 구성할 수 있습니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | CompareOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | 다양한 스타일에 대한 설정을 포함하여 CompareOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | 유사성을 기반으로 변경을 무시하는 설정을 가져옵니다. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | 유사성을 기반으로 변경을 무시하는 설정을 설정합니다. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | 다이어그램에 대한 사용자 마스터 템플릿 경로를 가져옵니다. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | 다이어그램에 대한 사용자 마스터 템플릿 경로를 설정합니다. |
|
|  | [getComparisonType()](#getComparisonType--) | 비교가 문서들을 어떻게 비교할지 알 수 있도록 소스 및 대상 문서 유형을 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 객체로 가져옵니다. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | 비교가 문서들을 어떻게 비교할지 알 수 있도록 소스 및 대상 문서 유형을 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 객체로 설정합니다. |
|
|  | [getPaperSize()](#getPaperSize--) | 결과 문서의 용지 크기를 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 객체로 가져옵니다. |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | 결과 문서의 용지 크기를 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 객체로 설정합니다. |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 객체로 좌표 계산 모드를 가져옵니다. |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 객체로 좌표 계산 모드를 설정합니다. |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | 결과 문서에 삭제된 구성 요소를 표시할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | 결과 문서에 삭제된 구성 요소를 표시할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | 결과 문서에 삽입된 구성 요소를 표시할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | 결과 문서에 삽입된 구성 요소를 표시할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | 결과 문서에 감지된 변경 통계가 포함된 요약 페이지를 추가할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | 결과 문서에 감지된 변경 통계가 포함된 요약 페이지를 추가할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | 요약 페이지에 확장 파일 비교 정보를 추가할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | 요약 페이지에 확장 파일 비교 정보를 추가할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | 결과 문서에 감지된 변경 통계가 포함된 페이지만 남길지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | 결과 문서에 감지된 변경 통계가 포함된 페이지만 남길지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | 스타일 변경을 감지할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | 스타일 변경을 감지할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | 삭제되거나 삽입된 요소의 자식을 삭제되었거나 삽입된 것으로 표시할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | 삭제되거나 삽입된 요소의 자식을 삭제되었거나 삽입된 것으로 표시할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | 변경된 구성 요소에 대한 좌표를 계산할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | 변경된 구성 요소에 대한 좌표를 계산할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | 머리글/바닥글 내용을 비교할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | 머리글/바닥글 내용을 비교할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | 비교 세분화 수준을 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)으로 가져옵니다. |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | 비교 세분화 수준을 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)으로 설정합니다. |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | 워드 프로세싱의 도형 및 이미지 문서의 사각형에 대한 프레임을 사용할지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | 워드 프로세싱의 도형 및 이미지 문서의 사각형에 대한 프레임을 사용할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | 삽입된 항목에 적용될 스타일 설정을 가져옵니다. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 삽입된 항목에 적용될 스타일 설정을 설정합니다. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | 삭제된 항목에 적용될 스타일 설정을 가져옵니다. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 삭제된 항목에 적용될 스타일 설정을 설정합니다. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | 변경된 항목에 적용될 스타일 설정을 가져옵니다. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | 변경된 항목에 적용될 스타일 설정을 설정합니다. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | 비교 민감도를 가져옵니다. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | 비교 민감도를 설정합니다. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | 표에 대한 비교 민감도를 설정합니다. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | 표에 대한 비교 민감도를 가져옵니다. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | 텍스트를 단어로 분할하는 데 사용될 구분자 배열을 설정합니다. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 객체로 표시되는 비밀번호 저장 옵션을 가져옵니다. |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 객체로 표시되는 비밀번호 저장 옵션을 설정합니다. |
|
|  | [getOriginalSize()](#getOriginalSize--) | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) 객체로 표시되는 비교된 문서의 원본 크기를 가져옵니다. |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) 객체로 표시되는 비교된 문서의 원본 크기를 설정합니다. |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 객체로 표시되는 다이어그램 문서의 마스터 페이지 설정을 가져옵니다. |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 객체로 표시되는 다이어그램 문서의 마스터 페이지 설정을 설정합니다. |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | 디렉터리 비교가 활성화되어 있는지 여부를 나타내는 플래그를 반환합니다. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | 디렉터리 비교를 활성화해야 하는지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | 변경된 항목만 표시해야 하는지 여부를 나타내는 부울 값을 반환합니다. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | 변경된 항목만 표시해야 하는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | 결과 폴더 비교 파일의 형식을 가져옵니다. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | 결과 폴더 비교 파일의 형식을 설정합니다. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


CompareOptions 클래스의 새 인스턴스를 초기화합니다.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


다양한 스타일에 대한 설정을 포함하여 CompareOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 삽입된 항목에 대한 스타일 설정 |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 삭제된 항목에 대한 스타일 설정 |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 변경된 스타일 항목에 대한 스타일 설정 |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


유사성을 기반으로 변경을 무시하는 설정을 가져옵니다.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - 변경을 무시하는 설정.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


유사성을 기반으로 변경을 무시하는 설정을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | 변경을 무시하는 설정. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


다이어그램에 대한 사용자 마스터 템플릿 경로를 가져옵니다.


**Returns:**
java.lang.String - 다이어그램용 사용자 마스터 템플릿 경로.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


다이어그램에 대한 사용자 마스터 템플릿 경로를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | 다이어그램용 사용자 마스터 템플릿 경로. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


비교가 문서들을 어떻게 비교할지 알 수 있도록 소스 및 대상 문서 유형을 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 객체로 가져옵니다.
이 옵션이 설정되면, [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) 옵션이 생략됩니다.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


비교가 문서들을 어떻게 비교할지 알 수 있도록 소스 및 대상 문서 유형을 [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) 객체로 설정합니다.
이 옵션이 설정되면, [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) 옵션이 생략됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | 소스 및 대상 문서의 유형 |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


결과 문서의 용지 크기를 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 객체로 가져옵니다.


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


결과 문서의 용지 크기를 [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) 객체로 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | 결과 문서의 용지 크기 |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 객체로 좌표 계산 모드를 가져옵니다.


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) 객체로 좌표 계산 모드를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | 좌표 계산 모드 |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


결과 문서에 삭제된 구성 요소를 표시할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 결과 문서에 삭제된 구성 요소가 표시되는 경우 true, 그렇지 않으면 false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


결과 문서에 삭제된 구성 요소를 표시할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 삭제된 구성 요소가 결과 문서에 표시되어야 하는 경우 true, 그렇지 않으면 false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


결과 문서에 삽입된 구성 요소를 표시할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 결과 문서에 삽입된 구성 요소가 표시되는 경우 true, 그렇지 않으면 false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


결과 문서에 삽입된 구성 요소를 표시할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 삽입된 구성 요소가 결과 문서에 표시되어야 하는 경우 true, 그렇지 않으면 false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


결과 문서에 감지된 변경 통계가 포함된 요약 페이지를 추가할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 요약 페이지가 추가되는 경우 true, 그렇지 않으면 false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


결과 문서에 감지된 변경 통계가 포함된 요약 페이지를 추가할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 요약 페이지가 추가되어야 하는 경우 true, 그렇지 않으면 false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


요약 페이지에 확장 파일 비교 정보를 추가할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 확장 파일 비교 정보가 요약 페이지에 추가되는 경우 true, 그렇지 않으면 false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


요약 페이지에 확장 파일 비교 정보를 추가할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 확장 파일 비교 정보가 요약 페이지에 추가되어야 하는 경우 true, 그렇지 않으면 false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


결과 문서에 감지된 변경 통계가 포함된 페이지만 남길지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 결과 문서에 감지된 변경 사항 통계 페이지만 남는 경우 true, 그렇지 않으면 false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


결과 문서에 감지된 변경 통계가 포함된 페이지만 남길지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 결과 문서에 감지된 변경 사항 통계 페이지만 남겨야 하는 경우 true, 그렇지 않으면 false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


스타일 변경을 감지할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 스타일 변경이 감지되는 경우 true, 그렇지 않으면 false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


스타일 변경을 감지할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 스타일 변경이 감지되어야 하는 경우 true, 그렇지 않으면 false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


삭제되거나 삽입된 요소의 자식을 삭제되었거나 삽입된 것으로 표시할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 삭제되거나 삽입된 요소의 자식이 삭제되거나 삽입된 것으로 표시되는 경우 true, 그렇지 않으면 false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


삭제되거나 삽입된 요소의 자식을 삭제되었거나 삽입된 것으로 표시할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 삭제되거나 삽입된 요소의 자식이 삭제되거나 삽입된 것으로 표시되어야 하는 경우 true, 그렇지 않으면 false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


변경된 구성 요소에 대한 좌표를 계산할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 변경된 구성 요소의 좌표가 계산되는 경우 true, 그렇지 않으면 false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


변경된 구성 요소에 대한 좌표를 계산할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 변경된 구성 요소의 좌표가 계산되어야 하는 경우 true, 그렇지 않으면 false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


머리글/바닥글 내용을 비교할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 머리글/바닥글 내용이 비교되는 경우 true, 그렇지 않으면 false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


머리글/바닥글 내용을 비교할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 헤더/푸터 내용이 비교되어야 하면 true, 그렇지 않으면 false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


비교 세분화 수준을 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)으로 가져옵니다.
기본값은 [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)입니다.


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


비교 세분화 수준을 [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)으로 설정합니다.
기본값은 [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW)입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | 비교 세부화 수준 |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


워드 프로세싱의 도형 및 이미지 문서의 사각형에 대한 프레임을 사용할지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 프레임이 사용될 경우 true, 그렇지 않으면 false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


워드 프로세싱의 도형 및 이미지 문서의 사각형에 대한 프레임을 사용할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 프레임을 사용해야 하면 true, 그렇지 않으면 false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


삽입된 항목에 적용될 스타일 설정을 가져옵니다.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


삽입된 항목에 적용될 스타일 설정을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 삽입된 항목의 스타일 설정 |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


삭제된 항목에 적용될 스타일 설정을 가져옵니다.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


삭제된 항목에 적용될 스타일 설정을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 삭제된 항목의 스타일 설정 |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


변경된 항목에 적용될 스타일 설정을 가져옵니다.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


변경된 항목에 적용될 스타일 설정을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | 변경된 항목의 스타일 설정 |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


비교 민감도를 가져옵니다.
두 비교된 객체의 전체 요소에 대한 삭제 및 삽입된 요소의 비율

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - 비교 민감도

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


비교 민감도를 설정합니다.
두 비교된 객체의 전체 요소에 대한 삭제 및 삽입된 요소의 비율

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 비교 민감도 |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


표에 대한 비교 민감도를 설정합니다.
값이 null인 경우 SensitivityOfComparison가 대신 사용됩니다. 두 비교된 객체의 전체 요소에 대한 삭제 및 삽입된 요소의 비율.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Integer | 테이블에 대한 비교 민감도 |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


표에 대한 비교 민감도를 가져옵니다.
값이 null인 경우 SensitivityOfComparison가 대신 사용됩니다. 두 비교된 객체의 전체 요소에 대한 삭제 및 삽입된 요소의 비율.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - 테이블에 대한 비교 민감도

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


텍스트를 단어로 분할하는 데 사용될 구분자 배열을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | char[] | 텍스트를 단어로 분할하기 위한 구분자 배열 |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 객체로 표시되는 비밀번호 저장 옵션을 가져옵니다.


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) 객체로 표시되는 비밀번호 저장 옵션을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | 비밀번호 저장 옵션 |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


[OriginalSize](../../com.groupdocs.comparison.options/originalsize) 객체로 표시되는 비교된 문서의 원본 크기를 가져옵니다.


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


[OriginalSize](../../com.groupdocs.comparison.options/originalsize) 객체로 표시되는 비교된 문서의 원본 크기를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | 문서의 원본 크기 |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 객체로 표시되는 다이어그램 문서의 마스터 페이지 설정을 가져옵니다.


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) 객체로 표시되는 다이어그램 문서의 마스터 페이지 설정을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | 다이어그램 마스터 페이지 설정 |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


디렉터리 비교가 활성화되어 있는지 여부를 나타내는 플래그를 반환합니다.


**Returns:**
boolean - 디렉터리 비교가 활성화된 경우 true, 그렇지 않으면 false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


디렉터리 비교를 활성화해야 하는지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | directoryCompare | boolean | 디렉터리 비교를 활성화해야 하면 true, 그렇지 않으면 false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


변경된 항목만 표시해야 하는지 여부를 나타내는 부울 값을 반환합니다.


**Returns:**
boolean - 변경된 항목만 표시해야 하면 true, 그렇지 않으면 false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


변경된 항목만 표시해야 하는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | showOnlyChanged | boolean | 변경된 항목만 표시할지 여부를 나타내는 boolean 값 |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


결과 폴더 비교 파일의 형식을 가져옵니다.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - 결과 폴더 비교 파일의 형식을 나타내는 FolderComparisonExtension

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


결과 폴더 비교 파일의 형식을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | 결과 폴더 비교 파일의 형식을 나타내는 FolderComparisonExtension |
|

