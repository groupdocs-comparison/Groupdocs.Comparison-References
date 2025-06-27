---
title: compare method
second_title: GroupDocs.Comparison for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.comparison/comparer/compare/
is_root: false
weight: 40
---

## compare {#}

Compares documents without saving result with default options



```python
def compare(self):
    ...
```




## compare {#str}

Compares documents and saves result to file path



```python
def compare(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | Result document path |


## compare {#io.RawIOBase}

Compares documents and saves result to file stream



```python
def compare(self, document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | Result document stream |


## compare {#groupdocs.comparison.options.CompareOptions}

Compares documents without saving result.



```python
def compare(self, compare_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| compare_options | groupdocs.comparison.options.CompareOptions | Compare options |


## compare {#str-groupdocs.comparison.options.CompareOptions}

Compares documents and saves result to file path



```python
def compare(self, file_path, compare_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | Result document file path |
| compare_options | groupdocs.comparison.options.CompareOptions | Compare options |


## compare {#io.RawIOBase-groupdocs.comparison.options.CompareOptions}

Compares documents and saves result to file stream



```python
def compare(self, document, compare_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | Result document stream |
| compare_options | groupdocs.comparison.options.CompareOptions | Compare options |


## compare {#groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.CompareOptions}

Compares documents without saving result.



```python
def compare(self, save_options, compare_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| save_options | groupdocs.comparison.options.SaveOptions | Save options |
| compare_options | groupdocs.comparison.options.CompareOptions | Compare options |


## compare {#str-groupdocs.comparison.options.SaveOptions}

Compares documents and save result to file path



```python
def compare(self, file_path, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | Result document file path |
| save_options | groupdocs.comparison.options.SaveOptions | Save options |


## compare {#io.RawIOBase-groupdocs.comparison.options.SaveOptions}

Compares documents and save result to file stream



```python
def compare(self, document, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | Result document stream |
| save_options | groupdocs.comparison.options.SaveOptions | Save options |


## compare {#io.RawIOBase-groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.CompareOptions}

Compares documents and saves result to a stream.



```python
def compare(self, stream, save_options, compare_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | Result document stream |
| save_options | groupdocs.comparison.options.SaveOptions | Save options |
| compare_options | groupdocs.comparison.options.CompareOptions | Compare options |


## compare {#str-groupdocs.comparison.options.SaveOptions-groupdocs.comparison.options.CompareOptions}

Compares documents and saves result to file path



```python
def compare(self, file_path, save_options, compare_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | Result document file path |
| save_options | groupdocs.comparison.options.SaveOptions | Save options |
| compare_options | groupdocs.comparison.options.CompareOptions | Compare options |



### See Also
* module [`groupdocs.comparison`](../../)
* class [`Comparer`](/comparison/python-net/groupdocs.comparison/comparer)
