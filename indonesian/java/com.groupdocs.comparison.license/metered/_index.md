---
title: "Metered"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Menyediakan metode untuk menerapkan lisensi bermeter ke Comparison."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode untuk menerapkan lisensi bermeter ke Comparison.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Contoh penggunaan singkat:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Metered()](#Metered--) | Menginisialisasi instance baru dari kelas Metered. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Mendapatkan kuantitas konsumsi. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Mengambil jumlah kredit yang digunakan. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Menerapkan lisensi bermeter menggunakan kunci publik dan privat. |
|
### Metered() {#Metered--}
```
public Metered()
```


Menginisialisasi instance baru dari kelas Metered.


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Mendapatkan kuantitas konsumsi.


**Returns:**
double - kuantitas konsumsi

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Mengambil jumlah kredit yang digunakan.


**Returns:**
double - jumlah kredit yang sudah digunakan

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Menerapkan lisensi bermeter menggunakan kunci publik dan privat.


Contoh penggunaan:

````

 final Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | publicKey | java.lang.String | Kunci publik |
|
|  | privateKey | java.lang.String | Kunci pribadi |
|

