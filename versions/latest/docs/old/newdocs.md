# bClass Theme CSS Dokümantasyonu

Bu doküman, **bClass Theme CSS** kütüphanesinin sağladığı tüm yardımcı (utility) sınıfların yapılandırılmış referansıdır. Sınıflar; belirli CSS özelliklerini ve duyarlı tasarım (responsive) ihtiyaçlarını hızlıca atamak için kategorize edilmiştir.

## 1. Temalar ve Renkler

Kütüphane, projeyi farklı renk şemalarında kullanabilmeniz için hazır renk değişkenleri sunar. İlgili sınıfı sayfanın `<body>` etembetine veya bir kapsayıcıya (container) eklemeniz yeterlidir.

| Sınıf (Class)                      | Açıklama (Description)                                     |
| :--------------------------------- | :--------------------------------------------------------- |
| `body.dark`, `body`                | Koyu (varsayılan) tema renklerini etkinleştirir.           |
| `body.light`                       | Açık (light) tema renklerini etkinleştirir.                |
| `body.black`                       | Tamamen siyah (black) tema renklerini etkinleştirir.       |
| `body.transparent`                 | Şeffaf tema; arka plan görseli ve renksiz alanlar ayarlar. |
| `bg-transparent`                   | Arka planı tamamen şeffaf (`rgba(0,0,0,0)`) yapar.         |
| `text-transparent`                 | Metin rengini görünmez (şeffaf) yapar.                     |
| `content-1`, `content-1-bg`        | Ana içerik arka plan rengini atar.                         |
| `content-2`, `content-2-bg`        | Birincil (primary) arka plan rengini atar.                 |
| `content-3`, `content-3-bg`        | İkincil (secondary) arka plan rengini atar.                |
| `content-1-text`, `content-2-text` | Birincil ve ikincil metin renklerini atar.                 |

## 2. Tipografi ve Metin Biçimlendirme

Yazı boyutu, kalınlığı, hizalaması ve metin davranışlarını ayarlayan sınıflar.

| Sınıf / Desen               | Açıklama ve Alabileceği Değerler                                                          |
| :-------------------------- | :---------------------------------------------------------------------------------------- |
| `.font-size-{değer}`        | Yazı boyutu: 0.5'ten başlayarak 10'a kadar ondalık değerler (Örn: `.font-size-1.5`).      |
| `.font-weight-{değer}`      | Yazı kalınlığı: `100` - `900` ve `bold`.                                                  |
| `.font-{stil}`              | Yazı stili: `normal`, `italic`.                                                           |
| `.text-{hizalama}`          | Hizalama: `left`, `right`, `center`, `justify`, `start`, `end`.                           |
| `.text-line-{dekor}`        | Çizgi dekorasyonu: `none`, `underline`, `overline`, `through`.                            |
| `.text-{büyük/küçük}`       | Harf dönüşümü: `lowercase`, `uppercase`, `capitalize`.                                    |
| `.letter-spacing-{değer}`   | Harf arası boşluk: `0.1` ile `1` arası (Örn: `.letter-spacing-0.5`).                      |
| `.line-height-{değer}`      | Satır yüksekliği: `1` ile `5` arası tam sayılar.                                          |
| `.text-break-{davranış}`    | Kelime kırma: `normal`, `all`, `keep-all`, `word`.                                        |
| `.text-overflow-{davranış}` | Taşan metin: `ellipsis` (üç nokta), `clip` (keser).                                       |
| `.whitespace-{davranış}`    | Beyaz boşluk yönetimi: `normal`, `nowrap`, `pre`, `pre-line`, `pre-wrap`, `break-spaces`. |
| `.writing-{mod}`            | Yazma yönü: `h-tb` (yatay), `v-lr`, `v-rl` (dikey).                                       |
| `.dir-{yön}`                | Sayfa/Eleman yönü: `ltr` (soldan sağa), `rtl` (sağdan sola).                              |

## 3. Boyutlandırma (Genişlik ve Yükseklik)

Genişlik (`w`) ve yükseklik (`h`) değerleri 5'er artan yüzdelik dilimler veya ekran boyutlarına (viewport) göre belirlenebilir.

