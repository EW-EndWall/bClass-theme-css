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

##### Display - Mobile (≤ 480px)

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

##### Display - Tv (≥ 1200px)

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

##### Display - Tablet Max (≤ 768px)

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

##### Display - Tablet Pc Max (≤ 992px)

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

##### Display - Pc Max (≤ 1200px)

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

- `.float-end` - Плавающий конец
- `.float-left` - Плавать влево
- `.float-none` - Плавающее: нет
- `.float-right` - Плавать вправо
- `.float-start` - Плавающий старт
- `.hover:float-end` - Плавающее завершение при наведении
- `.hover:float-left` - Плавать влево при наведении
- `.hover:float-none` - Не плавать при наведении
- `.hover:float-right` - Плавать прямо при наведении
- `.hover:float-start` - Плавающий запуск при наведении

##### Float - Mobile (≤ 480px)

- `.hover:mobile:float-end` - Плавающее завершение при наведении курсора на мобильном телефоне
- `.hover:mobile:float-left` - Поплавок влево при наведении на мобильном телефоне
- `.hover:mobile:float-none` - Не плавать при наведении курсора на мобильном телефоне
- `.hover:mobile:float-right` - Плавать прямо при наведении на мобильном телефоне
- `.hover:mobile:float-start` - Плавающий запуск при наведении на мобильном телефоне
- `.mobile:float-end` - Плавающий конец на мобильном устройстве
- `.mobile:float-left` - Плавать влево на мобильном телефоне
- `.mobile:float-none` - Не плавать на мобильных устройствах
- `.mobile:float-right` - Плавайте прямо на мобильном телефоне
- `.mobile:float-start` - Плавающий запуск на мобильном устройстве

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - Плавающий конец при наведении на планшет
- `.hover:tablet:float-left` - Поплавок влево при наведении на планшете
- `.hover:tablet:float-none` - Не плавать при наведении курсора на планшет
- `.hover:tablet:float-right` - Всплывать прямо при наведении на планшет
- `.hover:tablet:float-start` - Плавающий запуск при наведении на планшет
- `.tablet:float-end` - Плавающий конец на планшете
- `.tablet:float-left` - Переместить влево на планшете
- `.tablet:float-none` - Не плавать на планшете
- `.tablet:float-right` - Плавающее прямо на планшете
- `.tablet:float-start` - Плавающий запуск на планшете

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - Плавающий конец при наведении курсора на планшетный компьютер
- `.hover:tablet-pc:float-left` - Перемещение влево при наведении курсора на планшетном ПК
- `.hover:tablet-pc:float-none` - Не плавать при наведении курсора на планшетный компьютер
- `.hover:tablet-pc:float-right` - Плавайте прямо при наведении на планшетном ПК
- `.hover:tablet-pc:float-start` - Плавающий запуск при наведении на планшетный ПК
- `.tablet-pc:float-end` - Плавающий конец на планшетном ПК
- `.tablet-pc:float-left` - Переместить влево на планшетном ПК
- `.tablet-pc:float-none` - Не плавать ни на планшетном ПК
- `.tablet-pc:float-right` - Плавайте прямо на планшетном ПК
- `.tablet-pc:float-start` - Плавающий запуск на планшетном ПК

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - Плавающее завершение при наведении курсора на ПК
- `.hover:pc:float-left` - Поплавок влево при наведении на ПК
- `.hover:pc:float-none` - Не плавать при наведении курсора мыши на ПК
- `.hover:pc:float-right` - Плавать прямо при наведении на ПК
- `.hover:pc:float-start` - Плавающий запуск при наведении на ПК
- `.pc:float-end` - Плавающий конец на ПК
- `.pc:float-left` - Поплавок влево на ПК
- `.pc:float-none` - Не плавать ни на ПК
- `.pc:float-right` - Плавайте прямо на ПК
- `.pc:float-start` - Плавающий запуск на ПК

##### Float - Tv (≥ 1200px)

- `.hover:tv:float-end` - Плавающее завершение при наведении на телевизор
- `.hover:tv:float-left` - Плавать влево при наведении на телевизор
- `.hover:tv:float-none` - Не плавать при наведении курсора на телевизор
- `.hover:tv:float-right` - Плавайте прямо при наведении на телевизор
- `.hover:tv:float-start` - Плавающий запуск при наведении на телевизор
- `.tv:float-end` - Плавающий конец на телевизоре
- `.tv:float-left` - Поплавок влево по телевизору
- `.tv:float-none` - Не плавать по телевизору
- `.tv:float-right` - Плавайте прямо по телевизору
- `.tv:float-start` - Плавающий запуск на телевизоре

##### Float - Tablet Max (≤ 768px)

- `.hover:tablet-max:float-end` - Плавающий конец при наведении на планшет макс.
- `.hover:tablet-max:float-left` - Поплавок влево при наведении на планшете максимум
- `.hover:tablet-max:float-none` - Не плавать при наведении на планшет макс.
- `.hover:tablet-max:float-right` - Плавать вправо при наведении на планшете Max
- `.hover:tablet-max:float-start` - Плавающий запуск при наведении на планшете Max
- `.tablet-max:float-end` - Плавающий конец на планшете макс.
- `.tablet-max:float-left` - Плавать влево на планшете максимум
- `.tablet-max:float-none` - Не плавать на планшете Max
- `.tablet-max:float-right` - Плавающее право на планшете Max
- `.tablet-max:float-start` - Плавающий запуск на планшете Max

##### Float - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:float-end` - Плавающий конец при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:float-left` - Поплавок влево при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:float-none` - Не плавать при наведении курсора мыши на планшетном ПК макс.
- `.hover:tablet-pc-max:float-right` - Плавать вправо при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:float-start` - Плавающий запуск при наведении на планшетный ПК макс.
- `.tablet-pc-max:float-end` - Плавающий конец на планшетном ПК макс.
- `.tablet-pc-max:float-left` - Поплавок влево на планшетном ПК макс.
- `.tablet-pc-max:float-none` - Float none на планшетном ПК макс.
- `.tablet-pc-max:float-right` - Плавать прямо на планшетном ПК макс.
- `.tablet-pc-max:float-start` - Плавающий запуск на планшетном ПК макс.

##### Float - Pc Max (≤ 1200px)

- `.hover:pc-max:float-end` - Плавающий конец при наведении на ПК макс.
- `.hover:pc-max:float-left` - Поплавок влево при наведении на ПК макс.
- `.hover:pc-max:float-none` - Не плавать при наведении курсора мыши на ПК макс.
- `.hover:pc-max:float-right` - Всплывать вправо при наведении на ПК макс.
- `.hover:pc-max:float-start` - Плавающий запуск при наведении на ПК макс.
- `.pc-max:float-end` - Плавающий конец на ПК Макс.
- `.pc-max:float-left` - Поплавок влево на ПК Макс
- `.pc-max:float-none` - Float none на ПК Макс.
- `.pc-max:float-right` - Плавать прямо на ПК Макс
- `.pc-max:float-start` - Плавающий запуск на ПК макс.

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

##### Object - Mobile (≤ 480px)

- `.hover:mobile:object-contain` - Объект содержится при наведении на мобильный телефон
- `.hover:mobile:object-cover` - Закрытие объекта при наведении на мобильном телефоне
- `.hover:mobile:object-fill` - Заполнение объекта при наведении на мобильном телефоне
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
- `.hover:tablet:object-fill` - Заполнение объекта при наведении на планшет
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
- `.hover:tablet-pc:object-fill` - Заполнение объекта при наведении на планшетном ПК
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
- `.hover:pc:object-fill` - Заполнение объекта при наведении на ПК
- `.hover:pc:object-none` - Объект нет при наведении на ПК
- `.hover:pc:object-scale` - Масштабирование объекта при наведении на ПК
- `.pc:object-contain` - Объект содержится на ПК
- `.pc:object-cover` - Крышка объекта на ПК
- `.pc:object-fill` - Заливка объекта на ПК
- `.pc:object-none` - Объект отсутствует на ПК
- `.pc:object-scale` - Масштаб объекта на ПК

##### Object - Tv (≥ 1200px)

- `.hover:tv:object-contain` - Объект содержится при наведении на телевизор
- `.hover:tv:object-cover` - Закрытие объекта при наведении на телевизоре
- `.hover:tv:object-fill` - Заполнение объекта при наведении на телевизоре
- `.hover:tv:object-none` - Объект нет при наведении на телевизор
- `.hover:tv:object-scale` - Масштабирование объекта при наведении на телевизоре
- `.tv:object-contain` - Объект содержится на телевизоре
- `.tv:object-cover` - Обложка объекта на телевизоре
- `.tv:object-fill` - Заливка объектов на ТВ
- `.tv:object-none` - Объект нет по телевизору
- `.tv:object-scale` - Масштаб объекта на телевизоре

##### Object - Tablet Max (≤ 768px)

- `.hover:tablet-max:object-contain` - Объект содержится при наведении на планшет макс.
- `.hover:tablet-max:object-cover` - Закрытие объекта при наведении на планшет макс.
- `.hover:tablet-max:object-fill` - Заполнение объекта при наведении на планшете Max
- `.hover:tablet-max:object-none` - Объект нет при наведении на планшет Макс.
- `.hover:tablet-max:object-scale` - Масштабирование объекта при наведении на планшете Max
- `.tablet-max:object-contain` - Объект содержится на планшете Max
- `.tablet-max:object-cover` - Чехол для предметов на планшете max
- `.tablet-max:object-fill` - Заливка объекта на планшете Max
- `.tablet-max:object-none` - Объект отсутствует на планшете Max
- `.tablet-max:object-scale` - Масштаб объекта на планшете макс.

##### Object - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:object-contain` - Объект содержится при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:object-cover` - Покрытие объекта при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:object-fill` - Заполнение объекта при наведении на планшетном ПК Max
- `.hover:tablet-pc-max:object-none` - Объект нет при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:object-scale` - Масштабирование объекта при наведении на планшетном ПК макс.
- `.tablet-pc-max:object-contain` - Объект содержится на планшетном ПК макс.
- `.tablet-pc-max:object-cover` - Обложка объекта на планшетном ПК макс.
- `.tablet-pc-max:object-fill` - Заливка объекта на планшетном ПК Max
- `.tablet-pc-max:object-none` - Объект отсутствует на планшетном ПК Макс.
- `.tablet-pc-max:object-scale` - Масштаб объекта на планшетном ПК макс.

##### Object - Pc Max (≤ 1200px)

- `.hover:pc-max:object-contain` - Объект содержится при наведении на ПК макс.
- `.hover:pc-max:object-cover` - Закрытие объекта при наведении на ПК макс
- `.hover:pc-max:object-fill` - Заполнение объекта при наведении на ПК макс.
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

##### Flex - Mobile (≤ 480px)

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

##### Flex - Tv (≥ 1200px)

- `.hover:tv:flex-col` - Flex Col при наведении на телевизор
- `.hover:tv:flex-nowrap` - Flex nowrap при наведении на телевизор
- `.hover:tv:flex-row` - Гибкая строка при наведении на телевизоре
- `.hover:tv:flex-wrap` - Гибкая упаковка при наведении на телевизоре
- `.tv:flex-col` - Flex Col по телевизору
- `.tv:flex-nowrap` - Flex Nowrap по телевизору
- `.tv:flex-row` - Flex Row по телевизору
- `.tv:flex-wrap` - Гибкая пленка на телевизоре

##### Flex - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-col` - Flex Col при наведении на планшете Max
- `.hover:tablet-max:flex-nowrap` - Flex Nowrap при наведении на планшете Max
- `.hover:tablet-max:flex-row` - Гибкая строка при наведении на планшете Max
- `.hover:tablet-max:flex-wrap` - Гибкая обертка при наведении на планшете Max
- `.tablet-max:flex-col` - Flex Col на планшете Max
- `.tablet-max:flex-nowrap` - Flex Nowrap на планшете Max
- `.tablet-max:flex-row` - Flex row на планшете Max
- `.tablet-max:flex-wrap` - Гибкая пленка на планшете Max

##### Flex - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-col` - Flex Col при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-nowrap` - Flex Nowrap при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-row` - Гибкая строка при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-wrap` - Гибкая пленка при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-col` - Flex col на планшетном ПК макс.
- `.tablet-pc-max:flex-nowrap` - Flex Nowrap на планшетном ПК макс.
- `.tablet-pc-max:flex-row` - Flex row на планшетном ПК макс.
- `.tablet-pc-max:flex-wrap` - Гибкая пленка на планшетном ПК макс.

##### Flex - Pc Max (≤ 1200px)

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

##### Flex col - Mobile (≤ 480px)

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

##### Flex col - Tv (≥ 1200px)

- `.hover:tv:flex-col-reverse` - Flex Col переворачивается при наведении на телевизор
- `.tv:flex-col-reverse` - Flex Col Reverse на телевизоре

##### Flex col - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-col-reverse` - Flex Col Reverse при наведении на планшете Max
- `.tablet-max:flex-col-reverse` - Flex Col Reverse на планшете Max

##### Flex col - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - Flex Col Reverse при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-col-reverse` - Flex Col Reverse на планшетном ПК макс.

##### Flex col - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-col-reverse` - Flex Col Reverse при наведении на ПК макс.
- `.pc-max:flex-col-reverse` - Flex Col Reverse на ПК Макс.

### Flex row

- `.flex-row-reverse` - Гибкая строка в обратном направлении
- `.hover:flex-row-reverse` - Изменение направления строки при наведении

##### Flex row - Mobile (≤ 480px)

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

##### Flex row - Tv (≥ 1200px)

- `.hover:tv:flex-row-reverse` - Изменение положения строки при наведении на телевизор
- `.tv:flex-row-reverse` - Flex Row обратный по телевизору

##### Flex row - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-row-reverse` - Гибкая обратная строка при наведении на планшет макс.
- `.tablet-max:flex-row-reverse` - Реверс гибкой строки на планшете Max

##### Flex row - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - Реверс гибкой строки при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-row-reverse` - Flex Row Reverse на планшетном ПК макс.

##### Flex row - Pc Max (≤ 1200px)

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

##### Flex grow - Mobile (≤ 480px)

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

##### Flex grow - Tv (≥ 1200px)

- `.hover:tv:flex-grow-3` - Flex Grow 3 при наведении на телевизор
- `.hover:tv:flex-grow-2` - Flex Grow 2 при наведении на телевизор
- `.hover:tv:flex-grow-1` - Flex Grow 1 при наведении на телевизор
- `.hover:tv:flex-grow-0` - Flex Grow 0 при наведении на телевизор
- `.tv:flex-grow-3` - Flex Grow 3 по телевизору
- `.tv:flex-grow-2` - Flex Grow 2 по телевизору
- `.tv:flex-grow-1` - Flex Grow 1 по телевизору
- `.tv:flex-grow-0` - Flex Grow 0 по телевизору

##### Flex grow - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-grow-3` - Flex Grow 3 при наведении на планшет макс.
- `.hover:tablet-max:flex-grow-2` - Flex Grow 2 при наведении на планшет макс.
- `.hover:tablet-max:flex-grow-1` - Flex Grow 1 при наведении на планшет макс.
- `.hover:tablet-max:flex-grow-0` - Flex Grow 0 при наведении на планшет макс.
- `.tablet-max:flex-grow-3` - Flex Grow 3 на планшете Max
- `.tablet-max:flex-grow-2` - Flex Grow 2 на планшете Max
- `.tablet-max:flex-grow-1` - Flex Grow 1 на планшете макс.
- `.tablet-max:flex-grow-0` - Flex Grow 0 на планшете Max

##### Flex grow - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex Grow 3 при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-grow-2` - Flex Grow 2 при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-grow-1` - Flex Grow 1 при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:flex-grow-0` - Flex Grow 0 при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-grow-3` - Flex Grow 3 на планшетном ПК макс.
- `.tablet-pc-max:flex-grow-2` - Flex Grow 2 на планшетном ПК макс.
- `.tablet-pc-max:flex-grow-1` - Flex Grow 1 на планшетном ПК макс.
- `.tablet-pc-max:flex-grow-0` - Flex Grow 0 на планшетном ПК макс.

##### Flex grow - Pc Max (≤ 1200px)

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

##### Flex wrap - Mobile (≤ 480px)

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

##### Flex wrap - Tv (≥ 1200px)

- `.hover:tv:flex-wrap-reverse` - Реверс гибкой обмотки при наведении курсора на телевизоре
- `.tv:flex-wrap-reverse` - Гибкая пленка обратная на телевизоре

##### Flex wrap - Tablet Max (≤ 768px)

- `.hover:tablet-max:flex-wrap-reverse` - Реверс гибкой обертки при наведении на планшет макс.
- `.tablet-max:flex-wrap-reverse` - Обратная пленка Flex на планшете Max

##### Flex wrap - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - Гибкая пленка обратная при наведении на планшетный ПК макс.
- `.tablet-pc-max:flex-wrap-reverse` - Обратная пленка Flex на планшетном ПК Max

##### Flex wrap - Pc Max (≤ 1200px)

- `.hover:pc-max:flex-wrap-reverse` - Обратное переворачивание Flex при наведении на ПК макс.
- `.pc-max:flex-wrap-reverse` - Обратная пленка Flex на ПК Макс.

### Gap

#### Gap All

- `.gap-5` - Гэп Олл 5рем
- `.gap-4.5` - Гэп Все 0рем
- `.gap-4` - Гэп Олл 4рем
- `.gap-3.5` - Гэп Все 0рем
- `.gap-3` - Гэп Олл 3рем
- `.gap-2.5` - Гэп Все 0рем
- `.gap-2` - Гэп Олл 2рем
- `.gap-1.9` - Гэп Все 0рем
- `.gap-1.8` - Гэп Все 0рем
- `.gap-1.7` - Гэп Все 0рем
- `.gap-1.6` - Гэп Все 0рем
- `.gap-1.5` - Гэп Все 0рем
- `.gap-1.4` - Гэп Все 0рем
- `.gap-1.3` - Гэп Все 0рем
- `.gap-1.2` - Гэп Все 0рем
- `.gap-1.1` - Гэп Все 0рем
- `.gap-1` - Гэп Олл 1рем
- `.gap-0.9` - Гэп Все 0рем
- `.gap-0.8` - Гэп Все 0рем
- `.gap-0.7` - Гэп Все 0рем
- `.gap-0.6` - Гэп Все 0рем
- `.gap-0.5` - Гэп Все 0рем
- `.gap-0.4` - Гэп Все 0рем
- `.gap-0.3` - Гэп Все 0рем
- `.gap-0.2` - Разрыв всех 0,2рем
- `.gap-0.1` - Разрыв всех 0,1рем
- `.gap-0` - Гэп Все 0рем
- `.hover:gap-5` - Gap All 5rem при наведении
- `.hover:gap-4.5` - Gap All 0rem при наведении
- `.hover:gap-4` - Gap All 4rem при наведении
- `.hover:gap-3.5` - Gap All 0rem при наведении
- `.hover:gap-3` - Gap All 3rem при наведении
- `.hover:gap-2.5` - Gap All 0rem при наведении
- `.hover:gap-2` - Gap All 2rem при наведении
- `.hover:gap-1.9` - Gap All 0rem при наведении
- `.hover:gap-1.8` - Gap All 0rem при наведении
- `.hover:gap-1.7` - Gap All 0rem при наведении
- `.hover:gap-1.6` - Gap All 0rem при наведении
- `.hover:gap-1.5` - Gap All 0rem при наведении
- `.hover:gap-1.4` - Gap All 0rem при наведении
- `.hover:gap-1.3` - Gap All 0rem при наведении
- `.hover:gap-1.2` - Gap All 0rem при наведении
- `.hover:gap-1.1` - Gap All 0rem при наведении
- `.hover:gap-1` - Gap All 1rem при наведении
- `.hover:gap-0.9` - Gap All 0rem при наведении
- `.hover:gap-0.8` - Gap All 0rem при наведении
- `.hover:gap-0.7` - Gap All 0rem при наведении
- `.hover:gap-0.6` - Gap All 0rem при наведении
- `.hover:gap-0.5` - Gap All 0rem при наведении
- `.hover:gap-0.4` - Gap All 0rem при наведении
- `.hover:gap-0.3` - Gap All 0rem при наведении
- `.hover:gap-0.2` - Разрыв всех 0,2рем при наведении
- `.hover:gap-0.1` - Разрыв всех 0,1рем при наведении
- `.hover:gap-0` - Gap All 0rem при наведении

#### Gap X-Axis

- `.gap-x-5` - Зазор по оси X 5рем
- `.gap-x-4.5` - Зазор по оси X 0рем
- `.gap-x-4` - Зазор X-ось 4рем
- `.gap-x-3.5` - Зазор по оси X 0рем
- `.gap-x-3` - Зазор X-ось 3рем
- `.gap-x-2.5` - Зазор по оси X 0рем
- `.gap-x-2` - Зазор по оси X 2rem
- `.gap-x-1.9` - Зазор по оси X 0рем
- `.gap-x-1.8` - Зазор по оси X 0рем
- `.gap-x-1.7` - Зазор по оси X 0рем
- `.gap-x-1.6` - Зазор по оси X 0рем
- `.gap-x-1.5` - Зазор по оси X 0рем
- `.gap-x-1.4` - Зазор по оси X 0рем
- `.gap-x-1.3` - Зазор по оси X 0рем
- `.gap-x-1.2` - Зазор по оси X 0рем
- `.gap-x-1.1` - Зазор по оси X 0рем
- `.gap-x-1` - Зазор по оси X 1 рем.
- `.gap-x-0.9` - Зазор по оси X 0рем
- `.gap-x-0.8` - Зазор по оси X 0рем
- `.gap-x-0.7` - Зазор по оси X 0рем
- `.gap-x-0.6` - Зазор по оси X 0рем
- `.gap-x-0.5` - Зазор по оси X 0рем
- `.gap-x-0.4` - Зазор по оси X 0рем
- `.gap-x-0.3` - Зазор по оси X 0рем
- `.gap-x-0.2` - Зазор по оси X 0,2 рем.
- `.gap-x-0.1` - Зазор по оси X: 0,1 рем.
- `.gap-x-0` - Зазор по оси X 0рем
- `.hover:gap-x-5` - Зазор X-Axis 5rem при наведении
- `.hover:gap-x-4.5` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-4` - Зазор X-Axis 4rem при наведении
- `.hover:gap-x-3.5` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-3` - Зазор X-Axis 3rem при наведении
- `.hover:gap-x-2.5` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-2` - Зазор по оси X 2rem при наведении
- `.hover:gap-x-1.9` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.8` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.7` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.6` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.5` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.4` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.3` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.2` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1.1` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-1` - Зазор X-Axis 1rem при наведении
- `.hover:gap-x-0.9` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.8` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.7` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.6` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.5` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.4` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.3` - Зазор по оси X 0rem при наведении
- `.hover:gap-x-0.2` - Зазор по оси X 0,2 рем. при наведении
- `.hover:gap-x-0.1` - Зазор по оси X 0,1 рем при наведении
- `.hover:gap-x-0` - Зазор по оси X 0rem при наведении

#### Gap Y-Axis

- `.gap-y-5` - Зазор по оси Y 5рем
- `.gap-y-4.5` - Зазор по оси Y 0рем
- `.gap-y-4` - Зазор по оси Y 4rem
- `.gap-y-3.5` - Зазор по оси Y 0рем
- `.gap-y-3` - Зазор по оси Y 3rem
- `.gap-y-2.5` - Зазор по оси Y 0рем
- `.gap-y-2` - Зазор по оси Y 2rem
- `.gap-y-1.9` - Зазор по оси Y 0рем
- `.gap-y-1.8` - Зазор по оси Y 0рем
- `.gap-y-1.7` - Зазор по оси Y 0рем
- `.gap-y-1.6` - Зазор по оси Y 0рем
- `.gap-y-1.5` - Зазор по оси Y 0рем
- `.gap-y-1.4` - Зазор по оси Y 0рем
- `.gap-y-1.3` - Зазор по оси Y 0рем
- `.gap-y-1.2` - Зазор по оси Y 0рем
- `.gap-y-1.1` - Зазор по оси Y 0рем
- `.gap-y-1` - Зазор по оси Y 1рем
- `.gap-y-0.9` - Зазор по оси Y 0рем
- `.gap-y-0.8` - Зазор по оси Y 0рем
- `.gap-y-0.7` - Зазор по оси Y 0рем
- `.gap-y-0.6` - Зазор по оси Y 0рем
- `.gap-y-0.5` - Зазор по оси Y 0рем
- `.gap-y-0.4` - Зазор по оси Y 0рем
- `.gap-y-0.3` - Зазор по оси Y 0рем
- `.gap-y-0.2` - Зазор по оси Y: 0,2 рем.
- `.gap-y-0.1` - Зазор по оси Y: 0,1 рем.
- `.gap-y-0` - Зазор по оси Y 0рем
- `.hover:gap-y-5` - Зазор по оси Y 5rem при наведении
- `.hover:gap-y-4.5` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-4` - Зазор по оси Y 4rem при наведении
- `.hover:gap-y-3.5` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-3` - Зазор по оси Y 3rem при наведении
- `.hover:gap-y-2.5` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-2` - Зазор по оси Y 2rem при наведении
- `.hover:gap-y-1.9` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.8` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.7` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.6` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.5` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.4` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.3` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.2` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1.1` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-1` - Зазор по оси Y 1 рем при наведении
- `.hover:gap-y-0.9` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.8` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.7` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.6` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.5` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.4` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.3` - Зазор по оси Y 0rem при наведении
- `.hover:gap-y-0.2` - Зазор по оси Y 0,2 рем. при наведении
- `.hover:gap-y-0.1` - Зазор по оси Y 0,1 рем при наведении
- `.hover:gap-y-0` - Зазор по оси Y 0rem при наведении

### Align content

- `.align-content-around` - Выровняйте контент вокруг
- `.align-content-between` - Выровняйте контент между
- `.align-content-center` - Выровнять центр содержимого
- `.align-content-end` - Выровнять конец контента
- `.align-content-evenly` - Выравнивайте контент равномерно
- `.align-content-start` - Выровнять начало контента
- `.align-content-stretch` - Выровнять растяжение контента
- `.hover:align-content-around` - Выравнивание контента при наведении
- `.hover:align-content-between` - Выравнивание содержимого при наведении
- `.hover:align-content-center` - Выравнивание центра содержимого при наведении
- `.hover:align-content-end` - Выровнять конец контента при наведении
- `.hover:align-content-evenly` - Равномерно выравнивайте контент при наведении
- `.hover:align-content-start` - Выровнять начало контента при наведении
- `.hover:align-content-stretch` - Выравнивание растяжения контента при наведении

