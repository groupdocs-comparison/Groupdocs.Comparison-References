---
title: CompareOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows configuring the process of document comparison.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Allows configuring the process of document comparison.

Example usage:

```

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
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CompareOptions()](#CompareOptions--) | Initializes a new instance of the CompareOptions class. |
| [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | Initializes a new instance of the CompareOptions class with settings for different styles. |
## Methods

| Method | Description |
| --- | --- |
| [getUserMasterPath()](#getUserMasterPath--) | Gets the path to the user master's template for Diagrams. |
| [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Sets the path to the user master's template for Diagrams. |
| [getRevisionAuthorName()](#getRevisionAuthorName--) | Gets or sets revision author name. |
| [setRevisionAuthorName(String revisionAuthorName)](#setRevisionAuthorName-java.lang.String-) | Sets the revision author name. |
| [isLeaveGaps()](#isLeaveGaps--) | Gets a flag that determines whether to leave empty lines instead of inserted/deleted components or not. |
| [setLeaveGaps(boolean value)](#setLeaveGaps-boolean-) | Sets a flag that determines whether to leave empty lines instead of inserted/deleted components or not. |
| [getComparisonType()](#getComparisonType--) | Gets a type of source and target documents as [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object so that Comparison will know how to compare them. |
| [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Sets a type of source and target documents as [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object so that Comparison will know how to compare them. |
| [getPaperSize()](#getPaperSize--) | Gets a size of a paper in result document as [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object. |
| [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Sets a size of a paper in result document as [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object. |
| [isShowDeletedContent()](#isShowDeletedContent--) | Gets a flag that indicates whether to show deleted components in resultant document or not. |
| [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Sets a flag that indicates whether to show deleted components in resultant document or not. |
| [isShowInsertedContent()](#isShowInsertedContent--) | Gets a flag that indicates whether to show inserted components in resultant document or not. |
| [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Sets a flag that indicates whether to show inserted components in resultant document or not. |
| [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Gets a flag that indicates whether to add summary page with detected changes statistics to resultant document or not. |
| [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Sets a flag that indicates whether to add summary page with detected changes statistics to resultant document or not. |
| [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Gets a flag that indicates whether to add extended file comparison information to the summary page or not. |
| [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Sets a flag that indicates whether to add extended file comparison information to the summary page or not. |
| [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Gets a flag that indicates whether to leave in the resulting document only a page with statistics of detected changes or not. |
| [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Sets a flag that indicates whether to leave in the resulting document only a page with statistics of detected changes or not. |
| [isDetectStyleChanges()](#isDetectStyleChanges--) | Gets a flag that indicates whether to detect style changes or not. |
| [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Sets a flag that indicates whether to detect style changes or not. |
| [isMarkNestedContent()](#isMarkNestedContent--) | Gets a flag that indicates whether to mark the children of the deleted or inserted elements as deleted or inserted. |
| [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Sets a flag that indicates whether to mark the children of the deleted or inserted elements as deleted or inserted. |
| [isCalculateCoordinates()](#isCalculateCoordinates--) | Gets a flag that indicates whether to calculate coordinates for changed components. |
| [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Sets a flag that indicates whether to calculate coordinates for changed components. |
| [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Gets a flag that indicates whether to compare header/footer contents. |
| [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Sets a flag that indicates whether to compare header/footer contents. |
| [getDetalisationLevel()](#getDetalisationLevel--) | Gets a level of comparison detalization represented as [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
| [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Sets a level of comparison detalization represented as [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel). |
| [isMarkChangedContent()](#isMarkChangedContent--) | Gets a flag that indicates whether frames for shapes in Word Processing and for rectangles in Image documents will be used. |
| [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Sets a flag that indicates whether frames for shapes in Word Processing and for rectangles in Image documents will be used. |
| [getInsertedItemStyle()](#getInsertedItemStyle--) | Gets a style settings that will be applied to inserted items. |
| [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Sets a style settings that will be applied to inserted items. |
| [getDeletedItemStyle()](#getDeletedItemStyle--) | Gets a style settings that will be applied to deleted items. |
| [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Sets a style settings that will be applied to deleted items. |
| [getChangedItemStyle()](#getChangedItemStyle--) | Gets a style settings that will be applied to changed items. |
| [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Sets a style settings that will be applied to changed items. |
| [isCompareBookmarks()](#isCompareBookmarks--) | Gets a flag that indicates whether bookmarks in Word documents will be compared. |
| [setCompareBookmarks(boolean value)](#setCompareBookmarks-boolean-) | Sets a flag that indicates whether bookmarks in Word documents should be compared. |
| [isCompareVariableProperty()](#isCompareVariableProperty--) | Gets a flag that indicates whether variables properties in Word documents will be compared. |
| [setCompareVariableProperty(boolean value)](#setCompareVariableProperty-boolean-) | Sets a flag that indicates whether variables properties in Word documents should be compared. |
| [isCompareDocumentProperty()](#isCompareDocumentProperty--) | Gets a flag that indicates whether built and custom properties in Word documents will be compared. |
| [setCompareDocumentProperty(boolean value)](#setCompareDocumentProperty-boolean-) | Sets a flag that indicates whether built and custom properties in Word documents should be compared. |
| [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Gets a sensitivity of comparison. |
| [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Sets a sensitivity of comparison. |
| [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Sets an array of delimiters which will be used to split text into words. |
| [getPasswordSaveOption()](#getPasswordSaveOption--) | Gets a password save option represented by [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object. |
| [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | Sets a password save option represented by [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object. |
| [getOriginalSize()](#getOriginalSize--) | Gets an original sizes of compared documents represented by [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object. |
| [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | Sets an original sizes of compared documents represented by [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object. |
| [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Gets a setting of master page for Diagram documents represented by [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object. |
| [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Sets a setting of master page for Diagram documents represented by [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object. |
| [isShowRevisions()](#isShowRevisions--) | Gets a flag that indicates whether others revisions in the resulting document will be displayed. |
| [setShowRevisions(boolean value)](#setShowRevisions-boolean-) | Sets a flag that indicates whether others revisions in the resulting document should be displayed. |
| [isWordTrackChanges()](#isWordTrackChanges--) | Gets a flag that indicates whether Words Track Revisions will be compared. |
| [setWordTrackChanges(boolean value)](#setWordTrackChanges-boolean-) | Sets a flag that indicates whether Words Track Revisions should be compared. |
| [isDirectoryCompare()](#isDirectoryCompare--) | Returns a flag that indicates whether directory comparison is enabled. |
| [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Sets a flag that indicates whether directory comparison should be enabled. |
| [isShowOnlyChanged()](#isShowOnlyChanged--) | Returns a boolean value that indicates whether only changed items should be displayed. |
| [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Sets the value indicating whether only changed items should be displayed. |
| [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Gets the format of the resulting folder comparison file. |
| [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Sets the format of the resulting folder comparison file. |
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


Initializes a new instance of the CompareOptions class.

### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


Initializes a new instance of the CompareOptions class with settings for different styles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Style settings for inserted items |
| deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Style settings for deleted items |
| changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Style settings for changed style items |

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Gets the path to the user master's template for Diagrams.

**Returns:**
java.lang.String - The path to the user master's template for Diagrams.
### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Sets the path to the user master's template for Diagrams.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userMasterPath | java.lang.String | The path to the user master's template for Diagrams. |

### getRevisionAuthorName() {#getRevisionAuthorName--}
```
public String getRevisionAuthorName()
```


Gets or sets revision author name. Enabled if not null.

**Returns:**
java.lang.String - The revision author name.
### setRevisionAuthorName(String revisionAuthorName) {#setRevisionAuthorName-java.lang.String-}
```
public void setRevisionAuthorName(String revisionAuthorName)
```


Sets the revision author name. Enabled if not null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| revisionAuthorName | java.lang.String | The new revision author name to be set. |

### isLeaveGaps() {#isLeaveGaps--}
```
public boolean isLeaveGaps()
```


Gets a flag that determines whether to leave empty lines instead of inserted/deleted components or not.

Whether to display empty lines instead of inserted/deleted components in the final document or not. Used with [isShowInsertedContent()](../../com.groupdocs.comparison.options/compareoptions\#isShowInsertedContent--) or [isShowDeletedContent()](../../com.groupdocs.comparison.options/compareoptions\#isShowDeletedContent--) properties.

**Returns:**
boolean - true if empty lines should be displayed instead of inserted/deleted components, otherwise false
### setLeaveGaps(boolean value) {#setLeaveGaps-boolean-}
```
public void setLeaveGaps(boolean value)
```


Sets a flag that determines whether to leave empty lines instead of inserted/deleted components or not.

Whether to display empty lines instead of inserted/deleted components in the final document or not. Used with [isShowInsertedContent()](../../com.groupdocs.comparison.options/compareoptions\#isShowInsertedContent--) or [isShowDeletedContent()](../../com.groupdocs.comparison.options/compareoptions\#isShowDeletedContent--) properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if empty lines should be displayed instead of inserted/deleted components, otherwise false |

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Gets a type of source and target documents as [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object so that Comparison will know how to compare them.

When this option is set, [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions\#getFileType--) option will be omitted.

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents
### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Sets a type of source and target documents as [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) object so that Comparison will know how to compare them.

When this option is set, [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions\#setFileType-FileType-) option will be omitted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | The type of source and target documents |

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Gets a size of a paper in result document as [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object.

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document
### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Sets a size of a paper in result document as [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | The size of a paper in result document |

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Gets a flag that indicates whether to show deleted components in resultant document or not.

**Returns:**
boolean - true if deleted components in resultant document will be shown, otherwise false
### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Sets a flag that indicates whether to show deleted components in resultant document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if deleted components in resultant document should be shown, otherwise false |

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Gets a flag that indicates whether to show inserted components in resultant document or not.

**Returns:**
boolean - true if inserted components in resultant document should be shown, otherwise false
### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Sets a flag that indicates whether to show inserted components in resultant document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if inserted components in resultant document should be shown, otherwise false |

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Gets a flag that indicates whether to add summary page with detected changes statistics to resultant document or not.

**Returns:**
boolean - true if summary page will be added, otherwise false
### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Sets a flag that indicates whether to add summary page with detected changes statistics to resultant document or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if summary page should be added, otherwise false |

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Gets a flag that indicates whether to add extended file comparison information to the summary page or not.

**Returns:**
boolean - true if extended file comparison information will be added to summary page, otherwise false
### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Sets a flag that indicates whether to add extended file comparison information to the summary page or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if extended file comparison information should be added to summary page, otherwise false |

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Gets a flag that indicates whether to leave in the resulting document only a page with statistics of detected changes or not.

**Returns:**
boolean - true if in the resulting document only a page with statistics of detected changes will be left, otherwise false
### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Sets a flag that indicates whether to leave in the resulting document only a page with statistics of detected changes or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if in the resulting document only a page with statistics of detected changes should be left, otherwise false |

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Gets a flag that indicates whether to detect style changes or not.

**Returns:**
boolean - true if style changes will be detected, otherwise false
### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Sets a flag that indicates whether to detect style changes or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if style changes should be detected, otherwise false |

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Gets a flag that indicates whether to mark the children of the deleted or inserted elements as deleted or inserted.

**Returns:**
boolean - true if the children of the deleted or inserted elements will be marked as deleted or inserted, otherwise false
### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Sets a flag that indicates whether to mark the children of the deleted or inserted elements as deleted or inserted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the children of the deleted or inserted elements should be marked as deleted or inserted, otherwise false |

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Gets a flag that indicates whether to calculate coordinates for changed components.

**Returns:**
boolean - true if coordinates for changed components will be calculated, otherwise false
### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Sets a flag that indicates whether to calculate coordinates for changed components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if coordinates for changed components should be calculated, otherwise false |

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Gets a flag that indicates whether to compare header/footer contents.

**Returns:**
boolean - true if header/footer contents will be compared, otherwise false
### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Sets a flag that indicates whether to compare header/footer contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if header/footer contents should be compared, otherwise false |

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Gets a level of comparison detalization represented as [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).

Default value is [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel\#LOW).

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization
### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Sets a level of comparison detalization represented as [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel).

Default value is [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel\#LOW)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | The level of comparison detalization |

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Gets a flag that indicates whether frames for shapes in Word Processing and for rectangles in Image documents will be used.

**Returns:**
boolean - true if frames will be used, otherwise false
### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Sets a flag that indicates whether frames for shapes in Word Processing and for rectangles in Image documents will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if frames should be used, otherwise false |

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Gets a style settings that will be applied to inserted items.

**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items
### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Sets a style settings that will be applied to inserted items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Style settings of inserted items |

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Gets a style settings that will be applied to deleted items.

**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items
### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Sets a style settings that will be applied to deleted items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Style settings of deleted items |

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Gets a style settings that will be applied to changed items.

**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items
### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Sets a style settings that will be applied to changed items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Style settings of changed items |

### isCompareBookmarks() {#isCompareBookmarks--}
```
public boolean isCompareBookmarks()
```


Gets a flag that indicates whether bookmarks in Word documents will be compared.

**Returns:**
boolean - true if bookmarks in Word documents will be compared, otherwise false
### setCompareBookmarks(boolean value) {#setCompareBookmarks-boolean-}
```
public void setCompareBookmarks(boolean value)
```


Sets a flag that indicates whether bookmarks in Word documents should be compared.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if bookmarks in Word documents should be compared, otherwise false |

### isCompareVariableProperty() {#isCompareVariableProperty--}
```
public boolean isCompareVariableProperty()
```


Gets a flag that indicates whether variables properties in Word documents will be compared.

**Returns:**
boolean - true if variables properties in Word documents will be compared, otherwise false
### setCompareVariableProperty(boolean value) {#setCompareVariableProperty-boolean-}
```
public void setCompareVariableProperty(boolean value)
```


Sets a flag that indicates whether variables properties in Word documents should be compared.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if variables properties in Word documents should be compared, otherwise false |

### isCompareDocumentProperty() {#isCompareDocumentProperty--}
```
public boolean isCompareDocumentProperty()
```


Gets a flag that indicates whether built and custom properties in Word documents will be compared.

**Returns:**
boolean - true if built and custom properties in Word documents will be compared, otherwise false
### setCompareDocumentProperty(boolean value) {#setCompareDocumentProperty-boolean-}
```
public void setCompareDocumentProperty(boolean value)
```


Sets a flag that indicates whether built and custom properties in Word documents should be compared.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if built and custom properties in Word documents should be compared, otherwise false |

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Gets a sensitivity of comparison.

The percentage of deleted and inserted elements of two compared objects in relation to all elements of these objects.

 *  If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
 *  Min value - 0% => The comparison doesn't occur for any length of the common subsequence of two compared object.
 *  Default value - 75% => Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
 *  Max value - 100% => The comparison occurs at any length of the common subsequence of two compared objects.

**Returns:**
int - the sensitivity of comparison
### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Sets a sensitivity of comparison.

The percentage of deleted and inserted elements of two compared objects in relation to all elements of these objects.

 *  If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
 *  Min value - 0% => The comparison doesn't occur for any length of the common subsequence of two compared object.
 *  Default value - 75% => Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
 *  Max value - 100% => The comparison occurs at any length of the common subsequence of two compared objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sensitivity of comparison |

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Sets an array of delimiters which will be used to split text into words.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | The array of delimiters to split text into words |

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


Gets a password save option represented by [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object.

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option
### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


Sets a password save option represented by [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | The password save option |

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


Gets an original sizes of compared documents represented by [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object.

**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents
### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


Sets an original sizes of compared documents represented by [OriginalSize](../../com.groupdocs.comparison.options/originalsize) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | The original size of documents |

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Gets a setting of master page for Diagram documents represented by [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object.

**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting
### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Sets a setting of master page for Diagram documents represented by [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | The diagram master page setting |

### isShowRevisions() {#isShowRevisions--}
```
public boolean isShowRevisions()
```


Gets a flag that indicates whether others revisions in the resulting document will be displayed.

**Returns:**
boolean - value true if others revisions in the resulting document will be displayed, otherwise false
### setShowRevisions(boolean value) {#setShowRevisions-boolean-}
```
public void setShowRevisions(boolean value)
```


Sets a flag that indicates whether others revisions in the resulting document should be displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if others revisions in the resulting document should be displayed, otherwise false |

### isWordTrackChanges() {#isWordTrackChanges--}
```
public boolean isWordTrackChanges()
```


Gets a flag that indicates whether Words Track Revisions will be compared.

**Returns:**
boolean - true if Words Track Revisions will be compared, otherwise false
### setWordTrackChanges(boolean value) {#setWordTrackChanges-boolean-}
```
public void setWordTrackChanges(boolean value)
```


Sets a flag that indicates whether Words Track Revisions should be compared.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if Words Track Revisions should be compared, otherwise false |

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Returns a flag that indicates whether directory comparison is enabled.

**Returns:**
boolean - true if directory comparison is enabled, otherwise false
### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Sets a flag that indicates whether directory comparison should be enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| directoryCompare | boolean | true if directory comparison should be enabled, otherwise false |

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Returns a boolean value that indicates whether only changed items should be displayed.

**Returns:**
boolean - true if only changed items should be displayed, otherwise false
### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Sets the value indicating whether only changed items should be displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| showOnlyChanged | boolean | the boolean value indicating whether only changed items should be displayed |

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Gets the format of the resulting folder comparison file.

**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - the FolderComparisonExtension representing the format of the resulting folder comparison file
### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Sets the format of the resulting folder comparison file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | the FolderComparisonExtension representing the format of the resulting folder comparison file |

