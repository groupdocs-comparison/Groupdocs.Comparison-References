---
title: Comparer
second_title: GroupDocs.Comparison for .NET API Reference
description: Represents main class that controls the documents comparison process.
type: docs
weight: 100
url: /net/groupdocs.comparison/comparer/
---
## Comparer class

Represents main class that controls the documents comparison process.

```csharp
public class Comparer : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Initializes new instance of [`Comparer`](../comparer) class with source document stream. |
| [Comparer](comparer#constructor_4)(string) | Initializes new instance of [`Comparer`](../comparer) class with source file path. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Initializes new instance of [`Comparer`](../comparer) class with source document stream and [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Initializes new instance of [`Comparer`](../comparer) with source document stream and [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Folder comparer. |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Initializes new instance of [`Comparer`](../comparer) class with source file path and [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Initializes new instance of [`Comparer`](../comparer) with source file path and [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Initializes new instance of [`Comparer`](../comparer) class with document stream, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) and [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Initializes new instance of [`Comparer`](../comparer) class with source file path, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) and [`ComparerSettings`](../comparersettings). |

## Properties

| Name | Description |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Source file that is being compared. |
| [sourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Source folder that is being compared. |
| [targetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Target folder that is being compared. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | List of target files to compare with source file. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Adds document stream to comparison. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Adds file to comparison. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Adds document stream to comparison with loading options specified. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Adds folder to comparison. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Adds file to comparison with loading options specified. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Compares documents without saving result with default options |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Compares documents without saving result. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Compares documents and saves result to file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Compares documents and saves result to file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Compares documents without saving result. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Compares documents and saves result to file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Compares documents and save result to file stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Compares documents and saves result to file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Compares documents and save result to file path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Compares documents and saves result to a stream. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Compares documents and saves result to file path |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Compares directory and saves result to file path |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Releases resources. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Gets list of changes between source and target file(s). |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Gets list of changes between source and target file(s). |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Get result string after comparison (For Text Comparison only). |

### See Also

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
