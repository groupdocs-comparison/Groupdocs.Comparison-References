---
title: "라이선스"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "License 클래스는 GroupDocs.Comparison에 대한 라이선스를 설정하고 적용하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

License 클래스는 GroupDocs.Comparison에 대한 라이선스를 설정하고 적용하는 메서드를 제공합니다.


적용된 라이선스를 기반으로 라이브러리의 특정 기능을 활성화하거나 비활성화할 수 있습니다.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


사용 예시:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | 라이선스가 설정되었는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 입력 스트림을 사용하여 Comparison에 라이선스를 설정합니다. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | 라이선스 파일 경로를 사용하여 Comparison에 라이선스를 설정합니다. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | 라이선스 파일 경로를 사용하여 Comparison에 라이선스를 설정합니다. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


라이선스가 설정되었는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 라이선스가 성공적으로 설정되면 true, 그렇지 않으면 false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


입력 스트림을 사용하여 Comparison에 라이선스를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | 라이선스 스트림이며, null이면 라이선스가 해제됩니다. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


라이선스 파일 경로를 사용하여 Comparison에 라이선스를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | 라이선스 파일 경로 |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


라이선스 파일 경로를 사용하여 Comparison에 라이선스를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | licensePath | java.lang.String | 라이선스 파일 경로 |
|