| Sınıf / Desen   | Açıkllama ve Alabileceği Değerler                         |
| :-------------- | :-------------------------------------------------------- |
| `.w-{değer}`    | Yüzdelik Genişlik: `auto`, `5`, `10`, ..., `95`, `100`.   |
| `.w-vw-{değer}` | Viewport Genişliği (vw): Sadece `25`, `50`, `75`, `100`.  |
| `.h-{değer}`    | Yüzdelik Yükseklik: `auto`, `5`, `10`, ..., `95`, `100`.  |
| `.h-vh-{değer}` | Viewport Yüksekliği (vh): Sadece `25`, `50`, `75`, `100`. |

## 4. Boşluklandırma (Padding & Margin)

Boşluk atamaları için `0` ile `5` arasında tam ve ondalıklı sayılar (Örn: `1.5`, `2`) ile belirli yüzdelik değerler (`25`, `50`, `75`, `100`) desteklenmektedir.

| Özellik                 | Yönlendirme Önekleri ve Açıklamaları                                                                                                    |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| **Padding (İç Boşluk)** | Tüm yönler: `p-`. <br> Dikey/Yatay: `py-` (üst/alt), `px-` (sağ/sol). <br> Tek yön: `pt-` (üst), `pb-` (alt), `pl-` (sol), `pr-` (sağ). |
| **Margin (Dış Boşluk)** | Tüm yönler: `m-` veya `m-auto`. <br> Dikey/Yatay: `my-` (üst/alt), `mx-` (sağ/sol). <br> Tek Yön: `mt-`, `mb-`, `ml-`, `mr-`.           |
| **Mantıksal Boşluk**    | `ms-` (İç satır başı), `me-` (İç satır sonu), `mse-` (Satır başı ve sonu ortak).                                                        |

## 5. Konum ve Pozisyonlama

Elemanların ekrandaki konumlarını yönetir. Konum öteleme değerleri pozitif ve negatif değerleri destekler.

| Sınıf / Desen                     | Açıklama ve Alabileceği Değerler                                                      |
| :-------------------------------- | :------------------------------------------------------------------------------------ |
| `.{pozisyon}`                     | `static`, `relative`, `absolute`, `fixed`, `sticky`.                                  |
| `.left-{değer}`, `.right-{değer}` | Yatay Konum: `0-5` arası değerler, `25, 50, 75, 100` %. Negatif için `-left-{değer}`. |
| `.top-{değer}`, `.bottom-{değer}` | Dikey Konum: `0-5` arası değerler, `25, 50, 75, 100` %. Negatif için `-top-{değer}`.  |
| `.float-{yön}`                    | Kaydırma: `start`, `end`, `left`, `right`, `none`.                                    |
| `.z-{değer}`                      | Derinlik: `auto`, `0-5` arası veya eksi katmanlar `-z-1` ile `-z-5` arası.            |
| `.overflow-{davranış}`            | Taşma (`-x`, `-y`): `auto`, `hidden`, `clip`, `visible`, `scroll`.                    |

## 6. Düzen (Display, Flex & Grid)

Yapısal yerleşimleri koordine eden model sınıflarıdır.

| Sınıf Grubu           | Alabileceği Sınıflar ve Açlama                                                                                                             |
| :-------------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| **Görünüm Türü**      | `.d-none`, `.d-inline`, `.d-block`, `.d-flex`, `.d-grid`, `.d-table`, `.d-list-item` vb.                                                   |
| **Flex Davranışı**    | **Yön:** `.flex-row`, `.flex-col`. <br> **Sarma:** `.flex-nowrap`, `.flex-wrap`. <br> **Büyüme:** `.flex-grow-0` ile `.flex-grow-3` arası. |
| **Hizalama**          | `.justify-content-{start, center, end...}`, `.align-items-{start, center...}`                                                              |
| **Grid/Flex Boşluğu** | `.gap-{değer}` (0-5), `.gap-x-{değer}`, `.gap-y-{dereg}`.                                                                                  |
| **Sıralama (Order)**  | `.order-first`, `.order-last`, `.order-0` ile `5` arası, negatif: `.-order-1`.                                                             |

## 7. Kenarlık ve Köşeler (Borders & Radius)

Kenarlık kalınlığı ve kavis vermek için kullanılır.

