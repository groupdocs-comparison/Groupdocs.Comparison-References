---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "提供在比较过程中生成文档预览的选项。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

提供在比较过程中生成文档预览的选项。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | 初始化 PreviewOptions 类的新实例，指定 Delegates.CreatePageStream 函数。 |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | 初始化 PreviewOptions 类的新实例，指定 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) 函数。 |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | 初始化 PreviewOptions 类的新实例，指定 Delegates.CreatePageStream 和 Delegates.ReleasePageStream 函数。 |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | 初始化 PreviewOptions 类的新实例，指定 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) 和 [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) 函数。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | 获取用于创建输出页面预览流的函数。 |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | 设置用于创建输出页面预览流的函数。 |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | 设置用于创建输出页面预览流的函数。 |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | 获取用于释放输出页面预览流的函数。 |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | 获取用于释放输出页面预览流的函数。 |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | 设置用于释放输出页面预览流的函数。 |
|
|  | [getWidth()](#getWidth--) | 获取预览图像的宽度。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 设置预览图像的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取预览图像的高度。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 设置预览图像的高度。 |
|
|  | [getPageNumbers()](#getPageNumbers--) | 获取将生成预览图像的页码数组。 |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 设置将生成预览图像的页码数组。 |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 获取预览图像的格式。 |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | 设置预览图像的格式。 |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


初始化 PreviewOptions 类的新实例，指定 Delegates.CreatePageStream 函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 用于创建输出页预览流的函数。 |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


初始化 PreviewOptions 类的新实例，指定 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) 函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 用于创建输出页预览流的函数。 |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


初始化 PreviewOptions 类的新实例，指定 Delegates.CreatePageStream 和 Delegates.ReleasePageStream 函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 用于创建输出页预览流的函数。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | 用于释放输出页预览流的函数。 |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


初始化 PreviewOptions 类的新实例，指定 [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) 和 [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) 函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 用于创建输出页预览流的函数。 |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | 用于释放输出页预览流的函数。 |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


获取用于创建输出页面预览流的函数。


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


设置用于创建输出页面预览流的函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | 用于创建输出页预览流的函数。 |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


设置用于创建输出页面预览流的函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | 用于创建输出页预览流的函数。 |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


获取用于释放输出页面预览流的函数。


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


获取用于释放输出页面预览流的函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | 用于释放输出页预览流的函数。 |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


设置用于释放输出页面预览流的函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | 用于释放输出页预览流的函数。 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取预览图像的宽度。


**Returns:**
int - 预览图像的宽度。

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置预览图像的宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 预览图像的宽度。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取预览图像的高度。


**Returns:**
int - 预览图像的高度。

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置预览图像的高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 预览图像的高度。 |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


获取将生成预览图像的页码数组。


**Returns:**
int[] - 页码数组

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


设置将生成预览图像的页码数组。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 页码数组 |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


获取预览图像的格式。


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


设置预览图像的格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | 预览图像格式 |
|