##### Align content - Mobile (≤ 480px)

- `.hover:mobile:align-content-around` - Выравнивание контента при наведении на мобильном устройстве
- `.hover:mobile:align-content-between` - Выравнивание контента при наведении на мобильном устройстве
- `.hover:mobile:align-content-center` - Выравнивание центра контента при наведении на мобильном устройстве
- `.hover:mobile:align-content-end` - Выровнять конец контента при наведении на мобильном устройстве
- `.hover:mobile:align-content-evenly` - Равномерно выравнивайте контент при наведении на мобильном устройстве
- `.hover:mobile:align-content-start` - Выровняйте начало контента при наведении на мобильном устройстве
- `.hover:mobile:align-content-stretch` - Выравнивание растяжения контента при наведении на мобильном устройстве
- `.mobile:align-content-around` - Выравнивайте контент на мобильных устройствах
- `.mobile:align-content-between` - Выровняйте контент между мобильными устройствами
- `.mobile:align-content-center` - Выравнивание контент-центра на мобильном устройстве
- `.mobile:align-content-end` - Выровнять конец контента на мобильном устройстве
- `.mobile:align-content-evenly` - Равномерно выравнивайте контент на мобильных устройствах
- `.mobile:align-content-start` - Выровняйте начало контента на мобильных устройствах
- `.mobile:align-content-stretch` - Выровняйте растяжение контента на мобильных устройствах

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - Выравнивание контента при наведении на планшете
- `.hover:tablet:align-content-between` - Выравнивание содержимого при наведении на планшет
- `.hover:tablet:align-content-center` - Выравнивание центра содержимого при наведении на планшет
- `.hover:tablet:align-content-end` - Выровнять конец контента при наведении на планшет
- `.hover:tablet:align-content-evenly` - Равномерно выравнивайте контент при наведении на планшет
- `.hover:tablet:align-content-start` - Выровнять начало контента при наведении на планшет
- `.hover:tablet:align-content-stretch` - Выравнивание растяжения контента при наведении на планшет
- `.tablet:align-content-around` - Выровняйте контент на планшете
- `.tablet:align-content-between` - Выравнивание содержимого на планшете
- `.tablet:align-content-center` - Выравнивание центра содержимого на планшете
- `.tablet:align-content-end` - Выровнять конец содержимого на планшете
- `.tablet:align-content-evenly` - Равномерно выравнивайте контент на планшете
- `.tablet:align-content-start` - Выровняйте начало контента на планшете
- `.tablet:align-content-stretch` - Выровняйте растяжение контента на планшете

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - Выравнивание контента при наведении курсора мыши на планшетном ПК
- `.hover:tablet-pc:align-content-between` - Выравнивание содержимого при наведении на планшетном ПК
- `.hover:tablet-pc:align-content-center` - Выравнивание центра содержимого при наведении курсора мыши на планшетном компьютере
- `.hover:tablet-pc:align-content-end` - Выровнять конец контента при наведении на планшетном ПК
- `.hover:tablet-pc:align-content-evenly` - Равномерно выравнивайте контент при наведении на планшетном ПК
- `.hover:tablet-pc:align-content-start` - Выровнять начало контента при наведении на планшетном ПК
- `.hover:tablet-pc:align-content-stretch` - Выравнивание растяжения контента при наведении на планшетном ПК
- `.tablet-pc:align-content-around` - Выровняйте контент на планшетном ПК
- `.tablet-pc:align-content-between` - Выравнивание содержимого между планшетным ПК
- `.tablet-pc:align-content-center` - Выравнивание центра содержимого на планшетном ПК
- `.tablet-pc:align-content-end` - Выровнять конец содержимого на планшетном ПК
- `.tablet-pc:align-content-evenly` - Равномерно выровняйте содержимое на планшетном ПК
- `.tablet-pc:align-content-start` - Выровняйте начало контента на планшетном ПК
- `.tablet-pc:align-content-stretch` - Выровняйте растяжение содержимого на планшетном ПК

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - Выравнивание контента при наведении на ПК
- `.hover:pc:align-content-between` - Выравнивание содержимого при наведении на ПК
- `.hover:pc:align-content-center` - Выравнивание центра содержимого при наведении на ПК
- `.hover:pc:align-content-end` - Выровнять конец контента при наведении на ПК
- `.hover:pc:align-content-evenly` - Равномерно выравнивайте контент при наведении на ПК
- `.hover:pc:align-content-start` - Выровнять начало контента при наведении на ПК
- `.hover:pc:align-content-stretch` - Выравнивание растяжения контента при наведении на ПК
- `.pc:align-content-around` - Выравнивание контента на ПК
- `.pc:align-content-between` - Выравнивание содержимого между ПК
- `.pc:align-content-center` - Выравнивание Библиотеки компонентов на ПК
- `.pc:align-content-end` - Выровнять конец содержимого на компьютере
- `.pc:align-content-evenly` - Равномерно выровняйте контент на ПК
- `.pc:align-content-start` - Выровнять начало контента на ПК
- `.pc:align-content-stretch` - Выровнять растяжение содержимого на ПК

##### Align content - Tv (≥ 1200px)

- `.hover:tv:align-content-around` - Выравнивание контента при наведении курсора на телевизоре
- `.hover:tv:align-content-between` - Выравнивание контента при наведении курсора на телевизоре
- `.hover:tv:align-content-center` - Выравнивание центра контента при наведении на телевизор
- `.hover:tv:align-content-end` - Выровнять конец контента при наведении курсора на телевизоре
- `.hover:tv:align-content-evenly` - Равномерно выравнивайте контент при наведении на телевизор
- `.hover:tv:align-content-start` - Выровнять начало контента при наведении на телевизор
- `.hover:tv:align-content-stretch` - Выровнять растяжение контента при наведении на телевизоре
- `.tv:align-content-around` - Выровняйте контент по телевизору
- `.tv:align-content-between` - Выровняйте контент по телевизору
- `.tv:align-content-center` - Выровняйте контент-центр на телевизоре
- `.tv:align-content-end` - Выровнять конец контента на телевизоре
- `.tv:align-content-evenly` - Равномерное выравнивание контента на телевизоре
- `.tv:align-content-start` - Выровнять начало контента на телевизоре
- `.tv:align-content-stretch` - Выровняйте растяжение контента на телевизоре

##### Align content - Tablet Max (≤ 768px)

- `.hover:tablet-max:align-content-around` - Выравнивание контента при наведении на планшете Max
- `.hover:tablet-max:align-content-between` - Выравнивание содержимого при наведении на планшете Max
- `.hover:tablet-max:align-content-center` - Выравнивание центра контента при наведении на планшете Max
- `.hover:tablet-max:align-content-end` - Выровнять конец контента при наведении на планшете Max
- `.hover:tablet-max:align-content-evenly` - Равномерное выравнивание контента при наведении на планшете Max
- `.hover:tablet-max:align-content-start` - Выровнять начало контента при наведении на планшете Max
- `.hover:tablet-max:align-content-stretch` - Выровнять растяжение контента при наведении на планшете Max
- `.tablet-max:align-content-around` - Выравнивание контента на планшете Max
- `.tablet-max:align-content-between` - Выравнивание содержимого на планшете Max
- `.tablet-max:align-content-center` - Выровнять центр содержимого на планшете Max
- `.tablet-max:align-content-end` - Выровнять конец содержимого на планшете максимум
- `.tablet-max:align-content-evenly` - Равномерно выровняйте контент на планшете Max.
- `.tablet-max:align-content-start` - Выровнять начало контента на планшете Max
- `.tablet-max:align-content-stretch` - Выровнять растяжение контента на планшете Max

##### Align content - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:align-content-around` - Выравнивание контента при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-content-between` - Выравнивание содержимого при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-content-center` - Выравнивание центра содержимого при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-content-end` - Выровнять конец контента при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-content-evenly` - Равномерное выравнивание контента при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:align-content-start` - Выровнять начало контента при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-content-stretch` - Выровнять растяжение содержимого при наведении на планшетном ПК макс.
- `.tablet-pc-max:align-content-around` - Выровняйте контент вокруг на планшетном ПК макс.
- `.tablet-pc-max:align-content-between` - Выравнивание содержимого на планшетном ПК макс.
- `.tablet-pc-max:align-content-center` - Выровнять центр содержимого на планшетном ПК макс.
- `.tablet-pc-max:align-content-end` - Выровнять конец содержимого на планшетном ПК макс.
- `.tablet-pc-max:align-content-evenly` - Равномерно выровняйте контент на планшетном ПК макс.
- `.tablet-pc-max:align-content-start` - Выровнять начало контента на планшетном ПК макс.
- `.tablet-pc-max:align-content-stretch` - Выровнять растяжение содержимого на планшетном ПК макс.

##### Align content - Pc Max (≤ 1200px)

- `.hover:pc-max:align-content-around` - Выравнивание контента при наведении на ПК Max
- `.hover:pc-max:align-content-between` - Выровнять контент при наведении на ПК макс.
- `.hover:pc-max:align-content-center` - Выравнивание центра контента при наведении на ПК макс.
- `.hover:pc-max:align-content-end` - Выровнять конец контента при наведении на ПК макс.
- `.hover:pc-max:align-content-evenly` - Равномерное выравнивание контента при наведении на ПК Макс.
- `.hover:pc-max:align-content-start` - Выровнять начало контента при наведении на ПК Max
- `.hover:pc-max:align-content-stretch` - Выровнять растяжение контента при наведении на ПК макс.
- `.pc-max:align-content-around` - Выровняйте контент вокруг на ПК Макс.
- `.pc-max:align-content-between` - Выровнять контент между ПК Макс.
- `.pc-max:align-content-center` - Выровнять центр содержимого на ПК Макс.
- `.pc-max:align-content-end` - Выровнять конец контента на ПК Макс.
- `.pc-max:align-content-evenly` - Выровняйте контент равномерно на ПК Макс.
- `.pc-max:align-content-start` - Выровнять начало контента на ПК Макс.
- `.pc-max:align-content-stretch` - Выровнять растяжение контента на ПК Макс.

### Align items

- `.align-items-center` - Выровнять элементы по центру
- `.align-items-end` - Выровнять элементы по концу
- `.align-items-start` - Выровнять элементы по началу
- `.align-items-stretch` - Выровнять элементы, растянуть
- `.hover:align-items-center` - Выравнивание элементов по центру при наведении
- `.hover:align-items-end` - Выровнять элементы по концу при наведении
- `.hover:align-items-start` - Выровнять элементы, начиная с наведения
- `.hover:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении

##### Align items - Mobile (≤ 480px)

- `.hover:mobile:align-items-center` - Выровнять элементы по центру при наведении на мобильном телефоне
- `.hover:mobile:align-items-end` - Выровнять элементы по концу при наведении на мобильном устройстве
- `.hover:mobile:align-items-start` - Выравнивание элементов, начинающихся при наведении курсора на мобильном телефоне
- `.hover:mobile:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на мобильном телефоне
- `.mobile:align-items-center` - Выровнять элементы по центру на мобильном телефоне
- `.mobile:align-items-end` - Выровнять элементы по концу на мобильном устройстве
- `.mobile:align-items-start` - Выровнять элементы по началу на мобильном устройстве
- `.mobile:align-items-stretch` - Выровнять элементы, растягивая их на мобильных устройствах

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - Выровнять элементы по центру при наведении на планшете
- `.hover:tablet:align-items-end` - Выровнять элементы по концу при наведении на планшете
- `.hover:tablet:align-items-start` - Выравнивание элементов, начинающихся при наведении курсора на планшете
- `.hover:tablet:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на планшет
- `.tablet:align-items-center` - Выровнять элементы по центру планшета
- `.tablet:align-items-end` - Выровнять элементы по краям планшета
- `.tablet:align-items-start` - Выровнять элементы по началу на планшете
- `.tablet:align-items-stretch` - Выровняйте элементы, растягивая их на планшете

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - Выровнять элементы по центру при наведении на планшетном ПК
- `.hover:tablet-pc:align-items-end` - Выровнять элементы по концу при наведении на планшетном ПК
- `.hover:tablet-pc:align-items-start` - Выравнивание элементов при наведении курсора на планшетный компьютер
- `.hover:tablet-pc:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на планшетный компьютер
- `.tablet-pc:align-items-center` - Выровнять элементы по центру планшетного ПК
- `.tablet-pc:align-items-end` - Выровнять элементы по краям на планшетном ПК
- `.tablet-pc:align-items-start` - Выровнять элементы по началу на планшетном ПК
- `.tablet-pc:align-items-stretch` - Выровняйте элементы, растягивая их на планшетном ПК

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - Выровнять элементы по центру при наведении на ПК
- `.hover:pc:align-items-end` - Выровнять элементы по концу при наведении на ПК
- `.hover:pc:align-items-start` - Выровнять элементы по началу при наведении на ПК
- `.hover:pc:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на ПК
- `.pc:align-items-center` - Выровнять элементы по центру на компьютере
- `.pc:align-items-end` - Выровнять элементы по краям на ПК
- `.pc:align-items-start` - Выровнять элементы по началу на ПК
- `.pc:align-items-stretch` - Выровнять элементы, растягивая их на ПК

##### Align items - Tv (≥ 1200px)

- `.hover:tv:align-items-center` - Выровнять элементы по центру при наведении курсора на телевизоре
- `.hover:tv:align-items-end` - Выровнять элементы по концу при наведении на телевизоре
- `.hover:tv:align-items-start` - Выровнять элементы, начинающиеся при наведении курсора на телевизоре
- `.hover:tv:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на телевизоре
- `.tv:align-items-center` - Выровнять элементы по центру телевизора
- `.tv:align-items-end` - Выровнять элементы по концам на телевизоре
- `.tv:align-items-start` - Выравнивание элементов начинается на телевизоре
- `.tv:align-items-stretch` - Выровнять элементы, растягивая их на телевизоре

##### Align items - Tablet Max (≤ 768px)

- `.hover:tablet-max:align-items-center` - Выровнять элементы по центру при наведении на планшете Max
- `.hover:tablet-max:align-items-end` - Выровнять элементы по концу при наведении на планшете максимум
- `.hover:tablet-max:align-items-start` - Выровнять начало элементов при наведении на планшете Max
- `.hover:tablet-max:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на планшете Max
- `.tablet-max:align-items-center` - Выровнять элементы по центру планшета макс.
- `.tablet-max:align-items-end` - Выровнять элементы по краям планшета максимум
- `.tablet-max:align-items-start` - Выровнять элементы по началу на планшете Max
- `.tablet-max:align-items-stretch` - Выровнять элементы, растягивая их на планшете Max

##### Align items - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:align-items-center` - Выровнять элементы по центру при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-items-end` - Выровнять элементы по концу при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:align-items-start` - Выровнять элементы по началу при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на планшетный ПК, макс.
- `.tablet-pc-max:align-items-center` - Выровнять элементы по центру на планшетном ПК макс.
- `.tablet-pc-max:align-items-end` - Выровнять элементы по краям на планшетном ПК макс.
- `.tablet-pc-max:align-items-start` - Выровнять элементы по началу на планшетном ПК макс.
- `.tablet-pc-max:align-items-stretch` - Выровнять элементы, растягивая их на планшетном ПК Max

##### Align items - Pc Max (≤ 1200px)

- `.hover:pc-max:align-items-center` - Выровнять элементы по центру при наведении на ПК макс.
- `.hover:pc-max:align-items-end` - Выровнять элементы по концу при наведении на ПК макс.
- `.hover:pc-max:align-items-start` - Выровнять элементы по началу при наведении на ПК макс.
- `.hover:pc-max:align-items-stretch` - Выравнивание элементов, растягивающихся при наведении на ПК макс.
- `.pc-max:align-items-center` - Выровнять элементы по центру на ПК Макс.
- `.pc-max:align-items-end` - Выровнять элементы по концу на ПК Макс.
- `.pc-max:align-items-start` - Выровнять элементы в начале на ПК Макс.
- `.pc-max:align-items-stretch` - Выровнять элементы, растягивая их на ПК Макс.

### Align self

- `.align-self-center` - Выровнять себя по центру
- `.align-self-end` - Выровнять конец
- `.align-self-start` - Выровнять самозапуск
- `.align-self-stretch` - Выровнять самостоятельное растяжение
- `.hover:align-self-center` - Выровнять центр при наведении
- `.hover:align-self-end` - Выровнять конец при наведении
- `.hover:align-self-start` - Выровнять автозапуск при наведении
- `.hover:align-self-stretch` - Выровнять саморастягивание при наведении

##### Align self - Mobile (≤ 480px)

- `.hover:mobile:align-self-center` - Выравнивание центра при наведении на мобильном телефоне
- `.hover:mobile:align-self-end` - Выровнять конец при наведении на мобильном устройстве
- `.hover:mobile:align-self-start` - Выровняйте автозапуск при наведении на мобильном устройстве
- `.hover:mobile:align-self-stretch` - Выровнять саморастягивание при наведении на мобильном устройстве
- `.mobile:align-self-center` - Выровнять центр на мобильном телефоне
- `.mobile:align-self-end` - Выровнять край на мобильном телефоне
- `.mobile:align-self-start` - Согласуйте самозапуск на мобильном устройстве
- `.mobile:align-self-stretch` - Выровняйте саморастягивание на мобильном устройстве

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - Выравнивание центра при наведении на планшет
- `.hover:tablet:align-self-end` - Выравнивание края при наведении на планшет
- `.hover:tablet:align-self-start` - Выровняйте автозапуск при наведении на планшет
- `.hover:tablet:align-self-stretch` - Выровнять саморастягивание при наведении на планшет
- `.tablet:align-self-center` - Выровнять центр планшета
- `.tablet:align-self-end` - Выровняйте край планшета
- `.tablet:align-self-start` - Выровняйте автозапуск на планшете
- `.tablet:align-self-stretch` - Выровняйте саморастягивание на планшете

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - Выравнивание центра при наведении на планшетном ПК
- `.hover:tablet-pc:align-self-end` - Выравнивание конца при наведении курсора на планшетный компьютер
- `.hover:tablet-pc:align-self-start` - Выровняйте самозапуск при наведении курсора на планшетный компьютер
- `.hover:tablet-pc:align-self-stretch` - Выровнять саморастягивание при наведении курсора на планшетный компьютер
- `.tablet-pc:align-self-center` - Выровняйте центр на планшетном ПК
- `.tablet-pc:align-self-end` - Выровняйте край на планшетном ПК
- `.tablet-pc:align-self-start` - Выровняйте автозапуск на планшетном ПК
- `.tablet-pc:align-self-stretch` - Выровняйте саморастягивание на планшетном компьютере

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - Выровнять центр при наведении на ПК
- `.hover:pc:align-self-end` - Выровнять конец при наведении на ПК
- `.hover:pc:align-self-start` - Выровнять автозапуск при наведении на ПК
- `.hover:pc:align-self-stretch` - Выровнять саморастягивание при наведении на ПК
- `.pc:align-self-center` - Выровнять центр на компьютере
- `.pc:align-self-end` - Выровняйте край на компьютере
- `.pc:align-self-start` - Выровняйте автозапуск на ПК
- `.pc:align-self-stretch` - Выровняйте саморастягивание на ПК

##### Align self - Tv (≥ 1200px)

- `.hover:tv:align-self-center` - Выровнять центр при наведении на телевизор
- `.hover:tv:align-self-end` - Выровнять конец при наведении на телевизор
- `.hover:tv:align-self-start` - Выровнять автозапуск при наведении курсора на телевизоре
- `.hover:tv:align-self-stretch` - Выровнять саморастягивание при наведении на телевизор
- `.tv:align-self-center` - Выровняйте центр на телевизоре
- `.tv:align-self-end` - Выровнять конец на телевизоре
- `.tv:align-self-start` - Настройте автозапуск на телевизоре
- `.tv:align-self-stretch` - Выровняйте саморастяжку на телевизоре

##### Align self - Tablet Max (≤ 768px)

- `.hover:tablet-max:align-self-center` - Выровнять центр при наведении на планшет максимум
- `.hover:tablet-max:align-self-end` - Выровнять край при наведении на планшет максимум
- `.hover:tablet-max:align-self-start` - Выровнять самозапуск при наведении на планшете Max
- `.hover:tablet-max:align-self-stretch` - Выровнять саморастягивание при наведении на планшете максимум
- `.tablet-max:align-self-center` - Выровнять центр на планшете макс.
- `.tablet-max:align-self-end` - Выровняйте край планшета по максимуму
- `.tablet-max:align-self-start` - Выровняйте автозапуск на планшете Max
- `.tablet-max:align-self-stretch` - Выровняйте саморастягивание на планшете Max

##### Align self - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:align-self-center` - Выровнять самоцентрирование при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:align-self-end` - Выровнять конец при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:align-self-start` - Выровнять самозапуск при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:align-self-stretch` - Выровнять саморастягивание при наведении на планшетный ПК макс.
- `.tablet-pc-max:align-self-center` - Выровнять центр на планшетном ПК макс.
- `.tablet-pc-max:align-self-end` - Выровняйте саморез на планшетном ПК макс.
- `.tablet-pc-max:align-self-start` - Выровняйте самозапуск на планшетном ПК макс.
- `.tablet-pc-max:align-self-stretch` - Выровняйте саморастягивание на планшетном ПК макс.

##### Align self - Pc Max (≤ 1200px)

- `.hover:pc-max:align-self-center` - Выровнять центр при наведении на ПК макс.
- `.hover:pc-max:align-self-end` - Выровнять конец при наведении на ПК макс.
- `.hover:pc-max:align-self-start` - Выровнять самозапуск при наведении на ПК макс.
- `.hover:pc-max:align-self-stretch` - Выровнять саморастягивание при наведении на ПК макс.
- `.pc-max:align-self-center` - Выровнять центр на ПК Макс.
- `.pc-max:align-self-end` - Выровнять саморез на ПК Макс.
- `.pc-max:align-self-start` - Выровнять автозапуск на ПК макс.
- `.pc-max:align-self-stretch` - Выровнять саморастягивание на ПК Макс.

### Justify content

- `.hover:justify-content-around` - Выравнивание контента при наведении
- `.hover:justify-content-between` - Выравнивание контента между при наведении
- `.hover:justify-content-center` - Выровнять контент-центр при наведении
- `.hover:justify-content-end` - Выровнять конец контента при наведении
- `.hover:justify-content-evenly` - Равномерно выравнивайте контент при наведении
- `.hover:justify-content-start` - Оправдать начало контента при наведении
- `.hover:justify-content-stretch` - Оправдать растяжение контента при наведении
- `.justify-content-around` - Обоснуйте содержание вокруг
- `.justify-content-between` - Обосновать содержание между
- `.justify-content-center` - Информационный центр Justify
- `.justify-content-end` - Обоснуйте конец контента
- `.justify-content-evenly` - Выравнивайте содержание равномерно
- `.justify-content-start` - Обоснуйте начало контента
- `.justify-content-stretch` - Оправдать растяжение контента

##### Justify content - Mobile (≤ 480px)

- `.hover:mobile:justify-content-around` - Выравнивание контента при наведении курсора на мобильном телефоне
- `.hover:mobile:justify-content-between` - Выравнивание контента между наведением на мобильном устройстве
- `.hover:mobile:justify-content-center` - Выровнять контент-центр при наведении на мобильном телефоне
- `.hover:mobile:justify-content-end` - Обоснуйте конец контента при наведении на мобильном телефоне
- `.hover:mobile:justify-content-start` - Обоснуйте начало контента при наведении на мобильном телефоне
- `.mobile:justify-content-around` - Обоснование контента на мобильных устройствах
- `.mobile:justify-content-between` - Обоснование контента между на мобильных устройствах
- `.mobile:justify-content-center` - Информационный центр Justify на мобильных устройствах
- `.mobile:justify-content-end` - Обоснуйте конец контента на мобильных устройствах
- `.mobile:justify-content-start` - Обоснование запуска контента на мобильных устройствах

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - Выравнивание контента при наведении на планшет
- `.hover:tablet:justify-content-between` - Выравнивание контента между наведением на планшете
- `.hover:tablet:justify-content-center` - Выравнивание информационного центра при наведении на планшет
- `.hover:tablet:justify-content-end` - Выравнивание окончания контента при наведении курсора на планшете
- `.hover:tablet:justify-content-start` - Оправдать начало контента при наведении на планшет
- `.tablet:justify-content-around` - Выравнивание контента на планшете
- `.tablet:justify-content-between` - Выравнивание контента между планшетами
- `.tablet:justify-content-center` - Информационный центр Justify на планшете
- `.tablet:justify-content-end` - Выровнять конец контента на планшете
- `.tablet:justify-content-start` - Обоснование начала контента на планшете

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - Выравнивание содержимого при наведении на планшетный компьютер
- `.hover:tablet-pc:justify-content-between` - Выравнивание содержимого между наведением на планшетном ПК
- `.hover:tablet-pc:justify-content-center` - Выравнивание информационного центра при наведении на планшетный компьютер
- `.hover:tablet-pc:justify-content-end` - Выравнивание окончания контента при наведении на планшетном ПК
- `.hover:tablet-pc:justify-content-start` - Оправдать запуск контента при наведении курсора на планшетный компьютер
- `.tablet-pc:justify-content-around` - Обоснование содержимого на планшетном ПК
- `.tablet-pc:justify-content-between` - Выравнивание содержимого между планшетным ПК
- `.tablet-pc:justify-content-center` - Информационный центр Justify на планшетном ПК
- `.tablet-pc:justify-content-end` - Выровнять конец контента на планшетном ПК
- `.tablet-pc:justify-content-start` - Обоснование начала контента на планшетном ПК

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - Выравнивание содержимого при наведении курсора мыши на ПК
- `.hover:pc:justify-content-between` - Выравнивание содержимого при наведении на ПК
- `.hover:pc:justify-content-center` - Выровнять центр содержимого при наведении на ПК
- `.hover:pc:justify-content-end` - Выравнивание окончания контента при наведении на ПК
- `.hover:pc:justify-content-start` - Оправдать начало контента при наведении на ПК
- `.pc:justify-content-around` - Обоснование контента на ПК
- `.pc:justify-content-between` - Обоснование контента между ПК
- `.pc:justify-content-center` - Информационный центр Justify на ПК
- `.pc:justify-content-end` - Обосновать конец контента на ПК
- `.pc:justify-content-start` - Обоснование начала контента на ПК

