# bClass theme css

Web siteleri ve uygulamalara yönelik arayüzler geliştirmeye yönelik kapsamlı bir kütüphane.

## Requirements

Bu kitaplıkla birlikte `bClass theme js`, `bClass theme colors`, `bClass components`, `bClass animations` ve `bClass media player` kullanılması önerilir.

## Table of Contents

### Layout

- [Container](#container)
- [Display](#display)
- [Float](#float)
- [Object](#object)
- [Overflow](#overflow)
- [Overflow x](#overflow-x)
- [Overflow y](#overflow-y)
- [Header](#header)
- [Footer](#footer)

### Flexbox

- [Flex](#flex)
- [Flex col](#flex-col)
- [Flex row](#flex-row)
- [Flex grow](#flex-grow)
- [Flex wrap](#flex-wrap)
- [Gap](#gap)
- [Align content](#align-content)
- [Align items](#align-items)
- [Align self](#align-self)
- [Justify content](#justify-content)
- [Justify items](#justify-items)
- [Order](#order)

### Spacing

- [Margin](#margin)
- [Padding](#padding)

### Sizing

- [Width](#width)
- [Height](#height)

### Positioning

- [Static](#static)
- [Relative](#relative)
- [Absolute](#absolute)
- [Fixed](#fixed)
- [Sticky](#sticky)
- [Top](#top)
- [Right](#right)
- [Bottom](#bottom)
- [Left](#left)
- [Z-Index](#z-index)

### Typography

- [Font](#font)
- [Font Size](#font-size)
- [Font Weight](#font-weight)
- [Letter spacing](#letter-spacing)
- [Line height](#line-height)
- [Text](#text)
- [Whitespace](#whitespace)
- [Whitespace break](#whitespace-break)
- [Whitespace pre](#whitespace-pre)
- [Writing h](#writing-h)
- [Writing v](#writing-v)

### Backgrounds

- [Background](#background)
- [Bg blur](#bg-blur)

### Borders

- [Border](#border)
- [Border Radius](#border-radius)

### Effects

- [Box Shadow](#box-shadow)
- [Blur](#blur)
- [Opacity](#opacity)

### Transforms

- [Rotate](#rotate)
- [Skew](#skew)
- [Translate](#translate)
- [Zoom](#zoom)

### Colors

- [Black](#black)
- [Dark](#dark)
- [Light](#light)
- [Transparent](#transparent)

### Interactivity

- [Cursor](#cursor)
- [Disabled](#disabled)
- [Resize](#resize)
- [Select](#select)

### Misc

- [Content](#content)
- [Dir](#dir)
- [Mse](#mse)
- [Visibility](#visibility)
- [Customization](#customization)
- [License](#license)

---

## Layout

### Container

- `.container` - Konteyner

### Display

- `.d-block` - Ekran bloğu
- `.d-contents` - İçerikleri görüntüle
- `.d-flex` - Esnek ekran
- `.d-flow-root` - Akış kökünü görüntüle
- `.d-grid` - Izgarayı göster
- `.d-inline` - Satır içi görüntüle
- `.d-inline-block` - Satır içi bloğu görüntüle
- `.d-inline-flex` - Satır içi esnekliği göster
- `.d-inline-grid` - Satır içi ızgarayı görüntüle
- `.d-inline-table` - Satır içi tabloyu görüntüle
- `.d-list-item` - Liste öğesini görüntüle
- `.d-none` - Hiçbirini göster
- `.d-table` - Ekran tablosu
- `.d-table-caption` - Tablo başlığını görüntüle
- `.d-table-cell` - Tablo hücresini görüntüle
- `.d-table-col` - Tablo sütununu göster
- `.d-table-col-group` - Tablo sütun grubunu görüntüle
- `.d-table-footer-group` - Tablo altbilgi grubunu görüntüle
- `.d-table-header-group` - Tablo başlığı grubunu görüntüle
- `.d-table-row` - Tablo satırını görüntüle
- `.d-table-row-group` - Tablo satır grubunu görüntüle
- `.hover:d-block` - Fareyle üzerine gelindiğinde bloğu görüntüle
- `.hover:d-flex` - Fareyle üzerine gelindiğinde esnekliği göster
- `.hover:d-inline` - Fareyle üzerine gelindiğinde satır içi görüntüle
- `.hover:d-inline-block` - Fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:d-inline-flex` - Fareyle üzerine gelindiğinde satır içi esnekliği görüntüle
- `.hover:d-none` - Fareyle üzerine gelindiğinde hiçbirini gösterme

##### Display - Mobile (≤ 480px)

- `.hover:mobile:d-block` - Mobil cihazda fareyle üzerine gelindiğinde bloğu görüntüleme
- `.hover:mobile:d-flex` - Mobil cihazda fareyle üzerine gelindiğinde esnekliği görüntüleyin
- `.hover:mobile:d-inline` - Mobil cihazda fareyle üzerine gelindiğinde satır içi görüntüleme
- `.hover:mobile:d-inline-block` - Mobil cihazda fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:mobile:d-inline-flex` - Mobil cihazda fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:mobile:d-none` - Mobil cihazda fareyle üzerine gelindiğinde hiçbirini gösterme
- `.mobile:d-block` - Mobil cihazda görüntüleme engellemesi
- `.mobile:d-flex` - Mobil cihazlarda esnek ekran
- `.mobile:d-grid` - Izgarayı mobil cihazda görüntüle
- `.mobile:d-inline` - Mobil cihazlarda satır içi görüntüleme
- `.mobile:d-inline-block` - Mobil cihazda satır içi bloğu görüntüle
- `.mobile:d-inline-flex` - Satır içi esnekliği mobil cihazlarda görüntüleyin
- `.mobile:d-inline-grid` - Mobil cihazlarda satır içi ızgarayı görüntüle
- `.mobile:d-none` - Mobil cihazda hiçbirini gösterme

##### Display - Tablet (480px - 768px)

- `.hover:tablet:d-block` - Tablette fareyle üzerine gelindiğinde bloğu görüntüleme
- `.hover:tablet:d-flex` - Tablette fareyle üzerine gelindiğinde esnekliği görüntüleyin
- `.hover:tablet:d-inline` - Tablette fareyle üzerine gelindiğinde satır içi görüntüle
- `.hover:tablet:d-inline-block` - Tablette fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:tablet:d-inline-flex` - Tablette fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:tablet:d-none` - Tablette fareyle üzerine gelindiğinde hiçbiri görüntülenmiyor
- `.tablet:d-block` - Tablette görüntüleme bloğu
- `.tablet:d-flex` - Tablette esnek ekran
- `.tablet:d-grid` - Tabloyu tablette görüntüleme
- `.tablet:d-inline` - Tablette satır içi görüntüleme
- `.tablet:d-inline-block` - Satır içi bloğu tablette görüntüle
- `.tablet:d-inline-flex` - Satır içi esnekliği tablette görüntüleyin
- `.tablet:d-inline-grid` - Tablette satır içi ızgarayı görüntüle
- `.tablet:d-none` - Tablette hiçbirini gösterme

##### Display - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:d-block` - Tablet bilgisayarda fareyle üzerine gelindiğinde görüntüleme bloğu
- `.hover:tablet-pc:d-flex` - Tablet bilgisayarda fareyle üzerine gelindiğinde ekran esnekliği
- `.hover:tablet-pc:d-inline` - Tablet bilgisayarda fareyle üzerine gelindiğinde satır içi görüntüleme
- `.hover:tablet-pc:d-inline-block` - Tablet bilgisayarda fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:tablet-pc:d-inline-flex` - Tablet bilgisayarda fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:tablet-pc:d-none` - Tablet bilgisayarda fareyle üzerine gelindiğinde hiçbiri görüntülenmiyor
- `.tablet-pc:d-block` - Tablet PC'de ekran bloğu
- `.tablet-pc:d-flex` - Tablet PC'de ekran esnekliği
- `.tablet-pc:d-grid` - Tablet bilgisayarda ızgarayı görüntüleme
- `.tablet-pc:d-inline` - Tablet bilgisayarda satır içi görüntüleme
- `.tablet-pc:d-inline-block` - Tablet PC'de satır içi bloğu görüntüle
- `.tablet-pc:d-inline-flex` - Tablet bilgisayarda satır içi esnekliği görüntüleyin
- `.tablet-pc:d-inline-grid` - Tablet bilgisayarda satır içi ızgarayı görüntüleme
- `.tablet-pc:d-none` - Tablet PC'de hiçbiri görüntülenmiyor

##### Display - Pc (992px - 1200px)

- `.hover:pc:d-block` - PC'de fareyle üzerine gelindiğinde görüntüleme bloğu
- `.hover:pc:d-flex` - PC'de fareyle üzerine gelindiğinde esnek ekran
- `.hover:pc:d-inline` - PC'de fareyle üzerine gelindiğinde satır içi görüntüleme
- `.hover:pc:d-inline-block` - PC'de fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:pc:d-inline-flex` - PC'de fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:pc:d-none` - Bilgisayarda fareyle üzerine gelindiğinde hiçbirini gösterme
- `.pc:d-block` - PC'de ekran bloğu
- `.pc:d-flex` - PC'de esnek ekran
- `.pc:d-grid` - Izgarayı bilgisayarda görüntüleme
- `.pc:d-inline` - PC'de satır içi görüntüleme
- `.pc:d-inline-block` - PC'de satır içi bloğu görüntüle
- `.pc:d-inline-flex` - Satır içi esnekliği PC'de görüntüleyin
- `.pc:d-inline-grid` - PC'de satır içi ızgarayı görüntüle
- `.pc:d-none` - PC'de hiçbirini gösterme

##### Display - Tv (≥ 1200px)

- `.hover:tv:d-block` - TV'de fareyle üzerine gelindiğinde görüntüleme bloğu
- `.hover:tv:d-flex` - TV'de fareyle üzerine gelindiğinde esnekliği görüntüleyin
- `.hover:tv:d-inline` - TV'de fareyle üzerine gelindiğinde satır içi görüntüleme
- `.hover:tv:d-inline-block` - TV'de fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:tv:d-inline-flex` - TV'de fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:tv:d-none` - TV'de fareyle üzerine gelindiğinde hiçbirini gösterme
- `.tv:d-block` - Televizyonda görüntü engelleme
- `.tv:d-flex` - Televizyonda Flex'i görüntüle
- `.tv:d-grid` - Izgarayı TV'de görüntüleme
- `.tv:d-inline` - TV'de satır içi görüntüleme
- `.tv:d-inline-block` - Satır içi bloğu TV'de göster
- `.tv:d-inline-flex` - Satır içi esnekliği TV'de görüntüleyin
- `.tv:d-inline-grid` - Satır içi ızgarayı TV'de görüntüle
- `.tv:d-none` - Hiçbirini televizyonda gösterme

##### Display - Tablet Max (≤ 768px)

- `.hover:tablet-max:d-block` - Tablet max üzerinde fareyle üzerine gelindiğinde görüntüleme bloğu
- `.hover:tablet-max:d-flex` - Maksimum tablette fareyle üzerine gelindiğinde esnekliği görüntüleyin
- `.hover:tablet-max:d-inline` - Tablet max'te fareyle üzerine gelindiğinde satır içi görüntüle
- `.hover:tablet-max:d-inline-block` - Tablet max'te fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:tablet-max:d-inline-flex` - Tablet max üzerinde fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:tablet-max:d-none` - Tablet max üzerinde fareyle üzerine gelindiğinde hiçbirini gösterme
- `.tablet-max:d-block` - Tablet max'ta ekran bloğu
- `.tablet-max:d-flex` - Maksimum tablette ekran esnekliği
- `.tablet-max:d-grid` - Tablet max'ta ızgarayı görüntüle
- `.tablet-max:d-inline` - Maksimum tablette satır içi görüntüle
- `.tablet-max:d-inline-block` - Tablet max'te satır içi bloğu görüntüle
- `.tablet-max:d-inline-flex` - Tablet max'te satır içi esnekliği görüntüleyin
- `.tablet-max:d-inline-grid` - Tablet max'te satır içi ızgarayı görüntüle
- `.tablet-max:d-none` - Tablet max'ta hiçbirini gösterme

##### Display - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:d-block` - Tablet pc max'ta fareyle üzerine gelindiğinde görüntüleme bloğu
- `.hover:tablet-pc-max:d-flex` - Tablet PC max'ta fareyle üzerine gelindiğinde ekran esnekliği
- `.hover:tablet-pc-max:d-inline` - Tablet PC max'ta fareyle üzerine gelindiğinde satır içi görüntüleme
- `.hover:tablet-pc-max:d-inline-block` - Tablet PC max'ta fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:tablet-pc-max:d-inline-flex` - Tablet PC max'ta fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:tablet-pc-max:d-none` - Tablet PC max'ta fareyle üzerine gelindiğinde hiçbiri görüntülenmiyor
- `.tablet-pc-max:d-block` - Tablet pc max'ta ekran bloğu
- `.tablet-pc-max:d-flex` - Tablet pc max'ta ekran esnekliği
- `.tablet-pc-max:d-grid` - Tablet pc max'ta ekran ızgarası
- `.tablet-pc-max:d-inline` - Tablet PC'de satır içi görüntüleme max
- `.tablet-pc-max:d-inline-block` - Tablet PC max'ta satır içi bloğu görüntüle
- `.tablet-pc-max:d-inline-flex` - Tablet pc max'ta satır içi esnekliği görüntüleyin
- `.tablet-pc-max:d-inline-grid` - Tablet PC'de satır içi ızgarayı görüntüleme max
- `.tablet-pc-max:d-none` - Tablet PC max'ta hiçbiri görüntülenmiyor

##### Display - Pc Max (≤ 1200px)

- `.hover:pc-max:d-block` - PC max'ta fareyle üzerine gelindiğinde görüntüleme bloğu
- `.hover:pc-max:d-flex` - PC max'ta fareyle üzerine gelindiğinde ekran esnekliği
- `.hover:pc-max:d-inline` - PC max'ta fareyle üzerine gelindiğinde satır içi görüntüleme
- `.hover:pc-max:d-inline-block` - PC max'ta fareyle üzerine gelindiğinde satır içi bloğu görüntüle
- `.hover:pc-max:d-inline-flex` - PC max'ta fareyle üzerine gelindiğinde satır içi esnekliği görüntüleyin
- `.hover:pc-max:d-none` - PC max'ta fareyle üzerine gelindiğinde hiçbirini gösterme
- `.pc-max:d-block` - PC max'ta ekran bloğu
- `.pc-max:d-flex` - PC max'ta ekran esnekliği
- `.pc-max:d-grid` - PC max'ta ızgarayı görüntüleme
- `.pc-max:d-inline` - PC max'ta satır içi görüntüleme
- `.pc-max:d-inline-block` - PC max'ta satır içi bloğu görüntüle
- `.pc-max:d-inline-flex` - PC max'ta satır içi esnekliği görüntüleyin
- `.pc-max:d-inline-grid` - PC max'ta satır içi ızgarayı görüntüle
- `.pc-max:d-none` - PC max'ta hiçbirini gösterme

### Float

- `.float-end` - Şamandıra sonu
- `.float-left` - Sola kayan
- `.float-none` - Hiçbiri kayan
- `.float-right` - Sağa doğru süzül
- `.float-start` - Kayan başlangıç
- `.hover:float-end` - Fareyle üzerine gelindiğinde kayan nokta
- `.hover:float-left` - Fareyle üzerine gelindiğinde sola doğru süzülme
- `.hover:float-none` - Fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:float-right` - Fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:float-start` - Fareyle üzerine gelindiğinde kayan başlangıç

##### Float - Mobile (≤ 480px)

- `.hover:mobile:float-end` - Mobil cihazda fareyle üzerine gelindiğinde kayan nokta
- `.hover:mobile:float-left` - Mobil cihazda fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:mobile:float-none` - Mobil cihazda fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:mobile:float-right` - Mobil cihazda fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:mobile:float-start` - Mobil cihazda fareyle üzerine gelindiğinde kayan başlangıç
- `.mobile:float-end` - Mobil cihazda kayan uç
- `.mobile:float-left` - Mobil cihazda sola doğru kayan
- `.mobile:float-none` - Mobil cihazda hiçbiri kayan
- `.mobile:float-right` - Mobil cihazda sağa doğru süzülün
- `.mobile:float-start` - Mobil cihazda kayan başlangıç

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - Tabletin üzerine gelindiğinde kayan uç
- `.hover:tablet:float-left` - Tablette fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:tablet:float-none` - Tabletin üzerine gelindiğinde hiçbiri kayan
- `.hover:tablet:float-right` - Tabletin üzerine gelindiğinde sağa doğru süzülün
- `.hover:tablet:float-start` - Tablet üzerinde fareyle üzerine gelindiğinde kayan başlangıç
- `.tablet:float-end` - Tablette kayan uç
- `.tablet:float-left` - Tablette sola kayan
- `.tablet:float-none` - Hiçbiri tablette kayan
- `.tablet:float-right` - Tabletin üzerinde sağa doğru süzülün
- `.tablet:float-start` - Tablette kayan başlangıç

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - Tablet bilgisayarda fareyle üzerine gelindiğinde kayan uç
- `.hover:tablet-pc:float-left` - Tablet bilgisayarda fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:tablet-pc:float-none` - Tablet bilgisayarda fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:tablet-pc:float-right` - Tablet bilgisayarda fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:tablet-pc:float-start` - Tablet bilgisayarda fareyle üzerine gelindiğinde kayan başlangıç
- `.tablet-pc:float-end` - Tablet PC'de kayan uç
- `.tablet-pc:float-left` - Tablet bilgisayarda sola doğru kayan
- `.tablet-pc:float-none` - Tablet PC'de hiçbiri kayan
- `.tablet-pc:float-right` - Tablet PC'de sağa doğru süzülün
- `.tablet-pc:float-start` - Tablet PC'de kayan başlangıç

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - PC'de fareyle üzerine gelindiğinde kayan nokta
- `.hover:pc:float-left` - PC'de fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:pc:float-none` - PC'de fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:pc:float-right` - PC'de fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:pc:float-start` - PC'de fareyle üzerine gelindiğinde kayan başlangıç
- `.pc:float-end` - PC'de kayan nokta
- `.pc:float-left` - PC'de sola doğru kayan
- `.pc:float-none` - Hiçbiri PC'de kayan
- `.pc:float-right` - PC'de sağa doğru süzülün
- `.pc:float-start` - PC'de kayan başlangıç

##### Float - Tv (≥ 1200px)

- `.hover:tv:float-end` - Televizyonun üzerine gelindiğinde kayan nokta
- `.hover:tv:float-left` - TV'de fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:tv:float-none` - Hiçbiri TV'nin üzerine gelindiğinde kayan
- `.hover:tv:float-right` - TV'de fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:tv:float-start` - Televizyonun üzerine gelindiğinde kayan başlangıç
- `.tv:float-end` - Televizyonda kayan nokta
- `.tv:float-left` - Televizyonda sola kayan
- `.tv:float-none` - Hiçbiri televizyonda yayınlanmıyor
- `.tv:float-right` - Televizyonda sağa doğru süzülün
- `.tv:float-start` - Televizyonda kayan başlangıç

##### Float - Tablet Max (≤ 768px)

- `.hover:tablet-max:float-end` - Maksimum tabletin üzerinde fareyle üzerine gelindiğinde kayan uç
- `.hover:tablet-max:float-left` - Tablet max üzerinde fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:tablet-max:float-none` - Tablet max üzerinde fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:tablet-max:float-right` - Tablet max üzerinde fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:tablet-max:float-start` - Maksimum tablette fareyle üzerine gelindiğinde kayan başlangıç
- `.tablet-max:float-end` - Maksimum tablette kayan uç
- `.tablet-max:float-left` - Maksimum tablette sola doğru kayan
- `.tablet-max:float-none` - Hiçbiri tablet max'ta kayan
- `.tablet-max:float-right` - Maksimum tablette sağa doğru süzülün
- `.tablet-max:float-start` - Maksimum tablette kayan başlangıç

##### Float - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:float-end` - Tablet PC max üzerinde fareyle üzerine gelindiğinde kayan uç
- `.hover:tablet-pc-max:float-left` - Tablet PC max'ta fareyle üzerine gelindiğinde sola doğru kayan
- `.hover:tablet-pc-max:float-none` - Tablet PC max üzerinde fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:tablet-pc-max:float-right` - Tablet PC max üzerinde fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:tablet-pc-max:float-start` - Tablet PC max'ta fareyle üzerine gelindiğinde kayan başlangıç
- `.tablet-pc-max:float-end` - Tablet PC max'ta kayan uç
- `.tablet-pc-max:float-left` - Tablet PC max'ta sola doğru kayan
- `.tablet-pc-max:float-none` - Hiçbiri tablet pc max'ta kayan
- `.tablet-pc-max:float-right` - Tablet PC max'ta sağa doğru süzülün
- `.tablet-pc-max:float-start` - Tablet PC Max'te kayan başlangıç

##### Float - Pc Max (≤ 1200px)

- `.hover:pc-max:float-end` - PC max'ta fareyle üzerine gelindiğinde kayan nokta
- `.hover:pc-max:float-left` - PC max'ta fareyle üzerine gelindiğinde sola doğru süzülün
- `.hover:pc-max:float-none` - PC max üzerinde fareyle üzerine gelindiğinde hiçbiri kayan
- `.hover:pc-max:float-right` - PC max'ta fareyle üzerine gelindiğinde sağa doğru süzülün
- `.hover:pc-max:float-start` - PC max'ta fareyle üzerine gelindiğinde kayan başlangıç
- `.pc-max:float-end` - PC max'ta kayan uç
- `.pc-max:float-left` - PC max'ta sola doğru kayan
- `.pc-max:float-none` - PC max'ta hiçbiri kayan
- `.pc-max:float-right` - PC max'ta sağa doğru süzülün
- `.pc-max:float-start` - PC max'ta kayan başlangıç

### Object

- `.hover:object-contain` - Fareyle üzerine gelindiğinde nesne içeriyor
- `.hover:object-cover` - Fareyle üzerine gelindiğinde nesne kapağı
- `.hover:object-fill` - Fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:object-none` - Fareyle üzerine gelindiğinde nesne yok
- `.hover:object-scale` - Fareyle üzerine gelindiğinde nesne ölçeği
- `.object-contain` - Nesne içeriği
- `.object-cover` - Nesne kapağı
- `.object-fill` - Nesne dolgusu
- `.object-none` - nesne yok
- `.object-scale` - Nesne ölçeği

##### Object - Mobile (≤ 480px)

- `.hover:mobile:object-contain` - Mobil cihazda fareyle üzerine gelindiğinde nesne içeriyor
- `.hover:mobile:object-cover` - Mobil cihazda fareyle üzerine gelindiğinde nesne kapağı
- `.hover:mobile:object-fill` - Mobil cihazda fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:mobile:object-none` - Mobil cihazda fareyle üzerine gelindiğinde nesne yok
- `.hover:mobile:object-scale` - Mobil cihazda fareyle üzerine gelindiğinde nesne ölçeği
- `.mobile:object-contain` - Mobil cihazda nesne içeriyor
- `.mobile:object-cover` - Mobil cihazda nesne kapağı
- `.mobile:object-fill` - Mobil cihazda nesne doldurma
- `.mobile:object-none` - Mobil cihazda nesne yok
- `.mobile:object-scale` - Mobil cihazlarda nesne ölçeği

##### Object - Tablet (480px - 768px)

- `.hover:tablet:object-contain` - Tabletin üzerine gelindiğinde nesne içeriyor
- `.hover:tablet:object-cover` - Tabletin üzerine gelindiğinde nesne kapağı
- `.hover:tablet:object-fill` - Tablette fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:tablet:object-none` - Tabletin üzerine gelindiğinde nesne yok
- `.hover:tablet:object-scale` - Tabletin üzerine gelindiğinde nesne ölçeği
- `.tablet:object-contain` - Nesne tablette içeriyor
- `.tablet:object-cover` - Tabletteki nesne kapağı
- `.tablet:object-fill` - Tablette nesne doldurma
- `.tablet:object-none` - Tablette nesne yok
- `.tablet:object-scale` - Tablette nesne ölçeği

##### Object - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:object-contain` - Tablet PC'de fareyle üzerine gelindiğinde nesne içeriyor
- `.hover:tablet-pc:object-cover` - Tablet bilgisayarda fareyle üzerine gelindiğinde nesne kapağı
- `.hover:tablet-pc:object-fill` - Tablet bilgisayarda fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:tablet-pc:object-none` - Tablet bilgisayarda fareyle üzerine gelindiğinde nesne yok
- `.hover:tablet-pc:object-scale` - Tablet bilgisayarda fareyle üzerine gelindiğinde nesne ölçeği
- `.tablet-pc:object-contain` - Tablet PC'de nesne içeriyor
- `.tablet-pc:object-cover` - Tablet PC'de nesne kapağı
- `.tablet-pc:object-fill` - Tablet PC'de nesne doldurma
- `.tablet-pc:object-none` - Tablet PC'de nesne yok
- `.tablet-pc:object-scale` - Tablet PC'de nesne ölçeği

##### Object - Pc (992px - 1200px)

- `.hover:pc:object-contain` - PC'de fareyle üzerine gelindiğinde nesne içeriyor
- `.hover:pc:object-cover` - PC'de fareyle üzerine gelindiğinde nesne kapağı
- `.hover:pc:object-fill` - PC'de fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:pc:object-none` - PC'de fareyle üzerine gelindiğinde nesne yok
- `.hover:pc:object-scale` - PC'de fareyle üzerine gelindiğinde nesne ölçeği
- `.pc:object-contain` - Nesne bilgisayarda bulunur
- `.pc:object-cover` - PC'de nesne kapağı
- `.pc:object-fill` - PC'de nesne doldurma
- `.pc:object-none` - PC'de nesne yok
- `.pc:object-scale` - PC'de nesne ölçeği

##### Object - Tv (≥ 1200px)

- `.hover:tv:object-contain` - Televizyonun üzerine gelindiğinde nesne içeriyor
- `.hover:tv:object-cover` - Televizyonda fareyle üzerine gelindiğinde nesne kapağı
- `.hover:tv:object-fill` - Televizyonda fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:tv:object-none` - Televizyonun üzerine gelindiğinde nesne yok
- `.hover:tv:object-scale` - Televizyonun üzerine gelindiğinde nesne ölçeği
- `.tv:object-contain` - Nesne televizyonda yer alıyor
- `.tv:object-cover` - Televizyondaki nesne kapağı
- `.tv:object-fill` - Televizyonda nesne doldurma
- `.tv:object-none` - Televizyonda nesne yok
- `.tv:object-scale` - Televizyonda nesne ölçeği

##### Object - Tablet Max (≤ 768px)

- `.hover:tablet-max:object-contain` - Tablet max üzerinde fareyle üzerine gelindiğinde nesne içeriyor
- `.hover:tablet-max:object-cover` - Tablet max üzerinde fareyle üzerine gelindiğinde nesne kapağı
- `.hover:tablet-max:object-fill` - Maksimum tablette fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:tablet-max:object-none` - Tablet max üzerinde fareyle üzerine gelindiğinde nesne yok
- `.hover:tablet-max:object-scale` - Tablet max üzerinde fareyle üzerine gelindiğinde nesne ölçeği
- `.tablet-max:object-contain` - Tablet max'te nesne içeriyor
- `.tablet-max:object-cover` - Tablet max'ta nesne kapağı
- `.tablet-max:object-fill` - Maksimum tablette nesne doldurma
- `.tablet-max:object-none` - Tablet max'ta hiçbirine itiraz etme
- `.tablet-max:object-scale` - Tablet max'ta nesne ölçeği

##### Object - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:object-contain` - Tablet PC max üzerinde fareyle üzerine gelindiğinde nesne içeriyor
- `.hover:tablet-pc-max:object-cover` - Tablet PC max üzerinde fareyle üzerine gelindiğinde nesne kapağı
- `.hover:tablet-pc-max:object-fill` - Tablet pc max'ta fareyle üzerine gelindiğinde nesne dolgusu
- `.hover:tablet-pc-max:object-none` - Tablet PC Max'te fareyle üzerine gelindiğinde nesne yok
- `.hover:tablet-pc-max:object-scale` - Tablet pc max'ta fareyle üzerine gelindiğinde nesne ölçeği
- `.tablet-pc-max:object-contain` - Nesne tablet pc max'ta içeriyor
- `.tablet-pc-max:object-cover` - Tablet PC Max'te nesne kapağı
- `.tablet-pc-max:object-fill` - Tablet pc max'ta nesne doldurma
- `.tablet-pc-max:object-none` - Tablet pc max'ta nesne yok
- `.tablet-pc-max:object-scale` - Tablet PC Max'te nesne ölçeği

##### Object - Pc Max (≤ 1200px)

- `.hover:pc-max:object-contain` - Nesne, pc max'ta fareyle üzerine gelindiğinde içeriyor
- `.hover:pc-max:object-cover` - PC max'ta fareyle üzerine gelindiğinde nesne kapağı
- `.hover:pc-max:object-fill` - PC max'ta fareyle üzerine gelindiğinde nesne doldurma
- `.hover:pc-max:object-none` - PC max üzerinde fareyle üzerine gelindiğinde nesne yok
- `.hover:pc-max:object-scale` - PC max'ta fareyle üzerine gelindiğinde nesne ölçeği
- `.pc-max:object-contain` - Nesne pc max'ta içeriyor
- `.pc-max:object-cover` - PC max'ta nesne kapağı
- `.pc-max:object-fill` - PC max'ta nesne doldurma
- `.pc-max:object-none` - PC max'ta nesne yok
- `.pc-max:object-scale` - PC max'ta nesne ölçeği

### Overflow

- `.hover:overflow-scroll` - Fareyle üzerine gelindiğinde taşma kaydırması
- `.overflow-auto` - Otomatik taşma
- `.overflow-clip` - Taşma klibi
- `.overflow-hidden` - Taşma gizlendi
- `.overflow-scroll` - Taşma kaydırma
- `.overflow-visible` - Taşma görünür

### Overflow x

- `.hover:overflow-x-scroll` - Taşma x fareyle üzerine gelindiğinde kaydırma
- `.overflow-x-auto` - Taşma x otomatik
- `.overflow-x-clip` - Taşma x klip
- `.overflow-x-hidden` - Taşma x gizli
- `.overflow-x-scroll` - Taşma x kaydırma
- `.overflow-x-visible` - Taşma x görünür

### Overflow y

- `.hover:overflow-y-scroll` - Taşma ve fareyle üzerine gelindiğinde kaydırma
- `.overflow-y-auto` - Taşma ve otomatik
- `.overflow-y-clip` - Taşma y klibi
- `.overflow-y-hidden` - Taşma ve gizli
- `.overflow-y-scroll` - Taşma ve kaydırma
- `.overflow-y-visible` - Taşma ve görünür

### Header

- `.header` - Başlık

### Footer

- `.footer` - Altbilgi

## Flexbox

### Flex

- `.flex-col` - Esnek sütun
- `.flex-nowrap` - Artık rap'i esnekleştir
- `.flex-row` - Esnek satır
- `.flex-wrap` - Esnek sarma
- `.hover:flex-col` - Fareyle üzerine gelindiğinde sütunu esnekleştirin
- `.hover:flex-nowrap` - Fareyle üzerine gelindiğinde şimdi rap'i esnetin
- `.hover:flex-row` - Fareyle üzerine gelindiğinde satırı esnekleştirin
- `.hover:flex-wrap` - Fareyle üzerine gelindiğinde esnek sarma

##### Flex - Mobile (≤ 480px)

- `.hover:mobile:flex-col` - Mobil cihazda fareyle üzerine gelindiğinde Flex Col
- `.hover:mobile:flex-nowrap` - Mobil cihazda fareyle üzerine gelindiğinde Nowrap'i esnekleştirin
- `.hover:mobile:flex-row` - Mobil cihazda fareyle üzerine gelindiğinde satırı esnekleştirin
- `.hover:mobile:flex-wrap` - Mobil cihazda fareyle üzerine gelindiğinde esnek sarma
- `.mobile:flex-col` - Mobil cihazda Flex Col
- `.mobile:flex-nowrap` - Mobil cihazda Flex nowrap
- `.mobile:flex-row` - Mobil cihazda esnek satır
- `.mobile:flex-wrap` - Mobil cihazlarda esnek sarma

##### Flex - Tablet (480px - 768px)

- `.hover:tablet:flex-col` - Tabletin üzerine gelindiğinde Flex Col
- `.hover:tablet:flex-nowrap` - Tabletin üzerine gelindiğinde Nowrap'i esnekleştirin
- `.hover:tablet:flex-row` - Tabletin üzerine gelindiğinde satırı esnekleştirin
- `.hover:tablet:flex-wrap` - Tabletin üzerine gelindiğinde esnek sarma
- `.tablet:flex-col` - Tablette Flex Col
- `.tablet:flex-nowrap` - Tablette Flex Nowrap
- `.tablet:flex-row` - Tablette esnek satır
- `.tablet:flex-wrap` - Tablette esnek sarma

##### Flex - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col` - Tablet bilgisayarda fareyle üzerine gelindiğinde Flex Col
- `.hover:tablet-pc:flex-nowrap` - Tablet bilgisayarda fareyle üzerine gelindiğinde Flex nowrap
- `.hover:tablet-pc:flex-row` - Tablet bilgisayarda fareyle üzerine gelindiğinde esnek satır
- `.hover:tablet-pc:flex-wrap` - Tablet bilgisayarda fareyle üzerine gelindiğinde esnek sarma
- `.tablet-pc:flex-col` - Tablet bilgisayarda Flex col
- `.tablet-pc:flex-nowrap` - Tablet PC'de Flex Nowrap
- `.tablet-pc:flex-row` - Tablet bilgisayarda esnek satır
- `.tablet-pc:flex-wrap` - Tablet PC'de Flex Wrap

##### Flex - Pc (992px - 1200px)

- `.hover:pc:flex-col` - PC'de fareyle üzerine gelindiğinde Flex col
- `.hover:pc:flex-nowrap` - Bilgisayarda fareyle üzerine gelindiğinde Flex nowrap
- `.hover:pc:flex-row` - Bilgisayarda fareyle üzerine gelindiğinde esnek satır
- `.hover:pc:flex-wrap` - PC'de fareyle üzerine gelindiğinde esnek sarma
- `.pc:flex-col` - PC'de Flex Col
- `.pc:flex-nowrap` - PC'de Flex nowrap
- `.pc:flex-row` - PC'de esnek satır
- `.pc:flex-wrap` - PC'de Flex Wrap

##### Flex - Tv (≥ 1200px)

- `.hover:tv:flex-col` - Televizyonun üzerine gelindiğinde Flex Col
- `.hover:tv:flex-nowrap` - Televizyonun üzerine gelindiğinde Nowrap'i esnekleştirin
- `.hover:tv:flex-row` - TV'de fareyle üzerine gelindiğinde esnek satır
- `.hover:tv:flex-wrap` - TV'de fareyle üzerine gelindiğinde esnek sarma
- `.tv:flex-col` - TV'de Flex Col
- `.tv:flex-nowrap` - TV'de Flex nowrap
- `.tv:flex-row` - Televizyonda esnek satır
- `.tv:flex-wrap` - Televizyonda Flex Wrap

##### Flex - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-col` - Maksimum tabletin üzerinde fareyle üzerine gelindiğinde Flex Col
- `.hover:tablet-max:flex-nowrap` - Maksimum tabletin üzerine gelindiğinde Nowrap'i esnekleştirin
- `.hover:tablet-max:flex-row` - Maksimum tabletin üzerine gelindiğinde satırı esnekleştirin
- `.hover:tablet-max:flex-wrap` - Maksimum tablette fareyle üzerine gelindiğinde esnek sarma
- `.tablet-max:flex-col` - Tablet max'ta Flex col
- `.tablet-max:flex-nowrap` - Tablet max'ta Flex nowrap
- `.tablet-max:flex-row` - Maksimum tablette esnek satır
- `.tablet-max:flex-wrap` - Maksimum tablette esnek sarma

##### Flex - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-col` - Tablet PC max üzerinde fareyle üzerine gelindiğinde Flex Col
- `.hover:tablet-pc-max:flex-nowrap` - Tablet PC max üzerinde fareyle üzerine gelindiğinde Flex nowrap
- `.hover:tablet-pc-max:flex-row` - Tablet PC max üzerinde fareyle üzerine gelindiğinde esnek satır
- `.hover:tablet-pc-max:flex-wrap` - Tablet PC'de fareyle üzerine gelindiğinde esnek sarma
- `.tablet-pc-max:flex-col` - Tablet PC'de Flex col max
- `.tablet-pc-max:flex-nowrap` - Tablet PC max'ta Flex nowrap
- `.tablet-pc-max:flex-row` - Tablet PC'de Flex satır max
- `.tablet-pc-max:flex-wrap` - Tablet PC'de Flex Wrap Max

##### Flex - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-col` - PC max üzerinde fareyle üzerine gelindiğinde Flex Col
- `.hover:pc-max:flex-nowrap` - PC max'ta fareyle üzerine gelindiğinde esnek nowrap
- `.hover:pc-max:flex-row` - PC max'ta fareyle üzerine gelindiğinde esnek satır
- `.hover:pc-max:flex-wrap` - PC max'ta fareyle üzerine gelindiğinde esnek sarma
- `.pc-max:flex-col` - Maksimum PC'de Flex Col
- `.pc-max:flex-nowrap` - PC max'ta Flex nowrap
- `.pc-max:flex-row` - PC max'ta esnek satır
- `.pc-max:flex-wrap` - PC max'ta esnek sarma

### Flex col

- `.flex-col-reverse` - Esnek sütun ters
- `.hover:flex-col-reverse` - Fareyle üzerine gelindiğinde sütunu ters çevirin

##### Flex col - Mobile (≤ 480px)

- `.hover:mobile:flex-col-reverse` - Mobil cihazda fareyle üzerine gelindiğinde Flex Col ters çevirin
- `.mobile:flex-col-reverse` - Mobil cihazda Flex Col ters

##### Flex col - Tablet (480px - 768px)

- `.hover:tablet:flex-col-reverse` - Tablette fareyle üzerine gelindiğinde Flex Col ters
- `.tablet:flex-col-reverse` - Tablette Flex col ters

##### Flex col - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col-reverse` - Tablet bilgisayarda fareyle üzerine gelindiğinde Flex col ters çevriliyor
- `.tablet-pc:flex-col-reverse` - Tablet bilgisayarda Flex col ters

##### Flex col - Pc (992px - 1200px)

- `.hover:pc:flex-col-reverse` - PC'de fareyle üzerine gelindiğinde Flex Col ters
- `.pc:flex-col-reverse` - PC'de Flex Col ters

##### Flex col - Tv (≥ 1200px)

- `.hover:tv:flex-col-reverse` - Televizyonda fareyle üzerine gelindiğinde Flex Col ters
- `.tv:flex-col-reverse` - Televizyonda Flex col ters

##### Flex col - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-col-reverse` - Tablet max üzerinde fareyle üzerine gelindiğinde Flex Col ters
- `.tablet-max:flex-col-reverse` - Tablet max'ta Flex col ters

##### Flex col - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - Tablet PC max'ta fareyle üzerine gelindiğinde Flex col ters çevirin
- `.tablet-pc-max:flex-col-reverse` - Tablet pc max'ta Flex col ters

##### Flex col - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-col-reverse` - PC max üzerinde fareyle üzerine gelindiğinde Flex Col ters
- `.pc-max:flex-col-reverse` - PC max'ta Flex col ters

### Flex row

- `.flex-row-reverse` - Esnek sıra ters
- `.hover:flex-row-reverse` - Fareyle üzerine gelindiğinde satırı ters yönde esnetin

##### Flex row - Mobile (≤ 480px)

- `.hover:mobile:flex-row-reverse` - Mobil cihazda fareyle üzerine gelindiğinde satırı ters yönde esnetin
- `.mobile:flex-row-reverse` - Mobil cihazda sırayı tersine çevirme

##### Flex row - Tablet (480px - 768px)

- `.hover:tablet:flex-row-reverse` - Tablette fareyle üzerine gelindiğinde satırı ters yönde esnetin
- `.tablet:flex-row-reverse` - Tablette esnek sıra ters

##### Flex row - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-row-reverse` - Tablet bilgisayarda fareyle üzerine gelindiğinde esnek sıra ters
- `.tablet-pc:flex-row-reverse` - Tablet bilgisayarda esnek sıra ters

##### Flex row - Pc (992px - 1200px)

- `.hover:pc:flex-row-reverse` - PC'de fareyle üzerine gelindiğinde sırayı tersine çevir
- `.pc:flex-row-reverse` - PC'de esnek sıra ters

##### Flex row - Tv (≥ 1200px)

- `.hover:tv:flex-row-reverse` - TV'de fareyle üzerine gelindiğinde satırı ters çevir
- `.tv:flex-row-reverse` - Televizyonda esnek satır ters

##### Flex row - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-row-reverse` - Maksimum tablette fareyle üzerine gelindiğinde satırı ters yönde esnetin
- `.tablet-max:flex-row-reverse` - Tablet max'ta esnek sıra ters

##### Flex row - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - Tablet PC max'ta fareyle üzerine gelindiğinde esnek sıra ters
- `.tablet-pc-max:flex-row-reverse` - Tablet pc max'ta esnek sıra ters

##### Flex row - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-row-reverse` - PC max'ta fareyle üzerine gelindiğinde esnek sıra ters
- `.pc-max:flex-row-reverse` - PC max'ta esnek sıra ters

### Flex grow

- `.flex-grow-3` - Esnek büyümek 3
- `.flex-grow-2` - Esnek büyümek 2
- `.flex-grow-1` - Esnek büyümek 1
- `.flex-grow-0` - Esnek büyümek 0
- `.hover:flex-grow-3` - Flex fareyle üzerine gelindiğinde 3 büyür
- `.hover:flex-grow-2` - Flex fareyle üzerine gelindiğinde 2 büyür
- `.hover:flex-grow-1` - Flex fareyle üzerine gelindiğinde 1 büyür
- `.hover:flex-grow-0` - Flex fareyle üzerine gelindiğinde 0 büyür

##### Flex grow - Mobile (≤ 480px)

- `.hover:mobile:flex-grow-3` - Flex, mobil cihazda fareyle üzerine gelindiğinde 3 büyütür
- `.hover:mobile:flex-grow-2` - Flex, mobil cihazda fareyle üzerine gelindiğinde 2 büyütür
- `.hover:mobile:flex-grow-1` - Flex, mobil cihazda fareyle üzerine gelindiğinde 1 büyür
- `.hover:mobile:flex-grow-0` - Flex, mobil cihazda fareyle üzerine gelindiğinde 0 büyütür
- `.mobile:flex-grow-3` - Flex mobil cihazda 3 büyütüyor
- `.mobile:flex-grow-2` - Flex mobil cihazda 2 büyütün
- `.mobile:flex-grow-1` - Flex mobilde 1 büyütün
- `.mobile:flex-grow-0` - Flex mobil cihazda 0 büyütün

##### Flex grow - Tablet (480px - 768px)

- `.hover:tablet:flex-grow-3` - Flex, tabletin üzerine gelindiğinde 3 büyütür
- `.hover:tablet:flex-grow-2` - Flex, tabletin üzerine gelindiğinde 2 büyütür
- `.hover:tablet:flex-grow-1` - Flex, tabletin üzerine gelindiğinde 1 büyür
- `.hover:tablet:flex-grow-0` - Flex, tabletin üzerine gelindiğinde 0 büyütür
- `.tablet:flex-grow-3` - Flex tablette 3 büyütüyor
- `.tablet:flex-grow-2` - Flex tablette 2 büyütün
- `.tablet:flex-grow-1` - Flex tablette 1 büyütüyor
- `.tablet:flex-grow-0` - Flex tablette 0 büyütüyor

##### Flex grow - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-grow-3` - Flex, tablet bilgisayarda fareyle üzerine gelindiğinde 3 büyütüyor
- `.hover:tablet-pc:flex-grow-2` - Flex, tablet bilgisayarda fareyle üzerine gelindiğinde 2 büyütüyor
- `.hover:tablet-pc:flex-grow-1` - Flex, tablet bilgisayarda fareyle üzerine gelindiğinde 1 büyütür
- `.hover:tablet-pc:flex-grow-0` - Flex, tablet bilgisayarda fareyle üzerine gelindiğinde 0 büyütür
- `.tablet-pc:flex-grow-3` - Tablet bilgisayarda Flex Grow 3
- `.tablet-pc:flex-grow-2` - Tablet PC'de Flex Grow 2
- `.tablet-pc:flex-grow-1` - Flex tablet bilgisayarda 1 büyütüyor
- `.tablet-pc:flex-grow-0` - Flex tablet bilgisayarda 0 büyütün

##### Flex grow - Pc (992px - 1200px)

- `.hover:pc:flex-grow-3` - Flex, PC'de fareyle üzerine gelindiğinde 3 büyütüyor
- `.hover:pc:flex-grow-2` - Flex, PC'de fareyle üzerine gelindiğinde 2 büyütüyor
- `.hover:pc:flex-grow-1` - Flex, PC'de fareyle üzerine gelindiğinde 1 büyütür
- `.hover:pc:flex-grow-0` - Flex, PC'de fareyle üzerine gelindiğinde 0 büyütüyor
- `.pc:flex-grow-3` - Flex PC'de 3 büyütüyor
- `.pc:flex-grow-2` - Flex PC'de 2 büyütüyor
- `.pc:flex-grow-1` - Flex PC'de 1 büyütüyor
- `.pc:flex-grow-0` - Flex PC'de 0 büyütün

##### Flex grow - Tv (≥ 1200px)

- `.hover:tv:flex-grow-3` - Flex, televizyonda fareyle üzerine gelindiğinde 3 büyütüyor
- `.hover:tv:flex-grow-2` - Flex, televizyonda fareyle üzerine gelindiğinde 2 büyütüyor
- `.hover:tv:flex-grow-1` - Flex televizyonda fareyle üzerine gelindiğinde 1 büyütüyor
- `.hover:tv:flex-grow-0` - Flex, televizyonda fareyle üzerine gelindiğinde 0 büyütüyor
- `.tv:flex-grow-3` - Flex TV'de 3 büyütüyor
- `.tv:flex-grow-2` - Flex televizyonda 2 büyütün
- `.tv:flex-grow-1` - Flex televizyonda 1 büyütüyor
- `.tv:flex-grow-0` - Flex televizyonda 0 büyütüyor

##### Flex grow - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-grow-3` - Flex, tablet max üzerinde fareyle üzerine gelindiğinde 3 büyür
- `.hover:tablet-max:flex-grow-2` - Flex, tablet max üzerinde fareyle üzerine gelindiğinde 2 büyür
- `.hover:tablet-max:flex-grow-1` - Flex, tablet max'ın üzerine gelindiğinde 1 büyür
- `.hover:tablet-max:flex-grow-0` - Flex, tablet max'ın üzerine gelindiğinde 0 büyür
- `.tablet-max:flex-grow-3` - Flex tablet max'ta 3 büyütün
- `.tablet-max:flex-grow-2` - Flex tablet max'ta 2 büyütün
- `.tablet-max:flex-grow-1` - Flex tablette maksimum 1 büyütün
- `.tablet-max:flex-grow-0` - Flex tablet max'ta 0 büyütün

##### Flex grow - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex, tablet PC max üzerinde fareyle üzerine gelindiğinde 3 büyütür
- `.hover:tablet-pc-max:flex-grow-2` - Flex, tablet PC max üzerinde fareyle üzerine gelindiğinde 2 büyütür
- `.hover:tablet-pc-max:flex-grow-1` - Flex, tablet PC max'ta fareyle üzerine gelindiğinde 1 büyür
- `.hover:tablet-pc-max:flex-grow-0` - Flex, tablet pc max'ta fareyle üzerine gelindiğinde 0 büyütür
- `.tablet-pc-max:flex-grow-3` - Flex tablet pc max'ta 3 büyütün
- `.tablet-pc-max:flex-grow-2` - Flex tablet pc max'ta 2 büyütün
- `.tablet-pc-max:flex-grow-1` - Flex tablet pc max'ta 1 büyütün
- `.tablet-pc-max:flex-grow-0` - Flex tablet pc max'ta 0 büyütün

##### Flex grow - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-grow-3` - Flex, PC max'ta fareyle üzerine gelindiğinde 3 büyütür
- `.hover:pc-max:flex-grow-2` - Flex, PC max'ta fareyle üzerine gelindiğinde 2 büyütür
- `.hover:pc-max:flex-grow-1` - Flex, PC max üzerinde fareyle üzerine gelindiğinde 1 büyür
- `.hover:pc-max:flex-grow-0` - Flex, PC max üzerinde fareyle üzerine gelindiğinde 0 büyütür
- `.pc-max:flex-grow-3` - Flex PC max'ta 3 büyütün
- `.pc-max:flex-grow-2` - Flex PC'de maksimum 2 büyütün
- `.pc-max:flex-grow-1` - Flex PC'de maksimum 1 büyütün
- `.pc-max:flex-grow-0` - Flex PC'de maksimum 0 büyütün

### Flex wrap

- `.flex-wrap-reverse` - Flex sarma ters
- `.hover:flex-wrap-reverse` - Fareyle üzerine gelindiğinde ters yönde esnek sarma

##### Flex wrap - Mobile (≤ 480px)

- `.hover:mobile:flex-wrap-reverse` - Mobil cihazda fareyle üzerine gelindiğinde esnek sarma ters
- `.mobile:flex-wrap-reverse` - Mobil cihazda esnek sarma ters

##### Flex wrap - Tablet (480px - 768px)

- `.hover:tablet:flex-wrap-reverse` - Tablet üzerinde fareyle üzerine gelindiğinde ters sarma
- `.tablet:flex-wrap-reverse` - Tablette esnek sarma ters

##### Flex wrap - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-wrap-reverse` - Tablet bilgisayarda fareyle üzerine gelindiğinde Flex sarma ters yönde
- `.tablet-pc:flex-wrap-reverse` - Tablet PC'de Flex Wrap ters

##### Flex wrap - Pc (992px - 1200px)

- `.hover:pc:flex-wrap-reverse` - PC'de fareyle üzerine gelindiğinde esnek sarma ters
- `.pc:flex-wrap-reverse` - PC'de esnek sarma ters

##### Flex wrap - Tv (≥ 1200px)

- `.hover:tv:flex-wrap-reverse` - Televizyonda fareyle üzerine gelindiğinde ters sarma
- `.tv:flex-wrap-reverse` - Televizyonda ters sarma

##### Flex wrap - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-wrap-reverse` - Tablet max'te fareyle üzerine gelindiğinde ters yönde esnek sarma
- `.tablet-max:flex-wrap-reverse` - Tablet max'ta ters yönde esnek sarma

##### Flex wrap - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - Tablet PC max'ta fareyle üzerine gelindiğinde ters sarma
- `.tablet-pc-max:flex-wrap-reverse` - Tablet PC Max'te Flex Wrap ters

##### Flex wrap - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-wrap-reverse` - PC max'ta fareyle üzerine gelindiğinde ters yönde esnek sarma
- `.pc-max:flex-wrap-reverse` - PC max'ta esnek sarma ters

### Gap

#### Gap All

- `.gap-5` - Tüm 5rem boşluğu
- `.gap-4.5` - Tüm Boşluk 0rem
- `.gap-4` - Tüm 4rem boşluğu
- `.gap-3.5` - Tüm Boşluk 0rem
- `.gap-3` - Tüm 3rem boşluğu
- `.gap-2.5` - Tüm Boşluk 0rem
- `.gap-2` - Tüm Boşluk 2rem
- `.gap-1.9` - Tüm Boşluk 0rem
- `.gap-1.8` - Tüm Boşluk 0rem
- `.gap-1.7` - Tüm Boşluk 0rem
- `.gap-1.6` - Tüm Boşluk 0rem
- `.gap-1.5` - Tüm Boşluk 0rem
- `.gap-1.4` - Tüm Boşluk 0rem
- `.gap-1.3` - Tüm Boşluk 0rem
- `.gap-1.2` - Tüm Boşluk 0rem
- `.gap-1.1` - Tüm Boşluk 0rem
- `.gap-1` - Tüm Boşluk 1rem
- `.gap-0.9` - Tüm Boşluk 0rem
- `.gap-0.8` - Tüm Boşluk 0rem
- `.gap-0.7` - Tüm Boşluk 0rem
- `.gap-0.6` - Tüm Boşluk 0rem
- `.gap-0.5` - Tüm Boşluk 0rem
- `.gap-0.4` - Tüm Boşluk 0rem
- `.gap-0.3` - Tüm Boşluk 0rem
- `.gap-0.2` - Tüm Boşluk 0,2rem
- `.gap-0.1` - Tüm Boşluk 0,1 rem
- `.gap-0` - Tüm Boşluk 0rem
- `.hover:gap-5` - Fareyle üzerine gelindiğinde 5rem'in tamamındaki boşluk
- `.hover:gap-4.5` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-4` - Fareyle üzerine gelindiğinde Tüm 4rem'deki boşluk
- `.hover:gap-3.5` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-3` - Fareyle üzerine gelindiğinde Tüm 3rem'lik boşluk
- `.hover:gap-2.5` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-2` - Fareyle üzerine gelindiğinde Tümü 2rem Aralığı
- `.hover:gap-1.9` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.8` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.7` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.6` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.5` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.4` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.3` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.2` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1.1` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-1` - Vurguluyken Tümü 1rem Aralığı
- `.hover:gap-0.9` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.8` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.7` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.6` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.5` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.4` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.3` - Vurguluyken Tüm 0rem'i Boşaltın
- `.hover:gap-0.2` - Fareyle üzerine gelindiğinde Tüm Boşluk 0,2rem
- `.hover:gap-0.1` - Fareyle üzerine gelindiğinde Tüm Boşluk 0,1 rem
- `.hover:gap-0` - Vurguluyken Tüm 0rem'i Boşaltın

#### Gap X-Axis

- `.gap-x-5` - Boşluk X Ekseni 5rem
- `.gap-x-4.5` - Boşluk X Ekseni 0rem
- `.gap-x-4` - Boşluk X Ekseni 4rem
- `.gap-x-3.5` - Boşluk X Ekseni 0rem
- `.gap-x-3` - Boşluk X Ekseni 3rem
- `.gap-x-2.5` - Boşluk X Ekseni 0rem
- `.gap-x-2` - Boşluk X Ekseni 2rem
- `.gap-x-1.9` - Boşluk X Ekseni 0rem
- `.gap-x-1.8` - Boşluk X Ekseni 0rem
- `.gap-x-1.7` - Boşluk X Ekseni 0rem
- `.gap-x-1.6` - Boşluk X Ekseni 0rem
- `.gap-x-1.5` - Boşluk X Ekseni 0rem
- `.gap-x-1.4` - Boşluk X Ekseni 0rem
- `.gap-x-1.3` - Boşluk X Ekseni 0rem
- `.gap-x-1.2` - Boşluk X Ekseni 0rem
- `.gap-x-1.1` - Boşluk X Ekseni 0rem
- `.gap-x-1` - Boşluk X Ekseni 1rem
- `.gap-x-0.9` - Boşluk X Ekseni 0rem
- `.gap-x-0.8` - Boşluk X Ekseni 0rem
- `.gap-x-0.7` - Boşluk X Ekseni 0rem
- `.gap-x-0.6` - Boşluk X Ekseni 0rem
- `.gap-x-0.5` - Boşluk X Ekseni 0rem
- `.gap-x-0.4` - Boşluk X Ekseni 0rem
- `.gap-x-0.3` - Boşluk X Ekseni 0rem
- `.gap-x-0.2` - Boşluk X Ekseni 0,2 rem
- `.gap-x-0.1` - Boşluk X Ekseni 0,1 rem
- `.gap-x-0` - Boşluk X Ekseni 0rem
- `.hover:gap-x-5` - Fareyle üzerine gelindiğinde X Ekseni Gap 5rem
- `.hover:gap-x-4.5` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-4` - Vurguluyken Gap X Ekseni 4rem
- `.hover:gap-x-3.5` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-3` - Fareyle üzerine gelindiğinde X Ekseni Gap 3rem
- `.hover:gap-x-2.5` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-2` - Fareyle üzerine gelindiğinde X Ekseni Gap 2rem
- `.hover:gap-x-1.9` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.8` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.7` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.6` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.5` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.4` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.3` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.2` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1.1` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-1` - Fareyle üzerine gelindiğinde X Ekseni 1rem boşluğu
- `.hover:gap-x-0.9` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.8` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.7` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.6` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.5` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.4` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.3` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem
- `.hover:gap-x-0.2` - Fareyle üzerine gelindiğinde X Ekseni Gap 0,2rem
- `.hover:gap-x-0.1` - Fareyle üzerine gelindiğinde X Ekseni Gap 0,1rem
- `.hover:gap-x-0` - Fareyle üzerine gelindiğinde X Ekseni Gap 0rem

#### Gap Y-Axis

- `.gap-y-5` - Boşluk Y Ekseni 5rem
- `.gap-y-4.5` - Boşluk Y Ekseni 0rem
- `.gap-y-4` - Boşluk Y Ekseni 4rem
- `.gap-y-3.5` - Boşluk Y Ekseni 0rem
- `.gap-y-3` - Boşluk Y Ekseni 3rem
- `.gap-y-2.5` - Boşluk Y Ekseni 0rem
- `.gap-y-2` - Boşluk Y Ekseni 2rem
- `.gap-y-1.9` - Boşluk Y Ekseni 0rem
- `.gap-y-1.8` - Boşluk Y Ekseni 0rem
- `.gap-y-1.7` - Boşluk Y Ekseni 0rem
- `.gap-y-1.6` - Boşluk Y Ekseni 0rem
- `.gap-y-1.5` - Boşluk Y Ekseni 0rem
- `.gap-y-1.4` - Boşluk Y Ekseni 0rem
- `.gap-y-1.3` - Boşluk Y Ekseni 0rem
- `.gap-y-1.2` - Boşluk Y Ekseni 0rem
- `.gap-y-1.1` - Boşluk Y Ekseni 0rem
- `.gap-y-1` - Boşluk Y Ekseni 1rem
- `.gap-y-0.9` - Boşluk Y Ekseni 0rem
- `.gap-y-0.8` - Boşluk Y Ekseni 0rem
- `.gap-y-0.7` - Boşluk Y Ekseni 0rem
- `.gap-y-0.6` - Boşluk Y Ekseni 0rem
- `.gap-y-0.5` - Boşluk Y Ekseni 0rem
- `.gap-y-0.4` - Boşluk Y Ekseni 0rem
- `.gap-y-0.3` - Boşluk Y Ekseni 0rem
- `.gap-y-0.2` - Boşluk Y Ekseni 0,2rem
- `.gap-y-0.1` - Boşluk Y Ekseni 0,1 rem
- `.gap-y-0` - Boşluk Y Ekseni 0rem
- `.hover:gap-y-5` - Fareyle üzerine gelindiğinde Y Ekseni boşluğu 5rem
- `.hover:gap-y-4.5` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-4` - Fareyle üzerine gelindiğinde Y Ekseni Gap 4rem
- `.hover:gap-y-3.5` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-3` - Fareyle üzerine gelindiğinde Y Ekseni Gap 3rem
- `.hover:gap-y-2.5` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-2` - Fareyle üzerine gelindiğinde Y Ekseni Gap 2rem
- `.hover:gap-y-1.9` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.8` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.7` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.6` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.5` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.4` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.3` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.2` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1.1` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-1` - Fareyle üzerine gelindiğinde Y Ekseni boşluğu 1rem
- `.hover:gap-y-0.9` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.8` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.7` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.6` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.5` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.4` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.3` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem
- `.hover:gap-y-0.2` - Vurguluyken Y Ekseni Boşluğu 0,2rem
- `.hover:gap-y-0.1` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0,1 rem
- `.hover:gap-y-0` - Fareyle üzerine gelindiğinde Y Ekseni Boşluğu 0rem

### Align content

- `.align-content-around` - İçeriği hizalayın
- `.align-content-between` - İçerikleri arasında hizalayın
- `.align-content-center` - İçerik merkezini hizalayın
- `.align-content-end` - İçerik ucunu hizala
- `.align-content-evenly` - İçeriği eşit şekilde hizalayın
- `.align-content-start` - İçerik başlangıcını hizala
- `.align-content-stretch` - İçerik genişletmeyi hizalayın
- `.hover:align-content-around` - İçeriği fareyle üzerine gelindiğinde hizalayın
- `.hover:align-content-between` - İçeriği fareyle üzerine gelindiğinde hizalama
- `.hover:align-content-center` - Fareyle üzerine gelindiğinde içerik merkezini hizalayın
- `.hover:align-content-end` - İçerik ucunu fareyle üzerine gelindiğinde hizalayın
- `.hover:align-content-evenly` - İçeriği fareyle üzerine gelindiğinde eşit şekilde hizalayın
- `.hover:align-content-start` - İçerik başlangıcını fareyle üzerine gelindiğinde hizalayın
- `.hover:align-content-stretch` - Fareyle üzerine gelindiğinde içerik uzantısını hizalayın

##### Align content - Mobile (≤ 480px)

- `.hover:mobile:align-content-around` - Mobil cihazda fareyle üzerine gelindiğinde içeriği hizalayın
- `.hover:mobile:align-content-between` - Mobil cihazda fareyle üzerine gelindiğinde içeriği hizalayın
- `.hover:mobile:align-content-center` - Mobil cihazda fareyle üzerine gelindiğinde içerik merkezini hizalayın
- `.hover:mobile:align-content-end` - Mobil cihazda fareyle üzerine gelindiğinde içeriğin ucunu hizalayın
- `.hover:mobile:align-content-evenly` - Mobil cihazda fareyle üzerine gelindiğinde içeriği eşit şekilde hizalayın
- `.hover:mobile:align-content-start` - Mobil cihazda fareyle üzerine gelindiğinde içerik başlangıcını hizalayın
- `.hover:mobile:align-content-stretch` - Mobil cihazda fareyle üzerine gelindiğinde içerik uzantısını hizalayın
- `.mobile:align-content-around` - İçeriği mobil cihazlarda hizalayın
- `.mobile:align-content-between` - İçeriği mobil cihazlar arasında hizalayın
- `.mobile:align-content-center` - İçerik merkezini mobil cihazda hizalayın
- `.mobile:align-content-end` - Mobil cihazda içerik ucunu hizalayın
- `.mobile:align-content-evenly` - İçeriği mobil cihazlarda eşit şekilde hizalayın
- `.mobile:align-content-start` - Mobil cihazda içerik başlangıcını hizalayın
- `.mobile:align-content-stretch` - Mobil cihazlarda içerik genişletmeyi hizalayın

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - İçeriği tablette fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet:align-content-between` - İçeriği tablette fareyle üzerine gelindiğinde hizalama
- `.hover:tablet:align-content-center` - İçerik merkezini tablet üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet:align-content-end` - İçerik ucunu tablette fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet:align-content-evenly` - Tabletin üzerine gelindiğinde içeriği eşit şekilde hizalayın
- `.hover:tablet:align-content-start` - İçerik başlangıcını tablette fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet:align-content-stretch` - Tablette fareyle üzerine gelindiğinde içerik uzantısını hizalayın
- `.tablet:align-content-around` - İçeriği tablette hizalayın
- `.tablet:align-content-between` - İçeriği tablettekiler arasında hizalayın
- `.tablet:align-content-center` - İçerik merkezini tablette hizalayın
- `.tablet:align-content-end` - İçerik ucunu tablette hizalayın
- `.tablet:align-content-evenly` - İçeriği tablette eşit şekilde hizalayın
- `.tablet:align-content-start` - Tabletteki içerik başlangıcını hizalayın
- `.tablet:align-content-stretch` - Tabletteki içerik genişletmeyi hizalama

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - İçeriği tablet bilgisayarda fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc:align-content-between` - İçeriği tablet bilgisayarda fareyle üzerine gelindiğinde hizalama
- `.hover:tablet-pc:align-content-center` - İçerik merkezini tablet bilgisayardaki fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc:align-content-end` - Tablet bilgisayarda fareyle üzerine gelindiğinde içerik ucunu hizalayın
- `.hover:tablet-pc:align-content-evenly` - İçeriği tablet bilgisayardaki fareyle üzerine gelindiğinde eşit şekilde hizalayın
- `.hover:tablet-pc:align-content-start` - İçerik başlangıcını tablet bilgisayarda fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc:align-content-stretch` - Tablet bilgisayarda fareyle üzerine gelindiğinde içerik genişletmeyi hizalayın
- `.tablet-pc:align-content-around` - Tablet PC'deki içeriği hizalayın
- `.tablet-pc:align-content-between` - İçeriği tablet bilgisayar arasında hizalayın
- `.tablet-pc:align-content-center` - Tablet PC'deki içerik merkezini hizalayın
- `.tablet-pc:align-content-end` - Tablet PC'de içerik ucunu hizalayın
- `.tablet-pc:align-content-evenly` - İçeriği tablet bilgisayarda eşit şekilde hizalayın
- `.tablet-pc:align-content-start` - Tablet PC'de içerik başlangıcını hizalayın
- `.tablet-pc:align-content-stretch` - Tablet bilgisayarda içerik genişletmeyi hizalama

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - PC'de fareyle üzerine gelindiğinde içeriği hizalayın
- `.hover:pc:align-content-between` - İçeriği PC'de fareyle üzerine gelindiğinde hizalayın
- `.hover:pc:align-content-center` - İçerik merkezini bilgisayardaki fareyle üzerine gelindiğinde hizalayın
- `.hover:pc:align-content-end` - PC'de fareyle üzerine gelindiğinde içeriğin ucunu hizalayın
- `.hover:pc:align-content-evenly` - PC'de fareyle üzerine gelindiğinde içeriği eşit şekilde hizalayın
- `.hover:pc:align-content-start` - İçerik başlangıcını bilgisayarda fareyle üzerine gelindiğinde hizalayın
- `.hover:pc:align-content-stretch` - PC'de fareyle üzerine gelindiğinde içerik uzantısını hizalayın
- `.pc:align-content-around` - İçeriği PC'de hizalayın
- `.pc:align-content-between` - İçeriği bilgisayardakiler arasında hizalayın
- `.pc:align-content-center` - PC'deki içerik merkezini hizalayın
- `.pc:align-content-end` - İçeriğin ucunu bilgisayarda hizalayın
- `.pc:align-content-evenly` - İçeriği bilgisayarda eşit şekilde hizalayın
- `.pc:align-content-start` - PC'de içerik başlangıcını hizalayın
- `.pc:align-content-stretch` - PC'de içerik genişletmeyi hizalama

##### Align content - Tv (≥ 1200px)

- `.hover:tv:align-content-around` - Televizyonun üzerine gelindiğinde içeriği hizalayın
- `.hover:tv:align-content-between` - İçeriği TV'de fareyle üzerine gelindiğinde hizalama
- `.hover:tv:align-content-center` - İçerik merkezini TV'de fareyle üzerine gelindiğinde hizalayın
- `.hover:tv:align-content-end` - İçeriğin ucunu TV'de fareyle üzerine gelindiğinde hizalayın
- `.hover:tv:align-content-evenly` - Televizyonun üzerine gelindiğinde içeriği eşit şekilde hizalayın
- `.hover:tv:align-content-start` - İçerik başlangıcını TV'de fareyle üzerine gelindiğinde hizalayın
- `.hover:tv:align-content-stretch` - TV'de fareyle üzerine gelindiğinde içerik uzantısını hizalayın
- `.tv:align-content-around` - İçeriği TV'de hizalayın
- `.tv:align-content-between` - İçeriği TV'dekiler arasında hizalayın
- `.tv:align-content-center` - İçerik merkezini TV'de hizalayın
- `.tv:align-content-end` - İçerik ucunu TV'de hizalayın
- `.tv:align-content-evenly` - İçeriği TV'de eşit şekilde hizalayın
- `.tv:align-content-start` - İçerik başlangıcını TV'de hizalayın
- `.tv:align-content-stretch` - TV'deki içerik uzantısını hizalayın

##### Align content - Tablet Max (≤ 768px)

- `.hover:tablet-max:align-content-around` - İçeriği tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-max:align-content-between` - İçeriği tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-max:align-content-center` - İçerik merkezini tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-max:align-content-end` - İçerik ucunu tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-max:align-content-evenly` - İçeriği tablet max üzerinde fareyle üzerine gelindiğinde eşit şekilde hizalayın
- `.hover:tablet-max:align-content-start` - İçerik başlangıcını tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-max:align-content-stretch` - Tablet max üzerinde fareyle üzerine gelindiğinde içerik genişletmeyi hizalayın
- `.tablet-max:align-content-around` - İçeriği tablet max'a göre hizalayın
- `.tablet-max:align-content-between` - İçeriği tablet max arasında hizalayın
- `.tablet-max:align-content-center` - İçerik merkezini tablet max'ta hizalayın
- `.tablet-max:align-content-end` - İçeriğin ucunu tablet max'ta hizalayın
- `.tablet-max:align-content-evenly` - İçeriği tablet max'ta eşit şekilde hizalayın
- `.tablet-max:align-content-start` - İçerik başlangıcını tablet max'ta hizalayın
- `.tablet-max:align-content-stretch` - Tablet max'te içerik genişletmeyi hizalayın

##### Align content - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:align-content-around` - Tablet PC Max'te fareyle üzerine gelindiğinde içeriği hizalayın
- `.hover:tablet-pc-max:align-content-between` - İçeriği tablet PC max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc-max:align-content-center` - İçerik merkezini tablet pc max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc-max:align-content-end` - Tablet PC Max'te fareyle üzerine gelindiğinde içerik ucunu hizalayın
- `.hover:tablet-pc-max:align-content-evenly` - Tablet PC max üzerinde fareyle üzerine gelindiğinde içeriği eşit şekilde hizalayın
- `.hover:tablet-pc-max:align-content-start` - İçerik başlangıcını tablet pc max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc-max:align-content-stretch` - Tablet PC Max'te fareyle üzerine gelindiğinde içerik genişletmeyi hizalayın
- `.tablet-pc-max:align-content-around` - İçeriği tablet pc max'a göre hizalayın
- `.tablet-pc-max:align-content-between` - İçeriği tablet pc max arasında hizalayın
- `.tablet-pc-max:align-content-center` - İçerik merkezini tablet pc max'ta hizalayın
- `.tablet-pc-max:align-content-end` - Tablet PC max'ta içerik ucunu hizalayın
- `.tablet-pc-max:align-content-evenly` - İçeriği tablet pc max'ta eşit şekilde hizalayın
- `.tablet-pc-max:align-content-start` - Tablet PC Max'te içerik başlangıcını hizalayın
- `.tablet-pc-max:align-content-stretch` - Tablet PC Max'te içerik genişletmeyi hizalama

##### Align content - Pc Max (≤ 1200px)

- `.hover:pc-max:align-content-around` - PC max'ta fareyle üzerine gelindiğinde içeriği hizalayın
- `.hover:pc-max:align-content-between` - İçeriği PC max'ta fareyle üzerine gelindiğinde hizalayın
- `.hover:pc-max:align-content-center` - PC max üzerinde fareyle üzerine gelindiğinde içerik merkezini hizalayın
- `.hover:pc-max:align-content-end` - PC max'ta fareyle üzerine gelindiğinde içeriğin ucunu hizalayın
- `.hover:pc-max:align-content-evenly` - PC max'ta fareyle üzerine gelindiğinde içeriği eşit şekilde hizalayın
- `.hover:pc-max:align-content-start` - İçerik başlangıcını PC max'ta fareyle üzerine gelindiğinde hizalayın
- `.hover:pc-max:align-content-stretch` - PC max'ta fareyle üzerine gelindiğinde içerik genişletmeyi hizalayın
- `.pc-max:align-content-around` - İçeriği pc max'a göre hizalayın
- `.pc-max:align-content-between` - İçeriği PC max arasında hizalayın
- `.pc-max:align-content-center` - İçerik merkezini pc max'ta hizalayın
- `.pc-max:align-content-end` - İçeriğin ucunu pc max'ta hizalayın
- `.pc-max:align-content-evenly` - İçeriği pc max'ta eşit şekilde hizalayın
- `.pc-max:align-content-start` - İçerik başlangıcını PC max'ta hizalayın
- `.pc-max:align-content-stretch` - PC max'ta içerik genişletmeyi hizalayın

### Align items

- `.align-items-center` - Öğe merkezini hizala
- `.align-items-end` - Öğelerin sonunu hizala
- `.align-items-start` - Öğeleri hizalama başlangıcı
- `.align-items-stretch` - Öğeleri hizalayın
- `.hover:align-items-center` - Fareyle üzerine gelindiğinde öğelerin ortasını hizalayın
- `.hover:align-items-end` - Fareyle üzerine gelindiğinde öğeleri hizalama
- `.hover:align-items-start` - Öğeleri hizalama fareyle üzerine gelindiğinde başlar
- `.hover:align-items-stretch` - Fareyle üzerine gelindiğinde öğeleri hizalayın

##### Align items - Mobile (≤ 480px)

- `.hover:mobile:align-items-center` - Mobil cihazda fareyle üzerine gelindiğinde öğelerin ortasını hizalayın
- `.hover:mobile:align-items-end` - Öğeleri mobil cihazda fareyle üzerine gelindiğinde hizalayın
- `.hover:mobile:align-items-start` - Öğeleri hizalama, mobil cihazda fareyle üzerine gelindiğinde başlar
- `.hover:mobile:align-items-stretch` - Mobil cihazda fareyle üzerine gelindiğinde öğeleri hizalayın
- `.mobile:align-items-center` - Mobil cihazdaki öğelerin merkezini hizalayın
- `.mobile:align-items-end` - Mobil cihazda öğelerin sonunu hizalama
- `.mobile:align-items-start` - Öğeleri hizalama mobilde başlar
- `.mobile:align-items-stretch` - Mobil cihazdaki öğeleri hizalayın

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - Tabletteki fareyle üzerine gelindiğinde öğelerin ortasını hizalayın
- `.hover:tablet:align-items-end` - Öğeleri tablet üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet:align-items-start` - Öğeleri hizalama tabletin üzerine gelindiğinde başlar
- `.hover:tablet:align-items-stretch` - Tablette fareyle üzerine gelindiğinde öğeleri hizalayın
- `.tablet:align-items-center` - Tabletteki öğelerin ortasını hizalayın
- `.tablet:align-items-end` - Öğeleri tablette hizalayın
- `.tablet:align-items-start` - Öğeleri hizalama tablette başlar
- `.tablet:align-items-stretch` - Tabletteki öğeleri hizalayın

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - Tablet PC'de fareyle üzerine gelindiğinde öğelerin ortasını hizalayın
- `.hover:tablet-pc:align-items-end` - Öğeleri tablet bilgisayarda fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-pc:align-items-start` - Öğeleri hizalama tablet bilgisayarda fareyle üzerine gelindiğinde başlar
- `.hover:tablet-pc:align-items-stretch` - Tablet bilgisayarda fareyle üzerine gelindiğinde öğeleri hizalayın
- `.tablet-pc:align-items-center` - Tablet PC'deki öğelerin merkezini hizalama
- `.tablet-pc:align-items-end` - Öğeleri tablet bilgisayarda hizalayın
- `.tablet-pc:align-items-start` - Öğeleri hizalama tablet bilgisayarda başlar
- `.tablet-pc:align-items-stretch` - Tablet PC'deki öğeleri hizalayın

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - PC'de fareyle üzerine gelindiğinde öğelerin merkezini hizalayın
- `.hover:pc:align-items-end` - Öğeleri PC'de fareyle üzerine gelindiğinde hizalayın
- `.hover:pc:align-items-start` - Öğeleri hizalama, bilgisayarda fareyle üzerine gelindiğinde başlar
- `.hover:pc:align-items-stretch` - PC'de fareyle üzerine gelindiğinde öğeleri hizalayın
- `.pc:align-items-center` - PC'deki öğelerin merkezini hizalama
- `.pc:align-items-end` - Öğeleri PC'de hizalayın
- `.pc:align-items-start` - Öğeleri hizalama bilgisayarda başlar
- `.pc:align-items-stretch` - PC'deki öğeleri hizalayın

##### Align items - Tv (≥ 1200px)

- `.hover:tv:align-items-center` - Televizyondaki fareyle üzerine gelindiğinde öğelerin ortasını hizalayın
- `.hover:tv:align-items-end` - Öğeleri TV'de fareyle üzerine gelindiğinde hizalayın
- `.hover:tv:align-items-start` - Öğeleri hizalama, televizyondaki fareyle üzerine gelindiğinde başlar
- `.hover:tv:align-items-stretch` - TV'de fareyle üzerine gelindiğinde öğeleri hizalayın
- `.tv:align-items-center` - TV'deki öğelerin merkezini hizalama
- `.tv:align-items-end` - Öğeleri TV'de hizalayın
- `.tv:align-items-start` - Öğeleri hizalama TV'de başlar
- `.tv:align-items-stretch` - TV'deki öğeleri hizalayın

##### Align items - Tablet Max (≤ 768px)

- `.hover:tablet-max:align-items-center` - Tablet max üzerinde fareyle üzerine gelindiğinde öğelerin merkezini hizalayın
- `.hover:tablet-max:align-items-end` - Öğeleri tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.hover:tablet-max:align-items-start` - Öğeleri hizalama, tablet max üzerinde fareyle üzerine gelindiğinde başlar
- `.hover:tablet-max:align-items-stretch` - Öğeleri tablet max üzerinde fareyle üzerine gelindiğinde hizalayın
- `.tablet-max:align-items-center` - Öğeleri tablet max'ta ortalayarak hizalayın
- `.tablet-max:align-items-end` - Öğeleri tablet max'ta hizalayın
- `.tablet-max:align-items-start` - Öğeleri hizalama tablet max'ta başlar
- `.tablet-max:align-items-stretch` - Öğeleri tablet max üzerinde hizalayın

##### Align items - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:align-items-center` - Tablet PC Max'te fareyle üzerine gelindiğinde öğelerin merkezini hizalayın
- `.hover:tablet-pc-max:align-items-end` - Öğeleri hizalama, tablet PC max'ta fareyle üzerine gelindiğinde sona eriyor
- `.hover:tablet-pc-max:align-items-start` - Öğeleri hizalama, tablet pc max'ta fareyle üzerine gelindiğinde başlar
- `.hover:tablet-pc-max:align-items-stretch` - Tablet PC max'ta fareyle üzerine gelindiğinde öğeleri hizalayın
- `.tablet-pc-max:align-items-center` - Tablet PC Max'te öğelerin merkezini hizalayın
- `.tablet-pc-max:align-items-end` - Öğeleri tablet pc max'ta hizalayın
- `.tablet-pc-max:align-items-start` - Öğeleri hizalama tablet pc max'ta başlar
- `.tablet-pc-max:align-items-stretch` - Tablet PC'de gerilmiş öğeleri hizalama max

##### Align items - Pc Max (≤ 1200px)

- `.hover:pc-max:align-items-center` - PC max'ta fareyle üzerine gelindiğinde öğelerin merkezini hizalayın
- `.hover:pc-max:align-items-end` - Öğeleri hizalama, PC max'ta fareyle üzerine gelindiğinde sona erer
- `.hover:pc-max:align-items-start` - Öğeleri hizalama, PC max'ta fareyle üzerine gelindiğinde başlar
- `.hover:pc-max:align-items-stretch` - PC max'ta fareyle üzerine gelindiğinde öğeleri hizalayın
- `.pc-max:align-items-center` - PC max'ta öğelerin merkezini hizalayın
- `.pc-max:align-items-end` - Öğeleri PC max'ta hizalayın
- `.pc-max:align-items-start` - Öğeleri hizalama PC max'ta başlar
- `.pc-max:align-items-stretch` - PC max'ta öğeleri hizalayın

### Align self

- `.align-self-center` - Kendi merkezini hizala
- `.align-self-end` - Kendi ucunu hizala
- `.align-self-start` - Otomatik başlatmayı hizalayın
- `.align-self-stretch` - Kendi kendine esnemeyi hizalayın
- `.hover:align-self-center` - Fareyle üzerine gelindiğinde kendi merkezini hizala
- `.hover:align-self-end` - Fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:align-self-start` - Fareyle üzerine gelindiğinde otomatik başlatmayı hizalayın
- `.hover:align-self-stretch` - Fareyle üzerine gelindiğinde kendini uzatmayı hizalayın

##### Align self - Mobile (≤ 480px)

- `.hover:mobile:align-self-center` - Mobil cihazda fareyle üzerine gelindiğinde kendi merkezimi hizalama
- `.hover:mobile:align-self-end` - Mobil cihazda fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:mobile:align-self-start` - Mobil cihazda fareyle üzerine gelindiğinde otomatik başlatmayı hizalama
- `.hover:mobile:align-self-stretch` - Mobil cihazda fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.mobile:align-self-center` - Mobil cihazda benlik merkezini hizalama
- `.mobile:align-self-end` - Mobil cihazda kendi ucunu hizalama
- `.mobile:align-self-start` - Mobil cihazda otomatik başlatmayı hizalama
- `.mobile:align-self-stretch` - Mobil cihazda kendi kendine esnemeyi hizalayın

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - Tabletin fareyle üzerine gelindiğinde kendi merkezini hizala
- `.hover:tablet:align-self-end` - Tabletin üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:tablet:align-self-start` - Tablet üzerinde fareyle üzerine gelindiğinde otomatik başlatmayı hizalayın
- `.hover:tablet:align-self-stretch` - Tablet üzerinde fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.tablet:align-self-center` - Tablette benlik merkezini hizalama
- `.tablet:align-self-end` - Kendi ucunu tablette hizala
- `.tablet:align-self-start` - Tablette otomatik başlatmayı hizalama
- `.tablet:align-self-stretch` - Tablette kendi kendine esnemeyi hizalayın

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - Tablet bilgisayarda fareyle üzerine gelindiğinde kendi merkezini hizalayın
- `.hover:tablet-pc:align-self-end` - Tablet PC'de fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:tablet-pc:align-self-start` - Tablet bilgisayarda fareyle üzerine gelindiğinde otomatik başlatmayı hizalama
- `.hover:tablet-pc:align-self-stretch` - Tablet bilgisayarda fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.tablet-pc:align-self-center` - Tablet bilgisayarda benlik merkezini hizalama
- `.tablet-pc:align-self-end` - Tablet PC'de kendi ucunu hizalayın
- `.tablet-pc:align-self-start` - Tablet PC'de otomatik başlatmayı hizalama
- `.tablet-pc:align-self-stretch` - Tablet PC'de kendi kendine gerdirmeyi hizalayın

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - PC'de fareyle üzerine gelindiğinde kendi merkezini hizalayın
- `.hover:pc:align-self-end` - PC'de fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:pc:align-self-start` - PC'de fareyle üzerine gelindiğinde kendi kendine başlamayı hizalayın
- `.hover:pc:align-self-stretch` - PC'de fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.pc:align-self-center` - PC'de kişisel merkezi hizalama
- `.pc:align-self-end` - PC'de kendi ucunu hizalayın
- `.pc:align-self-start` - PC'de kendi kendine başlatmayı hizalama
- `.pc:align-self-stretch` - PC'de kendi kendini germeyi hizalayın

##### Align self - Tv (≥ 1200px)

- `.hover:tv:align-self-center` - Televizyonun üzerine gelindiğinde kendi merkezini hizala
- `.hover:tv:align-self-end` - TV'de fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:tv:align-self-start` - TV'de fareyle üzerine gelindiğinde otomatik başlatmayı hizalayın
- `.hover:tv:align-self-stretch` - TV'de fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.tv:align-self-center` - TV'de benlik merkezini hizalama
- `.tv:align-self-end` - Kendini TV'de hizala
- `.tv:align-self-start` - TV'de otomatik başlatmayı hizalama
- `.tv:align-self-stretch` - TV'de kendi kendini uzatmayı hizalayın

##### Align self - Tablet Max (≤ 768px)

- `.hover:tablet-max:align-self-center` - Tablet max üzerinde fareyle üzerine gelindiğinde kendi merkezini hizalayın
- `.hover:tablet-max:align-self-end` - Tablet max üzerinde fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:tablet-max:align-self-start` - Tablet max üzerinde fareyle üzerine gelindiğinde otomatik başlatmayı hizalayın
- `.hover:tablet-max:align-self-stretch` - Tablet max üzerinde fareyle üzerine gelindiğinde kendini uzatmayı hizalayın
- `.tablet-max:align-self-center` - Tablet max'ta kendi merkezini hizala
- `.tablet-max:align-self-end` - Tablet max'ta kendi ucunu hizalayın
- `.tablet-max:align-self-start` - Tablet max'te otomatik başlatmayı hizalama
- `.tablet-max:align-self-stretch` - Tablet max'ta kendi kendine esnemeyi hizalayın

##### Align self - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:align-self-center` - Tablet PC max üzerinde fareyle üzerine gelindiğinde kendi merkezini hizalayın
- `.hover:tablet-pc-max:align-self-end` - Tablet PC max üzerinde fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:tablet-pc-max:align-self-start` - Tablet PC max üzerinde fareyle üzerine gelindiğinde otomatik başlatmayı hizalama
- `.hover:tablet-pc-max:align-self-stretch` - Tablet PC max'ta fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.tablet-pc-max:align-self-center` - Tablet PC max'ta kendi merkezini hizalama
- `.tablet-pc-max:align-self-end` - Tablet PC max'ta kendi ucunu hizalayın
- `.tablet-pc-max:align-self-start` - Tablet PC max'ta otomatik başlatmayı hizalama
- `.tablet-pc-max:align-self-stretch` - Tablet PC Max'te kendi kendine gerdirmeyi hizalayın

##### Align self - Pc Max (≤ 1200px)

- `.hover:pc-max:align-self-center` - PC max üzerinde fareyle üzerine gelindiğinde kendi merkezini hizalayın
- `.hover:pc-max:align-self-end` - PC max üzerinde fareyle üzerine gelindiğinde kendi ucunu hizalayın
- `.hover:pc-max:align-self-start` - PC max üzerinde fareyle üzerine gelindiğinde kendi kendine başlamayı hizalayın
- `.hover:pc-max:align-self-stretch` - PC max üzerinde fareyle üzerine gelindiğinde kendi kendini uzatmayı hizalayın
- `.pc-max:align-self-center` - PC max'ta kendi merkezini hizala
- `.pc-max:align-self-end` - PC max'ta kendi ucunu hizalayın
- `.pc-max:align-self-start` - PC max'ta kendi kendine başlamayı hizalayın
- `.pc-max:align-self-stretch` - PC max'ta kendi kendine gerdirmeyi hizalayın

### Justify content

- `.hover:justify-content-around` - İçeriği fareyle üzerine gelindiğinde iki yana yaslayın
- `.hover:justify-content-between` - Fareyle üzerine gelindiğinde içeriği iki yana yasla
- `.hover:justify-content-center` - Fareyle üzerine gelindiğinde içerik merkezini iki yana yasla
- `.hover:justify-content-end` - Fareyle üzerine gelindiğinde içeriğin sonunu iki yana yasla
- `.hover:justify-content-evenly` - Fareyle üzerine gelindiğinde içeriği eşit şekilde iki yana yaslayın
- `.hover:justify-content-start` - İçeriğin fareyle üzerine gelindiğinde başlamasını iki yana yasla
- `.hover:justify-content-stretch` - Fareyle üzerine gelindiğinde içeriği uzatmayı haklı göster
- `.justify-content-around` - İçeriği gerekçelendirin
- `.justify-content-between` - İçeriği iki yana yasla
- `.justify-content-center` - İçerik merkezini gerekçelendir
- `.justify-content-end` - İçeriğin sonunu haklı göster
- `.justify-content-evenly` - İçeriği eşit şekilde gerekçelendirin
- `.justify-content-start` - İçerik başlangıcını haklı göster
- `.justify-content-stretch` - İçerik genişletmeyi gerekçelendir

##### Justify content - Mobile (≤ 480px)

- `.hover:mobile:justify-content-around` - Mobil cihazda fareyle üzerine gelindiğinde içeriği sağa sola yaslayın
- `.hover:mobile:justify-content-between` - Mobil cihazda fareyle üzerine gelindiğinde içeriği iki yana yaslayın
- `.hover:mobile:justify-content-center` - Mobil cihazda fareyle üzerine gelindiğinde içerik merkezini gerekçelendirin
- `.hover:mobile:justify-content-end` - Mobil cihazda fareyle üzerine gelindiğinde içeriğin bitişini haklı göster
- `.hover:mobile:justify-content-start` - Mobil cihazda fareyle üzerine gelindiğinde içeriğin başlamasını gerekçelendirin
- `.mobile:justify-content-around` - Mobil cihazlarda içeriği gerekçelendirin
- `.mobile:justify-content-between` - İçeriği mobil cihazlar arasında iki yana yasla
- `.mobile:justify-content-center` - Mobil cihazlarda içerik merkezini gerekçelendirin
- `.mobile:justify-content-end` - Mobil cihazlarda içeriğin sonunu haklı çıkarma
- `.mobile:justify-content-start` - İçeriğin mobilde başlatılmasını gerekçelendirin

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - İçeriği tablette fareyle üzerine gelindiğinde iki yana yaslayın
- `.hover:tablet:justify-content-between` - İçeriği tablet üzerinde fareyle üzerine gelindiğinde iki yana yaslama
- `.hover:tablet:justify-content-center` - Tablette fareyle üzerine gelindiğinde içerik merkezini iki yana yaslayın
- `.hover:tablet:justify-content-end` - Tablette fareyle üzerine gelindiğinde içeriğin sonunu iki yana yaslayın
- `.hover:tablet:justify-content-start` - İçerik başlangıcını tablette fareyle üzerine gelindiğinde iki yana yaslayın
- `.tablet:justify-content-around` - İçeriği tablette iki yana yaslama
- `.tablet:justify-content-between` - İçeriği tablette iki yana yasla
- `.tablet:justify-content-center` - Tabletteki içerik merkezini gerekçelendir
- `.tablet:justify-content-end` - Tablette içerik sonunu iki yana yasla
- `.tablet:justify-content-start` - İçerik başlangıcını tablette iki yana yasla

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - Tablet bilgisayarda fareyle üzerine gelindiğinde içeriği iki yana yaslayın
- `.hover:tablet-pc:justify-content-between` - Tablet bilgisayarda fareyle üzerine gelindiğinde içeriği iki yana yaslama
- `.hover:tablet-pc:justify-content-center` - Tablet bilgisayarda fareyle üzerine gelindiğinde içerik merkezini haklılaştırın
- `.hover:tablet-pc:justify-content-end` - Tablet PC'de fareyle üzerine gelindiğinde içeriğin sonunu iki yana yaslayın
- `.hover:tablet-pc:justify-content-start` - Tablet PC'de fareyle üzerine gelindiğinde içeriğin başlamasını iki yana yaslayın
- `.tablet-pc:justify-content-around` - İçeriği tablet bilgisayarda gerekçelendirin
- `.tablet-pc:justify-content-between` - İçeriği tablet PC'de iki yana yasla
- `.tablet-pc:justify-content-center` - Tablet PC'deki içerik merkezini gerekçelendirin
- `.tablet-pc:justify-content-end` - Tablet PC'de içeriğin sonunu haklı çıkarma
- `.tablet-pc:justify-content-start` - İçeriğin tablet bilgisayarda başlatılmasını haklı çıkarma

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - PC'de fareyle üzerine gelindiğinde içeriği iki yana yaslayın
- `.hover:pc:justify-content-between` - PC'de fareyle üzerine gelindiğinde içeriği iki yana yaslayın
- `.hover:pc:justify-content-center` - PC'de fareyle üzerine gelindiğinde içerik merkezini gerekçelendirin
- `.hover:pc:justify-content-end` - PC'de fareyle üzerine gelindiğinde içeriğin sonunu iki yana yaslayın
- `.hover:pc:justify-content-start` - İçeriğin PC'de fareyle üzerine gelindiğinde başlamasını gerekçelendirin
- `.pc:justify-content-around` - İçeriği PC'de gerekçelendirin
- `.pc:justify-content-between` - İçeriği PC'de iki yana yasla
- `.pc:justify-content-center` - PC'de içerik merkezini haklı göster
- `.pc:justify-content-end` - PC'de içeriğin sonunu haklı çıkarma
- `.pc:justify-content-start` - İçeriğin bilgisayarda başlatılmasını gerekçelendirin

##### Justify content - Tv (≥ 1200px)

- `.hover:tv:justify-content-around` - Televizyonun üzerine gelindiğinde içeriği gerekçelendirin
- `.hover:tv:justify-content-between` - Televizyonun üzerine gelindiğinde içeriği iki yana yaslayın
- `.hover:tv:justify-content-center` - Televizyonun üzerine gelindiğinde içerik merkezini haklılaştırın
- `.hover:tv:justify-content-end` - Televizyonun üzerine gelindiğinde içeriğin sonunu haklı çıkarın
- `.hover:tv:justify-content-start` - İçeriğin TV'de fareyle üzerine gelindiğinde başlamasını gerekçelendirin
- `.tv:justify-content-around` - Televizyondaki içeriği gerekçelendirin
- `.tv:justify-content-between` - Televizyondaki içeriği iki yana yasla
- `.tv:justify-content-center` - Televizyondaki içerik merkezini gerekçelendir
- `.tv:justify-content-end` - TV'de içeriğin bitmesini haklı göster
- `.tv:justify-content-start` - İçeriğin TV'de başlatılmasını gerekçelendirin

##### Justify content - Tablet Max (≤ 768px)

- `.hover:tablet-max:justify-content-around` - İçeriği tablet max üzerinde fareyle üzerine gelindiğinde iki yana yaslayın
- `.hover:tablet-max:justify-content-between` - İçeriği tablet max üzerinde fareyle üzerine gelindiğinde iki yana yaslayın
- `.hover:tablet-max:justify-content-center` - Tablet max üzerinde fareyle üzerine gelindiğinde içerik merkezini gerekçelendirin
- `.hover:tablet-max:justify-content-end` - Tablet max üzerinde fareyle üzerine gelindiğinde içeriğin bitişini haklı göster
- `.hover:tablet-max:justify-content-start` - İçerik başlangıcını tablet max üzerinde fareyle üzerine gelindiğinde gerekçelendirin
- `.tablet-max:justify-content-around` - İçeriği tablet max'ta gerekçelendirin
- `.tablet-max:justify-content-between` - İçeriği tablet max arasında iki yana yasla
- `.tablet-max:justify-content-center` - İçerik merkezini tablet max'ta gerekçelendirin
- `.tablet-max:justify-content-end` - İçeriğin tablet max'ta sona ermesini gerekçelendir
- `.tablet-max:justify-content-start` - İçeriğin tablet max'ta başlatılmasını gerekçelendirin

##### Justify content - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:justify-content-around` - Tablet PC Max'te fareyle üzerine gelindiğinde içeriği iki yana yaslayın
- `.hover:tablet-pc-max:justify-content-between` - İçeriği tablet PC max üzerinde fareyle üzerine gelindiğinde iki yana yaslayın
- `.hover:tablet-pc-max:justify-content-center` - Tablet PC max üzerinde fareyle üzerine gelindiğinde içerik merkezini gerekçelendirin
- `.hover:tablet-pc-max:justify-content-end` - Tablet PC max üzerinde fareyle üzerine gelindiğinde içeriğin sonunu haklı çıkarın
- `.hover:tablet-pc-max:justify-content-start` - Tablet PC max'ta fareyle üzerine gelindiğinde içeriğin başlatılmasını gerekçelendirin
- `.tablet-pc-max:justify-content-around` - İçeriği tablet pc max'ta gerekçelendirin
- `.tablet-pc-max:justify-content-between` - İçeriği tablet pc max arasında iki yana yasla
- `.tablet-pc-max:justify-content-center` - Tablet PC Max'te içerik merkezini gerekçelendirin
- `.tablet-pc-max:justify-content-end` - Tablet PC Max'te içeriğin sonunu haklı çıkarma
- `.tablet-pc-max:justify-content-start` - İçeriğin tablet pc max'ta başlatılmasını gerekçelendirin

##### Justify content - Pc Max (≤ 1200px)

- `.hover:pc-max:justify-content-around` - PC max'ta fareyle üzerine gelindiğinde içeriği gerekçelendirin
- `.hover:pc-max:justify-content-between` - İçeriği PC max üzerinde fareyle üzerine gelindiğinde iki yana yaslayın
- `.hover:pc-max:justify-content-center` - PC max üzerinde fareyle üzerine gelindiğinde içerik merkezini gerekçelendirin
- `.hover:pc-max:justify-content-end` - PC max'ta fareyle üzerine gelindiğinde içeriğin sonunu haklı çıkarın
- `.hover:pc-max:justify-content-start` - PC max'ta fareyle üzerine gelindiğinde içeriğin başlamasını gerekçelendirin
- `.pc-max:justify-content-around` - İçeriği pc max'ta gerekçelendirin
- `.pc-max:justify-content-between` - İçeriği PC max arasında iki yana yasla
- `.pc-max:justify-content-center` - PC max'ta içerik merkezini haklı göster
- `.pc-max:justify-content-end` - PC max'ta içeriğin sonunu haklı göster
- `.pc-max:justify-content-start` - İçeriğin PC max'ta başlatılmasını gerekçelendirin

### Justify items

- `.hover:justify-items-center` - Fareyle üzerine gelindiğinde öğeleri ortalayın
- `.hover:justify-items-end` - Öğelerin fareyle üzerine gelindiğinde bitmesini iki yana yasla
- `.hover:justify-items-start` - Öğelerin fareyle üzerine gelindiğinde başlamasını iki yana yasla
- `.hover:justify-items-stretch` - Fareyle üzerine gelindiğinde öğelerin uzamasını iki yana yasla
- `.justify-items-center` - Öğe merkezini iki yana yasla
- `.justify-items-end` - Öğelerin bitişini iki yana yasla
- `.justify-items-start` - Öğelerin başlangıcını iki yana yasla
- `.justify-items-stretch` - Öğeleri uzatmayı haklı göster

### Order

- `.hover:order-5` - Fareyle üzerine gelindiğinde 5'i sipariş edin
- `.hover:order-4` - Fareyle üzerine gelindiğinde 4. sipariş verin
- `.hover:order-3` - Fareyle üzerine gelindiğinde 3. sipariş verin
- `.hover:order-2` - Fareyle üzerine gelindiğinde 2. sipariş verin
- `.hover:order-1` - Fareyle üzerine gelindiğinde 1. sipariş verin
- `.hover:order-0` - Fareyle üzerine gelindiğinde 0 sırala
- `.hover:order-first` - Fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:order-last` - Fareyle üzerine gelindiğinde en son sipariş verin
- `.order-5` - Sipariş 5
- `.order-4` - Sipariş 4
- `.order-3` - Sipariş 3
- `.order-2` - Sipariş 2
- `.order-1` - Sipariş 1
- `.order-0` - Sipariş 0
- `.order-first` - Önce sipariş verin
- `.order-last` - Son sipariş

##### Negative Order

- `.-order-5` - Negatif Sıra 5
- `.-order-4` - Negatif Sıra 4
- `.-order-3` - Negatif Sıra 3
- `.-order-2` - Negatif Sıra 2
- `.-order-1` - Negatif Sıra 1
- `.hover:-order-5` - Fareyle üzerine gelindiğinde Negatif Sıra 5
- `.hover:-order-4` - Fareyle üzerine gelindiğinde Negatif Sıra 4
- `.hover:-order-3` - Fareyle üzerine gelindiğinde Negatif Sıra 3
- `.hover:-order-2` - Fareyle üzerine gelindiğinde Negatif Sıra 2
- `.hover:-order-1` - Fareyle üzerine gelindiğinde Negatif Sıra 1

##### Order - Mobile (≤ 480px)

- `.hover:mobile:order-5` - Mobil cihazda fareyle üzerine gelindiğinde 5 sipariş verin
- `.hover:mobile:order-4` - Mobil cihazda fareyle üzerine gelindiğinde 4'ü sipariş edin
- `.hover:mobile:order-3` - Mobil cihazda fareyle üzerine gelindiğinde 3. sipariş verin
- `.hover:mobile:order-2` - Mobil cihazda fareyle üzerine gelindiğinde 2. sipariş verin
- `.hover:mobile:order-1` - Mobil cihazda fareyle üzerine gelindiğinde 1. Sipariş verin
- `.hover:mobile:order-0` - Mobil cihazda fareyle üzerine gelindiğinde 0 sipariş edin
- `.hover:mobile:order-first` - Mobil cihazda fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:mobile:order-last` - Mobil cihazda fareyle üzerine gelindiğinde son siparişi verin
- `.mobile:order-5` - Mobil cihazdan 5 sipariş verin
- `.mobile:order-4` - Mobil cihazdan 4 sipariş verin
- `.mobile:order-3` - Mobil cihazdan 3 sipariş verin
- `.mobile:order-2` - Mobil cihazdan 2 sipariş verin
- `.mobile:order-1` - Mobil cihazdan 1 sipariş verin
- `.mobile:order-0` - Mobil cihazda 0 sipariş edin
- `.mobile:order-first` - Mobilde ilk önce sipariş verin
- `.mobile:order-last` - Mobil cihazda son sipariş

##### Negative Order - Mobile (≤ 480px)

- `.hover:mobile:-order-5` - Mobil cihazda fareyle üzerine gelindiğinde Negatif Sıra 5
- `.hover:mobile:-order-4` - Mobil cihazda fareyle üzerine gelindiğinde Negatif Sıra 4
- `.hover:mobile:-order-3` - Mobil cihazda fareyle üzerine gelindiğinde Negatif Sıra 3
- `.hover:mobile:-order-2` - Mobil cihazda fareyle üzerine gelindiğinde Negatif Sıra 2
- `.hover:mobile:-order-1` - Mobil cihazda fareyle üzerine gelindiğinde Negatif Sıra 1
- `.mobile:-order-5` - Mobil cihazda Negatif Sıra 5
- `.mobile:-order-4` - Mobil cihazda Negatif Sıra 4
- `.mobile:-order-3` - Mobil cihazda Negatif Sıra 3
- `.mobile:-order-2` - Mobil cihazda Negatif Sipariş 2
- `.mobile:-order-1` - Mobil cihazda Negatif Sıra 1

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - Tabletin üzerine gelindiğinde 5'i sipariş edin
- `.hover:tablet:order-4` - Tabletin üzerine gelindiğinde 4'ü sipariş edin
- `.hover:tablet:order-3` - Tabletin üzerine gelindiğinde 3. sipariş verin
- `.hover:tablet:order-2` - Tabletin üzerine gelindiğinde 2. sipariş verin
- `.hover:tablet:order-1` - Tabletin üzerine gelindiğinde 1. sipariş verin
- `.hover:tablet:order-0` - Tabletin üzerine gelindiğinde 0 sipariş edin
- `.hover:tablet:order-first` - Tabletin üzerine gelindiğinde ilk önce sipariş verin
- `.hover:tablet:order-last` - Tablette fareyle üzerine gelindiğinde son siparişi verin
- `.tablet:order-5` - Tablette 5 sipariş edin
- `.tablet:order-4` - Tablette 4 sipariş edin
- `.tablet:order-3` - Tablette 3 sipariş edin
- `.tablet:order-2` - Tablette 2 sipariş edin
- `.tablet:order-1` - Tablette 1 sipariş verin
- `.tablet:order-0` - Tablette 0 sipariş edin
- `.tablet:order-first` - İlk önce tablette sipariş verin
- `.tablet:order-last` - Tablette son sipariş

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - Tabletin üzerine gelindiğinde Negatif Sıra 5
- `.hover:tablet:-order-4` - Tabletin üzerine gelindiğinde Negatif Sıra 4
- `.hover:tablet:-order-3` - Tabletin üzerine gelindiğinde Negatif Sıra 3
- `.hover:tablet:-order-2` - Tabletin üzerine gelindiğinde Negatif Sıra 2
- `.hover:tablet:-order-1` - Tabletin üzerine gelindiğinde Negatif Sıra 1
- `.tablet:-order-5` - Tablette Negatif Sıra 5
- `.tablet:-order-4` - Tablette Negatif Sıra 4
- `.tablet:-order-3` - Tablette Negatif Sıra 3
- `.tablet:-order-2` - Tablette Negatif Sıra 2
- `.tablet:-order-1` - Tablette Negatif Sıra 1

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - Tablet bilgisayarda fareyle üzerine gelindiğinde 5'i sipariş edin
- `.hover:tablet-pc:order-4` - Tablet bilgisayarda fareyle üzerine gelindiğinde 4'ü sipariş edin
- `.hover:tablet-pc:order-3` - Tablet bilgisayarda fareyle üzerine gelindiğinde 3. Siparişi verin
- `.hover:tablet-pc:order-2` - Tablet bilgisayarda fareyle üzerine gelindiğinde 2. Siparişi verin
- `.hover:tablet-pc:order-1` - Tablet bilgisayarda fareyle üzerine gelindiğinde 1. Siparişi verin
- `.hover:tablet-pc:order-0` - Tablet bilgisayarda fareyle üzerine gelindiğinde 0 sipariş edin
- `.hover:tablet-pc:order-first` - Tablet bilgisayarda fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:tablet-pc:order-last` - Tablet bilgisayarda fareyle üzerine gelindiğinde son sipariş verin
- `.tablet-pc:order-5` - Tablet PC'de 5 sipariş edin
- `.tablet-pc:order-4` - Tablet PC'de 4 sipariş edin
- `.tablet-pc:order-3` - Tablet PC'de 3 sipariş edin
- `.tablet-pc:order-2` - Tablet PC'de 2 sipariş edin
- `.tablet-pc:order-1` - Tablet PC'de 1 Sipariş Ver
- `.tablet-pc:order-0` - Tablet PC'de 0 sipariş edin
- `.tablet-pc:order-first` - Tablet PC'de ilk önce sipariş verin
- `.tablet-pc:order-last` - Tablet PC'de son sipariş

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - Tablet bilgisayarda fareyle üzerine gelindiğinde Negatif Sıra 5
- `.hover:tablet-pc:-order-4` - Tablet bilgisayarda fareyle üzerine gelindiğinde Negatif Sıra 4
- `.hover:tablet-pc:-order-3` - Tablet bilgisayarda fareyle üzerine gelindiğinde Negatif Sıra 3
- `.hover:tablet-pc:-order-2` - Tablet bilgisayarda fareyle üzerine gelindiğinde Negatif Sıra 2
- `.hover:tablet-pc:-order-1` - Tablet bilgisayarda fareyle üzerine gelindiğinde Negatif Sıra 1
- `.tablet-pc:-order-5` - Tablet PC'de Negatif Sıra 5
- `.tablet-pc:-order-4` - Tablet PC'de Negatif Sıra 4
- `.tablet-pc:-order-3` - Tablet PC'de Negatif Sıra 3
- `.tablet-pc:-order-2` - Tablet PC'de Negatif Sıra 2
- `.tablet-pc:-order-1` - Tablet PC'de Negatif Sıra 1

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - PC'de fareyle üzerine gelindiğinde 5 sipariş edin
- `.hover:pc:order-4` - PC'de fareyle üzerine gelindiğinde 4'ü sipariş edin
- `.hover:pc:order-3` - PC'de fareyle üzerine gelindiğinde 3. sipariş verin
- `.hover:pc:order-2` - PC'de fareyle üzerine gelindiğinde 2. Siparişi verin
- `.hover:pc:order-1` - PC'de fareyle üzerine gelindiğinde 1. Siparişi verin
- `.hover:pc:order-0` - PC'de fareyle üzerine gelindiğinde 0 sipariş edin
- `.hover:pc:order-first` - PC'de fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:pc:order-last` - PC'de fareyle üzerine gelindiğinde son sipariş verin
- `.pc:order-5` - PC'de 5 sipariş edin
- `.pc:order-4` - PC'de 4 sipariş edin
- `.pc:order-3` - PC'de 3 sipariş edin
- `.pc:order-2` - PC'de 2 sipariş ver
- `.pc:order-1` - PC'de 1 sipariş verin
- `.pc:order-0` - PC'de 0 sipariş edin
- `.pc:order-first` - İlk önce PC'de sipariş verin
- `.pc:order-last` - PC'de son sipariş

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - PC'de fareyle üzerine gelindiğinde Negatif Sıra 5
- `.hover:pc:-order-4` - PC'de fareyle üzerine gelindiğinde Negatif Sıra 4
- `.hover:pc:-order-3` - PC'de fareyle üzerine gelindiğinde Negatif Sıra 3
- `.hover:pc:-order-2` - PC'de fareyle üzerine gelindiğinde Negatif Sıra 2
- `.hover:pc:-order-1` - PC'de fareyle üzerine gelindiğinde Negatif Sıra 1
- `.pc:-order-5` - PC'de Negatif Sipariş 5
- `.pc:-order-4` - PC'de Negatif Sipariş 4
- `.pc:-order-3` - PC'de Negatif Sipariş 3
- `.pc:-order-2` - PC'de Negatif Sipariş 2
- `.pc:-order-1` - PC'de Negatif Sipariş 1

##### Order - Tv (≥ 1200px)

- `.hover:tv:order-5` - Televizyonda fareyle üzerine gelindiğinde 5'i sipariş edin
- `.hover:tv:order-4` - TV'de fareyle üzerine gelindiğinde 4'ü sipariş edin
- `.hover:tv:order-3` - Televizyonda fareyle üzerine gelindiğinde 3. Siparişi verin
- `.hover:tv:order-2` - Televizyonda fareyle üzerine gelindiğinde 2. Siparişi verin
- `.hover:tv:order-1` - Televizyonda fareyle üzerine gelindiğinde 1. Siparişi verin
- `.hover:tv:order-0` - Televizyonun üzerine gelindiğinde 0 sipariş edin
- `.hover:tv:order-first` - TV'de fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:tv:order-last` - Televizyonda fareyle üzerine gelindiğinde son sipariş verin
- `.tv:order-5` - TV'de 5 sipariş ver
- `.tv:order-4` - TV'de 4 sipariş ver
- `.tv:order-3` - TV'de 3 sipariş ver
- `.tv:order-2` - TV'de 2 sipariş ver
- `.tv:order-1` - TV'de 1 sipariş ver
- `.tv:order-0` - TV'de 0 sipariş et
- `.tv:order-first` - TV'de ilk önce sipariş verin
- `.tv:order-last` - TV'de son sipariş

##### Negative Order - Tv (≥ 1200px)

- `.hover:tv:-order-5` - Televizyonun üzerine gelindiğinde Negatif Sıra 5
- `.hover:tv:-order-4` - Negatif Sıralama 4 televizyonun üzerine gelindiğinde
- `.hover:tv:-order-3` - Televizyonun üzerine gelindiğinde Negatif Sıra 3
- `.hover:tv:-order-2` - Televizyonun üzerine gelindiğinde Negatif Sıra 2
- `.hover:tv:-order-1` - Televizyonun üzerine gelindiğinde Negatif Sıra 1
- `.tv:-order-5` - TV'de Negatif Sıralama 5
- `.tv:-order-4` - Negatif Sıralama 4 televizyonda
- `.tv:-order-3` - TV'de Negatif Sıralama 3
- `.tv:-order-2` - Negatif Sipariş 2 televizyonda
- `.tv:-order-1` - TV'de Negatif Sıra 1

##### Order - Tablet Max (≤ 768px)

- `.hover:tablet-max:order-5` - Maksimum tablette fareyle üzerine gelindiğinde 5 sipariş verin
- `.hover:tablet-max:order-4` - Maksimum tablette fareyle üzerine gelindiğinde 4 sipariş verin
- `.hover:tablet-max:order-3` - Tablet max üzerinde fareyle üzerine gelindiğinde 3 sipariş verin
- `.hover:tablet-max:order-2` - Tablet max üzerinde fareyle üzerine gelindiğinde 2 sipariş verin
- `.hover:tablet-max:order-1` - Maksimum tabletin üzerine gelindiğinde 1 sipariş verin
- `.hover:tablet-max:order-0` - Maksimum tablette fareyle üzerine gelindiğinde 0 sipariş edin
- `.hover:tablet-max:order-first` - Tablet max üzerinde fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:tablet-max:order-last` - Tablet max üzerinde fareyle üzerine gelindiğinde en son sipariş verin
- `.tablet-max:order-5` - Maksimum tablette 5 sipariş verin
- `.tablet-max:order-4` - Maksimum tablette 4 sipariş verin
- `.tablet-max:order-3` - Tablet max'ta 3 sipariş verin
- `.tablet-max:order-2` - Tablet max'ta 2 sipariş verin
- `.tablet-max:order-1` - Maksimum tablette 1 sipariş verin
- `.tablet-max:order-0` - Tablet max'ta 0 sipariş edin
- `.tablet-max:order-first` - Tablet max'ta ilk önce sipariş verin
- `.tablet-max:order-last` - Tablet max'ta son sipariş

##### Negative Order - Tablet Max (≤ 768px)

- `.hover:tablet-max:-order-5` - Maksimum tabletin üzerine gelindiğinde Negatif Sıra 5
- `.hover:tablet-max:-order-4` - Maksimum tabletin üzerine gelindiğinde Negatif Sıra 4
- `.hover:tablet-max:-order-3` - Maksimum tabletin üzerine gelindiğinde Negatif Sıra 3
- `.hover:tablet-max:-order-2` - Maksimum tabletin üzerine gelindiğinde Negatif Sıra 2
- `.hover:tablet-max:-order-1` - Maksimum tabletin üzerine gelindiğinde Negatif Sıra 1
- `.tablet-max:-order-5` - Tablet max'ta Negatif Sıra 5
- `.tablet-max:-order-4` - Tablet max'ta Negatif Sıra 4
- `.tablet-max:-order-3` - Tablet max'ta Negatif Sıra 3
- `.tablet-max:-order-2` - Tablet max'ta Negatif Sipariş 2
- `.tablet-max:-order-1` - Maksimum tablette Negatif Sıra 1

##### Order - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:order-5` - Tablet PC max üzerinde fareyle üzerine gelindiğinde 5 sipariş verin
- `.hover:tablet-pc-max:order-4` - Tablet PC max üzerinde fareyle üzerine gelindiğinde 4 sipariş verin
- `.hover:tablet-pc-max:order-3` - Tablet PC max üzerinde fareyle üzerine gelindiğinde 3 sipariş verin
- `.hover:tablet-pc-max:order-2` - Tablet PC max üzerinde fareyle üzerine gelindiğinde 2 sipariş verin
- `.hover:tablet-pc-max:order-1` - Tablet PC max üzerinde fareyle üzerine gelindiğinde 1 sipariş verin
- `.hover:tablet-pc-max:order-0` - Maksimum tablet PC'de fareyle üzerine gelindiğinde 0 sipariş edin
- `.hover:tablet-pc-max:order-first` - Tablet PC max'ta fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:tablet-pc-max:order-last` - Tablet PC max'ta fareyle üzerine gelindiğinde son sipariş verin
- `.tablet-pc-max:order-5` - Tablet PC'de maksimum 5 sipariş verin
- `.tablet-pc-max:order-4` - Tablet PC'de max 4 adet sipariş verin
- `.tablet-pc-max:order-3` - Tablet pc max'ta 3 sipariş verin
- `.tablet-pc-max:order-2` - Tablet PC max için 2 adet sipariş verin
- `.tablet-pc-max:order-1` - Tablet PC'de maksimum 1 sipariş verin
- `.tablet-pc-max:order-0` - Tablet PC'de max sipariş 0
- `.tablet-pc-max:order-first` - Tablet PC Max'te ilk önce sipariş verin
- `.tablet-pc-max:order-last` - Tablet PC max'ta son sipariş

##### Negative Order - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:-order-5` - Tablet PC max'ın üzerine gelindiğinde Negatif Sıra 5
- `.hover:tablet-pc-max:-order-4` - Tablet PC max'ın üzerine gelindiğinde Negatif Sıra 4
- `.hover:tablet-pc-max:-order-3` - Tablet PC max'ın üzerine gelindiğinde Negatif Sıra 3
- `.hover:tablet-pc-max:-order-2` - Tablet PC'de fareyle üzerine gelindiğinde Negatif Sıra 2
- `.hover:tablet-pc-max:-order-1` - Tablet PC max'ın üzerine gelindiğinde Negatif Sıra 1
- `.tablet-pc-max:-order-5` - Tablet PC max'ta Negatif Sıra 5
- `.tablet-pc-max:-order-4` - Tablet PC max'ta Negatif Sıra 4
- `.tablet-pc-max:-order-3` - Tablet PC max'ta Negatif Sıra 3
- `.tablet-pc-max:-order-2` - Tablet PC max'ta Negatif Sıra 2
- `.tablet-pc-max:-order-1` - Tablet PC max'ta Negatif Sıra 1

##### Order - Pc Max (≤ 1200px)

- `.hover:pc-max:order-5` - PC max üzerinde fareyle üzerine gelindiğinde 5 sipariş verin
- `.hover:pc-max:order-4` - PC max üzerinde fareyle üzerine gelindiğinde 4 sipariş verin
- `.hover:pc-max:order-3` - PC max üzerinde fareyle üzerine gelindiğinde 3 sipariş verin
- `.hover:pc-max:order-2` - PC max üzerinde fareyle üzerine gelindiğinde 2 sipariş verin
- `.hover:pc-max:order-1` - PC max üzerinde fareyle üzerine gelindiğinde 1 sipariş verin
- `.hover:pc-max:order-0` - PC max üzerinde fareyle üzerine gelindiğinde 0 sipariş edin
- `.hover:pc-max:order-first` - PC max'ta fareyle üzerine gelindiğinde ilk önce sipariş verin
- `.hover:pc-max:order-last` - PC max'ta fareyle üzerine gelindiğinde son sipariş verin
- `.pc-max:order-5` - PC'de maksimum 5 sipariş verin
- `.pc-max:order-4` - Maksimum PC'de 4 sipariş verin
- `.pc-max:order-3` - Maksimum PC'de 3 sipariş verin
- `.pc-max:order-2` - PC'de maksimum 2 adet sipariş verin
- `.pc-max:order-1` - PC'de maksimum 1 sipariş verin
- `.pc-max:order-0` - PC'de maksimum sipariş 0
- `.pc-max:order-first` - PC max'ta ilk önce sipariş verin
- `.pc-max:order-last` - PC max'ta son sipariş

##### Negative Order - Pc Max (≤ 1200px)

- `.hover:pc-max:-order-5` - PC max üzerinde fareyle üzerine gelindiğinde Negatif Sıra 5
- `.hover:pc-max:-order-4` - PC max üzerinde fareyle üzerine gelindiğinde Negatif Sıra 4
- `.hover:pc-max:-order-3` - PC max üzerinde fareyle üzerine gelindiğinde Negatif Sıra 3
- `.hover:pc-max:-order-2` - PC max üzerinde fareyle üzerine gelindiğinde Negatif Sıra 2
- `.hover:pc-max:-order-1` - PC max üzerinde fareyle üzerine gelindiğinde Negatif Sıra 1
- `.pc-max:-order-5` - PC'de maksimum Negatif Sipariş 5
- `.pc-max:-order-4` - PC'de maksimum Negatif Sipariş 4
- `.pc-max:-order-3` - PC max'ta Negatif Sipariş 3
- `.pc-max:-order-2` - PC'de maksimum Negatif Sipariş 2
- `.pc-max:-order-1` - PC'de maksimum Negatif Sipariş 1

## Spacing

### Margin

#### Margin All

- `.first:m-0` - Marj Tümü ilk başta 0rem
- `.hover:m-5` - Tüm Marj Fareyle üzerine gelindiğinde 5rem
- `.hover:m-4.5` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-4` - Marj Tümü 4rem fareyle üzerine gelindiğinde
- `.hover:m-3.5` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-3` - Fareyle üzerine gelindiğinde Tüm Marj 3rem
- `.hover:m-2.5` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-2` - Fareyle üzerine gelindiğinde Tüm Marj 2rem
- `.hover:m-1.9` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.8` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.7` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.6` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.5` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.4` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.3` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.2` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1.1` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-1` - Fareyle üzerine gelindiğinde Tüm Marj 1rem
- `.hover:m-0.9` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.8` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.7` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.6` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.5` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.4` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.3` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-0.2` - Fareyle üzerine gelindiğinde Tüm Marj 0,2rem
- `.hover:m-0.1` - Tüm Marj Fareyle üzerine gelindiğinde 0,1 rem
- `.hover:m-0` - Kenar Boşluğu Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:m-auto` - Kenar Boşluğu Fareyle üzerine gelindiğinde tümü otomatik
- `.last:m-0` - Marj Tümü 0rem sonda
- `.m-5` - Tümü Marj 5rem
- `.m-4.5` - Tüm Marj 0rem
- `.m-4` - Marjın Tamamı 4rem
- `.m-3.5` - Tüm Marj 0rem
- `.m-3` - Tümü Marj 3rem
- `.m-2.5` - Tüm Marj 0rem
- `.m-2` - Tüm Marj 2rem
- `.m-1.9` - Tüm Marj 0rem
- `.m-1.8` - Tüm Marj 0rem
- `.m-1.7` - Tüm Marj 0rem
- `.m-1.6` - Tüm Marj 0rem
- `.m-1.5` - Tüm Marj 0rem
- `.m-1.4` - Tüm Marj 0rem
- `.m-1.3` - Tüm Marj 0rem
- `.m-1.2` - Tüm Marj 0rem
- `.m-1.1` - Tüm Marj 0rem
- `.m-1` - Tüm Marj 1rem
- `.m-0.9` - Tüm Marj 0rem
- `.m-0.8` - Tüm Marj 0rem
- `.m-0.7` - Tüm Marj 0rem
- `.m-0.6` - Tüm Marj 0rem
- `.m-0.5` - Tüm Marj 0rem
- `.m-0.4` - Tüm Marj 0rem
- `.m-0.3` - Tüm Marj 0rem
- `.m-0.2` - Tüm Marj 0,2rem
- `.m-0.1` - Tüm Marj 0,1rem
- `.m-0` - Tüm Marj 0rem
- `.m-auto` - Marj Tümü otomatik

#### Margin Bottom

- `.first:mb-0` - Marj Alt 0rem ilk başta
- `.hover:mb-100` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt %100
- `.hover:mb-75` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt %75
- `.hover:mb-50` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt %50
- `.hover:mb-25` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt %25
- `.hover:mb-5` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 5rem
- `.hover:mb-4.5` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-4` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 4rem
- `.hover:mb-3.5` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-3` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 3rem
- `.hover:mb-2.5` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-2` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 2rem
- `.hover:mb-1.9` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.8` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.7` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.6` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.5` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.4` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.3` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.2` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1.1` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-1` - Fareyle üzerine gelindiğinde Alt Marj 1rem
- `.hover:mb-0.9` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.8` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.7` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.6` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.5` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.4` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.3` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-0.2` - Fareyle üzerine gelindiğinde Alt Marj 0,2rem
- `.hover:mb-0.1` - Fareyle üzerine gelindiğinde Alt Marj 0,1 rem
- `.hover:mb-0` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt 0rem
- `.hover:mb-auto` - Fareyle üzerine gelindiğinde Kenar Boşluğu Alt otomatik
- `.last:mb-0` - Marj Alt 0rem sonda
- `.mb-100` - Kenar Boşluğu Alt %100
- `.mb-75` - Alt Marj %75
- `.mb-50` - Kenar Boşluğu Alt %50
- `.mb-25` - Kenar Boşluğu Alt %25
- `.mb-5` - Kenar Boşluğu Alt 5rem
- `.mb-4.5` - Marj Alt 0rem
- `.mb-4` - Kenar Boşluğu Alt 4rem
- `.mb-3.5` - Marj Alt 0rem
- `.mb-3` - Alt Marj 3rem
- `.mb-2.5` - Marj Alt 0rem
- `.mb-2` - Alt Marj 2rem
- `.mb-1.9` - Marj Alt 0rem
- `.mb-1.8` - Marj Alt 0rem
- `.mb-1.7` - Marj Alt 0rem
- `.mb-1.6` - Marj Alt 0rem
- `.mb-1.5` - Marj Alt 0rem
- `.mb-1.4` - Marj Alt 0rem
- `.mb-1.3` - Marj Alt 0rem
- `.mb-1.2` - Marj Alt 0rem
- `.mb-1.1` - Marj Alt 0rem
- `.mb-1` - Kenar Boşluğu Alt 1rem
- `.mb-0.9` - Marj Alt 0rem
- `.mb-0.8` - Marj Alt 0rem
- `.mb-0.7` - Marj Alt 0rem
- `.mb-0.6` - Marj Alt 0rem
- `.mb-0.5` - Marj Alt 0rem
- `.mb-0.4` - Marj Alt 0rem
- `.mb-0.3` - Marj Alt 0rem
- `.mb-0.2` - Alt Marj 0,2rem
- `.mb-0.1` - Alt Marj 0,1rem
- `.mb-0` - Marj Alt 0rem
- `.mb-auto` - Kenar Boşluğu Alt otomatik

#### Margin End

- `.hover:me-2` - Fareyle üzerine gelindiğinde Marj Sonu 2rem
- `.hover:me-1.5` - Fareyle üzerine gelindiğinde Marj Sonu 1,5 rem
- `.hover:me-1` - Fareyle üzerine gelindiğinde Marj Sonu 1rem
- `.hover:me-0.5` - Fareyle üzerine gelindiğinde Marj Sonu 0,5rem
- `.hover:me-0` - Fareyle üzerine gelindiğinde Marj Sonu 0rem
- `.me-2` - Marj Sonu 2rem
- `.me-1.5` - Marj Sonu 1,5rem
- `.me-1` - Marj Sonu 1rem
- `.me-0.5` - Marj Sonu 0,5 rem
- `.me-0` - Marj Sonu 0rem

#### Margin Left

- `.first:ml-0` - Marj İlk başta 0rem kaldı
- `.hover:ml-100` - Fareyle üzerine gelindiğinde Sol Marj %100
- `.hover:ml-75` - Fareyle üzerine gelindiğinde Sol Marj %75
- `.hover:ml-50` - Fareyle üzerine gelindiğinde Sol Marj %50
- `.hover:ml-25` - Fareyle üzerine gelindiğinde Sol Marj %25
- `.hover:ml-5` - Fareyle üzerine gelindiğinde Sol Marj 5rem
- `.hover:ml-4.5` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-4` - Fareyle üzerine gelindiğinde Sol Marj 4rem
- `.hover:ml-3.5` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-3` - Fareyle üzerine gelindiğinde Sol Marj 3rem
- `.hover:ml-2.5` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-2` - Fareyle üzerine gelindiğinde Sol Kenar Boşluğu 2rem
- `.hover:ml-1.9` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.8` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.7` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.6` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.5` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.4` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.3` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.2` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1.1` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-1` - Fareyle üzerine gelindiğinde Sol Marj 1rem
- `.hover:ml-0.9` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.8` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.7` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.6` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.5` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.4` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.3` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-0.2` - Vurguluyken Sol Marj 0,2rem
- `.hover:ml-0.1` - Fareyle üzerine gelindiğinde Sol Marj 0,1 rem
- `.hover:ml-0` - Fareyle üzerine gelindiğinde Sol Marj 0rem
- `.hover:ml-auto` - Fareyle üzerine gelindiğinde Kenar Boşluğu Sol otomatik
- `.last:ml-0` - Sonda Kalan Marj 0rem
- `.ml-100` - Sol Marj %100
- `.ml-75` - Sol Marj %75
- `.ml-50` - Sol Marj %50
- `.ml-25` - Sol Marj %25
- `.ml-5` - Sol Kenar Boşluğu 5rem
- `.ml-4.5` - Sol Marj 0rem
- `.ml-4` - Sol Marj 4rem
- `.ml-3.5` - Sol Marj 0rem
- `.ml-3` - Sol Marj 3rem
- `.ml-2.5` - Sol Marj 0rem
- `.ml-2` - Sol Marj 2rem
- `.ml-1.9` - Sol Marj 0rem
- `.ml-1.8` - Sol Marj 0rem
- `.ml-1.7` - Sol Marj 0rem
- `.ml-1.6` - Sol Marj 0rem
- `.ml-1.5` - Sol Marj 0rem
- `.ml-1.4` - Sol Marj 0rem
- `.ml-1.3` - Sol Marj 0rem
- `.ml-1.2` - Sol Marj 0rem
- `.ml-1.1` - Sol Marj 0rem
- `.ml-1` - Sol Marj 1rem
- `.ml-0.9` - Sol Marj 0rem
- `.ml-0.8` - Sol Marj 0rem
- `.ml-0.7` - Sol Marj 0rem
- `.ml-0.6` - Sol Marj 0rem
- `.ml-0.5` - Sol Marj 0rem
- `.ml-0.4` - Sol Marj 0rem
- `.ml-0.3` - Sol Marj 0rem
- `.ml-0.2` - Sol Marj 0,2rem
- `.ml-0.1` - Sol Marj 0,1rem
- `.ml-0` - Sol Marj 0rem
- `.ml-auto` - Kenar Boşluğu Sol otomatik

#### Margin Right

- `.first:mr-0` - Marj Sağ İlk başta 0rem
- `.hover:mr-100` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu %100
- `.hover:mr-75` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu %75
- `.hover:mr-50` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu %50
- `.hover:mr-25` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu %25
- `.hover:mr-5` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 5rem
- `.hover:mr-4.5` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-4` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 4rem
- `.hover:mr-3.5` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-3` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 3rem
- `.hover:mr-2.5` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-2` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 2rem
- `.hover:mr-1.9` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.8` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.7` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.6` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.5` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.4` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.3` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.2` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1.1` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-1` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 1rem
- `.hover:mr-0.9` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.8` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.7` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.6` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.5` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.4` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.3` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-0.2` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0,2 rem
- `.hover:mr-0.1` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0,1 rem
- `.hover:mr-0` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu 0rem
- `.hover:mr-auto` - Fareyle üzerine gelindiğinde Sağ Kenar Boşluğu otomatik
- `.last:mr-0` - Marj Sağ 0rem sonda
- `.mr-100` - Sağ Kenar Boşluğu %100
- `.mr-75` - Sağ Kenar Boşluğu %75
- `.mr-50` - Sağ Kenar Boşluğu %50
- `.mr-25` - Sağ Kenar Boşluğu %25
- `.mr-5` - Sağ Kenar Boşluğu 5rem
- `.mr-4.5` - Sağ Kenar Boşluğu 0rem
- `.mr-4` - Sağ Kenar Boşluğu 4rem
- `.mr-3.5` - Sağ Kenar Boşluğu 0rem
- `.mr-3` - Sağ Kenar Boşluğu 3rem
- `.mr-2.5` - Sağ Kenar Boşluğu 0rem
- `.mr-2` - Sağ Kenar Boşluğu 2rem
- `.mr-1.9` - Sağ Kenar Boşluğu 0rem
- `.mr-1.8` - Sağ Kenar Boşluğu 0rem
- `.mr-1.7` - Sağ Kenar Boşluğu 0rem
- `.mr-1.6` - Sağ Kenar Boşluğu 0rem
- `.mr-1.5` - Sağ Kenar Boşluğu 0rem
- `.mr-1.4` - Sağ Kenar Boşluğu 0rem
- `.mr-1.3` - Sağ Kenar Boşluğu 0rem
- `.mr-1.2` - Sağ Kenar Boşluğu 0rem
- `.mr-1.1` - Sağ Kenar Boşluğu 0rem
- `.mr-1` - Sağ Kenar Boşluğu 1rem
- `.mr-0.9` - Sağ Kenar Boşluğu 0rem
- `.mr-0.8` - Sağ Kenar Boşluğu 0rem
- `.mr-0.7` - Sağ Kenar Boşluğu 0rem
- `.mr-0.6` - Sağ Kenar Boşluğu 0rem
- `.mr-0.5` - Sağ Kenar Boşluğu 0rem
- `.mr-0.4` - Sağ Kenar Boşluğu 0rem
- `.mr-0.3` - Sağ Kenar Boşluğu 0rem
- `.mr-0.2` - Sağ Kenar Boşluğu 0,2rem
- `.mr-0.1` - Sağ Kenar Boşluğu 0,1rem
- `.mr-0` - Sağ Kenar Boşluğu 0rem
- `.mr-auto` - Sağ Kenar Boşluğu otomatik

#### Margin Start

- `.hover:ms-2` - Fareyle üzerine gelindiğinde Marj Başlangıcı 2rem
- `.hover:ms-1.5` - Marj Başlangıcı 1,5 rem fareyle üzerine gelindiğinde
- `.hover:ms-1` - Marj Başlangıcı 1rem fareyle üzerine gelindiğinde
- `.hover:ms-0.5` - Marj Başlangıcı 0,5rem fareyle üzerine gelindiğinde
- `.hover:ms-0` - Marj Başlangıcı 0rem fareyle üzerine gelindiğinde
- `.ms-2` - Marj Başlangıcı 2rem
- `.ms-1.5` - Marj Başlangıcı 1,5rem
- `.ms-1` - Marj Başlangıcı 1rem
- `.ms-0.5` - Marj Başlangıcı 0,5rem
- `.ms-0` - Marj Başlangıcı 0rem

#### Margin Top

- `.first:mt-0` - Marj Üst 0rem ilk başta
- `.hover:mt-100` - Fareyle üzerine gelindiğinde Marj İlk %100
- `.hover:mt-75` - Fareyle üzerine gelindiğinde Marj Top %75
- `.hover:mt-50` - Fareyle üzerine gelindiğinde Marj İlk %50
- `.hover:mt-25` - Fareyle üzerine gelindiğinde Marj İlk %25
- `.hover:mt-5` - Fareyle üzerine gelindiğinde Marj İlk 5rem
- `.hover:mt-4.5` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-4` - Fareyle üzerine gelindiğinde Marj Top 4rem
- `.hover:mt-3.5` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-3` - Fareyle üzerine gelindiğinde Marj Top 3rem
- `.hover:mt-2.5` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-2` - Fareyle üzerine gelindiğinde Marj Üst 2rem
- `.hover:mt-1.9` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.8` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.7` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.6` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.5` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.4` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.3` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.2` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1.1` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-1` - Fareyle üzerine gelindiğinde Marj Üst 1rem
- `.hover:mt-0.9` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.8` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.7` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.6` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.5` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.4` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.3` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-0.2` - Fareyle üzerine gelindiğinde Marj Üst 0,2rem
- `.hover:mt-0.1` - Fareyle üzerine gelindiğinde Marj Üst 0,1 rem
- `.hover:mt-0` - Fareyle üzerine gelindiğinde Marj Üst 0rem
- `.hover:mt-auto` - Fareyle üzerine gelindiğinde Kenar Boşluğu Üstü otomatik
- `.last:mt-0` - Marj Üst 0rem sonda
- `.mt-100` - Marj İlk %100
- `.mt-75` - Marj Üst %75
- `.mt-50` - Marj İlk %50
- `.mt-25` - Marj Üst %25
- `.mt-5` - Marj Üst 5rem
- `.mt-4.5` - Marj Üst 0rem
- `.mt-4` - Marj Üst 4rem
- `.mt-3.5` - Marj Üst 0rem
- `.mt-3` - Marj Üst 3rem
- `.mt-2.5` - Marj Üst 0rem
- `.mt-2` - Marj Üst 2rem
- `.mt-1.9` - Marj Üst 0rem
- `.mt-1.8` - Marj Üst 0rem
- `.mt-1.7` - Marj Üst 0rem
- `.mt-1.6` - Marj Üst 0rem
- `.mt-1.5` - Marj Üst 0rem
- `.mt-1.4` - Marj Üst 0rem
- `.mt-1.3` - Marj Üst 0rem
- `.mt-1.2` - Marj Üst 0rem
- `.mt-1.1` - Marj Üst 0rem
- `.mt-1` - Marj Üst 1rem
- `.mt-0.9` - Marj Üst 0rem
- `.mt-0.8` - Marj Üst 0rem
- `.mt-0.7` - Marj Üst 0rem
- `.mt-0.6` - Marj Üst 0rem
- `.mt-0.5` - Marj Üst 0rem
- `.mt-0.4` - Marj Üst 0rem
- `.mt-0.3` - Marj Üst 0rem
- `.mt-0.2` - Marj Üst 0,2rem
- `.mt-0.1` - Marj Üst 0,1 rem
- `.mt-0` - Marj Üst 0rem
- `.mt-auto` - Marj Üst otomatik

#### Margin X-Axis

- `.hover:mx-100` - Fareyle üzerine gelindiğinde X Ekseni Marjı %100
- `.hover:mx-75` - Fareyle üzerine gelindiğinde X Ekseni Marjı %75
- `.hover:mx-50` - Fareyle üzerine gelindiğinde X Ekseni Marjı %50
- `.hover:mx-25` - Fareyle üzerine gelindiğinde X Ekseni Marjı %25
- `.hover:mx-5` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 5rem
- `.hover:mx-4.5` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-4` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 4rem
- `.hover:mx-3.5` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-3` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 3rem
- `.hover:mx-2.5` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-2` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 2rem
- `.hover:mx-1.9` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.8` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.7` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.6` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.5` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.4` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.3` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.2` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1.1` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-1` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 1 rem
- `.hover:mx-0.9` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.8` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.7` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.6` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.5` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.4` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.3` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-0.2` - Fareyle üzerine gelindiğinde X Ekseni Marjı 0,2 rem
- `.hover:mx-0.1` - Fareyle üzerine gelindiğinde X Ekseni Marjı 0,1 rem
- `.hover:mx-0` - Fareyle üzerine gelindiğinde X Ekseni Kenar Boşluğu 0rem
- `.hover:mx-auto` - Fareyle üzerine gelindiğinde X Ekseni Marjı otomatik
- `.mx-100` - Marj X Ekseni %100
- `.mx-75` - Marj X Ekseni %75
- `.mx-50` - Marj X Ekseni %50
- `.mx-25` - Marj X Ekseni %25
- `.mx-5` - Marj X Ekseni 5 rem
- `.mx-4.5` - Marj X Ekseni 0rem
- `.mx-4` - Marj X Ekseni 4rem
- `.mx-3.5` - Marj X Ekseni 0rem
- `.mx-3` - Marj X Ekseni 3rem
- `.mx-2.5` - Marj X Ekseni 0rem
- `.mx-2` - Marj X Ekseni 2rem
- `.mx-1.9` - Marj X Ekseni 0rem
- `.mx-1.8` - Marj X Ekseni 0rem
- `.mx-1.7` - Marj X Ekseni 0rem
- `.mx-1.6` - Marj X Ekseni 0rem
- `.mx-1.5` - Marj X Ekseni 0rem
- `.mx-1.4` - Marj X Ekseni 0rem
- `.mx-1.3` - Marj X Ekseni 0rem
- `.mx-1.2` - Marj X Ekseni 0rem
- `.mx-1.1` - Marj X Ekseni 0rem
- `.mx-1` - Marj X Ekseni 1 rem
- `.mx-0.9` - Marj X Ekseni 0rem
- `.mx-0.8` - Marj X Ekseni 0rem
- `.mx-0.7` - Marj X Ekseni 0rem
- `.mx-0.6` - Marj X Ekseni 0rem
- `.mx-0.5` - Marj X Ekseni 0rem
- `.mx-0.4` - Marj X Ekseni 0rem
- `.mx-0.3` - Marj X Ekseni 0rem
- `.mx-0.2` - Marj X Ekseni 0,2 rem
- `.mx-0.1` - Marj X Ekseni 0,1 rem
- `.mx-0` - Marj X Ekseni 0rem
- `.mx-auto` - Marj X Ekseni otomatik

#### Margin Y-Axis

- `.hover:my-100` - Fareyle üzerine gelindiğinde Y Ekseni Marjı %100
- `.hover:my-75` - Fareyle üzerine gelindiğinde Y Ekseni Marjı %75
- `.hover:my-50` - Fareyle üzerine gelindiğinde Y Ekseni Marjı %50
- `.hover:my-25` - Fareyle üzerine gelindiğinde Y Ekseni Marjı %25
- `.hover:my-5` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 5rem
- `.hover:my-4.5` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-4` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 4rem
- `.hover:my-3.5` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-3` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 3rem
- `.hover:my-2.5` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-2` - Fareyle üzerine gelindiğinde Y Ekseni Kenar Boşluğu 2rem
- `.hover:my-1.9` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.8` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.7` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.6` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.5` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.4` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.3` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.2` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1.1` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-1` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 1rem
- `.hover:my-0.9` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.8` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.7` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.6` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.5` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.4` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.3` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-0.2` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0,2rem
- `.hover:my-0.1` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0,1 rem
- `.hover:my-0` - Fareyle üzerine gelindiğinde Y Ekseni Marjı 0rem
- `.hover:my-auto` - Fareyle üzerine gelindiğinde Y Ekseni Kenar Boşluğu otomatik
- `.my-100` - Marj Y Ekseni %100
- `.my-75` - Marj Y Ekseni %75
- `.my-50` - Marj Y Ekseni %50
- `.my-25` - Marj Y Ekseni %25
- `.my-5` - Marj Y Ekseni 5 rem
- `.my-4.5` - Marj Y Ekseni 0rem
- `.my-4` - Marj Y Ekseni 4rem
- `.my-3.5` - Marj Y Ekseni 0rem
- `.my-3` - Marj Y Ekseni 3rem
- `.my-2.5` - Marj Y Ekseni 0rem
- `.my-2` - Marj Y Ekseni 2rem
- `.my-1.9` - Marj Y Ekseni 0rem
- `.my-1.8` - Marj Y Ekseni 0rem
- `.my-1.7` - Marj Y Ekseni 0rem
- `.my-1.6` - Marj Y Ekseni 0rem
- `.my-1.5` - Marj Y Ekseni 0rem
- `.my-1.4` - Marj Y Ekseni 0rem
- `.my-1.3` - Marj Y Ekseni 0rem
- `.my-1.2` - Marj Y Ekseni 0rem
- `.my-1.1` - Marj Y Ekseni 0rem
- `.my-1` - Marj Y Ekseni 1 rem
- `.my-0.9` - Marj Y Ekseni 0rem
- `.my-0.8` - Marj Y Ekseni 0rem
- `.my-0.7` - Marj Y Ekseni 0rem
- `.my-0.6` - Marj Y Ekseni 0rem
- `.my-0.5` - Marj Y Ekseni 0rem
- `.my-0.4` - Marj Y Ekseni 0rem
- `.my-0.3` - Marj Y Ekseni 0rem
- `.my-0.2` - Marj Y Ekseni 0,2rem
- `.my-0.1` - Y Ekseni Marjı 0,1rem
- `.my-0` - Marj Y Ekseni 0rem
- `.my-auto` - Marj Y Ekseni otomatik

### Padding

#### Padding All

- `.first:p-0` - İlk önce tüm 0rem'i doldurma
- `.hover:p-5` - Vurguluyken tüm 5rem'i doldurma
- `.hover:p-4.5` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-4` - Vurguluyken tüm 4rem'i doldurma
- `.hover:p-3.5` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-3` - Vurguluyken tüm 3rem'i doldurma
- `.hover:p-2.5` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-2` - Vurguluyken tüm 2rem'i doldurma
- `.hover:p-1.9` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.8` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.7` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.6` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.5` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.4` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.3` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.2` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1.1` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-1` - Vurguluyken tüm 1rem'i doldurma
- `.hover:p-0.9` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.8` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.7` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.6` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.5` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.4` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.3` - Vurguluyken tüm 0rem'i doldurma
- `.hover:p-0.2` - Vurguluyken tümü 0,2 rem dolgulu
- `.hover:p-0.1` - Vurguluyken tümü 0,1 rem dolgulu
- `.hover:p-0` - Vurguluyken tüm 0rem'i doldurma
- `.last:p-0` - Tüm 0rem'i en sonda doldurma
- `.p-5` - Dolgunun tamamı 5rem
- `.p-4.5` - Dolgu Tümü 0rem
- `.p-4` - Tümü 4rem'i doldurma
- `.p-3.5` - Dolgu Tümü 0rem
- `.p-3` - Dolgu Tümü 3rem
- `.p-2.5` - Dolgu Tümü 0rem
- `.p-2` - Dolgu Tümü 2rem
- `.p-1.9` - Dolgu Tümü 0rem
- `.p-1.8` - Dolgu Tümü 0rem
- `.p-1.7` - Dolgu Tümü 0rem
- `.p-1.6` - Dolgu Tümü 0rem
- `.p-1.5` - Dolgu Tümü 0rem
- `.p-1.4` - Dolgu Tümü 0rem
- `.p-1.3` - Dolgu Tümü 0rem
- `.p-1.2` - Dolgu Tümü 0rem
- `.p-1.1` - Dolgu Tümü 0rem
- `.p-1` - Dolgunun tamamı 1rem
- `.p-0.9` - Dolgu Tümü 0rem
- `.p-0.8` - Dolgu Tümü 0rem
- `.p-0.7` - Dolgu Tümü 0rem
- `.p-0.6` - Dolgu Tümü 0rem
- `.p-0.5` - Dolgu Tümü 0rem
- `.p-0.4` - Dolgu Tümü 0rem
- `.p-0.3` - Dolgu Tümü 0rem
- `.p-0.2` - Dolgunun tamamı 0,2 rem
- `.p-0.1` - Dolgunun tamamı 0,1 rem
- `.p-0` - Dolgu Tümü 0rem

#### Padding Bottom

- `.first:pb-0` - Önce Alttan 0rem Dolgu
- `.hover:pb-100` - Vurguluyken Altta %100 Dolgu
- `.hover:pb-75` - Vurguluyken Alt Dolgu %75
- `.hover:pb-50` - Vurguluyken Alttan %50 Dolgu
- `.hover:pb-25` - Vurguluyken Alttan %25 Dolgu
- `.hover:pb-5` - Vurguluyken Alttan 5rem Dolgu
- `.hover:pb-4.5` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-4` - Vurguluyken Alttan 4rem Dolgu
- `.hover:pb-3.5` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-3` - Vurguluyken Alttan 3rem Dolgu
- `.hover:pb-2.5` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-2` - Vurguluyken Alttan 2rem Dolgu
- `.hover:pb-1.9` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.8` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.7` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.6` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.5` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.4` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.3` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.2` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1.1` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-1` - Vurguluyken Alttan 1rem Dolgu
- `.hover:pb-0.9` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.8` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.7` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.6` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.5` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.4` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.3` - Vurguluyken Alttan 0rem Dolgu
- `.hover:pb-0.2` - Vurguluyken Alt Dolgu 0,2rem
- `.hover:pb-0.1` - Vurguluyken Alt Dolgu 0,1 rem
- `.hover:pb-0` - Vurguluyken Alttan 0rem Dolgu
- `.last:pb-0` - Dolgu Alt 0rem sonda
- `.pb-100` - Dolgu Alt %100
- `.pb-75` - Alt Dolgu %75
- `.pb-50` - Dolgu Alt %50
- `.pb-25` - Dolgu Alt %25
- `.pb-5` - Dolgu Alt 5rem
- `.pb-4.5` - Alt Dolgu 0rem
- `.pb-4` - Dolgu Alt 4rem
- `.pb-3.5` - Alt Dolgu 0rem
- `.pb-3` - Dolgu Alt 3rem
- `.pb-2.5` - Alt Dolgu 0rem
- `.pb-2` - Dolgu Alt 2rem
- `.pb-1.9` - Alt Dolgu 0rem
- `.pb-1.8` - Alt Dolgu 0rem
- `.pb-1.7` - Alt Dolgu 0rem
- `.pb-1.6` - Alt Dolgu 0rem
- `.pb-1.5` - Alt Dolgu 0rem
- `.pb-1.4` - Alt Dolgu 0rem
- `.pb-1.3` - Alt Dolgu 0rem
- `.pb-1.2` - Alt Dolgu 0rem
- `.pb-1.1` - Alt Dolgu 0rem
- `.pb-1` - Dolgu Alt 1rem
- `.pb-0.9` - Alt Dolgu 0rem
- `.pb-0.8` - Alt Dolgu 0rem
- `.pb-0.7` - Alt Dolgu 0rem
- `.pb-0.6` - Alt Dolgu 0rem
- `.pb-0.5` - Alt Dolgu 0rem
- `.pb-0.4` - Alt Dolgu 0rem
- `.pb-0.3` - Alt Dolgu 0rem
- `.pb-0.2` - Alt Dolgu 0,2rem
- `.pb-0.1` - Alt Dolgu 0,1 rem
- `.pb-0` - Alt Dolgu 0rem

#### Padding Left

- `.first:pl-0` - Dolgu İlk önce 0rem sola
- `.hover:pl-5` - Vurguluyken 5rem sola dolgu
- `.hover:pl-4.5` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-4` - Vurguluyken Sol 4rem Dolgu
- `.hover:pl-3.5` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-3` - Vurguluyken 3rem Sol Dolgu
- `.hover:pl-2.5` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-2` - Vurguluyken 2rem Sol Dolgu
- `.hover:pl-1.9` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.8` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.7` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.6` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.5` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.4` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.3` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.2` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1.1` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-1` - Vurguluyken 1rem sola dolgu
- `.hover:pl-0.9` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.8` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.7` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.6` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.5` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.4` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.3` - Vurguluyken 0rem Sol Dolgu
- `.hover:pl-0.2` - Vurguluyken Sol 0,2 rem Dolgu
- `.hover:pl-0.1` - Vurguluyken 0,1 rem Sol Dolgu
- `.hover:pl-0` - Vurguluyken 0rem Sol Dolgu
- `.last:pl-0` - Dolgu Sola 0rem sonda
- `.pl-5` - Sol 5rem Dolgu
- `.pl-4.5` - Dolgu Sol 0rem
- `.pl-4` - Dolgu Sol 4rem
- `.pl-3.5` - Dolgu Sol 0rem
- `.pl-3` - Dolgu Sol 3rem
- `.pl-2.5` - Dolgu Sol 0rem
- `.pl-2` - Dolgu Sol 2rem
- `.pl-1.9` - Dolgu Sol 0rem
- `.pl-1.8` - Dolgu Sol 0rem
- `.pl-1.7` - Dolgu Sol 0rem
- `.pl-1.6` - Dolgu Sol 0rem
- `.pl-1.5` - Dolgu Sol 0rem
- `.pl-1.4` - Dolgu Sol 0rem
- `.pl-1.3` - Dolgu Sol 0rem
- `.pl-1.2` - Dolgu Sol 0rem
- `.pl-1.1` - Dolgu Sol 0rem
- `.pl-1` - Sol 1rem dolgu
- `.pl-0.9` - Dolgu Sol 0rem
- `.pl-0.8` - Dolgu Sol 0rem
- `.pl-0.7` - Dolgu Sol 0rem
- `.pl-0.6` - Dolgu Sol 0rem
- `.pl-0.5` - Dolgu Sol 0rem
- `.pl-0.4` - Dolgu Sol 0rem
- `.pl-0.3` - Dolgu Sol 0rem
- `.pl-0.2` - Dolgu Sol 0,2rem
- `.pl-0.1` - Dolgu Sol 0,1rem
- `.pl-0` - Dolgu Sol 0rem

#### Padding Right

- `.first:pr-0` - İlk önce Sağa 0rem Dolgu
- `.hover:pr-100` - Vurguluyken Sağa %100 Dolgu
- `.hover:pr-75` - Vurguluyken Sağa %75 Dolgu
- `.hover:pr-50` - Vurguluyken Sağa %50 Dolgu
- `.hover:pr-25` - Vurguluyken Sağa %25 Dolgu
- `.hover:pr-5` - Vurguluyken Sağa 5rem Dolgu
- `.hover:pr-4.5` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-4` - Fareyle üzerine gelindiğinde Sağa 4rem Dolgu
- `.hover:pr-3.5` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-3` - Vurguluyken Sağa 3rem Dolgu
- `.hover:pr-2.5` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-2` - Fareyle üzerine gelindiğinde Sağa 2rem Dolgu
- `.hover:pr-1.9` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.8` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.7` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.6` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.5` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.4` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.3` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.2` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1.1` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-1` - Fareyle üzerine gelindiğinde 1rem Sağa Dolgu
- `.hover:pr-0.9` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.8` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.7` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.6` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.5` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.4` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.3` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.hover:pr-0.2` - Fareyle üzerine gelindiğinde Sağa 0,2 rem Dolgu
- `.hover:pr-0.1` - Fareyle üzerine gelindiğinde Sağa 0,1 rem Dolgu
- `.hover:pr-0` - Fareyle üzerine gelindiğinde Sağa 0rem Dolgu
- `.last:pr-0` - Sonda Sağa 0rem Dolgu
- `.pr-100` - Sağa Dolgu %100
- `.pr-75` - Sağa Dolgu %75
- `.pr-50` - Sağa Dolgu %50
- `.pr-25` - Sağa Dolgu %25
- `.pr-5` - Sağa Dolgu 5rem
- `.pr-4.5` - Sağa Dolgu 0rem
- `.pr-4` - Sağa Dolgu 4rem
- `.pr-3.5` - Sağa Dolgu 0rem
- `.pr-3` - Sağa Dolgu 3rem
- `.pr-2.5` - Sağa Dolgu 0rem
- `.pr-2` - Sağa Dolgu 2rem
- `.pr-1.9` - Sağa Dolgu 0rem
- `.pr-1.8` - Sağa Dolgu 0rem
- `.pr-1.7` - Sağa Dolgu 0rem
- `.pr-1.6` - Sağa Dolgu 0rem
- `.pr-1.5` - Sağa Dolgu 0rem
- `.pr-1.4` - Sağa Dolgu 0rem
- `.pr-1.3` - Sağa Dolgu 0rem
- `.pr-1.2` - Sağa Dolgu 0rem
- `.pr-1.1` - Sağa Dolgu 0rem
- `.pr-1` - Sağa Dolgu 1rem
- `.pr-0.9` - Sağa Dolgu 0rem
- `.pr-0.8` - Sağa Dolgu 0rem
- `.pr-0.7` - Sağa Dolgu 0rem
- `.pr-0.6` - Sağa Dolgu 0rem
- `.pr-0.5` - Sağa Dolgu 0rem
- `.pr-0.4` - Sağa Dolgu 0rem
- `.pr-0.3` - Sağa Dolgu 0rem
- `.pr-0.2` - Sağa Dolgu 0,2rem
- `.pr-0.1` - Sağa Dolgu 0,1 rem
- `.pr-0` - Sağa Dolgu 0rem

#### Padding Top

- `.first:pt-0` - İlk önce Üst 0rem dolgusu
- `.hover:pt-100` - Fareyle üzerine gelindiğinde Top %100 doldurma
- `.hover:pt-75` - Fareyle üzerine gelindiğinde Top %75 dolgusu
- `.hover:pt-50` - Fareyle üzerine gelindiğinde Top %50 dolgusu
- `.hover:pt-25` - Fareyle üzerine gelindiğinde Top %25 dolgusu
- `.hover:pt-5` - Fareyle üzerine gelindiğinde Top 5rem dolgusu
- `.hover:pt-4.5` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-4` - Fareyle üzerine gelindiğinde Top 4rem dolgusu
- `.hover:pt-3.5` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-3` - Fareyle üzerine gelindiğinde Top 3rem dolgusu
- `.hover:pt-2.5` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-2` - Fareyle üzerine gelindiğinde Top 2rem dolgusu
- `.hover:pt-1.9` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.8` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.7` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.6` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.5` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.4` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.3` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.2` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1.1` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-1` - Fareyle üzerine gelindiğinde Üst 1rem dolgusu
- `.hover:pt-0.9` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.8` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.7` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.6` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.5` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.4` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.3` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.hover:pt-0.2` - Vurguluyken Üst Dolgu 0,2rem
- `.hover:pt-0.1` - Vurguluyken Üst Dolgu 0,1rem
- `.hover:pt-0` - Fareyle üzerine gelindiğinde Üst 0rem dolgusu
- `.last:pt-0` - Dolgu Üst 0rem sonda
- `.pt-100` - Dolgu Üstü %100
- `.pt-75` - Dolgu Üstü %75
- `.pt-50` - Dolgu Üst %50
- `.pt-25` - Dolgu Üstü %25
- `.pt-5` - Dolgu Üstü 5rem
- `.pt-4.5` - Dolgu Üstü 0rem
- `.pt-4` - Dolgu Üstü 4rem
- `.pt-3.5` - Dolgu Üstü 0rem
- `.pt-3` - Dolgu Üstü 3rem
- `.pt-2.5` - Dolgu Üstü 0rem
- `.pt-2` - Dolgu Üstü 2rem
- `.pt-1.9` - Dolgu Üstü 0rem
- `.pt-1.8` - Dolgu Üstü 0rem
- `.pt-1.7` - Dolgu Üstü 0rem
- `.pt-1.6` - Dolgu Üstü 0rem
- `.pt-1.5` - Dolgu Üstü 0rem
- `.pt-1.4` - Dolgu Üstü 0rem
- `.pt-1.3` - Dolgu Üstü 0rem
- `.pt-1.2` - Dolgu Üstü 0rem
- `.pt-1.1` - Dolgu Üstü 0rem
- `.pt-1` - Dolgu Üstü 1rem
- `.pt-0.9` - Dolgu Üstü 0rem
- `.pt-0.8` - Dolgu Üstü 0rem
- `.pt-0.7` - Dolgu Üstü 0rem
- `.pt-0.6` - Dolgu Üstü 0rem
- `.pt-0.5` - Dolgu Üstü 0rem
- `.pt-0.4` - Dolgu Üstü 0rem
- `.pt-0.3` - Dolgu Üstü 0rem
- `.pt-0.2` - Dolgu Üstü 0.2rem
- `.pt-0.1` - Dolgu Üstü 0.1rem
- `.pt-0` - Dolgu Üstü 0rem

#### Padding X-Axis

- `.hover:px-100` - Fareyle üzerine gelindiğinde X Ekseni %100 dolgusu
- `.hover:px-75` - Fareyle üzerine gelindiğinde X Ekseni %75 dolgusu
- `.hover:px-50` - Fareyle üzerine gelindiğinde X Ekseni %50 dolgusu
- `.hover:px-25` - Fareyle üzerine gelindiğinde X Ekseni %25 dolgusu
- `.hover:px-5` - Fareyle üzerine gelindiğinde X Ekseni 5rem dolgusu
- `.hover:px-4.5` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-4` - Fareyle üzerine gelindiğinde X Ekseni 4rem dolgusu
- `.hover:px-3.5` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-3` - Fareyle üzerine gelindiğinde X Ekseni 3rem dolgusu
- `.hover:px-2.5` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-2` - Fareyle üzerine gelindiğinde X Ekseni 2rem dolgusu
- `.hover:px-1.9` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.8` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.7` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.6` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.5` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.4` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.3` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.2` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1.1` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-1` - Fareyle üzerine gelindiğinde X Ekseni 1rem dolgusu
- `.hover:px-0.9` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.8` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.7` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.6` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.5` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.4` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.3` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.hover:px-0.2` - Fareyle üzerine gelindiğinde X Ekseni 0,2rem dolgusu
- `.hover:px-0.1` - Fareyle üzerine gelindiğinde X Ekseni 0,1rem dolgusu
- `.hover:px-0` - Fareyle üzerine gelindiğinde X Ekseni 0rem dolgusu
- `.px-100` - Dolgu X Ekseni %100
- `.px-75` - Dolgu X Ekseni %75
- `.px-50` - Dolgu X Ekseni %50
- `.px-25` - Dolgu X Ekseni %25
- `.px-5` - Dolgu X Ekseni 5rem
- `.px-4.5` - Dolgu X Ekseni 0 rem
- `.px-4` - Dolgu X Ekseni 4rem
- `.px-3.5` - Dolgu X Ekseni 0 rem
- `.px-3` - Dolgu X Ekseni 3rem
- `.px-2.5` - Dolgu X Ekseni 0 rem
- `.px-2` - Dolgu X Ekseni 2rem
- `.px-1.9` - Dolgu X Ekseni 0 rem
- `.px-1.8` - Dolgu X Ekseni 0 rem
- `.px-1.7` - Dolgu X Ekseni 0 rem
- `.px-1.6` - Dolgu X Ekseni 0 rem
- `.px-1.5` - Dolgu X Ekseni 0 rem
- `.px-1.4` - Dolgu X Ekseni 0 rem
- `.px-1.3` - Dolgu X Ekseni 0 rem
- `.px-1.2` - Dolgu X Ekseni 0 rem
- `.px-1.1` - Dolgu X Ekseni 0 rem
- `.px-1` - Dolgu X Ekseni 1rem
- `.px-0.9` - Dolgu X Ekseni 0 rem
- `.px-0.8` - Dolgu X Ekseni 0 rem
- `.px-0.7` - Dolgu X Ekseni 0 rem
- `.px-0.6` - Dolgu X Ekseni 0 rem
- `.px-0.5` - Dolgu X Ekseni 0 rem
- `.px-0.4` - Dolgu X Ekseni 0 rem
- `.px-0.3` - Dolgu X Ekseni 0 rem
- `.px-0.2` - Dolgu X Ekseni 0,2 rem
- `.px-0.1` - Dolgu X Ekseni 0,1 rem
- `.px-0` - Dolgu X Ekseni 0 rem

#### Padding Y-Axis

- `.hover:py-100` - Fareyle üzerine gelindiğinde Y Ekseni %100 dolgusu
- `.hover:py-75` - Vurguluyken Y Ekseni %75 dolgusu
- `.hover:py-50` - Fareyle üzerine gelindiğinde Y Ekseni %50 dolgusu
- `.hover:py-25` - Vurguluyken Y Ekseni %25 dolgusu
- `.hover:py-5` - Fareyle üzerine gelindiğinde Y Ekseni 5rem dolgusu
- `.hover:py-4.5` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-4` - Fareyle üzerine gelindiğinde Y Ekseni 4rem dolgusu
- `.hover:py-3.5` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-3` - Fareyle üzerine gelindiğinde Y Ekseni 3rem dolgusu
- `.hover:py-2.5` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-2` - Fareyle üzerine gelindiğinde Y Ekseni 2rem dolgusu
- `.hover:py-1.9` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.8` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.7` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.6` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.5` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.4` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.3` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.2` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1.1` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-1` - Fareyle üzerine gelindiğinde Y Ekseni 1rem dolgusu
- `.hover:py-0.9` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.8` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.7` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.6` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.5` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.4` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.3` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.hover:py-0.2` - Fareyle üzerine gelindiğinde Y Ekseni 0,2 rem dolgusu
- `.hover:py-0.1` - Fareyle üzerine gelindiğinde Y Ekseni 0,1 rem dolgusu
- `.hover:py-0` - Fareyle üzerine gelindiğinde Y Ekseni 0rem dolgusu
- `.py-100` - Dolgu Y Ekseni %100
- `.py-75` - Dolgu Y Ekseni %75
- `.py-50` - Dolgu Y Ekseni %50
- `.py-25` - Dolgu Y Ekseni %25
- `.py-5` - Dolgu Y Ekseni 5rem
- `.py-4.5` - Dolgu Y Ekseni 0rem
- `.py-4` - Dolgu Y Ekseni 4rem
- `.py-3.5` - Dolgu Y Ekseni 0rem
- `.py-3` - Dolgu Y Ekseni 3rem
- `.py-2.5` - Dolgu Y Ekseni 0rem
- `.py-2` - Dolgu Y Ekseni 2rem
- `.py-1.9` - Dolgu Y Ekseni 0rem
- `.py-1.8` - Dolgu Y Ekseni 0rem
- `.py-1.7` - Dolgu Y Ekseni 0rem
- `.py-1.6` - Dolgu Y Ekseni 0rem
- `.py-1.5` - Dolgu Y Ekseni 0rem
- `.py-1.4` - Dolgu Y Ekseni 0rem
- `.py-1.3` - Dolgu Y Ekseni 0rem
- `.py-1.2` - Dolgu Y Ekseni 0rem
- `.py-1.1` - Dolgu Y Ekseni 0rem
- `.py-1` - Dolgu Y Ekseni 1rem
- `.py-0.9` - Dolgu Y Ekseni 0rem
- `.py-0.8` - Dolgu Y Ekseni 0rem
- `.py-0.7` - Dolgu Y Ekseni 0rem
- `.py-0.6` - Dolgu Y Ekseni 0rem
- `.py-0.5` - Dolgu Y Ekseni 0rem
- `.py-0.4` - Dolgu Y Ekseni 0rem
- `.py-0.3` - Dolgu Y Ekseni 0rem
- `.py-0.2` - Dolgu Y Ekseni 0,2rem
- `.py-0.1` - Dolgu Y Ekseni 0,1 rem
- `.py-0` - Dolgu Y Ekseni 0rem

## Sizing

### Width

- `.hover:w-100` - Fareyle üzerine gelindiğinde genişlik %100
- `.hover:w-95` - Fareyle üzerine gelindiğinde genişlik %95
- `.hover:w-90` - Fareyle üzerine gelindiğinde genişlik %90
- `.hover:w-85` - Fareyle üzerine gelindiğinde genişlik %85
- `.hover:w-80` - Fareyle üzerine gelindiğinde genişlik %80
- `.hover:w-75` - Fareyle üzerine gelindiğinde genişlik %75
- `.hover:w-70` - Fareyle üzerine gelindiğinde genişlik %70
- `.hover:w-65` - Fareyle üzerine gelindiğinde genişlik %65
- `.hover:w-60` - Fareyle üzerine gelindiğinde genişlik %60
- `.hover:w-55` - Fareyle üzerine gelindiğinde genişlik %55
- `.hover:w-50` - Fareyle üzerine gelindiğinde genişlik %50
- `.hover:w-45` - Fareyle üzerine gelindiğinde genişlik %45
- `.hover:w-40` - Fareyle üzerine gelindiğinde genişlik %40
- `.hover:w-35` - Fareyle üzerine gelindiğinde genişlik %35
- `.hover:w-30` - Fareyle üzerine gelindiğinde genişlik %30
- `.hover:w-25` - Fareyle üzerine gelindiğinde genişlik %25
- `.hover:w-20` - Fareyle üzerine gelindiğinde genişlik %20
- `.hover:w-15` - Fareyle üzerine gelindiğinde genişlik %15
- `.hover:w-10` - Fareyle üzerine gelindiğinde genişlik %10
- `.hover:w-5` - Fareyle üzerine gelindiğinde genişlik %5
- `.hover:w-auto` - Fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.w-100` - Genişlik %100
- `.w-95` - Genişlik %95
- `.w-90` - Genişlik %90
- `.w-85` - Genişlik %85
- `.w-80` - Genişlik %80
- `.w-75` - Genişlik %75
- `.w-70` - Genişlik %70
- `.w-65` - Genişlik %65
- `.w-60` - Genişlik %60
- `.w-55` - Genişlik %55
- `.w-50` - Genişlik %50
- `.w-45` - Genişlik %45
- `.w-40` - Genişlik %40
- `.w-35` - Genişlik %35
- `.w-30` - Genişlik %30
- `.w-25` - Genişlik %25
- `.w-20` - Genişlik %20
- `.w-15` - Genişlik %15
- `.w-10` - Genişlik %10
- `.w-5` - Genişlik %5
- `.w-auto` - Otomatik genişlik %

##### Width - Mobile (≤ 480px)

- `.hover:mobile:w-100` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %100
- `.hover:mobile:w-95` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %95
- `.hover:mobile:w-90` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %90
- `.hover:mobile:w-85` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %85
- `.hover:mobile:w-80` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %80
- `.hover:mobile:w-75` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %75
- `.hover:mobile:w-70` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %70
- `.hover:mobile:w-65` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %65
- `.hover:mobile:w-60` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %60
- `.hover:mobile:w-55` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %55
- `.hover:mobile:w-50` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %50
- `.hover:mobile:w-45` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %45
- `.hover:mobile:w-40` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %40
- `.hover:mobile:w-35` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %35
- `.hover:mobile:w-30` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %30
- `.hover:mobile:w-25` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %25
- `.hover:mobile:w-20` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %20
- `.hover:mobile:w-15` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %15
- `.hover:mobile:w-10` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %10
- `.hover:mobile:w-5` - Mobil cihazda fareyle üzerine gelindiğinde genişlik %5
- `.hover:mobile:w-auto` - Mobil cihazda fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.mobile:w-100` - Mobil cihazlarda genişlik %100
- `.mobile:w-95` - Mobil cihazlarda genişlik %95
- `.mobile:w-90` - Mobil cihazlarda genişlik %90
- `.mobile:w-85` - Mobil cihazlarda genişlik %85
- `.mobile:w-80` - Mobil cihazlarda genişlik %80
- `.mobile:w-75` - Mobil cihazlarda genişlik %75
- `.mobile:w-70` - Mobil cihazlarda genişlik %70
- `.mobile:w-65` - Mobil cihazlarda genişlik %65
- `.mobile:w-60` - Mobil cihazlarda genişlik %60
- `.mobile:w-55` - Mobil cihazlarda genişlik %55
- `.mobile:w-50` - Mobil cihazlarda genişlik %50
- `.mobile:w-45` - Mobil cihazlarda genişlik %45
- `.mobile:w-40` - Mobil cihazlarda genişlik %40
- `.mobile:w-35` - Mobil cihazlarda genişlik %35
- `.mobile:w-30` - Mobil cihazlarda genişlik %30
- `.mobile:w-25` - Mobil cihazlarda genişlik %25
- `.mobile:w-20` - Mobil cihazlarda genişlik %20
- `.mobile:w-15` - Mobil cihazlarda genişlik %15
- `.mobile:w-10` - Mobil cihazlarda genişlik %10
- `.mobile:w-5` - Mobil cihazlarda genişlik %5
- `.mobile:w-auto` - Mobil cihazda otomatik genişlik %'si

##### Width - Tablet (480px - 768px)

- `.hover:tablet:w-100` - Tabletin üzerine gelindiğinde genişlik %100
- `.hover:tablet:w-95` - Tabletin üzerine gelindiğinde genişlik %95
- `.hover:tablet:w-90` - Tabletin üzerine gelindiğinde genişlik %90
- `.hover:tablet:w-85` - Tablet üzerinde fareyle üzerine gelindiğinde genişlik %85
- `.hover:tablet:w-80` - Tabletin üzerine gelindiğinde genişlik %80
- `.hover:tablet:w-75` - Tablet üzerinde fareyle üzerine gelindiğinde genişlik %75
- `.hover:tablet:w-70` - Tabletin üzerine gelindiğinde genişlik %70
- `.hover:tablet:w-65` - Tablet üzerinde fareyle üzerine gelindiğinde genişlik %65
- `.hover:tablet:w-60` - Tabletin üzerine gelindiğinde genişlik %60
- `.hover:tablet:w-55` - Tabletin üzerine gelindiğinde genişlik %55
- `.hover:tablet:w-50` - Tablet üzerinde fareyle üzerine gelindiğinde genişlik %50
- `.hover:tablet:w-45` - Genişlik tablet üzerinde fareyle üzerine gelindiğinde %45
- `.hover:tablet:w-40` - Tabletin üzerine gelindiğinde genişlik %40
- `.hover:tablet:w-35` - Tablet üzerinde fareyle üzerine gelindiğinde genişlik %35
- `.hover:tablet:w-30` - Tabletin üzerine gelindiğinde genişlik %30
- `.hover:tablet:w-25` - Genişlik tablet üzerinde fareyle üzerine gelindiğinde %25
- `.hover:tablet:w-20` - Genişlik tablet üzerinde fareyle üzerine gelindiğinde %20
- `.hover:tablet:w-15` - Tabletin üzerine gelindiğinde genişlik %15
- `.hover:tablet:w-10` - Tabletin üzerine gelindiğinde genişlik %10
- `.hover:tablet:w-5` - Tabletin üzerine gelindiğinde genişlik %5
- `.hover:tablet:w-auto` - Tablette fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.tablet:w-100` - Tablette genişlik %100
- `.tablet:w-95` - Tablette genişlik %95
- `.tablet:w-90` - Tablette genişlik %90
- `.tablet:w-85` - Tablette genişlik %85
- `.tablet:w-80` - Tablette genişlik %80
- `.tablet:w-75` - Tablette genişlik %75
- `.tablet:w-70` - Tablette genişlik %70
- `.tablet:w-65` - Tablette genişlik %65
- `.tablet:w-60` - Tablette genişlik %60
- `.tablet:w-55` - Tablette genişlik %55
- `.tablet:w-50` - Tablette genişlik %50
- `.tablet:w-45` - Tablette genişlik %45
- `.tablet:w-40` - Tablette genişlik %40
- `.tablet:w-35` - Tablette genişlik %35
- `.tablet:w-30` - Tablette genişlik %30
- `.tablet:w-25` - Tablette genişlik %25
- `.tablet:w-20` - Tablette genişlik %20
- `.tablet:w-15` - Tablette genişlik %15
- `.tablet:w-10` - Tablette genişlik %10
- `.tablet:w-5` - Tablette genişlik %5
- `.tablet:w-auto` - Tablette otomatik genişlik yüzdesi

##### Width - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:w-100` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %100
- `.hover:tablet-pc:w-95` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %95
- `.hover:tablet-pc:w-90` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %90
- `.hover:tablet-pc:w-85` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %85
- `.hover:tablet-pc:w-80` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %80
- `.hover:tablet-pc:w-75` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %75
- `.hover:tablet-pc:w-70` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %70
- `.hover:tablet-pc:w-65` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %65
- `.hover:tablet-pc:w-60` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %60
- `.hover:tablet-pc:w-55` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %55
- `.hover:tablet-pc:w-50` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %50
- `.hover:tablet-pc:w-45` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %45
- `.hover:tablet-pc:w-40` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %40
- `.hover:tablet-pc:w-35` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %35
- `.hover:tablet-pc:w-30` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %30
- `.hover:tablet-pc:w-25` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %25
- `.hover:tablet-pc:w-20` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %20
- `.hover:tablet-pc:w-15` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %15
- `.hover:tablet-pc:w-10` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %10
- `.hover:tablet-pc:w-5` - Tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %5
- `.hover:tablet-pc:w-auto` - Tablet bilgisayarda fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.tablet-pc:w-100` - Tablet bilgisayarda genişlik %100
- `.tablet-pc:w-95` - Tablet bilgisayarda genişlik %95
- `.tablet-pc:w-90` - Tablet bilgisayarda genişlik %90
- `.tablet-pc:w-85` - Tablet bilgisayarda genişlik %85
- `.tablet-pc:w-80` - Tablet bilgisayarda genişlik %80
- `.tablet-pc:w-75` - Tablet bilgisayarda genişlik %75
- `.tablet-pc:w-70` - Tablet PC'de genişlik %70
- `.tablet-pc:w-65` - Tablet bilgisayarda genişlik %65
- `.tablet-pc:w-60` - Tablet bilgisayarda genişlik %60
- `.tablet-pc:w-55` - Tablet bilgisayarda genişlik %55
- `.tablet-pc:w-50` - Tablet PC'de genişlik %50
- `.tablet-pc:w-45` - Tablet bilgisayarda genişlik %45
- `.tablet-pc:w-40` - Tablet PC'de genişlik %40
- `.tablet-pc:w-35` - Tablet PC'de genişlik %35
- `.tablet-pc:w-30` - Tablet PC'de genişlik %30
- `.tablet-pc:w-25` - Tablet bilgisayarda genişlik %25
- `.tablet-pc:w-20` - Tablet bilgisayarda genişlik %20
- `.tablet-pc:w-15` - Tablet bilgisayarda genişlik %15
- `.tablet-pc:w-10` - Tablet bilgisayarda genişlik %10
- `.tablet-pc:w-5` - Tablet bilgisayarda genişlik %5
- `.tablet-pc:w-auto` - Tablet PC'de otomatik genişlik %'si

##### Width - Pc (992px - 1200px)

- `.hover:pc:w-100` - PC'de fareyle üzerine gelindiğinde genişlik %100
- `.hover:pc:w-95` - PC'de fareyle üzerine gelindiğinde genişlik %95
- `.hover:pc:w-90` - PC'de fareyle üzerine gelindiğinde genişlik %90
- `.hover:pc:w-85` - PC'de fareyle üzerine gelindiğinde genişlik %85
- `.hover:pc:w-80` - PC'de fareyle üzerine gelindiğinde genişlik %80
- `.hover:pc:w-75` - PC'de fareyle üzerine gelindiğinde genişlik %75
- `.hover:pc:w-70` - PC'de fareyle üzerine gelindiğinde genişlik %70
- `.hover:pc:w-65` - PC'de fareyle üzerine gelindiğinde genişlik %65
- `.hover:pc:w-60` - PC'de fareyle üzerine gelindiğinde genişlik %60
- `.hover:pc:w-55` - PC'de fareyle üzerine gelindiğinde genişlik %55
- `.hover:pc:w-50` - PC'de fareyle üzerine gelindiğinde genişlik %50
- `.hover:pc:w-45` - PC'de fareyle üzerine gelindiğinde genişlik %45
- `.hover:pc:w-40` - PC'de fareyle üzerine gelindiğinde genişlik %40
- `.hover:pc:w-35` - PC'de fareyle üzerine gelindiğinde genişlik %35
- `.hover:pc:w-30` - PC'de fareyle üzerine gelindiğinde genişlik %30
- `.hover:pc:w-25` - PC'de fareyle üzerine gelindiğinde genişlik %25
- `.hover:pc:w-20` - PC'de fareyle üzerine gelindiğinde genişlik %20
- `.hover:pc:w-15` - PC'de fareyle üzerine gelindiğinde genişlik %15
- `.hover:pc:w-10` - PC'de fareyle üzerine gelindiğinde genişlik %10
- `.hover:pc:w-5` - PC'de fareyle üzerine gelindiğinde genişlik %5
- `.hover:pc:w-auto` - PC'de fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.pc:w-100` - PC'de genişlik %100
- `.pc:w-95` - PC'de genişlik %95
- `.pc:w-90` - PC'de genişlik %90
- `.pc:w-85` - PC'de genişlik %85
- `.pc:w-80` - PC'de genişlik %80
- `.pc:w-75` - PC'de genişlik %75
- `.pc:w-70` - PC'de genişlik %70
- `.pc:w-65` - PC'de genişlik %65
- `.pc:w-60` - PC'de genişlik %60
- `.pc:w-55` - PC'de genişlik %55
- `.pc:w-50` - PC'de genişlik %50
- `.pc:w-45` - PC'de genişlik %45
- `.pc:w-40` - PC'de genişlik %40
- `.pc:w-35` - PC'de genişlik %35
- `.pc:w-30` - PC'de genişlik %30
- `.pc:w-25` - PC'de genişlik %25
- `.pc:w-20` - PC'de genişlik %20
- `.pc:w-15` - PC'de genişlik %15
- `.pc:w-10` - PC'de genişlik %10
- `.pc:w-5` - PC'de genişlik %5
- `.pc:w-auto` - PC'de otomatik genişlik %'si

##### Width - Tv (≥ 1200px)

- `.hover:tv:w-100` - TV'de fareyle üzerine gelindiğinde genişlik %100
- `.hover:tv:w-95` - TV'de fareyle üzerine gelindiğinde genişlik %95
- `.hover:tv:w-90` - TV'de fareyle üzerine gelindiğinde genişlik %90
- `.hover:tv:w-85` - TV'de fareyle üzerine gelindiğinde genişlik %85
- `.hover:tv:w-80` - TV'de fareyle üzerine gelindiğinde genişlik %80
- `.hover:tv:w-75` - TV'de fareyle üzerine gelindiğinde genişlik %75
- `.hover:tv:w-70` - TV'de fareyle üzerine gelindiğinde genişlik %70
- `.hover:tv:w-65` - TV'de fareyle üzerine gelindiğinde genişlik %65
- `.hover:tv:w-60` - TV'de fareyle üzerine gelindiğinde genişlik %60
- `.hover:tv:w-55` - TV'de fareyle üzerine gelindiğinde genişlik %55
- `.hover:tv:w-50` - TV'de fareyle üzerine gelindiğinde genişlik %50
- `.hover:tv:w-45` - TV'de fareyle üzerine gelindiğinde genişlik %45
- `.hover:tv:w-40` - TV'de fareyle üzerine gelindiğinde genişlik %40
- `.hover:tv:w-35` - TV'de fareyle üzerine gelindiğinde genişlik %35
- `.hover:tv:w-30` - TV'de fareyle üzerine gelindiğinde genişlik %30
- `.hover:tv:w-25` - TV'de fareyle üzerine gelindiğinde genişlik %25
- `.hover:tv:w-20` - TV'de fareyle üzerine gelindiğinde genişlik %20
- `.hover:tv:w-15` - TV'de fareyle üzerine gelindiğinde genişlik %15
- `.hover:tv:w-10` - TV'de fareyle üzerine gelindiğinde genişlik %10
- `.hover:tv:w-5` - TV'de fareyle üzerine gelindiğinde genişlik %5
- `.hover:tv:w-auto` - TV'de fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.tv:w-100` - TV'de %100 genişlik
- `.tv:w-95` - TV'de genişlik %95
- `.tv:w-90` - TV'de genişlik %90
- `.tv:w-85` - TV'de genişlik %85
- `.tv:w-80` - TV'de genişlik %80
- `.tv:w-75` - TV'de genişlik %75
- `.tv:w-70` - TV'de genişlik %70
- `.tv:w-65` - TV'de genişlik %65
- `.tv:w-60` - TV'de genişlik %60
- `.tv:w-55` - TV'de genişlik %55
- `.tv:w-50` - TV'de genişlik %50
- `.tv:w-45` - TV'de genişlik %45
- `.tv:w-40` - TV'de genişlik %40
- `.tv:w-35` - TV'de genişlik %35
- `.tv:w-30` - TV'de genişlik %30
- `.tv:w-25` - TV'de genişlik %25
- `.tv:w-20` - TV'de genişlik %20
- `.tv:w-15` - TV'de genişlik %15
- `.tv:w-10` - TV'de genişlik %10
- `.tv:w-5` - Televizyonda genişlik %5
- `.tv:w-auto` - TV'de otomatik genişlik %'si

##### Width - Tablet Max (≤ 768px)

- `.hover:tablet-max:w-100` - Maksimum tabletin üzerine gelindiğinde genişlik %100
- `.hover:tablet-max:w-95` - Maksimum tabletin üzerine gelindiğinde genişlik %95
- `.hover:tablet-max:w-90` - Maksimum tabletin üzerine gelindiğinde genişlik %90
- `.hover:tablet-max:w-85` - Maksimum tabletin üzerine gelindiğinde genişlik %85
- `.hover:tablet-max:w-80` - Maksimum tabletin üzerine gelindiğinde genişlik %80
- `.hover:tablet-max:w-75` - Maksimum tabletin üzerine gelindiğinde genişlik %75
- `.hover:tablet-max:w-70` - Maksimum tabletin üzerine gelindiğinde genişlik %70
- `.hover:tablet-max:w-65` - Maksimum tabletin üzerine gelindiğinde genişlik %65
- `.hover:tablet-max:w-60` - Maksimum tabletin üzerine gelindiğinde genişlik %60
- `.hover:tablet-max:w-55` - Maksimum tabletin üzerine gelindiğinde genişlik %55
- `.hover:tablet-max:w-50` - Maksimum tabletin üzerine gelindiğinde genişlik %50
- `.hover:tablet-max:w-45` - Maksimum tabletin üzerine gelindiğinde genişlik %45
- `.hover:tablet-max:w-40` - Maksimum tabletin üzerine gelindiğinde genişlik %40
- `.hover:tablet-max:w-35` - Maksimum tabletin üzerine gelindiğinde genişlik %35
- `.hover:tablet-max:w-30` - Maksimum tabletin üzerine gelindiğinde genişlik %30
- `.hover:tablet-max:w-25` - Maksimum tabletin üzerine gelindiğinde genişlik %25
- `.hover:tablet-max:w-20` - Maksimum tabletin üzerine gelindiğinde genişlik %20
- `.hover:tablet-max:w-15` - Maksimum tabletin üzerine gelindiğinde genişlik %15
- `.hover:tablet-max:w-10` - Maksimum tabletin üzerine gelindiğinde genişlik %10
- `.hover:tablet-max:w-5` - Maksimum tabletin üzerine gelindiğinde genişlik %5
- `.hover:tablet-max:w-auto` - Maksimum tabletin üzerine gelindiğinde otomatik genişlik %'si
- `.tablet-max:w-100` - Maksimum tablette genişlik %100
- `.tablet-max:w-95` - Maksimum tablette %95 genişlik
- `.tablet-max:w-90` - Maksimum tablette genişlik %90
- `.tablet-max:w-85` - Maksimum tablette genişlik %85
- `.tablet-max:w-80` - Maksimum tablette genişlik %80
- `.tablet-max:w-75` - Maksimum tablette genişlik %75
- `.tablet-max:w-70` - Maksimum tablette genişlik %70
- `.tablet-max:w-65` - Maksimum tablette genişlik %65
- `.tablet-max:w-60` - Maksimum tablette genişlik %60
- `.tablet-max:w-55` - Maksimum tablette genişlik %55
- `.tablet-max:w-50` - Maksimum tablette genişlik %50
- `.tablet-max:w-45` - Maksimum tablette genişlik %45
- `.tablet-max:w-40` - Maksimum tablette genişlik %40
- `.tablet-max:w-35` - Maksimum tablette genişlik %35
- `.tablet-max:w-30` - Maksimum tablette genişlik %30
- `.tablet-max:w-25` - Genişlik tablette maksimum %25
- `.tablet-max:w-20` - Tablette maksimum %20 genişlik
- `.tablet-max:w-15` - Maksimum tablette genişlik %15
- `.tablet-max:w-10` - Maksimum tablette %10 genişlik
- `.tablet-max:w-5` - Maksimum tablette %5 genişlik
- `.tablet-max:w-auto` - Maksimum tablette otomatik genişlik yüzdesi

##### Width - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:w-100` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %100
- `.hover:tablet-pc-max:w-95` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde %95 genişlik
- `.hover:tablet-pc-max:w-90` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde %90 genişlik
- `.hover:tablet-pc-max:w-85` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %85
- `.hover:tablet-pc-max:w-80` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %80
- `.hover:tablet-pc-max:w-75` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %75
- `.hover:tablet-pc-max:w-70` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %70
- `.hover:tablet-pc-max:w-65` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %65
- `.hover:tablet-pc-max:w-60` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %60
- `.hover:tablet-pc-max:w-55` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %55
- `.hover:tablet-pc-max:w-50` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %50
- `.hover:tablet-pc-max:w-45` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %45
- `.hover:tablet-pc-max:w-40` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %40
- `.hover:tablet-pc-max:w-35` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %35
- `.hover:tablet-pc-max:w-30` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %30
- `.hover:tablet-pc-max:w-25` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %25
- `.hover:tablet-pc-max:w-20` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %20
- `.hover:tablet-pc-max:w-15` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %15
- `.hover:tablet-pc-max:w-10` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %10
- `.hover:tablet-pc-max:w-5` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde genişlik %5
- `.hover:tablet-pc-max:w-auto` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.tablet-pc-max:w-100` - Tablet PC'de maksimum %100 genişlik
- `.tablet-pc-max:w-95` - Tablet PC'de maksimum %95 genişlik
- `.tablet-pc-max:w-90` - Tablet PC'de maksimum %90 genişlik
- `.tablet-pc-max:w-85` - Tablet PC'de maksimum %85 genişlik
- `.tablet-pc-max:w-80` - Tablet PC'de maksimum %80 genişlik
- `.tablet-pc-max:w-75` - Tablet PC'de maksimum %75 genişlik
- `.tablet-pc-max:w-70` - Tablet PC'de maksimum %70 genişlik
- `.tablet-pc-max:w-65` - Tablet PC'de maksimum %65 genişlik
- `.tablet-pc-max:w-60` - Tablet PC'de maksimum %60 genişlik
- `.tablet-pc-max:w-55` - Tablet PC'de maksimum %55 genişlik
- `.tablet-pc-max:w-50` - Tablet PC'de maksimum %50 genişlik
- `.tablet-pc-max:w-45` - Tablet PC'de maksimum %45 genişlik
- `.tablet-pc-max:w-40` - Tablet PC'de maksimum %40 genişlik
- `.tablet-pc-max:w-35` - Tablet PC'de maksimum %35 genişlik
- `.tablet-pc-max:w-30` - Tablet PC'de maksimum %30 genişlik
- `.tablet-pc-max:w-25` - Tablet PC'de maksimum %25 genişlik
- `.tablet-pc-max:w-20` - Tablet PC'de maksimum %20 genişlik
- `.tablet-pc-max:w-15` - Genişlik tablet bilgisayarda maksimum %15
- `.tablet-pc-max:w-10` - Tablet PC'de maksimum %10 genişlik
- `.tablet-pc-max:w-5` - Tablet PC'de maksimum %5 genişlik
- `.tablet-pc-max:w-auto` - Tablet PC'de maksimum genişlik otomatik %

##### Width - Pc Max (≤ 1200px)

- `.hover:pc-max:w-100` - PC'de fareyle üzerine gelindiğinde genişlik %100 maksimum
- `.hover:pc-max:w-95` - PC'de fareyle üzerine gelindiğinde genişlik %95 maksimum
- `.hover:pc-max:w-90` - PC'de fareyle üzerine gelindiğinde genişlik %90 maksimum
- `.hover:pc-max:w-85` - PC'de fareyle üzerine gelindiğinde genişlik %85 ​​maksimum
- `.hover:pc-max:w-80` - PC'de fareyle üzerine gelindiğinde genişlik %80 maksimum
- `.hover:pc-max:w-75` - PC'de fareyle üzerine gelindiğinde genişlik %75 maksimum
- `.hover:pc-max:w-70` - PC'de fareyle üzerine gelindiğinde genişlik %70 maksimum
- `.hover:pc-max:w-65` - PC'de fareyle üzerine gelindiğinde genişlik %65 maksimum
- `.hover:pc-max:w-60` - PC'de fareyle üzerine gelindiğinde genişlik %60 maksimum
- `.hover:pc-max:w-55` - PC'de fareyle üzerine gelindiğinde genişlik %55 maksimum
- `.hover:pc-max:w-50` - PC'de fareyle üzerine gelindiğinde genişlik %50 maksimum
- `.hover:pc-max:w-45` - Maksimum PC üzerinde fareyle üzerine gelindiğinde genişlik %45
- `.hover:pc-max:w-40` - PC'de fareyle üzerine gelindiğinde genişlik %40 maksimum
- `.hover:pc-max:w-35` - PC'de fareyle üzerine gelindiğinde genişlik %35 maksimum
- `.hover:pc-max:w-30` - PC'de fareyle üzerine gelindiğinde genişlik %30 maksimum
- `.hover:pc-max:w-25` - PC'de fareyle üzerine gelindiğinde genişlik %25 maksimum
- `.hover:pc-max:w-20` - PC'de fareyle üzerine gelindiğinde genişlik %20 maksimum
- `.hover:pc-max:w-15` - PC'de fareyle üzerine gelindiğinde genişlik %15 maksimum
- `.hover:pc-max:w-10` - PC'de fareyle üzerine gelindiğinde genişlik %10 maksimum
- `.hover:pc-max:w-5` - PC'de fareyle üzerine gelindiğinde genişlik %5 maksimum
- `.hover:pc-max:w-auto` - PC max üzerinde fareyle üzerine gelindiğinde otomatik genişlik %'si
- `.pc-max:w-100` - Genişlik PC'de maksimum %100
- `.pc-max:w-95` - Genişlik PC'de maksimum %95
- `.pc-max:w-90` - Genişlik PC'de maksimum %90
- `.pc-max:w-85` - Genişlik PC'de maksimum %85
- `.pc-max:w-80` - Genişlik PC'de maksimum %80
- `.pc-max:w-75` - Genişlik PC'de maksimum %75
- `.pc-max:w-70` - Genişlik PC'de maksimum %70
- `.pc-max:w-65` - Genişlik PC'de maksimum %65
- `.pc-max:w-60` - Genişlik PC'de maksimum %60
- `.pc-max:w-55` - Genişlik PC'de maksimum %55
- `.pc-max:w-50` - Genişlik PC'de maksimum %50
- `.pc-max:w-45` - Genişlik PC'de maksimum %45
- `.pc-max:w-40` - Genişlik PC'de maksimum %40
- `.pc-max:w-35` - Genişlik PC'de maksimum %35
- `.pc-max:w-30` - Genişlik PC'de maksimum %30
- `.pc-max:w-25` - Genişlik PC'de maksimum %25
- `.pc-max:w-20` - Genişlik PC'de maksimum %20
- `.pc-max:w-15` - Genişlik PC'de maksimum %15
- `.pc-max:w-10` - Genişlik PC'de maksimum %10
- `.pc-max:w-5` - Genişlik PC'de maksimum %5
- `.pc-max:w-auto` - PC'de maksimum genişlik otomatik %

#### Width vh

- `.hover:w-vh-100` - Genişlik vh fareyle üzerine gelindiğinde 100vh
- `.hover:w-vh-75` - Genişlik vh fareyle üzerine gelindiğinde 75vh
- `.hover:w-vh-50` - Genişlik vh 50vh fareyle üzerine gelindiğinde
- `.hover:w-vh-25` - Genişlik vh fareyle üzerine gelindiğinde 25vh
- `.w-vh-100` - Genişlik vh 100vh
- `.w-vh-75` - Genişlik vh 75vh
- `.w-vh-50` - Genişlik vh 50vh
- `.w-vh-25` - Genişlik vh 25vh

#### Width vw

- `.hover:w-vw-100` - Vw genişliği 100vw fareyle üzerine gelindiğinde
- `.hover:w-vw-75` - Vw genişliği 75vw fareyle üzerine gelindiğinde
- `.hover:w-vw-50` - Vw genişliği fareyle üzerine gelindiğinde 50vw
- `.hover:w-vw-25` - Vw genişliği fareyle üzerine gelindiğinde 25vw
- `.w-vw-100` - Genişlik vw 100vw
- `.w-vw-75` - Genişlik vw 75vw
- `.w-vw-50` - Genişlik vw 50vw
- `.w-vw-25` - Genişlik vw 25vw

### Height

- `.h-100` - Yükseklik %100
- `.h-95` - Yükseklik %95
- `.h-90` - Yükseklik %90
- `.h-85` - Yükseklik %85
- `.h-80` - Yükseklik %80
- `.h-75` - Yükseklik %75
- `.h-70` - Yükseklik %70
- `.h-65` - Yükseklik %65
- `.h-60` - Yükseklik %60
- `.h-55` - Yükseklik %55
- `.h-50` - Yükseklik %50
- `.h-45` - Yükseklik %45
- `.h-40` - Yükseklik %40
- `.h-35` - Yükseklik %35
- `.h-30` - Yükseklik %30
- `.h-25` - Yükseklik %25
- `.h-20` - Yükseklik %20
- `.h-15` - Yükseklik %15
- `.h-10` - Yükseklik %10
- `.h-5` - Yükseklik %5
- `.h-auto` - Yükseklik otomatik%
- `.hover:h-100` - Fareyle üzerine gelindiğinde yükseklik %100
- `.hover:h-95` - Fareyle üzerine gelindiğinde yükseklik %95
- `.hover:h-90` - Fareyle üzerine gelindiğinde yükseklik %90
- `.hover:h-85` - Fareyle üzerine gelindiğinde yükseklik %85
- `.hover:h-80` - Fareyle üzerine gelindiğinde yükseklik %80
- `.hover:h-75` - Fareyle üzerine gelindiğinde yükseklik %75
- `.hover:h-70` - Fareyle üzerine gelindiğinde yükseklik %70
- `.hover:h-65` - Fareyle üzerine gelindiğinde yükseklik %65
- `.hover:h-60` - Fareyle üzerine gelindiğinde yükseklik %60
- `.hover:h-55` - Fareyle üzerine gelindiğinde yükseklik %55
- `.hover:h-50` - Fareyle üzerine gelindiğinde yükseklik %50
- `.hover:h-45` - Fareyle üzerine gelindiğinde yükseklik %45
- `.hover:h-40` - Fareyle üzerine gelindiğinde yükseklik %40
- `.hover:h-35` - Fareyle üzerine gelindiğinde yükseklik %35
- `.hover:h-30` - Fareyle üzerine gelindiğinde yükseklik %30
- `.hover:h-25` - Fareyle üzerine gelindiğinde yükseklik %25
- `.hover:h-20` - Fareyle üzerine gelindiğinde yükseklik %20
- `.hover:h-15` - Fareyle üzerine gelindiğinde yükseklik %15
- `.hover:h-10` - Fareyle üzerine gelindiğinde yükseklik %10
- `.hover:h-5` - Fareyle üzerine gelindiğinde yükseklik %5
- `.hover:h-auto` - Fareyle üzerine gelindiğinde otomatik yükseklik %'si

##### Height - Mobile (≤ 480px)

- `.hover:mobile:h-100` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %100
- `.hover:mobile:h-95` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %95
- `.hover:mobile:h-90` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %90
- `.hover:mobile:h-85` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %85
- `.hover:mobile:h-80` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %80
- `.hover:mobile:h-75` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %75
- `.hover:mobile:h-70` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %70
- `.hover:mobile:h-65` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %65
- `.hover:mobile:h-60` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %60
- `.hover:mobile:h-55` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %55
- `.hover:mobile:h-50` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %50
- `.hover:mobile:h-45` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %45
- `.hover:mobile:h-40` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %40
- `.hover:mobile:h-35` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %35
- `.hover:mobile:h-30` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %30
- `.hover:mobile:h-25` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %25
- `.hover:mobile:h-20` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %20
- `.hover:mobile:h-15` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %15
- `.hover:mobile:h-10` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %10
- `.hover:mobile:h-5` - Mobil cihazda fareyle üzerine gelindiğinde yükseklik %5
- `.hover:mobile:h-auto` - Mobil cihazda fareyle üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.mobile:h-100` - Mobil cihazlarda yükseklik %100
- `.mobile:h-95` - Mobil cihazda yükseklik %95
- `.mobile:h-90` - Mobil cihazda yükseklik %90
- `.mobile:h-85` - Mobil cihazda yükseklik %85
- `.mobile:h-80` - Mobil cihazda yükseklik %80
- `.mobile:h-75` - Mobil cihazda yükseklik %75
- `.mobile:h-70` - Mobil cihazda yükseklik %70
- `.mobile:h-65` - Mobil cihazda yükseklik %65
- `.mobile:h-60` - Mobil cihazda yükseklik %60
- `.mobile:h-55` - Mobil cihazda yükseklik %55
- `.mobile:h-50` - Mobil cihazda yükseklik %50
- `.mobile:h-45` - Mobil cihazda yükseklik %45
- `.mobile:h-40` - Mobil cihazda yükseklik %40
- `.mobile:h-35` - Mobil cihazda yükseklik %35
- `.mobile:h-30` - Mobil cihazda yükseklik %30
- `.mobile:h-25` - Mobil cihazda yükseklik %25
- `.mobile:h-20` - Mobil cihazda yükseklik %20
- `.mobile:h-15` - Mobil cihazda yükseklik %15
- `.mobile:h-10` - Mobil cihazda yükseklik %10
- `.mobile:h-5` - Mobil cihazda yükseklik %5
- `.mobile:h-auto` - Mobil cihazda otomatik yükseklik yüzdesi

##### Height - Tablet (480px - 768px)

- `.hover:tablet:h-100` - Tabletin üzerine gelindiğinde yükseklik %100
- `.hover:tablet:h-95` - Tabletin üzerine gelindiğinde yükseklik %95
- `.hover:tablet:h-90` - Tabletin üzerine gelindiğinde yükseklik %90
- `.hover:tablet:h-85` - Tabletin üzerine gelindiğinde yükseklik %85
- `.hover:tablet:h-80` - Tabletin üzerine gelindiğinde yükseklik %80
- `.hover:tablet:h-75` - Tabletin üzerine gelindiğinde yükseklik %75
- `.hover:tablet:h-70` - Tabletin üzerine gelindiğinde yükseklik %70
- `.hover:tablet:h-65` - Tabletin üzerine gelindiğinde yükseklik %65
- `.hover:tablet:h-60` - Tabletin üzerine gelindiğinde yükseklik %60
- `.hover:tablet:h-55` - Tabletin üzerine gelindiğinde yükseklik %55
- `.hover:tablet:h-50` - Tabletin üzerine gelindiğinde yükseklik %50
- `.hover:tablet:h-45` - Tabletin üzerine gelindiğinde yükseklik %45
- `.hover:tablet:h-40` - Tabletin üzerine gelindiğinde yükseklik %40
- `.hover:tablet:h-35` - Tabletin üzerine gelindiğinde yükseklik %35
- `.hover:tablet:h-30` - Tabletin üzerine gelindiğinde yükseklik %30
- `.hover:tablet:h-25` - Tabletin üzerine gelindiğinde yükseklik %25
- `.hover:tablet:h-20` - Tabletin üzerine gelindiğinde yükseklik %20
- `.hover:tablet:h-15` - Tabletin üzerine gelindiğinde yükseklik %15
- `.hover:tablet:h-10` - Tabletin üzerine gelindiğinde yükseklik %10
- `.hover:tablet:h-5` - Tabletin üzerine gelindiğinde yükseklik %5
- `.hover:tablet:h-auto` - Tablette fareyle üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.tablet:h-100` - Tablette yükseklik %100
- `.tablet:h-95` - Tablette yükseklik %95
- `.tablet:h-90` - Tablette yükseklik %90
- `.tablet:h-85` - Tablette yükseklik %85
- `.tablet:h-80` - Tablette yükseklik %80
- `.tablet:h-75` - Tablette yükseklik %75
- `.tablet:h-70` - Tablette yükseklik %70
- `.tablet:h-65` - Tablette yükseklik %65
- `.tablet:h-60` - Tablette yükseklik %60
- `.tablet:h-55` - Tablette yükseklik %55
- `.tablet:h-50` - Tablette yükseklik %50
- `.tablet:h-45` - Tablette yükseklik %45
- `.tablet:h-40` - Tablette yükseklik %40
- `.tablet:h-35` - Tablette yükseklik %35
- `.tablet:h-30` - Tablette yükseklik %30
- `.tablet:h-25` - Tablette yükseklik %25
- `.tablet:h-20` - Tablette yükseklik %20
- `.tablet:h-15` - Tablette yükseklik %15
- `.tablet:h-10` - Tablette yükseklik %10
- `.tablet:h-5` - Tablette yükseklik %5
- `.tablet:h-auto` - Tablette otomatik yükseklik yüzdesi

##### Height - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:h-100` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %100
- `.hover:tablet-pc:h-95` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %95
- `.hover:tablet-pc:h-90` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %90
- `.hover:tablet-pc:h-85` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %85
- `.hover:tablet-pc:h-75` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %75
- `.hover:tablet-pc:h-70` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %70
- `.hover:tablet-pc:h-65` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %65
- `.hover:tablet-pc:h-60` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %60
- `.hover:tablet-pc:h-55` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %55
- `.hover:tablet-pc:h-50` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %50
- `.hover:tablet-pc:h-45` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %45
- `.hover:tablet-pc:h-40` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %40
- `.hover:tablet-pc:h-35` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %35
- `.hover:tablet-pc:h-30` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %30
- `.hover:tablet-pc:h-25` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %25
- `.hover:tablet-pc:h-20` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %20
- `.hover:tablet-pc:h-15` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %15
- `.hover:tablet-pc:h-10` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %10
- `.hover:tablet-pc:h-5` - Tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %5
- `.hover:tablet-pc:h-auto` - Tablet bilgisayarda fareyle üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.tablet-pc:h-100` - Tablet bilgisayarda yükseklik %100
- `.tablet-pc:h-95` - Tablet bilgisayarda yükseklik %95
- `.tablet-pc:h-90` - Tablet bilgisayarda yükseklik %90
- `.tablet-pc:h-85` - Tablet bilgisayarda yükseklik %85
- `.tablet-pc:h-80` - Tablet bilgisayarda yükseklik %80
- `.tablet-pc:h-75` - Tablet bilgisayarda yükseklik %75
- `.tablet-pc:h-70` - Tablet bilgisayarda yükseklik %70
- `.tablet-pc:h-65` - Tablet bilgisayarda yükseklik %65
- `.tablet-pc:h-60` - Tablet bilgisayarda yükseklik %60
- `.tablet-pc:h-55` - Tablet bilgisayarda yükseklik %55
- `.tablet-pc:h-50` - Tablet bilgisayarda yükseklik %50
- `.tablet-pc:h-45` - Tablet bilgisayarda yükseklik %45
- `.tablet-pc:h-40` - Tablet bilgisayarda yükseklik %40
- `.tablet-pc:h-35` - Tablet bilgisayarda yükseklik %35
- `.tablet-pc:h-30` - Tablet bilgisayarda yükseklik %30
- `.tablet-pc:h-25` - Tablet bilgisayarda yükseklik %25
- `.tablet-pc:h-20` - Tablet bilgisayarda yükseklik %20
- `.tablet-pc:h-15` - Tablet bilgisayarda yükseklik %15
- `.tablet-pc:h-10` - Tablet bilgisayarda yükseklik %10
- `.tablet-pc:h-5` - Tablet bilgisayarda yükseklik %5
- `.tablet-pc:h-auto` - Tablet PC'de otomatik yükseklik yüzdesi

##### Height - Pc (992px - 1200px)

- `.hover:pc:h-100` - PC'de fareyle üzerine gelindiğinde yükseklik %100
- `.hover:pc:h-95` - PC'de fareyle üzerine gelindiğinde yükseklik %95
- `.hover:pc:h-90` - PC'de fareyle üzerine gelindiğinde yükseklik %90
- `.hover:pc:h-85` - PC'de fareyle üzerine gelindiğinde yükseklik %85
- `.hover:pc:h-80` - PC'de fareyle üzerine gelindiğinde yükseklik %80
- `.hover:pc:h-75` - PC'de fareyle üzerine gelindiğinde yükseklik %75
- `.hover:pc:h-70` - PC'de fareyle üzerine gelindiğinde yükseklik %70
- `.hover:pc:h-65` - PC'de fareyle üzerine gelindiğinde yükseklik %65
- `.hover:pc:h-60` - PC'de fareyle üzerine gelindiğinde yükseklik %60
- `.hover:pc:h-55` - PC'de fareyle üzerine gelindiğinde yükseklik %55
- `.hover:pc:h-50` - PC'de fareyle üzerine gelindiğinde yükseklik %50
- `.hover:pc:h-45` - PC'de fareyle üzerine gelindiğinde yükseklik %45
- `.hover:pc:h-40` - PC'de fareyle üzerine gelindiğinde yükseklik %40
- `.hover:pc:h-35` - PC'de fareyle üzerine gelindiğinde yükseklik %35
- `.hover:pc:h-30` - PC'de fareyle üzerine gelindiğinde yükseklik %30
- `.hover:pc:h-25` - PC'de fareyle üzerine gelindiğinde yükseklik %25
- `.hover:pc:h-20` - PC'de fareyle üzerine gelindiğinde yükseklik %20
- `.hover:pc:h-15` - PC'de fareyle üzerine gelindiğinde yükseklik %15
- `.hover:pc:h-10` - PC'de fareyle üzerine gelindiğinde yükseklik %10
- `.hover:pc:h-5` - PC'de fareyle üzerine gelindiğinde yükseklik %5
- `.hover:pc:h-auto` - PC'de fareyle üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.pc:h-100` - PC'de yükseklik %100
- `.pc:h-95` - PC'de yükseklik %95
- `.pc:h-90` - PC'de yükseklik %90
- `.pc:h-85` - PC'de yükseklik %85
- `.pc:h-80` - PC'de yükseklik %80
- `.pc:h-75` - PC'de yükseklik %75
- `.pc:h-70` - PC'de yükseklik %70
- `.pc:h-65` - PC'de yükseklik %65
- `.pc:h-60` - PC'de yükseklik %60
- `.pc:h-55` - PC'de yükseklik %55
- `.pc:h-50` - PC'de yükseklik %50
- `.pc:h-45` - Yükseklik PC'de %45
- `.pc:h-40` - PC'de yükseklik %40
- `.pc:h-35` - Yükseklik PC'de %35
- `.pc:h-30` - PC'de yükseklik %30
- `.pc:h-25` - PC'de yükseklik %25
- `.pc:h-20` - PC'de yükseklik %20
- `.pc:h-15` - PC'de yükseklik %15
- `.pc:h-10` - PC'de yükseklik %10
- `.pc:h-5` - PC'de yükseklik %5
- `.pc:h-auto` - PC'de otomatik yükseklik yüzdesi

##### Height - Tv (≥ 1200px)

- `.hover:tv:h-100` - TV'de fareyle üzerine gelindiğinde yükseklik %100
- `.hover:tv:h-95` - TV'de fareyle üzerine gelindiğinde yükseklik %95
- `.hover:tv:h-90` - TV'de fareyle üzerine gelindiğinde yükseklik %90
- `.hover:tv:h-85` - TV'de fareyle üzerine gelindiğinde yükseklik %85
- `.hover:tv:h-80` - TV'de fareyle üzerine gelindiğinde yükseklik %80
- `.hover:tv:h-75` - TV'de fareyle üzerine gelindiğinde yükseklik %75
- `.hover:tv:h-70` - TV'de fareyle üzerine gelindiğinde yükseklik %70
- `.hover:tv:h-65` - TV'de fareyle üzerine gelindiğinde yükseklik %65
- `.hover:tv:h-60` - TV'de fareyle üzerine gelindiğinde yükseklik %60
- `.hover:tv:h-55` - TV'de fareyle üzerine gelindiğinde yükseklik %55
- `.hover:tv:h-50` - TV'de fareyle üzerine gelindiğinde yükseklik %50
- `.hover:tv:h-45` - TV'de fareyle üzerine gelindiğinde yükseklik %45
- `.hover:tv:h-40` - TV'de fareyle üzerine gelindiğinde yükseklik %40
- `.hover:tv:h-35` - TV'de fareyle üzerine gelindiğinde yükseklik %35
- `.hover:tv:h-30` - TV'de fareyle üzerine gelindiğinde yükseklik %30
- `.hover:tv:h-25` - TV'de fareyle üzerine gelindiğinde yükseklik %25
- `.hover:tv:h-20` - TV'de fareyle üzerine gelindiğinde yükseklik %20
- `.hover:tv:h-15` - TV'de fareyle üzerine gelindiğinde yükseklik %15
- `.hover:tv:h-10` - TV'de fareyle üzerine gelindiğinde yükseklik %10
- `.hover:tv:h-5` - TV'de fareyle üzerine gelindiğinde yükseklik %5
- `.hover:tv:h-auto` - TV'de fareyle üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.tv:h-100` - Televizyonda yükseklik %100
- `.tv:h-95` - Televizyonda yükseklik %95
- `.tv:h-90` - Televizyonda yükseklik %90
- `.tv:h-85` - Televizyonda yükseklik %85
- `.tv:h-80` - Yükseklik TV'de %80
- `.tv:h-75` - Televizyonda yükseklik %75
- `.tv:h-70` - Yükseklik TV'de %70
- `.tv:h-65` - Televizyonda yükseklik %65
- `.tv:h-60` - Televizyonda boy %60
- `.tv:h-55` - Televizyonda yükseklik %55
- `.tv:h-50` - Televizyonda yükseklik %50
- `.tv:h-45` - Televizyonda yükseklik %45
- `.tv:h-40` - Televizyonda yükseklik %40
- `.tv:h-35` - Televizyonda yükseklik %35
- `.tv:h-30` - Televizyonda yükseklik %30
- `.tv:h-25` - Televizyonda yükseklik %25
- `.tv:h-20` - Televizyonda yükseklik %20
- `.tv:h-15` - Televizyonda yükseklik %15
- `.tv:h-10` - Televizyonda yükseklik %10
- `.tv:h-5` - Televizyonda yükseklik %5
- `.tv:h-auto` - TV'de otomatik yükseklik %'si

##### Height - Tablet Max (≤ 768px)

- `.hover:tablet-max:h-100` - Maksimum tabletin üzerine gelindiğinde yükseklik %100
- `.hover:tablet-max:h-95` - Maksimum tabletin üzerine gelindiğinde yükseklik %95
- `.hover:tablet-max:h-90` - Maksimum tabletin üzerine gelindiğinde yükseklik %90
- `.hover:tablet-max:h-85` - Maksimum tabletin üzerine gelindiğinde yükseklik %85
- `.hover:tablet-max:h-80` - Maksimum tabletin üzerine gelindiğinde yükseklik %80
- `.hover:tablet-max:h-75` - Maksimum tabletin üzerine gelindiğinde yükseklik %75
- `.hover:tablet-max:h-70` - Maksimum tabletin üzerine gelindiğinde yükseklik %70
- `.hover:tablet-max:h-65` - Maksimum tabletin üzerine gelindiğinde yükseklik %65
- `.hover:tablet-max:h-60` - Maksimum tabletin üzerine gelindiğinde yükseklik %60
- `.hover:tablet-max:h-55` - Maksimum tabletin üzerine gelindiğinde yükseklik %55
- `.hover:tablet-max:h-50` - Maksimum tabletin üzerine gelindiğinde yükseklik %50
- `.hover:tablet-max:h-45` - Maksimum tabletin üzerine gelindiğinde yükseklik %45
- `.hover:tablet-max:h-40` - Maksimum tabletin üzerine gelindiğinde yükseklik %40
- `.hover:tablet-max:h-35` - Maksimum tabletin üzerine gelindiğinde yükseklik %35
- `.hover:tablet-max:h-30` - Maksimum tabletin üzerine gelindiğinde yükseklik %30
- `.hover:tablet-max:h-25` - Maksimum tabletin üzerine gelindiğinde yükseklik %25
- `.hover:tablet-max:h-20` - Maksimum tabletin üzerine gelindiğinde yükseklik %20
- `.hover:tablet-max:h-15` - Maksimum tabletin üzerine gelindiğinde yükseklik %15
- `.hover:tablet-max:h-10` - Maksimum tabletin üzerine gelindiğinde yükseklik %10
- `.hover:tablet-max:h-5` - Maksimum tabletin üzerine gelindiğinde yükseklik %5
- `.hover:tablet-max:h-auto` - Maksimum tabletin üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.tablet-max:h-100` - Tablette yükseklik maksimum %100
- `.tablet-max:h-95` - Maksimum tablette yükseklik %95
- `.tablet-max:h-90` - Maksimum tablette yükseklik %90
- `.tablet-max:h-85` - Maksimum tablette yükseklik %85
- `.tablet-max:h-80` - Maksimum tablette yükseklik %80
- `.tablet-max:h-75` - Maksimum tablette yükseklik %75
- `.tablet-max:h-70` - Tablette yükseklik maksimum %70
- `.tablet-max:h-65` - Maksimum tablette yükseklik %65
- `.tablet-max:h-60` - Maksimum tablette yükseklik %60
- `.tablet-max:h-55` - Maksimum tablette yükseklik %55
- `.tablet-max:h-50` - Tablette yükseklik maksimum %50
- `.tablet-max:h-45` - Tablette yükseklik maksimum %45
- `.tablet-max:h-40` - Tablette yükseklik maksimum %40
- `.tablet-max:h-35` - Maksimum tablette yükseklik %35
- `.tablet-max:h-30` - Maksimum tablette yükseklik %30
- `.tablet-max:h-25` - Tablette yükseklik maksimum %25
- `.tablet-max:h-20` - Tablette yükseklik maksimum %20
- `.tablet-max:h-15` - Maksimum tablette yükseklik %15
- `.tablet-max:h-10` - Tablette yükseklik maksimum %10
- `.tablet-max:h-5` - Tablette yükseklik maksimum %5
- `.tablet-max:h-auto` - Maksimum tablette otomatik yükseklik yüzdesi

##### Height - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:h-100` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %100
- `.hover:tablet-pc-max:h-95` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %95
- `.hover:tablet-pc-max:h-90` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %90
- `.hover:tablet-pc-max:h-85` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %85
- `.hover:tablet-pc-max:h-80` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %80
- `.hover:tablet-pc-max:h-75` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %75
- `.hover:tablet-pc-max:h-70` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %70
- `.hover:tablet-pc-max:h-65` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %65
- `.hover:tablet-pc-max:h-60` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %60
- `.hover:tablet-pc-max:h-55` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %55
- `.hover:tablet-pc-max:h-50` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %50
- `.hover:tablet-pc-max:h-45` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %45
- `.hover:tablet-pc-max:h-40` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %40
- `.hover:tablet-pc-max:h-35` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %35
- `.hover:tablet-pc-max:h-30` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %30
- `.hover:tablet-pc-max:h-25` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %25
- `.hover:tablet-pc-max:h-20` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %20
- `.hover:tablet-pc-max:h-15` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %15
- `.hover:tablet-pc-max:h-10` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %10
- `.hover:tablet-pc-max:h-5` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde yükseklik %5
- `.hover:tablet-pc-max:h-auto` - Maksimum tablet bilgisayarda fareyle üzerine gelindiğinde otomatik yükseklik yüzdesi
- `.tablet-pc-max:h-100` - Tablet PC'de maksimum yükseklik %100
- `.tablet-pc-max:h-95` - Tablet PC'de maksimum yükseklik %95
- `.tablet-pc-max:h-90` - Tablet PC'de maksimum yükseklik %90
- `.tablet-pc-max:h-85` - Tablet PC'de maksimum yükseklik %85
- `.tablet-pc-max:h-80` - Tablet PC'de maksimum yükseklik %80
- `.tablet-pc-max:h-75` - Tablet PC'de maksimum yükseklik %75
- `.tablet-pc-max:h-70` - Tablet PC'de maksimum yükseklik %70
- `.tablet-pc-max:h-65` - Tablet PC'de maksimum yükseklik %65
- `.tablet-pc-max:h-60` - Tablet PC'de maksimum yükseklik %60
- `.tablet-pc-max:h-55` - Tablet PC'de maksimum yükseklik %55
- `.tablet-pc-max:h-50` - Tablet PC'de maksimum yükseklik %50
- `.tablet-pc-max:h-45` - Tablet PC'de maksimum yükseklik %45
- `.tablet-pc-max:h-40` - Tablet PC'de maksimum yükseklik %40
- `.tablet-pc-max:h-35` - Tablet PC'de maksimum yükseklik %35
- `.tablet-pc-max:h-30` - Tablet PC'de maksimum yükseklik %30
- `.tablet-pc-max:h-25` - Tablet PC'de maksimum yükseklik %25
- `.tablet-pc-max:h-20` - Tablet PC'de maksimum yükseklik %20
- `.tablet-pc-max:h-15` - Tablet PC'de maksimum yükseklik %15
- `.tablet-pc-max:h-10` - Tablet PC'de maksimum yükseklik %10
- `.tablet-pc-max:h-5` - Tablet PC'de maksimum yükseklik %5
- `.tablet-pc-max:h-auto` - Tablet PC'de maksimum yükseklik otomatik %

##### Height - Pc Max (≤ 1200px)

- `.hover:pc-max:h-100` - PC'de fareyle üzerine gelindiğinde yükseklik %100 maksimum
- `.hover:pc-max:h-95` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %95
- `.hover:pc-max:h-90` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %90
- `.hover:pc-max:h-85` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %85
- `.hover:pc-max:h-80` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %80
- `.hover:pc-max:h-75` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %75
- `.hover:pc-max:h-70` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %70
- `.hover:pc-max:h-65` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %65
- `.hover:pc-max:h-60` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %60
- `.hover:pc-max:h-55` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %55
- `.hover:pc-max:h-50` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %50
- `.hover:pc-max:h-45` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %45
- `.hover:pc-max:h-40` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %40
- `.hover:pc-max:h-35` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %35
- `.hover:pc-max:h-30` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %30
- `.hover:pc-max:h-25` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %25
- `.hover:pc-max:h-20` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %20
- `.hover:pc-max:h-15` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %15
- `.hover:pc-max:h-10` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %10
- `.hover:pc-max:h-5` - Maksimum PC üzerinde fareyle üzerine gelindiğinde yükseklik %5
- `.hover:pc-max:h-auto` - Maksimum bilgisayar üzerinde fareyle üzerine gelindiğinde otomatik yükseklik %'si
- `.pc-max:h-100` - Yükseklik PC'de maksimum %100
- `.pc-max:h-95` - Yükseklik PC'de maksimum %95
- `.pc-max:h-90` - Yükseklik PC'de maksimum %90
- `.pc-max:h-85` - Yükseklik PC'de maksimum %85
- `.pc-max:h-80` - Yükseklik PC'de maksimum %80
- `.pc-max:h-75` - Yükseklik PC'de maksimum %75
- `.pc-max:h-70` - Yükseklik PC'de maksimum %70
- `.pc-max:h-65` - Yükseklik PC'de maksimum %65
- `.pc-max:h-60` - Yükseklik PC'de maksimum %60
- `.pc-max:h-55` - Yükseklik PC'de maksimum %55
- `.pc-max:h-50` - Yükseklik PC'de maksimum %50
- `.pc-max:h-45` - Yükseklik PC'de maksimum %45
- `.pc-max:h-40` - Yükseklik PC'de maksimum %40
- `.pc-max:h-35` - Yükseklik PC'de maksimum %35
- `.pc-max:h-30` - Yükseklik PC'de maksimum %30
- `.pc-max:h-25` - Yükseklik PC'de maksimum %25
- `.pc-max:h-20` - Yükseklik PC'de maksimum %20
- `.pc-max:h-15` - Yükseklik PC'de maksimum %15
- `.pc-max:h-10` - Yükseklik PC'de maksimum %10
- `.pc-max:h-5` - Yükseklik PC'de maksimum %5
- `.pc-max:h-auto` - PC'de maksimum yükseklik otomatik %

#### Height vh

- `.h-vh-100` - Yükseklik vh 100vh
- `.h-vh-75` - Yükseklik vh 75vh
- `.h-vh-50` - Yükseklik vh 50vh
- `.h-vh-25` - Yükseklik vh 25vh
- `.hover:h-vh-100` - Fareyle üzerine gelindiğinde yükseklik vh 100vh
- `.hover:h-vh-75` - Yükseklik vh 75vh fareyle üzerine gelindiğinde
- `.hover:h-vh-50` - Fareyle üzerine gelindiğinde yükseklik vh 50vh
- `.hover:h-vh-25` - Yükseklik vh 25vh fareyle üzerine gelindiğinde

#### Height vw

- `.h-vw-100` - Yükseklik vw 100vw
- `.h-vw-75` - Yükseklik vw 75vw
- `.h-vw-50` - Yükseklik vw 50vw
- `.h-vw-25` - Yükseklik vw 25vw
- `.hover:h-vw-100` - Vw'nin yüksekliği fareyle üzerine gelindiğinde 100vw
- `.hover:h-vw-75` - Yükseklik vw 75vw fareyle üzerine gelindiğinde
- `.hover:h-vw-50` - Vw'nin yüksekliği fareyle üzerine gelindiğinde 50vw
- `.hover:h-vw-25` - Yükseklik vw 25vw fareyle üzerine gelindiğinde

## Positioning

### Static

- `.hover:static` - Fareyle üzerine gelindiğinde statik
- `.static` - Statik

### Relative

- `.hover:relative` - Fareyle üzerine gelindiğinde göreceli
- `.relative` - Akraba

### Absolute

- `.absolute` - Mutlak
- `.hover:absolute` - Fareyle üzerine gelindiğinde mutlak

### Fixed

- `.fixed` - Sabit
- `.hover:fixed` - Fareyle üzerine gelindiğinde sabitlendi

### Sticky

- `.hover:sticky` - Fareyle üzerine gelindiğinde yapışkan
- `.sticky` - Yapışkan

### Top

- `.hover:top-100` - Fareyle üzerine gelindiğinde ilk %100
- `.hover:top-75` - Fareyle üzerine gelindiğinde ilk %75
- `.hover:top-50` - Fareyle üzerine gelindiğinde ilk %50
- `.hover:top-25` - Fareyle üzerine gelindiğinde ilk %25
- `.hover:top-5` - Fareyle üzerine gelindiğinde ilk 5rem
- `.hover:top-4.5` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-4` - Fareyle üzerine gelindiğinde ilk 4rem
- `.hover:top-3.5` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-3` - Fareyle üzerine gelindiğinde ilk 3rem
- `.hover:top-2.5` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-2` - Fareyle üzerine gelindiğinde ilk 2rem
- `.hover:top-1.9` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.8` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.7` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.6` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.5` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.4` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.3` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.2` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1.1` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-1` - Fareyle üzerine gelindiğinde ilk 1rem
- `.hover:top-0.9` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.8` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.7` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.6` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.5` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.4` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.3` - Fareyle üzerine gelindiğinde ilk 0rem
- `.hover:top-0.2` - Fareyle üzerine gelindiğinde en iyi 0,2rem
- `.hover:top-0.1` - Fareyle üzerine gelindiğinde ilk 0,1rem
- `.hover:top-0` - Fareyle üzerine gelindiğinde ilk 0rem
- `.top-100` - En iyi %100
- `.top-75` - En iyi %75
- `.top-50` - En iyi %50
- `.top-25` - En iyi %25
- `.top-5` - İlk 5rem
- `.top-4.5` - En iyi 0rem
- `.top-4` - En iyi 4rem
- `.top-3.5` - En iyi 0rem
- `.top-3` - İlk 3rem
- `.top-2.5` - En iyi 0rem
- `.top-2` - En iyi 2rem
- `.top-1.9` - En iyi 0rem
- `.top-1.8` - En iyi 0rem
- `.top-1.7` - En iyi 0rem
- `.top-1.6` - En iyi 0rem
- `.top-1.5` - En iyi 0rem
- `.top-1.4` - En iyi 0rem
- `.top-1.3` - En iyi 0rem
- `.top-1.2` - En iyi 0rem
- `.top-1.1` - En iyi 0rem
- `.top-1` - İlk 1rem
- `.top-0.9` - En iyi 0rem
- `.top-0.8` - En iyi 0rem
- `.top-0.7` - En iyi 0rem
- `.top-0.6` - En iyi 0rem
- `.top-0.5` - En iyi 0rem
- `.top-0.4` - En iyi 0rem
- `.top-0.3` - En iyi 0rem
- `.top-0.2` - En iyi 0,2rem
- `.top-0.1` - En iyi 0,1rem
- `.top-0` - En iyi 0rem

##### Negative Top

- `.-top-5` - Negatif İlk 5rem
- `.-top-4.5` - Negatif Üst ​​0rem
- `.-top-4` - Negatif Üst ​​4rem
- `.-top-3.5` - Negatif Üst ​​0rem
- `.-top-3` - Negatif Üst ​​3rem
- `.-top-2.5` - Negatif Üst ​​0rem
- `.-top-2` - Negatif Üst ​​2rem
- `.-top-1.9` - Negatif Üst ​​0rem
- `.-top-1.8` - Negatif Üst ​​0rem
- `.-top-1.7` - Negatif Üst ​​0rem
- `.-top-1.6` - Negatif Üst ​​0rem
- `.-top-1.5` - Negatif Üst ​​0rem
- `.-top-1.4` - Negatif Üst ​​0rem
- `.-top-1.3` - Negatif Üst ​​0rem
- `.-top-1.2` - Negatif Üst ​​0rem
- `.-top-1.1` - Negatif Üst ​​0rem
- `.-top-1` - Negatif Üst ​​1rem
- `.-top-0.9` - Negatif Üst ​​0rem
- `.-top-0.8` - Negatif Üst ​​0rem
- `.-top-0.7` - Negatif Üst ​​0rem
- `.-top-0.6` - Negatif Üst ​​0rem
- `.-top-0.5` - Negatif Üst ​​0rem
- `.-top-0.4` - Negatif Üst ​​0rem
- `.-top-0.3` - Negatif Üst ​​0,3rem
- `.-top-0.2` - Negatif Üst ​​0,2rem
- `.-top-0.1` - Negatif Üst ​​0,1 rem
- `.hover:-top-5` - Fareyle üzerine gelindiğinde Negatif İlk 5rem
- `.hover:-top-4.5` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-4` - Negatif Üst ​​4rem fareyle üzerine gelindiğinde
- `.hover:-top-3.5` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-3` - Fareyle üzerine gelindiğinde Negatif İlk 3rem
- `.hover:-top-2.5` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-2` - Negatif Üst ​​2rem fareyle üzerine gelindiğinde
- `.hover:-top-1.9` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.8` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.7` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.6` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.5` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.4` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.3` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.2` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1.1` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-1` - Negatif Üst ​​1rem fareyle üzerine gelindiğinde
- `.hover:-top-0.9` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-0.8` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-0.7` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-0.6` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-0.5` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-0.4` - Fareyle üzerine gelindiğinde Negatif Üst ​​0rem
- `.hover:-top-0.3` - Negatif Üst ​​0,3rem fareyle üzerine gelindiğinde
- `.hover:-top-0.2` - Negatif Üst ​​0,2rem fareyle üzerine gelindiğinde
- `.hover:-top-0.1` - Negatif Üst ​​0,1rem fareyle üzerine gelindiğinde

### Right

- `.hover:right-100` - Fareyle üzerine gelindiğinde sağa %100
- `.hover:right-75` - Fareyle üzerine gelindiğinde sağa %75
- `.hover:right-50` - Vurguluyken sağa %50
- `.hover:right-25` - Fareyle üzerine gelindiğinde sağa %25
- `.hover:right-5` - Vurguluyken sağa 5rem
- `.hover:right-4.5` - Vurguluyken sağa 0rem
- `.hover:right-4` - Fareyle üzerine gelindiğinde sağa 4rem
- `.hover:right-3.5` - Vurguluyken sağa 0rem
- `.hover:right-3` - Fareyle üzerine gelindiğinde sağa 3rem
- `.hover:right-2.5` - Vurguluyken sağa 0rem
- `.hover:right-2` - Fareyle üzerine gelindiğinde sağa 2rem
- `.hover:right-1.9` - Vurguluyken sağa 0rem
- `.hover:right-1.8` - Vurguluyken sağa 0rem
- `.hover:right-1.7` - Vurguluyken sağa 0rem
- `.hover:right-1.6` - Vurguluyken sağa 0rem
- `.hover:right-1.5` - Vurguluyken sağa 0rem
- `.hover:right-1.4` - Vurguluyken sağa 0rem
- `.hover:right-1.3` - Vurguluyken sağa 0rem
- `.hover:right-1.2` - Vurguluyken sağa 0rem
- `.hover:right-1.1` - Vurguluyken sağa 0rem
- `.hover:right-1` - Vurguluyken sağa 1rem
- `.hover:right-0.9` - Vurguluyken sağa 0rem
- `.hover:right-0.8` - Vurguluyken sağa 0rem
- `.hover:right-0.7` - Vurguluyken sağa 0rem
- `.hover:right-0.6` - Vurguluyken sağa 0rem
- `.hover:right-0.5` - Vurguluyken sağa 0rem
- `.hover:right-0.4` - Vurguluyken sağa 0rem
- `.hover:right-0.3` - Vurguluyken sağa 0rem
- `.hover:right-0.2` - Fareyle üzerine gelindiğinde sağa 0,2rem
- `.hover:right-0.1` - Fareyle üzerine gelindiğinde sağa 0,1 rem
- `.hover:right-0` - Vurguluyken sağa 0rem
- `.right-100` - Sağ %100
- `.right-75` - Sağ %75
- `.right-50` - Sağ %50
- `.right-25` - Sağ %25
- `.right-5` - Sağ 5rem
- `.right-4.5` - Sağ 0rem
- `.right-4` - Sağ 4rem
- `.right-3.5` - Sağ 0rem
- `.right-3` - Sağ 3rem
- `.right-2.5` - Sağ 0rem
- `.right-2` - Sağ 2rem
- `.right-1.9` - Sağ 0rem
- `.right-1.8` - Sağ 0rem
- `.right-1.7` - Sağ 0rem
- `.right-1.6` - Sağ 0rem
- `.right-1.5` - Sağ 0rem
- `.right-1.4` - Sağ 0rem
- `.right-1.3` - Sağ 0rem
- `.right-1.2` - Sağ 0rem
- `.right-1.1` - Sağ 0rem
- `.right-1` - Sağ 1rem
- `.right-0.9` - Sağ 0rem
- `.right-0.8` - Sağ 0rem
- `.right-0.7` - Sağ 0rem
- `.right-0.6` - Sağ 0rem
- `.right-0.5` - Sağ 0rem
- `.right-0.4` - Sağ 0rem
- `.right-0.3` - Sağ 0rem
- `.right-0.2` - Sağ 0,2rem
- `.right-0.1` - Sağ 0,1rem
- `.right-0` - Sağ 0rem

##### Negative Right

- `.-right-5` - Negatif Sağ 5rem
- `.-right-4.5` - Negatif Sağ 0rem
- `.-right-4` - Negatif Sağ 4rem
- `.-right-3.5` - Negatif Sağ 0rem
- `.-right-3` - Negatif Sağ 3rem
- `.-right-2.5` - Negatif Sağ 0rem
- `.-right-2` - Negatif Sağ 2rem
- `.-right-1.9` - Negatif Sağ 0rem
- `.-right-1.8` - Negatif Sağ 0rem
- `.-right-1.7` - Negatif Sağ 0rem
- `.-right-1.6` - Negatif Sağ 0rem
- `.-right-1.5` - Negatif Sağ 0rem
- `.-right-1.4` - Negatif Sağ 0rem
- `.-right-1.3` - Negatif Sağ 0rem
- `.-right-1.2` - Negatif Sağ 0rem
- `.-right-1.1` - Negatif Sağ 0rem
- `.-right-1` - Negatif Sağ 1 rem
- `.-right-0.9` - Negatif Sağ 0rem
- `.-right-0.8` - Negatif Sağ 0rem
- `.-right-0.7` - Negatif Sağ 0rem
- `.-right-0.6` - Negatif Sağ 0rem
- `.-right-0.5` - Negatif Sağ 0rem
- `.-right-0.4` - Negatif Sağ 0rem
- `.-right-0.3` - Negatif Sağ 0,3rem
- `.-right-0.2` - Negatif Sağ 0,2 rem
- `.-right-0.1` - Negatif Sağ 0,1 rem
- `.hover:-right-5` - Negatif Sağ Fareyle üzerine gelindiğinde 5rem
- `.hover:-right-4.5` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-4` - Negatif Sağ Fareyle üzerine gelindiğinde 4rem
- `.hover:-right-3.5` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-3` - Negatif Sağ Fareyle üzerine gelindiğinde 3rem
- `.hover:-right-2.5` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-2` - Negatif Sağ Fareyle üzerine gelindiğinde 2rem
- `.hover:-right-1.9` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.8` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.7` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.6` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.5` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.4` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.3` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.2` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1.1` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-1` - Negatif Sağ Fareyle üzerine gelindiğinde 1rem
- `.hover:-right-0.9` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-0.8` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-0.7` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-0.6` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-0.5` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-0.4` - Negatif Sağ Fareyle üzerine gelindiğinde 0rem
- `.hover:-right-0.3` - Negatif Sağ Fareyle üzerine gelindiğinde 0,3rem
- `.hover:-right-0.2` - Negatif Sağ Fareyle üzerine gelindiğinde 0,2rem
- `.hover:-right-0.1` - Negatif Sağ Fareyle üzerine gelindiğinde 0,1 rem

### Bottom

- `.bottom-100` - Alt %100
- `.bottom-75` - Alt %75
- `.bottom-50` - Alt %50
- `.bottom-25` - Alt %25
- `.bottom-5` - Alt 5rem
- `.bottom-4.5` - Alt 0rem
- `.bottom-4` - Alt 4rem
- `.bottom-3.5` - Alt 0rem
- `.bottom-3` - Alt 3rem
- `.bottom-2.5` - Alt 0rem
- `.bottom-2` - Alt 2rem
- `.bottom-1.9` - Alt 0rem
- `.bottom-1.8` - Alt 0rem
- `.bottom-1.7` - Alt 0rem
- `.bottom-1.6` - Alt 0rem
- `.bottom-1.5` - Alt 0rem
- `.bottom-1.4` - Alt 0rem
- `.bottom-1.3` - Alt 0rem
- `.bottom-1.2` - Alt 0rem
- `.bottom-1.1` - Alt 0rem
- `.bottom-1` - Alt 1rem
- `.bottom-0.9` - Alt 0rem
- `.bottom-0.8` - Alt 0rem
- `.bottom-0.7` - Alt 0rem
- `.bottom-0.6` - Alt 0rem
- `.bottom-0.5` - Alt 0rem
- `.bottom-0.4` - Alt 0rem
- `.bottom-0.3` - Alt 0rem
- `.bottom-0.2` - Alt 0,2rem
- `.bottom-0.1` - Alt 0,1 rem
- `.bottom-0` - Alt 0rem
- `.hover:bottom-100` - Fareyle üzerine gelindiğinde alt %100
- `.hover:bottom-75` - Fareyle üzerine gelindiğinde alt %75
- `.hover:bottom-50` - Fareyle üzerine gelindiğinde alt %50
- `.hover:bottom-25` - Fareyle üzerine gelindiğinde alt %25
- `.hover:bottom-5` - Fareyle üzerine gelindiğinde alt 5rem
- `.hover:bottom-4.5` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-4` - Fareyle üzerine gelindiğinde alt 4rem
- `.hover:bottom-3.5` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-3` - Fareyle üzerine gelindiğinde alt 3rem
- `.hover:bottom-2.5` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-2` - Fareyle üzerine gelindiğinde alt 2rem
- `.hover:bottom-1.9` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.8` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.7` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.6` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.5` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.4` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.3` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.2` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1.1` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-1` - Fareyle üzerine gelindiğinde alt 1rem
- `.hover:bottom-0.9` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.8` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.7` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.6` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.5` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.4` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.3` - Fareyle üzerine gelindiğinde alt 0rem
- `.hover:bottom-0.2` - Fareyle üzerine gelindiğinde alt kısım 0,2rem
- `.hover:bottom-0.1` - Fareyle üzerine gelindiğinde alt kısım 0,1 rem
- `.hover:bottom-0` - Fareyle üzerine gelindiğinde alt 0rem

##### Negative Bottom

- `.-bottom-5` - Negatif Alt 5rem
- `.-bottom-4.5` - Negatif Alt 0rem
- `.-bottom-4` - Negatif Alt 4rem
- `.-bottom-3.5` - Negatif Alt 0rem
- `.-bottom-3` - Negatif Alt 3rem
- `.-bottom-2.5` - Negatif Alt 0rem
- `.-bottom-2` - Negatif Alt 2rem
- `.-bottom-1.9` - Negatif Alt 0rem
- `.-bottom-1.8` - Negatif Alt 0rem
- `.-bottom-1.7` - Negatif Alt 0rem
- `.-bottom-1.6` - Negatif Alt 0rem
- `.-bottom-1.5` - Negatif Alt 0rem
- `.-bottom-1.4` - Negatif Alt 0rem
- `.-bottom-1.3` - Negatif Alt 0rem
- `.-bottom-1.2` - Negatif Alt 0rem
- `.-bottom-1.1` - Negatif Alt 0rem
- `.-bottom-1` - Negatif Alt 1rem
- `.-bottom-0.9` - Negatif Alt 0rem
- `.-bottom-0.8` - Negatif Alt 0rem
- `.-bottom-0.7` - Negatif Alt 0rem
- `.-bottom-0.6` - Negatif Alt 0rem
- `.-bottom-0.5` - Negatif Alt 0rem
- `.-bottom-0.4` - Negatif Alt 0rem
- `.-bottom-0.3` - Negatif Alt 0,3rem
- `.-bottom-0.2` - Negatif Alt 0,2rem
- `.-bottom-0.1` - Negatif Alt 0,1rem
- `.hover:-bottom-5` - Negatif Alt 5rem fareyle üzerine gelindiğinde
- `.hover:-bottom-4.5` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-4` - Negatif Alt 4rem fareyle üzerine gelindiğinde
- `.hover:-bottom-3.5` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-3` - Negatif Alt 3rem fareyle üzerine gelindiğinde
- `.hover:-bottom-2.5` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-2` - Negatif Alt 2rem fareyle üzerine gelindiğinde
- `.hover:-bottom-1.9` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.8` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.7` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.6` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.5` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.4` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.3` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.2` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1.1` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-1` - Negatif Alt 1rem fareyle üzerine gelindiğinde
- `.hover:-bottom-0.9` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-0.8` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-0.7` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-0.6` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-0.5` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-0.4` - Vurguluyken Negatif Alt 0rem
- `.hover:-bottom-0.3` - Negatif Alt 0,3rem fareyle üzerine gelindiğinde
- `.hover:-bottom-0.2` - Negatif Alt 0,2rem fareyle üzerine gelindiğinde
- `.hover:-bottom-0.1` - Negatif Alt 0,1rem fareyle üzerine gelindiğinde

### Left

- `.hover:left-100` - Fareyle üzerine gelindiğinde %100 kaldı
- `.hover:left-75` - Fareyle üzerine gelindiğinde %75 kaldı
- `.hover:left-50` - Fareyle üzerine gelindiğinde %50 kaldı
- `.hover:left-25` - Fareyle üzerine gelindiğinde %25 kaldı
- `.hover:left-5` - Fareyle üzerine gelindiğinde 5rem kaldı
- `.hover:left-4.5` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-4` - Fareyle üzerine gelindiğinde 4rem sola
- `.hover:left-3.5` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-3` - Fareyle üzerine gelindiğinde 3rem sola
- `.hover:left-2.5` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-2` - Fareyle üzerine gelindiğinde 2rem kaldı
- `.hover:left-1.9` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.8` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.7` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.6` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.5` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.4` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.3` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.2` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1.1` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-1` - Fareyle üzerine gelindiğinde 1rem kaldı
- `.hover:left-0.9` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.8` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.7` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.6` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.5` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.4` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.3` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.hover:left-0.2` - Fareyle üzerine gelindiğinde 0,2rem kaldı
- `.hover:left-0.1` - Fareyle üzerine gelindiğinde 0,1rem kaldı
- `.hover:left-0` - Fareyle üzerine gelindiğinde 0rem kaldı
- `.left-100` - %100 kaldı
- `.left-75` - Sol %75
- `.left-50` - %50 kaldı
- `.left-25` - %25 kaldı
- `.left-5` - 5rem kaldı
- `.left-4.5` - 0rem kaldı
- `.left-4` - Sol 4rem
- `.left-3.5` - 0rem kaldı
- `.left-3` - Sol 3rem
- `.left-2.5` - 0rem kaldı
- `.left-2` - 2rem kaldı
- `.left-1.9` - 0rem kaldı
- `.left-1.8` - 0rem kaldı
- `.left-1.7` - 0rem kaldı
- `.left-1.6` - 0rem kaldı
- `.left-1.5` - 0rem kaldı
- `.left-1.4` - 0rem kaldı
- `.left-1.3` - 0rem kaldı
- `.left-1.2` - 0rem kaldı
- `.left-1.1` - 0rem kaldı
- `.left-1` - 1rem kaldı
- `.left-0.9` - 0rem kaldı
- `.left-0.8` - 0rem kaldı
- `.left-0.7` - 0rem kaldı
- `.left-0.6` - 0rem kaldı
- `.left-0.5` - 0rem kaldı
- `.left-0.4` - 0rem kaldı
- `.left-0.3` - 0rem kaldı
- `.left-0.2` - Sol 0,2rem
- `.left-0.1` - Sol 0,1rem
- `.left-0` - 0rem kaldı

##### Negative Left

- `.-left-5` - Negatif Sol 5rem
- `.-left-4.5` - Negatif Sol 0rem
- `.-left-4` - Negatif Sol 4rem
- `.-left-3.5` - Negatif Sol 0rem
- `.-left-3` - Negatif Sol 3rem
- `.-left-2.5` - Negatif Sol 0rem
- `.-left-2` - Negatif Sol 2rem
- `.-left-1.9` - Negatif Sol 0rem
- `.-left-1.8` - Negatif Sol 0rem
- `.-left-1.7` - Negatif Sol 0rem
- `.-left-1.6` - Negatif Sol 0rem
- `.-left-1.5` - Negatif Sol 0rem
- `.-left-1.4` - Negatif Sol 0rem
- `.-left-1.3` - Negatif Sol 0rem
- `.-left-1.2` - Negatif Sol 0rem
- `.-left-1.1` - Negatif Sol 0rem
- `.-left-1` - Negatif Sol 1rem
- `.-left-0.9` - Negatif Sol 0rem
- `.-left-0.8` - Negatif Sol 0rem
- `.-left-0.7` - Negatif Sol 0rem
- `.-left-0.6` - Negatif Sol 0rem
- `.-left-0.5` - Negatif Sol 0rem
- `.-left-0.4` - Negatif Sol 0rem
- `.-left-0.3` - Negatif Sol 0,3rem
- `.-left-0.2` - Negatif Sol 0,2rem
- `.-left-0.1` - Negatif Sol 0,1rem
- `.hover:-left-5` - Negatif Sol 5rem fareyle üzerine gelindiğinde
- `.hover:-left-4.5` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-4` - Negatif Sol 4rem fareyle üzerine gelindiğinde
- `.hover:-left-3.5` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-3` - Negatif Sol 3rem fareyle üzerine gelindiğinde
- `.hover:-left-2.5` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-2` - Negatif Sol 2rem fareyle üzerine gelindiğinde
- `.hover:-left-1.9` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.8` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.7` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.6` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.5` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.4` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.3` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.2` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1.1` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-1` - Negatif Sol 1rem fareyle üzerine gelindiğinde
- `.hover:-left-0.9` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-0.8` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-0.7` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-0.6` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-0.5` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-0.4` - Negatif Sol 0rem fareyle üzerine gelindiğinde
- `.hover:-left-0.3` - Negatif Sol 0,3rem fareyle üzerine gelindiğinde
- `.hover:-left-0.2` - Negatif Sol 0,2rem fareyle üzerine gelindiğinde
- `.hover:-left-0.1` - Negatif Sol 0,1rem fareyle üzerine gelindiğinde

### Z-Index

- `.hover:z-5` - Fareyle üzerine gelindiğinde Z-Index 1005
- `.hover:z-4` - Fareyle üzerine gelindiğinde Z-Index 1004
- `.hover:z-3` - Fareyle üzerine gelindiğinde Z-Index 1003
- `.hover:z-2` - Fareyle üzerine gelindiğinde Z-Index 1002
- `.hover:z-1` - Fareyle üzerine gelindiğinde Z-Index 1001
- `.hover:z-0` - Fareyle üzerine gelindiğinde Z-Index 0
- `.hover:z-auto` - Fareyle üzerine gelindiğinde Z-Index otomatik
- `.z-5` - Z-indeksi 1005
- `.z-4` - Z-indeksi 1004
- `.z-3` - Z-indeksi 1003
- `.z-2` - Z-indeksi 1002
- `.z-1` - Z-indeksi 1001
- `.z-0` - Z-indeksi 0
- `.z-auto` - Z-Index otomatik

##### Negative Z-Index

- `.-z-5` - Negatif Z-indeksi 5
- `.-z-4` - Negatif Z Endeksi 4
- `.-z-3` - Negatif Z-Index 3
- `.-z-2` - Negatif Z-indeksi 2
- `.-z-1` - Negatif Z-indeksi 1
- `.hover:-z-5` - Fareyle üzerine gelindiğinde Negatif Z-Index 5
- `.hover:-z-4` - Fareyle üzerine gelindiğinde Negatif Z-Index 4
- `.hover:-z-3` - Fareyle üzerine gelindiğinde Negatif Z-Index 3
- `.hover:-z-2` - Fareyle üzerine gelindiğinde Negatif Z-Index 2
- `.hover:-z-1` - Fareyle üzerine gelindiğinde Negatif Z-Index 1

## Typography

### Font

- `.font-italic` - Yazı tipi italik
- `.font-normal` - Yazı tipi normal
- `.hover:font-italic` - Fareyle üzerine gelindiğinde yazı tipi italik
- `.hover:font-normal` - Fareyle üzerine gelindiğinde yazı tipi normal

### Font Size

- `.font-size-10` - Yazı Tipi Boyutu 10rem
- `.font-size-9.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-9` - Yazı Tipi Boyutu 9rem
- `.font-size-8.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-8` - Yazı Tipi Boyutu 8rem
- `.font-size-7.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-7` - Yazı Tipi Boyutu 7rem
- `.font-size-6.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-6` - Yazı Tipi Boyutu 6rem
- `.font-size-5.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-5` - Yazı Tipi Boyutu 5rem
- `.font-size-4.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-4` - Yazı Tipi Boyutu 4 rem
- `.font-size-3.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-3` - Yazı Tipi Boyutu 3rem
- `.font-size-2.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-2` - Yazı Tipi Boyutu 2rem
- `.font-size-1.9` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.8` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.7` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.6` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.5` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.4` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.3` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.2` - Yazı Tipi Boyutu 0 rem
- `.font-size-1.1` - Yazı Tipi Boyutu 0 rem
- `.font-size-1` - Yazı Tipi Boyutu 1 rem
- `.font-size-0.9` - Yazı Tipi Boyutu 0 rem
- `.font-size-0.8` - Yazı Tipi Boyutu 0 rem
- `.font-size-0.7` - Yazı Tipi Boyutu 0,7 rem
- `.font-size-0.6` - Yazı Tipi Boyutu 0,6 rem
- `.font-size-0.5` - Yazı Tipi Boyutu 0,5 rem
- `.hover:font-size-10` - Yazı Tipi Boyutu: Fareyle üzerine gelindiğinde 10 rem
- `.hover:font-size-9.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-9` - Vurguluyken Yazı Tipi Boyutu 9 rem
- `.hover:font-size-8.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-8` - Vurguluyken Yazı Tipi Boyutu 8rem
- `.hover:font-size-7.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-7` - Vurguluyken Yazı Tipi Boyutu 7rem
- `.hover:font-size-6.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-6` - Vurguluyken Yazı Tipi Boyutu 6rem
- `.hover:font-size-5.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-5` - Vurguluyken Yazı Tipi Boyutu 5rem
- `.hover:font-size-4.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-4` - Vurguluyken Yazı Tipi Boyutu 4rem
- `.hover:font-size-3.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-3` - Vurguluyken Yazı Tipi Boyutu 3rem
- `.hover:font-size-2.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-2` - Vurguluyken Yazı Tipi Boyutu 2rem
- `.hover:font-size-1.9` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.8` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.7` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.6` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.5` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.4` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.3` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.2` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1.1` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-1` - Vurguluyken Yazı Tipi Boyutu 1rem
- `.hover:font-size-0.9` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-0.8` - Yazı Tipi Boyutu 0rem fareyle üzerine gelindiğinde
- `.hover:font-size-0.7` - Yazı Tipi Boyutu: Fareyle üzerine gelindiğinde 0,7 rem
- `.hover:font-size-0.6` - Yazı Tipi Boyutu: Fareyle üzerine gelindiğinde 0,6 rem
- `.hover:font-size-0.5` - Yazı Tipi Boyutu: Fareyle üzerine gelindiğinde 0,5 rem

### Font Weight

- `.font-weight-900` - Yazı Tipi Ağırlığı 900
- `.font-weight-800` - Yazı Tipi Ağırlığı 800
- `.font-weight-700` - Yazı Tipi Ağırlığı 700
- `.font-weight-600` - Yazı Tipi Ağırlığı 600
- `.font-weight-500` - Yazı Tipi Ağırlığı 500
- `.font-weight-400` - Yazı Tipi Ağırlığı 400
- `.font-weight-300` - Yazı Tipi Ağırlığı 300
- `.font-weight-200` - Yazı Tipi Ağırlığı 200
- `.font-weight-100` - Yazı Tipi Ağırlığı 100
- `.font-weight-bold` - Yazı Tipi Ağırlığı kalın
- `.hover:font-weight-900` - Vurguluyken Yazı Tipi Ağırlığı 900
- `.hover:font-weight-800` - Vurguluyken Yazı Tipi Ağırlığı 800
- `.hover:font-weight-700` - Vurguluyken Yazı Tipi Ağırlığı 700
- `.hover:font-weight-600` - Vurguluyken Yazı Tipi Ağırlığı 600
- `.hover:font-weight-500` - Vurguluyken Yazı Tipi Ağırlığı 500
- `.hover:font-weight-400` - Vurguluyken Yazı Tipi Ağırlığı 400
- `.hover:font-weight-300` - Vurguluyken Yazı Tipi Ağırlığı 300
- `.hover:font-weight-200` - Vurguluyken Yazı Tipi Ağırlığı 200
- `.hover:font-weight-100` - Vurguluyken Yazı Tipi Ağırlığı 100
- `.hover:font-weight-bold` - Yazı Tipi Ağırlığı vurguluyken kalın

### Letter spacing

- `.hover:letter-spacing-1` - Fareyle üzerine gelindiğinde harf aralığı 1rem
- `.hover:letter-spacing-0.9` - Fareyle üzerine gelindiğinde harf aralığı 0rem
- `.hover:letter-spacing-0.8` - Fareyle üzerine gelindiğinde harf aralığı 0rem
- `.hover:letter-spacing-0.7` - Fareyle üzerine gelindiğinde harf aralığı 0rem
- `.hover:letter-spacing-0.6` - Fareyle üzerine gelindiğinde harf aralığı 0rem
- `.hover:letter-spacing-0.5` - Fareyle üzerine gelindiğinde harf aralığı 0rem
- `.hover:letter-spacing-0.4` - Fareyle üzerine gelindiğinde harf aralığı 0rem
- `.hover:letter-spacing-0.3` - Fareyle üzerine gelindiğinde harf aralığı 0,3 rem
- `.hover:letter-spacing-0.2` - Fareyle üzerine gelindiğinde harf aralığı 0,2 rem
- `.hover:letter-spacing-0.1` - Fareyle üzerine gelindiğinde harf aralığı 0,1 rem
- `.letter-spacing-1` - Harf aralığı 1rem
- `.letter-spacing-0.9` - Harf aralığı 0rem
- `.letter-spacing-0.8` - Harf aralığı 0rem
- `.letter-spacing-0.7` - Harf aralığı 0rem
- `.letter-spacing-0.6` - Harf aralığı 0rem
- `.letter-spacing-0.5` - Harf aralığı 0rem
- `.letter-spacing-0.4` - Harf aralığı 0rem
- `.letter-spacing-0.3` - Harf aralığı 0,3rem
- `.letter-spacing-0.2` - Harf aralığı 0,2 rem
- `.letter-spacing-0.1` - Harf aralığı 0,1 rem

### Line height

- `.hover:line-height-5` - Fareyle üzerine gelindiğinde satır yüksekliği 5rem
- `.hover:line-height-4` - Fareyle üzerine gelindiğinde satır yüksekliği 4rem
- `.hover:line-height-3` - Fareyle üzerine gelindiğinde satır yüksekliği 3rem
- `.hover:line-height-2` - Fareyle üzerine gelindiğinde satır yüksekliği 2rem
- `.hover:line-height-1` - Fareyle üzerine gelindiğinde satır yüksekliği 1rem
- `.line-height-5` - Satır yüksekliği 5rem
- `.line-height-4` - Satır yüksekliği 4rem
- `.line-height-3` - Satır yüksekliği 3rem
- `.line-height-2` - Satır yüksekliği 2rem
- `.line-height-1` - Satır yüksekliği 1rem

### Text

- `.hover:text-capitalize` - Fareyle üzerine gelindiğinde metni büyük harfle yazmak
- `.hover:text-center` - Fareyle üzerine gelindiğinde metin merkezi
- `.hover:text-end` - Fareyle üzerine gelindiğinde metin sonu
- `.hover:text-justify` - Fareyle üzerine gelindiğinde metni iki yana yasla
- `.hover:text-left` - Fareyle üzerine gelindiğinde kalan metin
- `.hover:text-line-none` - Metin satırı-vurguluyken yok
- `.hover:text-line-overline` - Fareyle üzerine gelindiğinde metin satırının üst üste çizilmesi
- `.hover:text-line-through` - Fareyle üzerine gelindiğinde metin satırı geçişi
- `.hover:text-line-underline` - Fareyle üzerine gelindiğinde metin satırının altı çizili
- `.hover:text-lowercase` - Fareyle üzerine gelindiğinde metin küçük harf
- `.hover:text-right` - Fareyle üzerine gelindiğinde metin
- `.hover:text-start` - Fareyle üzerine gelindiğinde metin başlangıcı
- `.hover:text-transparent` - Fareyle üzerine gelindiğinde metin şeffaf
- `.hover:text-uppercase` - Fareyle üzerine gelindiğinde metin büyük harf
- `.text-break-all` - Metin sonu
- `.text-break-keep-all` - Metin ara-hepsi-tut
- `.text-break-normal` - Metin sonu-normal
- `.text-break-word` - Metin sonu-kelime
- `.text-capitalize` - Metin büyük harfle yaz
- `.text-center` - Metin merkezi
- `.text-end` - Metin sonu
- `.text-justify` - Metin iki yana yasla
- `.text-left` - Metin sola
- `.text-line-none` - Metin satırı-yok
- `.text-line-overline` - Metin satırı-üst çizgi
- `.text-line-through` - Metin satırı geçişi
- `.text-line-underline` - Metin satırı-altı çizili
- `.text-lowercase` - Metin küçük harf
- `.text-overflow-clip` - Metin taşması klibi
- `.text-overflow-ellipsis` - Metin taşması-üç nokta
- `.text-right` - Sağa metin
- `.text-start` - Metin başlangıcı
- `.text-transparent` - Metin şeffaf
- `.text-uppercase` - Metin büyük harf

##### Text - Mobile (≤ 480px)

- `.hover:mobile:text-center` - Mobil cihazda fareyle üzerine gelindiğinde metnin merkezi
- `.hover:mobile:text-end` - Mobil cihazda fareyle üzerine gelindiğinde metin sonu
- `.hover:mobile:text-justify` - Mobil cihazda fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:mobile:text-left` - Mobil cihazda fareyle üzerine gelindiğinde bırakılan metin
- `.hover:mobile:text-right` - Mobil cihazda fareyle üzerine gelindiğinde sağdaki metin
- `.hover:mobile:text-start` - Mobil cihazda fareyle üzerine gelindiğinde metin başlangıcı
- `.mobile:text-center` - Mobil cihazda metin merkezi
- `.mobile:text-end` - Mobil cihazda metin sonu
- `.mobile:text-justify` - Mobil cihazda metni iki yana yaslama
- `.mobile:text-left` - Mobil cihazda bırakılan metin
- `.mobile:text-right` - Doğrudan cep telefonunda mesaj gönderin
- `.mobile:text-start` - Mobil cihazda metin başlangıcı

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - Tabletin üzerine gelindiğinde metnin merkezi
- `.hover:tablet:text-end` - Tabletin üzerine gelindiğinde metin sonu
- `.hover:tablet:text-justify` - Tablette fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:tablet:text-left` - Tablette fareyle üzerine gelindiğinde kalan metin
- `.hover:tablet:text-right` - Tabletin üzerine gelindiğinde sağdaki metin
- `.hover:tablet:text-start` - Tabletin üzerine gelindiğinde metin başlangıcı
- `.tablet:text-center` - Tabletteki metin merkezi
- `.tablet:text-end` - Tablette metin sonu
- `.tablet:text-justify` - Metin tablette iki yana yasla
- `.tablet:text-left` - Tablette kalan metin
- `.tablet:text-right` - Doğrudan tablette metin
- `.tablet:text-start` - Tablette metin başlangıcı

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - Tablet bilgisayarda fareyle üzerine gelindiğinde metin merkezi
- `.hover:tablet-pc:text-end` - Tablet bilgisayarda fareyle üzerine gelindiğinde metin sonu
- `.hover:tablet-pc:text-justify` - Tablet bilgisayarda fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:tablet-pc:text-left` - Tablet bilgisayarda fareyle üzerine gelindiğinde kalan metin
- `.hover:tablet-pc:text-right` - Tablet bilgisayarda fareyle üzerine gelindiğinde sağdaki metin
- `.hover:tablet-pc:text-start` - Tablet bilgisayarda fareyle üzerine gelindiğinde metin başlangıcı
- `.tablet-pc:text-center` - Tablet bilgisayarda metin merkezi
- `.tablet-pc:text-end` - Tablet PC'de metin sonu
- `.tablet-pc:text-justify` - Tablet PC'de metni iki yana yaslama
- `.tablet-pc:text-left` - Tablet bilgisayarda bırakılan metin
- `.tablet-pc:text-right` - Doğrudan tablet bilgisayarda metin
- `.tablet-pc:text-start` - Tablet PC'de metin başlangıcı

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - PC'de fareyle üzerine gelindiğinde metin merkezi
- `.hover:pc:text-end` - PC'de fareyle üzerine gelindiğinde metin sonu
- `.hover:pc:text-justify` - PC'de fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:pc:text-left` - PC'de fareyle üzerine gelindiğinde kalan metin
- `.hover:pc:text-right` - PC'de sağ fareyle üzerine gelindiğinde metin
- `.hover:pc:text-start` - PC'de fareyle üzerine gelindiğinde metin başlangıcı
- `.pc:text-center` - Bilgisayardaki metin merkezi
- `.pc:text-end` - PC'de metin sonu
- `.pc:text-justify` - PC'de metni iki yana yasla
- `.pc:text-left` - Metin bilgisayarda kaldı
- `.pc:text-right` - Doğrudan PC'de metin gönderin
- `.pc:text-start` - PC'de metin başlangıcı

##### Text - Tv (≥ 1200px)

- `.hover:tv:text-center` - Televizyonun üzerine gelindiğinde metin merkezi
- `.hover:tv:text-end` - Televizyonun üzerine gelindiğinde metin sonu
- `.hover:tv:text-justify` - Televizyonda fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:tv:text-left` - Televizyonda fareyle üzerine gelindiğinde bırakılan metin
- `.hover:tv:text-right` - Televizyonun sağ faresiyle üzerine gelindiğinde metin
- `.hover:tv:text-start` - Televizyonun üzerine gelindiğinde metin başlangıcı
- `.tv:text-center` - Televizyondaki metin merkezi
- `.tv:text-end` - Televizyonda metin sonu
- `.tv:text-justify` - Televizyonda metni iki yana yasla
- `.tv:text-left` - Televizyona bırakılan metin
- `.tv:text-right` - Doğrudan televizyonda mesaj gönderin
- `.tv:text-start` - Televizyonda metin başlangıcı

##### Text - Tablet Max (≤ 768px)

- `.hover:tablet-max:text-center` - Tablet max üzerinde fareyle üzerine gelindiğinde metin merkezi
- `.hover:tablet-max:text-end` - Tablet max'ın üzerine gelindiğinde metin sonu
- `.hover:tablet-max:text-justify` - Tablet max üzerinde fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:tablet-max:text-left` - Tablet max üzerinde fareyle üzerine gelindiğinde kalan metin
- `.hover:tablet-max:text-right` - Tablet max'ın üzerine gelindiğinde sağdaki metin
- `.hover:tablet-max:text-start` - Tablet max'ın üzerine gelindiğinde metin başlangıcı
- `.tablet-max:text-center` - Tablet max'ta metin merkezi
- `.tablet-max:text-end` - Tablet max'ta metin sonu
- `.tablet-max:text-justify` - Metin tablet max'ta iki yana yasla
- `.tablet-max:text-left` - Tablet max'ta kalan metin
- `.tablet-max:text-right` - Tablet max'in sağ tarafında metin
- `.tablet-max:text-start` - Tablet max'ta metin başlangıcı

##### Text - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:text-center` - Tablet PC max'ta fareyle üzerine gelindiğinde metin merkezi
- `.hover:tablet-pc-max:text-end` - Tablet PC max üzerinde fareyle üzerine gelindiğinde metin sonu
- `.hover:tablet-pc-max:text-justify` - Tablet PC Max'te fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:tablet-pc-max:text-left` - Tablet PC Max'te fareyle üzerine gelindiğinde kalan metin
- `.hover:tablet-pc-max:text-right` - Tablet pc max'ın sağındaki metin
- `.hover:tablet-pc-max:text-start` - Tablet PC max üzerinde fareyle üzerine gelindiğinde metin başlangıcı
- `.tablet-pc-max:text-center` - Tablet pc max'ta metin merkezi
- `.tablet-pc-max:text-end` - Tablet pc max'ta metin sonu
- `.tablet-pc-max:text-justify` - Tablet pc max'ta metni iki yana yaslama
- `.tablet-pc-max:text-left` - Tablet PC Max'te kalan metin
- `.tablet-pc-max:text-right` - Tablet pc max'ta metin sağ
- `.tablet-pc-max:text-start` - Tablet PC max'ta metin başlangıcı

##### Text - Pc Max (≤ 1200px)

- `.hover:pc-max:text-center` - PC max'ta fareyle üzerine gelindiğinde metin merkezi
- `.hover:pc-max:text-end` - PC max'ta fareyle üzerine gelindiğinde metin sonu
- `.hover:pc-max:text-justify` - PC max'ta fareyle üzerine gelindiğinde metni iki yana yaslama
- `.hover:pc-max:text-left` - PC max'ta fareyle üzerine gelindiğinde kalan metin
- `.hover:pc-max:text-right` - PC max'ta fareyle üzerine gelindiğinde sağdaki metin
- `.hover:pc-max:text-start` - PC max'ta fareyle üzerine gelindiğinde metin başlangıcı
- `.pc-max:text-center` - PC max'ta metin merkezi
- `.pc-max:text-end` - PC max'ta metin sonu
- `.pc-max:text-justify` - PC max'ta metni iki yana yasla
- `.pc-max:text-left` - PC max'ta kalan metin
- `.pc-max:text-right` - PC max'ta doğru metin
- `.pc-max:text-start` - PC max'ta metin başlangıcı

### Whitespace

- `.hover:whitespace-normal` - Fareyle üzerine gelindiğinde normal boşluk
- `.whitespace-normal` - Boşluk normal
- `.whitespace-nowrap` - Boşluk artık rapi
- `.whitespace-pre` - Boşluk öncesi

### Whitespace break

- `.hover:whitespace-break-spaces` - Fareyle üzerine gelindiğinde boşluk bırakma boşlukları
- `.whitespace-break-spaces` - Boşluk ara boşlukları

### Whitespace pre

- `.hover:whitespace-pre-line` - Fareyle üzerine gelindiğinde boşluk ön satırı
- `.hover:whitespace-pre-wrap` - Fareyle üzerine gelindiğinde boşluk ön sarma
- `.whitespace-pre-line` - Boşluk ön çizgisi
- `.whitespace-pre-wrap` - Boşluk ön sarma

### Writing h

- `.writing-h-tb` - H tb yazma

### Writing v

- `.writing-v-lr` - V lr yazma
- `.writing-v-rl` - V rl yazma

## Backgrounds

### Background

- `.bg-transparent` - Arka plan şeffaf
- `.hover:bg-transparent` - Fareyle üzerine gelindiğinde arka plan şeffaf

### Bg blur

- `.bg-blur-5` - Bg bulanıklığı 24px
- `.bg-blur-4` - Bg bulanıklık 16px
- `.bg-blur-3` - Bg bulanıklık 12px
- `.bg-blur-2` - Bg bulanıklığı 8px
- `.bg-blur-1` - Bg bulanıklığı 4px
- `.bg-blur-0` - Bg bulanıklığı 0px
- `.hover:bg-blur-5` - Vurguluyken Bg bulanıklığı 24px
- `.hover:bg-blur-4` - Bg fareyle üzerine gelindiğinde 16px bulanıklığı
- `.hover:bg-blur-3` - Vurguluyken Bg bulanıklığı 12px
- `.hover:bg-blur-2` - Vurguluyken Bg bulanıklığı 8px
- `.hover:bg-blur-1` - Vurguluyken Bg bulanıklığı 4px
- `.hover:bg-blur-0` - Vurguluyken Bg bulanıklığı 0px

## Borders

### Border

#### Border All

- `.border-2` - Sınırın Tamamı 2rem
- `.border-1.5` - Kenarlık Tümü 0rem
- `.border-1` - Sınırın Tamamı 1rem
- `.border-0.9` - Kenarlık Tümü 0rem
- `.border-0.8` - Kenarlık Tümü 0rem
- `.border-0.7` - Kenarlık Tümü 0rem
- `.border-0.6` - Kenarlık Tümü 0rem
- `.border-0.5` - Kenarlık Tümü 0rem
- `.border-0.4` - Kenarlığın Tamamı 0,4 rem
- `.border-0.3` - Kenarlık Tümü 0rem
- `.border-0.2` - Sınırın Tamamı 0,2 rem
- `.border-0.1` - Sınırın Tamamı 0,1 rem
- `.border-0` - Kenarlık Tümü 0rem
- `.hover:border-2` - Kenarlık Tümü 2rem fareyle üzerine gelindiğinde
- `.hover:border-1.5` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-1` - Kenarlık Tümü 1rem fareyle üzerine gelindiğinde
- `.hover:border-0.9` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.8` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.7` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.6` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.5` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.4` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.3` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:border-0.2` - Kenarlık Tümü 0,2 rem fareyle üzerine gelindiğinde
- `.hover:border-0.1` - Kenarlık Tümü 0,1 rem fareyle üzerine gelindiğinde
- `.hover:border-0` - Kenarlık Tümü 0rem fareyle üzerine gelindiğinde

#### Border Bottom

- `.border-b-2` - Kenarlık Alt 2rem
- `.border-b-1.5` - Kenarlık Alt 0rem
- `.border-b-1` - Kenarlık Alt 1rem
- `.border-b-0.9` - Kenarlık Alt 0rem
- `.border-b-0.8` - Kenarlık Alt 0rem
- `.border-b-0.7` - Kenarlık Alt 0rem
- `.border-b-0.6` - Kenarlık Alt 0rem
- `.border-b-0.5` - Kenarlık Alt 0,5rem
- `.border-b-0.4` - Kenarlık Alt 0rem
- `.border-b-0.3` - Kenarlık Alt 0rem
- `.border-b-0.2` - Kenarlık Alt 0,2 rem
- `.border-b-0.1` - Kenarlık Alt 0,1 rem
- `.border-b-0` - Kenarlık Alt 0rem
- `.hover:border-b-2` - Fareyle üzerine gelindiğinde Kenarlık Alt 2rem
- `.hover:border-b-1.5` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-1` - Fareyle üzerine gelindiğinde Kenarlık Alt 1rem
- `.hover:border-b-0.9` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.8` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.7` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.6` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.5` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.4` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.3` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem
- `.hover:border-b-0.2` - Fareyle üzerine gelindiğinde Kenarlık Alt kısmı 0,2 rem
- `.hover:border-b-0.1` - Fareyle üzerine gelindiğinde Kenarlık Alt kısmı 0,1 rem
- `.hover:border-b-0` - Fareyle üzerine gelindiğinde Kenarlık Alt 0rem

#### Border Left

- `.border-l-2` - Kenarlık Sol 2rem
- `.border-l-1.5` - Kenarlık Sol 0rem
- `.border-l-1` - Kenarlık Sol 1rem
- `.border-l-0.9` - Kenarlık Sol 0rem
- `.border-l-0.8` - Kenarlık Sol 0rem
- `.border-l-0.7` - Kenarlık Sol 0rem
- `.border-l-0.6` - Kenarlık Sol 0rem
- `.border-l-0.5` - Kenarlık Sol 0rem
- `.border-l-0.4` - Kenarlık Sol 0rem
- `.border-l-0.3` - Kenarlık Sol 0rem
- `.border-l-0.2` - Kenarlık Sol 0,2rem
- `.border-l-0.1` - Kenarlık Sol 0,1 rem
- `.border-l-0` - Kenarlık Sol 0rem
- `.hover:border-l-2` - Fareyle üzerine gelindiğinde Kenarlık Sol 2rem
- `.hover:border-l-1.5` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-1` - Fareyle üzerine gelindiğinde Kenarlık Sol 1rem
- `.hover:border-l-0.9` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.8` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.7` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.6` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.5` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.4` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.3` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem
- `.hover:border-l-0.2` - Fareyle üzerine gelindiğinde Kenarlık Sol 0,2rem
- `.hover:border-l-0.1` - Fareyle üzerine gelindiğinde Kenarlık Sol 0,1 rem
- `.hover:border-l-0` - Fareyle üzerine gelindiğinde Kenarlık Sol 0rem

#### Border Right

- `.border-r-2` - Kenarlık Sağ 2rem
- `.border-r-1.5` - Kenarlık Sağ 0rem
- `.border-r-1` - Kenarlık Sağ 1rem
- `.border-r-0.9` - Kenarlık Sağ 0rem
- `.border-r-0.8` - Kenarlık Sağ 0rem
- `.border-r-0.7` - Kenarlık Sağ 0rem
- `.border-r-0.6` - Kenarlık Sağ 0rem
- `.border-r-0.5` - Kenarlık Sağ 0rem
- `.border-r-0.4` - Kenarlık Sağ 0rem
- `.border-r-0.3` - Kenarlık Sağ 0rem
- `.border-r-0.2` - Kenarlık Sağ 0,2rem
- `.border-r-0.1` - Kenarlık Sağ 0,1rem
- `.border-r-0` - Kenarlık Sağ 0rem
- `.hover:border-r-2` - Fareyle üzerine gelindiğinde Sağ Kenarlık 2rem
- `.hover:border-r-1.5` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-1` - Fareyle üzerine gelindiğinde Sağ Kenarlık 1rem
- `.hover:border-r-0.9` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.8` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.7` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.6` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.5` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.4` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.3` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem
- `.hover:border-r-0.2` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0,2rem
- `.hover:border-r-0.1` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0,1 rem
- `.hover:border-r-0` - Fareyle üzerine gelindiğinde Sağ Kenarlık 0rem

#### Border Top

- `.border-t-2` - Kenarlık Üst 2rem
- `.border-t-1.5` - Kenarlık Üst 0rem
- `.border-t-1` - Kenarlık Üst 1rem
- `.border-t-0.9` - Kenarlık Üst 0rem
- `.border-t-0.8` - Kenarlık Üst 0rem
- `.border-t-0.7` - Kenarlık Üst 0rem
- `.border-t-0.6` - Kenarlık Üst 0rem
- `.border-t-0.5` - Kenarlık Üst 0rem
- `.border-t-0.4` - Kenarlık Üst 0rem
- `.border-t-0.3` - Kenarlık Üst 0rem
- `.border-t-0.2` - Kenarlık Üstü 0,2 rem
- `.border-t-0.1` - Kenarlık Üst 0,1 rem
- `.border-t-0` - Kenarlık Üst 0rem
- `.hover:border-t-2` - Fareyle üzerine gelindiğinde Kenarlık Üst 2rem
- `.hover:border-t-1.5` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-1` - Fareyle üzerine gelindiğinde Kenarlık Üst 1rem
- `.hover:border-t-0.9` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.8` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.7` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.6` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.5` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.4` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.3` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem
- `.hover:border-t-0.2` - Fareyle üzerine gelindiğinde Kenarlık Üstü 0,2rem
- `.hover:border-t-0.1` - Fareyle üzerine gelindiğinde Kenarlık Üst 0,1rem
- `.hover:border-t-0` - Fareyle üzerine gelindiğinde Kenarlık Üst 0rem

#### Border X-Axis

- `.border-x-2` - Kenarlık X Ekseni 2rem
- `.border-x-1.5` - Kenarlık X Ekseni 0rem
- `.border-x-1` - Kenarlık X Ekseni 1rem
- `.border-x-0.9` - Kenarlık X Ekseni 0rem
- `.border-x-0.8` - Kenarlık X Ekseni 0rem
- `.border-x-0.7` - Kenarlık X Ekseni 0rem
- `.border-x-0.6` - Kenarlık X Ekseni 0rem
- `.border-x-0.5` - Kenarlık X Ekseni 0rem
- `.border-x-0.4` - Kenarlık X Ekseni 0rem
- `.border-x-0.3` - Kenarlık X Ekseni 0rem
- `.border-x-0.2` - Kenarlık X Ekseni 0,2 rem
- `.border-x-0.1` - Kenarlık X Ekseni 0,1 rem
- `.border-x-0` - Kenarlık X Ekseni 0rem
- `.hover:border-x-2` - Fareyle üzerine gelindiğinde X Ekseni Kenarlığı 2rem
- `.hover:border-x-1.5` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-1` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 1rem
- `.hover:border-x-0.9` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.8` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.7` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.6` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.5` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.4` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.3` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem
- `.hover:border-x-0.2` - Vurguluyken Kenarlık X Ekseni 0,2 rem
- `.hover:border-x-0.1` - Fareyle üzerine gelindiğinde X Ekseni Kenarlığı 0,1 rem
- `.hover:border-x-0` - Fareyle üzerine gelindiğinde Kenarlık X Ekseni 0rem

#### Border Y-Axis

- `.border-y-2` - Kenarlık Y Ekseni 2rem
- `.border-y-1.5` - Kenarlık Y Ekseni 0rem
- `.border-y-1` - Kenarlık Y Ekseni 1rem
- `.border-y-0.9` - Kenarlık Y Ekseni 0rem
- `.border-y-0.8` - Kenarlık Y Ekseni 0rem
- `.border-y-0.7` - Kenarlık Y Ekseni 0rem
- `.border-y-0.6` - Kenarlık Y Ekseni 0rem
- `.border-y-0.5` - Kenarlık Y Ekseni 0,5rem
- `.border-y-0.4` - Kenarlık Y Ekseni 0rem
- `.border-y-0.3` - Kenarlık Y Ekseni 0rem
- `.border-y-0.2` - Kenarlık Y Ekseni 0,2rem
- `.border-y-0.1` - Kenarlık Y Ekseni 0,1rem
- `.border-y-0` - Kenarlık Y Ekseni 0rem
- `.hover:border-y-2` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 2rem
- `.hover:border-y-1.5` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-1` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 1rem
- `.hover:border-y-0.9` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.8` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.7` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.6` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.5` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.4` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.3` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem
- `.hover:border-y-0.2` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0,2 rem
- `.hover:border-y-0.1` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0,1 rem
- `.hover:border-y-0` - Fareyle üzerine gelindiğinde Y Ekseni Kenarlığı 0rem

### Border Radius

#### Border Radius All

- `.hover:rounded-5` - Kenar Yarıçapı Tümü 5rem fareyle üzerine gelindiğinde
- `.hover:rounded-4.5` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-4` - Kenarlık Yarıçapı Tümü 4rem fareyle üzerine gelindiğinde
- `.hover:rounded-3.5` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-3` - Kenar Yarıçapının Tamamı 3rem fareyle üzerine gelindiğinde
- `.hover:rounded-2.5` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-2` - Kenar Yarıçapının Tamamı 2rem fareyle üzerine gelindiğinde
- `.hover:rounded-1.5` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-1` - Kenar Yarıçapının Tamamı 1rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.9` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.8` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.7` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.6` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.5` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.4` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.3` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.2` - Kenar Yarıçapının Tamamı 0,2rem fareyle üzerine gelindiğinde
- `.hover:rounded-0.1` - Kenar Yarıçapı Fareyle üzerine gelindiğinde tamamı 0,1 rem
- `.hover:rounded-0` - Kenar Yarıçapı Tümü 0rem fareyle üzerine gelindiğinde
- `.rounded-5` - Kenar Yarıçapının Tamamı 5rem
- `.rounded-4.5` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-4` - Kenar Yarıçapının Tamamı 4rem
- `.rounded-3.5` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-3` - Kenarlık Yarıçapının Tamamı 3rem
- `.rounded-2.5` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-2` - Kenarlık Yarıçapının Tamamı 2rem
- `.rounded-1.5` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-1` - Kenarlık Yarıçapının Tamamı 1rem
- `.rounded-0.9` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.8` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.7` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.6` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.5` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.4` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.3` - Kenarlık Yarıçapı Tümü 0rem
- `.rounded-0.2` - Kenar Yarıçapı Tümü 0,2rem
- `.rounded-0.1` - Kenar Yarıçapının Tamamı 0,1 rem
- `.rounded-0` - Kenarlık Yarıçapı Tümü 0rem

#### Border Radius Bottom Left

- `.hover:rounded-bl-5` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sol Altta 5rem
- `.hover:rounded-bl-4.5` - Kenarlık Yarıçapı Sol Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-4` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sol Altta 4rem
- `.hover:rounded-bl-3.5` - Kenarlık Yarıçapı Sol Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-3` - Kenarlık Yarıçapı Sol Altta 3rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-2.5` - Kenarlık Yarıçapı Sol Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-2` - Kenarlık Yarıçapı Sol Altta 2rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-1.5` - Kenarlık Yarıçapı Sol Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-1` - Kenarlık Yarıçapı Sol Altta 1rem fareyle üzerine gelindiğinde
- `.hover:rounded-bl-0.5` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sol Alt 0,5 rem
- `.hover:rounded-bl-0` - Kenarlık Yarıçapı Sol Alt 0rem fareyle üzerine gelindiğinde
- `.rounded-bl-5` - Kenarlık Yarıçapı Sol Alt 5rem
- `.rounded-bl-4.5` - Kenarlık Yarıçapı Sol Alt 0rem
- `.rounded-bl-4` - Kenarlık Yarıçapı Sol Alt 4rem
- `.rounded-bl-3.5` - Kenarlık Yarıçapı Sol Alt 0rem
- `.rounded-bl-3` - Kenarlık Yarıçapı Sol Alt 3rem
- `.rounded-bl-2.5` - Kenarlık Yarıçapı Sol Alt 0rem
- `.rounded-bl-2` - Kenarlık Yarıçapı Sol Alt 2rem
- `.rounded-bl-1.5` - Kenarlık Yarıçapı Sol Alt 0rem
- `.rounded-bl-1` - Kenarlık Yarıçapı Sol Alt 1rem
- `.rounded-bl-0.5` - Kenarlık Yarıçapı Sol Alt 0,5 rem
- `.rounded-bl-0` - Kenarlık Yarıçapı Sol Alt 0rem

#### Border Radius Bottom Right

- `.hover:rounded-br-5` - Kenarlık Yarıçapı Sağ Alt 5rem fareyle üzerine gelindiğinde
- `.hover:rounded-br-4.5` - Kenarlık Yarıçapı Sağ Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-br-4` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sağ Altta 4rem
- `.hover:rounded-br-3.5` - Kenarlık Yarıçapı Sağ Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-br-3` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sağ Altta 3rem
- `.hover:rounded-br-2.5` - Kenarlık Yarıçapı Sağ Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-br-2` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sağ Altta 2rem
- `.hover:rounded-br-1.5` - Kenarlık Yarıçapı Sağ Alt 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-br-1` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sağ Altta 1rem
- `.hover:rounded-br-0.5` - Fareyle üzerine gelindiğinde Sağ Alt Kenar Yarıçapı 0,5 rem
- `.hover:rounded-br-0` - Kenarlık Yarıçapı Sağ Alt 0rem fareyle üzerine gelindiğinde
- `.rounded-br-5` - Kenarlık Yarıçapı Sağ Alt 5rem
- `.rounded-br-4.5` - Kenarlık Yarıçapı Sağ Alt 0rem
- `.rounded-br-4` - Kenarlık Yarıçapı Sağ Alt 4rem
- `.rounded-br-3.5` - Kenarlık Yarıçapı Sağ Alt 0rem
- `.rounded-br-3` - Kenarlık Yarıçapı Sağ Alt 3rem
- `.rounded-br-2.5` - Kenarlık Yarıçapı Sağ Alt 0rem
- `.rounded-br-2` - Kenarlık Yarıçapı Sağ Alt 2rem
- `.rounded-br-1.5` - Kenarlık Yarıçapı Sağ Alt 0rem
- `.rounded-br-1` - Kenarlık Yarıçapı Sağ Alt 1rem
- `.rounded-br-0.5` - Kenarlık Yarıçapı Sağ Alt 0,5 rem
- `.rounded-br-0` - Kenarlık Yarıçapı Sağ Alt 0rem

#### Border Radius Top Left

- `.hover:rounded-tl-5` - Kenarlık Yarıçapı Üst Sol 5rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-4.5` - Kenarlık Yarıçapı Üst Sol 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-4` - Kenarlık Yarıçapı Üst Sol 4rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-3.5` - Kenarlık Yarıçapı Üst Sol 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-3` - Fareyle üzerine gelindiğinde Kenarlık Yarıçapı Sol Üst 3rem
- `.hover:rounded-tl-2.5` - Kenarlık Yarıçapı Üst Sol 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-2` - Kenarlık Yarıçapı Üst Sol 2rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-1.5` - Kenarlık Yarıçapı Üst Sol 0rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-1` - Kenarlık Yarıçapı Üst Sol 1rem fareyle üzerine gelindiğinde
- `.hover:rounded-tl-0.5` - Fareyle üzerine gelindiğinde Kenar Yarıçapı Sol Üst 0,5rem
- `.hover:rounded-tl-0` - Kenarlık Yarıçapı Üst Sol 0rem fareyle üzerine gelindiğinde
- `.rounded-tl-5` - Kenarlık Yarıçapı Sol Üst 5rem
- `.rounded-tl-4.5` - Kenarlık Yarıçapı Sol Üst 0rem
- `.rounded-tl-4` - Kenarlık Yarıçapı Sol Üst 4rem
- `.rounded-tl-3.5` - Kenarlık Yarıçapı Sol Üst 0rem
- `.rounded-tl-3` - Kenarlık Yarıçapı Sol Üst 3rem
- `.rounded-tl-2.5` - Kenarlık Yarıçapı Sol Üst 0rem
- `.rounded-tl-2` - Kenarlık Yarıçapı Sol Üst 2rem
- `.rounded-tl-1.5` - Kenarlık Yarıçapı Sol Üst 0rem
- `.rounded-tl-1` - Kenarlık Yarıçapı Sol Üst 1rem
- `.rounded-tl-0.5` - Kenar Yarıçapı Sol Üst 0,5 rem
- `.rounded-tl-0` - Kenarlık Yarıçapı Sol Üst 0rem

#### Border Radius Top Right

- `.hover:rounded-tr-5` - Kenarlık Yarıçapı Sağ Üst 5rem fareyle üzerine gelindiğinde
- `.hover:rounded-tr-4.5` - Kenarlık Yarıçapı Sağ Üst Fareyle üzerine gelindiğinde 0rem
- `.hover:rounded-tr-4` - Fareyle üzerine gelindiğinde Kenar Yarıçapı Sağ Üst 4rem
- `.hover:rounded-tr-3.5` - Kenarlık Yarıçapı Sağ Üst Fareyle üzerine gelindiğinde 0rem
- `.hover:rounded-tr-3` - Fareyle üzerine gelindiğinde Kenar Yarıçapı Sağ Üst 3rem
- `.hover:rounded-tr-2.5` - Kenarlık Yarıçapı Sağ Üst Fareyle üzerine gelindiğinde 0rem
- `.hover:rounded-tr-2` - Fareyle üzerine gelindiğinde Kenar Yarıçapı Sağ Üst 2rem
- `.hover:rounded-tr-1.5` - Kenarlık Yarıçapı Sağ Üst Fareyle üzerine gelindiğinde 0rem
- `.hover:rounded-tr-1` - Fareyle üzerine gelindiğinde Kenar Yarıçapı Sağ Üst 1rem
- `.hover:rounded-tr-0.5` - Fareyle üzerine gelindiğinde Kenar Yarıçapı Sağ Üst 0,5rem
- `.hover:rounded-tr-0` - Kenarlık Yarıçapı Sağ Üst Fareyle üzerine gelindiğinde 0rem
- `.rounded-tr-5` - Kenarlık Yarıçapı Sağ Üst 5rem
- `.rounded-tr-4.5` - Kenarlık Yarıçapı Sağ Üst 0rem
- `.rounded-tr-4` - Kenar Yarıçapı Sağ Üst 4rem
- `.rounded-tr-3.5` - Kenarlık Yarıçapı Sağ Üst 0rem
- `.rounded-tr-3` - Kenarlık Yarıçapı Sağ Üst 3rem
- `.rounded-tr-2.5` - Kenarlık Yarıçapı Sağ Üst 0rem
- `.rounded-tr-2` - Kenar Yarıçapı Sağ Üst 2rem
- `.rounded-tr-1.5` - Kenarlık Yarıçapı Sağ Üst 0rem
- `.rounded-tr-1` - Kenarlık Yarıçapı Sağ Üst 1rem
- `.rounded-tr-0.5` - Kenar Yarıçapı Sağ Üst 0,5 rem
- `.rounded-tr-0` - Kenarlık Yarıçapı Sağ Üst 0rem

## Effects

### Box Shadow

#### Box Shadow All

- `.hover:shadow-5` - Kutu Gölgesi Tümü 5rem fareyle üzerine gelindiğinde
- `.hover:shadow-5-1` - Kutu Gölgesi Tümü 0 0 5rem 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-4` - Kutu Gölgesi Tümü 4rem fareyle üzerine gelindiğinde
- `.hover:shadow-4-1` - Kutu Gölgesi Tümü 0 0 4rem 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-3` - Kutu Gölgesi Tümü 3rem fareyle üzerine gelindiğinde
- `.hover:shadow-3-1` - Kutu Gölgesi Tümü 0 0 3rem 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-2` - Kutu Gölgesi Tümü 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-2-1` - Kutu Gölgesi Tümü 0 0 2rem 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-1` - Kutu Gölgesi Tümü 1rem fareyle üzerine gelindiğinde
- `.hover:shadow-1-1` - Kutu Gölgesi Tümü 0 0 1rem 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-none` - Kutu Gölgesi Fareyle üzerine gelindiğinde hiçbiri yok
- `.shadow-5` - Kutu Gölgesi Tümü 5rem
- `.shadow-5-1` - Kutu Gölgesi Tümü 0 0 5rem 2rem
- `.shadow-4` - Kutu Gölgesi Tümü 4rem
- `.shadow-4-1` - Kutu Gölgesi Tümü 0 0 4rem 2rem
- `.shadow-3` - Kutu Gölgesi Tümü 3rem
- `.shadow-3-1` - Kutu Gölgesi Tümü 0 0 3rem 2rem
- `.shadow-2` - Kutu Gölgesi Tümü 2rem
- `.shadow-2-1` - Kutu Gölgesi Tümü 0 0 2rem 2rem
- `.shadow-1` - Kutu Gölgesi Tümü 1rem
- `.shadow-1-1` - Kutu Gölgesi Tümü 0 0 1rem 2rem
- `.shadow-none` - Kutu Gölgesi Hepsi hiçbiri

#### Box Shadow Bottom

- `.hover:shadow-b-10` - Kutu Gölgesi Altta 10rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-9` - Kutu Gölgesi Alt 9rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-8` - Kutu Gölgesi Alt 8rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-7` - Fareyle üzerine gelindiğinde Kutu Gölgesi Alt 7rem
- `.hover:shadow-b-6` - Kutu Gölgesi Alt 6rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-5` - Kutu Gölgesi Alt 5rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-4` - Fareyle üzerine gelindiğinde Kutu Gölgesi Alt 4rem
- `.hover:shadow-b-3` - Kutu Gölgesi Altta 3rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-2` - Kutu Gölgesi Alt 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-b-1` - Kutu Gölgesi Altta 1rem fareyle üzerine gelindiğinde
- `.shadow-b-10` - Kutu Gölgesi Alt 10rem
- `.shadow-b-9` - Kutu Gölgesi Alt 9rem
- `.shadow-b-8` - Kutu Gölgesi Alt 8rem
- `.shadow-b-7` - Kutu Gölgesi Alt 7rem
- `.shadow-b-6` - Kutu Gölgesi Alt 6rem
- `.shadow-b-5` - Kutu Gölgesi Alt 5rem
- `.shadow-b-4` - Kutu Gölgesi Alt 4rem
- `.shadow-b-3` - Kutu Gölgesi Alt 3rem
- `.shadow-b-2` - Kutu Gölgesi Alt 2rem
- `.shadow-b-1` - Kutu Gölgesi Alt 1rem

#### Box Shadow Left

- `.hover:shadow-l-10` - Kutu Gölgesi Fareyle üzerine gelindiğinde 10 saniye kaldı
- `.hover:shadow-l-9` - Kutu Gölgesi Fareyle üzerine gelindiğinde 9 saniye kaldı
- `.hover:shadow-l-8` - Kutu Gölgesi Fareyle üzerine gelindiğinde 8 saniye kaldı
- `.hover:shadow-l-7` - Kutu Gölgesi Fareyle üzerine gelindiğinde 7 saniye kaldı
- `.hover:shadow-l-6` - Kutu Gölgesi Vurguluyken 6rem Sol
- `.hover:shadow-l-5` - Kutu Gölgesi Fareyle üzerine gelindiğinde 5 saniye kaldı
- `.hover:shadow-l-4` - Kutu Gölgesi Vurguluyken 4rem Sol
- `.hover:shadow-l-3` - Kutu Gölgesi Fareyle üzerine gelindiğinde 3 saniye kaldı
- `.hover:shadow-l-2` - Kutu Gölgesi Fareyle üzerine gelindiğinde 2 saniye kaldı
- `.hover:shadow-l-1` - Kutu Gölgesi Fareyle üzerine gelindiğinde 1 saniye kaldı
- `.shadow-l-10` - Kutu Gölgesi Sol 10rem
- `.shadow-l-9` - Kutu Gölgesi Sol 9rem
- `.shadow-l-8` - Kutu Gölgesi Sol 8rem
- `.shadow-l-7` - Kutu Gölgesi Sol 7rem
- `.shadow-l-6` - Kutu Gölgesi Sol 6rem
- `.shadow-l-5` - Kutu Gölgesi Sol 5rem
- `.shadow-l-4` - Kutu Gölgesi Sol 4rem
- `.shadow-l-3` - Kutu Gölgesi Sol 3rem
- `.shadow-l-2` - Kutu Gölgesi Sol 2rem
- `.shadow-l-1` - Kutu Gölgesi Sol 1rem

#### Box Shadow Right

- `.hover:shadow-r-10` - Kutu Gölgesi Sağa 10rem fareyle üzerine gelindiğinde
- `.hover:shadow-r-9` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 9rem
- `.hover:shadow-r-8` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 8rem
- `.hover:shadow-r-7` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 7rem
- `.hover:shadow-r-6` - Kutu Gölgesi Sağa 6rem fareyle üzerine gelindiğinde
- `.hover:shadow-r-5` - Kutu Gölgesi Sağa 5rem fareyle üzerine gelindiğinde
- `.hover:shadow-r-4` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 4rem
- `.hover:shadow-r-3` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 3rem
- `.hover:shadow-r-2` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 2rem
- `.hover:shadow-r-1` - Fareyle üzerine gelindiğinde Kutu Gölgesi Sağ 1rem
- `.shadow-r-10` - Kutu Gölgesi Sağ 10rem
- `.shadow-r-9` - Kutu Gölgesi Sağ 9rem
- `.shadow-r-8` - Kutu Gölgesi Sağ 8rem
- `.shadow-r-7` - Kutu Gölgesi Sağ 7rem
- `.shadow-r-6` - Kutu Gölgesi Sağ 6rem
- `.shadow-r-5` - Kutu Gölgesi Sağ 5rem
- `.shadow-r-4` - Kutu Gölgesi Sağ 4rem
- `.shadow-r-3` - Kutu Gölgesi Sağ 3rem
- `.shadow-r-2` - Kutu Gölgesi Sağ 2rem
- `.shadow-r-1` - Kutu Gölgesi Sağ 1rem

#### Box Shadow Top

- `.hover:shadow-t-10` - Fareyle üzerine gelindiğinde Box Shadow Top 10rem
- `.hover:shadow-t-9` - Fareyle üzerine gelindiğinde Box Shadow Top 9rem
- `.hover:shadow-t-8` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 8rem
- `.hover:shadow-t-7` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 7rem
- `.hover:shadow-t-6` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 6rem
- `.hover:shadow-t-5` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 5rem
- `.hover:shadow-t-4` - Fareyle üzerine gelindiğinde Box Shadow Top 4rem
- `.hover:shadow-t-3` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 3rem
- `.hover:shadow-t-2` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 2rem
- `.hover:shadow-t-1` - Fareyle üzerine gelindiğinde Kutu Gölgesi Üst 1rem
- `.shadow-t-10` - Kutu Gölgesi Üst 10rem
- `.shadow-t-9` - Kutu Gölge Üstü 9rem
- `.shadow-t-8` - Kutu Gölge Üstü 8rem
- `.shadow-t-7` - Kutu Gölge Üstü 7rem
- `.shadow-t-6` - Kutu Gölge Üstü 6rem
- `.shadow-t-5` - Kutu Gölge Üstü 5rem
- `.shadow-t-4` - Kutu Gölge Üstü 4rem
- `.shadow-t-3` - Kutu Gölge Üstü 3rem
- `.shadow-t-2` - Kutu Gölge Üstü 2rem
- `.shadow-t-1` - Kutu Gölge Üstü 1rem

#### Box Shadow X-Axis

- `.hover:shadow-x-10` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 10rem
- `.hover:shadow-x-9` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 9rem
- `.hover:shadow-x-8` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 8rem
- `.hover:shadow-x-7` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 7rem
- `.hover:shadow-x-6` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 6rem
- `.hover:shadow-x-5` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 5rem
- `.hover:shadow-x-4` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 4rem
- `.hover:shadow-x-3` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 3rem
- `.hover:shadow-x-2` - Fareyle üzerine gelindiğinde Box Shadow X Ekseni 2rem
- `.hover:shadow-x-1` - Fareyle üzerine gelindiğinde Kutu Gölge X Ekseni 1rem
- `.shadow-x-10` - Kutu Gölge X Ekseni 10rem
- `.shadow-x-9` - Kutu Gölge X Ekseni 9rem
- `.shadow-x-8` - Kutu Gölge X Ekseni 8rem
- `.shadow-x-7` - Kutu Gölge X Ekseni 7rem
- `.shadow-x-6` - Kutu Gölge X Ekseni 6rem
- `.shadow-x-5` - Kutu Gölge X Ekseni 5rem
- `.shadow-x-4` - Kutu Gölge X Ekseni 4rem
- `.shadow-x-3` - Kutu Gölge X Ekseni 3rem
- `.shadow-x-2` - Kutu Gölge X Ekseni 2rem
- `.shadow-x-1` - Kutu Gölge X Ekseni 1rem

#### Box Shadow Y-Axis

- `.hover:shadow-y-10` - Kutu Gölge Y Ekseni 10rem fareyle üzerine gelindiğinde
- `.hover:shadow-y-9` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 9rem
- `.hover:shadow-y-8` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 8rem
- `.hover:shadow-y-7` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 7rem
- `.hover:shadow-y-6` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 6rem
- `.hover:shadow-y-5` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 5rem
- `.hover:shadow-y-4` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 4rem
- `.hover:shadow-y-3` - Fareyle üzerine gelindiğinde Kutu Gölge Y Ekseni 3rem
- `.hover:shadow-y-2` - Kutu Gölgesi Y Ekseni 2rem fareyle üzerine gelindiğinde
- `.hover:shadow-y-1` - Kutu Gölgesi Y Ekseni 1rem fareyle üzerine gelindiğinde
- `.shadow-y-10` - Kutu Gölge Y Ekseni 10rem
- `.shadow-y-9` - Kutu Gölge Y Ekseni 9rem
- `.shadow-y-8` - Kutu Gölge Y Ekseni 8rem
- `.shadow-y-7` - Kutu Gölge Y Ekseni 7rem
- `.shadow-y-6` - Kutu Gölge Y Ekseni 6rem
- `.shadow-y-5` - Kutu Gölge Y Ekseni 5rem
- `.shadow-y-4` - Kutu Gölge Y Ekseni 4rem
- `.shadow-y-3` - Kutu Gölge Y Ekseni 3rem
- `.shadow-y-2` - Kutu Gölge Y Ekseni 2rem
- `.shadow-y-1` - Kutu Gölge Y Ekseni 1rem

### Blur

- `.blur-5` - Bulanıklaştırma 24px
- `.blur-4` - Bulanıklaştırma 16px
- `.blur-3` - Bulanıklaştırma 12px
- `.blur-2` - Bulanıklaştırma 8px
- `.blur-1` - Bulanıklaştırma 4px
- `.blur-0` - Bulanıklaştırma 0px
- `.hover:blur-5` - Fareyle üzerine gelindiğinde 24px bulanıklaştır
- `.hover:blur-4` - Fareyle üzerine gelindiğinde 16px bulanıklaştırma
- `.hover:blur-3` - Fareyle üzerine gelindiğinde 12px bulanıklaştırma
- `.hover:blur-2` - Fareyle üzerine gelindiğinde 8px bulanıklaştır
- `.hover:blur-1` - Fareyle üzerine gelindiğinde 4px bulanıklaştır
- `.hover:blur-0` - Fareyle üzerine gelindiğinde 0px bulanıklaştır

### Opacity

- `.hover:opacity-100` - Fareyle üzerine gelindiğinde opaklık %100
- `.hover:opacity-95` - Fareyle üzerine gelindiğinde opaklık %95
- `.hover:opacity-90` - Fareyle üzerine gelindiğinde opaklık %90
- `.hover:opacity-85` - Fareyle üzerine gelindiğinde opaklık %85
- `.hover:opacity-80` - Fareyle üzerine gelindiğinde opaklık %80
- `.hover:opacity-75` - Fareyle üzerine gelindiğinde opaklık %75
- `.hover:opacity-70` - Fareyle üzerine gelindiğinde opaklık %70
- `.hover:opacity-65` - Fareyle üzerine gelindiğinde opaklık %65
- `.hover:opacity-60` - Fareyle üzerine gelindiğinde opaklık %60
- `.hover:opacity-55` - Fareyle üzerine gelindiğinde opaklık %55
- `.hover:opacity-50` - Fareyle üzerine gelindiğinde opaklık %50
- `.hover:opacity-45` - Fareyle üzerine gelindiğinde opaklık %45
- `.hover:opacity-40` - Fareyle üzerine gelindiğinde opaklık %40
- `.hover:opacity-35` - Fareyle üzerine gelindiğinde opaklık %35
- `.hover:opacity-30` - Fareyle üzerine gelindiğinde opaklık %30
- `.hover:opacity-25` - Fareyle üzerine gelindiğinde opaklık %25
- `.hover:opacity-20` - Fareyle üzerine gelindiğinde opaklık %20
- `.hover:opacity-15` - Fareyle üzerine gelindiğinde opaklık %15
- `.hover:opacity-10` - Fareyle üzerine gelindiğinde opaklık %10
- `.hover:opacity-5` - Fareyle üzerine gelindiğinde opaklık %5
- `.hover:opacity-0` - Fareyle üzerine gelindiğinde opaklık %0
- `.opacity-100` - Opaklık %100
- `.opacity-95` - Opaklık %95
- `.opacity-90` - Opaklık %90
- `.opacity-85` - Opaklık %85
- `.opacity-80` - Opaklık %80
- `.opacity-75` - Opaklık %75
- `.opacity-70` - Opaklık %70
- `.opacity-65` - Opaklık %65
- `.opacity-60` - Opaklık %60
- `.opacity-55` - Opaklık %55
- `.opacity-50` - Opaklık %50
- `.opacity-45` - Opaklık %45
- `.opacity-40` - Opaklık %40
- `.opacity-35` - Opaklık %35
- `.opacity-30` - Opaklık %30
- `.opacity-25` - Opaklık %25
- `.opacity-20` - Opaklık %20
- `.opacity-15` - Opaklık %15
- `.opacity-10` - Opaklık %10
- `.opacity-5` - Opaklık %5
- `.opacity-0` - Opaklık %0

## Transforms

### Rotate

- `.hover:rotate-180` - Fareyle üzerine gelindiğinde 180deg döndürün
- `.hover:rotate-135` - Fareyle üzerine gelindiğinde 135deg döndürün
- `.hover:rotate-90` - Fareyle üzerine gelindiğinde 90deg döndürün
- `.hover:rotate-45` - Fareyle üzerine gelindiğinde 45deg döndürün
- `.hover:rotate-12` - Fareyle üzerine gelindiğinde 12deg döndür
- `.hover:rotate-9` - Fareyle üzerine gelindiğinde 9deg döndür
- `.hover:rotate-6` - Fareyle üzerine gelindiğinde 6deg döndür
- `.hover:rotate-3` - Fareyle üzerine gelindiğinde 3deg döndür
- `.hover:rotate-0` - Fareyle üzerine gelindiğinde 0deg döndür
- `.rotate-180` - 180deg döndür
- `.rotate-135` - 135deg döndür
- `.rotate-90` - 90deg döndür
- `.rotate-45` - 45deg döndür
- `.rotate-12` - 12deg döndür
- `.rotate-9` - 9deg döndür
- `.rotate-6` - 6deg döndür
- `.rotate-3` - 3deg döndür
- `.rotate-0` - 0deg döndür

##### Negative Rotate

- `.-rotate-180` - Negatif Döndürme 180deg
- `.-rotate-135` - Negatif Döndürme 135deg
- `.-rotate-90` - Negatif Döndürme 90deg
- `.-rotate-45` - Negatif Döndürme 45deg
- `.-rotate-12` - Negatif Döndürme 12deg
- `.-rotate-9` - Negatif Döndürme 9deg
- `.-rotate-6` - Negatif Döndürme 6deg
- `.-rotate-3` - Negatif Döndürme 3deg
- `.hover:-rotate-180` - Fareyle üzerine gelindiğinde 180deg Negatif Döndürme
- `.hover:-rotate-135` - Fareyle üzerine gelindiğinde 135deg Negatif Döndürme
- `.hover:-rotate-90` - Fareyle üzerine gelindiğinde 90deg Negatif Döndürme
- `.hover:-rotate-45` - Fareyle üzerine gelindiğinde 45deg Negatif Döndürme
- `.hover:-rotate-12` - Fareyle üzerine gelindiğinde 12deg Negatif Döndürme
- `.hover:-rotate-9` - Fareyle üzerine gelindiğinde 9deg Negatif Döndürme
- `.hover:-rotate-6` - Vurguluyken 6deg Negatif Döndürme
- `.hover:-rotate-3` - Vurguluyken 3deg Negatif Döndürme

### Skew

#### Skew X-Axis

- `.hover:skew-x-12` - Fareyle üzerine gelindiğinde X Ekseni'ni 12deg eğme
- `.hover:skew-x-6` - Fareyle üzerine gelindiğinde X Ekseni'ni 6deg eğme
- `.hover:skew-x-3` - Fareyle üzerine gelindiğinde X Ekseni'ni 3deg eğme
- `.hover:skew-x-0` - Fareyle üzerine gelindiğinde X Ekseni'ni 0deg eğme
- `.skew-x-12` - Eğik X Ekseni 12deg
- `.skew-x-6` - Eğik X Ekseni 6deg
- `.skew-x-3` - Eğik X Ekseni 3deg
- `.skew-x-0` - X Ekseni Eğriltme 0deg

##### Negative Skew X-Axis

- `.-skew-x-12` - Negatif Eğimli X Ekseni 12deg
- `.-skew-x-6` - Negatif Eğimli X Ekseni 6deg
- `.-skew-x-3` - Negatif Eğimli X Ekseni 3deg
- `.hover:-skew-x-12` - Negatif Eğik X Ekseni 12deg fareyle üzerine gelindiğinde
- `.hover:-skew-x-6` - Negatif Eğik X Ekseni 6deg fareyle üzerine gelindiğinde
- `.hover:-skew-x-3` - Negatif Eğik X Ekseni 3deg fareyle üzerine gelindiğinde

#### Skew Y-Axis

- `.hover:skew-y-12` - Fareyle üzerine gelindiğinde Y Ekseni'ni 12deg eğme
- `.hover:skew-y-6` - Fareyle üzerine gelindiğinde Y Ekseni'ni 6deg eğme
- `.hover:skew-y-3` - Fareyle üzerine gelindiğinde Y Ekseni'ni 3deg eğme
- `.hover:skew-y-0` - Fareyle üzerine gelindiğinde Y Eksenini 0deg eğme
- `.skew-y-12` - Eğik Y Ekseni 12deg
- `.skew-y-6` - Eğik Y Ekseni 6deg
- `.skew-y-3` - Eğik Y Ekseni 3deg
- `.skew-y-0` - Eğik Y Ekseni 0deg

##### Negative Skew Y-Axis

- `.-skew-y-12` - Negatif Eğik Y Ekseni 12deg
- `.-skew-y-6` - Negatif Eğik Y Ekseni 6deg
- `.-skew-y-3` - Negatif Eğik Y Ekseni 3deg
- `.hover:-skew-y-12` - Vurguluyken Negatif Eğik Y Ekseni 12deg
- `.hover:-skew-y-6` - Vurguluyken Negatif Eğik Y Ekseni 6deg
- `.hover:-skew-y-3` - Negatif Eğik Y Ekseni 3deg fareyle üzerine gelindiğinde

### Translate

- `.hover:translate-50` - Fareyle üzerine gelindiğinde %50 çevirin
- `.hover:translate-25` - Fareyle üzerine gelindiğinde %25 çevirin
- `.translate-50` - %50 çevir
- `.translate-25` - %25 çevir

##### Negative Translate

- `.-translate-50` - Negatif Çevirme %50
- `.-translate-25` - Negatif Çevirme %25
- `.hover:-translate-50` - Negatif Çevirme %50 fareyle üzerine gelindiğinde
- `.hover:-translate-25` - Negatif Çevirme %25 fareyle üzerine gelindiğinde

#### Translate X-Axis

- `.hover:translate-x-50` - Fareyle üzerine gelindiğinde X Ekseni %50 çevirin
- `.hover:translate-x-25` - Fareyle üzerine gelindiğinde X Ekseni %25 çevirin
- `.hover:translate-x-2` - Fareyle üzerine gelindiğinde X Ekseni 2rem'i çevirin
- `.hover:translate-x-1.5` - Fareyle üzerine gelindiğinde X Ekseni 0rem'i çevirin
- `.hover:translate-x-1` - Fareyle üzerine gelindiğinde X Ekseni 1rem'i çevirin
- `.hover:translate-x-0.5` - Fareyle üzerine gelindiğinde X Ekseni 0,5rem'i çevirin
- `.hover:translate-x-0` - Fareyle üzerine gelindiğinde X Ekseni 0rem'i çevirin
- `.translate-x-50` - X Ekseni %50 çevir
- `.translate-x-25` - X Ekseni %25 çevir
- `.translate-x-2` - X Ekseni 2rem'i çevir
- `.translate-x-1.5` - X Ekseni 0rem'i Çevir
- `.translate-x-1` - X Ekseni 1rem'i Çevir
- `.translate-x-0.5` - X Eksenini 0,5rem Çevir
- `.translate-x-0` - X Ekseni 0rem'i Çevir

##### Negative Translate X-Axis

- `.-translate-x-50` - Negatif Çevirme X Ekseni %50
- `.-translate-x-25` - Negatif Öteleme X Ekseni %25
- `.-translate-x-2` - Negatif Öteleme X Ekseni 2rem
- `.-translate-x-1.5` - Negatif Öteleme X Ekseni 1,5rem
- `.-translate-x-1` - Negatif Öteleme X Ekseni 1rem
- `.-translate-x-0.5` - Negatif Öteleme X Ekseni 0,5rem
- `.hover:-translate-x-50` - Negatif Çevirme X Ekseni %50 fareyle üzerine gelindiğinde
- `.hover:-translate-x-25` - Negatif Çevirme X Ekseni %25 fareyle üzerine gelindiğinde
- `.hover:-translate-x-2` - Negatif Çevirme X Ekseni 2rem fareyle üzerine gelindiğinde
- `.hover:-translate-x-1.5` - Negatif Çevirme X Ekseni 1,5rem fareyle üzerine gelindiğinde
- `.hover:-translate-x-1` - Negatif Çevirme X Ekseni 1rem fareyle üzerine gelindiğinde
- `.hover:-translate-x-0.5` - Negatif Çevirme X Ekseni 0,5rem fareyle üzerine gelindiğinde

#### Translate Y-Axis

- `.hover:translate-y-50` - Fareyle üzerine gelindiğinde Y Eksenini %50 çevir
- `.hover:translate-y-25` - Fareyle üzerine gelindiğinde Y Ekseni %25 çevirin
- `.hover:translate-y-2` - Fareyle üzerine gelindiğinde Y Ekseni 2rem'i çevirin
- `.hover:translate-y-1.5` - Fareyle üzerine gelindiğinde Y Ekseni 0rem'i çevirin
- `.hover:translate-y-1` - Fareyle üzerine gelindiğinde Y Ekseni 1rem'i çevirin
- `.hover:translate-y-0.5` - Fareyle üzerine gelindiğinde Y Ekseni 0,5rem'i çevirin
- `.hover:translate-y-0` - Fareyle üzerine gelindiğinde Y Ekseni 0rem'i çevirin
- `.translate-y-50` - Y Ekseni %50 Çevir
- `.translate-y-25` - Y Ekseni %25 Çevir
- `.translate-y-2` - Y Ekseni 2rem'i Çevir
- `.translate-y-1.5` - Y Ekseni 0rem'i Çevir
- `.translate-y-1` - Y Ekseni 1rem'i Çevir
- `.translate-y-0.5` - Y Eksenini 0,5rem Çevir
- `.translate-y-0` - Y Ekseni 0rem'i Çevir

##### Negative Translate Y-Axis

- `.-translate-y-50` - Negatif Çevirme Y Ekseni %50
- `.-translate-y-25` - Negatif Çevirme Y Ekseni %25
- `.-translate-y-2` - Negatif Öteleme Y Ekseni 2rem
- `.-translate-y-1.5` - Negatif Çevirme Y Ekseni 1,5rem
- `.-translate-y-1` - Negatif Öteleme Y Ekseni 1rem
- `.-translate-y-0.5` - Negatif Çevirme Y Ekseni 0,5rem
- `.hover:-translate-y-50` - Negatif Çevirme Y Ekseni %50 fareyle üzerine gelindiğinde
- `.hover:-translate-y-25` - Negatif Çevirme Y Ekseni %25 fareyle üzerine gelindiğinde
- `.hover:-translate-y-2` - Negatif Çevirme Y Ekseni 2rem fareyle üzerine gelindiğinde
- `.hover:-translate-y-1.5` - Negatif Çevirme Y Ekseni 1,5rem fareyle üzerine gelindiğinde
- `.hover:-translate-y-1` - Negatif Çevirme Y Ekseni 1rem fareyle üzerine gelindiğinde
- `.hover:-translate-y-0.5` - Negatif Çevirme Y Ekseni 0,5rem fareyle üzerine gelindiğinde

### Zoom

- `.hover:zoom` - Vurguluyken yakınlaştır
- `.hover:zoom-2` - Vurguluyken 2 yakınlaştır
- `.hover:zoom-1.5` - Fareyle üzerine gelindiğinde 1,5 yakınlaştırma
- `.zoom` - Yakınlaştır
- `.zoom-2` - Yakınlaştırma 2
- `.zoom-1.5` - Yakınlaştırma 1,5

## Colors

### Black

- `.black` - Siyah

### Dark

- `.dark` - Karanlık

### Light

- `.light` - Işık

### Transparent

- `.transparent` - Şeffaf

## Interactivity

### Cursor

- `.cursor-alias` - İmleç takma adı
- `.cursor-all-scroll` - İmlecin tamamını kaydırma
- `.cursor-auto` - Otomatik imleç
- `.cursor-cell` - İmleç hücresi
- `.cursor-col-resize` - İmleci yeniden boyutlandır
- `.cursor-context-menu` - İmleç içerik menüsü
- `.cursor-copy` - İmleç kopyası
- `.cursor-crosshair` - İmleç artı işareti
- `.cursor-default` - İmleç
- `.cursor-e-resize` - İmleç e-yeniden boyutlandırma
- `.cursor-ew-resize` - İmleç yeni-yeniden boyutlandır
- `.cursor-grab` - İmleç yakalama
- `.cursor-grabbing` - İmleç yakalama
- `.cursor-help` - İmleç yardımı
- `.cursor-move` - İmleç hareketi
- `.cursor-n-resize` - İmleç n-yeniden boyutlandırma
- `.cursor-ne-resize` - İmleci yeniden boyutlandır
- `.cursor-nesw-resize` - İmleç haber-yeniden boyutlandırma
- `.cursor-no-drop` - İmleç düşmeden
- `.cursor-none` - İmleç yok
- `.cursor-not-allowed` - İmlece izin verilmiyor
- `.cursor-ns-resize` - İmleç ns-yeniden boyutlandırma
- `.cursor-nw-resize` - İmleç yeni boyutlandırma
- `.cursor-nwse-resize` - İmleç nwse-yeniden boyutlandır
- `.cursor-pointer` - İmleç işaretçisi
- `.cursor-progress` - İmleç ilerlemesi
- `.cursor-row-resize` - İmleç satırını yeniden boyutlandırma
- `.cursor-s-resize` - İmleç s-yeniden boyutlandırma
- `.cursor-se-resize` - İmleci yeniden boyutlandır
- `.cursor-sw-resize` - İmleç sw-yeniden boyutlandırma
- `.cursor-text` - İmleç metni
- `.cursor-vertical-text` - İmleç dikey metni
- `.cursor-w-resize` - İmleç w-yeniden boyutlandırma
- `.cursor-wait` - İmleç bekle
- `.cursor-zoom-in` - İmleç yakınlaştırma
- `.cursor-zoom-out` - İmleç uzaklaştırma

### Disabled

- `.disabled` - Engelli

### Resize

- `.resize` - Yeniden boyutlandır
- `.resize-none` - Hiçbirini yeniden boyutlandırma
- `.resize-x` - X'i yeniden boyutlandır
- `.resize-y` - Y'yi yeniden boyutlandır

### Select

- `.select-auto` - Otomatik seç
- `.select-none` - Hiçbirini seçme

## Misc

### Content

- `.content-3` - İçerik 3
- `.content-3-bg` - İçerik 3-bg
- `.content-2` - İçerik 2
- `.content-2-bg` - İçerik 2-bg
- `.content-2-text` - İçerik 2-text
- `.content-1` - İçerik 1
- `.content-1-bg` - İçerik 1-bg
- `.content-1-text` - İçerik 1-text
- `.hover:content-3-bg` - İçerik 3-bg fareyle üzerine gelindiğinde
- `.hover:content-2-bg` - İçerik 2-bg fareyle üzerine gelindiğinde
- `.hover:content-2-text` - İçerik üzerine gelindiğinde 2-text
- `.hover:content-1-bg` - İçerik 1-bg fareyle üzerine gelindiğinde
- `.hover:content-1-text` - Fareyle üzerine gelindiğinde içerik 1-text

### Dir

- `.dir-ltr` - Yön ltr
- `.dir-rtl` - Sen rtl

### Mse

- `.hover:mse-2` - Fareyle üzerine gelindiğinde Mse 2rem
- `.hover:mse-1.5` - Fareyle üzerine gelindiğinde Mse 1,5rem
- `.hover:mse-1` - Fareyle üzerine gelindiğinde Mse 1rem
- `.hover:mse-0.5` - Fareyle üzerine gelindiğinde Mse 0,5rem
- `.hover:mse-0` - Fareyle üzerine gelindiğinde Mse 0rem
- `.mse-2` - Mse 2rem
- `.mse-1.5` - Mse 1,5rem
- `.mse-1` - Mse 1rem
- `.mse-0.5` - Mse 0,5rem
- `.mse-0` - Mse 0rem

### Visibility

- `.hover:v-hide` - Fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:v-show` - Fareyle üzerine gelindiğinde görünürlük
- `.v-hide` - Görünürlük gizlendi
- `.v-show` - Görünürlük görünür

##### Visibility - Mobile (≤ 480px)

- `.hover:mobile:v-hide` - Mobil cihazda fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:mobile:v-show` - Mobil cihazda fareyle üzerine gelindiğinde görünürlük
- `.mobile:v-hide` - Görünürlük mobilde gizlendi
- `.mobile:v-show` - Mobil cihazlarda görünürlük

##### Visibility - Tablet (480px - 768px)

- `.hover:tablet:v-hide` - Tabletin üzerine gelindiğinde görünürlük gizlendi
- `.hover:tablet:v-show` - Görünürlük tabletin üzerine gelindiğinde görünür
- `.tablet:v-hide` - Görünürlük tablette gizlendi
- `.tablet:v-show` - Görünürlük tablette görülebilir

##### Visibility - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:v-hide` - Tablet bilgisayarda fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:tablet-pc:v-show` - Tablet PC'nin üzerine gelindiğinde görünürlük
- `.tablet-pc:v-hide` - Görünürlük tablet bilgisayarda gizlendi
- `.tablet-pc:v-show` - Tablet PC'de görünürlük

##### Visibility - Pc (992px - 1200px)

- `.hover:pc:v-hide` - PC'de fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:pc:v-show` - PC'de fareyle üzerine gelindiğinde görünürlük
- `.pc:v-hide` - Görünürlük bilgisayarda gizlendi
- `.pc:v-show` - PC'de görünürlük

##### Visibility - Tv (≥ 1200px)

- `.hover:tv:v-hide` - Televizyonun üzerine gelindiğinde görünürlük gizlendi
- `.hover:tv:v-show` - Televizyonun üzerine gelindiğinde görünürlük
- `.tv:v-hide` - Görünürlük televizyonda gizlendi
- `.tv:v-show` - TV'de görünürlük

##### Visibility - Tablet Max (≤ 768px)

- `.hover:tablet-max:v-hide` - Maksimum tablette fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:tablet-max:v-show` - Maksimum tabletin üzerine gelindiğinde görünürlük
- `.tablet-max:v-hide` - Tablet max'te görünürlük gizlendi
- `.tablet-max:v-show` - Görünürlük tablet max'ta görünür

##### Visibility - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:v-hide` - Tablet PC Max'te fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:tablet-pc-max:v-show` - Tablet PC max'ta fareyle üzerine gelindiğinde görünürlük
- `.tablet-pc-max:v-hide` - Tablet PC Max'te görünürlük gizlendi
- `.tablet-pc-max:v-show` - Tablet PC max'ta görünürlük

##### Visibility - Pc Max (≤ 1200px)

- `.hover:pc-max:v-hide` - PC max'ta fareyle üzerine gelindiğinde görünürlük gizlendi
- `.hover:pc-max:v-show` - PC max'ta fareyle üzerine gelindiğinde görünürlük
- `.pc-max:v-hide` - PC max'ta görünürlük gizlendi
- `.pc-max:v-show` - PC max'ta görünürlük

### Customization

bClass, tema oluşturmak için CSS değişkenlerini kullanır:

- `--plainBg` - Düz arka plan rengi
- `--contentBg` - İçerik arka plan rengi
- `--contentBgPrimary` - Birincil içerik arka planı
- `--contentBgSecondary` - İkincil içerik arka planı
- `--contentTextPrimary` - Birincil metin rengi
- `--contentTextSecondary` - İkincil metin rengi
- `--headerBg` - Başlık arka plan rengi

### License

> Bik Kamu Lisansı 2.0 Lisansı altında dağıtılmaktadır. Daha fazla bilgi için [LICENSE](./../../../LICENSE) adresine bakın.
