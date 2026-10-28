# bClass theme css

A comprehensive library for developing interfaces to websites and applications.

## Requirements

It is recommended to use `bClass theme js`, `bClass theme colors`, `bClass components`, `bClass animations` and `bClass media player` along with this library.

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

- `.container` - Container

### Display

- `.d-block` - Display block
- `.d-contents` - Display contents
- `.d-flex` - Display flex
- `.d-flow-root` - Display flow-root
- `.d-grid` - Display grid
- `.d-inline` - Display inline
- `.d-inline-block` - Display inline-block
- `.d-inline-flex` - Display inline-flex
- `.d-inline-grid` - Display inline-grid
- `.d-inline-table` - Display inline-table
- `.d-list-item` - Display list-item
- `.d-none` - Display none
- `.d-table` - Display table
- `.d-table-caption` - Display table-caption
- `.d-table-cell` - Display table-cell
- `.d-table-col` - Display table-col
- `.d-table-col-group` - Display table-col-group
- `.d-table-footer-group` - Display table-footer-group
- `.d-table-header-group` - Display table-header-group
- `.d-table-row` - Display table-row
- `.d-table-row-group` - Display table-row-group
- `.hover:d-block` - Display block on hover
- `.hover:d-flex` - Display flex on hover
- `.hover:d-inline` - Display inline on hover
- `.hover:d-inline-block` - Display inline-block on hover
- `.hover:d-inline-flex` - Display inline-flex on hover
- `.hover:d-none` - Display none on hover

##### Display - Mobile (<= 480px)

- `.hover:mobile:d-block` - Display block on hover on mobile
- `.hover:mobile:d-flex` - Display flex on hover on mobile
- `.hover:mobile:d-inline` - Display inline on hover on mobile
- `.hover:mobile:d-inline-block` - Display inline-block on hover on mobile
- `.hover:mobile:d-inline-flex` - Display inline-flex on hover on mobile
- `.hover:mobile:d-none` - Display none on hover on mobile
- `.mobile:d-block` - Display block on mobile
- `.mobile:d-flex` - Display flex on mobile
- `.mobile:d-grid` - Display grid on mobile
- `.mobile:d-inline` - Display inline on mobile
- `.mobile:d-inline-block` - Display inline-block on mobile
- `.mobile:d-inline-flex` - Display inline-flex on mobile
- `.mobile:d-inline-grid` - Display inline-grid on mobile
- `.mobile:d-none` - Display none on mobile

##### Display - Tablet (480px - 768px)

- `.hover:tablet:d-block` - Display block on hover on tablet
- `.hover:tablet:d-flex` - Display flex on hover on tablet
- `.hover:tablet:d-inline` - Display inline on hover on tablet
- `.hover:tablet:d-inline-block` - Display inline-block on hover on tablet
- `.hover:tablet:d-inline-flex` - Display inline-flex on hover on tablet
- `.hover:tablet:d-none` - Display none on hover on tablet
- `.tablet:d-block` - Display block on tablet
- `.tablet:d-flex` - Display flex on tablet
- `.tablet:d-grid` - Display grid on tablet
- `.tablet:d-inline` - Display inline on tablet
- `.tablet:d-inline-block` - Display inline-block on tablet
- `.tablet:d-inline-flex` - Display inline-flex on tablet
- `.tablet:d-inline-grid` - Display inline-grid on tablet
- `.tablet:d-none` - Display none on tablet

##### Display - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:d-block` - Display block on hover on tablet pc
- `.hover:tablet-pc:d-flex` - Display flex on hover on tablet pc
- `.hover:tablet-pc:d-inline` - Display inline on hover on tablet pc
- `.hover:tablet-pc:d-inline-block` - Display inline-block on hover on tablet pc
- `.hover:tablet-pc:d-inline-flex` - Display inline-flex on hover on tablet pc
- `.hover:tablet-pc:d-none` - Display none on hover on tablet pc
- `.tablet-pc:d-block` - Display block on tablet pc
- `.tablet-pc:d-flex` - Display flex on tablet pc
- `.tablet-pc:d-grid` - Display grid on tablet pc
- `.tablet-pc:d-inline` - Display inline on tablet pc
- `.tablet-pc:d-inline-block` - Display inline-block on tablet pc
- `.tablet-pc:d-inline-flex` - Display inline-flex on tablet pc
- `.tablet-pc:d-inline-grid` - Display inline-grid on tablet pc
- `.tablet-pc:d-none` - Display none on tablet pc

##### Display - Pc (992px - 1200px)

- `.hover:pc:d-block` - Display block on hover on pc
- `.hover:pc:d-flex` - Display flex on hover on pc
- `.hover:pc:d-inline` - Display inline on hover on pc
- `.hover:pc:d-inline-block` - Display inline-block on hover on pc
- `.hover:pc:d-inline-flex` - Display inline-flex on hover on pc
- `.hover:pc:d-none` - Display none on hover on pc
- `.pc:d-block` - Display block on pc
- `.pc:d-flex` - Display flex on pc
- `.pc:d-grid` - Display grid on pc
- `.pc:d-inline` - Display inline on pc
- `.pc:d-inline-block` - Display inline-block on pc
- `.pc:d-inline-flex` - Display inline-flex on pc
- `.pc:d-inline-grid` - Display inline-grid on pc
- `.pc:d-none` - Display none on pc

##### Display - Tv (>= 1200px)

- `.hover:tv:d-block` - Display block on hover on tv
- `.hover:tv:d-flex` - Display flex on hover on tv
- `.hover:tv:d-inline` - Display inline on hover on tv
- `.hover:tv:d-inline-block` - Display inline-block on hover on tv
- `.hover:tv:d-inline-flex` - Display inline-flex on hover on tv
- `.hover:tv:d-none` - Display none on hover on tv
- `.tv:d-block` - Display block on tv
- `.tv:d-flex` - Display flex on tv
- `.tv:d-grid` - Display grid on tv
- `.tv:d-inline` - Display inline on tv
- `.tv:d-inline-block` - Display inline-block on tv
- `.tv:d-inline-flex` - Display inline-flex on tv
- `.tv:d-inline-grid` - Display inline-grid on tv
- `.tv:d-none` - Display none on tv

##### Display - Tablet Max (<= 768px)

- `.hover:tablet-max:d-block` - Display block on hover on tablet max
- `.hover:tablet-max:d-flex` - Display flex on hover on tablet max
- `.hover:tablet-max:d-inline` - Display inline on hover on tablet max
- `.hover:tablet-max:d-inline-block` - Display inline-block on hover on tablet max
- `.hover:tablet-max:d-inline-flex` - Display inline-flex on hover on tablet max
- `.hover:tablet-max:d-none` - Display none on hover on tablet max
- `.tablet-max:d-block` - Display block on tablet max
- `.tablet-max:d-flex` - Display flex on tablet max
- `.tablet-max:d-grid` - Display grid on tablet max
- `.tablet-max:d-inline` - Display inline on tablet max
- `.tablet-max:d-inline-block` - Display inline-block on tablet max
- `.tablet-max:d-inline-flex` - Display inline-flex on tablet max
- `.tablet-max:d-inline-grid` - Display inline-grid on tablet max
- `.tablet-max:d-none` - Display none on tablet max

##### Display - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:d-block` - Display block on hover on tablet pc max
- `.hover:tablet-pc-max:d-flex` - Display flex on hover on tablet pc max
- `.hover:tablet-pc-max:d-inline` - Display inline on hover on tablet pc max
- `.hover:tablet-pc-max:d-inline-block` - Display inline-block on hover on tablet pc max
- `.hover:tablet-pc-max:d-inline-flex` - Display inline-flex on hover on tablet pc max
- `.hover:tablet-pc-max:d-none` - Display none on hover on tablet pc max
- `.tablet-pc-max:d-block` - Display block on tablet pc max
- `.tablet-pc-max:d-flex` - Display flex on tablet pc max
- `.tablet-pc-max:d-grid` - Display grid on tablet pc max
- `.tablet-pc-max:d-inline` - Display inline on tablet pc max
- `.tablet-pc-max:d-inline-block` - Display inline-block on tablet pc max
- `.tablet-pc-max:d-inline-flex` - Display inline-flex on tablet pc max
- `.tablet-pc-max:d-inline-grid` - Display inline-grid on tablet pc max
- `.tablet-pc-max:d-none` - Display none on tablet pc max

##### Display - Pc Max (<= 1200px)

- `.hover:pc-max:d-block` - Display block on hover on pc max
- `.hover:pc-max:d-flex` - Display flex on hover on pc max
- `.hover:pc-max:d-inline` - Display inline on hover on pc max
- `.hover:pc-max:d-inline-block` - Display inline-block on hover on pc max
- `.hover:pc-max:d-inline-flex` - Display inline-flex on hover on pc max
- `.hover:pc-max:d-none` - Display none on hover on pc max
- `.pc-max:d-block` - Display block on pc max
- `.pc-max:d-flex` - Display flex on pc max
- `.pc-max:d-grid` - Display grid on pc max
- `.pc-max:d-inline` - Display inline on pc max
- `.pc-max:d-inline-block` - Display inline-block on pc max
- `.pc-max:d-inline-flex` - Display inline-flex on pc max
- `.pc-max:d-inline-grid` - Display inline-grid on pc max
- `.pc-max:d-none` - Display none on pc max

### Float

- `.float-end` - Float end
- `.float-left` - Float left
- `.float-none` - Float none
- `.float-right` - Float right
- `.float-start` - Float start
- `.hover:float-end` - Float end on hover
- `.hover:float-left` - Float left on hover
- `.hover:float-none` - Float none on hover
- `.hover:float-right` - Float right on hover
- `.hover:float-start` - Float start on hover

##### Float - Mobile (<= 480px)

- `.hover:mobile:float-end` - Float end on hover on mobile
- `.hover:mobile:float-left` - Float left on hover on mobile
- `.hover:mobile:float-none` - Float none on hover on mobile
- `.hover:mobile:float-right` - Float right on hover on mobile
- `.hover:mobile:float-start` - Float start on hover on mobile
- `.mobile:float-end` - Float end on mobile
- `.mobile:float-left` - Float left on mobile
- `.mobile:float-none` - Float none on mobile
- `.mobile:float-right` - Float right on mobile
- `.mobile:float-start` - Float start on mobile

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - Float end on hover on tablet
- `.hover:tablet:float-left` - Float left on hover on tablet
- `.hover:tablet:float-none` - Float none on hover on tablet
- `.hover:tablet:float-right` - Float right on hover on tablet
- `.hover:tablet:float-start` - Float start on hover on tablet
- `.tablet:float-end` - Float end on tablet
- `.tablet:float-left` - Float left on tablet
- `.tablet:float-none` - Float none on tablet
- `.tablet:float-right` - Float right on tablet
- `.tablet:float-start` - Float start on tablet

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - Float end on hover on tablet pc
- `.hover:tablet-pc:float-left` - Float left on hover on tablet pc
- `.hover:tablet-pc:float-none` - Float none on hover on tablet pc
- `.hover:tablet-pc:float-right` - Float right on hover on tablet pc
- `.hover:tablet-pc:float-start` - Float start on hover on tablet pc
- `.tablet-pc:float-end` - Float end on tablet pc
- `.tablet-pc:float-left` - Float left on tablet pc
- `.tablet-pc:float-none` - Float none on tablet pc
- `.tablet-pc:float-right` - Float right on tablet pc
- `.tablet-pc:float-start` - Float start on tablet pc

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - Float end on hover on pc
- `.hover:pc:float-left` - Float left on hover on pc
- `.hover:pc:float-none` - Float none on hover on pc
- `.hover:pc:float-right` - Float right on hover on pc
- `.hover:pc:float-start` - Float start on hover on pc
- `.pc:float-end` - Float end on pc
- `.pc:float-left` - Float left on pc
- `.pc:float-none` - Float none on pc
- `.pc:float-right` - Float right on pc
- `.pc:float-start` - Float start on pc

##### Float - Tv (>= 1200px)

- `.hover:tv:float-end` - Float end on hover on tv
- `.hover:tv:float-left` - Float left on hover on tv
- `.hover:tv:float-none` - Float none on hover on tv
- `.hover:tv:float-right` - Float right on hover on tv
- `.hover:tv:float-start` - Float start on hover on tv
- `.tv:float-end` - Float end on tv
- `.tv:float-left` - Float left on tv
- `.tv:float-none` - Float none on tv
- `.tv:float-right` - Float right on tv
- `.tv:float-start` - Float start on tv

##### Float - Tablet Max (<= 768px)

- `.hover:tablet-max:float-end` - Float end on hover on tablet max
- `.hover:tablet-max:float-left` - Float left on hover on tablet max
- `.hover:tablet-max:float-none` - Float none on hover on tablet max
- `.hover:tablet-max:float-right` - Float right on hover on tablet max
- `.hover:tablet-max:float-start` - Float start on hover on tablet max
- `.tablet-max:float-end` - Float end on tablet max
- `.tablet-max:float-left` - Float left on tablet max
- `.tablet-max:float-none` - Float none on tablet max
- `.tablet-max:float-right` - Float right on tablet max
- `.tablet-max:float-start` - Float start on tablet max

##### Float - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:float-end` - Float end on hover on tablet pc max
- `.hover:tablet-pc-max:float-left` - Float left on hover on tablet pc max
- `.hover:tablet-pc-max:float-none` - Float none on hover on tablet pc max
- `.hover:tablet-pc-max:float-right` - Float right on hover on tablet pc max
- `.hover:tablet-pc-max:float-start` - Float start on hover on tablet pc max
- `.tablet-pc-max:float-end` - Float end on tablet pc max
- `.tablet-pc-max:float-left` - Float left on tablet pc max
- `.tablet-pc-max:float-none` - Float none on tablet pc max
- `.tablet-pc-max:float-right` - Float right on tablet pc max
- `.tablet-pc-max:float-start` - Float start on tablet pc max

##### Float - Pc Max (<= 1200px)

- `.hover:pc-max:float-end` - Float end on hover on pc max
- `.hover:pc-max:float-left` - Float left on hover on pc max
- `.hover:pc-max:float-none` - Float none on hover on pc max
- `.hover:pc-max:float-right` - Float right on hover on pc max
- `.hover:pc-max:float-start` - Float start on hover on pc max
- `.pc-max:float-end` - Float end on pc max
- `.pc-max:float-left` - Float left on pc max
- `.pc-max:float-none` - Float none on pc max
- `.pc-max:float-right` - Float right on pc max
- `.pc-max:float-start` - Float start on pc max

### Object

- `.hover:object-contain` - Object contain on hover
- `.hover:object-cover` - Object cover on hover
- `.hover:object-fill` - Object fill on hover
- `.hover:object-none` - Object none on hover
- `.hover:object-scale` - Object scale on hover
- `.object-contain` - Object contain
- `.object-cover` - Object cover
- `.object-fill` - Object fill
- `.object-none` - Object none
- `.object-scale` - Object scale

##### Object - Mobile (<= 480px)

- `.hover:mobile:object-contain` - Object contain on hover on mobile
- `.hover:mobile:object-cover` - Object cover on hover on mobile
- `.hover:mobile:object-fill` - Object fill on hover on mobile
- `.hover:mobile:object-none` - Object none on hover on mobile
- `.hover:mobile:object-scale` - Object scale on hover on mobile
- `.mobile:object-contain` - Object contain on mobile
- `.mobile:object-cover` - Object cover on mobile
- `.mobile:object-fill` - Object fill on mobile
- `.mobile:object-none` - Object none on mobile
- `.mobile:object-scale` - Object scale on mobile

##### Object - Tablet (480px - 768px)

- `.hover:tablet:object-contain` - Object contain on hover on tablet
- `.hover:tablet:object-cover` - Object cover on hover on tablet
- `.hover:tablet:object-fill` - Object fill on hover on tablet
- `.hover:tablet:object-none` - Object none on hover on tablet
- `.hover:tablet:object-scale` - Object scale on hover on tablet
- `.tablet:object-contain` - Object contain on tablet
- `.tablet:object-cover` - Object cover on tablet
- `.tablet:object-fill` - Object fill on tablet
- `.tablet:object-none` - Object none on tablet
- `.tablet:object-scale` - Object scale on tablet

##### Object - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:object-contain` - Object contain on hover on tablet pc
- `.hover:tablet-pc:object-cover` - Object cover on hover on tablet pc
- `.hover:tablet-pc:object-fill` - Object fill on hover on tablet pc
- `.hover:tablet-pc:object-none` - Object none on hover on tablet pc
- `.hover:tablet-pc:object-scale` - Object scale on hover on tablet pc
- `.tablet-pc:object-contain` - Object contain on tablet pc
- `.tablet-pc:object-cover` - Object cover on tablet pc
- `.tablet-pc:object-fill` - Object fill on tablet pc
- `.tablet-pc:object-none` - Object none on tablet pc
- `.tablet-pc:object-scale` - Object scale on tablet pc

##### Object - Pc (992px - 1200px)

- `.hover:pc:object-contain` - Object contain on hover on pc
- `.hover:pc:object-cover` - Object cover on hover on pc
- `.hover:pc:object-fill` - Object fill on hover on pc
- `.hover:pc:object-none` - Object none on hover on pc
- `.hover:pc:object-scale` - Object scale on hover on pc
- `.pc:object-contain` - Object contain on pc
- `.pc:object-cover` - Object cover on pc
- `.pc:object-fill` - Object fill on pc
- `.pc:object-none` - Object none on pc
- `.pc:object-scale` - Object scale on pc

##### Object - Tv (>= 1200px)

- `.hover:tv:object-contain` - Object contain on hover on tv
- `.hover:tv:object-cover` - Object cover on hover on tv
- `.hover:tv:object-fill` - Object fill on hover on tv
- `.hover:tv:object-none` - Object none on hover on tv
- `.hover:tv:object-scale` - Object scale on hover on tv
- `.tv:object-contain` - Object contain on tv
- `.tv:object-cover` - Object cover on tv
- `.tv:object-fill` - Object fill on tv
- `.tv:object-none` - Object none on tv
- `.tv:object-scale` - Object scale on tv

##### Object - Tablet Max (<= 768px)

- `.hover:tablet-max:object-contain` - Object contain on hover on tablet max
- `.hover:tablet-max:object-cover` - Object cover on hover on tablet max
- `.hover:tablet-max:object-fill` - Object fill on hover on tablet max
- `.hover:tablet-max:object-none` - Object none on hover on tablet max
- `.hover:tablet-max:object-scale` - Object scale on hover on tablet max
- `.tablet-max:object-contain` - Object contain on tablet max
- `.tablet-max:object-cover` - Object cover on tablet max
- `.tablet-max:object-fill` - Object fill on tablet max
- `.tablet-max:object-none` - Object none on tablet max
- `.tablet-max:object-scale` - Object scale on tablet max

##### Object - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:object-contain` - Object contain on hover on tablet pc max
- `.hover:tablet-pc-max:object-cover` - Object cover on hover on tablet pc max
- `.hover:tablet-pc-max:object-fill` - Object fill on hover on tablet pc max
- `.hover:tablet-pc-max:object-none` - Object none on hover on tablet pc max
- `.hover:tablet-pc-max:object-scale` - Object scale on hover on tablet pc max
- `.tablet-pc-max:object-contain` - Object contain on tablet pc max
- `.tablet-pc-max:object-cover` - Object cover on tablet pc max
- `.tablet-pc-max:object-fill` - Object fill on tablet pc max
- `.tablet-pc-max:object-none` - Object none on tablet pc max
- `.tablet-pc-max:object-scale` - Object scale on tablet pc max

##### Object - Pc Max (<= 1200px)

- `.hover:pc-max:object-contain` - Object contain on hover on pc max
- `.hover:pc-max:object-cover` - Object cover on hover on pc max
- `.hover:pc-max:object-fill` - Object fill on hover on pc max
- `.hover:pc-max:object-none` - Object none on hover on pc max
- `.hover:pc-max:object-scale` - Object scale on hover on pc max
- `.pc-max:object-contain` - Object contain on pc max
- `.pc-max:object-cover` - Object cover on pc max
- `.pc-max:object-fill` - Object fill on pc max
- `.pc-max:object-none` - Object none on pc max
- `.pc-max:object-scale` - Object scale on pc max

### Overflow

- `.hover:overflow-scroll` - Overflow scroll on hover
- `.overflow-auto` - Overflow auto
- `.overflow-clip` - Overflow clip
- `.overflow-hidden` - Overflow hidden
- `.overflow-scroll` - Overflow scroll
- `.overflow-visible` - Overflow visible

### Overflow x

- `.hover:overflow-x-scroll` - Overflow x scroll on hover
- `.overflow-x-auto` - Overflow x auto
- `.overflow-x-clip` - Overflow x clip
- `.overflow-x-hidden` - Overflow x hidden
- `.overflow-x-scroll` - Overflow x scroll
- `.overflow-x-visible` - Overflow x visible

### Overflow y

- `.hover:overflow-y-scroll` - Overflow y scroll on hover
- `.overflow-y-auto` - Overflow y auto
- `.overflow-y-clip` - Overflow y clip
- `.overflow-y-hidden` - Overflow y hidden
- `.overflow-y-scroll` - Overflow y scroll
- `.overflow-y-visible` - Overflow y visible

### Header

- `.header` - Header

### Footer

- `.footer` - Footer

## Flexbox

### Flex

- `.flex-col` - Flex col
- `.flex-nowrap` - Flex nowrap
- `.flex-row` - Flex row
- `.flex-wrap` - Flex wrap
- `.hover:flex-col` - Flex col on hover
- `.hover:flex-nowrap` - Flex nowrap on hover
- `.hover:flex-row` - Flex row on hover
- `.hover:flex-wrap` - Flex wrap on hover

##### Flex - Mobile (<= 480px)

- `.hover:mobile:flex-col` - Flex col on hover on mobile
- `.hover:mobile:flex-nowrap` - Flex nowrap on hover on mobile
- `.hover:mobile:flex-row` - Flex row on hover on mobile
- `.hover:mobile:flex-wrap` - Flex wrap on hover on mobile
- `.mobile:flex-col` - Flex col on mobile
- `.mobile:flex-nowrap` - Flex nowrap on mobile
- `.mobile:flex-row` - Flex row on mobile
- `.mobile:flex-wrap` - Flex wrap on mobile

##### Flex - Tablet (480px - 768px)

- `.hover:tablet:flex-col` - Flex col on hover on tablet
- `.hover:tablet:flex-nowrap` - Flex nowrap on hover on tablet
- `.hover:tablet:flex-row` - Flex row on hover on tablet
- `.hover:tablet:flex-wrap` - Flex wrap on hover on tablet
- `.tablet:flex-col` - Flex col on tablet
- `.tablet:flex-nowrap` - Flex nowrap on tablet
- `.tablet:flex-row` - Flex row on tablet
- `.tablet:flex-wrap` - Flex wrap on tablet

##### Flex - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col` - Flex col on hover on tablet pc
- `.hover:tablet-pc:flex-nowrap` - Flex nowrap on hover on tablet pc
- `.hover:tablet-pc:flex-row` - Flex row on hover on tablet pc
- `.hover:tablet-pc:flex-wrap` - Flex wrap on hover on tablet pc
- `.tablet-pc:flex-col` - Flex col on tablet pc
- `.tablet-pc:flex-nowrap` - Flex nowrap on tablet pc
- `.tablet-pc:flex-row` - Flex row on tablet pc
- `.tablet-pc:flex-wrap` - Flex wrap on tablet pc

##### Flex - Pc (992px - 1200px)

- `.hover:pc:flex-col` - Flex col on hover on pc
- `.hover:pc:flex-nowrap` - Flex nowrap on hover on pc
- `.hover:pc:flex-row` - Flex row on hover on pc
- `.hover:pc:flex-wrap` - Flex wrap on hover on pc
- `.pc:flex-col` - Flex col on pc
- `.pc:flex-nowrap` - Flex nowrap on pc
- `.pc:flex-row` - Flex row on pc
- `.pc:flex-wrap` - Flex wrap on pc

##### Flex - Tv (>= 1200px)

- `.hover:tv:flex-col` - Flex col on hover on tv
- `.hover:tv:flex-nowrap` - Flex nowrap on hover on tv
- `.hover:tv:flex-row` - Flex row on hover on tv
- `.hover:tv:flex-wrap` - Flex wrap on hover on tv
- `.tv:flex-col` - Flex col on tv
- `.tv:flex-nowrap` - Flex nowrap on tv
- `.tv:flex-row` - Flex row on tv
- `.tv:flex-wrap` - Flex wrap on tv

##### Flex - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-col` - Flex col on hover on tablet max
- `.hover:tablet-max:flex-nowrap` - Flex nowrap on hover on tablet max
- `.hover:tablet-max:flex-row` - Flex row on hover on tablet max
- `.hover:tablet-max:flex-wrap` - Flex wrap on hover on tablet max
- `.tablet-max:flex-col` - Flex col on tablet max
- `.tablet-max:flex-nowrap` - Flex nowrap on tablet max
- `.tablet-max:flex-row` - Flex row on tablet max
- `.tablet-max:flex-wrap` - Flex wrap on tablet max

##### Flex - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-col` - Flex col on hover on tablet pc max
- `.hover:tablet-pc-max:flex-nowrap` - Flex nowrap on hover on tablet pc max
- `.hover:tablet-pc-max:flex-row` - Flex row on hover on tablet pc max
- `.hover:tablet-pc-max:flex-wrap` - Flex wrap on hover on tablet pc max
- `.tablet-pc-max:flex-col` - Flex col on tablet pc max
- `.tablet-pc-max:flex-nowrap` - Flex nowrap on tablet pc max
- `.tablet-pc-max:flex-row` - Flex row on tablet pc max
- `.tablet-pc-max:flex-wrap` - Flex wrap on tablet pc max

##### Flex - Pc Max (<= 1200px)

- `.hover:pc-max:flex-col` - Flex col on hover on pc max
- `.hover:pc-max:flex-nowrap` - Flex nowrap on hover on pc max
- `.hover:pc-max:flex-row` - Flex row on hover on pc max
- `.hover:pc-max:flex-wrap` - Flex wrap on hover on pc max
- `.pc-max:flex-col` - Flex col on pc max
- `.pc-max:flex-nowrap` - Flex nowrap on pc max
- `.pc-max:flex-row` - Flex row on pc max
- `.pc-max:flex-wrap` - Flex wrap on pc max

### Flex col

- `.flex-col-reverse` - Flex col reverse
- `.hover:flex-col-reverse` - Flex col reverse on hover

##### Flex col - Mobile (<= 480px)

- `.hover:mobile:flex-col-reverse` - Flex col reverse on hover on mobile
- `.mobile:flex-col-reverse` - Flex col reverse on mobile

##### Flex col - Tablet (480px - 768px)

- `.hover:tablet:flex-col-reverse` - Flex col reverse on hover on tablet
- `.tablet:flex-col-reverse` - Flex col reverse on tablet

##### Flex col - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col-reverse` - Flex col reverse on hover on tablet pc
- `.tablet-pc:flex-col-reverse` - Flex col reverse on tablet pc

##### Flex col - Pc (992px - 1200px)

- `.hover:pc:flex-col-reverse` - Flex col reverse on hover on pc
- `.pc:flex-col-reverse` - Flex col reverse on pc

##### Flex col - Tv (>= 1200px)

- `.hover:tv:flex-col-reverse` - Flex col reverse on hover on tv
- `.tv:flex-col-reverse` - Flex col reverse on tv

##### Flex col - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-col-reverse` - Flex col reverse on hover on tablet max
- `.tablet-max:flex-col-reverse` - Flex col reverse on tablet max

##### Flex col - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - Flex col reverse on hover on tablet pc max
- `.tablet-pc-max:flex-col-reverse` - Flex col reverse on tablet pc max

##### Flex col - Pc Max (<= 1200px)

- `.hover:pc-max:flex-col-reverse` - Flex col reverse on hover on pc max
- `.pc-max:flex-col-reverse` - Flex col reverse on pc max

### Flex row

- `.flex-row-reverse` - Flex row reverse
- `.hover:flex-row-reverse` - Flex row reverse on hover

##### Flex row - Mobile (<= 480px)

- `.hover:mobile:flex-row-reverse` - Flex row reverse on hover on mobile
- `.mobile:flex-row-reverse` - Flex row reverse on mobile

##### Flex row - Tablet (480px - 768px)

- `.hover:tablet:flex-row-reverse` - Flex row reverse on hover on tablet
- `.tablet:flex-row-reverse` - Flex row reverse on tablet

##### Flex row - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-row-reverse` - Flex row reverse on hover on tablet pc
- `.tablet-pc:flex-row-reverse` - Flex row reverse on tablet pc

##### Flex row - Pc (992px - 1200px)

- `.hover:pc:flex-row-reverse` - Flex row reverse on hover on pc
- `.pc:flex-row-reverse` - Flex row reverse on pc

##### Flex row - Tv (>= 1200px)

- `.hover:tv:flex-row-reverse` - Flex row reverse on hover on tv
- `.tv:flex-row-reverse` - Flex row reverse on tv

##### Flex row - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-row-reverse` - Flex row reverse on hover on tablet max
- `.tablet-max:flex-row-reverse` - Flex row reverse on tablet max

##### Flex row - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - Flex row reverse on hover on tablet pc max
- `.tablet-pc-max:flex-row-reverse` - Flex row reverse on tablet pc max

##### Flex row - Pc Max (<= 1200px)

- `.hover:pc-max:flex-row-reverse` - Flex row reverse on hover on pc max
- `.pc-max:flex-row-reverse` - Flex row reverse on pc max

### Flex grow

- `.flex-grow-3` - Flex grow 3
- `.flex-grow-2` - Flex grow 2
- `.flex-grow-1` - Flex grow 1
- `.flex-grow-0` - Flex grow 0
- `.hover:flex-grow-3` - Flex grow 3 on hover
- `.hover:flex-grow-2` - Flex grow 2 on hover
- `.hover:flex-grow-1` - Flex grow 1 on hover
- `.hover:flex-grow-0` - Flex grow 0 on hover

##### Flex grow - Mobile (<= 480px)

- `.hover:mobile:flex-grow-3` - Flex grow 3 on hover on mobile
- `.hover:mobile:flex-grow-2` - Flex grow 2 on hover on mobile
- `.hover:mobile:flex-grow-1` - Flex grow 1 on hover on mobile
- `.hover:mobile:flex-grow-0` - Flex grow 0 on hover on mobile
- `.mobile:flex-grow-3` - Flex grow 3 on mobile
- `.mobile:flex-grow-2` - Flex grow 2 on mobile
- `.mobile:flex-grow-1` - Flex grow 1 on mobile
- `.mobile:flex-grow-0` - Flex grow 0 on mobile

##### Flex grow - Tablet (480px - 768px)

- `.hover:tablet:flex-grow-3` - Flex grow 3 on hover on tablet
- `.hover:tablet:flex-grow-2` - Flex grow 2 on hover on tablet
- `.hover:tablet:flex-grow-1` - Flex grow 1 on hover on tablet
- `.hover:tablet:flex-grow-0` - Flex grow 0 on hover on tablet
- `.tablet:flex-grow-3` - Flex grow 3 on tablet
- `.tablet:flex-grow-2` - Flex grow 2 on tablet
- `.tablet:flex-grow-1` - Flex grow 1 on tablet
- `.tablet:flex-grow-0` - Flex grow 0 on tablet

##### Flex grow - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-grow-3` - Flex grow 3 on hover on tablet pc
- `.hover:tablet-pc:flex-grow-2` - Flex grow 2 on hover on tablet pc
- `.hover:tablet-pc:flex-grow-1` - Flex grow 1 on hover on tablet pc
- `.hover:tablet-pc:flex-grow-0` - Flex grow 0 on hover on tablet pc
- `.tablet-pc:flex-grow-3` - Flex grow 3 on tablet pc
- `.tablet-pc:flex-grow-2` - Flex grow 2 on tablet pc
- `.tablet-pc:flex-grow-1` - Flex grow 1 on tablet pc
- `.tablet-pc:flex-grow-0` - Flex grow 0 on tablet pc

##### Flex grow - Pc (992px - 1200px)

- `.hover:pc:flex-grow-3` - Flex grow 3 on hover on pc
- `.hover:pc:flex-grow-2` - Flex grow 2 on hover on pc
- `.hover:pc:flex-grow-1` - Flex grow 1 on hover on pc
- `.hover:pc:flex-grow-0` - Flex grow 0 on hover on pc
- `.pc:flex-grow-3` - Flex grow 3 on pc
- `.pc:flex-grow-2` - Flex grow 2 on pc
- `.pc:flex-grow-1` - Flex grow 1 on pc
- `.pc:flex-grow-0` - Flex grow 0 on pc

##### Flex grow - Tv (>= 1200px)

- `.hover:tv:flex-grow-3` - Flex grow 3 on hover on tv
- `.hover:tv:flex-grow-2` - Flex grow 2 on hover on tv
- `.hover:tv:flex-grow-1` - Flex grow 1 on hover on tv
- `.hover:tv:flex-grow-0` - Flex grow 0 on hover on tv
- `.tv:flex-grow-3` - Flex grow 3 on tv
- `.tv:flex-grow-2` - Flex grow 2 on tv
- `.tv:flex-grow-1` - Flex grow 1 on tv
- `.tv:flex-grow-0` - Flex grow 0 on tv

##### Flex grow - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-grow-3` - Flex grow 3 on hover on tablet max
- `.hover:tablet-max:flex-grow-2` - Flex grow 2 on hover on tablet max
- `.hover:tablet-max:flex-grow-1` - Flex grow 1 on hover on tablet max
- `.hover:tablet-max:flex-grow-0` - Flex grow 0 on hover on tablet max
- `.tablet-max:flex-grow-3` - Flex grow 3 on tablet max
- `.tablet-max:flex-grow-2` - Flex grow 2 on tablet max
- `.tablet-max:flex-grow-1` - Flex grow 1 on tablet max
- `.tablet-max:flex-grow-0` - Flex grow 0 on tablet max

##### Flex grow - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex grow 3 on hover on tablet pc max
- `.hover:tablet-pc-max:flex-grow-2` - Flex grow 2 on hover on tablet pc max
- `.hover:tablet-pc-max:flex-grow-1` - Flex grow 1 on hover on tablet pc max
- `.hover:tablet-pc-max:flex-grow-0` - Flex grow 0 on hover on tablet pc max
- `.tablet-pc-max:flex-grow-3` - Flex grow 3 on tablet pc max
- `.tablet-pc-max:flex-grow-2` - Flex grow 2 on tablet pc max
- `.tablet-pc-max:flex-grow-1` - Flex grow 1 on tablet pc max
- `.tablet-pc-max:flex-grow-0` - Flex grow 0 on tablet pc max

##### Flex grow - Pc Max (<= 1200px)

