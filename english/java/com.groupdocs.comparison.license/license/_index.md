---
title: License
second_title: GroupDocs.Comparison for Java API Reference
description: The License class provides methods to set and apply licenses for GroupDocs.Comparison.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

The License class provides methods to set and apply licenses for GroupDocs.Comparison.

It allows you to enable or disable specific features of the library based on the license applied.

 *  More about licensing: [GroupDocs Licensing FAQ][]
 *  More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing][]

Example usage:

```

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValidLicense()](#isValidLicense--) | Gets a value indicating whether license was set or no. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Sets a license to Comparison using input stream. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Sets a license to Comparison using license file path. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Sets a license to Comparison using license file path. |
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Gets a value indicating whether license was set or no.

**Returns:**
boolean - true if license was set successfully, otherwise false
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Sets a license to Comparison using input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream | The license stream, null unsets license |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Sets a license to Comparison using license file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.nio.file.Path | The license file path |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Sets a license to Comparison using license file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | The license file path |