##### Justify content - Tv (≥ 1200px)

- `.hover:tv:justify-content-around` - Обоснование контента при наведении курсора на телевизор
- `.hover:tv:justify-content-between` - Обоснование контента между наведением на телевизоре
- `.hover:tv:justify-content-center` - Оправдать контент-центр при наведении на телевизор
- `.hover:tv:justify-content-end` - Оправдать завершение контента при наведении на телевизор
- `.hover:tv:justify-content-start` - Оправдать запуск контента при наведении на телевизор
- `.tv:justify-content-around` - Обоснование контента на телевидении
- `.tv:justify-content-between` - Обоснование контента между показами по телевизору
- `.tv:justify-content-center` - Контент-центр Justify на ТВ
- `.tv:justify-content-end` - Обосновать конец контента на телевидении
- `.tv:justify-content-start` - Обосновать запуск контента на телевидении

##### Justify content - Tablet Max (≤ 768px)

- `.hover:tablet-max:justify-content-around` - Выравнивание контента при наведении курсора мыши на планшете Max
- `.hover:tablet-max:justify-content-between` - Выравнивание контента между наведением на планшете Max
- `.hover:tablet-max:justify-content-center` - Выровнять контент-центр при наведении на планшете Max
- `.hover:tablet-max:justify-content-end` - Выровнять конец контента при наведении на планшете Max
- `.hover:tablet-max:justify-content-start` - Оправдать запуск контента при наведении на планшете Max
- `.tablet-max:justify-content-around` - Обоснование контента на планшете Max
- `.tablet-max:justify-content-between` - Обоснование контента между планшетами Max
- `.tablet-max:justify-content-center` - Информационный центр Justify на планшете Max
- `.tablet-max:justify-content-end` - Выровнять конец контента на планшете Max
- `.tablet-max:justify-content-start` - Обоснование начала контента на планшете Max

##### Justify content - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:justify-content-around` - Выравнивание контента при наведении на планшетный ПК Max
- `.hover:tablet-pc-max:justify-content-between` - Выравнивание контента при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:justify-content-center` - Оправдать центр контента при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:justify-content-end` - Выровнять конец контента при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:justify-content-start` - Оправдать запуск контента при наведении на планшетный ПК макс.
- `.tablet-pc-max:justify-content-around` - Обоснование контента на планшетном ПК макс.
- `.tablet-pc-max:justify-content-between` - Обоснование контента между планшетным ПК макс.
- `.tablet-pc-max:justify-content-center` - Информационный центр Justify на планшетном ПК макс.
- `.tablet-pc-max:justify-content-end` - Выровнять конец контента на планшетном ПК макс.
- `.tablet-pc-max:justify-content-start` - Обоснование начала контента на планшетном ПК макс.

##### Justify content - Pc Max (≤ 1200px)

- `.hover:pc-max:justify-content-around` - Выравнивание контента при наведении на ПК Max
- `.hover:pc-max:justify-content-between` - Выравнивание контента при наведении на ПК макс.
- `.hover:pc-max:justify-content-center` - Выровнять контент-центр при наведении на ПК Max
- `.hover:pc-max:justify-content-end` - Выровнять конец контента при наведении на ПК макс.
- `.hover:pc-max:justify-content-start` - Оправдать начало контента при наведении на ПК макс.
- `.pc-max:justify-content-around` - Обоснование контента на ПК Макс.
- `.pc-max:justify-content-between` - Обоснование контента между ПК Макс.
- `.pc-max:justify-content-center` - Информационный центр Justify на ПК Макс.
- `.pc-max:justify-content-end` - Обосновать конец контента на ПК макс.
- `.pc-max:justify-content-start` - Обосновать запуск контента на ПК макс.

### Justify items

- `.hover:justify-items-center` - Выравнивание элементов по центру при наведении
- `.hover:justify-items-end` - Выравнивание элементов заканчивается при наведении
- `.hover:justify-items-start` - Выравнивание элементов начинается при наведении
- `.hover:justify-items-stretch` - Выровнять элементы, растягивающиеся при наведении
- `.justify-items-center` - Выровнять элементы по центру
- `.justify-items-end` - Выровнять элементы в конце
- `.justify-items-start` - Выровнять начало элементов
- `.justify-items-stretch` - Выравнивание элементов растягивается

### Order

- `.hover:order-5` - Заказать 5 при наведении
- `.hover:order-4` - Заказ 4 при наведении
- `.hover:order-3` - Заказ 3 при наведении
- `.hover:order-2` - Заказ 2 при наведении
- `.hover:order-1` - Заказать 1 при наведении
- `.hover:order-0` - Заказ 0 при наведении
- `.hover:order-first` - Заказывайте первым при наведении
- `.hover:order-last` - Последний заказ при наведении
- `.order-5` - Заказать 5
- `.order-4` - Заказ 4
- `.order-3` - Заказ 3
- `.order-2` - Заказ 2
- `.order-1` - Заказ 1
- `.order-0` - Заказать 0
- `.order-first` - Закажи сначала
- `.order-last` - Заказывайте последним

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

##### Order - Mobile (≤ 480px)

- `.hover:mobile:order-5` - Закажите 5 при наведении на мобильном телефоне
- `.hover:mobile:order-4` - Заказать 4 при наведении на мобильном телефоне
- `.hover:mobile:order-3` - Заказать 3 при наведении на мобильном телефоне
- `.hover:mobile:order-2` - Заказать 2 при наведении на мобильном телефоне
- `.hover:mobile:order-1` - Заказать 1 при наведении на мобильном телефоне
- `.hover:mobile:order-0` - Заказ 0 при наведении на мобильном телефоне
- `.hover:mobile:order-first` - Закажите первым при наведении на мобильном телефоне
- `.hover:mobile:order-last` - Заказ последним при наведении на мобильном телефоне
- `.mobile:order-5` - Закажите 5 на мобильном телефоне
- `.mobile:order-4` - Заказать 4 на мобильном телефоне
- `.mobile:order-3` - Заказать 3 на мобильном телефоне
- `.mobile:order-2` - Заказать 2 на мобильном телефоне
- `.mobile:order-1` - Заказать 1 на мобильном телефоне
- `.mobile:order-0` - Заказать 0 на мобильном телефоне
- `.mobile:order-first` - Сначала закажите на мобильном телефоне
- `.mobile:order-last` - Последний заказ на мобильном телефоне

##### Negative Order - Mobile (≤ 480px)

- `.hover:mobile:-order-5` - Отрицательный порядок 5 при наведении на мобильном телефоне
- `.hover:mobile:-order-4` - Отрицательный порядок 4 при наведении на мобильном телефоне
- `.hover:mobile:-order-3` - Отрицательный порядок 3 при наведении на мобильном телефоне
- `.hover:mobile:-order-2` - Отрицательный заказ 2 при наведении на мобильном телефоне
- `.hover:mobile:-order-1` - Отрицательный заказ 1 при наведении на мобильном телефоне
- `.mobile:-order-5` - Отрицательный заказ 5 на мобильном телефоне
- `.mobile:-order-4` - Отрицательный заказ 4 на мобильном телефоне
- `.mobile:-order-3` - Отрицательный заказ 3 на мобильном телефоне
- `.mobile:-order-2` - Отрицательный заказ 2 на мобильном телефоне
- `.mobile:-order-1` - Отрицательный заказ 1 на мобильном телефоне

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - Заказать 5 при наведении на планшет
- `.hover:tablet:order-4` - Заказать 4 при наведении на планшет
- `.hover:tablet:order-3` - Заказать 3 при наведении на планшет
- `.hover:tablet:order-2` - Заказать 2 при наведении на планшет
- `.hover:tablet:order-1` - Заказать 1 при наведении на планшет
- `.hover:tablet:order-0` - Заказ 0 при наведении на планшет
- `.hover:tablet:order-first` - Закажите первым при наведении на планшет
- `.hover:tablet:order-last` - Заказать последним при наведении на планшет
- `.tablet:order-5` - Закажите 5 на планшете
- `.tablet:order-4` - Заказать 4 на планшете
- `.tablet:order-3` - Заказать 3 на планшете
- `.tablet:order-2` - Заказать 2 на планшете
- `.tablet:order-1` - Заказать 1 на планшете
- `.tablet:order-0` - Заказать 0 на планшете
- `.tablet:order-first` - Сначала закажите на планшете
- `.tablet:order-last` - Последний заказ на планшете

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - Отрицательный заказ 5 при наведении на планшет
- `.hover:tablet:-order-4` - Отрицательный заказ 4 при наведении на планшет
- `.hover:tablet:-order-3` - Отрицательный заказ 3 при наведении на планшет
- `.hover:tablet:-order-2` - Отрицательный заказ 2 при наведении на планшет
- `.hover:tablet:-order-1` - Отрицательный заказ 1 при наведении на планшет
- `.tablet:-order-5` - Отрицательный заказ 5 на планшете
- `.tablet:-order-4` - Отрицательный заказ 4 на планшете
- `.tablet:-order-3` - Отрицательный заказ 3 на планшете
- `.tablet:-order-2` - Отрицательный заказ 2 на планшете
- `.tablet:-order-1` - Отрицательный заказ 1 на планшете

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - Заказать 5 при наведении на планшетный ПК
- `.hover:tablet-pc:order-4` - Заказать 4 при наведении на планшетный ПК
- `.hover:tablet-pc:order-3` - Заказать 3 при наведении на планшетный компьютер
- `.hover:tablet-pc:order-2` - Заказать 2 при наведении на планшетный компьютер
- `.hover:tablet-pc:order-1` - Заказать 1 при наведении на планшетный компьютер
- `.hover:tablet-pc:order-0` - Заказ 0 при наведении на планшетный компьютер
- `.hover:tablet-pc:order-first` - Сначала закажите при наведении на планшетный компьютер
- `.hover:tablet-pc:order-last` - Заказ последним при наведении на планшетный компьютер
- `.tablet-pc:order-5` - Закажите 5 на планшетном ПК
- `.tablet-pc:order-4` - Закажите 4 на планшетном ПК
- `.tablet-pc:order-3` - Закажите 3 на планшетном ПК
- `.tablet-pc:order-2` - Закажите 2 на планшетном ПК
- `.tablet-pc:order-1` - Закажите 1 на планшетном ПК
- `.tablet-pc:order-0` - Заказ 0 на планшетном ПК
- `.tablet-pc:order-first` - Сначала закажите на планшетном ПК
- `.tablet-pc:order-last` - Последний заказ на планшетном ПК

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - Отрицательный заказ 5 при наведении на планшетный ПК
- `.hover:tablet-pc:-order-4` - Отрицательный заказ 4 при наведении на планшетный ПК
- `.hover:tablet-pc:-order-3` - Отрицательный заказ 3 при наведении на планшетный ПК
- `.hover:tablet-pc:-order-2` - Отрицательный заказ 2 при наведении на планшетный ПК
- `.hover:tablet-pc:-order-1` - Отрицательный заказ 1 при наведении на планшетный ПК
- `.tablet-pc:-order-5` - Отрицательный заказ 5 на планшетном ПК
- `.tablet-pc:-order-4` - Отрицательный заказ 4 на планшетном ПК
- `.tablet-pc:-order-3` - Отрицательный заказ 3 на планшетном ПК
- `.tablet-pc:-order-2` - Негативный заказ 2 на планшетном ПК
- `.tablet-pc:-order-1` - Отрицательный заказ 1 на планшетном ПК

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - Заказать 5 при наведении на ПК
- `.hover:pc:order-4` - Заказать 4 при наведении на ПК
- `.hover:pc:order-3` - Заказать 3 при наведении на ПК
- `.hover:pc:order-2` - Заказать 2 при наведении на ПК
- `.hover:pc:order-1` - Заказать 1 при наведении на ПК
- `.hover:pc:order-0` - Заказ 0 при наведении на ПК
- `.hover:pc:order-first` - Сначала закажите при наведении на ПК
- `.hover:pc:order-last` - Заказ последним при наведении на ПК
- `.pc:order-5` - Заказать 5 на ПК
- `.pc:order-4` - Заказать 4 на ПК
- `.pc:order-3` - Заказать 3 на ПК
- `.pc:order-2` - Заказать 2 на ПК
- `.pc:order-1` - Заказать 1 на ПК
- `.pc:order-0` - Заказ 0 на ПК
- `.pc:order-first` - Сначала закажите на ПК
- `.pc:order-last` - Последний заказ на ПК

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - Отрицательный порядок 5 при наведении на ПК
- `.hover:pc:-order-4` - Отрицательный порядок 4 при наведении на ПК
- `.hover:pc:-order-3` - Отрицательный заказ 3 при наведении на ПК
- `.hover:pc:-order-2` - Отрицательный заказ 2 при наведении на ПК
- `.hover:pc:-order-1` - Отрицательный заказ 1 при наведении на ПК
- `.pc:-order-5` - Отрицательный заказ 5 на ПК
- `.pc:-order-4` - Отрицательный заказ 4 на ПК
- `.pc:-order-3` - Отрицательный заказ 3 на ПК
- `.pc:-order-2` - Отрицательный заказ 2 на ПК
- `.pc:-order-1` - Отрицательный заказ 1 на ПК

##### Order - Tv (≥ 1200px)

- `.hover:tv:order-5` - Заказать 5 при наведении на телевизор
- `.hover:tv:order-4` - Заказать 4 при наведении на телевизор
- `.hover:tv:order-3` - Заказать 3 при наведении на телевизор
- `.hover:tv:order-2` - Заказать 2 при наведении на телевизор
- `.hover:tv:order-1` - Заказать 1 при наведении на телевизор
- `.hover:tv:order-0` - Заказать 0 при наведении на телевизор
- `.hover:tv:order-first` - Закажите первым при наведении курсора на телевизор
- `.hover:tv:order-last` - Последний заказ при наведении на телевизор
- `.tv:order-5` - Заказать 5 по телевизору
- `.tv:order-4` - Заказать 4 по телевизору
- `.tv:order-3` - Заказать 3 по телевизору
- `.tv:order-2` - Заказать 2 по телевизору
- `.tv:order-1` - Заказать 1 по телевизору
- `.tv:order-0` - Заказать 0 по телевизору
- `.tv:order-first` - Сначала закажи по телевизору
- `.tv:order-last` - Последний заказ по телевизору

##### Negative Order - Tv (≥ 1200px)

- `.hover:tv:-order-5` - Отрицательный порядок 5 при наведении на телевизор
- `.hover:tv:-order-4` - Отрицательный порядок 4 при наведении на телевизор
- `.hover:tv:-order-3` - Отрицательный заказ 3 при наведении на телевизор
- `.hover:tv:-order-2` - Отрицательный заказ 2 при наведении на телевизор
- `.hover:tv:-order-1` - Отрицательный порядок 1 при наведении на телевизор
- `.tv:-order-5` - Негативный заказ 5 по телевизору
- `.tv:-order-4` - Негативный заказ 4 на ТВ
- `.tv:-order-3` - Негативный заказ 3 на ТВ
- `.tv:-order-2` - Негативный заказ 2 на ТВ
- `.tv:-order-1` - Негативный заказ 1 по телевизору

##### Order - Tablet Max (≤ 768px)

- `.hover:tablet-max:order-5` - Заказать 5 при наведении на планшет макс.
- `.hover:tablet-max:order-4` - Заказать 4 при наведении на планшет макс.
- `.hover:tablet-max:order-3` - Заказать 3 при наведении на планшет макс.
- `.hover:tablet-max:order-2` - Заказ 2 при наведении на планшет макс.
- `.hover:tablet-max:order-1` - Заказать 1 при наведении на планшет макс.
- `.hover:tablet-max:order-0` - Заказ 0 при наведении на планшет макс.
- `.hover:tablet-max:order-first` - Закажите первым при наведении на планшете Max
- `.hover:tablet-max:order-last` - Заказ последним при наведении на планшете Max
- `.tablet-max:order-5` - Закажите 5 планшетов максимум
- `.tablet-max:order-4` - Заказ 4 на планшет макс.
- `.tablet-max:order-3` - Заказ 3 на планшет макс.
- `.tablet-max:order-2` - Заказ 2 на планшет макс.
- `.tablet-max:order-1` - Заказ 1 на планшет макс.
- `.tablet-max:order-0` - Заказ 0 на планшете макс.
- `.tablet-max:order-first` - Сначала закажите планшет Max
- `.tablet-max:order-last` - Последний заказ на планшете Max

##### Negative Order - Tablet Max (≤ 768px)

- `.hover:tablet-max:-order-5` - Отрицательный заказ 5 при наведении на планшет макс.
- `.hover:tablet-max:-order-4` - Отрицательный заказ 4 при наведении на планшет макс.
- `.hover:tablet-max:-order-3` - Отрицательный заказ 3 при наведении на планшет макс.
- `.hover:tablet-max:-order-2` - Отрицательный заказ 2 при наведении на планшет макс.
- `.hover:tablet-max:-order-1` - Отрицательный заказ 1 при наведении на планшет макс.
- `.tablet-max:-order-5` - Отрицательный заказ 5 на планшете макс.
- `.tablet-max:-order-4` - Отрицательный заказ 4 на планшете макс.
- `.tablet-max:-order-3` - Отрицательный заказ 3 на планшете макс.
- `.tablet-max:-order-2` - Отрицательный заказ 2 на планшете макс.
- `.tablet-max:-order-1` - Отрицательный заказ 1 на планшете макс.

##### Order - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:order-5` - Закажите 5 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:order-4` - Заказ 4 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:order-3` - Заказ 3 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:order-2` - Заказ 2 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:order-1` - Заказ 1 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:order-0` - Заказ 0 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:order-first` - Сначала закажите при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:order-last` - Последний заказ при наведении на планшетном ПК макс.
- `.tablet-pc-max:order-5` - Закажите максимум 5 штук на планшетном ПК
- `.tablet-pc-max:order-4` - Закажите 4 максимум на планшетном ПК
- `.tablet-pc-max:order-3` - Закажите 3 максимум на планшетном ПК
- `.tablet-pc-max:order-2` - Закажите 2 максимум на планшетном ПК
- `.tablet-pc-max:order-1` - Заказ 1 на планшетном ПК максимум
- `.tablet-pc-max:order-0` - Заказ 0 на планшетном ПК максимум
- `.tablet-pc-max:order-first` - Сначала закажите на планшетном ПК макс.
- `.tablet-pc-max:order-last` - Последний заказ на планшетном ПК макс.

##### Negative Order - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:-order-5` - Отрицательный заказ 5 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:-order-4` - Отрицательный заказ 4 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:-order-3` - Отрицательный заказ 3 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:-order-2` - Отрицательный заказ 2 при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:-order-1` - Отрицательный заказ 1 при наведении на планшетный ПК максимум
- `.tablet-pc-max:-order-5` - Отрицательный заказ 5 на планшетном ПК максимум
- `.tablet-pc-max:-order-4` - Отрицательный заказ 4 на планшетном ПК макс.
- `.tablet-pc-max:-order-3` - Отрицательный заказ 3 на планшетном ПК макс.
- `.tablet-pc-max:-order-2` - Отрицательный заказ 2 на планшетном ПК макс.
- `.tablet-pc-max:-order-1` - Отрицательный заказ 1 на планшетном ПК максимум

##### Order - Pc Max (≤ 1200px)

- `.hover:pc-max:order-5` - Заказать 5 при наведении на ПК максимум
- `.hover:pc-max:order-4` - Заказ 4 при наведении на ПК максимум
- `.hover:pc-max:order-3` - Заказ 3 при наведении на ПК максимум
- `.hover:pc-max:order-2` - Заказ 2 при наведении на ПК максимум
- `.hover:pc-max:order-1` - Заказ 1 при наведении на ПК максимум
- `.hover:pc-max:order-0` - Заказ 0 при наведении на ПК макс.
- `.hover:pc-max:order-first` - Заказывайте первым при наведении на ПК макс.
- `.hover:pc-max:order-last` - Последний заказ при наведении на ПК макс.
- `.pc-max:order-5` - Закажите 5 штук максимум на ПК
- `.pc-max:order-4` - Заказать 4 максимум на ПК
- `.pc-max:order-3` - Заказать 3 на ПК максимум
- `.pc-max:order-2` - Заказать 2 максимум на ПК
- `.pc-max:order-1` - Заказ 1 на ПК максимум
- `.pc-max:order-0` - Заказ 0 на ПК максимум
- `.pc-max:order-first` - Сначала закажите на ПК Макс.
- `.pc-max:order-last` - Последний заказ на ПК Макс.

##### Negative Order - Pc Max (≤ 1200px)

- `.hover:pc-max:-order-5` - Отрицательный порядок 5 при наведении на ПК макс.
- `.hover:pc-max:-order-4` - Отрицательный порядок 4 при наведении на ПК макс.
- `.hover:pc-max:-order-3` - Отрицательный порядок 3 при наведении на ПК макс.
- `.hover:pc-max:-order-2` - Отрицательный заказ 2 при наведении на ПК макс.
- `.hover:pc-max:-order-1` - Отрицательный заказ 1 при наведении на ПК макс.
- `.pc-max:-order-5` - Отрицательный заказ 5 на ПК максимум
- `.pc-max:-order-4` - Отрицательный заказ 4 на ПК макс.
- `.pc-max:-order-3` - Отрицательный заказ 3 на ПК макс.
- `.pc-max:-order-2` - Отрицательный заказ 2 на ПК макс.
- `.pc-max:-order-1` - Отрицательный заказ 1 на ПК максимум

## Spacing

### Margin

#### Margin All

- `.first:m-0` - Маржа Все 0рем в первую очередь
- `.hover:m-5` - Маржа Все 5рем при наведении
- `.hover:m-4.5` - Маржа Все 0рем при наведении
- `.hover:m-4` - Маржа Все 4rem при наведении
- `.hover:m-3.5` - Маржа Все 0рем при наведении
- `.hover:m-3` - Маржа Все 3rem при наведении
- `.hover:m-2.5` - Маржа Все 0рем при наведении
- `.hover:m-2` - Маржа Все 2rem при наведении
- `.hover:m-1.9` - Маржа Все 0рем при наведении
- `.hover:m-1.8` - Маржа Все 0рем при наведении
- `.hover:m-1.7` - Маржа Все 0рем при наведении
- `.hover:m-1.6` - Маржа Все 0рем при наведении
- `.hover:m-1.5` - Маржа Все 0рем при наведении
- `.hover:m-1.4` - Маржа Все 0рем при наведении
- `.hover:m-1.3` - Маржа Все 0рем при наведении
- `.hover:m-1.2` - Маржа Все 0рем при наведении
- `.hover:m-1.1` - Маржа Все 0рем при наведении
- `.hover:m-1` - Маржа Все 1рем при наведении
- `.hover:m-0.9` - Маржа Все 0рем при наведении
- `.hover:m-0.8` - Маржа Все 0рем при наведении
- `.hover:m-0.7` - Маржа Все 0рем при наведении
- `.hover:m-0.6` - Маржа Все 0рем при наведении
- `.hover:m-0.5` - Маржа Все 0рем при наведении
- `.hover:m-0.4` - Маржа Все 0рем при наведении
- `.hover:m-0.3` - Маржа Все 0рем при наведении
- `.hover:m-0.2` - Маржа Все 0,2рем при наведении
- `.hover:m-0.1` - Маржа Все 0,1рем при наведении
- `.hover:m-0` - Маржа Все 0рем при наведении
- `.hover:m-auto` - Маржа Все автоматически при наведении
- `.last:m-0` - Маржа Все 0рем на последнем
- `.m-5` - Маржа Все 5рем
- `.m-4.5` - Маржа Все 0рем
- `.m-4` - Маржа Все 4рем
- `.m-3.5` - Маржа Все 0рем
- `.m-3` - Маржа Все 3рем
- `.m-2.5` - Маржа Все 0рем
- `.m-2` - Маржа Все 2рем
- `.m-1.9` - Маржа Все 0рем
- `.m-1.8` - Маржа Все 0рем
- `.m-1.7` - Маржа Все 0рем
- `.m-1.6` - Маржа Все 0рем
- `.m-1.5` - Маржа Все 0рем
- `.m-1.4` - Маржа Все 0рем
- `.m-1.3` - Маржа Все 0рем
- `.m-1.2` - Маржа Все 0рем
- `.m-1.1` - Маржа Все 0рем
- `.m-1` - Маржа Все 1рем
- `.m-0.9` - Маржа Все 0рем
- `.m-0.8` - Маржа Все 0рем
- `.m-0.7` - Маржа Все 0рем
- `.m-0.6` - Маржа Все 0рем
- `.m-0.5` - Маржа Все 0рем
- `.m-0.4` - Маржа Все 0рем
- `.m-0.3` - Маржа Все 0рем
- `.m-0.2` - Маржа Все 0,2рем
- `.m-0.1` - Маржа Все 0,1рем
- `.m-0` - Маржа Все 0рем
- `.m-auto` - Маржа Все авто

#### Margin Bottom