- `.hover:pc-max:flex-grow-3` - Flex grow 3 on hover on pc max
- `.hover:pc-max:flex-grow-2` - Flex grow 2 on hover on pc max
- `.hover:pc-max:flex-grow-1` - Flex grow 1 on hover on pc max
- `.hover:pc-max:flex-grow-0` - Flex grow 0 on hover on pc max
- `.pc-max:flex-grow-3` - Flex grow 3 on pc max
- `.pc-max:flex-grow-2` - Flex grow 2 on pc max
- `.pc-max:flex-grow-1` - Flex grow 1 on pc max
- `.pc-max:flex-grow-0` - Flex grow 0 on pc max

### Flex wrap

- `.flex-wrap-reverse` - Flex wrap reverse
- `.hover:flex-wrap-reverse` - Flex wrap reverse on hover

##### Flex wrap - Mobile (<= 480px)

- `.hover:mobile:flex-wrap-reverse` - Flex wrap reverse on hover on mobile
- `.mobile:flex-wrap-reverse` - Flex wrap reverse on mobile

##### Flex wrap - Tablet (480px - 768px)

- `.hover:tablet:flex-wrap-reverse` - Flex wrap reverse on hover on tablet
- `.tablet:flex-wrap-reverse` - Flex wrap reverse on tablet

##### Flex wrap - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-wrap-reverse` - Flex wrap reverse on hover on tablet pc
- `.tablet-pc:flex-wrap-reverse` - Flex wrap reverse on tablet pc

##### Flex wrap - Pc (992px - 1200px)

- `.hover:pc:flex-wrap-reverse` - Flex wrap reverse on hover on pc
- `.pc:flex-wrap-reverse` - Flex wrap reverse on pc

##### Flex wrap - Tv (>= 1200px)

- `.hover:tv:flex-wrap-reverse` - Flex wrap reverse on hover on tv
- `.tv:flex-wrap-reverse` - Flex wrap reverse on tv

##### Flex wrap - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-wrap-reverse` - Flex wrap reverse on hover on tablet max
- `.tablet-max:flex-wrap-reverse` - Flex wrap reverse on tablet max

##### Flex wrap - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - Flex wrap reverse on hover on tablet pc max
- `.tablet-pc-max:flex-wrap-reverse` - Flex wrap reverse on tablet pc max

##### Flex wrap - Pc Max (<= 1200px)

- `.hover:pc-max:flex-wrap-reverse` - Flex wrap reverse on hover on pc max
- `.pc-max:flex-wrap-reverse` - Flex wrap reverse on pc max

### Gap

#### Gap All

- `.gap-5` - Gap All 5rem
- `.gap-4.5` - Gap All 0rem
- `.gap-4` - Gap All 4rem
- `.gap-3.5` - Gap All 0rem
- `.gap-3` - Gap All 3rem
- `.gap-2.5` - Gap All 0rem
- `.gap-2` - Gap All 2rem
- `.gap-1.9` - Gap All 0rem
- `.gap-1.8` - Gap All 0rem
- `.gap-1.7` - Gap All 0rem
- `.gap-1.6` - Gap All 0rem
- `.gap-1.5` - Gap All 0rem
- `.gap-1.4` - Gap All 0rem
- `.gap-1.3` - Gap All 0rem
- `.gap-1.2` - Gap All 0rem
- `.gap-1.1` - Gap All 0rem
- `.gap-1` - Gap All 1rem
- `.gap-0.9` - Gap All 0rem
- `.gap-0.8` - Gap All 0rem
- `.gap-0.7` - Gap All 0rem
- `.gap-0.6` - Gap All 0rem
- `.gap-0.5` - Gap All 0rem
- `.gap-0.4` - Gap All 0rem
- `.gap-0.3` - Gap All 0rem
- `.gap-0.2` - Gap All 0.2rem
- `.gap-0.1` - Gap All 0.1rem
- `.gap-0` - Gap All 0rem
- `.hover:gap-5` - Gap All 5rem on hover
- `.hover:gap-4.5` - Gap All 0rem on hover
- `.hover:gap-4` - Gap All 4rem on hover
- `.hover:gap-3.5` - Gap All 0rem on hover
- `.hover:gap-3` - Gap All 3rem on hover
- `.hover:gap-2.5` - Gap All 0rem on hover
- `.hover:gap-2` - Gap All 2rem on hover
- `.hover:gap-1.9` - Gap All 0rem on hover
- `.hover:gap-1.8` - Gap All 0rem on hover
- `.hover:gap-1.7` - Gap All 0rem on hover
- `.hover:gap-1.6` - Gap All 0rem on hover
- `.hover:gap-1.5` - Gap All 0rem on hover
- `.hover:gap-1.4` - Gap All 0rem on hover
- `.hover:gap-1.3` - Gap All 0rem on hover
- `.hover:gap-1.2` - Gap All 0rem on hover
- `.hover:gap-1.1` - Gap All 0rem on hover
- `.hover:gap-1` - Gap All 1rem on hover
- `.hover:gap-0.9` - Gap All 0rem on hover
- `.hover:gap-0.8` - Gap All 0rem on hover
- `.hover:gap-0.7` - Gap All 0rem on hover
- `.hover:gap-0.6` - Gap All 0rem on hover
- `.hover:gap-0.5` - Gap All 0rem on hover
- `.hover:gap-0.4` - Gap All 0rem on hover
- `.hover:gap-0.3` - Gap All 0rem on hover
- `.hover:gap-0.2` - Gap All 0.2rem on hover
- `.hover:gap-0.1` - Gap All 0.1rem on hover
- `.hover:gap-0` - Gap All 0rem on hover

#### Gap X-Axis

- `.gap-x-5` - Gap X-Axis 5rem
- `.gap-x-4.5` - Gap X-Axis 0rem
- `.gap-x-4` - Gap X-Axis 4rem
- `.gap-x-3.5` - Gap X-Axis 0rem
- `.gap-x-3` - Gap X-Axis 3rem
- `.gap-x-2.5` - Gap X-Axis 0rem
- `.gap-x-2` - Gap X-Axis 2rem
- `.gap-x-1.9` - Gap X-Axis 0rem
- `.gap-x-1.8` - Gap X-Axis 0rem
- `.gap-x-1.7` - Gap X-Axis 0rem
- `.gap-x-1.6` - Gap X-Axis 0rem
- `.gap-x-1.5` - Gap X-Axis 0rem
- `.gap-x-1.4` - Gap X-Axis 0rem
- `.gap-x-1.3` - Gap X-Axis 0rem
- `.gap-x-1.2` - Gap X-Axis 0rem
- `.gap-x-1.1` - Gap X-Axis 0rem
- `.gap-x-1` - Gap X-Axis 1rem
- `.gap-x-0.9` - Gap X-Axis 0rem
- `.gap-x-0.8` - Gap X-Axis 0rem
- `.gap-x-0.7` - Gap X-Axis 0rem
- `.gap-x-0.6` - Gap X-Axis 0rem
- `.gap-x-0.5` - Gap X-Axis 0rem
- `.gap-x-0.4` - Gap X-Axis 0rem
- `.gap-x-0.3` - Gap X-Axis 0rem
- `.gap-x-0.2` - Gap X-Axis 0.2rem
- `.gap-x-0.1` - Gap X-Axis 0.1rem
- `.gap-x-0` - Gap X-Axis 0rem
- `.hover:gap-x-5` - Gap X-Axis 5rem on hover
- `.hover:gap-x-4.5` - Gap X-Axis 0rem on hover
- `.hover:gap-x-4` - Gap X-Axis 4rem on hover
- `.hover:gap-x-3.5` - Gap X-Axis 0rem on hover
- `.hover:gap-x-3` - Gap X-Axis 3rem on hover
- `.hover:gap-x-2.5` - Gap X-Axis 0rem on hover
- `.hover:gap-x-2` - Gap X-Axis 2rem on hover
- `.hover:gap-x-1.9` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.8` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.7` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.6` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.5` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.4` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.3` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.2` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1.1` - Gap X-Axis 0rem on hover
- `.hover:gap-x-1` - Gap X-Axis 1rem on hover
- `.hover:gap-x-0.9` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.8` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.7` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.6` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.5` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.4` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.3` - Gap X-Axis 0rem on hover
- `.hover:gap-x-0.2` - Gap X-Axis 0.2rem on hover
- `.hover:gap-x-0.1` - Gap X-Axis 0.1rem on hover
- `.hover:gap-x-0` - Gap X-Axis 0rem on hover

#### Gap Y-Axis

- `.gap-y-5` - Gap Y-Axis 5rem
- `.gap-y-4.5` - Gap Y-Axis 0rem
- `.gap-y-4` - Gap Y-Axis 4rem
- `.gap-y-3.5` - Gap Y-Axis 0rem
- `.gap-y-3` - Gap Y-Axis 3rem
- `.gap-y-2.5` - Gap Y-Axis 0rem
- `.gap-y-2` - Gap Y-Axis 2rem
- `.gap-y-1.9` - Gap Y-Axis 0rem
- `.gap-y-1.8` - Gap Y-Axis 0rem
- `.gap-y-1.7` - Gap Y-Axis 0rem
- `.gap-y-1.6` - Gap Y-Axis 0rem
- `.gap-y-1.5` - Gap Y-Axis 0rem
- `.gap-y-1.4` - Gap Y-Axis 0rem
- `.gap-y-1.3` - Gap Y-Axis 0rem
- `.gap-y-1.2` - Gap Y-Axis 0rem
- `.gap-y-1.1` - Gap Y-Axis 0rem
- `.gap-y-1` - Gap Y-Axis 1rem
- `.gap-y-0.9` - Gap Y-Axis 0rem
- `.gap-y-0.8` - Gap Y-Axis 0rem
- `.gap-y-0.7` - Gap Y-Axis 0rem
- `.gap-y-0.6` - Gap Y-Axis 0rem
- `.gap-y-0.5` - Gap Y-Axis 0rem
- `.gap-y-0.4` - Gap Y-Axis 0rem
- `.gap-y-0.3` - Gap Y-Axis 0rem
- `.gap-y-0.2` - Gap Y-Axis 0.2rem
- `.gap-y-0.1` - Gap Y-Axis 0.1rem
- `.gap-y-0` - Gap Y-Axis 0rem
- `.hover:gap-y-5` - Gap Y-Axis 5rem on hover
- `.hover:gap-y-4.5` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-4` - Gap Y-Axis 4rem on hover
- `.hover:gap-y-3.5` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-3` - Gap Y-Axis 3rem on hover
- `.hover:gap-y-2.5` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-2` - Gap Y-Axis 2rem on hover
- `.hover:gap-y-1.9` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.8` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.7` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.6` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.5` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.4` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.3` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.2` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1.1` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-1` - Gap Y-Axis 1rem on hover
- `.hover:gap-y-0.9` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.8` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.7` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.6` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.5` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.4` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.3` - Gap Y-Axis 0rem on hover
- `.hover:gap-y-0.2` - Gap Y-Axis 0.2rem on hover
- `.hover:gap-y-0.1` - Gap Y-Axis 0.1rem on hover
- `.hover:gap-y-0` - Gap Y-Axis 0rem on hover

### Align content

- `.align-content-around` - Align content around
- `.align-content-between` - Align content between
- `.align-content-center` - Align content center
- `.align-content-end` - Align content end
- `.align-content-evenly` - Align content evenly
- `.align-content-start` - Align content start
- `.align-content-stretch` - Align content stretch
- `.hover:align-content-around` - Align content around on hover
- `.hover:align-content-between` - Align content between on hover
- `.hover:align-content-center` - Align content center on hover
- `.hover:align-content-end` - Align content end on hover
- `.hover:align-content-evenly` - Align content evenly on hover
- `.hover:align-content-start` - Align content start on hover
- `.hover:align-content-stretch` - Align content stretch on hover

##### Align content - Mobile (<= 480px)

- `.hover:mobile:align-content-around` - Align content around on hover on mobile
- `.hover:mobile:align-content-between` - Align content between on hover on mobile
- `.hover:mobile:align-content-center` - Align content center on hover on mobile
- `.hover:mobile:align-content-end` - Align content end on hover on mobile
- `.hover:mobile:align-content-evenly` - Align content evenly on hover on mobile
- `.hover:mobile:align-content-start` - Align content start on hover on mobile
- `.hover:mobile:align-content-stretch` - Align content stretch on hover on mobile
- `.mobile:align-content-around` - Align content around on mobile
- `.mobile:align-content-between` - Align content between on mobile
- `.mobile:align-content-center` - Align content center on mobile
- `.mobile:align-content-end` - Align content end on mobile
- `.mobile:align-content-evenly` - Align content evenly on mobile
- `.mobile:align-content-start` - Align content start on mobile
- `.mobile:align-content-stretch` - Align content stretch on mobile

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - Align content around on hover on tablet
- `.hover:tablet:align-content-between` - Align content between on hover on tablet
- `.hover:tablet:align-content-center` - Align content center on hover on tablet
- `.hover:tablet:align-content-end` - Align content end on hover on tablet
- `.hover:tablet:align-content-evenly` - Align content evenly on hover on tablet
- `.hover:tablet:align-content-start` - Align content start on hover on tablet
- `.hover:tablet:align-content-stretch` - Align content stretch on hover on tablet
- `.tablet:align-content-around` - Align content around on tablet
- `.tablet:align-content-between` - Align content between on tablet
- `.tablet:align-content-center` - Align content center on tablet
- `.tablet:align-content-end` - Align content end on tablet
- `.tablet:align-content-evenly` - Align content evenly on tablet
- `.tablet:align-content-start` - Align content start on tablet
- `.tablet:align-content-stretch` - Align content stretch on tablet

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - Align content around on hover on tablet pc
- `.hover:tablet-pc:align-content-between` - Align content between on hover on tablet pc
- `.hover:tablet-pc:align-content-center` - Align content center on hover on tablet pc
- `.hover:tablet-pc:align-content-end` - Align content end on hover on tablet pc
- `.hover:tablet-pc:align-content-evenly` - Align content evenly on hover on tablet pc
- `.hover:tablet-pc:align-content-start` - Align content start on hover on tablet pc
- `.hover:tablet-pc:align-content-stretch` - Align content stretch on hover on tablet pc
- `.tablet-pc:align-content-around` - Align content around on tablet pc
- `.tablet-pc:align-content-between` - Align content between on tablet pc
- `.tablet-pc:align-content-center` - Align content center on tablet pc
- `.tablet-pc:align-content-end` - Align content end on tablet pc
- `.tablet-pc:align-content-evenly` - Align content evenly on tablet pc
- `.tablet-pc:align-content-start` - Align content start on tablet pc
- `.tablet-pc:align-content-stretch` - Align content stretch on tablet pc

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - Align content around on hover on pc
- `.hover:pc:align-content-between` - Align content between on hover on pc
- `.hover:pc:align-content-center` - Align content center on hover on pc
- `.hover:pc:align-content-end` - Align content end on hover on pc
- `.hover:pc:align-content-evenly` - Align content evenly on hover on pc
- `.hover:pc:align-content-start` - Align content start on hover on pc
- `.hover:pc:align-content-stretch` - Align content stretch on hover on pc
- `.pc:align-content-around` - Align content around on pc
- `.pc:align-content-between` - Align content between on pc
- `.pc:align-content-center` - Align content center on pc
- `.pc:align-content-end` - Align content end on pc
- `.pc:align-content-evenly` - Align content evenly on pc
- `.pc:align-content-start` - Align content start on pc
- `.pc:align-content-stretch` - Align content stretch on pc

##### Align content - Tv (>= 1200px)

- `.hover:tv:align-content-around` - Align content around on hover on tv
- `.hover:tv:align-content-between` - Align content between on hover on tv
- `.hover:tv:align-content-center` - Align content center on hover on tv
- `.hover:tv:align-content-end` - Align content end on hover on tv
- `.hover:tv:align-content-evenly` - Align content evenly on hover on tv
- `.hover:tv:align-content-start` - Align content start on hover on tv
- `.hover:tv:align-content-stretch` - Align content stretch on hover on tv
- `.tv:align-content-around` - Align content around on tv
- `.tv:align-content-between` - Align content between on tv
- `.tv:align-content-center` - Align content center on tv
- `.tv:align-content-end` - Align content end on tv
- `.tv:align-content-evenly` - Align content evenly on tv
- `.tv:align-content-start` - Align content start on tv
- `.tv:align-content-stretch` - Align content stretch on tv

##### Align content - Tablet Max (<= 768px)

- `.hover:tablet-max:align-content-around` - Align content around on hover on tablet max
- `.hover:tablet-max:align-content-between` - Align content between on hover on tablet max
- `.hover:tablet-max:align-content-center` - Align content center on hover on tablet max
- `.hover:tablet-max:align-content-end` - Align content end on hover on tablet max
- `.hover:tablet-max:align-content-evenly` - Align content evenly on hover on tablet max
- `.hover:tablet-max:align-content-start` - Align content start on hover on tablet max
- `.hover:tablet-max:align-content-stretch` - Align content stretch on hover on tablet max
- `.tablet-max:align-content-around` - Align content around on tablet max
- `.tablet-max:align-content-between` - Align content between on tablet max
- `.tablet-max:align-content-center` - Align content center on tablet max
- `.tablet-max:align-content-end` - Align content end on tablet max
- `.tablet-max:align-content-evenly` - Align content evenly on tablet max
- `.tablet-max:align-content-start` - Align content start on tablet max
- `.tablet-max:align-content-stretch` - Align content stretch on tablet max

##### Align content - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-content-around` - Align content around on hover on tablet pc max
- `.hover:tablet-pc-max:align-content-between` - Align content between on hover on tablet pc max
- `.hover:tablet-pc-max:align-content-center` - Align content center on hover on tablet pc max
- `.hover:tablet-pc-max:align-content-end` - Align content end on hover on tablet pc max
- `.hover:tablet-pc-max:align-content-evenly` - Align content evenly on hover on tablet pc max
- `.hover:tablet-pc-max:align-content-start` - Align content start on hover on tablet pc max
- `.hover:tablet-pc-max:align-content-stretch` - Align content stretch on hover on tablet pc max
- `.tablet-pc-max:align-content-around` - Align content around on tablet pc max
- `.tablet-pc-max:align-content-between` - Align content between on tablet pc max
- `.tablet-pc-max:align-content-center` - Align content center on tablet pc max
- `.tablet-pc-max:align-content-end` - Align content end on tablet pc max
- `.tablet-pc-max:align-content-evenly` - Align content evenly on tablet pc max
- `.tablet-pc-max:align-content-start` - Align content start on tablet pc max
- `.tablet-pc-max:align-content-stretch` - Align content stretch on tablet pc max

##### Align content - Pc Max (<= 1200px)

- `.hover:pc-max:align-content-around` - Align content around on hover on pc max
- `.hover:pc-max:align-content-between` - Align content between on hover on pc max
- `.hover:pc-max:align-content-center` - Align content center on hover on pc max
- `.hover:pc-max:align-content-end` - Align content end on hover on pc max
- `.hover:pc-max:align-content-evenly` - Align content evenly on hover on pc max
- `.hover:pc-max:align-content-start` - Align content start on hover on pc max
- `.hover:pc-max:align-content-stretch` - Align content stretch on hover on pc max
- `.pc-max:align-content-around` - Align content around on pc max
- `.pc-max:align-content-between` - Align content between on pc max
- `.pc-max:align-content-center` - Align content center on pc max
- `.pc-max:align-content-end` - Align content end on pc max
- `.pc-max:align-content-evenly` - Align content evenly on pc max
- `.pc-max:align-content-start` - Align content start on pc max
- `.pc-max:align-content-stretch` - Align content stretch on pc max

### Align items

- `.align-items-center` - Align items center
- `.align-items-end` - Align items end
- `.align-items-start` - Align items start
- `.align-items-stretch` - Align items stretch
- `.hover:align-items-center` - Align items center on hover
- `.hover:align-items-end` - Align items end on hover
- `.hover:align-items-start` - Align items start on hover
- `.hover:align-items-stretch` - Align items stretch on hover

##### Align items - Mobile (<= 480px)

- `.hover:mobile:align-items-center` - Align items center on hover on mobile
- `.hover:mobile:align-items-end` - Align items end on hover on mobile
- `.hover:mobile:align-items-start` - Align items start on hover on mobile
- `.hover:mobile:align-items-stretch` - Align items stretch on hover on mobile
- `.mobile:align-items-center` - Align items center on mobile
- `.mobile:align-items-end` - Align items end on mobile
- `.mobile:align-items-start` - Align items start on mobile
- `.mobile:align-items-stretch` - Align items stretch on mobile

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - Align items center on hover on tablet
- `.hover:tablet:align-items-end` - Align items end on hover on tablet
- `.hover:tablet:align-items-start` - Align items start on hover on tablet
- `.hover:tablet:align-items-stretch` - Align items stretch on hover on tablet
- `.tablet:align-items-center` - Align items center on tablet
- `.tablet:align-items-end` - Align items end on tablet
- `.tablet:align-items-start` - Align items start on tablet
- `.tablet:align-items-stretch` - Align items stretch on tablet

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - Align items center on hover on tablet pc
- `.hover:tablet-pc:align-items-end` - Align items end on hover on tablet pc
- `.hover:tablet-pc:align-items-start` - Align items start on hover on tablet pc
- `.hover:tablet-pc:align-items-stretch` - Align items stretch on hover on tablet pc
- `.tablet-pc:align-items-center` - Align items center on tablet pc
- `.tablet-pc:align-items-end` - Align items end on tablet pc
- `.tablet-pc:align-items-start` - Align items start on tablet pc
- `.tablet-pc:align-items-stretch` - Align items stretch on tablet pc

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - Align items center on hover on pc
- `.hover:pc:align-items-end` - Align items end on hover on pc
- `.hover:pc:align-items-start` - Align items start on hover on pc
- `.hover:pc:align-items-stretch` - Align items stretch on hover on pc
- `.pc:align-items-center` - Align items center on pc
- `.pc:align-items-end` - Align items end on pc
- `.pc:align-items-start` - Align items start on pc
- `.pc:align-items-stretch` - Align items stretch on pc

##### Align items - Tv (>= 1200px)

- `.hover:tv:align-items-center` - Align items center on hover on tv
- `.hover:tv:align-items-end` - Align items end on hover on tv
- `.hover:tv:align-items-start` - Align items start on hover on tv
- `.hover:tv:align-items-stretch` - Align items stretch on hover on tv
- `.tv:align-items-center` - Align items center on tv
- `.tv:align-items-end` - Align items end on tv
- `.tv:align-items-start` - Align items start on tv
- `.tv:align-items-stretch` - Align items stretch on tv

##### Align items - Tablet Max (<= 768px)

- `.hover:tablet-max:align-items-center` - Align items center on hover on tablet max
- `.hover:tablet-max:align-items-end` - Align items end on hover on tablet max
- `.hover:tablet-max:align-items-start` - Align items start on hover on tablet max
- `.hover:tablet-max:align-items-stretch` - Align items stretch on hover on tablet max
- `.tablet-max:align-items-center` - Align items center on tablet max
- `.tablet-max:align-items-end` - Align items end on tablet max
- `.tablet-max:align-items-start` - Align items start on tablet max
- `.tablet-max:align-items-stretch` - Align items stretch on tablet max

##### Align items - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-items-center` - Align items center on hover on tablet pc max
- `.hover:tablet-pc-max:align-items-end` - Align items end on hover on tablet pc max
- `.hover:tablet-pc-max:align-items-start` - Align items start on hover on tablet pc max
- `.hover:tablet-pc-max:align-items-stretch` - Align items stretch on hover on tablet pc max
- `.tablet-pc-max:align-items-center` - Align items center on tablet pc max
- `.tablet-pc-max:align-items-end` - Align items end on tablet pc max
- `.tablet-pc-max:align-items-start` - Align items start on tablet pc max
- `.tablet-pc-max:align-items-stretch` - Align items stretch on tablet pc max

##### Align items - Pc Max (<= 1200px)

- `.hover:pc-max:align-items-center` - Align items center on hover on pc max
- `.hover:pc-max:align-items-end` - Align items end on hover on pc max
- `.hover:pc-max:align-items-start` - Align items start on hover on pc max
- `.hover:pc-max:align-items-stretch` - Align items stretch on hover on pc max
- `.pc-max:align-items-center` - Align items center on pc max
- `.pc-max:align-items-end` - Align items end on pc max
- `.pc-max:align-items-start` - Align items start on pc max
- `.pc-max:align-items-stretch` - Align items stretch on pc max

### Align self

- `.align-self-center` - Align self center
- `.align-self-end` - Align self end
- `.align-self-start` - Align self start
- `.align-self-stretch` - Align self stretch
- `.hover:align-self-center` - Align self center on hover
- `.hover:align-self-end` - Align self end on hover
- `.hover:align-self-start` - Align self start on hover
- `.hover:align-self-stretch` - Align self stretch on hover

##### Align self - Mobile (<= 480px)

- `.hover:mobile:align-self-center` - Align self center on hover on mobile
- `.hover:mobile:align-self-end` - Align self end on hover on mobile
- `.hover:mobile:align-self-start` - Align self start on hover on mobile
- `.hover:mobile:align-self-stretch` - Align self stretch on hover on mobile
- `.mobile:align-self-center` - Align self center on mobile
- `.mobile:align-self-end` - Align self end on mobile
- `.mobile:align-self-start` - Align self start on mobile
- `.mobile:align-self-stretch` - Align self stretch on mobile

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - Align self center on hover on tablet
- `.hover:tablet:align-self-end` - Align self end on hover on tablet
- `.hover:tablet:align-self-start` - Align self start on hover on tablet
- `.hover:tablet:align-self-stretch` - Align self stretch on hover on tablet
- `.tablet:align-self-center` - Align self center on tablet
- `.tablet:align-self-end` - Align self end on tablet
- `.tablet:align-self-start` - Align self start on tablet
- `.tablet:align-self-stretch` - Align self stretch on tablet

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - Align self center on hover on tablet pc
- `.hover:tablet-pc:align-self-end` - Align self end on hover on tablet pc
- `.hover:tablet-pc:align-self-start` - Align self start on hover on tablet pc
- `.hover:tablet-pc:align-self-stretch` - Align self stretch on hover on tablet pc
- `.tablet-pc:align-self-center` - Align self center on tablet pc
- `.tablet-pc:align-self-end` - Align self end on tablet pc
- `.tablet-pc:align-self-start` - Align self start on tablet pc
- `.tablet-pc:align-self-stretch` - Align self stretch on tablet pc

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - Align self center on hover on pc
- `.hover:pc:align-self-end` - Align self end on hover on pc
- `.hover:pc:align-self-start` - Align self start on hover on pc
- `.hover:pc:align-self-stretch` - Align self stretch on hover on pc
- `.pc:align-self-center` - Align self center on pc
- `.pc:align-self-end` - Align self end on pc
- `.pc:align-self-start` - Align self start on pc
- `.pc:align-self-stretch` - Align self stretch on pc

##### Align self - Tv (>= 1200px)

- `.hover:tv:align-self-center` - Align self center on hover on tv
- `.hover:tv:align-self-end` - Align self end on hover on tv
- `.hover:tv:align-self-start` - Align self start on hover on tv
- `.hover:tv:align-self-stretch` - Align self stretch on hover on tv
- `.tv:align-self-center` - Align self center on tv
- `.tv:align-self-end` - Align self end on tv
- `.tv:align-self-start` - Align self start on tv
- `.tv:align-self-stretch` - Align self stretch on tv

##### Align self - Tablet Max (<= 768px)

- `.hover:tablet-max:align-self-center` - Align self center on hover on tablet max
- `.hover:tablet-max:align-self-end` - Align self end on hover on tablet max
- `.hover:tablet-max:align-self-start` - Align self start on hover on tablet max
- `.hover:tablet-max:align-self-stretch` - Align self stretch on hover on tablet max
- `.tablet-max:align-self-center` - Align self center on tablet max
- `.tablet-max:align-self-end` - Align self end on tablet max
- `.tablet-max:align-self-start` - Align self start on tablet max
- `.tablet-max:align-self-stretch` - Align self stretch on tablet max

##### Align self - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-self-center` - Align self center on hover on tablet pc max
- `.hover:tablet-pc-max:align-self-end` - Align self end on hover on tablet pc max
- `.hover:tablet-pc-max:align-self-start` - Align self start on hover on tablet pc max
- `.hover:tablet-pc-max:align-self-stretch` - Align self stretch on hover on tablet pc max
- `.tablet-pc-max:align-self-center` - Align self center on tablet pc max
- `.tablet-pc-max:align-self-end` - Align self end on tablet pc max
- `.tablet-pc-max:align-self-start` - Align self start on tablet pc max
- `.tablet-pc-max:align-self-stretch` - Align self stretch on tablet pc max

##### Align self - Pc Max (<= 1200px)

- `.hover:pc-max:align-self-center` - Align self center on hover on pc max
- `.hover:pc-max:align-self-end` - Align self end on hover on pc max
- `.hover:pc-max:align-self-start` - Align self start on hover on pc max
- `.hover:pc-max:align-self-stretch` - Align self stretch on hover on pc max
- `.pc-max:align-self-center` - Align self center on pc max
- `.pc-max:align-self-end` - Align self end on pc max
- `.pc-max:align-self-start` - Align self start on pc max
- `.pc-max:align-self-stretch` - Align self stretch on pc max

### Justify content

- `.hover:justify-content-around` - Justify content around on hover
- `.hover:justify-content-between` - Justify content between on hover
- `.hover:justify-content-center` - Justify content center on hover
- `.hover:justify-content-end` - Justify content end on hover
- `.hover:justify-content-evenly` - Justify content evenly on hover
- `.hover:justify-content-start` - Justify content start on hover
- `.hover:justify-content-stretch` - Justify content stretch on hover
- `.justify-content-around` - Justify content around
- `.justify-content-between` - Justify content between
- `.justify-content-center` - Justify content center
- `.justify-content-end` - Justify content end
- `.justify-content-evenly` - Justify content evenly
- `.justify-content-start` - Justify content start
- `.justify-content-stretch` - Justify content stretch

##### Justify content - Mobile (<= 480px)

- `.hover:mobile:justify-content-around` - Justify content around on hover on mobile
- `.hover:mobile:justify-content-between` - Justify content between on hover on mobile
- `.hover:mobile:justify-content-center` - Justify content center on hover on mobile
- `.hover:mobile:justify-content-end` - Justify content end on hover on mobile
- `.hover:mobile:justify-content-start` - Justify content start on hover on mobile
- `.mobile:justify-content-around` - Justify content around on mobile
- `.mobile:justify-content-between` - Justify content between on mobile
- `.mobile:justify-content-center` - Justify content center on mobile
- `.mobile:justify-content-end` - Justify content end on mobile
- `.mobile:justify-content-start` - Justify content start on mobile

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - Justify content around on hover on tablet
- `.hover:tablet:justify-content-between` - Justify content between on hover on tablet
- `.hover:tablet:justify-content-center` - Justify content center on hover on tablet
- `.hover:tablet:justify-content-end` - Justify content end on hover on tablet
- `.hover:tablet:justify-content-start` - Justify content start on hover on tablet
- `.tablet:justify-content-around` - Justify content around on tablet
- `.tablet:justify-content-between` - Justify content between on tablet
- `.tablet:justify-content-center` - Justify content center on tablet
- `.tablet:justify-content-end` - Justify content end on tablet
- `.tablet:justify-content-start` - Justify content start on tablet

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - Justify content around on hover on tablet pc
- `.hover:tablet-pc:justify-content-between` - Justify content between on hover on tablet pc
- `.hover:tablet-pc:justify-content-center` - Justify content center on hover on tablet pc
- `.hover:tablet-pc:justify-content-end` - Justify content end on hover on tablet pc
- `.hover:tablet-pc:justify-content-start` - Justify content start on hover on tablet pc
- `.tablet-pc:justify-content-around` - Justify content around on tablet pc
- `.tablet-pc:justify-content-between` - Justify content between on tablet pc
- `.tablet-pc:justify-content-center` - Justify content center on tablet pc
- `.tablet-pc:justify-content-end` - Justify content end on tablet pc
- `.tablet-pc:justify-content-start` - Justify content start on tablet pc

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - Justify content around on hover on pc
- `.hover:pc:justify-content-between` - Justify content between on hover on pc
- `.hover:pc:justify-content-center` - Justify content center on hover on pc
- `.hover:pc:justify-content-end` - Justify content end on hover on pc
- `.hover:pc:justify-content-start` - Justify content start on hover on pc
- `.pc:justify-content-around` - Justify content around on pc
- `.pc:justify-content-between` - Justify content between on pc
- `.pc:justify-content-center` - Justify content center on pc
- `.pc:justify-content-end` - Justify content end on pc
- `.pc:justify-content-start` - Justify content start on pc

##### Justify content - Tv (>= 1200px)

- `.hover:tv:justify-content-around` - Justify content around on hover on tv
- `.hover:tv:justify-content-between` - Justify content between on hover on tv
- `.hover:tv:justify-content-center` - Justify content center on hover on tv
- `.hover:tv:justify-content-end` - Justify content end on hover on tv
- `.hover:tv:justify-content-start` - Justify content start on hover on tv
- `.tv:justify-content-around` - Justify content around on tv
- `.tv:justify-content-between` - Justify content between on tv
- `.tv:justify-content-center` - Justify content center on tv
- `.tv:justify-content-end` - Justify content end on tv
- `.tv:justify-content-start` - Justify content start on tv

##### Justify content - Tablet Max (<= 768px)

- `.hover:tablet-max:justify-content-around` - Justify content around on hover on tablet max
- `.hover:tablet-max:justify-content-between` - Justify content between on hover on tablet max
- `.hover:tablet-max:justify-content-center` - Justify content center on hover on tablet max
- `.hover:tablet-max:justify-content-end` - Justify content end on hover on tablet max
- `.hover:tablet-max:justify-content-start` - Justify content start on hover on tablet max
- `.tablet-max:justify-content-around` - Justify content around on tablet max
- `.tablet-max:justify-content-between` - Justify content between on tablet max
- `.tablet-max:justify-content-center` - Justify content center on tablet max
- `.tablet-max:justify-content-end` - Justify content end on tablet max
- `.tablet-max:justify-content-start` - Justify content start on tablet max

##### Justify content - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:justify-content-around` - Justify content around on hover on tablet pc max
- `.hover:tablet-pc-max:justify-content-between` - Justify content between on hover on tablet pc max
- `.hover:tablet-pc-max:justify-content-center` - Justify content center on hover on tablet pc max
- `.hover:tablet-pc-max:justify-content-end` - Justify content end on hover on tablet pc max
- `.hover:tablet-pc-max:justify-content-start` - Justify content start on hover on tablet pc max
- `.tablet-pc-max:justify-content-around` - Justify content around on tablet pc max
- `.tablet-pc-max:justify-content-between` - Justify content between on tablet pc max
- `.tablet-pc-max:justify-content-center` - Justify content center on tablet pc max
- `.tablet-pc-max:justify-content-end` - Justify content end on tablet pc max
- `.tablet-pc-max:justify-content-start` - Justify content start on tablet pc max

##### Justify content - Pc Max (<= 1200px)

