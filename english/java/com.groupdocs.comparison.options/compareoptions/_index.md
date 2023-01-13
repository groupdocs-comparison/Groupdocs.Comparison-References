---
title: CompareOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows to set different compare options.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Allows to set different compare options.
## Constructors

| Constructor | Description |
| --- | --- |
| [CompareOptions()](#CompareOptions--) | Initializes a new instance of the [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [isLeaveGaps()](#isLeaveGaps--) | Indicates whether to display empty lines instead of inserted / deleted components in the final document or not (used with ShowInsertedContent or ShowDeletedContent properties). |
| [setLeaveGaps(boolean leaveGaps)](#setLeaveGaps-boolean-) | Indicates whether to display empty lines instead of inserted / deleted components in the final document or not (used with ShowInsertedContent or ShowDeletedContent properties). |
| [getComparisonType()](#getComparisonType--) | File type to compare documents as, ComparisonType Disables [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions\#getFileType--) |
| [setComparisonType(int comparisonType)](#setComparisonType-int-) | File type to compare documents as, ComparisonType Disables [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions\#getFileType--) |
| [getPaperSize()](#getPaperSize--) | Gets or sets the result document paper size. |
| [setPaperSize(int value)](#setPaperSize-int-) | Gets or sets the result document paper size. |
| [isShowDeletedContent()](#isShowDeletedContent--) | Indicates whether to show deleted components in resultant document or not. |
| [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Indicates whether to show deleted components in resultant document or not. |
| [isShowInsertedContent()](#isShowInsertedContent--) | Indicates whether to show inserted components in resultant document or not. |
| [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Indicates whether to show inserted components in resultant document or not. |
| [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Indicates whether to add summary page with detected changes statistics to resultant document or not. |
| [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Indicates whether to add summary page with detected changes statistics to resultant document or not. |
| [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Indicates whether to add extended file comparison information to the summary page or not. |
| [setExtendedSummaryPage(boolean extendedSummaryPage)](#setExtendedSummaryPage-boolean-) | Indicates whether to add extended file comparison information to the summary page or not. |
| [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Indicates whether to leave in the resulting document only a page with statistics of detected changes in the resulting document or not. |
| [setShowOnlySummaryPage(boolean auto_ShowOnlySummaryPage)](#setShowOnlySummaryPage-boolean-) | Indicates whether to leave in the resulting document only a page with statistics of detected changes in the resulting document or not. |
| [isDetectStyleChanges()](#isDetectStyleChanges--) | Indicates whether to detect style changes or not. |
| [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Indicates whether to detect style changes or not. |
| [isMarkNestedContent()](#isMarkNestedContent--) | Gets or sets a value indicating whether to mark the children of the deleted or inserted element as deleted or inserted. |
| [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Gets or sets a value indicating whether to mark the children of the deleted or inserted element as deleted or inserted. |
| [isCalculateCoordinates()](#isCalculateCoordinates--) | Indicates whether to calculate coordinates for changed components. |
| [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Indicates whether to calculate coordinates for changed components. |
| [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Control to turn on comparison of header/footer contents. |
| [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Control to turn on comparison of header/footer contents. |
| [getDetalisationLevel()](#getDetalisationLevel--) | Gets or sets the comparison detail level. |
| [setDetalisationLevel(int value)](#setDetalisationLevel-int-) | Gets or sets the comparison detail level. |
| [isMarkChangedContent()](#isMarkChangedContent--) | Indicates whether to use frames for shapes in Word Processing and for rectangles in Image documents. |
| [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Indicates whether to use frames for shapes in Word Processing and for rectangles in Image documents. |
| [getInsertedItemStyle()](#getInsertedItemStyle--) | Describes style for inserted components. |
| [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Describes style for inserted components. |
| [getDeletedItemStyle()](#getDeletedItemStyle--) | Describes style for deleted components. |
| [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Describes style for deleted components. |
| [getChangedItemStyle()](#getChangedItemStyle--) | Describes style for changed components. |
| [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Describes style for changed components. |
| [isCompareBookmarks()](#isCompareBookmarks--) | Control to turn on comparison of bookmarks in Word format. |
| [setCompareBookmarks(boolean compareBookmarks)](#setCompareBookmarks-boolean-) | Sets compare bookmarks. |
| [isCompareVariableProperty()](#isCompareVariableProperty--) | Control to turn on comparison of variables properties in Word format. |
| [setCompareVariableProperty(boolean compareVariableProperty)](#setCompareVariableProperty-boolean-) | Sets compare variable property. |
| [isCompareDocumentProperty()](#isCompareDocumentProperty--) | Control to turn on comparison of built and custom properties in Word format. |
| [setCompareDocumentProperty(boolean compareDocumentProperty)](#setCompareDocumentProperty-boolean-) | Control to turn on comparison of built and custom properties in Word format. |
| [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Gets or sets a sensitivity of comparison. |
| [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Sets sensitivity of comparison. |
| [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Gets or sets an array of delimiters to split text into words. |
| [getPasswordSaveOption()](#getPasswordSaveOption--) | Gets or sets the password save option. |
| [setPasswordSaveOption(int value)](#setPasswordSaveOption-int-) | Gets or sets the password save option. |
| [getOriginalSize()](#getOriginalSize--) | Get or sets the original sizes of compared documents. |
| [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Get or sets the original sizes of compared documents. |
| [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Gets or sets the path value for master or use compare without path of master. |
| [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Gets or sets the path value for master or use compare without path of master. |
| [isShowRevisions()](#isShowRevisions--) | Indicates whether to display others revisions in the resulting document or not. |
| [setShowRevisions(boolean showRevisions)](#setShowRevisions-boolean-) | Indicates whether to display others revisions in the resulting document or not. |
| [isWordTrackChanges()](#isWordTrackChanges--) | Control to turn on comparison of Words Track Revisions. |
| [setWordTrackChanges(boolean wordTrackChanges)](#setWordTrackChanges-boolean-) | Control to turn on comparison of Words Track Revisions. |
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Initializes a new instance of the [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) class.

### isLeaveGaps() {#isLeaveGaps--}
```
public boolean isLeaveGaps()
```


Indicates whether to display empty lines instead of inserted / deleted components in the final document or not (used with ShowInsertedContent or ShowDeletedContent properties).

**Returns:**
boolean - enabled or not
### setLeaveGaps(boolean leaveGaps) {#setLeaveGaps-boolean-}
```
public void setLeaveGaps(boolean leaveGaps)
```


Indicates whether to display empty lines instead of inserted / deleted components in the final document or not (used with ShowInsertedContent or ShowDeletedContent properties).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leaveGaps | boolean | enabled or not |

### getComparisonType() {#getComparisonType--}
```
public int getComparisonType()
```


File type to compare documents as, ComparisonType Disables [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions\#getFileType--)

**Returns:**
int - file type to compare documents as
### setComparisonType(int comparisonType) {#setComparisonType-int-}
```
public void setComparisonType(int comparisonType)
```


File type to compare documents as, ComparisonType Disables [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions\#getFileType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comparisonType | int | file type to compare documents as |

### getPaperSize() {#getPaperSize--}
```
public final int getPaperSize()
```


Gets or sets the result document paper size.

**Returns:**
int - the paper size
### setPaperSize(int value) {#setPaperSize-int-}
```
public final void setPaperSize(int value)
```


Gets or sets the result document paper size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Indicates whether to show deleted components in resultant document or not.

**Returns:**
boolean - the boolean
### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Indicates whether to show deleted components in resultant document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Indicates whether to show inserted components in resultant document or not.

**Returns:**
boolean - the boolean
### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Indicates whether to show inserted components in resultant document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Indicates whether to add summary page with detected changes statistics to resultant document or not.

**Returns:**
boolean - the generate summary page
### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Indicates whether to add summary page with detected changes statistics to resultant document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Indicates whether to add extended file comparison information to the summary page or not.

**Returns:**
boolean - the boolean
### setExtendedSummaryPage(boolean extendedSummaryPage) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean extendedSummaryPage)
```


Indicates whether to add extended file comparison information to the summary page or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extendedSummaryPage | boolean | the extended summary page |

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Indicates whether to leave in the resulting document only a page with statistics of detected changes in the resulting document or not.

**Returns:**
boolean - the boolean
### setShowOnlySummaryPage(boolean auto_ShowOnlySummaryPage) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean auto_ShowOnlySummaryPage)
```


Indicates whether to leave in the resulting document only a page with statistics of detected changes in the resulting document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| auto_ShowOnlySummaryPage | boolean | the auto show only summary page |

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Indicates whether to detect style changes or not.

**Returns:**
boolean - the boolean
### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Indicates whether to detect style changes or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Gets or sets a value indicating whether to mark the children of the deleted or inserted element as deleted or inserted.

**Returns:**
boolean - the boolean
### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Gets or sets a value indicating whether to mark the children of the deleted or inserted element as deleted or inserted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Indicates whether to calculate coordinates for changed components.

**Returns:**
boolean - the boolean
### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Indicates whether to calculate coordinates for changed components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Control to turn on comparison of header/footer contents.

**Returns:**
boolean - the boolean
### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Control to turn on comparison of header/footer contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final int getDetalisationLevel()
```


Gets or sets the comparison detail level.

**Returns:**
int - the detalisation level
### setDetalisationLevel(int value) {#setDetalisationLevel-int-}
```
public final void setDetalisationLevel(int value)
```


Gets or sets the comparison detail level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Indicates whether to use frames for shapes in Word Processing and for rectangles in Image documents.

**Returns:**
boolean - the boolean
### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Indicates whether to use frames for shapes in Word Processing and for rectangles in Image documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value |

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Describes style for inserted components.

**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - the inserted item style
### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Describes style for inserted components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | the value |

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Describes style for deleted components.

**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - the deleted item style
### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Describes style for deleted components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | the value |

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Describes style for changed components.

**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - the changed item style
### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Describes style for changed components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | the value |

### isCompareBookmarks() {#isCompareBookmarks--}
```
public boolean isCompareBookmarks()
```


Control to turn on comparison of bookmarks in Word format.

**Returns:**
boolean - the boolean
### setCompareBookmarks(boolean compareBookmarks) {#setCompareBookmarks-boolean-}
```
public void setCompareBookmarks(boolean compareBookmarks)
```


Sets compare bookmarks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compareBookmarks | boolean | the compare bookmarks |

### isCompareVariableProperty() {#isCompareVariableProperty--}
```
public boolean isCompareVariableProperty()
```


Control to turn on comparison of variables properties in Word format.

**Returns:**
boolean - the boolean
### setCompareVariableProperty(boolean compareVariableProperty) {#setCompareVariableProperty-boolean-}
```
public void setCompareVariableProperty(boolean compareVariableProperty)
```


Sets compare variable property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compareVariableProperty | boolean | the compare variable property |

### isCompareDocumentProperty() {#isCompareDocumentProperty--}
```
public boolean isCompareDocumentProperty()
```


Control to turn on comparison of built and custom properties in Word format.

**Returns:**
boolean - the boolean
### setCompareDocumentProperty(boolean compareDocumentProperty) {#setCompareDocumentProperty-boolean-}
```
public void setCompareDocumentProperty(boolean compareDocumentProperty)
```


Control to turn on comparison of built and custom properties in Word format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compareDocumentProperty | boolean | the compare document property |

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Gets or sets a sensitivity of comparison.

Value: The percentage of deleted and inserted elements of two compared objects in relation to all elements of these objects. if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted. Min value - 0% => The comparison doesn't occur for any length of the common subsequence of two compared object. Default value - 75% => Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75. Max value - 100% => The comparison occurs at any length of the common subsequence of two compared objects.

**Returns:**
int - the sensitivity of comparison
### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Sets sensitivity of comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Gets or sets an array of delimiters to split text into words.

Value: The words separator chars.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | the value |

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final int getPasswordSaveOption()
```


Gets or sets the password save option.

Value: The password save option.

**Returns:**
int - the password save option
### setPasswordSaveOption(int value) {#setPasswordSaveOption-int-}
```
public final void setPasswordSaveOption(int value)
```


Gets or sets the password save option.

Value: The password save option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the value |

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Get or sets the original sizes of compared documents.

**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size
### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Get or sets the original sizes of compared documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | the value |

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Gets or sets the path value for master or use compare without path of master. This option only for Diagram.

Value: The master option for Diagram.

**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master setting
### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Gets or sets the path value for master or use compare without path of master. This option only for Diagram.

Value: The master option for Diagram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | the value |

### isShowRevisions() {#isShowRevisions--}
```
public boolean isShowRevisions()
```


Indicates whether to display others revisions in the resulting document or not.

**Returns:**
boolean - the boolean
### setShowRevisions(boolean showRevisions) {#setShowRevisions-boolean-}
```
public void setShowRevisions(boolean showRevisions)
```


Indicates whether to display others revisions in the resulting document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| showRevisions | boolean | the show revisions |

### isWordTrackChanges() {#isWordTrackChanges--}
```
public boolean isWordTrackChanges()
```


Control to turn on comparison of Words Track Revisions.

**Returns:**
boolean - Words Track Revisions
### setWordTrackChanges(boolean wordTrackChanges) {#setWordTrackChanges-boolean-}
```
public void setWordTrackChanges(boolean wordTrackChanges)
```


Control to turn on comparison of Words Track Revisions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wordTrackChanges | boolean | Words Track Revisions |