- `.first:mb-0` - Нижняя маржа 0rem на первом месте
- `.hover:mb-100` - Нижняя маржа 100% при наведении
- `.hover:mb-75` - Нижняя маржа 75% при наведении
- `.hover:mb-50` - Нижняя маржа 50% при наведении
- `.hover:mb-25` - Нижняя маржа 25% при наведении
- `.hover:mb-5` - Нижняя маржа 5рем при наведении
- `.hover:mb-4.5` - Нижняя граница поля 0rem при наведении
- `.hover:mb-4` - Нижняя граница поля 4rem при наведении
- `.hover:mb-3.5` - Нижняя граница поля 0rem при наведении
- `.hover:mb-3` - Нижняя маржа 3rem при наведении
- `.hover:mb-2.5` - Нижняя граница поля 0rem при наведении
- `.hover:mb-2` - Нижняя граница 2rem при наведении
- `.hover:mb-1.9` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.8` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.7` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.6` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.5` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.4` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.3` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.2` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1.1` - Нижняя граница поля 0rem при наведении
- `.hover:mb-1` - Нижняя маржа 1rem при наведении
- `.hover:mb-0.9` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.8` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.7` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.6` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.5` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.4` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.3` - Нижняя граница поля 0rem при наведении
- `.hover:mb-0.2` - Нижняя маржа 0.2rem при наведении
- `.hover:mb-0.1` - Нижняя маржа 0,1 рем при наведении
- `.hover:mb-0` - Нижняя граница поля 0rem при наведении
- `.hover:mb-auto` - Нижнее поле автоматически при наведении
- `.last:mb-0` - Нижняя маржа 0rem на последнем
- `.mb-100` - Нижняя маржа 100%
- `.mb-75` - Нижняя маржа 75%
- `.mb-50` - Нижняя маржа 50%
- `.mb-25` - Нижняя маржа 25%
- `.mb-5` - Нижняя маржа 5рем
- `.mb-4.5` - Нижняя граница 0рем
- `.mb-4` - Нижняя маржа 4rem
- `.mb-3.5` - Нижняя граница 0рем
- `.mb-3` - Нижняя граница 3рем.
- `.mb-2.5` - Нижняя граница 0рем
- `.mb-2` - Нижняя маржа 2rem
- `.mb-1.9` - Нижняя граница 0рем
- `.mb-1.8` - Нижняя граница 0рем
- `.mb-1.7` - Нижняя граница 0рем
- `.mb-1.6` - Нижняя граница 0рем
- `.mb-1.5` - Нижняя граница 0рем
- `.mb-1.4` - Нижняя граница 0рем
- `.mb-1.3` - Нижняя граница 0рем
- `.mb-1.2` - Нижняя граница 0рем
- `.mb-1.1` - Нижняя граница 0рем
- `.mb-1` - Нижняя маржа: 1 рем.
- `.mb-0.9` - Нижняя граница 0рем
- `.mb-0.8` - Нижняя граница 0рем
- `.mb-0.7` - Нижняя граница 0рем
- `.mb-0.6` - Нижняя граница 0рем
- `.mb-0.5` - Нижняя граница 0рем
- `.mb-0.4` - Нижняя граница 0рем
- `.mb-0.3` - Нижняя граница 0рем
- `.mb-0.2` - Нижняя маржа 0,2 рем.
- `.mb-0.1` - Нижняя маржа 0,1 рем.
- `.mb-0` - Нижняя граница 0рем
- `.mb-auto` - Нижнее поле авто

#### Margin End

- `.hover:me-2` - Маржа Конец 2rem при наведении
- `.hover:me-1.5` - Конец маржи 1.5rem при наведении
- `.hover:me-1` - Конец маржи 1rem при наведении
- `.hover:me-0.5` - Конец маржи 0,5rem при наведении
- `.hover:me-0` - Margin End 0rem при наведении
- `.me-2` - Маржа Конец 2рем.
- `.me-1.5` - Конечная маржа 1,5 рем.
- `.me-1` - Маржа Конец 1рем
- `.me-0.5` - Конец маржи 0,5рем
- `.me-0` - Конец маржи 0рем

#### Margin Left

- `.first:ml-0` - Маржа слева 0rem на первом месте
- `.hover:ml-100` - Маржа слева 100% при наведении
- `.hover:ml-75` - Маржа слева 75% при наведении
- `.hover:ml-50` - Маржа слева 50% при наведении
- `.hover:ml-25` - Маржа слева 25% при наведении
- `.hover:ml-5` - Маржа слева 5рем при наведении
- `.hover:ml-4.5` - Маржа слева 0rem при наведении
- `.hover:ml-4` - Маржа слева 4rem при наведении
- `.hover:ml-3.5` - Маржа слева 0rem при наведении
- `.hover:ml-3` - Маржа слева 3rem при наведении
- `.hover:ml-2.5` - Маржа слева 0rem при наведении
- `.hover:ml-2` - Маржа слева 2rem при наведении
- `.hover:ml-1.9` - Маржа слева 0rem при наведении
- `.hover:ml-1.8` - Маржа слева 0rem при наведении
- `.hover:ml-1.7` - Маржа слева 0rem при наведении
- `.hover:ml-1.6` - Маржа слева 0rem при наведении
- `.hover:ml-1.5` - Маржа слева 0rem при наведении
- `.hover:ml-1.4` - Маржа слева 0rem при наведении
- `.hover:ml-1.3` - Маржа слева 0rem при наведении
- `.hover:ml-1.2` - Маржа слева 0rem при наведении
- `.hover:ml-1.1` - Маржа слева 0rem при наведении
- `.hover:ml-1` - Левое поле 1рем при наведении
- `.hover:ml-0.9` - Маржа слева 0rem при наведении
- `.hover:ml-0.8` - Маржа слева 0rem при наведении
- `.hover:ml-0.7` - Маржа слева 0rem при наведении
- `.hover:ml-0.6` - Маржа слева 0rem при наведении
- `.hover:ml-0.5` - Маржа слева 0rem при наведении
- `.hover:ml-0.4` - Маржа слева 0rem при наведении
- `.hover:ml-0.3` - Маржа слева 0rem при наведении
- `.hover:ml-0.2` - Маржа слева 0.2rem при наведении
- `.hover:ml-0.1` - Маржа слева 0,1 рем при наведении
- `.hover:ml-0` - Маржа слева 0rem при наведении
- `.hover:ml-auto` - Поле слева автоматически при наведении
- `.last:ml-0` - Маржа слева 0рем на последнем
- `.ml-100` - Оставшаяся маржа 100%
- `.ml-75` - Маржа слева 75%
- `.ml-50` - Оставшаяся маржа 50%
- `.ml-25` - Маржа слева 25%
- `.ml-5` - Маржа слева 5рем
- `.ml-4.5` - Левое поле 0рем
- `.ml-4` - Маржа слева 4рем
- `.ml-3.5` - Левое поле 0рем
- `.ml-3` - Маржа слева 3рем
- `.ml-2.5` - Левое поле 0рем
- `.ml-2` - Маржа слева 2рем
- `.ml-1.9` - Левое поле 0рем
- `.ml-1.8` - Левое поле 0рем
- `.ml-1.7` - Левое поле 0рем
- `.ml-1.6` - Левое поле 0рем
- `.ml-1.5` - Левое поле 0рем
- `.ml-1.4` - Левое поле 0рем
- `.ml-1.3` - Левое поле 0рем
- `.ml-1.2` - Левое поле 0рем
- `.ml-1.1` - Левое поле 0рем
- `.ml-1` - Левый запас: 1 рем.
- `.ml-0.9` - Левое поле 0рем
- `.ml-0.8` - Левое поле 0рем
- `.ml-0.7` - Левое поле 0рем
- `.ml-0.6` - Левое поле 0рем
- `.ml-0.5` - Левое поле 0рем
- `.ml-0.4` - Левое поле 0рем
- `.ml-0.3` - Левое поле 0рем
- `.ml-0.2` - Левая маржа 0,2 рем.
- `.ml-0.1` - Левая маржа 0,1 рем.
- `.ml-0` - Левое поле 0рем
- `.ml-auto` - Поле слева авто

#### Margin Right

- `.first:mr-0` - Маржа справа 0rem на первом месте
- `.hover:mr-100` - Маржа справа 100% при наведении
- `.hover:mr-75` - Маржа справа 75% при наведении
- `.hover:mr-50` - Маржа справа 50% при наведении
- `.hover:mr-25` - Маржа справа 25% при наведении
- `.hover:mr-5` - Маржа справа 5рем при наведении
- `.hover:mr-4.5` - Маржа справа 0рем при наведении
- `.hover:mr-4` - Маржа справа 4rem при наведении
- `.hover:mr-3.5` - Маржа справа 0рем при наведении
- `.hover:mr-3` - Маржа справа 3rem при наведении
- `.hover:mr-2.5` - Маржа справа 0рем при наведении
- `.hover:mr-2` - Маржа справа 2rem при наведении
- `.hover:mr-1.9` - Маржа справа 0рем при наведении
- `.hover:mr-1.8` - Маржа справа 0рем при наведении
- `.hover:mr-1.7` - Маржа справа 0рем при наведении
- `.hover:mr-1.6` - Маржа справа 0рем при наведении
- `.hover:mr-1.5` - Маржа справа 0рем при наведении
- `.hover:mr-1.4` - Маржа справа 0рем при наведении
- `.hover:mr-1.3` - Маржа справа 0рем при наведении
- `.hover:mr-1.2` - Маржа справа 0рем при наведении
- `.hover:mr-1.1` - Маржа справа 0рем при наведении
- `.hover:mr-1` - Маржа справа 1рем при наведении
- `.hover:mr-0.9` - Маржа справа 0рем при наведении
- `.hover:mr-0.8` - Маржа справа 0рем при наведении
- `.hover:mr-0.7` - Маржа справа 0рем при наведении
- `.hover:mr-0.6` - Маржа справа 0рем при наведении
- `.hover:mr-0.5` - Маржа справа 0рем при наведении
- `.hover:mr-0.4` - Маржа справа 0рем при наведении
- `.hover:mr-0.3` - Маржа справа 0рем при наведении
- `.hover:mr-0.2` - Маржа справа 0.2rem при наведении
- `.hover:mr-0.1` - Маржа справа 0,1 рем при наведении
- `.hover:mr-0` - Маржа справа 0рем при наведении
- `.hover:mr-auto` - Поле справа автоматически при наведении
- `.last:mr-0` - Маржа справа 0рем на последнем
- `.mr-100` - Маржа справа 100%
- `.mr-75` - Маржа справа 75%
- `.mr-50` - Маржа справа 50%
- `.mr-25` - Маржа справа 25%
- `.mr-5` - Маржа справа 5рем
- `.mr-4.5` - Маржа справа 0рем
- `.mr-4` - Маржа справа 4рем
- `.mr-3.5` - Маржа справа 0рем
- `.mr-3` - Маржа справа 3рем
- `.mr-2.5` - Маржа справа 0рем
- `.mr-2` - Маржа справа 2rem
- `.mr-1.9` - Маржа справа 0рем
- `.mr-1.8` - Маржа справа 0рем
- `.mr-1.7` - Маржа справа 0рем
- `.mr-1.6` - Маржа справа 0рем
- `.mr-1.5` - Маржа справа 0рем
- `.mr-1.4` - Маржа справа 0рем
- `.mr-1.3` - Маржа справа 0рем
- `.mr-1.2` - Маржа справа 0рем
- `.mr-1.1` - Маржа справа 0рем
- `.mr-1` - Маржа справа 1рем
- `.mr-0.9` - Маржа справа 0рем
- `.mr-0.8` - Маржа справа 0рем
- `.mr-0.7` - Маржа справа 0рем
- `.mr-0.6` - Маржа справа 0рем
- `.mr-0.5` - Маржа справа 0рем
- `.mr-0.4` - Маржа справа 0рем
- `.mr-0.3` - Маржа справа 0рем
- `.mr-0.2` - Маржа справа 0,2рем
- `.mr-0.1` - Маржа справа 0,1рем
- `.mr-0` - Маржа справа 0рем
- `.mr-auto` - Поле справа авто

#### Margin Start

- `.hover:ms-2` - Маржа Start 2rem при наведении
- `.hover:ms-1.5` - Маржа Старт 1,5рем при наведении
- `.hover:ms-1` - Маржа Старт 1рем при наведении
- `.hover:ms-0.5` - Маржа Старт 0,5рем при наведении
- `.hover:ms-0` - Маржа Start 0rem при наведении
- `.ms-2` - Маржа Старт 2рем
- `.ms-1.5` - Маржа Старт 1,5рем
- `.ms-1` - Маржа Старт 1рем
- `.ms-0.5` - Маржа Старт 0,5рем
- `.ms-0` - Маржа Старт 0рем

#### Margin Top

- `.first:mt-0` - Маржа Top 0rem на первом месте
- `.hover:mt-100` - Маржа Top 100% при наведении
- `.hover:mt-75` - Маржа Top 75% при наведении
- `.hover:mt-50` - Маржа Top 50% при наведении
- `.hover:mt-25` - Маржа Top 25% при наведении
- `.hover:mt-5` - Маржа Top 5rem при наведении
- `.hover:mt-4.5` - Маржа сверху 0рем при наведении
- `.hover:mt-4` - Маржа Top 4rem при наведении
- `.hover:mt-3.5` - Маржа сверху 0рем при наведении
- `.hover:mt-3` - Маржа Top 3rem при наведении
- `.hover:mt-2.5` - Маржа сверху 0рем при наведении
- `.hover:mt-2` - Маржа Top 2rem при наведении
- `.hover:mt-1.9` - Маржа сверху 0рем при наведении
- `.hover:mt-1.8` - Маржа сверху 0рем при наведении
- `.hover:mt-1.7` - Маржа сверху 0рем при наведении
- `.hover:mt-1.6` - Маржа сверху 0рем при наведении
- `.hover:mt-1.5` - Маржа сверху 0рем при наведении
- `.hover:mt-1.4` - Маржа сверху 0рем при наведении
- `.hover:mt-1.3` - Маржа сверху 0рем при наведении
- `.hover:mt-1.2` - Маржа сверху 0рем при наведении
- `.hover:mt-1.1` - Маржа сверху 0рем при наведении
- `.hover:mt-1` - Маржа Top 1rem при наведении
- `.hover:mt-0.9` - Маржа сверху 0рем при наведении
- `.hover:mt-0.8` - Маржа сверху 0рем при наведении
- `.hover:mt-0.7` - Маржа сверху 0рем при наведении
- `.hover:mt-0.6` - Маржа сверху 0рем при наведении
- `.hover:mt-0.5` - Маржа сверху 0рем при наведении
- `.hover:mt-0.4` - Маржа сверху 0рем при наведении
- `.hover:mt-0.3` - Маржа сверху 0рем при наведении
- `.hover:mt-0.2` - Верхняя маржа 0,2 рем. при наведении
- `.hover:mt-0.1` - Верхняя маржа 0,1 рем при наведении
- `.hover:mt-0` - Маржа сверху 0рем при наведении
- `.hover:mt-auto` - Margin Top автоматически при наведении
- `.last:mt-0` - Маржа Top 0rem на последнем
- `.mt-100` - Маржа Топ 100%
- `.mt-75` - Маржа Топ 75%
- `.mt-50` - Маржа Топ 50%
- `.mt-25` - Маржа Топ 25%
- `.mt-5` - Маржа Топ 5рем
- `.mt-4.5` - Маржа сверху 0рем
- `.mt-4` - Маржа Топ 4рем
- `.mt-3.5` - Маржа сверху 0рем
- `.mt-3` - Маржа Топ 3рем
- `.mt-2.5` - Маржа сверху 0рем
- `.mt-2` - Маржа Топ 2рем
- `.mt-1.9` - Маржа сверху 0рем
- `.mt-1.8` - Маржа сверху 0рем
- `.mt-1.7` - Маржа сверху 0рем
- `.mt-1.6` - Маржа сверху 0рем
- `.mt-1.5` - Маржа сверху 0рем
- `.mt-1.4` - Маржа сверху 0рем
- `.mt-1.3` - Маржа сверху 0рем
- `.mt-1.2` - Маржа сверху 0рем
- `.mt-1.1` - Маржа сверху 0рем
- `.mt-1` - Маржа Топ 1рем
- `.mt-0.9` - Маржа сверху 0рем
- `.mt-0.8` - Маржа сверху 0рем
- `.mt-0.7` - Маржа сверху 0рем
- `.mt-0.6` - Маржа сверху 0рем
- `.mt-0.5` - Маржа сверху 0рем
- `.mt-0.4` - Маржа сверху 0рем
- `.mt-0.3` - Маржа сверху 0рем
- `.mt-0.2` - Верхняя маржа 0,2 рем.
- `.mt-0.1` - Верхняя маржа 0,1 рем.
- `.mt-0` - Маржа сверху 0рем
- `.mt-auto` - Маржа сверху авто

#### Margin X-Axis

- `.hover:mx-100` - Маржа X-Axis 100% при наведении
- `.hover:mx-75` - Маржа X-Axis 75% при наведении
- `.hover:mx-50` - Маржа по оси X 50% при наведении
- `.hover:mx-25` - Маржа X-Axis 25% при наведении
- `.hover:mx-5` - Маржа X-Axis 5rem при наведении
- `.hover:mx-4.5` - Маржа X-Axis 0rem при наведении
- `.hover:mx-4` - Маржа X-Axis 4rem при наведении
- `.hover:mx-3.5` - Маржа X-Axis 0rem при наведении
- `.hover:mx-3` - Маржа X-Axis 3rem при наведении
- `.hover:mx-2.5` - Маржа X-Axis 0rem при наведении
- `.hover:mx-2` - Маржа X-Axis 2rem при наведении
- `.hover:mx-1.9` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.8` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.7` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.6` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.5` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.4` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.3` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.2` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1.1` - Маржа X-Axis 0rem при наведении
- `.hover:mx-1` - Маржа X-Axis 1rem при наведении
- `.hover:mx-0.9` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.8` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.7` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.6` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.5` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.4` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.3` - Маржа X-Axis 0rem при наведении
- `.hover:mx-0.2` - Маржа по оси X: 0,2 рем. при наведении
- `.hover:mx-0.1` - Маржа по оси X: 0,1 рем при наведении
- `.hover:mx-0` - Маржа X-Axis 0rem при наведении
- `.hover:mx-auto` - Маржа по оси X автоматически при наведении
- `.mx-100` - Маржа по оси X: 100%
- `.mx-75` - Запас по оси X 75%
- `.mx-50` - Маржа по оси X: 50%
- `.mx-25` - Маржа по оси X: 25%
- `.mx-5` - Маржа по оси X 5рем
- `.mx-4.5` - Маржа по оси X: 0рем
- `.mx-4` - Маржа по оси X 4rem
- `.mx-3.5` - Маржа по оси X: 0рем
- `.mx-3` - Запас по оси X 3rem
- `.mx-2.5` - Маржа по оси X: 0рем
- `.mx-2` - Запас по оси X 2rem
- `.mx-1.9` - Маржа по оси X: 0рем
- `.mx-1.8` - Маржа по оси X: 0рем
- `.mx-1.7` - Маржа по оси X: 0рем
- `.mx-1.6` - Маржа по оси X: 0рем
- `.mx-1.5` - Маржа по оси X: 0рем
- `.mx-1.4` - Маржа по оси X: 0рем
- `.mx-1.3` - Маржа по оси X: 0рем
- `.mx-1.2` - Маржа по оси X: 0рем
- `.mx-1.1` - Маржа по оси X: 0рем
- `.mx-1` - Запас по оси X: 1 рем.
- `.mx-0.9` - Маржа по оси X: 0рем
- `.mx-0.8` - Маржа по оси X: 0рем
- `.mx-0.7` - Маржа по оси X: 0рем
- `.mx-0.6` - Маржа по оси X: 0рем
- `.mx-0.5` - Маржа по оси X: 0рем
- `.mx-0.4` - Маржа по оси X: 0рем
- `.mx-0.3` - Маржа по оси X: 0рем
- `.mx-0.2` - Запас по оси X: 0,2 рем.
- `.mx-0.1` - Запас по оси X: 0,1 рем.
- `.mx-0` - Маржа по оси X: 0рем
- `.mx-auto` - Маржа по оси X, авто

#### Margin Y-Axis

- `.hover:my-100` - Маржа по оси Y: 100% при наведении
- `.hover:my-75` - Маржа по оси Y 75% при наведении
- `.hover:my-50` - Маржа по оси Y 50% при наведении
- `.hover:my-25` - Маржа по оси Y 25% при наведении
- `.hover:my-5` - Маржа по оси Y 5rem при наведении
- `.hover:my-4.5` - Маржа оси Y 0rem при наведении
- `.hover:my-4` - Маржа по оси Y 4rem при наведении
- `.hover:my-3.5` - Маржа оси Y 0rem при наведении
- `.hover:my-3` - Маржа по оси Y 3rem при наведении
- `.hover:my-2.5` - Маржа оси Y 0rem при наведении
- `.hover:my-2` - Маржа по оси Y 2rem при наведении
- `.hover:my-1.9` - Маржа оси Y 0rem при наведении
- `.hover:my-1.8` - Маржа оси Y 0rem при наведении
- `.hover:my-1.7` - Маржа оси Y 0rem при наведении
- `.hover:my-1.6` - Маржа оси Y 0rem при наведении
- `.hover:my-1.5` - Маржа оси Y 0rem при наведении
- `.hover:my-1.4` - Маржа оси Y 0rem при наведении
- `.hover:my-1.3` - Маржа оси Y 0rem при наведении
- `.hover:my-1.2` - Маржа оси Y 0rem при наведении
- `.hover:my-1.1` - Маржа оси Y 0rem при наведении
- `.hover:my-1` - Маржа по оси Y: 1 рем при наведении
- `.hover:my-0.9` - Маржа оси Y 0rem при наведении
- `.hover:my-0.8` - Маржа оси Y 0rem при наведении
- `.hover:my-0.7` - Маржа оси Y 0rem при наведении
- `.hover:my-0.6` - Маржа оси Y 0rem при наведении
- `.hover:my-0.5` - Маржа оси Y 0rem при наведении
- `.hover:my-0.4` - Маржа оси Y 0rem при наведении
- `.hover:my-0.3` - Маржа оси Y 0rem при наведении
- `.hover:my-0.2` - Маржа по оси Y: 0,2 рем. при наведении
- `.hover:my-0.1` - Маржа по оси Y: 0,1 рем при наведении
- `.hover:my-0` - Маржа оси Y 0rem при наведении
- `.hover:my-auto` - Отступ по оси Y автоматически при наведении
- `.my-100` - Запас по оси Y: 100%
- `.my-75` - Поле по оси Y 75%
- `.my-50` - Запас по оси Y: 50%
- `.my-25` - Запас по оси Y: 25%
- `.my-5` - Запас по оси Y 5rem
- `.my-4.5` - Поле по оси Y 0рем
- `.my-4` - Запас по оси Y 4rem
- `.my-3.5` - Поле по оси Y 0рем
- `.my-3` - Маржа по оси Y 3rem
- `.my-2.5` - Поле по оси Y 0рем
- `.my-2` - Запас по оси Y 2rem
- `.my-1.9` - Поле по оси Y 0рем
- `.my-1.8` - Поле по оси Y 0рем
- `.my-1.7` - Поле по оси Y 0рем
- `.my-1.6` - Поле по оси Y 0рем
- `.my-1.5` - Поле по оси Y 0рем
- `.my-1.4` - Поле по оси Y 0рем
- `.my-1.3` - Поле по оси Y 0рем
- `.my-1.2` - Поле по оси Y 0рем
- `.my-1.1` - Поле по оси Y 0рем
- `.my-1` - Запас по оси Y: 1 рем.
- `.my-0.9` - Поле по оси Y 0рем
- `.my-0.8` - Поле по оси Y 0рем
- `.my-0.7` - Поле по оси Y 0рем
- `.my-0.6` - Поле по оси Y 0рем
- `.my-0.5` - Поле по оси Y 0рем
- `.my-0.4` - Поле по оси Y 0рем
- `.my-0.3` - Поле по оси Y 0рем
- `.my-0.2` - Запас по оси Y: 0,2 рем.
- `.my-0.1` - Запас по оси Y: 0,1 рем.
- `.my-0` - Поле по оси Y 0рем
- `.my-auto` - Поле по оси Y, авто

### Padding

#### Padding All

- `.first:p-0` - Заполнение всех 0rem первым
- `.hover:p-5` - Заполнение всех 5rem при наведении
- `.hover:p-4.5` - Заполнение всех 0rem при наведении
- `.hover:p-4` - Заполнение всех 4rem при наведении
- `.hover:p-3.5` - Заполнение всех 0rem при наведении
- `.hover:p-3` - Заполнение всех 3rem при наведении
- `.hover:p-2.5` - Заполнение всех 0rem при наведении
- `.hover:p-2` - Заполнение всех 2rem при наведении
- `.hover:p-1.9` - Заполнение всех 0rem при наведении
- `.hover:p-1.8` - Заполнение всех 0rem при наведении
- `.hover:p-1.7` - Заполнение всех 0rem при наведении
- `.hover:p-1.6` - Заполнение всех 0rem при наведении
- `.hover:p-1.5` - Заполнение всех 0rem при наведении
- `.hover:p-1.4` - Заполнение всех 0rem при наведении
- `.hover:p-1.3` - Заполнение всех 0rem при наведении
- `.hover:p-1.2` - Заполнение всех 0rem при наведении
- `.hover:p-1.1` - Заполнение всех 0rem при наведении
- `.hover:p-1` - Заполнение всех 1rem при наведении
- `.hover:p-0.9` - Заполнение всех 0rem при наведении
- `.hover:p-0.8` - Заполнение всех 0rem при наведении
- `.hover:p-0.7` - Заполнение всех 0rem при наведении
- `.hover:p-0.6` - Заполнение всех 0rem при наведении
- `.hover:p-0.5` - Заполнение всех 0rem при наведении
- `.hover:p-0.4` - Заполнение всех 0rem при наведении
- `.hover:p-0.3` - Заполнение всех 0rem при наведении
- `.hover:p-0.2` - Заполнение всех 0,2rem при наведении
- `.hover:p-0.1` - Заполнение всех 0,1rem при наведении
- `.hover:p-0` - Заполнение всех 0rem при наведении
- `.last:p-0` - Заполнение всех 0rem последним
- `.p-5` - Набивка Все 5рем
- `.p-4.5` - Заполнение всех 0rem
- `.p-4` - Набивка Все 4рем
- `.p-3.5` - Заполнение всех 0rem
- `.p-3` - Набивка Все 3рем
- `.p-2.5` - Заполнение всех 0rem
- `.p-2` - Заполнение всех 2rem
- `.p-1.9` - Заполнение всех 0rem
- `.p-1.8` - Заполнение всех 0rem
- `.p-1.7` - Заполнение всех 0rem
- `.p-1.6` - Заполнение всех 0rem
- `.p-1.5` - Заполнение всех 0rem
- `.p-1.4` - Заполнение всех 0rem
- `.p-1.3` - Заполнение всех 0rem
- `.p-1.2` - Заполнение всех 0rem
- `.p-1.1` - Заполнение всех 0rem
- `.p-1` - Набивка Все 1рем
- `.p-0.9` - Заполнение всех 0rem
- `.p-0.8` - Заполнение всех 0rem
- `.p-0.7` - Заполнение всех 0rem
- `.p-0.6` - Заполнение всех 0rem
- `.p-0.5` - Заполнение всех 0rem
- `.p-0.4` - Заполнение всех 0rem
- `.p-0.3` - Заполнение всех 0rem
- `.p-0.2` - Заполнение всех 0.2rem
- `.p-0.1` - Заполнение всех 0,1рем
- `.p-0` - Заполнение всех 0rem