- `.hover:pc-max:justify-content-around` - Justify content around on hover on pc max
- `.hover:pc-max:justify-content-between` - Justify content between on hover on pc max
- `.hover:pc-max:justify-content-center` - Justify content center on hover on pc max
- `.hover:pc-max:justify-content-end` - Justify content end on hover on pc max
- `.hover:pc-max:justify-content-start` - Justify content start on hover on pc max
- `.pc-max:justify-content-around` - Justify content around on pc max
- `.pc-max:justify-content-between` - Justify content between on pc max
- `.pc-max:justify-content-center` - Justify content center on pc max
- `.pc-max:justify-content-end` - Justify content end on pc max
- `.pc-max:justify-content-start` - Justify content start on pc max

### Justify items

- `.hover:justify-items-center` - Justify items center on hover
- `.hover:justify-items-end` - Justify items end on hover
- `.hover:justify-items-start` - Justify items start on hover
- `.hover:justify-items-stretch` - Justify items stretch on hover
- `.justify-items-center` - Justify items center
- `.justify-items-end` - Justify items end
- `.justify-items-start` - Justify items start
- `.justify-items-stretch` - Justify items stretch

### Order

- `.hover:order-5` - Order 5 on hover
- `.hover:order-4` - Order 4 on hover
- `.hover:order-3` - Order 3 on hover
- `.hover:order-2` - Order 2 on hover
- `.hover:order-1` - Order 1 on hover
- `.hover:order-0` - Order 0 on hover
- `.hover:order-first` - Order first on hover
- `.hover:order-last` - Order last on hover
- `.order-5` - Order 5
- `.order-4` - Order 4
- `.order-3` - Order 3
- `.order-2` - Order 2
- `.order-1` - Order 1
- `.order-0` - Order 0
- `.order-first` - Order first
- `.order-last` - Order last

##### Negative Order

- `.-order-5` - Negative Order 5
- `.-order-4` - Negative Order 4
- `.-order-3` - Negative Order 3
- `.-order-2` - Negative Order 2
- `.-order-1` - Negative Order 1
- `.hover:-order-5` - Negative Order 5 on hover
- `.hover:-order-4` - Negative Order 4 on hover
- `.hover:-order-3` - Negative Order 3 on hover
- `.hover:-order-2` - Negative Order 2 on hover
- `.hover:-order-1` - Negative Order 1 on hover

##### Order - Mobile (<= 480px)

- `.hover:mobile:order-5` - Order 5 on hover on mobile
- `.hover:mobile:order-4` - Order 4 on hover on mobile
- `.hover:mobile:order-3` - Order 3 on hover on mobile
- `.hover:mobile:order-2` - Order 2 on hover on mobile
- `.hover:mobile:order-1` - Order 1 on hover on mobile
- `.hover:mobile:order-0` - Order 0 on hover on mobile
- `.hover:mobile:order-first` - Order first on hover on mobile
- `.hover:mobile:order-last` - Order last on hover on mobile
- `.mobile:order-5` - Order 5 on mobile
- `.mobile:order-4` - Order 4 on mobile
- `.mobile:order-3` - Order 3 on mobile
- `.mobile:order-2` - Order 2 on mobile
- `.mobile:order-1` - Order 1 on mobile
- `.mobile:order-0` - Order 0 on mobile
- `.mobile:order-first` - Order first on mobile
- `.mobile:order-last` - Order last on mobile

##### Negative Order - Mobile (<= 480px)

- `.hover:mobile:-order-5` - Negative Order 5 on hover on mobile
- `.hover:mobile:-order-4` - Negative Order 4 on hover on mobile
- `.hover:mobile:-order-3` - Negative Order 3 on hover on mobile
- `.hover:mobile:-order-2` - Negative Order 2 on hover on mobile
- `.hover:mobile:-order-1` - Negative Order 1 on hover on mobile
- `.mobile:-order-5` - Negative Order 5 on mobile
- `.mobile:-order-4` - Negative Order 4 on mobile
- `.mobile:-order-3` - Negative Order 3 on mobile
- `.mobile:-order-2` - Negative Order 2 on mobile
- `.mobile:-order-1` - Negative Order 1 on mobile

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - Order 5 on hover on tablet
- `.hover:tablet:order-4` - Order 4 on hover on tablet
- `.hover:tablet:order-3` - Order 3 on hover on tablet
- `.hover:tablet:order-2` - Order 2 on hover on tablet
- `.hover:tablet:order-1` - Order 1 on hover on tablet
- `.hover:tablet:order-0` - Order 0 on hover on tablet
- `.hover:tablet:order-first` - Order first on hover on tablet
- `.hover:tablet:order-last` - Order last on hover on tablet
- `.tablet:order-5` - Order 5 on tablet
- `.tablet:order-4` - Order 4 on tablet
- `.tablet:order-3` - Order 3 on tablet
- `.tablet:order-2` - Order 2 on tablet
- `.tablet:order-1` - Order 1 on tablet
- `.tablet:order-0` - Order 0 on tablet
- `.tablet:order-first` - Order first on tablet
- `.tablet:order-last` - Order last on tablet

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - Negative Order 5 on hover on tablet
- `.hover:tablet:-order-4` - Negative Order 4 on hover on tablet
- `.hover:tablet:-order-3` - Negative Order 3 on hover on tablet
- `.hover:tablet:-order-2` - Negative Order 2 on hover on tablet
- `.hover:tablet:-order-1` - Negative Order 1 on hover on tablet
- `.tablet:-order-5` - Negative Order 5 on tablet
- `.tablet:-order-4` - Negative Order 4 on tablet
- `.tablet:-order-3` - Negative Order 3 on tablet
- `.tablet:-order-2` - Negative Order 2 on tablet
- `.tablet:-order-1` - Negative Order 1 on tablet

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - Order 5 on hover on tablet pc
- `.hover:tablet-pc:order-4` - Order 4 on hover on tablet pc
- `.hover:tablet-pc:order-3` - Order 3 on hover on tablet pc
- `.hover:tablet-pc:order-2` - Order 2 on hover on tablet pc
- `.hover:tablet-pc:order-1` - Order 1 on hover on tablet pc
- `.hover:tablet-pc:order-0` - Order 0 on hover on tablet pc
- `.hover:tablet-pc:order-first` - Order first on hover on tablet pc
- `.hover:tablet-pc:order-last` - Order last on hover on tablet pc
- `.tablet-pc:order-5` - Order 5 on tablet pc
- `.tablet-pc:order-4` - Order 4 on tablet pc
- `.tablet-pc:order-3` - Order 3 on tablet pc
- `.tablet-pc:order-2` - Order 2 on tablet pc
- `.tablet-pc:order-1` - Order 1 on tablet pc
- `.tablet-pc:order-0` - Order 0 on tablet pc
- `.tablet-pc:order-first` - Order first on tablet pc
- `.tablet-pc:order-last` - Order last on tablet pc

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - Negative Order 5 on hover on tablet pc
- `.hover:tablet-pc:-order-4` - Negative Order 4 on hover on tablet pc
- `.hover:tablet-pc:-order-3` - Negative Order 3 on hover on tablet pc
- `.hover:tablet-pc:-order-2` - Negative Order 2 on hover on tablet pc
- `.hover:tablet-pc:-order-1` - Negative Order 1 on hover on tablet pc
- `.tablet-pc:-order-5` - Negative Order 5 on tablet pc
- `.tablet-pc:-order-4` - Negative Order 4 on tablet pc
- `.tablet-pc:-order-3` - Negative Order 3 on tablet pc
- `.tablet-pc:-order-2` - Negative Order 2 on tablet pc
- `.tablet-pc:-order-1` - Negative Order 1 on tablet pc

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - Order 5 on hover on pc
- `.hover:pc:order-4` - Order 4 on hover on pc
- `.hover:pc:order-3` - Order 3 on hover on pc
- `.hover:pc:order-2` - Order 2 on hover on pc
- `.hover:pc:order-1` - Order 1 on hover on pc
- `.hover:pc:order-0` - Order 0 on hover on pc
- `.hover:pc:order-first` - Order first on hover on pc
- `.hover:pc:order-last` - Order last on hover on pc
- `.pc:order-5` - Order 5 on pc
- `.pc:order-4` - Order 4 on pc
- `.pc:order-3` - Order 3 on pc
- `.pc:order-2` - Order 2 on pc
- `.pc:order-1` - Order 1 on pc
- `.pc:order-0` - Order 0 on pc
- `.pc:order-first` - Order first on pc
- `.pc:order-last` - Order last on pc

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - Negative Order 5 on hover on pc
- `.hover:pc:-order-4` - Negative Order 4 on hover on pc
- `.hover:pc:-order-3` - Negative Order 3 on hover on pc
- `.hover:pc:-order-2` - Negative Order 2 on hover on pc
- `.hover:pc:-order-1` - Negative Order 1 on hover on pc
- `.pc:-order-5` - Negative Order 5 on pc
- `.pc:-order-4` - Negative Order 4 on pc
- `.pc:-order-3` - Negative Order 3 on pc
- `.pc:-order-2` - Negative Order 2 on pc
- `.pc:-order-1` - Negative Order 1 on pc

##### Order - Tv (>= 1200px)

- `.hover:tv:order-5` - Order 5 on hover on tv
- `.hover:tv:order-4` - Order 4 on hover on tv
- `.hover:tv:order-3` - Order 3 on hover on tv
- `.hover:tv:order-2` - Order 2 on hover on tv
- `.hover:tv:order-1` - Order 1 on hover on tv
- `.hover:tv:order-0` - Order 0 on hover on tv
- `.hover:tv:order-first` - Order first on hover on tv
- `.hover:tv:order-last` - Order last on hover on tv
- `.tv:order-5` - Order 5 on tv
- `.tv:order-4` - Order 4 on tv
- `.tv:order-3` - Order 3 on tv
- `.tv:order-2` - Order 2 on tv
- `.tv:order-1` - Order 1 on tv
- `.tv:order-0` - Order 0 on tv
- `.tv:order-first` - Order first on tv
- `.tv:order-last` - Order last on tv

##### Negative Order - Tv (>= 1200px)

- `.hover:tv:-order-5` - Negative Order 5 on hover on tv
- `.hover:tv:-order-4` - Negative Order 4 on hover on tv
- `.hover:tv:-order-3` - Negative Order 3 on hover on tv
- `.hover:tv:-order-2` - Negative Order 2 on hover on tv
- `.hover:tv:-order-1` - Negative Order 1 on hover on tv
- `.tv:-order-5` - Negative Order 5 on tv
- `.tv:-order-4` - Negative Order 4 on tv
- `.tv:-order-3` - Negative Order 3 on tv
- `.tv:-order-2` - Negative Order 2 on tv
- `.tv:-order-1` - Negative Order 1 on tv

##### Order - Tablet Max (<= 768px)

- `.hover:tablet-max:order-5` - Order 5 on hover on tablet max
- `.hover:tablet-max:order-4` - Order 4 on hover on tablet max
- `.hover:tablet-max:order-3` - Order 3 on hover on tablet max
- `.hover:tablet-max:order-2` - Order 2 on hover on tablet max
- `.hover:tablet-max:order-1` - Order 1 on hover on tablet max
- `.hover:tablet-max:order-0` - Order 0 on hover on tablet max
- `.hover:tablet-max:order-first` - Order first on hover on tablet max
- `.hover:tablet-max:order-last` - Order last on hover on tablet max
- `.tablet-max:order-5` - Order 5 on tablet max
- `.tablet-max:order-4` - Order 4 on tablet max
- `.tablet-max:order-3` - Order 3 on tablet max
- `.tablet-max:order-2` - Order 2 on tablet max
- `.tablet-max:order-1` - Order 1 on tablet max
- `.tablet-max:order-0` - Order 0 on tablet max
- `.tablet-max:order-first` - Order first on tablet max
- `.tablet-max:order-last` - Order last on tablet max

##### Negative Order - Tablet Max (<= 768px)

- `.hover:tablet-max:-order-5` - Negative Order 5 on hover on tablet max
- `.hover:tablet-max:-order-4` - Negative Order 4 on hover on tablet max
- `.hover:tablet-max:-order-3` - Negative Order 3 on hover on tablet max
- `.hover:tablet-max:-order-2` - Negative Order 2 on hover on tablet max
- `.hover:tablet-max:-order-1` - Negative Order 1 on hover on tablet max
- `.tablet-max:-order-5` - Negative Order 5 on tablet max
- `.tablet-max:-order-4` - Negative Order 4 on tablet max
- `.tablet-max:-order-3` - Negative Order 3 on tablet max
- `.tablet-max:-order-2` - Negative Order 2 on tablet max
- `.tablet-max:-order-1` - Negative Order 1 on tablet max

##### Order - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:order-5` - Order 5 on hover on tablet pc max
- `.hover:tablet-pc-max:order-4` - Order 4 on hover on tablet pc max
- `.hover:tablet-pc-max:order-3` - Order 3 on hover on tablet pc max
- `.hover:tablet-pc-max:order-2` - Order 2 on hover on tablet pc max
- `.hover:tablet-pc-max:order-1` - Order 1 on hover on tablet pc max
- `.hover:tablet-pc-max:order-0` - Order 0 on hover on tablet pc max
- `.hover:tablet-pc-max:order-first` - Order first on hover on tablet pc max
- `.hover:tablet-pc-max:order-last` - Order last on hover on tablet pc max
- `.tablet-pc-max:order-5` - Order 5 on tablet pc max
- `.tablet-pc-max:order-4` - Order 4 on tablet pc max
- `.tablet-pc-max:order-3` - Order 3 on tablet pc max
- `.tablet-pc-max:order-2` - Order 2 on tablet pc max
- `.tablet-pc-max:order-1` - Order 1 on tablet pc max
- `.tablet-pc-max:order-0` - Order 0 on tablet pc max
- `.tablet-pc-max:order-first` - Order first on tablet pc max
- `.tablet-pc-max:order-last` - Order last on tablet pc max

##### Negative Order - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:-order-5` - Negative Order 5 on hover on tablet pc max
- `.hover:tablet-pc-max:-order-4` - Negative Order 4 on hover on tablet pc max
- `.hover:tablet-pc-max:-order-3` - Negative Order 3 on hover on tablet pc max
- `.hover:tablet-pc-max:-order-2` - Negative Order 2 on hover on tablet pc max
- `.hover:tablet-pc-max:-order-1` - Negative Order 1 on hover on tablet pc max
- `.tablet-pc-max:-order-5` - Negative Order 5 on tablet pc max
- `.tablet-pc-max:-order-4` - Negative Order 4 on tablet pc max
- `.tablet-pc-max:-order-3` - Negative Order 3 on tablet pc max
- `.tablet-pc-max:-order-2` - Negative Order 2 on tablet pc max
- `.tablet-pc-max:-order-1` - Negative Order 1 on tablet pc max

##### Order - Pc Max (<= 1200px)

- `.hover:pc-max:order-5` - Order 5 on hover on pc max
- `.hover:pc-max:order-4` - Order 4 on hover on pc max
- `.hover:pc-max:order-3` - Order 3 on hover on pc max
- `.hover:pc-max:order-2` - Order 2 on hover on pc max
- `.hover:pc-max:order-1` - Order 1 on hover on pc max
- `.hover:pc-max:order-0` - Order 0 on hover on pc max
- `.hover:pc-max:order-first` - Order first on hover on pc max
- `.hover:pc-max:order-last` - Order last on hover on pc max
- `.pc-max:order-5` - Order 5 on pc max
- `.pc-max:order-4` - Order 4 on pc max
- `.pc-max:order-3` - Order 3 on pc max
- `.pc-max:order-2` - Order 2 on pc max
- `.pc-max:order-1` - Order 1 on pc max
- `.pc-max:order-0` - Order 0 on pc max
- `.pc-max:order-first` - Order first on pc max
- `.pc-max:order-last` - Order last on pc max

##### Negative Order - Pc Max (<= 1200px)

- `.hover:pc-max:-order-5` - Negative Order 5 on hover on pc max
- `.hover:pc-max:-order-4` - Negative Order 4 on hover on pc max
- `.hover:pc-max:-order-3` - Negative Order 3 on hover on pc max
- `.hover:pc-max:-order-2` - Negative Order 2 on hover on pc max
- `.hover:pc-max:-order-1` - Negative Order 1 on hover on pc max
- `.pc-max:-order-5` - Negative Order 5 on pc max
- `.pc-max:-order-4` - Negative Order 4 on pc max
- `.pc-max:-order-3` - Negative Order 3 on pc max
- `.pc-max:-order-2` - Negative Order 2 on pc max
- `.pc-max:-order-1` - Negative Order 1 on pc max

## Spacing

### Margin

#### Margin All

- `.first:m-0` - Margin All 0rem on first
- `.hover:m-5` - Margin All 5rem on hover
- `.hover:m-4.5` - Margin All 0rem on hover
- `.hover:m-4` - Margin All 4rem on hover
- `.hover:m-3.5` - Margin All 0rem on hover
- `.hover:m-3` - Margin All 3rem on hover
- `.hover:m-2.5` - Margin All 0rem on hover
- `.hover:m-2` - Margin All 2rem on hover
- `.hover:m-1.9` - Margin All 0rem on hover
- `.hover:m-1.8` - Margin All 0rem on hover
- `.hover:m-1.7` - Margin All 0rem on hover
- `.hover:m-1.6` - Margin All 0rem on hover
- `.hover:m-1.5` - Margin All 0rem on hover
- `.hover:m-1.4` - Margin All 0rem on hover
- `.hover:m-1.3` - Margin All 0rem on hover
- `.hover:m-1.2` - Margin All 0rem on hover
- `.hover:m-1.1` - Margin All 0rem on hover
- `.hover:m-1` - Margin All 1rem on hover
- `.hover:m-0.9` - Margin All 0rem on hover
- `.hover:m-0.8` - Margin All 0rem on hover
- `.hover:m-0.7` - Margin All 0rem on hover
- `.hover:m-0.6` - Margin All 0rem on hover
- `.hover:m-0.5` - Margin All 0rem on hover
- `.hover:m-0.4` - Margin All 0rem on hover
- `.hover:m-0.3` - Margin All 0rem on hover
- `.hover:m-0.2` - Margin All 0.2rem on hover
- `.hover:m-0.1` - Margin All 0.1rem on hover
- `.hover:m-0` - Margin All 0rem on hover
- `.hover:m-auto` - Margin All auto on hover
- `.last:m-0` - Margin All 0rem on last
- `.m-5` - Margin All 5rem
- `.m-4.5` - Margin All 0rem
- `.m-4` - Margin All 4rem
- `.m-3.5` - Margin All 0rem
- `.m-3` - Margin All 3rem
- `.m-2.5` - Margin All 0rem
- `.m-2` - Margin All 2rem
- `.m-1.9` - Margin All 0rem
- `.m-1.8` - Margin All 0rem
- `.m-1.7` - Margin All 0rem
- `.m-1.6` - Margin All 0rem
- `.m-1.5` - Margin All 0rem
- `.m-1.4` - Margin All 0rem
- `.m-1.3` - Margin All 0rem
- `.m-1.2` - Margin All 0rem
- `.m-1.1` - Margin All 0rem
- `.m-1` - Margin All 1rem
- `.m-0.9` - Margin All 0rem
- `.m-0.8` - Margin All 0rem
- `.m-0.7` - Margin All 0rem
- `.m-0.6` - Margin All 0rem
- `.m-0.5` - Margin All 0rem
- `.m-0.4` - Margin All 0rem
- `.m-0.3` - Margin All 0rem
- `.m-0.2` - Margin All 0.2rem
- `.m-0.1` - Margin All 0.1rem
- `.m-0` - Margin All 0rem
- `.m-auto` - Margin All auto

#### Margin Bottom

- `.first:mb-0` - Margin Bottom 0rem on first
- `.hover:mb-100` - Margin Bottom 100% on hover
- `.hover:mb-75` - Margin Bottom 75% on hover
- `.hover:mb-50` - Margin Bottom 50% on hover
- `.hover:mb-25` - Margin Bottom 25% on hover
- `.hover:mb-5` - Margin Bottom 5rem on hover
- `.hover:mb-4.5` - Margin Bottom 0rem on hover
- `.hover:mb-4` - Margin Bottom 4rem on hover
- `.hover:mb-3.5` - Margin Bottom 0rem on hover
- `.hover:mb-3` - Margin Bottom 3rem on hover
- `.hover:mb-2.5` - Margin Bottom 0rem on hover
- `.hover:mb-2` - Margin Bottom 2rem on hover
- `.hover:mb-1.9` - Margin Bottom 0rem on hover
- `.hover:mb-1.8` - Margin Bottom 0rem on hover
- `.hover:mb-1.7` - Margin Bottom 0rem on hover
- `.hover:mb-1.6` - Margin Bottom 0rem on hover
- `.hover:mb-1.5` - Margin Bottom 0rem on hover
- `.hover:mb-1.4` - Margin Bottom 0rem on hover
- `.hover:mb-1.3` - Margin Bottom 0rem on hover
- `.hover:mb-1.2` - Margin Bottom 0rem on hover
- `.hover:mb-1.1` - Margin Bottom 0rem on hover
- `.hover:mb-1` - Margin Bottom 1rem on hover
- `.hover:mb-0.9` - Margin Bottom 0rem on hover
- `.hover:mb-0.8` - Margin Bottom 0rem on hover
- `.hover:mb-0.7` - Margin Bottom 0rem on hover
- `.hover:mb-0.6` - Margin Bottom 0rem on hover
- `.hover:mb-0.5` - Margin Bottom 0rem on hover
- `.hover:mb-0.4` - Margin Bottom 0rem on hover
- `.hover:mb-0.3` - Margin Bottom 0rem on hover
- `.hover:mb-0.2` - Margin Bottom 0.2rem on hover
- `.hover:mb-0.1` - Margin Bottom 0.1rem on hover
- `.hover:mb-0` - Margin Bottom 0rem on hover
- `.hover:mb-auto` - Margin Bottom auto on hover
- `.last:mb-0` - Margin Bottom 0rem on last
- `.mb-100` - Margin Bottom 100%
- `.mb-75` - Margin Bottom 75%
- `.mb-50` - Margin Bottom 50%
- `.mb-25` - Margin Bottom 25%
- `.mb-5` - Margin Bottom 5rem
- `.mb-4.5` - Margin Bottom 0rem
- `.mb-4` - Margin Bottom 4rem
- `.mb-3.5` - Margin Bottom 0rem
- `.mb-3` - Margin Bottom 3rem
- `.mb-2.5` - Margin Bottom 0rem
- `.mb-2` - Margin Bottom 2rem
- `.mb-1.9` - Margin Bottom 0rem
- `.mb-1.8` - Margin Bottom 0rem
- `.mb-1.7` - Margin Bottom 0rem
- `.mb-1.6` - Margin Bottom 0rem
- `.mb-1.5` - Margin Bottom 0rem
- `.mb-1.4` - Margin Bottom 0rem
- `.mb-1.3` - Margin Bottom 0rem
- `.mb-1.2` - Margin Bottom 0rem
- `.mb-1.1` - Margin Bottom 0rem
- `.mb-1` - Margin Bottom 1rem
- `.mb-0.9` - Margin Bottom 0rem
- `.mb-0.8` - Margin Bottom 0rem
- `.mb-0.7` - Margin Bottom 0rem
- `.mb-0.6` - Margin Bottom 0rem
- `.mb-0.5` - Margin Bottom 0rem
- `.mb-0.4` - Margin Bottom 0rem
- `.mb-0.3` - Margin Bottom 0rem
- `.mb-0.2` - Margin Bottom 0.2rem
- `.mb-0.1` - Margin Bottom 0.1rem
- `.mb-0` - Margin Bottom 0rem
- `.mb-auto` - Margin Bottom auto

#### Margin End

- `.hover:me-2` - Margin End 2rem on hover
- `.hover:me-1.5` - Margin End 1.5rem on hover
- `.hover:me-1` - Margin End 1rem on hover
- `.hover:me-0.5` - Margin End 0.5rem on hover
- `.hover:me-0` - Margin End 0rem on hover
- `.me-2` - Margin End 2rem
- `.me-1.5` - Margin End 1.5rem
- `.me-1` - Margin End 1rem
- `.me-0.5` - Margin End 0.5rem
- `.me-0` - Margin End 0rem

#### Margin Left

- `.first:ml-0` - Margin Left 0rem on first
- `.hover:ml-100` - Margin Left 100% on hover
- `.hover:ml-75` - Margin Left 75% on hover
- `.hover:ml-50` - Margin Left 50% on hover
- `.hover:ml-25` - Margin Left 25% on hover
- `.hover:ml-5` - Margin Left 5rem on hover
- `.hover:ml-4.5` - Margin Left 0rem on hover
- `.hover:ml-4` - Margin Left 4rem on hover
- `.hover:ml-3.5` - Margin Left 0rem on hover
- `.hover:ml-3` - Margin Left 3rem on hover
- `.hover:ml-2.5` - Margin Left 0rem on hover
- `.hover:ml-2` - Margin Left 2rem on hover
- `.hover:ml-1.9` - Margin Left 0rem on hover
- `.hover:ml-1.8` - Margin Left 0rem on hover
- `.hover:ml-1.7` - Margin Left 0rem on hover
- `.hover:ml-1.6` - Margin Left 0rem on hover
- `.hover:ml-1.5` - Margin Left 0rem on hover
- `.hover:ml-1.4` - Margin Left 0rem on hover
- `.hover:ml-1.3` - Margin Left 0rem on hover
- `.hover:ml-1.2` - Margin Left 0rem on hover
- `.hover:ml-1.1` - Margin Left 0rem on hover
- `.hover:ml-1` - Margin Left 1rem on hover
- `.hover:ml-0.9` - Margin Left 0rem on hover
- `.hover:ml-0.8` - Margin Left 0rem on hover
- `.hover:ml-0.7` - Margin Left 0rem on hover
- `.hover:ml-0.6` - Margin Left 0rem on hover
- `.hover:ml-0.5` - Margin Left 0rem on hover
- `.hover:ml-0.4` - Margin Left 0rem on hover
- `.hover:ml-0.3` - Margin Left 0rem on hover
- `.hover:ml-0.2` - Margin Left 0.2rem on hover
- `.hover:ml-0.1` - Margin Left 0.1rem on hover
- `.hover:ml-0` - Margin Left 0rem on hover
- `.hover:ml-auto` - Margin Left auto on hover
- `.last:ml-0` - Margin Left 0rem on last
- `.ml-100` - Margin Left 100%
- `.ml-75` - Margin Left 75%
- `.ml-50` - Margin Left 50%
- `.ml-25` - Margin Left 25%
- `.ml-5` - Margin Left 5rem
- `.ml-4.5` - Margin Left 0rem
- `.ml-4` - Margin Left 4rem
- `.ml-3.5` - Margin Left 0rem
- `.ml-3` - Margin Left 3rem
- `.ml-2.5` - Margin Left 0rem
- `.ml-2` - Margin Left 2rem
- `.ml-1.9` - Margin Left 0rem
- `.ml-1.8` - Margin Left 0rem
- `.ml-1.7` - Margin Left 0rem
- `.ml-1.6` - Margin Left 0rem
- `.ml-1.5` - Margin Left 0rem
- `.ml-1.4` - Margin Left 0rem
- `.ml-1.3` - Margin Left 0rem
- `.ml-1.2` - Margin Left 0rem
- `.ml-1.1` - Margin Left 0rem
- `.ml-1` - Margin Left 1rem
- `.ml-0.9` - Margin Left 0rem
- `.ml-0.8` - Margin Left 0rem
- `.ml-0.7` - Margin Left 0rem
- `.ml-0.6` - Margin Left 0rem
- `.ml-0.5` - Margin Left 0rem
- `.ml-0.4` - Margin Left 0rem
- `.ml-0.3` - Margin Left 0rem
- `.ml-0.2` - Margin Left 0.2rem
- `.ml-0.1` - Margin Left 0.1rem
- `.ml-0` - Margin Left 0rem
- `.ml-auto` - Margin Left auto

#### Margin Right

- `.first:mr-0` - Margin Right 0rem on first
- `.hover:mr-100` - Margin Right 100% on hover
- `.hover:mr-75` - Margin Right 75% on hover
- `.hover:mr-50` - Margin Right 50% on hover
- `.hover:mr-25` - Margin Right 25% on hover
- `.hover:mr-5` - Margin Right 5rem on hover
- `.hover:mr-4.5` - Margin Right 0rem on hover
- `.hover:mr-4` - Margin Right 4rem on hover
- `.hover:mr-3.5` - Margin Right 0rem on hover
- `.hover:mr-3` - Margin Right 3rem on hover
- `.hover:mr-2.5` - Margin Right 0rem on hover
- `.hover:mr-2` - Margin Right 2rem on hover
- `.hover:mr-1.9` - Margin Right 0rem on hover
- `.hover:mr-1.8` - Margin Right 0rem on hover
- `.hover:mr-1.7` - Margin Right 0rem on hover
- `.hover:mr-1.6` - Margin Right 0rem on hover
- `.hover:mr-1.5` - Margin Right 0rem on hover
- `.hover:mr-1.4` - Margin Right 0rem on hover
- `.hover:mr-1.3` - Margin Right 0rem on hover
- `.hover:mr-1.2` - Margin Right 0rem on hover
- `.hover:mr-1.1` - Margin Right 0rem on hover
- `.hover:mr-1` - Margin Right 1rem on hover
- `.hover:mr-0.9` - Margin Right 0rem on hover
- `.hover:mr-0.8` - Margin Right 0rem on hover
- `.hover:mr-0.7` - Margin Right 0rem on hover
- `.hover:mr-0.6` - Margin Right 0rem on hover
- `.hover:mr-0.5` - Margin Right 0rem on hover
- `.hover:mr-0.4` - Margin Right 0rem on hover
- `.hover:mr-0.3` - Margin Right 0rem on hover
- `.hover:mr-0.2` - Margin Right 0.2rem on hover
- `.hover:mr-0.1` - Margin Right 0.1rem on hover
- `.hover:mr-0` - Margin Right 0rem on hover
- `.hover:mr-auto` - Margin Right auto on hover
- `.last:mr-0` - Margin Right 0rem on last
- `.mr-100` - Margin Right 100%
- `.mr-75` - Margin Right 75%
- `.mr-50` - Margin Right 50%
- `.mr-25` - Margin Right 25%
- `.mr-5` - Margin Right 5rem
- `.mr-4.5` - Margin Right 0rem
- `.mr-4` - Margin Right 4rem
- `.mr-3.5` - Margin Right 0rem
- `.mr-3` - Margin Right 3rem
- `.mr-2.5` - Margin Right 0rem
- `.mr-2` - Margin Right 2rem
- `.mr-1.9` - Margin Right 0rem
- `.mr-1.8` - Margin Right 0rem
- `.mr-1.7` - Margin Right 0rem
- `.mr-1.6` - Margin Right 0rem
- `.mr-1.5` - Margin Right 0rem
- `.mr-1.4` - Margin Right 0rem
- `.mr-1.3` - Margin Right 0rem
- `.mr-1.2` - Margin Right 0rem
- `.mr-1.1` - Margin Right 0rem
- `.mr-1` - Margin Right 1rem
- `.mr-0.9` - Margin Right 0rem
- `.mr-0.8` - Margin Right 0rem
- `.mr-0.7` - Margin Right 0rem
- `.mr-0.6` - Margin Right 0rem
- `.mr-0.5` - Margin Right 0rem
- `.mr-0.4` - Margin Right 0rem
- `.mr-0.3` - Margin Right 0rem
- `.mr-0.2` - Margin Right 0.2rem
- `.mr-0.1` - Margin Right 0.1rem
- `.mr-0` - Margin Right 0rem
- `.mr-auto` - Margin Right auto

#### Margin Start

- `.hover:ms-2` - Margin Start 2rem on hover
- `.hover:ms-1.5` - Margin Start 1.5rem on hover
- `.hover:ms-1` - Margin Start 1rem on hover
- `.hover:ms-0.5` - Margin Start 0.5rem on hover
- `.hover:ms-0` - Margin Start 0rem on hover
- `.ms-2` - Margin Start 2rem
- `.ms-1.5` - Margin Start 1.5rem
- `.ms-1` - Margin Start 1rem
- `.ms-0.5` - Margin Start 0.5rem
- `.ms-0` - Margin Start 0rem

#### Margin Top

- `.first:mt-0` - Margin Top 0rem on first
- `.hover:mt-100` - Margin Top 100% on hover
- `.hover:mt-75` - Margin Top 75% on hover
- `.hover:mt-50` - Margin Top 50% on hover
- `.hover:mt-25` - Margin Top 25% on hover
- `.hover:mt-5` - Margin Top 5rem on hover
- `.hover:mt-4.5` - Margin Top 0rem on hover
- `.hover:mt-4` - Margin Top 4rem on hover
- `.hover:mt-3.5` - Margin Top 0rem on hover
- `.hover:mt-3` - Margin Top 3rem on hover
- `.hover:mt-2.5` - Margin Top 0rem on hover
- `.hover:mt-2` - Margin Top 2rem on hover
- `.hover:mt-1.9` - Margin Top 0rem on hover
- `.hover:mt-1.8` - Margin Top 0rem on hover
- `.hover:mt-1.7` - Margin Top 0rem on hover
- `.hover:mt-1.6` - Margin Top 0rem on hover
- `.hover:mt-1.5` - Margin Top 0rem on hover
- `.hover:mt-1.4` - Margin Top 0rem on hover
- `.hover:mt-1.3` - Margin Top 0rem on hover
- `.hover:mt-1.2` - Margin Top 0rem on hover
- `.hover:mt-1.1` - Margin Top 0rem on hover
- `.hover:mt-1` - Margin Top 1rem on hover
- `.hover:mt-0.9` - Margin Top 0rem on hover
- `.hover:mt-0.8` - Margin Top 0rem on hover
- `.hover:mt-0.7` - Margin Top 0rem on hover
- `.hover:mt-0.6` - Margin Top 0rem on hover
- `.hover:mt-0.5` - Margin Top 0rem on hover
- `.hover:mt-0.4` - Margin Top 0rem on hover
- `.hover:mt-0.3` - Margin Top 0rem on hover
- `.hover:mt-0.2` - Margin Top 0.2rem on hover
- `.hover:mt-0.1` - Margin Top 0.1rem on hover
- `.hover:mt-0` - Margin Top 0rem on hover
- `.hover:mt-auto` - Margin Top auto on hover
- `.last:mt-0` - Margin Top 0rem on last
- `.mt-100` - Margin Top 100%
- `.mt-75` - Margin Top 75%
- `.mt-50` - Margin Top 50%
- `.mt-25` - Margin Top 25%
- `.mt-5` - Margin Top 5rem
- `.mt-4.5` - Margin Top 0rem
- `.mt-4` - Margin Top 4rem
- `.mt-3.5` - Margin Top 0rem
- `.mt-3` - Margin Top 3rem
- `.mt-2.5` - Margin Top 0rem
- `.mt-2` - Margin Top 2rem
- `.mt-1.9` - Margin Top 0rem
- `.mt-1.8` - Margin Top 0rem
- `.mt-1.7` - Margin Top 0rem
- `.mt-1.6` - Margin Top 0rem
- `.mt-1.5` - Margin Top 0rem
- `.mt-1.4` - Margin Top 0rem
- `.mt-1.3` - Margin Top 0rem
- `.mt-1.2` - Margin Top 0rem
- `.mt-1.1` - Margin Top 0rem
- `.mt-1` - Margin Top 1rem
- `.mt-0.9` - Margin Top 0rem
- `.mt-0.8` - Margin Top 0rem
- `.mt-0.7` - Margin Top 0rem
- `.mt-0.6` - Margin Top 0rem
- `.mt-0.5` - Margin Top 0rem
- `.mt-0.4` - Margin Top 0rem
- `.mt-0.3` - Margin Top 0rem
- `.mt-0.2` - Margin Top 0.2rem
- `.mt-0.1` - Margin Top 0.1rem
- `.mt-0` - Margin Top 0rem
- `.mt-auto` - Margin Top auto

