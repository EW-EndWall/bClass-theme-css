# bClass theme css

مكتبة شاملة لتطوير واجهات المواقع والتطبيقات.

## Requirements

يوصى باستخدام `bClass theme js`، `bClass theme colors`، `bClass components`، `bClass animations` و `bClass media player` مع هذه المكتبة.

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
- [Other](#other)
- [Visibility](#visibility)
- [Customization](#customization)
- [License](#license)

---

## Layout

### Container

- `.container` - حاوية

### Display

- `.d-block` - كتلة العرض
- `.d-contents` - عرض المحتويات
- `.d-flex` - عرض مرن
- `.d-flow-root` - عرض جذر التدفق
- `.d-grid` - شبكة العرض
- `.d-inline` - عرض مضمنة
- `.d-inline-block` - عرض الكتلة المضمنة
- `.d-inline-flex` - عرض مضمنة المرن
- `.d-inline-grid` - عرض الشبكة المضمنة
- `.d-inline-table` - عرض الجدول المضمن
- `.d-list-item` - عرض عنصر القائمة
- `.d-none` - عرض لا شيء
- `.d-table` - عرض الجدول
- `.d-table-caption` - عرض التسمية التوضيحية للجدول
- `.d-table-cell` - عرض خلية الجدول
- `.d-table-col` - عرض الجدول العقيد
- `.d-table-col-group` - عرض جدول المجموعة
- `.d-table-footer-group` - عرض مجموعة تذييل الجدول
- `.d-table-header-group` - عرض مجموعة رأس الجدول
- `.d-table-row` - عرض صف الجدول
- `.d-table-row-group` - عرض مجموعة صفوف الجدول
- `.hover:d-block` - عرض الكتلة عند التمرير
- `.hover:d-flex` - عرض المرن عند التمرير
- `.hover:d-inline` - عرض مضمن عند التمرير
- `.hover:d-inline-block` - عرض الكتلة المضمنة عند التمرير
- `.hover:d-inline-flex` - عرض المرن المضمن عند التمرير
- `.hover:d-none` - عرض لا شيء عند التمرير

##### Display - Mobile (< 480px)

- `.hover:mobile:d-block` - عرض الكتلة عند التمرير على الهاتف المحمول
- `.hover:mobile:d-flex` - عرض مرن عند التمرير على الهاتف المحمول
- `.hover:mobile:d-inline` - عرض مضمن عند التمرير على الهاتف المحمول
- `.hover:mobile:d-inline-block` - عرض الكتلة المضمنة عند التمرير على الهاتف المحمول
- `.hover:mobile:d-inline-flex` - عرض المرن المضمّن عند التمرير على الهاتف المحمول
- `.hover:mobile:d-none` - لا يتم عرض أي شيء عند التمرير على الهاتف المحمول
- `.mobile:d-block` - عرض الكتلة على الهاتف المحمول
- `.mobile:d-flex` - عرض المرن على الهاتف المحمول
- `.mobile:d-grid` - عرض الشبكة على الهاتف المحمول
- `.mobile:d-inline` - عرض مضمنة على الهاتف المحمول
- `.mobile:d-inline-block` - عرض الكتلة المضمنة على الهاتف المحمول
- `.mobile:d-inline-flex` - عرض مضمنة المرن على الهاتف المحمول
- `.mobile:d-inline-grid` - عرض الشبكة المضمنة على الهاتف المحمول
- `.mobile:d-none` - عرض لا شيء على الهاتف المحمول

##### Display - Tablet (480px - 768px)

- `.hover:tablet:d-block` - عرض الكتلة عند التمرير على الجهاز اللوحي
- `.hover:tablet:d-flex` - عرض مرن عند التمرير على الجهاز اللوحي
- `.hover:tablet:d-inline` - عرض مضمن عند التمرير على الجهاز اللوحي
- `.hover:tablet:d-inline-block` - عرض الكتلة المضمنة عند التمرير على الجهاز اللوحي
- `.hover:tablet:d-inline-flex` - عرض المرن المضمّن عند التمرير على الجهاز اللوحي
- `.hover:tablet:d-none` - لا يتم عرض أي شيء عند التمرير على الجهاز اللوحي
- `.tablet:d-block` - عرض الكتلة على الجهاز اللوحي
- `.tablet:d-flex` - عرض المرن على الكمبيوتر اللوحي
- `.tablet:d-grid` - عرض الشبكة على الجهاز اللوحي
- `.tablet:d-inline` - عرض مضمنة على الجهاز اللوحي
- `.tablet:d-inline-block` - عرض الكتلة المضمنة على الجهاز اللوحي
- `.tablet:d-inline-flex` - عرض مضمنة المرن على الكمبيوتر اللوحي
- `.tablet:d-inline-grid` - عرض الشبكة المضمنة على الجهاز اللوحي
- `.tablet:d-none` - عرض لا شيء على الجهاز اللوحي

##### Display - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:d-block` - عرض الكتلة عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:d-flex` - عرض المرن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:d-inline` - عرض مضمّن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:d-inline-block` - عرض الكتلة المضمنة عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:d-inline-flex` - عرض المرن المضمن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:d-none` - لا يتم عرض أي شيء عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:d-block` - عرض الكتلة على الكمبيوتر اللوحي
- `.tablet-pc:d-flex` - عرض المرن على الكمبيوتر اللوحي
- `.tablet-pc:d-grid` - عرض الشبكة على الكمبيوتر اللوحي
- `.tablet-pc:d-inline` - عرض مضمنة على الكمبيوتر اللوحي
- `.tablet-pc:d-inline-block` - عرض الكتلة المضمنة على الكمبيوتر اللوحي
- `.tablet-pc:d-inline-flex` - عرض مضمنة فليكس على الكمبيوتر اللوحي
- `.tablet-pc:d-inline-grid` - عرض الشبكة المضمنة على الكمبيوتر اللوحي
- `.tablet-pc:d-none` - عرض لا شيء على الكمبيوتر اللوحي

##### Display - Pc (992px - 1200px)

- `.hover:pc:d-block` - عرض الكتلة عند التمرير على جهاز الكمبيوتر
- `.hover:pc:d-flex` - عرض المرن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:d-inline` - عرض مضمن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:d-inline-block` - عرض الكتلة المضمنة عند التمرير على جهاز الكمبيوتر
- `.hover:pc:d-inline-flex` - عرض المرن المضمن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:d-none` - عرض لا شيء عند التمرير على جهاز الكمبيوتر
- `.pc:d-block` - عرض الكتلة على جهاز الكمبيوتر
- `.pc:d-flex` - عرض فليكس على جهاز الكمبيوتر
- `.pc:d-grid` - عرض الشبكة على جهاز الكمبيوتر
- `.pc:d-inline` - عرض مضمن على جهاز الكمبيوتر
- `.pc:d-inline-block` - عرض الكتلة المضمنة على جهاز الكمبيوتر
- `.pc:d-inline-flex` - عرض مضمنة فليكس على جهاز الكمبيوتر
- `.pc:d-inline-grid` - عرض الشبكة المضمنة على جهاز الكمبيوتر
- `.pc:d-none` - عرض لا شيء على جهاز الكمبيوتر

##### Display - Tv (> 1200px)

- `.hover:tv:d-block` - عرض الكتلة عند التمرير على شاشة التلفزيون
- `.hover:tv:d-flex` - عرض المرن على التمرير على شاشة التلفزيون
- `.hover:tv:d-inline` - عرض مضمن عند التمرير على شاشة التلفزيون
- `.hover:tv:d-inline-block` - عرض الكتلة المضمنة عند التمرير على شاشة التلفزيون
- `.hover:tv:d-inline-flex` - عرض المرن المضمن عند التمرير على شاشة التلفزيون
- `.hover:tv:d-none` - عرض لا شيء على التمرير على شاشة التلفزيون
- `.tv:d-block` - كتلة العرض على شاشة التلفزيون
- `.tv:d-flex` - عرض فليكس على شاشة التلفزيون
- `.tv:d-grid` - شبكة العرض على شاشة التلفزيون
- `.tv:d-inline` - عرض مضمن على شاشة التلفزيون
- `.tv:d-inline-block` - عرض الكتلة المضمنة على شاشة التلفزيون
- `.tv:d-inline-flex` - عرض مضمنة فليكس على شاشة التلفزيون
- `.tv:d-inline-grid` - عرض الشبكة المضمنة على شاشة التلفزيون
- `.tv:d-none` - عرض لا شيء على شاشة التلفزيون

##### Display - Tablet Max (< 768px)

- `.hover:tablet-max:d-block` - عرض الكتلة عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:d-flex` - عرض مرن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:d-inline` - عرض مضمّن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:d-inline-block` - عرض الكتلة المضمنة عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:d-inline-flex` - عرض المرن المضمّن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:d-none` - لا يتم عرض أي شيء عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:d-block` - عرض الكتلة على الجهاز اللوحي بحد أقصى
- `.tablet-max:d-flex` - عرض المرن على الكمبيوتر اللوحي بحد أقصى
- `.tablet-max:d-grid` - عرض الشبكة على الكمبيوتر اللوحي بحد أقصى
- `.tablet-max:d-inline` - عرض مضمن على الجهاز اللوحي بحد أقصى
- `.tablet-max:d-inline-block` - عرض الكتلة المضمنة على الجهاز اللوحي بحد أقصى
- `.tablet-max:d-inline-flex` - عرض مضمّن مرن على الجهاز اللوحي بحد أقصى
- `.tablet-max:d-inline-grid` - عرض الشبكة المضمنة على الجهاز اللوحي بحد أقصى
- `.tablet-max:d-none` - عرض لا شيء على الجهاز اللوحي كحد أقصى

##### Display - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:d-block` - عرض الكتلة عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:d-flex` - عرض مرن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:d-inline` - عرض مضمّن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:d-inline-block` - عرض الكتلة المضمنة عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:d-inline-flex` - عرض المرن المضمن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:d-none` - لا يتم عرض أي شيء عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:d-block` - كتلة العرض على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:d-flex` - عرض المرن على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:d-grid` - عرض الشبكة على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:d-inline` - عرض مضمن على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:d-inline-block` - عرض الكتلة المضمنة على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:d-inline-flex` - عرض مضمّن مرن على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:d-inline-grid` - عرض الشبكة المضمنة على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:d-none` - عرض لا شيء على الكمبيوتر اللوحي كحد أقصى

##### Display - Pc Max (< 1200px)

- `.hover:pc-max:d-block` - عرض الكتلة عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:d-flex` - عرض مرن عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:d-inline` - عرض مضمن عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:d-inline-block` - عرض الكتلة المضمنة عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:d-inline-flex` - عرض المرن المضمن عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:d-none` - عرض لا شيء عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-block` - عرض الكتلة على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-flex` - عرض المرن على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-grid` - عرض الشبكة على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-inline` - عرض مضمن على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-inline-block` - عرض الكتلة المضمنة على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-inline-flex` - عرض مضمّن مرن على جهاز الكمبيوتر بحد أقصى
- `.pc-max:d-inline-grid` - عرض الشبكة المضمنة على جهاز الكمبيوتر كحد أقصى
- `.pc-max:d-none` - عرض لا شيء على جهاز الكمبيوتر كحد أقصى

### Float

- `.float-end` - نهاية تعويم
- `.float-left` - تطفو إلى اليسار
- `.float-none` - لا تطفو
- `.float-right` - تطفو على اليمين
- `.float-start` - تعويم البداية
- `.hover:float-end` - نهاية تعويم عند التحويم
- `.hover:float-left` - تعويم اليسار على التحويم
- `.hover:float-none` - تعويم لا شيء عند التمرير
- `.hover:float-right` - تطفو على اليمين عند التمرير
- `.hover:float-start` - تعويم البدء عند التحويم

##### Float - Mobile (< 480px)

- `.hover:mobile:float-end` - تعويم النهاية عند التمرير على الهاتف المحمول
- `.hover:mobile:float-left` - تعويم لليسار عند التمرير على الهاتف المحمول
- `.hover:mobile:float-none` - تعويم لا شيء عند التمرير على الهاتف المحمول
- `.hover:mobile:float-right` - تطفو مباشرة عند التمرير على الهاتف المحمول
- `.hover:mobile:float-start` - تعويم البدء عند التمرير على الهاتف المحمول
- `.mobile:float-end` - نهاية تعويم على الهاتف المحمول
- `.mobile:float-left` - تعويم اليسار على الهاتف المحمول
- `.mobile:float-none` - لا تطفو على الهاتف المحمول
- `.mobile:float-right` - تطفو مباشرة على الهاتف المحمول
- `.mobile:float-start` - تعويم البداية على الهاتف المحمول

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - تعويم النهاية عند التمرير على الجهاز اللوحي
- `.hover:tablet:float-left` - تطفو على اليسار عند التمرير على الجهاز اللوحي
- `.hover:tablet:float-none` - لا تطفو على الإطلاق عند التمرير على الجهاز اللوحي
- `.hover:tablet:float-right` - تطفو مباشرة عند التمرير على الجهاز اللوحي
- `.hover:tablet:float-start` - تعويم البدء عند التمرير على الجهاز اللوحي
- `.tablet:float-end` - نهاية تعويم على الجهاز اللوحي
- `.tablet:float-left` - تطفو على اليسار على الجهاز اللوحي
- `.tablet:float-none` - لا تطفو على الجهاز اللوحي
- `.tablet:float-right` - تطفو مباشرة على الجهاز اللوحي
- `.tablet:float-start` - تعويم البداية على الكمبيوتر اللوحي

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - تعويم النهاية عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:float-left` - تطفو على اليسار عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:float-none` - تعويم لا شيء عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:float-right` - تطفو مباشرة عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:float-start` - تعويم البدء عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:float-end` - نهاية تعويم على الكمبيوتر اللوحي
- `.tablet-pc:float-left` - تطفو على اليسار على الكمبيوتر اللوحي
- `.tablet-pc:float-none` - لا تطفو على الكمبيوتر اللوحي
- `.tablet-pc:float-right` - تطفو مباشرة على الكمبيوتر اللوحي
- `.tablet-pc:float-start` - تعويم البداية على الكمبيوتر اللوحي

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - تعويم النهاية عند التمرير على جهاز الكمبيوتر
- `.hover:pc:float-left` - تطفو على اليسار عند التمرير على جهاز الكمبيوتر
- `.hover:pc:float-none` - تعويم لا شيء عند التمرير على جهاز الكمبيوتر
- `.hover:pc:float-right` - تطفو مباشرة عند التمرير على جهاز الكمبيوتر
- `.hover:pc:float-start` - تعويم البدء عند التمرير على جهاز الكمبيوتر
- `.pc:float-end` - نهاية تعويم على جهاز الكمبيوتر
- `.pc:float-left` - تطفو على اليسار على جهاز الكمبيوتر
- `.pc:float-none` - لا تطفو على جهاز الكمبيوتر
- `.pc:float-right` - تطفو مباشرة على جهاز الكمبيوتر
- `.pc:float-start` - تعويم البداية على جهاز الكمبيوتر

##### Float - Tv (> 1200px)

- `.hover:tv:float-end` - نهاية التعويم عند التمرير على شاشة التلفزيون
- `.hover:tv:float-left` - تطفو على اليسار عند التمرير على شاشة التلفزيون
- `.hover:tv:float-none` - لا شيء يطفو على التحويم على شاشة التلفزيون
- `.hover:tv:float-right` - تطفو مباشرة على التحويم على شاشة التلفزيون
- `.hover:tv:float-start` - تعويم البدء عند التمرير على شاشة التلفزيون
- `.tv:float-end` - تعويم النهاية على شاشة التلفزيون
- `.tv:float-left` - تطفو على اليسار على شاشة التلفزيون
- `.tv:float-none` - لا تطفو على شاشة التلفزيون
- `.tv:float-right` - تطفو مباشرة على شاشة التلفزيون
- `.tv:float-start` - تعويم البداية على شاشة التلفزيون

##### Float - Tablet Max (< 768px)

- `.hover:tablet-max:float-end` - تعويم النهاية عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:float-left` - تعويم لليسار عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:float-none` - تعويم لا شيء عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:float-right` - تطفو مباشرة عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:float-start` - تعويم البدء عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:float-end` - نهاية تعويم على الجهاز اللوحي بحد أقصى
- `.tablet-max:float-left` - تعويم اليسار على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:float-none` - تعويم لا شيء على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:float-right` - تطفو مباشرة على الجهاز اللوحي بحد أقصى
- `.tablet-max:float-start` - تعويم البداية على الكمبيوتر اللوحي كحد أقصى

##### Float - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:float-end` - تعويم النهاية عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:float-left` - تعويم لليسار عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:float-none` - تعويم لا شيء عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:float-right` - تطفو مباشرة عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:float-start` - تعويم البدء عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:float-end` - نهاية تعويم على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:float-left` - تعويم اليسار على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:float-none` - تعويم لا شيء على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:float-right` - تطفو مباشرة على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:float-start` - تعويم البداية على الكمبيوتر اللوحي كحد أقصى

##### Float - Pc Max (< 1200px)

- `.hover:pc-max:float-end` - تعويم نهاية عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:float-left` - تعويم لليسار عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:float-none` - تعويم لا شيء عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:float-right` - تطفو مباشرة عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:float-start` - تعويم البدء عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:float-end` - نهاية تعويم على جهاز الكمبيوتر كحد أقصى
- `.pc-max:float-left` - تعويم اليسار على جهاز الكمبيوتر كحد أقصى
- `.pc-max:float-none` - تعويم لا شيء على جهاز الكمبيوتر كحد أقصى
- `.pc-max:float-right` - تطفو مباشرة على جهاز الكمبيوتر كحد أقصى
- `.pc-max:float-start` - تعويم البداية على جهاز الكمبيوتر كحد أقصى

### Object

- `.hover:object-contain` - يحتوي الكائن على التمرير
- `.hover:object-cover` - غطاء الكائن عند التمرير
- `.hover:object-fill` - تعبئة الكائن عند التمرير
- `.hover:object-none` - لا يوجد كائن عند التمرير
- `.hover:object-scale` - مقياس الكائن عند التمرير
- `.object-contain` - يحتوي الكائن
- `.object-cover` - غطاء الكائن
- `.object-fill` - تعبئة الكائن
- `.object-none` - لا شيء
- `.object-scale` - مقياس الكائن

##### Object - Mobile (< 480px)

- `.hover:mobile:object-contain` - يحتوي الكائن على التمرير على الهاتف المحمول
- `.hover:mobile:object-cover` - غطاء الكائن عند التمرير على الهاتف المحمول
- `.hover:mobile:object-fill` - تعبئة الكائن عند التمرير على الهاتف المحمول
- `.hover:mobile:object-none` - لا يوجد كائن عند التمرير على الهاتف المحمول
- `.hover:mobile:object-scale` - مقياس الكائن عند التمرير على الهاتف المحمول
- `.mobile:object-contain` - يحتوي الكائن على الهاتف المحمول
- `.mobile:object-cover` - تغطية الكائن على الهاتف المحمول
- `.mobile:object-fill` - تعبئة الكائنات على الهاتف المحمول
- `.mobile:object-none` - لا يوجد اعتراض على الهاتف المحمول
- `.mobile:object-scale` - مقياس الكائن على الهاتف المحمول

##### Object - Tablet (480px - 768px)

- `.hover:tablet:object-contain` - يحتوي الكائن على التمرير على الجهاز اللوحي
- `.hover:tablet:object-cover` - غطاء الكائن عند التمرير على الجهاز اللوحي
- `.hover:tablet:object-fill` - تعبئة الكائن عند التمرير على الجهاز اللوحي
- `.hover:tablet:object-none` - لا يوجد كائن عند التمرير على الجهاز اللوحي
- `.hover:tablet:object-scale` - مقياس الكائن عند التمرير على الجهاز اللوحي
- `.tablet:object-contain` - كائن يحتوي على الكمبيوتر اللوحي
- `.tablet:object-cover` - غطاء الكائن على الجهاز اللوحي
- `.tablet:object-fill` - تعبئة الكائن على الجهاز اللوحي
- `.tablet:object-none` - لا يوجد كائن على الجهاز اللوحي
- `.tablet:object-scale` - مقياس الكائن على الجهاز اللوحي

##### Object - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:object-contain` - يحتوي الكائن على التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:object-cover` - غطاء الكائن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:object-fill` - تعبئة الكائن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:object-none` - لا يوجد كائن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:object-scale` - مقياس الكائن عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:object-contain` - الكائن يحتوي على الكمبيوتر اللوحي
- `.tablet-pc:object-cover` - غطاء الكائن على الكمبيوتر اللوحي
- `.tablet-pc:object-fill` - تعبئة الكائنات على الكمبيوتر اللوحي
- `.tablet-pc:object-none` - لا يوجد كائن على الكمبيوتر اللوحي
- `.tablet-pc:object-scale` - مقياس الكائن على الكمبيوتر اللوحي

##### Object - Pc (992px - 1200px)

- `.hover:pc:object-contain` - يحتوي الكائن على التمرير على جهاز الكمبيوتر
- `.hover:pc:object-cover` - غطاء الكائن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:object-fill` - ملء الكائن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:object-none` - لا يوجد كائن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:object-scale` - مقياس الكائن عند التمرير على جهاز الكمبيوتر
- `.pc:object-contain` - كائن يحتوي على جهاز الكمبيوتر
- `.pc:object-cover` - غلاف الكائن على جهاز الكمبيوتر
- `.pc:object-fill` - تعبئة الكائنات على جهاز الكمبيوتر
- `.pc:object-none` - لا يوجد كائن على جهاز الكمبيوتر
- `.pc:object-scale` - مقياس الكائن على جهاز الكمبيوتر

##### Object - Tv (> 1200px)

- `.hover:tv:object-contain` - يحتوي الكائن على التمرير على شاشة التلفزيون
- `.hover:tv:object-cover` - غطاء الكائن على التحويم على شاشة التلفزيون
- `.hover:tv:object-fill` - ملء الكائن عند التمرير على شاشة التلفزيون
- `.hover:tv:object-none` - لا شيء يعترض على التمرير على شاشة التلفزيون
- `.hover:tv:object-scale` - مقياس الكائن على التحويم على شاشة التلفزيون
- `.tv:object-contain` - كائن يحتوي على شاشة التلفزيون
- `.tv:object-cover` - غطاء الكائن على شاشة التلفزيون
- `.tv:object-fill` - كائن ملء على شاشة التلفزيون
- `.tv:object-none` - لا يعترض على أي شيء على شاشة التلفزيون
- `.tv:object-scale` - مقياس الكائن على شاشة التلفزيون

##### Object - Tablet Max (< 768px)

- `.hover:tablet-max:object-contain` - يحتوي الكائن على التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:object-cover` - غطاء الكائن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:object-fill` - تعبئة الكائن عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:object-none` - لا يوجد كائن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:object-scale` - مقياس الكائن عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:object-contain` - الكائن يحتوي على الكمبيوتر اللوحي بحد أقصى
- `.tablet-max:object-cover` - غطاء الكائن على الجهاز اللوحي كحد أقصى
- `.tablet-max:object-fill` - تعبئة الكائن على الجهاز اللوحي كحد أقصى
- `.tablet-max:object-none` - لا يوجد كائن على الجهاز اللوحي بحد أقصى
- `.tablet-max:object-scale` - مقياس الكائن على الجهاز اللوحي بحد أقصى

##### Object - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:object-contain` - يحتوي الكائن على التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:object-cover` - غطاء الكائن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:object-fill` - تعبئة الكائن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:object-none` - لا يوجد كائن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:object-scale` - مقياس الكائن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:object-contain` - الكائن يحتوي على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:object-cover` - غطاء الكائن على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:object-fill` - تعبئة الكائنات على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:object-none` - لا يوجد كائن على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:object-scale` - مقياس الكائن على الكمبيوتر اللوحي بحد أقصى

##### Object - Pc Max (< 1200px)

- `.hover:pc-max:object-contain` - يحتوي الكائن على التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:object-cover` - غطاء الكائن عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:object-fill` - تعبئة الكائن عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:object-none` - لا يوجد كائن عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:object-scale` - مقياس الكائن عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.pc-max:object-contain` - يحتوي الكائن على جهاز كمبيوتر كحد أقصى
- `.pc-max:object-cover` - غطاء الكائن على جهاز الكمبيوتر كحد أقصى
- `.pc-max:object-fill` - تعبئة الكائنات على جهاز الكمبيوتر كحد أقصى
- `.pc-max:object-none` - لا يوجد كائن على جهاز الكمبيوتر كحد أقصى
- `.pc-max:object-scale` - مقياس الكائن على جهاز الكمبيوتر كحد أقصى

### Overflow

- `.hover:overflow-scroll` - التمرير الفائض عند التمرير
- `.overflow-auto` - الفائض التلقائي
- `.overflow-clip` - مقطع الفائض
- `.overflow-hidden` - الفائض مخفي
- `.overflow-scroll` - التمرير الفائض
- `.overflow-visible` - تجاوز مرئية

### Overflow x

- `.hover:overflow-x-scroll` - تجاوز السعة × قم بالتمرير عند التمرير
- `.overflow-x-auto` - تجاوز السعة × تلقائي
- `.overflow-x-clip` - تجاوز × مقطع
- `.overflow-x-hidden` - تجاوز × مخفي
- `.overflow-x-scroll` - تجاوز السعة × التمرير
- `.overflow-x-visible` - الفائض × مرئي

### Overflow y

- `.hover:overflow-y-scroll` - تجاوز السعة وقم بالتمرير عند التمرير
- `.overflow-y-auto` - تجاوز السعة وتلقائيًا
- `.overflow-y-clip` - تجاوز ذ مقطع
- `.overflow-y-hidden` - تجاوز ذ مخفي
- `.overflow-y-scroll` - تجاوز السعة والتمرير
- `.overflow-y-visible` - تجاوز y مرئية

### Header

- `.header` - رأس

### Footer

- `.footer` - تذييل

## Flexbox

### Flex

- `.flex-col` - فليكس كول
- `.flex-nowrap` - فليكس الآن
- `.flex-row` - الصف المرن
- `.flex-wrap` - التفاف المرن
- `.hover:flex-col` - فليكس كول عند التمرير
- `.hover:flex-nowrap` - فليكس الآن عند التمرير
- `.hover:flex-row` - الصف المرن عند التمرير
- `.hover:flex-wrap` - التفاف مرن عند التحويم

##### Flex - Mobile (< 480px)

- `.hover:mobile:flex-col` - فليكس كول عند التمرير على الهاتف المحمول
- `.hover:mobile:flex-nowrap` - فليكس الآن عند التمرير على الهاتف المحمول
- `.hover:mobile:flex-row` - الصف المرن عند التمرير على الهاتف المحمول
- `.hover:mobile:flex-wrap` - التفاف مرن عند التمرير على الهاتف المحمول
- `.mobile:flex-col` - فليكس كول على الهاتف المحمول
- `.mobile:flex-nowrap` - فليكس الآنراب على الهاتف المحمول
- `.mobile:flex-row` - الصف المرن على الهاتف المحمول
- `.mobile:flex-wrap` - التفاف المرن على الهاتف المحمول

##### Flex - Tablet (480px - 768px)

- `.hover:tablet:flex-col` - عمود مرن عند التمرير على الجهاز اللوحي
- `.hover:tablet:flex-nowrap` - فليكس الآن عند التمرير على الجهاز اللوحي
- `.hover:tablet:flex-row` - الصف المرن عند التمرير على الجهاز اللوحي
- `.hover:tablet:flex-wrap` - التفاف مرن عند التمرير على الجهاز اللوحي
- `.tablet:flex-col` - فليكس كول على الجهاز اللوحي
- `.tablet:flex-nowrap` - فليكس الآن على الجهاز اللوحي
- `.tablet:flex-row` - الصف المرن على الجهاز اللوحي
- `.tablet:flex-wrap` - التفاف المرن على الكمبيوتر اللوحي

##### Flex - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col` - Flex col عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:flex-nowrap` - Flex nowrap on hover على الكمبيوتر اللوحي
- `.hover:tablet-pc:flex-row` - الصف المرن عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:flex-wrap` - التفاف مرن عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:flex-col` - فليكس كول على الكمبيوتر اللوحي
- `.tablet-pc:flex-nowrap` - Flex nowrap على الكمبيوتر اللوحي
- `.tablet-pc:flex-row` - الصف المرن على الكمبيوتر اللوحي
- `.tablet-pc:flex-wrap` - التفاف المرن على الكمبيوتر اللوحي

##### Flex - Pc (992px - 1200px)

- `.hover:pc:flex-col` - فليكس كول عند التمرير على جهاز الكمبيوتر
- `.hover:pc:flex-nowrap` - Flex nowrap عند التحويم على جهاز الكمبيوتر
- `.hover:pc:flex-row` - الصف المرن عند التمرير على جهاز الكمبيوتر
- `.hover:pc:flex-wrap` - التفاف مرن عند التمرير على جهاز الكمبيوتر
- `.pc:flex-col` - فليكس كول على جهاز الكمبيوتر
- `.pc:flex-nowrap` - فليكس الآنراب على جهاز الكمبيوتر
- `.pc:flex-row` - الصف المرن على جهاز الكمبيوتر
- `.pc:flex-wrap` - التفاف المرن على جهاز الكمبيوتر

##### Flex - Tv (> 1200px)

- `.hover:tv:flex-col` - فليكس كول عند التمرير على شاشة التلفزيون
- `.hover:tv:flex-nowrap` - فليكس الآن راب على التحويم على شاشة التلفزيون
- `.hover:tv:flex-row` - الصف المرن عند التمرير على شاشة التلفزيون
- `.hover:tv:flex-wrap` - التفاف المرن على التمرير على شاشة التلفزيون
- `.tv:flex-col` - فليكس كول على شاشة التلفزيون
- `.tv:flex-nowrap` - فليكس الآن على شاشة التلفزيون
- `.tv:flex-row` - الصف المرن على شاشة التلفزيون
- `.tv:flex-wrap` - التفاف المرن على شاشة التلفزيون

##### Flex - Tablet Max (< 768px)

- `.hover:tablet-max:flex-col` - عمود مرن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:flex-nowrap` - Flex nowrap عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:flex-row` - الصف المرن عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:flex-wrap` - التفاف مرن عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:flex-col` - فليكس كول على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:flex-nowrap` - Flex nowrap على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:flex-row` - الصف المرن على الجهاز اللوحي كحد أقصى
- `.tablet-max:flex-wrap` - غلاف مرن على الجهاز اللوحي بحد أقصى

##### Flex - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-col` - فليكس كول عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:flex-nowrap` - Flex nowrap on hover على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:flex-row` - الصف المرن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:flex-wrap` - التفاف مرن عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-col` - فليكس كول على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:flex-nowrap` - Flex nowrap على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:flex-row` - الصف المرن على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-wrap` - غلاف مرن على الكمبيوتر اللوحي بحد أقصى

##### Flex - Pc Max (< 1200px)

- `.hover:pc-max:flex-col` - فليكس كول عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:flex-nowrap` - فليكس الآن عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:flex-row` - الصف المرن عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:flex-wrap` - التفاف مرن عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.pc-max:flex-col` - فليكس كول على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-nowrap` - فليكس Nowrap على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-row` - الصف المرن على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-wrap` - التفاف مرن على جهاز الكمبيوتر كحد أقصى

### Flex col

- `.flex-col-reverse` - فليكس العمود العكسي
- `.hover:flex-col-reverse` - فليكس كول عكسي عند التمرير

##### Flex col - Mobile (< 480px)

- `.hover:mobile:flex-col-reverse` - فليكس كول عكسي عند التمرير على الهاتف المحمول
- `.mobile:flex-col-reverse` - فليكس كول عكس على الهاتف المحمول

##### Flex col - Tablet (480px - 768px)

- `.hover:tablet:flex-col-reverse` - عكس العمود المرن عند التمرير على الجهاز اللوحي
- `.tablet:flex-col-reverse` - فليكس كول عكس على الكمبيوتر اللوحي

##### Flex col - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col-reverse` - عكس العمود المرن عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:flex-col-reverse` - فليكس كول عكس على الكمبيوتر اللوحي

##### Flex col - Pc (992px - 1200px)

- `.hover:pc:flex-col-reverse` - فليكس كول عكس عند التمرير على جهاز الكمبيوتر
- `.pc:flex-col-reverse` - فليكس كول عكس على جهاز الكمبيوتر

##### Flex col - Tv (> 1200px)

- `.hover:tv:flex-col-reverse` - فليكس كول عكسي عند التمرير على شاشة التلفزيون
- `.tv:flex-col-reverse` - فليكس كول عكس على شاشة التلفزيون

##### Flex col - Tablet Max (< 768px)

- `.hover:tablet-max:flex-col-reverse` - فليكس كول عكسي عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:flex-col-reverse` - فليكس كول عكس على الكمبيوتر اللوحي بحد أقصى

##### Flex col - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - فليكس كول عكسي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-col-reverse` - فليكس كول عكس على الكمبيوتر اللوحي كحد أقصى

##### Flex col - Pc Max (< 1200px)

- `.hover:pc-max:flex-col-reverse` - فليكس كول عكسي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-col-reverse` - فليكس كول عكس على جهاز الكمبيوتر كحد أقصى

### Flex row

- `.flex-row-reverse` - عكس الصف المرن
- `.hover:flex-row-reverse` - عكس الصف المرن عند التمرير

##### Flex row - Mobile (< 480px)

- `.hover:mobile:flex-row-reverse` - عكس الصف المرن عند التمرير على الهاتف المحمول
- `.mobile:flex-row-reverse` - عكس الصف المرن على الهاتف المحمول

##### Flex row - Tablet (480px - 768px)

- `.hover:tablet:flex-row-reverse` - عكس الصف المرن عند التمرير على الجهاز اللوحي
- `.tablet:flex-row-reverse` - عكس الصف المرن على الجهاز اللوحي

##### Flex row - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-row-reverse` - عكس الصف المرن عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:flex-row-reverse` - عكس الصف المرن على الكمبيوتر اللوحي

##### Flex row - Pc (992px - 1200px)

- `.hover:pc:flex-row-reverse` - عكس الصف المرن عند التمرير على جهاز الكمبيوتر
- `.pc:flex-row-reverse` - عكس الصف المرن على جهاز الكمبيوتر

##### Flex row - Tv (> 1200px)

- `.hover:tv:flex-row-reverse` - عكس الصف المرن عند التمرير على شاشة التلفزيون
- `.tv:flex-row-reverse` - عكس الصف المرن على شاشة التلفزيون

##### Flex row - Tablet Max (< 768px)

- `.hover:tablet-max:flex-row-reverse` - الصف المرن للخلف عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:flex-row-reverse` - الصف المرن للخلف على الجهاز اللوحي بحد أقصى

##### Flex row - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - الصف المرن للخلف عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-row-reverse` - عكس الصف المرن على الكمبيوتر اللوحي بحد أقصى

##### Flex row - Pc Max (< 1200px)

- `.hover:pc-max:flex-row-reverse` - الصف المرن للخلف عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.pc-max:flex-row-reverse` - عكس الصف المرن على جهاز الكمبيوتر كحد أقصى

### Flex grow

- `.flex-grow-3` - فليكس تنمو 3ريم
- `.flex-grow-2` - فليكس تنمو 2ريم
- `.flex-grow-1` - فليكس ينمو 1ريم
- `.flex-grow-0` - فليكس تنمو 0rem
- `.hover:flex-grow-3` - فليكس ينمو 3ريم عند التحويم
- `.hover:flex-grow-2` - فليكس ينمو 2ريم عند التحويم
- `.hover:flex-grow-1` - فليكس ينمو 1ريم عند التحويم
- `.hover:flex-grow-0` - فليكس ينمو 0rem عند التحويم

##### Flex grow - Mobile (< 480px)

- `.hover:mobile:flex-grow-3` - Flex Grow 3rem عند التمرير على الهاتف المحمول
- `.hover:mobile:flex-grow-2` - Flex Grow 2rem عند التمرير على الهاتف المحمول
- `.hover:mobile:flex-grow-1` - Flex Grow 1rem عند التمرير على الهاتف المحمول
- `.hover:mobile:flex-grow-0` - Flex Grow 0rem عند التمرير على الهاتف المحمول
- `.mobile:flex-grow-3` - فليكس تنمو 3rem على الهاتف المحمول
- `.mobile:flex-grow-2` - فليكس تنمو 2rem على الهاتف المحمول
- `.mobile:flex-grow-1` - فليكس ينمو 1rem على الهاتف المحمول
- `.mobile:flex-grow-0` - فليكس تنمو 0rem على الهاتف المحمول

##### Flex grow - Tablet (480px - 768px)

- `.hover:tablet:flex-grow-3` - Flex Grow 3rem عند التمرير على الجهاز اللوحي
- `.hover:tablet:flex-grow-2` - Flex Grow 2rem عند التمرير على الجهاز اللوحي
- `.hover:tablet:flex-grow-1` - Flex Grow 1rem عند التمرير على الجهاز اللوحي
- `.hover:tablet:flex-grow-0` - Flex Grow 0rem عند التمرير على الجهاز اللوحي
- `.tablet:flex-grow-3` - فليكس جرو 3ريم على الجهاز اللوحي
- `.tablet:flex-grow-2` - فليكس جرو 2ريم على الجهاز اللوحي
- `.tablet:flex-grow-1` - فليكس ينمو 1ريم على الجهاز اللوحي
- `.tablet:flex-grow-0` - فليكس ينمو 0rem على الجهاز اللوحي

##### Flex grow - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-grow-3` - Flex Grow 3rem عند التحويم على الكمبيوتر اللوحي
- `.hover:tablet-pc:flex-grow-2` - Flex Grow 2rem عند التحويم على الكمبيوتر اللوحي
- `.hover:tablet-pc:flex-grow-1` - Flex Grow 1rem عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:flex-grow-0` - Flex Grow 0rem عند التحويم على الكمبيوتر اللوحي
- `.tablet-pc:flex-grow-3` - Flex Grow 3rem على الكمبيوتر اللوحي
- `.tablet-pc:flex-grow-2` - Flex Grow 2rem على الكمبيوتر اللوحي
- `.tablet-pc:flex-grow-1` - Flex Grow 1rem على الكمبيوتر اللوحي
- `.tablet-pc:flex-grow-0` - Flex Grow 0rem على الكمبيوتر اللوحي

##### Flex grow - Pc (992px - 1200px)

- `.hover:pc:flex-grow-3` - Flex Grow 3rem عند التحويم على جهاز الكمبيوتر
- `.hover:pc:flex-grow-2` - Flex Grow 2rem عند التحويم على جهاز الكمبيوتر
- `.hover:pc:flex-grow-1` - Flex Grow 1rem عند التحويم على جهاز الكمبيوتر
- `.hover:pc:flex-grow-0` - Flex Grow 0rem عند التحويم على جهاز الكمبيوتر
- `.pc:flex-grow-3` - فليكس جرو 3ريم على جهاز الكمبيوتر
- `.pc:flex-grow-2` - فليكس جرو 2ريم على جهاز الكمبيوتر
- `.pc:flex-grow-1` - فليكس جرو 1ريم على جهاز الكمبيوتر
- `.pc:flex-grow-0` - فليكس جرو 0ريم على جهاز الكمبيوتر

##### Flex grow - Tv (> 1200px)

- `.hover:tv:flex-grow-3` - Flex Grow 3rem عند التحويم على شاشة التلفزيون
- `.hover:tv:flex-grow-2` - Flex Grow 2rem عند التحويم على شاشة التلفزيون
- `.hover:tv:flex-grow-1` - Flex Grow 1rem عند التمرير على شاشة التلفزيون
- `.hover:tv:flex-grow-0` - فليكس ينمو 0rem على التحويم على شاشة التلفزيون
- `.tv:flex-grow-3` - فليكس جرو 3ريم على شاشة التلفزيون
- `.tv:flex-grow-2` - فليكس جرو 2ريم على شاشة التلفزيون
- `.tv:flex-grow-1` - فليكس ينمو 1ريم على شاشة التلفزيون
- `.tv:flex-grow-0` - فليكس تنمو 0rem على شاشة التلفزيون

##### Flex grow - Tablet Max (< 768px)

- `.hover:tablet-max:flex-grow-3` - Flex Grow 3rem عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:flex-grow-2` - Flex Grow 2rem عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:flex-grow-1` - Flex Grow 1rem عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:flex-grow-0` - Flex Grow 0rem عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:flex-grow-3` - فليكس جرو 3ريم على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:flex-grow-2` - فليكس جرو 2ريم على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:flex-grow-1` - فليكس جرو 1ريم على الجهاز اللوحي كحد أقصى
- `.tablet-max:flex-grow-0` - Flex Grow 0rem على الجهاز اللوحي بحد أقصى

##### Flex grow - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex Grow 3rem عند التحويم على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:flex-grow-2` - Flex Grow 2rem عند التحويم على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:flex-grow-1` - Flex Grow 1rem عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:flex-grow-0` - Flex Grow 0rem عند التحويم على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-grow-3` - Flex Grow 3rem على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:flex-grow-2` - Flex Grow 2rem على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-grow-1` - Flex Grow 1rem على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-grow-0` - Flex Grow 0rem على الكمبيوتر اللوحي بحد أقصى

##### Flex grow - Pc Max (< 1200px)

- `.hover:pc-max:flex-grow-3` - Flex Grow 3rem عند التحويم على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:flex-grow-2` - Flex Grow 2rem عند التحويم على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:flex-grow-1` - Flex Grow 1rem عند التحويم على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:flex-grow-0` - Flex Grow 0rem عند التحويم على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-grow-3` - فليكس جرو 3ريم على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-grow-2` - فليكس جرو 2ريم على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-grow-1` - فليكس جرو 1ريم على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-grow-0` - Flex Grow 0rem على جهاز الكمبيوتر كحد أقصى

### Flex wrap

- `.flex-wrap-reverse` - التفاف المرن العكسي
- `.hover:flex-wrap-reverse` - التفاف مرن عكسي عند التمرير

##### Flex wrap - Mobile (< 480px)

- `.hover:mobile:flex-wrap-reverse` - التفاف مرن للخلف عند التمرير على الهاتف المحمول
- `.mobile:flex-wrap-reverse` - التفاف مرن عكسي على الهاتف المحمول

##### Flex wrap - Tablet (480px - 768px)

- `.hover:tablet:flex-wrap-reverse` - التفاف مرن للخلف عند التمرير على الجهاز اللوحي
- `.tablet:flex-wrap-reverse` - التفاف مرن عكسي على الجهاز اللوحي

##### Flex wrap - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-wrap-reverse` - التفاف مرن عكسي عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:flex-wrap-reverse` - فليكس التفاف عكسي على الكمبيوتر اللوحي

##### Flex wrap - Pc (992px - 1200px)

- `.hover:pc:flex-wrap-reverse` - التفاف مرن عكسي عند التمرير على جهاز الكمبيوتر
- `.pc:flex-wrap-reverse` - فليكس التفاف عكسي على جهاز الكمبيوتر

##### Flex wrap - Tv (> 1200px)

- `.hover:tv:flex-wrap-reverse` - التفاف مرن للخلف عند التمرير على شاشة التلفزيون
- `.tv:flex-wrap-reverse` - التفاف المرن على شاشة التلفزيون

##### Flex wrap - Tablet Max (< 768px)

- `.hover:tablet-max:flex-wrap-reverse` - التفاف مرن للخلف عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:flex-wrap-reverse` - التفاف مرن عكسي على الجهاز اللوحي بحد أقصى

##### Flex wrap - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - التفاف مرن عكسي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:flex-wrap-reverse` - التفاف مرن عكسي على الكمبيوتر اللوحي بحد أقصى

##### Flex wrap - Pc Max (< 1200px)

- `.hover:pc-max:flex-wrap-reverse` - التفاف مرن عكسي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:flex-wrap-reverse` - التفاف مرن عكسي على جهاز الكمبيوتر بحد أقصى

### Gap

#### Gap All

- `.gap-5` - الفجوة كل 5rem
- `.gap-4.5` - فجوة الكل 0rem
- `.gap-4` - الفجوة كل 4rem
- `.gap-3.5` - فجوة الكل 0rem
- `.gap-3` - فجوة كل 3rem
- `.gap-2.5` - فجوة الكل 0rem
- `.gap-2` - فجوة كل 2rem
- `.gap-1.9` - فجوة الكل 0rem
- `.gap-1.8` - فجوة الكل 0rem
- `.gap-1.7` - فجوة الكل 0rem
- `.gap-1.6` - فجوة الكل 0rem
- `.gap-1.5` - فجوة الكل 0rem
- `.gap-1.4` - فجوة الكل 0rem
- `.gap-1.3` - فجوة الكل 0rem
- `.gap-1.2` - فجوة الكل 0rem
- `.gap-1.1` - فجوة الكل 0rem
- `.gap-1` - فجوة الكل 1rem
- `.gap-0.9` - فجوة الكل 0rem
- `.gap-0.8` - فجوة الكل 0rem
- `.gap-0.7` - فجوة الكل 0rem
- `.gap-0.6` - فجوة الكل 0rem
- `.gap-0.5` - فجوة الكل 0rem
- `.gap-0.4` - فجوة الكل 0rem
- `.gap-0.3` - فجوة الكل 0rem
- `.gap-0.2` - فجوة الكل 0.2rem
- `.gap-0.1` - فجوة الكل 0.1rem
- `.gap-0` - فجوة الكل 0rem
- `.hover:gap-5` - فجوة جميع 5rem عند التمرير
- `.hover:gap-4.5` - فجوة الكل 0rem عند التمرير
- `.hover:gap-4` - فجوة جميع 4rem عند التمرير
- `.hover:gap-3.5` - فجوة الكل 0rem عند التمرير
- `.hover:gap-3` - فجوة جميع 3rem عند التمرير
- `.hover:gap-2.5` - فجوة الكل 0rem عند التمرير
- `.hover:gap-2` - فجوة الكل 2rem عند التمرير
- `.hover:gap-1.9` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.8` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.7` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.6` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.5` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.4` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.3` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.2` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1.1` - فجوة الكل 0rem عند التمرير
- `.hover:gap-1` - فجوة الكل 1rem عند التمرير
- `.hover:gap-0.9` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.8` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.7` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.6` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.5` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.4` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.3` - فجوة الكل 0rem عند التمرير
- `.hover:gap-0.2` - فجوة الكل 0.2rem عند التمرير
- `.hover:gap-0.1` - فجوة الكل 0.1rem عند التمرير
- `.hover:gap-0` - فجوة الكل 0rem عند التمرير

#### Gap X-Axis

- `.gap-x-5` - فجوة المحور السيني 5rem
- `.gap-x-4.5` - فجوة المحور السيني 0rem
- `.gap-x-4` - فجوة المحور السيني 4rem
- `.gap-x-3.5` - فجوة المحور السيني 0rem
- `.gap-x-3` - فجوة المحور السيني 3rem
- `.gap-x-2.5` - فجوة المحور السيني 0rem
- `.gap-x-2` - فجوة المحور السيني 2rem
- `.gap-x-1.9` - فجوة المحور السيني 0rem
- `.gap-x-1.8` - فجوة المحور السيني 0rem
- `.gap-x-1.7` - فجوة المحور السيني 0rem
- `.gap-x-1.6` - فجوة المحور السيني 0rem
- `.gap-x-1.5` - فجوة المحور السيني 0rem
- `.gap-x-1.4` - فجوة المحور السيني 0rem
- `.gap-x-1.3` - فجوة المحور السيني 0rem
- `.gap-x-1.2` - فجوة المحور السيني 0rem
- `.gap-x-1.1` - فجوة المحور السيني 0rem
- `.gap-x-1` - فجوة المحور السيني 1rem
- `.gap-x-0.9` - فجوة المحور السيني 0rem
- `.gap-x-0.8` - فجوة المحور السيني 0rem
- `.gap-x-0.7` - فجوة المحور السيني 0rem
- `.gap-x-0.6` - فجوة المحور السيني 0rem
- `.gap-x-0.5` - فجوة المحور السيني 0rem
- `.gap-x-0.4` - فجوة المحور السيني 0rem
- `.gap-x-0.3` - فجوة المحور السيني 0rem
- `.gap-x-0.2` - فجوة المحور السيني 0.2rem
- `.gap-x-0.1` - فجوة المحور السيني 0.1rem
- `.gap-x-0` - فجوة المحور السيني 0rem
- `.hover:gap-x-5` - فجوة المحور X 5rem عند التحويم
- `.hover:gap-x-4.5` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-4` - فجوة المحور X 4rem عند التحويم
- `.hover:gap-x-3.5` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-3` - فجوة المحور السيني 3rem عند التمرير
- `.hover:gap-x-2.5` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-2` - فجوة المحور السيني 2rem عند التحويم
- `.hover:gap-x-1.9` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.8` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.7` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.6` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.5` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.4` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.3` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.2` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1.1` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-1` - فجوة المحور السيني 1rem عند التمرير
- `.hover:gap-x-0.9` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.8` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.7` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.6` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.5` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.4` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.3` - فجوة المحور السيني 0rem عند التمرير
- `.hover:gap-x-0.2` - فجوة المحور السيني 0.2rem عند التحويم
- `.hover:gap-x-0.1` - فجوة المحور السيني 0.1rem عند التحويم
- `.hover:gap-x-0` - فجوة المحور السيني 0rem عند التمرير

#### Gap Y-Axis

- `.gap-y-5` - فجوة المحور ص 5rem
- `.gap-y-4.5` - فجوة المحور Y 0rem
- `.gap-y-4` - فجوة المحور Y 4rem
- `.gap-y-3.5` - فجوة المحور Y 0rem
- `.gap-y-3` - فجوة المحور ص 3rem
- `.gap-y-2.5` - فجوة المحور Y 0rem
- `.gap-y-2` - فجوة المحور Y 2rem
- `.gap-y-1.9` - فجوة المحور Y 0rem
- `.gap-y-1.8` - فجوة المحور Y 0rem
- `.gap-y-1.7` - فجوة المحور Y 0rem
- `.gap-y-1.6` - فجوة المحور Y 0rem
- `.gap-y-1.5` - فجوة المحور Y 0rem
- `.gap-y-1.4` - فجوة المحور Y 0rem
- `.gap-y-1.3` - فجوة المحور Y 0rem
- `.gap-y-1.2` - فجوة المحور Y 0rem
- `.gap-y-1.1` - فجوة المحور Y 0rem
- `.gap-y-1` - فجوة المحور ص 1rem
- `.gap-y-0.9` - فجوة المحور Y 0rem
- `.gap-y-0.8` - فجوة المحور Y 0rem
- `.gap-y-0.7` - فجوة المحور Y 0rem
- `.gap-y-0.6` - فجوة المحور Y 0rem
- `.gap-y-0.5` - فجوة المحور Y 0rem
- `.gap-y-0.4` - فجوة المحور Y 0rem
- `.gap-y-0.3` - فجوة المحور Y 0rem
- `.gap-y-0.2` - فجوة المحور Y 0.2rem
- `.gap-y-0.1` - فجوة المحور Y 0.1rem
- `.gap-y-0` - فجوة المحور Y 0rem
- `.hover:gap-y-5` - فجوة المحور Y 5rem عند التمرير
- `.hover:gap-y-4.5` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-4` - فجوة المحور Y 4rem عند التمرير
- `.hover:gap-y-3.5` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-3` - فجوة المحور Y 3rem عند التمرير
- `.hover:gap-y-2.5` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-2` - فجوة المحور Y 2rem عند التمرير
- `.hover:gap-y-1.9` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.8` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.7` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.6` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.5` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.4` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.3` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.2` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1.1` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-1` - فجوة المحور Y 1rem عند التمرير
- `.hover:gap-y-0.9` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.8` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.7` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.6` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.5` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.4` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.3` - فجوة المحور Y 0rem عند التمرير
- `.hover:gap-y-0.2` - فجوة المحور Y 0.2rem عند التمرير
- `.hover:gap-y-0.1` - فجوة المحور Y 0.1rem عند التمرير
- `.hover:gap-y-0` - فجوة المحور Y 0rem عند التمرير

### Align content

- `.align-content-around` - محاذاة المحتوى حولها
- `.align-content-between` - محاذاة المحتوى بين
- `.align-content-center` - محاذاة مركز المحتوى
- `.align-content-end` - محاذاة نهاية المحتوى
- `.align-content-evenly` - محاذاة المحتوى بالتساوي
- `.align-content-start` - محاذاة بداية المحتوى
- `.align-content-stretch` - محاذاة امتداد المحتوى
- `.hover:align-content-around` - قم بمحاذاة المحتوى عند التمرير
- `.hover:align-content-between` - محاذاة المحتوى بين عند التمرير
- `.hover:align-content-center` - محاذاة مركز المحتوى عند التمرير
- `.hover:align-content-end` - محاذاة نهاية المحتوى عند التمرير
- `.hover:align-content-evenly` - محاذاة المحتوى بالتساوي عند التمرير
- `.hover:align-content-start` - محاذاة المحتوى تبدأ عند التمرير
- `.hover:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير

##### Align content - Mobile (< 480px)

- `.hover:mobile:align-content-around` - قم بمحاذاة المحتوى عند التمرير على الهاتف المحمول
- `.hover:mobile:align-content-between` - قم بمحاذاة المحتوى بين التمرير على الهاتف المحمول
- `.hover:mobile:align-content-center` - محاذاة مركز المحتوى عند التمرير على الهاتف المحمول
- `.hover:mobile:align-content-end` - محاذاة نهاية المحتوى عند التمرير على الهاتف المحمول
- `.hover:mobile:align-content-evenly` - قم بمحاذاة المحتوى بالتساوي عند التمرير على الهاتف المحمول
- `.hover:mobile:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على الهاتف المحمول
- `.hover:mobile:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير على الهاتف المحمول
- `.mobile:align-content-around` - محاذاة المحتوى على الهاتف المحمول
- `.mobile:align-content-between` - محاذاة المحتوى بين على الهاتف المحمول
- `.mobile:align-content-center` - محاذاة مركز المحتوى على الهاتف المحمول
- `.mobile:align-content-end` - محاذاة نهاية المحتوى على الهاتف المحمول
- `.mobile:align-content-evenly` - محاذاة المحتوى بالتساوي على الهاتف المحمول
- `.mobile:align-content-start` - محاذاة المحتوى تبدأ على الهاتف المحمول
- `.mobile:align-content-stretch` - محاذاة امتداد المحتوى على الهاتف المحمول

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - قم بمحاذاة المحتوى عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-content-between` - قم بمحاذاة المحتوى بين التمرير على الجهاز اللوحي
- `.hover:tablet:align-content-center` - محاذاة مركز المحتوى عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-content-end` - قم بمحاذاة نهاية المحتوى عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-content-evenly` - قم بمحاذاة المحتوى بالتساوي عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير على الجهاز اللوحي
- `.tablet:align-content-around` - محاذاة المحتوى على الجهاز اللوحي
- `.tablet:align-content-between` - محاذاة المحتوى بين على الجهاز اللوحي
- `.tablet:align-content-center` - محاذاة مركز المحتوى على الجهاز اللوحي
- `.tablet:align-content-end` - محاذاة نهاية المحتوى على الجهاز اللوحي
- `.tablet:align-content-evenly` - محاذاة المحتوى بالتساوي على الجهاز اللوحي
- `.tablet:align-content-start` - محاذاة المحتوى يبدأ على الجهاز اللوحي
- `.tablet:align-content-stretch` - محاذاة امتداد المحتوى على الجهاز اللوحي

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - قم بمحاذاة المحتوى عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-content-between` - قم بمحاذاة المحتوى بين التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-content-center` - محاذاة مركز المحتوى عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-content-end` - قم بمحاذاة نهاية المحتوى عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-content-evenly` - قم بمحاذاة المحتوى بالتساوي عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:align-content-around` - محاذاة المحتوى حول الكمبيوتر اللوحي
- `.tablet-pc:align-content-between` - محاذاة المحتوى بين الكمبيوتر اللوحي
- `.tablet-pc:align-content-center` - محاذاة مركز المحتوى على الكمبيوتر اللوحي
- `.tablet-pc:align-content-end` - محاذاة نهاية المحتوى على الكمبيوتر اللوحي
- `.tablet-pc:align-content-evenly` - محاذاة المحتوى بالتساوي على الكمبيوتر اللوحي
- `.tablet-pc:align-content-start` - محاذاة المحتوى تبدأ على الكمبيوتر اللوحي
- `.tablet-pc:align-content-stretch` - محاذاة المحتوى تمتد على الكمبيوتر اللوحي

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - قم بمحاذاة المحتوى عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-content-between` - قم بمحاذاة المحتوى بين التمرير على جهاز الكمبيوتر
- `.hover:pc:align-content-center` - محاذاة مركز المحتوى عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-content-end` - محاذاة نهاية المحتوى عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-content-evenly` - محاذاة المحتوى بالتساوي عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير على جهاز الكمبيوتر
- `.pc:align-content-around` - محاذاة المحتوى حول جهاز الكمبيوتر
- `.pc:align-content-between` - محاذاة المحتوى بين على جهاز الكمبيوتر
- `.pc:align-content-center` - محاذاة مركز المحتوى على جهاز الكمبيوتر
- `.pc:align-content-end` - محاذاة نهاية المحتوى على جهاز الكمبيوتر
- `.pc:align-content-evenly` - محاذاة المحتوى بالتساوي على جهاز الكمبيوتر
- `.pc:align-content-start` - محاذاة المحتوى تبدأ على جهاز الكمبيوتر
- `.pc:align-content-stretch` - محاذاة المحتوى تمتد على جهاز الكمبيوتر

##### Align content - Tv (> 1200px)

- `.hover:tv:align-content-around` - قم بمحاذاة المحتوى عند التمرير على شاشة التلفزيون
- `.hover:tv:align-content-between` - قم بمحاذاة المحتوى بين التمرير على شاشة التلفزيون
- `.hover:tv:align-content-center` - محاذاة مركز المحتوى عند التمرير على شاشة التلفزيون
- `.hover:tv:align-content-end` - قم بمحاذاة نهاية المحتوى عند التمرير على شاشة التلفزيون
- `.hover:tv:align-content-evenly` - قم بمحاذاة المحتوى بالتساوي عند التمرير على شاشة التلفزيون
- `.hover:tv:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على شاشة التلفزيون
- `.hover:tv:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير على شاشة التلفزيون
- `.tv:align-content-around` - محاذاة المحتوى حول التلفزيون
- `.tv:align-content-between` - محاذاة المحتوى بين على شاشة التلفزيون
- `.tv:align-content-center` - محاذاة مركز المحتوى على شاشة التلفزيون
- `.tv:align-content-end` - محاذاة نهاية المحتوى على شاشة التلفزيون
- `.tv:align-content-evenly` - محاذاة المحتوى بالتساوي على شاشة التلفزيون
- `.tv:align-content-start` - محاذاة المحتوى يبدأ على شاشة التلفزيون
- `.tv:align-content-stretch` - محاذاة امتداد المحتوى على شاشة التلفزيون

##### Align content - Tablet Max (< 768px)

- `.hover:tablet-max:align-content-around` - قم بمحاذاة المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-content-between` - قم بمحاذاة المحتوى بين التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-content-center` - محاذاة مركز المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-content-end` - قم بمحاذاة نهاية المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-content-evenly` - قم بمحاذاة المحتوى بالتساوي عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-content-stretch` - محاذاة امتداد المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-content-around` - قم بمحاذاة المحتوى على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-content-between` - محاذاة المحتوى بين الحد الأقصى للكمبيوتر اللوحي
- `.tablet-max:align-content-center` - محاذاة مركز المحتوى على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-content-end` - محاذاة نهاية المحتوى على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-content-evenly` - محاذاة المحتوى بالتساوي على الجهاز اللوحي كحد أقصى
- `.tablet-max:align-content-start` - محاذاة المحتوى تبدأ على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-content-stretch` - محاذاة امتداد المحتوى على الجهاز اللوحي بحد أقصى

##### Align content - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:align-content-around` - قم بمحاذاة المحتوى عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-content-between` - قم بمحاذاة المحتوى بين التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-content-center` - قم بمحاذاة مركز المحتوى عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:align-content-end` - قم بمحاذاة نهاية المحتوى عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-content-evenly` - قم بمحاذاة المحتوى بالتساوي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-content-stretch` - محاذاة المحتوى عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-content-around` - قم بمحاذاة المحتوى على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-content-between` - محاذاة المحتوى بين أجهزة الكمبيوتر اللوحية بحد أقصى
- `.tablet-pc-max:align-content-center` - محاذاة مركز المحتوى على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-content-end` - محاذاة نهاية المحتوى على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-content-evenly` - محاذاة المحتوى بالتساوي على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-content-start` - محاذاة المحتوى تبدأ على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-content-stretch` - محاذاة المحتوى الممتد على الكمبيوتر اللوحي كحد أقصى

##### Align content - Pc Max (< 1200px)

- `.hover:pc-max:align-content-around` - قم بمحاذاة المحتوى عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:align-content-between` - محاذاة المحتوى بين عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-content-center` - محاذاة مركز المحتوى عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-content-end` - محاذاة نهاية المحتوى عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-content-evenly` - محاذاة المحتوى بالتساوي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-content-start` - محاذاة المحتوى تبدأ عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-content-stretch` - محاذاة المحتوى الممتد عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-content-around` - محاذاة المحتوى على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-content-between` - محاذاة المحتوى بين الحد الأقصى لجهاز الكمبيوتر
- `.pc-max:align-content-center` - محاذاة مركز المحتوى على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-content-end` - محاذاة نهاية المحتوى على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-content-evenly` - محاذاة المحتوى بالتساوي على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-content-start` - محاذاة المحتوى تبدأ على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-content-stretch` - محاذاة المحتوى تمتد على جهاز الكمبيوتر كحد أقصى

### Align items

- `.align-items-center` - محاذاة العناصر إلى المركز
- `.align-items-end` - نهاية محاذاة العناصر
- `.align-items-start` - محاذاة العناصر تبدأ
- `.align-items-stretch` - محاذاة العناصر تمتد
- `.hover:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير
- `.hover:align-items-end` - تنتهي محاذاة العناصر عند التمرير
- `.hover:align-items-start` - تبدأ محاذاة العناصر عند التمرير
- `.hover:align-items-stretch` - محاذاة العناصر تمتد عند التمرير

##### Align items - Mobile (< 480px)

- `.hover:mobile:align-items-center` - محاذاة العناصر إلى المركز عند التمرير على الهاتف المحمول
- `.hover:mobile:align-items-end` - تنتهي محاذاة العناصر عند التمرير على الهاتف المحمول
- `.hover:mobile:align-items-start` - تبدأ محاذاة العناصر عند التمرير على الهاتف المحمول
- `.hover:mobile:align-items-stretch` - تمتد محاذاة العناصر عند التمرير على الهاتف المحمول
- `.mobile:align-items-center` - محاذاة العناصر إلى المركز على الهاتف المحمول
- `.mobile:align-items-end` - محاذاة العناصر تنتهي على الهاتف المحمول
- `.mobile:align-items-start` - محاذاة العناصر تبدأ على الهاتف المحمول
- `.mobile:align-items-stretch` - محاذاة العناصر تمتد على الهاتف المحمول

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-items-end` - تنتهي محاذاة العناصر عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-items-start` - تبدأ محاذاة العناصر عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-items-stretch` - تمتد محاذاة العناصر عند التمرير على الجهاز اللوحي
- `.tablet:align-items-center` - محاذاة العناصر إلى المنتصف على الجهاز اللوحي
- `.tablet:align-items-end` - محاذاة العناصر نهاية على الجهاز اللوحي
- `.tablet:align-items-start` - محاذاة العناصر تبدأ على الجهاز اللوحي
- `.tablet:align-items-stretch` - محاذاة العناصر تمتد على الجهاز اللوحي

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-items-end` - تنتهي محاذاة العناصر عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-items-start` - تبدأ محاذاة العناصر عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-items-stretch` - محاذاة العناصر تمتد عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:align-items-center` - محاذاة العناصر إلى المنتصف على الكمبيوتر اللوحي
- `.tablet-pc:align-items-end` - محاذاة العناصر تنتهي على الكمبيوتر اللوحي
- `.tablet-pc:align-items-start` - تبدأ محاذاة العناصر على الكمبيوتر اللوحي
- `.tablet-pc:align-items-stretch` - محاذاة العناصر تمتد على الكمبيوتر اللوحي

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-items-end` - تنتهي محاذاة العناصر عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-items-start` - تبدأ محاذاة العناصر عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-items-stretch` - محاذاة العناصر تمتد عند التمرير على جهاز الكمبيوتر
- `.pc:align-items-center` - محاذاة العناصر إلى المركز على جهاز الكمبيوتر
- `.pc:align-items-end` - محاذاة العناصر تنتهي على جهاز الكمبيوتر
- `.pc:align-items-start` - محاذاة العناصر تبدأ على جهاز الكمبيوتر
- `.pc:align-items-stretch` - محاذاة العناصر تمتد على جهاز الكمبيوتر

##### Align items - Tv (> 1200px)

- `.hover:tv:align-items-center` - محاذاة العناصر إلى المركز عند التمرير على شاشة التلفزيون
- `.hover:tv:align-items-end` - تنتهي محاذاة العناصر عند التمرير على شاشة التلفزيون
- `.hover:tv:align-items-start` - تبدأ محاذاة العناصر عند التمرير على شاشة التلفزيون
- `.hover:tv:align-items-stretch` - محاذاة العناصر تمتد عند التمرير على شاشة التلفزيون
- `.tv:align-items-center` - محاذاة مركز العناصر على شاشة التلفزيون
- `.tv:align-items-end` - محاذاة العناصر تنتهي على شاشة التلفزيون
- `.tv:align-items-start` - محاذاة العناصر تبدأ على شاشة التلفزيون
- `.tv:align-items-stretch` - محاذاة العناصر تمتد على شاشة التلفزيون

##### Align items - Tablet Max (< 768px)

- `.hover:tablet-max:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-items-end` - تنتهي محاذاة العناصر عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:align-items-start` - تبدأ محاذاة العناصر عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-items-stretch` - تمتد محاذاة العناصر عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-items-center` - محاذاة العناصر إلى المنتصف على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-items-end` - محاذاة العناصر تنتهي على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-items-start` - تبدأ محاذاة العناصر على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-items-stretch` - محاذاة العناصر تمتد على الجهاز اللوحي بحد أقصى

##### Align items - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-items-end` - تنتهي محاذاة العناصر عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:align-items-start` - تبدأ محاذاة العناصر عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-items-stretch` - محاذاة العناصر تمتد عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-items-center` - محاذاة العناصر إلى المنتصف على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-items-end` - محاذاة العناصر تنتهي على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:align-items-start` - تبدأ محاذاة العناصر على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:align-items-stretch` - محاذاة العناصر تمتد على الكمبيوتر اللوحي كحد أقصى

##### Align items - Pc Max (< 1200px)

- `.hover:pc-max:align-items-center` - محاذاة العناصر إلى المنتصف عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:align-items-end` - تنتهي محاذاة العناصر عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:align-items-start` - تبدأ محاذاة العناصر عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:align-items-stretch` - محاذاة العناصر تمتد عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-items-center` - محاذاة العناصر إلى المركز على جهاز الكمبيوتر بحد أقصى
- `.pc-max:align-items-end` - محاذاة العناصر تنتهي على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-items-start` - تبدأ محاذاة العناصر على جهاز الكمبيوتر بحد أقصى
- `.pc-max:align-items-stretch` - محاذاة العناصر تمتد على جهاز الكمبيوتر كحد أقصى

### Align self

- `.align-self-center` - محاذاة المركز الذاتي
- `.align-self-end` - محاذاة النهاية الذاتية
- `.align-self-start` - محاذاة البداية الذاتية
- `.align-self-stretch` - محاذاة تمتد الذاتي
- `.hover:align-self-center` - محاذاة المركز الذاتي عند التمرير
- `.hover:align-self-end` - محاذاة النهاية الذاتية عند التمرير
- `.hover:align-self-start` - محاذاة البداية الذاتية عند التمرير
- `.hover:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير

##### Align self - Mobile (< 480px)

- `.hover:mobile:align-self-center` - محاذاة المركز الذاتي عند التمرير على الهاتف المحمول
- `.hover:mobile:align-self-end` - محاذاة النهاية الذاتية عند التمرير على الهاتف المحمول
- `.hover:mobile:align-self-start` - محاذاة البدء الذاتي عند التمرير على الهاتف المحمول
- `.hover:mobile:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على الهاتف المحمول
- `.mobile:align-self-center` - محاذاة المركز الذاتي على الهاتف المحمول
- `.mobile:align-self-end` - محاذاة النهاية الذاتية على الهاتف المحمول
- `.mobile:align-self-start` - محاذاة البداية الذاتية على الهاتف المحمول
- `.mobile:align-self-stretch` - محاذاة تمتد الذاتي على الهاتف المحمول

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - محاذاة المركز الذاتي عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-self-end` - قم بمحاذاة النهاية الذاتية عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-self-start` - محاذاة البدء الذاتي عند التمرير على الجهاز اللوحي
- `.hover:tablet:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على الجهاز اللوحي
- `.tablet:align-self-center` - محاذاة المركز الذاتي على الجهاز اللوحي
- `.tablet:align-self-end` - محاذاة النهاية الذاتية على الجهاز اللوحي
- `.tablet:align-self-start` - محاذاة البدء الذاتي على الجهاز اللوحي
- `.tablet:align-self-stretch` - محاذاة تمتد الذاتي على الكمبيوتر اللوحي

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - محاذاة المركز الذاتي عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-self-end` - قم بمحاذاة النهاية الذاتية عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-self-start` - محاذاة البدء الذاتي عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:align-self-center` - محاذاة المركز الذاتي على الكمبيوتر اللوحي
- `.tablet-pc:align-self-end` - محاذاة النهاية الذاتية على الكمبيوتر اللوحي
- `.tablet-pc:align-self-start` - محاذاة البدء الذاتي على الكمبيوتر اللوحي
- `.tablet-pc:align-self-stretch` - محاذاة التمدد الذاتي على الكمبيوتر اللوحي

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - محاذاة المركز الذاتي عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-self-end` - محاذاة النهاية الذاتية عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-self-start` - محاذاة البدء الذاتي عند التمرير على جهاز الكمبيوتر
- `.hover:pc:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على جهاز الكمبيوتر
- `.pc:align-self-center` - محاذاة المركز الذاتي على جهاز الكمبيوتر
- `.pc:align-self-end` - محاذاة النهاية الذاتية على جهاز الكمبيوتر
- `.pc:align-self-start` - محاذاة البداية الذاتية على جهاز الكمبيوتر
- `.pc:align-self-stretch` - محاذاة التمدد الذاتي على جهاز الكمبيوتر

##### Align self - Tv (> 1200px)

- `.hover:tv:align-self-center` - محاذاة المركز الذاتي عند التمرير على شاشة التلفزيون
- `.hover:tv:align-self-end` - محاذاة النهاية الذاتية عند التمرير على شاشة التلفزيون
- `.hover:tv:align-self-start` - محاذاة البدء الذاتي عند التمرير على شاشة التلفزيون
- `.hover:tv:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على شاشة التلفزيون
- `.tv:align-self-center` - محاذاة المركز الذاتي على شاشة التلفزيون
- `.tv:align-self-end` - محاذاة النهاية الذاتية على شاشة التلفزيون
- `.tv:align-self-start` - محاذاة البداية الذاتية على شاشة التلفزيون
- `.tv:align-self-stretch` - محاذاة تمتد النفس على شاشة التلفزيون

##### Align self - Tablet Max (< 768px)

- `.hover:tablet-max:align-self-center` - محاذاة المركز الذاتي عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-self-end` - قم بمحاذاة النهاية الذاتية عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-self-start` - محاذاة البدء الذاتي عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-self-center` - محاذاة المركز الذاتي على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-self-end` - محاذاة النهاية الذاتية على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-self-start` - محاذاة البدء الذاتي على الجهاز اللوحي بحد أقصى
- `.tablet-max:align-self-stretch` - محاذاة التمدد الذاتي على الجهاز اللوحي بحد أقصى

##### Align self - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:align-self-center` - قم بمحاذاة المركز الذاتي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-self-end` - قم بمحاذاة النهاية الذاتية عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:align-self-start` - محاذاة البدء الذاتي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-self-center` - محاذاة المركز الذاتي على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-self-end` - محاذاة النهاية الذاتية على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-self-start` - محاذاة البدء الذاتي على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:align-self-stretch` - محاذاة التمدد الذاتي على الكمبيوتر اللوحي بحد أقصى

##### Align self - Pc Max (< 1200px)

- `.hover:pc-max:align-self-center` - محاذاة المركز الذاتي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-self-end` - محاذاة النهاية الذاتية عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-self-start` - محاذاة البدء الذاتي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:align-self-stretch` - محاذاة التمدد الذاتي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-self-center` - محاذاة المركز الذاتي على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-self-end` - محاذاة النهاية الذاتية على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-self-start` - محاذاة البداية الذاتية على جهاز الكمبيوتر كحد أقصى
- `.pc-max:align-self-stretch` - محاذاة التمدد الذاتي على جهاز الكمبيوتر كحد أقصى

### Justify content

- `.hover:justify-content-around` - ضبط المحتوى عند التمرير
- `.hover:justify-content-between` - ضبط المحتوى بين عند التمرير
- `.hover:justify-content-center` - ضبط مركز المحتوى عند التمرير
- `.hover:justify-content-end` - نهاية ضبط المحتوى عند التمرير
- `.hover:justify-content-evenly` - ضبط المحتوى بالتساوي عند التمرير
- `.hover:justify-content-start` - ضبط المحتوى يبدأ عند التمرير
- `.hover:justify-content-stretch` - ضبط امتداد المحتوى عند التمرير
- `.justify-content-around` - تبرير المحتوى حولها
- `.justify-content-between` - تبرير المحتوى بين
- `.justify-content-center` - تبرير مركز المحتوى
- `.justify-content-end` - تبرير نهاية المحتوى
- `.justify-content-evenly` - تبرير المحتوى بالتساوي
- `.justify-content-start` - تبرير بداية المحتوى
- `.justify-content-stretch` - تبرير امتداد المحتوى

##### Justify content - Mobile (< 480px)

- `.hover:mobile:justify-content-around` - قم بضبط المحتوى عند التمرير على الهاتف المحمول
- `.hover:mobile:justify-content-between` - ضبط المحتوى بين التمرير على الهاتف المحمول
- `.hover:mobile:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على الهاتف المحمول
- `.hover:mobile:justify-content-end` - قم بضبط نهاية المحتوى عند التمرير على الهاتف المحمول
- `.hover:mobile:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على الهاتف المحمول
- `.mobile:justify-content-around` - تبرير المحتوى الموجود على الهاتف المحمول
- `.mobile:justify-content-between` - تبرير المحتوى بين على الهاتف المحمول
- `.mobile:justify-content-center` - ضبط مركز المحتوى على الهاتف المحمول
- `.mobile:justify-content-end` - تبرير نهاية المحتوى على الهاتف المحمول
- `.mobile:justify-content-start` - تبرير المحتوى يبدأ على الهاتف المحمول

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - قم بضبط المحتوى عند التمرير على الجهاز اللوحي
- `.hover:tablet:justify-content-between` - قم بضبط المحتوى بين التمرير على الجهاز اللوحي
- `.hover:tablet:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على الجهاز اللوحي
- `.hover:tablet:justify-content-end` - قم بضبط نهاية المحتوى عند التمرير على الجهاز اللوحي
- `.hover:tablet:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على الجهاز اللوحي
- `.tablet:justify-content-around` - تبرير المحتوى الموجود على الجهاز اللوحي
- `.tablet:justify-content-between` - ضبط المحتوى بين الجهاز اللوحي
- `.tablet:justify-content-center` - ضبط مركز المحتوى على الجهاز اللوحي
- `.tablet:justify-content-end` - ضبط نهاية المحتوى على الجهاز اللوحي
- `.tablet:justify-content-start` - ضبط محتوى البدء على الجهاز اللوحي

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - قم بضبط المحتوى عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:justify-content-between` - قم بضبط المحتوى بين التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:justify-content-end` - قم بضبط نهاية المحتوى عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:justify-content-around` - تبرير المحتوى الموجود على الكمبيوتر اللوحي
- `.tablet-pc:justify-content-between` - ضبط المحتوى بين الكمبيوتر اللوحي
- `.tablet-pc:justify-content-center` - ضبط مركز المحتوى على الكمبيوتر اللوحي
- `.tablet-pc:justify-content-end` - ضبط نهاية المحتوى على الكمبيوتر اللوحي
- `.tablet-pc:justify-content-start` - ضبط المحتوى يبدأ على الكمبيوتر اللوحي

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - تبرير المحتوى الموجود عند التمرير على جهاز الكمبيوتر
- `.hover:pc:justify-content-between` - ضبط المحتوى بين التمرير على جهاز الكمبيوتر
- `.hover:pc:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على جهاز الكمبيوتر
- `.hover:pc:justify-content-end` - ضبط نهاية المحتوى عند التمرير على جهاز الكمبيوتر
- `.hover:pc:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على جهاز الكمبيوتر
- `.pc:justify-content-around` - تبرير المحتوى الموجود على جهاز الكمبيوتر
- `.pc:justify-content-between` - تبرير المحتوى بين على جهاز الكمبيوتر
- `.pc:justify-content-center` - ضبط مركز المحتوى على جهاز الكمبيوتر
- `.pc:justify-content-end` - تبرير نهاية المحتوى على جهاز الكمبيوتر
- `.pc:justify-content-start` - تبرير بدء المحتوى على جهاز الكمبيوتر

##### Justify content - Tv (> 1200px)

- `.hover:tv:justify-content-around` - قم بتبرير المحتوى الموجود عند التمرير على شاشة التلفزيون
- `.hover:tv:justify-content-between` - ضبط المحتوى بين التمرير على شاشة التلفزيون
- `.hover:tv:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على شاشة التلفزيون
- `.hover:tv:justify-content-end` - قم بتبرير نهاية المحتوى عند التمرير على شاشة التلفزيون
- `.hover:tv:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على شاشة التلفزيون
- `.tv:justify-content-around` - تبرير المحتوى الموجود على شاشة التلفزيون
- `.tv:justify-content-between` - تبرير المحتوى بين على شاشة التلفزيون
- `.tv:justify-content-center` - تبرير مركز المحتوى على شاشة التلفزيون
- `.tv:justify-content-end` - تبرير نهاية المحتوى على شاشة التلفزيون
- `.tv:justify-content-start` - تبرير المحتوى يبدأ على شاشة التلفزيون

##### Justify content - Tablet Max (< 768px)

- `.hover:tablet-max:justify-content-around` - قم بضبط المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:justify-content-between` - ضبط المحتوى بين التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:justify-content-end` - قم بضبط نهاية المحتوى عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:justify-content-around` - تبرير المحتوى الموجود على الجهاز اللوحي بحد أقصى
- `.tablet-max:justify-content-between` - ضبط المحتوى بين الحد الأقصى للكمبيوتر اللوحي
- `.tablet-max:justify-content-center` - ضبط مركز المحتوى على الجهاز اللوحي بحد أقصى
- `.tablet-max:justify-content-end` - ضبط نهاية المحتوى على الجهاز اللوحي بحد أقصى
- `.tablet-max:justify-content-start` - ضبط المحتوى يبدأ على الجهاز اللوحي بحد أقصى

##### Justify content - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:justify-content-around` - قم بضبط المحتوى عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:justify-content-between` - ضبط المحتوى بين التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:justify-content-center` - قم بضبط مركز المحتوى عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:justify-content-end` - قم بضبط نهاية المحتوى عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:justify-content-around` - تبرير المحتوى الموجود على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:justify-content-between` - ضبط المحتوى بين أجهزة الكمبيوتر اللوحية بحد أقصى
- `.tablet-pc-max:justify-content-center` - ضبط مركز المحتوى على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:justify-content-end` - ضبط نهاية المحتوى على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:justify-content-start` - ضبط محتوى البدء على الكمبيوتر اللوحي بحد أقصى

##### Justify content - Pc Max (< 1200px)

- `.hover:pc-max:justify-content-around` - قم بضبط المحتوى عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:justify-content-between` - ضبط المحتوى بين التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:justify-content-center` - ضبط مركز المحتوى عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:justify-content-end` - ضبط نهاية المحتوى عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:justify-content-start` - ضبط المحتوى يبدأ عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:justify-content-around` - تبرير المحتوى الموجود على جهاز الكمبيوتر كحد أقصى
- `.pc-max:justify-content-between` - تبرير المحتوى بين الحد الأقصى لجهاز الكمبيوتر
- `.pc-max:justify-content-center` - ضبط مركز المحتوى على جهاز الكمبيوتر كحد أقصى
- `.pc-max:justify-content-end` - تبرير نهاية المحتوى على جهاز الكمبيوتر كحد أقصى
- `.pc-max:justify-content-start` - تبرير بدء المحتوى على جهاز الكمبيوتر كحد أقصى

### Justify items

- `.hover:justify-items-center` - ضبط مركز العناصر عند التمرير
- `.hover:justify-items-end` - تنتهي عناصر الضبط عند التمرير
- `.hover:justify-items-start` - تبدأ عناصر الضبط عند التمرير
- `.hover:justify-items-stretch` - تبرير العناصر يمتد عند التمرير
- `.justify-items-center` - تبرير مركز العناصر
- `.justify-items-end` - نهاية تبرير العناصر
- `.justify-items-start` - تبرير العناصر تبدأ
- `.justify-items-stretch` - تبرير العناصر تمتد

### Order

- `.hover:order-5` - اطلب 5 عند التمرير
- `.hover:order-4` - اطلب 4 عند التمرير
- `.hover:order-3` - اطلب 3 عند التمرير
- `.hover:order-2` - اطلب 2 عند التمرير
- `.hover:order-1` - اطلب 1 عند التمرير
- `.hover:order-0` - اطلب 0 عند التمرير
- `.hover:order-first` - اطلب أولاً عند التمرير
- `.hover:order-last` - الطلب الأخير عند التمرير
- `.order-5` - الطلب 5
- `.order-4` - الطلب 4
- `.order-3` - الطلب 3
- `.order-2` - الطلب 2
- `.order-1` - الطلب 1
- `.order-0` - اطلب 0
- `.order-first` - اطلب أولاً
- `.order-last` - اطلب أخيرًا

##### Negative Order

- `.-order-5` - أمر سلبي 5
- `.-order-4` - الترتيب السلبي 4
- `.-order-3` - أمر سلبي 3
- `.-order-2` - أمر سلبي 2
- `.-order-1` - أمر سلبي 1
- `.hover:-order-5` - الطلب السلبي 5 عند التمرير
- `.hover:-order-4` - الطلب السلبي 4 عند التمرير
- `.hover:-order-3` - الطلب السلبي 3 عند التمرير
- `.hover:-order-2` - الطلب السلبي 2 عند التمرير
- `.hover:-order-1` - أمر سلبي 1 عند التمرير

##### Order - Mobile (< 480px)

- `.hover:mobile:order-5` - اطلب 5 عند التمرير على الهاتف المحمول
- `.hover:mobile:order-4` - اطلب 4 عند التمرير على الهاتف المحمول
- `.hover:mobile:order-3` - اطلب 3 عند التمرير على الهاتف المحمول
- `.hover:mobile:order-2` - اطلب 2 عند التمرير على الهاتف المحمول
- `.hover:mobile:order-1` - اطلب 1 عند التمرير على الهاتف المحمول
- `.hover:mobile:order-0` - اطلب 0 عند التمرير على الهاتف المحمول
- `.hover:mobile:order-first` - اطلب أولاً عند التمرير على الهاتف المحمول
- `.hover:mobile:order-last` - الطلب الأخير عند التمرير على الهاتف المحمول
- `.mobile:order-5` - اطلب 5 على الهاتف المحمول
- `.mobile:order-4` - اطلب 4 على الهاتف المحمول
- `.mobile:order-3` - اطلب 3 على الجوال
- `.mobile:order-2` - اطلب 2 على الجوال
- `.mobile:order-1` - اطلب 1 على الهاتف المحمول
- `.mobile:order-0` - اطلب 0 على الهاتف المحمول
- `.mobile:order-first` - اطلب أولاً على الهاتف المحمول
- `.mobile:order-last` - الطلب الأخير على الهاتف المحمول

##### Negative Order - Mobile (< 480px)

- `.hover:mobile:-order-5` - الطلب السلبي 5 عند التمرير على الهاتف المحمول
- `.hover:mobile:-order-4` - الطلب السلبي 4 عند التمرير على الهاتف المحمول
- `.hover:mobile:-order-3` - الطلب السلبي 3 عند التمرير على الهاتف المحمول
- `.hover:mobile:-order-2` - الطلب السلبي 2 عند التمرير على الهاتف المحمول
- `.hover:mobile:-order-1` - الطلب السلبي 1 عند التمرير على الهاتف المحمول
- `.mobile:-order-5` - الطلب السلبي 5 على الهاتف المحمول
- `.mobile:-order-4` - الطلب السلبي 4 على الهاتف المحمول
- `.mobile:-order-3` - الطلب السلبي 3 على الهاتف المحمول
- `.mobile:-order-2` - الطلب السلبي 2 على الهاتف المحمول
- `.mobile:-order-1` - الطلب السلبي 1 على الهاتف المحمول

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - اطلب 5 عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-4` - اطلب 4 عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-3` - اطلب 3 عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-2` - اطلب 2 عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-1` - اطلب 1 عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-0` - اطلب 0 عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-first` - اطلب أولاً عند التمرير على الجهاز اللوحي
- `.hover:tablet:order-last` - اطلب آخر مرة عند التمرير على الجهاز اللوحي
- `.tablet:order-5` - اطلب 5 على الجهاز اللوحي
- `.tablet:order-4` - اطلب 4 على الجهاز اللوحي
- `.tablet:order-3` - اطلب 3 على الجهاز اللوحي
- `.tablet:order-2` - اطلب 2 على الجهاز اللوحي
- `.tablet:order-1` - اطلب 1 على الجهاز اللوحي
- `.tablet:order-0` - اطلب 0 على الجهاز اللوحي
- `.tablet:order-first` - اطلب أولاً على الجهاز اللوحي
- `.tablet:order-last` - الطلب الأخير على الجهاز اللوحي

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - الطلب السلبي 5 عند التمرير على الجهاز اللوحي
- `.hover:tablet:-order-4` - الطلب السلبي 4 عند التمرير على الجهاز اللوحي
- `.hover:tablet:-order-3` - الطلب السلبي 3 عند التمرير على الجهاز اللوحي
- `.hover:tablet:-order-2` - الطلب السلبي 2 عند التمرير على الجهاز اللوحي
- `.hover:tablet:-order-1` - الطلب السلبي 1 عند التمرير على الجهاز اللوحي
- `.tablet:-order-5` - الطلب السلبي 5 على الجهاز اللوحي
- `.tablet:-order-4` - الطلب السلبي 4 على الجهاز اللوحي
- `.tablet:-order-3` - الطلب السلبي 3 على الجهاز اللوحي
- `.tablet:-order-2` - الطلب السلبي 2 على الجهاز اللوحي
- `.tablet:-order-1` - الطلب السلبي 1 على الجهاز اللوحي

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - اطلب 5 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-4` - اطلب 4 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-3` - اطلب 3 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-2` - اطلب 2 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-1` - اطلب 1 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-0` - اطلب 0 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-first` - اطلب أولاً عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:order-last` - اطلب آخر مرة عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:order-5` - اطلب 5 على الكمبيوتر اللوحي
- `.tablet-pc:order-4` - اطلب 4 على الكمبيوتر اللوحي
- `.tablet-pc:order-3` - اطلب 3 على الكمبيوتر اللوحي
- `.tablet-pc:order-2` - اطلب 2 على الكمبيوتر اللوحي
- `.tablet-pc:order-1` - اطلب 1 على الكمبيوتر اللوحي
- `.tablet-pc:order-0` - اطلب 0 على الكمبيوتر اللوحي
- `.tablet-pc:order-first` - اطلب أولاً على الكمبيوتر اللوحي
- `.tablet-pc:order-last` - اطلب أخيرًا على الكمبيوتر اللوحي

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - الطلب السلبي 5 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:-order-4` - الطلب السلبي 4 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:-order-3` - الطلب السلبي 3 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:-order-2` - الطلب السلبي 2 عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:-order-1` - الطلب السلبي 1 عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:-order-5` - الطلب السلبي 5 على الكمبيوتر اللوحي
- `.tablet-pc:-order-4` - الطلب السلبي 4 على الكمبيوتر اللوحي
- `.tablet-pc:-order-3` - الطلب السلبي 3 على الكمبيوتر اللوحي
- `.tablet-pc:-order-2` - الطلب السلبي 2 على الكمبيوتر اللوحي
- `.tablet-pc:-order-1` - الطلب السلبي 1 على الكمبيوتر اللوحي

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - اطلب 5 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-4` - اطلب 4 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-3` - اطلب 3 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-2` - اطلب 2 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-1` - اطلب 1 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-0` - اطلب 0 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-first` - اطلب أولاً عند التمرير على جهاز الكمبيوتر
- `.hover:pc:order-last` - الطلب الأخير عند التمرير على جهاز الكمبيوتر
- `.pc:order-5` - اطلب 5 على جهاز الكمبيوتر
- `.pc:order-4` - اطلب 4 على جهاز الكمبيوتر
- `.pc:order-3` - اطلب 3 على جهاز الكمبيوتر
- `.pc:order-2` - اطلب 2 على جهاز الكمبيوتر
- `.pc:order-1` - اطلب 1 على جهاز الكمبيوتر
- `.pc:order-0` - اطلب 0 على جهاز الكمبيوتر
- `.pc:order-first` - اطلب أولاً على جهاز الكمبيوتر
- `.pc:order-last` - الطلب الأخير على جهاز الكمبيوتر

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - الطلب السلبي 5 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:-order-4` - الطلب السلبي 4 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:-order-3` - الطلب السلبي 3 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:-order-2` - الطلب السلبي 2 عند التمرير على جهاز الكمبيوتر
- `.hover:pc:-order-1` - الطلب السلبي 1 عند التمرير على جهاز الكمبيوتر
- `.pc:-order-5` - الطلب السلبي 5 على جهاز الكمبيوتر
- `.pc:-order-4` - الطلب السلبي 4 على جهاز الكمبيوتر
- `.pc:-order-3` - الطلب السلبي 3 على جهاز الكمبيوتر
- `.pc:-order-2` - الطلب السلبي 2 على جهاز الكمبيوتر
- `.pc:-order-1` - الطلب السلبي 1 على جهاز الكمبيوتر

##### Order - Tv (> 1200px)

- `.hover:tv:order-5` - اطلب 5 عند التمرير على شاشة التلفزيون
- `.hover:tv:order-4` - اطلب 4 عند التمرير على شاشة التلفزيون
- `.hover:tv:order-3` - اطلب 3 عند التمرير على شاشة التلفزيون
- `.hover:tv:order-2` - اطلب 2 عند التمرير على شاشة التلفزيون
- `.hover:tv:order-1` - اطلب 1 عند التمرير على شاشة التلفزيون
- `.hover:tv:order-0` - اطلب 0 عند التمرير على شاشة التلفزيون
- `.hover:tv:order-first` - اطلب أولاً عند التمرير على شاشة التلفزيون
- `.hover:tv:order-last` - الطلب الأخير عند التمرير على شاشة التلفزيون
- `.tv:order-5` - اطلب 5 على شاشة التلفزيون
- `.tv:order-4` - اطلب 4 على شاشة التلفزيون
- `.tv:order-3` - اطلب 3 على شاشة التلفزيون
- `.tv:order-2` - اطلب 2 على شاشة التلفزيون
- `.tv:order-1` - اطلب 1 على شاشة التلفزيون
- `.tv:order-0` - اطلب 0 على شاشة التلفزيون
- `.tv:order-first` - اطلب أولاً على شاشة التلفزيون
- `.tv:order-last` - النظام الأخير على شاشة التلفزيون

##### Negative Order - Tv (> 1200px)

- `.hover:tv:-order-5` - الطلب السلبي 5 عند التمرير على شاشة التلفزيون
- `.hover:tv:-order-4` - الطلب السلبي 4 عند التمرير على شاشة التلفزيون
- `.hover:tv:-order-3` - الطلب السلبي 3 عند التمرير على شاشة التلفزيون
- `.hover:tv:-order-2` - الطلب السلبي 2 عند التمرير على شاشة التلفزيون
- `.hover:tv:-order-1` - الطلب السلبي 1 عند التمرير على شاشة التلفزيون
- `.tv:-order-5` - الطلب السلبي 5 على شاشة التلفزيون
- `.tv:-order-4` - الطلب السلبي 4 على شاشة التلفزيون
- `.tv:-order-3` - الطلب السلبي 3 على شاشة التلفزيون
- `.tv:-order-2` - الطلب السلبي 2 على شاشة التلفزيون
- `.tv:-order-1` - الطلب السلبي 1 على شاشة التلفزيون

##### Order - Tablet Max (< 768px)

- `.hover:tablet-max:order-5` - اطلب 5 عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:order-4` - اطلب 4 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:order-3` - اطلب 3 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:order-2` - اطلب 2 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:order-1` - اطلب 1 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:order-0` - اطلب 0 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:order-first` - اطلب أولاً عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:order-last` - الطلب الأخير عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:order-5` - اطلب 5 على الجهاز اللوحي كحد أقصى
- `.tablet-max:order-4` - اطلب 4 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-max:order-3` - اطلب 3 على الجهاز اللوحي كحد أقصى
- `.tablet-max:order-2` - اطلب 2 على الجهاز اللوحي كحد أقصى
- `.tablet-max:order-1` - اطلب 1 على الجهاز اللوحي كحد أقصى
- `.tablet-max:order-0` - اطلب 0 على الجهاز اللوحي كحد أقصى
- `.tablet-max:order-first` - اطلب أولاً على الجهاز اللوحي بحد أقصى
- `.tablet-max:order-last` - الطلب الأخير على الجهاز اللوحي بحد أقصى

##### Negative Order - Tablet Max (< 768px)

- `.hover:tablet-max:-order-5` - الطلب السلبي 5 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:-order-4` - الطلب السلبي 4 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:-order-3` - الطلب السلبي 3 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:-order-2` - الطلب السلبي 2 عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:-order-1` - الطلب السلبي 1 عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:-order-5` - الطلب السلبي 5 على الجهاز اللوحي كحد أقصى
- `.tablet-max:-order-4` - الطلب السلبي 4 على الجهاز اللوحي كحد أقصى
- `.tablet-max:-order-3` - الطلب السلبي 3 على الجهاز اللوحي كحد أقصى
- `.tablet-max:-order-2` - الطلب السلبي 2 على الجهاز اللوحي كحد أقصى
- `.tablet-max:-order-1` - الطلب السلبي 1 على الجهاز اللوحي بحد أقصى

##### Order - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:order-5` - اطلب 5 عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:order-4` - اطلب 4 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:order-3` - اطلب 3 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:order-2` - اطلب 2 عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:order-1` - اطلب 1 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:order-0` - اطلب 0 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:order-first` - اطلب أولاً عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:order-last` - اطلب آخر مرة عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:order-5` - اطلب 5 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:order-4` - اطلب 4 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:order-3` - اطلب 3 قطع على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:order-2` - اطلب 2 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:order-1` - اطلب 1 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:order-0` - اطلب 0 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:order-first` - اطلب أولاً على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:order-last` - الطلب الأخير على الكمبيوتر اللوحي بحد أقصى

##### Negative Order - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:-order-5` - الطلب السلبي 5 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:-order-4` - الطلب السلبي 4 عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:-order-3` - الطلب السلبي 3 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:-order-2` - الطلب السلبي 2 عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:-order-1` - الطلب السلبي 1 عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:-order-5` - الطلب السلبي 5 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:-order-4` - الطلب السلبي 4 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:-order-3` - الطلب السلبي 3 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:-order-2` - الطلب السلبي 2 على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:-order-1` - الطلب السلبي 1 على الكمبيوتر اللوحي بحد أقصى

##### Order - Pc Max (< 1200px)

- `.hover:pc-max:order-5` - اطلب 5 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-4` - اطلب 4 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-3` - اطلب 3 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-2` - اطلب 2 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-1` - اطلب 1 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-0` - اطلب 0 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-first` - اطلب أولاً عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:order-last` - الطلب الأخير عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-5` - اطلب 5 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-4` - اطلب 4 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-3` - اطلب 3 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-2` - اطلب 2 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-1` - اطلب 1 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-0` - اطلب 0 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-first` - اطلب أولاً على جهاز الكمبيوتر كحد أقصى
- `.pc-max:order-last` - الطلب الأخير على جهاز الكمبيوتر كحد أقصى

##### Negative Order - Pc Max (< 1200px)

- `.hover:pc-max:-order-5` - الطلب السلبي 5 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:-order-4` - الطلب السلبي 4 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:-order-3` - الطلب السلبي 3 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:-order-2` - الطلب السلبي 2 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:-order-1` - الطلب السلبي 1 عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:-order-5` - الطلب السلبي 5 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:-order-4` - الطلب السلبي 4 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:-order-3` - الطلب السلبي 3 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:-order-2` - الطلب السلبي 2 على جهاز الكمبيوتر كحد أقصى
- `.pc-max:-order-1` - الطلب السلبي 1 على جهاز الكمبيوتر كحد أقصى

## Spacing

### Margin

#### Margin All

- `.first:m-0` - هامش الكل 0rem في البداية
- `.hover:m-5` - الهامش الكل 5rem عند التمرير
- `.hover:m-4.5` - الهامش الكل 0rem عند التمرير
- `.hover:m-4` - هامش الكل 4rem عند التمرير
- `.hover:m-3.5` - الهامش الكل 0rem عند التمرير
- `.hover:m-3` - هامش الكل 3rem عند التمرير
- `.hover:m-2.5` - الهامش الكل 0rem عند التمرير
- `.hover:m-2` - هامش الكل 2rem عند التمرير
- `.hover:m-1.9` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.8` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.7` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.6` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.5` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.4` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.3` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.2` - الهامش الكل 0rem عند التمرير
- `.hover:m-1.1` - الهامش الكل 0rem عند التمرير
- `.hover:m-1` - هامش الكل 1rem عند التمرير
- `.hover:m-0.9` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.8` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.7` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.6` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.5` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.4` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.3` - الهامش الكل 0rem عند التمرير
- `.hover:m-0.2` - الهامش الكل 0.2rem عند التمرير
- `.hover:m-0.1` - الهامش الكل 0.1rem عند التمرير
- `.hover:m-0` - الهامش الكل 0rem عند التمرير
- `.hover:m-auto` - الهامش الكل تلقائي عند التمرير
- `.last:m-0` - هامش الكل 0rem في الماضي
- `.m-5` - هامش الكل 5rem
- `.m-4.5` - هامش الكل 0rem
- `.m-4` - هامش الكل 4rem
- `.m-3.5` - هامش الكل 0rem
- `.m-3` - هامش الكل 3rem
- `.m-2.5` - هامش الكل 0rem
- `.m-2` - هامش الكل 2rem
- `.m-1.9` - هامش الكل 0rem
- `.m-1.8` - هامش الكل 0rem
- `.m-1.7` - هامش الكل 0rem
- `.m-1.6` - هامش الكل 0rem
- `.m-1.5` - هامش الكل 0rem
- `.m-1.4` - هامش الكل 0rem
- `.m-1.3` - هامش الكل 0rem
- `.m-1.2` - هامش الكل 0rem
- `.m-1.1` - هامش الكل 0rem
- `.m-1` - هامش الكل 1rem
- `.m-0.9` - هامش الكل 0rem
- `.m-0.8` - هامش الكل 0rem
- `.m-0.7` - هامش الكل 0rem
- `.m-0.6` - هامش الكل 0rem
- `.m-0.5` - هامش الكل 0rem
- `.m-0.4` - هامش الكل 0rem
- `.m-0.3` - هامش الكل 0rem
- `.m-0.2` - هامش الكل 0.2rem
- `.m-0.1` - هامش الكل 0.1rem
- `.m-0` - هامش الكل 0rem
- `.m-auto` - هامش الكل تلقائي

#### Margin Bottom

- `.first:mb-0` - الهامش السفلي 0rem في البداية
- `.hover:mb-100` - الهامش السفلي 100ريم عند التحويم
- `.hover:mb-75` - الهامش السفلي 75rem عند التحويم
- `.hover:mb-50` - الهامش السفلي 50ريم عند التحويم
- `.hover:mb-25` - الهامش السفلي 25rem عند التمرير
- `.hover:mb-5` - الهامش السفلي 5rem عند التمرير
- `.hover:mb-4.5` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-4` - الهامش السفلي 4rem عند التمرير
- `.hover:mb-3.5` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-3` - الهامش السفلي 3rem عند التمرير
- `.hover:mb-2.5` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-2` - الهامش السفلي 2rem عند التمرير
- `.hover:mb-1.9` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.8` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.7` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.6` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.5` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.4` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.3` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.2` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1.1` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-1` - الهامش السفلي 1rem عند التمرير
- `.hover:mb-0.9` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.8` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.7` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.6` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.5` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.4` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.3` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-0.2` - الهامش السفلي 0.2rem عند التمرير
- `.hover:mb-0.1` - الهامش السفلي 0.1rem عند التمرير
- `.hover:mb-0` - الهامش السفلي 0rem عند التمرير
- `.hover:mb-auto` - أسفل الهامش تلقائيًا عند التمرير
- `.last:mb-0` - الهامش السفلي 0rem في الماضي
- `.mb-100` - الهامش السفلي 100ريم
- `.mb-75` - الهامش السفلي 75ريم
- `.mb-50` - الهامش السفلي 50ريم
- `.mb-25` - الهامش السفلي 25ريم
- `.mb-5` - الهامش السفلي 5rem
- `.mb-4.5` - الهامش السفلي 0rem
- `.mb-4` - الهامش السفلي 4rem
- `.mb-3.5` - الهامش السفلي 0rem
- `.mb-3` - الهامش السفلي 3rem
- `.mb-2.5` - الهامش السفلي 0rem
- `.mb-2` - الهامش السفلي 2rem
- `.mb-1.9` - الهامش السفلي 0rem
- `.mb-1.8` - الهامش السفلي 0rem
- `.mb-1.7` - الهامش السفلي 0rem
- `.mb-1.6` - الهامش السفلي 0rem
- `.mb-1.5` - الهامش السفلي 0rem
- `.mb-1.4` - الهامش السفلي 0rem
- `.mb-1.3` - الهامش السفلي 0rem
- `.mb-1.2` - الهامش السفلي 0rem
- `.mb-1.1` - الهامش السفلي 0rem
- `.mb-1` - الهامش السفلي 1rem
- `.mb-0.9` - الهامش السفلي 0rem
- `.mb-0.8` - الهامش السفلي 0rem
- `.mb-0.7` - الهامش السفلي 0rem
- `.mb-0.6` - الهامش السفلي 0rem
- `.mb-0.5` - الهامش السفلي 0rem
- `.mb-0.4` - الهامش السفلي 0rem
- `.mb-0.3` - الهامش السفلي 0rem
- `.mb-0.2` - الهامش السفلي 0.2rem
- `.mb-0.1` - الهامش السفلي 0.1rem
- `.mb-0` - الهامش السفلي 0rem
- `.mb-auto` - الهامش السفلي تلقائي

#### Margin End

- `.hover:me-2` - نهاية الهامش 2rem عند التمرير
- `.hover:me-1.5` - نهاية الهامش 1.5ريم عند التمرير
- `.hover:me-1` - نهاية الهامش 1rem عند التمرير
- `.hover:me-0.5` - نهاية الهامش 0.5ريم عند التمرير
- `.hover:me-0` - نهاية الهامش 0rem عند التمرير
- `.me-2` - نهاية الهامش 2rem
- `.me-1.5` - نهاية الهامش 1.5ريم
- `.me-1` - نهاية الهامش 1rem
- `.me-0.5` - نهاية الهامش 0.5ريم
- `.me-0` - نهاية الهامش 0rem

#### Margin Left

- `.first:ml-0` - الهامش الأيسر 0rem في البداية
- `.hover:ml-100` - الهامش الأيسر 100ريم عند التحويم
- `.hover:ml-75` - الهامش الأيسر 75ريم عند التحويم
- `.hover:ml-50` - الهامش الأيسر 50ريم عند التحويم
- `.hover:ml-25` - الهامش الأيسر 25rem عند التمرير
- `.hover:ml-5` - الهامش الأيسر 5rem عند التمرير
- `.hover:ml-4.5` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-4` - الهامش الأيسر 4rem عند التمرير
- `.hover:ml-3.5` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-3` - الهامش الأيسر 3rem عند التمرير
- `.hover:ml-2.5` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-2` - الهامش الأيسر 2rem عند التمرير
- `.hover:ml-1.9` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.8` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.7` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.6` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.5` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.4` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.3` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.2` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1.1` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-1` - الهامش الأيسر 1rem عند التمرير
- `.hover:ml-0.9` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.8` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.7` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.6` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.5` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.4` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.3` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-0.2` - الهامش الأيسر 0.2rem عند التمرير
- `.hover:ml-0.1` - الهامش الأيسر 0.1ريم عند التمرير
- `.hover:ml-0` - الهامش الأيسر 0rem عند التمرير
- `.hover:ml-auto` - الهامش الأيسر تلقائي عند التمرير
- `.last:ml-0` - الهامش الأيسر 0rem في الماضي
- `.ml-100` - الهامش الأيسر 100ريم
- `.ml-75` - الهامش الأيسر 75ريم
- `.ml-50` - الهامش الأيسر 50ريم
- `.ml-25` - الهامش الأيسر 25ريم
- `.ml-5` - الهامش الأيسر 5ريم
- `.ml-4.5` - الهامش الأيسر 0rem
- `.ml-4` - الهامش الأيسر 4rem
- `.ml-3.5` - الهامش الأيسر 0rem
- `.ml-3` - الهامش الأيسر 3rem
- `.ml-2.5` - الهامش الأيسر 0rem
- `.ml-2` - الهامش الأيسر 2ريم
- `.ml-1.9` - الهامش الأيسر 0rem
- `.ml-1.8` - الهامش الأيسر 0rem
- `.ml-1.7` - الهامش الأيسر 0rem
- `.ml-1.6` - الهامش الأيسر 0rem
- `.ml-1.5` - الهامش الأيسر 0rem
- `.ml-1.4` - الهامش الأيسر 0rem
- `.ml-1.3` - الهامش الأيسر 0rem
- `.ml-1.2` - الهامش الأيسر 0rem
- `.ml-1.1` - الهامش الأيسر 0rem
- `.ml-1` - الهامش الأيسر 1ريم
- `.ml-0.9` - الهامش الأيسر 0rem
- `.ml-0.8` - الهامش الأيسر 0rem
- `.ml-0.7` - الهامش الأيسر 0rem
- `.ml-0.6` - الهامش الأيسر 0rem
- `.ml-0.5` - الهامش الأيسر 0rem
- `.ml-0.4` - الهامش الأيسر 0rem
- `.ml-0.3` - الهامش الأيسر 0rem
- `.ml-0.2` - الهامش الأيسر 0.2ريم
- `.ml-0.1` - الهامش الأيسر 0.1ريم
- `.ml-0` - الهامش الأيسر 0rem
- `.ml-auto` - الهامش الأيسر تلقائي

#### Margin Right

- `.first:mr-0` - الهامش الأيمن 0rem في البداية
- `.hover:mr-100` - الهامش الأيمن 100ريم عند التحويم
- `.hover:mr-75` - الهامش الأيمن 75ريم عند التحويم
- `.hover:mr-50` - الهامش الأيمن 50ريم عند التحويم
- `.hover:mr-25` - الهامش الأيمن 25rem عند التحويم
- `.hover:mr-5` - الهامش الأيمن 5rem عند التمرير
- `.hover:mr-4.5` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-4` - الهامش الأيمن 4rem عند التمرير
- `.hover:mr-3.5` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-3` - الهامش الأيمن 3rem عند التمرير
- `.hover:mr-2.5` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-2` - الهامش الأيمن 2rem عند التمرير
- `.hover:mr-1.9` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.8` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.7` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.6` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.5` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.4` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.3` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.2` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1.1` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-1` - الهامش الأيمن 1rem عند التمرير
- `.hover:mr-0.9` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.8` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.7` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.6` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.5` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.4` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.3` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-0.2` - الهامش الأيمن 0.2rem عند التمرير
- `.hover:mr-0.1` - الهامش الأيمن 0.1rem عند التمرير
- `.hover:mr-0` - الهامش الأيمن 0rem عند التمرير
- `.hover:mr-auto` - الهامش الأيمن تلقائي عند التمرير
- `.last:mr-0` - الهامش الأيمن 0rem في الماضي
- `.mr-100` - الهامش الصحيح 100ريم
- `.mr-75` - الهامش الأيمن 75ريم
- `.mr-50` - الهامش الصحيح 50ريم
- `.mr-25` - الهامش الأيمن 25ريم
- `.mr-5` - الهامش الأيمن 5rem
- `.mr-4.5` - الهامش الأيمن 0rem
- `.mr-4` - الهامش الأيمن 4rem
- `.mr-3.5` - الهامش الأيمن 0rem
- `.mr-3` - الهامش الأيمن 3rem
- `.mr-2.5` - الهامش الأيمن 0rem
- `.mr-2` - الهامش الأيمن 2rem
- `.mr-1.9` - الهامش الأيمن 0rem
- `.mr-1.8` - الهامش الأيمن 0rem
- `.mr-1.7` - الهامش الأيمن 0rem
- `.mr-1.6` - الهامش الأيمن 0rem
- `.mr-1.5` - الهامش الأيمن 0rem
- `.mr-1.4` - الهامش الأيمن 0rem
- `.mr-1.3` - الهامش الأيمن 0rem
- `.mr-1.2` - الهامش الأيمن 0rem
- `.mr-1.1` - الهامش الأيمن 0rem
- `.mr-1` - الهامش الأيمن 1rem
- `.mr-0.9` - الهامش الأيمن 0rem
- `.mr-0.8` - الهامش الأيمن 0rem
- `.mr-0.7` - الهامش الأيمن 0rem
- `.mr-0.6` - الهامش الأيمن 0rem
- `.mr-0.5` - الهامش الأيمن 0rem
- `.mr-0.4` - الهامش الأيمن 0rem
- `.mr-0.3` - الهامش الأيمن 0rem
- `.mr-0.2` - الهامش الأيمن 0.2ريم
- `.mr-0.1` - الهامش الأيمن 0.1rem
- `.mr-0` - الهامش الأيمن 0rem
- `.mr-auto` - الهامش الأيمن تلقائي

#### Margin Start

- `.hover:ms-2` - الهامش يبدأ 2rem عند التمرير
- `.hover:ms-1.5` - الهامش يبدأ 1.5ريم عند التحويم
- `.hover:ms-1` - الهامش يبدأ 1rem عند التمرير
- `.hover:ms-0.5` - الهامش يبدأ 0.5ريم عند التمرير
- `.hover:ms-0` - الهامش يبدأ 0rem عند التمرير
- `.ms-2` - هامش البداية 2ريم
- `.ms-1.5` - الهامش يبدأ 1.5ريم
- `.ms-1` - الهامش يبدأ 1ريم
- `.ms-0.5` - الهامش يبدأ 0.5ريم
- `.ms-0` - الهامش يبدأ 0rem

#### Margin Top

- `.first:mt-0` - الهامش الأعلى 0rem في البداية
- `.hover:mt-100` - أعلى هامش 100rem عند التمرير
- `.hover:mt-75` - أعلى الهامش 75rem عند التمرير
- `.hover:mt-50` - أعلى هامش 50rem عند التمرير
- `.hover:mt-25` - أعلى هامش 25rem عند التمرير
- `.hover:mt-5` - أعلى الهامش 5rem عند التمرير
- `.hover:mt-4.5` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-4` - أعلى الهامش 4rem عند التمرير
- `.hover:mt-3.5` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-3` - أعلى الهامش 3rem عند التمرير
- `.hover:mt-2.5` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-2` - أعلى الهامش 2rem عند التمرير
- `.hover:mt-1.9` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.8` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.7` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.6` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.5` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.4` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.3` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.2` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1.1` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-1` - أعلى الهامش 1rem عند التمرير
- `.hover:mt-0.9` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.8` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.7` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.6` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.5` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.4` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.3` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-0.2` - أعلى الهامش 0.2rem عند التمرير
- `.hover:mt-0.1` - أعلى الهامش 0.1rem عند التمرير
- `.hover:mt-0` - أعلى الهامش 0rem عند التمرير
- `.hover:mt-auto` - أعلى الهامش تلقائيًا عند التمرير
- `.last:mt-0` - الهامش الأعلى 0rem في الماضي
- `.mt-100` - الهامش الأعلى 100ريم
- `.mt-75` - الهامش الأعلى 75ريم
- `.mt-50` - الهامش الأعلى 50ريم
- `.mt-25` - الهامش الأعلى 25rem
- `.mt-5` - الهامش الأعلى 5rem
- `.mt-4.5` - الهامش الأعلى 0rem
- `.mt-4` - الهامش الأعلى 4rem
- `.mt-3.5` - الهامش الأعلى 0rem
- `.mt-3` - الهامش الأعلى 3rem
- `.mt-2.5` - الهامش الأعلى 0rem
- `.mt-2` - الهامش الأعلى 2rem
- `.mt-1.9` - الهامش الأعلى 0rem
- `.mt-1.8` - الهامش الأعلى 0rem
- `.mt-1.7` - الهامش الأعلى 0rem
- `.mt-1.6` - الهامش الأعلى 0rem
- `.mt-1.5` - الهامش الأعلى 0rem
- `.mt-1.4` - الهامش الأعلى 0rem
- `.mt-1.3` - الهامش الأعلى 0rem
- `.mt-1.2` - الهامش الأعلى 0rem
- `.mt-1.1` - الهامش الأعلى 0rem
- `.mt-1` - الهامش الأعلى 1rem
- `.mt-0.9` - الهامش الأعلى 0rem
- `.mt-0.8` - الهامش الأعلى 0rem
- `.mt-0.7` - الهامش الأعلى 0rem
- `.mt-0.6` - الهامش الأعلى 0rem
- `.mt-0.5` - الهامش الأعلى 0rem
- `.mt-0.4` - الهامش الأعلى 0rem
- `.mt-0.3` - الهامش الأعلى 0rem
- `.mt-0.2` - الهامش الأعلى 0.2rem
- `.mt-0.1` - الهامش الأعلى 0.1rem
- `.mt-0` - الهامش الأعلى 0rem
- `.mt-auto` - هامش أعلى السيارات

#### Margin X-Axis

- `.hover:mx-100` - هامش المحور X 100rem عند التمرير
- `.hover:mx-75` - هامش المحور X 75rem عند التمرير
- `.hover:mx-50` - هامش المحور X 50rem عند التمرير
- `.hover:mx-25` - هامش المحور X 25rem عند التمرير
- `.hover:mx-5` - هامش المحور السيني 5rem عند التمرير
- `.hover:mx-4.5` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-4` - هامش المحور السيني 4rem عند التمرير
- `.hover:mx-3.5` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-3` - هامش المحور السيني 3rem عند التمرير
- `.hover:mx-2.5` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-2` - هامش المحور السيني 2rem عند التمرير
- `.hover:mx-1.9` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.8` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.7` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.6` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.5` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.4` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.3` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.2` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1.1` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-1` - هامش المحور X 1rem عند التمرير
- `.hover:mx-0.9` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.8` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.7` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.6` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.5` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.4` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.3` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-0.2` - هامش المحور X 0.2rem عند التمرير
- `.hover:mx-0.1` - هامش المحور X 0.1rem عند التمرير
- `.hover:mx-0` - هامش المحور السيني 0rem عند التمرير
- `.hover:mx-auto` - هامش المحور X تلقائي عند التمرير
- `.mx-100` - هامش المحور السيني 100ريم
- `.mx-75` - هامش المحور السيني 75ريم
- `.mx-50` - هامش المحور السيني 50ريم
- `.mx-25` - هامش المحور السيني 25rem
- `.mx-5` - هامش المحور X 5rem
- `.mx-4.5` - هامش المحور X 0rem
- `.mx-4` - هامش المحور X 4rem
- `.mx-3.5` - هامش المحور X 0rem
- `.mx-3` - هامش المحور X 3rem
- `.mx-2.5` - هامش المحور X 0rem
- `.mx-2` - هامش المحور X 2rem
- `.mx-1.9` - هامش المحور X 0rem
- `.mx-1.8` - هامش المحور X 0rem
- `.mx-1.7` - هامش المحور X 0rem
- `.mx-1.6` - هامش المحور X 0rem
- `.mx-1.5` - هامش المحور X 0rem
- `.mx-1.4` - هامش المحور X 0rem
- `.mx-1.3` - هامش المحور X 0rem
- `.mx-1.2` - هامش المحور X 0rem
- `.mx-1.1` - هامش المحور X 0rem
- `.mx-1` - هامش المحور X 1rem
- `.mx-0.9` - هامش المحور X 0rem
- `.mx-0.8` - هامش المحور X 0rem
- `.mx-0.7` - هامش المحور X 0rem
- `.mx-0.6` - هامش المحور X 0rem
- `.mx-0.5` - هامش المحور X 0rem
- `.mx-0.4` - هامش المحور X 0rem
- `.mx-0.3` - هامش المحور X 0rem
- `.mx-0.2` - هامش المحور السيني 0.2rem
- `.mx-0.1` - هامش المحور السيني 0.1rem
- `.mx-0` - هامش المحور X 0rem
- `.mx-auto` - هامش المحور X تلقائي

#### Margin Y-Axis

- `.hover:my-100` - هامش المحور Y 100rem عند التمرير
- `.hover:my-75` - هامش المحور Y 75rem عند التمرير
- `.hover:my-50` - هامش المحور Y 50rem عند التمرير
- `.hover:my-25` - هامش المحور Y 25rem عند التمرير
- `.hover:my-5` - هامش المحور Y 5rem عند التمرير
- `.hover:my-4.5` - هامش المحور ص 0rem عند التمرير
- `.hover:my-4` - هامش المحور Y 4rem عند التمرير
- `.hover:my-3.5` - هامش المحور ص 0rem عند التمرير
- `.hover:my-3` - هامش المحور Y 3rem عند التمرير
- `.hover:my-2.5` - هامش المحور ص 0rem عند التمرير
- `.hover:my-2` - هامش المحور Y 2rem عند التمرير
- `.hover:my-1.9` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.8` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.7` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.6` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.5` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.4` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.3` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.2` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1.1` - هامش المحور ص 0rem عند التمرير
- `.hover:my-1` - هامش المحور ص 1rem عند التمرير
- `.hover:my-0.9` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.8` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.7` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.6` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.5` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.4` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.3` - هامش المحور ص 0rem عند التمرير
- `.hover:my-0.2` - هامش المحور Y 0.2rem عند التمرير
- `.hover:my-0.1` - هامش المحور Y 0.1rem عند التمرير
- `.hover:my-0` - هامش المحور ص 0rem عند التمرير
- `.hover:my-auto` - هامش المحور Y تلقائي عند التمرير
- `.my-100` - هامش المحور ص 100ريم
- `.my-75` - Margin Y-Axis 75rem
- `.my-50` - هامش المحور ص 50ريم
- `.my-25` - هامش المحور Y 25rem
- `.my-5` - Margin Y-Axis 5rem
- `.my-4.5` - هامش المحور ص 0rem
- `.my-4` - هامش المحور Y 4rem
- `.my-3.5` - هامش المحور ص 0rem
- `.my-3` - هامش المحور ص 3rem
- `.my-2.5` - هامش المحور ص 0rem
- `.my-2` - هامش المحور Y 2rem
- `.my-1.9` - هامش المحور ص 0rem
- `.my-1.8` - هامش المحور ص 0rem
- `.my-1.7` - هامش المحور ص 0rem
- `.my-1.6` - هامش المحور ص 0rem
- `.my-1.5` - هامش المحور ص 0rem
- `.my-1.4` - هامش المحور ص 0rem
- `.my-1.3` - هامش المحور ص 0rem
- `.my-1.2` - هامش المحور ص 0rem
- `.my-1.1` - هامش المحور ص 0rem
- `.my-1` - هامش المحور ص 1rem
- `.my-0.9` - هامش المحور ص 0rem
- `.my-0.8` - هامش المحور ص 0rem
- `.my-0.7` - هامش المحور ص 0rem
- `.my-0.6` - هامش المحور ص 0rem
- `.my-0.5` - هامش المحور ص 0rem
- `.my-0.4` - هامش المحور ص 0rem
- `.my-0.3` - هامش المحور ص 0rem
- `.my-0.2` - هامش المحور Y 0.2rem
- `.my-0.1` - هامش المحور Y 0.1rem
- `.my-0` - هامش المحور ص 0rem
- `.my-auto` - هامش المحور Y تلقائي

### Padding

#### Padding All

- `.first:p-0` - الحشو الكل 0rem في البداية
- `.hover:p-5` - الحشو كل 5rem عند التحويم
- `.hover:p-4.5` - الحشو كل 0rem عند التحويم
- `.hover:p-4` - الحشو كل 4rem عند التحويم
- `.hover:p-3.5` - الحشو كل 0rem عند التحويم
- `.hover:p-3` - الحشو كل 3rem عند التحويم
- `.hover:p-2.5` - الحشو كل 0rem عند التحويم
- `.hover:p-2` - الحشو كل 2rem عند التحويم
- `.hover:p-1.9` - الحشو كل 0rem عند التحويم
- `.hover:p-1.8` - الحشو كل 0rem عند التحويم
- `.hover:p-1.7` - الحشو كل 0rem عند التحويم
- `.hover:p-1.6` - الحشو كل 0rem عند التحويم
- `.hover:p-1.5` - الحشو كل 0rem عند التحويم
- `.hover:p-1.4` - الحشو كل 0rem عند التحويم
- `.hover:p-1.3` - الحشو كل 0rem عند التحويم
- `.hover:p-1.2` - الحشو كل 0rem عند التحويم
- `.hover:p-1.1` - الحشو كل 0rem عند التحويم
- `.hover:p-1` - الحشو كل 1rem عند التمرير
- `.hover:p-0.9` - الحشو كل 0rem عند التحويم
- `.hover:p-0.8` - الحشو كل 0rem عند التحويم
- `.hover:p-0.7` - الحشو كل 0rem عند التحويم
- `.hover:p-0.6` - الحشو كل 0rem عند التحويم
- `.hover:p-0.5` - الحشو كل 0rem عند التحويم
- `.hover:p-0.4` - الحشو كل 0rem عند التحويم
- `.hover:p-0.3` - الحشو كل 0rem عند التحويم
- `.hover:p-0.2` - الحشو كل 0.2rem عند التمرير
- `.hover:p-0.1` - الحشو كل 0.1rem عند التمرير
- `.hover:p-0` - الحشو كل 0rem عند التحويم
- `.last:p-0` - الحشو جميع 0rem في الماضي
- `.p-5` - الحشو جميع 5rem
- `.p-4.5` - الحشو الكل 0rem
- `.p-4` - الحشو جميع 4rem
- `.p-3.5` - الحشو الكل 0rem
- `.p-3` - الحشو جميع 3rem
- `.p-2.5` - الحشو الكل 0rem
- `.p-2` - الحشو جميع 2rem
- `.p-1.9` - الحشو الكل 0rem
- `.p-1.8` - الحشو الكل 0rem
- `.p-1.7` - الحشو الكل 0rem
- `.p-1.6` - الحشو الكل 0rem
- `.p-1.5` - الحشو الكل 0rem
- `.p-1.4` - الحشو الكل 0rem
- `.p-1.3` - الحشو الكل 0rem
- `.p-1.2` - الحشو الكل 0rem
- `.p-1.1` - الحشو الكل 0rem
- `.p-1` - الحشو الكل 1rem
- `.p-0.9` - الحشو الكل 0rem
- `.p-0.8` - الحشو الكل 0rem
- `.p-0.7` - الحشو الكل 0rem
- `.p-0.6` - الحشو الكل 0rem
- `.p-0.5` - الحشو الكل 0rem
- `.p-0.4` - الحشو الكل 0rem
- `.p-0.3` - الحشو الكل 0rem
- `.p-0.2` - الحشو الكل 0.2rem
- `.p-0.1` - الحشو الكل 0.1rem
- `.p-0` - الحشو الكل 0rem

#### Padding Bottom

- `.first:pb-0` - الحشو السفلي 0rem في البداية
- `.hover:pb-100` - الحشو السفلي 100ريم عند التحويم
- `.hover:pb-75` - الحشو السفلي 75rem عند التحويم
- `.hover:pb-50` - الحشو السفلي 50rem عند التحويم
- `.hover:pb-25` - الحشو السفلي 25rem عند التحويم
- `.hover:pb-5` - الحشو أسفل 5rem عند التحويم
- `.hover:pb-4.5` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-4` - الحشو السفلي 4rem عند التحويم
- `.hover:pb-3.5` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-3` - الحشو أسفل 3rem عند التحويم
- `.hover:pb-2.5` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-2` - الحشو أسفل 2rem عند التحويم
- `.hover:pb-1.9` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.8` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.7` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.6` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.5` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.4` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.3` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.2` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1.1` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-1` - الحشو السفلي 1rem عند التمرير
- `.hover:pb-0.9` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.8` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.7` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.6` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.5` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.4` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.3` - الحشو السفلي 0rem عند التحويم
- `.hover:pb-0.2` - الحشو السفلي 0.2rem عند التحويم
- `.hover:pb-0.1` - الحشو السفلي 0.1rem عند التحويم
- `.hover:pb-0` - الحشو السفلي 0rem عند التحويم
- `.last:pb-0` - الحشو أسفل 0rem في الماضي
- `.pb-100` - الحشو السفلي 100ريم
- `.pb-75` - الحشو السفلي 75ريم
- `.pb-50` - الحشو السفلي 50ريم
- `.pb-25` - الحشو السفلي 25ريم
- `.pb-5` - الحشو السفلي 5rem
- `.pb-4.5` - الحشو السفلي 0rem
- `.pb-4` - الحشو السفلي 4rem
- `.pb-3.5` - الحشو السفلي 0rem
- `.pb-3` - الحشو السفلي 3rem
- `.pb-2.5` - الحشو السفلي 0rem
- `.pb-2` - الحشو السفلي 2rem
- `.pb-1.9` - الحشو السفلي 0rem
- `.pb-1.8` - الحشو السفلي 0rem
- `.pb-1.7` - الحشو السفلي 0rem
- `.pb-1.6` - الحشو السفلي 0rem
- `.pb-1.5` - الحشو السفلي 0rem
- `.pb-1.4` - الحشو السفلي 0rem
- `.pb-1.3` - الحشو السفلي 0rem
- `.pb-1.2` - الحشو السفلي 0rem
- `.pb-1.1` - الحشو السفلي 0rem
- `.pb-1` - الحشو السفلي 1rem
- `.pb-0.9` - الحشو السفلي 0rem
- `.pb-0.8` - الحشو السفلي 0rem
- `.pb-0.7` - الحشو السفلي 0rem
- `.pb-0.6` - الحشو السفلي 0rem
- `.pb-0.5` - الحشو السفلي 0rem
- `.pb-0.4` - الحشو السفلي 0rem
- `.pb-0.3` - الحشو السفلي 0rem
- `.pb-0.2` - الحشو السفلي 0.2rem
- `.pb-0.1` - الحشو السفلي 0.1rem
- `.pb-0` - الحشو السفلي 0rem

#### Padding Left

- `.first:pl-0` - الحشو الأيسر 0rem في البداية
- `.hover:pl-5` - الحشو الأيسر 5rem عند التحويم
- `.hover:pl-4.5` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-4` - الحشو الأيسر 4rem عند التحويم
- `.hover:pl-3.5` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-3` - الحشو الأيسر 3rem عند التمرير
- `.hover:pl-2.5` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-2` - الحشو الأيسر 2rem عند التمرير
- `.hover:pl-1.9` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.8` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.7` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.6` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.5` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.4` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.3` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.2` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1.1` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-1` - الحشو الأيسر 1rem عند التمرير
- `.hover:pl-0.9` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.8` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.7` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.6` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.5` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.4` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.3` - الحشو الأيسر 0rem عند التمرير
- `.hover:pl-0.2` - الحشو الأيسر 0.2rem عند التحويم
- `.hover:pl-0.1` - الحشو الأيسر 0.1ريم عند التحويم
- `.hover:pl-0` - الحشو الأيسر 0rem عند التمرير
- `.last:pl-0` - الحشو الأيسر 0rem في الماضي
- `.pl-5` - الحشو الأيسر 5ريم
- `.pl-4.5` - الحشو الأيسر 0rem
- `.pl-4` - الحشو الأيسر 4ريم
- `.pl-3.5` - الحشو الأيسر 0rem
- `.pl-3` - الحشو الأيسر 3rem
- `.pl-2.5` - الحشو الأيسر 0rem
- `.pl-2` - الحشو الأيسر 2rem
- `.pl-1.9` - الحشو الأيسر 0rem
- `.pl-1.8` - الحشو الأيسر 0rem
- `.pl-1.7` - الحشو الأيسر 0rem
- `.pl-1.6` - الحشو الأيسر 0rem
- `.pl-1.5` - الحشو الأيسر 0rem
- `.pl-1.4` - الحشو الأيسر 0rem
- `.pl-1.3` - الحشو الأيسر 0rem
- `.pl-1.2` - الحشو الأيسر 0rem
- `.pl-1.1` - الحشو الأيسر 0rem
- `.pl-1` - الحشو الأيسر 1rem
- `.pl-0.9` - الحشو الأيسر 0rem
- `.pl-0.8` - الحشو الأيسر 0rem
- `.pl-0.7` - الحشو الأيسر 0rem
- `.pl-0.6` - الحشو الأيسر 0rem
- `.pl-0.5` - الحشو الأيسر 0rem
- `.pl-0.4` - الحشو الأيسر 0rem
- `.pl-0.3` - الحشو الأيسر 0rem
- `.pl-0.2` - الحشو الأيسر 0.2rem
- `.pl-0.1` - الحشو الأيسر 0.1rem
- `.pl-0` - الحشو الأيسر 0rem

#### Padding Right

- `.first:pr-0` - الحشو الأيمن 0rem في البداية
- `.hover:pr-100` - الحشو الأيمن 100ريم عند التحويم
- `.hover:pr-75` - الحشو الصحيح 75rem عند التحويم
- `.hover:pr-50` - الحشو الصحيح 50ريم عند التحويم
- `.hover:pr-25` - الحشو الصحيح 25rem عند التحويم
- `.hover:pr-5` - الحشو الصحيح 5rem عند التحويم
- `.hover:pr-4.5` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-4` - الحشو الصحيح 4rem عند التحويم
- `.hover:pr-3.5` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-3` - الحشو الصحيح 3rem عند التحويم
- `.hover:pr-2.5` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-2` - الحشو الأيمن 2rem عند التحويم
- `.hover:pr-1.9` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.8` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.7` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.6` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.5` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.4` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.3` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.2` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1.1` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-1` - الحشو الصحيح 1rem عند التمرير
- `.hover:pr-0.9` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.8` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.7` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.6` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.5` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.4` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.3` - الحشو الأيمن 0rem عند التحويم
- `.hover:pr-0.2` - الحشو الأيمن 0.2ريم عند التحويم
- `.hover:pr-0.1` - الحشو الأيمن 0.1ريم عند التحويم
- `.hover:pr-0` - الحشو الأيمن 0rem عند التحويم
- `.last:pr-0` - الحشو الأيمن 0rem في الماضي
- `.pr-100` - الحشو الصحيح 100ريم
- `.pr-75` - الحشو الصحيح 75ريم
- `.pr-50` - الحشو الصحيح 50ريم
- `.pr-25` - الحشو الصحيح 25ريم
- `.pr-5` - الحشو الصحيح 5rem
- `.pr-4.5` - الحشو الأيمن 0rem
- `.pr-4` - الحشو الصحيح 4rem
- `.pr-3.5` - الحشو الأيمن 0rem
- `.pr-3` - الحشو الصحيح 3rem
- `.pr-2.5` - الحشو الأيمن 0rem
- `.pr-2` - الحشو الصحيح 2rem
- `.pr-1.9` - الحشو الأيمن 0rem
- `.pr-1.8` - الحشو الأيمن 0rem
- `.pr-1.7` - الحشو الأيمن 0rem
- `.pr-1.6` - الحشو الأيمن 0rem
- `.pr-1.5` - الحشو الأيمن 0rem
- `.pr-1.4` - الحشو الأيمن 0rem
- `.pr-1.3` - الحشو الأيمن 0rem
- `.pr-1.2` - الحشو الأيمن 0rem
- `.pr-1.1` - الحشو الأيمن 0rem
- `.pr-1` - الحشو الصحيح 1rem
- `.pr-0.9` - الحشو الأيمن 0rem
- `.pr-0.8` - الحشو الأيمن 0rem
- `.pr-0.7` - الحشو الأيمن 0rem
- `.pr-0.6` - الحشو الأيمن 0rem
- `.pr-0.5` - الحشو الأيمن 0rem
- `.pr-0.4` - الحشو الأيمن 0rem
- `.pr-0.3` - الحشو الأيمن 0rem
- `.pr-0.2` - الحشو الأيمن 0.2rem
- `.pr-0.1` - الحشو الأيمن 0.1rem
- `.pr-0` - الحشو الأيمن 0rem

#### Padding Top

- `.first:pt-0` - الحشو أعلى 0rem في البداية
- `.hover:pt-100` - الحشو أعلى 100rem عند التحويم
- `.hover:pt-75` - الحشو أعلى 75rem عند التحويم
- `.hover:pt-50` - الحشو أعلى 50rem عند التحويم
- `.hover:pt-25` - الحشو أعلى 25rem عند التحويم
- `.hover:pt-5` - الحشو أعلى 5rem عند التحويم
- `.hover:pt-4.5` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-4` - الحشو أعلى 4rem عند التحويم
- `.hover:pt-3.5` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-3` - الحشو أعلى 3rem عند التحويم
- `.hover:pt-2.5` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-2` - الحشو أعلى 2rem عند التحويم
- `.hover:pt-1.9` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.8` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.7` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.6` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.5` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.4` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.3` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.2` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1.1` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-1` - الحشو أعلى 1rem عند التمرير
- `.hover:pt-0.9` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.8` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.7` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.6` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.5` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.4` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.3` - الحشو أعلى 0rem عند التحويم
- `.hover:pt-0.2` - الحشو العلوي 0.2rem عند التحويم
- `.hover:pt-0.1` - الحشو العلوي 0.1rem عند التحويم
- `.hover:pt-0` - الحشو أعلى 0rem عند التحويم
- `.last:pt-0` - الحشو أعلى 0rem في الماضي
- `.pt-100` - الحشو أعلى 100ريم
- `.pt-75` - الحشو أعلى 75rem
- `.pt-50` - الحشو أعلى 50rem
- `.pt-25` - الحشو أعلى 25rem
- `.pt-5` - الحشو أعلى 5rem
- `.pt-4.5` - الحشو أعلى 0rem
- `.pt-4` - الحشو أعلى 4rem
- `.pt-3.5` - الحشو أعلى 0rem
- `.pt-3` - الحشو أعلى 3rem
- `.pt-2.5` - الحشو أعلى 0rem
- `.pt-2` - الحشو أعلى 2rem
- `.pt-1.9` - الحشو أعلى 0rem
- `.pt-1.8` - الحشو أعلى 0rem
- `.pt-1.7` - الحشو أعلى 0rem
- `.pt-1.6` - الحشو أعلى 0rem
- `.pt-1.5` - الحشو أعلى 0rem
- `.pt-1.4` - الحشو أعلى 0rem
- `.pt-1.3` - الحشو أعلى 0rem
- `.pt-1.2` - الحشو أعلى 0rem
- `.pt-1.1` - الحشو أعلى 0rem
- `.pt-1` - الحشو أعلى 1rem
- `.pt-0.9` - الحشو أعلى 0rem
- `.pt-0.8` - الحشو أعلى 0rem
- `.pt-0.7` - الحشو أعلى 0rem
- `.pt-0.6` - الحشو أعلى 0rem
- `.pt-0.5` - الحشو أعلى 0rem
- `.pt-0.4` - الحشو أعلى 0rem
- `.pt-0.3` - الحشو أعلى 0rem
- `.pt-0.2` - الحشو العلوي 0.2rem
- `.pt-0.1` - الحشو العلوي 0.1rem
- `.pt-0` - الحشو أعلى 0rem

#### Padding X-Axis

- `.hover:px-100` - حشو المحور X 100rem عند التحويم
- `.hover:px-75` - حشو المحور X 75rem عند التحويم
- `.hover:px-50` - حشو المحور X 50rem عند التحويم
- `.hover:px-25` - حشو المحور X 25rem عند التحويم
- `.hover:px-5` - حشو المحور X 5rem عند التمرير
- `.hover:px-4.5` - حشو المحور X 0rem عند التمرير
- `.hover:px-4` - حشو المحور X 4rem عند التمرير
- `.hover:px-3.5` - حشو المحور X 0rem عند التمرير
- `.hover:px-3` - حشو المحور X 3rem عند التمرير
- `.hover:px-2.5` - حشو المحور X 0rem عند التمرير
- `.hover:px-2` - حشو المحور X 2rem عند التمرير
- `.hover:px-1.9` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.8` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.7` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.6` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.5` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.4` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.3` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.2` - حشو المحور X 0rem عند التمرير
- `.hover:px-1.1` - حشو المحور X 0rem عند التمرير
- `.hover:px-1` - حشو المحور X 1rem عند التمرير
- `.hover:px-0.9` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.8` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.7` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.6` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.5` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.4` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.3` - حشو المحور X 0rem عند التمرير
- `.hover:px-0.2` - حشو المحور X 0.2rem عند التحويم
- `.hover:px-0.1` - حشو المحور X 0.1rem عند التمرير
- `.hover:px-0` - حشو المحور X 0rem عند التمرير
- `.px-100` - حشوة المحور X 100rem
- `.px-75` - حشوة المحور X 75rem
- `.px-50` - حشوة المحور X 50rem
- `.px-25` - حشوة المحور X 25rem
- `.px-5` - حشوة المحور X 5rem
- `.px-4.5` - حشوة المحور X 0rem
- `.px-4` - حشوة المحور X 4rem
- `.px-3.5` - حشوة المحور X 0rem
- `.px-3` - حشوة المحور X 3rem
- `.px-2.5` - حشوة المحور X 0rem
- `.px-2` - حشوة المحور X 2rem
- `.px-1.9` - حشوة المحور X 0rem
- `.px-1.8` - حشوة المحور X 0rem
- `.px-1.7` - حشوة المحور X 0rem
- `.px-1.6` - حشوة المحور X 0rem
- `.px-1.5` - حشوة المحور X 0rem
- `.px-1.4` - حشوة المحور X 0rem
- `.px-1.3` - حشوة المحور X 0rem
- `.px-1.2` - حشوة المحور X 0rem
- `.px-1.1` - حشوة المحور X 0rem
- `.px-1` - حشوة المحور X 1rem
- `.px-0.9` - حشوة المحور X 0rem
- `.px-0.8` - حشوة المحور X 0rem
- `.px-0.7` - حشوة المحور X 0rem
- `.px-0.6` - حشوة المحور X 0rem
- `.px-0.5` - حشوة المحور X 0rem
- `.px-0.4` - حشوة المحور X 0rem
- `.px-0.3` - حشوة المحور X 0rem
- `.px-0.2` - حشوة المحور X 0.2rem
- `.px-0.1` - حشوة المحور X 0.1rem
- `.px-0` - حشوة المحور X 0rem

#### Padding Y-Axis

- `.hover:py-100` - حشو المحور Y 100rem عند التحويم
- `.hover:py-75` - حشوة المحور Y 75rem عند التحويم
- `.hover:py-50` - حشو المحور Y 50rem عند التحويم
- `.hover:py-25` - حشو المحور Y 25rem عند التحويم
- `.hover:py-5` - حشو المحور Y 5rem عند التمرير
- `.hover:py-4.5` - حشو المحور Y 0rem عند التمرير
- `.hover:py-4` - حشو المحور Y 4rem عند التحويم
- `.hover:py-3.5` - حشو المحور Y 0rem عند التمرير
- `.hover:py-3` - حشو المحور Y 3rem عند التمرير
- `.hover:py-2.5` - حشو المحور Y 0rem عند التمرير
- `.hover:py-2` - حشو المحور Y 2rem عند التمرير
- `.hover:py-1.9` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.8` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.7` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.6` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.5` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.4` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.3` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.2` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1.1` - حشو المحور Y 0rem عند التمرير
- `.hover:py-1` - حشو المحور Y 1rem عند التمرير
- `.hover:py-0.9` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.8` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.7` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.6` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.5` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.4` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.3` - حشو المحور Y 0rem عند التمرير
- `.hover:py-0.2` - حشوة المحور Y 0.2rem عند التحويم
- `.hover:py-0.1` - حشوة المحور Y 0.1rem عند التحويم
- `.hover:py-0` - حشو المحور Y 0rem عند التمرير
- `.py-100` - حشوة المحور Y 100ريم
- `.py-75` - حشوة المحور Y 75rem
- `.py-50` - حشوة المحور Y 50rem
- `.py-25` - حشوة المحور Y 25rem
- `.py-5` - حشوة المحور Y 5rem
- `.py-4.5` - حشوة المحور Y 0rem
- `.py-4` - حشوة المحور Y 4rem
- `.py-3.5` - حشوة المحور Y 0rem
- `.py-3` - حشوة المحور Y 3rem
- `.py-2.5` - حشوة المحور Y 0rem
- `.py-2` - حشوة المحور Y 2rem
- `.py-1.9` - حشوة المحور Y 0rem
- `.py-1.8` - حشوة المحور Y 0rem
- `.py-1.7` - حشوة المحور Y 0rem
- `.py-1.6` - حشوة المحور Y 0rem
- `.py-1.5` - حشوة المحور Y 0rem
- `.py-1.4` - حشوة المحور Y 0rem
- `.py-1.3` - حشوة المحور Y 0rem
- `.py-1.2` - حشوة المحور Y 0rem
- `.py-1.1` - حشوة المحور Y 0rem
- `.py-1` - حشوة المحور Y 1rem
- `.py-0.9` - حشوة المحور Y 0rem
- `.py-0.8` - حشوة المحور Y 0rem
- `.py-0.7` - حشوة المحور Y 0rem
- `.py-0.6` - حشوة المحور Y 0rem
- `.py-0.5` - حشوة المحور Y 0rem
- `.py-0.4` - حشوة المحور Y 0rem
- `.py-0.3` - حشوة المحور Y 0rem
- `.py-0.2` - حشوة المحور Y 0.2rem
- `.py-0.1` - حشوة المحور Y 0.1rem
- `.py-0` - حشوة المحور Y 0rem

## Sizing

### Width

- `.hover:w-100` - العرض 100% عند التمرير
- `.hover:w-95` - العرض 95% عند التحويم
- `.hover:w-90` - العرض 90% عند التحويم
- `.hover:w-85` - العرض 85% عند التحويم
- `.hover:w-80` - العرض 80% عند التحويم
- `.hover:w-75` - العرض 75% عند التحويم
- `.hover:w-70` - العرض 70% عند التحويم
- `.hover:w-65` - العرض 65% عند التحويم
- `.hover:w-60` - العرض 60% عند التحويم
- `.hover:w-55` - العرض 55% عند التحويم
- `.hover:w-50` - العرض 50% عند التحويم
- `.hover:w-45` - العرض 45% عند التحويم
- `.hover:w-40` - العرض 40% عند التحويم
- `.hover:w-35` - العرض 35% عند التحويم
- `.hover:w-30` - العرض 30% عند التحويم
- `.hover:w-25` - العرض 25% عند التحويم
- `.hover:w-20` - العرض 20% عند التحويم
- `.hover:w-15` - العرض 15% عند التحويم
- `.hover:w-10` - العرض 10% عند التحويم
- `.hover:w-5` - العرض 5% عند التحويم
- `.hover:w-auto` - العرض التلقائي٪ عند التمرير
- `.w-100` - العرض 100%
- `.w-95` - العرض 95%
- `.w-90` - العرض 90%
- `.w-85` - العرض 85%
- `.w-80` - العرض 80%
- `.w-75` - العرض 75%
- `.w-70` - العرض 70%
- `.w-65` - العرض 65%
- `.w-60` - العرض 60%
- `.w-55` - العرض 55%
- `.w-50` - العرض 50%
- `.w-45` - العرض 45%
- `.w-40` - العرض 40%
- `.w-35` - العرض 35%
- `.w-30` - العرض 30%
- `.w-25` - العرض 25%
- `.w-20` - العرض 20%
- `.w-15` - العرض 15%
- `.w-10` - العرض 10%
- `.w-5` - العرض 5%
- `.w-auto` - العرض التلقائي٪

##### Width - Mobile (< 480px)

- `.hover:mobile:w-100` - العرض 100% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-95` - العرض 95% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-90` - العرض 90% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-85` - العرض 85% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-80` - العرض 80% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-75` - العرض 75% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-70` - العرض 70% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-65` - العرض 65% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-60` - العرض 60% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-55` - العرض 55% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-50` - العرض 50% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-45` - العرض 45% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-40` - العرض 40% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-35` - العرض 35% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-30` - العرض 30% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-25` - العرض 25% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-20` - العرض 20% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-15` - العرض 15% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-10` - العرض 10% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-5` - العرض 5% عند التمرير على الهاتف المحمول
- `.hover:mobile:w-auto` - العرض٪ تلقائي عند التمرير على الهاتف المحمول
- `.mobile:w-100` - العرض 100% على الهاتف المحمول
- `.mobile:w-95` - العرض 95% على الهاتف المحمول
- `.mobile:w-90` - العرض 90% على الهاتف المحمول
- `.mobile:w-85` - العرض 85% على الجوال
- `.mobile:w-80` - العرض 80% على الجوال
- `.mobile:w-75` - العرض 75% على الجوال
- `.mobile:w-70` - العرض 70% على الجوال
- `.mobile:w-65` - العرض 65% على الجوال
- `.mobile:w-60` - العرض 60% على الجوال
- `.mobile:w-55` - العرض 55% على الجوال
- `.mobile:w-50` - العرض 50% على الجوال
- `.mobile:w-45` - العرض 45% على الجوال
- `.mobile:w-40` - العرض 40% على الجوال
- `.mobile:w-35` - العرض 35% على الجوال
- `.mobile:w-30` - العرض 30% على الجوال
- `.mobile:w-25` - العرض 25% على الجوال
- `.mobile:w-20` - العرض 20% على الجوال
- `.mobile:w-15` - العرض 15% على الجوال
- `.mobile:w-10` - العرض 10% على الجوال
- `.mobile:w-5` - العرض 5% على الجوال
- `.mobile:w-auto` - العرض التلقائي٪ على الهاتف المحمول

##### Width - Tablet (480px - 768px)

- `.hover:tablet:w-100` - العرض 100% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-95` - العرض 95% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-90` - العرض 90% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-85` - العرض 85% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-80` - العرض 80% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-75` - العرض 75% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-70` - العرض 70% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-65` - العرض 65% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-60` - العرض 60% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-55` - العرض 55% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-50` - العرض 50% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-45` - العرض 45% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-40` - العرض 40% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-35` - العرض 35% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-30` - العرض 30% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-25` - العرض 25% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-20` - العرض 20% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-15` - العرض 15% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-10` - العرض 10% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-5` - العرض 5% عند التمرير على الجهاز اللوحي
- `.hover:tablet:w-auto` - العرض التلقائي% عند التمرير على الجهاز اللوحي
- `.tablet:w-100` - العرض 100% على الجهاز اللوحي
- `.tablet:w-95` - العرض 95% على الجهاز اللوحي
- `.tablet:w-90` - العرض 90% على الجهاز اللوحي
- `.tablet:w-85` - العرض 85% على التابلت
- `.tablet:w-80` - العرض 80% على التابلت
- `.tablet:w-75` - العرض 75% على التابلت
- `.tablet:w-70` - العرض 70% على التابلت
- `.tablet:w-65` - العرض 65% على التابلت
- `.tablet:w-60` - العرض 60% على التابلت
- `.tablet:w-55` - العرض 55% على التابلت
- `.tablet:w-50` - العرض 50% على التابلت
- `.tablet:w-45` - العرض 45% على التابلت
- `.tablet:w-40` - العرض 40% على التابلت
- `.tablet:w-35` - العرض 35% على التابلت
- `.tablet:w-30` - العرض 30% على التابلت
- `.tablet:w-25` - العرض 25% على التابلت
- `.tablet:w-20` - العرض 20% على التابلت
- `.tablet:w-15` - العرض 15% على التابلت
- `.tablet:w-10` - العرض 10% على التابلت
- `.tablet:w-5` - العرض 5% على التابلت
- `.tablet:w-auto` - العرض التلقائي% على الجهاز اللوحي

##### Width - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:w-100` - العرض 100% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-95` - العرض 95% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-90` - العرض 90% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-85` - العرض 85% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-80` - العرض 80% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-75` - العرض 75% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-70` - العرض 70% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-65` - العرض 65% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-60` - العرض 60% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-55` - العرض 55% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-50` - العرض 50% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-45` - العرض 45% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-40` - العرض 40% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-35` - العرض 35% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-30` - العرض 30% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-25` - العرض 25% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-20` - العرض 20% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-15` - العرض 15% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-10` - العرض 10% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-5` - العرض 5% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:w-auto` - العرض التلقائي٪ عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:w-100` - العرض 100% على الكمبيوتر اللوحي
- `.tablet-pc:w-95` - العرض 95% على الكمبيوتر اللوحي
- `.tablet-pc:w-90` - العرض 90% على الكمبيوتر اللوحي
- `.tablet-pc:w-85` - العرض 85% على الكمبيوتر اللوحي
- `.tablet-pc:w-80` - العرض 80% على الكمبيوتر اللوحي
- `.tablet-pc:w-75` - العرض 75% على الكمبيوتر اللوحي
- `.tablet-pc:w-70` - العرض 70% على الكمبيوتر اللوحي
- `.tablet-pc:w-65` - العرض 65% على الكمبيوتر اللوحي
- `.tablet-pc:w-60` - العرض 60% على الكمبيوتر اللوحي
- `.tablet-pc:w-55` - العرض 55% على الكمبيوتر اللوحي
- `.tablet-pc:w-50` - العرض 50% على الكمبيوتر اللوحي
- `.tablet-pc:w-45` - العرض 45% على الكمبيوتر اللوحي
- `.tablet-pc:w-40` - العرض 40% على الكمبيوتر اللوحي
- `.tablet-pc:w-35` - العرض 35% على الكمبيوتر اللوحي
- `.tablet-pc:w-30` - العرض 30% على الكمبيوتر اللوحي
- `.tablet-pc:w-25` - العرض 25% على الكمبيوتر اللوحي
- `.tablet-pc:w-20` - العرض 20% على الكمبيوتر اللوحي
- `.tablet-pc:w-15` - العرض 15% على الكمبيوتر اللوحي
- `.tablet-pc:w-10` - العرض 10% على الكمبيوتر اللوحي
- `.tablet-pc:w-5` - العرض 5% على الكمبيوتر اللوحي
- `.tablet-pc:w-auto` - العرض التلقائي٪ على الكمبيوتر اللوحي

##### Width - Pc (992px - 1200px)

- `.hover:pc:w-100` - العرض 100% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-95` - العرض 95% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-90` - العرض 90% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-85` - العرض 85% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-80` - العرض 80% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-75` - العرض 75% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-70` - العرض 70% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-65` - العرض 65% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-60` - العرض 60% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-55` - العرض 55% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-50` - العرض 50% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-45` - العرض 45% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-40` - العرض 40% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-35` - العرض 35% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-30` - العرض 30% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-25` - العرض 25% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-20` - العرض 20% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-15` - العرض 15% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-10` - العرض 10% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-5` - العرض 5% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:w-auto` - العرض التلقائي٪ عند التمرير على جهاز الكمبيوتر
- `.pc:w-100` - العرض 100% على جهاز الكمبيوتر
- `.pc:w-95` - العرض 95% على جهاز الكمبيوتر
- `.pc:w-90` - العرض 90% على جهاز الكمبيوتر
- `.pc:w-85` - العرض 85% على جهاز الكمبيوتر
- `.pc:w-80` - العرض 80% على جهاز الكمبيوتر
- `.pc:w-75` - العرض 75% على جهاز الكمبيوتر
- `.pc:w-70` - العرض 70% على جهاز الكمبيوتر
- `.pc:w-65` - العرض 65% على جهاز الكمبيوتر
- `.pc:w-60` - العرض 60% على جهاز الكمبيوتر
- `.pc:w-55` - العرض 55% على جهاز الكمبيوتر
- `.pc:w-50` - العرض 50% على جهاز الكمبيوتر
- `.pc:w-45` - العرض 45% على جهاز الكمبيوتر
- `.pc:w-40` - العرض 40% على جهاز الكمبيوتر
- `.pc:w-35` - العرض 35% على جهاز الكمبيوتر
- `.pc:w-30` - العرض 30% على جهاز الكمبيوتر
- `.pc:w-25` - العرض 25% على جهاز الكمبيوتر
- `.pc:w-20` - العرض 20% على جهاز الكمبيوتر
- `.pc:w-15` - العرض 15% على جهاز الكمبيوتر
- `.pc:w-10` - العرض 10% على جهاز الكمبيوتر
- `.pc:w-5` - العرض 5% على جهاز الكمبيوتر
- `.pc:w-auto` - العرض التلقائي٪ على جهاز الكمبيوتر

##### Width - Tv (> 1200px)

- `.hover:tv:w-100` - العرض 100% عند التمرير على التلفاز
- `.hover:tv:w-95` - العرض 95% عند التحويم على التلفاز
- `.hover:tv:w-90` - العرض 90% عند التمرير على التلفاز
- `.hover:tv:w-85` - العرض 85% عند التحويم على التلفاز
- `.hover:tv:w-80` - العرض 80% عند التحويم على التلفاز
- `.hover:tv:w-75` - العرض 75% عند التحويم على التلفاز
- `.hover:tv:w-70` - العرض 70% عند التحويم على التلفاز
- `.hover:tv:w-65` - العرض 65% عند التحويم على التلفاز
- `.hover:tv:w-60` - العرض 60% عند التحويم على التلفاز
- `.hover:tv:w-55` - العرض 55% عند التحويم على التلفاز
- `.hover:tv:w-50` - العرض 50% عند التحويم على التلفاز
- `.hover:tv:w-45` - العرض 45% عند التحويم على التلفاز
- `.hover:tv:w-40` - العرض 40% عند التحويم على التلفاز
- `.hover:tv:w-35` - العرض 35% عند التحويم على التلفاز
- `.hover:tv:w-30` - العرض 30% عند التحويم على التلفاز
- `.hover:tv:w-25` - العرض 25% عند التحويم على التلفاز
- `.hover:tv:w-20` - العرض 20% عند التمرير على التلفاز
- `.hover:tv:w-15` - العرض 15% عند التمرير على التلفاز
- `.hover:tv:w-10` - العرض 10% عند التمرير على التلفاز
- `.hover:tv:w-5` - العرض 5% عند التمرير على التلفاز
- `.hover:tv:w-auto` - العرض التلقائي٪ عند التمرير على شاشة التلفزيون
- `.tv:w-100` - العرض 100% على التلفاز
- `.tv:w-95` - عرض 95% على شاشة التلفزيون
- `.tv:w-90` - عرض 90% على شاشة التلفزيون
- `.tv:w-85` - العرض 85% على التلفاز
- `.tv:w-80` - عرض 80% على شاشة التلفزيون
- `.tv:w-75` - العرض 75% على التلفاز
- `.tv:w-70` - عرض 70% على شاشة التلفزيون
- `.tv:w-65` - العرض 65% على التلفاز
- `.tv:w-60` - عرض 60% على شاشة التلفزيون
- `.tv:w-55` - عرض 55% على شاشة التلفزيون
- `.tv:w-50` - عرض 50% على شاشة التلفزيون
- `.tv:w-45` - العرض 45% على التلفاز
- `.tv:w-40` - عرض 40% على شاشة التلفزيون
- `.tv:w-35` - عرض 35% على التلفاز
- `.tv:w-30` - عرض 30% على شاشة التلفزيون
- `.tv:w-25` - عرض 25% على التلفاز
- `.tv:w-20` - عرض 20% على شاشة التلفزيون
- `.tv:w-15` - عرض 15% على التلفاز
- `.tv:w-10` - العرض 10% على التلفاز
- `.tv:w-5` - العرض 5% على التلفاز
- `.tv:w-auto` - العرض التلقائي٪ على شاشة التلفزيون

##### Width - Tablet Max (< 768px)

- `.hover:tablet-max:w-100` - العرض 100% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-95` - العرض 95% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-90` - العرض 90% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-85` - العرض 85% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-80` - العرض 80% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-75` - العرض 75% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-70` - العرض 70% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-65` - العرض 65% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-60` - العرض 60% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-55` - العرض 55% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-50` - العرض 50% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-45` - العرض 45% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-40` - العرض 40% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-35` - العرض 35% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-30` - العرض 30% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-25` - العرض 25% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-20` - العرض 20% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-15` - العرض 15% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-10` - العرض 10% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:w-5` - العرض 5% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:w-auto` - العرض التلقائي% عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-100` - العرض 100% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-95` - العرض 95% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-90` - العرض 90% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-85` - العرض 85% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-80` - العرض 80% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-75` - العرض 75% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-70` - العرض 70% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-65` - العرض 65% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-60` - العرض 60% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-55` - العرض 55% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-50` - العرض 50% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-45` - العرض 45% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-40` - العرض 40% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-35` - العرض 35% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-30` - العرض 30% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-25` - العرض 25% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-20` - العرض 20% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-15` - العرض 15% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-10` - العرض 10% على الجهاز اللوحي بحد أقصى
- `.tablet-max:w-5` - العرض 5% على الجهاز اللوحي كحد أقصى
- `.tablet-max:w-auto` - العرض التلقائي% على الجهاز اللوحي بحد أقصى

##### Width - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:w-100` - العرض 100% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-95` - العرض 95% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-90` - العرض 90% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-85` - العرض 85% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-80` - العرض 80% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-75` - العرض 75% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-70` - العرض 70% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-65` - العرض 65% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-60` - العرض 60% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-55` - العرض 55% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-50` - العرض 50% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-45` - العرض 45% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-40` - العرض 40% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-35` - العرض 35% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-30` - العرض 30% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-25` - العرض 25% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-20` - العرض 20% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-15` - العرض 15% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-10` - العرض 10% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-5` - العرض 5% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:w-auto` - العرض التلقائي٪ عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-100` - العرض 100% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-95` - العرض 95% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:w-90` - العرض 90% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-85` - العرض 85% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-80` - العرض 80% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-75` - العرض 75% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-70` - العرض 70% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-65` - العرض 65% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-60` - العرض 60% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-55` - العرض 55% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-50` - العرض 50% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-45` - العرض 45% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-40` - العرض 40% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-35` - العرض 35% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-30` - العرض 30% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-25` - العرض 25% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-20` - العرض 20% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-15` - العرض 15% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-10` - العرض 10% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-5` - العرض 5% على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:w-auto` - العرض التلقائي٪ على الكمبيوتر اللوحي كحد أقصى

##### Width - Pc Max (< 1200px)

- `.hover:pc-max:w-100` - العرض 100% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-95` - العرض 95% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-90` - العرض 90% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-85` - العرض 85% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-80` - العرض 80% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-75` - العرض 75% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-70` - العرض 70% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-65` - العرض 65% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-60` - العرض 60% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-55` - العرض 55% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-50` - العرض 50% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-45` - العرض 45% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-40` - العرض 40% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-35` - العرض 35% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-30` - العرض 30% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-25` - العرض 25% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-20` - العرض 20% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-15` - العرض 15% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-10` - العرض 10% عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.hover:pc-max:w-5` - العرض 5% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:w-auto` - العرض التلقائي٪ عند التمرير على جهاز الكمبيوتر بحد أقصى
- `.pc-max:w-100` - العرض 100% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-95` - العرض 95% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-90` - العرض 90% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-85` - العرض 85% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-80` - العرض 80% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-75` - العرض 75% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-70` - العرض 70% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-65` - العرض 65% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-60` - العرض 60% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-55` - العرض 55% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-50` - العرض 50% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-45` - العرض 45% على الكمبيوتر كحد أقصى
- `.pc-max:w-40` - العرض 40% على الكمبيوتر كحد أقصى
- `.pc-max:w-35` - العرض 35% على الكمبيوتر كحد أقصى
- `.pc-max:w-30` - العرض 30% على الكمبيوتر كحد أقصى
- `.pc-max:w-25` - العرض 25% على الكمبيوتر كحد أقصى
- `.pc-max:w-20` - العرض 20% على الكمبيوتر كحد أقصى
- `.pc-max:w-15` - العرض 15% على الكمبيوتر كحد أقصى
- `.pc-max:w-10` - العرض 10% على الكمبيوتر كحد أقصى
- `.pc-max:w-5` - العرض 5% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:w-auto` - العرض التلقائي٪ على جهاز الكمبيوتر كحد أقصى

#### Width vh

- `.hover:w-vh-100` - العرض vh 100% عند التمرير
- `.hover:w-vh-75` - العرض vh 75% عند التحويم
- `.hover:w-vh-50` - العرض vh 50% عند التحويم
- `.hover:w-vh-25` - العرض vh 25% عند التحويم
- `.w-vh-100` - العرض vh 100%
- `.w-vh-75` - عرض vh 75%
- `.w-vh-50` - العرض vh 50%
- `.w-vh-25` - العرض vh 25%

#### Width vw

- `.hover:w-vw-100` - العرض فولكس فاجن 100% عند التحويم
- `.hover:w-vw-75` - العرض فولكس فاجن 75% عند التحويم
- `.hover:w-vw-50` - العرض فولكس فاجن 50% عند التحويم
- `.hover:w-vw-25` - العرض فولكس فاجن 25% عند التحويم
- `.w-vw-100` - عرض فولكس فاجن 100%
- `.w-vw-75` - عرض فولكس فاجن 75%
- `.w-vw-50` - عرض فولكس فاجن 50%
- `.w-vw-25` - عرض فولكس فاجن 25%

### Height

- `.h-100` - الارتفاع 100%
- `.h-95` - الارتفاع 95%
- `.h-90` - الارتفاع 90%
- `.h-85` - الارتفاع 85%
- `.h-80` - الارتفاع 80%
- `.h-75` - الارتفاع 75%
- `.h-70` - الارتفاع 70%
- `.h-65` - الارتفاع 65%
- `.h-60` - الارتفاع 60%
- `.h-55` - الارتفاع 55%
- `.h-50` - الارتفاع 50%
- `.h-45` - الارتفاع 45%
- `.h-40` - الارتفاع 40%
- `.h-35` - الارتفاع 35%
- `.h-30` - الارتفاع 30%
- `.h-25` - الارتفاع 25%
- `.h-20` - الارتفاع 20%
- `.h-15` - الارتفاع 15%
- `.h-10` - الارتفاع 10%
- `.h-5` - الارتفاع 5%
- `.h-auto` - الارتفاع التلقائي٪
- `.hover:h-100` - الارتفاع 100% عند التحويم
- `.hover:h-95` - الارتفاع 95% عند التحويم
- `.hover:h-90` - الارتفاع 90% عند التحويم
- `.hover:h-85` - الارتفاع 85% عند التحويم
- `.hover:h-80` - الارتفاع 80% عند التحويم
- `.hover:h-75` - الارتفاع 75% عند التحويم
- `.hover:h-70` - الارتفاع 70% عند التحويم
- `.hover:h-65` - الارتفاع 65% عند التحويم
- `.hover:h-60` - الارتفاع 60% عند التحويم
- `.hover:h-55` - الارتفاع 55% عند التحويم
- `.hover:h-50` - الارتفاع 50% عند التحويم
- `.hover:h-45` - الارتفاع 45% عند التحويم
- `.hover:h-40` - الارتفاع 40% عند التحويم
- `.hover:h-35` - الارتفاع 35% عند التحويم
- `.hover:h-30` - الارتفاع 30% عند التحويم
- `.hover:h-25` - الارتفاع 25% عند التحويم
- `.hover:h-20` - الارتفاع 20% عند التحويم
- `.hover:h-15` - الارتفاع 15% عند التحويم
- `.hover:h-10` - الارتفاع 10% عند التحويم
- `.hover:h-5` - الارتفاع 5% عند التحويم
- `.hover:h-auto` - الارتفاع التلقائي٪ عند التمرير

##### Height - Mobile (< 480px)

- `.hover:mobile:h-100` - الارتفاع 100% عند التمرير على الهاتف المحمول
- `.hover:mobile:h-95` - الارتفاع 95% عند المرور على الجوال
- `.hover:mobile:h-90` - الارتفاع 90% عند المرور على الجوال
- `.hover:mobile:h-85` - الارتفاع 85% عند المرور على الجوال
- `.hover:mobile:h-80` - الارتفاع 80% عند المرور على الجوال
- `.hover:mobile:h-75` - الارتفاع 75% عند المرور على الجوال
- `.hover:mobile:h-70` - الارتفاع 70% عند المرور على الجوال
- `.hover:mobile:h-65` - الارتفاع 65% عند المرور على الجوال
- `.hover:mobile:h-60` - الارتفاع 60% عند المرور على الجوال
- `.hover:mobile:h-55` - الارتفاع 55% عند المرور على الجوال
- `.hover:mobile:h-50` - الارتفاع 50% عند المرور على الجوال
- `.hover:mobile:h-45` - الارتفاع 45% عند المرور على الجوال
- `.hover:mobile:h-40` - الارتفاع 40% عند المرور على الجوال
- `.hover:mobile:h-35` - الارتفاع 35% عند المرور على الجوال
- `.hover:mobile:h-30` - الارتفاع 30% عند المرور على الجوال
- `.hover:mobile:h-25` - الارتفاع 25% عند المرور على الجوال
- `.hover:mobile:h-20` - الارتفاع 20% عند المرور على الجوال
- `.hover:mobile:h-15` - الارتفاع 15% عند المرور على الجوال
- `.hover:mobile:h-10` - الارتفاع 10% عند المرور على الجوال
- `.hover:mobile:h-5` - الارتفاع 5% عند المرور على الجوال
- `.hover:mobile:h-auto` - الارتفاع التلقائي٪ عند التمرير على الهاتف المحمول
- `.mobile:h-100` - الارتفاع 100% على الجوال
- `.mobile:h-95` - الارتفاع 95% على الجوال
- `.mobile:h-90` - الارتفاع 90% على الجوال
- `.mobile:h-85` - الارتفاع 85% على الجوال
- `.mobile:h-80` - الارتفاع 80% على الجوال
- `.mobile:h-75` - الارتفاع 75% على الجوال
- `.mobile:h-70` - الارتفاع 70% على الجوال
- `.mobile:h-65` - الارتفاع 65% على الجوال
- `.mobile:h-60` - الارتفاع 60% على الجوال
- `.mobile:h-55` - الارتفاع 55% على الجوال
- `.mobile:h-50` - الارتفاع 50% على الجوال
- `.mobile:h-45` - الارتفاع 45% على الجوال
- `.mobile:h-40` - الارتفاع 40% على الجوال
- `.mobile:h-35` - الارتفاع 35% على الجوال
- `.mobile:h-30` - الارتفاع 30% على الجوال
- `.mobile:h-25` - الارتفاع 25% على الجوال
- `.mobile:h-20` - الارتفاع 20% على الجوال
- `.mobile:h-15` - الارتفاع 15% على الجوال
- `.mobile:h-10` - الارتفاع 10% على الجوال
- `.mobile:h-5` - الارتفاع 5% على الجوال
- `.mobile:h-auto` - الارتفاع التلقائي٪ على الهاتف المحمول

##### Height - Tablet (480px - 768px)

- `.hover:tablet:h-100` - الارتفاع 100% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-95` - الارتفاع 95% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-90` - الارتفاع 90% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-85` - الارتفاع 85% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-80` - الارتفاع 80% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-75` - الارتفاع 75% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-70` - الارتفاع 70% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-65` - الارتفاع 65% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-60` - الارتفاع 60% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-55` - الارتفاع 55% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-50` - الارتفاع 50% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-45` - الارتفاع 45% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-40` - الارتفاع 40% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-35` - الارتفاع 35% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-30` - الارتفاع 30% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-25` - الارتفاع 25% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-20` - الارتفاع 20% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-15` - الارتفاع 15% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-10` - الارتفاع 10% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-5` - الارتفاع 5% عند التمرير على الجهاز اللوحي
- `.hover:tablet:h-auto` - الارتفاع التلقائي٪ عند التمرير على الجهاز اللوحي
- `.tablet:h-100` - الارتفاع 100% على الجهاز اللوحي
- `.tablet:h-95` - الارتفاع 95% على التابلت
- `.tablet:h-90` - الارتفاع 90% على التابلت
- `.tablet:h-85` - الارتفاع 85% على التابلت
- `.tablet:h-80` - الارتفاع 80% على التابلت
- `.tablet:h-75` - الارتفاع 75% على التابلت
- `.tablet:h-70` - الارتفاع 70% على التابلت
- `.tablet:h-65` - الارتفاع 65% على التابلت
- `.tablet:h-60` - الارتفاع 60% على التابلت
- `.tablet:h-55` - الارتفاع 55% على التابلت
- `.tablet:h-50` - الارتفاع 50% على التابلت
- `.tablet:h-45` - الارتفاع 45% على التابلت
- `.tablet:h-40` - الارتفاع 40% على التابلت
- `.tablet:h-35` - الارتفاع 35% على التابلت
- `.tablet:h-30` - الارتفاع 30% على التابلت
- `.tablet:h-25` - الارتفاع 25% على التابلت
- `.tablet:h-20` - الارتفاع 20% على التابلت
- `.tablet:h-15` - الارتفاع 15% على التابلت
- `.tablet:h-10` - الارتفاع 10% على التابلت
- `.tablet:h-5` - الارتفاع 5% على التابلت
- `.tablet:h-auto` - الارتفاع التلقائي% على الجهاز اللوحي

##### Height - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:h-100` - الارتفاع 100% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-95` - الارتفاع 95% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-90` - الارتفاع 90% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-85` - الارتفاع 85% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-75` - الارتفاع 75% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-70` - الارتفاع 70% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-65` - الارتفاع 65% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-60` - الارتفاع 60% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-55` - الارتفاع 55% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-50` - الارتفاع 50% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-45` - الارتفاع 45% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-40` - الارتفاع 40% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-35` - الارتفاع 35% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-30` - الارتفاع 30% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-25` - الارتفاع 25% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-20` - الارتفاع 20% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-15` - الارتفاع 15% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-10` - الارتفاع 10% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-5` - الارتفاع 5% عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:h-auto` - الارتفاع التلقائي٪ عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:h-100` - الارتفاع 100% على الكمبيوتر اللوحي
- `.tablet-pc:h-95` - الارتفاع 95% على الكمبيوتر اللوحي
- `.tablet-pc:h-90` - الارتفاع 90% على الكمبيوتر اللوحي
- `.tablet-pc:h-85` - الارتفاع 85% على الكمبيوتر اللوحي
- `.tablet-pc:h-80` - الارتفاع 80% على الكمبيوتر اللوحي
- `.tablet-pc:h-75` - الارتفاع 75% على الكمبيوتر اللوحي
- `.tablet-pc:h-70` - الارتفاع 70% على الكمبيوتر اللوحي
- `.tablet-pc:h-65` - الارتفاع 65% على الكمبيوتر اللوحي
- `.tablet-pc:h-60` - الارتفاع 60% على الكمبيوتر اللوحي
- `.tablet-pc:h-55` - الارتفاع 55% على الكمبيوتر اللوحي
- `.tablet-pc:h-50` - الارتفاع 50% على الكمبيوتر اللوحي
- `.tablet-pc:h-45` - الارتفاع 45% على الكمبيوتر اللوحي
- `.tablet-pc:h-40` - الارتفاع 40% على الكمبيوتر اللوحي
- `.tablet-pc:h-35` - الارتفاع 35% على الكمبيوتر اللوحي
- `.tablet-pc:h-30` - الارتفاع 30% على الكمبيوتر اللوحي
- `.tablet-pc:h-25` - الارتفاع 25% على الكمبيوتر اللوحي
- `.tablet-pc:h-20` - الارتفاع 20% على الكمبيوتر اللوحي
- `.tablet-pc:h-15` - الارتفاع 15% على الكمبيوتر اللوحي
- `.tablet-pc:h-10` - الارتفاع 10% على الكمبيوتر اللوحي
- `.tablet-pc:h-5` - الارتفاع 5% على الكمبيوتر اللوحي
- `.tablet-pc:h-auto` - الارتفاع التلقائي٪ على الكمبيوتر اللوحي

##### Height - Pc (992px - 1200px)

- `.hover:pc:h-100` - الارتفاع 100% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:h-95` - الارتفاع 95% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-90` - الارتفاع 90% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-85` - الارتفاع 85% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-80` - الارتفاع 80% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-75` - الارتفاع 75% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-70` - الارتفاع 70% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-65` - الارتفاع 65% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-60` - الارتفاع 60% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-55` - الارتفاع 55% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-50` - الارتفاع 50% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-45` - الارتفاع 45% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-40` - الارتفاع 40% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-35` - الارتفاع 35% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-30` - الارتفاع 30% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-25` - الارتفاع 25% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-20` - الارتفاع 20% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-15` - الارتفاع 15% عند التحويم على جهاز الكمبيوتر
- `.hover:pc:h-10` - الارتفاع 10% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:h-5` - الارتفاع 5% عند التمرير على جهاز الكمبيوتر
- `.hover:pc:h-auto` - الارتفاع التلقائي٪ عند التمرير على جهاز الكمبيوتر
- `.pc:h-100` - الارتفاع 100% على جهاز الكمبيوتر
- `.pc:h-95` - الارتفاع 95% على جهاز الكمبيوتر
- `.pc:h-90` - الارتفاع 90% على جهاز الكمبيوتر
- `.pc:h-85` - الارتفاع 85% على جهاز الكمبيوتر
- `.pc:h-80` - الارتفاع 80% على جهاز الكمبيوتر
- `.pc:h-75` - الارتفاع 75% على جهاز الكمبيوتر
- `.pc:h-70` - الارتفاع 70% على جهاز الكمبيوتر
- `.pc:h-65` - الارتفاع 65% على جهاز الكمبيوتر
- `.pc:h-60` - الارتفاع 60% على جهاز الكمبيوتر
- `.pc:h-55` - الارتفاع 55% على جهاز الكمبيوتر
- `.pc:h-50` - الارتفاع 50% على جهاز الكمبيوتر
- `.pc:h-45` - الارتفاع 45% على جهاز الكمبيوتر
- `.pc:h-40` - الارتفاع 40% على جهاز الكمبيوتر
- `.pc:h-35` - الارتفاع 35% على جهاز الكمبيوتر
- `.pc:h-30` - الارتفاع 30% على جهاز الكمبيوتر
- `.pc:h-25` - الارتفاع 25% على جهاز الكمبيوتر
- `.pc:h-20` - الارتفاع 20% على جهاز الكمبيوتر
- `.pc:h-15` - الارتفاع 15% على جهاز الكمبيوتر
- `.pc:h-10` - الارتفاع 10% على جهاز الكمبيوتر
- `.pc:h-5` - الارتفاع 5% على جهاز الكمبيوتر
- `.pc:h-auto` - الارتفاع التلقائي٪ على جهاز الكمبيوتر

##### Height - Tv (> 1200px)

- `.hover:tv:h-100` - الارتفاع 100% عند التحويم على التلفاز
- `.hover:tv:h-95` - الارتفاع 95% عند التحويم على التلفاز
- `.hover:tv:h-90` - الارتفاع 90% عند التحويم على التلفاز
- `.hover:tv:h-85` - الارتفاع 85% عند التحويم على التلفاز
- `.hover:tv:h-80` - الارتفاع 80% عند التحويم على التلفاز
- `.hover:tv:h-75` - الارتفاع 75% عند التحويم على التلفاز
- `.hover:tv:h-70` - الارتفاع 70% عند التحويم على التلفاز
- `.hover:tv:h-65` - الارتفاع 65% عند التحويم على التلفاز
- `.hover:tv:h-60` - الارتفاع 60% عند التحويم على التلفاز
- `.hover:tv:h-55` - الارتفاع 55% عند التحويم على التلفاز
- `.hover:tv:h-50` - الارتفاع 50% عند التحويم على التلفاز
- `.hover:tv:h-45` - الارتفاع 45% عند التحويم على التلفاز
- `.hover:tv:h-40` - الارتفاع 40% عند التحويم على التلفاز
- `.hover:tv:h-35` - الارتفاع 35% عند التحويم على التلفاز
- `.hover:tv:h-30` - الارتفاع 30% عند التحويم على التلفاز
- `.hover:tv:h-25` - الارتفاع 25% عند التحويم على التلفاز
- `.hover:tv:h-20` - الارتفاع 20% عند التحويم على التلفاز
- `.hover:tv:h-15` - الارتفاع 15% عند التحويم على التلفاز
- `.hover:tv:h-10` - الارتفاع 10% عند التحويم على التلفاز
- `.hover:tv:h-5` - الارتفاع 5% عند التحويم على التلفاز
- `.hover:tv:h-auto` - الارتفاع التلقائي٪ عند التمرير على شاشة التلفزيون
- `.tv:h-100` - الارتفاع 100% على شاشة التلفزيون
- `.tv:h-95` - الطول 95% على التلفاز
- `.tv:h-90` - الارتفاع 90% على شاشة التلفزيون
- `.tv:h-85` - الارتفاع 85% على التلفاز
- `.tv:h-80` - الارتفاع 80% على التلفاز
- `.tv:h-75` - الارتفاع 75% على التلفاز
- `.tv:h-70` - الارتفاع 70% على التلفاز
- `.tv:h-65` - الارتفاع 65% على التلفاز
- `.tv:h-60` - الارتفاع 60% على التلفاز
- `.tv:h-55` - الطول 55% على التلفاز
- `.tv:h-50` - الارتفاع 50% على شاشة التلفزيون
- `.tv:h-45` - الارتفاع 45% على التلفاز
- `.tv:h-40` - الارتفاع 40% على التلفاز
- `.tv:h-35` - الارتفاع 35% على التلفاز
- `.tv:h-30` - الارتفاع 30% على التلفاز
- `.tv:h-25` - الارتفاع 25% على التلفاز
- `.tv:h-20` - الارتفاع 20% على التلفاز
- `.tv:h-15` - الارتفاع 15% على التلفاز
- `.tv:h-10` - الارتفاع 10% على التلفاز
- `.tv:h-5` - الارتفاع 5% على التلفاز
- `.tv:h-auto` - الارتفاع التلقائي٪ على شاشة التلفزيون

##### Height - Tablet Max (< 768px)

- `.hover:tablet-max:h-100` - الارتفاع 100% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-95` - الارتفاع 95% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-90` - الارتفاع 90% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-85` - الارتفاع 85% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-80` - الارتفاع 80% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-75` - الارتفاع 75% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-70` - الارتفاع 70% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-65` - الارتفاع 65% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-60` - الارتفاع 60% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-55` - الارتفاع 55% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-50` - الارتفاع 50% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-45` - الارتفاع 45% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-40` - الارتفاع 40% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-35` - الارتفاع 35% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-30` - الارتفاع 30% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-25` - الارتفاع 25% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-20` - الارتفاع 20% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-15` - الارتفاع 15% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:h-10` - الارتفاع 10% عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:h-5` - الارتفاع 5% عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:h-auto` - الارتفاع التلقائي٪ عند التمرير على الجهاز اللوحي كحد أقصى
- `.tablet-max:h-100` - الارتفاع 100% على الجهاز اللوحي كحد أقصى
- `.tablet-max:h-95` - الارتفاع 95% على الجهاز اللوحي كحد أقصى
- `.tablet-max:h-90` - الارتفاع 90% على الجهاز اللوحي كحد أقصى
- `.tablet-max:h-85` - الارتفاع 85% على التابلت كحد أقصى
- `.tablet-max:h-80` - الارتفاع 80% على التابلت كحد أقصى
- `.tablet-max:h-75` - الارتفاع 75% على التابلت كحد أقصى
- `.tablet-max:h-70` - الارتفاع 70% على التابلت كحد أقصى
- `.tablet-max:h-65` - الارتفاع 65% على التابلت كحد أقصى
- `.tablet-max:h-60` - الارتفاع 60% على التابلت كحد أقصى
- `.tablet-max:h-55` - الارتفاع 55% على التابلت كحد أقصى
- `.tablet-max:h-50` - الارتفاع 50% على التابلت كحد أقصى
- `.tablet-max:h-45` - الارتفاع 45% على التابلت كحد أقصى
- `.tablet-max:h-40` - الارتفاع 40% على التابلت كحد أقصى
- `.tablet-max:h-35` - الارتفاع 35% على التابلت كحد أقصى
- `.tablet-max:h-30` - الارتفاع 30% على التابلت كحد أقصى
- `.tablet-max:h-25` - الارتفاع 25% على التابلت كحد أقصى
- `.tablet-max:h-20` - الارتفاع 20% على التابلت كحد أقصى
- `.tablet-max:h-15` - الارتفاع 15% على التابلت كحد أقصى
- `.tablet-max:h-10` - الارتفاع 10% على التابلت كحد أقصى
- `.tablet-max:h-5` - الارتفاع 5% على التابلت كحد أقصى
- `.tablet-max:h-auto` - الارتفاع التلقائي٪ على الجهاز اللوحي كحد أقصى

##### Height - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:h-100` - الارتفاع 100% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-95` - الارتفاع 95% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-90` - الارتفاع 90% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-85` - الارتفاع 85% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-80` - الارتفاع 80% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-75` - الارتفاع 75% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-70` - الارتفاع 70% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-65` - الارتفاع 65% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-60` - الارتفاع 60% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-55` - الارتفاع 55% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-50` - الارتفاع 50% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-45` - الارتفاع 45% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-40` - الارتفاع 40% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-35` - الارتفاع 35% عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:h-30` - الارتفاع 30% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-25` - الارتفاع 25% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-20` - الارتفاع 20% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-15` - الارتفاع 15% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-10` - الارتفاع 10% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-5` - الارتفاع 5% عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.hover:tablet-pc-max:h-auto` - الارتفاع التلقائي٪ عند التمرير على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-100` - الارتفاع 100% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-95` - الارتفاع 95% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-90` - الارتفاع 90% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-85` - الارتفاع 85% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-80` - الارتفاع 80% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-75` - الارتفاع 75% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-70` - الارتفاع 70% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-65` - الارتفاع 65% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-60` - الارتفاع 60% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-55` - الارتفاع 55% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-50` - الارتفاع 50% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-45` - الارتفاع 45% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-40` - الارتفاع 40% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-35` - الارتفاع 35% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-30` - الارتفاع 30% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-25` - الارتفاع 25% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-20` - الارتفاع 20% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-15` - الارتفاع 15% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-10` - الارتفاع 10% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-5` - الارتفاع 5% على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:h-auto` - الارتفاع التلقائي٪ على الكمبيوتر اللوحي كحد أقصى

##### Height - Pc Max (< 1200px)

- `.hover:pc-max:h-100` - الارتفاع 100% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-95` - الارتفاع 95% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-90` - الارتفاع 90% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-85` - الارتفاع 85% عند التحويم على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-80` - الارتفاع 80% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-75` - الارتفاع 75% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-70` - الارتفاع 70% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-65` - الارتفاع 65% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-60` - الارتفاع 60% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-55` - الارتفاع 55% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-50` - الارتفاع 50% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-45` - الارتفاع 45% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-40` - الارتفاع 40% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-35` - الارتفاع 35% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-30` - الارتفاع 30% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-25` - الارتفاع 25% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-20` - الارتفاع 20% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-15` - الارتفاع 15% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-10` - الارتفاع 10% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-5` - الارتفاع 5% عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:h-auto` - الارتفاع التلقائي٪ عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:h-100` - الارتفاع 100% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:h-95` - الارتفاع 95% على الكمبيوتر كحد أقصى
- `.pc-max:h-90` - الارتفاع 90% على جهاز الكمبيوتر كحد أقصى
- `.pc-max:h-85` - الارتفاع 85% على الكمبيوتر كحد أقصى
- `.pc-max:h-80` - الارتفاع 80% على الكمبيوتر كحد أقصى
- `.pc-max:h-75` - الارتفاع 75% على الكمبيوتر كحد أقصى
- `.pc-max:h-70` - الارتفاع 70% على الكمبيوتر كحد أقصى
- `.pc-max:h-65` - الارتفاع 65% على الكمبيوتر كحد أقصى
- `.pc-max:h-60` - الارتفاع 60% على الكمبيوتر كحد أقصى
- `.pc-max:h-55` - الارتفاع 55% على الكمبيوتر كحد أقصى
- `.pc-max:h-50` - الارتفاع 50% على الكمبيوتر كحد أقصى
- `.pc-max:h-45` - الارتفاع 45% على الكمبيوتر كحد أقصى
- `.pc-max:h-40` - الارتفاع 40% على الكمبيوتر كحد أقصى
- `.pc-max:h-35` - الارتفاع 35% على الكمبيوتر كحد أقصى
- `.pc-max:h-30` - الارتفاع 30% على الكمبيوتر كحد أقصى
- `.pc-max:h-25` - الارتفاع 25% على الكمبيوتر كحد أقصى
- `.pc-max:h-20` - الارتفاع 20% على الكمبيوتر كحد أقصى
- `.pc-max:h-15` - الارتفاع 15% على الكمبيوتر كحد أقصى
- `.pc-max:h-10` - الارتفاع 10% على الكمبيوتر كحد أقصى
- `.pc-max:h-5` - الارتفاع 5% على الكمبيوتر كحد أقصى
- `.pc-max:h-auto` - الارتفاع التلقائي٪ على جهاز الكمبيوتر كحد أقصى

#### Height vh

- `.h-vh-100` - الارتفاع 100%
- `.h-vh-75` - الارتفاع 75%
- `.h-vh-50` - الارتفاع 50%
- `.h-vh-25` - الارتفاع 25%
- `.hover:h-vh-100` - الارتفاع vh 100% عند التحويم
- `.hover:h-vh-75` - الارتفاع vh 75% عند التحويم
- `.hover:h-vh-50` - الارتفاع vh 50% عند التحويم
- `.hover:h-vh-25` - الارتفاع vh 25% عند التحويم

#### Height vw

- `.h-vw-100` - الارتفاع فولكس فاجن 100%
- `.h-vw-75` - الارتفاع فولكس فاجن 75%
- `.h-vw-50` - الارتفاع فولكس فاجن 50%
- `.h-vw-25` - الارتفاع فولكس فاجن 25%
- `.hover:h-vw-100` - الارتفاع فولكس فاجن 100% عند التحويم
- `.hover:h-vw-75` - الارتفاع فولكس فاجن 75% عند التحويم
- `.hover:h-vw-50` - الارتفاع فولكس فاجن 50% عند التحويم
- `.hover:h-vw-25` - الارتفاع فولكس فاجن 25% عند التحويم

## Positioning

### Static

- `.hover:static` - ثابت عند التمرير
- `.static` - ثابت

### Relative

- `.hover:relative` - نسبي عند التمرير
- `.relative` - نسبي

### Absolute

- `.absolute` - مطلق
- `.hover:absolute` - مطلق عند التمرير

### Fixed

- `.fixed` - مُثَبَّت
- `.hover:fixed` - ثابت على التحويم

### Sticky

- `.hover:sticky` - لزجة على التحويم
- `.sticky` - لزجة

### Top

- `.hover:top-100` - أعلى 100ريم عند التحويم
- `.hover:top-75` - أعلى 75ريم عند التحويم
- `.hover:top-50` - أعلى 50ريمًا عند التحويم
- `.hover:top-25` - أعلى 25ريمًا عند التحويم
- `.hover:top-5` - أعلى 5ريم عند التحويم
- `.hover:top-4.5` - أعلى 0rem عند التمرير
- `.hover:top-4` - أعلى 4ريم عند التحويم
- `.hover:top-3.5` - أعلى 0rem عند التمرير
- `.hover:top-3` - أعلى 3ريم عند التمرير
- `.hover:top-2.5` - أعلى 0rem عند التمرير
- `.hover:top-2` - أعلى 2rem عند التمرير
- `.hover:top-1.9` - أعلى 0rem عند التمرير
- `.hover:top-1.8` - أعلى 0rem عند التمرير
- `.hover:top-1.7` - أعلى 0rem عند التمرير
- `.hover:top-1.6` - أعلى 0rem عند التمرير
- `.hover:top-1.5` - أعلى 0rem عند التمرير
- `.hover:top-1.4` - أعلى 0rem عند التمرير
- `.hover:top-1.3` - أعلى 0rem عند التمرير
- `.hover:top-1.2` - أعلى 0rem عند التمرير
- `.hover:top-1.1` - أعلى 0rem عند التمرير
- `.hover:top-1` - أعلى 1rem عند التمرير
- `.hover:top-0.9` - أعلى 0rem عند التمرير
- `.hover:top-0.8` - أعلى 0rem عند التمرير
- `.hover:top-0.7` - أعلى 0rem عند التمرير
- `.hover:top-0.6` - أعلى 0rem عند التمرير
- `.hover:top-0.5` - أعلى 0rem عند التمرير
- `.hover:top-0.4` - أعلى 0rem عند التمرير
- `.hover:top-0.3` - أعلى 0rem عند التمرير
- `.hover:top-0.2` - أعلى 0.2rem عند التمرير
- `.hover:top-0.1` - أعلى 0.1rem عند التمرير
- `.hover:top-0` - أعلى 0rem عند التمرير
- `.top-100` - أعلى 100ريم
- `.top-75` - أعلى 75ريم
- `.top-50` - أعلى 50ريم
- `.top-25` - أعلى 25ريم
- `.top-5` - أعلى 5ريم
- `.top-4.5` - أعلى 0ريم
- `.top-4` - أعلى 4ريم
- `.top-3.5` - أعلى 0ريم
- `.top-3` - أعلى 3ريم
- `.top-2.5` - أعلى 0ريم
- `.top-2` - أعلى 2ريم
- `.top-1.9` - أعلى 0ريم
- `.top-1.8` - أعلى 0ريم
- `.top-1.7` - أعلى 0ريم
- `.top-1.6` - أعلى 0ريم
- `.top-1.5` - أعلى 0ريم
- `.top-1.4` - أعلى 0ريم
- `.top-1.3` - أعلى 0ريم
- `.top-1.2` - أعلى 0ريم
- `.top-1.1` - أعلى 0ريم
- `.top-1` - أعلى 1ريم
- `.top-0.9` - أعلى 0ريم
- `.top-0.8` - أعلى 0ريم
- `.top-0.7` - أعلى 0ريم
- `.top-0.6` - أعلى 0ريم
- `.top-0.5` - أعلى 0ريم
- `.top-0.4` - أعلى 0ريم
- `.top-0.3` - أعلى 0ريم
- `.top-0.2` - أعلى 0.2ريم
- `.top-0.1` - أعلى 0.1rem
- `.top-0` - أعلى 0ريم

##### Negative Top

- `.-top-5` - أعلى 5rem سلبي
- `.-top-4.5` - أعلى سلبي 0rem
- `.-top-4` - أعلى سلبي 4rem
- `.-top-3.5` - أعلى سلبي 0rem
- `.-top-3` - أعلى سلبي 3rem
- `.-top-2.5` - أعلى سلبي 0rem
- `.-top-2` - أعلى سلبي 2rem
- `.-top-1.9` - أعلى سلبي 0rem
- `.-top-1.8` - أعلى سلبي 0rem
- `.-top-1.7` - أعلى سلبي 0rem
- `.-top-1.6` - أعلى سلبي 0rem
- `.-top-1.5` - أعلى سلبي 0rem
- `.-top-1.4` - أعلى سلبي 0rem
- `.-top-1.3` - أعلى سلبي 0rem
- `.-top-1.2` - أعلى سلبي 0rem
- `.-top-1.1` - أعلى سلبي 0rem
- `.-top-1` - أعلى سلبي 1rem
- `.-top-0.9` - أعلى سلبي 0rem
- `.-top-0.8` - أعلى سلبي 0rem
- `.-top-0.7` - أعلى سلبي 0rem
- `.-top-0.6` - أعلى سلبي 0rem
- `.-top-0.5` - أعلى سلبي 0rem
- `.-top-0.4` - أعلى سلبي 0rem
- `.-top-0.3` - أعلى سلبي 0.3rem
- `.-top-0.2` - أعلى سلبي 0.2rem
- `.-top-0.1` - أعلى سلبي 0.1rem
- `.hover:-top-5` - أعلى 5rem سلبي عند التمرير
- `.hover:-top-4.5` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-4` - أعلى 4rem سلبي عند التمرير
- `.hover:-top-3.5` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-3` - أعلى 3rem سلبي عند التمرير
- `.hover:-top-2.5` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-2` - أعلى 2rem سلبي عند التمرير
- `.hover:-top-1.9` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.8` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.7` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.6` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.5` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.4` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.3` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.2` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1.1` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-1` - أعلى 1rem سلبي عند التمرير
- `.hover:-top-0.9` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-0.8` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-0.7` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-0.6` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-0.5` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-0.4` - أعلى سلبي 0rem عند التمرير
- `.hover:-top-0.3` - أعلى سلبي 0.3rem عند التمرير
- `.hover:-top-0.2` - أعلى سلبي 0.2rem عند التمرير
- `.hover:-top-0.1` - أعلى سلبي 0.1rem عند التمرير

### Right

- `.hover:right-100` - حق 100 ريم عند التحويم
- `.hover:right-75` - 75ريمًا صحيحًا عند التحويم
- `.hover:right-50` - حق 50ريم عند التحويم
- `.hover:right-25` - الحق 25rem عند التحويم
- `.hover:right-5` - 5rem الصحيح عند التحويم
- `.hover:right-4.5` - حق 0rem عند التحويم
- `.hover:right-4` - حق 4rem عند التحويم
- `.hover:right-3.5` - حق 0rem عند التحويم
- `.hover:right-3` - حق 3rem عند التحويم
- `.hover:right-2.5` - حق 0rem عند التحويم
- `.hover:right-2` - حق 2rem عند التحويم
- `.hover:right-1.9` - حق 0rem عند التحويم
- `.hover:right-1.8` - حق 0rem عند التحويم
- `.hover:right-1.7` - حق 0rem عند التحويم
- `.hover:right-1.6` - حق 0rem عند التحويم
- `.hover:right-1.5` - حق 0rem عند التحويم
- `.hover:right-1.4` - حق 0rem عند التحويم
- `.hover:right-1.3` - حق 0rem عند التحويم
- `.hover:right-1.2` - حق 0rem عند التحويم
- `.hover:right-1.1` - حق 0rem عند التحويم
- `.hover:right-1` - 1rem الصحيح عند التمرير
- `.hover:right-0.9` - حق 0rem عند التحويم
- `.hover:right-0.8` - حق 0rem عند التحويم
- `.hover:right-0.7` - حق 0rem عند التحويم
- `.hover:right-0.6` - حق 0rem عند التحويم
- `.hover:right-0.5` - حق 0rem عند التحويم
- `.hover:right-0.4` - حق 0rem عند التحويم
- `.hover:right-0.3` - حق 0rem عند التحويم
- `.hover:right-0.2` - الحق 0.2rem عند التحويم
- `.hover:right-0.1` - حق 0.1rem عند التحويم
- `.hover:right-0` - حق 0rem عند التحويم
- `.right-100` - الحق 100ريم
- `.right-75` - الحق 75ريم
- `.right-50` - حق 50ريم
- `.right-25` - حق 25ريم
- `.right-5` - حق 5ريم
- `.right-4.5` - صحيح 0ريم
- `.right-4` - حق 4ريم
- `.right-3.5` - صحيح 0ريم
- `.right-3` - حق 3ريم
- `.right-2.5` - صحيح 0ريم
- `.right-2` - حق 2ريم
- `.right-1.9` - صحيح 0ريم
- `.right-1.8` - صحيح 0ريم
- `.right-1.7` - صحيح 0ريم
- `.right-1.6` - صحيح 0ريم
- `.right-1.5` - صحيح 0ريم
- `.right-1.4` - صحيح 0ريم
- `.right-1.3` - صحيح 0ريم
- `.right-1.2` - صحيح 0ريم
- `.right-1.1` - صحيح 0ريم
- `.right-1` - حق 1ريم
- `.right-0.9` - صحيح 0ريم
- `.right-0.8` - صحيح 0ريم
- `.right-0.7` - صحيح 0ريم
- `.right-0.6` - صحيح 0ريم
- `.right-0.5` - صحيح 0ريم
- `.right-0.4` - صحيح 0ريم
- `.right-0.3` - صحيح 0ريم
- `.right-0.2` - حق 0.2ريم
- `.right-0.1` - الحق 0.1ريم
- `.right-0` - صحيح 0ريم

##### Negative Right

- `.-right-5` - الحق السلبي 5rem
- `.-right-4.5` - الحق السلبي 0rem
- `.-right-4` - الحق السلبي 4rem
- `.-right-3.5` - الحق السلبي 0rem
- `.-right-3` - الحق السلبي 3rem
- `.-right-2.5` - الحق السلبي 0rem
- `.-right-2` - الحق السلبي 2rem
- `.-right-1.9` - الحق السلبي 0rem
- `.-right-1.8` - الحق السلبي 0rem
- `.-right-1.7` - الحق السلبي 0rem
- `.-right-1.6` - الحق السلبي 0rem
- `.-right-1.5` - الحق السلبي 0rem
- `.-right-1.4` - الحق السلبي 0rem
- `.-right-1.3` - الحق السلبي 0rem
- `.-right-1.2` - الحق السلبي 0rem
- `.-right-1.1` - الحق السلبي 0rem
- `.-right-1` - الحق السلبي 1rem
- `.-right-0.9` - الحق السلبي 0rem
- `.-right-0.8` - الحق السلبي 0rem
- `.-right-0.7` - الحق السلبي 0rem
- `.-right-0.6` - الحق السلبي 0rem
- `.-right-0.5` - الحق السلبي 0rem
- `.-right-0.4` - الحق السلبي 0rem
- `.-right-0.3` - الحق السلبي 0.3rem
- `.-right-0.2` - الحق السلبي 0.2rem
- `.-right-0.1` - الحق السلبي 0.1rem
- `.hover:-right-5` - 5rem الأيمن السلبي عند التحويم
- `.hover:-right-4.5` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-4` - الحق السلبي 4rem عند التحويم
- `.hover:-right-3.5` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-3` - 3rem صحيح سلبي عند التمرير
- `.hover:-right-2.5` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-2` - حق سلبي 2rem عند التحويم
- `.hover:-right-1.9` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.8` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.7` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.6` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.5` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.4` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.3` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.2` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1.1` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-1` - 1rem صحيح سلبي عند التمرير
- `.hover:-right-0.9` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-0.8` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-0.7` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-0.6` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-0.5` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-0.4` - سلبي صحيح 0rem عند التحويم
- `.hover:-right-0.3` - الحق السلبي 0.3rem عند التحويم
- `.hover:-right-0.2` - الحق السلبي 0.2rem عند التحويم
- `.hover:-right-0.1` - الحق السلبي 0.1rem عند التحويم

### Bottom

- `.bottom-100` - أسفل 100ريم
- `.bottom-75` - أسفل 75ريم
- `.bottom-50` - أسفل 50ريم
- `.bottom-25` - أسفل 25ريم
- `.bottom-5` - أسفل 5ريم
- `.bottom-4.5` - أسفل 0ريم
- `.bottom-4` - أسفل 4ريم
- `.bottom-3.5` - أسفل 0ريم
- `.bottom-3` - أسفل 3ريم
- `.bottom-2.5` - أسفل 0ريم
- `.bottom-2` - أسفل 2ريم
- `.bottom-1.9` - أسفل 0ريم
- `.bottom-1.8` - أسفل 0ريم
- `.bottom-1.7` - أسفل 0ريم
- `.bottom-1.6` - أسفل 0ريم
- `.bottom-1.5` - أسفل 0ريم
- `.bottom-1.4` - أسفل 0ريم
- `.bottom-1.3` - أسفل 0ريم
- `.bottom-1.2` - أسفل 0ريم
- `.bottom-1.1` - أسفل 0ريم
- `.bottom-1` - أسفل 1ريم
- `.bottom-0.9` - أسفل 0ريم
- `.bottom-0.8` - أسفل 0ريم
- `.bottom-0.7` - أسفل 0ريم
- `.bottom-0.6` - أسفل 0ريم
- `.bottom-0.5` - أسفل 0ريم
- `.bottom-0.4` - أسفل 0ريم
- `.bottom-0.3` - أسفل 0ريم
- `.bottom-0.2` - أسفل 0.2rem
- `.bottom-0.1` - أسفل 0.1rem
- `.bottom-0` - أسفل 0ريم
- `.hover:bottom-100` - أسفل 100 ريم عند التحويم
- `.hover:bottom-75` - أسفل 75ريم عند التحويم
- `.hover:bottom-50` - أسفل 50 ريم عند التحويم
- `.hover:bottom-25` - أسفل 25ريم عند التحويم
- `.hover:bottom-5` - أسفل 5rem عند التمرير
- `.hover:bottom-4.5` - أسفل 0rem عند التمرير
- `.hover:bottom-4` - أسفل 4rem عند التمرير
- `.hover:bottom-3.5` - أسفل 0rem عند التمرير
- `.hover:bottom-3` - أسفل 3rem عند التمرير
- `.hover:bottom-2.5` - أسفل 0rem عند التمرير
- `.hover:bottom-2` - أسفل 2rem عند التمرير
- `.hover:bottom-1.9` - أسفل 0rem عند التمرير
- `.hover:bottom-1.8` - أسفل 0rem عند التمرير
- `.hover:bottom-1.7` - أسفل 0rem عند التمرير
- `.hover:bottom-1.6` - أسفل 0rem عند التمرير
- `.hover:bottom-1.5` - أسفل 0rem عند التمرير
- `.hover:bottom-1.4` - أسفل 0rem عند التمرير
- `.hover:bottom-1.3` - أسفل 0rem عند التمرير
- `.hover:bottom-1.2` - أسفل 0rem عند التمرير
- `.hover:bottom-1.1` - أسفل 0rem عند التمرير
- `.hover:bottom-1` - أسفل 1rem عند التمرير
- `.hover:bottom-0.9` - أسفل 0rem عند التمرير
- `.hover:bottom-0.8` - أسفل 0rem عند التمرير
- `.hover:bottom-0.7` - أسفل 0rem عند التمرير
- `.hover:bottom-0.6` - أسفل 0rem عند التمرير
- `.hover:bottom-0.5` - أسفل 0rem عند التمرير
- `.hover:bottom-0.4` - أسفل 0rem عند التمرير
- `.hover:bottom-0.3` - أسفل 0rem عند التمرير
- `.hover:bottom-0.2` - أسفل 0.2rem عند التمرير
- `.hover:bottom-0.1` - أسفل 0.1rem عند التمرير
- `.hover:bottom-0` - أسفل 0rem عند التمرير

##### Negative Bottom

- `.-bottom-5` - القاع السلبي 5rem
- `.-bottom-4.5` - القاع السلبي 0rem
- `.-bottom-4` - القاع السلبي 4rem
- `.-bottom-3.5` - القاع السلبي 0rem
- `.-bottom-3` - القاع السلبي 3rem
- `.-bottom-2.5` - القاع السلبي 0rem
- `.-bottom-2` - القاع السلبي 2rem
- `.-bottom-1.9` - القاع السلبي 0rem
- `.-bottom-1.8` - القاع السلبي 0rem
- `.-bottom-1.7` - القاع السلبي 0rem
- `.-bottom-1.6` - القاع السلبي 0rem
- `.-bottom-1.5` - القاع السلبي 0rem
- `.-bottom-1.4` - القاع السلبي 0rem
- `.-bottom-1.3` - القاع السلبي 0rem
- `.-bottom-1.2` - القاع السلبي 0rem
- `.-bottom-1.1` - القاع السلبي 0rem
- `.-bottom-1` - القاع السلبي 1rem
- `.-bottom-0.9` - القاع السلبي 0rem
- `.-bottom-0.8` - القاع السلبي 0rem
- `.-bottom-0.7` - القاع السلبي 0rem
- `.-bottom-0.6` - القاع السلبي 0rem
- `.-bottom-0.5` - القاع السلبي 0rem
- `.-bottom-0.4` - القاع السلبي 0rem
- `.-bottom-0.3` - القاع السلبي 0.3rem
- `.-bottom-0.2` - القاع السلبي 0.2rem
- `.-bottom-0.1` - القاع السلبي 0.1rem
- `.hover:-bottom-5` - 5rem السفلي السلبي عند التمرير
- `.hover:-bottom-4.5` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-4` - سلبي أسفل 4rem عند التمرير
- `.hover:-bottom-3.5` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-3` - سلبي أسفل 3rem عند التمرير
- `.hover:-bottom-2.5` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-2` - سلبي أسفل 2rem عند التمرير
- `.hover:-bottom-1.9` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.8` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.7` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.6` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.5` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.4` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.3` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.2` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1.1` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-1` - 1rem أسفل سلبي عند التمرير
- `.hover:-bottom-0.9` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-0.8` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-0.7` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-0.6` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-0.5` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-0.4` - سلبي أسفل 0rem عند التمرير
- `.hover:-bottom-0.3` - القاع السلبي 0.3rem عند التحويم
- `.hover:-bottom-0.2` - القاع السلبي 0.2rem عند التمرير
- `.hover:-bottom-0.1` - القاع السلبي 0.1rem عند التمرير

### Left

- `.hover:left-100` - ترك 100ريم عند التحويم
- `.hover:left-75` - ترك 75ريمًا عند التحويم
- `.hover:left-50` - ترك 50ريمًا عند التحويم
- `.hover:left-25` - ترك 25ريمًا عند التحويم
- `.hover:left-5` - اليسار 5ريم على التحويم
- `.hover:left-4.5` - اليسار 0rem عند التمرير
- `.hover:left-4` - اليسار 4ريم على التحويم
- `.hover:left-3.5` - اليسار 0rem عند التمرير
- `.hover:left-3` - اليسار 3rem على التحويم
- `.hover:left-2.5` - اليسار 0rem عند التمرير
- `.hover:left-2` - اليسار 2ريم على التحويم
- `.hover:left-1.9` - اليسار 0rem عند التمرير
- `.hover:left-1.8` - اليسار 0rem عند التمرير
- `.hover:left-1.7` - اليسار 0rem عند التمرير
- `.hover:left-1.6` - اليسار 0rem عند التمرير
- `.hover:left-1.5` - اليسار 0rem عند التمرير
- `.hover:left-1.4` - اليسار 0rem عند التمرير
- `.hover:left-1.3` - اليسار 0rem عند التمرير
- `.hover:left-1.2` - اليسار 0rem عند التمرير
- `.hover:left-1.1` - اليسار 0rem عند التمرير
- `.hover:left-1` - ترك 1rem عند التمرير
- `.hover:left-0.9` - اليسار 0rem عند التمرير
- `.hover:left-0.8` - اليسار 0rem عند التمرير
- `.hover:left-0.7` - اليسار 0rem عند التمرير
- `.hover:left-0.6` - اليسار 0rem عند التمرير
- `.hover:left-0.5` - اليسار 0rem عند التمرير
- `.hover:left-0.4` - اليسار 0rem عند التمرير
- `.hover:left-0.3` - اليسار 0rem عند التمرير
- `.hover:left-0.2` - ترك 0.2ريم عند التحويم
- `.hover:left-0.1` - اليسار 0.1rem عند التمرير
- `.hover:left-0` - اليسار 0rem عند التمرير
- `.left-100` - اليسار 100ريم
- `.left-75` - اليسار 75ريم
- `.left-50` - اليسار 50ريم
- `.left-25` - اليسار 25ريم
- `.left-5` - اليسار 5ريم
- `.left-4.5` - اليسار 0ريم
- `.left-4` - اليسار 4ريم
- `.left-3.5` - اليسار 0ريم
- `.left-3` - اليسار 3ريم
- `.left-2.5` - اليسار 0ريم
- `.left-2` - اليسار 2ريم
- `.left-1.9` - اليسار 0ريم
- `.left-1.8` - اليسار 0ريم
- `.left-1.7` - اليسار 0ريم
- `.left-1.6` - اليسار 0ريم
- `.left-1.5` - اليسار 0ريم
- `.left-1.4` - اليسار 0ريم
- `.left-1.3` - اليسار 0ريم
- `.left-1.2` - اليسار 0ريم
- `.left-1.1` - اليسار 0ريم
- `.left-1` - اليسار 1ريم
- `.left-0.9` - اليسار 0ريم
- `.left-0.8` - اليسار 0ريم
- `.left-0.7` - اليسار 0ريم
- `.left-0.6` - اليسار 0ريم
- `.left-0.5` - اليسار 0ريم
- `.left-0.4` - اليسار 0ريم
- `.left-0.3` - اليسار 0ريم
- `.left-0.2` - اليسار 0.2ريم
- `.left-0.1` - اليسار 0.1ريم
- `.left-0` - اليسار 0ريم

##### Negative Left

- `.-left-5` - اليسار السلبي 5rem
- `.-left-4.5` - اليسار السلبي 0rem
- `.-left-4` - اليسار السلبي 4rem
- `.-left-3.5` - اليسار السلبي 0rem
- `.-left-3` - اليسار السلبي 3rem
- `.-left-2.5` - اليسار السلبي 0rem
- `.-left-2` - اليسار السلبي 2rem
- `.-left-1.9` - اليسار السلبي 0rem
- `.-left-1.8` - اليسار السلبي 0rem
- `.-left-1.7` - اليسار السلبي 0rem
- `.-left-1.6` - اليسار السلبي 0rem
- `.-left-1.5` - اليسار السلبي 0rem
- `.-left-1.4` - اليسار السلبي 0rem
- `.-left-1.3` - اليسار السلبي 0rem
- `.-left-1.2` - اليسار السلبي 0rem
- `.-left-1.1` - اليسار السلبي 0rem
- `.-left-1` - سلبي اليسار 1rem
- `.-left-0.9` - اليسار السلبي 0rem
- `.-left-0.8` - اليسار السلبي 0rem
- `.-left-0.7` - اليسار السلبي 0rem
- `.-left-0.6` - اليسار السلبي 0rem
- `.-left-0.5` - اليسار السلبي 0rem
- `.-left-0.4` - اليسار السلبي 0rem
- `.-left-0.3` - سلبي اليسار 0.3rem
- `.-left-0.2` - سلبي اليسار 0.2rem
- `.-left-0.1` - سلبي اليسار 0.1rem
- `.hover:-left-5` - السلبية اليسرى 5rem عند التحويم
- `.hover:-left-4.5` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-4` - السلبية اليسرى 4rem عند التحويم
- `.hover:-left-3.5` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-3` - سلبي 3rem الأيسر عند التمرير
- `.hover:-left-2.5` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-2` - السلبية اليسرى 2rem عند التحويم
- `.hover:-left-1.9` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.8` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.7` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.6` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.5` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.4` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.3` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.2` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1.1` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-1` - 1rem الأيسر السلبي عند التمرير
- `.hover:-left-0.9` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-0.8` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-0.7` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-0.6` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-0.5` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-0.4` - السلبية اليسرى 0rem عند التمرير
- `.hover:-left-0.3` - اليسار السلبي 0.3rem عند التمرير
- `.hover:-left-0.2` - سلبي اليسار 0.2rem عند التحويم
- `.hover:-left-0.1` - سلبي اليسار 0.1rem عند التحويم

### Z-Index

- `.hover:z-5` - مؤشر Z 5 عند التمرير
- `.hover:z-4` - مؤشر Z 4 عند التمرير
- `.hover:z-3` - مؤشر Z 3 عند التمرير
- `.hover:z-2` - مؤشر Z 2 عند التمرير
- `.hover:z-1` - مؤشر Z 1 عند التمرير
- `.hover:z-0` - مؤشر Z 0 عند التمرير
- `.hover:z-auto` - مؤشر Z تلقائي عند التمرير
- `.z-5` - مؤشر Z 5
- `.z-4` - مؤشر Z 4
- `.z-3` - مؤشر Z 3
- `.z-2` - مؤشر Z 2
- `.z-1` - مؤشر Z 1
- `.z-0` - مؤشر Z 0
- `.z-auto` - مؤشر Z تلقائي

##### Negative Z-Index

- `.-z-5` - مؤشر Z السلبي 5
- `.-z-4` - مؤشر Z السلبي 4
- `.-z-3` - مؤشر Z السلبي 3
- `.-z-2` - مؤشر Z السلبي 2
- `.-z-1` - مؤشر Z السلبي 1
- `.hover:-z-5` - مؤشر Z سلبي 5 عند التمرير
- `.hover:-z-4` - مؤشر Z سلبي 4 عند التمرير
- `.hover:-z-3` - مؤشر Z سلبي 3 عند التمرير
- `.hover:-z-2` - مؤشر Z سلبي 2 عند التمرير
- `.hover:-z-1` - مؤشر Z سلبي 1 عند التمرير

## Typography

### Font

- `.font-italic` - الخط مائل
- `.font-normal` - الخط عادي
- `.hover:font-italic` - الخط مائل عند التمرير
- `.hover:font-normal` - الخط عادي عند التمرير

### Font Size

- `.font-size-10` - حجم الخط 10ريم
- `.font-size-9.5` - حجم الخط 0ريم
- `.font-size-9` - حجم الخط 9ريم
- `.font-size-8.5` - حجم الخط 0ريم
- `.font-size-8` - حجم الخط 8ريم
- `.font-size-7.5` - حجم الخط 0ريم
- `.font-size-7` - حجم الخط 7ريم
- `.font-size-6.5` - حجم الخط 0ريم
- `.font-size-6` - حجم الخط 6ريم
- `.font-size-5.5` - حجم الخط 0ريم
- `.font-size-5` - حجم الخط 5ريم
- `.font-size-4.5` - حجم الخط 0ريم
- `.font-size-4` - حجم الخط 4ريم
- `.font-size-3.5` - حجم الخط 0ريم
- `.font-size-3` - حجم الخط 3ريم
- `.font-size-2.5` - حجم الخط 0ريم
- `.font-size-2` - حجم الخط 2ريم
- `.font-size-1.9` - حجم الخط 0ريم
- `.font-size-1.8` - حجم الخط 0ريم
- `.font-size-1.7` - حجم الخط 0ريم
- `.font-size-1.6` - حجم الخط 0ريم
- `.font-size-1.5` - حجم الخط 0ريم
- `.font-size-1.4` - حجم الخط 0ريم
- `.font-size-1.3` - حجم الخط 0ريم
- `.font-size-1.2` - حجم الخط 0ريم
- `.font-size-1.1` - حجم الخط 0ريم
- `.font-size-1` - حجم الخط 1ريم
- `.font-size-0.9` - حجم الخط 0ريم
- `.font-size-0.8` - حجم الخط 0ريم
- `.font-size-0.7` - حجم الخط 0.7ريم
- `.font-size-0.6` - حجم الخط 0.6ريم
- `.font-size-0.5` - حجم الخط 0.5ريم
- `.hover:font-size-10` - حجم الخط 10ريم عند التحويم
- `.hover:font-size-9.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-9` - حجم الخط 9rem عند التحويم
- `.hover:font-size-8.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-8` - حجم الخط 8rem عند التحويم
- `.hover:font-size-7.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-7` - حجم الخط 7rem عند التحويم
- `.hover:font-size-6.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-6` - حجم الخط 6rem عند التمرير
- `.hover:font-size-5.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-5` - حجم الخط 5rem عند التمرير
- `.hover:font-size-4.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-4` - حجم الخط 4rem عند التمرير
- `.hover:font-size-3.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-3` - حجم الخط 3rem عند التمرير
- `.hover:font-size-2.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-2` - حجم الخط 2rem عند التمرير
- `.hover:font-size-1.9` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.8` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.7` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.6` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.5` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.4` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.3` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.2` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1.1` - حجم الخط 0rem عند التمرير
- `.hover:font-size-1` - حجم الخط 1rem عند التمرير
- `.hover:font-size-0.9` - حجم الخط 0rem عند التمرير
- `.hover:font-size-0.8` - حجم الخط 0rem عند التمرير
- `.hover:font-size-0.7` - حجم الخط 0.7ريم عند التحويم
- `.hover:font-size-0.6` - حجم الخط 0.6rem عند التمرير
- `.hover:font-size-0.5` - حجم الخط 0.5rem عند التمرير

### Font Weight

- `.font-weight-900` - وزن الخط 900
- `.font-weight-800` - وزن الخط 800
- `.font-weight-700` - وزن الخط 700
- `.font-weight-600` - وزن الخط 600
- `.font-weight-500` - وزن الخط 500
- `.font-weight-400` - وزن الخط 400
- `.font-weight-300` - وزن الخط 300
- `.font-weight-200` - وزن الخط 200
- `.font-weight-100` - وزن الخط 100
- `.font-weight-bold` - وزن الخط غامق
- `.hover:font-weight-900` - وزن الخط 900 عند التمرير
- `.hover:font-weight-800` - وزن الخط 800 عند التمرير
- `.hover:font-weight-700` - وزن الخط 700 عند التمرير
- `.hover:font-weight-600` - وزن الخط 600 عند التمرير
- `.hover:font-weight-500` - وزن الخط 500 عند التمرير
- `.hover:font-weight-400` - وزن الخط 400 عند التمرير
- `.hover:font-weight-300` - وزن الخط 300 عند التمرير
- `.hover:font-weight-200` - وزن الخط 200 عند التمرير
- `.hover:font-weight-100` - وزن الخط 100 عند التمرير
- `.hover:font-weight-bold` - وزن الخط غامق عند التمرير

### Letter spacing

- `.hover:letter-spacing-1` - تباعد الحروف 1rem عند التمرير
- `.hover:letter-spacing-0.9` - تباعد الحروف 0rem عند التمرير
- `.hover:letter-spacing-0.8` - تباعد الحروف 0rem عند التمرير
- `.hover:letter-spacing-0.7` - تباعد الحروف 0rem عند التمرير
- `.hover:letter-spacing-0.6` - تباعد الحروف 0rem عند التمرير
- `.hover:letter-spacing-0.5` - تباعد الحروف 0rem عند التمرير
- `.hover:letter-spacing-0.4` - تباعد الحروف 0rem عند التمرير
- `.hover:letter-spacing-0.3` - تباعد الحروف 0.3rem عند التمرير
- `.hover:letter-spacing-0.2` - تباعد الحروف 0.2rem عند التمرير
- `.hover:letter-spacing-0.1` - تباعد الحروف 0.1rem عند التمرير
- `.letter-spacing-1` - تباعد الحروف 1ريم
- `.letter-spacing-0.9` - تباعد الحروف 0rem
- `.letter-spacing-0.8` - تباعد الحروف 0rem
- `.letter-spacing-0.7` - تباعد الحروف 0rem
- `.letter-spacing-0.6` - تباعد الحروف 0rem
- `.letter-spacing-0.5` - تباعد الحروف 0rem
- `.letter-spacing-0.4` - تباعد الحروف 0rem
- `.letter-spacing-0.3` - تباعد الحروف 0.3ريم
- `.letter-spacing-0.2` - تباعد الحروف 0.2ريم
- `.letter-spacing-0.1` - تباعد الحروف 0.1ريم

### Line height

- `.hover:line-height-5` - ارتفاع الخط 5rem عند التحويم
- `.hover:line-height-4` - ارتفاع الخط 4rem عند التحويم
- `.hover:line-height-3` - ارتفاع الخط 3rem عند التمرير
- `.hover:line-height-2` - ارتفاع الخط 2rem عند التحويم
- `.hover:line-height-1` - ارتفاع الخط 1rem عند التمرير
- `.line-height-5` - ارتفاع الخط 5ريم
- `.line-height-4` - ارتفاع الخط 4ريم
- `.line-height-3` - ارتفاع الخط 3ريم
- `.line-height-2` - ارتفاع الخط 2ريم
- `.line-height-1` - ارتفاع الخط 1ريم

### Text

- `.hover:text-capitalize` - الاستفادة من النص عند التمرير
- `.hover:text-center` - مركز النص عند التمرير
- `.hover:text-end` - نهاية النص عند التمرير
- `.hover:text-justify` - ضبط النص عند التمرير
- `.hover:text-left` - ترك النص عند التمرير
- `.hover:text-line-none` - سطر النص لا شيء عند التمرير
- `.hover:text-line-overline` - خط علوي للنص عند التمرير
- `.hover:text-line-through` - سطر النص عند التمرير
- `.hover:text-line-underline` - تسطير سطر النص عند التمرير
- `.hover:text-lowercase` - نص صغير عند التمرير
- `.hover:text-right` - النص مباشرة عند التمرير
- `.hover:text-start` - يبدأ النص عند التمرير
- `.hover:text-transparent` - نص شفاف عند التمرير
- `.hover:text-uppercase` - النص بأحرف كبيرة عند التمرير
- `.text-break-all` - كسر النص للجميع
- `.text-break-keep-all` - فاصل النص، الاحتفاظ بالكل
- `.text-break-normal` - كسر النص عادي
- `.text-break-word` - كلمة فاصل النص
- `.text-capitalize` - تكبير النص
- `.text-center` - مركز النص
- `.text-end` - نهاية النص
- `.text-justify` - تبرير النص
- `.text-left` - ترك النص
- `.text-line-none` - سطر النص-لا شيء
- `.text-line-overline` - خط النص فوق الخط
- `.text-line-through` - سطر من خلال النص
- `.text-line-underline` - تسطير سطر النص
- `.text-lowercase` - النص بأحرف صغيرة
- `.text-overflow-clip` - مقطع تجاوز النص
- `.text-overflow-ellipsis` - تجاوز النص القطع الناقص
- `.text-right` - النص الصحيح
- `.text-start` - بداية النص
- `.text-transparent` - النص شفاف
- `.text-uppercase` - النص بأحرف كبيرة

##### Text - Mobile (< 480px)

- `.hover:mobile:text-center` - مركز النص عند التمرير على الهاتف المحمول
- `.hover:mobile:text-end` - نهاية النص عند التمرير على الهاتف المحمول
- `.hover:mobile:text-justify` - ضبط النص عند التمرير على الهاتف المحمول
- `.hover:mobile:text-left` - النص المتبقي عند التمرير على الهاتف المحمول
- `.hover:mobile:text-right` - إرسال رسالة نصية مباشرة عند التمرير على الهاتف المحمول
- `.hover:mobile:text-start` - يبدأ النص عند التمرير على الهاتف المحمول
- `.mobile:text-center` - مركز النص على الهاتف المحمول
- `.mobile:text-end` - نهاية النص على الهاتف المحمول
- `.mobile:text-justify` - ضبط النص على الهاتف المحمول
- `.mobile:text-left` - النص المتبقي على الهاتف المحمول
- `.mobile:text-right` - إرسال رسالة نصية مباشرة على الهاتف المحمول
- `.mobile:text-start` - يبدأ النص على الهاتف المحمول

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - مركز النص عند التمرير على الجهاز اللوحي
- `.hover:tablet:text-end` - نهاية النص عند التمرير على الجهاز اللوحي
- `.hover:tablet:text-justify` - ضبط النص عند التمرير على الجهاز اللوحي
- `.hover:tablet:text-left` - النص المتبقي عند التمرير على الجهاز اللوحي
- `.hover:tablet:text-right` - إرسال النص مباشرة عند التمرير على الجهاز اللوحي
- `.hover:tablet:text-start` - يبدأ النص عند التمرير على الجهاز اللوحي
- `.tablet:text-center` - مركز النص على الجهاز اللوحي
- `.tablet:text-end` - نهاية النص على الجهاز اللوحي
- `.tablet:text-justify` - ضبط النص على الجهاز اللوحي
- `.tablet:text-left` - النص المتبقي على الجهاز اللوحي
- `.tablet:text-right` - النص مباشرة على الجهاز اللوحي
- `.tablet:text-start` - يبدأ النص على الجهاز اللوحي

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - مركز النص عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:text-end` - نهاية النص عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:text-justify` - ضبط النص عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:text-left` - النص المتبقي عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:text-right` - النص مباشرة عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:text-start` - يبدأ النص عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:text-center` - مركز النص على الكمبيوتر اللوحي
- `.tablet-pc:text-end` - نهاية النص على الكمبيوتر اللوحي
- `.tablet-pc:text-justify` - ضبط النص على الكمبيوتر اللوحي
- `.tablet-pc:text-left` - النص المتبقي على الكمبيوتر اللوحي
- `.tablet-pc:text-right` - النص مباشرة على الكمبيوتر اللوحي
- `.tablet-pc:text-start` - يبدأ النص على الكمبيوتر اللوحي

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - مركز النص عند التمرير على جهاز الكمبيوتر
- `.hover:pc:text-end` - نهاية النص عند التمرير على جهاز الكمبيوتر
- `.hover:pc:text-justify` - ضبط النص عند التمرير على جهاز الكمبيوتر
- `.hover:pc:text-left` - النص المتبقي عند التمرير على جهاز الكمبيوتر
- `.hover:pc:text-right` - إرسال النص مباشرة عند التمرير على جهاز الكمبيوتر
- `.hover:pc:text-start` - يبدأ النص عند التمرير على جهاز الكمبيوتر
- `.pc:text-center` - مركز النص على جهاز الكمبيوتر
- `.pc:text-end` - نهاية النص على جهاز الكمبيوتر
- `.pc:text-justify` - ضبط النص على جهاز الكمبيوتر
- `.pc:text-left` - النص المتبقي على جهاز الكمبيوتر
- `.pc:text-right` - النص مباشرة على جهاز الكمبيوتر
- `.pc:text-start` - يبدأ النص على جهاز الكمبيوتر

##### Text - Tv (> 1200px)

- `.hover:tv:text-center` - مركز النص عند التمرير على شاشة التلفزيون
- `.hover:tv:text-end` - نهاية النص عند التمرير على شاشة التلفزيون
- `.hover:tv:text-justify` - تبرير النص عند التمرير على شاشة التلفزيون
- `.hover:tv:text-left` - النص المتبقي على التمرير على شاشة التلفزيون
- `.hover:tv:text-right` - إرسال رسالة نصية مباشرة عند التمرير على شاشة التلفزيون
- `.hover:tv:text-start` - يبدأ النص عند التمرير على شاشة التلفزيون
- `.tv:text-center` - مركز النص على شاشة التلفزيون
- `.tv:text-end` - نهاية النص على شاشة التلفزيون
- `.tv:text-justify` - تبرير النص على شاشة التلفزيون
- `.tv:text-left` - النص المتبقي على شاشة التلفزيون
- `.tv:text-right` - النص مباشرة على شاشة التلفزيون
- `.tv:text-start` - يبدأ النص على شاشة التلفزيون

##### Text - Tablet Max (< 768px)

- `.hover:tablet-max:text-center` - مركز النص عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:text-end` - نهاية النص عند التمرير على الجهاز اللوحي كحد أقصى
- `.hover:tablet-max:text-justify` - ضبط النص عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:text-left` - النص المتبقي عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:text-right` - النص مباشرة عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:text-start` - يبدأ النص عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:text-center` - مركز النص على الجهاز اللوحي كحد أقصى
- `.tablet-max:text-end` - نهاية النص على الجهاز اللوحي كحد أقصى
- `.tablet-max:text-justify` - ضبط النص على الجهاز اللوحي بحد أقصى
- `.tablet-max:text-left` - النص المتبقي على الجهاز اللوحي كحد أقصى
- `.tablet-max:text-right` - النص مباشرة على الجهاز اللوحي بحد أقصى
- `.tablet-max:text-start` - بداية النص على الجهاز اللوحي بحد أقصى

##### Text - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:text-center` - مركز النص عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:text-end` - نهاية النص عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:text-justify` - ضبط النص عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:text-left` - النص المتبقي عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:text-right` - النص مباشرة عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:text-start` - يبدأ النص عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:text-center` - مركز النص على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:text-end` - نهاية النص على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:text-justify` - ضبط النص على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:text-left` - النص المتبقي على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:text-right` - النص مباشرة على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:text-start` - بدء النص على الكمبيوتر اللوحي بحد أقصى

##### Text - Pc Max (< 1200px)

- `.hover:pc-max:text-center` - مركز النص عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:text-end` - نهاية النص عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:text-justify` - ضبط النص عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:text-left` - النص المتبقي عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:text-right` - النص مباشرة عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:text-start` - يبدأ النص عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:text-center` - مركز النص على جهاز الكمبيوتر كحد أقصى
- `.pc-max:text-end` - نهاية النص على جهاز الكمبيوتر كحد أقصى
- `.pc-max:text-justify` - ضبط النص على جهاز الكمبيوتر كحد أقصى
- `.pc-max:text-left` - النص المتبقي على جهاز الكمبيوتر كحد أقصى
- `.pc-max:text-right` - النص مباشرة على جهاز الكمبيوتر كحد أقصى
- `.pc-max:text-start` - بدء النص على جهاز الكمبيوتر كحد أقصى

### Whitespace

- `.hover:whitespace-normal` - المسافة البيضاء عادية عند التمرير
- `.whitespace-normal` - مسافة بيضاء عادية
- `.whitespace-nowrap` - المسافة البيضاء الآن راب
- `.whitespace-pre` - مسافة بيضاء قبل

### Whitespace break

- `.hover:whitespace-break-spaces` - مسافة بيضاء تفصل المسافات عند التمرير
- `.whitespace-break-spaces` - مسافات فاصلة بالمسافات البيضاء

### Whitespace pre

- `.hover:whitespace-pre-line` - مسافة بيضاء قبل الخط عند التمرير
- `.hover:whitespace-pre-wrap` - التفاف المسافة البيضاء مسبقًا عند التمرير
- `.whitespace-pre-line` - مسافة بيضاء قبل السطر
- `.whitespace-pre-wrap` - مسافة بيضاء قبل التفاف

### Writing h

- `.writing-h-tb` - كتابة ح السل

### Writing v

- `.writing-v-lr` - الكتابة ضد لير
- `.writing-v-rl` - الكتابة ضد رل

## Backgrounds

### Background

- `.bg-transparent` - الخلفية شفافة
- `.hover:bg-transparent` - خلفية شفافة عند التمرير

### Bg blur

- `.bg-blur-5` - بي جي طمس 5rem
- `.bg-blur-4` - بي جي طمس 4rem
- `.bg-blur-3` - بي جي طمس 3rem
- `.bg-blur-2` - بي جي طمس 2rem
- `.bg-blur-1` - بي جي طمس 1rem
- `.bg-blur-0` - طمس 0rem
- `.hover:bg-blur-5` - Bg طمس 5rem عند التحويم
- `.hover:bg-blur-4` - Bg طمس 4rem عند التحويم
- `.hover:bg-blur-3` - Bg طمس 3rem عند التحويم
- `.hover:bg-blur-2` - Bg طمس 2rem عند التحويم
- `.hover:bg-blur-1` - Bg طمس 1rem عند التمرير
- `.hover:bg-blur-0` - Bg طمس 0rem عند التحويم

## Borders

### Border

#### Border All

- `.border-2` - الحدود جميع 2rem
- `.border-1.5` - الحدود الكل 0rem
- `.border-1` - الحدود جميع 1rem
- `.border-0.9` - الحدود الكل 0rem
- `.border-0.8` - الحدود الكل 0rem
- `.border-0.7` - الحدود الكل 0rem
- `.border-0.6` - الحدود الكل 0rem
- `.border-0.5` - الحدود الكل 0rem
- `.border-0.4` - الحدود الكل 0.4rem
- `.border-0.3` - الحدود الكل 0rem
- `.border-0.2` - الحدود الكل 0.2rem
- `.border-0.1` - الحدود الكل 0.1rem
- `.border-0` - الحدود الكل 0rem
- `.hover:border-2` - الحدود الكل 2rem عند التحويم
- `.hover:border-1.5` - الحدود الكل 0rem عند التحويم
- `.hover:border-1` - الحدود الكل 1rem عند التحويم
- `.hover:border-0.9` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.8` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.7` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.6` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.5` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.4` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.3` - الحدود الكل 0rem عند التحويم
- `.hover:border-0.2` - الحدود الكل 0.2rem عند التحويم
- `.hover:border-0.1` - الحدود الكل 0.1rem عند التحويم
- `.hover:border-0` - الحدود الكل 0rem عند التحويم

#### Border Bottom

- `.border-b-2` - الحدود السفلية 2rem
- `.border-b-1.5` - الحدود السفلية 0rem
- `.border-b-1` - الحدود السفلية 1rem
- `.border-b-0.9` - الحدود السفلية 0rem
- `.border-b-0.8` - الحدود السفلية 0rem
- `.border-b-0.7` - الحدود السفلية 0rem
- `.border-b-0.6` - الحدود السفلية 0rem
- `.border-b-0.5` - الحدود السفلية 0.5ريم
- `.border-b-0.4` - الحدود السفلية 0rem
- `.border-b-0.3` - الحدود السفلية 0rem
- `.border-b-0.2` - الحدود السفلية 0.2rem
- `.border-b-0.1` - الحدود السفلية 0.1rem
- `.border-b-0` - الحدود السفلية 0rem
- `.hover:border-b-2` - الحدود السفلية 2rem عند التحويم
- `.hover:border-b-1.5` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-1` - الحدود السفلية 1rem عند التمرير
- `.hover:border-b-0.9` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.8` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.7` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.6` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.5` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.4` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.3` - الحدود السفلية 0rem عند التمرير
- `.hover:border-b-0.2` - الحد السفلي 0.2rem عند التحويم
- `.hover:border-b-0.1` - الحد السفلي 0.1rem عند التحويم
- `.hover:border-b-0` - الحدود السفلية 0rem عند التمرير

#### Border Left

- `.border-l-2` - الحدود اليسرى 2rem
- `.border-l-1.5` - الحدود اليسرى 0rem
- `.border-l-1` - الحدود اليسرى 1rem
- `.border-l-0.9` - الحدود اليسرى 0rem
- `.border-l-0.8` - الحدود اليسرى 0rem
- `.border-l-0.7` - الحدود اليسرى 0rem
- `.border-l-0.6` - الحدود اليسرى 0rem
- `.border-l-0.5` - الحدود اليسرى 0rem
- `.border-l-0.4` - الحدود اليسرى 0rem
- `.border-l-0.3` - الحدود اليسرى 0rem
- `.border-l-0.2` - الحدود اليسرى 0.2rem
- `.border-l-0.1` - الحدود اليسرى 0.1rem
- `.border-l-0` - الحدود اليسرى 0rem
- `.hover:border-l-2` - الحدود اليسرى 2rem عند التحويم
- `.hover:border-l-1.5` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-1` - الحد الأيسر 1rem عند التمرير
- `.hover:border-l-0.9` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.8` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.7` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.6` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.5` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.4` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.3` - الحد الأيسر 0rem عند التمرير
- `.hover:border-l-0.2` - الحدود اليسرى 0.2rem عند التمرير
- `.hover:border-l-0.1` - الحد الأيسر 0.1rem عند التمرير
- `.hover:border-l-0` - الحد الأيسر 0rem عند التمرير

#### Border Right

- `.border-r-2` - الحدود اليمنى 2rem
- `.border-r-1.5` - الحدود اليمنى 0rem
- `.border-r-1` - الحدود اليمنى 1rem
- `.border-r-0.9` - الحدود اليمنى 0rem
- `.border-r-0.8` - الحدود اليمنى 0rem
- `.border-r-0.7` - الحدود اليمنى 0rem
- `.border-r-0.6` - الحدود اليمنى 0rem
- `.border-r-0.5` - الحدود اليمنى 0rem
- `.border-r-0.4` - الحدود اليمنى 0rem
- `.border-r-0.3` - الحدود اليمنى 0rem
- `.border-r-0.2` - الحدود اليمنى 0.2rem
- `.border-r-0.1` - الحدود اليمنى 0.1rem
- `.border-r-0` - الحدود اليمنى 0rem
- `.hover:border-r-2` - الحدود اليمنى 2rem عند التحويم
- `.hover:border-r-1.5` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-1` - الحدود اليمنى 1rem عند التمرير
- `.hover:border-r-0.9` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.8` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.7` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.6` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.5` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.4` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.3` - الحدود اليمنى 0rem عند التمرير
- `.hover:border-r-0.2` - الحدود اليمنى 0.2rem عند التحويم
- `.hover:border-r-0.1` - الحدود اليمنى 0.1rem عند التمرير
- `.hover:border-r-0` - الحدود اليمنى 0rem عند التمرير

#### Border Top

- `.border-t-2` - الحدود الأعلى 2rem
- `.border-t-1.5` - الحدود الأعلى 0rem
- `.border-t-1` - الحدود الأعلى 1rem
- `.border-t-0.9` - الحدود الأعلى 0rem
- `.border-t-0.8` - الحدود الأعلى 0rem
- `.border-t-0.7` - الحدود الأعلى 0rem
- `.border-t-0.6` - الحدود الأعلى 0rem
- `.border-t-0.5` - الحدود الأعلى 0rem
- `.border-t-0.4` - الحدود الأعلى 0rem
- `.border-t-0.3` - الحدود الأعلى 0rem
- `.border-t-0.2` - الحدود الأعلى 0.2rem
- `.border-t-0.1` - الحدود الأعلى 0.1rem
- `.border-t-0` - الحدود الأعلى 0rem
- `.hover:border-t-2` - الحدود الأعلى 2rem عند التحويم
- `.hover:border-t-1.5` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-1` - الحدود العليا 1rem عند التحويم
- `.hover:border-t-0.9` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.8` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.7` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.6` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.5` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.4` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.3` - الحدود الأعلى 0rem عند التحويم
- `.hover:border-t-0.2` - الحدود العليا 0.2rem عند التحويم
- `.hover:border-t-0.1` - أعلى الحدود 0.1rem عند التحويم
- `.hover:border-t-0` - الحدود الأعلى 0rem عند التحويم

#### Border X-Axis

- `.border-x-2` - الحدود المحور X 2rem
- `.border-x-1.5` - الحدود المحور X 0rem
- `.border-x-1` - الحدود المحور X 1rem
- `.border-x-0.9` - الحدود المحور X 0rem
- `.border-x-0.8` - الحدود المحور X 0rem
- `.border-x-0.7` - الحدود المحور X 0rem
- `.border-x-0.6` - الحدود المحور X 0rem
- `.border-x-0.5` - الحدود المحور X 0rem
- `.border-x-0.4` - الحدود المحور X 0rem
- `.border-x-0.3` - الحدود المحور X 0rem
- `.border-x-0.2` - الحدود المحور السيني 0.2rem
- `.border-x-0.1` - الحدود المحور السيني 0.1rem
- `.border-x-0` - الحدود المحور X 0rem
- `.hover:border-x-2` - الحدود X-Axis 2rem عند التحويم
- `.hover:border-x-1.5` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-1` - الحدود X-Axis 1rem عند التمرير
- `.hover:border-x-0.9` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.8` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.7` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.6` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.5` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.4` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.3` - حدود المحور السيني 0rem عند التمرير
- `.hover:border-x-0.2` - حدود المحور X 0.2rem عند التحويم
- `.hover:border-x-0.1` - حدود المحور X 0.1rem عند التحويم
- `.hover:border-x-0` - حدود المحور السيني 0rem عند التمرير

#### Border Y-Axis

- `.border-y-2` - الحدود المحور ص 2rem
- `.border-y-1.5` - الحدود المحور ص 0rem
- `.border-y-1` - الحدود المحور ص 1rem
- `.border-y-0.9` - الحدود المحور ص 0rem
- `.border-y-0.8` - الحدود المحور ص 0rem
- `.border-y-0.7` - الحدود المحور ص 0rem
- `.border-y-0.6` - الحدود المحور ص 0rem
- `.border-y-0.5` - الحدود المحور Y 0.5rem
- `.border-y-0.4` - الحدود المحور ص 0rem
- `.border-y-0.3` - الحدود المحور ص 0rem
- `.border-y-0.2` - الحدود المحور Y 0.2rem
- `.border-y-0.1` - الحدود المحور Y 0.1rem
- `.border-y-0` - الحدود المحور ص 0rem
- `.hover:border-y-2` - حدود المحور Y 2rem عند التحويم
- `.hover:border-y-1.5` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-1` - حدود المحور Y 1rem عند التمرير
- `.hover:border-y-0.9` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.8` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.7` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.6` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.5` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.4` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.3` - حدود المحور Y 0rem عند التمرير
- `.hover:border-y-0.2` - حدود المحور Y 0.2rem عند التحويم
- `.hover:border-y-0.1` - حدود المحور Y 0.1rem عند التحويم
- `.hover:border-y-0` - حدود المحور Y 0rem عند التمرير

### Border Radius

#### Border Radius All

- `.hover:rounded-5` - نصف قطر الحدود كل 5rem عند التحويم
- `.hover:rounded-4.5` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-4` - نصف قطر الحدود الكل 4rem عند التحويم
- `.hover:rounded-3.5` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-3` - نصف قطر الحدود الكل 3rem عند التحويم
- `.hover:rounded-2.5` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-2` - نصف قطر الحدود الكل 2rem عند التحويم
- `.hover:rounded-1.5` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-1` - نصف قطر الحدود الكل 1rem عند التمرير
- `.hover:rounded-0.9` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.8` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.7` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.6` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.5` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.4` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.3` - نصف قطر الحدود الكل 0rem عند التمرير
- `.hover:rounded-0.2` - نصف قطر الحدود الكل 0.2rem عند التمرير
- `.hover:rounded-0.1` - نصف قطر الحدود الكل 0.1rem عند التمرير
- `.hover:rounded-0` - نصف قطر الحدود الكل 0rem عند التمرير
- `.rounded-5` - نصف قطر الحدود كل 5rem
- `.rounded-4.5` - نصف قطر الحدود الكل 0rem
- `.rounded-4` - نصف قطر الحدود الكل 4rem
- `.rounded-3.5` - نصف قطر الحدود الكل 0rem
- `.rounded-3` - نصف قطر الحدود الكل 3rem
- `.rounded-2.5` - نصف قطر الحدود الكل 0rem
- `.rounded-2` - نصف قطر الحدود الكل 2rem
- `.rounded-1.5` - نصف قطر الحدود الكل 0rem
- `.rounded-1` - نصف قطر الحدود الكل 1rem
- `.rounded-0.9` - نصف قطر الحدود الكل 0rem
- `.rounded-0.8` - نصف قطر الحدود الكل 0rem
- `.rounded-0.7` - نصف قطر الحدود الكل 0rem
- `.rounded-0.6` - نصف قطر الحدود الكل 0rem
- `.rounded-0.5` - نصف قطر الحدود الكل 0rem
- `.rounded-0.4` - نصف قطر الحدود الكل 0rem
- `.rounded-0.3` - نصف قطر الحدود الكل 0rem
- `.rounded-0.2` - نصف قطر الحدود الكل 0.2rem
- `.rounded-0.1` - نصف قطر الحدود الكل 0.1rem
- `.rounded-0` - نصف قطر الحدود الكل 0rem

#### Border Radius Bottom Left

- `.hover:rounded-bl-5` - نصف قطر الحدود أسفل اليسار 5ريم عند التحويم
- `.hover:rounded-bl-4.5` - نصف قطر الحدود أسفل اليسار 0rem عند التمرير
- `.hover:rounded-bl-4` - نصف قطر الحدود أسفل اليسار 4ريم عند التحويم
- `.hover:rounded-bl-3.5` - نصف قطر الحدود أسفل اليسار 0rem عند التمرير
- `.hover:rounded-bl-3` - نصف قطر الحدود أسفل اليسار 3rem عند التمرير
- `.hover:rounded-bl-2.5` - نصف قطر الحدود أسفل اليسار 0rem عند التمرير
- `.hover:rounded-bl-2` - نصف قطر الحدود أسفل اليسار 2ريم عند التحويم
- `.hover:rounded-bl-1.5` - نصف قطر الحدود أسفل اليسار 0rem عند التمرير
- `.hover:rounded-bl-1` - نصف قطر الحدود أسفل اليسار 1ريم عند التمرير
- `.hover:rounded-bl-0.5` - نصف قطر الحدود أسفل اليسار 0.5ريم عند التحويم
- `.hover:rounded-bl-0` - نصف قطر الحدود أسفل اليسار 0rem عند التمرير
- `.rounded-bl-5` - نصف قطر الحدود أسفل اليسار 5ريم
- `.rounded-bl-4.5` - نصف قطر الحدود أسفل اليسار 0rem
- `.rounded-bl-4` - نصف قطر الحدود أسفل اليسار 4ريم
- `.rounded-bl-3.5` - نصف قطر الحدود أسفل اليسار 0rem
- `.rounded-bl-3` - نصف قطر الحدود أسفل اليسار 3rem
- `.rounded-bl-2.5` - نصف قطر الحدود أسفل اليسار 0rem
- `.rounded-bl-2` - نصف قطر الحدود أسفل اليسار 2rem
- `.rounded-bl-1.5` - نصف قطر الحدود أسفل اليسار 0rem
- `.rounded-bl-1` - نصف قطر الحدود أسفل اليسار 1rem
- `.rounded-bl-0.5` - نصف قطر الحدود أسفل اليسار 0.5ريم
- `.rounded-bl-0` - نصف قطر الحدود أسفل اليسار 0rem

#### Border Radius Bottom Right

- `.hover:rounded-br-5` - نصف قطر الحدود أسفل اليمين 5ريم عند التحويم
- `.hover:rounded-br-4.5` - نصف قطر الحدود أسفل اليمين 0rem عند التمرير
- `.hover:rounded-br-4` - نصف قطر الحدود أسفل اليمين 4ريم عند التحويم
- `.hover:rounded-br-3.5` - نصف قطر الحدود أسفل اليمين 0rem عند التمرير
- `.hover:rounded-br-3` - نصف قطر الحدود أسفل اليمين 3rem عند التمرير
- `.hover:rounded-br-2.5` - نصف قطر الحدود أسفل اليمين 0rem عند التمرير
- `.hover:rounded-br-2` - نصف قطر الحدود أسفل اليمين 2ريم عند التحويم
- `.hover:rounded-br-1.5` - نصف قطر الحدود أسفل اليمين 0rem عند التمرير
- `.hover:rounded-br-1` - نصف قطر الحدود أسفل اليمين 1ريم عند التمرير
- `.hover:rounded-br-0.5` - نصف قطر الحدود أسفل اليمين 0.5 ريم عند التحويم
- `.hover:rounded-br-0` - نصف قطر الحدود أسفل اليمين 0rem عند التمرير
- `.rounded-br-5` - نصف قطر الحدود أسفل اليمين 5ريم
- `.rounded-br-4.5` - نصف قطر الحدود أسفل اليمين 0rem
- `.rounded-br-4` - نصف قطر الحدود أسفل اليمين 4rem
- `.rounded-br-3.5` - نصف قطر الحدود أسفل اليمين 0rem
- `.rounded-br-3` - نصف قطر الحدود أسفل اليمين 3rem
- `.rounded-br-2.5` - نصف قطر الحدود أسفل اليمين 0rem
- `.rounded-br-2` - نصف قطر الحدود أسفل اليمين 2rem
- `.rounded-br-1.5` - نصف قطر الحدود أسفل اليمين 0rem
- `.rounded-br-1` - نصف قطر الحدود أسفل اليمين 1rem
- `.rounded-br-0.5` - نصف قطر الحدود أسفل اليمين 0.5ريم
- `.rounded-br-0` - نصف قطر الحدود أسفل اليمين 0rem

#### Border Radius Top Left

- `.hover:rounded-tl-5` - نصف قطر الحدود أعلى اليسار 5ريم عند التحويم
- `.hover:rounded-tl-4.5` - نصف قطر الحدود أعلى اليسار 0rem عند التمرير
- `.hover:rounded-tl-4` - نصف قطر الحدود أعلى اليسار 4ريم عند التحويم
- `.hover:rounded-tl-3.5` - نصف قطر الحدود أعلى اليسار 0rem عند التمرير
- `.hover:rounded-tl-3` - نصف قطر الحدود أعلى اليسار 3rem عند التمرير
- `.hover:rounded-tl-2.5` - نصف قطر الحدود أعلى اليسار 0rem عند التمرير
- `.hover:rounded-tl-2` - نصف قطر الحدود أعلى اليسار 2ريم عند التحويم
- `.hover:rounded-tl-1.5` - نصف قطر الحدود أعلى اليسار 0rem عند التمرير
- `.hover:rounded-tl-1` - نصف قطر الحدود أعلى اليسار 1ريم عند التحويم
- `.hover:rounded-tl-0.5` - نصف قطر الحدود أعلى اليسار 0.5ريم عند التمرير
- `.hover:rounded-tl-0` - نصف قطر الحدود أعلى اليسار 0rem عند التمرير
- `.rounded-tl-5` - نصف قطر الحدود أعلى اليسار 5rem
- `.rounded-tl-4.5` - نصف قطر الحدود أعلى اليسار 0rem
- `.rounded-tl-4` - نصف قطر الحدود أعلى اليسار 4rem
- `.rounded-tl-3.5` - نصف قطر الحدود أعلى اليسار 0rem
- `.rounded-tl-3` - نصف قطر الحدود أعلى اليسار 3rem
- `.rounded-tl-2.5` - نصف قطر الحدود أعلى اليسار 0rem
- `.rounded-tl-2` - نصف قطر الحدود أعلى اليسار 2rem
- `.rounded-tl-1.5` - نصف قطر الحدود أعلى اليسار 0rem
- `.rounded-tl-1` - نصف قطر الحدود أعلى اليسار 1rem
- `.rounded-tl-0.5` - نصف قطر الحدود أعلى اليسار 0.5ريم
- `.rounded-tl-0` - نصف قطر الحدود أعلى اليسار 0rem

#### Border Radius Top Right

- `.hover:rounded-tr-5` - نصف قطر الحدود أعلى اليمين 5ريم عند التحويم
- `.hover:rounded-tr-4.5` - نصف قطر الحدود أعلى اليمين 0rem عند التمرير
- `.hover:rounded-tr-4` - نصف قطر الحدود العلوي الأيمن 4ريم عند التحويم
- `.hover:rounded-tr-3.5` - نصف قطر الحدود أعلى اليمين 0rem عند التمرير
- `.hover:rounded-tr-3` - نصف قطر الحدود أعلى اليمين 3rem عند التمرير
- `.hover:rounded-tr-2.5` - نصف قطر الحدود أعلى اليمين 0rem عند التمرير
- `.hover:rounded-tr-2` - نصف قطر الحدود العلوي الأيمن 2ريم عند التحويم
- `.hover:rounded-tr-1.5` - نصف قطر الحدود أعلى اليمين 0rem عند التمرير
- `.hover:rounded-tr-1` - نصف قطر الحدود أعلى اليمين 1ريم عند التمرير
- `.hover:rounded-tr-0.5` - نصف قطر الحدود العلوي الأيمن 0.5ريم عند التحويم
- `.hover:rounded-tr-0` - نصف قطر الحدود أعلى اليمين 0rem عند التمرير
- `.rounded-tr-5` - نصف قطر الحدود أعلى اليمين 5rem
- `.rounded-tr-4.5` - نصف قطر الحدود أعلى اليمين 0rem
- `.rounded-tr-4` - نصف قطر الحدود أعلى اليمين 4rem
- `.rounded-tr-3.5` - نصف قطر الحدود أعلى اليمين 0rem
- `.rounded-tr-3` - نصف قطر الحدود أعلى اليمين 3rem
- `.rounded-tr-2.5` - نصف قطر الحدود أعلى اليمين 0rem
- `.rounded-tr-2` - نصف قطر الحدود أعلى اليمين 2rem
- `.rounded-tr-1.5` - نصف قطر الحدود أعلى اليمين 0rem
- `.rounded-tr-1` - نصف قطر الحدود أعلى اليمين 1rem
- `.rounded-tr-0.5` - نصف قطر الحدود أعلى اليمين 0.5ريم
- `.rounded-tr-0` - نصف قطر الحدود أعلى اليمين 0rem

## Effects

### Box Shadow

#### Box Shadow All

- `.hover:shadow-5` - Box Shadow All 5rem عند التحويم
- `.hover:shadow-5-1` - Box Shadow All 5-1rem عند التحويم
- `.hover:shadow-4` - Box Shadow All 4rem عند التحويم
- `.hover:shadow-4-1` - Box Shadow All 4-1rem عند التحويم
- `.hover:shadow-3` - Box Shadow All 3rem عند التحويم
- `.hover:shadow-3-1` - Box Shadow All 3-1rem عند التحويم
- `.hover:shadow-2` - Box Shadow All 2rem عند التحويم
- `.hover:shadow-2-1` - Box Shadow All 2-1rem عند التحويم
- `.hover:shadow-1` - Box Shadow All 1rem عند التحويم
- `.hover:shadow-1-1` - Box Shadow All 1-1rem عند التحويم
- `.hover:shadow-none` - Box Shadow الكل لا شيء عند التمرير
- `.shadow-5` - صندوق الظل الكل 5ريم
- `.shadow-5-1` - صندوق الظل الكل 5-1ريم
- `.shadow-4` - صندوق الظل الكل 4ريم
- `.shadow-4-1` - صندوق الظل الكل 4-1ريم
- `.shadow-3` - صندوق الظل الكل 3rem
- `.shadow-3-1` - صندوق الظل الكل 3-1ريم
- `.shadow-2` - صندوق الظل الكل 2rem
- `.shadow-2-1` - صندوق الظل الكل 2-1ريم
- `.shadow-1` - صندوق الظل الكل 1rem
- `.shadow-1-1` - صندوق الظل الكل 1-1ريم
- `.shadow-none` - صندوق الظل الكل لا شيء

#### Box Shadow Bottom

- `.hover:shadow-b-10` - صندوق الظل السفلي 10ريم عند التحويم
- `.hover:shadow-b-9` - Box Shadow Bottom 9rem عند التحويم
- `.hover:shadow-b-8` - Box Shadow Bottom 8rem عند التحويم
- `.hover:shadow-b-7` - صندوق الظل السفلي 7rem عند التحويم
- `.hover:shadow-b-6` - Box Shadow Bottom 6rem عند التحويم
- `.hover:shadow-b-5` - Box Shadow Bottom 5rem عند التحويم
- `.hover:shadow-b-4` - Box Shadow Bottom 4rem عند التحويم
- `.hover:shadow-b-3` - Box Shadow Bottom 3rem عند التحويم
- `.hover:shadow-b-2` - Box Shadow Bottom 2rem عند التحويم
- `.hover:shadow-b-1` - Box Shadow Bottom 1rem عند التحويم
- `.shadow-b-10` - صندوق الظل السفلي 10ريم
- `.shadow-b-9` - صندوق الظل السفلي 9rem
- `.shadow-b-8` - صندوق الظل السفلي 8ريم
- `.shadow-b-7` - صندوق الظل السفلي 7ريم
- `.shadow-b-6` - صندوق الظل السفلي 6ريم
- `.shadow-b-5` - صندوق الظل السفلي 5ريم
- `.shadow-b-4` - صندوق الظل السفلي 4ريم
- `.shadow-b-3` - صندوق الظل السفلي 3rem
- `.shadow-b-2` - صندوق الظل السفلي 2rem
- `.shadow-b-1` - صندوق الظل السفلي 1rem

#### Box Shadow Left

- `.hover:shadow-l-10` - Box Shadow Left 10rem عند التحويم
- `.hover:shadow-l-9` - Box Shadow Left 9rem عند التحويم
- `.hover:shadow-l-8` - Box Shadow Left 8rem عند التحويم
- `.hover:shadow-l-7` - Box Shadow Left 7rem عند التحويم
- `.hover:shadow-l-6` - Box Shadow Left 6rem عند التحويم
- `.hover:shadow-l-5` - Box Shadow Left 5rem عند التحويم
- `.hover:shadow-l-4` - Box Shadow Left 4rem عند التحويم
- `.hover:shadow-l-3` - Box Shadow Left 3rem عند التحويم
- `.hover:shadow-l-2` - Box Shadow Left 2rem عند التحويم
- `.hover:shadow-l-1` - Box Shadow Left 1rem عند التحويم
- `.shadow-l-10` - صندوق الظل الأيسر 10ريم
- `.shadow-l-9` - صندوق الظل الأيسر 9rem
- `.shadow-l-8` - صندوق الظل الأيسر 8ريم
- `.shadow-l-7` - صندوق الظل الأيسر 7ريم
- `.shadow-l-6` - صندوق الظل الأيسر 6ريم
- `.shadow-l-5` - صندوق الظل الأيسر 5ريم
- `.shadow-l-4` - صندوق الظل الأيسر 4ريم
- `.shadow-l-3` - صندوق الظل الأيسر 3rem
- `.shadow-l-2` - صندوق الظل الأيسر 2ريم
- `.shadow-l-1` - صندوق الظل الأيسر 1ريم

#### Box Shadow Right

- `.hover:shadow-r-10` - Box Shadow يمين 10ريم عند التحويم
- `.hover:shadow-r-9` - Box Shadow Right 9rem عند التحويم
- `.hover:shadow-r-8` - Box Shadow Right 8rem عند التحويم
- `.hover:shadow-r-7` - Box Shadow Right 7rem عند التحويم
- `.hover:shadow-r-6` - Box Shadow Right 6rem عند التحويم
- `.hover:shadow-r-5` - Box Shadow Right 5rem عند التحويم
- `.hover:shadow-r-4` - Box Shadow Right 4rem عند التحويم
- `.hover:shadow-r-3` - Box Shadow Right 3rem عند التحويم
- `.hover:shadow-r-2` - Box Shadow Right 2rem عند التحويم
- `.hover:shadow-r-1` - Box Shadow Right 1rem عند التحويم
- `.shadow-r-10` - صندوق الظل الأيمن 10ريم
- `.shadow-r-9` - صندوق الظل الأيمن 9rem
- `.shadow-r-8` - صندوق الظل الأيمن 8ريم
- `.shadow-r-7` - صندوق الظل الأيمن 7ريم
- `.shadow-r-6` - صندوق الظل الأيمن 6ريم
- `.shadow-r-5` - صندوق الظل الأيمن 5ريم
- `.shadow-r-4` - صندوق الظل الأيمن 4ريم
- `.shadow-r-3` - صندوق الظل الأيمن 3rem
- `.shadow-r-2` - صندوق الظل الأيمن 2ريم
- `.shadow-r-1` - صندوق الظل الأيمن 1rem

#### Box Shadow Top

- `.hover:shadow-t-10` - Box Shadow Top 10rem عند التحويم
- `.hover:shadow-t-9` - Box Shadow Top 9rem عند التحويم
- `.hover:shadow-t-8` - Box Shadow Top 8rem عند التحويم
- `.hover:shadow-t-7` - Box Shadow Top 7rem عند التحويم
- `.hover:shadow-t-6` - Box Shadow Top 6rem عند التحويم
- `.hover:shadow-t-5` - Box Shadow Top 5rem عند التحويم
- `.hover:shadow-t-4` - Box Shadow Top 4rem عند التحويم
- `.hover:shadow-t-3` - Box Shadow Top 3rem عند التحويم
- `.hover:shadow-t-2` - Box Shadow Top 2rem عند التحويم
- `.hover:shadow-t-1` - Box Shadow Top 1rem عند التحويم
- `.shadow-t-10` - بوكس شادو توب 10ريم
- `.shadow-t-9` - صندوق الظل الأعلى 9rem
- `.shadow-t-8` - بوكس شادو توب 8ريم
- `.shadow-t-7` - بوكس شادو توب 7ريم
- `.shadow-t-6` - بوكس شادو توب 6ريم
- `.shadow-t-5` - صندوق الظل الأعلى 5rem
- `.shadow-t-4` - بوكس شادو توب 4ريم
- `.shadow-t-3` - صندوق الظل الأعلى 3rem
- `.shadow-t-2` - صندوق الظل الأعلى 2rem
- `.shadow-t-1` - صندوق الظل الأعلى 1rem

#### Box Shadow X-Axis

- `.hover:shadow-x-10` - Box Shadow X-Axis 10rem عند التحويم
- `.hover:shadow-x-9` - Box Shadow X-Axis 9rem عند التحويم
- `.hover:shadow-x-8` - Box Shadow X-Axis 8rem عند التحويم
- `.hover:shadow-x-7` - Box Shadow X-Axis 7rem عند التحويم
- `.hover:shadow-x-6` - Box Shadow X-Axis 6rem عند التحويم
- `.hover:shadow-x-5` - Box Shadow X-Axis 5rem عند التحويم
- `.hover:shadow-x-4` - Box Shadow X-Axis 4rem عند التحويم
- `.hover:shadow-x-3` - Box Shadow X-Axis 3rem عند التحويم
- `.hover:shadow-x-2` - Box Shadow X-Axis 2rem عند التحويم
- `.hover:shadow-x-1` - Box Shadow X-Axis 1rem عند التحويم
- `.shadow-x-10` - صندوق الظل X-Axis 10rem
- `.shadow-x-9` - صندوق الظل X-Axis 9rem
- `.shadow-x-8` - صندوق الظل X-Axis 8rem
- `.shadow-x-7` - صندوق الظل X-Axis 7rem
- `.shadow-x-6` - مربع الظل المحور السيني 6rem
- `.shadow-x-5` - صندوق الظل X-Axis 5rem
- `.shadow-x-4` - مربع الظل المحور السيني 4rem
- `.shadow-x-3` - مربع الظل المحور السيني 3rem
- `.shadow-x-2` - مربع الظل المحور السيني 2rem
- `.shadow-x-1` - مربع الظل المحور السيني 1rem

#### Box Shadow Y-Axis

- `.hover:shadow-y-10` - Box Shadow Y-Axis 10rem عند التحويم
- `.hover:shadow-y-9` - Box Shadow Y-Axis 9rem عند التحويم
- `.hover:shadow-y-8` - Box Shadow Y-Axis 8rem عند التحويم
- `.hover:shadow-y-7` - Box Shadow Y-Axis 7rem عند التحويم
- `.hover:shadow-y-6` - Box Shadow Y-Axis 6rem عند التحويم
- `.hover:shadow-y-5` - Box Shadow Y-Axis 5rem عند التحويم
- `.hover:shadow-y-4` - Box Shadow Y-Axis 4rem عند التحويم
- `.hover:shadow-y-3` - Box Shadow Y-Axis 3rem عند التحويم
- `.hover:shadow-y-2` - Box Shadow Y-Axis 2rem عند التحويم
- `.hover:shadow-y-1` - Box Shadow Y-Axis 1rem عند التحويم
- `.shadow-y-10` - صندوق الظل Y-Axis 10rem
- `.shadow-y-9` - صندوق الظل المحور Y 9rem
- `.shadow-y-8` - صندوق الظل Y-Axis 8rem
- `.shadow-y-7` - صندوق الظل Y-Axis 7rem
- `.shadow-y-6` - صندوق الظل المحور Y 6rem
- `.shadow-y-5` - صندوق الظل Y-Axis 5rem
- `.shadow-y-4` - صندوق الظل المحور Y 4rem
- `.shadow-y-3` - صندوق الظل المحور Y 3rem
- `.shadow-y-2` - صندوق الظل المحور Y 2rem
- `.shadow-y-1` - صندوق الظل المحور Y 1rem

### Blur

- `.blur-5` - طمس 5rem
- `.blur-4` - طمس 4ريم
- `.blur-3` - طمس 3rem
- `.blur-2` - طمس 2rem
- `.blur-1` - طمس 1rem
- `.blur-0` - طمس 0rem
- `.hover:blur-5` - طمس 5rem عند التمرير
- `.hover:blur-4` - طمس 4rem عند التمرير
- `.hover:blur-3` - طمس 3rem عند التمرير
- `.hover:blur-2` - طمس 2rem عند التمرير
- `.hover:blur-1` - طمس 1rem عند التمرير
- `.hover:blur-0` - طمس 0rem عند التمرير

### Opacity

- `.hover:opacity-100` - العتامة 100٪ عند التمرير
- `.hover:opacity-95` - التعتيم 95٪ عند التمرير
- `.hover:opacity-90` - التعتيم 90٪ عند التمرير
- `.hover:opacity-85` - التعتيم 85٪ عند التمرير
- `.hover:opacity-80` - التعتيم 80٪ عند التمرير
- `.hover:opacity-75` - العتامة 75٪ عند التمرير
- `.hover:opacity-70` - التعتيم 70٪ عند التمرير
- `.hover:opacity-65` - العتامة 65% عند التمرير
- `.hover:opacity-60` - التعتيم 60٪ عند التمرير
- `.hover:opacity-55` - التعتيم 55٪ عند التمرير
- `.hover:opacity-50` - التعتيم 50٪ عند التمرير
- `.hover:opacity-45` - العتامة 45٪ عند التمرير
- `.hover:opacity-40` - العتامة 40٪ عند التمرير
- `.hover:opacity-35` - العتامة 35% عند التمرير
- `.hover:opacity-30` - التعتيم 30٪ عند التمرير
- `.hover:opacity-25` - العتامة 25% عند التمرير
- `.hover:opacity-20` - العتامة 20٪ عند التمرير
- `.hover:opacity-15` - العتامة 15% عند التمرير
- `.hover:opacity-10` - العتامة 10٪ عند التمرير
- `.hover:opacity-5` - العتامة 5% عند التمرير
- `.hover:opacity-0` - العتامة 0% عند التمرير
- `.opacity-100` - التعتيم 100%
- `.opacity-95` - التعتيم 95%
- `.opacity-90` - التعتيم 90%
- `.opacity-85` - التعتيم 85%
- `.opacity-80` - التعتيم 80%
- `.opacity-75` - التعتيم 75%
- `.opacity-70` - التعتيم 70%
- `.opacity-65` - التعتيم 65%
- `.opacity-60` - التعتيم 60%
- `.opacity-55` - التعتيم 55%
- `.opacity-50` - التعتيم 50%
- `.opacity-45` - العتامة 45%
- `.opacity-40` - التعتيم 40%
- `.opacity-35` - التعتيم 35%
- `.opacity-30` - التعتيم 30%
- `.opacity-25` - العتامة 25%
- `.opacity-20` - التعتيم 20%
- `.opacity-15` - العتامة 15%
- `.opacity-10` - العتامة 10%
- `.opacity-5` - العتامة 5%
- `.opacity-0` - العتامة 0%

## Transforms

### Rotate

- `.hover:rotate-180` - تدوير 180ريم عند التحويم
- `.hover:rotate-135` - قم بتدوير 135 ريم عند التحويم
- `.hover:rotate-90` - تدوير 90rem عند التحويم
- `.hover:rotate-45` - تدوير 45ريم عند التحويم
- `.hover:rotate-12` - قم بتدوير 12 ريم عند التحويم
- `.hover:rotate-9` - قم بتدوير 9rem عند التمرير
- `.hover:rotate-6` - قم بتدوير 6rem عند التمرير
- `.hover:rotate-3` - قم بتدوير 3rem عند التمرير
- `.hover:rotate-0` - تدوير 0rem عند التمرير
- `.rotate-180` - تدوير 180ريم
- `.rotate-135` - تدوير 135ريم
- `.rotate-90` - تدوير 90ريم
- `.rotate-45` - تدوير 45ريم
- `.rotate-12` - تدوير 12ريم
- `.rotate-9` - تدوير 9ريم
- `.rotate-6` - تدوير 6ريم
- `.rotate-3` - تدوير 3ريم
- `.rotate-0` - تدوير 0ريم

##### Negative Rotate

- `.-rotate-180` - تدوير سلبي 180ريم
- `.-rotate-135` - تدوير سلبي 135rem
- `.-rotate-90` - تدوير سلبي 90rem
- `.-rotate-45` - تدوير سلبي 45rem
- `.-rotate-12` - تدوير سلبي 12rem
- `.-rotate-9` - تدوير سلبي 9rem
- `.-rotate-6` - تدوير سلبي 6rem
- `.-rotate-3` - تدوير سلبي 3rem
- `.hover:-rotate-180` - تدوير سلبي 180ريم عند التحويم
- `.hover:-rotate-135` - تدوير سلبي 135rem عند التحويم
- `.hover:-rotate-90` - تدوير سلبي 90rem عند التحويم
- `.hover:-rotate-45` - تدوير سلبي 45rem عند التحويم
- `.hover:-rotate-12` - تدوير سلبي 12rem عند التمرير
- `.hover:-rotate-9` - تدوير سلبي 9rem عند التمرير
- `.hover:-rotate-6` - تدوير سلبي 6rem عند التمرير
- `.hover:-rotate-3` - تدوير سلبي 3rem عند التمرير

### Skew

#### Skew X-Axis

- `.hover:skew-x-12` - انحراف المحور X 12rem عند التحويم
- `.hover:skew-x-6` - انحراف المحور السيني 6rem عند التحويم
- `.hover:skew-x-3` - انحراف المحور السيني 3rem عند التحويم
- `.hover:skew-x-0` - انحراف المحور السيني 0rem عند التمرير
- `.skew-x-12` - انحراف المحور X 12rem
- `.skew-x-6` - انحراف المحور السيني 6rem
- `.skew-x-3` - انحراف المحور السيني 3rem
- `.skew-x-0` - انحراف المحور السيني 0rem

##### Negative Skew X-Axis

- `.-skew-x-12` - الانحراف السلبي للمحور السيني 12rem
- `.-skew-x-6` - الانحراف السلبي للمحور السيني 6rem
- `.-skew-x-3` - الانحراف السلبي للمحور السيني 3rem
- `.hover:-skew-x-12` - الانحراف السلبي للمحور X 12rem عند التمرير
- `.hover:-skew-x-6` - الانحراف السلبي للمحور السيني 6rem عند التمرير
- `.hover:-skew-x-3` - الانحراف السلبي للمحور السيني 3rem عند التمرير

#### Skew Y-Axis

- `.hover:skew-y-12` - انحراف المحور Y 12rem عند التحويم
- `.hover:skew-y-6` - انحراف المحور Y 6rem عند التحويم
- `.hover:skew-y-3` - انحراف المحور Y 3rem عند التمرير
- `.hover:skew-y-0` - انحراف المحور Y 0rem عند التحويم
- `.skew-y-12` - انحراف المحور Y 12rem
- `.skew-y-6` - Skew Y-Axis 6rem
- `.skew-y-3` - انحراف المحور Y 3rem
- `.skew-y-0` - Skew Y-Axis 0rem

##### Negative Skew Y-Axis

- `.-skew-y-12` - الانحراف السلبي للمحور Y 12rem
- `.-skew-y-6` - الانحراف السلبي للمحور Y 6rem
- `.-skew-y-3` - الانحراف السلبي للمحور Y 3rem
- `.hover:-skew-y-12` - الانحراف السلبي للمحور Y 12rem عند التمرير
- `.hover:-skew-y-6` - الانحراف السلبي للمحور Y 6rem عند التمرير
- `.hover:-skew-y-3` - الانحراف السلبي للمحور Y 3rem عند التمرير

### Translate

- `.hover:translate-50` - ترجمة 50rem عند التحويم
- `.hover:translate-25` - ترجمة 25rem عند التحويم
- `.translate-50` - ترجمة 50ريم
- `.translate-25` - ترجمة 25ريم

##### Negative Translate

- `.-translate-50` - ترجمة سلبية 50ريم
- `.-translate-25` - ترجمة سلبية 25rem
- `.hover:-translate-50` - ترجمة سلبية 50rem عند التحويم
- `.hover:-translate-25` - ترجمة سلبية 25rem عند التحويم

#### Translate X-Axis

- `.hover:translate-x-50` - ترجمة المحور X 50rem عند التمرير
- `.hover:translate-x-25` - ترجمة المحور X 25rem عند التحويم
- `.hover:translate-x-2` - ترجمة المحور X 2rem عند التمرير
- `.hover:translate-x-1.5` - ترجمة المحور السيني 0rem عند التمرير
- `.hover:translate-x-1` - ترجمة المحور X 1rem عند التمرير
- `.hover:translate-x-0.5` - ترجمة المحور X 0.5rem عند التمرير
- `.hover:translate-x-0` - ترجمة المحور السيني 0rem عند التمرير
- `.translate-x-50` - ترجمة المحور السيني 50rem
- `.translate-x-25` - ترجمة المحور السيني 25rem
- `.translate-x-2` - ترجمة المحور X 2rem
- `.translate-x-1.5` - ترجمة المحور السيني 0rem
- `.translate-x-1` - ترجمة المحور السيني 1rem
- `.translate-x-0.5` - ترجمة المحور السيني 0.5rem
- `.translate-x-0` - ترجمة المحور السيني 0rem

##### Negative Translate X-Axis

- `.-translate-x-50` - ترجمة سلبية للمحور X 50rem
- `.-translate-x-25` - ترجمة سلبية للمحور السيني 25rem
- `.-translate-x-2` - ترجمة سلبية للمحور X 2rem
- `.-translate-x-1.5` - ترجمة سلبية للمحور X 1.5rem
- `.-translate-x-1` - ترجمة سلبية للمحور X 1rem
- `.-translate-x-0.5` - ترجمة سلبية للمحور X 0.5rem
- `.hover:-translate-x-50` - ترجمة سلبية للمحور X 50rem عند التمرير
- `.hover:-translate-x-25` - ترجمة سلبية للمحور X 25rem عند التمرير
- `.hover:-translate-x-2` - ترجمة سلبية للمحور X 2rem عند التمرير
- `.hover:-translate-x-1.5` - ترجمة سلبية للمحور X 1.5rem عند التمرير
- `.hover:-translate-x-1` - ترجمة سلبية للمحور X 1rem عند التمرير
- `.hover:-translate-x-0.5` - ترجمة سلبية للمحور X 0.5rem عند التمرير

#### Translate Y-Axis

- `.hover:translate-y-50` - ترجمة المحور Y 50rem عند التمرير
- `.hover:translate-y-25` - ترجمة المحور Y 25rem عند التمرير
- `.hover:translate-y-2` - ترجمة المحور Y 2rem عند التمرير
- `.hover:translate-y-1.5` - ترجمة المحور Y 0rem عند التمرير
- `.hover:translate-y-1` - ترجمة المحور Y 1rem عند التمرير
- `.hover:translate-y-0.5` - ترجمة المحور Y 0.5rem عند التمرير
- `.hover:translate-y-0` - ترجمة المحور Y 0rem عند التمرير
- `.translate-y-50` - ترجمة المحور Y 50rem
- `.translate-y-25` - ترجمة المحور Y 25rem
- `.translate-y-2` - ترجمة المحور Y 2rem
- `.translate-y-1.5` - ترجمة المحور Y 0rem
- `.translate-y-1` - ترجمة المحور Y 1rem
- `.translate-y-0.5` - ترجمة المحور Y 0.5rem
- `.translate-y-0` - ترجمة المحور Y 0rem

##### Negative Translate Y-Axis

- `.-translate-y-50` - ترجمة سلبية للمحور Y 50rem
- `.-translate-y-25` - ترجمة سلبية للمحور Y 25rem
- `.-translate-y-2` - ترجمة سلبية للمحور Y 2rem
- `.-translate-y-1.5` - ترجمة سلبية للمحور Y 1.5rem
- `.-translate-y-1` - ترجمة سلبية للمحور Y 1rem
- `.-translate-y-0.5` - ترجمة سلبية للمحور Y 0.5rem
- `.hover:-translate-y-50` - ترجمة سلبية للمحور Y 50rem عند التمرير
- `.hover:-translate-y-25` - ترجمة سلبية للمحور Y 25rem عند التمرير
- `.hover:-translate-y-2` - ترجمة سلبية للمحور Y 2rem عند التمرير
- `.hover:-translate-y-1.5` - ترجمة سلبية للمحور Y 1.5rem عند التمرير
- `.hover:-translate-y-1` - ترجمة سلبية للمحور Y 1rem عند التمرير
- `.hover:-translate-y-0.5` - ترجمة سلبية للمحور Y 0.5rem عند التمرير

### Zoom

- `.hover:zoom` - تكبير عند التمرير
- `.hover:zoom-2` - تكبير 2rem عند التمرير
- `.hover:zoom-1.5` - تكبير 1.5ريم عند التحويم
- `.zoom` - تكبير
- `.zoom-2` - تكبير 2ريم
- `.zoom-1.5` - تكبير 1.5

## Colors

### Black

- `.black` - أسود

### Dark

- `.dark` - مظلم

### Light

- `.light` - ضوء

### Transparent

- `.transparent` - شفاف

## Interactivity

### Cursor

- `.cursor-alias` - الاسم المستعار للمؤشر
- `.cursor-all-scroll` - المؤشر للتمرير الشامل
- `.cursor-auto` - المؤشر التلقائي
- `.cursor-cell` - خلية المؤشر
- `.cursor-col-resize` - تغيير حجم المؤشر
- `.cursor-context-menu` - قائمة سياق المؤشر
- `.cursor-copy` - نسخة المؤشر
- `.cursor-crosshair` - تقاطع المؤشر
- `.cursor-default` - المؤشر
- `.cursor-e-resize` - تغيير حجم المؤشر الإلكتروني
- `.cursor-ew-resize` - تغيير حجم المؤشر
- `.cursor-grab` - الاستيلاء على المؤشر
- `.cursor-grabbing` - الاستيلاء على المؤشر
- `.cursor-help` - مساعدة المؤشر
- `.cursor-move` - تحرك المؤشر
- `.cursor-n-resize` - تغيير حجم المؤشر
- `.cursor-ne-resize` - تغيير حجم المؤشر
- `.cursor-nesw-resize` - تغيير حجم المؤشر
- `.cursor-no-drop` - عدم إسقاط المؤشر
- `.cursor-none` - المؤشر لا شيء
- `.cursor-not-allowed` - المؤشر غير مسموح به
- `.cursor-ns-resize` - المؤشر ns-تغيير الحجم
- `.cursor-nw-resize` - تغيير حجم المؤشر
- `.cursor-nwse-resize` - تغيير حجم المؤشر
- `.cursor-pointer` - مؤشر المؤشر
- `.cursor-progress` - تقدم المؤشر
- `.cursor-row-resize` - تغيير حجم صف المؤشر
- `.cursor-s-resize` - تغيير حجم المؤشر
- `.cursor-se-resize` - تغيير حجم المؤشر
- `.cursor-sw-resize` - تغيير حجم المؤشر
- `.cursor-text` - نص المؤشر
- `.cursor-vertical-text` - المؤشر العمودي النص
- `.cursor-w-resize` - تغيير حجم المؤشر
- `.cursor-wait` - انتظر المؤشر
- `.cursor-zoom-in` - تكبير المؤشر
- `.cursor-zoom-out` - تصغير المؤشر

### Disabled

- `.disabled` - عاجز

### Resize

- `.resize` - تغيير الحجم
- `.resize-none` - تغيير الحجم لا شيء
- `.resize-x` - تغيير الحجم ×
- `.resize-y` - تغيير الحجم ذ

### Select

- `.select-auto` - حدد تلقائي
- `.select-none` - حدد لا شيء

## Misc

### Content

- `.content-3` - المحتوى 3rem
- `.content-3-bg` - المحتوى 3-bgrem
- `.content-2` - المحتوى 2ريم
- `.content-2-bg` - المحتوى 2-bgrem
- `.content-2-text` - المحتوى 2-النص
- `.content-1` - المحتوى 1ريم
- `.content-1-bg` - المحتوى 1-bgrem
- `.content-1-text` - المحتوى 1-النص
- `.hover:content-3-bg` - المحتوى 3-bgrem عند التحويم
- `.hover:content-2-bg` - المحتوى 2-bgrem عند التحويم
- `.hover:content-2-text` - المحتوى 2-textrem عند التمرير
- `.hover:content-1-bg` - المحتوى 1-bgrem عند التمرير
- `.hover:content-1-text` - المحتوى 1-نص عند التمرير

### Dir

- `.dir-ltr` - دير لتر
- `.dir-rtl` - أنت رتل

### Mse

- `.hover:mse-2` - Mse 2rem على التحويم
- `.hover:mse-1.5` - Mse 1.5rem عند التحويم
- `.hover:mse-1` - Mse 1rem عند التحويم
- `.hover:mse-0.5` - Mse 0.5rem عند التحويم
- `.hover:mse-0` - Mse 0rem عند التحويم
- `.mse-2` - مس 2ريم
- `.mse-1.5` - مس 1.5ريم
- `.mse-1` - مس 1ريم
- `.mse-0.5` - مس 0.5ريم
- `.mse-0` - السيدة 0ريم

### Other

##### Other - undefined

- `.hover:px-3.5` - أخرى عند التمرير على px 3.5

### Visibility

- `.hover:v-hide` - الرؤية مخفية عند التمرير
- `.hover:v-show` - الرؤية مرئية عند التمرير
- `.v-hide` - الرؤية مخفية
- `.v-show` - الرؤية مرئية

##### Visibility - Mobile (< 480px)

- `.hover:mobile:v-hide` - الرؤية مخفية عند التمرير على الهاتف المحمول
- `.hover:mobile:v-show` - إمكانية الرؤية عند التمرير على الهاتف المحمول
- `.mobile:v-hide` - الرؤية مخفية على الهاتف المحمول
- `.mobile:v-show` - إمكانية الرؤية على الهاتف المحمول

##### Visibility - Tablet (480px - 768px)

- `.hover:tablet:v-hide` - الرؤية مخفية عند التمرير على الجهاز اللوحي
- `.hover:tablet:v-show` - إمكانية الرؤية عند التمرير على الجهاز اللوحي
- `.tablet:v-hide` - الرؤية مخفية على الجهاز اللوحي
- `.tablet:v-show` - الرؤية مرئية على الكمبيوتر اللوحي

##### Visibility - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:v-hide` - الرؤية مخفية عند التمرير على الكمبيوتر اللوحي
- `.hover:tablet-pc:v-show` - إمكانية الرؤية عند التمرير على الكمبيوتر اللوحي
- `.tablet-pc:v-hide` - الرؤية مخفية على الكمبيوتر اللوحي
- `.tablet-pc:v-show` - إمكانية الرؤية على الكمبيوتر اللوحي

##### Visibility - Pc (992px - 1200px)

- `.hover:pc:v-hide` - الرؤية مخفية عند التمرير على جهاز الكمبيوتر
- `.hover:pc:v-show` - إمكانية الرؤية عند التمرير على جهاز الكمبيوتر
- `.pc:v-hide` - الرؤية مخفية على جهاز الكمبيوتر
- `.pc:v-show` - إمكانية الرؤية على جهاز الكمبيوتر

##### Visibility - Tv (> 1200px)

- `.hover:tv:v-hide` - الرؤية مخفية عند التمرير على شاشة التلفزيون
- `.hover:tv:v-show` - الرؤية مرئية عند التمرير على شاشة التلفزيون
- `.tv:v-hide` - الرؤية مخفية على شاشة التلفزيون
- `.tv:v-show` - الرؤية مرئية على شاشة التلفزيون

##### Visibility - Tablet Max (< 768px)

- `.hover:tablet-max:v-hide` - الرؤية مخفية عند التمرير على الجهاز اللوحي بحد أقصى
- `.hover:tablet-max:v-show` - الرؤية مرئية عند التمرير على الجهاز اللوحي بحد أقصى
- `.tablet-max:v-hide` - الرؤية مخفية على الجهاز اللوحي بحد أقصى
- `.tablet-max:v-show` - الرؤية مرئية على الكمبيوتر اللوحي بحد أقصى

##### Visibility - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:v-hide` - الرؤية مخفية عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.hover:tablet-pc-max:v-show` - الرؤية مرئية عند التمرير على الكمبيوتر اللوحي بحد أقصى
- `.tablet-pc-max:v-hide` - الرؤية مخفية على الكمبيوتر اللوحي كحد أقصى
- `.tablet-pc-max:v-show` - الرؤية مرئية على الكمبيوتر اللوحي كحد أقصى

##### Visibility - Pc Max (< 1200px)

- `.hover:pc-max:v-hide` - الرؤية مخفية عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.hover:pc-max:v-show` - الرؤية مرئية عند التمرير على جهاز الكمبيوتر كحد أقصى
- `.pc-max:v-hide` - الرؤية مخفية على جهاز الكمبيوتر كحد أقصى
- `.pc-max:v-show` - الرؤية مرئية على جهاز الكمبيوتر كحد أقصى

### Customization

يستخدم bClass متغيرات CSS للموضوعات:

- `--plainBg` - لون الخلفية عادي
- `--contentBg` - لون خلفية المحتوى
- `--contentBgPrimary` - خلفية المحتوى الأساسي
- `--contentBgSecondary` - خلفية المحتوى الثانوية
- `--contentTextPrimary` - لون النص الأساسي
- `--contentTextSecondary` - لون النص الثانوي
- `--headerBg` - لون خلفية الرأس

### License

> موزعة بموجب رخصة Bik العامة 2.0. راجع [LICENSE](./../../../LICENSE) لمزيد من المعلومات.