| Sınıf / Desen             | Açıklama ve Alabileceği Değerler                                                         |
| :------------------------ | :--------------------------------------------------------------------------------------- |
| `.border-{değer}`         | Tüm kenarlar: `0`, `0.1`'den `2`'ye kadar kalınlıklar.                                   |
| `.border-{yön}-{değer}`   | Spesifik kenarlar: `t` (üst), `b` (alt), `l` (sol), `r` (sağ), `x` (yatay), `y` (dikey). |
| `.rounded-{değer}`        | Tüm köşeler: `0`, `0.1`'den `5`'e kadar değerler.                                        |
| `.rounded-{köşe}-{değer}` | Özel kavisler: `tr` (sağ üst), `tl` (sol üst), `br` (sağ alt), `bl` (sol alt).           |

## 8. Efektler ve Gölgeler (Effects, Transforms, Shadows)

Görsel efektler ve dönüşümler hızlı etkileşim sağlar.

| Sınıf Grubu           | Alabileceği Sınıflar ve Açıklamalar                                                                                                                                                |
| :-------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Görünürlük**        | Görünürlük: `.v-show`, `.v-hide`. <br> Opaklık: `.opacity-0` ile `.opacity-100` arası (5'er adımlı).                                                                               |
| **Bulanıklık (Blur)** | Filtre bulanıklığı: `.blur-0` - `.blur-5`. <br> Arka plan (`backdrop`): `.bg-blur-0` - `.bg-blur-5`.                                                                               |
| **Dönüşümler**        | **Translate:** `.translate-x-{değer}`, `.translate-25`. <br> **Rotate:** `.rotate-0`, `45`, `90`, `180` vb. <br> **Skew:** `.skew-x-{değer}`. <br> **Zoom:** `.zoom`, `.zoom-1.5`. |
| **Gölgeler (Shadow)** | **Kutu:** `.shadow-none`, `.shadow-1` - `.shadow-5`. <br> **Yönlü İç Gölge:** `.shadow-x-{1-10}`, `.shadow-t-{1-10}` vb.                                                           |

## 9. Etkileşim (Interactivity)

Kullanıcı deneyimini şekillendiren sınıflardır.

| Sınıf Grubu       | Alabileceği Sınıflar ve Açıklamalar                                                                                         |
| :---------------- | :-------------------------------------------------------------------------------------------------------------------------- |
| **Fare İmleci**   | `.cursor-pointer`, `wait`, `text`, `not-allowed`, `grab`, `zoom-in` vb. (30+ tip).                                          |
| **Seçim & Boyut** | **Metin Seçimi:** `.select-auto`, `.select-none`. <br> **Yeniden Boyutlandırma:** `.resize-none`, `.resize-y`, `.resize-x`. |
| **Obje Oturtma**  | Resim/Video: `.object-contain`, `.object-cover`, `.object-fill`.                                                            |
| **Devre Dışı**    | Öğeyi pasif hale getirmek için `.disabled` sınıfı.                                                                          |

## 10. Varyantlar (Responsive & Durum Önekleri)

Tüm yardımcı sınıflar, `önek:sınıf-adı` yapısıyla farklı cihaz boyutlarında çalışabilir. (Örn: `hover:opacity-50`)

| Önek (Prefix)    | Tetiklendiği Durum (Breakpoint & State)                  |
| :--------------- | :------------------------------------------------------- |
| `hover:`         | Fare ile elemanın üzerine gelindiğinde.                  |
| `first:`         | Sadece ebeveyn içindeki ilk eşleşen elemana uygulanır.   |
| `last:`          | Sadece ebeveyn içindeki son eşleşen elemana uygulanır.   |
| `mobile:`        | `< 480px` ekranlarda.                                    |
| `tablet:`        | `480px - 768px` arası ekranlarda.                        |
| `tablet-max:`    | Maksimum `768px`'e kadar olan ekranlarda.                |
| `tablet-pc:`     | `768px - 992px` arası ekranlarda.                        |
| `tablet-pc-max:` | Maksimum `992px`'e kadar olan ekranlarda.                |
| `pc:`            | `992px - 1200px` arası standart bilgisayar ekranlarında. |
| `pc-max:`        | Maksimum `1200px`'e kadar olan ekranlarda.               |
| `tv:`            | `> 1200px` genişliğe sahip dev ekranlarda.               |