#### Margin X-Axis

- `.hover:mx-100` - Margin X-Axis 100% on hover
- `.hover:mx-75` - Margin X-Axis 75% on hover
- `.hover:mx-50` - Margin X-Axis 50% on hover
- `.hover:mx-25` - Margin X-Axis 25% on hover
- `.hover:mx-5` - Margin X-Axis 5rem on hover
- `.hover:mx-4.5` - Margin X-Axis 0rem on hover
- `.hover:mx-4` - Margin X-Axis 4rem on hover
- `.hover:mx-3.5` - Margin X-Axis 0rem on hover
- `.hover:mx-3` - Margin X-Axis 3rem on hover
- `.hover:mx-2.5` - Margin X-Axis 0rem on hover
- `.hover:mx-2` - Margin X-Axis 2rem on hover
- `.hover:mx-1.9` - Margin X-Axis 0rem on hover
- `.hover:mx-1.8` - Margin X-Axis 0rem on hover
- `.hover:mx-1.7` - Margin X-Axis 0rem on hover
- `.hover:mx-1.6` - Margin X-Axis 0rem on hover
- `.hover:mx-1.5` - Margin X-Axis 0rem on hover
- `.hover:mx-1.4` - Margin X-Axis 0rem on hover
- `.hover:mx-1.3` - Margin X-Axis 0rem on hover
- `.hover:mx-1.2` - Margin X-Axis 0rem on hover
- `.hover:mx-1.1` - Margin X-Axis 0rem on hover
- `.hover:mx-1` - Margin X-Axis 1rem on hover
- `.hover:mx-0.9` - Margin X-Axis 0rem on hover
- `.hover:mx-0.8` - Margin X-Axis 0rem on hover
- `.hover:mx-0.7` - Margin X-Axis 0rem on hover
- `.hover:mx-0.6` - Margin X-Axis 0rem on hover
- `.hover:mx-0.5` - Margin X-Axis 0rem on hover
- `.hover:mx-0.4` - Margin X-Axis 0rem on hover
- `.hover:mx-0.3` - Margin X-Axis 0rem on hover
- `.hover:mx-0.2` - Margin X-Axis 0.2rem on hover
- `.hover:mx-0.1` - Margin X-Axis 0.1rem on hover
- `.hover:mx-0` - Margin X-Axis 0rem on hover
- `.hover:mx-auto` - Margin X-Axis auto on hover
- `.mx-100` - Margin X-Axis 100%
- `.mx-75` - Margin X-Axis 75%
- `.mx-50` - Margin X-Axis 50%
- `.mx-25` - Margin X-Axis 25%
- `.mx-5` - Margin X-Axis 5rem
- `.mx-4.5` - Margin X-Axis 0rem
- `.mx-4` - Margin X-Axis 4rem
- `.mx-3.5` - Margin X-Axis 0rem
- `.mx-3` - Margin X-Axis 3rem
- `.mx-2.5` - Margin X-Axis 0rem
- `.mx-2` - Margin X-Axis 2rem
- `.mx-1.9` - Margin X-Axis 0rem
- `.mx-1.8` - Margin X-Axis 0rem
- `.mx-1.7` - Margin X-Axis 0rem
- `.mx-1.6` - Margin X-Axis 0rem
- `.mx-1.5` - Margin X-Axis 0rem
- `.mx-1.4` - Margin X-Axis 0rem
- `.mx-1.3` - Margin X-Axis 0rem
- `.mx-1.2` - Margin X-Axis 0rem
- `.mx-1.1` - Margin X-Axis 0rem
- `.mx-1` - Margin X-Axis 1rem
- `.mx-0.9` - Margin X-Axis 0rem
- `.mx-0.8` - Margin X-Axis 0rem
- `.mx-0.7` - Margin X-Axis 0rem
- `.mx-0.6` - Margin X-Axis 0rem
- `.mx-0.5` - Margin X-Axis 0rem
- `.mx-0.4` - Margin X-Axis 0rem
- `.mx-0.3` - Margin X-Axis 0rem
- `.mx-0.2` - Margin X-Axis 0.2rem
- `.mx-0.1` - Margin X-Axis 0.1rem
- `.mx-0` - Margin X-Axis 0rem
- `.mx-auto` - Margin X-Axis auto

#### Margin Y-Axis

- `.hover:my-100` - Margin Y-Axis 100% on hover
- `.hover:my-75` - Margin Y-Axis 75% on hover
- `.hover:my-50` - Margin Y-Axis 50% on hover
- `.hover:my-25` - Margin Y-Axis 25% on hover
- `.hover:my-5` - Margin Y-Axis 5rem on hover
- `.hover:my-4.5` - Margin Y-Axis 0rem on hover
- `.hover:my-4` - Margin Y-Axis 4rem on hover
- `.hover:my-3.5` - Margin Y-Axis 0rem on hover
- `.hover:my-3` - Margin Y-Axis 3rem on hover
- `.hover:my-2.5` - Margin Y-Axis 0rem on hover
- `.hover:my-2` - Margin Y-Axis 2rem on hover
- `.hover:my-1.9` - Margin Y-Axis 0rem on hover
- `.hover:my-1.8` - Margin Y-Axis 0rem on hover
- `.hover:my-1.7` - Margin Y-Axis 0rem on hover
- `.hover:my-1.6` - Margin Y-Axis 0rem on hover
- `.hover:my-1.5` - Margin Y-Axis 0rem on hover
- `.hover:my-1.4` - Margin Y-Axis 0rem on hover
- `.hover:my-1.3` - Margin Y-Axis 0rem on hover
- `.hover:my-1.2` - Margin Y-Axis 0rem on hover
- `.hover:my-1.1` - Margin Y-Axis 0rem on hover
- `.hover:my-1` - Margin Y-Axis 1rem on hover
- `.hover:my-0.9` - Margin Y-Axis 0rem on hover
- `.hover:my-0.8` - Margin Y-Axis 0rem on hover
- `.hover:my-0.7` - Margin Y-Axis 0rem on hover
- `.hover:my-0.6` - Margin Y-Axis 0rem on hover
- `.hover:my-0.5` - Margin Y-Axis 0rem on hover
- `.hover:my-0.4` - Margin Y-Axis 0rem on hover
- `.hover:my-0.3` - Margin Y-Axis 0rem on hover
- `.hover:my-0.2` - Margin Y-Axis 0.2rem on hover
- `.hover:my-0.1` - Margin Y-Axis 0.1rem on hover
- `.hover:my-0` - Margin Y-Axis 0rem on hover
- `.hover:my-auto` - Margin Y-Axis auto on hover
- `.my-100` - Margin Y-Axis 100%
- `.my-75` - Margin Y-Axis 75%
- `.my-50` - Margin Y-Axis 50%
- `.my-25` - Margin Y-Axis 25%
- `.my-5` - Margin Y-Axis 5rem
- `.my-4.5` - Margin Y-Axis 0rem
- `.my-4` - Margin Y-Axis 4rem
- `.my-3.5` - Margin Y-Axis 0rem
- `.my-3` - Margin Y-Axis 3rem
- `.my-2.5` - Margin Y-Axis 0rem
- `.my-2` - Margin Y-Axis 2rem
- `.my-1.9` - Margin Y-Axis 0rem
- `.my-1.8` - Margin Y-Axis 0rem
- `.my-1.7` - Margin Y-Axis 0rem
- `.my-1.6` - Margin Y-Axis 0rem
- `.my-1.5` - Margin Y-Axis 0rem
- `.my-1.4` - Margin Y-Axis 0rem
- `.my-1.3` - Margin Y-Axis 0rem
- `.my-1.2` - Margin Y-Axis 0rem
- `.my-1.1` - Margin Y-Axis 0rem
- `.my-1` - Margin Y-Axis 1rem
- `.my-0.9` - Margin Y-Axis 0rem
- `.my-0.8` - Margin Y-Axis 0rem
- `.my-0.7` - Margin Y-Axis 0rem
- `.my-0.6` - Margin Y-Axis 0rem
- `.my-0.5` - Margin Y-Axis 0rem
- `.my-0.4` - Margin Y-Axis 0rem
- `.my-0.3` - Margin Y-Axis 0rem
- `.my-0.2` - Margin Y-Axis 0.2rem
- `.my-0.1` - Margin Y-Axis 0.1rem
- `.my-0` - Margin Y-Axis 0rem
- `.my-auto` - Margin Y-Axis auto

### Padding

#### Padding All

- `.first:p-0` - Padding All 0rem on first
- `.hover:p-5` - Padding All 5rem on hover
- `.hover:p-4.5` - Padding All 0rem on hover
- `.hover:p-4` - Padding All 4rem on hover
- `.hover:p-3.5` - Padding All 0rem on hover
- `.hover:p-3` - Padding All 3rem on hover
- `.hover:p-2.5` - Padding All 0rem on hover
- `.hover:p-2` - Padding All 2rem on hover
- `.hover:p-1.9` - Padding All 0rem on hover
- `.hover:p-1.8` - Padding All 0rem on hover
- `.hover:p-1.7` - Padding All 0rem on hover
- `.hover:p-1.6` - Padding All 0rem on hover
- `.hover:p-1.5` - Padding All 0rem on hover
- `.hover:p-1.4` - Padding All 0rem on hover
- `.hover:p-1.3` - Padding All 0rem on hover
- `.hover:p-1.2` - Padding All 0rem on hover
- `.hover:p-1.1` - Padding All 0rem on hover
- `.hover:p-1` - Padding All 1rem on hover
- `.hover:p-0.9` - Padding All 0rem on hover
- `.hover:p-0.8` - Padding All 0rem on hover
- `.hover:p-0.7` - Padding All 0rem on hover
- `.hover:p-0.6` - Padding All 0rem on hover
- `.hover:p-0.5` - Padding All 0rem on hover
- `.hover:p-0.4` - Padding All 0rem on hover
- `.hover:p-0.3` - Padding All 0rem on hover
- `.hover:p-0.2` - Padding All 0.2rem on hover
- `.hover:p-0.1` - Padding All 0.1rem on hover
- `.hover:p-0` - Padding All 0rem on hover
- `.last:p-0` - Padding All 0rem on last
- `.p-5` - Padding All 5rem
- `.p-4.5` - Padding All 0rem
- `.p-4` - Padding All 4rem
- `.p-3.5` - Padding All 0rem
- `.p-3` - Padding All 3rem
- `.p-2.5` - Padding All 0rem
- `.p-2` - Padding All 2rem
- `.p-1.9` - Padding All 0rem
- `.p-1.8` - Padding All 0rem
- `.p-1.7` - Padding All 0rem
- `.p-1.6` - Padding All 0rem
- `.p-1.5` - Padding All 0rem
- `.p-1.4` - Padding All 0rem
- `.p-1.3` - Padding All 0rem
- `.p-1.2` - Padding All 0rem
- `.p-1.1` - Padding All 0rem
- `.p-1` - Padding All 1rem
- `.p-0.9` - Padding All 0rem
- `.p-0.8` - Padding All 0rem
- `.p-0.7` - Padding All 0rem
- `.p-0.6` - Padding All 0rem
- `.p-0.5` - Padding All 0rem
- `.p-0.4` - Padding All 0rem
- `.p-0.3` - Padding All 0rem
- `.p-0.2` - Padding All 0.2rem
- `.p-0.1` - Padding All 0.1rem
- `.p-0` - Padding All 0rem

#### Padding Bottom

- `.first:pb-0` - Padding Bottom 0rem on first
- `.hover:pb-100` - Padding Bottom 100% on hover
- `.hover:pb-75` - Padding Bottom 75% on hover
- `.hover:pb-50` - Padding Bottom 50% on hover
- `.hover:pb-25` - Padding Bottom 25% on hover
- `.hover:pb-5` - Padding Bottom 5rem on hover
- `.hover:pb-4.5` - Padding Bottom 0rem on hover
- `.hover:pb-4` - Padding Bottom 4rem on hover
- `.hover:pb-3.5` - Padding Bottom 0rem on hover
- `.hover:pb-3` - Padding Bottom 3rem on hover
- `.hover:pb-2.5` - Padding Bottom 0rem on hover
- `.hover:pb-2` - Padding Bottom 2rem on hover
- `.hover:pb-1.9` - Padding Bottom 0rem on hover
- `.hover:pb-1.8` - Padding Bottom 0rem on hover
- `.hover:pb-1.7` - Padding Bottom 0rem on hover
- `.hover:pb-1.6` - Padding Bottom 0rem on hover
- `.hover:pb-1.5` - Padding Bottom 0rem on hover
- `.hover:pb-1.4` - Padding Bottom 0rem on hover
- `.hover:pb-1.3` - Padding Bottom 0rem on hover
- `.hover:pb-1.2` - Padding Bottom 0rem on hover
- `.hover:pb-1.1` - Padding Bottom 0rem on hover
- `.hover:pb-1` - Padding Bottom 1rem on hover
- `.hover:pb-0.9` - Padding Bottom 0rem on hover
- `.hover:pb-0.8` - Padding Bottom 0rem on hover
- `.hover:pb-0.7` - Padding Bottom 0rem on hover
- `.hover:pb-0.6` - Padding Bottom 0rem on hover
- `.hover:pb-0.5` - Padding Bottom 0rem on hover
- `.hover:pb-0.4` - Padding Bottom 0rem on hover
- `.hover:pb-0.3` - Padding Bottom 0rem on hover
- `.hover:pb-0.2` - Padding Bottom 0.2rem on hover
- `.hover:pb-0.1` - Padding Bottom 0.1rem on hover
- `.hover:pb-0` - Padding Bottom 0rem on hover
- `.last:pb-0` - Padding Bottom 0rem on last
- `.pb-100` - Padding Bottom 100%
- `.pb-75` - Padding Bottom 75%
- `.pb-50` - Padding Bottom 50%
- `.pb-25` - Padding Bottom 25%
- `.pb-5` - Padding Bottom 5rem
- `.pb-4.5` - Padding Bottom 0rem
- `.pb-4` - Padding Bottom 4rem
- `.pb-3.5` - Padding Bottom 0rem
- `.pb-3` - Padding Bottom 3rem
- `.pb-2.5` - Padding Bottom 0rem
- `.pb-2` - Padding Bottom 2rem
- `.pb-1.9` - Padding Bottom 0rem
- `.pb-1.8` - Padding Bottom 0rem
- `.pb-1.7` - Padding Bottom 0rem
- `.pb-1.6` - Padding Bottom 0rem
- `.pb-1.5` - Padding Bottom 0rem
- `.pb-1.4` - Padding Bottom 0rem
- `.pb-1.3` - Padding Bottom 0rem
- `.pb-1.2` - Padding Bottom 0rem
- `.pb-1.1` - Padding Bottom 0rem
- `.pb-1` - Padding Bottom 1rem
- `.pb-0.9` - Padding Bottom 0rem
- `.pb-0.8` - Padding Bottom 0rem
- `.pb-0.7` - Padding Bottom 0rem
- `.pb-0.6` - Padding Bottom 0rem
- `.pb-0.5` - Padding Bottom 0rem
- `.pb-0.4` - Padding Bottom 0rem
- `.pb-0.3` - Padding Bottom 0rem
- `.pb-0.2` - Padding Bottom 0.2rem
- `.pb-0.1` - Padding Bottom 0.1rem
- `.pb-0` - Padding Bottom 0rem

#### Padding Left

- `.first:pl-0` - Padding Left 0rem on first
- `.hover:pl-5` - Padding Left 5rem on hover
- `.hover:pl-4.5` - Padding Left 0rem on hover
- `.hover:pl-4` - Padding Left 4rem on hover
- `.hover:pl-3.5` - Padding Left 0rem on hover
- `.hover:pl-3` - Padding Left 3rem on hover
- `.hover:pl-2.5` - Padding Left 0rem on hover
- `.hover:pl-2` - Padding Left 2rem on hover
- `.hover:pl-1.9` - Padding Left 0rem on hover
- `.hover:pl-1.8` - Padding Left 0rem on hover
- `.hover:pl-1.7` - Padding Left 0rem on hover
- `.hover:pl-1.6` - Padding Left 0rem on hover
- `.hover:pl-1.5` - Padding Left 0rem on hover
- `.hover:pl-1.4` - Padding Left 0rem on hover
- `.hover:pl-1.3` - Padding Left 0rem on hover
- `.hover:pl-1.2` - Padding Left 0rem on hover
- `.hover:pl-1.1` - Padding Left 0rem on hover
- `.hover:pl-1` - Padding Left 1rem on hover
- `.hover:pl-0.9` - Padding Left 0rem on hover
- `.hover:pl-0.8` - Padding Left 0rem on hover
- `.hover:pl-0.7` - Padding Left 0rem on hover
- `.hover:pl-0.6` - Padding Left 0rem on hover
- `.hover:pl-0.5` - Padding Left 0rem on hover
- `.hover:pl-0.4` - Padding Left 0rem on hover
- `.hover:pl-0.3` - Padding Left 0rem on hover
- `.hover:pl-0.2` - Padding Left 0.2rem on hover
- `.hover:pl-0.1` - Padding Left 0.1rem on hover
- `.hover:pl-0` - Padding Left 0rem on hover
- `.last:pl-0` - Padding Left 0rem on last
- `.pl-5` - Padding Left 5rem
- `.pl-4.5` - Padding Left 0rem
- `.pl-4` - Padding Left 4rem
- `.pl-3.5` - Padding Left 0rem
- `.pl-3` - Padding Left 3rem
- `.pl-2.5` - Padding Left 0rem
- `.pl-2` - Padding Left 2rem
- `.pl-1.9` - Padding Left 0rem
- `.pl-1.8` - Padding Left 0rem
- `.pl-1.7` - Padding Left 0rem
- `.pl-1.6` - Padding Left 0rem
- `.pl-1.5` - Padding Left 0rem
- `.pl-1.4` - Padding Left 0rem
- `.pl-1.3` - Padding Left 0rem
- `.pl-1.2` - Padding Left 0rem
- `.pl-1.1` - Padding Left 0rem
- `.pl-1` - Padding Left 1rem
- `.pl-0.9` - Padding Left 0rem
- `.pl-0.8` - Padding Left 0rem
- `.pl-0.7` - Padding Left 0rem
- `.pl-0.6` - Padding Left 0rem
- `.pl-0.5` - Padding Left 0rem
- `.pl-0.4` - Padding Left 0rem
- `.pl-0.3` - Padding Left 0rem
- `.pl-0.2` - Padding Left 0.2rem
- `.pl-0.1` - Padding Left 0.1rem
- `.pl-0` - Padding Left 0rem

#### Padding Right

- `.first:pr-0` - Padding Right 0rem on first
- `.hover:pr-100` - Padding Right 100% on hover
- `.hover:pr-75` - Padding Right 75% on hover
- `.hover:pr-50` - Padding Right 50% on hover
- `.hover:pr-25` - Padding Right 25% on hover
- `.hover:pr-5` - Padding Right 5rem on hover
- `.hover:pr-4.5` - Padding Right 0rem on hover
- `.hover:pr-4` - Padding Right 4rem on hover
- `.hover:pr-3.5` - Padding Right 0rem on hover
- `.hover:pr-3` - Padding Right 3rem on hover
- `.hover:pr-2.5` - Padding Right 0rem on hover
- `.hover:pr-2` - Padding Right 2rem on hover
- `.hover:pr-1.9` - Padding Right 0rem on hover
- `.hover:pr-1.8` - Padding Right 0rem on hover
- `.hover:pr-1.7` - Padding Right 0rem on hover
- `.hover:pr-1.6` - Padding Right 0rem on hover
- `.hover:pr-1.5` - Padding Right 0rem on hover
- `.hover:pr-1.4` - Padding Right 0rem on hover
- `.hover:pr-1.3` - Padding Right 0rem on hover
- `.hover:pr-1.2` - Padding Right 0rem on hover
- `.hover:pr-1.1` - Padding Right 0rem on hover
- `.hover:pr-1` - Padding Right 1rem on hover
- `.hover:pr-0.9` - Padding Right 0rem on hover
- `.hover:pr-0.8` - Padding Right 0rem on hover
- `.hover:pr-0.7` - Padding Right 0rem on hover
- `.hover:pr-0.6` - Padding Right 0rem on hover
- `.hover:pr-0.5` - Padding Right 0rem on hover
- `.hover:pr-0.4` - Padding Right 0rem on hover
- `.hover:pr-0.3` - Padding Right 0rem on hover
- `.hover:pr-0.2` - Padding Right 0.2rem on hover
- `.hover:pr-0.1` - Padding Right 0.1rem on hover
- `.hover:pr-0` - Padding Right 0rem on hover
- `.last:pr-0` - Padding Right 0rem on last
- `.pr-100` - Padding Right 100%
- `.pr-75` - Padding Right 75%
- `.pr-50` - Padding Right 50%
- `.pr-25` - Padding Right 25%
- `.pr-5` - Padding Right 5rem
- `.pr-4.5` - Padding Right 0rem
- `.pr-4` - Padding Right 4rem
- `.pr-3.5` - Padding Right 0rem
- `.pr-3` - Padding Right 3rem
- `.pr-2.5` - Padding Right 0rem
- `.pr-2` - Padding Right 2rem
- `.pr-1.9` - Padding Right 0rem
- `.pr-1.8` - Padding Right 0rem
- `.pr-1.7` - Padding Right 0rem
- `.pr-1.6` - Padding Right 0rem
- `.pr-1.5` - Padding Right 0rem
- `.pr-1.4` - Padding Right 0rem
- `.pr-1.3` - Padding Right 0rem
- `.pr-1.2` - Padding Right 0rem
- `.pr-1.1` - Padding Right 0rem
- `.pr-1` - Padding Right 1rem
- `.pr-0.9` - Padding Right 0rem
- `.pr-0.8` - Padding Right 0rem
- `.pr-0.7` - Padding Right 0rem
- `.pr-0.6` - Padding Right 0rem
- `.pr-0.5` - Padding Right 0rem
- `.pr-0.4` - Padding Right 0rem
- `.pr-0.3` - Padding Right 0rem
- `.pr-0.2` - Padding Right 0.2rem
- `.pr-0.1` - Padding Right 0.1rem
- `.pr-0` - Padding Right 0rem

#### Padding Top

- `.first:pt-0` - Padding Top 0rem on first
- `.hover:pt-100` - Padding Top 100% on hover
- `.hover:pt-75` - Padding Top 75% on hover
- `.hover:pt-50` - Padding Top 50% on hover
- `.hover:pt-25` - Padding Top 25% on hover
- `.hover:pt-5` - Padding Top 5rem on hover
- `.hover:pt-4.5` - Padding Top 0rem on hover
- `.hover:pt-4` - Padding Top 4rem on hover
- `.hover:pt-3.5` - Padding Top 0rem on hover
- `.hover:pt-3` - Padding Top 3rem on hover
- `.hover:pt-2.5` - Padding Top 0rem on hover
- `.hover:pt-2` - Padding Top 2rem on hover
- `.hover:pt-1.9` - Padding Top 0rem on hover
- `.hover:pt-1.8` - Padding Top 0rem on hover
- `.hover:pt-1.7` - Padding Top 0rem on hover
- `.hover:pt-1.6` - Padding Top 0rem on hover
- `.hover:pt-1.5` - Padding Top 0rem on hover
- `.hover:pt-1.4` - Padding Top 0rem on hover
- `.hover:pt-1.3` - Padding Top 0rem on hover
- `.hover:pt-1.2` - Padding Top 0rem on hover
- `.hover:pt-1.1` - Padding Top 0rem on hover
- `.hover:pt-1` - Padding Top 1rem on hover
- `.hover:pt-0.9` - Padding Top 0rem on hover
- `.hover:pt-0.8` - Padding Top 0rem on hover
- `.hover:pt-0.7` - Padding Top 0rem on hover
- `.hover:pt-0.6` - Padding Top 0rem on hover
- `.hover:pt-0.5` - Padding Top 0rem on hover
- `.hover:pt-0.4` - Padding Top 0rem on hover
- `.hover:pt-0.3` - Padding Top 0rem on hover
- `.hover:pt-0.2` - Padding Top 0.2rem on hover
- `.hover:pt-0.1` - Padding Top 0.1rem on hover
- `.hover:pt-0` - Padding Top 0rem on hover
- `.last:pt-0` - Padding Top 0rem on last
- `.pt-100` - Padding Top 100%
- `.pt-75` - Padding Top 75%
- `.pt-50` - Padding Top 50%
- `.pt-25` - Padding Top 25%
- `.pt-5` - Padding Top 5rem
- `.pt-4.5` - Padding Top 0rem
- `.pt-4` - Padding Top 4rem
- `.pt-3.5` - Padding Top 0rem
- `.pt-3` - Padding Top 3rem
- `.pt-2.5` - Padding Top 0rem
- `.pt-2` - Padding Top 2rem
- `.pt-1.9` - Padding Top 0rem
- `.pt-1.8` - Padding Top 0rem
- `.pt-1.7` - Padding Top 0rem
- `.pt-1.6` - Padding Top 0rem
- `.pt-1.5` - Padding Top 0rem
- `.pt-1.4` - Padding Top 0rem
- `.pt-1.3` - Padding Top 0rem
- `.pt-1.2` - Padding Top 0rem
- `.pt-1.1` - Padding Top 0rem
- `.pt-1` - Padding Top 1rem
- `.pt-0.9` - Padding Top 0rem
- `.pt-0.8` - Padding Top 0rem
- `.pt-0.7` - Padding Top 0rem
- `.pt-0.6` - Padding Top 0rem
- `.pt-0.5` - Padding Top 0rem
- `.pt-0.4` - Padding Top 0rem
- `.pt-0.3` - Padding Top 0rem
- `.pt-0.2` - Padding Top 0.2rem
- `.pt-0.1` - Padding Top 0.1rem
- `.pt-0` - Padding Top 0rem

#### Padding X-Axis

- `.hover:px-100` - Padding X-Axis 100% on hover
- `.hover:px-75` - Padding X-Axis 75% on hover
- `.hover:px-50` - Padding X-Axis 50% on hover
- `.hover:px-25` - Padding X-Axis 25% on hover
- `.hover:px-5` - Padding X-Axis 5rem on hover
- `.hover:px-4.5` - Padding X-Axis 0rem on hover
- `.hover:px-4` - Padding X-Axis 4rem on hover
- `.hover:px-3.5` - Padding X-Axis 0rem on hover
- `.hover:px-3` - Padding X-Axis 3rem on hover
- `.hover:px-2.5` - Padding X-Axis 0rem on hover
- `.hover:px-2` - Padding X-Axis 2rem on hover
- `.hover:px-1.9` - Padding X-Axis 0rem on hover
- `.hover:px-1.8` - Padding X-Axis 0rem on hover
- `.hover:px-1.7` - Padding X-Axis 0rem on hover
- `.hover:px-1.6` - Padding X-Axis 0rem on hover
- `.hover:px-1.5` - Padding X-Axis 0rem on hover
- `.hover:px-1.4` - Padding X-Axis 0rem on hover
- `.hover:px-1.3` - Padding X-Axis 0rem on hover
- `.hover:px-1.2` - Padding X-Axis 0rem on hover
- `.hover:px-1.1` - Padding X-Axis 0rem on hover
- `.hover:px-1` - Padding X-Axis 1rem on hover
- `.hover:px-0.9` - Padding X-Axis 0rem on hover
- `.hover:px-0.8` - Padding X-Axis 0rem on hover
- `.hover:px-0.7` - Padding X-Axis 0rem on hover
- `.hover:px-0.6` - Padding X-Axis 0rem on hover
- `.hover:px-0.5` - Padding X-Axis 0rem on hover
- `.hover:px-0.4` - Padding X-Axis 0rem on hover
- `.hover:px-0.3` - Padding X-Axis 0rem on hover
- `.hover:px-0.2` - Padding X-Axis 0.2rem on hover
- `.hover:px-0.1` - Padding X-Axis 0.1rem on hover
- `.hover:px-0` - Padding X-Axis 0rem on hover
- `.px-100` - Padding X-Axis 100%
- `.px-75` - Padding X-Axis 75%
- `.px-50` - Padding X-Axis 50%
- `.px-25` - Padding X-Axis 25%
- `.px-5` - Padding X-Axis 5rem
- `.px-4.5` - Padding X-Axis 0rem
- `.px-4` - Padding X-Axis 4rem
- `.px-3.5` - Padding X-Axis 0rem
- `.px-3` - Padding X-Axis 3rem
- `.px-2.5` - Padding X-Axis 0rem
- `.px-2` - Padding X-Axis 2rem
- `.px-1.9` - Padding X-Axis 0rem
- `.px-1.8` - Padding X-Axis 0rem
- `.px-1.7` - Padding X-Axis 0rem
- `.px-1.6` - Padding X-Axis 0rem
- `.px-1.5` - Padding X-Axis 0rem
- `.px-1.4` - Padding X-Axis 0rem
- `.px-1.3` - Padding X-Axis 0rem
- `.px-1.2` - Padding X-Axis 0rem
- `.px-1.1` - Padding X-Axis 0rem
- `.px-1` - Padding X-Axis 1rem
- `.px-0.9` - Padding X-Axis 0rem
- `.px-0.8` - Padding X-Axis 0rem
- `.px-0.7` - Padding X-Axis 0rem
- `.px-0.6` - Padding X-Axis 0rem
- `.px-0.5` - Padding X-Axis 0rem
- `.px-0.4` - Padding X-Axis 0rem
- `.px-0.3` - Padding X-Axis 0rem
- `.px-0.2` - Padding X-Axis 0.2rem
- `.px-0.1` - Padding X-Axis 0.1rem
- `.px-0` - Padding X-Axis 0rem

#### Padding Y-Axis

- `.hover:py-100` - Padding Y-Axis 100% on hover
- `.hover:py-75` - Padding Y-Axis 75% on hover
- `.hover:py-50` - Padding Y-Axis 50% on hover
- `.hover:py-25` - Padding Y-Axis 25% on hover
- `.hover:py-5` - Padding Y-Axis 5rem on hover
- `.hover:py-4.5` - Padding Y-Axis 0rem on hover
- `.hover:py-4` - Padding Y-Axis 4rem on hover
- `.hover:py-3.5` - Padding Y-Axis 0rem on hover
- `.hover:py-3` - Padding Y-Axis 3rem on hover
- `.hover:py-2.5` - Padding Y-Axis 0rem on hover
- `.hover:py-2` - Padding Y-Axis 2rem on hover
- `.hover:py-1.9` - Padding Y-Axis 0rem on hover
- `.hover:py-1.8` - Padding Y-Axis 0rem on hover
- `.hover:py-1.7` - Padding Y-Axis 0rem on hover
- `.hover:py-1.6` - Padding Y-Axis 0rem on hover
- `.hover:py-1.5` - Padding Y-Axis 0rem on hover
- `.hover:py-1.4` - Padding Y-Axis 0rem on hover
- `.hover:py-1.3` - Padding Y-Axis 0rem on hover
- `.hover:py-1.2` - Padding Y-Axis 0rem on hover
- `.hover:py-1.1` - Padding Y-Axis 0rem on hover
- `.hover:py-1` - Padding Y-Axis 1rem on hover
- `.hover:py-0.9` - Padding Y-Axis 0rem on hover
- `.hover:py-0.8` - Padding Y-Axis 0rem on hover
- `.hover:py-0.7` - Padding Y-Axis 0rem on hover
- `.hover:py-0.6` - Padding Y-Axis 0rem on hover
- `.hover:py-0.5` - Padding Y-Axis 0rem on hover
- `.hover:py-0.4` - Padding Y-Axis 0rem on hover
- `.hover:py-0.3` - Padding Y-Axis 0rem on hover
- `.hover:py-0.2` - Padding Y-Axis 0.2rem on hover
- `.hover:py-0.1` - Padding Y-Axis 0.1rem on hover
- `.hover:py-0` - Padding Y-Axis 0rem on hover
- `.py-100` - Padding Y-Axis 100%
- `.py-75` - Padding Y-Axis 75%
- `.py-50` - Padding Y-Axis 50%
- `.py-25` - Padding Y-Axis 25%
- `.py-5` - Padding Y-Axis 5rem
- `.py-4.5` - Padding Y-Axis 0rem
- `.py-4` - Padding Y-Axis 4rem
- `.py-3.5` - Padding Y-Axis 0rem
- `.py-3` - Padding Y-Axis 3rem
- `.py-2.5` - Padding Y-Axis 0rem
- `.py-2` - Padding Y-Axis 2rem
- `.py-1.9` - Padding Y-Axis 0rem
- `.py-1.8` - Padding Y-Axis 0rem
- `.py-1.7` - Padding Y-Axis 0rem
- `.py-1.6` - Padding Y-Axis 0rem
- `.py-1.5` - Padding Y-Axis 0rem
- `.py-1.4` - Padding Y-Axis 0rem
- `.py-1.3` - Padding Y-Axis 0rem
- `.py-1.2` - Padding Y-Axis 0rem
- `.py-1.1` - Padding Y-Axis 0rem
- `.py-1` - Padding Y-Axis 1rem
- `.py-0.9` - Padding Y-Axis 0rem
- `.py-0.8` - Padding Y-Axis 0rem
- `.py-0.7` - Padding Y-Axis 0rem
- `.py-0.6` - Padding Y-Axis 0rem
- `.py-0.5` - Padding Y-Axis 0rem
- `.py-0.4` - Padding Y-Axis 0rem
- `.py-0.3` - Padding Y-Axis 0rem
- `.py-0.2` - Padding Y-Axis 0.2rem
- `.py-0.1` - Padding Y-Axis 0.1rem
- `.py-0` - Padding Y-Axis 0rem

## Sizing

### Width

