---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "枚举文档比较支持的预览格式。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

枚举文档比较支持的预览格式。
PreviewFormats 枚举提供了一系列可用于生成比较文档预览的格式。

支持的格式包括：

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [PNG](#PNG) | PNG - 如果页面包含大量彩色图形，可能会消耗大量磁盘空间或网络流量。 |
|
|  | [JPEG](#JPEG) | Jpeg - 提供更快的处理速度且占用更少的磁盘空间和网络流量，但可能导致图像质量降低。 |
|
|  | [BMP](#BMP) | BMP - 提供最佳图像质量，但需要更慢的处理速度且占用更高的磁盘空间和网络流量。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 PreviewFormats 的字符串表示以获取枚举常量。 |
|
|  | [toString()](#toString--) | PreviewFormats 的字符串表示。 |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - 如果页面包含大量彩色图形，可能会消耗大量磁盘空间或网络流量。默认预览格式。


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - 提供更快的处理速度且占用更少的磁盘空间和网络流量，但可能导致图像质量降低。


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - 提供最佳图像质量，但需要更慢的处理速度且占用更高的磁盘空间和网络流量。


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


解析 PreviewFormats 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PreviewFormats 的字符串表示 |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PreviewFormats 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值

