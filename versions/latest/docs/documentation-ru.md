# bClass theme css

Комплексная библиотека для разработки интерфейсов к веб-сайтам и приложениям.

## Requirements

Вместе с этой библиотекой рекомендуется использовать `bClass theme js`, `bClass theme colors`, `bClass components`, `bClass animations` и `bClass media player`.

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

- `.container` - Контейнер

### Display

- `.d-block` - Блок дисплея
- `.d-contents` - Отобразить содержимое
- `.d-flex` - Гибкий дисплей
- `.d-flow-root` - Отобразить корень потока
- `.d-grid` - Сетка отображения
- `.d-inline` - Отобразить в строке
- `.d-inline-block` - Отображать встроенный блок
- `.d-inline-flex` - Встроенный гибкий дисплей
- `.d-inline-grid` - Отображение встроенной сетки
- `.d-inline-table` - Отобразить встроенную таблицу
- `.d-list-item` - Отобразить элемент списка
- `.d-none` - Отображать нет
- `.d-table` - Таблица отображения
- `.d-table-caption` - Отобразить заголовок таблицы
- `.d-table-cell` - Отобразить ячейку таблицы
- `.d-table-col` - Отобразить таблицу-столбец
- `.d-table-col-group` - Отобразить группу столбцов таблицы
- `.d-table-footer-group` - Отобразить группу нижнего колонтитула таблицы
- `.d-table-header-group` - Отобразить группу заголовков таблицы
- `.d-table-row` - Отобразить строку таблицы
- `.d-table-row-group` - Отобразить группу строк таблицы
- `.hover:d-block` - Блок отображения при наведении
- `.hover:d-flex` - Гибкое отображение при наведении
- `.hover:d-inline` - Отображать в строке при наведении
- `.hover:d-inline-block` - Отображать встроенный блок при наведении
- `.hover:d-inline-flex` - Отображать inline-flex при наведении
- `.hover:d-none` - Не отображать ничего при наведении

##### Display - Mobile (<= 480px)

- `.hover:mobile:d-block` - Блок отображения при наведении на мобильном телефоне
- `.hover:mobile:d-flex` - Гибкий дисплей при наведении на мобильном устройстве
- `.hover:mobile:d-inline` - Встроенное отображение при наведении на мобильном устройстве
- `.hover:mobile:d-inline-block` - Отображать встроенный блок при наведении на мобильном устройстве
- `.hover:mobile:d-inline-flex` - Отображать inline-flex при наведении на мобильном телефоне
- `.hover:mobile:d-none` - Не отображать ничего при наведении на мобильном телефоне
- `.mobile:d-block` - Блок отображения на мобильном телефоне
- `.mobile:d-flex` - Гибкий дисплей на мобильных устройствах
- `.mobile:d-grid` - Отображать сетку на мобильном телефоне
- `.mobile:d-inline` - Встроенное отображение на мобильных устройствах
- `.mobile:d-inline-block` - Отображение встроенного блока на мобильном устройстве
- `.mobile:d-inline-flex` - Отображать inline-flex на мобильных устройствах
- `.mobile:d-inline-grid` - Отображать встроенную сетку на мобильном телефоне
- `.mobile:d-none` - Не отображать ничего на мобильном телефоне

##### Display - Tablet (480px - 768px)

- `.hover:tablet:d-block` - Блок отображения при наведении на планшет
- `.hover:tablet:d-flex` - Гибкий дисплей при наведении на планшет
- `.hover:tablet:d-inline` - Встроенное отображение при наведении на планшете
- `.hover:tablet:d-inline-block` - Отображать встроенный блок при наведении на планшет
- `.hover:tablet:d-inline-flex` - Отображение встроенной гибкости при наведении на планшет
- `.hover:tablet:d-none` - Ничего не отображать при наведении на планшет
- `.tablet:d-block` - Блок дисплея на планшете
- `.tablet:d-flex` - Гибкий дисплей на планшете
- `.tablet:d-grid` - Отображение сетки на планшете
- `.tablet:d-inline` - Встроенный дисплей на планшете
- `.tablet:d-inline-block` - Отображение встроенного блока на планшете
- `.tablet:d-inline-flex` - Отображение inline-flex на планшете
- `.tablet:d-inline-grid` - Отображение встроенной сетки на планшете
- `.tablet:d-none` - Ничего не отображать на планшете

##### Display - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:d-block` - Блок отображения при наведении на планшетный компьютер
- `.hover:tablet-pc:d-flex` - Гибкий дисплей при наведении на планшетный компьютер
- `.hover:tablet-pc:d-inline` - Отображение в строке при наведении на планшетном ПК
- `.hover:tablet-pc:d-inline-block` - Отображать встроенный блок при наведении на планшетный компьютер
- `.hover:tablet-pc:d-inline-flex` - Отображение inline-flex при наведении на планшетный компьютер
- `.hover:tablet-pc:d-none` - Ничего не отображать при наведении на планшетный компьютер
- `.tablet-pc:d-block` - Блок дисплея на планшетном ПК
- `.tablet-pc:d-flex` - Гибкий дисплей на планшетном ПК
- `.tablet-pc:d-grid` - Отображение сетки на планшетном ПК
- `.tablet-pc:d-inline` - Встроенный дисплей на планшетном ПК
- `.tablet-pc:d-inline-block` - Отображение встроенного блока на планшетном ПК
- `.tablet-pc:d-inline-flex` - Дисплей inline-flex на планшетном ПК
- `.tablet-pc:d-inline-grid` - Отображение встроенной сетки на планшетном ПК
- `.tablet-pc:d-none` - Ничего не отображать на планшетном ПК

##### Display - Pc (992px - 1200px)

- `.hover:pc:d-block` - Блок отображения при наведении на ПК
- `.hover:pc:d-flex` - Гибкий дисплей при наведении на ПК
- `.hover:pc:d-inline` - Отображать в строке при наведении на ПК
- `.hover:pc:d-inline-block` - Отображать встроенный блок при наведении на ПК
- `.hover:pc:d-inline-flex` - Отображать inline-flex при наведении на ПК
- `.hover:pc:d-none` - Не отображать ничего при наведении на ПК
- `.pc:d-block` - Блок дисплея на ПК
- `.pc:d-flex` - Гибкий дисплей на ПК
- `.pc:d-grid` - Отображение сетки на ПК
- `.pc:d-inline` - Встроенное отображение на ПК
- `.pc:d-inline-block` - Отображение встроенного блока на ПК
- `.pc:d-inline-flex` - Дисплей inline-flex на ПК
- `.pc:d-inline-grid` - Отображение встроенной сетки на ПК
- `.pc:d-none` - Не отображать ничего на ПК

##### Display - Tv (>= 1200px)

- `.hover:tv:d-block` - Блок отображения при наведении на телевизор
- `.hover:tv:d-flex` - Гибкий дисплей при наведении на телевизор
- `.hover:tv:d-inline` - Встроенное отображение при наведении на телевизор
- `.hover:tv:d-inline-block` - Отображать встроенный блок при наведении на телевизор
- `.hover:tv:d-inline-flex` - Отображать inline-flex при наведении на телевизор
- `.hover:tv:d-none` - Ничего не показывать при наведении на телевизор
- `.tv:d-block` - Блок дисплея на телевизоре
- `.tv:d-flex` - Гибкий дисплей на телевизоре
- `.tv:d-grid` - Отображение сетки на телевизоре
- `.tv:d-inline` - Встроенное отображение на телевизоре
- `.tv:d-inline-block` - Отображение встроенного блока на телевизоре
- `.tv:d-inline-flex` - Отображение inline-flex на телевизоре
- `.tv:d-inline-grid` - Отображение встроенной сетки на телевизоре
- `.tv:d-none` - Ничего не показывать на телевизоре

##### Display - Tablet Max (<= 768px)

- `.hover:tablet-max:d-block` - Блок отображения при наведении на планшет макс.
- `.hover:tablet-max:d-flex` - Гибкий дисплей при наведении на планшет макс.
- `.hover:tablet-max:d-inline` - Встроенное отображение при наведении на планшете Max
- `.hover:tablet-max:d-inline-block` - Отображать встроенный блок при наведении на планшет макс.
- `.hover:tablet-max:d-inline-flex` - Отображение встроенного гибкого экрана при наведении на планшет макс.
- `.hover:tablet-max:d-none` - Не отображать ничего при наведении на планшет Макс.
- `.tablet-max:d-block` - Блок дисплея на планшете макс
- `.tablet-max:d-flex` - Дисплей Flex на планшете Max
- `.tablet-max:d-grid` - Сетка отображения на планшете макс.
- `.tablet-max:d-inline` - Встроенный дисплей на планшете Max
- `.tablet-max:d-inline-block` - Отображение встроенного блока на планшете макс.
- `.tablet-max:d-inline-flex` - Дисплей inline-flex на планшете max
- `.tablet-max:d-inline-grid` - Отображение встроенной сетки на планшете Max
- `.tablet-max:d-none` - Ничего не отображать на планшете Max

##### Display - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:d-block` - Блок отображения при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:d-flex` - Гибкий дисплей при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:d-inline` - Отображение в строке при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:d-inline-block` - Отображать встроенный блок при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:d-inline-flex` - Отображение inline-flex при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:d-none` - Не отображать ничего при наведении на планшетный ПК макс.
- `.tablet-pc-max:d-block` - Блок дисплея на планшетном ПК макс.
- `.tablet-pc-max:d-flex` - Дисплей Flex на планшетном ПК макс.
- `.tablet-pc-max:d-grid` - Сетка отображения на планшетном ПК макс.
- `.tablet-pc-max:d-inline` - Встроенный дисплей на планшетном ПК макс.
- `.tablet-pc-max:d-inline-block` - Отображение встроенного блока на планшетном ПК макс.
- `.tablet-pc-max:d-inline-flex` - Дисплей inline-flex на планшетном ПК макс.
- `.tablet-pc-max:d-inline-grid` - Отображение встроенной сетки на планшетном ПК макс.
- `.tablet-pc-max:d-none` - Отображать нет на планшетном ПК макс.

##### Display - Pc Max (<= 1200px)

- `.hover:pc-max:d-block` - Блок отображения при наведении на ПК макс.
- `.hover:pc-max:d-flex` - Гибкий дисплей при наведении на ПК макс.
- `.hover:pc-max:d-inline` - Встроенное отображение при наведении на ПК макс.
- `.hover:pc-max:d-inline-block` - Отображать встроенный блок при наведении на ПК макс.
- `.hover:pc-max:d-inline-flex` - Отображать inline-flex при наведении на ПК макс.
- `.hover:pc-max:d-none` - Не отображать ничего при наведении на ПК макс.
- `.pc-max:d-block` - Блок дисплея на пк макс
- `.pc-max:d-flex` - Дисплей Flex на ПК Макс.
- `.pc-max:d-grid` - Отображать сетку на ПК Макс.
- `.pc-max:d-inline` - Встроенный дисплей на ПК макс.
- `.pc-max:d-inline-block` - Отображение встроенного блока на ПК макс.
- `.pc-max:d-inline-flex` - Дисплей inline-flex на ПК макс.
- `.pc-max:d-inline-grid` - Отображение встроенной сетки на ПК Макс.
- `.pc-max:d-none` - Отображать нет на ПК макс.

### Float

- `.float-end` - Float в конце
- `.float-left` - Float слева
- `.float-none` - Float нет
- `.float-right` - Float справа
- `.float-start` - Float в начале
- `.hover:float-end` - Float в конце при наведении
- `.hover:float-left` - Float слева при наведении
- `.hover:float-none` - Float нет при наведении
- `.hover:float-right` - Float справа при наведении
- `.hover:float-start` - Float в начале при наведении

##### Float - Mobile (<= 480px)

- `.hover:mobile:float-end` - Float в конце при наведении на мобильных
- `.hover:mobile:float-left` - Float слева при наведении на мобильных
- `.hover:mobile:float-none` - Float нет при наведении на мобильных
- `.hover:mobile:float-right` - Float справа при наведении на мобильных
- `.hover:mobile:float-start` - Float в начале при наведении на мобильных
- `.mobile:float-end` - Float в конце на мобильных
- `.mobile:float-left` - Float слева на мобильных
- `.mobile:float-none` - Float нет на мобильных
- `.mobile:float-right` - Float справа на мобильных
- `.mobile:float-start` - Float в начале на мобильных

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - Float в конце при наведении на планшетах
- `.hover:tablet:float-left` - Float слева при наведении на планшетах
- `.hover:tablet:float-none` - Float нет при наведении на планшетах
- `.hover:tablet:float-right` - Float справа при наведении на планшетах
- `.hover:tablet:float-start` - Float в начале при наведении на планшетах
- `.tablet:float-end` - Float в конце на планшетах
- `.tablet:float-left` - Float слева на планшетах
- `.tablet:float-none` - Float нет на планшетах
- `.tablet:float-right` - Float справа на планшетах
- `.tablet:float-start` - Float в начале на планшетах

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - Float в конце при наведении на планшетных ПК
- `.hover:tablet-pc:float-left` - Float слева при наведении на планшетных ПК
- `.hover:tablet-pc:float-none` - Float нет при наведении на планшетных ПК
- `.hover:tablet-pc:float-right` - Float справа при наведении на планшетных ПК
- `.hover:tablet-pc:float-start` - Float в начале при наведении на планшетных ПК
- `.tablet-pc:float-end` - Float в конце на планшетных ПК
- `.tablet-pc:float-left` - Float слева на планшетных ПК
- `.tablet-pc:float-none` - Float нет на планшетных ПК
- `.tablet-pc:float-right` - Float справа на планшетных ПК
- `.tablet-pc:float-start` - Float в начале на планшетных ПК

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - Float в конце при наведении на ПК
- `.hover:pc:float-left` - Float слева при наведении на ПК
- `.hover:pc:float-none` - Float нет при наведении на ПК
- `.hover:pc:float-right` - Float справа при наведении на ПК
- `.hover:pc:float-start` - Float в начале при наведении на ПК
- `.pc:float-end` - Float в конце на ПК
- `.pc:float-left` - Float слева на ПК
- `.pc:float-none` - Float нет на ПК
- `.pc:float-right` - Float справа на ПК
- `.pc:float-start` - Float в начале на ПК

##### Float - Tv (>= 1200px)

- `.hover:tv:float-end` - Float в конце при наведении на ТВ
- `.hover:tv:float-left` - Float слева при наведении на ТВ
- `.hover:tv:float-none` - Float нет при наведении на ТВ
- `.hover:tv:float-right` - Float справа при наведении на ТВ
- `.hover:tv:float-start` - Float в начале при наведении на ТВ
- `.tv:float-end` - Float в конце на ТВ
- `.tv:float-left` - Float слева на ТВ
- `.tv:float-none` - Float нет на ТВ
- `.tv:float-right` - Float справа на ТВ
- `.tv:float-start` - Float в начале на ТВ

##### Float - Tablet Max (<= 768px)

- `.hover:tablet-max:float-end` - Float в конце при наведении на планшетах (макс.)
- `.hover:tablet-max:float-left` - Float слева при наведении на планшетах (макс.)
- `.hover:tablet-max:float-none` - Float нет при наведении на планшетах (макс.)
- `.hover:tablet-max:float-right` - Float справа при наведении на планшетах (макс.)
- `.hover:tablet-max:float-start` - Float в начале при наведении на планшетах (макс.)
- `.tablet-max:float-end` - Float в конце на планшетах (макс.)
- `.tablet-max:float-left` - Float слева на планшетах (макс.)
- `.tablet-max:float-none` - Float нет на планшетах (макс.)
- `.tablet-max:float-right` - Float справа на планшетах (макс.)
- `.tablet-max:float-start` - Float в начале на планшетах (макс.)

##### Float - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:float-end` - Float в конце при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:float-left` - Float слева при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:float-none` - Float нет при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:float-right` - Float справа при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:float-start` - Float в начале при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:float-end` - Float в конце на планшетных ПК (макс.)
- `.tablet-pc-max:float-left` - Float слева на планшетных ПК (макс.)
- `.tablet-pc-max:float-none` - Float нет на планшетных ПК (макс.)
- `.tablet-pc-max:float-right` - Float справа на планшетных ПК (макс.)
- `.tablet-pc-max:float-start` - Float в начале на планшетных ПК (макс.)

##### Float - Pc Max (<= 1200px)

- `.hover:pc-max:float-end` - Float в конце при наведении на ПК (макс.)
- `.hover:pc-max:float-left` - Float слева при наведении на ПК (макс.)
- `.hover:pc-max:float-none` - Float нет при наведении на ПК (макс.)
- `.hover:pc-max:float-right` - Float справа при наведении на ПК (макс.)
- `.hover:pc-max:float-start` - Float в начале при наведении на ПК (макс.)
- `.pc-max:float-end` - Float в конце на ПК (макс.)
- `.pc-max:float-left` - Float слева на ПК (макс.)
- `.pc-max:float-none` - Float нет на ПК (макс.)
- `.pc-max:float-right` - Float справа на ПК (макс.)
- `.pc-max:float-start` - Float в начале на ПК (макс.)

### Object

- `.hover:object-contain` - Объект содержится при наведении
- `.hover:object-cover` - Закрытие объекта при наведении
- `.hover:object-fill` - Заливка объекта при наведении
- `.hover:object-none` - Объект нет при наведении
- `.hover:object-scale` - Масштабирование объекта при наведении
- `.object-contain` - Объект содержит
- `.object-cover` - Крышка объекта
- `.object-fill` - Заливка объекта
- `.object-none` - Объект нет
- `.object-scale` - Масштаб объекта

##### Object - Mobile (<= 480px)

- `.hover:mobile:object-contain` - Объект содержится при наведении на мобильный телефон
- `.hover:mobile:object-cover` - Закрытие объекта при наведении на мобильном телефоне
- `.hover:mobile:object-fill` - Заливка объекта при наведении на мобильных
- `.hover:mobile:object-none` - Объект нет при наведении курсора на мобильном телефоне
- `.hover:mobile:object-scale` - Масштабирование объекта при наведении на мобильном телефоне
- `.mobile:object-contain` - Объект содержится на мобильном телефоне
- `.mobile:object-cover` - Прикрытие объекта на мобильном телефоне
- `.mobile:object-fill` - Заливка объекта на мобильном телефоне
- `.mobile:object-none` - Объект «Нет» на мобильном устройстве
- `.mobile:object-scale` - Масштабирование объекта на мобильном телефоне

##### Object - Tablet (480px - 768px)

- `.hover:tablet:object-contain` - Объект содержится при наведении на планшет
- `.hover:tablet:object-cover` - Закрытие объекта при наведении на планшет
- `.hover:tablet:object-fill` - Заливка объекта при наведении на планшетах
- `.hover:tablet:object-none` - Объект нет при наведении на планшет
- `.hover:tablet:object-scale` - Масштабирование объекта при наведении на планшет
- `.tablet:object-contain` - Объект содержится на планшете
- `.tablet:object-cover` - Обложка объекта на планшете
- `.tablet:object-fill` - Заливка объекта на планшете
- `.tablet:object-none` - Объект отсутствует на планшете
- `.tablet:object-scale` - Масштаб объекта на планшете

##### Object - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:object-contain` - Объект содержится при наведении на планшетный компьютер
- `.hover:tablet-pc:object-cover` - Покрытие объекта при наведении на планшетный компьютер
- `.hover:tablet-pc:object-fill` - Заливка объекта при наведении на планшетных ПК
- `.hover:tablet-pc:object-none` - Объект нет при наведении на планшетный компьютер
- `.hover:tablet-pc:object-scale` - Масштабирование объекта при наведении на планшетном ПК
- `.tablet-pc:object-contain` - Объект содержится на планшетном ПК
- `.tablet-pc:object-cover` - Крышка объекта на планшетном ПК
- `.tablet-pc:object-fill` - Заливка объекта на планшетном ПК
- `.tablet-pc:object-none` - Нет объекта на планшетном ПК
- `.tablet-pc:object-scale` - Масштаб объекта на планшетном ПК

##### Object - Pc (992px - 1200px)

- `.hover:pc:object-contain` - Объект содержится при наведении на ПК
- `.hover:pc:object-cover` - Закрытие объекта при наведении на ПК
- `.hover:pc:object-fill` - Заливка объекта при наведении на ПК
- `.hover:pc:object-none` - Объект нет при наведении на ПК
- `.hover:pc:object-scale` - Масштабирование объекта при наведении на ПК
- `.pc:object-contain` - Объект содержится на ПК
- `.pc:object-cover` - Крышка объекта на ПК
- `.pc:object-fill` - Заливка объекта на ПК
- `.pc:object-none` - Объект отсутствует на ПК
- `.pc:object-scale` - Масштаб объекта на ПК

##### Object - Tv (>= 1200px)

- `.hover:tv:object-contain` - Объект содержится при наведении на телевизор
- `.hover:tv:object-cover` - Закрытие объекта при наведении на телевизоре
- `.hover:tv:object-fill` - Заливка объекта при наведении на ТВ
- `.hover:tv:object-none` - Объект нет при наведении на телевизор
- `.hover:tv:object-scale` - Масштабирование объекта при наведении на телевизоре
- `.tv:object-contain` - Объект содержится на телевизоре
- `.tv:object-cover` - Обложка объекта на телевизоре
- `.tv:object-fill` - Заливка объектов на ТВ
- `.tv:object-none` - Объект нет по телевизору
- `.tv:object-scale` - Масштаб объекта на телевизоре

##### Object - Tablet Max (<= 768px)

- `.hover:tablet-max:object-contain` - Объект содержится при наведении на планшет макс.
- `.hover:tablet-max:object-cover` - Закрытие объекта при наведении на планшет макс.
- `.hover:tablet-max:object-fill` - Заливка объекта при наведении на планшетах (макс.)
- `.hover:tablet-max:object-none` - Объект нет при наведении на планшет Макс.
- `.hover:tablet-max:object-scale` - Масштабирование объекта при наведении на планшете Max
- `.tablet-max:object-contain` - Объект содержится на планшете Max
- `.tablet-max:object-cover` - Чехол для предметов на планшете max
- `.tablet-max:object-fill` - Заливка объекта на планшете Max
- `.tablet-max:object-none` - Объект отсутствует на планшете Max
- `.tablet-max:object-scale` - Масштаб объекта на планшете макс.

##### Object - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:object-contain` - Объект содержится при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:object-cover` - Покрытие объекта при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:object-fill` - Заливка объекта при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:object-none` - Объект нет при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:object-scale` - Масштабирование объекта при наведении на планшетном ПК макс.
- `.tablet-pc-max:object-contain` - Объект содержится на планшетном ПК макс.
- `.tablet-pc-max:object-cover` - Обложка объекта на планшетном ПК макс.
- `.tablet-pc-max:object-fill` - Заливка объекта на планшетном ПК Max
- `.tablet-pc-max:object-none` - Объект отсутствует на планшетном ПК Макс.
- `.tablet-pc-max:object-scale` - Масштаб объекта на планшетном ПК макс.

##### Object - Pc Max (<= 1200px)

- `.hover:pc-max:object-contain` - Объект содержится при наведении на ПК макс.
- `.hover:pc-max:object-cover` - Закрытие объекта при наведении на ПК макс
- `.hover:pc-max:object-fill` - Заливка объекта при наведении на ПК (макс.)
- `.hover:pc-max:object-none` - Объект отсутствует при наведении на ПК макс.
- `.hover:pc-max:object-scale` - Масштабирование объекта при наведении на ПК макс.
- `.pc-max:object-contain` - Объект содержится на ПК Макс.
- `.pc-max:object-cover` - Обложка объекта на пк макс
- `.pc-max:object-fill` - Заливка объекта на пк макс
- `.pc-max:object-none` - Объект отсутствует на ПК Макс.
- `.pc-max:object-scale` - Масштаб объекта на пк макс

### Overflow

- `.hover:overflow-scroll` - Прокрутка переполнения при наведении
- `.overflow-auto` - Переполнение авто
- `.overflow-clip` - Зажим переполнения
- `.overflow-hidden` - Переполнение скрыто
- `.overflow-scroll` - Прокрутка переполнения
- `.overflow-visible` - Видно переполнение

### Overflow x

- `.hover:overflow-x-scroll` - Переполнение x прокрутка при наведении
- `.overflow-x-auto` - Переполнение x авто
- `.overflow-x-clip` - Переполнение x клип
- `.overflow-x-hidden` - Переполнение x скрыто
- `.overflow-x-scroll` - Переполнение x прокрутка
- `.overflow-x-visible` - Переполнение x видимое

### Overflow y

- `.hover:overflow-y-scroll` - Переполнение и прокрутка при наведении
- `.overflow-y-auto` - Переполнение и авто
- `.overflow-y-clip` - Переполнение и клип
- `.overflow-y-hidden` - Переполнение скрыто
- `.overflow-y-scroll` - Переполнение и прокрутка
- `.overflow-y-visible` - Переполнение видно

### Header

- `.header` - Заголовок

### Footer

- `.footer` - Нижний колонтитул

## Flexbox

### Flex

- `.flex-col` - Гибкий кол
- `.flex-nowrap` - Flex теперьрап
- `.flex-row` - Гибкий ряд
- `.flex-wrap` - Гибкая пленка
- `.hover:flex-col` - Гибкий столбец при наведении
- `.hover:flex-nowrap` - Flex Nowrap при наведении
- `.hover:flex-row` - Гибкая строка при наведении
- `.hover:flex-wrap` - Гибкая упаковка при наведении

##### Flex - Mobile (<= 480px)

- `.hover:mobile:flex-col` - Flex Col при наведении на мобильном телефоне
- `.hover:mobile:flex-nowrap` - Flex nowrap при наведении на мобильном телефоне
- `.hover:mobile:flex-row` - Гибкая строка при наведении на мобильном телефоне
- `.hover:mobile:flex-wrap` - Гибкая упаковка при наведении на мобильном устройстве
- `.mobile:flex-col` - Flex Col на мобильном телефоне
- `.mobile:flex-nowrap` - Flex nowrap на мобильном телефоне
- `.mobile:flex-row` - Гибкая строка на мобильном устройстве
- `.mobile:flex-wrap` - Гибкая упаковка на мобильном телефоне

##### Flex - Tablet (480px - 768px)

- `.hover:tablet:flex-col` - Flex Col при наведении на планшет
- `.hover:tablet:flex-nowrap` - Flex Nowrap при наведении на планшет
- `.hover:tablet:flex-row` - Гибкая строка при наведении на планшете
- `.hover:tablet:flex-wrap` - Гибкая упаковка при наведении на планшет
- `.tablet:flex-col` - Flex Col на планшете
- `.tablet:flex-nowrap` - Flex Nowrap на планшете
- `.tablet:flex-row` - Гибкая строка на планшете
- `.tablet:flex-wrap` - Гибкая пленка на планшете

##### Flex - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col` - Flex Col при наведении на планшетный компьютер
- `.hover:tablet-pc:flex-nowrap` - Flex nowrap при наведении на планшетный компьютер
- `.hover:tablet-pc:flex-row` - Гибкая строка при наведении на планшетный компьютер
- `.hover:tablet-pc:flex-wrap` - Гибкая пленка при наведении на планшетный компьютер
- `.tablet-pc:flex-col` - Flex Col на планшетном ПК
- `.tablet-pc:flex-nowrap` - Flex Nowrap на планшетном ПК
- `.tablet-pc:flex-row` - Flex row на планшетном ПК
- `.tablet-pc:flex-wrap` - Гибкая пленка на планшетном ПК

##### Flex - Pc (992px - 1200px)

- `.hover:pc:flex-col` - Flex Col при наведении на ПК
- `.hover:pc:flex-nowrap` - Flex Nowrap при наведении на ПК
- `.hover:pc:flex-row` - Гибкая строка при наведении на ПК
- `.hover:pc:flex-wrap` - Гибкая упаковка при наведении на ПК
- `.pc:flex-col` - Flex Col на ПК
- `.pc:flex-nowrap` - Flex Nowrap на ПК
- `.pc:flex-row` - Гибкая строка на ПК
- `.pc:flex-wrap` - Гибкая пленка на ПК

##### Flex - Tv (>= 1200px)

- `.hover:tv:flex-col` - Flex Col при наведении на телевизор
- `.hover:tv:flex-nowrap` - Flex nowrap при наведении на телевизор
- `.hover:tv:flex-row` - Гибкая строка при наведении на телевизоре
- `.hover:tv:flex-wrap` - Гибкая упаковка при наведении на телевизоре
- `.tv:flex-col` - Flex Col по телевизору
- `.tv:flex-nowrap` - Flex Nowrap по телевизору
- `.tv:flex-row` - Flex Row по телевизору
- `.tv:flex-wrap` - Гибкая пленка на телевизоре

##### Flex - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-col` - Flex Col при наведении на планшете Max
- `.hover:tablet-max:flex-nowrap` - Flex Nowrap при наведении на планшете Max
- `.hover:tablet-max:flex-row` - Гибкая строка при наведении на планшете Max
- `.hover:tablet-max:flex-wrap` - Гибкая обертка при наведении на планшете Max
- `.tablet-max:flex-col` - Flex Col на планшете Max
- `.tablet-max:flex-nowrap` - Flex Nowrap на планшете Max
- `.tablet-max:flex-row` - Flex row на планшете Max
- `.tablet-max:flex-wrap` - Гибкая пленка на планшете Max

##### Flex - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-col` - Flex Col при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-nowrap` - Flex Nowrap при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-row` - Гибкая строка при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-wrap` - Гибкая пленка при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-col` - Flex col на планшетном ПК макс.
- `.tablet-pc-max:flex-nowrap` - Flex Nowrap на планшетном ПК макс.
- `.tablet-pc-max:flex-row` - Flex row на планшетном ПК макс.
- `.tablet-pc-max:flex-wrap` - Гибкая пленка на планшетном ПК макс.

##### Flex - Pc Max (<= 1200px)

- `.hover:pc-max:flex-col` - Flex Col при наведении на ПК макс.
- `.hover:pc-max:flex-nowrap` - Flex Nowrap при наведении на ПК макс.
- `.hover:pc-max:flex-row` - Гибкая строка при наведении на ПК макс.
- `.hover:pc-max:flex-wrap` - Гибкая обертка при наведении на ПК макс.
- `.pc-max:flex-col` - Flex Col на ПК Макс.
- `.pc-max:flex-nowrap` - Flex Nowrap на ПК Макс
- `.pc-max:flex-row` - Flex row на ПК Макс.
- `.pc-max:flex-wrap` - Гибкая пленка на ПК Макс.

### Flex col

- `.flex-col-reverse` - Гибкая колонка реверс
- `.hover:flex-col-reverse` - Flex Col переворачивается при наведении

##### Flex col - Mobile (<= 480px)

- `.hover:mobile:flex-col-reverse` - Flex Col переворачивается при наведении на мобильном телефоне
- `.mobile:flex-col-reverse` - Flex Col Reverse на мобильном телефоне

##### Flex col - Tablet (480px - 768px)

- `.hover:tablet:flex-col-reverse` - Flex Col переворачивается при наведении на планшет
- `.tablet:flex-col-reverse` - Flex Col Reverse на планшете

##### Flex col - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col-reverse` - Flex Col переворачивается при наведении на планшетный компьютер
- `.tablet-pc:flex-col-reverse` - Flex Col Reverse на планшетном ПК

##### Flex col - Pc (992px - 1200px)

- `.hover:pc:flex-col-reverse` - Flex Col переворачивается при наведении на ПК
- `.pc:flex-col-reverse` - Flex Col Reverse на ПК

##### Flex col - Tv (>= 1200px)

- `.hover:tv:flex-col-reverse` - Flex Col переворачивается при наведении на телевизор
- `.tv:flex-col-reverse` - Flex Col Reverse на телевизоре

##### Flex col - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-col-reverse` - Flex Col Reverse при наведении на планшете Max
- `.tablet-max:flex-col-reverse` - Flex Col Reverse на планшете Max

##### Flex col - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - Flex Col Reverse при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-col-reverse` - Flex Col Reverse на планшетном ПК макс.

##### Flex col - Pc Max (<= 1200px)

- `.hover:pc-max:flex-col-reverse` - Flex Col Reverse при наведении на ПК макс.
- `.pc-max:flex-col-reverse` - Flex Col Reverse на ПК Макс.

### Flex row

- `.flex-row-reverse` - Гибкая строка в обратном направлении
- `.hover:flex-row-reverse` - Изменение направления строки при наведении

##### Flex row - Mobile (<= 480px)

- `.hover:mobile:flex-row-reverse` - Изменение направления строки при наведении на мобильном устройстве
- `.mobile:flex-row-reverse` - Изменение направления гибкой строки на мобильном устройстве

##### Flex row - Tablet (480px - 768px)

- `.hover:tablet:flex-row-reverse` - Изменение направления строки при наведении на планшет
- `.tablet:flex-row-reverse` - Реверс гибкой строки на планшете

##### Flex row - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-row-reverse` - Реверс гибкой строки при наведении курсора на планшетный компьютер
- `.tablet-pc:flex-row-reverse` - Реверс гибкой строки на планшетном ПК

##### Flex row - Pc (992px - 1200px)

- `.hover:pc:flex-row-reverse` - Изменение направления строки при наведении на ПК
- `.pc:flex-row-reverse` - Реверс гибкой строки на ПК

##### Flex row - Tv (>= 1200px)

- `.hover:tv:flex-row-reverse` - Изменение положения строки при наведении на телевизор
- `.tv:flex-row-reverse` - Flex Row обратный по телевизору

##### Flex row - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-row-reverse` - Гибкая обратная строка при наведении на планшет макс.
- `.tablet-max:flex-row-reverse` - Реверс гибкой строки на планшете Max

##### Flex row - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - Реверс гибкой строки при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-row-reverse` - Flex Row Reverse на планшетном ПК макс.

##### Flex row - Pc Max (<= 1200px)

- `.hover:pc-max:flex-row-reverse` - Гибкая обратная строка при наведении на ПК макс.
- `.pc-max:flex-row-reverse` - Обратная строка Flex на ПК Макс.

### Flex grow

- `.flex-grow-3` - Flex Grow 3
- `.flex-grow-2` - Flex Grow 2
- `.flex-grow-1` - Гибкий рост 1
- `.flex-grow-0` - Flex растет 0
- `.hover:flex-grow-3` - Flex Grow 3 при наведении
- `.hover:flex-grow-2` - Flex растет на 2 при наведении
- `.hover:flex-grow-1` - Flex растет на 1 при наведении
- `.hover:flex-grow-0` - Flex растет на 0 при наведении

##### Flex grow - Mobile (<= 480px)

- `.hover:mobile:flex-grow-3` - Flex Grow 3 при наведении на мобильном телефоне
- `.hover:mobile:flex-grow-2` - Flex Grow 2 при наведении на мобильном телефоне
- `.hover:mobile:flex-grow-1` - Flex Grow 1 при наведении на мобильном телефоне
- `.hover:mobile:flex-grow-0` - Flex Grow 0 при наведении на мобильном телефоне
- `.mobile:flex-grow-3` - Flex Grow 3 на мобильном телефоне
- `.mobile:flex-grow-2` - Flex Grow 2 на мобильном телефоне
- `.mobile:flex-grow-1` - Flex Grow 1 на мобильном телефоне
- `.mobile:flex-grow-0` - Flex Grow 0 на мобильном телефоне

##### Flex grow - Tablet (480px - 768px)

- `.hover:tablet:flex-grow-3` - Flex Grow 3 при наведении на планшет
- `.hover:tablet:flex-grow-2` - Flex Grow 2 при наведении на планшет
- `.hover:tablet:flex-grow-1` - Flex Grow 1 при наведении на планшет
- `.hover:tablet:flex-grow-0` - Flex увеличивает 0 при наведении на планшет
- `.tablet:flex-grow-3` - Flex Grow 3 на планшете
- `.tablet:flex-grow-2` - Flex Grow 2 на планшете
- `.tablet:flex-grow-1` - Flex Grow 1 на планшете
- `.tablet:flex-grow-0` - Flex Grow 0 на планшете

##### Flex grow - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-grow-3` - Flex Grow 3 при наведении на планшетный ПК
- `.hover:tablet-pc:flex-grow-2` - Flex Grow 2 при наведении на планшетный ПК
- `.hover:tablet-pc:flex-grow-1` - Flex Grow 1 при наведении на планшетный ПК
- `.hover:tablet-pc:flex-grow-0` - Flex Grow 0 при наведении на планшетный ПК
- `.tablet-pc:flex-grow-3` - Flex Grow 3 на планшетном ПК
- `.tablet-pc:flex-grow-2` - Flex Grow 2 на планшетном ПК
- `.tablet-pc:flex-grow-1` - Flex Grow 1 на планшетном ПК
- `.tablet-pc:flex-grow-0` - Flex Grow 0 на планшетном ПК

##### Flex grow - Pc (992px - 1200px)

- `.hover:pc:flex-grow-3` - Flex Grow 3 при наведении на ПК
- `.hover:pc:flex-grow-2` - Flex Grow 2 при наведении на ПК
- `.hover:pc:flex-grow-1` - Flex Grow 1 при наведении на ПК
- `.hover:pc:flex-grow-0` - Flex Grow 0 при наведении на ПК
- `.pc:flex-grow-3` - Flex Grow 3 на ПК
- `.pc:flex-grow-2` - Flex Grow 2 на ПК
- `.pc:flex-grow-1` - Flex Grow 1 на ПК
- `.pc:flex-grow-0` - Flex Grow 0 на ПК

##### Flex grow - Tv (>= 1200px)

- `.hover:tv:flex-grow-3` - Flex Grow 3 при наведении на телевизор
- `.hover:tv:flex-grow-2` - Flex Grow 2 при наведении на телевизор
- `.hover:tv:flex-grow-1` - Flex Grow 1 при наведении на телевизор
- `.hover:tv:flex-grow-0` - Flex Grow 0 при наведении на телевизор
- `.tv:flex-grow-3` - Flex Grow 3 по телевизору
- `.tv:flex-grow-2` - Flex Grow 2 по телевизору
- `.tv:flex-grow-1` - Flex Grow 1 по телевизору
- `.tv:flex-grow-0` - Flex Grow 0 по телевизору

##### Flex grow - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-grow-3` - Flex Grow 3 при наведении на планшет макс.
- `.hover:tablet-max:flex-grow-2` - Flex Grow 2 при наведении на планшет макс.
- `.hover:tablet-max:flex-grow-1` - Flex Grow 1 при наведении на планшет макс.
- `.hover:tablet-max:flex-grow-0` - Flex Grow 0 при наведении на планшет макс.
- `.tablet-max:flex-grow-3` - Flex Grow 3 на планшете Max
- `.tablet-max:flex-grow-2` - Flex Grow 2 на планшете Max
- `.tablet-max:flex-grow-1` - Flex Grow 1 на планшете макс.
- `.tablet-max:flex-grow-0` - Flex Grow 0 на планшете Max

##### Flex grow - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex Grow 3 при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-grow-2` - Flex Grow 2 при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-grow-1` - Flex Grow 1 при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-grow-0` - Flex Grow 0 при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-grow-3` - Flex Grow 3 на планшетном ПК макс.
- `.tablet-pc-max:flex-grow-2` - Flex Grow 2 на планшетном ПК макс.
- `.tablet-pc-max:flex-grow-1` - Flex Grow 1 на планшетном ПК макс.
- `.tablet-pc-max:flex-grow-0` - Flex Grow 0 на планшетном ПК макс.

##### Flex grow - Pc Max (<= 1200px)

- `.hover:pc-max:flex-grow-3` - Flex Grow 3 при наведении на ПК макс.
- `.hover:pc-max:flex-grow-2` - Flex Grow 2 при наведении на ПК макс.
- `.hover:pc-max:flex-grow-1` - Flex Grow 1 при наведении на ПК макс.
- `.hover:pc-max:flex-grow-0` - Flex Grow 0 при наведении на ПК макс.
- `.pc-max:flex-grow-3` - Flex Grow 3 на ПК Макс.
- `.pc-max:flex-grow-2` - Flex Grow 2 на ПК Макс.
- `.pc-max:flex-grow-1` - Flex Grow 1 на ПК макс.
- `.pc-max:flex-grow-0` - Flex Grow 0 на ПК Макс.

### Flex wrap

- `.flex-wrap-reverse` - Гибкая обертка обратная
- `.hover:flex-wrap-reverse` - Обратное переворачивание Flex при наведении

##### Flex wrap - Mobile (<= 480px)

- `.hover:mobile:flex-wrap-reverse` - Обратное переворачивание Flex при наведении на мобильном телефоне
- `.mobile:flex-wrap-reverse` - Обратная обертка Flex на мобильном телефоне

##### Flex wrap - Tablet (480px - 768px)

- `.hover:tablet:flex-wrap-reverse` - Реверс гибкой обертки при наведении на планшет
- `.tablet:flex-wrap-reverse` - Обратная пленка Flex на планшете

##### Flex wrap - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-wrap-reverse` - Обратное переворачивание гибкой пленки при наведении на планшетный компьютер
- `.tablet-pc:flex-wrap-reverse` - Обратная пленка Flex на планшетном ПК

##### Flex wrap - Pc (992px - 1200px)

- `.hover:pc:flex-wrap-reverse` - Обратное переворачивание Flex при наведении на ПК
- `.pc:flex-wrap-reverse` - Обратная пленка Flex на ПК

##### Flex wrap - Tv (>= 1200px)

- `.hover:tv:flex-wrap-reverse` - Реверс гибкой обмотки при наведении курсора на телевизоре
- `.tv:flex-wrap-reverse` - Гибкая пленка обратная на телевизоре

##### Flex wrap - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-wrap-reverse` - Реверс гибкой обертки при наведении на планшет макс.
- `.tablet-max:flex-wrap-reverse` - Обратная пленка Flex на планшете Max

##### Flex wrap - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - Гибкая пленка обратная при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-wrap-reverse` - Обратная пленка Flex на планшетном ПК Max

##### Flex wrap - Pc Max (<= 1200px)

- `.hover:pc-max:flex-wrap-reverse` - Обратное переворачивание Flex при наведении на ПК макс.
- `.pc-max:flex-wrap-reverse` - Обратная пленка Flex на ПК Макс.

### Gap

#### Gap All

- `.gap-5` - Зазор со всех сторон 5rem
- `.gap-4.5` - Зазор со всех сторон 4.5rem
- `.gap-4` - Зазор со всех сторон 4rem
- `.gap-3.5` - Зазор со всех сторон 3.5rem
- `.gap-3` - Зазор со всех сторон 3rem
- `.gap-2.5` - Зазор со всех сторон 2.5rem
- `.gap-2` - Зазор со всех сторон 2rem
- `.gap-1.9` - Зазор со всех сторон 1.9rem
- `.gap-1.8` - Зазор со всех сторон 1.8rem
- `.gap-1.7` - Зазор со всех сторон 1.7rem
- `.gap-1.6` - Зазор со всех сторон 1.6rem
- `.gap-1.5` - Зазор со всех сторон 1.5rem
- `.gap-1.4` - Зазор со всех сторон 1.4rem
- `.gap-1.3` - Зазор со всех сторон 1.3rem
- `.gap-1.2` - Зазор со всех сторон 1.2rem
- `.gap-1.1` - Зазор со всех сторон 1.1rem
- `.gap-1` - Зазор со всех сторон 1rem
- `.gap-0.9` - Зазор со всех сторон 0.9rem
- `.gap-0.8` - Зазор со всех сторон 0.8rem
- `.gap-0.7` - Зазор со всех сторон 0.7rem
- `.gap-0.6` - Зазор со всех сторон 0.6rem
- `.gap-0.5` - Зазор со всех сторон 0.5rem
- `.gap-0.4` - Зазор со всех сторон 0.4rem
- `.gap-0.3` - Зазор со всех сторон 0.3rem
- `.gap-0.2` - Зазор со всех сторон 0.2rem
- `.gap-0.1` - Зазор со всех сторон 0.1rem
- `.gap-0` - Зазор со всех сторон 0rem
- `.hover:gap-5` - Зазор со всех сторон 5rem при наведении
- `.hover:gap-4.5` - Зазор со всех сторон 4.5rem при наведении
- `.hover:gap-4` - Зазор со всех сторон 4rem при наведении
- `.hover:gap-3.5` - Зазор со всех сторон 3.5rem при наведении
- `.hover:gap-3` - Зазор со всех сторон 3rem при наведении
- `.hover:gap-2.5` - Зазор со всех сторон 2.5rem при наведении
- `.hover:gap-2` - Зазор со всех сторон 2rem при наведении
- `.hover:gap-1.9` - Зазор со всех сторон 1.9rem при наведении
- `.hover:gap-1.8` - Зазор со всех сторон 1.8rem при наведении
- `.hover:gap-1.7` - Зазор со всех сторон 1.7rem при наведении
- `.hover:gap-1.6` - Зазор со всех сторон 1.6rem при наведении
- `.hover:gap-1.5` - Зазор со всех сторон 1.5rem при наведении
- `.hover:gap-1.4` - Зазор со всех сторон 1.4rem при наведении
- `.hover:gap-1.3` - Зазор со всех сторон 1.3rem при наведении
- `.hover:gap-1.2` - Зазор со всех сторон 1.2rem при наведении
- `.hover:gap-1.1` - Зазор со всех сторон 1.1rem при наведении
- `.hover:gap-1` - Зазор со всех сторон 1rem при наведении
- `.hover:gap-0.9` - Зазор со всех сторон 0.9rem при наведении
- `.hover:gap-0.8` - Зазор со всех сторон 0.8rem при наведении
- `.hover:gap-0.7` - Зазор со всех сторон 0.7rem при наведении
- `.hover:gap-0.6` - Зазор со всех сторон 0.6rem при наведении
- `.hover:gap-0.5` - Зазор со всех сторон 0.5rem при наведении
- `.hover:gap-0.4` - Зазор со всех сторон 0.4rem при наведении
- `.hover:gap-0.3` - Зазор со всех сторон 0.3rem при наведении
- `.hover:gap-0.2` - Зазор со всех сторон 0.2rem при наведении
- `.hover:gap-0.1` - Зазор со всех сторон 0.1rem при наведении
- `.hover:gap-0` - Зазор со всех сторон 0rem при наведении

#### Gap X-Axis

- `.gap-x-5` - Зазор по оси X 5rem
- `.gap-x-4.5` - Зазор по оси X 4.5rem
- `.gap-x-4` - Зазор X-ось 4rem
- `.gap-x-3.5` - Зазор по оси X 3.5rem
- `.gap-x-3` - Зазор X-ось 3rem
- `.gap-x-2.5` - Зазор по оси X 2.5rem
- `.gap-x-2` - Зазор по оси X 2rem
- `.gap-x-1.9` - Зазор по оси X 1.9rem
- `.gap-x-1.8` - Зазор по оси X 1.8rem
- `.gap-x-1.7` - Зазор по оси X 1.7rem
- `.gap-x-1.6` - Зазор по оси X 1.6rem
- `.gap-x-1.5` - Зазор по оси X 1.5rem
- `.gap-x-1.4` - Зазор по оси X 1.4rem
- `.gap-x-1.3` - Зазор по оси X 1.3rem
- `.gap-x-1.2` - Зазор по оси X 1.2rem
- `.gap-x-1.1` - Зазор по оси X 1.1rem
- `.gap-x-1` - Зазор по оси X 1rem
- `.gap-x-0.9` - Зазор по оси X 0.9rem
- `.gap-x-0.8` - Зазор по оси X 0.8rem
- `.gap-x-0.7` - Зазор по оси X 0.7rem
- `.gap-x-0.6` - Зазор по оси X 0.6rem
- `.gap-x-0.5` - Зазор по оси X 0.5rem
- `.gap-x-0.4` - Зазор по оси X 0.4rem
- `.gap-x-0.3` - Зазор по оси X 0.3rem
- `.gap-x-0.2` - Зазор по оси X 0,2rem
- `.gap-x-0.1` - Зазор по оси X: 0,1rem
- `.gap-x-0` - Зазор по оси X 0rem
- `.hover:gap-x-5` - Зазор X-Axis 5rem при наведении
- `.hover:gap-x-4.5` - Зазор по оси X 4.5rem при наведении
- `.hover:gap-x-4` - Зазор X-Axis 4rem при наведении
- `.hover:gap-x-3.5` - Зазор по оси X 3.5rem при наведении
- `.hover:gap-x-3` - Зазор X-Axis 3rem при наведении
- `.hover:gap-x-2.5` - Зазор по оси X 2.5rem при наведении
- `.hover:gap-x-2` - Зазор по оси X 2rem при наведении
- `.hover:gap-x-1.9` - Зазор по оси X 1.9rem при наведении
- `.hover:gap-x-1.8` - Зазор по оси X 1.8rem при наведении
- `.hover:gap-x-1.7` - Зазор по оси X 1.7rem при наведении
- `.hover:gap-x-1.6` - Зазор по оси X 1.6rem при наведении
- `.hover:gap-x-1.5` - Зазор по оси X 1.5rem при наведении
- `.hover:gap-x-1.4` - Зазор по оси X 1.4rem при наведении
- `.hover:gap-x-1.3` - Зазор по оси X 1.3rem при наведении
- `.hover:gap-x-1.2` - Зазор по оси X 1.2rem при наведении
- `.hover:gap-x-1.1` - Зазор по оси X 1.1rem при наведении
- `.hover:gap-x-1` - Зазор X-Axis 1rem при наведении
- `.hover:gap-x-0.9` - Зазор по оси X 0.9rem при наведении
- `.hover:gap-x-0.8` - Зазор по оси X 0.8rem при наведении
- `.hover:gap-x-0.7` - Зазор по оси X 0.7rem при наведении
- `.hover:gap-x-0.6` - Зазор по оси X 0.6rem при наведении
- `.hover:gap-x-0.5` - Зазор по оси X 0.5rem при наведении
- `.hover:gap-x-0.4` - Зазор по оси X 0.4rem при наведении
- `.hover:gap-x-0.3` - Зазор по оси X 0.3rem при наведении
- `.hover:gap-x-0.2` - Зазор по оси X 0,2rem при наведении
- `.hover:gap-x-0.1` - Зазор по оси X 0,1rem при наведении
- `.hover:gap-x-0` - Зазор по оси X 0rem при наведении

#### Gap Y-Axis

- `.gap-y-5` - Зазор по оси Y 5rem
- `.gap-y-4.5` - Зазор по оси Y 4.5rem
- `.gap-y-4` - Зазор по оси Y 4rem
- `.gap-y-3.5` - Зазор по оси Y 3.5rem
- `.gap-y-3` - Зазор по оси Y 3rem
- `.gap-y-2.5` - Зазор по оси Y 2.5rem
- `.gap-y-2` - Зазор по оси Y 2rem
- `.gap-y-1.9` - Зазор по оси Y 1.9rem
- `.gap-y-1.8` - Зазор по оси Y 1.8rem
- `.gap-y-1.7` - Зазор по оси Y 1.7rem
- `.gap-y-1.6` - Зазор по оси Y 1.6rem
- `.gap-y-1.5` - Зазор по оси Y 1.5rem
- `.gap-y-1.4` - Зазор по оси Y 1.4rem
- `.gap-y-1.3` - Зазор по оси Y 1.3rem
- `.gap-y-1.2` - Зазор по оси Y 1.2rem
- `.gap-y-1.1` - Зазор по оси Y 1.1rem
- `.gap-y-1` - Зазор по оси Y 1rem
- `.gap-y-0.9` - Зазор по оси Y 0.9rem
- `.gap-y-0.8` - Зазор по оси Y 0.8rem
- `.gap-y-0.7` - Зазор по оси Y 0.7rem
- `.gap-y-0.6` - Зазор по оси Y 0.6rem
- `.gap-y-0.5` - Зазор по оси Y 0.5rem
- `.gap-y-0.4` - Зазор по оси Y 0.4rem
- `.gap-y-0.3` - Зазор по оси Y 0.3rem
- `.gap-y-0.2` - Зазор по оси Y: 0,2rem
- `.gap-y-0.1` - Зазор по оси Y: 0,1rem
- `.gap-y-0` - Зазор по оси Y 0rem
- `.hover:gap-y-5` - Зазор по оси Y 5rem при наведении
- `.hover:gap-y-4.5` - Зазор по оси Y 4.5rem при наведении
- `.hover:gap-y-4` - Зазор по оси Y 4rem при наведении
- `.hover:gap-y-3.5` - Зазор по оси Y 3.5rem при наведении
- `.hover:gap-y-3` - Зазор по оси Y 3rem при наведении
- `.hover:gap-y-2.5` - Зазор по оси Y 2.5rem при наведении
- `.hover:gap-y-2` - Зазор по оси Y 2rem при наведении
- `.hover:gap-y-1.9` - Зазор по оси Y 1.9rem при наведении
- `.hover:gap-y-1.8` - Зазор по оси Y 1.8rem при наведении
- `.hover:gap-y-1.7` - Зазор по оси Y 1.7rem при наведении
- `.hover:gap-y-1.6` - Зазор по оси Y 1.6rem при наведении
- `.hover:gap-y-1.5` - Зазор по оси Y 1.5rem при наведении
- `.hover:gap-y-1.4` - Зазор по оси Y 1.4rem при наведении
- `.hover:gap-y-1.3` - Зазор по оси Y 1.3rem при наведении
- `.hover:gap-y-1.2` - Зазор по оси Y 1.2rem при наведении
- `.hover:gap-y-1.1` - Зазор по оси Y 1.1rem при наведении
- `.hover:gap-y-1` - Зазор по оси Y 1rem при наведении
- `.hover:gap-y-0.9` - Зазор по оси Y 0.9rem при наведении
- `.hover:gap-y-0.8` - Зазор по оси Y 0.8rem при наведении
- `.hover:gap-y-0.7` - Зазор по оси Y 0.7rem при наведении
- `.hover:gap-y-0.6` - Зазор по оси Y 0.6rem при наведении
- `.hover:gap-y-0.5` - Зазор по оси Y 0.5rem при наведении
- `.hover:gap-y-0.4` - Зазор по оси Y 0.4rem при наведении
- `.hover:gap-y-0.3` - Зазор по оси Y 0.3rem при наведении
- `.hover:gap-y-0.2` - Зазор по оси Y 0,2rem при наведении
- `.hover:gap-y-0.1` - Зазор по оси Y 0,1rem при наведении
- `.hover:gap-y-0` - Зазор по оси Y 0rem при наведении

### Align content

- `.align-content-around` - Выравнивание содержимого: around
- `.align-content-between` - Выравнивание содержимого: between
- `.align-content-center` - Выравнивание содержимого: центр
- `.align-content-end` - Выравнивание содержимого: конец
- `.align-content-evenly` - Выравнивание содержимого: evenly
- `.align-content-start` - Выравнивание содержимого: начало
- `.align-content-stretch` - Выравнивание содержимого: stretch
- `.hover:align-content-around` - Выравнивание содержимого: around при наведении
- `.hover:align-content-between` - Выравнивание содержимого: between при наведении
- `.hover:align-content-center` - Выравнивание содержимого: центр при наведении
- `.hover:align-content-end` - Выравнивание содержимого: конец при наведении
- `.hover:align-content-evenly` - Выравнивание содержимого: evenly при наведении
- `.hover:align-content-start` - Выравнивание содержимого: начало при наведении
- `.hover:align-content-stretch` - Выравнивание содержимого: stretch при наведении

##### Align content - Mobile (<= 480px)

- `.hover:mobile:align-content-around` - Выравнивание содержимого: around при наведении на мобильных
- `.hover:mobile:align-content-between` - Выравнивание содержимого: between при наведении на мобильных
- `.hover:mobile:align-content-center` - Выравнивание содержимого: центр при наведении на мобильных
- `.hover:mobile:align-content-end` - Выравнивание содержимого: конец при наведении на мобильных
- `.hover:mobile:align-content-evenly` - Выравнивание содержимого: evenly при наведении на мобильных
- `.hover:mobile:align-content-start` - Выравнивание содержимого: начало при наведении на мобильных
- `.hover:mobile:align-content-stretch` - Выравнивание содержимого: stretch при наведении на мобильных
- `.mobile:align-content-around` - Выравнивание содержимого: around на мобильных
- `.mobile:align-content-between` - Выравнивание содержимого: between на мобильных
- `.mobile:align-content-center` - Выравнивание содержимого: центр на мобильных
- `.mobile:align-content-end` - Выравнивание содержимого: конец на мобильных
- `.mobile:align-content-evenly` - Выравнивание содержимого: evenly на мобильных
- `.mobile:align-content-start` - Выравнивание содержимого: начало на мобильных
- `.mobile:align-content-stretch` - Выравнивание содержимого: stretch на мобильных

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - Выравнивание содержимого: around при наведении на планшетах
- `.hover:tablet:align-content-between` - Выравнивание содержимого: between при наведении на планшетах
- `.hover:tablet:align-content-center` - Выравнивание содержимого: центр при наведении на планшетах
- `.hover:tablet:align-content-end` - Выравнивание содержимого: конец при наведении на планшетах
- `.hover:tablet:align-content-evenly` - Выравнивание содержимого: evenly при наведении на планшетах
- `.hover:tablet:align-content-start` - Выравнивание содержимого: начало при наведении на планшетах
- `.hover:tablet:align-content-stretch` - Выравнивание содержимого: stretch при наведении на планшетах
- `.tablet:align-content-around` - Выравнивание содержимого: around на планшетах
- `.tablet:align-content-between` - Выравнивание содержимого: between на планшетах
- `.tablet:align-content-center` - Выравнивание содержимого: центр на планшетах
- `.tablet:align-content-end` - Выравнивание содержимого: конец на планшетах
- `.tablet:align-content-evenly` - Выравнивание содержимого: evenly на планшетах
- `.tablet:align-content-start` - Выравнивание содержимого: начало на планшетах
- `.tablet:align-content-stretch` - Выравнивание содержимого: stretch на планшетах

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - Выравнивание содержимого: around при наведении на планшетных ПК
- `.hover:tablet-pc:align-content-between` - Выравнивание содержимого: between при наведении на планшетных ПК
- `.hover:tablet-pc:align-content-center` - Выравнивание содержимого: центр при наведении на планшетных ПК
- `.hover:tablet-pc:align-content-end` - Выравнивание содержимого: конец при наведении на планшетных ПК
- `.hover:tablet-pc:align-content-evenly` - Выравнивание содержимого: evenly при наведении на планшетных ПК
- `.hover:tablet-pc:align-content-start` - Выравнивание содержимого: начало при наведении на планшетных ПК
- `.hover:tablet-pc:align-content-stretch` - Выравнивание содержимого: stretch при наведении на планшетных ПК
- `.tablet-pc:align-content-around` - Выравнивание содержимого: around на планшетных ПК
- `.tablet-pc:align-content-between` - Выравнивание содержимого: between на планшетных ПК
- `.tablet-pc:align-content-center` - Выравнивание содержимого: центр на планшетных ПК
- `.tablet-pc:align-content-end` - Выравнивание содержимого: конец на планшетных ПК
- `.tablet-pc:align-content-evenly` - Выравнивание содержимого: evenly на планшетных ПК
- `.tablet-pc:align-content-start` - Выравнивание содержимого: начало на планшетных ПК
- `.tablet-pc:align-content-stretch` - Выравнивание содержимого: stretch на планшетных ПК

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - Выравнивание содержимого: around при наведении на ПК
- `.hover:pc:align-content-between` - Выравнивание содержимого: between при наведении на ПК
- `.hover:pc:align-content-center` - Выравнивание содержимого: центр при наведении на ПК
- `.hover:pc:align-content-end` - Выравнивание содержимого: конец при наведении на ПК
- `.hover:pc:align-content-evenly` - Выравнивание содержимого: evenly при наведении на ПК
- `.hover:pc:align-content-start` - Выравнивание содержимого: начало при наведении на ПК
- `.hover:pc:align-content-stretch` - Выравнивание содержимого: stretch при наведении на ПК
- `.pc:align-content-around` - Выравнивание содержимого: around на ПК
- `.pc:align-content-between` - Выравнивание содержимого: between на ПК
- `.pc:align-content-center` - Выравнивание содержимого: центр на ПК
- `.pc:align-content-end` - Выравнивание содержимого: конец на ПК
- `.pc:align-content-evenly` - Выравнивание содержимого: evenly на ПК
- `.pc:align-content-start` - Выравнивание содержимого: начало на ПК
- `.pc:align-content-stretch` - Выравнивание содержимого: stretch на ПК

##### Align content - Tv (>= 1200px)

- `.hover:tv:align-content-around` - Выравнивание содержимого: around при наведении на ТВ
- `.hover:tv:align-content-between` - Выравнивание содержимого: between при наведении на ТВ
- `.hover:tv:align-content-center` - Выравнивание содержимого: центр при наведении на ТВ
- `.hover:tv:align-content-end` - Выравнивание содержимого: конец при наведении на ТВ
- `.hover:tv:align-content-evenly` - Выравнивание содержимого: evenly при наведении на ТВ
- `.hover:tv:align-content-start` - Выравнивание содержимого: начало при наведении на ТВ
- `.hover:tv:align-content-stretch` - Выравнивание содержимого: stretch при наведении на ТВ
- `.tv:align-content-around` - Выравнивание содержимого: around на ТВ
- `.tv:align-content-between` - Выравнивание содержимого: between на ТВ
- `.tv:align-content-center` - Выравнивание содержимого: центр на ТВ
- `.tv:align-content-end` - Выравнивание содержимого: конец на ТВ
- `.tv:align-content-evenly` - Выравнивание содержимого: evenly на ТВ
- `.tv:align-content-start` - Выравнивание содержимого: начало на ТВ
- `.tv:align-content-stretch` - Выравнивание содержимого: stretch на ТВ

##### Align content - Tablet Max (<= 768px)

- `.hover:tablet-max:align-content-around` - Выравнивание содержимого: around при наведении на планшетах (макс.)
- `.hover:tablet-max:align-content-between` - Выравнивание содержимого: between при наведении на планшетах (макс.)
- `.hover:tablet-max:align-content-center` - Выравнивание содержимого: центр при наведении на планшетах (макс.)
- `.hover:tablet-max:align-content-end` - Выравнивание содержимого: конец при наведении на планшетах (макс.)
- `.hover:tablet-max:align-content-evenly` - Выравнивание содержимого: evenly при наведении на планшетах (макс.)
- `.hover:tablet-max:align-content-start` - Выравнивание содержимого: начало при наведении на планшетах (макс.)
- `.hover:tablet-max:align-content-stretch` - Выравнивание содержимого: stretch при наведении на планшетах (макс.)
- `.tablet-max:align-content-around` - Выравнивание содержимого: around на планшетах (макс.)
- `.tablet-max:align-content-between` - Выравнивание содержимого: between на планшетах (макс.)
- `.tablet-max:align-content-center` - Выравнивание содержимого: центр на планшетах (макс.)
- `.tablet-max:align-content-end` - Выравнивание содержимого: конец на планшетах (макс.)
- `.tablet-max:align-content-evenly` - Выравнивание содержимого: evenly на планшетах (макс.)
- `.tablet-max:align-content-start` - Выравнивание содержимого: начало на планшетах (макс.)
- `.tablet-max:align-content-stretch` - Выравнивание содержимого: stretch на планшетах (макс.)

##### Align content - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-content-around` - Выравнивание содержимого: around при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-content-between` - Выравнивание содержимого: between при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-content-center` - Выравнивание содержимого: центр при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-content-end` - Выравнивание содержимого: конец при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-content-evenly` - Выравнивание содержимого: evenly при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-content-start` - Выравнивание содержимого: начало при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-content-stretch` - Выравнивание содержимого: stretch при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-around` - Выравнивание содержимого: around на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-between` - Выравнивание содержимого: between на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-center` - Выравнивание содержимого: центр на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-end` - Выравнивание содержимого: конец на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-evenly` - Выравнивание содержимого: evenly на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-start` - Выравнивание содержимого: начало на планшетных ПК (макс.)
- `.tablet-pc-max:align-content-stretch` - Выравнивание содержимого: stretch на планшетных ПК (макс.)

##### Align content - Pc Max (<= 1200px)

- `.hover:pc-max:align-content-around` - Выравнивание содержимого: around при наведении на ПК (макс.)
- `.hover:pc-max:align-content-between` - Выравнивание содержимого: between при наведении на ПК (макс.)
- `.hover:pc-max:align-content-center` - Выравнивание содержимого: центр при наведении на ПК (макс.)
- `.hover:pc-max:align-content-end` - Выравнивание содержимого: конец при наведении на ПК (макс.)
- `.hover:pc-max:align-content-evenly` - Выравнивание содержимого: evenly при наведении на ПК (макс.)
- `.hover:pc-max:align-content-start` - Выравнивание содержимого: начало при наведении на ПК (макс.)
- `.hover:pc-max:align-content-stretch` - Выравнивание содержимого: stretch при наведении на ПК (макс.)
- `.pc-max:align-content-around` - Выравнивание содержимого: around на ПК (макс.)
- `.pc-max:align-content-between` - Выравнивание содержимого: between на ПК (макс.)
- `.pc-max:align-content-center` - Выравнивание содержимого: центр на ПК (макс.)
- `.pc-max:align-content-end` - Выравнивание содержимого: конец на ПК (макс.)
- `.pc-max:align-content-evenly` - Выравнивание содержимого: evenly на ПК (макс.)
- `.pc-max:align-content-start` - Выравнивание содержимого: начало на ПК (макс.)
- `.pc-max:align-content-stretch` - Выравнивание содержимого: stretch на ПК (макс.)

### Align items

- `.align-items-center` - Выравнивание элементов: центр
- `.align-items-end` - Выравнивание элементов: конец
- `.align-items-start` - Выравнивание элементов: начало
- `.align-items-stretch` - Выравнивание элементов: stretch
- `.hover:align-items-center` - Выравнивание элементов: центр при наведении
- `.hover:align-items-end` - Выравнивание элементов: конец при наведении
- `.hover:align-items-start` - Выравнивание элементов: начало при наведении
- `.hover:align-items-stretch` - Выравнивание элементов: stretch при наведении

##### Align items - Mobile (<= 480px)

- `.hover:mobile:align-items-center` - Выравнивание элементов: центр при наведении на мобильных
- `.hover:mobile:align-items-end` - Выравнивание элементов: конец при наведении на мобильных
- `.hover:mobile:align-items-start` - Выравнивание элементов: начало при наведении на мобильных
- `.hover:mobile:align-items-stretch` - Выравнивание элементов: stretch при наведении на мобильных
- `.mobile:align-items-center` - Выравнивание элементов: центр на мобильных
- `.mobile:align-items-end` - Выравнивание элементов: конец на мобильных
- `.mobile:align-items-start` - Выравнивание элементов: начало на мобильных
- `.mobile:align-items-stretch` - Выравнивание элементов: stretch на мобильных

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - Выравнивание элементов: центр при наведении на планшетах
- `.hover:tablet:align-items-end` - Выравнивание элементов: конец при наведении на планшетах
- `.hover:tablet:align-items-start` - Выравнивание элементов: начало при наведении на планшетах
- `.hover:tablet:align-items-stretch` - Выравнивание элементов: stretch при наведении на планшетах
- `.tablet:align-items-center` - Выравнивание элементов: центр на планшетах
- `.tablet:align-items-end` - Выравнивание элементов: конец на планшетах
- `.tablet:align-items-start` - Выравнивание элементов: начало на планшетах
- `.tablet:align-items-stretch` - Выравнивание элементов: stretch на планшетах

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - Выравнивание элементов: центр при наведении на планшетных ПК
- `.hover:tablet-pc:align-items-end` - Выравнивание элементов: конец при наведении на планшетных ПК
- `.hover:tablet-pc:align-items-start` - Выравнивание элементов: начало при наведении на планшетных ПК
- `.hover:tablet-pc:align-items-stretch` - Выравнивание элементов: stretch при наведении на планшетных ПК
- `.tablet-pc:align-items-center` - Выравнивание элементов: центр на планшетных ПК
- `.tablet-pc:align-items-end` - Выравнивание элементов: конец на планшетных ПК
- `.tablet-pc:align-items-start` - Выравнивание элементов: начало на планшетных ПК
- `.tablet-pc:align-items-stretch` - Выравнивание элементов: stretch на планшетных ПК

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - Выравнивание элементов: центр при наведении на ПК
- `.hover:pc:align-items-end` - Выравнивание элементов: конец при наведении на ПК
- `.hover:pc:align-items-start` - Выравнивание элементов: начало при наведении на ПК
- `.hover:pc:align-items-stretch` - Выравнивание элементов: stretch при наведении на ПК
- `.pc:align-items-center` - Выравнивание элементов: центр на ПК
- `.pc:align-items-end` - Выравнивание элементов: конец на ПК
- `.pc:align-items-start` - Выравнивание элементов: начало на ПК
- `.pc:align-items-stretch` - Выравнивание элементов: stretch на ПК

##### Align items - Tv (>= 1200px)

- `.hover:tv:align-items-center` - Выравнивание элементов: центр при наведении на ТВ
- `.hover:tv:align-items-end` - Выравнивание элементов: конец при наведении на ТВ
- `.hover:tv:align-items-start` - Выравнивание элементов: начало при наведении на ТВ
- `.hover:tv:align-items-stretch` - Выравнивание элементов: stretch при наведении на ТВ
- `.tv:align-items-center` - Выравнивание элементов: центр на ТВ
- `.tv:align-items-end` - Выравнивание элементов: конец на ТВ
- `.tv:align-items-start` - Выравнивание элементов: начало на ТВ
- `.tv:align-items-stretch` - Выравнивание элементов: stretch на ТВ

##### Align items - Tablet Max (<= 768px)

- `.hover:tablet-max:align-items-center` - Выравнивание элементов: центр при наведении на планшетах (макс.)
- `.hover:tablet-max:align-items-end` - Выравнивание элементов: конец при наведении на планшетах (макс.)
- `.hover:tablet-max:align-items-start` - Выравнивание элементов: начало при наведении на планшетах (макс.)
- `.hover:tablet-max:align-items-stretch` - Выравнивание элементов: stretch при наведении на планшетах (макс.)
- `.tablet-max:align-items-center` - Выравнивание элементов: центр на планшетах (макс.)
- `.tablet-max:align-items-end` - Выравнивание элементов: конец на планшетах (макс.)
- `.tablet-max:align-items-start` - Выравнивание элементов: начало на планшетах (макс.)
- `.tablet-max:align-items-stretch` - Выравнивание элементов: stretch на планшетах (макс.)

##### Align items - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-items-center` - Выравнивание элементов: центр при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-items-end` - Выравнивание элементов: конец при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-items-start` - Выравнивание элементов: начало при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-items-stretch` - Выравнивание элементов: stretch при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:align-items-center` - Выравнивание элементов: центр на планшетных ПК (макс.)
- `.tablet-pc-max:align-items-end` - Выравнивание элементов: конец на планшетных ПК (макс.)
- `.tablet-pc-max:align-items-start` - Выравнивание элементов: начало на планшетных ПК (макс.)
- `.tablet-pc-max:align-items-stretch` - Выравнивание элементов: stretch на планшетных ПК (макс.)

##### Align items - Pc Max (<= 1200px)

- `.hover:pc-max:align-items-center` - Выравнивание элементов: центр при наведении на ПК (макс.)
- `.hover:pc-max:align-items-end` - Выравнивание элементов: конец при наведении на ПК (макс.)
- `.hover:pc-max:align-items-start` - Выравнивание элементов: начало при наведении на ПК (макс.)
- `.hover:pc-max:align-items-stretch` - Выравнивание элементов: stretch при наведении на ПК (макс.)
- `.pc-max:align-items-center` - Выравнивание элементов: центр на ПК (макс.)
- `.pc-max:align-items-end` - Выравнивание элементов: конец на ПК (макс.)
- `.pc-max:align-items-start` - Выравнивание элементов: начало на ПК (макс.)
- `.pc-max:align-items-stretch` - Выравнивание элементов: stretch на ПК (макс.)

### Align self

- `.align-self-center` - Выравнивание самого элемента: центр
- `.align-self-end` - Выравнивание самого элемента: конец
- `.align-self-start` - Выравнивание самого элемента: начало
- `.align-self-stretch` - Выравнивание самого элемента: stretch
- `.hover:align-self-center` - Выравнивание самого элемента: центр при наведении
- `.hover:align-self-end` - Выравнивание самого элемента: конец при наведении
- `.hover:align-self-start` - Выравнивание самого элемента: начало при наведении
- `.hover:align-self-stretch` - Выравнивание самого элемента: stretch при наведении

##### Align self - Mobile (<= 480px)

- `.hover:mobile:align-self-center` - Выравнивание самого элемента: центр при наведении на мобильных
- `.hover:mobile:align-self-end` - Выравнивание самого элемента: конец при наведении на мобильных
- `.hover:mobile:align-self-start` - Выравнивание самого элемента: начало при наведении на мобильных
- `.hover:mobile:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на мобильных
- `.mobile:align-self-center` - Выравнивание самого элемента: центр на мобильных
- `.mobile:align-self-end` - Выравнивание самого элемента: конец на мобильных
- `.mobile:align-self-start` - Выравнивание самого элемента: начало на мобильных
- `.mobile:align-self-stretch` - Выравнивание самого элемента: stretch на мобильных

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - Выравнивание самого элемента: центр при наведении на планшетах
- `.hover:tablet:align-self-end` - Выравнивание самого элемента: конец при наведении на планшетах
- `.hover:tablet:align-self-start` - Выравнивание самого элемента: начало при наведении на планшетах
- `.hover:tablet:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на планшетах
- `.tablet:align-self-center` - Выравнивание самого элемента: центр на планшетах
- `.tablet:align-self-end` - Выравнивание самого элемента: конец на планшетах
- `.tablet:align-self-start` - Выравнивание самого элемента: начало на планшетах
- `.tablet:align-self-stretch` - Выравнивание самого элемента: stretch на планшетах

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - Выравнивание самого элемента: центр при наведении на планшетных ПК
- `.hover:tablet-pc:align-self-end` - Выравнивание самого элемента: конец при наведении на планшетных ПК
- `.hover:tablet-pc:align-self-start` - Выравнивание самого элемента: начало при наведении на планшетных ПК
- `.hover:tablet-pc:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на планшетных ПК
- `.tablet-pc:align-self-center` - Выравнивание самого элемента: центр на планшетных ПК
- `.tablet-pc:align-self-end` - Выравнивание самого элемента: конец на планшетных ПК
- `.tablet-pc:align-self-start` - Выравнивание самого элемента: начало на планшетных ПК
- `.tablet-pc:align-self-stretch` - Выравнивание самого элемента: stretch на планшетных ПК

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - Выравнивание самого элемента: центр при наведении на ПК
- `.hover:pc:align-self-end` - Выравнивание самого элемента: конец при наведении на ПК
- `.hover:pc:align-self-start` - Выравнивание самого элемента: начало при наведении на ПК
- `.hover:pc:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на ПК
- `.pc:align-self-center` - Выравнивание самого элемента: центр на ПК
- `.pc:align-self-end` - Выравнивание самого элемента: конец на ПК
- `.pc:align-self-start` - Выравнивание самого элемента: начало на ПК
- `.pc:align-self-stretch` - Выравнивание самого элемента: stretch на ПК

##### Align self - Tv (>= 1200px)

- `.hover:tv:align-self-center` - Выравнивание самого элемента: центр при наведении на ТВ
- `.hover:tv:align-self-end` - Выравнивание самого элемента: конец при наведении на ТВ
- `.hover:tv:align-self-start` - Выравнивание самого элемента: начало при наведении на ТВ
- `.hover:tv:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на ТВ
- `.tv:align-self-center` - Выравнивание самого элемента: центр на ТВ
- `.tv:align-self-end` - Выравнивание самого элемента: конец на ТВ
- `.tv:align-self-start` - Выравнивание самого элемента: начало на ТВ
- `.tv:align-self-stretch` - Выравнивание самого элемента: stretch на ТВ

##### Align self - Tablet Max (<= 768px)

- `.hover:tablet-max:align-self-center` - Выравнивание самого элемента: центр при наведении на планшетах (макс.)
- `.hover:tablet-max:align-self-end` - Выравнивание самого элемента: конец при наведении на планшетах (макс.)
- `.hover:tablet-max:align-self-start` - Выравнивание самого элемента: начало при наведении на планшетах (макс.)
- `.hover:tablet-max:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на планшетах (макс.)
- `.tablet-max:align-self-center` - Выравнивание самого элемента: центр на планшетах (макс.)
- `.tablet-max:align-self-end` - Выравнивание самого элемента: конец на планшетах (макс.)
- `.tablet-max:align-self-start` - Выравнивание самого элемента: начало на планшетах (макс.)
- `.tablet-max:align-self-stretch` - Выравнивание самого элемента: stretch на планшетах (макс.)

##### Align self - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-self-center` - Выравнивание самого элемента: центр при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-self-end` - Выравнивание самого элемента: конец при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-self-start` - Выравнивание самого элемента: начало при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:align-self-center` - Выравнивание самого элемента: центр на планшетных ПК (макс.)
- `.tablet-pc-max:align-self-end` - Выравнивание самого элемента: конец на планшетных ПК (макс.)
- `.tablet-pc-max:align-self-start` - Выравнивание самого элемента: начало на планшетных ПК (макс.)
- `.tablet-pc-max:align-self-stretch` - Выравнивание самого элемента: stretch на планшетных ПК (макс.)

##### Align self - Pc Max (<= 1200px)

- `.hover:pc-max:align-self-center` - Выравнивание самого элемента: центр при наведении на ПК (макс.)
- `.hover:pc-max:align-self-end` - Выравнивание самого элемента: конец при наведении на ПК (макс.)
- `.hover:pc-max:align-self-start` - Выравнивание самого элемента: начало при наведении на ПК (макс.)
- `.hover:pc-max:align-self-stretch` - Выравнивание самого элемента: stretch при наведении на ПК (макс.)
- `.pc-max:align-self-center` - Выравнивание самого элемента: центр на ПК (макс.)
- `.pc-max:align-self-end` - Выравнивание самого элемента: конец на ПК (макс.)
- `.pc-max:align-self-start` - Выравнивание самого элемента: начало на ПК (макс.)
- `.pc-max:align-self-stretch` - Выравнивание самого элемента: stretch на ПК (макс.)

### Justify content

- `.hover:justify-content-around` - Распределение содержимого: around при наведении
- `.hover:justify-content-between` - Распределение содержимого: between при наведении
- `.hover:justify-content-center` - Распределение содержимого: центр при наведении
- `.hover:justify-content-end` - Распределение содержимого: конец при наведении
- `.hover:justify-content-evenly` - Распределение содержимого: evenly при наведении
- `.hover:justify-content-start` - Распределение содержимого: начало при наведении
- `.hover:justify-content-stretch` - Распределение содержимого: stretch при наведении
- `.justify-content-around` - Распределение содержимого: around
- `.justify-content-between` - Распределение содержимого: between
- `.justify-content-center` - Распределение содержимого: центр
- `.justify-content-end` - Распределение содержимого: конец
- `.justify-content-evenly` - Распределение содержимого: evenly
- `.justify-content-start` - Распределение содержимого: начало
- `.justify-content-stretch` - Распределение содержимого: stretch

##### Justify content - Mobile (<= 480px)

- `.hover:mobile:justify-content-around` - Распределение содержимого: around при наведении на мобильных
- `.hover:mobile:justify-content-between` - Распределение содержимого: between при наведении на мобильных
- `.hover:mobile:justify-content-center` - Распределение содержимого: центр при наведении на мобильных
- `.hover:mobile:justify-content-end` - Распределение содержимого: конец при наведении на мобильных
- `.hover:mobile:justify-content-start` - Распределение содержимого: начало при наведении на мобильных
- `.mobile:justify-content-around` - Распределение содержимого: around на мобильных
- `.mobile:justify-content-between` - Распределение содержимого: between на мобильных
- `.mobile:justify-content-center` - Распределение содержимого: центр на мобильных
- `.mobile:justify-content-end` - Распределение содержимого: конец на мобильных
- `.mobile:justify-content-start` - Распределение содержимого: начало на мобильных

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - Распределение содержимого: around при наведении на планшетах
- `.hover:tablet:justify-content-between` - Распределение содержимого: between при наведении на планшетах
- `.hover:tablet:justify-content-center` - Распределение содержимого: центр при наведении на планшетах
- `.hover:tablet:justify-content-end` - Распределение содержимого: конец при наведении на планшетах
- `.hover:tablet:justify-content-start` - Распределение содержимого: начало при наведении на планшетах
- `.tablet:justify-content-around` - Распределение содержимого: around на планшетах
- `.tablet:justify-content-between` - Распределение содержимого: between на планшетах
- `.tablet:justify-content-center` - Распределение содержимого: центр на планшетах
- `.tablet:justify-content-end` - Распределение содержимого: конец на планшетах
- `.tablet:justify-content-start` - Распределение содержимого: начало на планшетах

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - Распределение содержимого: around при наведении на планшетных ПК
- `.hover:tablet-pc:justify-content-between` - Распределение содержимого: between при наведении на планшетных ПК
- `.hover:tablet-pc:justify-content-center` - Распределение содержимого: центр при наведении на планшетных ПК
- `.hover:tablet-pc:justify-content-end` - Распределение содержимого: конец при наведении на планшетных ПК
- `.hover:tablet-pc:justify-content-start` - Распределение содержимого: начало при наведении на планшетных ПК
- `.tablet-pc:justify-content-around` - Распределение содержимого: around на планшетных ПК
- `.tablet-pc:justify-content-between` - Распределение содержимого: between на планшетных ПК
- `.tablet-pc:justify-content-center` - Распределение содержимого: центр на планшетных ПК
- `.tablet-pc:justify-content-end` - Распределение содержимого: конец на планшетных ПК
- `.tablet-pc:justify-content-start` - Распределение содержимого: начало на планшетных ПК

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - Распределение содержимого: around при наведении на ПК
- `.hover:pc:justify-content-between` - Распределение содержимого: between при наведении на ПК
- `.hover:pc:justify-content-center` - Распределение содержимого: центр при наведении на ПК
- `.hover:pc:justify-content-end` - Распределение содержимого: конец при наведении на ПК
- `.hover:pc:justify-content-start` - Распределение содержимого: начало при наведении на ПК
- `.pc:justify-content-around` - Распределение содержимого: around на ПК
- `.pc:justify-content-between` - Распределение содержимого: between на ПК
- `.pc:justify-content-center` - Распределение содержимого: центр на ПК
- `.pc:justify-content-end` - Распределение содержимого: конец на ПК
- `.pc:justify-content-start` - Распределение содержимого: начало на ПК

##### Justify content - Tv (>= 1200px)

- `.hover:tv:justify-content-around` - Распределение содержимого: around при наведении на ТВ
- `.hover:tv:justify-content-between` - Распределение содержимого: between при наведении на ТВ
- `.hover:tv:justify-content-center` - Распределение содержимого: центр при наведении на ТВ
- `.hover:tv:justify-content-end` - Распределение содержимого: конец при наведении на ТВ
- `.hover:tv:justify-content-start` - Распределение содержимого: начало при наведении на ТВ
- `.tv:justify-content-around` - Распределение содержимого: around на ТВ
- `.tv:justify-content-between` - Распределение содержимого: between на ТВ
- `.tv:justify-content-center` - Распределение содержимого: центр на ТВ
- `.tv:justify-content-end` - Распределение содержимого: конец на ТВ
- `.tv:justify-content-start` - Распределение содержимого: начало на ТВ

##### Justify content - Tablet Max (<= 768px)

- `.hover:tablet-max:justify-content-around` - Распределение содержимого: around при наведении на планшетах (макс.)
- `.hover:tablet-max:justify-content-between` - Распределение содержимого: between при наведении на планшетах (макс.)
- `.hover:tablet-max:justify-content-center` - Распределение содержимого: центр при наведении на планшетах (макс.)
- `.hover:tablet-max:justify-content-end` - Распределение содержимого: конец при наведении на планшетах (макс.)
- `.hover:tablet-max:justify-content-start` - Распределение содержимого: начало при наведении на планшетах (макс.)
- `.tablet-max:justify-content-around` - Распределение содержимого: around на планшетах (макс.)
- `.tablet-max:justify-content-between` - Распределение содержимого: between на планшетах (макс.)
- `.tablet-max:justify-content-center` - Распределение содержимого: центр на планшетах (макс.)
- `.tablet-max:justify-content-end` - Распределение содержимого: конец на планшетах (макс.)
- `.tablet-max:justify-content-start` - Распределение содержимого: начало на планшетах (макс.)

##### Justify content - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:justify-content-around` - Распределение содержимого: around при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:justify-content-between` - Распределение содержимого: between при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:justify-content-center` - Распределение содержимого: центр при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:justify-content-end` - Распределение содержимого: конец при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:justify-content-start` - Распределение содержимого: начало при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:justify-content-around` - Распределение содержимого: around на планшетных ПК (макс.)
- `.tablet-pc-max:justify-content-between` - Распределение содержимого: between на планшетных ПК (макс.)
- `.tablet-pc-max:justify-content-center` - Распределение содержимого: центр на планшетных ПК (макс.)
- `.tablet-pc-max:justify-content-end` - Распределение содержимого: конец на планшетных ПК (макс.)
- `.tablet-pc-max:justify-content-start` - Распределение содержимого: начало на планшетных ПК (макс.)

##### Justify content - Pc Max (<= 1200px)

- `.hover:pc-max:justify-content-around` - Распределение содержимого: around при наведении на ПК (макс.)
- `.hover:pc-max:justify-content-between` - Распределение содержимого: between при наведении на ПК (макс.)
- `.hover:pc-max:justify-content-center` - Распределение содержимого: центр при наведении на ПК (макс.)
- `.hover:pc-max:justify-content-end` - Распределение содержимого: конец при наведении на ПК (макс.)
- `.hover:pc-max:justify-content-start` - Распределение содержимого: начало при наведении на ПК (макс.)
- `.pc-max:justify-content-around` - Распределение содержимого: around на ПК (макс.)
- `.pc-max:justify-content-between` - Распределение содержимого: between на ПК (макс.)
- `.pc-max:justify-content-center` - Распределение содержимого: центр на ПК (макс.)
- `.pc-max:justify-content-end` - Распределение содержимого: конец на ПК (макс.)
- `.pc-max:justify-content-start` - Распределение содержимого: начало на ПК (макс.)

### Justify items

- `.hover:justify-items-center` - Горизонтальное выравнивание элементов: центр при наведении
- `.hover:justify-items-end` - Горизонтальное выравнивание элементов: конец при наведении
- `.hover:justify-items-start` - Горизонтальное выравнивание элементов: начало при наведении
- `.hover:justify-items-stretch` - Горизонтальное выравнивание элементов: stretch при наведении
- `.justify-items-center` - Горизонтальное выравнивание элементов: центр
- `.justify-items-end` - Горизонтальное выравнивание элементов: конец
- `.justify-items-start` - Горизонтальное выравнивание элементов: начало
- `.justify-items-stretch` - Горизонтальное выравнивание элементов: stretch

### Order

- `.hover:order-5` - Порядок 5 при наведении
- `.hover:order-4` - Порядок 4 при наведении
- `.hover:order-3` - Порядок 3 при наведении
- `.hover:order-2` - Порядок 2 при наведении
- `.hover:order-1` - Порядок 1 при наведении
- `.hover:order-0` - Порядок 0 при наведении
- `.hover:order-first` - Порядок: первый при наведении
- `.hover:order-last` - Порядок: последний при наведении
- `.order-5` - Порядок 5
- `.order-4` - Порядок 4
- `.order-3` - Порядок 3
- `.order-2` - Порядок 2
- `.order-1` - Порядок 1
- `.order-0` - Порядок 0
- `.order-first` - Порядок: первый
- `.order-last` - Порядок: последний

##### Negative Order

- `.-order-5` - Отрицательный порядок 5
- `.-order-4` - Отрицательный порядок 4
- `.-order-3` - Отрицательный порядок 3
- `.-order-2` - Отрицательный порядок 2
- `.-order-1` - Отрицательный порядок 1
- `.hover:-order-5` - Отрицательный порядок 5 при наведении
- `.hover:-order-4` - Отрицательный порядок 4 при наведении
- `.hover:-order-3` - Отрицательный порядок 3 при наведении
- `.hover:-order-2` - Отрицательный порядок 2 при наведении
- `.hover:-order-1` - Отрицательный порядок 1 при наведении

##### Order - Mobile (<= 480px)

- `.hover:mobile:order-5` - Порядок 5 при наведении на мобильных
- `.hover:mobile:order-4` - Порядок 4 при наведении на мобильных
- `.hover:mobile:order-3` - Порядок 3 при наведении на мобильных
- `.hover:mobile:order-2` - Порядок 2 при наведении на мобильных
- `.hover:mobile:order-1` - Порядок 1 при наведении на мобильных
- `.hover:mobile:order-0` - Порядок 0 при наведении на мобильных
- `.hover:mobile:order-first` - Порядок: первый при наведении на мобильных
- `.hover:mobile:order-last` - Порядок: последний при наведении на мобильных
- `.mobile:order-5` - Порядок 5 на мобильных
- `.mobile:order-4` - Порядок 4 на мобильных
- `.mobile:order-3` - Порядок 3 на мобильных
- `.mobile:order-2` - Порядок 2 на мобильных
- `.mobile:order-1` - Порядок 1 на мобильных
- `.mobile:order-0` - Порядок 0 на мобильных
- `.mobile:order-first` - Порядок: первый на мобильных
- `.mobile:order-last` - Порядок: последний на мобильных

##### Negative Order - Mobile (<= 480px)

- `.hover:mobile:-order-5` - Отрицательный порядок 5 при наведении на мобильном телефоне
- `.hover:mobile:-order-4` - Отрицательный порядок 4 при наведении на мобильном телефоне
- `.hover:mobile:-order-3` - Отрицательный порядок 3 при наведении на мобильном телефоне
- `.hover:mobile:-order-2` - Отрицательный порядок 2 при наведении на мобильных
- `.hover:mobile:-order-1` - Отрицательный порядок 1 при наведении на мобильных
- `.mobile:-order-5` - Отрицательный порядок 5 на мобильных
- `.mobile:-order-4` - Отрицательный порядок 4 на мобильных
- `.mobile:-order-3` - Отрицательный порядок 3 на мобильных
- `.mobile:-order-2` - Отрицательный порядок 2 на мобильных
- `.mobile:-order-1` - Отрицательный порядок 1 на мобильных

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - Порядок 5 при наведении на планшетах
- `.hover:tablet:order-4` - Порядок 4 при наведении на планшетах
- `.hover:tablet:order-3` - Порядок 3 при наведении на планшетах
- `.hover:tablet:order-2` - Порядок 2 при наведении на планшетах
- `.hover:tablet:order-1` - Порядок 1 при наведении на планшетах
- `.hover:tablet:order-0` - Порядок 0 при наведении на планшетах
- `.hover:tablet:order-first` - Порядок: первый при наведении на планшетах
- `.hover:tablet:order-last` - Порядок: последний при наведении на планшетах
- `.tablet:order-5` - Порядок 5 на планшетах
- `.tablet:order-4` - Порядок 4 на планшетах
- `.tablet:order-3` - Порядок 3 на планшетах
- `.tablet:order-2` - Порядок 2 на планшетах
- `.tablet:order-1` - Порядок 1 на планшетах
- `.tablet:order-0` - Порядок 0 на планшетах
- `.tablet:order-first` - Порядок: первый на планшетах
- `.tablet:order-last` - Порядок: последний на планшетах

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - Отрицательный порядок 5 при наведении на планшетах
- `.hover:tablet:-order-4` - Отрицательный порядок 4 при наведении на планшетах
- `.hover:tablet:-order-3` - Отрицательный порядок 3 при наведении на планшетах
- `.hover:tablet:-order-2` - Отрицательный порядок 2 при наведении на планшетах
- `.hover:tablet:-order-1` - Отрицательный порядок 1 при наведении на планшетах
- `.tablet:-order-5` - Отрицательный порядок 5 на планшетах
- `.tablet:-order-4` - Отрицательный порядок 4 на планшетах
- `.tablet:-order-3` - Отрицательный порядок 3 на планшетах
- `.tablet:-order-2` - Отрицательный порядок 2 на планшетах
- `.tablet:-order-1` - Отрицательный порядок 1 на планшетах

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - Порядок 5 при наведении на планшетных ПК
- `.hover:tablet-pc:order-4` - Порядок 4 при наведении на планшетных ПК
- `.hover:tablet-pc:order-3` - Порядок 3 при наведении на планшетных ПК
- `.hover:tablet-pc:order-2` - Порядок 2 при наведении на планшетных ПК
- `.hover:tablet-pc:order-1` - Порядок 1 при наведении на планшетных ПК
- `.hover:tablet-pc:order-0` - Порядок 0 при наведении на планшетных ПК
- `.hover:tablet-pc:order-first` - Порядок: первый при наведении на планшетных ПК
- `.hover:tablet-pc:order-last` - Порядок: последний при наведении на планшетных ПК
- `.tablet-pc:order-5` - Порядок 5 на планшетных ПК
- `.tablet-pc:order-4` - Порядок 4 на планшетных ПК
- `.tablet-pc:order-3` - Порядок 3 на планшетных ПК
- `.tablet-pc:order-2` - Порядок 2 на планшетных ПК
- `.tablet-pc:order-1` - Порядок 1 на планшетных ПК
- `.tablet-pc:order-0` - Порядок 0 на планшетных ПК
- `.tablet-pc:order-first` - Порядок: первый на планшетных ПК
- `.tablet-pc:order-last` - Порядок: последний на планшетных ПК

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - Отрицательный порядок 5 при наведении на планшетных ПК
- `.hover:tablet-pc:-order-4` - Отрицательный порядок 4 при наведении на планшетных ПК
- `.hover:tablet-pc:-order-3` - Отрицательный порядок 3 при наведении на планшетных ПК
- `.hover:tablet-pc:-order-2` - Отрицательный порядок 2 при наведении на планшетных ПК
- `.hover:tablet-pc:-order-1` - Отрицательный порядок 1 при наведении на планшетных ПК
- `.tablet-pc:-order-5` - Отрицательный порядок 5 на планшетных ПК
- `.tablet-pc:-order-4` - Отрицательный порядок 4 на планшетных ПК
- `.tablet-pc:-order-3` - Отрицательный порядок 3 на планшетных ПК
- `.tablet-pc:-order-2` - Отрицательный порядок 2 на планшетных ПК
- `.tablet-pc:-order-1` - Отрицательный порядок 1 на планшетных ПК

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - Порядок 5 при наведении на ПК
- `.hover:pc:order-4` - Порядок 4 при наведении на ПК
- `.hover:pc:order-3` - Порядок 3 при наведении на ПК
- `.hover:pc:order-2` - Порядок 2 при наведении на ПК
- `.hover:pc:order-1` - Порядок 1 при наведении на ПК
- `.hover:pc:order-0` - Порядок 0 при наведении на ПК
- `.hover:pc:order-first` - Порядок: первый при наведении на ПК
- `.hover:pc:order-last` - Порядок: последний при наведении на ПК
- `.pc:order-5` - Порядок 5 на ПК
- `.pc:order-4` - Порядок 4 на ПК
- `.pc:order-3` - Порядок 3 на ПК
- `.pc:order-2` - Порядок 2 на ПК
- `.pc:order-1` - Порядок 1 на ПК
- `.pc:order-0` - Порядок 0 на ПК
- `.pc:order-first` - Порядок: первый на ПК
- `.pc:order-last` - Порядок: последний на ПК

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - Отрицательный порядок 5 при наведении на ПК
- `.hover:pc:-order-4` - Отрицательный порядок 4 при наведении на ПК
- `.hover:pc:-order-3` - Отрицательный порядок 3 при наведении на ПК
- `.hover:pc:-order-2` - Отрицательный порядок 2 при наведении на ПК
- `.hover:pc:-order-1` - Отрицательный порядок 1 при наведении на ПК
- `.pc:-order-5` - Отрицательный порядок 5 на ПК
- `.pc:-order-4` - Отрицательный порядок 4 на ПК
- `.pc:-order-3` - Отрицательный порядок 3 на ПК
- `.pc:-order-2` - Отрицательный порядок 2 на ПК
- `.pc:-order-1` - Отрицательный порядок 1 на ПК

##### Order - Tv (>= 1200px)

- `.hover:tv:order-5` - Порядок 5 при наведении на ТВ
- `.hover:tv:order-4` - Порядок 4 при наведении на ТВ
- `.hover:tv:order-3` - Порядок 3 при наведении на ТВ
- `.hover:tv:order-2` - Порядок 2 при наведении на ТВ
- `.hover:tv:order-1` - Порядок 1 при наведении на ТВ
- `.hover:tv:order-0` - Порядок 0 при наведении на ТВ
- `.hover:tv:order-first` - Порядок: первый при наведении на ТВ
- `.hover:tv:order-last` - Порядок: последний при наведении на ТВ
- `.tv:order-5` - Порядок 5 на ТВ
- `.tv:order-4` - Порядок 4 на ТВ
- `.tv:order-3` - Порядок 3 на ТВ
- `.tv:order-2` - Порядок 2 на ТВ
- `.tv:order-1` - Порядок 1 на ТВ
- `.tv:order-0` - Порядок 0 на ТВ
- `.tv:order-first` - Порядок: первый на ТВ
- `.tv:order-last` - Порядок: последний на ТВ

##### Negative Order - Tv (>= 1200px)

- `.hover:tv:-order-5` - Отрицательный порядок 5 при наведении на телевизор
- `.hover:tv:-order-4` - Отрицательный порядок 4 при наведении на телевизор
- `.hover:tv:-order-3` - Отрицательный порядок 3 при наведении на ТВ
- `.hover:tv:-order-2` - Отрицательный порядок 2 при наведении на ТВ
- `.hover:tv:-order-1` - Отрицательный порядок 1 при наведении на телевизор
- `.tv:-order-5` - Отрицательный порядок 5 на ТВ
- `.tv:-order-4` - Отрицательный порядок 4 на ТВ
- `.tv:-order-3` - Отрицательный порядок 3 на ТВ
- `.tv:-order-2` - Отрицательный порядок 2 на ТВ
- `.tv:-order-1` - Отрицательный порядок 1 на ТВ

##### Order - Tablet Max (<= 768px)

- `.hover:tablet-max:order-5` - Порядок 5 при наведении на планшетах (макс.)
- `.hover:tablet-max:order-4` - Порядок 4 при наведении на планшетах (макс.)
- `.hover:tablet-max:order-3` - Порядок 3 при наведении на планшетах (макс.)
- `.hover:tablet-max:order-2` - Порядок 2 при наведении на планшетах (макс.)
- `.hover:tablet-max:order-1` - Порядок 1 при наведении на планшетах (макс.)
- `.hover:tablet-max:order-0` - Порядок 0 при наведении на планшетах (макс.)
- `.hover:tablet-max:order-first` - Порядок: первый при наведении на планшетах (макс.)
- `.hover:tablet-max:order-last` - Порядок: последний при наведении на планшетах (макс.)
- `.tablet-max:order-5` - Порядок 5 на планшетах (макс.)
- `.tablet-max:order-4` - Порядок 4 на планшетах (макс.)
- `.tablet-max:order-3` - Порядок 3 на планшетах (макс.)
- `.tablet-max:order-2` - Порядок 2 на планшетах (макс.)
- `.tablet-max:order-1` - Порядок 1 на планшетах (макс.)
- `.tablet-max:order-0` - Порядок 0 на планшетах (макс.)
- `.tablet-max:order-first` - Порядок: первый на планшетах (макс.)
- `.tablet-max:order-last` - Порядок: последний на планшетах (макс.)

##### Negative Order - Tablet Max (<= 768px)

- `.hover:tablet-max:-order-5` - Отрицательный порядок 5 при наведении на планшетах (макс.)
- `.hover:tablet-max:-order-4` - Отрицательный порядок 4 при наведении на планшетах (макс.)
- `.hover:tablet-max:-order-3` - Отрицательный порядок 3 при наведении на планшетах (макс.)
- `.hover:tablet-max:-order-2` - Отрицательный порядок 2 при наведении на планшетах (макс.)
- `.hover:tablet-max:-order-1` - Отрицательный порядок 1 при наведении на планшетах (макс.)
- `.tablet-max:-order-5` - Отрицательный порядок 5 на планшетах (макс.)
- `.tablet-max:-order-4` - Отрицательный порядок 4 на планшетах (макс.)
- `.tablet-max:-order-3` - Отрицательный порядок 3 на планшетах (макс.)
- `.tablet-max:-order-2` - Отрицательный порядок 2 на планшетах (макс.)
- `.tablet-max:-order-1` - Отрицательный порядок 1 на планшетах (макс.)

##### Order - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:order-5` - Порядок 5 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-4` - Порядок 4 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-3` - Порядок 3 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-2` - Порядок 2 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-1` - Порядок 1 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-0` - Порядок 0 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-first` - Порядок: первый при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:order-last` - Порядок: последний при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:order-5` - Порядок 5 на планшетных ПК (макс.)
- `.tablet-pc-max:order-4` - Порядок 4 на планшетных ПК (макс.)
- `.tablet-pc-max:order-3` - Порядок 3 на планшетных ПК (макс.)
- `.tablet-pc-max:order-2` - Порядок 2 на планшетных ПК (макс.)
- `.tablet-pc-max:order-1` - Порядок 1 на планшетных ПК (макс.)
- `.tablet-pc-max:order-0` - Порядок 0 на планшетных ПК (макс.)
- `.tablet-pc-max:order-first` - Порядок: первый на планшетных ПК (макс.)
- `.tablet-pc-max:order-last` - Порядок: последний на планшетных ПК (макс.)

##### Negative Order - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:-order-5` - Отрицательный порядок 5 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:-order-4` - Отрицательный порядок 4 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:-order-3` - Отрицательный порядок 3 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:-order-2` - Отрицательный порядок 2 при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:-order-1` - Отрицательный порядок 1 при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:-order-5` - Отрицательный порядок 5 на планшетных ПК (макс.)
- `.tablet-pc-max:-order-4` - Отрицательный порядок 4 на планшетных ПК (макс.)
- `.tablet-pc-max:-order-3` - Отрицательный порядок 3 на планшетных ПК (макс.)
- `.tablet-pc-max:-order-2` - Отрицательный порядок 2 на планшетных ПК (макс.)
- `.tablet-pc-max:-order-1` - Отрицательный порядок 1 на планшетных ПК (макс.)

##### Order - Pc Max (<= 1200px)

- `.hover:pc-max:order-5` - Порядок 5 при наведении на ПК (макс.)
- `.hover:pc-max:order-4` - Порядок 4 при наведении на ПК (макс.)
- `.hover:pc-max:order-3` - Порядок 3 при наведении на ПК (макс.)
- `.hover:pc-max:order-2` - Порядок 2 при наведении на ПК (макс.)
- `.hover:pc-max:order-1` - Порядок 1 при наведении на ПК (макс.)
- `.hover:pc-max:order-0` - Порядок 0 при наведении на ПК (макс.)
- `.hover:pc-max:order-first` - Порядок: первый при наведении на ПК (макс.)
- `.hover:pc-max:order-last` - Порядок: последний при наведении на ПК (макс.)
- `.pc-max:order-5` - Порядок 5 на ПК (макс.)
- `.pc-max:order-4` - Порядок 4 на ПК (макс.)
- `.pc-max:order-3` - Порядок 3 на ПК (макс.)
- `.pc-max:order-2` - Порядок 2 на ПК (макс.)
- `.pc-max:order-1` - Порядок 1 на ПК (макс.)
- `.pc-max:order-0` - Порядок 0 на ПК (макс.)
- `.pc-max:order-first` - Порядок: первый на ПК (макс.)
- `.pc-max:order-last` - Порядок: последний на ПК (макс.)

##### Negative Order - Pc Max (<= 1200px)

- `.hover:pc-max:-order-5` - Отрицательный порядок 5 при наведении на ПК макс.
- `.hover:pc-max:-order-4` - Отрицательный порядок 4 при наведении на ПК макс.
- `.hover:pc-max:-order-3` - Отрицательный порядок 3 при наведении на ПК макс.
- `.hover:pc-max:-order-2` - Отрицательный порядок 2 при наведении на ПК (макс.)
- `.hover:pc-max:-order-1` - Отрицательный порядок 1 при наведении на ПК (макс.)
- `.pc-max:-order-5` - Отрицательный порядок 5 на ПК (макс.)
- `.pc-max:-order-4` - Отрицательный порядок 4 на ПК (макс.)
- `.pc-max:-order-3` - Отрицательный порядок 3 на ПК (макс.)
- `.pc-max:-order-2` - Отрицательный порядок 2 на ПК (макс.)
- `.pc-max:-order-1` - Отрицательный порядок 1 на ПК (макс.)

## Spacing

### Margin

#### Margin All

- `.first:m-0` - Маржа Все 0rem в первую очередь
- `.hover:m-5` - Маржа Все 5rem при наведении
- `.hover:m-4.5` - Маржа Все 4.5rem при наведении
- `.hover:m-4` - Маржа Все 4rem при наведении
- `.hover:m-3.5` - Маржа Все 3.5rem при наведении
- `.hover:m-3` - Маржа Все 3rem при наведении
- `.hover:m-2.5` - Маржа Все 2.5rem при наведении
- `.hover:m-2` - Маржа Все 2rem при наведении
- `.hover:m-1.9` - Маржа Все 1.9rem при наведении
- `.hover:m-1.8` - Маржа Все 1.8rem при наведении
- `.hover:m-1.7` - Маржа Все 1.7rem при наведении
- `.hover:m-1.6` - Маржа Все 1.6rem при наведении
- `.hover:m-1.5` - Маржа Все 1.5rem при наведении
- `.hover:m-1.4` - Маржа Все 1.4rem при наведении
- `.hover:m-1.3` - Маржа Все 1.3rem при наведении
- `.hover:m-1.2` - Маржа Все 1.2rem при наведении
- `.hover:m-1.1` - Маржа Все 1.1rem при наведении
- `.hover:m-1` - Маржа Все 1rem при наведении
- `.hover:m-0.9` - Маржа Все 0.9rem при наведении
- `.hover:m-0.8` - Маржа Все 0.8rem при наведении
- `.hover:m-0.7` - Маржа Все 0.7rem при наведении
- `.hover:m-0.6` - Маржа Все 0.6rem при наведении
- `.hover:m-0.5` - Маржа Все 0.5rem при наведении
- `.hover:m-0.4` - Маржа Все 0.4rem при наведении
- `.hover:m-0.3` - Маржа Все 0.3rem при наведении
- `.hover:m-0.2` - Маржа Все 0,2rem при наведении
- `.hover:m-0.1` - Маржа Все 0,1rem при наведении
- `.hover:m-0` - Маржа Все 0rem при наведении
- `.hover:m-auto` - Маржа Все автоматически при наведении
- `.last:m-0` - Маржа Все 0rem на последнем
- `.m-5` - Маржа Все 5rem
- `.m-4.5` - Маржа Все 4.5rem
- `.m-4` - Маржа Все 4rem
- `.m-3.5` - Маржа Все 3.5rem
- `.m-3` - Маржа Все 3rem
- `.m-2.5` - Маржа Все 2.5rem
- `.m-2` - Маржа Все 2rem
- `.m-1.9` - Маржа Все 1.9rem
- `.m-1.8` - Маржа Все 1.8rem
- `.m-1.7` - Маржа Все 1.7rem
- `.m-1.6` - Маржа Все 1.6rem
- `.m-1.5` - Маржа Все 1.5rem
- `.m-1.4` - Маржа Все 1.4rem
- `.m-1.3` - Маржа Все 1.3rem
- `.m-1.2` - Маржа Все 1.2rem
- `.m-1.1` - Маржа Все 1.1rem
- `.m-1` - Маржа Все 1rem
- `.m-0.9` - Маржа Все 0.9rem
- `.m-0.8` - Маржа Все 0.8rem
- `.m-0.7` - Маржа Все 0.7rem
- `.m-0.6` - Маржа Все 0.6rem
- `.m-0.5` - Маржа Все 0.5rem
- `.m-0.4` - Маржа Все 0.4rem
- `.m-0.3` - Маржа Все 0.3rem
- `.m-0.2` - Маржа Все 0,2rem
- `.m-0.1` - Маржа Все 0,1rem
- `.m-0` - Маржа Все 0rem
- `.m-auto` - Маржа Все авто

#### Margin Bottom

- `.first:mb-0` - Нижняя маржа 0rem на первом месте
- `.hover:mb-100` - Нижняя маржа 100% при наведении
- `.hover:mb-75` - Нижняя маржа 75% при наведении
- `.hover:mb-50` - Нижняя маржа 50% при наведении
- `.hover:mb-25` - Нижняя маржа 25% при наведении
- `.hover:mb-5` - Нижняя маржа 5rem при наведении
- `.hover:mb-4.5` - Нижняя маржа 4.5rem при наведении
- `.hover:mb-4` - Нижняя маржа 4rem при наведении
- `.hover:mb-3.5` - Нижняя маржа 3.5rem при наведении
- `.hover:mb-3` - Нижняя маржа 3rem при наведении
- `.hover:mb-2.5` - Нижняя маржа 2.5rem при наведении
- `.hover:mb-2` - Нижняя маржа 2rem при наведении
- `.hover:mb-1.9` - Нижняя маржа 1.9rem при наведении
- `.hover:mb-1.8` - Нижняя маржа 1.8rem при наведении
- `.hover:mb-1.7` - Нижняя маржа 1.7rem при наведении
- `.hover:mb-1.6` - Нижняя маржа 1.6rem при наведении
- `.hover:mb-1.5` - Нижняя маржа 1.5rem при наведении
- `.hover:mb-1.4` - Нижняя маржа 1.4rem при наведении
- `.hover:mb-1.3` - Нижняя маржа 1.3rem при наведении
- `.hover:mb-1.2` - Нижняя маржа 1.2rem при наведении
- `.hover:mb-1.1` - Нижняя маржа 1.1rem при наведении
- `.hover:mb-1` - Нижняя маржа 1rem при наведении
- `.hover:mb-0.9` - Нижняя маржа 0.9rem при наведении
- `.hover:mb-0.8` - Нижняя маржа 0.8rem при наведении
- `.hover:mb-0.7` - Нижняя маржа 0.7rem при наведении
- `.hover:mb-0.6` - Нижняя маржа 0.6rem при наведении
- `.hover:mb-0.5` - Нижняя маржа 0.5rem при наведении
- `.hover:mb-0.4` - Нижняя маржа 0.4rem при наведении
- `.hover:mb-0.3` - Нижняя маржа 0.3rem при наведении
- `.hover:mb-0.2` - Нижняя маржа 0.2rem при наведении
- `.hover:mb-0.1` - Нижняя маржа 0,1rem при наведении
- `.hover:mb-0` - Нижняя маржа 0rem при наведении
- `.hover:mb-auto` - Нижнее поле автоматически при наведении
- `.last:mb-0` - Нижняя маржа 0rem на последнем
- `.mb-100` - Нижняя маржа 100%
- `.mb-75` - Нижняя маржа 75%
- `.mb-50` - Нижняя маржа 50%
- `.mb-25` - Нижняя маржа 25%
- `.mb-5` - Нижняя маржа 5rem
- `.mb-4.5` - Нижняя маржа 4.5rem
- `.mb-4` - Нижняя маржа 4rem
- `.mb-3.5` - Нижняя маржа 3.5rem
- `.mb-3` - Нижняя маржа 3rem
- `.mb-2.5` - Нижняя маржа 2.5rem
- `.mb-2` - Нижняя маржа 2rem
- `.mb-1.9` - Нижняя маржа 1.9rem
- `.mb-1.8` - Нижняя маржа 1.8rem
- `.mb-1.7` - Нижняя маржа 1.7rem
- `.mb-1.6` - Нижняя маржа 1.6rem
- `.mb-1.5` - Нижняя маржа 1.5rem
- `.mb-1.4` - Нижняя маржа 1.4rem
- `.mb-1.3` - Нижняя маржа 1.3rem
- `.mb-1.2` - Нижняя маржа 1.2rem
- `.mb-1.1` - Нижняя маржа 1.1rem
- `.mb-1` - Нижняя маржа: 1rem
- `.mb-0.9` - Нижняя маржа 0.9rem
- `.mb-0.8` - Нижняя маржа 0.8rem
- `.mb-0.7` - Нижняя маржа 0.7rem
- `.mb-0.6` - Нижняя маржа 0.6rem
- `.mb-0.5` - Нижняя маржа 0.5rem
- `.mb-0.4` - Нижняя маржа 0.4rem
- `.mb-0.3` - Нижняя маржа 0.3rem
- `.mb-0.2` - Нижняя маржа 0,2rem
- `.mb-0.1` - Нижняя маржа 0,1rem
- `.mb-0` - Нижняя маржа 0rem
- `.mb-auto` - Нижнее поле авто

#### Margin End

- `.hover:me-2` - Маржа Конец 2rem при наведении
- `.hover:me-1.5` - Маржа Конец 1.5rem при наведении
- `.hover:me-1` - Маржа Конец 1rem при наведении
- `.hover:me-0.5` - Маржа Конец 0.5rem при наведении
- `.hover:me-0` - Маржа Конец 0rem при наведении
- `.me-2` - Маржа Конец 2rem
- `.me-1.5` - Маржа Конец 1.5rem
- `.me-1` - Маржа Конец 1rem
- `.me-0.5` - Маржа Конец 0.5rem
- `.me-0` - Маржа Конец 0rem

#### Margin Left

- `.first:ml-0` - Маржа слева 0rem на первом месте
- `.hover:ml-100` - Маржа слева 100% при наведении
- `.hover:ml-75` - Маржа слева 75% при наведении
- `.hover:ml-50` - Маржа слева 50% при наведении
- `.hover:ml-25` - Маржа слева 25% при наведении
- `.hover:ml-5` - Маржа слева 5rem при наведении
- `.hover:ml-4.5` - Маржа слева 4.5rem при наведении
- `.hover:ml-4` - Маржа слева 4rem при наведении
- `.hover:ml-3.5` - Маржа слева 3.5rem при наведении
- `.hover:ml-3` - Маржа слева 3rem при наведении
- `.hover:ml-2.5` - Маржа слева 2.5rem при наведении
- `.hover:ml-2` - Маржа слева 2rem при наведении
- `.hover:ml-1.9` - Маржа слева 1.9rem при наведении
- `.hover:ml-1.8` - Маржа слева 1.8rem при наведении
- `.hover:ml-1.7` - Маржа слева 1.7rem при наведении
- `.hover:ml-1.6` - Маржа слева 1.6rem при наведении
- `.hover:ml-1.5` - Маржа слева 1.5rem при наведении
- `.hover:ml-1.4` - Маржа слева 1.4rem при наведении
- `.hover:ml-1.3` - Маржа слева 1.3rem при наведении
- `.hover:ml-1.2` - Маржа слева 1.2rem при наведении
- `.hover:ml-1.1` - Маржа слева 1.1rem при наведении
- `.hover:ml-1` - Левое поле 1rem при наведении
- `.hover:ml-0.9` - Маржа слева 0.9rem при наведении
- `.hover:ml-0.8` - Маржа слева 0.8rem при наведении
- `.hover:ml-0.7` - Маржа слева 0.7rem при наведении
- `.hover:ml-0.6` - Маржа слева 0.6rem при наведении
- `.hover:ml-0.5` - Маржа слева 0.5rem при наведении
- `.hover:ml-0.4` - Маржа слева 0.4rem при наведении
- `.hover:ml-0.3` - Маржа слева 0.3rem при наведении
- `.hover:ml-0.2` - Маржа слева 0.2rem при наведении
- `.hover:ml-0.1` - Маржа слева 0,1rem при наведении
- `.hover:ml-0` - Маржа слева 0rem при наведении
- `.hover:ml-auto` - Поле слева автоматически при наведении
- `.last:ml-0` - Маржа слева 0rem на последнем
- `.ml-100` - Левое поле 100%
- `.ml-75` - Маржа слева 75%
- `.ml-50` - Левое поле 50%
- `.ml-25` - Маржа слева 25%
- `.ml-5` - Маржа слева 5rem
- `.ml-4.5` - Левое поле 4.5rem
- `.ml-4` - Маржа слева 4rem
- `.ml-3.5` - Левое поле 3.5rem
- `.ml-3` - Маржа слева 3rem
- `.ml-2.5` - Левое поле 2.5rem
- `.ml-2` - Маржа слева 2rem
- `.ml-1.9` - Левое поле 1.9rem
- `.ml-1.8` - Левое поле 1.8rem
- `.ml-1.7` - Левое поле 1.7rem
- `.ml-1.6` - Левое поле 1.6rem
- `.ml-1.5` - Левое поле 1.5rem
- `.ml-1.4` - Левое поле 1.4rem
- `.ml-1.3` - Левое поле 1.3rem
- `.ml-1.2` - Левое поле 1.2rem
- `.ml-1.1` - Левое поле 1.1rem
- `.ml-1` - Левое поле 1rem
- `.ml-0.9` - Левое поле 0.9rem
- `.ml-0.8` - Левое поле 0.8rem
- `.ml-0.7` - Левое поле 0.7rem
- `.ml-0.6` - Левое поле 0.6rem
- `.ml-0.5` - Левое поле 0.5rem
- `.ml-0.4` - Левое поле 0.4rem
- `.ml-0.3` - Левое поле 0.3rem
- `.ml-0.2` - Левая маржа 0,2rem
- `.ml-0.1` - Левая маржа 0,1rem
- `.ml-0` - Левое поле 0rem
- `.ml-auto` - Поле слева авто

#### Margin Right

- `.first:mr-0` - Маржа справа 0rem на первом месте
- `.hover:mr-100` - Маржа справа 100% при наведении
- `.hover:mr-75` - Маржа справа 75% при наведении
- `.hover:mr-50` - Маржа справа 50% при наведении
- `.hover:mr-25` - Маржа справа 25% при наведении
- `.hover:mr-5` - Маржа справа 5rem при наведении
- `.hover:mr-4.5` - Маржа справа 4.5rem при наведении
- `.hover:mr-4` - Маржа справа 4rem при наведении
- `.hover:mr-3.5` - Маржа справа 3.5rem при наведении
- `.hover:mr-3` - Маржа справа 3rem при наведении
- `.hover:mr-2.5` - Маржа справа 2.5rem при наведении
- `.hover:mr-2` - Маржа справа 2rem при наведении
- `.hover:mr-1.9` - Маржа справа 1.9rem при наведении
- `.hover:mr-1.8` - Маржа справа 1.8rem при наведении
- `.hover:mr-1.7` - Маржа справа 1.7rem при наведении
- `.hover:mr-1.6` - Маржа справа 1.6rem при наведении
- `.hover:mr-1.5` - Маржа справа 1.5rem при наведении
- `.hover:mr-1.4` - Маржа справа 1.4rem при наведении
- `.hover:mr-1.3` - Маржа справа 1.3rem при наведении
- `.hover:mr-1.2` - Маржа справа 1.2rem при наведении
- `.hover:mr-1.1` - Маржа справа 1.1rem при наведении
- `.hover:mr-1` - Маржа справа 1rem при наведении
- `.hover:mr-0.9` - Маржа справа 0.9rem при наведении
- `.hover:mr-0.8` - Маржа справа 0.8rem при наведении
- `.hover:mr-0.7` - Маржа справа 0.7rem при наведении
- `.hover:mr-0.6` - Маржа справа 0.6rem при наведении
- `.hover:mr-0.5` - Маржа справа 0.5rem при наведении
- `.hover:mr-0.4` - Маржа справа 0.4rem при наведении
- `.hover:mr-0.3` - Маржа справа 0.3rem при наведении
- `.hover:mr-0.2` - Маржа справа 0.2rem при наведении
- `.hover:mr-0.1` - Маржа справа 0,1rem при наведении
- `.hover:mr-0` - Маржа справа 0rem при наведении
- `.hover:mr-auto` - Поле справа автоматически при наведении
- `.last:mr-0` - Маржа справа 0rem на последнем
- `.mr-100` - Маржа справа 100%
- `.mr-75` - Маржа справа 75%
- `.mr-50` - Маржа справа 50%
- `.mr-25` - Маржа справа 25%
- `.mr-5` - Маржа справа 5rem
- `.mr-4.5` - Маржа справа 4.5rem
- `.mr-4` - Маржа справа 4rem
- `.mr-3.5` - Маржа справа 3.5rem
- `.mr-3` - Маржа справа 3rem
- `.mr-2.5` - Маржа справа 2.5rem
- `.mr-2` - Маржа справа 2rem
- `.mr-1.9` - Маржа справа 1.9rem
- `.mr-1.8` - Маржа справа 1.8rem
- `.mr-1.7` - Маржа справа 1.7rem
- `.mr-1.6` - Маржа справа 1.6rem
- `.mr-1.5` - Маржа справа 1.5rem
- `.mr-1.4` - Маржа справа 1.4rem
- `.mr-1.3` - Маржа справа 1.3rem
- `.mr-1.2` - Маржа справа 1.2rem
- `.mr-1.1` - Маржа справа 1.1rem
- `.mr-1` - Маржа справа 1rem
- `.mr-0.9` - Маржа справа 0.9rem
- `.mr-0.8` - Маржа справа 0.8rem
- `.mr-0.7` - Маржа справа 0.7rem
- `.mr-0.6` - Маржа справа 0.6rem
- `.mr-0.5` - Маржа справа 0.5rem
- `.mr-0.4` - Маржа справа 0.4rem
- `.mr-0.3` - Маржа справа 0.3rem
- `.mr-0.2` - Маржа справа 0,2rem
- `.mr-0.1` - Маржа справа 0,1rem
- `.mr-0` - Маржа справа 0rem
- `.mr-auto` - Поле справа авто

#### Margin Start

- `.hover:ms-2` - Маржа Старт 2rem при наведении
- `.hover:ms-1.5` - Маржа Старт 1,5rem при наведении
- `.hover:ms-1` - Маржа Старт 1rem при наведении
- `.hover:ms-0.5` - Маржа Старт 0,5rem при наведении
- `.hover:ms-0` - Маржа Старт 0rem при наведении
- `.ms-2` - Маржа Старт 2rem
- `.ms-1.5` - Маржа Старт 1,5rem
- `.ms-1` - Маржа Старт 1rem
- `.ms-0.5` - Маржа Старт 0,5rem
- `.ms-0` - Маржа Старт 0rem

#### Margin Top

- `.first:mt-0` - Маржа сверху 0rem для первого элемента
- `.hover:mt-100` - Маржа сверху 100% при наведении
- `.hover:mt-75` - Маржа сверху 75% при наведении
- `.hover:mt-50` - Маржа сверху 50% при наведении
- `.hover:mt-25` - Маржа сверху 25% при наведении
- `.hover:mt-5` - Маржа сверху 5rem при наведении
- `.hover:mt-4.5` - Маржа сверху 4.5rem при наведении
- `.hover:mt-4` - Маржа сверху 4rem при наведении
- `.hover:mt-3.5` - Маржа сверху 3.5rem при наведении
- `.hover:mt-3` - Маржа сверху 3rem при наведении
- `.hover:mt-2.5` - Маржа сверху 2.5rem при наведении
- `.hover:mt-2` - Маржа сверху 2rem при наведении
- `.hover:mt-1.9` - Маржа сверху 1.9rem при наведении
- `.hover:mt-1.8` - Маржа сверху 1.8rem при наведении
- `.hover:mt-1.7` - Маржа сверху 1.7rem при наведении
- `.hover:mt-1.6` - Маржа сверху 1.6rem при наведении
- `.hover:mt-1.5` - Маржа сверху 1.5rem при наведении
- `.hover:mt-1.4` - Маржа сверху 1.4rem при наведении
- `.hover:mt-1.3` - Маржа сверху 1.3rem при наведении
- `.hover:mt-1.2` - Маржа сверху 1.2rem при наведении
- `.hover:mt-1.1` - Маржа сверху 1.1rem при наведении
- `.hover:mt-1` - Маржа сверху 1rem при наведении
- `.hover:mt-0.9` - Маржа сверху 0.9rem при наведении
- `.hover:mt-0.8` - Маржа сверху 0.8rem при наведении
- `.hover:mt-0.7` - Маржа сверху 0.7rem при наведении
- `.hover:mt-0.6` - Маржа сверху 0.6rem при наведении
- `.hover:mt-0.5` - Маржа сверху 0.5rem при наведении
- `.hover:mt-0.4` - Маржа сверху 0.4rem при наведении
- `.hover:mt-0.3` - Маржа сверху 0.3rem при наведении
- `.hover:mt-0.2` - Верхняя маржа 0,2rem при наведении
- `.hover:mt-0.1` - Верхняя маржа 0,1rem при наведении
- `.hover:mt-0` - Маржа сверху 0rem при наведении
- `.hover:mt-auto` - Маржа сверху авто при наведении
- `.last:mt-0` - Маржа сверху 0rem для последнего элемента
- `.mt-100` - Маржа сверху 100%
- `.mt-75` - Маржа сверху 75%
- `.mt-50` - Маржа сверху 50%
- `.mt-25` - Маржа сверху 25%
- `.mt-5` - Маржа сверху 5rem
- `.mt-4.5` - Маржа сверху 4.5rem
- `.mt-4` - Маржа сверху 4rem
- `.mt-3.5` - Маржа сверху 3.5rem
- `.mt-3` - Маржа сверху 3rem
- `.mt-2.5` - Маржа сверху 2.5rem
- `.mt-2` - Маржа сверху 2rem
- `.mt-1.9` - Маржа сверху 1.9rem
- `.mt-1.8` - Маржа сверху 1.8rem
- `.mt-1.7` - Маржа сверху 1.7rem
- `.mt-1.6` - Маржа сверху 1.6rem
- `.mt-1.5` - Маржа сверху 1.5rem
- `.mt-1.4` - Маржа сверху 1.4rem
- `.mt-1.3` - Маржа сверху 1.3rem
- `.mt-1.2` - Маржа сверху 1.2rem
- `.mt-1.1` - Маржа сверху 1.1rem
- `.mt-1` - Маржа сверху 1rem
- `.mt-0.9` - Маржа сверху 0.9rem
- `.mt-0.8` - Маржа сверху 0.8rem
- `.mt-0.7` - Маржа сверху 0.7rem
- `.mt-0.6` - Маржа сверху 0.6rem
- `.mt-0.5` - Маржа сверху 0.5rem
- `.mt-0.4` - Маржа сверху 0.4rem
- `.mt-0.3` - Маржа сверху 0.3rem
- `.mt-0.2` - Верхняя маржа 0,2rem
- `.mt-0.1` - Верхняя маржа 0,1rem
- `.mt-0` - Маржа сверху 0rem
- `.mt-auto` - Маржа сверху авто

#### Margin X-Axis

- `.hover:mx-100` - Маржа X-Axis 100% при наведении
- `.hover:mx-75` - Маржа X-Axis 75% при наведении
- `.hover:mx-50` - Маржа по оси X 50% при наведении
- `.hover:mx-25` - Маржа X-Axis 25% при наведении
- `.hover:mx-5` - Маржа X-Axis 5rem при наведении
- `.hover:mx-4.5` - Маржа X-Axis 4.5rem при наведении
- `.hover:mx-4` - Маржа X-Axis 4rem при наведении
- `.hover:mx-3.5` - Маржа X-Axis 3.5rem при наведении
- `.hover:mx-3` - Маржа X-Axis 3rem при наведении
- `.hover:mx-2.5` - Маржа X-Axis 2.5rem при наведении
- `.hover:mx-2` - Маржа X-Axis 2rem при наведении
- `.hover:mx-1.9` - Маржа X-Axis 1.9rem при наведении
- `.hover:mx-1.8` - Маржа X-Axis 1.8rem при наведении
- `.hover:mx-1.7` - Маржа X-Axis 1.7rem при наведении
- `.hover:mx-1.6` - Маржа X-Axis 1.6rem при наведении
- `.hover:mx-1.5` - Маржа X-Axis 1.5rem при наведении
- `.hover:mx-1.4` - Маржа X-Axis 1.4rem при наведении
- `.hover:mx-1.3` - Маржа X-Axis 1.3rem при наведении
- `.hover:mx-1.2` - Маржа X-Axis 1.2rem при наведении
- `.hover:mx-1.1` - Маржа X-Axis 1.1rem при наведении
- `.hover:mx-1` - Маржа X-Axis 1rem при наведении
- `.hover:mx-0.9` - Маржа X-Axis 0.9rem при наведении
- `.hover:mx-0.8` - Маржа X-Axis 0.8rem при наведении
- `.hover:mx-0.7` - Маржа X-Axis 0.7rem при наведении
- `.hover:mx-0.6` - Маржа X-Axis 0.6rem при наведении
- `.hover:mx-0.5` - Маржа X-Axis 0.5rem при наведении
- `.hover:mx-0.4` - Маржа X-Axis 0.4rem при наведении
- `.hover:mx-0.3` - Маржа X-Axis 0.3rem при наведении
- `.hover:mx-0.2` - Маржа по оси X: 0,2rem при наведении
- `.hover:mx-0.1` - Маржа по оси X: 0,1rem при наведении
- `.hover:mx-0` - Маржа X-Axis 0rem при наведении
- `.hover:mx-auto` - Маржа по оси X автоматически при наведении
- `.mx-100` - Маржа по оси X: 100%
- `.mx-75` - Маржа по оси X: 75%
- `.mx-50` - Маржа по оси X: 50%
- `.mx-25` - Маржа по оси X: 25%
- `.mx-5` - Маржа по оси X 5rem
- `.mx-4.5` - Маржа по оси X: 4.5rem
- `.mx-4` - Маржа по оси X 4rem
- `.mx-3.5` - Маржа по оси X: 3.5rem
- `.mx-3` - Маржа по оси X: 3rem
- `.mx-2.5` - Маржа по оси X: 2.5rem
- `.mx-2` - Маржа по оси X: 2rem
- `.mx-1.9` - Маржа по оси X: 1.9rem
- `.mx-1.8` - Маржа по оси X: 1.8rem
- `.mx-1.7` - Маржа по оси X: 1.7rem
- `.mx-1.6` - Маржа по оси X: 1.6rem
- `.mx-1.5` - Маржа по оси X: 1.5rem
- `.mx-1.4` - Маржа по оси X: 1.4rem
- `.mx-1.3` - Маржа по оси X: 1.3rem
- `.mx-1.2` - Маржа по оси X: 1.2rem
- `.mx-1.1` - Маржа по оси X: 1.1rem
- `.mx-1` - Маржа по оси X: 1rem
- `.mx-0.9` - Маржа по оси X: 0.9rem
- `.mx-0.8` - Маржа по оси X: 0.8rem
- `.mx-0.7` - Маржа по оси X: 0.7rem
- `.mx-0.6` - Маржа по оси X: 0.6rem
- `.mx-0.5` - Маржа по оси X: 0.5rem
- `.mx-0.4` - Маржа по оси X: 0.4rem
- `.mx-0.3` - Маржа по оси X: 0.3rem
- `.mx-0.2` - Маржа по оси X: 0.2rem
- `.mx-0.1` - Маржа по оси X: 0.1rem
- `.mx-0` - Маржа по оси X: 0rem
- `.mx-auto` - Маржа по оси X, авто

#### Margin Y-Axis

- `.hover:my-100` - Маржа по оси Y: 100% при наведении
- `.hover:my-75` - Маржа по оси Y 75% при наведении
- `.hover:my-50` - Маржа по оси Y 50% при наведении
- `.hover:my-25` - Маржа по оси Y 25% при наведении
- `.hover:my-5` - Маржа по оси Y 5rem при наведении
- `.hover:my-4.5` - Маржа оси Y 4.5rem при наведении
- `.hover:my-4` - Маржа по оси Y 4rem при наведении
- `.hover:my-3.5` - Маржа оси Y 3.5rem при наведении
- `.hover:my-3` - Маржа по оси Y 3rem при наведении
- `.hover:my-2.5` - Маржа оси Y 2.5rem при наведении
- `.hover:my-2` - Маржа по оси Y 2rem при наведении
- `.hover:my-1.9` - Маржа оси Y 1.9rem при наведении
- `.hover:my-1.8` - Маржа оси Y 1.8rem при наведении
- `.hover:my-1.7` - Маржа оси Y 1.7rem при наведении
- `.hover:my-1.6` - Маржа оси Y 1.6rem при наведении
- `.hover:my-1.5` - Маржа оси Y 1.5rem при наведении
- `.hover:my-1.4` - Маржа оси Y 1.4rem при наведении
- `.hover:my-1.3` - Маржа оси Y 1.3rem при наведении
- `.hover:my-1.2` - Маржа оси Y 1.2rem при наведении
- `.hover:my-1.1` - Маржа оси Y 1.1rem при наведении
- `.hover:my-1` - Маржа по оси Y: 1rem при наведении
- `.hover:my-0.9` - Маржа оси Y 0.9rem при наведении
- `.hover:my-0.8` - Маржа оси Y 0.8rem при наведении
- `.hover:my-0.7` - Маржа оси Y 0.7rem при наведении
- `.hover:my-0.6` - Маржа оси Y 0.6rem при наведении
- `.hover:my-0.5` - Маржа оси Y 0.5rem при наведении
- `.hover:my-0.4` - Маржа оси Y 0.4rem при наведении
- `.hover:my-0.3` - Маржа оси Y 0.3rem при наведении
- `.hover:my-0.2` - Маржа по оси Y: 0,2rem при наведении
- `.hover:my-0.1` - Маржа по оси Y: 0,1rem при наведении
- `.hover:my-0` - Маржа оси Y 0rem при наведении
- `.hover:my-auto` - Поле по оси Y, авто при наведении
- `.my-100` - Поле по оси Y 100%
- `.my-75` - Поле по оси Y 75%
- `.my-50` - Поле по оси Y 50%
- `.my-25` - Поле по оси Y 25%
- `.my-5` - Поле по оси Y 5rem
- `.my-4.5` - Поле по оси Y 4.5rem
- `.my-4` - Поле по оси Y 4rem
- `.my-3.5` - Поле по оси Y 3.5rem
- `.my-3` - Маржа по оси Y 3rem
- `.my-2.5` - Поле по оси Y 2.5rem
- `.my-2` - Поле по оси Y 2rem
- `.my-1.9` - Поле по оси Y 1.9rem
- `.my-1.8` - Поле по оси Y 1.8rem
- `.my-1.7` - Поле по оси Y 1.7rem
- `.my-1.6` - Поле по оси Y 1.6rem
- `.my-1.5` - Поле по оси Y 1.5rem
- `.my-1.4` - Поле по оси Y 1.4rem
- `.my-1.3` - Поле по оси Y 1.3rem
- `.my-1.2` - Поле по оси Y 1.2rem
- `.my-1.1` - Поле по оси Y 1.1rem
- `.my-1` - Поле по оси Y 1rem
- `.my-0.9` - Поле по оси Y 0.9rem
- `.my-0.8` - Поле по оси Y 0.8rem
- `.my-0.7` - Поле по оси Y 0.7rem
- `.my-0.6` - Поле по оси Y 0.6rem
- `.my-0.5` - Поле по оси Y 0.5rem
- `.my-0.4` - Поле по оси Y 0.4rem
- `.my-0.3` - Поле по оси Y 0.3rem
- `.my-0.2` - Поле по оси Y 0.2rem
- `.my-0.1` - Поле по оси Y 0.1rem
- `.my-0` - Поле по оси Y 0rem
- `.my-auto` - Поле по оси Y, авто

### Padding

#### Padding All

- `.first:p-0` - Внутренний отступ со всех сторон 0rem для первого элемента
- `.hover:p-5` - Внутренний отступ со всех сторон 5rem при наведении
- `.hover:p-4.5` - Внутренний отступ со всех сторон 4.5rem при наведении
- `.hover:p-4` - Внутренний отступ со всех сторон 4rem при наведении
- `.hover:p-3.5` - Внутренний отступ со всех сторон 3.5rem при наведении
- `.hover:p-3` - Внутренний отступ со всех сторон 3rem при наведении
- `.hover:p-2.5` - Внутренний отступ со всех сторон 2.5rem при наведении
- `.hover:p-2` - Внутренний отступ со всех сторон 2rem при наведении
- `.hover:p-1.9` - Внутренний отступ со всех сторон 1.9rem при наведении
- `.hover:p-1.8` - Внутренний отступ со всех сторон 1.8rem при наведении
- `.hover:p-1.7` - Внутренний отступ со всех сторон 1.7rem при наведении
- `.hover:p-1.6` - Внутренний отступ со всех сторон 1.6rem при наведении
- `.hover:p-1.5` - Внутренний отступ со всех сторон 1.5rem при наведении
- `.hover:p-1.4` - Внутренний отступ со всех сторон 1.4rem при наведении
- `.hover:p-1.3` - Внутренний отступ со всех сторон 1.3rem при наведении
- `.hover:p-1.2` - Внутренний отступ со всех сторон 1.2rem при наведении
- `.hover:p-1.1` - Внутренний отступ со всех сторон 1.1rem при наведении
- `.hover:p-1` - Внутренний отступ со всех сторон 1rem при наведении
- `.hover:p-0.9` - Внутренний отступ со всех сторон 0.9rem при наведении
- `.hover:p-0.8` - Внутренний отступ со всех сторон 0.8rem при наведении
- `.hover:p-0.7` - Внутренний отступ со всех сторон 0.7rem при наведении
- `.hover:p-0.6` - Внутренний отступ со всех сторон 0.6rem при наведении
- `.hover:p-0.5` - Внутренний отступ со всех сторон 0.5rem при наведении
- `.hover:p-0.4` - Внутренний отступ со всех сторон 0.4rem при наведении
- `.hover:p-0.3` - Внутренний отступ со всех сторон 0.3rem при наведении
- `.hover:p-0.2` - Внутренний отступ со всех сторон 0.2rem при наведении
- `.hover:p-0.1` - Внутренний отступ со всех сторон 0.1rem при наведении
- `.hover:p-0` - Внутренний отступ со всех сторон 0rem при наведении
- `.last:p-0` - Внутренний отступ со всех сторон 0rem для последнего элемента
- `.p-5` - Внутренний отступ со всех сторон 5rem
- `.p-4.5` - Внутренний отступ со всех сторон 4.5rem
- `.p-4` - Внутренний отступ со всех сторон 4rem
- `.p-3.5` - Внутренний отступ со всех сторон 3.5rem
- `.p-3` - Внутренний отступ со всех сторон 3rem
- `.p-2.5` - Внутренний отступ со всех сторон 2.5rem
- `.p-2` - Внутренний отступ со всех сторон 2rem
- `.p-1.9` - Внутренний отступ со всех сторон 1.9rem
- `.p-1.8` - Внутренний отступ со всех сторон 1.8rem
- `.p-1.7` - Внутренний отступ со всех сторон 1.7rem
- `.p-1.6` - Внутренний отступ со всех сторон 1.6rem
- `.p-1.5` - Внутренний отступ со всех сторон 1.5rem
- `.p-1.4` - Внутренний отступ со всех сторон 1.4rem
- `.p-1.3` - Внутренний отступ со всех сторон 1.3rem
- `.p-1.2` - Внутренний отступ со всех сторон 1.2rem
- `.p-1.1` - Внутренний отступ со всех сторон 1.1rem
- `.p-1` - Внутренний отступ со всех сторон 1rem
- `.p-0.9` - Внутренний отступ со всех сторон 0.9rem
- `.p-0.8` - Внутренний отступ со всех сторон 0.8rem
- `.p-0.7` - Внутренний отступ со всех сторон 0.7rem
- `.p-0.6` - Внутренний отступ со всех сторон 0.6rem
- `.p-0.5` - Внутренний отступ со всех сторон 0.5rem
- `.p-0.4` - Внутренний отступ со всех сторон 0.4rem
- `.p-0.3` - Внутренний отступ со всех сторон 0.3rem
- `.p-0.2` - Внутренний отступ со всех сторон 0.2rem
- `.p-0.1` - Внутренний отступ со всех сторон 0.1rem
- `.p-0` - Внутренний отступ со всех сторон 0rem

#### Padding Bottom

- `.first:pb-0` - Внутренний отступ снизу 0rem для первого элемента
- `.hover:pb-100` - Внутренний отступ снизу 100% при наведении
- `.hover:pb-75` - Внутренний отступ снизу 75% при наведении
- `.hover:pb-50` - Внутренний отступ снизу 50% при наведении
- `.hover:pb-25` - Внутренний отступ снизу 25% при наведении
- `.hover:pb-5` - Внутренний отступ снизу 5rem при наведении
- `.hover:pb-4.5` - Внутренний отступ снизу 4.5rem при наведении
- `.hover:pb-4` - Внутренний отступ снизу 4rem при наведении
- `.hover:pb-3.5` - Внутренний отступ снизу 3.5rem при наведении
- `.hover:pb-3` - Внутренний отступ снизу 3rem при наведении
- `.hover:pb-2.5` - Внутренний отступ снизу 2.5rem при наведении
- `.hover:pb-2` - Внутренний отступ снизу 2rem при наведении
- `.hover:pb-1.9` - Внутренний отступ снизу 1.9rem при наведении
- `.hover:pb-1.8` - Внутренний отступ снизу 1.8rem при наведении
- `.hover:pb-1.7` - Внутренний отступ снизу 1.7rem при наведении
- `.hover:pb-1.6` - Внутренний отступ снизу 1.6rem при наведении
- `.hover:pb-1.5` - Внутренний отступ снизу 1.5rem при наведении
- `.hover:pb-1.4` - Внутренний отступ снизу 1.4rem при наведении
- `.hover:pb-1.3` - Внутренний отступ снизу 1.3rem при наведении
- `.hover:pb-1.2` - Внутренний отступ снизу 1.2rem при наведении
- `.hover:pb-1.1` - Внутренний отступ снизу 1.1rem при наведении
- `.hover:pb-1` - Внутренний отступ снизу 1rem при наведении
- `.hover:pb-0.9` - Внутренний отступ снизу 0.9rem при наведении
- `.hover:pb-0.8` - Внутренний отступ снизу 0.8rem при наведении
- `.hover:pb-0.7` - Внутренний отступ снизу 0.7rem при наведении
- `.hover:pb-0.6` - Внутренний отступ снизу 0.6rem при наведении
- `.hover:pb-0.5` - Внутренний отступ снизу 0.5rem при наведении
- `.hover:pb-0.4` - Внутренний отступ снизу 0.4rem при наведении
- `.hover:pb-0.3` - Внутренний отступ снизу 0.3rem при наведении
- `.hover:pb-0.2` - Внутренний отступ снизу 0.2rem при наведении
- `.hover:pb-0.1` - Внутренний отступ снизу 0.1rem при наведении
- `.hover:pb-0` - Внутренний отступ снизу 0rem при наведении
- `.last:pb-0` - Внутренний отступ снизу 0rem для последнего элемента
- `.pb-100` - Внутренний отступ снизу 100%
- `.pb-75` - Внутренний отступ снизу 75%
- `.pb-50` - Внутренний отступ снизу 50%
- `.pb-25` - Внутренний отступ снизу 25%
- `.pb-5` - Внутренний отступ снизу 5rem
- `.pb-4.5` - Внутренний отступ снизу 4.5rem
- `.pb-4` - Внутренний отступ снизу 4rem
- `.pb-3.5` - Внутренний отступ снизу 3.5rem
- `.pb-3` - Внутренний отступ снизу 3rem
- `.pb-2.5` - Внутренний отступ снизу 2.5rem
- `.pb-2` - Внутренний отступ снизу 2rem
- `.pb-1.9` - Внутренний отступ снизу 1.9rem
- `.pb-1.8` - Внутренний отступ снизу 1.8rem
- `.pb-1.7` - Внутренний отступ снизу 1.7rem
- `.pb-1.6` - Внутренний отступ снизу 1.6rem
- `.pb-1.5` - Внутренний отступ снизу 1.5rem
- `.pb-1.4` - Внутренний отступ снизу 1.4rem
- `.pb-1.3` - Внутренний отступ снизу 1.3rem
- `.pb-1.2` - Внутренний отступ снизу 1.2rem
- `.pb-1.1` - Внутренний отступ снизу 1.1rem
- `.pb-1` - Внутренний отступ снизу 1rem
- `.pb-0.9` - Внутренний отступ снизу 0.9rem
- `.pb-0.8` - Внутренний отступ снизу 0.8rem
- `.pb-0.7` - Внутренний отступ снизу 0.7rem
- `.pb-0.6` - Внутренний отступ снизу 0.6rem
- `.pb-0.5` - Внутренний отступ снизу 0.5rem
- `.pb-0.4` - Внутренний отступ снизу 0.4rem
- `.pb-0.3` - Внутренний отступ снизу 0.3rem
- `.pb-0.2` - Внутренний отступ снизу 0.2rem
- `.pb-0.1` - Внутренний отступ снизу 0.1rem
- `.pb-0` - Внутренний отступ снизу 0rem

#### Padding Left

- `.first:pl-0` - Внутренний отступ слева 0rem для первого элемента
- `.hover:pl-5` - Внутренний отступ слева 5rem при наведении
- `.hover:pl-4.5` - Внутренний отступ слева 4.5rem при наведении
- `.hover:pl-4` - Внутренний отступ слева 4rem при наведении
- `.hover:pl-3.5` - Внутренний отступ слева 3.5rem при наведении
- `.hover:pl-3` - Внутренний отступ слева 3rem при наведении
- `.hover:pl-2.5` - Внутренний отступ слева 2.5rem при наведении
- `.hover:pl-2` - Внутренний отступ слева 2rem при наведении
- `.hover:pl-1.9` - Внутренний отступ слева 1.9rem при наведении
- `.hover:pl-1.8` - Внутренний отступ слева 1.8rem при наведении
- `.hover:pl-1.7` - Внутренний отступ слева 1.7rem при наведении
- `.hover:pl-1.6` - Внутренний отступ слева 1.6rem при наведении
- `.hover:pl-1.5` - Внутренний отступ слева 1.5rem при наведении
- `.hover:pl-1.4` - Внутренний отступ слева 1.4rem при наведении
- `.hover:pl-1.3` - Внутренний отступ слева 1.3rem при наведении
- `.hover:pl-1.2` - Внутренний отступ слева 1.2rem при наведении
- `.hover:pl-1.1` - Внутренний отступ слева 1.1rem при наведении
- `.hover:pl-1` - Внутренний отступ слева 1rem при наведении
- `.hover:pl-0.9` - Внутренний отступ слева 0.9rem при наведении
- `.hover:pl-0.8` - Внутренний отступ слева 0.8rem при наведении
- `.hover:pl-0.7` - Внутренний отступ слева 0.7rem при наведении
- `.hover:pl-0.6` - Внутренний отступ слева 0.6rem при наведении
- `.hover:pl-0.5` - Внутренний отступ слева 0.5rem при наведении
- `.hover:pl-0.4` - Внутренний отступ слева 0.4rem при наведении
- `.hover:pl-0.3` - Внутренний отступ слева 0.3rem при наведении
- `.hover:pl-0.2` - Внутренний отступ слева 0.2rem при наведении
- `.hover:pl-0.1` - Внутренний отступ слева 0.1rem при наведении
- `.hover:pl-0` - Внутренний отступ слева 0rem при наведении
- `.last:pl-0` - Внутренний отступ слева 0rem для последнего элемента
- `.pl-5` - Внутренний отступ слева 5rem
- `.pl-4.5` - Внутренний отступ слева 4.5rem
- `.pl-4` - Внутренний отступ слева 4rem
- `.pl-3.5` - Внутренний отступ слева 3.5rem
- `.pl-3` - Внутренний отступ слева 3rem
- `.pl-2.5` - Внутренний отступ слева 2.5rem
- `.pl-2` - Внутренний отступ слева 2rem
- `.pl-1.9` - Внутренний отступ слева 1.9rem
- `.pl-1.8` - Внутренний отступ слева 1.8rem
- `.pl-1.7` - Внутренний отступ слева 1.7rem
- `.pl-1.6` - Внутренний отступ слева 1.6rem
- `.pl-1.5` - Внутренний отступ слева 1.5rem
- `.pl-1.4` - Внутренний отступ слева 1.4rem
- `.pl-1.3` - Внутренний отступ слева 1.3rem
- `.pl-1.2` - Внутренний отступ слева 1.2rem
- `.pl-1.1` - Внутренний отступ слева 1.1rem
- `.pl-1` - Внутренний отступ слева 1rem
- `.pl-0.9` - Внутренний отступ слева 0.9rem
- `.pl-0.8` - Внутренний отступ слева 0.8rem
- `.pl-0.7` - Внутренний отступ слева 0.7rem
- `.pl-0.6` - Внутренний отступ слева 0.6rem
- `.pl-0.5` - Внутренний отступ слева 0.5rem
- `.pl-0.4` - Внутренний отступ слева 0.4rem
- `.pl-0.3` - Внутренний отступ слева 0.3rem
- `.pl-0.2` - Внутренний отступ слева 0.2rem
- `.pl-0.1` - Внутренний отступ слева 0.1rem
- `.pl-0` - Внутренний отступ слева 0rem

#### Padding Right

- `.first:pr-0` - Внутренний отступ справа 0rem для первого элемента
- `.hover:pr-100` - Внутренний отступ справа 100% при наведении
- `.hover:pr-75` - Внутренний отступ справа 75% при наведении
- `.hover:pr-50` - Внутренний отступ справа 50% при наведении
- `.hover:pr-25` - Внутренний отступ справа 25% при наведении
- `.hover:pr-5` - Внутренний отступ справа 5rem при наведении
- `.hover:pr-4.5` - Внутренний отступ справа 4.5rem при наведении
- `.hover:pr-4` - Внутренний отступ справа 4rem при наведении
- `.hover:pr-3.5` - Внутренний отступ справа 3.5rem при наведении
- `.hover:pr-3` - Внутренний отступ справа 3rem при наведении
- `.hover:pr-2.5` - Внутренний отступ справа 2.5rem при наведении
- `.hover:pr-2` - Внутренний отступ справа 2rem при наведении
- `.hover:pr-1.9` - Внутренний отступ справа 1.9rem при наведении
- `.hover:pr-1.8` - Внутренний отступ справа 1.8rem при наведении
- `.hover:pr-1.7` - Внутренний отступ справа 1.7rem при наведении
- `.hover:pr-1.6` - Внутренний отступ справа 1.6rem при наведении
- `.hover:pr-1.5` - Внутренний отступ справа 1.5rem при наведении
- `.hover:pr-1.4` - Внутренний отступ справа 1.4rem при наведении
- `.hover:pr-1.3` - Внутренний отступ справа 1.3rem при наведении
- `.hover:pr-1.2` - Внутренний отступ справа 1.2rem при наведении
- `.hover:pr-1.1` - Внутренний отступ справа 1.1rem при наведении
- `.hover:pr-1` - Внутренний отступ справа 1rem при наведении
- `.hover:pr-0.9` - Внутренний отступ справа 0.9rem при наведении
- `.hover:pr-0.8` - Внутренний отступ справа 0.8rem при наведении
- `.hover:pr-0.7` - Внутренний отступ справа 0.7rem при наведении
- `.hover:pr-0.6` - Внутренний отступ справа 0.6rem при наведении
- `.hover:pr-0.5` - Внутренний отступ справа 0.5rem при наведении
- `.hover:pr-0.4` - Внутренний отступ справа 0.4rem при наведении
- `.hover:pr-0.3` - Внутренний отступ справа 0.3rem при наведении
- `.hover:pr-0.2` - Внутренний отступ справа 0.2rem при наведении
- `.hover:pr-0.1` - Внутренний отступ справа 0.1rem при наведении
- `.hover:pr-0` - Внутренний отступ справа 0rem при наведении
- `.last:pr-0` - Внутренний отступ справа 0rem для последнего элемента
- `.pr-100` - Внутренний отступ справа 100%
- `.pr-75` - Внутренний отступ справа 75%
- `.pr-50` - Внутренний отступ справа 50%
- `.pr-25` - Внутренний отступ справа 25%
- `.pr-5` - Внутренний отступ справа 5rem
- `.pr-4.5` - Внутренний отступ справа 4.5rem
- `.pr-4` - Внутренний отступ справа 4rem
- `.pr-3.5` - Внутренний отступ справа 3.5rem
- `.pr-3` - Внутренний отступ справа 3rem
- `.pr-2.5` - Внутренний отступ справа 2.5rem
- `.pr-2` - Внутренний отступ справа 2rem
- `.pr-1.9` - Внутренний отступ справа 1.9rem
- `.pr-1.8` - Внутренний отступ справа 1.8rem
- `.pr-1.7` - Внутренний отступ справа 1.7rem
- `.pr-1.6` - Внутренний отступ справа 1.6rem
- `.pr-1.5` - Внутренний отступ справа 1.5rem
- `.pr-1.4` - Внутренний отступ справа 1.4rem
- `.pr-1.3` - Внутренний отступ справа 1.3rem
- `.pr-1.2` - Внутренний отступ справа 1.2rem
- `.pr-1.1` - Внутренний отступ справа 1.1rem
- `.pr-1` - Внутренний отступ справа 1rem
- `.pr-0.9` - Внутренний отступ справа 0.9rem
- `.pr-0.8` - Внутренний отступ справа 0.8rem
- `.pr-0.7` - Внутренний отступ справа 0.7rem
- `.pr-0.6` - Внутренний отступ справа 0.6rem
- `.pr-0.5` - Внутренний отступ справа 0.5rem
- `.pr-0.4` - Внутренний отступ справа 0.4rem
- `.pr-0.3` - Внутренний отступ справа 0.3rem
- `.pr-0.2` - Внутренний отступ справа 0.2rem
- `.pr-0.1` - Внутренний отступ справа 0.1rem
- `.pr-0` - Внутренний отступ справа 0rem

#### Padding Top

- `.first:pt-0` - Внутренний отступ сверху 0rem для первого элемента
- `.hover:pt-100` - Внутренний отступ сверху 100% при наведении
- `.hover:pt-75` - Внутренний отступ сверху 75% при наведении
- `.hover:pt-50` - Внутренний отступ сверху 50% при наведении
- `.hover:pt-25` - Внутренний отступ сверху 25% при наведении
- `.hover:pt-5` - Внутренний отступ сверху 5rem при наведении
- `.hover:pt-4.5` - Внутренний отступ сверху 4.5rem при наведении
- `.hover:pt-4` - Внутренний отступ сверху 4rem при наведении
- `.hover:pt-3.5` - Внутренний отступ сверху 3.5rem при наведении
- `.hover:pt-3` - Внутренний отступ сверху 3rem при наведении
- `.hover:pt-2.5` - Внутренний отступ сверху 2.5rem при наведении
- `.hover:pt-2` - Внутренний отступ сверху 2rem при наведении
- `.hover:pt-1.9` - Внутренний отступ сверху 1.9rem при наведении
- `.hover:pt-1.8` - Внутренний отступ сверху 1.8rem при наведении
- `.hover:pt-1.7` - Внутренний отступ сверху 1.7rem при наведении
- `.hover:pt-1.6` - Внутренний отступ сверху 1.6rem при наведении
- `.hover:pt-1.5` - Внутренний отступ сверху 1.5rem при наведении
- `.hover:pt-1.4` - Внутренний отступ сверху 1.4rem при наведении
- `.hover:pt-1.3` - Внутренний отступ сверху 1.3rem при наведении
- `.hover:pt-1.2` - Внутренний отступ сверху 1.2rem при наведении
- `.hover:pt-1.1` - Внутренний отступ сверху 1.1rem при наведении
- `.hover:pt-1` - Внутренний отступ сверху 1rem при наведении
- `.hover:pt-0.9` - Внутренний отступ сверху 0.9rem при наведении
- `.hover:pt-0.8` - Внутренний отступ сверху 0.8rem при наведении
- `.hover:pt-0.7` - Внутренний отступ сверху 0.7rem при наведении
- `.hover:pt-0.6` - Внутренний отступ сверху 0.6rem при наведении
- `.hover:pt-0.5` - Внутренний отступ сверху 0.5rem при наведении
- `.hover:pt-0.4` - Внутренний отступ сверху 0.4rem при наведении
- `.hover:pt-0.3` - Внутренний отступ сверху 0.3rem при наведении
- `.hover:pt-0.2` - Внутренний отступ сверху 0.2rem при наведении
- `.hover:pt-0.1` - Внутренний отступ сверху 0.1rem при наведении
- `.hover:pt-0` - Внутренний отступ сверху 0rem при наведении
- `.last:pt-0` - Внутренний отступ сверху 0rem для последнего элемента
- `.pt-100` - Внутренний отступ сверху 100%
- `.pt-75` - Внутренний отступ сверху 75%
- `.pt-50` - Внутренний отступ сверху 50%
- `.pt-25` - Внутренний отступ сверху 25%
- `.pt-5` - Внутренний отступ сверху 5rem
- `.pt-4.5` - Внутренний отступ сверху 4.5rem
- `.pt-4` - Внутренний отступ сверху 4rem
- `.pt-3.5` - Внутренний отступ сверху 3.5rem
- `.pt-3` - Внутренний отступ сверху 3rem
- `.pt-2.5` - Внутренний отступ сверху 2.5rem
- `.pt-2` - Внутренний отступ сверху 2rem
- `.pt-1.9` - Внутренний отступ сверху 1.9rem
- `.pt-1.8` - Внутренний отступ сверху 1.8rem
- `.pt-1.7` - Внутренний отступ сверху 1.7rem
- `.pt-1.6` - Внутренний отступ сверху 1.6rem
- `.pt-1.5` - Внутренний отступ сверху 1.5rem
- `.pt-1.4` - Внутренний отступ сверху 1.4rem
- `.pt-1.3` - Внутренний отступ сверху 1.3rem
- `.pt-1.2` - Внутренний отступ сверху 1.2rem
- `.pt-1.1` - Внутренний отступ сверху 1.1rem
- `.pt-1` - Внутренний отступ сверху 1rem
- `.pt-0.9` - Внутренний отступ сверху 0.9rem
- `.pt-0.8` - Внутренний отступ сверху 0.8rem
- `.pt-0.7` - Внутренний отступ сверху 0.7rem
- `.pt-0.6` - Внутренний отступ сверху 0.6rem
- `.pt-0.5` - Внутренний отступ сверху 0.5rem
- `.pt-0.4` - Внутренний отступ сверху 0.4rem
- `.pt-0.3` - Внутренний отступ сверху 0.3rem
- `.pt-0.2` - Внутренний отступ сверху 0.2rem
- `.pt-0.1` - Внутренний отступ сверху 0.1rem
- `.pt-0` - Внутренний отступ сверху 0rem

#### Padding X-Axis

- `.hover:px-100` - Внутренний отступ по оси X 100% при наведении
- `.hover:px-75` - Внутренний отступ по оси X 75% при наведении
- `.hover:px-50` - Внутренний отступ по оси X 50% при наведении
- `.hover:px-25` - Внутренний отступ по оси X 25% при наведении
- `.hover:px-5` - Внутренний отступ по оси X 5rem при наведении
- `.hover:px-4.5` - Внутренний отступ по оси X 4.5rem при наведении
- `.hover:px-4` - Внутренний отступ по оси X 4rem при наведении
- `.hover:px-3.5` - Внутренний отступ по оси X 3.5rem при наведении
- `.hover:px-3` - Внутренний отступ по оси X 3rem при наведении
- `.hover:px-2.5` - Внутренний отступ по оси X 2.5rem при наведении
- `.hover:px-2` - Внутренний отступ по оси X 2rem при наведении
- `.hover:px-1.9` - Внутренний отступ по оси X 1.9rem при наведении
- `.hover:px-1.8` - Внутренний отступ по оси X 1.8rem при наведении
- `.hover:px-1.7` - Внутренний отступ по оси X 1.7rem при наведении
- `.hover:px-1.6` - Внутренний отступ по оси X 1.6rem при наведении
- `.hover:px-1.5` - Внутренний отступ по оси X 1.5rem при наведении
- `.hover:px-1.4` - Внутренний отступ по оси X 1.4rem при наведении
- `.hover:px-1.3` - Внутренний отступ по оси X 1.3rem при наведении
- `.hover:px-1.2` - Внутренний отступ по оси X 1.2rem при наведении
- `.hover:px-1.1` - Внутренний отступ по оси X 1.1rem при наведении
- `.hover:px-1` - Внутренний отступ по оси X 1rem при наведении
- `.hover:px-0.9` - Внутренний отступ по оси X 0.9rem при наведении
- `.hover:px-0.8` - Внутренний отступ по оси X 0.8rem при наведении
- `.hover:px-0.7` - Внутренний отступ по оси X 0.7rem при наведении
- `.hover:px-0.6` - Внутренний отступ по оси X 0.6rem при наведении
- `.hover:px-0.5` - Внутренний отступ по оси X 0.5rem при наведении
- `.hover:px-0.4` - Внутренний отступ по оси X 0.4rem при наведении
- `.hover:px-0.3` - Внутренний отступ по оси X 0.3rem при наведении
- `.hover:px-0.2` - Внутренний отступ по оси X 0.2rem при наведении
- `.hover:px-0.1` - Внутренний отступ по оси X 0.1rem при наведении
- `.hover:px-0` - Внутренний отступ по оси X 0rem при наведении
- `.px-100` - Внутренний отступ по оси X 100%
- `.px-75` - Внутренний отступ по оси X 75%
- `.px-50` - Внутренний отступ по оси X 50%
- `.px-25` - Внутренний отступ по оси X 25%
- `.px-5` - Внутренний отступ по оси X 5rem
- `.px-4.5` - Внутренний отступ по оси X 4.5rem
- `.px-4` - Внутренний отступ по оси X 4rem
- `.px-3.5` - Внутренний отступ по оси X 3.5rem
- `.px-3` - Внутренний отступ по оси X 3rem
- `.px-2.5` - Внутренний отступ по оси X 2.5rem
- `.px-2` - Внутренний отступ по оси X 2rem
- `.px-1.9` - Внутренний отступ по оси X 1.9rem
- `.px-1.8` - Внутренний отступ по оси X 1.8rem
- `.px-1.7` - Внутренний отступ по оси X 1.7rem
- `.px-1.6` - Внутренний отступ по оси X 1.6rem
- `.px-1.5` - Внутренний отступ по оси X 1.5rem
- `.px-1.4` - Внутренний отступ по оси X 1.4rem
- `.px-1.3` - Внутренний отступ по оси X 1.3rem
- `.px-1.2` - Внутренний отступ по оси X 1.2rem
- `.px-1.1` - Внутренний отступ по оси X 1.1rem
- `.px-1` - Внутренний отступ по оси X 1rem
- `.px-0.9` - Внутренний отступ по оси X 0.9rem
- `.px-0.8` - Внутренний отступ по оси X 0.8rem
- `.px-0.7` - Внутренний отступ по оси X 0.7rem
- `.px-0.6` - Внутренний отступ по оси X 0.6rem
- `.px-0.5` - Внутренний отступ по оси X 0.5rem
- `.px-0.4` - Внутренний отступ по оси X 0.4rem
- `.px-0.3` - Внутренний отступ по оси X 0.3rem
- `.px-0.2` - Внутренний отступ по оси X 0.2rem
- `.px-0.1` - Внутренний отступ по оси X 0.1rem
- `.px-0` - Внутренний отступ по оси X 0rem

#### Padding Y-Axis

- `.hover:py-100` - Внутренний отступ по оси Y 100% при наведении
- `.hover:py-75` - Внутренний отступ по оси Y 75% при наведении
- `.hover:py-50` - Внутренний отступ по оси Y 50% при наведении
- `.hover:py-25` - Внутренний отступ по оси Y 25% при наведении
- `.hover:py-5` - Внутренний отступ по оси Y 5rem при наведении
- `.hover:py-4.5` - Внутренний отступ по оси Y 4.5rem при наведении
- `.hover:py-4` - Внутренний отступ по оси Y 4rem при наведении
- `.hover:py-3.5` - Внутренний отступ по оси Y 3.5rem при наведении
- `.hover:py-3` - Внутренний отступ по оси Y 3rem при наведении
- `.hover:py-2.5` - Внутренний отступ по оси Y 2.5rem при наведении
- `.hover:py-2` - Внутренний отступ по оси Y 2rem при наведении
- `.hover:py-1.9` - Внутренний отступ по оси Y 1.9rem при наведении
- `.hover:py-1.8` - Внутренний отступ по оси Y 1.8rem при наведении
- `.hover:py-1.7` - Внутренний отступ по оси Y 1.7rem при наведении
- `.hover:py-1.6` - Внутренний отступ по оси Y 1.6rem при наведении
- `.hover:py-1.5` - Внутренний отступ по оси Y 1.5rem при наведении
- `.hover:py-1.4` - Внутренний отступ по оси Y 1.4rem при наведении
- `.hover:py-1.3` - Внутренний отступ по оси Y 1.3rem при наведении
- `.hover:py-1.2` - Внутренний отступ по оси Y 1.2rem при наведении
- `.hover:py-1.1` - Внутренний отступ по оси Y 1.1rem при наведении
- `.hover:py-1` - Внутренний отступ по оси Y 1rem при наведении
- `.hover:py-0.9` - Внутренний отступ по оси Y 0.9rem при наведении
- `.hover:py-0.8` - Внутренний отступ по оси Y 0.8rem при наведении
- `.hover:py-0.7` - Внутренний отступ по оси Y 0.7rem при наведении
- `.hover:py-0.6` - Внутренний отступ по оси Y 0.6rem при наведении
- `.hover:py-0.5` - Внутренний отступ по оси Y 0.5rem при наведении
- `.hover:py-0.4` - Внутренний отступ по оси Y 0.4rem при наведении
- `.hover:py-0.3` - Внутренний отступ по оси Y 0.3rem при наведении
- `.hover:py-0.2` - Внутренний отступ по оси Y 0.2rem при наведении
- `.hover:py-0.1` - Внутренний отступ по оси Y 0.1rem при наведении
- `.hover:py-0` - Внутренний отступ по оси Y 0rem при наведении
- `.py-100` - Внутренний отступ по оси Y 100%
- `.py-75` - Внутренний отступ по оси Y 75%
- `.py-50` - Внутренний отступ по оси Y 50%
- `.py-25` - Внутренний отступ по оси Y 25%
- `.py-5` - Внутренний отступ по оси Y 5rem
- `.py-4.5` - Внутренний отступ по оси Y 4.5rem
- `.py-4` - Внутренний отступ по оси Y 4rem
- `.py-3.5` - Внутренний отступ по оси Y 3.5rem
- `.py-3` - Внутренний отступ по оси Y 3rem
- `.py-2.5` - Внутренний отступ по оси Y 2.5rem
- `.py-2` - Внутренний отступ по оси Y 2rem
- `.py-1.9` - Внутренний отступ по оси Y 1.9rem
- `.py-1.8` - Внутренний отступ по оси Y 1.8rem
- `.py-1.7` - Внутренний отступ по оси Y 1.7rem
- `.py-1.6` - Внутренний отступ по оси Y 1.6rem
- `.py-1.5` - Внутренний отступ по оси Y 1.5rem
- `.py-1.4` - Внутренний отступ по оси Y 1.4rem
- `.py-1.3` - Внутренний отступ по оси Y 1.3rem
- `.py-1.2` - Внутренний отступ по оси Y 1.2rem
- `.py-1.1` - Внутренний отступ по оси Y 1.1rem
- `.py-1` - Внутренний отступ по оси Y 1rem
- `.py-0.9` - Внутренний отступ по оси Y 0.9rem
- `.py-0.8` - Внутренний отступ по оси Y 0.8rem
- `.py-0.7` - Внутренний отступ по оси Y 0.7rem
- `.py-0.6` - Внутренний отступ по оси Y 0.6rem
- `.py-0.5` - Внутренний отступ по оси Y 0.5rem
- `.py-0.4` - Внутренний отступ по оси Y 0.4rem
- `.py-0.3` - Внутренний отступ по оси Y 0.3rem
- `.py-0.2` - Внутренний отступ по оси Y 0.2rem
- `.py-0.1` - Внутренний отступ по оси Y 0.1rem
- `.py-0` - Внутренний отступ по оси Y 0rem

## Sizing

### Width

- `.hover:w-100` - Ширина 100% при наведении
- `.hover:w-95` - Ширина 95% при наведении
- `.hover:w-90` - Ширина 90% при наведении
- `.hover:w-85` - Ширина 85% при наведении
- `.hover:w-80` - Ширина 80% при наведении
- `.hover:w-75` - Ширина 75% при наведении
- `.hover:w-70` - Ширина 70% при наведении
- `.hover:w-65` - Ширина 65% при наведении
- `.hover:w-60` - Ширина 60% при наведении
- `.hover:w-55` - Ширина 55% при наведении
- `.hover:w-50` - Ширина 50% при наведении
- `.hover:w-45` - Ширина 45% при наведении
- `.hover:w-40` - Ширина 40% при наведении
- `.hover:w-35` - Ширина 35% при наведении
- `.hover:w-30` - Ширина 30% при наведении
- `.hover:w-25` - Ширина 25% при наведении
- `.hover:w-20` - Ширина 20% при наведении
- `.hover:w-15` - Ширина 15% при наведении
- `.hover:w-10` - Ширина 10% при наведении
- `.hover:w-5` - Ширина 5% при наведении
- `.hover:w-auto` - Ширина автоматически % при наведении
- `.w-100` - Ширина 100%
- `.w-95` - Ширина 95%
- `.w-90` - Ширина 90%
- `.w-85` - Ширина 85%
- `.w-80` - Ширина 80%
- `.w-75` - Ширина 75%
- `.w-70` - Ширина 70%
- `.w-65` - Ширина 65%
- `.w-60` - Ширина 60%
- `.w-55` - Ширина 55%
- `.w-50` - Ширина 50%
- `.w-45` - Ширина 45%
- `.w-40` - Ширина 40%
- `.w-35` - Ширина 35%
- `.w-30` - Ширина 30%
- `.w-25` - Ширина 25%
- `.w-20` - Ширина 20%
- `.w-15` - Ширина 15%
- `.w-10` - Ширина 10%
- `.w-5` - Ширина 5%
- `.w-auto` - Ширина авто%

##### Width - Mobile (<= 480px)

- `.hover:mobile:w-100` - Ширина 100% при наведении на мобильном устройстве
- `.hover:mobile:w-95` - Ширина 95% при наведении на мобильном устройстве
- `.hover:mobile:w-90` - Ширина 90% при наведении на мобильном устройстве
- `.hover:mobile:w-85` - Ширина 85% при наведении на мобильном телефоне
- `.hover:mobile:w-80` - Ширина 80% при наведении на мобильном устройстве
- `.hover:mobile:w-75` - Ширина 75% при наведении на мобильном устройстве
- `.hover:mobile:w-70` - Ширина 70% при наведении на мобильном устройстве
- `.hover:mobile:w-65` - Ширина 65% при наведении на мобильном устройстве
- `.hover:mobile:w-60` - Ширина 60% при наведении на мобильном устройстве
- `.hover:mobile:w-55` - Ширина 55% при наведении на мобильном телефоне
- `.hover:mobile:w-50` - Ширина 50% при наведении на мобильном устройстве
- `.hover:mobile:w-45` - Ширина 45% при наведении на мобильном телефоне
- `.hover:mobile:w-40` - Ширина 40% при наведении на мобильном устройстве
- `.hover:mobile:w-35` - Ширина 35 % при наведении на мобильном устройстве.
- `.hover:mobile:w-30` - Ширина 30% при наведении на мобильном устройстве
- `.hover:mobile:w-25` - Ширина 25% при наведении на мобильном устройстве
- `.hover:mobile:w-20` - Ширина 20% при наведении на мобильном устройстве
- `.hover:mobile:w-15` - Ширина 15% при наведении на мобильном устройстве
- `.hover:mobile:w-10` - Ширина 10% при наведении на мобильном устройстве
- `.hover:mobile:w-5` - Ширина 5% при наведении на мобильном телефоне
- `.hover:mobile:w-auto` - Ширина автоматически % при наведении на мобильном устройстве
- `.mobile:w-100` - Ширина 100% на мобильных устройствах
- `.mobile:w-95` - Ширина 95% на мобильных устройствах
- `.mobile:w-90` - Ширина 90% на мобильных устройствах
- `.mobile:w-85` - Ширина 85% на мобильных устройствах
- `.mobile:w-80` - Ширина 80% на мобильных устройствах
- `.mobile:w-75` - Ширина 75% на мобильных устройствах
- `.mobile:w-70` - Ширина 70% на мобильных устройствах
- `.mobile:w-65` - Ширина 65% на мобильных устройствах
- `.mobile:w-60` - Ширина 60% на мобильных устройствах
- `.mobile:w-55` - Ширина 55% на мобильных устройствах
- `.mobile:w-50` - Ширина 50% на мобильных устройствах
- `.mobile:w-45` - Ширина 45% на мобильных устройствах
- `.mobile:w-40` - Ширина 40% на мобильных устройствах
- `.mobile:w-35` - Ширина 35% на мобильных устройствах
- `.mobile:w-30` - Ширина 30% на мобильных устройствах
- `.mobile:w-25` - Ширина 25% на мобильных устройствах
- `.mobile:w-20` - Ширина 20% на мобильных устройствах
- `.mobile:w-15` - Ширина 15% на мобильных устройствах
- `.mobile:w-10` - Ширина 10% на мобильных устройствах
- `.mobile:w-5` - Ширина 5% на мобильных устройствах
- `.mobile:w-auto` - Ширина автоматически % на мобильном устройстве

##### Width - Tablet (480px - 768px)

- `.hover:tablet:w-100` - Ширина 100% при наведении на планшете
- `.hover:tablet:w-95` - Ширина 95% при наведении на планшете
- `.hover:tablet:w-90` - Ширина 90% при наведении на планшете
- `.hover:tablet:w-85` - Ширина 85% при наведении на планшете
- `.hover:tablet:w-80` - Ширина 80% при наведении на планшете
- `.hover:tablet:w-75` - Ширина 75% при наведении на планшете
- `.hover:tablet:w-70` - Ширина 70% при наведении на планшете
- `.hover:tablet:w-65` - Ширина 65% при наведении на планшете
- `.hover:tablet:w-60` - Ширина 60% при наведении на планшете
- `.hover:tablet:w-55` - Ширина 55% при наведении на планшете
- `.hover:tablet:w-50` - Ширина 50% при наведении на планшете
- `.hover:tablet:w-45` - Ширина 45% при наведении на планшете
- `.hover:tablet:w-40` - Ширина 40% при наведении на планшете
- `.hover:tablet:w-35` - Ширина 35% при наведении на планшете
- `.hover:tablet:w-30` - Ширина 30% при наведении на планшете
- `.hover:tablet:w-25` - Ширина 25% при наведении на планшете
- `.hover:tablet:w-20` - Ширина 20% при наведении на планшете
- `.hover:tablet:w-15` - Ширина 15% при наведении на планшете
- `.hover:tablet:w-10` - Ширина 10% при наведении на планшете
- `.hover:tablet:w-5` - Ширина 5% при наведении на планшете
- `.hover:tablet:w-auto` - Ширина автоматически % при наведении на планшете
- `.tablet:w-100` - Ширина 100% на планшете
- `.tablet:w-95` - Ширина 95% на планшете
- `.tablet:w-90` - Ширина 90% на планшете
- `.tablet:w-85` - Ширина 85% на планшете
- `.tablet:w-80` - Ширина 80% на планшете
- `.tablet:w-75` - Ширина 75% на планшете
- `.tablet:w-70` - Ширина 70% на планшете
- `.tablet:w-65` - Ширина 65% на планшете
- `.tablet:w-60` - Ширина 60% на планшете
- `.tablet:w-55` - Ширина 55% на планшете
- `.tablet:w-50` - Ширина 50% на планшете
- `.tablet:w-45` - Ширина 45% на планшете
- `.tablet:w-40` - Ширина 40% на планшете
- `.tablet:w-35` - Ширина 35% на планшете
- `.tablet:w-30` - Ширина 30% на планшете
- `.tablet:w-25` - Ширина 25% на планшете
- `.tablet:w-20` - Ширина 20% на планшете
- `.tablet:w-15` - Ширина 15% на планшете
- `.tablet:w-10` - Ширина 10% на планшете
- `.tablet:w-5` - Ширина 5% на планшете
- `.tablet:w-auto` - Ширина авто% на планшете

##### Width - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:w-100` - Ширина 100% при наведении на планшетном ПК
- `.hover:tablet-pc:w-95` - Ширина 95% при наведении на планшетном ПК
- `.hover:tablet-pc:w-90` - Ширина 90% при наведении на планшетном ПК
- `.hover:tablet-pc:w-85` - Ширина 85% при наведении на планшетном ПК
- `.hover:tablet-pc:w-80` - Ширина 80% при наведении на планшетном ПК
- `.hover:tablet-pc:w-75` - Ширина 75% при наведении на планшетном ПК
- `.hover:tablet-pc:w-70` - Ширина 70% при наведении на планшетном ПК
- `.hover:tablet-pc:w-65` - Ширина 65% при наведении на планшетном ПК
- `.hover:tablet-pc:w-60` - Ширина 60% при наведении на планшетном ПК
- `.hover:tablet-pc:w-55` - Ширина 55% при наведении на планшетном ПК
- `.hover:tablet-pc:w-50` - Ширина 50% при наведении на планшетном ПК
- `.hover:tablet-pc:w-45` - Ширина 45% при наведении на планшетном ПК
- `.hover:tablet-pc:w-40` - Ширина 40% при наведении на планшетном ПК
- `.hover:tablet-pc:w-35` - Ширина 35% при наведении на планшетном ПК
- `.hover:tablet-pc:w-30` - Ширина 30% при наведении на планшетном ПК
- `.hover:tablet-pc:w-25` - Ширина 25% при наведении на планшетном ПК
- `.hover:tablet-pc:w-20` - Ширина 20% при наведении на планшетном ПК
- `.hover:tablet-pc:w-15` - Ширина 15% при наведении на планшетном ПК
- `.hover:tablet-pc:w-10` - Ширина 10% при наведении на планшетном ПК
- `.hover:tablet-pc:w-5` - Ширина 5% при наведении на планшетном ПК
- `.hover:tablet-pc:w-auto` - Ширина автоматически % при наведении на планшетный компьютер
- `.tablet-pc:w-100` - Ширина 100% на планшетном ПК
- `.tablet-pc:w-95` - Ширина 95% на планшетном ПК
- `.tablet-pc:w-90` - Ширина 90% на планшетном ПК
- `.tablet-pc:w-85` - Ширина 85% на планшетном ПК
- `.tablet-pc:w-80` - Ширина 80% на планшетном ПК
- `.tablet-pc:w-75` - Ширина 75% на планшетном ПК
- `.tablet-pc:w-70` - Ширина 70% на планшетном ПК
- `.tablet-pc:w-65` - Ширина 65% на планшетном ПК
- `.tablet-pc:w-60` - Ширина 60% на планшетном ПК
- `.tablet-pc:w-55` - Ширина 55% на планшетном ПК
- `.tablet-pc:w-50` - Ширина 50% на планшетном ПК
- `.tablet-pc:w-45` - Ширина 45% на планшетном ПК
- `.tablet-pc:w-40` - Ширина 40% на планшетном ПК
- `.tablet-pc:w-35` - Ширина 35% на планшетном ПК
- `.tablet-pc:w-30` - Ширина 30% на планшетном ПК
- `.tablet-pc:w-25` - Ширина 25% на планшетном ПК
- `.tablet-pc:w-20` - Ширина 20% на планшетном ПК
- `.tablet-pc:w-15` - Ширина 15% на планшетном ПК
- `.tablet-pc:w-10` - Ширина 10% на планшетном ПК
- `.tablet-pc:w-5` - Ширина 5% на планшетном ПК
- `.tablet-pc:w-auto` - Ширина авто% на планшетном ПК

##### Width - Pc (992px - 1200px)

- `.hover:pc:w-100` - Ширина 100% при наведении на ПК
- `.hover:pc:w-95` - Ширина 95% при наведении на ПК
- `.hover:pc:w-90` - Ширина 90% при наведении на ПК
- `.hover:pc:w-85` - Ширина 85% при наведении на ПК
- `.hover:pc:w-80` - Ширина 80% при наведении на ПК
- `.hover:pc:w-75` - Ширина 75% при наведении на ПК
- `.hover:pc:w-70` - Ширина 70% при наведении на ПК
- `.hover:pc:w-65` - Ширина 65% при наведении на ПК
- `.hover:pc:w-60` - Ширина 60% при наведении на ПК
- `.hover:pc:w-55` - Ширина 55% при наведении на ПК
- `.hover:pc:w-50` - Ширина 50% при наведении на ПК
- `.hover:pc:w-45` - Ширина 45% при наведении на ПК
- `.hover:pc:w-40` - Ширина 40% при наведении на ПК
- `.hover:pc:w-35` - Ширина 35% при наведении на ПК
- `.hover:pc:w-30` - Ширина 30% при наведении на ПК
- `.hover:pc:w-25` - Ширина 25% при наведении на ПК
- `.hover:pc:w-20` - Ширина 20% при наведении на ПК
- `.hover:pc:w-15` - Ширина 15% при наведении на ПК
- `.hover:pc:w-10` - Ширина 10% при наведении на ПК
- `.hover:pc:w-5` - Ширина 5% при наведении на ПК
- `.hover:pc:w-auto` - Ширина автоматически % при наведении на ПК
- `.pc:w-100` - Ширина 100% на ПК
- `.pc:w-95` - Ширина 95% на ПК
- `.pc:w-90` - Ширина 90% на ПК
- `.pc:w-85` - Ширина 85% на ПК
- `.pc:w-80` - Ширина 80% на ПК
- `.pc:w-75` - Ширина 75% на ПК
- `.pc:w-70` - Ширина 70% на ПК
- `.pc:w-65` - Ширина 65% на ПК
- `.pc:w-60` - Ширина 60% на ПК
- `.pc:w-55` - Ширина 55% на ПК
- `.pc:w-50` - Ширина 50% на ПК
- `.pc:w-45` - Ширина 45% на ПК
- `.pc:w-40` - Ширина 40% на ПК
- `.pc:w-35` - Ширина 35% на ПК
- `.pc:w-30` - Ширина 30% на ПК
- `.pc:w-25` - Ширина 25% на ПК
- `.pc:w-20` - Ширина 20% на ПК
- `.pc:w-15` - Ширина 15% на ПК
- `.pc:w-10` - Ширина 10% на ПК
- `.pc:w-5` - Ширина 5% на ПК
- `.pc:w-auto` - Ширина авто% на ПК

##### Width - Tv (>= 1200px)

- `.hover:tv:w-100` - Ширина 100% при наведении на телевизор
- `.hover:tv:w-95` - Ширина 95% при наведении на телевизор
- `.hover:tv:w-90` - Ширина 90% при наведении на телевизор
- `.hover:tv:w-85` - Ширина 85% при наведении на телевизор
- `.hover:tv:w-80` - Ширина 80% при наведении на телевизор
- `.hover:tv:w-75` - Ширина 75% при наведении на телевизор
- `.hover:tv:w-70` - Ширина 70% при наведении на телевизор
- `.hover:tv:w-65` - Ширина 65% при наведении на телевизор
- `.hover:tv:w-60` - Ширина 60% при наведении на телевизор
- `.hover:tv:w-55` - Ширина 55% при наведении на телевизор
- `.hover:tv:w-50` - Ширина 50% при наведении на телевизор
- `.hover:tv:w-45` - Ширина 45% при наведении на телевизор
- `.hover:tv:w-40` - Ширина 40% при наведении на телевизор
- `.hover:tv:w-35` - Ширина 35% при наведении на телевизор
- `.hover:tv:w-30` - Ширина 30% при наведении на телевизор
- `.hover:tv:w-25` - Ширина 25% при наведении на телевизор
- `.hover:tv:w-20` - Ширина 20% при наведении на телевизор
- `.hover:tv:w-15` - Ширина 15% при наведении на телевизор
- `.hover:tv:w-10` - Ширина 10% при наведении на ТВ
- `.hover:tv:w-5` - Ширина 5% при наведении на ТВ
- `.hover:tv:w-auto` - Ширина авто% при наведении на ТВ
- `.tv:w-100` - Ширина 100% на ТВ
- `.tv:w-95` - Ширина 95% на ТВ
- `.tv:w-90` - Ширина 90% на ТВ
- `.tv:w-85` - Ширина 85% на ТВ
- `.tv:w-80` - Ширина 80% на ТВ
- `.tv:w-75` - Ширина 75% на ТВ
- `.tv:w-70` - Ширина 70% на ТВ
- `.tv:w-65` - Ширина 65% на ТВ
- `.tv:w-60` - Ширина 60% на ТВ
- `.tv:w-55` - Ширина 55% на ТВ
- `.tv:w-50` - Ширина 50% на ТВ
- `.tv:w-45` - Ширина 45% на ТВ
- `.tv:w-40` - Ширина 40% на ТВ
- `.tv:w-35` - Ширина 35% на ТВ
- `.tv:w-30` - Ширина 30% на ТВ
- `.tv:w-25` - Ширина 25% на ТВ
- `.tv:w-20` - Ширина 20% на ТВ
- `.tv:w-15` - Ширина 15% на ТВ
- `.tv:w-10` - Ширина 10% на ТВ
- `.tv:w-5` - Ширина 5% на ТВ
- `.tv:w-auto` - Ширина авто% на ТВ

##### Width - Tablet Max (<= 768px)

- `.hover:tablet-max:w-100` - Ширина 100% при наведении на планшете макс.
- `.hover:tablet-max:w-95` - Ширина 95% при наведении на планшете макс.
- `.hover:tablet-max:w-90` - Ширина 90% при наведении на планшете макс.
- `.hover:tablet-max:w-85` - Ширина 85 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-80` - Ширина 80 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-75` - Ширина 75 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-70` - Ширина 70 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-65` - Ширина 65 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-60` - Ширина 60% при наведении на планшете макс.
- `.hover:tablet-max:w-55` - Ширина 55 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-50` - Ширина 50 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-45` - Ширина 45% при наведении на планшете макс.
- `.hover:tablet-max:w-40` - Ширина 40% при наведении на планшете макс.
- `.hover:tablet-max:w-35` - Ширина 35% при наведении на планшете макс.
- `.hover:tablet-max:w-30` - Ширина 30% при наведении на планшете макс.
- `.hover:tablet-max:w-25` - Ширина 25 % при наведении на планшете (макс.)
- `.hover:tablet-max:w-20` - Ширина 20 % при наведении на планшете (макс.)
- `.hover:tablet-max:w-15` - Ширина 15% при наведении на планшете макс.
- `.hover:tablet-max:w-10` - Ширина 10% при наведении на планшете макс.
- `.hover:tablet-max:w-5` - Ширина 5% при наведении на планшете макс.
- `.hover:tablet-max:w-auto` - Ширина авто% при наведении на планшет макс.
- `.tablet-max:w-100` - Ширина 100 % на планшете (макс.)
- `.tablet-max:w-95` - Ширина 95 % на планшете (макс.)
- `.tablet-max:w-90` - Ширина 90 % на планшете (макс.)
- `.tablet-max:w-85` - Ширина 85 % на планшете (макс.)
- `.tablet-max:w-80` - Ширина 80 % на планшете (макс.)
- `.tablet-max:w-75` - Ширина 75 % на планшете (макс.)
- `.tablet-max:w-70` - Ширина 70 % на планшете (макс.)
- `.tablet-max:w-65` - Ширина 65 % на планшете (макс.)
- `.tablet-max:w-60` - Ширина 60% на планшете макс.
- `.tablet-max:w-55` - Ширина 55 % на планшете (макс.)
- `.tablet-max:w-50` - Ширина 50 % на планшете (макс.)
- `.tablet-max:w-45` - Ширина 45% на планшете макс.
- `.tablet-max:w-40` - Ширина 40% на планшете макс.
- `.tablet-max:w-35` - Ширина 35% на планшете макс.
- `.tablet-max:w-30` - Ширина 30% на планшете макс.
- `.tablet-max:w-25` - Ширина 25 % на планшете (макс.)
- `.tablet-max:w-20` - Ширина 20% на планшете макс.
- `.tablet-max:w-15` - Ширина 15% на планшете макс.
- `.tablet-max:w-10` - Ширина 10% на планшете макс.
- `.tablet-max:w-5` - Ширина 5% на планшете макс.
- `.tablet-max:w-auto` - Ширина авто% на планшете макс.

##### Width - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:w-100` - Ширина 100% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:w-95` - Ширина 95 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-90` - Ширина 90% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-85` - Ширина 85% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:w-80` - Ширина 80% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-75` - Ширина 75 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:w-70` - Ширина 70 % при наведении на планшетном ПК (максимум)
- `.hover:tablet-pc-max:w-65` - Ширина 65 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:w-60` - Ширина 60% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-55` - Ширина 55 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:w-50` - Ширина 50 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-45` - Ширина 45% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-40` - Ширина 40% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-35` - Ширина 35% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-30` - Ширина 30% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-25` - Ширина 25 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-20` - Ширина 20 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-15` - Ширина 15% при наведении на планшетном ПК максимум
- `.hover:tablet-pc-max:w-10` - Ширина 10% при наведении на планшетном ПК максимум
- `.hover:tablet-pc-max:w-5` - Ширина 5 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-auto` - Ширина авто% при наведении на планшетный ПК макс.
- `.tablet-pc-max:w-100` - Ширина 100% на планшетном ПК макс.
- `.tablet-pc-max:w-95` - Ширина 95% на планшетном ПК макс.
- `.tablet-pc-max:w-90` - Ширина 90% на планшетном ПК макс.
- `.tablet-pc-max:w-85` - Ширина 85% на планшетном ПК макс.
- `.tablet-pc-max:w-80` - Ширина 80% на планшетном ПК макс.
- `.tablet-pc-max:w-75` - Ширина 75 % на планшетном ПК (макс.)
- `.tablet-pc-max:w-70` - Ширина 70% на планшетном ПК макс.
- `.tablet-pc-max:w-65` - Ширина 65% на планшетном ПК макс.
- `.tablet-pc-max:w-60` - Ширина 60% на планшетном ПК макс.
- `.tablet-pc-max:w-55` - Ширина 55% на планшетном ПК макс.
- `.tablet-pc-max:w-50` - Ширина 50% на планшетном ПК макс.
- `.tablet-pc-max:w-45` - Ширина 45% на планшетном ПК макс.
- `.tablet-pc-max:w-40` - Ширина 40% на планшетном ПК макс.
- `.tablet-pc-max:w-35` - Ширина 35% на планшетном ПК макс.
- `.tablet-pc-max:w-30` - Ширина 30% на планшетном ПК макс.
- `.tablet-pc-max:w-25` - Ширина 25% на планшетном ПК макс.
- `.tablet-pc-max:w-20` - Ширина 20% на планшетном ПК макс.
- `.tablet-pc-max:w-15` - Ширина 15% на планшетном ПК макс.
- `.tablet-pc-max:w-10` - Ширина 10% на планшетном ПК макс.
- `.tablet-pc-max:w-5` - Ширина 5% на планшетном ПК макс.
- `.tablet-pc-max:w-auto` - Ширина авто% на планшетном ПК макс.

##### Width - Pc Max (<= 1200px)

- `.hover:pc-max:w-100` - Ширина 100% при наведении на ПК макс.
- `.hover:pc-max:w-95` - Ширина 95% при наведении на ПК макс.
- `.hover:pc-max:w-90` - Ширина 90% при наведении на ПК макс.
- `.hover:pc-max:w-85` - Ширина 85% при наведении на ПК макс.
- `.hover:pc-max:w-80` - Ширина 80% при наведении на ПК макс.
- `.hover:pc-max:w-75` - Ширина 75% при наведении на ПК макс.
- `.hover:pc-max:w-70` - Ширина 70% при наведении на ПК макс.
- `.hover:pc-max:w-65` - Ширина 65% при наведении на ПК макс.
- `.hover:pc-max:w-60` - Ширина 60% при наведении на ПК макс.
- `.hover:pc-max:w-55` - Ширина 55% при наведении на ПК макс.
- `.hover:pc-max:w-50` - Ширина 50% при наведении на ПК макс.
- `.hover:pc-max:w-45` - Ширина 45% при наведении на ПК макс.
- `.hover:pc-max:w-40` - Ширина 40% при наведении на ПК макс.
- `.hover:pc-max:w-35` - Ширина 35% при наведении на ПК макс.
- `.hover:pc-max:w-30` - Ширина 30% при наведении на ПК макс.
- `.hover:pc-max:w-25` - Ширина 25% при наведении на ПК макс.
- `.hover:pc-max:w-20` - Ширина 20% при наведении на ПК макс.
- `.hover:pc-max:w-15` - Ширина 15% при наведении на ПК макс.
- `.hover:pc-max:w-10` - Ширина 10% при наведении на ПК макс.
- `.hover:pc-max:w-5` - Ширина 5% при наведении на ПК макс.
- `.hover:pc-max:w-auto` - Ширина авто% при наведении на ПК макс.
- `.pc-max:w-100` - Ширина 100% на ПК макс.
- `.pc-max:w-95` - Ширина 95% на ПК макс.
- `.pc-max:w-90` - Ширина 90% на ПК макс.
- `.pc-max:w-85` - Ширина 85% на ПК макс.
- `.pc-max:w-80` - Ширина 80% на ПК макс.
- `.pc-max:w-75` - Ширина 75% на ПК макс.
- `.pc-max:w-70` - Ширина 70% на ПК макс.
- `.pc-max:w-65` - Ширина 65% на ПК макс.
- `.pc-max:w-60` - Ширина 60% на ПК макс.
- `.pc-max:w-55` - Ширина 55% на ПК макс.
- `.pc-max:w-50` - Ширина 50% на ПК макс.
- `.pc-max:w-45` - Ширина 45% на ПК макс.
- `.pc-max:w-40` - Ширина 40% на ПК макс.
- `.pc-max:w-35` - Ширина 35% на ПК макс.
- `.pc-max:w-30` - Ширина 30% на ПК макс.
- `.pc-max:w-25` - Ширина 25% на ПК макс.
- `.pc-max:w-20` - Ширина 20% на ПК макс.
- `.pc-max:w-15` - Ширина 15% на ПК макс.
- `.pc-max:w-10` - Ширина 10% на ПК макс.
- `.pc-max:w-5` - Ширина 5% на ПК макс.
- `.pc-max:w-auto` - Ширина авто% на ПК макс.

#### Width vh

- `.hover:w-vh-100` - Ширина vh 100vh при наведении
- `.hover:w-vh-75` - Ширина vh 75vh при наведении
- `.hover:w-vh-50` - Ширина vh 50vh при наведении
- `.hover:w-vh-25` - Ширина vh 25vh при наведении
- `.w-vh-100` - Ширина вх 100vh
- `.w-vh-75` - Ширина вх 75vh
- `.w-vh-50` - Ширина вх 50vh
- `.w-vh-25` - Ширина вх 25vh

#### Width vw

- `.hover:w-vw-100` - Ширина vw 100vw при наведении
- `.hover:w-vw-75` - Ширина vw 75vw при наведении
- `.hover:w-vw-50` - Ширина vw 50vw при наведении
- `.hover:w-vw-25` - Ширина vw 25vw при наведении
- `.w-vw-100` - Ширина vw 100vw
- `.w-vw-75` - Ширина Фольксваген 75vw
- `.w-vw-50` - Ширина 50vw
- `.w-vw-25` - Ширина vw 25vw

### Height

- `.h-100` - Высота 100%
- `.h-95` - Высота 95%
- `.h-90` - Высота 90%
- `.h-85` - Высота 85%
- `.h-80` - Высота 80%
- `.h-75` - Высота 75%
- `.h-70` - Высота 70%
- `.h-65` - Высота 65%
- `.h-60` - Высота 60%
- `.h-55` - Высота 55%
- `.h-50` - Высота 50%
- `.h-45` - Высота 45%
- `.h-40` - Высота 40%
- `.h-35` - Высота 35%
- `.h-30` - Высота 30%
- `.h-25` - Высота 25%
- `.h-20` - Высота 20%
- `.h-15` - Высота 15%
- `.h-10` - Высота 10%
- `.h-5` - Высота 5%
- `.h-auto` - Высота авто%
- `.hover:h-100` - Высота 100% при наведении
- `.hover:h-95` - Высота 95% при наведении
- `.hover:h-90` - Высота 90% при наведении
- `.hover:h-85` - Высота 85% при наведении
- `.hover:h-80` - Высота 80% при наведении
- `.hover:h-75` - Высота 75% при наведении
- `.hover:h-70` - Высота 70% при наведении
- `.hover:h-65` - Высота 65% при наведении
- `.hover:h-60` - Высота 60% при наведении
- `.hover:h-55` - Высота 55% при наведении
- `.hover:h-50` - Высота 50% при наведении
- `.hover:h-45` - Высота 45% при наведении
- `.hover:h-40` - Высота 40% при наведении
- `.hover:h-35` - Высота 35% при наведении
- `.hover:h-30` - Высота 30% при наведении
- `.hover:h-25` - Высота 25% при наведении
- `.hover:h-20` - Высота 20% при наведении
- `.hover:h-15` - Высота 15% при наведении
- `.hover:h-10` - Высота 10% при наведении
- `.hover:h-5` - Высота 5% при наведении
- `.hover:h-auto` - Высота автоматически % при наведении

##### Height - Mobile (<= 480px)

- `.hover:mobile:h-100` - Высота 100% при наведении на мобильном телефоне
- `.hover:mobile:h-95` - Высота 95% при наведении на мобильном телефоне
- `.hover:mobile:h-90` - Высота 90% при наведении на мобильном телефоне
- `.hover:mobile:h-85` - Высота 85% при наведении на мобильном телефоне
- `.hover:mobile:h-80` - Высота 80% при наведении на мобильном телефоне
- `.hover:mobile:h-75` - Высота 75% при наведении на мобильном телефоне
- `.hover:mobile:h-70` - Высота 70% при наведении на мобильном телефоне
- `.hover:mobile:h-65` - Высота 65% при наведении на мобильном телефоне
- `.hover:mobile:h-60` - Высота 60% при наведении на мобильном телефоне
- `.hover:mobile:h-55` - Высота 55% при наведении на мобильном телефоне
- `.hover:mobile:h-50` - Высота 50% при наведении на мобильном телефоне
- `.hover:mobile:h-45` - Высота 45% при наведении на мобильном телефоне
- `.hover:mobile:h-40` - Высота 40% при наведении на мобильном телефоне
- `.hover:mobile:h-35` - Высота 35% при наведении на мобильном телефоне
- `.hover:mobile:h-30` - Высота 30% при наведении на мобильном телефоне
- `.hover:mobile:h-25` - Высота 25% при наведении на мобильном телефоне
- `.hover:mobile:h-20` - Высота 20% при наведении на мобильном телефоне
- `.hover:mobile:h-15` - Высота 15% при наведении на мобильном телефоне
- `.hover:mobile:h-10` - Высота 10% при наведении на мобильном телефоне
- `.hover:mobile:h-5` - Высота 5% при наведении на мобильном телефоне
- `.hover:mobile:h-auto` - Высота автоматически % при наведении на мобильном устройстве
- `.mobile:h-100` - Высота 100 % на мобильном устройстве
- `.mobile:h-95` - Высота 95% на мобильном телефоне
- `.mobile:h-90` - Высота 90% на мобильном телефоне
- `.mobile:h-85` - Высота 85% на мобильном телефоне
- `.mobile:h-80` - Высота 80% на мобильном телефоне
- `.mobile:h-75` - Высота 75% на мобильном телефоне
- `.mobile:h-70` - Высота 70% на мобильном телефоне
- `.mobile:h-65` - Высота 65% на мобильном телефоне
- `.mobile:h-60` - Высота 60% на мобильном телефоне
- `.mobile:h-55` - Высота 55% на мобильном телефоне
- `.mobile:h-50` - Высота 50% на мобильном телефоне
- `.mobile:h-45` - Высота 45% на мобильном телефоне
- `.mobile:h-40` - Высота 40% на мобильном телефоне
- `.mobile:h-35` - Высота 35% на мобильных устройствах
- `.mobile:h-30` - Высота 30% на мобильных устройствах
- `.mobile:h-25` - Высота 25% на мобильных устройствах
- `.mobile:h-20` - Высота 20% на мобильных устройствах
- `.mobile:h-15` - Высота 15% на мобильных устройствах
- `.mobile:h-10` - Высота 10% на мобильном телефоне
- `.mobile:h-5` - Высота 5% на мобильных устройствах
- `.mobile:h-auto` - Высота автоматически % на мобильном устройстве

##### Height - Tablet (480px - 768px)

- `.hover:tablet:h-100` - Высота 100% при наведении на планшете
- `.hover:tablet:h-95` - Высота 95% при наведении на планшете
- `.hover:tablet:h-90` - Высота 90% при наведении на планшете
- `.hover:tablet:h-85` - Высота 85% при наведении на планшет
- `.hover:tablet:h-80` - Высота 80% при наведении на планшет
- `.hover:tablet:h-75` - Высота 75% при наведении на планшете
- `.hover:tablet:h-70` - Высота 70% при наведении на планшете
- `.hover:tablet:h-65` - Высота 65% при наведении на планшет
- `.hover:tablet:h-60` - Высота 60% при наведении на планшете
- `.hover:tablet:h-55` - Высота 55% при наведении на планшете
- `.hover:tablet:h-50` - Высота 50% при наведении на планшете
- `.hover:tablet:h-45` - Высота 45% при наведении на планшете
- `.hover:tablet:h-40` - Высота 40% при наведении на планшете
- `.hover:tablet:h-35` - Высота 35% при наведении на планшете
- `.hover:tablet:h-30` - Высота 30% при наведении на планшете
- `.hover:tablet:h-25` - Высота 25% при наведении на планшете
- `.hover:tablet:h-20` - Высота 20% при наведении на планшете
- `.hover:tablet:h-15` - Высота 15% при наведении на планшете
- `.hover:tablet:h-10` - Высота 10% при наведении на планшете
- `.hover:tablet:h-5` - Высота 5% при наведении на планшете
- `.hover:tablet:h-auto` - Высота автоматически % при наведении на планшет
- `.tablet:h-100` - Высота 100% на планшете
- `.tablet:h-95` - Высота 95% на планшете
- `.tablet:h-90` - Высота 90% на планшете
- `.tablet:h-85` - Высота 85% на планшете
- `.tablet:h-80` - Высота 80% на планшете
- `.tablet:h-75` - Высота 75% на планшете
- `.tablet:h-70` - Высота 70% на планшете
- `.tablet:h-65` - Высота 65% на планшете
- `.tablet:h-60` - Высота 60% на планшете
- `.tablet:h-55` - Высота 55% на планшете
- `.tablet:h-50` - Высота 50% на планшете
- `.tablet:h-45` - Высота 45% на планшете
- `.tablet:h-40` - Высота 40% на планшете
- `.tablet:h-35` - Высота 35% на планшете
- `.tablet:h-30` - Высота 30% на планшете
- `.tablet:h-25` - Высота 25% на планшете
- `.tablet:h-20` - Высота 20% на планшете
- `.tablet:h-15` - Высота 15% на планшете
- `.tablet:h-10` - Высота 10% на планшете
- `.tablet:h-5` - Высота 5% на планшете
- `.tablet:h-auto` - Высота автоматически % на планшете

##### Height - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:h-100` - Высота 100% при наведении на планшетном ПК
- `.hover:tablet-pc:h-95` - Высота 95% при наведении на планшетном ПК
- `.hover:tablet-pc:h-90` - Высота 90% при наведении на планшетном ПК
- `.hover:tablet-pc:h-85` - Высота 85% при наведении на планшетном ПК
- `.hover:tablet-pc:h-75` - Высота 75% при наведении на планшетном ПК
- `.hover:tablet-pc:h-70` - Высота 70% при наведении на планшетном ПК
- `.hover:tablet-pc:h-65` - Высота 65% при наведении на планшетном ПК
- `.hover:tablet-pc:h-60` - Высота 60% при наведении на планшетном ПК
- `.hover:tablet-pc:h-55` - Высота 55% при наведении на планшетном ПК
- `.hover:tablet-pc:h-50` - Высота 50% при наведении на планшетном ПК
- `.hover:tablet-pc:h-45` - Высота 45% при наведении на планшетном ПК
- `.hover:tablet-pc:h-40` - Высота 40% при наведении на планшетном ПК
- `.hover:tablet-pc:h-35` - Высота 35% при наведении на планшетном ПК
- `.hover:tablet-pc:h-30` - Высота 30% при наведении на планшетном ПК
- `.hover:tablet-pc:h-25` - Высота 25% при наведении на планшетном ПК
- `.hover:tablet-pc:h-20` - Высота 20% при наведении на планшетном ПК
- `.hover:tablet-pc:h-15` - Высота 15% при наведении на планшетном ПК
- `.hover:tablet-pc:h-10` - Высота 10% при наведении на планшетном ПК
- `.hover:tablet-pc:h-5` - Высота 5% при наведении на планшетном ПК
- `.hover:tablet-pc:h-auto` - Автоматический процент высоты при наведении курсора на планшетный компьютер
- `.tablet-pc:h-100` - Высота 100% на планшетном ПК
- `.tablet-pc:h-95` - Высота 95% на планшетном ПК
- `.tablet-pc:h-90` - Высота 90% на планшетном ПК
- `.tablet-pc:h-85` - Высота 85% на планшетном ПК
- `.tablet-pc:h-80` - Высота 80% на планшетном ПК
- `.tablet-pc:h-75` - Высота 75% на планшетном ПК
- `.tablet-pc:h-70` - Высота 70% на планшетном ПК
- `.tablet-pc:h-65` - Высота 65% на планшетном ПК
- `.tablet-pc:h-60` - Высота 60% на планшетном ПК
- `.tablet-pc:h-55` - Высота 55% на планшетном ПК
- `.tablet-pc:h-50` - Высота 50% на планшетном ПК
- `.tablet-pc:h-45` - Высота 45% на планшетном ПК
- `.tablet-pc:h-40` - Высота 40% на планшетном ПК
- `.tablet-pc:h-35` - Высота 35% на планшетном ПК
- `.tablet-pc:h-30` - Высота 30% на планшетном ПК
- `.tablet-pc:h-25` - Высота 25% на планшетном ПК
- `.tablet-pc:h-20` - Высота 20% на планшетном ПК
- `.tablet-pc:h-15` - Высота 15% на планшетном ПК
- `.tablet-pc:h-10` - Высота 10% на планшетном ПК
- `.tablet-pc:h-5` - Высота 5% на планшетном ПК
- `.tablet-pc:h-auto` - Высота авто% на планшетном ПК

##### Height - Pc (992px - 1200px)

- `.hover:pc:h-100` - Высота 100% при наведении на ПК
- `.hover:pc:h-95` - Высота 95% при наведении на ПК
- `.hover:pc:h-90` - Высота 90% при наведении на ПК
- `.hover:pc:h-85` - Высота 85% при наведении на ПК
- `.hover:pc:h-80` - Высота 80% при наведении на ПК
- `.hover:pc:h-75` - Высота 75% при наведении на ПК
- `.hover:pc:h-70` - Высота 70% при наведении на ПК
- `.hover:pc:h-65` - Высота 65% при наведении на ПК
- `.hover:pc:h-60` - Высота 60% при наведении на ПК
- `.hover:pc:h-55` - Высота 55% при наведении на ПК
- `.hover:pc:h-50` - Высота 50% при наведении на ПК
- `.hover:pc:h-45` - Высота 45% при наведении на ПК
- `.hover:pc:h-40` - Высота 40% при наведении на ПК
- `.hover:pc:h-35` - Высота 35% при наведении на ПК
- `.hover:pc:h-30` - Высота 30% при наведении на ПК
- `.hover:pc:h-25` - Высота 25% при наведении на ПК
- `.hover:pc:h-20` - Высота 20% при наведении на ПК
- `.hover:pc:h-15` - Высота 15% при наведении на ПК
- `.hover:pc:h-10` - Высота 10% при наведении на ПК
- `.hover:pc:h-5` - Высота 5% при наведении на ПК
- `.hover:pc:h-auto` - Высота автоматически % при наведении на ПК
- `.pc:h-100` - Высота 100% на ПК
- `.pc:h-95` - Высота 95% на ПК
- `.pc:h-90` - Высота 90% на ПК
- `.pc:h-85` - Высота 85% на ПК
- `.pc:h-80` - Высота 80% на ПК
- `.pc:h-75` - Высота 75% на ПК
- `.pc:h-70` - Высота 70% на ПК
- `.pc:h-65` - Высота 65% на ПК
- `.pc:h-60` - Высота 60% на ПК
- `.pc:h-55` - Высота 55% на ПК
- `.pc:h-50` - Высота 50% на ПК
- `.pc:h-45` - Высота 45% на ПК
- `.pc:h-40` - Высота 40% на ПК
- `.pc:h-35` - Высота 35% на ПК
- `.pc:h-30` - Высота 30% на ПК
- `.pc:h-25` - Высота 25% на ПК
- `.pc:h-20` - Высота 20% на ПК
- `.pc:h-15` - Высота 15% на ПК
- `.pc:h-10` - Высота 10% на ПК
- `.pc:h-5` - Высота 5% на ПК
- `.pc:h-auto` - Высота авто% на ПК

##### Height - Tv (>= 1200px)

- `.hover:tv:h-100` - Высота 100% при наведении на телевизор
- `.hover:tv:h-95` - Высота 95% при наведении на телевизор
- `.hover:tv:h-90` - Высота 90% при наведении на телевизор
- `.hover:tv:h-85` - Высота 85% при наведении на телевизор
- `.hover:tv:h-80` - Высота 80% при наведении на телевизор
- `.hover:tv:h-75` - Высота 75% при наведении на телевизор
- `.hover:tv:h-70` - Высота 70% при наведении на телевизор
- `.hover:tv:h-65` - Высота 65% при наведении на телевизор
- `.hover:tv:h-60` - Высота 60% при наведении на телевизор
- `.hover:tv:h-55` - Высота 55% при наведении на телевизор
- `.hover:tv:h-50` - Высота 50% при наведении на телевизор
- `.hover:tv:h-45` - Высота 45% при наведении на телевизор
- `.hover:tv:h-40` - Высота 40% при наведении на телевизор
- `.hover:tv:h-35` - Высота 35% при наведении на телевизор
- `.hover:tv:h-30` - Высота 30% при наведении на телевизор
- `.hover:tv:h-25` - Высота 25% при наведении на ТВ
- `.hover:tv:h-20` - Высота 20% при наведении на телевизор
- `.hover:tv:h-15` - Высота 15% при наведении на ТВ
- `.hover:tv:h-10` - Высота 10% при наведении на ТВ
- `.hover:tv:h-5` - Высота 5% при наведении на ТВ
- `.hover:tv:h-auto` - Высота автоматически % при наведении курсора на телевизоре
- `.tv:h-100` - Рост 100% по телевизору
- `.tv:h-95` - Рост 95% по телевизору
- `.tv:h-90` - Рост 90% по телевизору
- `.tv:h-85` - Рост 85% по телевизору
- `.tv:h-80` - Рост 80% по телевизору
- `.tv:h-75` - Рост 75% по телевизору
- `.tv:h-70` - Рост 70% по телевизору
- `.tv:h-65` - Рост 65% по телевизору
- `.tv:h-60` - Рост 60% по телевизору
- `.tv:h-55` - Рост 55% по телевизору
- `.tv:h-50` - Рост 50% по телевизору
- `.tv:h-45` - Рост 45% по телевизору
- `.tv:h-40` - Рост 40% по телевизору
- `.tv:h-35` - Рост 35% по телевизору
- `.tv:h-30` - Рост 30% по телевизору
- `.tv:h-25` - Рост 25% по телевизору
- `.tv:h-20` - Рост 20% по телевизору
- `.tv:h-15` - Рост 15% по телевизору
- `.tv:h-10` - Рост 10% по телевизору
- `.tv:h-5` - Рост 5% по телевизору
- `.tv:h-auto` - Высота авто% на ТВ

##### Height - Tablet Max (<= 768px)

- `.hover:tablet-max:h-100` - Высота 100 % при наведении на планшет (максимум)
- `.hover:tablet-max:h-95` - Высота 95% при наведении на планшет макс.
- `.hover:tablet-max:h-90` - Высота 90% при наведении на планшете макс.
- `.hover:tablet-max:h-85` - Высота 85% при наведении на планшет макс.
- `.hover:tablet-max:h-80` - Высота 80% при наведении на планшет макс.
- `.hover:tablet-max:h-75` - Высота 75% при наведении на планшет макс.
- `.hover:tablet-max:h-70` - Высота 70% при наведении на планшет макс.
- `.hover:tablet-max:h-65` - Высота 65% при наведении на планшет макс.
- `.hover:tablet-max:h-60` - Высота 60% при наведении на планшет макс.
- `.hover:tablet-max:h-55` - Высота 55% при наведении на планшет макс.
- `.hover:tablet-max:h-50` - Высота 50 % при наведении на планшет (максимум)
- `.hover:tablet-max:h-45` - Высота 45% при наведении на планшет макс.
- `.hover:tablet-max:h-40` - Высота 40% при наведении на планшет макс.
- `.hover:tablet-max:h-35` - Высота 35% при наведении на планшет макс.
- `.hover:tablet-max:h-30` - Высота 30% при наведении на планшете макс.
- `.hover:tablet-max:h-25` - Высота 25% при наведении на планшете макс.
- `.hover:tablet-max:h-20` - Высота 20% при наведении на планшете макс.
- `.hover:tablet-max:h-15` - Высота 15% при наведении на планшете макс.
- `.hover:tablet-max:h-10` - Высота 10% при наведении на планшете макс.
- `.hover:tablet-max:h-5` - Высота 5% при наведении на планшете макс.
- `.hover:tablet-max:h-auto` - Высота авто% при наведении на планшет макс.
- `.tablet-max:h-100` - Высота 100% на планшете макс.
- `.tablet-max:h-95` - Высота 95% на планшете макс.
- `.tablet-max:h-90` - Высота 90% на планшете макс.
- `.tablet-max:h-85` - Высота 85% на планшете макс.
- `.tablet-max:h-80` - Высота 80% на планшете макс.
- `.tablet-max:h-75` - Высота 75% на планшете макс.
- `.tablet-max:h-70` - Высота 70% на планшете макс.
- `.tablet-max:h-65` - Высота 65% на планшете макс.
- `.tablet-max:h-60` - Высота 60% на планшете макс.
- `.tablet-max:h-55` - Высота 55% на планшете макс.
- `.tablet-max:h-50` - Высота 50% на планшете макс.
- `.tablet-max:h-45` - Высота 45% на планшете макс.
- `.tablet-max:h-40` - Высота 40% на планшете макс.
- `.tablet-max:h-35` - Высота 35% на планшете макс.
- `.tablet-max:h-30` - Высота 30% на планшете макс.
- `.tablet-max:h-25` - Высота 25% на планшете макс.
- `.tablet-max:h-20` - Высота 20% на планшете макс.
- `.tablet-max:h-15` - Высота 15% на планшете макс.
- `.tablet-max:h-10` - Высота 10% на планшете макс.
- `.tablet-max:h-5` - Высота 5% на планшете макс.
- `.tablet-max:h-auto` - Высота авто% на планшете макс.

##### Height - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:h-100` - Высота 100% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-95` - Высота 95% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-90` - Высота 90% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-85` - Высота 85% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-80` - Высота 80% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-75` - Высота 75% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-70` - Высота 70% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-65` - Высота 65% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-60` - Высота 60% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-55` - Высота 55 % при наведении на планшетный ПК (максимум)
- `.hover:tablet-pc-max:h-50` - Высота 50% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-45` - Высота 45% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-40` - Высота 40% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-35` - Высота 35% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-30` - Высота 30% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-25` - Высота 25 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:h-20` - Высота 20% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-15` - Высота 15% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-10` - Высота 10% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-5` - Высота 5% при наведении на планшетном ПК максимум
- `.hover:tablet-pc-max:h-auto` - Высота авто% при наведении на планшетный ПК макс.
- `.tablet-pc-max:h-100` - Высота 100% на планшетном ПК макс.
- `.tablet-pc-max:h-95` - Высота 95% на планшетном ПК макс.
- `.tablet-pc-max:h-90` - Высота 90% на планшетном ПК макс.
- `.tablet-pc-max:h-85` - Высота 85% на планшетном ПК макс.
- `.tablet-pc-max:h-80` - Высота 80% на планшетном ПК макс.
- `.tablet-pc-max:h-75` - Высота 75% на планшетном ПК макс.
- `.tablet-pc-max:h-70` - Высота 70% на планшетном ПК макс.
- `.tablet-pc-max:h-65` - Высота 65% на планшетном ПК макс.
- `.tablet-pc-max:h-60` - Высота 60% на планшетном ПК макс.
- `.tablet-pc-max:h-55` - Высота 55% на планшетном ПК макс.
- `.tablet-pc-max:h-50` - Высота 50% на планшетном ПК макс.
- `.tablet-pc-max:h-45` - Высота 45% на планшетном ПК макс.
- `.tablet-pc-max:h-40` - Высота максимум 40% на планшетном ПК
- `.tablet-pc-max:h-35` - Высота 35% на планшетном ПК макс.
- `.tablet-pc-max:h-30` - Высота максимум 30% на планшетном ПК
- `.tablet-pc-max:h-25` - Высота 25% на планшетном ПК макс.
- `.tablet-pc-max:h-20` - Высота 20% на планшетном ПК макс.
- `.tablet-pc-max:h-15` - Высота 15% на планшетном ПК макс.
- `.tablet-pc-max:h-10` - Высота 10% на планшетном ПК макс.
- `.tablet-pc-max:h-5` - Высота 5% на планшетном ПК макс.
- `.tablet-pc-max:h-auto` - Высота авто% на планшетном ПК макс.

##### Height - Pc Max (<= 1200px)

- `.hover:pc-max:h-100` - Высота 100% при наведении на ПК макс.
- `.hover:pc-max:h-95` - Высота 95% при наведении на ПК макс.
- `.hover:pc-max:h-90` - Высота 90% при наведении на ПК макс.
- `.hover:pc-max:h-85` - Высота 85% при наведении на ПК макс.
- `.hover:pc-max:h-80` - Высота 80% при наведении на ПК макс.
- `.hover:pc-max:h-75` - Высота 75% при наведении на ПК макс.
- `.hover:pc-max:h-70` - Высота 70% при наведении на ПК макс.
- `.hover:pc-max:h-65` - Высота 65% при наведении на ПК макс.
- `.hover:pc-max:h-60` - Высота 60% при наведении на ПК макс.
- `.hover:pc-max:h-55` - Высота 55% при наведении на ПК макс.
- `.hover:pc-max:h-50` - Высота 50% при наведении на ПК макс.
- `.hover:pc-max:h-45` - Высота 45% при наведении на ПК макс.
- `.hover:pc-max:h-40` - Высота 40% при наведении на ПК макс.
- `.hover:pc-max:h-35` - Высота 35% при наведении на ПК макс.
- `.hover:pc-max:h-30` - Высота 30% при наведении на ПК макс.
- `.hover:pc-max:h-25` - Высота 25% при наведении на ПК макс.
- `.hover:pc-max:h-20` - Высота 20% при наведении на ПК макс.
- `.hover:pc-max:h-15` - Высота 15% при наведении на ПК макс.
- `.hover:pc-max:h-10` - Высота 10% при наведении на ПК макс.
- `.hover:pc-max:h-5` - Высота 5% при наведении на ПК макс.
- `.hover:pc-max:h-auto` - Высота авто% при наведении на ПК макс.
- `.pc-max:h-100` - Высота 100% на ПК макс.
- `.pc-max:h-95` - Высота 95% на ПК макс.
- `.pc-max:h-90` - Высота 90% на ПК макс.
- `.pc-max:h-85` - Высота 85% на ПК макс.
- `.pc-max:h-80` - Высота 80% на ПК макс.
- `.pc-max:h-75` - Высота 75% на ПК макс.
- `.pc-max:h-70` - Высота 70% на ПК макс.
- `.pc-max:h-65` - Высота 65% на ПК макс.
- `.pc-max:h-60` - Высота 60% на ПК макс.
- `.pc-max:h-55` - Высота 55% на ПК макс.
- `.pc-max:h-50` - Высота 50% на ПК макс.
- `.pc-max:h-45` - Высота 45% на ПК макс.
- `.pc-max:h-40` - Высота 40% на ПК макс.
- `.pc-max:h-35` - Высота 35% на ПК макс.
- `.pc-max:h-30` - Высота 30% на ПК макс.
- `.pc-max:h-25` - Высота 25% на ПК макс.
- `.pc-max:h-20` - Высота 20% на ПК макс.
- `.pc-max:h-15` - Высота 15% на ПК макс.
- `.pc-max:h-10` - Высота 10% на ПК макс.
- `.pc-max:h-5` - Высота 5% на ПК макс.
- `.pc-max:h-auto` - Высота авто% на ПК макс.

#### Height vh

- `.h-vh-100` - Высота вх 100vh
- `.h-vh-75` - Высота вх 75vh
- `.h-vh-50` - Высота вх 50vh
- `.h-vh-25` - Высота вх 25vh
- `.hover:h-vh-100` - Высота vh 100vh при наведении
- `.hover:h-vh-75` - Высота vh 75vh при наведении
- `.hover:h-vh-50` - Высота vh 50vh при наведении
- `.hover:h-vh-25` - Высота vh 25vh при наведении

#### Height vw

- `.h-vw-100` - Высота vw 100vw
- `.h-vw-75` - Высота автомобиля 75vw
- `.h-vw-50` - Высота vw 50vw
- `.h-vw-25` - Высота vw 25vw
- `.hover:h-vw-100` - Высота vw 100vw при наведении
- `.hover:h-vw-75` - Высота vw 75vw при наведении
- `.hover:h-vw-50` - Высота vw 50vw при наведении
- `.hover:h-vw-25` - Высота vw 25vw при наведении

## Positioning

### Static

- `.hover:static` - Статика при наведении
- `.static` - Статический

### Relative

- `.hover:relative` - Относительный при наведении
- `.relative` - Родственник

### Absolute

- `.absolute` - Абсолютный
- `.hover:absolute` - Абсолют при наведении

### Fixed

- `.fixed` - Зафиксированный
- `.hover:fixed` - Исправлено при наведении

### Sticky

- `.hover:sticky` - Прилипает при наведении
- `.sticky` - Липкий

### Top

- `.hover:top-100` - Смещение сверху 100% при наведении
- `.hover:top-75` - Смещение сверху 75% при наведении
- `.hover:top-50` - Смещение сверху 50% при наведении
- `.hover:top-25` - Смещение сверху 25% при наведении
- `.hover:top-5` - Смещение сверху 5rem при наведении
- `.hover:top-4.5` - Смещение сверху 4.5rem при наведении
- `.hover:top-4` - Смещение сверху 4rem при наведении
- `.hover:top-3.5` - Смещение сверху 3.5rem при наведении
- `.hover:top-3` - Смещение сверху 3rem при наведении
- `.hover:top-2.5` - Смещение сверху 2.5rem при наведении
- `.hover:top-2` - Смещение сверху 2rem при наведении
- `.hover:top-1.9` - Смещение сверху 1.9rem при наведении
- `.hover:top-1.8` - Смещение сверху 1.8rem при наведении
- `.hover:top-1.7` - Смещение сверху 1.7rem при наведении
- `.hover:top-1.6` - Смещение сверху 1.6rem при наведении
- `.hover:top-1.5` - Смещение сверху 1.5rem при наведении
- `.hover:top-1.4` - Смещение сверху 1.4rem при наведении
- `.hover:top-1.3` - Смещение сверху 1.3rem при наведении
- `.hover:top-1.2` - Смещение сверху 1.2rem при наведении
- `.hover:top-1.1` - Смещение сверху 1.1rem при наведении
- `.hover:top-1` - Смещение сверху 1rem при наведении
- `.hover:top-0.9` - Смещение сверху 0.9rem при наведении
- `.hover:top-0.8` - Смещение сверху 0.8rem при наведении
- `.hover:top-0.7` - Смещение сверху 0.7rem при наведении
- `.hover:top-0.6` - Смещение сверху 0.6rem при наведении
- `.hover:top-0.5` - Смещение сверху 0.5rem при наведении
- `.hover:top-0.4` - Смещение сверху 0.4rem при наведении
- `.hover:top-0.3` - Смещение сверху 0.3rem при наведении
- `.hover:top-0.2` - Смещение сверху 0.2rem при наведении
- `.hover:top-0.1` - Смещение сверху 0.1rem при наведении
- `.hover:top-0` - Смещение сверху 0rem при наведении
- `.top-100` - Смещение сверху 100%
- `.top-75` - Смещение сверху 75%
- `.top-50` - Смещение сверху 50%
- `.top-25` - Смещение сверху 25%
- `.top-5` - Смещение сверху 5rem
- `.top-4.5` - Смещение сверху 4.5rem
- `.top-4` - Смещение сверху 4rem
- `.top-3.5` - Смещение сверху 3.5rem
- `.top-3` - Смещение сверху 3rem
- `.top-2.5` - Смещение сверху 2.5rem
- `.top-2` - Смещение сверху 2rem
- `.top-1.9` - Смещение сверху 1.9rem
- `.top-1.8` - Смещение сверху 1.8rem
- `.top-1.7` - Смещение сверху 1.7rem
- `.top-1.6` - Смещение сверху 1.6rem
- `.top-1.5` - Смещение сверху 1.5rem
- `.top-1.4` - Смещение сверху 1.4rem
- `.top-1.3` - Смещение сверху 1.3rem
- `.top-1.2` - Смещение сверху 1.2rem
- `.top-1.1` - Смещение сверху 1.1rem
- `.top-1` - Смещение сверху 1rem
- `.top-0.9` - Смещение сверху 0.9rem
- `.top-0.8` - Смещение сверху 0.8rem
- `.top-0.7` - Смещение сверху 0.7rem
- `.top-0.6` - Смещение сверху 0.6rem
- `.top-0.5` - Смещение сверху 0.5rem
- `.top-0.4` - Смещение сверху 0.4rem
- `.top-0.3` - Смещение сверху 0.3rem
- `.top-0.2` - Смещение сверху 0.2rem
- `.top-0.1` - Смещение сверху 0.1rem
- `.top-0` - Смещение сверху 0rem

##### Negative Top

- `.-top-5` - Отрицательное смещение сверху 5rem
- `.-top-4.5` - Отрицательное смещение сверху 4.5rem
- `.-top-4` - Отрицательное смещение сверху 4rem
- `.-top-3.5` - Отрицательное смещение сверху 3.5rem
- `.-top-3` - Отрицательное смещение сверху 3rem
- `.-top-2.5` - Отрицательное смещение сверху 2.5rem
- `.-top-2` - Отрицательное смещение сверху 2rem
- `.-top-1.9` - Отрицательное смещение сверху 1.9rem
- `.-top-1.8` - Отрицательное смещение сверху 1.8rem
- `.-top-1.7` - Отрицательное смещение сверху 1.7rem
- `.-top-1.6` - Отрицательное смещение сверху 1.6rem
- `.-top-1.5` - Отрицательное смещение сверху 1.5rem
- `.-top-1.4` - Отрицательное смещение сверху 1.4rem
- `.-top-1.3` - Отрицательное смещение сверху 1.3rem
- `.-top-1.2` - Отрицательное смещение сверху 1.2rem
- `.-top-1.1` - Отрицательное смещение сверху 1.1rem
- `.-top-1` - Отрицательное смещение сверху 1rem
- `.-top-0.9` - Отрицательное смещение сверху 0.9rem
- `.-top-0.8` - Отрицательное смещение сверху 0.8rem
- `.-top-0.7` - Отрицательное смещение сверху 0.7rem
- `.-top-0.6` - Отрицательное смещение сверху 0.6rem
- `.-top-0.5` - Отрицательное смещение сверху 0.5rem
- `.-top-0.4` - Отрицательное смещение сверху 0.4rem
- `.-top-0.3` - Отрицательное смещение сверху 0.3rem
- `.-top-0.2` - Отрицательное смещение сверху 0.2rem
- `.-top-0.1` - Отрицательное смещение сверху 0.1rem
- `.hover:-top-5` - Отрицательное смещение сверху 5rem при наведении
- `.hover:-top-4.5` - Отрицательное смещение сверху 4.5rem при наведении
- `.hover:-top-4` - Отрицательное смещение сверху 4rem при наведении
- `.hover:-top-3.5` - Отрицательное смещение сверху 3.5rem при наведении
- `.hover:-top-3` - Отрицательное смещение сверху 3rem при наведении
- `.hover:-top-2.5` - Отрицательное смещение сверху 2.5rem при наведении
- `.hover:-top-2` - Отрицательное смещение сверху 2rem при наведении
- `.hover:-top-1.9` - Отрицательное смещение сверху 1.9rem при наведении
- `.hover:-top-1.8` - Отрицательное смещение сверху 1.8rem при наведении
- `.hover:-top-1.7` - Отрицательное смещение сверху 1.7rem при наведении
- `.hover:-top-1.6` - Отрицательное смещение сверху 1.6rem при наведении
- `.hover:-top-1.5` - Отрицательное смещение сверху 1.5rem при наведении
- `.hover:-top-1.4` - Отрицательное смещение сверху 1.4rem при наведении
- `.hover:-top-1.3` - Отрицательное смещение сверху 1.3rem при наведении
- `.hover:-top-1.2` - Отрицательное смещение сверху 1.2rem при наведении
- `.hover:-top-1.1` - Отрицательное смещение сверху 1.1rem при наведении
- `.hover:-top-1` - Отрицательное смещение сверху 1rem при наведении
- `.hover:-top-0.9` - Отрицательное смещение сверху 0.9rem при наведении
- `.hover:-top-0.8` - Отрицательное смещение сверху 0.8rem при наведении
- `.hover:-top-0.7` - Отрицательное смещение сверху 0.7rem при наведении
- `.hover:-top-0.6` - Отрицательное смещение сверху 0.6rem при наведении
- `.hover:-top-0.5` - Отрицательное смещение сверху 0.5rem при наведении
- `.hover:-top-0.4` - Отрицательное смещение сверху 0.4rem при наведении
- `.hover:-top-0.3` - Отрицательное смещение сверху 0.3rem при наведении
- `.hover:-top-0.2` - Отрицательное смещение сверху 0.2rem при наведении
- `.hover:-top-0.1` - Отрицательное смещение сверху 0.1rem при наведении

### Right

- `.hover:right-100` - Смещение справа 100% при наведении
- `.hover:right-75` - Смещение справа 75% при наведении
- `.hover:right-50` - Смещение справа 50% при наведении
- `.hover:right-25` - Смещение справа 25% при наведении
- `.hover:right-5` - Смещение справа 5rem при наведении
- `.hover:right-4.5` - Смещение справа 4.5rem при наведении
- `.hover:right-4` - Смещение справа 4rem при наведении
- `.hover:right-3.5` - Смещение справа 3.5rem при наведении
- `.hover:right-3` - Смещение справа 3rem при наведении
- `.hover:right-2.5` - Смещение справа 2.5rem при наведении
- `.hover:right-2` - Смещение справа 2rem при наведении
- `.hover:right-1.9` - Смещение справа 1.9rem при наведении
- `.hover:right-1.8` - Смещение справа 1.8rem при наведении
- `.hover:right-1.7` - Смещение справа 1.7rem при наведении
- `.hover:right-1.6` - Смещение справа 1.6rem при наведении
- `.hover:right-1.5` - Смещение справа 1.5rem при наведении
- `.hover:right-1.4` - Смещение справа 1.4rem при наведении
- `.hover:right-1.3` - Смещение справа 1.3rem при наведении
- `.hover:right-1.2` - Смещение справа 1.2rem при наведении
- `.hover:right-1.1` - Смещение справа 1.1rem при наведении
- `.hover:right-1` - Смещение справа 1rem при наведении
- `.hover:right-0.9` - Смещение справа 0.9rem при наведении
- `.hover:right-0.8` - Смещение справа 0.8rem при наведении
- `.hover:right-0.7` - Смещение справа 0.7rem при наведении
- `.hover:right-0.6` - Смещение справа 0.6rem при наведении
- `.hover:right-0.5` - Смещение справа 0.5rem при наведении
- `.hover:right-0.4` - Смещение справа 0.4rem при наведении
- `.hover:right-0.3` - Смещение справа 0.3rem при наведении
- `.hover:right-0.2` - Смещение справа 0.2rem при наведении
- `.hover:right-0.1` - Смещение справа 0.1rem при наведении
- `.hover:right-0` - Смещение справа 0rem при наведении
- `.right-100` - Смещение справа 100%
- `.right-75` - Смещение справа 75%
- `.right-50` - Смещение справа 50%
- `.right-25` - Смещение справа 25%
- `.right-5` - Смещение справа 5rem
- `.right-4.5` - Смещение справа 4.5rem
- `.right-4` - Смещение справа 4rem
- `.right-3.5` - Смещение справа 3.5rem
- `.right-3` - Смещение справа 3rem
- `.right-2.5` - Смещение справа 2.5rem
- `.right-2` - Смещение справа 2rem
- `.right-1.9` - Смещение справа 1.9rem
- `.right-1.8` - Смещение справа 1.8rem
- `.right-1.7` - Смещение справа 1.7rem
- `.right-1.6` - Смещение справа 1.6rem
- `.right-1.5` - Смещение справа 1.5rem
- `.right-1.4` - Смещение справа 1.4rem
- `.right-1.3` - Смещение справа 1.3rem
- `.right-1.2` - Смещение справа 1.2rem
- `.right-1.1` - Смещение справа 1.1rem
- `.right-1` - Смещение справа 1rem
- `.right-0.9` - Смещение справа 0.9rem
- `.right-0.8` - Смещение справа 0.8rem
- `.right-0.7` - Смещение справа 0.7rem
- `.right-0.6` - Смещение справа 0.6rem
- `.right-0.5` - Смещение справа 0.5rem
- `.right-0.4` - Смещение справа 0.4rem
- `.right-0.3` - Смещение справа 0.3rem
- `.right-0.2` - Смещение справа 0.2rem
- `.right-0.1` - Смещение справа 0.1rem
- `.right-0` - Смещение справа 0rem

##### Negative Right

- `.-right-5` - Отрицательное смещение справа 5rem
- `.-right-4.5` - Отрицательное смещение справа 4.5rem
- `.-right-4` - Отрицательное смещение справа 4rem
- `.-right-3.5` - Отрицательное смещение справа 3.5rem
- `.-right-3` - Отрицательное смещение справа 3rem
- `.-right-2.5` - Отрицательное смещение справа 2.5rem
- `.-right-2` - Отрицательное смещение справа 2rem
- `.-right-1.9` - Отрицательное смещение справа 1.9rem
- `.-right-1.8` - Отрицательное смещение справа 1.8rem
- `.-right-1.7` - Отрицательное смещение справа 1.7rem
- `.-right-1.6` - Отрицательное смещение справа 1.6rem
- `.-right-1.5` - Отрицательное смещение справа 1.5rem
- `.-right-1.4` - Отрицательное смещение справа 1.4rem
- `.-right-1.3` - Отрицательное смещение справа 1.3rem
- `.-right-1.2` - Отрицательное смещение справа 1.2rem
- `.-right-1.1` - Отрицательное смещение справа 1.1rem
- `.-right-1` - Отрицательное смещение справа 1rem
- `.-right-0.9` - Отрицательное смещение справа 0.9rem
- `.-right-0.8` - Отрицательное смещение справа 0.8rem
- `.-right-0.7` - Отрицательное смещение справа 0.7rem
- `.-right-0.6` - Отрицательное смещение справа 0.6rem
- `.-right-0.5` - Отрицательное смещение справа 0.5rem
- `.-right-0.4` - Отрицательное смещение справа 0.4rem
- `.-right-0.3` - Отрицательное смещение справа 0.3rem
- `.-right-0.2` - Отрицательное смещение справа 0.2rem
- `.-right-0.1` - Отрицательное смещение справа 0.1rem
- `.hover:-right-5` - Отрицательное смещение справа 5rem при наведении
- `.hover:-right-4.5` - Отрицательное смещение справа 4.5rem при наведении
- `.hover:-right-4` - Отрицательное смещение справа 4rem при наведении
- `.hover:-right-3.5` - Отрицательное смещение справа 3.5rem при наведении
- `.hover:-right-3` - Отрицательное смещение справа 3rem при наведении
- `.hover:-right-2.5` - Отрицательное смещение справа 2.5rem при наведении
- `.hover:-right-2` - Отрицательное смещение справа 2rem при наведении
- `.hover:-right-1.9` - Отрицательное смещение справа 1.9rem при наведении
- `.hover:-right-1.8` - Отрицательное смещение справа 1.8rem при наведении
- `.hover:-right-1.7` - Отрицательное смещение справа 1.7rem при наведении
- `.hover:-right-1.6` - Отрицательное смещение справа 1.6rem при наведении
- `.hover:-right-1.5` - Отрицательное смещение справа 1.5rem при наведении
- `.hover:-right-1.4` - Отрицательное смещение справа 1.4rem при наведении
- `.hover:-right-1.3` - Отрицательное смещение справа 1.3rem при наведении
- `.hover:-right-1.2` - Отрицательное смещение справа 1.2rem при наведении
- `.hover:-right-1.1` - Отрицательное смещение справа 1.1rem при наведении
- `.hover:-right-1` - Отрицательное смещение справа 1rem при наведении
- `.hover:-right-0.9` - Отрицательное смещение справа 0.9rem при наведении
- `.hover:-right-0.8` - Отрицательное смещение справа 0.8rem при наведении
- `.hover:-right-0.7` - Отрицательное смещение справа 0.7rem при наведении
- `.hover:-right-0.6` - Отрицательное смещение справа 0.6rem при наведении
- `.hover:-right-0.5` - Отрицательное смещение справа 0.5rem при наведении
- `.hover:-right-0.4` - Отрицательное смещение справа 0.4rem при наведении
- `.hover:-right-0.3` - Отрицательное смещение справа 0.3rem при наведении
- `.hover:-right-0.2` - Отрицательное смещение справа 0.2rem при наведении
- `.hover:-right-0.1` - Отрицательное смещение справа 0.1rem при наведении

### Bottom

- `.bottom-100` - Смещение снизу 100%
- `.bottom-75` - Смещение снизу 75%
- `.bottom-50` - Смещение снизу 50%
- `.bottom-25` - Смещение снизу 25%
- `.bottom-5` - Смещение снизу 5rem
- `.bottom-4.5` - Смещение снизу 4.5rem
- `.bottom-4` - Смещение снизу 4rem
- `.bottom-3.5` - Смещение снизу 3.5rem
- `.bottom-3` - Смещение снизу 3rem
- `.bottom-2.5` - Смещение снизу 2.5rem
- `.bottom-2` - Смещение снизу 2rem
- `.bottom-1.9` - Смещение снизу 1.9rem
- `.bottom-1.8` - Смещение снизу 1.8rem
- `.bottom-1.7` - Смещение снизу 1.7rem
- `.bottom-1.6` - Смещение снизу 1.6rem
- `.bottom-1.5` - Смещение снизу 1.5rem
- `.bottom-1.4` - Смещение снизу 1.4rem
- `.bottom-1.3` - Смещение снизу 1.3rem
- `.bottom-1.2` - Смещение снизу 1.2rem
- `.bottom-1.1` - Смещение снизу 1.1rem
- `.bottom-1` - Смещение снизу 1rem
- `.bottom-0.9` - Смещение снизу 0.9rem
- `.bottom-0.8` - Смещение снизу 0.8rem
- `.bottom-0.7` - Смещение снизу 0.7rem
- `.bottom-0.6` - Смещение снизу 0.6rem
- `.bottom-0.5` - Смещение снизу 0.5rem
- `.bottom-0.4` - Смещение снизу 0.4rem
- `.bottom-0.3` - Смещение снизу 0.3rem
- `.bottom-0.2` - Смещение снизу 0.2rem
- `.bottom-0.1` - Смещение снизу 0.1rem
- `.bottom-0` - Смещение снизу 0rem
- `.hover:bottom-100` - Смещение снизу 100% при наведении
- `.hover:bottom-75` - Смещение снизу 75% при наведении
- `.hover:bottom-50` - Смещение снизу 50% при наведении
- `.hover:bottom-25` - Смещение снизу 25% при наведении
- `.hover:bottom-5` - Смещение снизу 5rem при наведении
- `.hover:bottom-4.5` - Смещение снизу 4.5rem при наведении
- `.hover:bottom-4` - Смещение снизу 4rem при наведении
- `.hover:bottom-3.5` - Смещение снизу 3.5rem при наведении
- `.hover:bottom-3` - Смещение снизу 3rem при наведении
- `.hover:bottom-2.5` - Смещение снизу 2.5rem при наведении
- `.hover:bottom-2` - Смещение снизу 2rem при наведении
- `.hover:bottom-1.9` - Смещение снизу 1.9rem при наведении
- `.hover:bottom-1.8` - Смещение снизу 1.8rem при наведении
- `.hover:bottom-1.7` - Смещение снизу 1.7rem при наведении
- `.hover:bottom-1.6` - Смещение снизу 1.6rem при наведении
- `.hover:bottom-1.5` - Смещение снизу 1.5rem при наведении
- `.hover:bottom-1.4` - Смещение снизу 1.4rem при наведении
- `.hover:bottom-1.3` - Смещение снизу 1.3rem при наведении
- `.hover:bottom-1.2` - Смещение снизу 1.2rem при наведении
- `.hover:bottom-1.1` - Смещение снизу 1.1rem при наведении
- `.hover:bottom-1` - Смещение снизу 1rem при наведении
- `.hover:bottom-0.9` - Смещение снизу 0.9rem при наведении
- `.hover:bottom-0.8` - Смещение снизу 0.8rem при наведении
- `.hover:bottom-0.7` - Смещение снизу 0.7rem при наведении
- `.hover:bottom-0.6` - Смещение снизу 0.6rem при наведении
- `.hover:bottom-0.5` - Смещение снизу 0.5rem при наведении
- `.hover:bottom-0.4` - Смещение снизу 0.4rem при наведении
- `.hover:bottom-0.3` - Смещение снизу 0.3rem при наведении
- `.hover:bottom-0.2` - Смещение снизу 0.2rem при наведении
- `.hover:bottom-0.1` - Смещение снизу 0.1rem при наведении
- `.hover:bottom-0` - Смещение снизу 0rem при наведении

##### Negative Bottom

- `.-bottom-5` - Отрицательное смещение снизу 5rem
- `.-bottom-4.5` - Отрицательное смещение снизу 4.5rem
- `.-bottom-4` - Отрицательное смещение снизу 4rem
- `.-bottom-3.5` - Отрицательное смещение снизу 3.5rem
- `.-bottom-3` - Отрицательное смещение снизу 3rem
- `.-bottom-2.5` - Отрицательное смещение снизу 2.5rem
- `.-bottom-2` - Отрицательное смещение снизу 2rem
- `.-bottom-1.9` - Отрицательное смещение снизу 1.9rem
- `.-bottom-1.8` - Отрицательное смещение снизу 1.8rem
- `.-bottom-1.7` - Отрицательное смещение снизу 1.7rem
- `.-bottom-1.6` - Отрицательное смещение снизу 1.6rem
- `.-bottom-1.5` - Отрицательное смещение снизу 1.5rem
- `.-bottom-1.4` - Отрицательное смещение снизу 1.4rem
- `.-bottom-1.3` - Отрицательное смещение снизу 1.3rem
- `.-bottom-1.2` - Отрицательное смещение снизу 1.2rem
- `.-bottom-1.1` - Отрицательное смещение снизу 1.1rem
- `.-bottom-1` - Отрицательное смещение снизу 1rem
- `.-bottom-0.9` - Отрицательное смещение снизу 0.9rem
- `.-bottom-0.8` - Отрицательное смещение снизу 0.8rem
- `.-bottom-0.7` - Отрицательное смещение снизу 0.7rem
- `.-bottom-0.6` - Отрицательное смещение снизу 0.6rem
- `.-bottom-0.5` - Отрицательное смещение снизу 0.5rem
- `.-bottom-0.4` - Отрицательное смещение снизу 0.4rem
- `.-bottom-0.3` - Отрицательное смещение снизу 0.3rem
- `.-bottom-0.2` - Отрицательное смещение снизу 0.2rem
- `.-bottom-0.1` - Отрицательное смещение снизу 0.1rem
- `.hover:-bottom-5` - Отрицательное смещение снизу 5rem при наведении
- `.hover:-bottom-4.5` - Отрицательное смещение снизу 4.5rem при наведении
- `.hover:-bottom-4` - Отрицательное смещение снизу 4rem при наведении
- `.hover:-bottom-3.5` - Отрицательное смещение снизу 3.5rem при наведении
- `.hover:-bottom-3` - Отрицательное смещение снизу 3rem при наведении
- `.hover:-bottom-2.5` - Отрицательное смещение снизу 2.5rem при наведении
- `.hover:-bottom-2` - Отрицательное смещение снизу 2rem при наведении
- `.hover:-bottom-1.9` - Отрицательное смещение снизу 1.9rem при наведении
- `.hover:-bottom-1.8` - Отрицательное смещение снизу 1.8rem при наведении
- `.hover:-bottom-1.7` - Отрицательное смещение снизу 1.7rem при наведении
- `.hover:-bottom-1.6` - Отрицательное смещение снизу 1.6rem при наведении
- `.hover:-bottom-1.5` - Отрицательное смещение снизу 1.5rem при наведении
- `.hover:-bottom-1.4` - Отрицательное смещение снизу 1.4rem при наведении
- `.hover:-bottom-1.3` - Отрицательное смещение снизу 1.3rem при наведении
- `.hover:-bottom-1.2` - Отрицательное смещение снизу 1.2rem при наведении
- `.hover:-bottom-1.1` - Отрицательное смещение снизу 1.1rem при наведении
- `.hover:-bottom-1` - Отрицательное смещение снизу 1rem при наведении
- `.hover:-bottom-0.9` - Отрицательное смещение снизу 0.9rem при наведении
- `.hover:-bottom-0.8` - Отрицательное смещение снизу 0.8rem при наведении
- `.hover:-bottom-0.7` - Отрицательное смещение снизу 0.7rem при наведении
- `.hover:-bottom-0.6` - Отрицательное смещение снизу 0.6rem при наведении
- `.hover:-bottom-0.5` - Отрицательное смещение снизу 0.5rem при наведении
- `.hover:-bottom-0.4` - Отрицательное смещение снизу 0.4rem при наведении
- `.hover:-bottom-0.3` - Отрицательное смещение снизу 0.3rem при наведении
- `.hover:-bottom-0.2` - Отрицательное смещение снизу 0.2rem при наведении
- `.hover:-bottom-0.1` - Отрицательное смещение снизу 0.1rem при наведении

### Left

- `.hover:left-100` - Смещение слева 100% при наведении
- `.hover:left-75` - Смещение слева 75% при наведении
- `.hover:left-50` - Смещение слева 50% при наведении
- `.hover:left-25` - Смещение слева 25% при наведении
- `.hover:left-5` - Смещение слева 5rem при наведении
- `.hover:left-4.5` - Смещение слева 4.5rem при наведении
- `.hover:left-4` - Смещение слева 4rem при наведении
- `.hover:left-3.5` - Смещение слева 3.5rem при наведении
- `.hover:left-3` - Смещение слева 3rem при наведении
- `.hover:left-2.5` - Смещение слева 2.5rem при наведении
- `.hover:left-2` - Смещение слева 2rem при наведении
- `.hover:left-1.9` - Смещение слева 1.9rem при наведении
- `.hover:left-1.8` - Смещение слева 1.8rem при наведении
- `.hover:left-1.7` - Смещение слева 1.7rem при наведении
- `.hover:left-1.6` - Смещение слева 1.6rem при наведении
- `.hover:left-1.5` - Смещение слева 1.5rem при наведении
- `.hover:left-1.4` - Смещение слева 1.4rem при наведении
- `.hover:left-1.3` - Смещение слева 1.3rem при наведении
- `.hover:left-1.2` - Смещение слева 1.2rem при наведении
- `.hover:left-1.1` - Смещение слева 1.1rem при наведении
- `.hover:left-1` - Смещение слева 1rem при наведении
- `.hover:left-0.9` - Смещение слева 0.9rem при наведении
- `.hover:left-0.8` - Смещение слева 0.8rem при наведении
- `.hover:left-0.7` - Смещение слева 0.7rem при наведении
- `.hover:left-0.6` - Смещение слева 0.6rem при наведении
- `.hover:left-0.5` - Смещение слева 0.5rem при наведении
- `.hover:left-0.4` - Смещение слева 0.4rem при наведении
- `.hover:left-0.3` - Смещение слева 0.3rem при наведении
- `.hover:left-0.2` - Смещение слева 0.2rem при наведении
- `.hover:left-0.1` - Смещение слева 0.1rem при наведении
- `.hover:left-0` - Смещение слева 0rem при наведении
- `.left-100` - Смещение слева 100%
- `.left-75` - Смещение слева 75%
- `.left-50` - Смещение слева 50%
- `.left-25` - Смещение слева 25%
- `.left-5` - Смещение слева 5rem
- `.left-4.5` - Смещение слева 4.5rem
- `.left-4` - Смещение слева 4rem
- `.left-3.5` - Смещение слева 3.5rem
- `.left-3` - Смещение слева 3rem
- `.left-2.5` - Смещение слева 2.5rem
- `.left-2` - Смещение слева 2rem
- `.left-1.9` - Смещение слева 1.9rem
- `.left-1.8` - Смещение слева 1.8rem
- `.left-1.7` - Смещение слева 1.7rem
- `.left-1.6` - Смещение слева 1.6rem
- `.left-1.5` - Смещение слева 1.5rem
- `.left-1.4` - Смещение слева 1.4rem
- `.left-1.3` - Смещение слева 1.3rem
- `.left-1.2` - Смещение слева 1.2rem
- `.left-1.1` - Смещение слева 1.1rem
- `.left-1` - Смещение слева 1rem
- `.left-0.9` - Смещение слева 0.9rem
- `.left-0.8` - Смещение слева 0.8rem
- `.left-0.7` - Смещение слева 0.7rem
- `.left-0.6` - Смещение слева 0.6rem
- `.left-0.5` - Смещение слева 0.5rem
- `.left-0.4` - Смещение слева 0.4rem
- `.left-0.3` - Смещение слева 0.3rem
- `.left-0.2` - Смещение слева 0.2rem
- `.left-0.1` - Смещение слева 0.1rem
- `.left-0` - Смещение слева 0rem

##### Negative Left

- `.-left-5` - Отрицательное смещение слева 5rem
- `.-left-4.5` - Отрицательное смещение слева 4.5rem
- `.-left-4` - Отрицательное смещение слева 4rem
- `.-left-3.5` - Отрицательное смещение слева 3.5rem
- `.-left-3` - Отрицательное смещение слева 3rem
- `.-left-2.5` - Отрицательное смещение слева 2.5rem
- `.-left-2` - Отрицательное смещение слева 2rem
- `.-left-1.9` - Отрицательное смещение слева 1.9rem
- `.-left-1.8` - Отрицательное смещение слева 1.8rem
- `.-left-1.7` - Отрицательное смещение слева 1.7rem
- `.-left-1.6` - Отрицательное смещение слева 1.6rem
- `.-left-1.5` - Отрицательное смещение слева 1.5rem
- `.-left-1.4` - Отрицательное смещение слева 1.4rem
- `.-left-1.3` - Отрицательное смещение слева 1.3rem
- `.-left-1.2` - Отрицательное смещение слева 1.2rem
- `.-left-1.1` - Отрицательное смещение слева 1.1rem
- `.-left-1` - Отрицательное смещение слева 1rem
- `.-left-0.9` - Отрицательное смещение слева 0.9rem
- `.-left-0.8` - Отрицательное смещение слева 0.8rem
- `.-left-0.7` - Отрицательное смещение слева 0.7rem
- `.-left-0.6` - Отрицательное смещение слева 0.6rem
- `.-left-0.5` - Отрицательное смещение слева 0.5rem
- `.-left-0.4` - Отрицательное смещение слева 0.4rem
- `.-left-0.3` - Отрицательное смещение слева 0.3rem
- `.-left-0.2` - Отрицательное смещение слева 0.2rem
- `.-left-0.1` - Отрицательное смещение слева 0.1rem
- `.hover:-left-5` - Отрицательное смещение слева 5rem при наведении
- `.hover:-left-4.5` - Отрицательное смещение слева 4.5rem при наведении
- `.hover:-left-4` - Отрицательное смещение слева 4rem при наведении
- `.hover:-left-3.5` - Отрицательное смещение слева 3.5rem при наведении
- `.hover:-left-3` - Отрицательное смещение слева 3rem при наведении
- `.hover:-left-2.5` - Отрицательное смещение слева 2.5rem при наведении
- `.hover:-left-2` - Отрицательное смещение слева 2rem при наведении
- `.hover:-left-1.9` - Отрицательное смещение слева 1.9rem при наведении
- `.hover:-left-1.8` - Отрицательное смещение слева 1.8rem при наведении
- `.hover:-left-1.7` - Отрицательное смещение слева 1.7rem при наведении
- `.hover:-left-1.6` - Отрицательное смещение слева 1.6rem при наведении
- `.hover:-left-1.5` - Отрицательное смещение слева 1.5rem при наведении
- `.hover:-left-1.4` - Отрицательное смещение слева 1.4rem при наведении
- `.hover:-left-1.3` - Отрицательное смещение слева 1.3rem при наведении
- `.hover:-left-1.2` - Отрицательное смещение слева 1.2rem при наведении
- `.hover:-left-1.1` - Отрицательное смещение слева 1.1rem при наведении
- `.hover:-left-1` - Отрицательное смещение слева 1rem при наведении
- `.hover:-left-0.9` - Отрицательное смещение слева 0.9rem при наведении
- `.hover:-left-0.8` - Отрицательное смещение слева 0.8rem при наведении
- `.hover:-left-0.7` - Отрицательное смещение слева 0.7rem при наведении
- `.hover:-left-0.6` - Отрицательное смещение слева 0.6rem при наведении
- `.hover:-left-0.5` - Отрицательное смещение слева 0.5rem при наведении
- `.hover:-left-0.4` - Отрицательное смещение слева 0.4rem при наведении
- `.hover:-left-0.3` - Отрицательное смещение слева 0.3rem при наведении
- `.hover:-left-0.2` - Отрицательное смещение слева 0.2rem при наведении
- `.hover:-left-0.1` - Отрицательное смещение слева 0.1rem при наведении

### Z-Index

- `.hover:z-5` - Z-индекс 1005 при наведении
- `.hover:z-4` - Z-индекс 1004 при наведении
- `.hover:z-3` - Z-индекс 1003 при наведении
- `.hover:z-2` - Z-индекс 1002 при наведении
- `.hover:z-1` - Z-индекс 1001 при наведении
- `.hover:z-0` - Z-индекс 0 при наведении
- `.hover:z-auto` - Z-Index автоматически при наведении
- `.z-5` - Z-индекс 1005
- `.z-4` - Z-индекс 1004
- `.z-3` - Z-индекс 1003
- `.z-2` - Z-индекс 1002
- `.z-1` - Z-индекс 1001
- `.z-0` - Z-индекс 0
- `.z-auto` - Z-индекс авто

##### Negative Z-Index

- `.-z-5` - Отрицательный Z-индекс 5
- `.-z-4` - Отрицательный Z-индекс 4
- `.-z-3` - Отрицательный Z-индекс 3
- `.-z-2` - Отрицательный Z-индекс 2
- `.-z-1` - Отрицательный Z-индекс 1
- `.hover:-z-5` - Отрицательный Z-индекс 5 при наведении
- `.hover:-z-4` - Отрицательный Z-индекс 4 при наведении
- `.hover:-z-3` - Отрицательный Z-индекс 3 при наведении
- `.hover:-z-2` - Отрицательный Z-индекс 2 при наведении
- `.hover:-z-1` - Отрицательный Z-индекс 1 при наведении

## Typography

### Font

- `.font-italic` - Шрифт курсив
- `.font-normal` - Шрифт нормальный
- `.hover:font-italic` - Шрифт курсив при наведении
- `.hover:font-normal` - Шрифт нормальный при наведении

### Font Size

- `.font-size-10` - Размер шрифта 10rem
- `.font-size-9.5` - Размер шрифта 9.5rem
- `.font-size-9` - Размер шрифта 9rem
- `.font-size-8.5` - Размер шрифта 8.5rem
- `.font-size-8` - Размер шрифта 8rem
- `.font-size-7.5` - Размер шрифта 7.5rem
- `.font-size-7` - Размер шрифта 7rem
- `.font-size-6.5` - Размер шрифта 6.5rem
- `.font-size-6` - Размер шрифта 6rem
- `.font-size-5.5` - Размер шрифта 5.5rem
- `.font-size-5` - Размер шрифта 5rem
- `.font-size-4.5` - Размер шрифта 4.5rem
- `.font-size-4` - Размер шрифта 4rem
- `.font-size-3.5` - Размер шрифта 3.5rem
- `.font-size-3` - Размер шрифта 3rem
- `.font-size-2.5` - Размер шрифта 2.5rem
- `.font-size-2` - Размер шрифта 2rem
- `.font-size-1.9` - Размер шрифта 1.9rem
- `.font-size-1.8` - Размер шрифта 1.8rem
- `.font-size-1.7` - Размер шрифта 1.7rem
- `.font-size-1.6` - Размер шрифта 1.6rem
- `.font-size-1.5` - Размер шрифта 1.5rem
- `.font-size-1.4` - Размер шрифта 1.4rem
- `.font-size-1.3` - Размер шрифта 1.3rem
- `.font-size-1.2` - Размер шрифта 1.2rem
- `.font-size-1.1` - Размер шрифта 1.1rem
- `.font-size-1` - Размер шрифта 1rem
- `.font-size-0.9` - Размер шрифта 0.9rem
- `.font-size-0.8` - Размер шрифта 0.8rem
- `.font-size-0.7` - Размер шрифта 0,7rem
- `.font-size-0.6` - Размер шрифта 0,6rem
- `.font-size-0.5` - Размер шрифта 0,5rem
- `.hover:font-size-10` - Размер шрифта 10rem при наведении
- `.hover:font-size-9.5` - Размер шрифта 9.5rem при наведении
- `.hover:font-size-9` - Размер шрифта 9rem при наведении
- `.hover:font-size-8.5` - Размер шрифта 8.5rem при наведении
- `.hover:font-size-8` - Размер шрифта 8rem при наведении
- `.hover:font-size-7.5` - Размер шрифта 7.5rem при наведении
- `.hover:font-size-7` - Размер шрифта 7rem при наведении
- `.hover:font-size-6.5` - Размер шрифта 6.5rem при наведении
- `.hover:font-size-6` - Размер шрифта 6rem при наведении
- `.hover:font-size-5.5` - Размер шрифта 5.5rem при наведении
- `.hover:font-size-5` - Размер шрифта 5rem при наведении
- `.hover:font-size-4.5` - Размер шрифта 4.5rem при наведении
- `.hover:font-size-4` - Размер шрифта 4rem при наведении
- `.hover:font-size-3.5` - Размер шрифта 3.5rem при наведении
- `.hover:font-size-3` - Размер шрифта 3rem при наведении
- `.hover:font-size-2.5` - Размер шрифта 2.5rem при наведении
- `.hover:font-size-2` - Размер шрифта 2rem при наведении
- `.hover:font-size-1.9` - Размер шрифта 1.9rem при наведении
- `.hover:font-size-1.8` - Размер шрифта 1.8rem при наведении
- `.hover:font-size-1.7` - Размер шрифта 1.7rem при наведении
- `.hover:font-size-1.6` - Размер шрифта 1.6rem при наведении
- `.hover:font-size-1.5` - Размер шрифта 1.5rem при наведении
- `.hover:font-size-1.4` - Размер шрифта 1.4rem при наведении
- `.hover:font-size-1.3` - Размер шрифта 1.3rem при наведении
- `.hover:font-size-1.2` - Размер шрифта 1.2rem при наведении
- `.hover:font-size-1.1` - Размер шрифта 1.1rem при наведении
- `.hover:font-size-1` - Размер шрифта 1rem при наведении
- `.hover:font-size-0.9` - Размер шрифта 0.9rem при наведении
- `.hover:font-size-0.8` - Размер шрифта 0.8rem при наведении
- `.hover:font-size-0.7` - Размер шрифта 0,7rem при наведении
- `.hover:font-size-0.6` - Размер шрифта 0.6rem при наведении
- `.hover:font-size-0.5` - Размер шрифта 0,5rem при наведении

### Font Weight

- `.font-weight-900` - Вес шрифта 900
- `.font-weight-800` - Вес шрифта 800
- `.font-weight-700` - Вес шрифта 700
- `.font-weight-600` - Вес шрифта 600
- `.font-weight-500` - Вес шрифта 500
- `.font-weight-400` - Вес шрифта 400
- `.font-weight-300` - Вес шрифта 300
- `.font-weight-200` - Вес шрифта 200
- `.font-weight-100` - Вес шрифта 100
- `.font-weight-bold` - Вес шрифта жирный
- `.hover:font-weight-900` - Вес шрифта 900 при наведении
- `.hover:font-weight-800` - Вес шрифта 800 при наведении
- `.hover:font-weight-700` - Вес шрифта 700 при наведении
- `.hover:font-weight-600` - Вес шрифта 600 при наведении
- `.hover:font-weight-500` - Вес шрифта 500 при наведении
- `.hover:font-weight-400` - Вес шрифта 400 при наведении
- `.hover:font-weight-300` - Вес шрифта 300 при наведении
- `.hover:font-weight-200` - Вес шрифта 200 при наведении
- `.hover:font-weight-100` - Вес шрифта 100 при наведении
- `.hover:font-weight-bold` - Начертание шрифта жирным шрифтом при наведении

### Letter spacing

- `.hover:letter-spacing-1` - Расстояние между буквами 1rem при наведении
- `.hover:letter-spacing-0.9` - Расстояние между буквами 0.9rem при наведении
- `.hover:letter-spacing-0.8` - Расстояние между буквами 0.8rem при наведении
- `.hover:letter-spacing-0.7` - Расстояние между буквами 0.7rem при наведении
- `.hover:letter-spacing-0.6` - Расстояние между буквами 0.6rem при наведении
- `.hover:letter-spacing-0.5` - Расстояние между буквами 0.5rem при наведении
- `.hover:letter-spacing-0.4` - Расстояние между буквами 0.4rem при наведении
- `.hover:letter-spacing-0.3` - Расстояние между буквами 0,3rem при наведении
- `.hover:letter-spacing-0.2` - Расстояние между буквами 0,2rem при наведении
- `.hover:letter-spacing-0.1` - Расстояние между буквами 0,1rem при наведении
- `.letter-spacing-1` - Расстояние между буквами 1rem
- `.letter-spacing-0.9` - Расстояние между буквами 0.9rem
- `.letter-spacing-0.8` - Расстояние между буквами 0.8rem
- `.letter-spacing-0.7` - Расстояние между буквами 0.7rem
- `.letter-spacing-0.6` - Расстояние между буквами 0.6rem
- `.letter-spacing-0.5` - Расстояние между буквами 0.5rem
- `.letter-spacing-0.4` - Расстояние между буквами 0.4rem
- `.letter-spacing-0.3` - Расстояние между буквами 0,3rem
- `.letter-spacing-0.2` - Расстояние между буквами 0,2rem
- `.letter-spacing-0.1` - Расстояние между буквами 0,1rem

### Line height

- `.hover:line-height-5` - Высота строки 5rem при наведении
- `.hover:line-height-4` - Высота строки 4rem при наведении
- `.hover:line-height-3` - Высота строки 3rem при наведении
- `.hover:line-height-2` - Высота строки 2rem при наведении
- `.hover:line-height-1` - Высота строки 1rem при наведении
- `.line-height-5` - Высота строки 5rem
- `.line-height-4` - Высота строки 4rem
- `.line-height-3` - Высота строки 3rem
- `.line-height-2` - Высота строки 2rem
- `.line-height-1` - Высота строки 1rem

### Text

- `.hover:text-capitalize` - Текст с заглавной буквы при наведении
- `.hover:text-center` - Текст по центру при наведении
- `.hover:text-end` - Текст по концу строки при наведении
- `.hover:text-justify` - Текст по ширине при наведении
- `.hover:text-left` - Текст по левому краю при наведении
- `.hover:text-line-none` - Текстовая строка-нет при наведении
- `.hover:text-line-overline` - Текстовая строка перечеркивается при наведении
- `.hover:text-line-through` - Перечеркивание текста при наведении
- `.hover:text-line-underline` - Подчеркивание строки текста при наведении
- `.hover:text-lowercase` - Текст строчный при наведении
- `.hover:text-right` - Текст по правому краю при наведении
- `.hover:text-start` - Текст по началу строки при наведении
- `.hover:text-transparent` - Текст прозрачный при наведении
- `.hover:text-uppercase` - Текст в верхнем регистре при наведении
- `.text-break-all` - Текстовый разрыв
- `.text-break-keep-all` - Разрыв текста с сохранением всего
- `.text-break-normal` - Разрыв текста - нормальный
- `.text-break-word` - Текстовое слово-разрыв
- `.text-capitalize` - Текст с заглавной буквы
- `.text-center` - Текст по центру
- `.text-end` - Текст по концу строки
- `.text-justify` - Текст по ширине
- `.text-left` - Текст по левому краю
- `.text-line-none` - Текстовая строка-нет
- `.text-line-overline` - Текстовая строка-перечеркнутая
- `.text-line-through` - Сквозной текст
- `.text-line-underline` - Текстовая строка-подчеркивание
- `.text-lowercase` - Текст строчный
- `.text-overflow-clip` - Клип переполнения текста
- `.text-overflow-ellipsis` - Переполнение текста-многоточие
- `.text-right` - Текст по правому краю
- `.text-start` - Текст по началу строки
- `.text-transparent` - Текст прозрачный
- `.text-uppercase` - Текст в верхнем регистре

##### Text - Mobile (<= 480px)

- `.hover:mobile:text-center` - Текст по центру при наведении на мобильных
- `.hover:mobile:text-end` - Текст по концу строки при наведении на мобильных
- `.hover:mobile:text-justify` - Текст по ширине при наведении на мобильных
- `.hover:mobile:text-left` - Текст по левому краю при наведении на мобильных
- `.hover:mobile:text-right` - Текст по правому краю при наведении на мобильных
- `.hover:mobile:text-start` - Текст по началу строки при наведении на мобильных
- `.mobile:text-center` - Текст по центру на мобильных
- `.mobile:text-end` - Текст по концу строки на мобильных
- `.mobile:text-justify` - Текст по ширине на мобильных
- `.mobile:text-left` - Текст по левому краю на мобильных
- `.mobile:text-right` - Текст по правому краю на мобильных
- `.mobile:text-start` - Текст по началу строки на мобильных

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - Текст по центру при наведении на планшетах
- `.hover:tablet:text-end` - Текст по концу строки при наведении на планшетах
- `.hover:tablet:text-justify` - Текст по ширине при наведении на планшетах
- `.hover:tablet:text-left` - Текст по левому краю при наведении на планшетах
- `.hover:tablet:text-right` - Текст по правому краю при наведении на планшетах
- `.hover:tablet:text-start` - Текст по началу строки при наведении на планшетах
- `.tablet:text-center` - Текст по центру на планшетах
- `.tablet:text-end` - Текст по концу строки на планшетах
- `.tablet:text-justify` - Текст по ширине на планшетах
- `.tablet:text-left` - Текст по левому краю на планшетах
- `.tablet:text-right` - Текст по правому краю на планшетах
- `.tablet:text-start` - Текст по началу строки на планшетах

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - Текст по центру при наведении на планшетных ПК
- `.hover:tablet-pc:text-end` - Текст по концу строки при наведении на планшетных ПК
- `.hover:tablet-pc:text-justify` - Текст по ширине при наведении на планшетных ПК
- `.hover:tablet-pc:text-left` - Текст по левому краю при наведении на планшетных ПК
- `.hover:tablet-pc:text-right` - Текст по правому краю при наведении на планшетных ПК
- `.hover:tablet-pc:text-start` - Текст по началу строки при наведении на планшетных ПК
- `.tablet-pc:text-center` - Текст по центру на планшетных ПК
- `.tablet-pc:text-end` - Текст по концу строки на планшетных ПК
- `.tablet-pc:text-justify` - Текст по ширине на планшетных ПК
- `.tablet-pc:text-left` - Текст по левому краю на планшетных ПК
- `.tablet-pc:text-right` - Текст по правому краю на планшетных ПК
- `.tablet-pc:text-start` - Текст по началу строки на планшетных ПК

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - Текст по центру при наведении на ПК
- `.hover:pc:text-end` - Текст по концу строки при наведении на ПК
- `.hover:pc:text-justify` - Текст по ширине при наведении на ПК
- `.hover:pc:text-left` - Текст по левому краю при наведении на ПК
- `.hover:pc:text-right` - Текст по правому краю при наведении на ПК
- `.hover:pc:text-start` - Текст по началу строки при наведении на ПК
- `.pc:text-center` - Текст по центру на ПК
- `.pc:text-end` - Текст по концу строки на ПК
- `.pc:text-justify` - Текст по ширине на ПК
- `.pc:text-left` - Текст по левому краю на ПК
- `.pc:text-right` - Текст по правому краю на ПК
- `.pc:text-start` - Текст по началу строки на ПК

##### Text - Tv (>= 1200px)

- `.hover:tv:text-center` - Текст по центру при наведении на ТВ
- `.hover:tv:text-end` - Текст по концу строки при наведении на ТВ
- `.hover:tv:text-justify` - Текст по ширине при наведении на ТВ
- `.hover:tv:text-left` - Текст по левому краю при наведении на ТВ
- `.hover:tv:text-right` - Текст по правому краю при наведении на ТВ
- `.hover:tv:text-start` - Текст по началу строки при наведении на ТВ
- `.tv:text-center` - Текст по центру на ТВ
- `.tv:text-end` - Текст по концу строки на ТВ
- `.tv:text-justify` - Текст по ширине на ТВ
- `.tv:text-left` - Текст по левому краю на ТВ
- `.tv:text-right` - Текст по правому краю на ТВ
- `.tv:text-start` - Текст по началу строки на ТВ

##### Text - Tablet Max (<= 768px)

- `.hover:tablet-max:text-center` - Текст по центру при наведении на планшетах (макс.)
- `.hover:tablet-max:text-end` - Текст по концу строки при наведении на планшетах (макс.)
- `.hover:tablet-max:text-justify` - Текст по ширине при наведении на планшетах (макс.)
- `.hover:tablet-max:text-left` - Текст по левому краю при наведении на планшетах (макс.)
- `.hover:tablet-max:text-right` - Текст по правому краю при наведении на планшетах (макс.)
- `.hover:tablet-max:text-start` - Текст по началу строки при наведении на планшетах (макс.)
- `.tablet-max:text-center` - Текст по центру на планшетах (макс.)
- `.tablet-max:text-end` - Текст по концу строки на планшетах (макс.)
- `.tablet-max:text-justify` - Текст по ширине на планшетах (макс.)
- `.tablet-max:text-left` - Текст по левому краю на планшетах (макс.)
- `.tablet-max:text-right` - Текст по правому краю на планшетах (макс.)
- `.tablet-max:text-start` - Текст по началу строки на планшетах (макс.)

##### Text - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:text-center` - Текст по центру при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:text-end` - Текст по концу строки при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:text-justify` - Текст по ширине при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:text-left` - Текст по левому краю при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:text-right` - Текст по правому краю при наведении на планшетных ПК (макс.)
- `.hover:tablet-pc-max:text-start` - Текст по началу строки при наведении на планшетных ПК (макс.)
- `.tablet-pc-max:text-center` - Текст по центру на планшетных ПК (макс.)
- `.tablet-pc-max:text-end` - Текст по концу строки на планшетных ПК (макс.)
- `.tablet-pc-max:text-justify` - Текст по ширине на планшетных ПК (макс.)
- `.tablet-pc-max:text-left` - Текст по левому краю на планшетных ПК (макс.)
- `.tablet-pc-max:text-right` - Текст по правому краю на планшетных ПК (макс.)
- `.tablet-pc-max:text-start` - Текст по началу строки на планшетных ПК (макс.)

##### Text - Pc Max (<= 1200px)

- `.hover:pc-max:text-center` - Текст по центру при наведении на ПК (макс.)
- `.hover:pc-max:text-end` - Текст по концу строки при наведении на ПК (макс.)
- `.hover:pc-max:text-justify` - Текст по ширине при наведении на ПК (макс.)
- `.hover:pc-max:text-left` - Текст по левому краю при наведении на ПК (макс.)
- `.hover:pc-max:text-right` - Текст по правому краю при наведении на ПК (макс.)
- `.hover:pc-max:text-start` - Текст по началу строки при наведении на ПК (макс.)
- `.pc-max:text-center` - Текст по центру на ПК (макс.)
- `.pc-max:text-end` - Текст по концу строки на ПК (макс.)
- `.pc-max:text-justify` - Текст по ширине на ПК (макс.)
- `.pc-max:text-left` - Текст по левому краю на ПК (макс.)
- `.pc-max:text-right` - Текст по правому краю на ПК (макс.)
- `.pc-max:text-start` - Текст по началу строки на ПК (макс.)

### Whitespace

- `.hover:whitespace-normal` - Пробелы нормальные при наведении
- `.whitespace-normal` - Пробелы нормальные
- `.whitespace-nowrap` - Пробелы
- `.whitespace-pre` - Пробелы предварительно

### Whitespace break

- `.hover:whitespace-break-spaces` - Пробелы разрываются при наведении
- `.whitespace-break-spaces` - Пробелы разрывают пробелы

### Whitespace pre

- `.hover:whitespace-pre-line` - Пробелы перед строкой при наведении
- `.hover:whitespace-pre-wrap` - Предварительная упаковка пробелов при наведении
- `.whitespace-pre-line` - Пробелы в начале строки
- `.whitespace-pre-wrap` - Предварительная упаковка пробелов

### Writing h

- `.writing-h-tb` - Написание ч тб

### Writing v

- `.writing-v-lr` - Написание v lr
- `.writing-v-rl` - Написание vrl

## Backgrounds

### Background

- `.bg-transparent` - Фон прозрачный
- `.hover:bg-transparent` - Прозрачный фон при наведении

### Bg blur

- `.bg-blur-5` - Фоновое размытие 24px
- `.bg-blur-4` - Фоновое размытие 16px
- `.bg-blur-3` - Фоновое размытие 12px
- `.bg-blur-2` - Фоновое размытие 8px
- `.bg-blur-1` - Размытие фона 4px
- `.bg-blur-0` - Размытие фона 0px
- `.hover:bg-blur-5` - Размытие фона 24px при наведении
- `.hover:bg-blur-4` - Размытие фона 16px при наведении
- `.hover:bg-blur-3` - Размытие фона 12px при наведении
- `.hover:bg-blur-2` - Размытие фона 8px при наведении
- `.hover:bg-blur-1` - Размытие фона 4px при наведении
- `.hover:bg-blur-0` - Размытие фона 0px при наведении

## Borders

### Border

#### Border All

- `.border-2` - Граница Все 2rem
- `.border-1.5` - Граница Все 1.5rem
- `.border-1` - Граница Все 1rem
- `.border-0.9` - Граница Все 0.9rem
- `.border-0.8` - Граница Все 0.8rem
- `.border-0.7` - Граница Все 0.7rem
- `.border-0.6` - Граница Все 0.6rem
- `.border-0.5` - Граница Все 0.5rem
- `.border-0.4` - Граница Все 0,4rem
- `.border-0.3` - Граница Все 0.3rem
- `.border-0.2` - Граница Все 0,2rem
- `.border-0.1` - Граница Все 0,1rem
- `.border-0` - Граница Все 0rem
- `.hover:border-2` - Граница Все 2rem при наведении
- `.hover:border-1.5` - Граница Все 1.5rem при наведении
- `.hover:border-1` - Граница Все 1rem при наведении
- `.hover:border-0.9` - Граница Все 0.9rem при наведении
- `.hover:border-0.8` - Граница Все 0.8rem при наведении
- `.hover:border-0.7` - Граница Все 0.7rem при наведении
- `.hover:border-0.6` - Граница Все 0.6rem при наведении
- `.hover:border-0.5` - Граница Все 0.5rem при наведении
- `.hover:border-0.4` - Граница Все 0.4rem при наведении
- `.hover:border-0.3` - Граница Все 0.3rem при наведении
- `.hover:border-0.2` - Граница Все 0,2rem при наведении
- `.hover:border-0.1` - Граница Все 0,1rem при наведении
- `.hover:border-0` - Граница Все 0rem при наведении

#### Border Bottom

- `.border-b-2` - Граница снизу 2rem
- `.border-b-1.5` - Граница снизу 1.5rem
- `.border-b-1` - Граница снизу 1rem
- `.border-b-0.9` - Граница снизу 0.9rem
- `.border-b-0.8` - Граница снизу 0.8rem
- `.border-b-0.7` - Граница снизу 0.7rem
- `.border-b-0.6` - Граница снизу 0.6rem
- `.border-b-0.5` - Граница снизу 0,5rem
- `.border-b-0.4` - Граница снизу 0.4rem
- `.border-b-0.3` - Граница снизу 0.3rem
- `.border-b-0.2` - Граница снизу 0.2rem
- `.border-b-0.1` - Граница снизу 0.1rem
- `.border-b-0` - Граница снизу 0rem
- `.hover:border-b-2` - Граница снизу 2rem при наведении
- `.hover:border-b-1.5` - Граница снизу 1.5rem при наведении
- `.hover:border-b-1` - Граница снизу 1rem при наведении
- `.hover:border-b-0.9` - Граница снизу 0.9rem при наведении
- `.hover:border-b-0.8` - Граница снизу 0.8rem при наведении
- `.hover:border-b-0.7` - Граница снизу 0.7rem при наведении
- `.hover:border-b-0.6` - Граница снизу 0.6rem при наведении
- `.hover:border-b-0.5` - Граница снизу 0.5rem при наведении
- `.hover:border-b-0.4` - Граница снизу 0.4rem при наведении
- `.hover:border-b-0.3` - Граница снизу 0.3rem при наведении
- `.hover:border-b-0.2` - Граница снизу 0.2rem при наведении
- `.hover:border-b-0.1` - Граница снизу 0.1rem при наведении
- `.hover:border-b-0` - Граница снизу 0rem при наведении

#### Border Left

- `.border-l-2` - Граница слева 2rem
- `.border-l-1.5` - Граница слева 1.5rem
- `.border-l-1` - Граница слева 1rem
- `.border-l-0.9` - Граница слева 0.9rem
- `.border-l-0.8` - Граница слева 0.8rem
- `.border-l-0.7` - Граница слева 0.7rem
- `.border-l-0.6` - Граница слева 0.6rem
- `.border-l-0.5` - Граница слева 0.5rem
- `.border-l-0.4` - Граница слева 0.4rem
- `.border-l-0.3` - Граница слева 0.3rem
- `.border-l-0.2` - Граница слева 0,2rem
- `.border-l-0.1` - Граница слева 0,1rem
- `.border-l-0` - Граница слева 0rem
- `.hover:border-l-2` - Граница слева 2rem при наведении
- `.hover:border-l-1.5` - Граница слева 1.5rem при наведении
- `.hover:border-l-1` - Граница слева 1rem при наведении
- `.hover:border-l-0.9` - Граница слева 0.9rem при наведении
- `.hover:border-l-0.8` - Граница слева 0.8rem при наведении
- `.hover:border-l-0.7` - Граница слева 0.7rem при наведении
- `.hover:border-l-0.6` - Граница слева 0.6rem при наведении
- `.hover:border-l-0.5` - Граница слева 0.5rem при наведении
- `.hover:border-l-0.4` - Граница слева 0.4rem при наведении
- `.hover:border-l-0.3` - Граница слева 0.3rem при наведении
- `.hover:border-l-0.2` - Граница слева 0,2rem при наведении
- `.hover:border-l-0.1` - Граница слева 0,1rem при наведении
- `.hover:border-l-0` - Граница слева 0rem при наведении

#### Border Right

- `.border-r-2` - Граница правая 2rem
- `.border-r-1.5` - Граница справа 1.5rem
- `.border-r-1` - Граница справа 1rem
- `.border-r-0.9` - Граница справа 0.9rem
- `.border-r-0.8` - Граница справа 0.8rem
- `.border-r-0.7` - Граница справа 0.7rem
- `.border-r-0.6` - Граница справа 0.6rem
- `.border-r-0.5` - Граница справа 0.5rem
- `.border-r-0.4` - Граница справа 0.4rem
- `.border-r-0.3` - Граница справа 0.3rem
- `.border-r-0.2` - Граница справа 0,2rem
- `.border-r-0.1` - Граница справа 0.1rem
- `.border-r-0` - Граница справа 0rem
- `.hover:border-r-2` - Граница справа 2rem при наведении
- `.hover:border-r-1.5` - Граница справа 1.5rem при наведении
- `.hover:border-r-1` - Граница справа 1rem при наведении
- `.hover:border-r-0.9` - Граница справа 0.9rem при наведении
- `.hover:border-r-0.8` - Граница справа 0.8rem при наведении
- `.hover:border-r-0.7` - Граница справа 0.7rem при наведении
- `.hover:border-r-0.6` - Граница справа 0.6rem при наведении
- `.hover:border-r-0.5` - Граница справа 0.5rem при наведении
- `.hover:border-r-0.4` - Граница справа 0.4rem при наведении
- `.hover:border-r-0.3` - Граница справа 0.3rem при наведении
- `.hover:border-r-0.2` - Граница справа 0,2rem при наведении
- `.hover:border-r-0.1` - Граница справа 0,1rem при наведении
- `.hover:border-r-0` - Граница справа 0rem при наведении

#### Border Top

- `.border-t-2` - Граница Верх 2rem
- `.border-t-1.5` - Граница Верх 1.5rem
- `.border-t-1` - Граница Верх 1rem
- `.border-t-0.9` - Граница Верх 0.9rem
- `.border-t-0.8` - Граница Верх 0.8rem
- `.border-t-0.7` - Граница Верх 0.7rem
- `.border-t-0.6` - Граница Верх 0.6rem
- `.border-t-0.5` - Граница Верх 0.5rem
- `.border-t-0.4` - Граница Верх 0.4rem
- `.border-t-0.3` - Граница Верх 0.3rem
- `.border-t-0.2` - Граница Верх 0.2rem
- `.border-t-0.1` - Граница Верх 0,1rem
- `.border-t-0` - Граница Верх 0rem
- `.hover:border-t-2` - Граница Верх 2rem при наведении
- `.hover:border-t-1.5` - Граница Верх 1.5rem при наведении
- `.hover:border-t-1` - Граница Верх 1rem при наведении
- `.hover:border-t-0.9` - Граница Верх 0.9rem при наведении
- `.hover:border-t-0.8` - Граница Верх 0.8rem при наведении
- `.hover:border-t-0.7` - Граница Верх 0.7rem при наведении
- `.hover:border-t-0.6` - Граница Верх 0.6rem при наведении
- `.hover:border-t-0.5` - Граница Верх 0.5rem при наведении
- `.hover:border-t-0.4` - Граница Верх 0.4rem при наведении
- `.hover:border-t-0.3` - Граница Верх 0.3rem при наведении
- `.hover:border-t-0.2` - Граница Верх 0,2rem при наведении
- `.hover:border-t-0.1` - Граница Верх 0,1rem при наведении
- `.hover:border-t-0` - Граница Верх 0rem при наведении

#### Border X-Axis

- `.border-x-2` - Граница оси X 2rem
- `.border-x-1.5` - Граница оси X 1.5rem
- `.border-x-1` - Граница оси X 1rem
- `.border-x-0.9` - Граница оси X 0.9rem
- `.border-x-0.8` - Граница оси X 0.8rem
- `.border-x-0.7` - Граница оси X 0.7rem
- `.border-x-0.6` - Граница оси X 0.6rem
- `.border-x-0.5` - Граница оси X 0.5rem
- `.border-x-0.4` - Граница оси X 0.4rem
- `.border-x-0.3` - Граница оси X 0.3rem
- `.border-x-0.2` - Граница оси X 0,2rem
- `.border-x-0.1` - Граница оси X: 0,1rem
- `.border-x-0` - Граница оси X 0rem
- `.hover:border-x-2` - Граница X-Axis 2rem при наведении
- `.hover:border-x-1.5` - Граница оси X 1.5rem при наведении
- `.hover:border-x-1` - Граница X-Axis 1rem при наведении
- `.hover:border-x-0.9` - Граница оси X 0.9rem при наведении
- `.hover:border-x-0.8` - Граница оси X 0.8rem при наведении
- `.hover:border-x-0.7` - Граница оси X 0.7rem при наведении
- `.hover:border-x-0.6` - Граница оси X 0.6rem при наведении
- `.hover:border-x-0.5` - Граница оси X 0.5rem при наведении
- `.hover:border-x-0.4` - Граница оси X 0.4rem при наведении
- `.hover:border-x-0.3` - Граница оси X 0.3rem при наведении
- `.hover:border-x-0.2` - Граница оси X 0,2rem при наведении
- `.hover:border-x-0.1` - Граница оси X 0,1rem при наведении
- `.hover:border-x-0` - Граница оси X 0rem при наведении

#### Border Y-Axis

- `.border-y-2` - Граница оси Y 2rem
- `.border-y-1.5` - Граница оси Y 1.5rem
- `.border-y-1` - Граница оси Y 1rem
- `.border-y-0.9` - Граница оси Y 0.9rem
- `.border-y-0.8` - Граница оси Y 0.8rem
- `.border-y-0.7` - Граница оси Y 0.7rem
- `.border-y-0.6` - Граница оси Y 0.6rem
- `.border-y-0.5` - Граница оси Y 0,5rem
- `.border-y-0.4` - Граница оси Y 0.4rem
- `.border-y-0.3` - Граница оси Y 0.3rem
- `.border-y-0.2` - Граница оси Y 0,2rem
- `.border-y-0.1` - Граница оси Y: 0,1rem
- `.border-y-0` - Граница оси Y 0rem
- `.hover:border-y-2` - Граница оси Y 2rem при наведении
- `.hover:border-y-1.5` - Граница оси Y 1.5rem при наведении
- `.hover:border-y-1` - Граница оси Y 1rem при наведении
- `.hover:border-y-0.9` - Граница оси Y 0.9rem при наведении
- `.hover:border-y-0.8` - Граница оси Y 0.8rem при наведении
- `.hover:border-y-0.7` - Граница оси Y 0.7rem при наведении
- `.hover:border-y-0.6` - Граница оси Y 0.6rem при наведении
- `.hover:border-y-0.5` - Граница оси Y 0.5rem при наведении
- `.hover:border-y-0.4` - Граница оси Y 0.4rem при наведении
- `.hover:border-y-0.3` - Граница оси Y 0.3rem при наведении
- `.hover:border-y-0.2` - Граница оси Y 0,2rem при наведении
- `.hover:border-y-0.1` - Граница оси Y 0,1rem при наведении
- `.hover:border-y-0` - Граница оси Y 0rem при наведении

### Border Radius

#### Border Radius All

- `.hover:rounded-5` - Радиус границы Все 5rem при наведении
- `.hover:rounded-4.5` - Радиус границы Все 4.5rem при наведении
- `.hover:rounded-4` - Радиус границы Все 4rem при наведении
- `.hover:rounded-3.5` - Радиус границы Все 3.5rem при наведении
- `.hover:rounded-3` - Радиус границы Все 3rem при наведении
- `.hover:rounded-2.5` - Радиус границы Все 2.5rem при наведении
- `.hover:rounded-2` - Радиус границы Все 2rem при наведении
- `.hover:rounded-1.5` - Радиус границы Все 1.5rem при наведении
- `.hover:rounded-1` - Радиус границы Все 1rem при наведении
- `.hover:rounded-0.9` - Радиус границы Все 0.9rem при наведении
- `.hover:rounded-0.8` - Радиус границы Все 0.8rem при наведении
- `.hover:rounded-0.7` - Радиус границы Все 0.7rem при наведении
- `.hover:rounded-0.6` - Радиус границы Все 0.6rem при наведении
- `.hover:rounded-0.5` - Радиус границы Все 0.5rem при наведении
- `.hover:rounded-0.4` - Радиус границы Все 0.4rem при наведении
- `.hover:rounded-0.3` - Радиус границы Все 0.3rem при наведении
- `.hover:rounded-0.2` - Радиус границы Все 0,2rem при наведении
- `.hover:rounded-0.1` - Радиус границы Все 0.1rem при наведении
- `.hover:rounded-0` - Радиус границы Все 0rem при наведении
- `.rounded-5` - Радиус границы Все 5rem
- `.rounded-4.5` - Радиус границы Все 4.5rem
- `.rounded-4` - Радиус границы Все 4rem
- `.rounded-3.5` - Радиус границы Все 3.5rem
- `.rounded-3` - Радиус границы Все 3rem
- `.rounded-2.5` - Радиус границы Все 2.5rem
- `.rounded-2` - Радиус границы Все 2rem
- `.rounded-1.5` - Радиус границы Все 1.5rem
- `.rounded-1` - Радиус границы Все 1rem
- `.rounded-0.9` - Радиус границы Все 0.9rem
- `.rounded-0.8` - Радиус границы Все 0.8rem
- `.rounded-0.7` - Радиус границы Все 0.7rem
- `.rounded-0.6` - Радиус границы Все 0.6rem
- `.rounded-0.5` - Радиус границы Все 0.5rem
- `.rounded-0.4` - Радиус границы Все 0.4rem
- `.rounded-0.3` - Радиус границы Все 0.3rem
- `.rounded-0.2` - Радиус границы Все 0.2rem
- `.rounded-0.1` - Радиус границы Все 0.1rem
- `.rounded-0` - Радиус границы Все 0rem

#### Border Radius Bottom Left

- `.hover:rounded-bl-5` - Радиус границы снизу слева 5rem при наведении
- `.hover:rounded-bl-4.5` - Радиус границы снизу слева 4.5rem при наведении
- `.hover:rounded-bl-4` - Радиус границы снизу слева 4rem при наведении
- `.hover:rounded-bl-3.5` - Радиус границы снизу слева 3.5rem при наведении
- `.hover:rounded-bl-3` - Радиус границы снизу слева 3rem при наведении
- `.hover:rounded-bl-2.5` - Радиус границы снизу слева 2.5rem при наведении
- `.hover:rounded-bl-2` - Радиус границы снизу слева 2rem при наведении
- `.hover:rounded-bl-1.5` - Радиус границы снизу слева 1.5rem при наведении
- `.hover:rounded-bl-1` - Радиус границы снизу слева 1rem при наведении
- `.hover:rounded-bl-0.5` - Радиус границы снизу слева 0.5rem при наведении
- `.hover:rounded-bl-0` - Радиус границы снизу слева 0rem при наведении
- `.rounded-bl-5` - Радиус границы снизу слева 5rem
- `.rounded-bl-4.5` - Радиус границы снизу слева 4.5rem
- `.rounded-bl-4` - Радиус границы снизу слева 4rem
- `.rounded-bl-3.5` - Радиус границы снизу слева 3.5rem
- `.rounded-bl-3` - Радиус границы снизу слева 3rem
- `.rounded-bl-2.5` - Радиус границы снизу слева 2.5rem
- `.rounded-bl-2` - Радиус границы снизу слева 2rem
- `.rounded-bl-1.5` - Радиус границы снизу слева 1.5rem
- `.rounded-bl-1` - Радиус границы снизу слева 1rem
- `.rounded-bl-0.5` - Радиус границы снизу слева 0.5rem
- `.rounded-bl-0` - Радиус границы снизу слева 0rem

#### Border Radius Bottom Right

- `.hover:rounded-br-5` - Радиус границы снизу справа 5rem при наведении
- `.hover:rounded-br-4.5` - Радиус границы снизу справа 4.5rem при наведении
- `.hover:rounded-br-4` - Радиус границы снизу справа 4rem при наведении
- `.hover:rounded-br-3.5` - Радиус границы снизу справа 3.5rem при наведении
- `.hover:rounded-br-3` - Радиус границы снизу справа 3rem при наведении
- `.hover:rounded-br-2.5` - Радиус границы снизу справа 2.5rem при наведении
- `.hover:rounded-br-2` - Радиус границы снизу справа 2rem при наведении
- `.hover:rounded-br-1.5` - Радиус границы снизу справа 1.5rem при наведении
- `.hover:rounded-br-1` - Радиус границы снизу справа 1rem при наведении
- `.hover:rounded-br-0.5` - Радиус границы снизу справа 0.5rem при наведении
- `.hover:rounded-br-0` - Радиус границы снизу справа 0rem при наведении
- `.rounded-br-5` - Радиус границы снизу справа 5rem
- `.rounded-br-4.5` - Радиус границы снизу справа 4.5rem
- `.rounded-br-4` - Радиус границы снизу справа 4rem
- `.rounded-br-3.5` - Радиус границы снизу справа 3.5rem
- `.rounded-br-3` - Радиус границы снизу справа 3rem
- `.rounded-br-2.5` - Радиус границы снизу справа 2.5rem
- `.rounded-br-2` - Радиус границы снизу справа 2rem
- `.rounded-br-1.5` - Радиус границы снизу справа 1.5rem
- `.rounded-br-1` - Радиус границы снизу справа 1rem
- `.rounded-br-0.5` - Радиус границы снизу справа 0.5rem
- `.rounded-br-0` - Радиус границы снизу справа 0rem

#### Border Radius Top Left

- `.hover:rounded-tl-5` - Радиус границы вверху слева 5rem при наведении
- `.hover:rounded-tl-4.5` - Радиус границы вверху слева 4.5rem при наведении
- `.hover:rounded-tl-4` - Радиус границы вверху слева 4rem при наведении
- `.hover:rounded-tl-3.5` - Радиус границы вверху слева 3.5rem при наведении
- `.hover:rounded-tl-3` - Радиус границы вверху слева 3rem при наведении
- `.hover:rounded-tl-2.5` - Радиус границы вверху слева 2.5rem при наведении
- `.hover:rounded-tl-2` - Радиус границы вверху слева 2rem при наведении
- `.hover:rounded-tl-1.5` - Радиус границы вверху слева 1.5rem при наведении
- `.hover:rounded-tl-1` - Радиус границы вверху слева 1rem при наведении
- `.hover:rounded-tl-0.5` - Радиус границы вверху слева 0,5rem при наведении
- `.hover:rounded-tl-0` - Радиус границы вверху слева 0rem при наведении
- `.rounded-tl-5` - Радиус границы вверху слева 5rem
- `.rounded-tl-4.5` - Радиус границы вверху слева 4.5rem
- `.rounded-tl-4` - Граница Радиус сверху слева 4rem
- `.rounded-tl-3.5` - Радиус границы вверху слева 3.5rem
- `.rounded-tl-3` - Граница Радиус сверху слева 3rem
- `.rounded-tl-2.5` - Радиус границы вверху слева 2.5rem
- `.rounded-tl-2` - Радиус границы вверху слева 2rem
- `.rounded-tl-1.5` - Радиус границы вверху слева 1.5rem
- `.rounded-tl-1` - Радиус границы вверху слева 1rem
- `.rounded-tl-0.5` - Радиус границы вверху слева 0,5rem
- `.rounded-tl-0` - Радиус границы вверху слева 0rem

#### Border Radius Top Right

- `.hover:rounded-tr-5` - Радиус границы вверху справа 5rem при наведении
- `.hover:rounded-tr-4.5` - Радиус границы вверху справа 4.5rem при наведении
- `.hover:rounded-tr-4` - Радиус границы вверху справа 4rem при наведении
- `.hover:rounded-tr-3.5` - Радиус границы вверху справа 3.5rem при наведении
- `.hover:rounded-tr-3` - Радиус границы вверху справа 3rem при наведении
- `.hover:rounded-tr-2.5` - Радиус границы вверху справа 2.5rem при наведении
- `.hover:rounded-tr-2` - Радиус границы вверху справа 2rem при наведении
- `.hover:rounded-tr-1.5` - Радиус границы вверху справа 1.5rem при наведении
- `.hover:rounded-tr-1` - Радиус границы вверху справа 1rem при наведении
- `.hover:rounded-tr-0.5` - Радиус границы вверху справа 0,5rem при наведении
- `.hover:rounded-tr-0` - Радиус границы вверху справа 0rem при наведении
- `.rounded-tr-5` - Радиус границы вверху справа 5rem
- `.rounded-tr-4.5` - Радиус границы вверху справа 4.5rem
- `.rounded-tr-4` - Радиус границы вверху справа 4rem
- `.rounded-tr-3.5` - Радиус границы вверху справа 3.5rem
- `.rounded-tr-3` - Граница Радиус сверху справа 3rem
- `.rounded-tr-2.5` - Радиус границы вверху справа 2.5rem
- `.rounded-tr-2` - Радиус границы вверху справа 2rem
- `.rounded-tr-1.5` - Радиус границы вверху справа 1.5rem
- `.rounded-tr-1` - Радиус границы вверху справа 1rem
- `.rounded-tr-0.5` - Радиус границы вверху справа 0,5rem
- `.rounded-tr-0` - Радиус границы вверху справа 0rem

## Effects

### Box Shadow

#### Box Shadow All

- `.hover:shadow-5` - Box Shadow Все 5rem 0 1rem 2rem при наведении
- `.hover:shadow-5-1` - Box Shadow Все 0 0 5rem 2rem при наведении
- `.hover:shadow-4` - Box Shadow Все 4rem 0 1rem 2rem при наведении
- `.hover:shadow-4-1` - Box Shadow Все 0 0 4rem 2rem 0 1rem 2rem при наведении
- `.hover:shadow-3` - Box Shadow Все 3rem 0 1rem 2rem при наведении
- `.hover:shadow-3-1` - Box Shadow Все 0 0 3rem 2rem 0 1rem 2rem при наведении
- `.hover:shadow-2` - Box Shadow Все 2rem 0 1rem 2rem при наведении
- `.hover:shadow-2-1` - Box Shadow Все 0 0 2rem 2rem 0 1rem 2rem при наведении
- `.hover:shadow-1` - Box Shadow Все 1rem при наведении
- `.hover:shadow-1-1` - Box Shadow Все 0 0 1rem 2rem при наведении
- `.hover:shadow-none` - Box Shadow Все нет при наведении
- `.shadow-5` - Box Shadow Все 5rem 0 1rem 2rem
- `.shadow-5-1` - Box Shadow Все 0 0 5rem 2rem 0 1rem 2rem
- `.shadow-4` - Box Shadow Все 4rem 0 1rem 2rem
- `.shadow-4-1` - Box Shadow Все 0 0 4rem 2rem 0 1rem 2rem
- `.shadow-3` - Box Shadow Все 3rem 0 1rem 2rem
- `.shadow-3-1` - Box Shadow Все 0 0 3rem 2rem 0 1rem 2rem
- `.shadow-2` - Box Shadow Все 2rem 0 1rem 2rem
- `.shadow-2-1` - Box Shadow Все 0 0 2rem 2rem 0 1rem 2rem
- `.shadow-1` - Box Shadow Все 1rem 0 1rem 2rem
- `.shadow-1-1` - Box Shadow Все 0 0 1rem 2rem
- `.shadow-none` - Box Shadow Все нет

#### Box Shadow Bottom

- `.hover:shadow-b-10` - Тень блока снизу 10rem при наведении
- `.hover:shadow-b-9` - Тень блока снизу 9rem при наведении
- `.hover:shadow-b-8` - Тень блока снизу 8rem при наведении
- `.hover:shadow-b-7` - Тень блока снизу 7rem при наведении
- `.hover:shadow-b-6` - Тень блока снизу 6rem при наведении
- `.hover:shadow-b-5` - Тень блока снизу 5rem при наведении
- `.hover:shadow-b-4` - Тень блока снизу 4rem при наведении
- `.hover:shadow-b-3` - Тень блока снизу 3rem при наведении
- `.hover:shadow-b-2` - Тень блока снизу 2rem при наведении
- `.hover:shadow-b-1` - Тень блока снизу 1rem при наведении
- `.shadow-b-10` - Тень блока снизу 10rem
- `.shadow-b-9` - Тень блока снизу 9rem
- `.shadow-b-8` - Тень блока снизу 8rem
- `.shadow-b-7` - Тень блока снизу 7rem
- `.shadow-b-6` - Тень блока снизу 6rem
- `.shadow-b-5` - Тень блока снизу 5rem
- `.shadow-b-4` - Тень блока снизу 4rem
- `.shadow-b-3` - Тень блока снизу 3rem
- `.shadow-b-2` - Тень блока снизу 2rem
- `.shadow-b-1` - Тень блока снизу 1rem

#### Box Shadow Left

- `.hover:shadow-l-10` - Box Shadow Левый 10rem при наведении
- `.hover:shadow-l-9` - Box Shadow Левый 9rem при наведении
- `.hover:shadow-l-8` - Box Shadow Левый 8rem при наведении
- `.hover:shadow-l-7` - Box Shadow Левый 7rem при наведении
- `.hover:shadow-l-6` - Box Shadow Левый 6rem при наведении
- `.hover:shadow-l-5` - Box Shadow Левый 5rem при наведении
- `.hover:shadow-l-4` - Box Shadow Левый 4rem при наведении
- `.hover:shadow-l-3` - Box Shadow Левый 3rem при наведении
- `.hover:shadow-l-2` - Box Shadow Левый 2rem при наведении
- `.hover:shadow-l-1` - Box Shadow Левый 1rem при наведении
- `.shadow-l-10` - Box Shadow Левый 10rem
- `.shadow-l-9` - Box Shadow Левый 9rem
- `.shadow-l-8` - Box Shadow Левый 8rem
- `.shadow-l-7` - Box Shadow Левый 7rem
- `.shadow-l-6` - Box Shadow Левый 6rem
- `.shadow-l-5` - Box Shadow Левый 5rem
- `.shadow-l-4` - Box Shadow Левый 4rem
- `.shadow-l-3` - Box Shadow Левый 3rem
- `.shadow-l-2` - Box Shadow Левый 2rem
- `.shadow-l-1` - Box Shadow слева 1rem

#### Box Shadow Right

- `.hover:shadow-r-10` - Тень блока справа 10rem при наведении
- `.hover:shadow-r-9` - Тень блока справа 9rem при наведении
- `.hover:shadow-r-8` - Тень блока справа 8rem при наведении
- `.hover:shadow-r-7` - Тень блока справа 7rem при наведении
- `.hover:shadow-r-6` - Тень блока справа 6rem при наведении
- `.hover:shadow-r-5` - Тень блока справа 5rem при наведении
- `.hover:shadow-r-4` - Тень блока справа 4rem при наведении
- `.hover:shadow-r-3` - Тень блока справа 3rem при наведении
- `.hover:shadow-r-2` - Тень блока справа 2rem при наведении
- `.hover:shadow-r-1` - Тень блока справа 1rem при наведении
- `.shadow-r-10` - Тень блока справа 10rem
- `.shadow-r-9` - Тень блока справа 9rem
- `.shadow-r-8` - Тень блока справа 8rem
- `.shadow-r-7` - Тень блока справа 7rem
- `.shadow-r-6` - Тень блока справа 6rem
- `.shadow-r-5` - Тень блока справа 5rem
- `.shadow-r-4` - Тень блока справа 4rem
- `.shadow-r-3` - Тень блока справа 3rem
- `.shadow-r-2` - Тень блока справа 2rem
- `.shadow-r-1` - Тень блока справа 1rem

#### Box Shadow Top

- `.hover:shadow-t-10` - Тень блока сверху 10rem при наведении
- `.hover:shadow-t-9` - Тень блока сверху 9rem при наведении
- `.hover:shadow-t-8` - Тень блока сверху 8rem при наведении
- `.hover:shadow-t-7` - Тень блока сверху 7rem при наведении
- `.hover:shadow-t-6` - Тень блока сверху 6rem при наведении
- `.hover:shadow-t-5` - Тень блока сверху 5rem при наведении
- `.hover:shadow-t-4` - Тень блока сверху 4rem при наведении
- `.hover:shadow-t-3` - Тень блока сверху 3rem при наведении
- `.hover:shadow-t-2` - Тень блока сверху 2rem при наведении
- `.hover:shadow-t-1` - Тень блока сверху 1rem при наведении
- `.shadow-t-10` - Тень блока сверху 10rem
- `.shadow-t-9` - Тень блока сверху 9rem
- `.shadow-t-8` - Тень блока сверху 8rem
- `.shadow-t-7` - Тень блока сверху 7rem
- `.shadow-t-6` - Тень блока сверху 6rem
- `.shadow-t-5` - Тень блока сверху 5rem
- `.shadow-t-4` - Тень блока сверху 4rem
- `.shadow-t-3` - Тень блока сверху 3rem
- `.shadow-t-2` - Тень блока сверху 2rem
- `.shadow-t-1` - Тень блока сверху 1rem

#### Box Shadow X-Axis

- `.hover:shadow-x-10` - Box Shadow X-Axis 10rem при наведении
- `.hover:shadow-x-9` - Box Shadow X-Axis 9rem при наведении
- `.hover:shadow-x-8` - Box Shadow X-Axis 8rem при наведении
- `.hover:shadow-x-7` - Box Shadow X-Axis 7rem при наведении
- `.hover:shadow-x-6` - Box Shadow X-Axis 6rem при наведении
- `.hover:shadow-x-5` - Box Shadow X-Axis 5rem при наведении
- `.hover:shadow-x-4` - Box Shadow X-Axis 4rem при наведении
- `.hover:shadow-x-3` - Box Shadow X-Axis 3rem при наведении
- `.hover:shadow-x-2` - Box Shadow X-Axis 2rem при наведении
- `.hover:shadow-x-1` - Box Shadow X-Axis 1rem при наведении
- `.shadow-x-10` - Тень блока по оси X 10rem
- `.shadow-x-9` - Тень блока по оси X 9rem
- `.shadow-x-8` - Тень блока по оси X 8rem
- `.shadow-x-7` - Тень блока по оси X 7rem
- `.shadow-x-6` - Тень блока по оси X 6rem
- `.shadow-x-5` - Тень блока по оси X 5rem
- `.shadow-x-4` - Тень блока по оси X 4rem
- `.shadow-x-3` - Тень блока по оси X 3rem
- `.shadow-x-2` - Тень блока по оси X 2rem
- `.shadow-x-1` - Тень блока по оси X 1rem

#### Box Shadow Y-Axis

- `.hover:shadow-y-10` - Box Shadow Y-Axis 10rem при наведении
- `.hover:shadow-y-9` - Box Shadow Y-Axis 9rem при наведении
- `.hover:shadow-y-8` - Box Shadow Y-Axis 8rem при наведении
- `.hover:shadow-y-7` - Box Shadow Y-Axis 7rem при наведении
- `.hover:shadow-y-6` - Box Shadow Y-Axis 6rem при наведении
- `.hover:shadow-y-5` - Box Shadow Y-Axis 5rem при наведении
- `.hover:shadow-y-4` - Box Shadow Y-Axis 4rem при наведении
- `.hover:shadow-y-3` - Box Shadow Y-Axis 3rem при наведении
- `.hover:shadow-y-2` - Box Shadow Y-Axis 2rem при наведении
- `.hover:shadow-y-1` - Box Shadow Y-Axis 1rem при наведении
- `.shadow-y-10` - Box Shadow Y-ось 10rem
- `.shadow-y-9` - Box Shadow Y-Axis 9rem
- `.shadow-y-8` - Box Shadow Y-Axis 8rem
- `.shadow-y-7` - Box Shadow Y-Axis 7rem
- `.shadow-y-6` - Box Shadow Y-Axis 6rem
- `.shadow-y-5` - Box Shadow Y-Axis 5rem
- `.shadow-y-4` - Box Shadow Y-Axis 4rem
- `.shadow-y-3` - Box Shadow Y-Axis 3rem
- `.shadow-y-2` - Box Shadow Y-Axis 2rem
- `.shadow-y-1` - Box Shadow Y-ось 1rem

### Blur

- `.blur-5` - Размытие 24px
- `.blur-4` - Размытие 16px
- `.blur-3` - Размытие 12px
- `.blur-2` - Размытие 8px
- `.blur-1` - Размытие 4px
- `.blur-0` - Размытие 0px
- `.hover:blur-5` - Размытие 24px при наведении
- `.hover:blur-4` - Размытие 16px при наведении
- `.hover:blur-3` - Размытие 12px при наведении
- `.hover:blur-2` - Размытие 8px при наведении
- `.hover:blur-1` - Размытие 4px при наведении
- `.hover:blur-0` - Размытие 0px при наведении

### Opacity

- `.hover:opacity-100` - Непрозрачность 100% при наведении
- `.hover:opacity-95` - Непрозрачность 95% при наведении
- `.hover:opacity-90` - Непрозрачность 90% при наведении
- `.hover:opacity-85` - Непрозрачность 85% при наведении
- `.hover:opacity-80` - Непрозрачность 80% при наведении
- `.hover:opacity-75` - Непрозрачность 75% при наведении
- `.hover:opacity-70` - Непрозрачность 70% при наведении
- `.hover:opacity-65` - Непрозрачность 65% при наведении
- `.hover:opacity-60` - Непрозрачность 60% при наведении
- `.hover:opacity-55` - Непрозрачность 55% при наведении
- `.hover:opacity-50` - Непрозрачность 50% при наведении
- `.hover:opacity-45` - Непрозрачность 45% при наведении
- `.hover:opacity-40` - Непрозрачность 40% при наведении
- `.hover:opacity-35` - Непрозрачность 35% при наведении
- `.hover:opacity-30` - Непрозрачность 30% при наведении
- `.hover:opacity-25` - Непрозрачность 25% при наведении
- `.hover:opacity-20` - Непрозрачность 20% при наведении
- `.hover:opacity-15` - Непрозрачность 15% при наведении
- `.hover:opacity-10` - Непрозрачность 10% при наведении
- `.hover:opacity-5` - Непрозрачность 5% при наведении
- `.hover:opacity-0` - Непрозрачность 0% при наведении
- `.opacity-100` - Непрозрачность 100%
- `.opacity-95` - Непрозрачность 95%
- `.opacity-90` - Непрозрачность 90%
- `.opacity-85` - Непрозрачность 85%
- `.opacity-80` - Непрозрачность 80%
- `.opacity-75` - Непрозрачность 75%
- `.opacity-70` - Непрозрачность 70%
- `.opacity-65` - Непрозрачность 65%
- `.opacity-60` - Непрозрачность 60%
- `.opacity-55` - Непрозрачность 55%
- `.opacity-50` - Непрозрачность 50%
- `.opacity-45` - Непрозрачность 45%
- `.opacity-40` - Непрозрачность 40%
- `.opacity-35` - Непрозрачность 35%
- `.opacity-30` - Непрозрачность 30%
- `.opacity-25` - Непрозрачность 25%
- `.opacity-20` - Непрозрачность 20%
- `.opacity-15` - Непрозрачность 15%
- `.opacity-10` - Непрозрачность 10%
- `.opacity-5` - Непрозрачность 5%
- `.opacity-0` - Непрозрачность 0%

## Transforms

### Rotate

- `.hover:rotate-180` - Поворот на 180deg при наведении
- `.hover:rotate-135` - Поворот на 135deg при наведении
- `.hover:rotate-90` - Поворот на 90deg при наведении
- `.hover:rotate-45` - Поворот на 45deg при наведении
- `.hover:rotate-12` - Поворот на 12deg при наведении
- `.hover:rotate-9` - Поворот на 9deg при наведении
- `.hover:rotate-6` - Поворот на 6deg при наведении
- `.hover:rotate-3` - Поворот на 3deg при наведении
- `.hover:rotate-0` - Поворот 0deg при наведении
- `.rotate-180` - Поворот на 180deg
- `.rotate-135` - Поворот на 135deg
- `.rotate-90` - Поворот на 90deg
- `.rotate-45` - Поворот на 45deg
- `.rotate-12` - Поворот на 12deg
- `.rotate-9` - Поворот на 9deg
- `.rotate-6` - Поворот на 6deg
- `.rotate-3` - Поворот на 3deg
- `.rotate-0` - Поворот на 0deg

##### Negative Rotate

- `.-rotate-180` - Отрицательное вращение 180deg
- `.-rotate-135` - Отрицательное вращение 135deg
- `.-rotate-90` - Отрицательное вращение 90deg
- `.-rotate-45` - Отрицательное вращение 45deg
- `.-rotate-12` - Отрицательное вращение 12deg
- `.-rotate-9` - Отрицательное вращение 9deg
- `.-rotate-6` - Отрицательное вращение 6deg
- `.-rotate-3` - Отрицательное вращение 3deg
- `.hover:-rotate-180` - Отрицательное вращение на 180deg при наведении
- `.hover:-rotate-135` - Отрицательное вращение на 135deg при наведении
- `.hover:-rotate-90` - Отрицательное вращение на 90deg при наведении
- `.hover:-rotate-45` - Отрицательное вращение на 45deg при наведении
- `.hover:-rotate-12` - Отрицательное вращение на 12deg при наведении
- `.hover:-rotate-9` - Отрицательное вращение 9deg при наведении
- `.hover:-rotate-6` - Отрицательное вращение 6deg при наведении
- `.hover:-rotate-3` - Отрицательное вращение на 3deg при наведении

### Skew

#### Skew X-Axis

- `.hover:skew-x-12` - Наклон оси X на 12deg при наведении
- `.hover:skew-x-6` - Наклон оси X 6deg при наведении
- `.hover:skew-x-3` - Наклон оси X 3deg при наведении
- `.hover:skew-x-0` - Наклон оси X 0deg при наведении
- `.skew-x-12` - Наклон оси X 12deg
- `.skew-x-6` - Наклон оси X 6deg
- `.skew-x-3` - Наклон оси X 3deg
- `.skew-x-0` - Наклон оси X 0deg

##### Negative Skew X-Axis

- `.-skew-x-12` - Отрицательный перекос по оси X, 12deg
- `.-skew-x-6` - Отрицательный перекос по оси X 6deg
- `.-skew-x-3` - Отрицательный перекос по оси X 3deg
- `.hover:-skew-x-12` - Отрицательный наклон оси X 12deg при наведении
- `.hover:-skew-x-6` - Отрицательный наклон оси X 6deg при наведении
- `.hover:-skew-x-3` - Отрицательный наклон оси X 3deg при наведении

#### Skew Y-Axis

- `.hover:skew-y-12` - Наклон оси Y на 12deg при наведении
- `.hover:skew-y-6` - Наклон оси Y 6deg при наведении
- `.hover:skew-y-3` - Наклон оси Y 3deg при наведении
- `.hover:skew-y-0` - Наклон оси Y 0deg при наведении
- `.skew-y-12` - Наклон оси Y 12deg
- `.skew-y-6` - Наклон оси Y 6deg
- `.skew-y-3` - Наклон оси Y 3deg
- `.skew-y-0` - Наклон оси Y 0deg

##### Negative Skew Y-Axis

- `.-skew-y-12` - Отрицательный перекос оси Y 12deg
- `.-skew-y-6` - Отрицательный перекос оси Y 6deg
- `.-skew-y-3` - Отрицательный перекос оси Y 3deg
- `.hover:-skew-y-12` - Отрицательный наклон оси Y 12deg при наведении
- `.hover:-skew-y-6` - Отрицательный наклон оси Y 6deg при наведении
- `.hover:-skew-y-3` - Отрицательный наклон оси Y 3deg при наведении

### Translate

- `.hover:translate-50` - Перевести 50% при наведении
- `.hover:translate-25` - Перевести 25% при наведении
- `.translate-50` - Перевести 50%
- `.translate-25` - Перевести 25%

##### Negative Translate

- `.-translate-50` - Отрицательный перевод 50%
- `.-translate-25` - Отрицательный перевод 25%
- `.hover:-translate-50` - Отрицательный перевод 50% при наведении
- `.hover:-translate-25` - Отрицательный перевод 25% при наведении

#### Translate X-Axis

- `.hover:translate-x-50` - Перевести X-Axis 50% при наведении
- `.hover:translate-x-25` - Перевести X-Axis 25% при наведении
- `.hover:translate-x-2` - Перевести X-Axis 2rem при наведении
- `.hover:translate-x-1.5` - Перевести X-Axis 1.5rem при наведении
- `.hover:translate-x-1` - Перевести X-Axis 1rem при наведении
- `.hover:translate-x-0.5` - Перевести 0,5rem по оси X при наведении
- `.hover:translate-x-0` - Перевести X-Axis 0rem при наведении
- `.translate-x-50` - Перевести ось X 50%
- `.translate-x-25` - Перевести X-Axis 25%
- `.translate-x-2` - Перевести ось X 2rem
- `.translate-x-1.5` - Перевести ось X 1.5rem
- `.translate-x-1` - Перевести ось X 1rem
- `.translate-x-0.5` - Перевести ось X 0,5rem
- `.translate-x-0` - Перевести ось X 0rem

##### Negative Translate X-Axis

- `.-translate-x-50` - Отрицательное перемещение оси X 50%
- `.-translate-x-25` - Отрицательный перевод оси X 25%
- `.-translate-x-2` - Отрицательное перемещение оси X 2rem
- `.-translate-x-1.5` - Отрицательное перемещение оси X 1,5rem
- `.-translate-x-1` - Отрицательное перемещение оси X 1rem
- `.-translate-x-0.5` - Отрицательное перемещение оси X 0,5rem
- `.hover:-translate-x-50` - Отрицательный перевод оси X 50% при наведении
- `.hover:-translate-x-25` - Отрицательный перевод оси X 25% при наведении
- `.hover:-translate-x-2` - Отрицательный перевод оси X 2rem при наведении
- `.hover:-translate-x-1.5` - Отрицательное перемещение оси X 1,5rem при наведении
- `.hover:-translate-x-1` - Отрицательный перевод оси X 1rem при наведении
- `.hover:-translate-x-0.5` - Отрицательное перемещение оси X 0,5rem при наведении

#### Translate Y-Axis

- `.hover:translate-y-50` - Перевести ось Y на 50% при наведении
- `.hover:translate-y-25` - Перевести ось Y 25% при наведении
- `.hover:translate-y-2` - Перевести ось Y 2rem при наведении
- `.hover:translate-y-1.5` - Перевести ось Y 1.5rem при наведении
- `.hover:translate-y-1` - Перевести ось Y 1rem при наведении
- `.hover:translate-y-0.5` - Перевести ось Y на 0,5rem при наведении
- `.hover:translate-y-0` - Перевести ось Y 0rem при наведении
- `.translate-y-50` - Перевести ось Y 50%
- `.translate-y-25` - Перевести ось Y 25%
- `.translate-y-2` - Перевести ось Y 2rem
- `.translate-y-1.5` - Перевести ось Y 1.5rem
- `.translate-y-1` - Перевести ось Y 1rem
- `.translate-y-0.5` - Перевести ось Y 0,5rem
- `.translate-y-0` - Перевести ось Y 0rem

##### Negative Translate Y-Axis

- `.-translate-y-50` - Отрицательное перемещение оси Y 50%
- `.-translate-y-25` - Отрицательное перемещение оси Y 25%
- `.-translate-y-2` - Отрицательное перемещение оси Y 2rem
- `.-translate-y-1.5` - Отрицательное перемещение оси Y 1,5rem
- `.-translate-y-1` - Отрицательное перемещение оси Y 1rem
- `.-translate-y-0.5` - Отрицательное перемещение оси Y 0,5rem
- `.hover:-translate-y-50` - Отрицательное перемещение оси Y 50% при наведении
- `.hover:-translate-y-25` - Отрицательный перевод оси Y 25% при наведении
- `.hover:-translate-y-2` - Отрицательное перемещение оси Y 2rem при наведении
- `.hover:-translate-y-1.5` - Отрицательное перемещение оси Y 1,5rem при наведении
- `.hover:-translate-y-1` - Отрицательное перемещение оси Y на 1rem при наведении
- `.hover:-translate-y-0.5` - Отрицательное перемещение оси Y 0,5rem при наведении

### Zoom

- `.hover:zoom` - Увеличение при наведении
- `.hover:zoom-2` - Увеличение 2 при наведении
- `.hover:zoom-1.5` - Увеличение 1,5 при наведении
- `.zoom` - Увеличить
- `.zoom-2` - Зум 2
- `.zoom-1.5` - Увеличение 1,5

## Colors

### Black

- `.black` - Черный

### Dark

- `.dark` - Темный

### Light

- `.light` - Свет

### Transparent

- `.transparent` - Прозрачный

## Interactivity

### Cursor

- `.cursor-alias` - Псевдоним курсора
- `.cursor-all-scroll` - Полная прокрутка курсора
- `.cursor-auto` - Автоматический курсор
- `.cursor-cell` - Курсорная ячейка
- `.cursor-col-resize` - Изменение размера курсора
- `.cursor-context-menu` - Контекстное меню курсора
- `.cursor-copy` - Копия курсора
- `.cursor-crosshair` - Перекрестие курсора
- `.cursor-default` - Курсор
- `.cursor-e-resize` - Электронное изменение размера курсора
- `.cursor-ew-resize` - Изменение размера курсора
- `.cursor-grab` - Захват курсора
- `.cursor-grabbing` - Захват курсора
- `.cursor-help` - Помощь курсора
- `.cursor-move` - Перемещение курсора
- `.cursor-n-resize` - Изменение размера курсора
- `.cursor-ne-resize` - Изменение размера курсора
- `.cursor-nesw-resize` - Курсор nesw-resize
- `.cursor-no-drop` - Курсор без падения
- `.cursor-none` - Курсор нет
- `.cursor-not-allowed` - Курсор запрещен
- `.cursor-ns-resize` - Курсор ns-resize
- `.cursor-nw-resize` - Изменение размера курсора
- `.cursor-nwse-resize` - Курсор nwse-resize
- `.cursor-pointer` - Указатель курсора
- `.cursor-progress` - Прогресс курсора
- `.cursor-row-resize` - Изменение размера строки курсора
- `.cursor-s-resize` - Изменение размера курсора
- `.cursor-se-resize` - Изменение размера курсора
- `.cursor-sw-resize` - Изменение размера курсора
- `.cursor-text` - Текст курсора
- `.cursor-vertical-text` - Курсор вертикальный текст
- `.cursor-w-resize` - Курсор с изменением размера
- `.cursor-wait` - Курсор ждет
- `.cursor-zoom-in` - Увеличение курсора
- `.cursor-zoom-out` - Уменьшение курсора

### Disabled

- `.disabled` - Неполноценный

### Resize

- `.resize` - Изменить размер
- `.resize-none` - Изменение размера нет
- `.resize-x` - Изменить размер x
- `.resize-y` - Изменить размер y

### Select

- `.select-auto` - Выберите авто
- `.select-none` - Выбрать нет

## Misc

### Content

- `.content-3` - Контент 3
- `.content-3-bg` - Содержание 3-bg
- `.content-2` - Контент 2
- `.content-2-bg` - Содержание 2-bg
- `.content-2-text` - Контент 2-text
- `.content-1` - Контент 1
- `.content-1-bg` - Содержание 1-bg
- `.content-1-text` - Содержание 1-text
- `.hover:content-3-bg` - Содержимое 3-bg при наведении
- `.hover:content-2-bg` - Содержимое 2-bg при наведении
- `.hover:content-2-text` - Контент 2-text при наведении
- `.hover:content-1-bg` - Содержимое 1-bg при наведении
- `.hover:content-1-text` - Контент 1-text при наведении

### Dir

- `.dir-ltr` - Направление, буква
- `.dir-rtl` - Ты ртл

### Mse

- `.hover:mse-2` - Мсэ 2rem при наведении
- `.hover:mse-1.5` - Mse 1,5rem при наведении
- `.hover:mse-1` - Mse 1rem при наведении
- `.hover:mse-0.5` - Mse 0,5rem при наведении
- `.hover:mse-0` - Mse 0rem при наведении
- `.mse-2` - Мсэ 2rem
- `.mse-1.5` - Мсэ 1,5rem
- `.mse-1` - Мсэ 1rem
- `.mse-0.5` - Мсэ 0.5rem
- `.mse-0` - Мсе 0rem

### Visibility

- `.hover:v-hide` - Видимость скрыта при наведении
- `.hover:v-show` - Видимость видна при наведении
- `.v-hide` - Видимость скрыта
- `.v-show` - Видимость видимая

##### Visibility - Mobile (<= 480px)

- `.hover:mobile:v-hide` - Видимость скрыта при наведении на мобильном телефоне
- `.hover:mobile:v-show` - Видимость видна при наведении на мобильном телефоне
- `.mobile:v-hide` - Видимость скрыта на мобильном устройстве
- `.mobile:v-show` - Видимость видна на мобильных устройствах

##### Visibility - Tablet (480px - 768px)

- `.hover:tablet:v-hide` - Видимость скрыта при наведении на планшете
- `.hover:tablet:v-show` - Видимость видна при наведении на планшете
- `.tablet:v-hide` - Видимость скрыта на планшете
- `.tablet:v-show` - Видимость видна на планшете

##### Visibility - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:v-hide` - Видимость скрыта при наведении на планшетном ПК
- `.hover:tablet-pc:v-show` - Видимость видна при наведении курсора на планшетном ПК
- `.tablet-pc:v-hide` - Видимость скрыта на планшетном ПК
- `.tablet-pc:v-show` - Видимость видна на планшетном ПК

##### Visibility - Pc (992px - 1200px)

- `.hover:pc:v-hide` - Видимость скрыта при наведении на ПК
- `.hover:pc:v-show` - Видимость видна при наведении на ПК
- `.pc:v-hide` - Видимость скрыта на ПК
- `.pc:v-show` - Видимость видна на ПК

##### Visibility - Tv (>= 1200px)

- `.hover:tv:v-hide` - Видимость скрыта при наведении на телевизоре
- `.hover:tv:v-show` - Видимость видна при наведении на телевизор
- `.tv:v-hide` - Видимость скрыта по телевизору
- `.tv:v-show` - Видимость видна по телевизору

##### Visibility - Tablet Max (<= 768px)

- `.hover:tablet-max:v-hide` - Видимость скрыта при наведении на планшете Max
- `.hover:tablet-max:v-show` - Видимость видна при наведении на планшете макс.
- `.tablet-max:v-hide` - Видимость скрыта на планшете Max
- `.tablet-max:v-show` - Видимость видима на планшете макс.

##### Visibility - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:v-hide` - Видимость скрыта при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:v-show` - Видимость видима при наведении на планшетном ПК макс.
- `.tablet-pc-max:v-hide` - Видимость скрыта на планшетном ПК макс.
- `.tablet-pc-max:v-show` - Видимость видима на планшетном ПК макс.

##### Visibility - Pc Max (<= 1200px)

- `.hover:pc-max:v-hide` - Видимость скрыта при наведении на ПК макс.
- `.hover:pc-max:v-show` - Видимость видна при наведении на ПК макс.
- `.pc-max:v-hide` - Видимость скрыта на ПК макс.
- `.pc-max:v-show` - Видимость видима на ПК макс.

### Customization

bClass использует переменные CSS для оформления тем:

- `--plainBg` - Однотонный фоновый цвет
- `--contentBg` - Цвет фона контента
- `--contentBgPrimary` - Основной фон контента
- `--contentBgSecondary` - Фон вторичного контента
- `--contentTextPrimary` - Основной цвет текста
- `--contentTextSecondary` - Дополнительный цвет текста
- `--headerBg` - Цвет фона заголовка

### License

> Распространяется по лицензии Bik Public License 2.0. Дополнительную информацию см. в разделе [LICENSE](./../../../LICENSE).