- `.hover:w-100` - Width 100% on hover
- `.hover:w-95` - Width 95% on hover
- `.hover:w-90` - Width 90% on hover
- `.hover:w-85` - Width 85% on hover
- `.hover:w-80` - Width 80% on hover
- `.hover:w-75` - Width 75% on hover
- `.hover:w-70` - Width 70% on hover
- `.hover:w-65` - Width 65% on hover
- `.hover:w-60` - Width 60% on hover
- `.hover:w-55` - Width 55% on hover
- `.hover:w-50` - Width 50% on hover
- `.hover:w-45` - Width 45% on hover
- `.hover:w-40` - Width 40% on hover
- `.hover:w-35` - Width 35% on hover
- `.hover:w-30` - Width 30% on hover
- `.hover:w-25` - Width 25% on hover
- `.hover:w-20` - Width 20% on hover
- `.hover:w-15` - Width 15% on hover
- `.hover:w-10` - Width 10% on hover
- `.hover:w-5` - Width 5% on hover
- `.hover:w-auto` - Width auto% on hover
- `.w-100` - Width 100%
- `.w-95` - Width 95%
- `.w-90` - Width 90%
- `.w-85` - Width 85%
- `.w-80` - Width 80%
- `.w-75` - Width 75%
- `.w-70` - Width 70%
- `.w-65` - Width 65%
- `.w-60` - Width 60%
- `.w-55` - Width 55%
- `.w-50` - Width 50%
- `.w-45` - Width 45%
- `.w-40` - Width 40%
- `.w-35` - Width 35%
- `.w-30` - Width 30%
- `.w-25` - Width 25%
- `.w-20` - Width 20%
- `.w-15` - Width 15%
- `.w-10` - Width 10%
- `.w-5` - Width 5%
- `.w-auto` - Width auto%

##### Width - Mobile (<= 480px)

- `.hover:mobile:w-100` - Width 100% on hover on mobile
- `.hover:mobile:w-95` - Width 95% on hover on mobile
- `.hover:mobile:w-90` - Width 90% on hover on mobile
- `.hover:mobile:w-85` - Width 85% on hover on mobile
- `.hover:mobile:w-80` - Width 80% on hover on mobile
- `.hover:mobile:w-75` - Width 75% on hover on mobile
- `.hover:mobile:w-70` - Width 70% on hover on mobile
- `.hover:mobile:w-65` - Width 65% on hover on mobile
- `.hover:mobile:w-60` - Width 60% on hover on mobile
- `.hover:mobile:w-55` - Width 55% on hover on mobile
- `.hover:mobile:w-50` - Width 50% on hover on mobile
- `.hover:mobile:w-45` - Width 45% on hover on mobile
- `.hover:mobile:w-40` - Width 40% on hover on mobile
- `.hover:mobile:w-35` - Width 35% on hover on mobile
- `.hover:mobile:w-30` - Width 30% on hover on mobile
- `.hover:mobile:w-25` - Width 25% on hover on mobile
- `.hover:mobile:w-20` - Width 20% on hover on mobile
- `.hover:mobile:w-15` - Width 15% on hover on mobile
- `.hover:mobile:w-10` - Width 10% on hover on mobile
- `.hover:mobile:w-5` - Width 5% on hover on mobile
- `.hover:mobile:w-auto` - Width auto% on hover on mobile
- `.mobile:w-100` - Width 100% on mobile
- `.mobile:w-95` - Width 95% on mobile
- `.mobile:w-90` - Width 90% on mobile
- `.mobile:w-85` - Width 85% on mobile
- `.mobile:w-80` - Width 80% on mobile
- `.mobile:w-75` - Width 75% on mobile
- `.mobile:w-70` - Width 70% on mobile
- `.mobile:w-65` - Width 65% on mobile
- `.mobile:w-60` - Width 60% on mobile
- `.mobile:w-55` - Width 55% on mobile
- `.mobile:w-50` - Width 50% on mobile
- `.mobile:w-45` - Width 45% on mobile
- `.mobile:w-40` - Width 40% on mobile
- `.mobile:w-35` - Width 35% on mobile
- `.mobile:w-30` - Width 30% on mobile
- `.mobile:w-25` - Width 25% on mobile
- `.mobile:w-20` - Width 20% on mobile
- `.mobile:w-15` - Width 15% on mobile
- `.mobile:w-10` - Width 10% on mobile
- `.mobile:w-5` - Width 5% on mobile
- `.mobile:w-auto` - Width auto% on mobile

##### Width - Tablet (480px - 768px)

- `.hover:tablet:w-100` - Width 100% on hover on tablet
- `.hover:tablet:w-95` - Width 95% on hover on tablet
- `.hover:tablet:w-90` - Width 90% on hover on tablet
- `.hover:tablet:w-85` - Width 85% on hover on tablet
- `.hover:tablet:w-80` - Width 80% on hover on tablet
- `.hover:tablet:w-75` - Width 75% on hover on tablet
- `.hover:tablet:w-70` - Width 70% on hover on tablet
- `.hover:tablet:w-65` - Width 65% on hover on tablet
- `.hover:tablet:w-60` - Width 60% on hover on tablet
- `.hover:tablet:w-55` - Width 55% on hover on tablet
- `.hover:tablet:w-50` - Width 50% on hover on tablet
- `.hover:tablet:w-45` - Width 45% on hover on tablet
- `.hover:tablet:w-40` - Width 40% on hover on tablet
- `.hover:tablet:w-35` - Width 35% on hover on tablet
- `.hover:tablet:w-30` - Width 30% on hover on tablet
- `.hover:tablet:w-25` - Width 25% on hover on tablet
- `.hover:tablet:w-20` - Width 20% on hover on tablet
- `.hover:tablet:w-15` - Width 15% on hover on tablet
- `.hover:tablet:w-10` - Width 10% on hover on tablet
- `.hover:tablet:w-5` - Width 5% on hover on tablet
- `.hover:tablet:w-auto` - Width auto% on hover on tablet
- `.tablet:w-100` - Width 100% on tablet
- `.tablet:w-95` - Width 95% on tablet
- `.tablet:w-90` - Width 90% on tablet
- `.tablet:w-85` - Width 85% on tablet
- `.tablet:w-80` - Width 80% on tablet
- `.tablet:w-75` - Width 75% on tablet
- `.tablet:w-70` - Width 70% on tablet
- `.tablet:w-65` - Width 65% on tablet
- `.tablet:w-60` - Width 60% on tablet
- `.tablet:w-55` - Width 55% on tablet
- `.tablet:w-50` - Width 50% on tablet
- `.tablet:w-45` - Width 45% on tablet
- `.tablet:w-40` - Width 40% on tablet
- `.tablet:w-35` - Width 35% on tablet
- `.tablet:w-30` - Width 30% on tablet
- `.tablet:w-25` - Width 25% on tablet
- `.tablet:w-20` - Width 20% on tablet
- `.tablet:w-15` - Width 15% on tablet
- `.tablet:w-10` - Width 10% on tablet
- `.tablet:w-5` - Width 5% on tablet
- `.tablet:w-auto` - Width auto% on tablet

##### Width - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:w-100` - Width 100% on hover on tablet pc
- `.hover:tablet-pc:w-95` - Width 95% on hover on tablet pc
- `.hover:tablet-pc:w-90` - Width 90% on hover on tablet pc
- `.hover:tablet-pc:w-85` - Width 85% on hover on tablet pc
- `.hover:tablet-pc:w-80` - Width 80% on hover on tablet pc
- `.hover:tablet-pc:w-75` - Width 75% on hover on tablet pc
- `.hover:tablet-pc:w-70` - Width 70% on hover on tablet pc
- `.hover:tablet-pc:w-65` - Width 65% on hover on tablet pc
- `.hover:tablet-pc:w-60` - Width 60% on hover on tablet pc
- `.hover:tablet-pc:w-55` - Width 55% on hover on tablet pc
- `.hover:tablet-pc:w-50` - Width 50% on hover on tablet pc
- `.hover:tablet-pc:w-45` - Width 45% on hover on tablet pc
- `.hover:tablet-pc:w-40` - Width 40% on hover on tablet pc
- `.hover:tablet-pc:w-35` - Width 35% on hover on tablet pc
- `.hover:tablet-pc:w-30` - Width 30% on hover on tablet pc
- `.hover:tablet-pc:w-25` - Width 25% on hover on tablet pc
- `.hover:tablet-pc:w-20` - Width 20% on hover on tablet pc
- `.hover:tablet-pc:w-15` - Width 15% on hover on tablet pc
- `.hover:tablet-pc:w-10` - Width 10% on hover on tablet pc
- `.hover:tablet-pc:w-5` - Width 5% on hover on tablet pc
- `.hover:tablet-pc:w-auto` - Width auto% on hover on tablet pc
- `.tablet-pc:w-100` - Width 100% on tablet pc
- `.tablet-pc:w-95` - Width 95% on tablet pc
- `.tablet-pc:w-90` - Width 90% on tablet pc
- `.tablet-pc:w-85` - Width 85% on tablet pc
- `.tablet-pc:w-80` - Width 80% on tablet pc
- `.tablet-pc:w-75` - Width 75% on tablet pc
- `.tablet-pc:w-70` - Width 70% on tablet pc
- `.tablet-pc:w-65` - Width 65% on tablet pc
- `.tablet-pc:w-60` - Width 60% on tablet pc
- `.tablet-pc:w-55` - Width 55% on tablet pc
- `.tablet-pc:w-50` - Width 50% on tablet pc
- `.tablet-pc:w-45` - Width 45% on tablet pc
- `.tablet-pc:w-40` - Width 40% on tablet pc
- `.tablet-pc:w-35` - Width 35% on tablet pc
- `.tablet-pc:w-30` - Width 30% on tablet pc
- `.tablet-pc:w-25` - Width 25% on tablet pc
- `.tablet-pc:w-20` - Width 20% on tablet pc
- `.tablet-pc:w-15` - Width 15% on tablet pc
- `.tablet-pc:w-10` - Width 10% on tablet pc
- `.tablet-pc:w-5` - Width 5% on tablet pc
- `.tablet-pc:w-auto` - Width auto% on tablet pc

##### Width - Pc (992px - 1200px)

- `.hover:pc:w-100` - Width 100% on hover on pc
- `.hover:pc:w-95` - Width 95% on hover on pc
- `.hover:pc:w-90` - Width 90% on hover on pc
- `.hover:pc:w-85` - Width 85% on hover on pc
- `.hover:pc:w-80` - Width 80% on hover on pc
- `.hover:pc:w-75` - Width 75% on hover on pc
- `.hover:pc:w-70` - Width 70% on hover on pc
- `.hover:pc:w-65` - Width 65% on hover on pc
- `.hover:pc:w-60` - Width 60% on hover on pc
- `.hover:pc:w-55` - Width 55% on hover on pc
- `.hover:pc:w-50` - Width 50% on hover on pc
- `.hover:pc:w-45` - Width 45% on hover on pc
- `.hover:pc:w-40` - Width 40% on hover on pc
- `.hover:pc:w-35` - Width 35% on hover on pc
- `.hover:pc:w-30` - Width 30% on hover on pc
- `.hover:pc:w-25` - Width 25% on hover on pc
- `.hover:pc:w-20` - Width 20% on hover on pc
- `.hover:pc:w-15` - Width 15% on hover on pc
- `.hover:pc:w-10` - Width 10% on hover on pc
- `.hover:pc:w-5` - Width 5% on hover on pc
- `.hover:pc:w-auto` - Width auto% on hover on pc
- `.pc:w-100` - Width 100% on pc
- `.pc:w-95` - Width 95% on pc
- `.pc:w-90` - Width 90% on pc
- `.pc:w-85` - Width 85% on pc
- `.pc:w-80` - Width 80% on pc
- `.pc:w-75` - Width 75% on pc
- `.pc:w-70` - Width 70% on pc
- `.pc:w-65` - Width 65% on pc
- `.pc:w-60` - Width 60% on pc
- `.pc:w-55` - Width 55% on pc
- `.pc:w-50` - Width 50% on pc
- `.pc:w-45` - Width 45% on pc
- `.pc:w-40` - Width 40% on pc
- `.pc:w-35` - Width 35% on pc
- `.pc:w-30` - Width 30% on pc
- `.pc:w-25` - Width 25% on pc
- `.pc:w-20` - Width 20% on pc
- `.pc:w-15` - Width 15% on pc
- `.pc:w-10` - Width 10% on pc
- `.pc:w-5` - Width 5% on pc
- `.pc:w-auto` - Width auto% on pc

##### Width - Tv (>= 1200px)

- `.hover:tv:w-100` - Width 100% on hover on tv
- `.hover:tv:w-95` - Width 95% on hover on tv
- `.hover:tv:w-90` - Width 90% on hover on tv
- `.hover:tv:w-85` - Width 85% on hover on tv
- `.hover:tv:w-80` - Width 80% on hover on tv
- `.hover:tv:w-75` - Width 75% on hover on tv
- `.hover:tv:w-70` - Width 70% on hover on tv
- `.hover:tv:w-65` - Width 65% on hover on tv
- `.hover:tv:w-60` - Width 60% on hover on tv
- `.hover:tv:w-55` - Width 55% on hover on tv
- `.hover:tv:w-50` - Width 50% on hover on tv
- `.hover:tv:w-45` - Width 45% on hover on tv
- `.hover:tv:w-40` - Width 40% on hover on tv
- `.hover:tv:w-35` - Width 35% on hover on tv
- `.hover:tv:w-30` - Width 30% on hover on tv
- `.hover:tv:w-25` - Width 25% on hover on tv
- `.hover:tv:w-20` - Width 20% on hover on tv
- `.hover:tv:w-15` - Width 15% on hover on tv
- `.hover:tv:w-10` - Width 10% on hover on tv
- `.hover:tv:w-5` - Width 5% on hover on tv
- `.hover:tv:w-auto` - Width auto% on hover on tv
- `.tv:w-100` - Width 100% on tv
- `.tv:w-95` - Width 95% on tv
- `.tv:w-90` - Width 90% on tv
- `.tv:w-85` - Width 85% on tv
- `.tv:w-80` - Width 80% on tv
- `.tv:w-75` - Width 75% on tv
- `.tv:w-70` - Width 70% on tv
- `.tv:w-65` - Width 65% on tv
- `.tv:w-60` - Width 60% on tv
- `.tv:w-55` - Width 55% on tv
- `.tv:w-50` - Width 50% on tv
- `.tv:w-45` - Width 45% on tv
- `.tv:w-40` - Width 40% on tv
- `.tv:w-35` - Width 35% on tv
- `.tv:w-30` - Width 30% on tv
- `.tv:w-25` - Width 25% on tv
- `.tv:w-20` - Width 20% on tv
- `.tv:w-15` - Width 15% on tv
- `.tv:w-10` - Width 10% on tv
- `.tv:w-5` - Width 5% on tv
- `.tv:w-auto` - Width auto% on tv

##### Width - Tablet Max (<= 768px)

- `.hover:tablet-max:w-100` - Width 100% on hover on tablet max
- `.hover:tablet-max:w-95` - Width 95% on hover on tablet max
- `.hover:tablet-max:w-90` - Width 90% on hover on tablet max
- `.hover:tablet-max:w-85` - Width 85% on hover on tablet max
- `.hover:tablet-max:w-80` - Width 80% on hover on tablet max
- `.hover:tablet-max:w-75` - Width 75% on hover on tablet max
- `.hover:tablet-max:w-70` - Width 70% on hover on tablet max
- `.hover:tablet-max:w-65` - Width 65% on hover on tablet max
- `.hover:tablet-max:w-60` - Width 60% on hover on tablet max
- `.hover:tablet-max:w-55` - Width 55% on hover on tablet max
- `.hover:tablet-max:w-50` - Width 50% on hover on tablet max
- `.hover:tablet-max:w-45` - Width 45% on hover on tablet max
- `.hover:tablet-max:w-40` - Width 40% on hover on tablet max
- `.hover:tablet-max:w-35` - Width 35% on hover on tablet max
- `.hover:tablet-max:w-30` - Width 30% on hover on tablet max
- `.hover:tablet-max:w-25` - Width 25% on hover on tablet max
- `.hover:tablet-max:w-20` - Width 20% on hover on tablet max
- `.hover:tablet-max:w-15` - Width 15% on hover on tablet max
- `.hover:tablet-max:w-10` - Width 10% on hover on tablet max
- `.hover:tablet-max:w-5` - Width 5% on hover on tablet max
- `.hover:tablet-max:w-auto` - Width auto% on hover on tablet max
- `.tablet-max:w-100` - Width 100% on tablet max
- `.tablet-max:w-95` - Width 95% on tablet max
- `.tablet-max:w-90` - Width 90% on tablet max
- `.tablet-max:w-85` - Width 85% on tablet max
- `.tablet-max:w-80` - Width 80% on tablet max
- `.tablet-max:w-75` - Width 75% on tablet max
- `.tablet-max:w-70` - Width 70% on tablet max
- `.tablet-max:w-65` - Width 65% on tablet max
- `.tablet-max:w-60` - Width 60% on tablet max
- `.tablet-max:w-55` - Width 55% on tablet max
- `.tablet-max:w-50` - Width 50% on tablet max
- `.tablet-max:w-45` - Width 45% on tablet max
- `.tablet-max:w-40` - Width 40% on tablet max
- `.tablet-max:w-35` - Width 35% on tablet max
- `.tablet-max:w-30` - Width 30% on tablet max
- `.tablet-max:w-25` - Width 25% on tablet max
- `.tablet-max:w-20` - Width 20% on tablet max
- `.tablet-max:w-15` - Width 15% on tablet max
- `.tablet-max:w-10` - Width 10% on tablet max
- `.tablet-max:w-5` - Width 5% on tablet max
- `.tablet-max:w-auto` - Width auto% on tablet max

##### Width - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:w-100` - Width 100% on hover on tablet pc max
- `.hover:tablet-pc-max:w-95` - Width 95% on hover on tablet pc max
- `.hover:tablet-pc-max:w-90` - Width 90% on hover on tablet pc max
- `.hover:tablet-pc-max:w-85` - Width 85% on hover on tablet pc max
- `.hover:tablet-pc-max:w-80` - Width 80% on hover on tablet pc max
- `.hover:tablet-pc-max:w-75` - Width 75% on hover on tablet pc max
- `.hover:tablet-pc-max:w-70` - Width 70% on hover on tablet pc max
- `.hover:tablet-pc-max:w-65` - Width 65% on hover on tablet pc max
- `.hover:tablet-pc-max:w-60` - Width 60% on hover on tablet pc max
- `.hover:tablet-pc-max:w-55` - Width 55% on hover on tablet pc max
- `.hover:tablet-pc-max:w-50` - Width 50% on hover on tablet pc max
- `.hover:tablet-pc-max:w-45` - Width 45% on hover on tablet pc max
- `.hover:tablet-pc-max:w-40` - Width 40% on hover on tablet pc max
- `.hover:tablet-pc-max:w-35` - Width 35% on hover on tablet pc max
- `.hover:tablet-pc-max:w-30` - Width 30% on hover on tablet pc max
- `.hover:tablet-pc-max:w-25` - Width 25% on hover on tablet pc max
- `.hover:tablet-pc-max:w-20` - Width 20% on hover on tablet pc max
- `.hover:tablet-pc-max:w-15` - Width 15% on hover on tablet pc max
- `.hover:tablet-pc-max:w-10` - Width 10% on hover on tablet pc max
- `.hover:tablet-pc-max:w-5` - Width 5% on hover on tablet pc max
- `.hover:tablet-pc-max:w-auto` - Width auto% on hover on tablet pc max
- `.tablet-pc-max:w-100` - Width 100% on tablet pc max
- `.tablet-pc-max:w-95` - Width 95% on tablet pc max
- `.tablet-pc-max:w-90` - Width 90% on tablet pc max
- `.tablet-pc-max:w-85` - Width 85% on tablet pc max
- `.tablet-pc-max:w-80` - Width 80% on tablet pc max
- `.tablet-pc-max:w-75` - Width 75% on tablet pc max
- `.tablet-pc-max:w-70` - Width 70% on tablet pc max
- `.tablet-pc-max:w-65` - Width 65% on tablet pc max
- `.tablet-pc-max:w-60` - Width 60% on tablet pc max
- `.tablet-pc-max:w-55` - Width 55% on tablet pc max
- `.tablet-pc-max:w-50` - Width 50% on tablet pc max
- `.tablet-pc-max:w-45` - Width 45% on tablet pc max
- `.tablet-pc-max:w-40` - Width 40% on tablet pc max
- `.tablet-pc-max:w-35` - Width 35% on tablet pc max
- `.tablet-pc-max:w-30` - Width 30% on tablet pc max
- `.tablet-pc-max:w-25` - Width 25% on tablet pc max
- `.tablet-pc-max:w-20` - Width 20% on tablet pc max
- `.tablet-pc-max:w-15` - Width 15% on tablet pc max
- `.tablet-pc-max:w-10` - Width 10% on tablet pc max
- `.tablet-pc-max:w-5` - Width 5% on tablet pc max
- `.tablet-pc-max:w-auto` - Width auto% on tablet pc max

##### Width - Pc Max (<= 1200px)

- `.hover:pc-max:w-100` - Width 100% on hover on pc max
- `.hover:pc-max:w-95` - Width 95% on hover on pc max
- `.hover:pc-max:w-90` - Width 90% on hover on pc max
- `.hover:pc-max:w-85` - Width 85% on hover on pc max
- `.hover:pc-max:w-80` - Width 80% on hover on pc max
- `.hover:pc-max:w-75` - Width 75% on hover on pc max
- `.hover:pc-max:w-70` - Width 70% on hover on pc max
- `.hover:pc-max:w-65` - Width 65% on hover on pc max
- `.hover:pc-max:w-60` - Width 60% on hover on pc max
- `.hover:pc-max:w-55` - Width 55% on hover on pc max
- `.hover:pc-max:w-50` - Width 50% on hover on pc max
- `.hover:pc-max:w-45` - Width 45% on hover on pc max
- `.hover:pc-max:w-40` - Width 40% on hover on pc max
- `.hover:pc-max:w-35` - Width 35% on hover on pc max
- `.hover:pc-max:w-30` - Width 30% on hover on pc max
- `.hover:pc-max:w-25` - Width 25% on hover on pc max
- `.hover:pc-max:w-20` - Width 20% on hover on pc max
- `.hover:pc-max:w-15` - Width 15% on hover on pc max
- `.hover:pc-max:w-10` - Width 10% on hover on pc max
- `.hover:pc-max:w-5` - Width 5% on hover on pc max
- `.hover:pc-max:w-auto` - Width auto% on hover on pc max
- `.pc-max:w-100` - Width 100% on pc max
- `.pc-max:w-95` - Width 95% on pc max
- `.pc-max:w-90` - Width 90% on pc max
- `.pc-max:w-85` - Width 85% on pc max
- `.pc-max:w-80` - Width 80% on pc max
- `.pc-max:w-75` - Width 75% on pc max
- `.pc-max:w-70` - Width 70% on pc max
- `.pc-max:w-65` - Width 65% on pc max
- `.pc-max:w-60` - Width 60% on pc max
- `.pc-max:w-55` - Width 55% on pc max
- `.pc-max:w-50` - Width 50% on pc max
- `.pc-max:w-45` - Width 45% on pc max
- `.pc-max:w-40` - Width 40% on pc max
- `.pc-max:w-35` - Width 35% on pc max
- `.pc-max:w-30` - Width 30% on pc max
- `.pc-max:w-25` - Width 25% on pc max
- `.pc-max:w-20` - Width 20% on pc max
- `.pc-max:w-15` - Width 15% on pc max
- `.pc-max:w-10` - Width 10% on pc max
- `.pc-max:w-5` - Width 5% on pc max
- `.pc-max:w-auto` - Width auto% on pc max

#### Width vh

- `.hover:w-vh-100` - Width vh 100vh on hover
- `.hover:w-vh-75` - Width vh 75vh on hover
- `.hover:w-vh-50` - Width vh 50vh on hover
- `.hover:w-vh-25` - Width vh 25vh on hover
- `.w-vh-100` - Width vh 100vh
- `.w-vh-75` - Width vh 75vh
- `.w-vh-50` - Width vh 50vh
- `.w-vh-25` - Width vh 25vh

#### Width vw

- `.hover:w-vw-100` - Width vw 100vw on hover
- `.hover:w-vw-75` - Width vw 75vw on hover
- `.hover:w-vw-50` - Width vw 50vw on hover
- `.hover:w-vw-25` - Width vw 25vw on hover
- `.w-vw-100` - Width vw 100vw
- `.w-vw-75` - Width vw 75vw
- `.w-vw-50` - Width vw 50vw
- `.w-vw-25` - Width vw 25vw

### Height

- `.h-100` - Height 100%
- `.h-95` - Height 95%
- `.h-90` - Height 90%
- `.h-85` - Height 85%
- `.h-80` - Height 80%
- `.h-75` - Height 75%
- `.h-70` - Height 70%
- `.h-65` - Height 65%
- `.h-60` - Height 60%
- `.h-55` - Height 55%
- `.h-50` - Height 50%
- `.h-45` - Height 45%
- `.h-40` - Height 40%
- `.h-35` - Height 35%
- `.h-30` - Height 30%
- `.h-25` - Height 25%
- `.h-20` - Height 20%
- `.h-15` - Height 15%
- `.h-10` - Height 10%
- `.h-5` - Height 5%
- `.h-auto` - Height auto%
- `.hover:h-100` - Height 100% on hover
- `.hover:h-95` - Height 95% on hover
- `.hover:h-90` - Height 90% on hover
- `.hover:h-85` - Height 85% on hover
- `.hover:h-80` - Height 80% on hover
- `.hover:h-75` - Height 75% on hover
- `.hover:h-70` - Height 70% on hover
- `.hover:h-65` - Height 65% on hover
- `.hover:h-60` - Height 60% on hover
- `.hover:h-55` - Height 55% on hover
- `.hover:h-50` - Height 50% on hover
- `.hover:h-45` - Height 45% on hover
- `.hover:h-40` - Height 40% on hover
- `.hover:h-35` - Height 35% on hover
- `.hover:h-30` - Height 30% on hover
- `.hover:h-25` - Height 25% on hover
- `.hover:h-20` - Height 20% on hover
- `.hover:h-15` - Height 15% on hover
- `.hover:h-10` - Height 10% on hover
- `.hover:h-5` - Height 5% on hover
- `.hover:h-auto` - Height auto% on hover

##### Height - Mobile (<= 480px)

- `.hover:mobile:h-100` - Height 100% on hover on mobile
- `.hover:mobile:h-95` - Height 95% on hover on mobile
- `.hover:mobile:h-90` - Height 90% on hover on mobile
- `.hover:mobile:h-85` - Height 85% on hover on mobile
- `.hover:mobile:h-80` - Height 80% on hover on mobile
- `.hover:mobile:h-75` - Height 75% on hover on mobile
- `.hover:mobile:h-70` - Height 70% on hover on mobile
- `.hover:mobile:h-65` - Height 65% on hover on mobile
- `.hover:mobile:h-60` - Height 60% on hover on mobile
- `.hover:mobile:h-55` - Height 55% on hover on mobile
- `.hover:mobile:h-50` - Height 50% on hover on mobile
- `.hover:mobile:h-45` - Height 45% on hover on mobile
- `.hover:mobile:h-40` - Height 40% on hover on mobile
- `.hover:mobile:h-35` - Height 35% on hover on mobile
- `.hover:mobile:h-30` - Height 30% on hover on mobile
- `.hover:mobile:h-25` - Height 25% on hover on mobile
- `.hover:mobile:h-20` - Height 20% on hover on mobile
- `.hover:mobile:h-15` - Height 15% on hover on mobile
- `.hover:mobile:h-10` - Height 10% on hover on mobile
- `.hover:mobile:h-5` - Height 5% on hover on mobile
- `.hover:mobile:h-auto` - Height auto% on hover on mobile
- `.mobile:h-100` - Height 100% on mobile
- `.mobile:h-95` - Height 95% on mobile
- `.mobile:h-90` - Height 90% on mobile
- `.mobile:h-85` - Height 85% on mobile
- `.mobile:h-80` - Height 80% on mobile
- `.mobile:h-75` - Height 75% on mobile
- `.mobile:h-70` - Height 70% on mobile
- `.mobile:h-65` - Height 65% on mobile
- `.mobile:h-60` - Height 60% on mobile
- `.mobile:h-55` - Height 55% on mobile
- `.mobile:h-50` - Height 50% on mobile
- `.mobile:h-45` - Height 45% on mobile
- `.mobile:h-40` - Height 40% on mobile
- `.mobile:h-35` - Height 35% on mobile
- `.mobile:h-30` - Height 30% on mobile
- `.mobile:h-25` - Height 25% on mobile
- `.mobile:h-20` - Height 20% on mobile
- `.mobile:h-15` - Height 15% on mobile
- `.mobile:h-10` - Height 10% on mobile
- `.mobile:h-5` - Height 5% on mobile
- `.mobile:h-auto` - Height auto% on mobile

##### Height - Tablet (480px - 768px)

- `.hover:tablet:h-100` - Height 100% on hover on tablet
- `.hover:tablet:h-95` - Height 95% on hover on tablet
- `.hover:tablet:h-90` - Height 90% on hover on tablet
- `.hover:tablet:h-85` - Height 85% on hover on tablet
- `.hover:tablet:h-80` - Height 80% on hover on tablet
- `.hover:tablet:h-75` - Height 75% on hover on tablet
- `.hover:tablet:h-70` - Height 70% on hover on tablet
- `.hover:tablet:h-65` - Height 65% on hover on tablet
- `.hover:tablet:h-60` - Height 60% on hover on tablet
- `.hover:tablet:h-55` - Height 55% on hover on tablet
- `.hover:tablet:h-50` - Height 50% on hover on tablet
- `.hover:tablet:h-45` - Height 45% on hover on tablet
- `.hover:tablet:h-40` - Height 40% on hover on tablet
- `.hover:tablet:h-35` - Height 35% on hover on tablet
- `.hover:tablet:h-30` - Height 30% on hover on tablet
- `.hover:tablet:h-25` - Height 25% on hover on tablet
- `.hover:tablet:h-20` - Height 20% on hover on tablet
- `.hover:tablet:h-15` - Height 15% on hover on tablet
- `.hover:tablet:h-10` - Height 10% on hover on tablet
- `.hover:tablet:h-5` - Height 5% on hover on tablet
- `.hover:tablet:h-auto` - Height auto% on hover on tablet
- `.tablet:h-100` - Height 100% on tablet
- `.tablet:h-95` - Height 95% on tablet
- `.tablet:h-90` - Height 90% on tablet
- `.tablet:h-85` - Height 85% on tablet
- `.tablet:h-80` - Height 80% on tablet
- `.tablet:h-75` - Height 75% on tablet
- `.tablet:h-70` - Height 70% on tablet
- `.tablet:h-65` - Height 65% on tablet
- `.tablet:h-60` - Height 60% on tablet
- `.tablet:h-55` - Height 55% on tablet
- `.tablet:h-50` - Height 50% on tablet
- `.tablet:h-45` - Height 45% on tablet
- `.tablet:h-40` - Height 40% on tablet
- `.tablet:h-35` - Height 35% on tablet
- `.tablet:h-30` - Height 30% on tablet
- `.tablet:h-25` - Height 25% on tablet
- `.tablet:h-20` - Height 20% on tablet
- `.tablet:h-15` - Height 15% on tablet
- `.tablet:h-10` - Height 10% on tablet
- `.tablet:h-5` - Height 5% on tablet
- `.tablet:h-auto` - Height auto% on tablet

##### Height - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:h-100` - Height 100% on hover on tablet pc
- `.hover:tablet-pc:h-95` - Height 95% on hover on tablet pc
- `.hover:tablet-pc:h-90` - Height 90% on hover on tablet pc
- `.hover:tablet-pc:h-85` - Height 85% on hover on tablet pc
- `.hover:tablet-pc:h-75` - Height 75% on hover on tablet pc
- `.hover:tablet-pc:h-70` - Height 70% on hover on tablet pc
- `.hover:tablet-pc:h-65` - Height 65% on hover on tablet pc
- `.hover:tablet-pc:h-60` - Height 60% on hover on tablet pc
- `.hover:tablet-pc:h-55` - Height 55% on hover on tablet pc
- `.hover:tablet-pc:h-50` - Height 50% on hover on tablet pc
- `.hover:tablet-pc:h-45` - Height 45% on hover on tablet pc
- `.hover:tablet-pc:h-40` - Height 40% on hover on tablet pc
- `.hover:tablet-pc:h-35` - Height 35% on hover on tablet pc
- `.hover:tablet-pc:h-30` - Height 30% on hover on tablet pc
- `.hover:tablet-pc:h-25` - Height 25% on hover on tablet pc
- `.hover:tablet-pc:h-20` - Height 20% on hover on tablet pc
- `.hover:tablet-pc:h-15` - Height 15% on hover on tablet pc
- `.hover:tablet-pc:h-10` - Height 10% on hover on tablet pc
- `.hover:tablet-pc:h-5` - Height 5% on hover on tablet pc
- `.hover:tablet-pc:h-auto` - Height auto% on hover on tablet pc
- `.tablet-pc:h-100` - Height 100% on tablet pc
- `.tablet-pc:h-95` - Height 95% on tablet pc
- `.tablet-pc:h-90` - Height 90% on tablet pc
- `.tablet-pc:h-85` - Height 85% on tablet pc
- `.tablet-pc:h-80` - Height 80% on tablet pc
- `.tablet-pc:h-75` - Height 75% on tablet pc
- `.tablet-pc:h-70` - Height 70% on tablet pc
- `.tablet-pc:h-65` - Height 65% on tablet pc
- `.tablet-pc:h-60` - Height 60% on tablet pc
- `.tablet-pc:h-55` - Height 55% on tablet pc
- `.tablet-pc:h-50` - Height 50% on tablet pc
- `.tablet-pc:h-45` - Height 45% on tablet pc
- `.tablet-pc:h-40` - Height 40% on tablet pc
- `.tablet-pc:h-35` - Height 35% on tablet pc
- `.tablet-pc:h-30` - Height 30% on tablet pc
- `.tablet-pc:h-25` - Height 25% on tablet pc
- `.tablet-pc:h-20` - Height 20% on tablet pc
- `.tablet-pc:h-15` - Height 15% on tablet pc
- `.tablet-pc:h-10` - Height 10% on tablet pc
- `.tablet-pc:h-5` - Height 5% on tablet pc
- `.tablet-pc:h-auto` - Height auto% on tablet pc

##### Height - Pc (992px - 1200px)