#### Padding Bottom

- `.first:pb-0` - Заполнение Bottom 0rem в первую очередь
- `.hover:pb-100` - Padding Bottom 100% при наведении
- `.hover:pb-75` - Заполнение нижней части 75% при наведении
- `.hover:pb-50` - Padding Bottom 50% при наведении
- `.hover:pb-25` - Padding Bottom 25% при наведении
- `.hover:pb-5` - Отступ снизу 5rem при наведении
- `.hover:pb-4.5` - Отступ снизу 0rem при наведении
- `.hover:pb-4` - Отступ снизу 4rem при наведении
- `.hover:pb-3.5` - Отступ снизу 0rem при наведении
- `.hover:pb-3` - Отступ снизу 3rem при наведении
- `.hover:pb-2.5` - Отступ снизу 0rem при наведении
- `.hover:pb-2` - Отступ снизу 2rem при наведении
- `.hover:pb-1.9` - Отступ снизу 0rem при наведении
- `.hover:pb-1.8` - Отступ снизу 0rem при наведении
- `.hover:pb-1.7` - Отступ снизу 0rem при наведении
- `.hover:pb-1.6` - Отступ снизу 0rem при наведении
- `.hover:pb-1.5` - Отступ снизу 0rem при наведении
- `.hover:pb-1.4` - Отступ снизу 0rem при наведении
- `.hover:pb-1.3` - Отступ снизу 0rem при наведении
- `.hover:pb-1.2` - Отступ снизу 0rem при наведении
- `.hover:pb-1.1` - Отступ снизу 0rem при наведении
- `.hover:pb-1` - Отступ снизу 1rem при наведении
- `.hover:pb-0.9` - Отступ снизу 0rem при наведении
- `.hover:pb-0.8` - Отступ снизу 0rem при наведении
- `.hover:pb-0.7` - Отступ снизу 0rem при наведении
- `.hover:pb-0.6` - Отступ снизу 0rem при наведении
- `.hover:pb-0.5` - Отступ снизу 0rem при наведении
- `.hover:pb-0.4` - Отступ снизу 0rem при наведении
- `.hover:pb-0.3` - Отступ снизу 0rem при наведении
- `.hover:pb-0.2` - Отступ снизу 0.2rem при наведении
- `.hover:pb-0.1` - Отступ снизу 0.1rem при наведении
- `.hover:pb-0` - Отступ снизу 0rem при наведении
- `.last:pb-0` - Заполнение Bottom 0rem в последнюю очередь
- `.pb-100` - Подкладка снизу 100%
- `.pb-75` - Подкладка снизу 75%
- `.pb-50` - Подкладка снизу 50%
- `.pb-25` - Подкладка снизу 25%
- `.pb-5` - Подкладка снизу 5rem
- `.pb-4.5` - Отступ снизу 0rem
- `.pb-4` - Подкладка снизу 4rem
- `.pb-3.5` - Отступ снизу 0rem
- `.pb-3` - Подкладка снизу 3rem
- `.pb-2.5` - Отступ снизу 0rem
- `.pb-2` - Подкладка снизу 2rem
- `.pb-1.9` - Отступ снизу 0rem
- `.pb-1.8` - Отступ снизу 0rem
- `.pb-1.7` - Отступ снизу 0rem
- `.pb-1.6` - Отступ снизу 0rem
- `.pb-1.5` - Отступ снизу 0rem
- `.pb-1.4` - Отступ снизу 0rem
- `.pb-1.3` - Отступ снизу 0rem
- `.pb-1.2` - Отступ снизу 0rem
- `.pb-1.1` - Отступ снизу 0rem
- `.pb-1` - Подкладка снизу 1rem
- `.pb-0.9` - Отступ снизу 0rem
- `.pb-0.8` - Отступ снизу 0rem
- `.pb-0.7` - Отступ снизу 0rem
- `.pb-0.6` - Отступ снизу 0rem
- `.pb-0.5` - Отступ снизу 0rem
- `.pb-0.4` - Отступ снизу 0rem
- `.pb-0.3` - Отступ снизу 0rem
- `.pb-0.2` - Заполнение снизу 0.2rem
- `.pb-0.1` - Отступ снизу 0.1rem
- `.pb-0` - Отступ снизу 0rem

#### Padding Left

- `.first:pl-0` - Заполнение слева 0rem в первую очередь
- `.hover:pl-5` - Отступ влево 5rem при наведении
- `.hover:pl-4.5` - Заполнение слева 0rem при наведении
- `.hover:pl-4` - Отступ влево 4rem при наведении
- `.hover:pl-3.5` - Заполнение слева 0rem при наведении
- `.hover:pl-3` - Отступ влево 3rem при наведении
- `.hover:pl-2.5` - Заполнение слева 0rem при наведении
- `.hover:pl-2` - Отступ влево 2rem при наведении
- `.hover:pl-1.9` - Заполнение слева 0rem при наведении
- `.hover:pl-1.8` - Заполнение слева 0rem при наведении
- `.hover:pl-1.7` - Заполнение слева 0rem при наведении
- `.hover:pl-1.6` - Заполнение слева 0rem при наведении
- `.hover:pl-1.5` - Заполнение слева 0rem при наведении
- `.hover:pl-1.4` - Заполнение слева 0rem при наведении
- `.hover:pl-1.3` - Заполнение слева 0rem при наведении
- `.hover:pl-1.2` - Заполнение слева 0rem при наведении
- `.hover:pl-1.1` - Заполнение слева 0rem при наведении
- `.hover:pl-1` - Отступ влево 1rem при наведении
- `.hover:pl-0.9` - Заполнение слева 0rem при наведении
- `.hover:pl-0.8` - Заполнение слева 0rem при наведении
- `.hover:pl-0.7` - Заполнение слева 0rem при наведении
- `.hover:pl-0.6` - Заполнение слева 0rem при наведении
- `.hover:pl-0.5` - Заполнение слева 0rem при наведении
- `.hover:pl-0.4` - Заполнение слева 0rem при наведении
- `.hover:pl-0.3` - Заполнение слева 0rem при наведении
- `.hover:pl-0.2` - Отступ влево 0,2 рем при наведении
- `.hover:pl-0.1` - Отступ влево 0,1 рем при наведении
- `.hover:pl-0` - Заполнение слева 0rem при наведении
- `.last:pl-0` - Заполнение слева 0rem на последнем
- `.pl-5` - Заполнение слева 5рем
- `.pl-4.5` - Заполнение слева 0rem
- `.pl-4` - Заполнение слева 4rem
- `.pl-3.5` - Заполнение слева 0rem
- `.pl-3` - Заполнение слева 3rem
- `.pl-2.5` - Заполнение слева 0rem
- `.pl-2` - Заполнение слева 2rem
- `.pl-1.9` - Заполнение слева 0rem
- `.pl-1.8` - Заполнение слева 0rem
- `.pl-1.7` - Заполнение слева 0rem
- `.pl-1.6` - Заполнение слева 0rem
- `.pl-1.5` - Заполнение слева 0rem
- `.pl-1.4` - Заполнение слева 0rem
- `.pl-1.3` - Заполнение слева 0rem
- `.pl-1.2` - Заполнение слева 0rem
- `.pl-1.1` - Заполнение слева 0rem
- `.pl-1` - Отступ слева 1рем
- `.pl-0.9` - Заполнение слева 0rem
- `.pl-0.8` - Заполнение слева 0rem
- `.pl-0.7` - Заполнение слева 0rem
- `.pl-0.6` - Заполнение слева 0rem
- `.pl-0.5` - Заполнение слева 0rem
- `.pl-0.4` - Заполнение слева 0rem
- `.pl-0.3` - Заполнение слева 0rem
- `.pl-0.2` - Отступ слева 0,2rem
- `.pl-0.1` - Отступ слева: 0,1 рем.
- `.pl-0` - Заполнение слева 0rem

#### Padding Right

- `.first:pr-0` - Заполнение справа 0rem в первую очередь
- `.hover:pr-100` - Отступ вправо 100% при наведении
- `.hover:pr-75` - Padding Right 75% при наведении
- `.hover:pr-50` - Отступ вправо 50% при наведении
- `.hover:pr-25` - Отступ справа 25% при наведении
- `.hover:pr-5` - Отступ вправо 5rem при наведении
- `.hover:pr-4.5` - Заполнение справа 0rem при наведении
- `.hover:pr-4` - Отступ вправо 4rem при наведении
- `.hover:pr-3.5` - Заполнение справа 0rem при наведении
- `.hover:pr-3` - Отступ вправо 3rem при наведении
- `.hover:pr-2.5` - Заполнение справа 0rem при наведении
- `.hover:pr-2` - Отступ вправо 2rem при наведении
- `.hover:pr-1.9` - Заполнение справа 0rem при наведении
- `.hover:pr-1.8` - Заполнение справа 0rem при наведении
- `.hover:pr-1.7` - Заполнение справа 0rem при наведении
- `.hover:pr-1.6` - Заполнение справа 0rem при наведении
- `.hover:pr-1.5` - Заполнение справа 0rem при наведении
- `.hover:pr-1.4` - Заполнение справа 0rem при наведении
- `.hover:pr-1.3` - Заполнение справа 0rem при наведении
- `.hover:pr-1.2` - Заполнение справа 0rem при наведении
- `.hover:pr-1.1` - Заполнение справа 0rem при наведении
- `.hover:pr-1` - Отступ вправо 1rem при наведении
- `.hover:pr-0.9` - Заполнение справа 0rem при наведении
- `.hover:pr-0.8` - Заполнение справа 0rem при наведении
- `.hover:pr-0.7` - Заполнение справа 0rem при наведении
- `.hover:pr-0.6` - Заполнение справа 0rem при наведении
- `.hover:pr-0.5` - Заполнение справа 0rem при наведении
- `.hover:pr-0.4` - Заполнение справа 0rem при наведении
- `.hover:pr-0.3` - Заполнение справа 0rem при наведении
- `.hover:pr-0.2` - Отступ вправо 0,2 рем при наведении
- `.hover:pr-0.1` - Отступ вправо 0,1 рем при наведении
- `.hover:pr-0` - Заполнение справа 0rem при наведении
- `.last:pr-0` - Заполнение справа 0rem на последнем
- `.pr-100` - Заполнение справа 100%
- `.pr-75` - Набивка правая 75%
- `.pr-50` - Заполнение справа 50%
- `.pr-25` - Набивка справа 25%
- `.pr-5` - Заполнение справа 5рем
- `.pr-4.5` - Заполнение справа 0rem
- `.pr-4` - Заполнение справа 4rem
- `.pr-3.5` - Заполнение справа 0rem
- `.pr-3` - Заполнение справа 3rem
- `.pr-2.5` - Заполнение справа 0rem
- `.pr-2` - Заполнение справа 2rem
- `.pr-1.9` - Заполнение справа 0rem
- `.pr-1.8` - Заполнение справа 0rem
- `.pr-1.7` - Заполнение справа 0rem
- `.pr-1.6` - Заполнение справа 0rem
- `.pr-1.5` - Заполнение справа 0rem
- `.pr-1.4` - Заполнение справа 0rem
- `.pr-1.3` - Заполнение справа 0rem
- `.pr-1.2` - Заполнение справа 0rem
- `.pr-1.1` - Заполнение справа 0rem
- `.pr-1` - Заполнение справа 1рем
- `.pr-0.9` - Заполнение справа 0rem
- `.pr-0.8` - Заполнение справа 0rem
- `.pr-0.7` - Заполнение справа 0rem
- `.pr-0.6` - Заполнение справа 0rem
- `.pr-0.5` - Заполнение справа 0rem
- `.pr-0.4` - Заполнение справа 0rem
- `.pr-0.3` - Заполнение справа 0rem
- `.pr-0.2` - Заполнение справа 0.2rem
- `.pr-0.1` - Заполнение справа 0,1рем
- `.pr-0` - Заполнение справа 0rem

#### Padding Top

- `.first:pt-0` - Заполнение Top 0rem в первую очередь
- `.hover:pt-100` - Заполнение Top 100% при наведении
- `.hover:pt-75` - Прокладка Top 75% при наведении
- `.hover:pt-50` - Заполнение Top 50% при наведении
- `.hover:pt-25` - Заполнение Top 25% при наведении
- `.hover:pt-5` - Отступы Top 5rem при наведении
- `.hover:pt-4.5` - Отступы Top 0rem при наведении
- `.hover:pt-4` - Заполнение Top 4rem при наведении
- `.hover:pt-3.5` - Отступы Top 0rem при наведении
- `.hover:pt-3` - Заполнение Top 3rem при наведении
- `.hover:pt-2.5` - Отступы Top 0rem при наведении
- `.hover:pt-2` - Прокладка Top 2rem при наведении
- `.hover:pt-1.9` - Отступы Top 0rem при наведении
- `.hover:pt-1.8` - Отступы Top 0rem при наведении
- `.hover:pt-1.7` - Отступы Top 0rem при наведении
- `.hover:pt-1.6` - Отступы Top 0rem при наведении
- `.hover:pt-1.5` - Отступы Top 0rem при наведении
- `.hover:pt-1.4` - Отступы Top 0rem при наведении
- `.hover:pt-1.3` - Отступы Top 0rem при наведении
- `.hover:pt-1.2` - Отступы Top 0rem при наведении
- `.hover:pt-1.1` - Отступы Top 0rem при наведении
- `.hover:pt-1` - Отступы Top 1rem при наведении
- `.hover:pt-0.9` - Отступы Top 0rem при наведении
- `.hover:pt-0.8` - Отступы Top 0rem при наведении
- `.hover:pt-0.7` - Отступы Top 0rem при наведении
- `.hover:pt-0.6` - Отступы Top 0rem при наведении
- `.hover:pt-0.5` - Отступы Top 0rem при наведении
- `.hover:pt-0.4` - Отступы Top 0rem при наведении
- `.hover:pt-0.3` - Отступы Top 0rem при наведении
- `.hover:pt-0.2` - Отступы Top 0,2rem при наведении
- `.hover:pt-0.1` - Отступы Top 0,1rem при наведении
- `.hover:pt-0` - Отступы Top 0rem при наведении
- `.last:pt-0` - Заполнение Top 0rem на последнем месте
- `.pt-100` - Набивка Топ 100%
- `.pt-75` - Набивка Топ 75%
- `.pt-50` - Набивка Топ 50%
- `.pt-25` - Набивка Топ 25%
- `.pt-5` - Набивка Топ 5рем
- `.pt-4.5` - Прокладка сверху 0rem
- `.pt-4` - Набивка Топ 4рем
- `.pt-3.5` - Прокладка сверху 0rem
- `.pt-3` - Набивка Топ 3рем
- `.pt-2.5` - Прокладка сверху 0rem
- `.pt-2` - Подкладка Топ 2rem
- `.pt-1.9` - Прокладка сверху 0rem
- `.pt-1.8` - Прокладка сверху 0rem
- `.pt-1.7` - Прокладка сверху 0rem
- `.pt-1.6` - Прокладка сверху 0rem
- `.pt-1.5` - Прокладка сверху 0rem
- `.pt-1.4` - Прокладка сверху 0rem
- `.pt-1.3` - Прокладка сверху 0rem
- `.pt-1.2` - Прокладка сверху 0rem
- `.pt-1.1` - Прокладка сверху 0rem
- `.pt-1` - Набивка Топ 1rem
- `.pt-0.9` - Прокладка сверху 0rem
- `.pt-0.8` - Прокладка сверху 0rem
- `.pt-0.7` - Прокладка сверху 0rem
- `.pt-0.6` - Прокладка сверху 0rem
- `.pt-0.5` - Прокладка сверху 0rem
- `.pt-0.4` - Прокладка сверху 0rem
- `.pt-0.3` - Прокладка сверху 0rem
- `.pt-0.2` - Прокладка Верх 0.2rem
- `.pt-0.1` - Прокладка Верх 0,1рем
- `.pt-0` - Прокладка сверху 0rem

#### Padding X-Axis

- `.hover:px-100` - Заполнение X-Axis 100% при наведении
- `.hover:px-75` - Заполнение X-Axis 75% при наведении
- `.hover:px-50` - Отступ X-Axis 50% при наведении
- `.hover:px-25` - Заполнение X-Axis 25% при наведении
- `.hover:px-5` - Заполнение X-Axis 5rem при наведении
- `.hover:px-4.5` - Заполнение оси X 0rem при наведении
- `.hover:px-4` - Заполнение X-Axis 4rem при наведении
- `.hover:px-3.5` - Заполнение оси X 0rem при наведении
- `.hover:px-3` - Заполнение X-Axis 3rem при наведении
- `.hover:px-2.5` - Заполнение оси X 0rem при наведении
- `.hover:px-2` - Заполнение X-Axis 2rem при наведении
- `.hover:px-1.9` - Заполнение оси X 0rem при наведении
- `.hover:px-1.8` - Заполнение оси X 0rem при наведении
- `.hover:px-1.7` - Заполнение оси X 0rem при наведении
- `.hover:px-1.6` - Заполнение оси X 0rem при наведении
- `.hover:px-1.5` - Заполнение оси X 0rem при наведении
- `.hover:px-1.4` - Заполнение оси X 0rem при наведении
- `.hover:px-1.3` - Заполнение оси X 0rem при наведении
- `.hover:px-1.2` - Заполнение оси X 0rem при наведении
- `.hover:px-1.1` - Заполнение оси X 0rem при наведении
- `.hover:px-1` - Заполнение X-Axis 1rem при наведении
- `.hover:px-0.9` - Заполнение оси X 0rem при наведении
- `.hover:px-0.8` - Заполнение оси X 0rem при наведении
- `.hover:px-0.7` - Заполнение оси X 0rem при наведении
- `.hover:px-0.6` - Заполнение оси X 0rem при наведении
- `.hover:px-0.5` - Заполнение оси X 0rem при наведении
- `.hover:px-0.4` - Заполнение оси X 0rem при наведении
- `.hover:px-0.3` - Заполнение оси X 0rem при наведении
- `.hover:px-0.2` - Заполнение оси X 0,2 рем. при наведении
- `.hover:px-0.1` - Заполнение оси X 0,1 рем при наведении
- `.hover:px-0` - Заполнение оси X 0rem при наведении
- `.px-100` - Заполнение оси X 100%
- `.px-75` - Заполнение оси X 75%
- `.px-50` - Заполнение оси X 50%
- `.px-25` - Заполнение X-Axis 25%
- `.px-5` - Заполнение оси X 5rem
- `.px-4.5` - Заполнение оси X 0rem
- `.px-4` - Заполнение оси X 4rem
- `.px-3.5` - Заполнение оси X 0rem
- `.px-3` - Заполнение оси X 3rem
- `.px-2.5` - Заполнение оси X 0rem
- `.px-2` - Заполнение оси X 2rem
- `.px-1.9` - Заполнение оси X 0rem
- `.px-1.8` - Заполнение оси X 0rem
- `.px-1.7` - Заполнение оси X 0rem
- `.px-1.6` - Заполнение оси X 0rem
- `.px-1.5` - Заполнение оси X 0rem
- `.px-1.4` - Заполнение оси X 0rem
- `.px-1.3` - Заполнение оси X 0rem
- `.px-1.2` - Заполнение оси X 0rem
- `.px-1.1` - Заполнение оси X 0rem
- `.px-1` - Заполнение оси X 1rem
- `.px-0.9` - Заполнение оси X 0rem
- `.px-0.8` - Заполнение оси X 0rem
- `.px-0.7` - Заполнение оси X 0rem
- `.px-0.6` - Заполнение оси X 0rem
- `.px-0.5` - Заполнение оси X 0rem
- `.px-0.4` - Заполнение оси X 0rem
- `.px-0.3` - Заполнение оси X 0rem
- `.px-0.2` - Заполнение оси X 0,2 рем.
- `.px-0.1` - Заполнение оси X: 0,1 рем.
- `.px-0` - Заполнение оси X 0rem

#### Padding Y-Axis

- `.hover:py-100` - Заполнение оси Y 100% при наведении
- `.hover:py-75` - Заполнение оси Y 75% при наведении
- `.hover:py-50` - Заполнение оси Y 50% при наведении
- `.hover:py-25` - Заполнение оси Y 25% при наведении
- `.hover:py-5` - Заполнение оси Y 5rem при наведении
- `.hover:py-4.5` - Заполнение оси Y 0rem при наведении
- `.hover:py-4` - Заполнение оси Y 4rem при наведении
- `.hover:py-3.5` - Заполнение оси Y 0rem при наведении
- `.hover:py-3` - Заполнение оси Y 3rem при наведении
- `.hover:py-2.5` - Заполнение оси Y 0rem при наведении
- `.hover:py-2` - Заполнение оси Y 2rem при наведении
- `.hover:py-1.9` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.8` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.7` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.6` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.5` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.4` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.3` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.2` - Заполнение оси Y 0rem при наведении
- `.hover:py-1.1` - Заполнение оси Y 0rem при наведении
- `.hover:py-1` - Заполнение оси Y 1rem при наведении
- `.hover:py-0.9` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.8` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.7` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.6` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.5` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.4` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.3` - Заполнение оси Y 0rem при наведении
- `.hover:py-0.2` - Заполнение оси Y 0,2 рем. при наведении
- `.hover:py-0.1` - Заполнение оси Y 0,1 рем при наведении
- `.hover:py-0` - Заполнение оси Y 0rem при наведении
- `.py-100` - Заполнение оси Y 100%
- `.py-75` - Заполнение оси Y 75%
- `.py-50` - Заполнение оси Y 50%
- `.py-25` - Заполнение оси Y 25%
- `.py-5` - Заполнение оси Y 5rem
- `.py-4.5` - Заполнение оси Y 0rem
- `.py-4` - Заполнение оси Y 4rem
- `.py-3.5` - Заполнение оси Y 0rem
- `.py-3` - Заполнение оси Y 3rem
- `.py-2.5` - Заполнение оси Y 0rem
- `.py-2` - Заполнение оси Y 2rem
- `.py-1.9` - Заполнение оси Y 0rem
- `.py-1.8` - Заполнение оси Y 0rem
- `.py-1.7` - Заполнение оси Y 0rem
- `.py-1.6` - Заполнение оси Y 0rem
- `.py-1.5` - Заполнение оси Y 0rem
- `.py-1.4` - Заполнение оси Y 0rem
- `.py-1.3` - Заполнение оси Y 0rem
- `.py-1.2` - Заполнение оси Y 0rem
- `.py-1.1` - Заполнение оси Y 0rem
- `.py-1` - Заполнение оси Y 1rem
- `.py-0.9` - Заполнение оси Y 0rem
- `.py-0.8` - Заполнение оси Y 0rem
- `.py-0.7` - Заполнение оси Y 0rem
- `.py-0.6` - Заполнение оси Y 0rem
- `.py-0.5` - Заполнение оси Y 0rem
- `.py-0.4` - Заполнение оси Y 0rem
- `.py-0.3` - Заполнение оси Y 0rem
- `.py-0.2` - Заполнение оси Y 0,2 рем.
- `.py-0.1` - Заполнение оси Y 0,1 рем.
- `.py-0` - Заполнение оси Y 0rem

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

##### Width - Mobile (≤ 480px)

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
- `.hover:mobile:w-35` - Ширина 35 % при наведении на мобильном устройстве.
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

##### Width - Tv (≥ 1200px)

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

##### Width - Tablet Max (≤ 768px)

- `.hover:tablet-max:w-100` - Ширина 100% при наведении на планшете макс.
- `.hover:tablet-max:w-95` - Ширина 95% при наведении на планшете макс.
- `.hover:tablet-max:w-90` - Ширина 90% при наведении на планшете макс.
- `.hover:tablet-max:w-85` - Ширина 85 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-80` - Ширина 80 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-75` - Ширина 75 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-70` - Ширина 70 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-65` - Ширина 65 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-60` - Ширина 60% при наведении на планшете макс.
- `.hover:tablet-max:w-55` - Ширина 55 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-50` - Ширина 50 % при наведении на планшете (максимум)
- `.hover:tablet-max:w-45` - Ширина 45% при наведении на планшете макс.
- `.hover:tablet-max:w-40` - Ширина 40% при наведении на планшете макс.
- `.hover:tablet-max:w-35` - Ширина 35% при наведении на планшете макс.
- `.hover:tablet-max:w-30` - Ширина 30% при наведении на планшете макс.
- `.hover:tablet-max:w-25` - Ширина 25 % при наведении на планшете (макс.)
- `.hover:tablet-max:w-20` - Ширина 20 % при наведении на планшете (макс.)
- `.hover:tablet-max:w-15` - Ширина 15% при наведении на планшете макс.
- `.hover:tablet-max:w-10` - Ширина 10% при наведении на планшете макс.
- `.hover:tablet-max:w-5` - Ширина 5% при наведении на планшете макс.
- `.hover:tablet-max:w-auto` - Ширина авто% при наведении на планшет макс.
- `.tablet-max:w-100` - Ширина 100 % на планшете (макс.)
- `.tablet-max:w-95` - Ширина 95 % на планшете (макс.)
- `.tablet-max:w-90` - Ширина 90 % на планшете (макс.)
- `.tablet-max:w-85` - Ширина 85 % на планшете (макс.)
- `.tablet-max:w-80` - Ширина 80 % на планшете (макс.)
- `.tablet-max:w-75` - Ширина 75 % на планшете (макс.)
- `.tablet-max:w-70` - Ширина 70 % на планшете (макс.)
- `.tablet-max:w-65` - Ширина 65 % на планшете (макс.)
- `.tablet-max:w-60` - Ширина 60% на планшете макс.
- `.tablet-max:w-55` - Ширина 55 % на планшете (макс.)
- `.tablet-max:w-50` - Ширина 50 % на планшете (макс.)
- `.tablet-max:w-45` - Ширина 45% на планшете макс.
- `.tablet-max:w-40` - Ширина 40% на планшете макс.
- `.tablet-max:w-35` - Ширина 35% на планшете макс.
- `.tablet-max:w-30` - Ширина 30% на планшете макс.
- `.tablet-max:w-25` - Ширина 25 % на планшете (макс.)
- `.tablet-max:w-20` - Ширина 20% на планшете макс.
- `.tablet-max:w-15` - Ширина 15% на планшете макс.
- `.tablet-max:w-10` - Ширина 10% на планшете макс.
- `.tablet-max:w-5` - Ширина 5% на планшете макс.
- `.tablet-max:w-auto` - Ширина авто% на планшете макс.

##### Width - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:w-100` - Ширина 100% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:w-95` - Ширина 95 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-90` - Ширина 90% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-85` - Ширина 85% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:w-80` - Ширина 80% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-75` - Ширина 75 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:w-70` - Ширина 70 % при наведении на планшетном ПК (максимум)
- `.hover:tablet-pc-max:w-65` - Ширина 65 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:w-60` - Ширина 60% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-55` - Ширина 55 % при наведении на планшетный ПК (макс.)
- `.hover:tablet-pc-max:w-50` - Ширина 50 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-45` - Ширина 45% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-40` - Ширина 40% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-35` - Ширина 35% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-30` - Ширина 30% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:w-25` - Ширина 25 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-20` - Ширина 20 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-15` - Ширина 15% при наведении на планшетном ПК максимум
- `.hover:tablet-pc-max:w-10` - Ширина 10% при наведении на планшетном ПК максимум
- `.hover:tablet-pc-max:w-5` - Ширина 5 % при наведении на планшетном ПК (макс.)
- `.hover:tablet-pc-max:w-auto` - Ширина авто% при наведении на планшетный ПК макс.
- `.tablet-pc-max:w-100` - Ширина 100% на планшетном ПК макс.
- `.tablet-pc-max:w-95` - Ширина 95% на планшетном ПК макс.
- `.tablet-pc-max:w-90` - Ширина 90% на планшетном ПК макс.
- `.tablet-pc-max:w-85` - Ширина 85% на планшетном ПК макс.
- `.tablet-pc-max:w-80` - Ширина 80% на планшетном ПК макс.
- `.tablet-pc-max:w-75` - Ширина 75 % на планшетном ПК (макс.)
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

##### Width - Pc Max (≤ 1200px)

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

##### Height - Mobile (≤ 480px)

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
- `.mobile:h-100` - Высота 100 % на мобильном устройстве
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

##### Height - Tv (≥ 1200px)

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

##### Height - Tablet Max (≤ 768px)

- `.hover:tablet-max:h-100` - Высота 100 % при наведении на планшет (максимум)
- `.hover:tablet-max:h-95` - Высота 95% при наведении на планшет макс.
- `.hover:tablet-max:h-90` - Высота 90% при наведении на планшете макс.
- `.hover:tablet-max:h-85` - Высота 85% при наведении на планшет макс.
- `.hover:tablet-max:h-80` - Высота 80% при наведении на планшет макс.
- `.hover:tablet-max:h-75` - Высота 75% при наведении на планшет макс.
- `.hover:tablet-max:h-70` - Высота 70% при наведении на планшет макс.
- `.hover:tablet-max:h-65` - Высота 65% при наведении на планшет макс.
- `.hover:tablet-max:h-60` - Высота 60% при наведении на планшет макс.
- `.hover:tablet-max:h-55` - Высота 55% при наведении на планшет макс.
- `.hover:tablet-max:h-50` - Высота 50 % при наведении на планшет (максимум)
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

##### Height - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:h-100` - Высота 100% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-95` - Высота 95% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-90` - Высота 90% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-85` - Высота 85% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-80` - Высота 80% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-75` - Высота 75% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-70` - Высота 70% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-65` - Высота 65% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-60` - Высота 60% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-55` - Высота 55 % при наведении на планшетный ПК (максимум)
- `.hover:tablet-pc-max:h-50` - Высота 50% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-45` - Высота 45% при наведении на планшетный ПК макс.
- `.hover:tablet-pc-max:h-40` - Высота 40% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-35` - Высота 35% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-30` - Высота 30% при наведении на планшетный ПК максимум
- `.hover:tablet-pc-max:h-25` - Высота 25 % при наведении на планшетный ПК (макс.)
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

