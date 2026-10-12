---
title: "Licence"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe License fournit des méthodes pour définir et appliquer des licences pour GroupDocs.Comparison."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

La classe License fournit des méthodes pour définir et appliquer des licences pour GroupDocs.Comparison.


Il vous permet d'activer ou de désactiver des fonctionnalités spécifiques de la bibliothèque en fonction de la licence appliquée.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Exemple d'utilisation :

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Obtient une valeur indiquant si la licence a été définie ou non. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Définit une licence pour Comparison en utilisant le flux d'entrée. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Définit une licence pour Comparison en utilisant le chemin du fichier de licence. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Définit une licence pour Comparison en utilisant le chemin du fichier de licence. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Obtient une valeur indiquant si la licence a été définie ou non.


**Returns:**
booléen - vrai si la licence a été définie avec succès, sinon faux

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Définit une licence pour Comparison en utilisant le flux d'entrée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Le flux de licence, null désactive la licence |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Définit une licence pour Comparison en utilisant le chemin du fichier de licence.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Le chemin du fichier de licence |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Définit une licence pour Comparison en utilisant le chemin du fichier de licence.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licensePath | java.lang.String | Le chemin du fichier de licence |
|