- `.hover:pc:h-100` - Height 100% on hover on pc
- `.hover:pc:h-95` - Height 95% on hover on pc
- `.hover:pc:h-90` - Height 90% on hover on pc
- `.hover:pc:h-85` - Height 85% on hover on pc
- `.hover:pc:h-80` - Height 80% on hover on pc
- `.hover:pc:h-75` - Height 75% on hover on pc
- `.hover:pc:h-70` - Height 70% on hover on pc
- `.hover:pc:h-65` - Height 65% on hover on pc
- `.hover:pc:h-60` - Height 60% on hover on pc
- `.hover:pc:h-55` - Height 55% on hover on pc
- `.hover:pc:h-50` - Height 50% on hover on pc
- `.hover:pc:h-45` - Height 45% on hover on pc
- `.hover:pc:h-40` - Height 40% on hover on pc
- `.hover:pc:h-35` - Height 35% on hover on pc
- `.hover:pc:h-30` - Height 30% on hover on pc
- `.hover:pc:h-25` - Height 25% on hover on pc
- `.hover:pc:h-20` - Height 20% on hover on pc
- `.hover:pc:h-15` - Height 15% on hover on pc
- `.hover:pc:h-10` - Height 10% on hover on pc
- `.hover:pc:h-5` - Height 5% on hover on pc
- `.hover:pc:h-auto` - Height auto% on hover on pc
- `.pc:h-100` - Height 100% on pc
- `.pc:h-95` - Height 95% on pc
- `.pc:h-90` - Height 90% on pc
- `.pc:h-85` - Height 85% on pc
- `.pc:h-80` - Height 80% on pc
- `.pc:h-75` - Height 75% on pc
- `.pc:h-70` - Height 70% on pc
- `.pc:h-65` - Height 65% on pc
- `.pc:h-60` - Height 60% on pc
- `.pc:h-55` - Height 55% on pc
- `.pc:h-50` - Height 50% on pc
- `.pc:h-45` - Height 45% on pc
- `.pc:h-40` - Height 40% on pc
- `.pc:h-35` - Height 35% on pc
- `.pc:h-30` - Height 30% on pc
- `.pc:h-25` - Height 25% on pc
- `.pc:h-20` - Height 20% on pc
- `.pc:h-15` - Height 15% on pc
- `.pc:h-10` - Height 10% on pc
- `.pc:h-5` - Height 5% on pc
- `.pc:h-auto` - Height auto% on pc

##### Height - Tv (>= 1200px)

- `.hover:tv:h-100` - Height 100% on hover on tv
- `.hover:tv:h-95` - Height 95% on hover on tv
- `.hover:tv:h-90` - Height 90% on hover on tv
- `.hover:tv:h-85` - Height 85% on hover on tv
- `.hover:tv:h-80` - Height 80% on hover on tv
- `.hover:tv:h-75` - Height 75% on hover on tv
- `.hover:tv:h-70` - Height 70% on hover on tv
- `.hover:tv:h-65` - Height 65% on hover on tv
- `.hover:tv:h-60` - Height 60% on hover on tv
- `.hover:tv:h-55` - Height 55% on hover on tv
- `.hover:tv:h-50` - Height 50% on hover on tv
- `.hover:tv:h-45` - Height 45% on hover on tv
- `.hover:tv:h-40` - Height 40% on hover on tv
- `.hover:tv:h-35` - Height 35% on hover on tv
- `.hover:tv:h-30` - Height 30% on hover on tv
- `.hover:tv:h-25` - Height 25% on hover on tv
- `.hover:tv:h-20` - Height 20% on hover on tv
- `.hover:tv:h-15` - Height 15% on hover on tv
- `.hover:tv:h-10` - Height 10% on hover on tv
- `.hover:tv:h-5` - Height 5% on hover on tv
- `.hover:tv:h-auto` - Height auto% on hover on tv
- `.tv:h-100` - Height 100% on tv
- `.tv:h-95` - Height 95% on tv
- `.tv:h-90` - Height 90% on tv
- `.tv:h-85` - Height 85% on tv
- `.tv:h-80` - Height 80% on tv
- `.tv:h-75` - Height 75% on tv
- `.tv:h-70` - Height 70% on tv
- `.tv:h-65` - Height 65% on tv
- `.tv:h-60` - Height 60% on tv
- `.tv:h-55` - Height 55% on tv
- `.tv:h-50` - Height 50% on tv
- `.tv:h-45` - Height 45% on tv
- `.tv:h-40` - Height 40% on tv
- `.tv:h-35` - Height 35% on tv
- `.tv:h-30` - Height 30% on tv
- `.tv:h-25` - Height 25% on tv
- `.tv:h-20` - Height 20% on tv
- `.tv:h-15` - Height 15% on tv
- `.tv:h-10` - Height 10% on tv
- `.tv:h-5` - Height 5% on tv
- `.tv:h-auto` - Height auto% on tv

##### Height - Tablet Max (<= 768px)

- `.hover:tablet-max:h-100` - Height 100% on hover on tablet max
- `.hover:tablet-max:h-95` - Height 95% on hover on tablet max
- `.hover:tablet-max:h-90` - Height 90% on hover on tablet max
- `.hover:tablet-max:h-85` - Height 85% on hover on tablet max
- `.hover:tablet-max:h-80` - Height 80% on hover on tablet max
- `.hover:tablet-max:h-75` - Height 75% on hover on tablet max
- `.hover:tablet-max:h-70` - Height 70% on hover on tablet max
- `.hover:tablet-max:h-65` - Height 65% on hover on tablet max
- `.hover:tablet-max:h-60` - Height 60% on hover on tablet max
- `.hover:tablet-max:h-55` - Height 55% on hover on tablet max
- `.hover:tablet-max:h-50` - Height 50% on hover on tablet max
- `.hover:tablet-max:h-45` - Height 45% on hover on tablet max
- `.hover:tablet-max:h-40` - Height 40% on hover on tablet max
- `.hover:tablet-max:h-35` - Height 35% on hover on tablet max
- `.hover:tablet-max:h-30` - Height 30% on hover on tablet max
- `.hover:tablet-max:h-25` - Height 25% on hover on tablet max
- `.hover:tablet-max:h-20` - Height 20% on hover on tablet max
- `.hover:tablet-max:h-15` - Height 15% on hover on tablet max
- `.hover:tablet-max:h-10` - Height 10% on hover on tablet max
- `.hover:tablet-max:h-5` - Height 5% on hover on tablet max
- `.hover:tablet-max:h-auto` - Height auto% on hover on tablet max
- `.tablet-max:h-100` - Height 100% on tablet max
- `.tablet-max:h-95` - Height 95% on tablet max
- `.tablet-max:h-90` - Height 90% on tablet max
- `.tablet-max:h-85` - Height 85% on tablet max
- `.tablet-max:h-80` - Height 80% on tablet max
- `.tablet-max:h-75` - Height 75% on tablet max
- `.tablet-max:h-70` - Height 70% on tablet max
- `.tablet-max:h-65` - Height 65% on tablet max
- `.tablet-max:h-60` - Height 60% on tablet max
- `.tablet-max:h-55` - Height 55% on tablet max
- `.tablet-max:h-50` - Height 50% on tablet max
- `.tablet-max:h-45` - Height 45% on tablet max
- `.tablet-max:h-40` - Height 40% on tablet max
- `.tablet-max:h-35` - Height 35% on tablet max
- `.tablet-max:h-30` - Height 30% on tablet max
- `.tablet-max:h-25` - Height 25% on tablet max
- `.tablet-max:h-20` - Height 20% on tablet max
- `.tablet-max:h-15` - Height 15% on tablet max
- `.tablet-max:h-10` - Height 10% on tablet max
- `.tablet-max:h-5` - Height 5% on tablet max
- `.tablet-max:h-auto` - Height auto% on tablet max

##### Height - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:h-100` - Height 100% on hover on tablet pc max
- `.hover:tablet-pc-max:h-95` - Height 95% on hover on tablet pc max
- `.hover:tablet-pc-max:h-90` - Height 90% on hover on tablet pc max
- `.hover:tablet-pc-max:h-85` - Height 85% on hover on tablet pc max
- `.hover:tablet-pc-max:h-80` - Height 80% on hover on tablet pc max
- `.hover:tablet-pc-max:h-75` - Height 75% on hover on tablet pc max
- `.hover:tablet-pc-max:h-70` - Height 70% on hover on tablet pc max
- `.hover:tablet-pc-max:h-65` - Height 65% on hover on tablet pc max
- `.hover:tablet-pc-max:h-60` - Height 60% on hover on tablet pc max
- `.hover:tablet-pc-max:h-55` - Height 55% on hover on tablet pc max
- `.hover:tablet-pc-max:h-50` - Height 50% on hover on tablet pc max
- `.hover:tablet-pc-max:h-45` - Height 45% on hover on tablet pc max
- `.hover:tablet-pc-max:h-40` - Height 40% on hover on tablet pc max
- `.hover:tablet-pc-max:h-35` - Height 35% on hover on tablet pc max
- `.hover:tablet-pc-max:h-30` - Height 30% on hover on tablet pc max
- `.hover:tablet-pc-max:h-25` - Height 25% on hover on tablet pc max
- `.hover:tablet-pc-max:h-20` - Height 20% on hover on tablet pc max
- `.hover:tablet-pc-max:h-15` - Height 15% on hover on tablet pc max
- `.hover:tablet-pc-max:h-10` - Height 10% on hover on tablet pc max
- `.hover:tablet-pc-max:h-5` - Height 5% on hover on tablet pc max
- `.hover:tablet-pc-max:h-auto` - Height auto% on hover on tablet pc max
- `.tablet-pc-max:h-100` - Height 100% on tablet pc max
- `.tablet-pc-max:h-95` - Height 95% on tablet pc max
- `.tablet-pc-max:h-90` - Height 90% on tablet pc max
- `.tablet-pc-max:h-85` - Height 85% on tablet pc max
- `.tablet-pc-max:h-80` - Height 80% on tablet pc max
- `.tablet-pc-max:h-75` - Height 75% on tablet pc max
- `.tablet-pc-max:h-70` - Height 70% on tablet pc max
- `.tablet-pc-max:h-65` - Height 65% on tablet pc max
- `.tablet-pc-max:h-60` - Height 60% on tablet pc max
- `.tablet-pc-max:h-55` - Height 55% on tablet pc max
- `.tablet-pc-max:h-50` - Height 50% on tablet pc max
- `.tablet-pc-max:h-45` - Height 45% on tablet pc max
- `.tablet-pc-max:h-40` - Height 40% on tablet pc max
- `.tablet-pc-max:h-35` - Height 35% on tablet pc max
- `.tablet-pc-max:h-30` - Height 30% on tablet pc max
- `.tablet-pc-max:h-25` - Height 25% on tablet pc max
- `.tablet-pc-max:h-20` - Height 20% on tablet pc max
- `.tablet-pc-max:h-15` - Height 15% on tablet pc max
- `.tablet-pc-max:h-10` - Height 10% on tablet pc max
- `.tablet-pc-max:h-5` - Height 5% on tablet pc max
- `.tablet-pc-max:h-auto` - Height auto% on tablet pc max

##### Height - Pc Max (<= 1200px)

- `.hover:pc-max:h-100` - Height 100% on hover on pc max
- `.hover:pc-max:h-95` - Height 95% on hover on pc max
- `.hover:pc-max:h-90` - Height 90% on hover on pc max
- `.hover:pc-max:h-85` - Height 85% on hover on pc max
- `.hover:pc-max:h-80` - Height 80% on hover on pc max
- `.hover:pc-max:h-75` - Height 75% on hover on pc max
- `.hover:pc-max:h-70` - Height 70% on hover on pc max
- `.hover:pc-max:h-65` - Height 65% on hover on pc max
- `.hover:pc-max:h-60` - Height 60% on hover on pc max
- `.hover:pc-max:h-55` - Height 55% on hover on pc max
- `.hover:pc-max:h-50` - Height 50% on hover on pc max
- `.hover:pc-max:h-45` - Height 45% on hover on pc max
- `.hover:pc-max:h-40` - Height 40% on hover on pc max
- `.hover:pc-max:h-35` - Height 35% on hover on pc max
- `.hover:pc-max:h-30` - Height 30% on hover on pc max
- `.hover:pc-max:h-25` - Height 25% on hover on pc max
- `.hover:pc-max:h-20` - Height 20% on hover on pc max
- `.hover:pc-max:h-15` - Height 15% on hover on pc max
- `.hover:pc-max:h-10` - Height 10% on hover on pc max
- `.hover:pc-max:h-5` - Height 5% on hover on pc max
- `.hover:pc-max:h-auto` - Height auto% on hover on pc max
- `.pc-max:h-100` - Height 100% on pc max
- `.pc-max:h-95` - Height 95% on pc max
- `.pc-max:h-90` - Height 90% on pc max
- `.pc-max:h-85` - Height 85% on pc max
- `.pc-max:h-80` - Height 80% on pc max
- `.pc-max:h-75` - Height 75% on pc max
- `.pc-max:h-70` - Height 70% on pc max
- `.pc-max:h-65` - Height 65% on pc max
- `.pc-max:h-60` - Height 60% on pc max
- `.pc-max:h-55` - Height 55% on pc max
- `.pc-max:h-50` - Height 50% on pc max
- `.pc-max:h-45` - Height 45% on pc max
- `.pc-max:h-40` - Height 40% on pc max
- `.pc-max:h-35` - Height 35% on pc max
- `.pc-max:h-30` - Height 30% on pc max
- `.pc-max:h-25` - Height 25% on pc max
- `.pc-max:h-20` - Height 20% on pc max
- `.pc-max:h-15` - Height 15% on pc max
- `.pc-max:h-10` - Height 10% on pc max
- `.pc-max:h-5` - Height 5% on pc max
- `.pc-max:h-auto` - Height auto% on pc max

#### Height vh

- `.h-vh-100` - Height vh 100vh
- `.h-vh-75` - Height vh 75vh
- `.h-vh-50` - Height vh 50vh
- `.h-vh-25` - Height vh 25vh
- `.hover:h-vh-100` - Height vh 100vh on hover
- `.hover:h-vh-75` - Height vh 75vh on hover
- `.hover:h-vh-50` - Height vh 50vh on hover
- `.hover:h-vh-25` - Height vh 25vh on hover

#### Height vw

- `.h-vw-100` - Height vw 100vw
- `.h-vw-75` - Height vw 75vw
- `.h-vw-50` - Height vw 50vw
- `.h-vw-25` - Height vw 25vw
- `.hover:h-vw-100` - Height vw 100vw on hover
- `.hover:h-vw-75` - Height vw 75vw on hover
- `.hover:h-vw-50` - Height vw 50vw on hover
- `.hover:h-vw-25` - Height vw 25vw on hover

## Positioning

### Static

- `.hover:static` - Static on hover
- `.static` - Static

### Relative

- `.hover:relative` - Relative on hover
- `.relative` - Relative

### Absolute

- `.absolute` - Absolute
- `.hover:absolute` - Absolute on hover

### Fixed

- `.fixed` - Fixed
- `.hover:fixed` - Fixed on hover

### Sticky

- `.hover:sticky` - Sticky on hover
- `.sticky` - Sticky

### Top

- `.hover:top-100` - Top 100% on hover
- `.hover:top-75` - Top 75% on hover
- `.hover:top-50` - Top 50% on hover
- `.hover:top-25` - Top 25% on hover
- `.hover:top-5` - Top 5rem on hover
- `.hover:top-4.5` - Top 0rem on hover
- `.hover:top-4` - Top 4rem on hover
- `.hover:top-3.5` - Top 0rem on hover
- `.hover:top-3` - Top 3rem on hover
- `.hover:top-2.5` - Top 0rem on hover
- `.hover:top-2` - Top 2rem on hover
- `.hover:top-1.9` - Top 0rem on hover
- `.hover:top-1.8` - Top 0rem on hover
- `.hover:top-1.7` - Top 0rem on hover
- `.hover:top-1.6` - Top 0rem on hover
- `.hover:top-1.5` - Top 0rem on hover
- `.hover:top-1.4` - Top 0rem on hover
- `.hover:top-1.3` - Top 0rem on hover
- `.hover:top-1.2` - Top 0rem on hover
- `.hover:top-1.1` - Top 0rem on hover
- `.hover:top-1` - Top 1rem on hover
- `.hover:top-0.9` - Top 0rem on hover
- `.hover:top-0.8` - Top 0rem on hover
- `.hover:top-0.7` - Top 0rem on hover
- `.hover:top-0.6` - Top 0rem on hover
- `.hover:top-0.5` - Top 0rem on hover
- `.hover:top-0.4` - Top 0rem on hover
- `.hover:top-0.3` - Top 0rem on hover
- `.hover:top-0.2` - Top 0.2rem on hover
- `.hover:top-0.1` - Top 0.1rem on hover
- `.hover:top-0` - Top 0rem on hover
- `.top-100` - Top 100%
- `.top-75` - Top 75%
- `.top-50` - Top 50%
- `.top-25` - Top 25%
- `.top-5` - Top 5rem
- `.top-4.5` - Top 0rem
- `.top-4` - Top 4rem
- `.top-3.5` - Top 0rem
- `.top-3` - Top 3rem
- `.top-2.5` - Top 0rem
- `.top-2` - Top 2rem
- `.top-1.9` - Top 0rem
- `.top-1.8` - Top 0rem
- `.top-1.7` - Top 0rem
- `.top-1.6` - Top 0rem
- `.top-1.5` - Top 0rem
- `.top-1.4` - Top 0rem
- `.top-1.3` - Top 0rem
- `.top-1.2` - Top 0rem
- `.top-1.1` - Top 0rem
- `.top-1` - Top 1rem
- `.top-0.9` - Top 0rem
- `.top-0.8` - Top 0rem
- `.top-0.7` - Top 0rem
- `.top-0.6` - Top 0rem
- `.top-0.5` - Top 0rem
- `.top-0.4` - Top 0rem
- `.top-0.3` - Top 0rem
- `.top-0.2` - Top 0.2rem
- `.top-0.1` - Top 0.1rem
- `.top-0` - Top 0rem

##### Negative Top

- `.-top-5` - Negative Top 5rem
- `.-top-4.5` - Negative Top 0rem
- `.-top-4` - Negative Top 4rem
- `.-top-3.5` - Negative Top 0rem
- `.-top-3` - Negative Top 3rem
- `.-top-2.5` - Negative Top 0rem
- `.-top-2` - Negative Top 2rem
- `.-top-1.9` - Negative Top 0rem
- `.-top-1.8` - Negative Top 0rem
- `.-top-1.7` - Negative Top 0rem
- `.-top-1.6` - Negative Top 0rem
- `.-top-1.5` - Negative Top 0rem
- `.-top-1.4` - Negative Top 0rem
- `.-top-1.3` - Negative Top 0rem
- `.-top-1.2` - Negative Top 0rem
- `.-top-1.1` - Negative Top 0rem
- `.-top-1` - Negative Top 1rem
- `.-top-0.9` - Negative Top 0rem
- `.-top-0.8` - Negative Top 0rem
- `.-top-0.7` - Negative Top 0rem
- `.-top-0.6` - Negative Top 0rem
- `.-top-0.5` - Negative Top 0rem
- `.-top-0.4` - Negative Top 0rem
- `.-top-0.3` - Negative Top 0.3rem
- `.-top-0.2` - Negative Top 0.2rem
- `.-top-0.1` - Negative Top 0.1rem
- `.hover:-top-5` - Negative Top 5rem on hover
- `.hover:-top-4.5` - Negative Top 0rem on hover
- `.hover:-top-4` - Negative Top 4rem on hover
- `.hover:-top-3.5` - Negative Top 0rem on hover
- `.hover:-top-3` - Negative Top 3rem on hover
- `.hover:-top-2.5` - Negative Top 0rem on hover
- `.hover:-top-2` - Negative Top 2rem on hover
- `.hover:-top-1.9` - Negative Top 0rem on hover
- `.hover:-top-1.8` - Negative Top 0rem on hover
- `.hover:-top-1.7` - Negative Top 0rem on hover
- `.hover:-top-1.6` - Negative Top 0rem on hover
- `.hover:-top-1.5` - Negative Top 0rem on hover
- `.hover:-top-1.4` - Negative Top 0rem on hover
- `.hover:-top-1.3` - Negative Top 0rem on hover
- `.hover:-top-1.2` - Negative Top 0rem on hover
- `.hover:-top-1.1` - Negative Top 0rem on hover
- `.hover:-top-1` - Negative Top 1rem on hover
- `.hover:-top-0.9` - Negative Top 0rem on hover
- `.hover:-top-0.8` - Negative Top 0rem on hover
- `.hover:-top-0.7` - Negative Top 0rem on hover
- `.hover:-top-0.6` - Negative Top 0rem on hover
- `.hover:-top-0.5` - Negative Top 0rem on hover
- `.hover:-top-0.4` - Negative Top 0rem on hover
- `.hover:-top-0.3` - Negative Top 0.3rem on hover
- `.hover:-top-0.2` - Negative Top 0.2rem on hover
- `.hover:-top-0.1` - Negative Top 0.1rem on hover

### Right

- `.hover:right-100` - Right 100% on hover
- `.hover:right-75` - Right 75% on hover
- `.hover:right-50` - Right 50% on hover
- `.hover:right-25` - Right 25% on hover
- `.hover:right-5` - Right 5rem on hover
- `.hover:right-4.5` - Right 0rem on hover
- `.hover:right-4` - Right 4rem on hover
- `.hover:right-3.5` - Right 0rem on hover
- `.hover:right-3` - Right 3rem on hover
- `.hover:right-2.5` - Right 0rem on hover
- `.hover:right-2` - Right 2rem on hover
- `.hover:right-1.9` - Right 0rem on hover
- `.hover:right-1.8` - Right 0rem on hover
- `.hover:right-1.7` - Right 0rem on hover
- `.hover:right-1.6` - Right 0rem on hover
- `.hover:right-1.5` - Right 0rem on hover
- `.hover:right-1.4` - Right 0rem on hover
- `.hover:right-1.3` - Right 0rem on hover
- `.hover:right-1.2` - Right 0rem on hover
- `.hover:right-1.1` - Right 0rem on hover
- `.hover:right-1` - Right 1rem on hover
- `.hover:right-0.9` - Right 0rem on hover
- `.hover:right-0.8` - Right 0rem on hover
- `.hover:right-0.7` - Right 0rem on hover
- `.hover:right-0.6` - Right 0rem on hover
- `.hover:right-0.5` - Right 0rem on hover
- `.hover:right-0.4` - Right 0rem on hover
- `.hover:right-0.3` - Right 0rem on hover
- `.hover:right-0.2` - Right 0.2rem on hover
- `.hover:right-0.1` - Right 0.1rem on hover
- `.hover:right-0` - Right 0rem on hover
- `.right-100` - Right 100%
- `.right-75` - Right 75%
- `.right-50` - Right 50%
- `.right-25` - Right 25%
- `.right-5` - Right 5rem
- `.right-4.5` - Right 0rem
- `.right-4` - Right 4rem
- `.right-3.5` - Right 0rem
- `.right-3` - Right 3rem
- `.right-2.5` - Right 0rem
- `.right-2` - Right 2rem
- `.right-1.9` - Right 0rem
- `.right-1.8` - Right 0rem
- `.right-1.7` - Right 0rem
- `.right-1.6` - Right 0rem
- `.right-1.5` - Right 0rem
- `.right-1.4` - Right 0rem
- `.right-1.3` - Right 0rem
- `.right-1.2` - Right 0rem
- `.right-1.1` - Right 0rem
- `.right-1` - Right 1rem
- `.right-0.9` - Right 0rem
- `.right-0.8` - Right 0rem
- `.right-0.7` - Right 0rem
- `.right-0.6` - Right 0rem
- `.right-0.5` - Right 0rem
- `.right-0.4` - Right 0rem
- `.right-0.3` - Right 0rem
- `.right-0.2` - Right 0.2rem
- `.right-0.1` - Right 0.1rem
- `.right-0` - Right 0rem

##### Negative Right

- `.-right-5` - Negative Right 5rem
- `.-right-4.5` - Negative Right 0rem
- `.-right-4` - Negative Right 4rem
- `.-right-3.5` - Negative Right 0rem
- `.-right-3` - Negative Right 3rem
- `.-right-2.5` - Negative Right 0rem
- `.-right-2` - Negative Right 2rem
- `.-right-1.9` - Negative Right 0rem
- `.-right-1.8` - Negative Right 0rem
- `.-right-1.7` - Negative Right 0rem
- `.-right-1.6` - Negative Right 0rem
- `.-right-1.5` - Negative Right 0rem
- `.-right-1.4` - Negative Right 0rem
- `.-right-1.3` - Negative Right 0rem
- `.-right-1.2` - Negative Right 0rem
- `.-right-1.1` - Negative Right 0rem
- `.-right-1` - Negative Right 1rem
- `.-right-0.9` - Negative Right 0rem
- `.-right-0.8` - Negative Right 0rem
- `.-right-0.7` - Negative Right 0rem
- `.-right-0.6` - Negative Right 0rem
- `.-right-0.5` - Negative Right 0rem
- `.-right-0.4` - Negative Right 0rem
- `.-right-0.3` - Negative Right 0.3rem
- `.-right-0.2` - Negative Right 0.2rem
- `.-right-0.1` - Negative Right 0.1rem
- `.hover:-right-5` - Negative Right 5rem on hover
- `.hover:-right-4.5` - Negative Right 0rem on hover
- `.hover:-right-4` - Negative Right 4rem on hover
- `.hover:-right-3.5` - Negative Right 0rem on hover
- `.hover:-right-3` - Negative Right 3rem on hover
- `.hover:-right-2.5` - Negative Right 0rem on hover
- `.hover:-right-2` - Negative Right 2rem on hover
- `.hover:-right-1.9` - Negative Right 0rem on hover
- `.hover:-right-1.8` - Negative Right 0rem on hover
- `.hover:-right-1.7` - Negative Right 0rem on hover
- `.hover:-right-1.6` - Negative Right 0rem on hover
- `.hover:-right-1.5` - Negative Right 0rem on hover
- `.hover:-right-1.4` - Negative Right 0rem on hover
- `.hover:-right-1.3` - Negative Right 0rem on hover
- `.hover:-right-1.2` - Negative Right 0rem on hover
- `.hover:-right-1.1` - Negative Right 0rem on hover
- `.hover:-right-1` - Negative Right 1rem on hover
- `.hover:-right-0.9` - Negative Right 0rem on hover
- `.hover:-right-0.8` - Negative Right 0rem on hover
- `.hover:-right-0.7` - Negative Right 0rem on hover
- `.hover:-right-0.6` - Negative Right 0rem on hover
- `.hover:-right-0.5` - Negative Right 0rem on hover
- `.hover:-right-0.4` - Negative Right 0rem on hover
- `.hover:-right-0.3` - Negative Right 0.3rem on hover
- `.hover:-right-0.2` - Negative Right 0.2rem on hover
- `.hover:-right-0.1` - Negative Right 0.1rem on hover

### Bottom

- `.bottom-100` - Bottom 100%
- `.bottom-75` - Bottom 75%
- `.bottom-50` - Bottom 50%
- `.bottom-25` - Bottom 25%
- `.bottom-5` - Bottom 5rem
- `.bottom-4.5` - Bottom 0rem
- `.bottom-4` - Bottom 4rem
- `.bottom-3.5` - Bottom 0rem
- `.bottom-3` - Bottom 3rem
- `.bottom-2.5` - Bottom 0rem
- `.bottom-2` - Bottom 2rem
- `.bottom-1.9` - Bottom 0rem
- `.bottom-1.8` - Bottom 0rem
- `.bottom-1.7` - Bottom 0rem
- `.bottom-1.6` - Bottom 0rem
- `.bottom-1.5` - Bottom 0rem
- `.bottom-1.4` - Bottom 0rem
- `.bottom-1.3` - Bottom 0rem
- `.bottom-1.2` - Bottom 0rem
- `.bottom-1.1` - Bottom 0rem
- `.bottom-1` - Bottom 1rem
- `.bottom-0.9` - Bottom 0rem
- `.bottom-0.8` - Bottom 0rem
- `.bottom-0.7` - Bottom 0rem
- `.bottom-0.6` - Bottom 0rem
- `.bottom-0.5` - Bottom 0rem
- `.bottom-0.4` - Bottom 0rem
- `.bottom-0.3` - Bottom 0rem
- `.bottom-0.2` - Bottom 0.2rem
- `.bottom-0.1` - Bottom 0.1rem
- `.bottom-0` - Bottom 0rem
- `.hover:bottom-100` - Bottom 100% on hover
- `.hover:bottom-75` - Bottom 75% on hover
- `.hover:bottom-50` - Bottom 50% on hover
- `.hover:bottom-25` - Bottom 25% on hover
- `.hover:bottom-5` - Bottom 5rem on hover
- `.hover:bottom-4.5` - Bottom 0rem on hover
- `.hover:bottom-4` - Bottom 4rem on hover
- `.hover:bottom-3.5` - Bottom 0rem on hover
- `.hover:bottom-3` - Bottom 3rem on hover
- `.hover:bottom-2.5` - Bottom 0rem on hover
- `.hover:bottom-2` - Bottom 2rem on hover
- `.hover:bottom-1.9` - Bottom 0rem on hover
- `.hover:bottom-1.8` - Bottom 0rem on hover
- `.hover:bottom-1.7` - Bottom 0rem on hover
- `.hover:bottom-1.6` - Bottom 0rem on hover
- `.hover:bottom-1.5` - Bottom 0rem on hover
- `.hover:bottom-1.4` - Bottom 0rem on hover
- `.hover:bottom-1.3` - Bottom 0rem on hover
- `.hover:bottom-1.2` - Bottom 0rem on hover
- `.hover:bottom-1.1` - Bottom 0rem on hover
- `.hover:bottom-1` - Bottom 1rem on hover
- `.hover:bottom-0.9` - Bottom 0rem on hover
- `.hover:bottom-0.8` - Bottom 0rem on hover
- `.hover:bottom-0.7` - Bottom 0rem on hover
- `.hover:bottom-0.6` - Bottom 0rem on hover
- `.hover:bottom-0.5` - Bottom 0rem on hover
- `.hover:bottom-0.4` - Bottom 0rem on hover
- `.hover:bottom-0.3` - Bottom 0rem on hover
- `.hover:bottom-0.2` - Bottom 0.2rem on hover
- `.hover:bottom-0.1` - Bottom 0.1rem on hover
- `.hover:bottom-0` - Bottom 0rem on hover

##### Negative Bottom