##### Height - Pc Max (≤ 1200px)

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

- `.hover:top-100` - Топ-100% при наведении
- `.hover:top-75` - Топ 75% при наведении
- `.hover:top-50` - Топ-50% при наведении
- `.hover:top-25` - Топ-25% при наведении
- `.hover:top-5` - Топ-5рем при наведении
- `.hover:top-4.5` - Топ 0rem при наведении
- `.hover:top-4` - Топ 4рем при наведении
- `.hover:top-3.5` - Топ 0rem при наведении
- `.hover:top-3` - Топ-3рем при наведении
- `.hover:top-2.5` - Топ 0rem при наведении
- `.hover:top-2` - Топ 2рем при наведении
- `.hover:top-1.9` - Топ 0rem при наведении
- `.hover:top-1.8` - Топ 0rem при наведении
- `.hover:top-1.7` - Топ 0rem при наведении
- `.hover:top-1.6` - Топ 0rem при наведении
- `.hover:top-1.5` - Топ 0rem при наведении
- `.hover:top-1.4` - Топ 0rem при наведении
- `.hover:top-1.3` - Топ 0rem при наведении
- `.hover:top-1.2` - Топ 0rem при наведении
- `.hover:top-1.1` - Топ 0rem при наведении
- `.hover:top-1` - Топ 1рем при наведении
- `.hover:top-0.9` - Топ 0rem при наведении
- `.hover:top-0.8` - Топ 0rem при наведении
- `.hover:top-0.7` - Топ 0rem при наведении
- `.hover:top-0.6` - Топ 0rem при наведении
- `.hover:top-0.5` - Топ 0rem при наведении
- `.hover:top-0.4` - Топ 0rem при наведении
- `.hover:top-0.3` - Топ 0rem при наведении
- `.hover:top-0.2` - Топ 0,2рем при наведении
- `.hover:top-0.1` - Топ 0,1рем при наведении
- `.hover:top-0` - Топ 0rem при наведении
- `.top-100` - Топ 100%
- `.top-75` - Топ 75%
- `.top-50` - Топ 50%
- `.top-25` - Топ 25%
- `.top-5` - Топ 5рем
- `.top-4.5` - Топ 0рем
- `.top-4` - Топ 4рем
- `.top-3.5` - Топ 0рем
- `.top-3` - Топ 3рем
- `.top-2.5` - Топ 0рем
- `.top-2` - Топ 2рем
- `.top-1.9` - Топ 0рем
- `.top-1.8` - Топ 0рем
- `.top-1.7` - Топ 0рем
- `.top-1.6` - Топ 0рем
- `.top-1.5` - Топ 0рем
- `.top-1.4` - Топ 0рем
- `.top-1.3` - Топ 0рем
- `.top-1.2` - Топ 0рем
- `.top-1.1` - Топ 0рем
- `.top-1` - Топ 1рем
- `.top-0.9` - Топ 0рем
- `.top-0.8` - Топ 0рем
- `.top-0.7` - Топ 0рем
- `.top-0.6` - Топ 0рем
- `.top-0.5` - Топ 0рем
- `.top-0.4` - Топ 0рем
- `.top-0.3` - Топ 0рем
- `.top-0.2` - Топ 0,2рем
- `.top-0.1` - Топ 0.1бэр
- `.top-0` - Топ 0рем

##### Negative Top

- `.-top-5` - Отрицательный топ-5рем
- `.-top-4.5` - Отрицательный топ 0рем
- `.-top-4` - Отрицательный Топ 4рем
- `.-top-3.5` - Отрицательный топ 0рем
- `.-top-3` - Отрицательный топ-3рем
- `.-top-2.5` - Отрицательный топ 0рем
- `.-top-2` - Отрицательный топ 2рем
- `.-top-1.9` - Отрицательный топ 0рем
- `.-top-1.8` - Отрицательный топ 0рем
- `.-top-1.7` - Отрицательный топ 0рем
- `.-top-1.6` - Отрицательный топ 0рем
- `.-top-1.5` - Отрицательный топ 0рем
- `.-top-1.4` - Отрицательный топ 0рем
- `.-top-1.3` - Отрицательный топ 0рем
- `.-top-1.2` - Отрицательный топ 0рем
- `.-top-1.1` - Отрицательный топ 0рем
- `.-top-1` - Отрицательный топ 1рем
- `.-top-0.9` - Отрицательный топ 0рем
- `.-top-0.8` - Отрицательный топ 0рем
- `.-top-0.7` - Отрицательный топ 0рем
- `.-top-0.6` - Отрицательный топ 0рем
- `.-top-0.5` - Отрицательный топ 0рем
- `.-top-0.4` - Отрицательный топ 0рем
- `.-top-0.3` - Отрицательный топ 0,3рем
- `.-top-0.2` - Отрицательный топ 0,2рем
- `.-top-0.1` - Отрицательный топ 0,1бэр
- `.hover:-top-5` - Отрицательный топ-5рем при наведении
- `.hover:-top-4.5` - Отрицательный Top 0rem при наведении
- `.hover:-top-4` - Отрицательный Top 4rem при наведении
- `.hover:-top-3.5` - Отрицательный Top 0rem при наведении
- `.hover:-top-3` - Отрицательный результат Top 3rem при наведении
- `.hover:-top-2.5` - Отрицательный Top 0rem при наведении
- `.hover:-top-2` - Отрицательный Top 2rem при наведении
- `.hover:-top-1.9` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.8` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.7` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.6` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.5` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.4` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.3` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.2` - Отрицательный Top 0rem при наведении
- `.hover:-top-1.1` - Отрицательный Top 0rem при наведении
- `.hover:-top-1` - Отрицательный результат Top 1rem при наведении
- `.hover:-top-0.9` - Отрицательный Top 0rem при наведении
- `.hover:-top-0.8` - Отрицательный Top 0rem при наведении
- `.hover:-top-0.7` - Отрицательный Top 0rem при наведении
- `.hover:-top-0.6` - Отрицательный Top 0rem при наведении
- `.hover:-top-0.5` - Отрицательный Top 0rem при наведении
- `.hover:-top-0.4` - Отрицательный Top 0rem при наведении
- `.hover:-top-0.3` - Отрицательный верхний предел 0,3рем при наведении
- `.hover:-top-0.2` - Отрицательный верхний предел 0,2 рем при наведении
- `.hover:-top-0.1` - Отрицательный верхний предел 0,1 рем при наведении

### Right

- `.hover:right-100` - Правые 100% при наведении
- `.hover:right-75` - Правый 75% при наведении
- `.hover:right-50` - Правый 50% при наведении
- `.hover:right-25` - Правый 25% при наведении
- `.hover:right-5` - Правая 5рем при наведении
- `.hover:right-4.5` - Правый 0rem при наведении
- `.hover:right-4` - Правый 4рем при наведении
- `.hover:right-3.5` - Правый 0rem при наведении
- `.hover:right-3` - Правая 3рем при наведении
- `.hover:right-2.5` - Правый 0rem при наведении
- `.hover:right-2` - Вправо 2рем при наведении
- `.hover:right-1.9` - Правый 0rem при наведении
- `.hover:right-1.8` - Правый 0rem при наведении
- `.hover:right-1.7` - Правый 0rem при наведении
- `.hover:right-1.6` - Правый 0rem при наведении
- `.hover:right-1.5` - Правый 0rem при наведении
- `.hover:right-1.4` - Правый 0rem при наведении
- `.hover:right-1.3` - Правый 0rem при наведении
- `.hover:right-1.2` - Правый 0rem при наведении
- `.hover:right-1.1` - Правый 0rem при наведении
- `.hover:right-1` - Вправо 1рем при наведении
- `.hover:right-0.9` - Правый 0rem при наведении
- `.hover:right-0.8` - Правый 0rem при наведении
- `.hover:right-0.7` - Правый 0rem при наведении
- `.hover:right-0.6` - Правый 0rem при наведении
- `.hover:right-0.5` - Правый 0rem при наведении
- `.hover:right-0.4` - Правый 0rem при наведении
- `.hover:right-0.3` - Правый 0rem при наведении
- `.hover:right-0.2` - Вправо 0,2рем при наведении
- `.hover:right-0.1` - Вправо 0,1рем при наведении
- `.hover:right-0` - Правый 0rem при наведении
- `.right-100` - Правый 100%
- `.right-75` - Правый 75%
- `.right-50` - Правый 50%
- `.right-25` - Правый 25%
- `.right-5` - Правый 5рем
- `.right-4.5` - Право 0рем
- `.right-4` - Правый 4рем
- `.right-3.5` - Право 0рем
- `.right-3` - Правый 3рем
- `.right-2.5` - Право 0рем
- `.right-2` - Правый 2рем
- `.right-1.9` - Право 0рем
- `.right-1.8` - Право 0рем
- `.right-1.7` - Право 0рем
- `.right-1.6` - Право 0рем
- `.right-1.5` - Право 0рем
- `.right-1.4` - Право 0рем
- `.right-1.3` - Право 0рем
- `.right-1.2` - Право 0рем
- `.right-1.1` - Право 0рем
- `.right-1` - Правый 1рем
- `.right-0.9` - Право 0рем
- `.right-0.8` - Право 0рем
- `.right-0.7` - Право 0рем
- `.right-0.6` - Право 0рем
- `.right-0.5` - Право 0рем
- `.right-0.4` - Право 0рем
- `.right-0.3` - Право 0рем
- `.right-0.2` - Правый 0,2рем
- `.right-0.1` - Правый 0,1бэр
- `.right-0` - Право 0рем

##### Negative Right

- `.-right-5` - Отрицательный правый 5рем
- `.-right-4.5` - Отрицательный правый 0рем
- `.-right-4` - Отрицательный правый 4рем
- `.-right-3.5` - Отрицательный правый 0рем
- `.-right-3` - Отрицательный правый 3рем
- `.-right-2.5` - Отрицательный правый 0рем
- `.-right-2` - Отрицательный правый 2рем
- `.-right-1.9` - Отрицательный правый 0рем
- `.-right-1.8` - Отрицательный правый 0рем
- `.-right-1.7` - Отрицательный правый 0рем
- `.-right-1.6` - Отрицательный правый 0рем
- `.-right-1.5` - Отрицательный правый 0рем
- `.-right-1.4` - Отрицательный правый 0рем
- `.-right-1.3` - Отрицательный правый 0рем
- `.-right-1.2` - Отрицательный правый 0рем
- `.-right-1.1` - Отрицательный правый 0рем
- `.-right-1` - Отрицательный правый 1рем
- `.-right-0.9` - Отрицательный правый 0рем
- `.-right-0.8` - Отрицательный правый 0рем
- `.-right-0.7` - Отрицательный правый 0рем
- `.-right-0.6` - Отрицательный правый 0рем
- `.-right-0.5` - Отрицательный правый 0рем
- `.-right-0.4` - Отрицательный правый 0рем
- `.-right-0.3` - Отрицательный правый 0,3рем
- `.-right-0.2` - Отрицательный правый 0,2бэр
- `.-right-0.1` - Отрицательный правый 0,1бэр
- `.hover:-right-5` - Отрицательное правое 5рем при наведении
- `.hover:-right-4.5` - Отрицательное правое 0rem при наведении
- `.hover:-right-4` - Отрицательный правый 4rem при наведении
- `.hover:-right-3.5` - Отрицательное правое 0rem при наведении
- `.hover:-right-3` - Отрицательный правый 3рем при наведении
- `.hover:-right-2.5` - Отрицательное правое 0rem при наведении
- `.hover:-right-2` - Отрицательное право 2rem при наведении
- `.hover:-right-1.9` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.8` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.7` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.6` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.5` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.4` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.3` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.2` - Отрицательное правое 0rem при наведении
- `.hover:-right-1.1` - Отрицательное правое 0rem при наведении
- `.hover:-right-1` - Отрицательный правый 1рем при наведении
- `.hover:-right-0.9` - Отрицательное правое 0rem при наведении
- `.hover:-right-0.8` - Отрицательное правое 0rem при наведении
- `.hover:-right-0.7` - Отрицательное правое 0rem при наведении
- `.hover:-right-0.6` - Отрицательное правое 0rem при наведении
- `.hover:-right-0.5` - Отрицательное правое 0rem при наведении
- `.hover:-right-0.4` - Отрицательное правое 0rem при наведении
- `.hover:-right-0.3` - Отрицательный правый 0,3рем при наведении
- `.hover:-right-0.2` - Отрицательный правый 0,2рем при наведении
- `.hover:-right-0.1` - Отрицательный правый 0,1рем при наведении

### Bottom

- `.bottom-100` - Низ 100%
- `.bottom-75` - Низ 75%
- `.bottom-50` - Нижний 50%
- `.bottom-25` - Низ 25%
- `.bottom-5` - Нижний 5рем
- `.bottom-4.5` - Нижний 0рем
- `.bottom-4` - Нижний 4рем
- `.bottom-3.5` - Нижний 0рем
- `.bottom-3` - Нижний 3рем
- `.bottom-2.5` - Нижний 0рем
- `.bottom-2` - Нижний 2рем
- `.bottom-1.9` - Нижний 0рем
- `.bottom-1.8` - Нижний 0рем
- `.bottom-1.7` - Нижний 0рем
- `.bottom-1.6` - Нижний 0рем
- `.bottom-1.5` - Нижний 0рем
- `.bottom-1.4` - Нижний 0рем
- `.bottom-1.3` - Нижний 0рем
- `.bottom-1.2` - Нижний 0рем
- `.bottom-1.1` - Нижний 0рем
- `.bottom-1` - Нижний 1рем
- `.bottom-0.9` - Нижний 0рем
- `.bottom-0.8` - Нижний 0рем
- `.bottom-0.7` - Нижний 0рем
- `.bottom-0.6` - Нижний 0рем
- `.bottom-0.5` - Нижний 0рем
- `.bottom-0.4` - Нижний 0рем
- `.bottom-0.3` - Нижний 0рем
- `.bottom-0.2` - Низ 0,2рем
- `.bottom-0.1` - Низ 0,1бэр
- `.bottom-0` - Нижний 0рем
- `.hover:bottom-100` - Нижние 100% при наведении
- `.hover:bottom-75` - Нижняя 75% при наведении
- `.hover:bottom-50` - Нижние 50% при наведении
- `.hover:bottom-25` - Нижние 25% при наведении
- `.hover:bottom-5` - Нижние 5рем при наведении
- `.hover:bottom-4.5` - Нижний 0рем при наведении
- `.hover:bottom-4` - Нижний 4rem при наведении
- `.hover:bottom-3.5` - Нижний 0рем при наведении
- `.hover:bottom-3` - Нижние 3рем при наведении
- `.hover:bottom-2.5` - Нижний 0рем при наведении
- `.hover:bottom-2` - Нижние 2рем при наведении
- `.hover:bottom-1.9` - Нижний 0рем при наведении
- `.hover:bottom-1.8` - Нижний 0рем при наведении
- `.hover:bottom-1.7` - Нижний 0рем при наведении
- `.hover:bottom-1.6` - Нижний 0рем при наведении
- `.hover:bottom-1.5` - Нижний 0рем при наведении
- `.hover:bottom-1.4` - Нижний 0рем при наведении
- `.hover:bottom-1.3` - Нижний 0рем при наведении
- `.hover:bottom-1.2` - Нижний 0рем при наведении
- `.hover:bottom-1.1` - Нижний 0рем при наведении
- `.hover:bottom-1` - Нижний 1рем при наведении
- `.hover:bottom-0.9` - Нижний 0рем при наведении
- `.hover:bottom-0.8` - Нижний 0рем при наведении
- `.hover:bottom-0.7` - Нижний 0рем при наведении
- `.hover:bottom-0.6` - Нижний 0рем при наведении
- `.hover:bottom-0.5` - Нижний 0рем при наведении
- `.hover:bottom-0.4` - Нижний 0рем при наведении
- `.hover:bottom-0.3` - Нижний 0рем при наведении
- `.hover:bottom-0.2` - Внизу 0,2 рем при наведении
- `.hover:bottom-0.1` - Внизу 0,1 рем при наведении
- `.hover:bottom-0` - Нижний 0рем при наведении

##### Negative Bottom

- `.-bottom-5` - Отрицательное дно 5рем
- `.-bottom-4.5` - Отрицательное дно 0рем
- `.-bottom-4` - Отрицательное дно 4рем
- `.-bottom-3.5` - Отрицательное дно 0рем
- `.-bottom-3` - Отрицательное дно 3рем
- `.-bottom-2.5` - Отрицательное дно 0рем
- `.-bottom-2` - Отрицательное дно 2рем
- `.-bottom-1.9` - Отрицательное дно 0рем
- `.-bottom-1.8` - Отрицательное дно 0рем
- `.-bottom-1.7` - Отрицательное дно 0рем
- `.-bottom-1.6` - Отрицательное дно 0рем
- `.-bottom-1.5` - Отрицательное дно 0рем
- `.-bottom-1.4` - Отрицательное дно 0рем
- `.-bottom-1.3` - Отрицательное дно 0рем
- `.-bottom-1.2` - Отрицательное дно 0рем
- `.-bottom-1.1` - Отрицательное дно 0рем
- `.-bottom-1` - Отрицательное дно 1рем
- `.-bottom-0.9` - Отрицательное дно 0рем
- `.-bottom-0.8` - Отрицательное дно 0рем
- `.-bottom-0.7` - Отрицательное дно 0рем
- `.-bottom-0.6` - Отрицательное дно 0рем
- `.-bottom-0.5` - Отрицательное дно 0рем
- `.-bottom-0.4` - Отрицательное дно 0рем
- `.-bottom-0.3` - Отрицательное дно 0,3 бэр
- `.-bottom-0.2` - Отрицательное дно 0,2 бэр
- `.-bottom-0.1` - Отрицательное дно 0,1 бэр
- `.hover:-bottom-5` - Отрицательное нижнее 5рем при наведении
- `.hover:-bottom-4.5` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-4` - Отрицательный нижний 4rem при наведении
- `.hover:-bottom-3.5` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-3` - Отрицательное нижнее 3рем при наведении
- `.hover:-bottom-2.5` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-2` - Отрицательное нижнее 2рем при наведении
- `.hover:-bottom-1.9` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.8` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.7` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.6` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.5` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.4` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.3` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.2` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1.1` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-1` - Отрицательный нижний 1рем при наведении
- `.hover:-bottom-0.9` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-0.8` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-0.7` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-0.6` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-0.5` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-0.4` - Отрицательное нижнее значение 0rem при наведении
- `.hover:-bottom-0.3` - Отрицательное дно 0,3рем при наведении
- `.hover:-bottom-0.2` - Отрицательное дно 0,2рем при наведении
- `.hover:-bottom-0.1` - Отрицательное дно 0,1 бэр при наведении

### Left

- `.hover:left-100` - Осталось 100% при наведении
- `.hover:left-75` - Осталось 75% при наведении
- `.hover:left-50` - Осталось 50% при наведении
- `.hover:left-25` - Осталось 25% при наведении
- `.hover:left-5` - Осталось 5рем при наведении
- `.hover:left-4.5` - Осталось 0рем при наведении
- `.hover:left-4` - Осталось 4рем при наведении
- `.hover:left-3.5` - Осталось 0рем при наведении
- `.hover:left-3` - Оставил 3рем при наведении
- `.hover:left-2.5` - Осталось 0рем при наведении
- `.hover:left-2` - Осталось 2рем при наведении
- `.hover:left-1.9` - Осталось 0рем при наведении
- `.hover:left-1.8` - Осталось 0рем при наведении
- `.hover:left-1.7` - Осталось 0рем при наведении
- `.hover:left-1.6` - Осталось 0рем при наведении
- `.hover:left-1.5` - Осталось 0рем при наведении
- `.hover:left-1.4` - Осталось 0рем при наведении
- `.hover:left-1.3` - Осталось 0рем при наведении
- `.hover:left-1.2` - Осталось 0рем при наведении
- `.hover:left-1.1` - Осталось 0рем при наведении
- `.hover:left-1` - Осталось 1рем при наведении
- `.hover:left-0.9` - Осталось 0рем при наведении
- `.hover:left-0.8` - Осталось 0рем при наведении
- `.hover:left-0.7` - Осталось 0рем при наведении
- `.hover:left-0.6` - Осталось 0рем при наведении
- `.hover:left-0.5` - Осталось 0рем при наведении
- `.hover:left-0.4` - Осталось 0рем при наведении
- `.hover:left-0.3` - Осталось 0рем при наведении
- `.hover:left-0.2` - Осталось 0,2рем при наведении
- `.hover:left-0.1` - Осталось 0,1 рем при наведении
- `.hover:left-0` - Осталось 0рем при наведении
- `.left-100` - Осталось 100%
- `.left-75` - Осталось 75%
- `.left-50` - Осталось 50%
- `.left-25` - Осталось 25%
- `.left-5` - Левый 5рем
- `.left-4.5` - Осталось 0рем
- `.left-4` - Левый 4рем
- `.left-3.5` - Осталось 0рем
- `.left-3` - Левый 3рем
- `.left-2.5` - Осталось 0рем
- `.left-2` - Осталось 2рем
- `.left-1.9` - Осталось 0рем
- `.left-1.8` - Осталось 0рем
- `.left-1.7` - Осталось 0рем
- `.left-1.6` - Осталось 0рем
- `.left-1.5` - Осталось 0рем
- `.left-1.4` - Осталось 0рем
- `.left-1.3` - Осталось 0рем
- `.left-1.2` - Осталось 0рем
- `.left-1.1` - Осталось 0рем
- `.left-1` - Осталось 1рем
- `.left-0.9` - Осталось 0рем
- `.left-0.8` - Осталось 0рем
- `.left-0.7` - Осталось 0рем
- `.left-0.6` - Осталось 0рем
- `.left-0.5` - Осталось 0рем
- `.left-0.4` - Осталось 0рем
- `.left-0.3` - Осталось 0рем
- `.left-0.2` - Левый 0,2рем
- `.left-0.1` - Осталось 0,1 бэр
- `.left-0` - Осталось 0рем

##### Negative Left

- `.-left-5` - Отрицательный левый 5рем
- `.-left-4.5` - Отрицательный левый 0рем
- `.-left-4` - Отрицательный левый 4рем
- `.-left-3.5` - Отрицательный левый 0рем
- `.-left-3` - Отрицательный левый 3рем
- `.-left-2.5` - Отрицательный левый 0рем
- `.-left-2` - Отрицательный левый 2рем
- `.-left-1.9` - Отрицательный левый 0рем
- `.-left-1.8` - Отрицательный левый 0рем
- `.-left-1.7` - Отрицательный левый 0рем
- `.-left-1.6` - Отрицательный левый 0рем
- `.-left-1.5` - Отрицательный левый 0рем
- `.-left-1.4` - Отрицательный левый 0рем
- `.-left-1.3` - Отрицательный левый 0рем
- `.-left-1.2` - Отрицательный левый 0рем
- `.-left-1.1` - Отрицательный левый 0рем
- `.-left-1` - Отрицательный левый 1рем
- `.-left-0.9` - Отрицательный левый 0рем
- `.-left-0.8` - Отрицательный левый 0рем
- `.-left-0.7` - Отрицательный левый 0рем
- `.-left-0.6` - Отрицательный левый 0рем
- `.-left-0.5` - Отрицательный левый 0рем
- `.-left-0.4` - Отрицательный левый 0рем
- `.-left-0.3` - Отрицательный левый 0,3рем
- `.-left-0.2` - Отрицательный левый 0,2бэр
- `.-left-0.1` - Отрицательный левый 0,1бэр
- `.hover:-left-5` - Отрицательное левое 5рем при наведении
- `.hover:-left-4.5` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-4` - Отрицательный левый 4rem при наведении
- `.hover:-left-3.5` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-3` - Отрицательный левый 3рем при наведении
- `.hover:-left-2.5` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-2` - Отрицательное значение Left 2rem при наведении
- `.hover:-left-1.9` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.8` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.7` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.6` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.5` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.4` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.3` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.2` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1.1` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-1` - Отрицательный левый 1рем при наведении
- `.hover:-left-0.9` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-0.8` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-0.7` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-0.6` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-0.5` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-0.4` - Отрицательное значение Left 0rem при наведении
- `.hover:-left-0.3` - Отрицательный левый 0,3рем при наведении
- `.hover:-left-0.2` - Отрицательный левый 0,2рем при наведении
- `.hover:-left-0.1` - Отрицательный левый 0,1рем при наведении

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

