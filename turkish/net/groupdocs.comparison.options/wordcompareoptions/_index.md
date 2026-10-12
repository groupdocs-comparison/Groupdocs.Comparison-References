---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison .NET için API Referansı"
description: "Word belgesi için özel karşılaştırma seçenekleri. Ortak seçenekleri CompareOptions./compareoptions adresinden devralır."
type: docs
weight: 440
url: /tr/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Word belgesi için özel karşılaştırma seçenekleri. Ortak seçenekleri [`CompareOptions`](../compareoptions) adresinden devralır.

```csharp
public class WordCompareOptions : CompareOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Yeni bir [`WordCompareOptions`](../wordcompareoptions) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Değiştirilen bileşenler için koordinatların hesaplanıp hesaplanmayacağını gösterir. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Değiştirilen bileşenler modu için koordinat hesaplamasını belirtir. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Değiştirilen bileşenler için stili tanımlar. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Kaynak ve hedef belgelerdeki yer imlerinin karşılaştırılıp sonuçta farkların dahil edilip edilmediğini alır veya ayarlar. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Yerleşik ve özel belge özelliklerinin karşılaştırılıp sonuçta farkların dahil edilip edilmediğini alır veya ayarlar (ör. özellikler özet sayfasında). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Belge değişken özelliklerinin (ör. DOCVARIABLE alanları) karşılaştırılıp sonuçta farkların dahil edilip edilmediğini alır veya ayarlar. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Silinen bileşenler için stili tanımlar. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Karşılaştırma ayrıntı seviyesini alır veya ayarlar. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Stil değişikliklerini algılayıp algılamayacağını gösterir. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Ana dosya için yol değerini alır veya ayarlar ya da ana dosyanın yolu olmadan karşılaştırma yapar. Bu seçenek yalnızca Diyagram için geçerlidir. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Klasör karşılaştırmasını etkinleştirmek için denetim. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Karşılaştırma sonuçlarının nasıl görüntüleneceğini alır veya ayarlar: Değişiklikleri İzleme modunda Word revizyonları olarak (Revisions) ya da doğrudan belgeye işlenen vurgulanmış değişiklikler olarak (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Özet sayfaya genişletilmiş dosya karşılaştırma bilgisi eklenip eklenmeyeceğini gösterir. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Oluşturulan klasör karşılaştırma dosyasının biçimini alır veya ayarlar. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Sonuç belgesine tespit edilen değişiklik istatistikleriyle özet sayfa eklenip eklenmeyeceğini gösterir. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Üst bilgi/alt bilgi içeriklerinin karşılaştırılmasını etkinleştirmek için denetim. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Benzerliğe dayalı değişiklikleri yok sayma ayarlarını alır veya ayarlar. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Eklenen bileşenler için stili tanımlar. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Ekleme veya silme içeriği yerine boş satırların bırakılıp bırakılmayacağını alır veya ayarlar; düzeni ve satır sayısını korumak için kullanılır ve [`ShowInsertedContent`](../compareoptions/showinsertedcontent) ve [`ShowDeletedContent`](../compareoptions/showdeletedcontent) ile birlikte kullanılır. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Word İşleme'de şekiller için çerçeveler ve Görüntü belgelerinde dikdörtgenler için çerçeveler kullanılıp kullanılmayacağını gösterir. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Belgeler arasındaki paragraf (satır) sonlarının sonuçta görsel olarak işaretlenip işaretlenmeyeceğini alır veya ayarlar. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Silinen veya eklenen öğenin alt öğelerinin silinmiş veya eklenmiş olarak işaretlenip işaretlenmeyeceğini gösteren bir değeri alır veya ayarlar. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Karşılaştırılan belgelerin orijinal boyutlarını alır veya ayarlar. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Sonuç belgesinin kağıt boyutunu alır veya ayarlar. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Parola kaydetme seçeneğini alır veya ayarlar. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | !:WordTrackChanges etkin olduğunda revizyonlar için kullanılan yazar adını alır veya ayarlar. Ayarlanırsa, bu ad sonuç belgesindeki revizyon işaretlemesine uygulanır. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Karşılaştırma hassasiyetini alır veya ayarlar. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Tablolar için karşılaştırma hassasiyetini alır veya ayarlar. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Sonuç belgesinde silinen bileşenlerin gösterilip gösterilmeyeceğini gösterir. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Sonuç belgesinde eklenen bileşenlerin gösterilip gösterilmeyeceğini gösterir. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Yalnızca değişen öğelerin görüntülenmesini etkinleştirmek için denetimler. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Sonuç belgesinde yalnızca tespit edilen değişikliklerin istatistiklerini içeren bir sayfanın bırakılıp bırakılmayacağını gösterir. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Sonuç belgesinin revizyon işaretlemesini görünür tutup tutmayacağını alır veya ayarlar. False ise, tüm revizyonlar kabul edilir ve sonuç son metin olarak görünür. Bu ayar yalnızca [`DisplayMode`](./displaymode) Highlight olarak ayarlandığında anlamlıdır. Varsayılan değer true'tur. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Diagramlar için kullanıcı ana şablonunun yolu. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Metni kelimelere bölmek için ayraçların bir dizisini alır veya ayarlar. |

### Ayrıca Bakınız

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DÜZENLEMEYİN: GroupDocs.Comparison.dll için xmldocmd tarafından oluşturuldu -->