- `.-bottom-5` - Negative Bottom 5rem
- `.-bottom-4.5` - Negative Bottom 0rem
- `.-bottom-4` - Negative Bottom 4rem
- `.-bottom-3.5` - Negative Bottom 0rem
- `.-bottom-3` - Negative Bottom 3rem
- `.-bottom-2.5` - Negative Bottom 0rem
- `.-bottom-2` - Negative Bottom 2rem
- `.-bottom-1.9` - Negative Bottom 0rem
- `.-bottom-1.8` - Negative Bottom 0rem
- `.-bottom-1.7` - Negative Bottom 0rem
- `.-bottom-1.6` - Negative Bottom 0rem
- `.-bottom-1.5` - Negative Bottom 0rem
- `.-bottom-1.4` - Negative Bottom 0rem
- `.-bottom-1.3` - Negative Bottom 0rem
- `.-bottom-1.2` - Negative Bottom 0rem
- `.-bottom-1.1` - Negative Bottom 0rem
- `.-bottom-1` - Negative Bottom 1rem
- `.-bottom-0.9` - Negative Bottom 0rem
- `.-bottom-0.8` - Negative Bottom 0rem
- `.-bottom-0.7` - Negative Bottom 0rem
- `.-bottom-0.6` - Negative Bottom 0rem
- `.-bottom-0.5` - Negative Bottom 0rem
- `.-bottom-0.4` - Negative Bottom 0rem
- `.-bottom-0.3` - Negative Bottom 0.3rem
- `.-bottom-0.2` - Negative Bottom 0.2rem
- `.-bottom-0.1` - Negative Bottom 0.1rem
- `.hover:-bottom-5` - Negative Bottom 5rem on hover
- `.hover:-bottom-4.5` - Negative Bottom 0rem on hover
- `.hover:-bottom-4` - Negative Bottom 4rem on hover
- `.hover:-bottom-3.5` - Negative Bottom 0rem on hover
- `.hover:-bottom-3` - Negative Bottom 3rem on hover
- `.hover:-bottom-2.5` - Negative Bottom 0rem on hover
- `.hover:-bottom-2` - Negative Bottom 2rem on hover
- `.hover:-bottom-1.9` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.8` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.7` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.6` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.5` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.4` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.3` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.2` - Negative Bottom 0rem on hover
- `.hover:-bottom-1.1` - Negative Bottom 0rem on hover
- `.hover:-bottom-1` - Negative Bottom 1rem on hover
- `.hover:-bottom-0.9` - Negative Bottom 0rem on hover
- `.hover:-bottom-0.8` - Negative Bottom 0rem on hover
- `.hover:-bottom-0.7` - Negative Bottom 0rem on hover
- `.hover:-bottom-0.6` - Negative Bottom 0rem on hover
- `.hover:-bottom-0.5` - Negative Bottom 0rem on hover
- `.hover:-bottom-0.4` - Negative Bottom 0rem on hover
- `.hover:-bottom-0.3` - Negative Bottom 0.3rem on hover
- `.hover:-bottom-0.2` - Negative Bottom 0.2rem on hover
- `.hover:-bottom-0.1` - Negative Bottom 0.1rem on hover

### Left

- `.hover:left-100` - Left 100% on hover
- `.hover:left-75` - Left 75% on hover
- `.hover:left-50` - Left 50% on hover
- `.hover:left-25` - Left 25% on hover
- `.hover:left-5` - Left 5rem on hover
- `.hover:left-4.5` - Left 0rem on hover
- `.hover:left-4` - Left 4rem on hover
- `.hover:left-3.5` - Left 0rem on hover
- `.hover:left-3` - Left 3rem on hover
- `.hover:left-2.5` - Left 0rem on hover
- `.hover:left-2` - Left 2rem on hover
- `.hover:left-1.9` - Left 0rem on hover
- `.hover:left-1.8` - Left 0rem on hover
- `.hover:left-1.7` - Left 0rem on hover
- `.hover:left-1.6` - Left 0rem on hover
- `.hover:left-1.5` - Left 0rem on hover
- `.hover:left-1.4` - Left 0rem on hover
- `.hover:left-1.3` - Left 0rem on hover
- `.hover:left-1.2` - Left 0rem on hover
- `.hover:left-1.1` - Left 0rem on hover
- `.hover:left-1` - Left 1rem on hover
- `.hover:left-0.9` - Left 0rem on hover
- `.hover:left-0.8` - Left 0rem on hover
- `.hover:left-0.7` - Left 0rem on hover
- `.hover:left-0.6` - Left 0rem on hover
- `.hover:left-0.5` - Left 0rem on hover
- `.hover:left-0.4` - Left 0rem on hover
- `.hover:left-0.3` - Left 0rem on hover
- `.hover:left-0.2` - Left 0.2rem on hover
- `.hover:left-0.1` - Left 0.1rem on hover
- `.hover:left-0` - Left 0rem on hover
- `.left-100` - Left 100%
- `.left-75` - Left 75%
- `.left-50` - Left 50%
- `.left-25` - Left 25%
- `.left-5` - Left 5rem
- `.left-4.5` - Left 0rem
- `.left-4` - Left 4rem
- `.left-3.5` - Left 0rem
- `.left-3` - Left 3rem
- `.left-2.5` - Left 0rem
- `.left-2` - Left 2rem
- `.left-1.9` - Left 0rem
- `.left-1.8` - Left 0rem
- `.left-1.7` - Left 0rem
- `.left-1.6` - Left 0rem
- `.left-1.5` - Left 0rem
- `.left-1.4` - Left 0rem
- `.left-1.3` - Left 0rem
- `.left-1.2` - Left 0rem
- `.left-1.1` - Left 0rem
- `.left-1` - Left 1rem
- `.left-0.9` - Left 0rem
- `.left-0.8` - Left 0rem
- `.left-0.7` - Left 0rem
- `.left-0.6` - Left 0rem
- `.left-0.5` - Left 0rem
- `.left-0.4` - Left 0rem
- `.left-0.3` - Left 0rem
- `.left-0.2` - Left 0.2rem
- `.left-0.1` - Left 0.1rem
- `.left-0` - Left 0rem

##### Negative Left

- `.-left-5` - Negative Left 5rem
- `.-left-4.5` - Negative Left 0rem
- `.-left-4` - Negative Left 4rem
- `.-left-3.5` - Negative Left 0rem
- `.-left-3` - Negative Left 3rem
- `.-left-2.5` - Negative Left 0rem
- `.-left-2` - Negative Left 2rem
- `.-left-1.9` - Negative Left 0rem
- `.-left-1.8` - Negative Left 0rem
- `.-left-1.7` - Negative Left 0rem
- `.-left-1.6` - Negative Left 0rem
- `.-left-1.5` - Negative Left 0rem
- `.-left-1.4` - Negative Left 0rem
- `.-left-1.3` - Negative Left 0rem
- `.-left-1.2` - Negative Left 0rem
- `.-left-1.1` - Negative Left 0rem
- `.-left-1` - Negative Left 1rem
- `.-left-0.9` - Negative Left 0rem
- `.-left-0.8` - Negative Left 0rem
- `.-left-0.7` - Negative Left 0rem
- `.-left-0.6` - Negative Left 0rem
- `.-left-0.5` - Negative Left 0rem
- `.-left-0.4` - Negative Left 0rem
- `.-left-0.3` - Negative Left 0.3rem
- `.-left-0.2` - Negative Left 0.2rem
- `.-left-0.1` - Negative Left 0.1rem
- `.hover:-left-5` - Negative Left 5rem on hover
- `.hover:-left-4.5` - Negative Left 0rem on hover
- `.hover:-left-4` - Negative Left 4rem on hover
- `.hover:-left-3.5` - Negative Left 0rem on hover
- `.hover:-left-3` - Negative Left 3rem on hover
- `.hover:-left-2.5` - Negative Left 0rem on hover
- `.hover:-left-2` - Negative Left 2rem on hover
- `.hover:-left-1.9` - Negative Left 0rem on hover
- `.hover:-left-1.8` - Negative Left 0rem on hover
- `.hover:-left-1.7` - Negative Left 0rem on hover
- `.hover:-left-1.6` - Negative Left 0rem on hover
- `.hover:-left-1.5` - Negative Left 0rem on hover
- `.hover:-left-1.4` - Negative Left 0rem on hover
- `.hover:-left-1.3` - Negative Left 0rem on hover
- `.hover:-left-1.2` - Negative Left 0rem on hover
- `.hover:-left-1.1` - Negative Left 0rem on hover
- `.hover:-left-1` - Negative Left 1rem on hover
- `.hover:-left-0.9` - Negative Left 0rem on hover
- `.hover:-left-0.8` - Negative Left 0rem on hover
- `.hover:-left-0.7` - Negative Left 0rem on hover
- `.hover:-left-0.6` - Negative Left 0rem on hover
- `.hover:-left-0.5` - Negative Left 0rem on hover
- `.hover:-left-0.4` - Negative Left 0rem on hover
- `.hover:-left-0.3` - Negative Left 0.3rem on hover
- `.hover:-left-0.2` - Negative Left 0.2rem on hover
- `.hover:-left-0.1` - Negative Left 0.1rem on hover

### Z-Index

- `.hover:z-5` - Z-Index 1005 on hover
- `.hover:z-4` - Z-Index 1004 on hover
- `.hover:z-3` - Z-Index 1003 on hover
- `.hover:z-2` - Z-Index 1002 on hover
- `.hover:z-1` - Z-Index 1001 on hover
- `.hover:z-0` - Z-Index 0 on hover
- `.hover:z-auto` - Z-Index auto on hover
- `.z-5` - Z-Index 1005
- `.z-4` - Z-Index 1004
- `.z-3` - Z-Index 1003
- `.z-2` - Z-Index 1002
- `.z-1` - Z-Index 1001
- `.z-0` - Z-Index 0
- `.z-auto` - Z-Index auto

##### Negative Z-Index

- `.-z-5` - Negative Z-Index 5
- `.-z-4` - Negative Z-Index 4
- `.-z-3` - Negative Z-Index 3
- `.-z-2` - Negative Z-Index 2
- `.-z-1` - Negative Z-Index 1
- `.hover:-z-5` - Negative Z-Index 5 on hover
- `.hover:-z-4` - Negative Z-Index 4 on hover
- `.hover:-z-3` - Negative Z-Index 3 on hover
- `.hover:-z-2` - Negative Z-Index 2 on hover
- `.hover:-z-1` - Negative Z-Index 1 on hover

## Typography

### Font

- `.font-italic` - Font italic
- `.font-normal` - Font normal
- `.hover:font-italic` - Font italic on hover
- `.hover:font-normal` - Font normal on hover

### Font Size

- `.font-size-10` - Font Size 10rem
- `.font-size-9.5` - Font Size 0rem
- `.font-size-9` - Font Size 9rem
- `.font-size-8.5` - Font Size 0rem
- `.font-size-8` - Font Size 8rem
- `.font-size-7.5` - Font Size 0rem
- `.font-size-7` - Font Size 7rem
- `.font-size-6.5` - Font Size 0rem
- `.font-size-6` - Font Size 6rem
- `.font-size-5.5` - Font Size 0rem
- `.font-size-5` - Font Size 5rem
- `.font-size-4.5` - Font Size 0rem
- `.font-size-4` - Font Size 4rem
- `.font-size-3.5` - Font Size 0rem
- `.font-size-3` - Font Size 3rem
- `.font-size-2.5` - Font Size 0rem
- `.font-size-2` - Font Size 2rem
- `.font-size-1.9` - Font Size 0rem
- `.font-size-1.8` - Font Size 0rem
- `.font-size-1.7` - Font Size 0rem
- `.font-size-1.6` - Font Size 0rem
- `.font-size-1.5` - Font Size 0rem
- `.font-size-1.4` - Font Size 0rem
- `.font-size-1.3` - Font Size 0rem
- `.font-size-1.2` - Font Size 0rem
- `.font-size-1.1` - Font Size 0rem
- `.font-size-1` - Font Size 1rem
- `.font-size-0.9` - Font Size 0rem
- `.font-size-0.8` - Font Size 0rem
- `.font-size-0.7` - Font Size 0.7rem
- `.font-size-0.6` - Font Size 0.6rem
- `.font-size-0.5` - Font Size 0.5rem
- `.hover:font-size-10` - Font Size 10rem on hover
- `.hover:font-size-9.5` - Font Size 0rem on hover
- `.hover:font-size-9` - Font Size 9rem on hover
- `.hover:font-size-8.5` - Font Size 0rem on hover
- `.hover:font-size-8` - Font Size 8rem on hover
- `.hover:font-size-7.5` - Font Size 0rem on hover
- `.hover:font-size-7` - Font Size 7rem on hover
- `.hover:font-size-6.5` - Font Size 0rem on hover
- `.hover:font-size-6` - Font Size 6rem on hover
- `.hover:font-size-5.5` - Font Size 0rem on hover
- `.hover:font-size-5` - Font Size 5rem on hover
- `.hover:font-size-4.5` - Font Size 0rem on hover
- `.hover:font-size-4` - Font Size 4rem on hover
- `.hover:font-size-3.5` - Font Size 0rem on hover
- `.hover:font-size-3` - Font Size 3rem on hover
- `.hover:font-size-2.5` - Font Size 0rem on hover
- `.hover:font-size-2` - Font Size 2rem on hover
- `.hover:font-size-1.9` - Font Size 0rem on hover
- `.hover:font-size-1.8` - Font Size 0rem on hover
- `.hover:font-size-1.7` - Font Size 0rem on hover
- `.hover:font-size-1.6` - Font Size 0rem on hover
- `.hover:font-size-1.5` - Font Size 0rem on hover
- `.hover:font-size-1.4` - Font Size 0rem on hover
- `.hover:font-size-1.3` - Font Size 0rem on hover
- `.hover:font-size-1.2` - Font Size 0rem on hover
- `.hover:font-size-1.1` - Font Size 0rem on hover
- `.hover:font-size-1` - Font Size 1rem on hover
- `.hover:font-size-0.9` - Font Size 0rem on hover
- `.hover:font-size-0.8` - Font Size 0rem on hover
- `.hover:font-size-0.7` - Font Size 0.7rem on hover
- `.hover:font-size-0.6` - Font Size 0.6rem on hover
- `.hover:font-size-0.5` - Font Size 0.5rem on hover

### Font Weight

- `.font-weight-900` - Font Weight 900
- `.font-weight-800` - Font Weight 800
- `.font-weight-700` - Font Weight 700
- `.font-weight-600` - Font Weight 600
- `.font-weight-500` - Font Weight 500
- `.font-weight-400` - Font Weight 400
- `.font-weight-300` - Font Weight 300
- `.font-weight-200` - Font Weight 200
- `.font-weight-100` - Font Weight 100
- `.font-weight-bold` - Font Weight bold
- `.hover:font-weight-900` - Font Weight 900 on hover
- `.hover:font-weight-800` - Font Weight 800 on hover
- `.hover:font-weight-700` - Font Weight 700 on hover
- `.hover:font-weight-600` - Font Weight 600 on hover
- `.hover:font-weight-500` - Font Weight 500 on hover
- `.hover:font-weight-400` - Font Weight 400 on hover
- `.hover:font-weight-300` - Font Weight 300 on hover
- `.hover:font-weight-200` - Font Weight 200 on hover
- `.hover:font-weight-100` - Font Weight 100 on hover
- `.hover:font-weight-bold` - Font Weight bold on hover

### Letter spacing

- `.hover:letter-spacing-1` - Letter spacing 1rem on hover
- `.hover:letter-spacing-0.9` - Letter spacing 0rem on hover
- `.hover:letter-spacing-0.8` - Letter spacing 0rem on hover
- `.hover:letter-spacing-0.7` - Letter spacing 0rem on hover
- `.hover:letter-spacing-0.6` - Letter spacing 0rem on hover
- `.hover:letter-spacing-0.5` - Letter spacing 0rem on hover
- `.hover:letter-spacing-0.4` - Letter spacing 0rem on hover
- `.hover:letter-spacing-0.3` - Letter spacing 0.3rem on hover
- `.hover:letter-spacing-0.2` - Letter spacing 0.2rem on hover
- `.hover:letter-spacing-0.1` - Letter spacing 0.1rem on hover
- `.letter-spacing-1` - Letter spacing 1rem
- `.letter-spacing-0.9` - Letter spacing 0rem
- `.letter-spacing-0.8` - Letter spacing 0rem
- `.letter-spacing-0.7` - Letter spacing 0rem
- `.letter-spacing-0.6` - Letter spacing 0rem
- `.letter-spacing-0.5` - Letter spacing 0rem
- `.letter-spacing-0.4` - Letter spacing 0rem
- `.letter-spacing-0.3` - Letter spacing 0.3rem
- `.letter-spacing-0.2` - Letter spacing 0.2rem
- `.letter-spacing-0.1` - Letter spacing 0.1rem

### Line height

- `.hover:line-height-5` - Line height 5rem on hover
- `.hover:line-height-4` - Line height 4rem on hover
- `.hover:line-height-3` - Line height 3rem on hover
- `.hover:line-height-2` - Line height 2rem on hover
- `.hover:line-height-1` - Line height 1rem on hover
- `.line-height-5` - Line height 5rem
- `.line-height-4` - Line height 4rem
- `.line-height-3` - Line height 3rem
- `.line-height-2` - Line height 2rem
- `.line-height-1` - Line height 1rem

### Text

- `.hover:text-capitalize` - Text capitalize on hover
- `.hover:text-center` - Text center on hover
- `.hover:text-end` - Text end on hover
- `.hover:text-justify` - Text justify on hover
- `.hover:text-left` - Text left on hover
- `.hover:text-line-none` - Text line-none on hover
- `.hover:text-line-overline` - Text line-overline on hover
- `.hover:text-line-through` - Text line-through on hover
- `.hover:text-line-underline` - Text line-underline on hover
- `.hover:text-lowercase` - Text lowercase on hover
- `.hover:text-right` - Text right on hover
- `.hover:text-start` - Text start on hover
- `.hover:text-transparent` - Text transparent on hover
- `.hover:text-uppercase` - Text uppercase on hover
- `.text-break-all` - Text break-all
- `.text-break-keep-all` - Text break-keep-all
- `.text-break-normal` - Text break-normal
- `.text-break-word` - Text break-word
- `.text-capitalize` - Text capitalize
- `.text-center` - Text center
- `.text-end` - Text end
- `.text-justify` - Text justify
- `.text-left` - Text left
- `.text-line-none` - Text line-none
- `.text-line-overline` - Text line-overline
- `.text-line-through` - Text line-through
- `.text-line-underline` - Text line-underline
- `.text-lowercase` - Text lowercase
- `.text-overflow-clip` - Text overflow-clip
- `.text-overflow-ellipsis` - Text overflow-ellipsis
- `.text-right` - Text right
- `.text-start` - Text start
- `.text-transparent` - Text transparent
- `.text-uppercase` - Text uppercase

##### Text - Mobile (<= 480px)

- `.hover:mobile:text-center` - Text center on hover on mobile
- `.hover:mobile:text-end` - Text end on hover on mobile
- `.hover:mobile:text-justify` - Text justify on hover on mobile
- `.hover:mobile:text-left` - Text left on hover on mobile
- `.hover:mobile:text-right` - Text right on hover on mobile
- `.hover:mobile:text-start` - Text start on hover on mobile
- `.mobile:text-center` - Text center on mobile
- `.mobile:text-end` - Text end on mobile
- `.mobile:text-justify` - Text justify on mobile
- `.mobile:text-left` - Text left on mobile
- `.mobile:text-right` - Text right on mobile
- `.mobile:text-start` - Text start on mobile

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - Text center on hover on tablet
- `.hover:tablet:text-end` - Text end on hover on tablet
- `.hover:tablet:text-justify` - Text justify on hover on tablet
- `.hover:tablet:text-left` - Text left on hover on tablet
- `.hover:tablet:text-right` - Text right on hover on tablet
- `.hover:tablet:text-start` - Text start on hover on tablet
- `.tablet:text-center` - Text center on tablet
- `.tablet:text-end` - Text end on tablet
- `.tablet:text-justify` - Text justify on tablet
- `.tablet:text-left` - Text left on tablet
- `.tablet:text-right` - Text right on tablet
- `.tablet:text-start` - Text start on tablet

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - Text center on hover on tablet pc
- `.hover:tablet-pc:text-end` - Text end on hover on tablet pc
- `.hover:tablet-pc:text-justify` - Text justify on hover on tablet pc
- `.hover:tablet-pc:text-left` - Text left on hover on tablet pc
- `.hover:tablet-pc:text-right` - Text right on hover on tablet pc
- `.hover:tablet-pc:text-start` - Text start on hover on tablet pc
- `.tablet-pc:text-center` - Text center on tablet pc
- `.tablet-pc:text-end` - Text end on tablet pc
- `.tablet-pc:text-justify` - Text justify on tablet pc
- `.tablet-pc:text-left` - Text left on tablet pc
- `.tablet-pc:text-right` - Text right on tablet pc
- `.tablet-pc:text-start` - Text start on tablet pc

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - Text center on hover on pc
- `.hover:pc:text-end` - Text end on hover on pc
- `.hover:pc:text-justify` - Text justify on hover on pc
- `.hover:pc:text-left` - Text left on hover on pc
- `.hover:pc:text-right` - Text right on hover on pc
- `.hover:pc:text-start` - Text start on hover on pc
- `.pc:text-center` - Text center on pc
- `.pc:text-end` - Text end on pc
- `.pc:text-justify` - Text justify on pc
- `.pc:text-left` - Text left on pc
- `.pc:text-right` - Text right on pc
- `.pc:text-start` - Text start on pc

##### Text - Tv (>= 1200px)

- `.hover:tv:text-center` - Text center on hover on tv
- `.hover:tv:text-end` - Text end on hover on tv
- `.hover:tv:text-justify` - Text justify on hover on tv
- `.hover:tv:text-left` - Text left on hover on tv
- `.hover:tv:text-right` - Text right on hover on tv
- `.hover:tv:text-start` - Text start on hover on tv
- `.tv:text-center` - Text center on tv
- `.tv:text-end` - Text end on tv
- `.tv:text-justify` - Text justify on tv
- `.tv:text-left` - Text left on tv
- `.tv:text-right` - Text right on tv
- `.tv:text-start` - Text start on tv

##### Text - Tablet Max (<= 768px)

- `.hover:tablet-max:text-center` - Text center on hover on tablet max
- `.hover:tablet-max:text-end` - Text end on hover on tablet max
- `.hover:tablet-max:text-justify` - Text justify on hover on tablet max
- `.hover:tablet-max:text-left` - Text left on hover on tablet max
- `.hover:tablet-max:text-right` - Text right on hover on tablet max
- `.hover:tablet-max:text-start` - Text start on hover on tablet max
- `.tablet-max:text-center` - Text center on tablet max
- `.tablet-max:text-end` - Text end on tablet max
- `.tablet-max:text-justify` - Text justify on tablet max
- `.tablet-max:text-left` - Text left on tablet max
- `.tablet-max:text-right` - Text right on tablet max
- `.tablet-max:text-start` - Text start on tablet max

##### Text - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:text-center` - Text center on hover on tablet pc max
- `.hover:tablet-pc-max:text-end` - Text end on hover on tablet pc max
- `.hover:tablet-pc-max:text-justify` - Text justify on hover on tablet pc max
- `.hover:tablet-pc-max:text-left` - Text left on hover on tablet pc max
- `.hover:tablet-pc-max:text-right` - Text right on hover on tablet pc max
- `.hover:tablet-pc-max:text-start` - Text start on hover on tablet pc max
- `.tablet-pc-max:text-center` - Text center on tablet pc max
- `.tablet-pc-max:text-end` - Text end on tablet pc max
- `.tablet-pc-max:text-justify` - Text justify on tablet pc max
- `.tablet-pc-max:text-left` - Text left on tablet pc max
- `.tablet-pc-max:text-right` - Text right on tablet pc max
- `.tablet-pc-max:text-start` - Text start on tablet pc max

##### Text - Pc Max (<= 1200px)

- `.hover:pc-max:text-center` - Text center on hover on pc max
- `.hover:pc-max:text-end` - Text end on hover on pc max
- `.hover:pc-max:text-justify` - Text justify on hover on pc max
- `.hover:pc-max:text-left` - Text left on hover on pc max
- `.hover:pc-max:text-right` - Text right on hover on pc max
- `.hover:pc-max:text-start` - Text start on hover on pc max
- `.pc-max:text-center` - Text center on pc max
- `.pc-max:text-end` - Text end on pc max
- `.pc-max:text-justify` - Text justify on pc max
- `.pc-max:text-left` - Text left on pc max
- `.pc-max:text-right` - Text right on pc max
- `.pc-max:text-start` - Text start on pc max

### Whitespace

- `.hover:whitespace-normal` - Whitespace normal on hover
- `.whitespace-normal` - Whitespace normal
- `.whitespace-nowrap` - Whitespace nowrap
- `.whitespace-pre` - Whitespace pre

### Whitespace break

- `.hover:whitespace-break-spaces` - Whitespace break spaces on hover
- `.whitespace-break-spaces` - Whitespace break spaces

### Whitespace pre

- `.hover:whitespace-pre-line` - Whitespace pre line on hover
- `.hover:whitespace-pre-wrap` - Whitespace pre wrap on hover
- `.whitespace-pre-line` - Whitespace pre line
- `.whitespace-pre-wrap` - Whitespace pre wrap

### Writing h

- `.writing-h-tb` - Writing h tb

### Writing v

- `.writing-v-lr` - Writing v lr
- `.writing-v-rl` - Writing v rl

## Backgrounds

### Background

- `.bg-transparent` - Background transparent
- `.hover:bg-transparent` - Background transparent on hover

### Bg blur

- `.bg-blur-5` - Bg blur 24px
- `.bg-blur-4` - Bg blur 16px
- `.bg-blur-3` - Bg blur 12px
- `.bg-blur-2` - Bg blur 8px
- `.bg-blur-1` - Bg blur 4px
- `.bg-blur-0` - Bg blur 0px
- `.hover:bg-blur-5` - Bg blur 24px on hover
- `.hover:bg-blur-4` - Bg blur 16px on hover
- `.hover:bg-blur-3` - Bg blur 12px on hover
- `.hover:bg-blur-2` - Bg blur 8px on hover
- `.hover:bg-blur-1` - Bg blur 4px on hover
- `.hover:bg-blur-0` - Bg blur 0px on hover

## Borders

### Border

#### Border All

- `.border-2` - Border All 2rem
- `.border-1.5` - Border All 0rem
- `.border-1` - Border All 1rem
- `.border-0.9` - Border All 0rem
- `.border-0.8` - Border All 0rem
- `.border-0.7` - Border All 0rem
- `.border-0.6` - Border All 0rem
- `.border-0.5` - Border All 0rem
- `.border-0.4` - Border All 0.4rem
- `.border-0.3` - Border All 0rem
- `.border-0.2` - Border All 0.2rem
- `.border-0.1` - Border All 0.1rem
- `.border-0` - Border All 0rem
- `.hover:border-2` - Border All 2rem on hover
- `.hover:border-1.5` - Border All 0rem on hover
- `.hover:border-1` - Border All 1rem on hover
- `.hover:border-0.9` - Border All 0rem on hover
- `.hover:border-0.8` - Border All 0rem on hover
- `.hover:border-0.7` - Border All 0rem on hover
- `.hover:border-0.6` - Border All 0rem on hover
- `.hover:border-0.5` - Border All 0rem on hover
- `.hover:border-0.4` - Border All 0rem on hover
- `.hover:border-0.3` - Border All 0rem on hover
- `.hover:border-0.2` - Border All 0.2rem on hover
- `.hover:border-0.1` - Border All 0.1rem on hover
- `.hover:border-0` - Border All 0rem on hover

#### Border Bottom

- `.border-b-2` - Border Bottom 2rem
- `.border-b-1.5` - Border Bottom 0rem
- `.border-b-1` - Border Bottom 1rem
- `.border-b-0.9` - Border Bottom 0rem
- `.border-b-0.8` - Border Bottom 0rem
- `.border-b-0.7` - Border Bottom 0rem
- `.border-b-0.6` - Border Bottom 0rem
- `.border-b-0.5` - Border Bottom 0.5rem
- `.border-b-0.4` - Border Bottom 0rem
- `.border-b-0.3` - Border Bottom 0rem
- `.border-b-0.2` - Border Bottom 0.2rem
- `.border-b-0.1` - Border Bottom 0.1rem
- `.border-b-0` - Border Bottom 0rem
- `.hover:border-b-2` - Border Bottom 2rem on hover
- `.hover:border-b-1.5` - Border Bottom 0rem on hover
- `.hover:border-b-1` - Border Bottom 1rem on hover
- `.hover:border-b-0.9` - Border Bottom 0rem on hover
- `.hover:border-b-0.8` - Border Bottom 0rem on hover
- `.hover:border-b-0.7` - Border Bottom 0rem on hover
- `.hover:border-b-0.6` - Border Bottom 0rem on hover
- `.hover:border-b-0.5` - Border Bottom 0rem on hover
- `.hover:border-b-0.4` - Border Bottom 0rem on hover
- `.hover:border-b-0.3` - Border Bottom 0rem on hover
- `.hover:border-b-0.2` - Border Bottom 0.2rem on hover
- `.hover:border-b-0.1` - Border Bottom 0.1rem on hover
- `.hover:border-b-0` - Border Bottom 0rem on hover

#### Border Left

- `.border-l-2` - Border Left 2rem
- `.border-l-1.5` - Border Left 0rem
- `.border-l-1` - Border Left 1rem
- `.border-l-0.9` - Border Left 0rem
- `.border-l-0.8` - Border Left 0rem
- `.border-l-0.7` - Border Left 0rem
- `.border-l-0.6` - Border Left 0rem
- `.border-l-0.5` - Border Left 0rem
- `.border-l-0.4` - Border Left 0rem
- `.border-l-0.3` - Border Left 0rem
- `.border-l-0.2` - Border Left 0.2rem
- `.border-l-0.1` - Border Left 0.1rem
- `.border-l-0` - Border Left 0rem
- `.hover:border-l-2` - Border Left 2rem on hover
- `.hover:border-l-1.5` - Border Left 0rem on hover
- `.hover:border-l-1` - Border Left 1rem on hover
- `.hover:border-l-0.9` - Border Left 0rem on hover
- `.hover:border-l-0.8` - Border Left 0rem on hover
- `.hover:border-l-0.7` - Border Left 0rem on hover
- `.hover:border-l-0.6` - Border Left 0rem on hover
- `.hover:border-l-0.5` - Border Left 0rem on hover
- `.hover:border-l-0.4` - Border Left 0rem on hover
- `.hover:border-l-0.3` - Border Left 0rem on hover
- `.hover:border-l-0.2` - Border Left 0.2rem on hover
- `.hover:border-l-0.1` - Border Left 0.1rem on hover
- `.hover:border-l-0` - Border Left 0rem on hover

#### Border Right

- `.border-r-2` - Border Right 2rem
- `.border-r-1.5` - Border Right 0rem
- `.border-r-1` - Border Right 1rem
- `.border-r-0.9` - Border Right 0rem
- `.border-r-0.8` - Border Right 0rem
- `.border-r-0.7` - Border Right 0rem
- `.border-r-0.6` - Border Right 0rem
- `.border-r-0.5` - Border Right 0rem
- `.border-r-0.4` - Border Right 0rem
- `.border-r-0.3` - Border Right 0rem
- `.border-r-0.2` - Border Right 0.2rem
- `.border-r-0.1` - Border Right 0.1rem
- `.border-r-0` - Border Right 0rem
- `.hover:border-r-2` - Border Right 2rem on hover
- `.hover:border-r-1.5` - Border Right 0rem on hover
- `.hover:border-r-1` - Border Right 1rem on hover
- `.hover:border-r-0.9` - Border Right 0rem on hover
- `.hover:border-r-0.8` - Border Right 0rem on hover
- `.hover:border-r-0.7` - Border Right 0rem on hover
- `.hover:border-r-0.6` - Border Right 0rem on hover
- `.hover:border-r-0.5` - Border Right 0rem on hover
- `.hover:border-r-0.4` - Border Right 0rem on hover
- `.hover:border-r-0.3` - Border Right 0rem on hover
- `.hover:border-r-0.2` - Border Right 0.2rem on hover
- `.hover:border-r-0.1` - Border Right 0.1rem on hover
- `.hover:border-r-0` - Border Right 0rem on hover

#### Border Top

- `.border-t-2` - Border Top 2rem
- `.border-t-1.5` - Border Top 0rem
- `.border-t-1` - Border Top 1rem
- `.border-t-0.9` - Border Top 0rem
- `.border-t-0.8` - Border Top 0rem
- `.border-t-0.7` - Border Top 0rem
- `.border-t-0.6` - Border Top 0rem
- `.border-t-0.5` - Border Top 0rem
- `.border-t-0.4` - Border Top 0rem
- `.border-t-0.3` - Border Top 0rem
- `.border-t-0.2` - Border Top 0.2rem
- `.border-t-0.1` - Border Top 0.1rem
- `.border-t-0` - Border Top 0rem
- `.hover:border-t-2` - Border Top 2rem on hover
- `.hover:border-t-1.5` - Border Top 0rem on hover
- `.hover:border-t-1` - Border Top 1rem on hover
- `.hover:border-t-0.9` - Border Top 0rem on hover
- `.hover:border-t-0.8` - Border Top 0rem on hover
- `.hover:border-t-0.7` - Border Top 0rem on hover
- `.hover:border-t-0.6` - Border Top 0rem on hover
- `.hover:border-t-0.5` - Border Top 0rem on hover
- `.hover:border-t-0.4` - Border Top 0rem on hover
- `.hover:border-t-0.3` - Border Top 0rem on hover
- `.hover:border-t-0.2` - Border Top 0.2rem on hover
- `.hover:border-t-0.1` - Border Top 0.1rem on hover
- `.hover:border-t-0` - Border Top 0rem on hover

#### Border X-Axis

- `.border-x-2` - Border X-Axis 2rem
- `.border-x-1.5` - Border X-Axis 0rem
- `.border-x-1` - Border X-Axis 1rem
- `.border-x-0.9` - Border X-Axis 0rem
- `.border-x-0.8` - Border X-Axis 0rem
- `.border-x-0.7` - Border X-Axis 0rem
- `.border-x-0.6` - Border X-Axis 0rem
- `.border-x-0.5` - Border X-Axis 0rem
- `.border-x-0.4` - Border X-Axis 0rem
- `.border-x-0.3` - Border X-Axis 0rem
- `.border-x-0.2` - Border X-Axis 0.2rem
- `.border-x-0.1` - Border X-Axis 0.1rem
- `.border-x-0` - Border X-Axis 0rem
- `.hover:border-x-2` - Border X-Axis 2rem on hover
- `.hover:border-x-1.5` - Border X-Axis 0rem on hover
- `.hover:border-x-1` - Border X-Axis 1rem on hover
- `.hover:border-x-0.9` - Border X-Axis 0rem on hover
- `.hover:border-x-0.8` - Border X-Axis 0rem on hover
- `.hover:border-x-0.7` - Border X-Axis 0rem on hover
- `.hover:border-x-0.6` - Border X-Axis 0rem on hover
- `.hover:border-x-0.5` - Border X-Axis 0rem on hover
- `.hover:border-x-0.4` - Border X-Axis 0rem on hover
- `.hover:border-x-0.3` - Border X-Axis 0rem on hover
- `.hover:border-x-0.2` - Border X-Axis 0.2rem on hover
- `.hover:border-x-0.1` - Border X-Axis 0.1rem on hover
- `.hover:border-x-0` - Border X-Axis 0rem on hover

#### Border Y-Axis

- `.border-y-2` - Border Y-Axis 2rem
- `.border-y-1.5` - Border Y-Axis 0rem
- `.border-y-1` - Border Y-Axis 1rem
- `.border-y-0.9` - Border Y-Axis 0rem
- `.border-y-0.8` - Border Y-Axis 0rem
- `.border-y-0.7` - Border Y-Axis 0rem
- `.border-y-0.6` - Border Y-Axis 0rem
- `.border-y-0.5` - Border Y-Axis 0.5rem
- `.border-y-0.4` - Border Y-Axis 0rem
- `.border-y-0.3` - Border Y-Axis 0rem
- `.border-y-0.2` - Border Y-Axis 0.2rem
- `.border-y-0.1` - Border Y-Axis 0.1rem
- `.border-y-0` - Border Y-Axis 0rem
- `.hover:border-y-2` - Border Y-Axis 2rem on hover
- `.hover:border-y-1.5` - Border Y-Axis 0rem on hover
- `.hover:border-y-1` - Border Y-Axis 1rem on hover
- `.hover:border-y-0.9` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.8` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.7` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.6` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.5` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.4` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.3` - Border Y-Axis 0rem on hover
- `.hover:border-y-0.2` - Border Y-Axis 0.2rem on hover
- `.hover:border-y-0.1` - Border Y-Axis 0.1rem on hover
- `.hover:border-y-0` - Border Y-Axis 0rem on hover

### Border Radius

#### Border Radius All

- `.hover:rounded-5` - Border Radius All 5rem on hover
- `.hover:rounded-4.5` - Border Radius All 0rem on hover
- `.hover:rounded-4` - Border Radius All 4rem on hover
- `.hover:rounded-3.5` - Border Radius All 0rem on hover
- `.hover:rounded-3` - Border Radius All 3rem on hover
- `.hover:rounded-2.5` - Border Radius All 0rem on hover
- `.hover:rounded-2` - Border Radius All 2rem on hover
- `.hover:rounded-1.5` - Border Radius All 0rem on hover
- `.hover:rounded-1` - Border Radius All 1rem on hover
- `.hover:rounded-0.9` - Border Radius All 0rem on hover
- `.hover:rounded-0.8` - Border Radius All 0rem on hover
- `.hover:rounded-0.7` - Border Radius All 0rem on hover
- `.hover:rounded-0.6` - Border Radius All 0rem on hover
- `.hover:rounded-0.5` - Border Radius All 0rem on hover
- `.hover:rounded-0.4` - Border Radius All 0rem on hover
- `.hover:rounded-0.3` - Border Radius All 0rem on hover
- `.hover:rounded-0.2` - Border Radius All 0.2rem on hover
- `.hover:rounded-0.1` - Border Radius All 0.1rem on hover
- `.hover:rounded-0` - Border Radius All 0rem on hover
- `.rounded-5` - Border Radius All 5rem
- `.rounded-4.5` - Border Radius All 0rem
- `.rounded-4` - Border Radius All 4rem
- `.rounded-3.5` - Border Radius All 0rem
- `.rounded-3` - Border Radius All 3rem
- `.rounded-2.5` - Border Radius All 0rem
- `.rounded-2` - Border Radius All 2rem
- `.rounded-1.5` - Border Radius All 0rem
- `.rounded-1` - Border Radius All 1rem
- `.rounded-0.9` - Border Radius All 0rem
- `.rounded-0.8` - Border Radius All 0rem
- `.rounded-0.7` - Border Radius All 0rem
- `.rounded-0.6` - Border Radius All 0rem
- `.rounded-0.5` - Border Radius All 0rem
- `.rounded-0.4` - Border Radius All 0rem
- `.rounded-0.3` - Border Radius All 0rem
- `.rounded-0.2` - Border Radius All 0.2rem
- `.rounded-0.1` - Border Radius All 0.1rem
- `.rounded-0` - Border Radius All 0rem

#### Border Radius Bottom Left