- `.font-size-10` - Размер шрифта 10рем
- `.font-size-9.5` - Размер шрифта 0рем
- `.font-size-9` - Размер шрифта 9рем
- `.font-size-8.5` - Размер шрифта 0рем
- `.font-size-8` - Размер шрифта 8рем
- `.font-size-7.5` - Размер шрифта 0рем
- `.font-size-7` - Размер шрифта 7рем
- `.font-size-6.5` - Размер шрифта 0рем
- `.font-size-6` - Размер шрифта 6рем
- `.font-size-5.5` - Размер шрифта 0рем
- `.font-size-5` - Размер шрифта 5рем
- `.font-size-4.5` - Размер шрифта 0рем
- `.font-size-4` - Размер шрифта 4рем
- `.font-size-3.5` - Размер шрифта 0рем
- `.font-size-3` - Размер шрифта 3rem
- `.font-size-2.5` - Размер шрифта 0рем
- `.font-size-2` - Размер шрифта 2рем
- `.font-size-1.9` - Размер шрифта 0рем
- `.font-size-1.8` - Размер шрифта 0рем
- `.font-size-1.7` - Размер шрифта 0рем
- `.font-size-1.6` - Размер шрифта 0рем
- `.font-size-1.5` - Размер шрифта 0рем
- `.font-size-1.4` - Размер шрифта 0рем
- `.font-size-1.3` - Размер шрифта 0рем
- `.font-size-1.2` - Размер шрифта 0рем
- `.font-size-1.1` - Размер шрифта 0рем
- `.font-size-1` - Размер шрифта 1рем
- `.font-size-0.9` - Размер шрифта 0рем
- `.font-size-0.8` - Размер шрифта 0рем
- `.font-size-0.7` - Размер шрифта 0,7 рем.
- `.font-size-0.6` - Размер шрифта 0,6 рем.
- `.font-size-0.5` - Размер шрифта 0,5 рем.
- `.hover:font-size-10` - Размер шрифта 10рем при наведении
- `.hover:font-size-9.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-9` - Размер шрифта 9rem при наведении
- `.hover:font-size-8.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-8` - Размер шрифта 8rem при наведении
- `.hover:font-size-7.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-7` - Размер шрифта 7rem при наведении
- `.hover:font-size-6.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-6` - Размер шрифта 6rem при наведении
- `.hover:font-size-5.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-5` - Размер шрифта 5rem при наведении
- `.hover:font-size-4.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-4` - Размер шрифта 4rem при наведении
- `.hover:font-size-3.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-3` - Размер шрифта 3rem при наведении
- `.hover:font-size-2.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-2` - Размер шрифта 2rem при наведении
- `.hover:font-size-1.9` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.8` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.7` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.6` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.5` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.4` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.3` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.2` - Размер шрифта 0рем при наведении
- `.hover:font-size-1.1` - Размер шрифта 0рем при наведении
- `.hover:font-size-1` - Размер шрифта 1rem при наведении
- `.hover:font-size-0.9` - Размер шрифта 0рем при наведении
- `.hover:font-size-0.8` - Размер шрифта 0рем при наведении
- `.hover:font-size-0.7` - Размер шрифта 0,7 рем при наведении
- `.hover:font-size-0.6` - Размер шрифта 0.6rem при наведении
- `.hover:font-size-0.5` - Размер шрифта 0,5 рем при наведении

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

- `.hover:letter-spacing-1` - Расстояние между буквами 1рем при наведении
- `.hover:letter-spacing-0.9` - Расстояние между буквами 0рем при наведении
- `.hover:letter-spacing-0.8` - Расстояние между буквами 0рем при наведении
- `.hover:letter-spacing-0.7` - Расстояние между буквами 0рем при наведении
- `.hover:letter-spacing-0.6` - Расстояние между буквами 0рем при наведении
- `.hover:letter-spacing-0.5` - Расстояние между буквами 0рем при наведении
- `.hover:letter-spacing-0.4` - Расстояние между буквами 0рем при наведении
- `.hover:letter-spacing-0.3` - Расстояние между буквами 0,3 рем при наведении
- `.hover:letter-spacing-0.2` - Расстояние между буквами 0,2 рем при наведении
- `.hover:letter-spacing-0.1` - Расстояние между буквами 0,1 рем при наведении
- `.letter-spacing-1` - Расстояние между буквами 1рем
- `.letter-spacing-0.9` - Расстояние между буквами 0рем
- `.letter-spacing-0.8` - Расстояние между буквами 0рем
- `.letter-spacing-0.7` - Расстояние между буквами 0рем
- `.letter-spacing-0.6` - Расстояние между буквами 0рем
- `.letter-spacing-0.5` - Расстояние между буквами 0рем
- `.letter-spacing-0.4` - Расстояние между буквами 0рем
- `.letter-spacing-0.3` - Расстояние между буквами 0,3 рем.
- `.letter-spacing-0.2` - Расстояние между буквами 0,2 рем.
- `.letter-spacing-0.1` - Расстояние между буквами 0,1 рем.

### Line height

- `.hover:line-height-5` - Высота строки 5rem при наведении
- `.hover:line-height-4` - Высота строки 4rem при наведении
- `.hover:line-height-3` - Высота строки 3rem при наведении
- `.hover:line-height-2` - Высота строки 2rem при наведении
- `.hover:line-height-1` - Высота строки 1rem при наведении
- `.line-height-5` - Высота строки 5рем
- `.line-height-4` - Высота строки 4рем
- `.line-height-3` - Высота строки 3рем
- `.line-height-2` - Высота строки 2рем
- `.line-height-1` - Высота строки 1рем

### Text

- `.hover:text-capitalize` - Текст с заглавной буквы при наведении
- `.hover:text-center` - Текстовый центр при наведении
- `.hover:text-end` - Конец текста при наведении
- `.hover:text-justify` - Выравнивание текста при наведении
- `.hover:text-left` - Текст, оставленный при наведении
- `.hover:text-line-none` - Текстовая строка-нет при наведении
- `.hover:text-line-overline` - Текстовая строка перечеркивается при наведении
- `.hover:text-line-through` - Перечеркивание текста при наведении
- `.hover:text-line-underline` - Подчеркивание строки текста при наведении
- `.hover:text-lowercase` - Текст строчный при наведении
- `.hover:text-right` - Текст прямо при наведении
- `.hover:text-start` - Начало текста при наведении
- `.hover:text-transparent` - Текст прозрачный при наведении
- `.hover:text-uppercase` - Текст в верхнем регистре при наведении
- `.text-break-all` - Текстовый разрыв
- `.text-break-keep-all` - Разрыв текста с сохранением всего
- `.text-break-normal` - Разрыв текста - нормальный
- `.text-break-word` - Текстовое слово-разрыв
- `.text-capitalize` - Текст с заглавной буквы
- `.text-center` - Текстовый центр
- `.text-end` - Конец текста
- `.text-justify` - Выравнивание текста
- `.text-left` - Текст слева
- `.text-line-none` - Текстовая строка-нет
- `.text-line-overline` - Текстовая строка-перечеркнутая
- `.text-line-through` - Сквозной текст
- `.text-line-underline` - Текстовая строка-подчеркивание
- `.text-lowercase` - Текст строчный
- `.text-overflow-clip` - Клип переполнения текста
- `.text-overflow-ellipsis` - Переполнение текста-многоточие
- `.text-right` - Текст справа
- `.text-start` - Начало текста
- `.text-transparent` - Текст прозрачный
- `.text-uppercase` - Текст в верхнем регистре

##### Text - Mobile (≤ 480px)

- `.hover:mobile:text-center` - Текстовый центр при наведении на мобильном телефоне
- `.hover:mobile:text-end` - Завершение текста при наведении на мобильном телефоне
- `.hover:mobile:text-justify` - Выравнивание текста при наведении на мобильном телефоне
- `.hover:mobile:text-left` - Текст, оставленный при наведении на мобильном телефоне
- `.hover:mobile:text-right` - Текст прямо при наведении на мобильном телефоне
- `.hover:mobile:text-start` - Начало текста при наведении на мобильном телефоне
- `.mobile:text-center` - Текстовый центр на мобильном телефоне
- `.mobile:text-end` - Конец текста на мобильном телефоне
- `.mobile:text-justify` - Выравнивание текста на мобильном телефоне
- `.mobile:text-left` - Текст остался на мобильном телефоне
- `.mobile:text-right` - Текст прямо на мобильном телефоне
- `.mobile:text-start` - Начало текста на мобильном телефоне

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - Текстовый центр при наведении на планшет
- `.hover:tablet:text-end` - Завершение текста при наведении на планшет
- `.hover:tablet:text-justify` - Выравнивание текста при наведении на планшет
- `.hover:tablet:text-left` - Текст, оставленный при наведении на планшет
- `.hover:tablet:text-right` - Текст прямо при наведении на планшете
- `.hover:tablet:text-start` - Начало текста при наведении на планшете
- `.tablet:text-center` - Текстовый центр на планшете
- `.tablet:text-end` - Конец текста на планшете
- `.tablet:text-justify` - Выравнивание текста на планшете
- `.tablet:text-left` - Текст остался на планшете
- `.tablet:text-right` - Текст прямо на планшете
- `.tablet:text-start` - Начало текста на планшете

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - Текстовый центр при наведении на планшетном ПК
- `.hover:tablet-pc:text-end` - Завершение текста при наведении на планшетном ПК
- `.hover:tablet-pc:text-justify` - Выравнивание текста при наведении на планшетном ПК
- `.hover:tablet-pc:text-left` - Текст, оставленный при наведении курсора на планшетном ПК
- `.hover:tablet-pc:text-right` - Текст прямо при наведении на планшетном ПК
- `.hover:tablet-pc:text-start` - Начало текста при наведении на планшетном ПК
- `.tablet-pc:text-center` - Текстовый центр на планшетном ПК
- `.tablet-pc:text-end` - Конец текста на планшетном ПК
- `.tablet-pc:text-justify` - Выравнивание текста на планшетном ПК
- `.tablet-pc:text-left` - Текст остался на планшетном компьютере
- `.tablet-pc:text-right` - Текст прямо на планшетном компьютере
- `.tablet-pc:text-start` - Начало текста на планшетном ПК

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - Текстовый центр при наведении на ПК
- `.hover:pc:text-end` - Завершение текста при наведении на ПК
- `.hover:pc:text-justify` - Выравнивание текста при наведении на ПК
- `.hover:pc:text-left` - Текст, оставленный при наведении на ПК
- `.hover:pc:text-right` - Текст прямо при наведении на ПК
- `.hover:pc:text-start` - Начало текста при наведении на ПК
- `.pc:text-center` - Текстовый центр на ПК
- `.pc:text-end` - Конец текста на ПК
- `.pc:text-justify` - Выравнивание текста на ПК
- `.pc:text-left` - Текст остался на компьютере
- `.pc:text-right` - Текст прямо на компьютере
- `.pc:text-start` - Начало текста на ПК

##### Text - Tv (≥ 1200px)

- `.hover:tv:text-center` - Текстовый центр при наведении на телевизор
- `.hover:tv:text-end` - Конец текста при наведении на телевизор
- `.hover:tv:text-justify` - Выравнивание текста при наведении на телевизор
- `.hover:tv:text-left` - Текст остается при наведении на телевизоре
- `.hover:tv:text-right` - Текст прямо при наведении на телевизор
- `.hover:tv:text-start` - Начало текста при наведении на телевизор
- `.tv:text-center` - Текстовый центр на телевизоре
- `.tv:text-end` - Конец текста на ТВ
- `.tv:text-justify` - Выравнивание текста по телевизору
- `.tv:text-left` - Текст остался на телевизоре
- `.tv:text-right` - Текст прямо на телевизоре
- `.tv:text-start` - Начало текстового сообщения на телевизоре

##### Text - Tablet Max (≤ 768px)

- `.hover:tablet-max:text-center` - Текстовый центр при наведении на планшете Max
- `.hover:tablet-max:text-end` - Завершение текста при наведении на планшете Max
- `.hover:tablet-max:text-justify` - Выравнивание текста при наведении на планшете Max
- `.hover:tablet-max:text-left` - Текст остается при наведении на планшете Max
- `.hover:tablet-max:text-right` - Текст прямо при наведении на планшете Max
- `.hover:tablet-max:text-start` - Начало текста при наведении на планшете Max
- `.tablet-max:text-center` - Текстовый центр на планшете Max
- `.tablet-max:text-end` - Конец текста на планшете Max
- `.tablet-max:text-justify` - Выравнивание текста на планшете Max
- `.tablet-max:text-left` - Текст остался на планшете макс.
- `.tablet-max:text-right` - Текст прямо на планшете Max
- `.tablet-max:text-start` - Начало текста на планшете Max

##### Text - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:text-center` - Текстовый центр при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:text-end` - Конец текста при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:text-justify` - Выравнивание текста при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:text-left` - Текст, оставленный при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:text-right` - Текст прямо при наведении на планшетном ПК Max
- `.hover:tablet-pc-max:text-start` - Начало текста при наведении на планшетном ПК макс.
- `.tablet-pc-max:text-center` - Текстовый центр на планшетном ПК Макс.
- `.tablet-pc-max:text-end` - Конец текста на планшетном ПК макс.
- `.tablet-pc-max:text-justify` - Выравнивание текста на планшетном ПК Max
- `.tablet-pc-max:text-left` - Текст остался на планшетном ПК макс.
- `.tablet-pc-max:text-right` - Текст прямо на планшетном ПК Макс.
- `.tablet-pc-max:text-start` - Начало текста на планшетном ПК Max

##### Text - Pc Max (≤ 1200px)

- `.hover:pc-max:text-center` - Текстовый центр при наведении на ПК макс.
- `.hover:pc-max:text-end` - Завершение текста при наведении на ПК макс.
- `.hover:pc-max:text-justify` - Выравнивание текста при наведении на ПК макс.
- `.hover:pc-max:text-left` - Текст, оставленный при наведении на ПК макс.
- `.hover:pc-max:text-right` - Текст прямо при наведении на ПК макс.
- `.hover:pc-max:text-start` - Начало текста при наведении на ПК макс.
- `.pc-max:text-center` - Текстовый центр на пк макс
- `.pc-max:text-end` - Конец текста на ПК макс.
- `.pc-max:text-justify` - Выравнивание текста на ПК Макс.
- `.pc-max:text-left` - Текст остался на ПК Макс.
- `.pc-max:text-right` - Текст прямо на ПК Макс.
- `.pc-max:text-start` - Начало текста на ПК макс

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

- `.border-2` - Граница Все 2рем
- `.border-1.5` - Граница Все 0рем
- `.border-1` - Граница Все 1рем
- `.border-0.9` - Граница Все 0рем
- `.border-0.8` - Граница Все 0рем
- `.border-0.7` - Граница Все 0рем
- `.border-0.6` - Граница Все 0рем
- `.border-0.5` - Граница Все 0рем
- `.border-0.4` - Граница Все 0,4рем
- `.border-0.3` - Граница Все 0рем
- `.border-0.2` - Граница Все 0,2рем
- `.border-0.1` - Граница Все 0,1рем
- `.border-0` - Граница Все 0рем
- `.hover:border-2` - Граница Все 2рем при наведении
- `.hover:border-1.5` - Граница Все 0rem при наведении
- `.hover:border-1` - Граница Все 1рем при наведении
- `.hover:border-0.9` - Граница Все 0rem при наведении
- `.hover:border-0.8` - Граница Все 0rem при наведении
- `.hover:border-0.7` - Граница Все 0rem при наведении
- `.hover:border-0.6` - Граница Все 0rem при наведении
- `.hover:border-0.5` - Граница Все 0rem при наведении
- `.hover:border-0.4` - Граница Все 0rem при наведении
- `.hover:border-0.3` - Граница Все 0rem при наведении
- `.hover:border-0.2` - Граница Все 0,2рем при наведении
- `.hover:border-0.1` - Граница Все 0,1рем при наведении
- `.hover:border-0` - Граница Все 0rem при наведении

#### Border Bottom

- `.border-b-2` - Граница снизу 2рем
- `.border-b-1.5` - Граница снизу 0рем
- `.border-b-1` - Граница снизу 1рем
- `.border-b-0.9` - Граница снизу 0рем
- `.border-b-0.8` - Граница снизу 0рем
- `.border-b-0.7` - Граница снизу 0рем
- `.border-b-0.6` - Граница снизу 0рем
- `.border-b-0.5` - Граница снизу 0,5рем
- `.border-b-0.4` - Граница снизу 0рем
- `.border-b-0.3` - Граница снизу 0рем
- `.border-b-0.2` - Граница снизу 0.2rem
- `.border-b-0.1` - Граница Низ 0,1рем
- `.border-b-0` - Граница снизу 0рем
- `.hover:border-b-2` - Граница снизу 2rem при наведении
- `.hover:border-b-1.5` - Граница внизу 0rem при наведении
- `.hover:border-b-1` - Граница внизу 1рем при наведении
- `.hover:border-b-0.9` - Граница внизу 0rem при наведении
- `.hover:border-b-0.8` - Граница внизу 0rem при наведении
- `.hover:border-b-0.7` - Граница внизу 0rem при наведении
- `.hover:border-b-0.6` - Граница внизу 0rem при наведении
- `.hover:border-b-0.5` - Граница внизу 0rem при наведении
- `.hover:border-b-0.4` - Граница внизу 0rem при наведении
- `.hover:border-b-0.3` - Граница внизу 0rem при наведении
- `.hover:border-b-0.2` - Граница внизу 0,2 рем при наведении
- `.hover:border-b-0.1` - Граница внизу 0,1 бэр при наведении
- `.hover:border-b-0` - Граница внизу 0rem при наведении

#### Border Left

- `.border-l-2` - Граница слева 2рем
- `.border-l-1.5` - Граница слева 0рем
- `.border-l-1` - Граница слева 1рем
- `.border-l-0.9` - Граница слева 0рем
- `.border-l-0.8` - Граница слева 0рем
- `.border-l-0.7` - Граница слева 0рем
- `.border-l-0.6` - Граница слева 0рем
- `.border-l-0.5` - Граница слева 0рем
- `.border-l-0.4` - Граница слева 0рем
- `.border-l-0.3` - Граница слева 0рем
- `.border-l-0.2` - Граница слева 0,2рем
- `.border-l-0.1` - Граница слева 0,1рем
- `.border-l-0` - Граница слева 0рем
- `.hover:border-l-2` - Граница слева 2рем при наведении
- `.hover:border-l-1.5` - Граница слева 0rem при наведении
- `.hover:border-l-1` - Граница слева 1рем при наведении
- `.hover:border-l-0.9` - Граница слева 0rem при наведении
- `.hover:border-l-0.8` - Граница слева 0rem при наведении
- `.hover:border-l-0.7` - Граница слева 0rem при наведении
- `.hover:border-l-0.6` - Граница слева 0rem при наведении
- `.hover:border-l-0.5` - Граница слева 0rem при наведении
- `.hover:border-l-0.4` - Граница слева 0rem при наведении
- `.hover:border-l-0.3` - Граница слева 0rem при наведении
- `.hover:border-l-0.2` - Граница слева 0,2 рем при наведении
- `.hover:border-l-0.1` - Граница слева 0,1 рем при наведении
- `.hover:border-l-0` - Граница слева 0rem при наведении

#### Border Right

- `.border-r-2` - Граница правая 2рем
- `.border-r-1.5` - Граница справа 0рем
- `.border-r-1` - Граница справа 1рем
- `.border-r-0.9` - Граница справа 0рем
- `.border-r-0.8` - Граница справа 0рем
- `.border-r-0.7` - Граница справа 0рем
- `.border-r-0.6` - Граница справа 0рем
- `.border-r-0.5` - Граница справа 0рем
- `.border-r-0.4` - Граница справа 0рем
- `.border-r-0.3` - Граница справа 0рем
- `.border-r-0.2` - Граница справа 0,2рем
- `.border-r-0.1` - Граница справа 0.1бэр
- `.border-r-0` - Граница справа 0рем
- `.hover:border-r-2` - Граница справа 2рем при наведении
- `.hover:border-r-1.5` - Граница справа 0rem при наведении
- `.hover:border-r-1` - Граница справа 1рем при наведении
- `.hover:border-r-0.9` - Граница справа 0rem при наведении
- `.hover:border-r-0.8` - Граница справа 0rem при наведении
- `.hover:border-r-0.7` - Граница справа 0rem при наведении
- `.hover:border-r-0.6` - Граница справа 0rem при наведении
- `.hover:border-r-0.5` - Граница справа 0rem при наведении
- `.hover:border-r-0.4` - Граница справа 0rem при наведении
- `.hover:border-r-0.3` - Граница справа 0rem при наведении
- `.hover:border-r-0.2` - Граница справа 0,2 рем при наведении
- `.hover:border-r-0.1` - Граница справа 0,1 рем при наведении
- `.hover:border-r-0` - Граница справа 0rem при наведении

#### Border Top

- `.border-t-2` - Бордер Топ 2рем
- `.border-t-1.5` - Бордюр Топ 0рем
- `.border-t-1` - Бордер Топ 1рем
- `.border-t-0.9` - Бордюр Топ 0рем
- `.border-t-0.8` - Бордюр Топ 0рем
- `.border-t-0.7` - Бордюр Топ 0рем
- `.border-t-0.6` - Бордюр Топ 0рем
- `.border-t-0.5` - Бордюр Топ 0рем
- `.border-t-0.4` - Бордюр Топ 0рем
- `.border-t-0.3` - Бордюр Топ 0рем
- `.border-t-0.2` - Граница Верх 0.2rem
- `.border-t-0.1` - Граница Верх 0,1рем
- `.border-t-0` - Бордюр Топ 0рем
- `.hover:border-t-2` - Граница Top 2rem при наведении
- `.hover:border-t-1.5` - Граница Top 0rem при наведении
- `.hover:border-t-1` - Граница Top 1rem при наведении
- `.hover:border-t-0.9` - Граница Top 0rem при наведении
- `.hover:border-t-0.8` - Граница Top 0rem при наведении
- `.hover:border-t-0.7` - Граница Top 0rem при наведении
- `.hover:border-t-0.6` - Граница Top 0rem при наведении
- `.hover:border-t-0.5` - Граница Top 0rem при наведении
- `.hover:border-t-0.4` - Граница Top 0rem при наведении
- `.hover:border-t-0.3` - Граница Top 0rem при наведении
- `.hover:border-t-0.2` - Граница Верх 0,2рем при наведении
- `.hover:border-t-0.1` - Граница Верх 0,1рем при наведении
- `.hover:border-t-0` - Граница Top 0rem при наведении

#### Border X-Axis

- `.border-x-2` - Граница оси X 2rem
- `.border-x-1.5` - Граница оси X 0rem
- `.border-x-1` - Граница оси X 1рем
- `.border-x-0.9` - Граница оси X 0rem
- `.border-x-0.8` - Граница оси X 0rem
- `.border-x-0.7` - Граница оси X 0rem
- `.border-x-0.6` - Граница оси X 0rem
- `.border-x-0.5` - Граница оси X 0rem
- `.border-x-0.4` - Граница оси X 0rem
- `.border-x-0.3` - Граница оси X 0rem
- `.border-x-0.2` - Граница оси X 0,2 рем.
- `.border-x-0.1` - Граница оси X: 0,1 рем.
- `.border-x-0` - Граница оси X 0rem
- `.hover:border-x-2` - Граница X-Axis 2rem при наведении
- `.hover:border-x-1.5` - Граница оси X 0rem при наведении
- `.hover:border-x-1` - Граница X-Axis 1rem при наведении
- `.hover:border-x-0.9` - Граница оси X 0rem при наведении
- `.hover:border-x-0.8` - Граница оси X 0rem при наведении
- `.hover:border-x-0.7` - Граница оси X 0rem при наведении
- `.hover:border-x-0.6` - Граница оси X 0rem при наведении
- `.hover:border-x-0.5` - Граница оси X 0rem при наведении
- `.hover:border-x-0.4` - Граница оси X 0rem при наведении
- `.hover:border-x-0.3` - Граница оси X 0rem при наведении
- `.hover:border-x-0.2` - Граница оси X 0,2 рем. при наведении
- `.hover:border-x-0.1` - Граница оси X 0,1 рем при наведении
- `.hover:border-x-0` - Граница оси X 0rem при наведении

