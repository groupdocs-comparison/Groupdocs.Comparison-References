---
title: Comparer class
second_title: GroupDocs.Comparison for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.comparison/comparer/
is_root: false
weight: 10
---

## Comparer class

Represents main class that controls the documents comparison process.



The Comparer type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#str) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) class with source file path. |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#str-groupdocs.comparison.options.CompareOptions) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) with source folder path and [`CompareOptions`](/comparison/python-net/groupdocs.comparison.options/compareoptions). |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#str-groupdocs.comparison.options.LoadOptions) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) with source file path and [`LoadOptions`](/comparison/python-net/groupdocs.comparison.options/loadoptions). |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#str-groupdocs.comparison.ComparerSettings) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) class with source file path and [`ComparerSettings`](/comparison/python-net/groupdocs.comparison/comparersettings). |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#str-groupdocs.comparison.options.LoadOptions-groupdocs.comparison.ComparerSettings) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) class with source file path, [`LoadOptions`](/comparison/python-net/groupdocs.comparison.options/loadoptions) and [`ComparerSettings`](/comparison/python-net/groupdocs.comparison/comparersettings). |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#io.RawIOBase) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) class with source document stream. |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#io.RawIOBase-groupdocs.comparison.options.LoadOptions) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) with source document stream and [`LoadOptions`](/comparison/python-net/groupdocs.comparison.options/loadoptions). |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#io.RawIOBase-groupdocs.comparison.ComparerSettings) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) class with source document stream and [`ComparerSettings`](/comparison/python-net/groupdocs.comparison/comparersettings). |
| [__init__](/comparison/python-net/groupdocs.comparison/comparer/__init__/#io.RawIOBase-groupdocs.comparison.options.LoadOptions-groupdocs.comparison.ComparerSettings) | Initializes new instance of [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer) class with document stream, [`LoadOptions`](/comparison/python-net/groupdocs.comparison.options/loadoptions) and [`ComparerSettings`](/comparison/python-net/groupdocs.comparison/comparersettings). |


### Properties
| Property | Description |
| :- | :- |
| [source](/comparison/python-net/groupdocs.comparison/comparer/source) | Source file that is being compared. |
| [source_folder](/comparison/python-net/groupdocs.comparison/comparer/source_folder) | Source folder that is being compared. |
| [targets](/comparison/python-net/groupdocs.comparison/comparer/targets) | List of target files to compare with source file. |
| [target_folder](/comparison/python-net/groupdocs.comparison/comparer/target_folder) | Target folder that is being compared. |
| [result](/comparison/python-net/groupdocs.comparison/comparer/result) | Result document. |


### Methods
| Method | Description |
| :- | :- |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#) | Compares documents without saving result with default options |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#str) | Compares documents and saves result to file path |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#io.RawIOBase) | Compares documents and saves result to file stream |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#str-groupdocs.comparison.options.CompareOptions) | Compares documents and saves result to file path |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#io.RawIOBase-groupdocs.comparison.options.CompareOptions) | Compares documents and saves result to file stream |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.CompareOptions) | Compares documents without saving result. |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#str-groupdocs.comparison.options.SaveOptions) | Compares documents and save result to file path |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#io.RawIOBase-groupdocs.comparison.options.SaveOptions) | Compares documents and save result to file stream |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#groupdocs.comparison.options.CompareOptions) | Compares documents without saving result. |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#io.RawIOBase-groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.CompareOptions) | Compares documents and saves result to a stream. |
| [compare](/comparison/python-net/groupdocs.comparison/comparer/compare/#str-groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.CompareOptions) | Compares documents and saves result to file path |
| [add](/comparison/python-net/groupdocs.comparison/comparer/add/#str) | Adds file to comparison. |
| [add](/comparison/python-net/groupdocs.comparison/comparer/add/#str-groupdocs.comparison.options.CompareOptions) | Adds folder to comparison. |
| [add](/comparison/python-net/groupdocs.comparison/comparer/add/#str-groupdocs.comparison.options.LoadOptions) | Adds file to comparison with loading options specified. |
| [add](/comparison/python-net/groupdocs.comparison/comparer/add/#io.RawIOBase) | Adds document stream to comparison. |
| [add](/comparison/python-net/groupdocs.comparison/comparer/add/#io.RawIOBase-groupdocs.comparison.options.LoadOptions) | Adds document stream to comparison with loading options specified. |
| [get_changes](/comparison/python-net/groupdocs.comparison/comparer/get_changes/#) | Gets list of changes between source and target file(s). |
| [get_changes](/comparison/python-net/groupdocs.comparison/comparer/get_changes/#groupdocs.comparison.options.GetChangeOptions) | Gets list of changes between source and target file(s). |
| [apply_changes](/comparison/python-net/groupdocs.comparison/comparer/apply_changes/#str-groupdocs.comparison.options.ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [apply_changes](/comparison/python-net/groupdocs.comparison/comparer/apply_changes/#io.RawIOBase-groupdocs.comparison.options.ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [apply_changes](/comparison/python-net/groupdocs.comparison/comparer/apply_changes/#str-groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [apply_changes](/comparison/python-net/groupdocs.comparison/comparer/apply_changes/#io.RawIOBase-groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.ApplyChangeOptions) | Accepts or rejects changes and applies them to resultant document. |
| [get_result_document_stream](/comparison/python-net/groupdocs.comparison/comparer/get_result_document_stream/#) | Gets the stream of result document, returns null if stream does not exist |
| [compare_directory](/comparison/python-net/groupdocs.comparison/comparer/compare_directory/#str-groupdocs.comparison.options.CompareOptions) | Compares directory and saves result to file path |
| [get_result_string](/comparison/python-net/groupdocs.comparison/comparer/get_result_string/#) | Get result string after comparison (For Text Comparison only). |



### See Also
* module [`groupdocs.comparison`](..)
* class [`CompareOptions`](/comparison/python-net/groupdocs.comparison.options/compareoptions)
* class [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer)
* class [`ComparerSettings`](/comparison/python-net/groupdocs.comparison/comparersettings)
* class [`LoadOptions`](/comparison/python-net/groupdocs.comparison.options/loadoptions)