- `.hover:rounded-bl-5` - Border Radius Bottom Left 5rem on hover
- `.hover:rounded-bl-4.5` - Border Radius Bottom Left 0rem on hover
- `.hover:rounded-bl-4` - Border Radius Bottom Left 4rem on hover
- `.hover:rounded-bl-3.5` - Border Radius Bottom Left 0rem on hover
- `.hover:rounded-bl-3` - Border Radius Bottom Left 3rem on hover
- `.hover:rounded-bl-2.5` - Border Radius Bottom Left 0rem on hover
- `.hover:rounded-bl-2` - Border Radius Bottom Left 2rem on hover
- `.hover:rounded-bl-1.5` - Border Radius Bottom Left 0rem on hover
- `.hover:rounded-bl-1` - Border Radius Bottom Left 1rem on hover
- `.hover:rounded-bl-0.5` - Border Radius Bottom Left 0.5rem on hover
- `.hover:rounded-bl-0` - Border Radius Bottom Left 0rem on hover
- `.rounded-bl-5` - Border Radius Bottom Left 5rem
- `.rounded-bl-4.5` - Border Radius Bottom Left 0rem
- `.rounded-bl-4` - Border Radius Bottom Left 4rem
- `.rounded-bl-3.5` - Border Radius Bottom Left 0rem
- `.rounded-bl-3` - Border Radius Bottom Left 3rem
- `.rounded-bl-2.5` - Border Radius Bottom Left 0rem
- `.rounded-bl-2` - Border Radius Bottom Left 2rem
- `.rounded-bl-1.5` - Border Radius Bottom Left 0rem
- `.rounded-bl-1` - Border Radius Bottom Left 1rem
- `.rounded-bl-0.5` - Border Radius Bottom Left 0.5rem
- `.rounded-bl-0` - Border Radius Bottom Left 0rem

#### Border Radius Bottom Right

- `.hover:rounded-br-5` - Border Radius Bottom Right 5rem on hover
- `.hover:rounded-br-4.5` - Border Radius Bottom Right 0rem on hover
- `.hover:rounded-br-4` - Border Radius Bottom Right 4rem on hover
- `.hover:rounded-br-3.5` - Border Radius Bottom Right 0rem on hover
- `.hover:rounded-br-3` - Border Radius Bottom Right 3rem on hover
- `.hover:rounded-br-2.5` - Border Radius Bottom Right 0rem on hover
- `.hover:rounded-br-2` - Border Radius Bottom Right 2rem on hover
- `.hover:rounded-br-1.5` - Border Radius Bottom Right 0rem on hover
- `.hover:rounded-br-1` - Border Radius Bottom Right 1rem on hover
- `.hover:rounded-br-0.5` - Border Radius Bottom Right 0.5rem on hover
- `.hover:rounded-br-0` - Border Radius Bottom Right 0rem on hover
- `.rounded-br-5` - Border Radius Bottom Right 5rem
- `.rounded-br-4.5` - Border Radius Bottom Right 0rem
- `.rounded-br-4` - Border Radius Bottom Right 4rem
- `.rounded-br-3.5` - Border Radius Bottom Right 0rem
- `.rounded-br-3` - Border Radius Bottom Right 3rem
- `.rounded-br-2.5` - Border Radius Bottom Right 0rem
- `.rounded-br-2` - Border Radius Bottom Right 2rem
- `.rounded-br-1.5` - Border Radius Bottom Right 0rem
- `.rounded-br-1` - Border Radius Bottom Right 1rem
- `.rounded-br-0.5` - Border Radius Bottom Right 0.5rem
- `.rounded-br-0` - Border Radius Bottom Right 0rem

#### Border Radius Top Left

- `.hover:rounded-tl-5` - Border Radius Top Left 5rem on hover
- `.hover:rounded-tl-4.5` - Border Radius Top Left 0rem on hover
- `.hover:rounded-tl-4` - Border Radius Top Left 4rem on hover
- `.hover:rounded-tl-3.5` - Border Radius Top Left 0rem on hover
- `.hover:rounded-tl-3` - Border Radius Top Left 3rem on hover
- `.hover:rounded-tl-2.5` - Border Radius Top Left 0rem on hover
- `.hover:rounded-tl-2` - Border Radius Top Left 2rem on hover
- `.hover:rounded-tl-1.5` - Border Radius Top Left 0rem on hover
- `.hover:rounded-tl-1` - Border Radius Top Left 1rem on hover
- `.hover:rounded-tl-0.5` - Border Radius Top Left 0.5rem on hover
- `.hover:rounded-tl-0` - Border Radius Top Left 0rem on hover
- `.rounded-tl-5` - Border Radius Top Left 5rem
- `.rounded-tl-4.5` - Border Radius Top Left 0rem
- `.rounded-tl-4` - Border Radius Top Left 4rem
- `.rounded-tl-3.5` - Border Radius Top Left 0rem
- `.rounded-tl-3` - Border Radius Top Left 3rem
- `.rounded-tl-2.5` - Border Radius Top Left 0rem
- `.rounded-tl-2` - Border Radius Top Left 2rem
- `.rounded-tl-1.5` - Border Radius Top Left 0rem
- `.rounded-tl-1` - Border Radius Top Left 1rem
- `.rounded-tl-0.5` - Border Radius Top Left 0.5rem
- `.rounded-tl-0` - Border Radius Top Left 0rem

#### Border Radius Top Right

- `.hover:rounded-tr-5` - Border Radius Top Right 5rem on hover
- `.hover:rounded-tr-4.5` - Border Radius Top Right 0rem on hover
- `.hover:rounded-tr-4` - Border Radius Top Right 4rem on hover
- `.hover:rounded-tr-3.5` - Border Radius Top Right 0rem on hover
- `.hover:rounded-tr-3` - Border Radius Top Right 3rem on hover
- `.hover:rounded-tr-2.5` - Border Radius Top Right 0rem on hover
- `.hover:rounded-tr-2` - Border Radius Top Right 2rem on hover
- `.hover:rounded-tr-1.5` - Border Radius Top Right 0rem on hover
- `.hover:rounded-tr-1` - Border Radius Top Right 1rem on hover
- `.hover:rounded-tr-0.5` - Border Radius Top Right 0.5rem on hover
- `.hover:rounded-tr-0` - Border Radius Top Right 0rem on hover
- `.rounded-tr-5` - Border Radius Top Right 5rem
- `.rounded-tr-4.5` - Border Radius Top Right 0rem
- `.rounded-tr-4` - Border Radius Top Right 4rem
- `.rounded-tr-3.5` - Border Radius Top Right 0rem
- `.rounded-tr-3` - Border Radius Top Right 3rem
- `.rounded-tr-2.5` - Border Radius Top Right 0rem
- `.rounded-tr-2` - Border Radius Top Right 2rem
- `.rounded-tr-1.5` - Border Radius Top Right 0rem
- `.rounded-tr-1` - Border Radius Top Right 1rem
- `.rounded-tr-0.5` - Border Radius Top Right 0.5rem
- `.rounded-tr-0` - Border Radius Top Right 0rem

## Effects

### Box Shadow

#### Box Shadow All

- `.hover:shadow-5` - Box Shadow All 5rem on hover
- `.hover:shadow-5-1` - Box Shadow All 0 0 5rem 2rem on hover
- `.hover:shadow-4` - Box Shadow All 4rem on hover
- `.hover:shadow-4-1` - Box Shadow All 0 0 4rem 2rem on hover
- `.hover:shadow-3` - Box Shadow All 3rem on hover
- `.hover:shadow-3-1` - Box Shadow All 0 0 3rem 2rem on hover
- `.hover:shadow-2` - Box Shadow All 2rem on hover
- `.hover:shadow-2-1` - Box Shadow All 0 0 2rem 2rem on hover
- `.hover:shadow-1` - Box Shadow All 1rem on hover
- `.hover:shadow-1-1` - Box Shadow All 0 0 1rem 2rem on hover
- `.hover:shadow-none` - Box Shadow All none on hover
- `.shadow-5` - Box Shadow All 5rem
- `.shadow-5-1` - Box Shadow All 0 0 5rem 2rem
- `.shadow-4` - Box Shadow All 4rem
- `.shadow-4-1` - Box Shadow All 0 0 4rem 2rem
- `.shadow-3` - Box Shadow All 3rem
- `.shadow-3-1` - Box Shadow All 0 0 3rem 2rem
- `.shadow-2` - Box Shadow All 2rem
- `.shadow-2-1` - Box Shadow All 0 0 2rem 2rem
- `.shadow-1` - Box Shadow All 1rem
- `.shadow-1-1` - Box Shadow All 0 0 1rem 2rem
- `.shadow-none` - Box Shadow All none

#### Box Shadow Bottom

- `.hover:shadow-b-10` - Box Shadow Bottom 10rem on hover
- `.hover:shadow-b-9` - Box Shadow Bottom 9rem on hover
- `.hover:shadow-b-8` - Box Shadow Bottom 8rem on hover
- `.hover:shadow-b-7` - Box Shadow Bottom 7rem on hover
- `.hover:shadow-b-6` - Box Shadow Bottom 6rem on hover
- `.hover:shadow-b-5` - Box Shadow Bottom 5rem on hover
- `.hover:shadow-b-4` - Box Shadow Bottom 4rem on hover
- `.hover:shadow-b-3` - Box Shadow Bottom 3rem on hover
- `.hover:shadow-b-2` - Box Shadow Bottom 2rem on hover
- `.hover:shadow-b-1` - Box Shadow Bottom 1rem on hover
- `.shadow-b-10` - Box Shadow Bottom 10rem
- `.shadow-b-9` - Box Shadow Bottom 9rem
- `.shadow-b-8` - Box Shadow Bottom 8rem
- `.shadow-b-7` - Box Shadow Bottom 7rem
- `.shadow-b-6` - Box Shadow Bottom 6rem
- `.shadow-b-5` - Box Shadow Bottom 5rem
- `.shadow-b-4` - Box Shadow Bottom 4rem
- `.shadow-b-3` - Box Shadow Bottom 3rem
- `.shadow-b-2` - Box Shadow Bottom 2rem
- `.shadow-b-1` - Box Shadow Bottom 1rem

#### Box Shadow Left

- `.hover:shadow-l-10` - Box Shadow Left 10rem on hover
- `.hover:shadow-l-9` - Box Shadow Left 9rem on hover
- `.hover:shadow-l-8` - Box Shadow Left 8rem on hover
- `.hover:shadow-l-7` - Box Shadow Left 7rem on hover
- `.hover:shadow-l-6` - Box Shadow Left 6rem on hover
- `.hover:shadow-l-5` - Box Shadow Left 5rem on hover
- `.hover:shadow-l-4` - Box Shadow Left 4rem on hover
- `.hover:shadow-l-3` - Box Shadow Left 3rem on hover
- `.hover:shadow-l-2` - Box Shadow Left 2rem on hover
- `.hover:shadow-l-1` - Box Shadow Left 1rem on hover
- `.shadow-l-10` - Box Shadow Left 10rem
- `.shadow-l-9` - Box Shadow Left 9rem
- `.shadow-l-8` - Box Shadow Left 8rem
- `.shadow-l-7` - Box Shadow Left 7rem
- `.shadow-l-6` - Box Shadow Left 6rem
- `.shadow-l-5` - Box Shadow Left 5rem
- `.shadow-l-4` - Box Shadow Left 4rem
- `.shadow-l-3` - Box Shadow Left 3rem
- `.shadow-l-2` - Box Shadow Left 2rem
- `.shadow-l-1` - Box Shadow Left 1rem

#### Box Shadow Right

- `.hover:shadow-r-10` - Box Shadow Right 10rem on hover
- `.hover:shadow-r-9` - Box Shadow Right 9rem on hover
- `.hover:shadow-r-8` - Box Shadow Right 8rem on hover
- `.hover:shadow-r-7` - Box Shadow Right 7rem on hover
- `.hover:shadow-r-6` - Box Shadow Right 6rem on hover
- `.hover:shadow-r-5` - Box Shadow Right 5rem on hover
- `.hover:shadow-r-4` - Box Shadow Right 4rem on hover
- `.hover:shadow-r-3` - Box Shadow Right 3rem on hover
- `.hover:shadow-r-2` - Box Shadow Right 2rem on hover
- `.hover:shadow-r-1` - Box Shadow Right 1rem on hover
- `.shadow-r-10` - Box Shadow Right 10rem
- `.shadow-r-9` - Box Shadow Right 9rem
- `.shadow-r-8` - Box Shadow Right 8rem
- `.shadow-r-7` - Box Shadow Right 7rem
- `.shadow-r-6` - Box Shadow Right 6rem
- `.shadow-r-5` - Box Shadow Right 5rem
- `.shadow-r-4` - Box Shadow Right 4rem
- `.shadow-r-3` - Box Shadow Right 3rem
- `.shadow-r-2` - Box Shadow Right 2rem
- `.shadow-r-1` - Box Shadow Right 1rem

#### Box Shadow Top

- `.hover:shadow-t-10` - Box Shadow Top 10rem on hover
- `.hover:shadow-t-9` - Box Shadow Top 9rem on hover
- `.hover:shadow-t-8` - Box Shadow Top 8rem on hover
- `.hover:shadow-t-7` - Box Shadow Top 7rem on hover
- `.hover:shadow-t-6` - Box Shadow Top 6rem on hover
- `.hover:shadow-t-5` - Box Shadow Top 5rem on hover
- `.hover:shadow-t-4` - Box Shadow Top 4rem on hover
- `.hover:shadow-t-3` - Box Shadow Top 3rem on hover
- `.hover:shadow-t-2` - Box Shadow Top 2rem on hover
- `.hover:shadow-t-1` - Box Shadow Top 1rem on hover
- `.shadow-t-10` - Box Shadow Top 10rem
- `.shadow-t-9` - Box Shadow Top 9rem
- `.shadow-t-8` - Box Shadow Top 8rem
- `.shadow-t-7` - Box Shadow Top 7rem
- `.shadow-t-6` - Box Shadow Top 6rem
- `.shadow-t-5` - Box Shadow Top 5rem
- `.shadow-t-4` - Box Shadow Top 4rem
- `.shadow-t-3` - Box Shadow Top 3rem
- `.shadow-t-2` - Box Shadow Top 2rem
- `.shadow-t-1` - Box Shadow Top 1rem

#### Box Shadow X-Axis

- `.hover:shadow-x-10` - Box Shadow X-Axis 10rem on hover
- `.hover:shadow-x-9` - Box Shadow X-Axis 9rem on hover
- `.hover:shadow-x-8` - Box Shadow X-Axis 8rem on hover
- `.hover:shadow-x-7` - Box Shadow X-Axis 7rem on hover
- `.hover:shadow-x-6` - Box Shadow X-Axis 6rem on hover
- `.hover:shadow-x-5` - Box Shadow X-Axis 5rem on hover
- `.hover:shadow-x-4` - Box Shadow X-Axis 4rem on hover
- `.hover:shadow-x-3` - Box Shadow X-Axis 3rem on hover
- `.hover:shadow-x-2` - Box Shadow X-Axis 2rem on hover
- `.hover:shadow-x-1` - Box Shadow X-Axis 1rem on hover
- `.shadow-x-10` - Box Shadow X-Axis 10rem
- `.shadow-x-9` - Box Shadow X-Axis 9rem
- `.shadow-x-8` - Box Shadow X-Axis 8rem
- `.shadow-x-7` - Box Shadow X-Axis 7rem
- `.shadow-x-6` - Box Shadow X-Axis 6rem
- `.shadow-x-5` - Box Shadow X-Axis 5rem
- `.shadow-x-4` - Box Shadow X-Axis 4rem
- `.shadow-x-3` - Box Shadow X-Axis 3rem
- `.shadow-x-2` - Box Shadow X-Axis 2rem
- `.shadow-x-1` - Box Shadow X-Axis 1rem

#### Box Shadow Y-Axis

- `.hover:shadow-y-10` - Box Shadow Y-Axis 10rem on hover
- `.hover:shadow-y-9` - Box Shadow Y-Axis 9rem on hover
- `.hover:shadow-y-8` - Box Shadow Y-Axis 8rem on hover
- `.hover:shadow-y-7` - Box Shadow Y-Axis 7rem on hover
- `.hover:shadow-y-6` - Box Shadow Y-Axis 6rem on hover
- `.hover:shadow-y-5` - Box Shadow Y-Axis 5rem on hover
- `.hover:shadow-y-4` - Box Shadow Y-Axis 4rem on hover
- `.hover:shadow-y-3` - Box Shadow Y-Axis 3rem on hover
- `.hover:shadow-y-2` - Box Shadow Y-Axis 2rem on hover
- `.hover:shadow-y-1` - Box Shadow Y-Axis 1rem on hover
- `.shadow-y-10` - Box Shadow Y-Axis 10rem
- `.shadow-y-9` - Box Shadow Y-Axis 9rem
- `.shadow-y-8` - Box Shadow Y-Axis 8rem
- `.shadow-y-7` - Box Shadow Y-Axis 7rem
- `.shadow-y-6` - Box Shadow Y-Axis 6rem
- `.shadow-y-5` - Box Shadow Y-Axis 5rem
- `.shadow-y-4` - Box Shadow Y-Axis 4rem
- `.shadow-y-3` - Box Shadow Y-Axis 3rem
- `.shadow-y-2` - Box Shadow Y-Axis 2rem
- `.shadow-y-1` - Box Shadow Y-Axis 1rem

### Blur

- `.blur-5` - Blur 24px
- `.blur-4` - Blur 16px
- `.blur-3` - Blur 12px
- `.blur-2` - Blur 8px
- `.blur-1` - Blur 4px
- `.blur-0` - Blur 0px
- `.hover:blur-5` - Blur 24px on hover
- `.hover:blur-4` - Blur 16px on hover
- `.hover:blur-3` - Blur 12px on hover
- `.hover:blur-2` - Blur 8px on hover
- `.hover:blur-1` - Blur 4px on hover
- `.hover:blur-0` - Blur 0px on hover

### Opacity

- `.hover:opacity-100` - Opacity 100% on hover
- `.hover:opacity-95` - Opacity 95% on hover
- `.hover:opacity-90` - Opacity 90% on hover
- `.hover:opacity-85` - Opacity 85% on hover
- `.hover:opacity-80` - Opacity 80% on hover
- `.hover:opacity-75` - Opacity 75% on hover
- `.hover:opacity-70` - Opacity 70% on hover
- `.hover:opacity-65` - Opacity 65% on hover
- `.hover:opacity-60` - Opacity 60% on hover
- `.hover:opacity-55` - Opacity 55% on hover
- `.hover:opacity-50` - Opacity 50% on hover
- `.hover:opacity-45` - Opacity 45% on hover
- `.hover:opacity-40` - Opacity 40% on hover
- `.hover:opacity-35` - Opacity 35% on hover
- `.hover:opacity-30` - Opacity 30% on hover
- `.hover:opacity-25` - Opacity 25% on hover
- `.hover:opacity-20` - Opacity 20% on hover
- `.hover:opacity-15` - Opacity 15% on hover
- `.hover:opacity-10` - Opacity 10% on hover
- `.hover:opacity-5` - Opacity 5% on hover
- `.hover:opacity-0` - Opacity 0% on hover
- `.opacity-100` - Opacity 100%
- `.opacity-95` - Opacity 95%
- `.opacity-90` - Opacity 90%
- `.opacity-85` - Opacity 85%
- `.opacity-80` - Opacity 80%
- `.opacity-75` - Opacity 75%
- `.opacity-70` - Opacity 70%
- `.opacity-65` - Opacity 65%
- `.opacity-60` - Opacity 60%
- `.opacity-55` - Opacity 55%
- `.opacity-50` - Opacity 50%
- `.opacity-45` - Opacity 45%
- `.opacity-40` - Opacity 40%
- `.opacity-35` - Opacity 35%
- `.opacity-30` - Opacity 30%
- `.opacity-25` - Opacity 25%
- `.opacity-20` - Opacity 20%
- `.opacity-15` - Opacity 15%
- `.opacity-10` - Opacity 10%
- `.opacity-5` - Opacity 5%
- `.opacity-0` - Opacity 0%

## Transforms

### Rotate

- `.hover:rotate-180` - Rotate 180deg on hover
- `.hover:rotate-135` - Rotate 135deg on hover
- `.hover:rotate-90` - Rotate 90deg on hover
- `.hover:rotate-45` - Rotate 45deg on hover
- `.hover:rotate-12` - Rotate 12deg on hover
- `.hover:rotate-9` - Rotate 9deg on hover
- `.hover:rotate-6` - Rotate 6deg on hover
- `.hover:rotate-3` - Rotate 3deg on hover
- `.hover:rotate-0` - Rotate 0deg on hover
- `.rotate-180` - Rotate 180deg
- `.rotate-135` - Rotate 135deg
- `.rotate-90` - Rotate 90deg
- `.rotate-45` - Rotate 45deg
- `.rotate-12` - Rotate 12deg
- `.rotate-9` - Rotate 9deg
- `.rotate-6` - Rotate 6deg
- `.rotate-3` - Rotate 3deg
- `.rotate-0` - Rotate 0deg

##### Negative Rotate

- `.-rotate-180` - Negative Rotate 180deg
- `.-rotate-135` - Negative Rotate 135deg
- `.-rotate-90` - Negative Rotate 90deg
- `.-rotate-45` - Negative Rotate 45deg
- `.-rotate-12` - Negative Rotate 12deg
- `.-rotate-9` - Negative Rotate 9deg
- `.-rotate-6` - Negative Rotate 6deg
- `.-rotate-3` - Negative Rotate 3deg
- `.hover:-rotate-180` - Negative Rotate 180deg on hover
- `.hover:-rotate-135` - Negative Rotate 135deg on hover
- `.hover:-rotate-90` - Negative Rotate 90deg on hover
- `.hover:-rotate-45` - Negative Rotate 45deg on hover
- `.hover:-rotate-12` - Negative Rotate 12deg on hover
- `.hover:-rotate-9` - Negative Rotate 9deg on hover
- `.hover:-rotate-6` - Negative Rotate 6deg on hover
- `.hover:-rotate-3` - Negative Rotate 3deg on hover

### Skew

#### Skew X-Axis

- `.hover:skew-x-12` - Skew X-Axis 12deg on hover
- `.hover:skew-x-6` - Skew X-Axis 6deg on hover
- `.hover:skew-x-3` - Skew X-Axis 3deg on hover
- `.hover:skew-x-0` - Skew X-Axis 0deg on hover
- `.skew-x-12` - Skew X-Axis 12deg
- `.skew-x-6` - Skew X-Axis 6deg
- `.skew-x-3` - Skew X-Axis 3deg
- `.skew-x-0` - Skew X-Axis 0deg

##### Negative Skew X-Axis

- `.-skew-x-12` - Negative Skew X-Axis 12deg
- `.-skew-x-6` - Negative Skew X-Axis 6deg
- `.-skew-x-3` - Negative Skew X-Axis 3deg
- `.hover:-skew-x-12` - Negative Skew X-Axis 12deg on hover
- `.hover:-skew-x-6` - Negative Skew X-Axis 6deg on hover
- `.hover:-skew-x-3` - Negative Skew X-Axis 3deg on hover

#### Skew Y-Axis

- `.hover:skew-y-12` - Skew Y-Axis 12deg on hover
- `.hover:skew-y-6` - Skew Y-Axis 6deg on hover
- `.hover:skew-y-3` - Skew Y-Axis 3deg on hover
- `.hover:skew-y-0` - Skew Y-Axis 0deg on hover
- `.skew-y-12` - Skew Y-Axis 12deg
- `.skew-y-6` - Skew Y-Axis 6deg
- `.skew-y-3` - Skew Y-Axis 3deg
- `.skew-y-0` - Skew Y-Axis 0deg

##### Negative Skew Y-Axis

- `.-skew-y-12` - Negative Skew Y-Axis 12deg
- `.-skew-y-6` - Negative Skew Y-Axis 6deg
- `.-skew-y-3` - Negative Skew Y-Axis 3deg
- `.hover:-skew-y-12` - Negative Skew Y-Axis 12deg on hover
- `.hover:-skew-y-6` - Negative Skew Y-Axis 6deg on hover
- `.hover:-skew-y-3` - Negative Skew Y-Axis 3deg on hover

### Translate

- `.hover:translate-50` - Translate 50% on hover
- `.hover:translate-25` - Translate 25% on hover
- `.translate-50` - Translate 50%
- `.translate-25` - Translate 25%

##### Negative Translate

- `.-translate-50` - Negative Translate 50%
- `.-translate-25` - Negative Translate 25%
- `.hover:-translate-50` - Negative Translate 50% on hover
- `.hover:-translate-25` - Negative Translate 25% on hover

#### Translate X-Axis

- `.hover:translate-x-50` - Translate X-Axis 50% on hover
- `.hover:translate-x-25` - Translate X-Axis 25% on hover
- `.hover:translate-x-2` - Translate X-Axis 2rem on hover
- `.hover:translate-x-1.5` - Translate X-Axis 0rem on hover
- `.hover:translate-x-1` - Translate X-Axis 1rem on hover
- `.hover:translate-x-0.5` - Translate X-Axis 0.5rem on hover
- `.hover:translate-x-0` - Translate X-Axis 0rem on hover
- `.translate-x-50` - Translate X-Axis 50%
- `.translate-x-25` - Translate X-Axis 25%
- `.translate-x-2` - Translate X-Axis 2rem
- `.translate-x-1.5` - Translate X-Axis 0rem
- `.translate-x-1` - Translate X-Axis 1rem
- `.translate-x-0.5` - Translate X-Axis 0.5rem
- `.translate-x-0` - Translate X-Axis 0rem

##### Negative Translate X-Axis

- `.-translate-x-50` - Negative Translate X-Axis 50%
- `.-translate-x-25` - Negative Translate X-Axis 25%
- `.-translate-x-2` - Negative Translate X-Axis 2rem
- `.-translate-x-1.5` - Negative Translate X-Axis 1.5rem
- `.-translate-x-1` - Negative Translate X-Axis 1rem
- `.-translate-x-0.5` - Negative Translate X-Axis 0.5rem
- `.hover:-translate-x-50` - Negative Translate X-Axis 50% on hover
- `.hover:-translate-x-25` - Negative Translate X-Axis 25% on hover
- `.hover:-translate-x-2` - Negative Translate X-Axis 2rem on hover
- `.hover:-translate-x-1.5` - Negative Translate X-Axis 1.5rem on hover
- `.hover:-translate-x-1` - Negative Translate X-Axis 1rem on hover
- `.hover:-translate-x-0.5` - Negative Translate X-Axis 0.5rem on hover

#### Translate Y-Axis

- `.hover:translate-y-50` - Translate Y-Axis 50% on hover
- `.hover:translate-y-25` - Translate Y-Axis 25% on hover
- `.hover:translate-y-2` - Translate Y-Axis 2rem on hover
- `.hover:translate-y-1.5` - Translate Y-Axis 0rem on hover
- `.hover:translate-y-1` - Translate Y-Axis 1rem on hover
- `.hover:translate-y-0.5` - Translate Y-Axis 0.5rem on hover
- `.hover:translate-y-0` - Translate Y-Axis 0rem on hover
- `.translate-y-50` - Translate Y-Axis 50%
- `.translate-y-25` - Translate Y-Axis 25%
- `.translate-y-2` - Translate Y-Axis 2rem
- `.translate-y-1.5` - Translate Y-Axis 0rem
- `.translate-y-1` - Translate Y-Axis 1rem
- `.translate-y-0.5` - Translate Y-Axis 0.5rem
- `.translate-y-0` - Translate Y-Axis 0rem

##### Negative Translate Y-Axis

- `.-translate-y-50` - Negative Translate Y-Axis 50%
- `.-translate-y-25` - Negative Translate Y-Axis 25%
- `.-translate-y-2` - Negative Translate Y-Axis 2rem
- `.-translate-y-1.5` - Negative Translate Y-Axis 1.5rem
- `.-translate-y-1` - Negative Translate Y-Axis 1rem
- `.-translate-y-0.5` - Negative Translate Y-Axis 0.5rem
- `.hover:-translate-y-50` - Negative Translate Y-Axis 50% on hover
- `.hover:-translate-y-25` - Negative Translate Y-Axis 25% on hover
- `.hover:-translate-y-2` - Negative Translate Y-Axis 2rem on hover
- `.hover:-translate-y-1.5` - Negative Translate Y-Axis 1.5rem on hover
- `.hover:-translate-y-1` - Negative Translate Y-Axis 1rem on hover
- `.hover:-translate-y-0.5` - Negative Translate Y-Axis 0.5rem on hover

### Zoom

- `.hover:zoom` - Zoom on hover
- `.hover:zoom-2` - Zoom 2 on hover
- `.hover:zoom-1.5` - Zoom 1.5 on hover
- `.zoom` - Zoom
- `.zoom-2` - Zoom 2
- `.zoom-1.5` - Zoom 1.5

## Colors

### Black

- `.black` - Black

### Dark

- `.dark` - Dark

### Light

- `.light` - Light

### Transparent

- `.transparent` - Transparent

## Interactivity

### Cursor

- `.cursor-alias` - Cursor alias
- `.cursor-all-scroll` - Cursor all-scroll
- `.cursor-auto` - Cursor auto
- `.cursor-cell` - Cursor cell
- `.cursor-col-resize` - Cursor col-resize
- `.cursor-context-menu` - Cursor context-menu
- `.cursor-copy` - Cursor copy
- `.cursor-crosshair` - Cursor crosshair
- `.cursor-default` - Cursor
- `.cursor-e-resize` - Cursor e-resize
- `.cursor-ew-resize` - Cursor ew-resize
- `.cursor-grab` - Cursor grab
- `.cursor-grabbing` - Cursor grabbing
- `.cursor-help` - Cursor help
- `.cursor-move` - Cursor move
- `.cursor-n-resize` - Cursor n-resize
- `.cursor-ne-resize` - Cursor ne-resize
- `.cursor-nesw-resize` - Cursor nesw-resize
- `.cursor-no-drop` - Cursor no-drop
- `.cursor-none` - Cursor none
- `.cursor-not-allowed` - Cursor not-allowed
- `.cursor-ns-resize` - Cursor ns-resize
- `.cursor-nw-resize` - Cursor nw-resize
- `.cursor-nwse-resize` - Cursor nwse-resize
- `.cursor-pointer` - Cursor pointer
- `.cursor-progress` - Cursor progress
- `.cursor-row-resize` - Cursor row-resize
- `.cursor-s-resize` - Cursor s-resize
- `.cursor-se-resize` - Cursor se-resize
- `.cursor-sw-resize` - Cursor sw-resize
- `.cursor-text` - Cursor text
- `.cursor-vertical-text` - Cursor vertical-text
- `.cursor-w-resize` - Cursor w-resize
- `.cursor-wait` - Cursor wait
- `.cursor-zoom-in` - Cursor zoom-in
- `.cursor-zoom-out` - Cursor zoom-out

### Disabled

- `.disabled` - Disabled

### Resize

- `.resize` - Resize
- `.resize-none` - Resize none
- `.resize-x` - Resize x
- `.resize-y` - Resize y

### Select

- `.select-auto` - Select auto
- `.select-none` - Select none

## Misc

### Content

- `.content-3` - Content 3
- `.content-3-bg` - Content 3-bg
- `.content-2` - Content 2
- `.content-2-bg` - Content 2-bg
- `.content-2-text` - Content 2-text
- `.content-1` - Content 1
- `.content-1-bg` - Content 1-bg
- `.content-1-text` - Content 1-text
- `.hover:content-3-bg` - Content 3-bg on hover
- `.hover:content-2-bg` - Content 2-bg on hover
- `.hover:content-2-text` - Content 2-text on hover
- `.hover:content-1-bg` - Content 1-bg on hover
- `.hover:content-1-text` - Content 1-text on hover

### Dir

- `.dir-ltr` - Dir ltr
- `.dir-rtl` - Dir rtl

### Mse

- `.hover:mse-2` - Mse 2rem on hover
- `.hover:mse-1.5` - Mse 1.5rem on hover
- `.hover:mse-1` - Mse 1rem on hover
- `.hover:mse-0.5` - Mse 0.5rem on hover
- `.hover:mse-0` - Mse 0rem on hover
- `.mse-2` - Mse 2rem
- `.mse-1.5` - Mse 1.5rem
- `.mse-1` - Mse 1rem
- `.mse-0.5` - Mse 0.5rem
- `.mse-0` - Mse 0rem

### Visibility

- `.hover:v-hide` - Visibility hidden on hover
- `.hover:v-show` - Visibility visible on hover
- `.v-hide` - Visibility hidden
- `.v-show` - Visibility visible

##### Visibility - Mobile (<= 480px)

- `.hover:mobile:v-hide` - Visibility hidden on hover on mobile
- `.hover:mobile:v-show` - Visibility visible on hover on mobile
- `.mobile:v-hide` - Visibility hidden on mobile
- `.mobile:v-show` - Visibility visible on mobile

##### Visibility - Tablet (480px - 768px)

- `.hover:tablet:v-hide` - Visibility hidden on hover on tablet
- `.hover:tablet:v-show` - Visibility visible on hover on tablet
- `.tablet:v-hide` - Visibility hidden on tablet
- `.tablet:v-show` - Visibility visible on tablet

##### Visibility - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:v-hide` - Visibility hidden on hover on tablet pc
- `.hover:tablet-pc:v-show` - Visibility visible on hover on tablet pc
- `.tablet-pc:v-hide` - Visibility hidden on tablet pc
- `.tablet-pc:v-show` - Visibility visible on tablet pc

##### Visibility - Pc (992px - 1200px)

- `.hover:pc:v-hide` - Visibility hidden on hover on pc
- `.hover:pc:v-show` - Visibility visible on hover on pc
- `.pc:v-hide` - Visibility hidden on pc
- `.pc:v-show` - Visibility visible on pc

##### Visibility - Tv (>= 1200px)

- `.hover:tv:v-hide` - Visibility hidden on hover on tv
- `.hover:tv:v-show` - Visibility visible on hover on tv
- `.tv:v-hide` - Visibility hidden on tv
- `.tv:v-show` - Visibility visible on tv

##### Visibility - Tablet Max (<= 768px)

- `.hover:tablet-max:v-hide` - Visibility hidden on hover on tablet max
- `.hover:tablet-max:v-show` - Visibility visible on hover on tablet max
- `.tablet-max:v-hide` - Visibility hidden on tablet max
- `.tablet-max:v-show` - Visibility visible on tablet max

##### Visibility - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:v-hide` - Visibility hidden on hover on tablet pc max
- `.hover:tablet-pc-max:v-show` - Visibility visible on hover on tablet pc max
- `.tablet-pc-max:v-hide` - Visibility hidden on tablet pc max
- `.tablet-pc-max:v-show` - Visibility visible on tablet pc max

##### Visibility - Pc Max (<= 1200px)

- `.hover:pc-max:v-hide` - Visibility hidden on hover on pc max
- `.hover:pc-max:v-show` - Visibility visible on hover on pc max
- `.pc-max:v-hide` - Visibility hidden on pc max
- `.pc-max:v-show` - Visibility visible on pc max

### Customization

bClass uses CSS variables for theming:

- `--plainBg` - Plain background color
- `--contentBg` - Content background color
- `--contentBgPrimary` - Primary content background
- `--contentBgSecondary` - Secondary content background
- `--contentTextPrimary` - Primary text color
- `--contentTextSecondary` - Secondary text color
- `--headerBg` - Header background color

### License

> Distributed under the Bik Public License 2.0 License. See [LICENSE](./../../../LICENSE) for more information.