#### Border Y-Axis

- `.border-y-2` - Граница оси Y 2rem
- `.border-y-1.5` - Граница оси Y 0rem
- `.border-y-1` - Граница оси Y 1рем
- `.border-y-0.9` - Граница оси Y 0rem
- `.border-y-0.8` - Граница оси Y 0rem
- `.border-y-0.7` - Граница оси Y 0rem
- `.border-y-0.6` - Граница оси Y 0rem
- `.border-y-0.5` - Граница оси Y 0,5 рем.
- `.border-y-0.4` - Граница оси Y 0rem
- `.border-y-0.3` - Граница оси Y 0rem
- `.border-y-0.2` - Граница оси Y 0,2 рем.
- `.border-y-0.1` - Граница оси Y: 0,1 рем.
- `.border-y-0` - Граница оси Y 0rem
- `.hover:border-y-2` - Граница оси Y 2rem при наведении
- `.hover:border-y-1.5` - Граница оси Y 0rem при наведении
- `.hover:border-y-1` - Граница оси Y 1 рем при наведении
- `.hover:border-y-0.9` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.8` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.7` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.6` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.5` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.4` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.3` - Граница оси Y 0rem при наведении
- `.hover:border-y-0.2` - Граница оси Y 0,2 рем. при наведении
- `.hover:border-y-0.1` - Граница оси Y 0,1 рем при наведении
- `.hover:border-y-0` - Граница оси Y 0rem при наведении

### Border Radius

#### Border Radius All

- `.hover:rounded-5` - Радиус границы Все 5рем при наведении
- `.hover:rounded-4.5` - Радиус границы Все 0rem при наведении
- `.hover:rounded-4` - Радиус границы Все 4rem при наведении
- `.hover:rounded-3.5` - Радиус границы Все 0rem при наведении
- `.hover:rounded-3` - Радиус границы Все 3rem при наведении
- `.hover:rounded-2.5` - Радиус границы Все 0rem при наведении
- `.hover:rounded-2` - Радиус границы Все 2rem при наведении
- `.hover:rounded-1.5` - Радиус границы Все 0rem при наведении
- `.hover:rounded-1` - Радиус границы Все 1 рем при наведении
- `.hover:rounded-0.9` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.8` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.7` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.6` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.5` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.4` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.3` - Радиус границы Все 0rem при наведении
- `.hover:rounded-0.2` - Радиус границы Все 0,2 рем. при наведении
- `.hover:rounded-0.1` - Радиус границы Все 0,1 бэр при наведении
- `.hover:rounded-0` - Радиус границы Все 0rem при наведении
- `.rounded-5` - Радиус границы Все 5rem
- `.rounded-4.5` - Радиус границы Все 0rem
- `.rounded-4` - Радиус границы Все 4rem
- `.rounded-3.5` - Радиус границы Все 0rem
- `.rounded-3` - Радиус границы Все 3rem
- `.rounded-2.5` - Радиус границы Все 0rem
- `.rounded-2` - Радиус границы Все 2rem
- `.rounded-1.5` - Радиус границы Все 0rem
- `.rounded-1` - Радиус границы Все 1рем
- `.rounded-0.9` - Радиус границы Все 0rem
- `.rounded-0.8` - Радиус границы Все 0rem
- `.rounded-0.7` - Радиус границы Все 0rem
- `.rounded-0.6` - Радиус границы Все 0rem
- `.rounded-0.5` - Радиус границы Все 0rem
- `.rounded-0.4` - Радиус границы Все 0rem
- `.rounded-0.3` - Радиус границы Все 0rem
- `.rounded-0.2` - Радиус границы Все 0.2rem
- `.rounded-0.1` - Радиус границы Все 0,1 бэр
- `.rounded-0` - Радиус границы Все 0rem

#### Border Radius Bottom Left

- `.hover:rounded-bl-5` - Радиус границы внизу слева 5rem при наведении
- `.hover:rounded-bl-4.5` - Радиус границы внизу слева 0rem при наведении
- `.hover:rounded-bl-4` - Радиус границы внизу слева 4rem при наведении
- `.hover:rounded-bl-3.5` - Радиус границы внизу слева 0rem при наведении
- `.hover:rounded-bl-3` - Радиус границы внизу слева 3rem при наведении
- `.hover:rounded-bl-2.5` - Радиус границы внизу слева 0rem при наведении
- `.hover:rounded-bl-2` - Радиус границы внизу слева 2rem при наведении
- `.hover:rounded-bl-1.5` - Радиус границы внизу слева 0rem при наведении
- `.hover:rounded-bl-1` - Радиус границы внизу слева 1rem при наведении
- `.hover:rounded-bl-0.5` - Радиус границы внизу слева 0,5 рем при наведении
- `.hover:rounded-bl-0` - Радиус границы внизу слева 0rem при наведении
- `.rounded-bl-5` - Радиус границы внизу слева 5rem
- `.rounded-bl-4.5` - Радиус границы внизу слева 0rem
- `.rounded-bl-4` - Радиус границы внизу слева 4rem
- `.rounded-bl-3.5` - Радиус границы внизу слева 0rem
- `.rounded-bl-3` - Радиус границы внизу слева 3rem
- `.rounded-bl-2.5` - Радиус границы внизу слева 0rem
- `.rounded-bl-2` - Радиус границы внизу слева 2rem
- `.rounded-bl-1.5` - Радиус границы внизу слева 0rem
- `.rounded-bl-1` - Радиус границы внизу слева 1rem
- `.rounded-bl-0.5` - Радиус границы внизу слева 0.5rem
- `.rounded-bl-0` - Радиус границы внизу слева 0rem

#### Border Radius Bottom Right

- `.hover:rounded-br-5` - Радиус границы внизу справа 5rem при наведении
- `.hover:rounded-br-4.5` - Радиус границы внизу справа 0rem при наведении
- `.hover:rounded-br-4` - Радиус границы внизу справа 4rem при наведении
- `.hover:rounded-br-3.5` - Радиус границы внизу справа 0rem при наведении
- `.hover:rounded-br-3` - Радиус границы внизу справа 3rem при наведении
- `.hover:rounded-br-2.5` - Радиус границы внизу справа 0rem при наведении
- `.hover:rounded-br-2` - Радиус границы внизу справа 2rem при наведении
- `.hover:rounded-br-1.5` - Радиус границы внизу справа 0rem при наведении
- `.hover:rounded-br-1` - Радиус границы внизу справа 1 рем при наведении
- `.hover:rounded-br-0.5` - Радиус границы внизу справа 0,5 рем. при наведении
- `.hover:rounded-br-0` - Радиус границы внизу справа 0rem при наведении
- `.rounded-br-5` - Радиус границы внизу справа 5rem
- `.rounded-br-4.5` - Радиус границы внизу справа 0rem
- `.rounded-br-4` - Радиус границы внизу справа 4rem
- `.rounded-br-3.5` - Радиус границы внизу справа 0rem
- `.rounded-br-3` - Радиус границы внизу справа 3rem
- `.rounded-br-2.5` - Радиус границы внизу справа 0rem
- `.rounded-br-2` - Радиус границы внизу справа 2rem
- `.rounded-br-1.5` - Радиус границы внизу справа 0rem
- `.rounded-br-1` - Радиус границы внизу справа 1rem
- `.rounded-br-0.5` - Радиус границы внизу справа 0.5rem
- `.rounded-br-0` - Радиус границы внизу справа 0rem

#### Border Radius Top Left

- `.hover:rounded-tl-5` - Радиус границы вверху слева 5rem при наведении
- `.hover:rounded-tl-4.5` - Радиус границы вверху слева 0rem при наведении
- `.hover:rounded-tl-4` - Радиус границы вверху слева 4rem при наведении
- `.hover:rounded-tl-3.5` - Радиус границы вверху слева 0rem при наведении
- `.hover:rounded-tl-3` - Радиус границы вверху слева 3rem при наведении
- `.hover:rounded-tl-2.5` - Радиус границы вверху слева 0rem при наведении
- `.hover:rounded-tl-2` - Радиус границы вверху слева 2rem при наведении
- `.hover:rounded-tl-1.5` - Радиус границы вверху слева 0rem при наведении
- `.hover:rounded-tl-1` - Радиус границы вверху слева 1 рем при наведении
- `.hover:rounded-tl-0.5` - Радиус границы вверху слева 0,5 рем при наведении
- `.hover:rounded-tl-0` - Радиус границы вверху слева 0rem при наведении
- `.rounded-tl-5` - Радиус границы вверху слева 5rem
- `.rounded-tl-4.5` - Радиус границы вверху слева 0rem
- `.rounded-tl-4` - Граница Радиус сверху слева 4rem
- `.rounded-tl-3.5` - Радиус границы вверху слева 0rem
- `.rounded-tl-3` - Граница Радиус сверху слева 3rem
- `.rounded-tl-2.5` - Радиус границы вверху слева 0rem
- `.rounded-tl-2` - Радиус границы вверху слева 2rem
- `.rounded-tl-1.5` - Радиус границы вверху слева 0rem
- `.rounded-tl-1` - Радиус границы вверху слева 1рем
- `.rounded-tl-0.5` - Радиус границы вверху слева 0,5 рем.
- `.rounded-tl-0` - Радиус границы вверху слева 0rem

#### Border Radius Top Right

- `.hover:rounded-tr-5` - Радиус границы вверху справа 5rem при наведении
- `.hover:rounded-tr-4.5` - Радиус границы вверху справа 0rem при наведении
- `.hover:rounded-tr-4` - Радиус границы вверху справа 4rem при наведении
- `.hover:rounded-tr-3.5` - Радиус границы вверху справа 0rem при наведении
- `.hover:rounded-tr-3` - Радиус границы вверху справа 3rem при наведении
- `.hover:rounded-tr-2.5` - Радиус границы вверху справа 0rem при наведении
- `.hover:rounded-tr-2` - Радиус границы вверху справа 2rem при наведении
- `.hover:rounded-tr-1.5` - Радиус границы вверху справа 0rem при наведении
- `.hover:rounded-tr-1` - Радиус границы вверху справа 1 рем при наведении
- `.hover:rounded-tr-0.5` - Радиус границы вверху справа 0,5 рем. при наведении
- `.hover:rounded-tr-0` - Радиус границы вверху справа 0rem при наведении
- `.rounded-tr-5` - Радиус границы вверху справа 5rem
- `.rounded-tr-4.5` - Радиус границы вверху справа 0rem
- `.rounded-tr-4` - Радиус границы вверху справа 4rem
- `.rounded-tr-3.5` - Радиус границы вверху справа 0rem
- `.rounded-tr-3` - Граница Радиус сверху справа 3rem
- `.rounded-tr-2.5` - Радиус границы вверху справа 0rem
- `.rounded-tr-2` - Радиус границы вверху справа 2rem
- `.rounded-tr-1.5` - Радиус границы вверху справа 0rem
- `.rounded-tr-1` - Радиус границы вверху справа 1rem
- `.rounded-tr-0.5` - Радиус границы вверху справа 0,5 рем.
- `.rounded-tr-0` - Радиус границы вверху справа 0rem

## Effects

### Box Shadow

#### Box Shadow All

- `.hover:shadow-5` - Box Shadow All 5rem при наведении
- `.hover:shadow-5-1` - Box Shadow Все 0 0 5rem 2rem при наведении
- `.hover:shadow-4` - Box Shadow All 4rem при наведении
- `.hover:shadow-4-1` - Box Shadow All 0 0 4rem 2rem при наведении
- `.hover:shadow-3` - Box Shadow All 3rem при наведении
- `.hover:shadow-3-1` - Box Shadow All 0 0 3rem 2rem при наведении
- `.hover:shadow-2` - Box Shadow All 2rem при наведении
- `.hover:shadow-2-1` - Box Shadow All 0 0 2rem 2rem при наведении
- `.hover:shadow-1` - Box Shadow Все 1рем при наведении
- `.hover:shadow-1-1` - Box Shadow Все 0 0 1rem 2rem при наведении
- `.hover:shadow-none` - Box Shadow Все нет при наведении
- `.shadow-5` - Коробка Shadow All 5rem
- `.shadow-5-1` - Бокс Шэдоу Все 0 0 5rem 2rem
- `.shadow-4` - Коробка Shadow All 4rem
- `.shadow-4-1` - Бокс Шэдоу Все 0 0 4rem 2rem
- `.shadow-3` - Коробка Тень Все 3рем
- `.shadow-3-1` - Бокс Шэдоу Все 0 0 3rem 2rem
- `.shadow-2` - Коробка Тень Все 2рем
- `.shadow-2-1` - Бокс Шэдоу Все 0 0 2rem 2rem
- `.shadow-1` - Коробка Тень Все 1рем
- `.shadow-1-1` - Box Shadow Все 0 0 1rem 2rem
- `.shadow-none` - Box Shadow Все нет

#### Box Shadow Bottom

- `.hover:shadow-b-10` - Box Shadow Bottom 10rem при наведении
- `.hover:shadow-b-9` - Box Shadow Bottom 9rem при наведении
- `.hover:shadow-b-8` - Box Shadow Bottom 8rem при наведении
- `.hover:shadow-b-7` - Box Shadow Bottom 7rem при наведении
- `.hover:shadow-b-6` - Box Shadow Bottom 6rem при наведении
- `.hover:shadow-b-5` - Box Shadow Bottom 5rem при наведении
- `.hover:shadow-b-4` - Box Shadow Bottom 4rem при наведении
- `.hover:shadow-b-3` - Box Shadow Bottom 3rem при наведении
- `.hover:shadow-b-2` - Box Shadow Bottom 2rem при наведении
- `.hover:shadow-b-1` - Box Shadow Bottom 1rem при наведении
- `.shadow-b-10` - Коробка Shadow Bottom 10рем
- `.shadow-b-9` - Коробка Shadow Bottom 9rem
- `.shadow-b-8` - Коробка Shadow Bottom 8rem
- `.shadow-b-7` - Коробка Shadow Bottom 7rem
- `.shadow-b-6` - Коробка Shadow Bottom 6rem
- `.shadow-b-5` - Коробка Shadow Bottom 5rem
- `.shadow-b-4` - Коробка Shadow Bottom 4rem
- `.shadow-b-3` - Коробка Shadow Bottom 3rem
- `.shadow-b-2` - Коробка Shadow Bottom 2rem
- `.shadow-b-1` - Коробка Shadow Bottom 1rem

#### Box Shadow Left

- `.hover:shadow-l-10` - Box Shadow Left 10rem при наведении
- `.hover:shadow-l-9` - Box Shadow Left 9rem при наведении
- `.hover:shadow-l-8` - Box Shadow Left 8rem при наведении
- `.hover:shadow-l-7` - Box Shadow Left 7rem при наведении
- `.hover:shadow-l-6` - Box Shadow Left 6rem при наведении
- `.hover:shadow-l-5` - Box Shadow Left 5rem при наведении
- `.hover:shadow-l-4` - Box Shadow Left 4rem при наведении
- `.hover:shadow-l-3` - Box Shadow Left 3rem при наведении
- `.hover:shadow-l-2` - Box Shadow Left 2rem при наведении
- `.hover:shadow-l-1` - Box Shadow Left 1rem при наведении
- `.shadow-l-10` - Коробка Тень Левая 10рем
- `.shadow-l-9` - Коробка Shadow Left 9rem
- `.shadow-l-8` - Коробка Shadow Left 8rem
- `.shadow-l-7` - Box Shadow Левый 7рем
- `.shadow-l-6` - Коробка Shadow Left 6rem
- `.shadow-l-5` - Коробка Тень Левая 5рем
- `.shadow-l-4` - Коробка Shadow Left 4rem
- `.shadow-l-3` - Коробка Тень Левая 3рем
- `.shadow-l-2` - Коробка Тень Левая 2рем
- `.shadow-l-1` - Box Shadow слева 1рем

#### Box Shadow Right

- `.hover:shadow-r-10` - Box Shadow Right 10rem при наведении
- `.hover:shadow-r-9` - Box Shadow Right 9rem при наведении
- `.hover:shadow-r-8` - Box Shadow Right 8rem при наведении
- `.hover:shadow-r-7` - Коробка Shadow Right 7rem при наведении
- `.hover:shadow-r-6` - Коробка Shadow Right 6rem при наведении
- `.hover:shadow-r-5` - Коробка Shadow Right 5rem при наведении
- `.hover:shadow-r-4` - Коробка Shadow Right 4rem при наведении
- `.hover:shadow-r-3` - Box Shadow Right 3rem при наведении
- `.hover:shadow-r-2` - Box Shadow Right 2rem при наведении
- `.hover:shadow-r-1` - Box Shadow Right 1rem при наведении
- `.shadow-r-10` - Коробка Shadow Right 10rem
- `.shadow-r-9` - Коробка Shadow Right 9rem
- `.shadow-r-8` - Коробка Shadow Right 8rem
- `.shadow-r-7` - Коробка Shadow Right 7rem
- `.shadow-r-6` - Коробка Shadow Right 6rem
- `.shadow-r-5` - Коробка Shadow Right 5rem
- `.shadow-r-4` - Коробка Shadow Right 4rem
- `.shadow-r-3` - Коробка Shadow Right 3rem
- `.shadow-r-2` - Коробка Shadow Right 2rem
- `.shadow-r-1` - Коробка Shadow Right 1рем

#### Box Shadow Top

- `.hover:shadow-t-10` - Box Shadow Top 10rem при наведении
- `.hover:shadow-t-9` - Box Shadow Top 9rem при наведении
- `.hover:shadow-t-8` - Box Shadow Top 8rem при наведении
- `.hover:shadow-t-7` - Box Shadow Top 7rem при наведении
- `.hover:shadow-t-6` - Коробка Shadow Top 6rem при наведении
- `.hover:shadow-t-5` - Box Shadow Top 5rem при наведении
- `.hover:shadow-t-4` - Коробка Shadow Top 4rem при наведении
- `.hover:shadow-t-3` - Box Shadow Top 3rem при наведении
- `.hover:shadow-t-2` - Box Shadow Top 2rem при наведении
- `.hover:shadow-t-1` - Box Shadow Top 1rem при наведении
- `.shadow-t-10` - Коробка Shadow Top 10rem
- `.shadow-t-9` - Коробка Shadow Top 9rem
- `.shadow-t-8` - Коробка Shadow Top 8rem
- `.shadow-t-7` - Коробка Shadow Top 7rem
- `.shadow-t-6` - Коробка Shadow Top 6rem
- `.shadow-t-5` - Коробка Shadow Top 5rem
- `.shadow-t-4` - Коробка Shadow Top 4rem
- `.shadow-t-3` - Box Shadow Top 3rem
- `.shadow-t-2` - Коробка Shadow Top 2rem
- `.shadow-t-1` - Box Shadow Top 1rem

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
- `.shadow-x-10` - Коробка Shadow X-Axis 10rem
- `.shadow-x-9` - Коробка Shadow X-Axis 9rem
- `.shadow-x-8` - Коробка Shadow X-Axis 8rem
- `.shadow-x-7` - Коробка Shadow X-Axis 7rem
- `.shadow-x-6` - Коробка Shadow X-Axis 6rem
- `.shadow-x-5` - Коробка Shadow X-Axis 5rem
- `.shadow-x-4` - Коробка Shadow X-Axis 4rem
- `.shadow-x-3` - Коробка Shadow X-Axis 3rem
- `.shadow-x-2` - Коробка Shadow X-Axis 2rem
- `.shadow-x-1` - Коробка Shadow X-Axis 1рем

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
- `.shadow-y-10` - Box Shadow Y-ось 10рем
- `.shadow-y-9` - Box Shadow Y-Axis 9rem
- `.shadow-y-8` - Box Shadow Y-Axis 8rem
- `.shadow-y-7` - Box Shadow Y-Axis 7rem
- `.shadow-y-6` - Box Shadow Y-Axis 6rem
- `.shadow-y-5` - Box Shadow Y-Axis 5rem
- `.shadow-y-4` - Box Shadow Y-Axis 4rem
- `.shadow-y-3` - Box Shadow Y-Axis 3rem
- `.shadow-y-2` - Box Shadow Y-Axis 2rem
- `.shadow-y-1` - Box Shadow Y-ось 1рем

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
- `.hover:translate-x-1.5` - Перевести X-Axis 0rem при наведении
- `.hover:translate-x-1` - Перевести X-Axis 1rem при наведении
- `.hover:translate-x-0.5` - Перевести 0,5рем по оси X при наведении
- `.hover:translate-x-0` - Перевести X-Axis 0rem при наведении
- `.translate-x-50` - Перевести ось X 50%
- `.translate-x-25` - Перевести X-Axis 25%
- `.translate-x-2` - Перевести ось X 2rem
- `.translate-x-1.5` - Перевести ось X 0rem
- `.translate-x-1` - Перевести ось X 1rem
- `.translate-x-0.5` - Перевести ось X 0,5рем
- `.translate-x-0` - Перевести ось X 0rem

##### Negative Translate X-Axis

- `.-translate-x-50` - Отрицательное перемещение оси X 50%
- `.-translate-x-25` - Отрицательный перевод оси X 25%
- `.-translate-x-2` - Отрицательное перемещение оси X 2rem
- `.-translate-x-1.5` - Отрицательное перемещение оси X 1,5 рем.
- `.-translate-x-1` - Отрицательное перемещение оси X 1rem
- `.-translate-x-0.5` - Отрицательное перемещение оси X 0,5 рем.
- `.hover:-translate-x-50` - Отрицательный перевод оси X 50% при наведении
- `.hover:-translate-x-25` - Отрицательный перевод оси X 25% при наведении
- `.hover:-translate-x-2` - Отрицательный перевод оси X 2rem при наведении
- `.hover:-translate-x-1.5` - Отрицательное перемещение оси X 1,5 рем. при наведении
- `.hover:-translate-x-1` - Отрицательный перевод оси X 1rem при наведении
- `.hover:-translate-x-0.5` - Отрицательное перемещение оси X 0,5 рем при наведении

#### Translate Y-Axis

- `.hover:translate-y-50` - Перевести ось Y на 50% при наведении
- `.hover:translate-y-25` - Перевести ось Y 25% при наведении
- `.hover:translate-y-2` - Перевести ось Y 2rem при наведении
- `.hover:translate-y-1.5` - Перевести ось Y 0rem при наведении
- `.hover:translate-y-1` - Перевести ось Y 1rem при наведении
- `.hover:translate-y-0.5` - Перевести ось Y на 0,5 рем при наведении
- `.hover:translate-y-0` - Перевести ось Y 0rem при наведении
- `.translate-y-50` - Перевести ось Y 50%
- `.translate-y-25` - Перевести ось Y 25%
- `.translate-y-2` - Перевести ось Y 2rem
- `.translate-y-1.5` - Перевести ось Y 0rem
- `.translate-y-1` - Перевести ось Y 1rem
- `.translate-y-0.5` - Перевести ось Y 0,5рем
- `.translate-y-0` - Перевести ось Y 0rem

##### Negative Translate Y-Axis

- `.-translate-y-50` - Отрицательное перемещение оси Y 50%
- `.-translate-y-25` - Отрицательное перемещение оси Y 25%
- `.-translate-y-2` - Отрицательное перемещение оси Y 2rem
- `.-translate-y-1.5` - Отрицательное перемещение оси Y 1,5 рем.
- `.-translate-y-1` - Отрицательное перемещение оси Y 1rem
- `.-translate-y-0.5` - Отрицательное перемещение оси Y 0,5рем
- `.hover:-translate-y-50` - Отрицательное перемещение оси Y 50% при наведении
- `.hover:-translate-y-25` - Отрицательный перевод оси Y 25% при наведении
- `.hover:-translate-y-2` - Отрицательное перемещение оси Y 2rem при наведении
- `.hover:-translate-y-1.5` - Отрицательное перемещение оси Y 1,5 рем. при наведении
- `.hover:-translate-y-1` - Отрицательное перемещение оси Y на 1 рем при наведении
- `.hover:-translate-y-0.5` - Отрицательное перемещение оси Y 0,5 рем при наведении

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

- `.hover:mse-2` - Мсэ 2рем при наведении
- `.hover:mse-1.5` - Mse 1,5рем при наведении
- `.hover:mse-1` - Mse 1rem при наведении
- `.hover:mse-0.5` - Mse 0,5рем при наведении
- `.hover:mse-0` - Mse 0rem при наведении
- `.mse-2` - Мсэ 2рем
- `.mse-1.5` - Мсэ 1,5рем
- `.mse-1` - Мсэ 1рем
- `.mse-0.5` - Мсэ 0,5бэр
- `.mse-0` - Мсе 0рем

### Visibility

- `.hover:v-hide` - Видимость скрыта при наведении
- `.hover:v-show` - Видимость видна при наведении
- `.v-hide` - Видимость скрыта
- `.v-show` - Видимость видимая

##### Visibility - Mobile (≤ 480px)

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

##### Visibility - Tv (≥ 1200px)

- `.hover:tv:v-hide` - Видимость скрыта при наведении на телевизоре
- `.hover:tv:v-show` - Видимость видна при наведении на телевизор
- `.tv:v-hide` - Видимость скрыта по телевизору
- `.tv:v-show` - Видимость видна по телевизору

##### Visibility - Tablet Max (≤ 768px)

- `.hover:tablet-max:v-hide` - Видимость скрыта при наведении на планшете Max
- `.hover:tablet-max:v-show` - Видимость видна при наведении на планшете макс.
- `.tablet-max:v-hide` - Видимость скрыта на планшете Max
- `.tablet-max:v-show` - Видимость видима на планшете макс.

##### Visibility - Tablet Pc Max (≤ 992px)

- `.hover:tablet-pc-max:v-hide` - Видимость скрыта при наведении на планшетном ПК макс.
- `.hover:tablet-pc-max:v-show` - Видимость видима при наведении на планшетном ПК макс.
- `.tablet-pc-max:v-hide` - Видимость скрыта на планшетном ПК макс.
- `.tablet-pc-max:v-show` - Видимость видима на планшетном ПК макс.

##### Visibility - Pc Max (≤ 1200px)

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
