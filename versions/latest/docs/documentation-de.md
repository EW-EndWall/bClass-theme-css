# bClass theme css

Eine umfassende Bibliothek zur Entwicklung von Schnittstellen zu Websites und Anwendungen.

## Requirements

Es wird empfohlen, `bClass theme js`, `bClass theme colors`, `bClass components`, `bClass animations` und `bClass media player` zusammen mit dieser Bibliothek zu verwenden.

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

- `.container` - Behälter

### Display

- `.d-block` - Anzeigeblock
- `.d-contents` - Inhalte anzeigen
- `.d-flex` - Display-Flex
- `.d-flow-root` - Flow-Root anzeigen
- `.d-grid` - Anzeigeraster
- `.d-inline` - Inline anzeigen
- `.d-inline-block` - Inline-Block anzeigen
- `.d-inline-flex` - Inline-Flex anzeigen
- `.d-inline-grid` - Inline-Gitter anzeigen
- `.d-inline-table` - Inline-Tabelle anzeigen
- `.d-list-item` - Listenelement anzeigen
- `.d-none` - Keine anzeigen
- `.d-table` - Anzeigetisch
- `.d-table-caption` - Tabellenüberschrift anzeigen
- `.d-table-cell` - Tabellenzelle anzeigen
- `.d-table-col` - Tabellenspalte anzeigen
- `.d-table-col-group` - Tabellenspaltengruppe anzeigen
- `.d-table-footer-group` - Tabellenfußgruppe anzeigen
- `.d-table-header-group` - Tabellenkopfgruppe anzeigen
- `.d-table-row` - Tabellenzeile anzeigen
- `.d-table-row-group` - Tabellenzeilengruppe anzeigen
- `.hover:d-block` - Anzeigeblock beim Schweben
- `.hover:d-flex` - Display-Flex beim Schweben
- `.hover:d-inline` - Bei Hover inline anzeigen
- `.hover:d-inline-block` - Inline-Block beim Hover anzeigen
- `.hover:d-inline-flex` - Inline-Flex beim Hover anzeigen
- `.hover:d-none` - Beim Schweben wird keine angezeigt

##### Display - Mobile (<= 480px)

- `.hover:mobile:d-block` - Anzeigeblock beim Hover auf Mobilgeräten
- `.hover:mobile:d-flex` - Anzeigeflexibilität beim Schweben auf Mobilgeräten
- `.hover:mobile:d-inline` - Anzeige inline beim Hover auf Mobilgeräten
- `.hover:mobile:d-inline-block` - Inline-Block beim Hover auf Mobilgeräten anzeigen
- `.hover:mobile:d-inline-flex` - Inline-Flex beim Hover auf Mobilgeräten anzeigen
- `.hover:mobile:d-none` - Beim Bewegen des Mauszeigers auf dem Mobilgerät wird keine angezeigt
- `.mobile:d-block` - Anzeigeblock auf Mobilgeräten
- `.mobile:d-flex` - Display-Flex auf Mobilgeräten
- `.mobile:d-grid` - Anzeigeraster auf Mobilgeräten
- `.mobile:d-inline` - Inline auf Mobilgeräten anzeigen
- `.mobile:d-inline-block` - Inline-Block auf Mobilgeräten anzeigen
- `.mobile:d-inline-flex` - Inline-Flex auf Mobilgeräten anzeigen
- `.mobile:d-inline-grid` - Inline-Grid auf Mobilgeräten anzeigen
- `.mobile:d-none` - Keine Anzeige auf Mobilgeräten

##### Display - Tablet (480px - 768px)

- `.hover:tablet:d-block` - Anzeigeblock beim Schweben auf dem Tablet
- `.hover:tablet:d-flex` - Display-Flex beim Schweben auf dem Tablet
- `.hover:tablet:d-inline` - Beim Hover auf dem Tablet inline anzeigen
- `.hover:tablet:d-inline-block` - Anzeige des Inline-Blocks beim Hover auf dem Tablet
- `.hover:tablet:d-inline-flex` - Inline-Flex beim Hover auf dem Tablet anzeigen
- `.hover:tablet:d-none` - Beim Bewegen des Mauszeigers auf dem Tablet wird keine angezeigt
- `.tablet:d-block` - Anzeigeblock auf dem Tablet
- `.tablet:d-flex` - Display-Flex auf dem Tablet
- `.tablet:d-grid` - Raster auf dem Tablet anzeigen
- `.tablet:d-inline` - Inline auf dem Tablet anzeigen
- `.tablet:d-inline-block` - Inline-Block auf dem Tablet anzeigen
- `.tablet:d-inline-flex` - Inline-Flex auf dem Tablet anzeigen
- `.tablet:d-inline-grid` - Inline-Raster auf dem Tablet anzeigen
- `.tablet:d-none` - Keine Anzeige auf dem Tablet

##### Display - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:d-block` - Anzeigeblock beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:d-flex` - Display-Flex beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:d-inline` - Anzeige inline beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:d-inline-block` - Anzeige des Inline-Blocks beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:d-inline-flex` - Inline-Flex beim Hover auf dem Tablet-PC anzeigen
- `.hover:tablet-pc:d-none` - Beim Bewegen des Mauszeigers auf dem Tablet-PC wird keine angezeigt
- `.tablet-pc:d-block` - Anzeigeblock auf Tablet-PC
- `.tablet-pc:d-flex` - Display-Flex auf Tablet-PC
- `.tablet-pc:d-grid` - Anzeigeraster auf dem Tablet-PC
- `.tablet-pc:d-inline` - Inline-Anzeige auf dem Tablet-PC
- `.tablet-pc:d-inline-block` - Inline-Block auf Tablet-PC anzeigen
- `.tablet-pc:d-inline-flex` - Inline-Flex auf Tablet-PC anzeigen
- `.tablet-pc:d-inline-grid` - Inline-Raster auf Tablet-PC anzeigen
- `.tablet-pc:d-none` - Keine Anzeige auf dem Tablet-PC

##### Display - Pc (992px - 1200px)

- `.hover:pc:d-block` - Anzeigeblock beim Hover auf dem PC
- `.hover:pc:d-flex` - Display-Flex beim Schweben auf dem PC
- `.hover:pc:d-inline` - Beim Hover auf dem PC inline anzeigen
- `.hover:pc:d-inline-block` - Inline-Block beim Hover auf dem PC anzeigen
- `.hover:pc:d-inline-flex` - Inline-Flex beim Hover auf dem PC anzeigen
- `.hover:pc:d-none` - Beim Hover auf dem PC wird keine angezeigt
- `.pc:d-block` - Anzeigeblock auf dem PC
- `.pc:d-flex` - Flex auf dem PC anzeigen
- `.pc:d-grid` - Raster auf dem PC anzeigen
- `.pc:d-inline` - Inline auf dem PC anzeigen
- `.pc:d-inline-block` - Inline-Block auf dem PC anzeigen
- `.pc:d-inline-flex` - Inline-Flex auf dem PC anzeigen
- `.pc:d-inline-grid` - Inline-Grid auf dem PC anzeigen
- `.pc:d-none` - Keine Anzeige auf dem PC

##### Display - Tv (>= 1200px)

- `.hover:tv:d-block` - Anzeigeblock beim Schweben im Fernsehen
- `.hover:tv:d-flex` - Display-Flex beim Schweben im Fernsehen
- `.hover:tv:d-inline` - Inline-Anzeige beim Hover auf dem Fernseher
- `.hover:tv:d-inline-block` - Inline-Block beim Hover auf dem Fernseher anzeigen
- `.hover:tv:d-inline-flex` - Inline-Flex beim Hover auf dem Fernseher anzeigen
- `.hover:tv:d-none` - Beim Schweben auf dem Fernseher wird keine angezeigt
- `.tv:d-block` - Anzeigeblock im Fernsehen
- `.tv:d-flex` - Flex auf dem Fernseher anzeigen
- `.tv:d-grid` - Raster auf dem Fernseher anzeigen
- `.tv:d-inline` - Inline-Anzeige im Fernsehen
- `.tv:d-inline-block` - Inline-Block auf dem Fernseher anzeigen
- `.tv:d-inline-flex` - Zeigen Sie Inline-Flex auf dem Fernseher an
- `.tv:d-inline-grid` - Inline-Grid auf dem Fernseher anzeigen
- `.tv:d-none` - Keine Anzeige im Fernsehen

##### Display - Tablet Max (<= 768px)

- `.hover:tablet-max:d-block` - Anzeigeblockierung beim Hover auf dem Tablet max
- `.hover:tablet-max:d-flex` - Maximale Displayflexibilität beim Schweben auf dem Tablet
- `.hover:tablet-max:d-inline` - Inline-Anzeige bei Hover auf dem Tablet max
- `.hover:tablet-max:d-inline-block` - Anzeige des Inline-Blocks beim Hover auf dem Tablet max
- `.hover:tablet-max:d-inline-flex` - Maximale Inline-Flex-Anzeige beim Hover auf dem Tablet
- `.hover:tablet-max:d-none` - Keine Anzeige beim Hover auf dem Tablet max
- `.tablet-max:d-block` - Anzeigeblock auf Tablet max
- `.tablet-max:d-flex` - Displayflex auf dem Tablet max
- `.tablet-max:d-grid` - Anzeigeraster auf dem Tablet max
- `.tablet-max:d-inline` - Anzeige inline auf Tablet max
- `.tablet-max:d-inline-block` - Inline-Block auf Tablet anzeigen max
- `.tablet-max:d-inline-flex` - Display Inline-Flex auf Tablet max
- `.tablet-max:d-inline-grid` - Inline-Grid auf dem Tablet anzeigen max
- `.tablet-max:d-none` - Keine Anzeige auf dem Tablet max

##### Display - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:d-block` - Anzeigeblock beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:d-flex` - Displayflex beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:d-inline` - Inline-Anzeige beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:d-inline-block` - Anzeige des Inline-Blocks beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:d-inline-flex` - Anzeige Inline-Flex beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:d-none` - Keine Anzeige beim Hover auf dem Tablet-PC max
- `.tablet-pc-max:d-block` - Anzeigeblock auf Tablet-PC max
- `.tablet-pc-max:d-flex` - Displayflex am Tablet-PC max
- `.tablet-pc-max:d-grid` - Anzeigeraster auf Tablet-PC max
- `.tablet-pc-max:d-inline` - Anzeige inline auf Tablet-PC max
- `.tablet-pc-max:d-inline-block` - Anzeige Inline-Block auf Tablet-PC max
- `.tablet-pc-max:d-inline-flex` - Anzeige Inline-Flex auf Tablet-PC max
- `.tablet-pc-max:d-inline-grid` - Anzeige Inline-Grid auf Tablet-PC max
- `.tablet-pc-max:d-none` - Anzeige keine auf Tablet-PC max

##### Display - Pc Max (<= 1200px)

- `.hover:pc-max:d-block` - Anzeigeblock beim Hover auf dem PC max
- `.hover:pc-max:d-flex` - Anzeigeflexibilität beim Schweben auf dem PC max
- `.hover:pc-max:d-inline` - Anzeige inline beim Hover auf dem PC max
- `.hover:pc-max:d-inline-block` - Anzeige des Inline-Blocks beim Hover auf dem PC max
- `.hover:pc-max:d-inline-flex` - Anzeige von Inline-Flex beim Hover auf dem PC max
- `.hover:pc-max:d-none` - Keine Anzeige beim Hover auf dem PC max
- `.pc-max:d-block` - Anzeigeblock am PC max
- `.pc-max:d-flex` - Displayflex am PC max
- `.pc-max:d-grid` - Anzeigeraster am PC max
- `.pc-max:d-inline` - Anzeige inline auf dem PC max
- `.pc-max:d-inline-block` - Inline-Block auf PC anzeigen max
- `.pc-max:d-inline-flex` - Inline-Flex auf dem PC anzeigen max
- `.pc-max:d-inline-grid` - Anzeige des Inline-Grids auf dem PC max
- `.pc-max:d-none` - Anzeige keine auf PC max

### Float

- `.float-end` - Float Ende
- `.float-left` - Float links
- `.float-none` - Float keine
- `.float-right` - Float rechts
- `.float-start` - Float Anfang
- `.hover:float-end` - Float Ende beim Hover
- `.hover:float-left` - Float links beim Hover
- `.hover:float-none` - Float keine beim Hover
- `.hover:float-right` - Float rechts beim Hover
- `.hover:float-start` - Float Anfang beim Hover

##### Float - Mobile (<= 480px)

- `.hover:mobile:float-end` - Float Ende beim Hover auf Mobilgeräten
- `.hover:mobile:float-left` - Float links beim Hover auf Mobilgeräten
- `.hover:mobile:float-none` - Float keine beim Hover auf Mobilgeräten
- `.hover:mobile:float-right` - Float rechts beim Hover auf Mobilgeräten
- `.hover:mobile:float-start` - Float Anfang beim Hover auf Mobilgeräten
- `.mobile:float-end` - Float Ende auf Mobilgeräten
- `.mobile:float-left` - Float links auf Mobilgeräten
- `.mobile:float-none` - Float keine auf Mobilgeräten
- `.mobile:float-right` - Float rechts auf Mobilgeräten
- `.mobile:float-start` - Float Anfang auf Mobilgeräten

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - Float Ende beim Hover auf Tablets
- `.hover:tablet:float-left` - Float links beim Hover auf Tablets
- `.hover:tablet:float-none` - Float keine beim Hover auf Tablets
- `.hover:tablet:float-right` - Float rechts beim Hover auf Tablets
- `.hover:tablet:float-start` - Float Anfang beim Hover auf Tablets
- `.tablet:float-end` - Float Ende auf Tablets
- `.tablet:float-left` - Float links auf Tablets
- `.tablet:float-none` - Float keine auf Tablets
- `.tablet:float-right` - Float rechts auf Tablets
- `.tablet:float-start` - Float Anfang auf Tablets

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - Float Ende beim Hover auf Tablet-PCs
- `.hover:tablet-pc:float-left` - Float links beim Hover auf Tablet-PCs
- `.hover:tablet-pc:float-none` - Float keine beim Hover auf Tablet-PCs
- `.hover:tablet-pc:float-right` - Float rechts beim Hover auf Tablet-PCs
- `.hover:tablet-pc:float-start` - Float Anfang beim Hover auf Tablet-PCs
- `.tablet-pc:float-end` - Float Ende auf Tablet-PCs
- `.tablet-pc:float-left` - Float links auf Tablet-PCs
- `.tablet-pc:float-none` - Float keine auf Tablet-PCs
- `.tablet-pc:float-right` - Float rechts auf Tablet-PCs
- `.tablet-pc:float-start` - Float Anfang auf Tablet-PCs

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - Float Ende beim Hover auf dem PC
- `.hover:pc:float-left` - Float links beim Hover auf dem PC
- `.hover:pc:float-none` - Float keine beim Hover auf dem PC
- `.hover:pc:float-right` - Float rechts beim Hover auf dem PC
- `.hover:pc:float-start` - Float Anfang beim Hover auf dem PC
- `.pc:float-end` - Float Ende auf dem PC
- `.pc:float-left` - Float links auf dem PC
- `.pc:float-none` - Float keine auf dem PC
- `.pc:float-right` - Float rechts auf dem PC
- `.pc:float-start` - Float Anfang auf dem PC

##### Float - Tv (>= 1200px)

- `.hover:tv:float-end` - Float Ende beim Hover auf dem TV
- `.hover:tv:float-left` - Float links beim Hover auf dem TV
- `.hover:tv:float-none` - Float keine beim Hover auf dem TV
- `.hover:tv:float-right` - Float rechts beim Hover auf dem TV
- `.hover:tv:float-start` - Float Anfang beim Hover auf dem TV
- `.tv:float-end` - Float Ende auf dem TV
- `.tv:float-left` - Float links auf dem TV
- `.tv:float-none` - Float keine auf dem TV
- `.tv:float-right` - Float rechts auf dem TV
- `.tv:float-start` - Float Anfang auf dem TV

##### Float - Tablet Max (<= 768px)

- `.hover:tablet-max:float-end` - Float Ende beim Hover auf Tablets (max.)
- `.hover:tablet-max:float-left` - Float links beim Hover auf Tablets (max.)
- `.hover:tablet-max:float-none` - Float keine beim Hover auf Tablets (max.)
- `.hover:tablet-max:float-right` - Float rechts beim Hover auf Tablets (max.)
- `.hover:tablet-max:float-start` - Float Anfang beim Hover auf Tablets (max.)
- `.tablet-max:float-end` - Float Ende auf Tablets (max.)
- `.tablet-max:float-left` - Float links auf Tablets (max.)
- `.tablet-max:float-none` - Float keine auf Tablets (max.)
- `.tablet-max:float-right` - Float rechts auf Tablets (max.)
- `.tablet-max:float-start` - Float Anfang auf Tablets (max.)

##### Float - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:float-end` - Float Ende beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:float-left` - Float links beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:float-none` - Float keine beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:float-right` - Float rechts beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:float-start` - Float Anfang beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:float-end` - Float Ende auf Tablet-PCs (max.)
- `.tablet-pc-max:float-left` - Float links auf Tablet-PCs (max.)
- `.tablet-pc-max:float-none` - Float keine auf Tablet-PCs (max.)
- `.tablet-pc-max:float-right` - Float rechts auf Tablet-PCs (max.)
- `.tablet-pc-max:float-start` - Float Anfang auf Tablet-PCs (max.)

##### Float - Pc Max (<= 1200px)

- `.hover:pc-max:float-end` - Float Ende beim Hover auf dem PC (max.)
- `.hover:pc-max:float-left` - Float links beim Hover auf dem PC (max.)
- `.hover:pc-max:float-none` - Float keine beim Hover auf dem PC (max.)
- `.hover:pc-max:float-right` - Float rechts beim Hover auf dem PC (max.)
- `.hover:pc-max:float-start` - Float Anfang beim Hover auf dem PC (max.)
- `.pc-max:float-end` - Float Ende auf dem PC (max.)
- `.pc-max:float-left` - Float links auf dem PC (max.)
- `.pc-max:float-none` - Float keine auf dem PC (max.)
- `.pc-max:float-right` - Float rechts auf dem PC (max.)
- `.pc-max:float-start` - Float Anfang auf dem PC (max.)

### Object

- `.hover:object-contain` - Objekt beim Schweben enthalten
- `.hover:object-cover` - Objektabdeckung beim Schweben
- `.hover:object-fill` - Objektfüllung beim Schweben
- `.hover:object-none` - Kein Objekt beim Schweben
- `.hover:object-scale` - Objektskalierung beim Schweben
- `.object-contain` - Objekt enthalten
- `.object-cover` - Objektabdeckung
- `.object-fill` - Objektfüllung
- `.object-none` - Objekt keins
- `.object-scale` - Objektmaßstab

##### Object - Mobile (<= 480px)

- `.hover:mobile:object-contain` - Objekt beim Hover auf dem Mobilgerät enthalten
- `.hover:mobile:object-cover` - Objektabdeckung beim Schweben auf dem Mobilgerät
- `.hover:mobile:object-fill` - Objektfüllung beim Hover auf Mobilgeräten
- `.hover:mobile:object-none` - Kein Objekt beim Hover auf dem Mobilgerät
- `.hover:mobile:object-scale` - Objektskalierung beim Schweben auf dem Mobilgerät
- `.mobile:object-contain` - Objekt auf Mobilgerät enthalten
- `.mobile:object-cover` - Objektabdeckung auf dem Handy
- `.mobile:object-fill` - Objektfüllung auf Mobilgeräten
- `.mobile:object-none` - Kein Objekt auf dem Handy
- `.mobile:object-scale` - Objektskalierung auf Mobilgeräten

##### Object - Tablet (480px - 768px)

- `.hover:tablet:object-contain` - Das Objekt wird beim Bewegen des Mauszeigers auf dem Tablet angezeigt
- `.hover:tablet:object-cover` - Objektabdeckung beim Schweben auf dem Tablet
- `.hover:tablet:object-fill` - Objektfüllung beim Schweben auf dem Tablet
- `.hover:tablet:object-none` - Kein Objekt beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:object-scale` - Objektskala beim Schweben auf dem Tablet
- `.tablet:object-contain` - Objekt auf Tablet enthalten
- `.tablet:object-cover` - Objektabdeckung auf Tablet
- `.tablet:object-fill` - Objektfüllung auf dem Tablet
- `.tablet:object-none` - Kein Objekt auf dem Tablet
- `.tablet:object-scale` - Objektskala auf Tablet

##### Object - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:object-contain` - Das Objekt wird beim Hover auf dem Tablet-PC angezeigt
- `.hover:tablet-pc:object-cover` - Objektabdeckung beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:object-fill` - Objektfüllung beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:object-none` - Kein Objekt beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:object-scale` - Objektskala beim Schweben auf dem Tablet-PC
- `.tablet-pc:object-contain` - Objekt auf Tablet-PC enthalten
- `.tablet-pc:object-cover` - Objektabdeckung auf Tablet-PC
- `.tablet-pc:object-fill` - Objektfüllung auf Tablet-PC
- `.tablet-pc:object-none` - Kein Objekt auf dem Tablet-PC
- `.tablet-pc:object-scale` - Objektskala auf Tablet-PC

##### Object - Pc (992px - 1200px)

- `.hover:pc:object-contain` - Objekt wird beim Hover auf dem PC angezeigt
- `.hover:pc:object-cover` - Objektabdeckung beim Schweben auf dem PC
- `.hover:pc:object-fill` - Objektfüllung beim Schweben auf dem PC
- `.hover:pc:object-none` - Kein Objekt beim Schweben auf dem PC
- `.hover:pc:object-scale` - Objektskalierung beim Schweben auf dem PC
- `.pc:object-contain` - Objekt auf dem PC enthalten
- `.pc:object-cover` - Objektabdeckung auf dem PC
- `.pc:object-fill` - Objektfüllung auf dem PC
- `.pc:object-none` - Kein Objekt auf dem PC
- `.pc:object-scale` - Objektskala auf dem PC

##### Object - Tv (>= 1200px)

- `.hover:tv:object-contain` - Das Objekt wird beim Schweben im Fernsehen angezeigt
- `.hover:tv:object-cover` - Objektabdeckung beim Schweben im Fernsehen
- `.hover:tv:object-fill` - Objektfüllung beim Schweben im Fernsehen
- `.hover:tv:object-none` - Kein Objekt beim Schweben im Fernsehen
- `.hover:tv:object-scale` - Objektskala beim Schweben im Fernsehen
- `.tv:object-contain` - Objekt im Fernsehen enthalten
- `.tv:object-cover` - Objektabdeckung im Fernsehen
- `.tv:object-fill` - Objektfüllung im Fernsehen
- `.tv:object-none` - Kein Objekt im Fernsehen
- `.tv:object-scale` - Objektmaßstab im Fernsehen

##### Object - Tablet Max (<= 768px)

- `.hover:tablet-max:object-contain` - Objekt enthält beim Hover auf dem Tablet max
- `.hover:tablet-max:object-cover` - Objektabdeckung beim Schweben auf dem Tablet max
- `.hover:tablet-max:object-fill` - Objektfüllung beim Schweben auf dem Tablet max
- `.hover:tablet-max:object-none` - Kein Objekt beim Hovern auf dem Tablet, max
- `.hover:tablet-max:object-scale` - Objektskalierung beim Schweben auf dem Tablet max
- `.tablet-max:object-contain` - Objekt enthalten auf Tablets (max.)
- `.tablet-max:object-cover` - Objektabdeckung auf Tablet max
- `.tablet-max:object-fill` - Objektfüllung auf Tablett max
- `.tablet-max:object-none` - Objekt keines auf Tablet max
- `.tablet-max:object-scale` - Objektskalierung auf Tablet max

##### Object - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:object-contain` - Objekt enthalten beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:object-cover` - Objektabdeckung beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:object-fill` - Objektfüllung beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:object-none` - Objekt keines beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:object-scale` - Objektskalierung beim Hover auf Tablet-PC max
- `.tablet-pc-max:object-contain` - Objekt enthalten auf Tablet-PC max
- `.tablet-pc-max:object-cover` - Objektabdeckung auf Tablet-PC max
- `.tablet-pc-max:object-fill` - Objektfüllung auf Tablet-PC max
- `.tablet-pc-max:object-none` - Objekt keines auf Tablet-PC max
- `.tablet-pc-max:object-scale` - Objektskalierung auf Tablet-PC max

##### Object - Pc Max (<= 1200px)

- `.hover:pc-max:object-contain` - Objekt enthalten beim Hover auf dem PC max
- `.hover:pc-max:object-cover` - Objektabdeckung beim Schweben auf dem PC max
- `.hover:pc-max:object-fill` - Objektfüllung beim Schweben auf dem PC max
- `.hover:pc-max:object-none` - Kein Objekt beim Schweben auf dem PC, max
- `.hover:pc-max:object-scale` - Objektskalierung beim Schweben auf dem PC max
- `.pc-max:object-contain` - Objekt auf dem PC enthalten max
- `.pc-max:object-cover` - Objektabdeckung am PC max
- `.pc-max:object-fill` - Objektfüllung auf dem PC max
- `.pc-max:object-none` - Objekt keines auf PC max
- `.pc-max:object-scale` - Objektgröße am PC max

### Overflow

- `.hover:overflow-scroll` - Überlauf-Scroll beim Hover
- `.overflow-auto` - Überlauf automatisch
- `.overflow-clip` - Überlaufclip
- `.overflow-hidden` - Überlauf ausgeblendet
- `.overflow-scroll` - Überlauf-Scroll
- `.overflow-visible` - Überlauf sichtbar

### Overflow x

- `.hover:overflow-x-scroll` - Überlauf x Scrollen beim Hover
- `.overflow-x-auto` - Überlauf x auto
- `.overflow-x-clip` - Überlauf x Clip
- `.overflow-x-hidden` - Überlauf x ausgeblendet
- `.overflow-x-scroll` - Überlauf x Scrollen
- `.overflow-x-visible` - Überlauf x sichtbar

### Overflow y

- `.hover:overflow-y-scroll` - Überlauf und Scrollen beim Hover
- `.overflow-y-auto` - Überlauf und automatisch
- `.overflow-y-clip` - Überlauf und Clip
- `.overflow-y-hidden` - Überlauf und versteckt
- `.overflow-y-scroll` - Überlauf und Scrollen
- `.overflow-y-visible` - Überlauf y sichtbar

### Header

- `.header` - Kopfzeile

### Footer

- `.footer` - Fußzeile

## Flexbox

### Flex

- `.flex-col` - Flex-Farbe
- `.flex-nowrap` - Flex nowrap
- `.flex-row` - Flex-Reihe
- `.flex-wrap` - Flexfolie
- `.hover:flex-col` - Flex Col beim Schweben
- `.hover:flex-nowrap` - Flex Nowrap beim Schweben
- `.hover:flex-row` - Flex-Reihe beim Schweben
- `.hover:flex-wrap` - Flex-Wickel beim Schweben

##### Flex - Mobile (<= 480px)

- `.hover:mobile:flex-col` - Flex Col beim Hover auf dem Handy
- `.hover:mobile:flex-nowrap` - Flex Nowrap beim Schweben auf Mobilgeräten
- `.hover:mobile:flex-row` - Flex-Reihe beim Schweben auf dem Handy
- `.hover:mobile:flex-wrap` - Flex-Wrap beim Schweben auf dem Handy
- `.mobile:flex-col` - Flex Col auf dem Handy
- `.mobile:flex-nowrap` - Flex Nowrap auf dem Handy
- `.mobile:flex-row` - Flexreihe auf dem Handy
- `.mobile:flex-wrap` - Flexfolie auf dem Handy

##### Flex - Tablet (480px - 768px)

- `.hover:tablet:flex-col` - Flex Col beim Hover auf dem Tablet
- `.hover:tablet:flex-nowrap` - Flex Nowrap beim Schweben auf dem Tablet
- `.hover:tablet:flex-row` - Flex-Reihe beim Schweben auf dem Tablet
- `.hover:tablet:flex-wrap` - Flexfolie beim Schweben auf dem Tablet
- `.tablet:flex-col` - Flex-Farbe auf dem Tablet
- `.tablet:flex-nowrap` - Flex Nowrap auf dem Tablet
- `.tablet:flex-row` - Flexreihe auf dem Tablet
- `.tablet:flex-wrap` - Flexfolie auf dem Tablet

##### Flex - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col` - Flex Col beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:flex-nowrap` - Flex Nowrap beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-row` - Flex-Reihe beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-wrap` - Flexfolie beim Schweben auf dem Tablet-PC
- `.tablet-pc:flex-col` - Flex Col auf Tablet-PC
- `.tablet-pc:flex-nowrap` - Flex Nowrap auf Tablet-PC
- `.tablet-pc:flex-row` - Flex-Reihe auf Tablet-PC
- `.tablet-pc:flex-wrap` - Flexfolie auf Tablet-PC

##### Flex - Pc (992px - 1200px)

- `.hover:pc:flex-col` - Flex Col beim Hover auf dem PC
- `.hover:pc:flex-nowrap` - Flex Nowrap beim Schweben auf dem PC
- `.hover:pc:flex-row` - Flexreihe beim Schweben auf dem PC
- `.hover:pc:flex-wrap` - Flex Wrap beim Schweben auf dem PC
- `.pc:flex-col` - Flex-Farbe auf dem PC
- `.pc:flex-nowrap` - Flex Nowrap auf dem PC
- `.pc:flex-row` - Flexreihe am PC
- `.pc:flex-wrap` - Flexfolie auf dem PC

##### Flex - Tv (>= 1200px)

- `.hover:tv:flex-col` - Flex Col beim Schweben im Fernsehen
- `.hover:tv:flex-nowrap` - Flex Nowrap im Hover im Fernsehen
- `.hover:tv:flex-row` - Flexreihe beim Schweben im Fernsehen
- `.hover:tv:flex-wrap` - Flex Wrap beim Schweben im Fernsehen
- `.tv:flex-col` - Flex Col im Fernsehen
- `.tv:flex-nowrap` - Flex Nowrap im Fernsehen
- `.tv:flex-row` - Flex Row im Fernsehen
- `.tv:flex-wrap` - Flexfolie im Fernsehen

##### Flex - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-col` - Flex Col beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-nowrap` - Flex Nowrap beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-row` - Flexreihe beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-wrap` - Flexfolie beim Schweben auf dem Tablet max
- `.tablet-max:flex-col` - Flex-Farbe auf Tablet max
- `.tablet-max:flex-nowrap` - Flex Nowrap auf Tablet max
- `.tablet-max:flex-row` - Flexreihe auf Tablet max
- `.tablet-max:flex-wrap` - Flexfolie am Tablet max

##### Flex - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-col` - Flex Col beim Hover auf Tablet PC max
- `.hover:tablet-pc-max:flex-nowrap` - Flex Nowrap beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:flex-row` - Flexreihe beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-wrap` - Flexfolie beim Hover auf Tablet-PC max
- `.tablet-pc-max:flex-col` - Flex-Farbe auf Tablet-PC max
- `.tablet-pc-max:flex-nowrap` - Flex Nowrap auf Tablet-PC max
- `.tablet-pc-max:flex-row` - Flexreihe am Tablet-PC max
- `.tablet-pc-max:flex-wrap` - Flexfolie am Tablet-PC max

##### Flex - Pc Max (<= 1200px)

- `.hover:pc-max:flex-col` - Flex Col beim Hover auf dem PC max
- `.hover:pc-max:flex-nowrap` - Flex Nowrap beim Schweben auf dem PC max
- `.hover:pc-max:flex-row` - Flexreihe beim Schweben auf dem PC max
- `.hover:pc-max:flex-wrap` - Flex Wrap beim Schweben auf dem PC max
- `.pc-max:flex-col` - Flex-Farbe auf dem PC max
- `.pc-max:flex-nowrap` - Flex Nowrap auf dem PC max
- `.pc-max:flex-row` - Flex Row am PC max
- `.pc-max:flex-wrap` - Flexfolie am PC max

### Flex col

- `.flex-col-reverse` - Flex-Col-Rückseite
- `.hover:flex-col-reverse` - Flex Col Reverse beim Schweben

##### Flex col - Mobile (<= 480px)

- `.hover:mobile:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem Handy
- `.mobile:flex-col-reverse` - Flex Col Reverse auf dem Handy

##### Flex col - Tablet (480px - 768px)

- `.hover:tablet:flex-col-reverse` - Biegen Sie die Spalte um, wenn Sie den Mauszeiger auf dem Tablet bewegen
- `.tablet:flex-col-reverse` - Flex-Col-Rückseite auf dem Tablet

##### Flex col - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem Tablet-PC
- `.tablet-pc:flex-col-reverse` - Flex Col Reverse auf Tablet-PC

##### Flex col - Pc (992px - 1200px)

- `.hover:pc:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem PC
- `.pc:flex-col-reverse` - Flex Col Reverse auf dem PC

##### Flex col - Tv (>= 1200px)

- `.hover:tv:flex-col-reverse` - Flex-Col-Reverse beim Schweben im Fernsehen
- `.tv:flex-col-reverse` - Flex Col Reverse im Fernsehen

##### Flex col - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem Tablet max
- `.tablet-max:flex-col-reverse` - Flex Col Reverse auf Tablet max

##### Flex col - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:flex-col-reverse` - Flex Col Reverse auf Tablet-PC max

##### Flex col - Pc Max (<= 1200px)

- `.hover:pc-max:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem PC max
- `.pc-max:flex-col-reverse` - Flex Col Reverse auf PC max

### Flex row

- `.flex-row-reverse` - Flexreihe umgekehrt
- `.hover:flex-row-reverse` - Beuge die Reihe beim Schweben rückwärts

##### Flex row - Mobile (<= 480px)

- `.hover:mobile:flex-row-reverse` - Flex-Reihenumkehr beim Schweben auf dem Handy
- `.mobile:flex-row-reverse` - Flex-Row-Reverse auf dem Handy

##### Flex row - Tablet (480px - 768px)

- `.hover:tablet:flex-row-reverse` - Biegen Sie die Reihe um, wenn Sie den Mauszeiger auf dem Tablet bewegen
- `.tablet:flex-row-reverse` - Flexreihe rückwärts auf dem Tablet

##### Flex row - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-row-reverse` - Flexreihe umkehren beim Schweben auf dem Tablet-PC
- `.tablet-pc:flex-row-reverse` - Flexreihe rückwärts auf Tablet-PC

##### Flex row - Pc (992px - 1200px)

- `.hover:pc:flex-row-reverse` - Flexreihe umkehren beim Schweben auf dem PC
- `.pc:flex-row-reverse` - Flexreihe umkehren am PC

##### Flex row - Tv (>= 1200px)

- `.hover:tv:flex-row-reverse` - Flexreihe umkehren beim Schweben im Fernsehen
- `.tv:flex-row-reverse` - Flex Row Reverse im Fernsehen

##### Flex row - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-row-reverse` - Flexreihe rückwärts beim Schweben auf dem Tablet max
- `.tablet-max:flex-row-reverse` - Flexreihenumkehr auf dem Tablet max

##### Flex row - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - Flexreihe umkehren beim Schweben auf Tablet-PC max
- `.tablet-pc-max:flex-row-reverse` - Flexreihe rückwärts auf Tablet-PC max

##### Flex row - Pc Max (<= 1200px)

- `.hover:pc-max:flex-row-reverse` - Flexreihe umkehren beim Schweben auf dem PC max
- `.pc-max:flex-row-reverse` - Flex-Reihenumkehr am PC max

### Flex grow

- `.flex-grow-3` - Flex wachsen 3
- `.flex-grow-2` - Flex wachsen 2
- `.flex-grow-1` - Flex wächst 1
- `.flex-grow-0` - Flex wächst 0
- `.hover:flex-grow-3` - Flex wächst 3 beim Schweben
- `.hover:flex-grow-2` - Flex wächst beim Schweben um 2
- `.hover:flex-grow-1` - Flex wächst beim Schweben um 1
- `.hover:flex-grow-0` - Flex wächst beim Schweben um 0

##### Flex grow - Mobile (<= 480px)

- `.hover:mobile:flex-grow-3` - Flex wächst 3 beim Hover auf dem Handy
- `.hover:mobile:flex-grow-2` - Flex wächst 2 beim Hover auf dem Handy
- `.hover:mobile:flex-grow-1` - Flex wächst um 1 beim Schweben auf dem Handy
- `.hover:mobile:flex-grow-0` - Flex wächst um 0 beim Hover auf Mobilgeräten
- `.mobile:flex-grow-3` - Flex Grow 3 auf dem Handy
- `.mobile:flex-grow-2` - Flex wachsen 2 auf dem Handy
- `.mobile:flex-grow-1` - Flex wachsen 1 auf dem Handy
- `.mobile:flex-grow-0` - Flex wächst 0 auf Mobilgeräten

##### Flex grow - Tablet (480px - 768px)

- `.hover:tablet:flex-grow-3` - Flex wachsen 3 beim Schweben auf dem Tablet
- `.hover:tablet:flex-grow-2` - Flex wachsen 2 beim Schweben auf dem Tablet
- `.hover:tablet:flex-grow-1` - Flex wachsen 1 beim Schweben auf dem Tablet
- `.hover:tablet:flex-grow-0` - Flex wächst 0 beim Schweben auf dem Tablet
- `.tablet:flex-grow-3` - Flex wachsen 3 auf dem Tablet
- `.tablet:flex-grow-2` - Flex wachsen 2 auf dem Tablet
- `.tablet:flex-grow-1` - Flex wachsen 1 auf dem Tablet
- `.tablet:flex-grow-0` - Flex wachsen 0 auf dem Tablet

##### Flex grow - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-grow-3` - Flex Grow 3 beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-grow-2` - Flex wachsen 2 beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-grow-1` - Flex wachsen 1 beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-grow-0` - Flex wächst 0 beim Schweben auf dem Tablet-PC
- `.tablet-pc:flex-grow-3` - Flex Grow 3 auf dem Tablet-PC
- `.tablet-pc:flex-grow-2` - Flex wachsen 2 auf dem Tablet-PC
- `.tablet-pc:flex-grow-1` - Flex wachsen 1 auf dem Tablet-PC
- `.tablet-pc:flex-grow-0` - Flex wachsen 0 auf Tablet-PC

##### Flex grow - Pc (992px - 1200px)

- `.hover:pc:flex-grow-3` - Flex Grow 3 beim Schweben auf dem PC
- `.hover:pc:flex-grow-2` - Flex wächst 2 beim Hover auf dem PC
- `.hover:pc:flex-grow-1` - Flex wächst 1 beim Hover auf dem PC
- `.hover:pc:flex-grow-0` - Flex wächst 0 beim Schweben auf dem PC
- `.pc:flex-grow-3` - Flex Grow 3 auf dem PC
- `.pc:flex-grow-2` - Flex wachsen 2 auf dem PC
- `.pc:flex-grow-1` - Flex wachsen 1 auf dem PC
- `.pc:flex-grow-0` - Flex wachsen 0 auf dem PC

##### Flex grow - Tv (>= 1200px)

- `.hover:tv:flex-grow-3` - Flex wachsen 3 beim Schweben im Fernsehen
- `.hover:tv:flex-grow-2` - Flex wächst 2 beim Schweben im Fernsehen
- `.hover:tv:flex-grow-1` - Flex wachsen 1 beim Schweben im Fernsehen
- `.hover:tv:flex-grow-0` - Flex wächst 0 beim Schweben im Fernsehen
- `.tv:flex-grow-3` - Flex Grow 3 im Fernsehen
- `.tv:flex-grow-2` - Flex Grow 2 im Fernsehen
- `.tv:flex-grow-1` - Flex wachsen 1 im Fernsehen
- `.tv:flex-grow-0` - Flex wachsen 0 im Fernsehen

##### Flex grow - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-grow-3` - Flex wachsen 3 beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-grow-2` - Flex wächst 2 beim Hover auf dem Tablet max
- `.hover:tablet-max:flex-grow-1` - Flex wächst 1 beim Hover auf dem Tablet max
- `.hover:tablet-max:flex-grow-0` - Flex wächst um 0 beim Schweben auf dem Tablet, max
- `.tablet-max:flex-grow-3` - Flex wachsen 3 auf Tablet max
- `.tablet-max:flex-grow-2` - Flex wachsen 2 auf Tablet max
- `.tablet-max:flex-grow-1` - Flex wachsen 1 auf Tablet max
- `.tablet-max:flex-grow-0` - Flex wachsen 0 auf Tablet max

##### Flex grow - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex wachsen 3 beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-grow-2` - Flex wachsen 2 beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-grow-1` - Flex wachsen 1 beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-grow-0` - Flex wächst 0 beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:flex-grow-3` - Flex Grow 3 auf Tablet-PC max
- `.tablet-pc-max:flex-grow-2` - Flex Grow 2 auf Tablet-PC max
- `.tablet-pc-max:flex-grow-1` - Flex wachsen 1 auf Tablet-PC max
- `.tablet-pc-max:flex-grow-0` - Flex wachsen 0 auf Tablet-PC max

##### Flex grow - Pc Max (<= 1200px)

- `.hover:pc-max:flex-grow-3` - Flex wachsen 3 beim Schweben auf dem PC max
- `.hover:pc-max:flex-grow-2` - Flex wächst 2 beim Hover auf dem PC max
- `.hover:pc-max:flex-grow-1` - Flex wächst 1 beim Hover auf dem PC max
- `.hover:pc-max:flex-grow-0` - Flex wächst 0 beim Schweben auf dem PC max
- `.pc-max:flex-grow-3` - Flex wachsen 3 auf dem PC max
- `.pc-max:flex-grow-2` - Flex wachsen 2 auf dem PC max
- `.pc-max:flex-grow-1` - Flex wachsen 1 auf dem PC max
- `.pc-max:flex-grow-0` - Flex wachsen 0 auf dem PC max

### Flex wrap

- `.flex-wrap-reverse` - Flex-Wrap-Rückseite
- `.hover:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben

##### Flex wrap - Mobile (<= 480px)

- `.hover:mobile:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben auf dem Mobilgerät
- `.mobile:flex-wrap-reverse` - Flex-Wrap-Rückseite auf dem Handy

##### Flex wrap - Tablet (480px - 768px)

- `.hover:tablet:flex-wrap-reverse` - Flexfolie umgekehrt, wenn Sie den Mauszeiger über das Tablet halten
- `.tablet:flex-wrap-reverse` - Flexfolie umgekehrt auf dem Tablet

##### Flex wrap - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben auf dem Tablet-PC
- `.tablet-pc:flex-wrap-reverse` - Flex-Wrap-Rückseite auf Tablet-PC

##### Flex wrap - Pc (992px - 1200px)

- `.hover:pc:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben auf dem PC
- `.pc:flex-wrap-reverse` - Flex Wrap umgekehrt auf dem PC

##### Flex wrap - Tv (>= 1200px)

- `.hover:tv:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben im Fernsehen
- `.tv:flex-wrap-reverse` - Flex Wrap umgekehrt im Fernsehen

##### Flex wrap - Tablet Max (<= 768px)

- `.hover:tablet-max:flex-wrap-reverse` - Flex-Wickel umgekehrt beim Schweben auf dem Tablet max
- `.tablet-max:flex-wrap-reverse` - Flexfolie rückwärts am Tablet max

##### Flex wrap - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - Flex-Wickel umgekehrt beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:flex-wrap-reverse` - Flex Wrap umgekehrt auf Tablet-PC max

##### Flex wrap - Pc Max (<= 1200px)

- `.hover:pc-max:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben auf dem PC max
- `.pc-max:flex-wrap-reverse` - Flex-Wrap rückwärts am PC max

### Gap

#### Gap All

- `.gap-5` - Lücke Alle 5rem
- `.gap-4.5` - Lücke Alle 0rem
- `.gap-4` - Lücke Alle 4rem
- `.gap-3.5` - Lücke Alle 0rem
- `.gap-3` - Lücke Alle 3rem
- `.gap-2.5` - Lücke Alle 0rem
- `.gap-2` - Lücke Alle 2rem
- `.gap-1.9` - Lücke Alle 0rem
- `.gap-1.8` - Lücke Alle 0rem
- `.gap-1.7` - Lücke Alle 0rem
- `.gap-1.6` - Lücke Alle 0rem
- `.gap-1.5` - Lücke Alle 0rem
- `.gap-1.4` - Lücke Alle 0rem
- `.gap-1.3` - Lücke Alle 0rem
- `.gap-1.2` - Lücke Alle 0rem
- `.gap-1.1` - Lücke Alle 0rem
- `.gap-1` - Lücke Alle 1rem
- `.gap-0.9` - Lücke Alle 0rem
- `.gap-0.8` - Lücke Alle 0rem
- `.gap-0.7` - Lücke Alle 0rem
- `.gap-0.6` - Lücke Alle 0rem
- `.gap-0.5` - Lücke Alle 0rem
- `.gap-0.4` - Lücke Alle 0rem
- `.gap-0.3` - Lücke Alle 0rem
- `.gap-0.2` - Lücke Alle 0,2rem
- `.gap-0.1` - Lücke Alle 0,1rem
- `.gap-0` - Lücke Alle 0rem
- `.hover:gap-5` - Lücke Alle 5rem beim Hover
- `.hover:gap-4.5` - Lücke Alle 0rem beim Hover
- `.hover:gap-4` - Lücke Alle 4rem beim Hover
- `.hover:gap-3.5` - Lücke Alle 0rem beim Hover
- `.hover:gap-3` - Lücke Alle 3rem beim Hover
- `.hover:gap-2.5` - Lücke Alle 0rem beim Hover
- `.hover:gap-2` - Lücke Alle 2rem beim Hover
- `.hover:gap-1.9` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.8` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.7` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.6` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.5` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.4` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.3` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.2` - Lücke Alle 0rem beim Hover
- `.hover:gap-1.1` - Lücke Alle 0rem beim Hover
- `.hover:gap-1` - Lücke Alle 1rem beim Hover
- `.hover:gap-0.9` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.8` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.7` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.6` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.5` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.4` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.3` - Lücke Alle 0rem beim Hover
- `.hover:gap-0.2` - Lücke Alle 0,2rem beim Schweben
- `.hover:gap-0.1` - Lücke Alle 0,1rem beim Schweben
- `.hover:gap-0` - Lücke Alle 0rem beim Hover

#### Gap X-Axis

- `.gap-x-5` - Abstand X-Achse 5rem
- `.gap-x-4.5` - Lücke X-Achse 0rem
- `.gap-x-4` - Abstand X-Achse 4rem
- `.gap-x-3.5` - Lücke X-Achse 0rem
- `.gap-x-3` - Abstand X-Achse 3rem
- `.gap-x-2.5` - Lücke X-Achse 0rem
- `.gap-x-2` - Abstand X-Achse 2rem
- `.gap-x-1.9` - Lücke X-Achse 0rem
- `.gap-x-1.8` - Lücke X-Achse 0rem
- `.gap-x-1.7` - Lücke X-Achse 0rem
- `.gap-x-1.6` - Lücke X-Achse 0rem
- `.gap-x-1.5` - Lücke X-Achse 0rem
- `.gap-x-1.4` - Lücke X-Achse 0rem
- `.gap-x-1.3` - Lücke X-Achse 0rem
- `.gap-x-1.2` - Lücke X-Achse 0rem
- `.gap-x-1.1` - Lücke X-Achse 0rem
- `.gap-x-1` - Abstand X-Achse 1rem
- `.gap-x-0.9` - Lücke X-Achse 0rem
- `.gap-x-0.8` - Lücke X-Achse 0rem
- `.gap-x-0.7` - Lücke X-Achse 0rem
- `.gap-x-0.6` - Lücke X-Achse 0rem
- `.gap-x-0.5` - Lücke X-Achse 0rem
- `.gap-x-0.4` - Lücke X-Achse 0rem
- `.gap-x-0.3` - Lücke X-Achse 0rem
- `.gap-x-0.2` - Abstand X-Achse 0,2rem
- `.gap-x-0.1` - Abstand X-Achse 0,1rem
- `.gap-x-0` - Lücke X-Achse 0rem
- `.hover:gap-x-5` - Lücke X-Achse 5rem beim Schweben
- `.hover:gap-x-4.5` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-4` - Lücke X-Achse 4rem beim Schweben
- `.hover:gap-x-3.5` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-3` - Lücke X-Achse 3rem beim Schweben
- `.hover:gap-x-2.5` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-2` - Lücke X-Achse 2rem beim Schweben
- `.hover:gap-x-1.9` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.8` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.7` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.6` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.5` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.4` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.3` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.2` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1.1` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-1` - Lücke X-Achse 1rem beim Schweben
- `.hover:gap-x-0.9` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.8` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.7` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.6` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.5` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.4` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.3` - Lücke X-Achse 0rem beim Schweben
- `.hover:gap-x-0.2` - Abstand X-Achse 0,2rem beim Schweben
- `.hover:gap-x-0.1` - Abstand X-Achse 0,1rem beim Schweben
- `.hover:gap-x-0` - Lücke X-Achse 0rem beim Schweben

#### Gap Y-Axis

- `.gap-y-5` - Abstand Y-Achse 5rem
- `.gap-y-4.5` - Abstand Y-Achse 0rem
- `.gap-y-4` - Abstand Y-Achse 4rem
- `.gap-y-3.5` - Abstand Y-Achse 0rem
- `.gap-y-3` - Abstand Y-Achse 3rem
- `.gap-y-2.5` - Abstand Y-Achse 0rem
- `.gap-y-2` - Abstand Y-Achse 2rem
- `.gap-y-1.9` - Abstand Y-Achse 0rem
- `.gap-y-1.8` - Abstand Y-Achse 0rem
- `.gap-y-1.7` - Abstand Y-Achse 0rem
- `.gap-y-1.6` - Abstand Y-Achse 0rem
- `.gap-y-1.5` - Abstand Y-Achse 0rem
- `.gap-y-1.4` - Abstand Y-Achse 0rem
- `.gap-y-1.3` - Abstand Y-Achse 0rem
- `.gap-y-1.2` - Abstand Y-Achse 0rem
- `.gap-y-1.1` - Abstand Y-Achse 0rem
- `.gap-y-1` - Abstand Y-Achse 1rem
- `.gap-y-0.9` - Abstand Y-Achse 0rem
- `.gap-y-0.8` - Abstand Y-Achse 0rem
- `.gap-y-0.7` - Abstand Y-Achse 0rem
- `.gap-y-0.6` - Abstand Y-Achse 0rem
- `.gap-y-0.5` - Abstand Y-Achse 0rem
- `.gap-y-0.4` - Abstand Y-Achse 0rem
- `.gap-y-0.3` - Abstand Y-Achse 0rem
- `.gap-y-0.2` - Abstand Y-Achse 0,2rem
- `.gap-y-0.1` - Abstand Y-Achse 0,1rem
- `.gap-y-0` - Abstand Y-Achse 0rem
- `.hover:gap-y-5` - Lücke Y-Achse 5rem beim Schweben
- `.hover:gap-y-4.5` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-4` - Lücke Y-Achse 4rem beim Schweben
- `.hover:gap-y-3.5` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-3` - Lücke Y-Achse 3rem beim Schweben
- `.hover:gap-y-2.5` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-2` - Lücke Y-Achse 2rem beim Schweben
- `.hover:gap-y-1.9` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.8` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.7` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.6` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.5` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.4` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.3` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.2` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1.1` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-1` - Lücke Y-Achse 1rem beim Schweben
- `.hover:gap-y-0.9` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.8` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.7` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.6` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.5` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.4` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.3` - Lücke Y-Achse 0rem beim Schweben
- `.hover:gap-y-0.2` - Abstand Y-Achse 0,2rem beim Schweben
- `.hover:gap-y-0.1` - Abstand Y-Achse 0,1rem beim Schweben
- `.hover:gap-y-0` - Lücke Y-Achse 0rem beim Schweben

### Align content

- `.align-content-around` - Inhalt ausrichten: around
- `.align-content-between` - Inhalt ausrichten: between
- `.align-content-center` - Inhalt ausrichten: Mitte
- `.align-content-end` - Inhalt ausrichten: Ende
- `.align-content-evenly` - Inhalt ausrichten: evenly
- `.align-content-start` - Inhalt ausrichten: Start
- `.align-content-stretch` - Inhalt ausrichten: stretch
- `.hover:align-content-around` - Inhalt ausrichten: around beim Hover
- `.hover:align-content-between` - Inhalt ausrichten: between beim Hover
- `.hover:align-content-center` - Inhalt ausrichten: Mitte beim Hover
- `.hover:align-content-end` - Inhalt ausrichten: Ende beim Hover
- `.hover:align-content-evenly` - Inhalt ausrichten: evenly beim Hover
- `.hover:align-content-start` - Inhalt ausrichten: Start beim Hover
- `.hover:align-content-stretch` - Inhalt ausrichten: stretch beim Hover

##### Align content - Mobile (<= 480px)

- `.hover:mobile:align-content-around` - Inhalt ausrichten: around beim Hover auf Mobilgeräten
- `.hover:mobile:align-content-between` - Inhalt ausrichten: between beim Hover auf Mobilgeräten
- `.hover:mobile:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf Mobilgeräten
- `.hover:mobile:align-content-end` - Inhalt ausrichten: Ende beim Hover auf Mobilgeräten
- `.hover:mobile:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf Mobilgeräten
- `.hover:mobile:align-content-start` - Inhalt ausrichten: Start beim Hover auf Mobilgeräten
- `.hover:mobile:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf Mobilgeräten
- `.mobile:align-content-around` - Inhalt ausrichten: around auf Mobilgeräten
- `.mobile:align-content-between` - Inhalt ausrichten: between auf Mobilgeräten
- `.mobile:align-content-center` - Inhalt ausrichten: Mitte auf Mobilgeräten
- `.mobile:align-content-end` - Inhalt ausrichten: Ende auf Mobilgeräten
- `.mobile:align-content-evenly` - Inhalt ausrichten: evenly auf Mobilgeräten
- `.mobile:align-content-start` - Inhalt ausrichten: Start auf Mobilgeräten
- `.mobile:align-content-stretch` - Inhalt ausrichten: stretch auf Mobilgeräten

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - Inhalt ausrichten: around beim Hover auf Tablets
- `.hover:tablet:align-content-between` - Inhalt ausrichten: between beim Hover auf Tablets
- `.hover:tablet:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf Tablets
- `.hover:tablet:align-content-end` - Inhalt ausrichten: Ende beim Hover auf Tablets
- `.hover:tablet:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf Tablets
- `.hover:tablet:align-content-start` - Inhalt ausrichten: Start beim Hover auf Tablets
- `.hover:tablet:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf Tablets
- `.tablet:align-content-around` - Inhalt ausrichten: around auf Tablets
- `.tablet:align-content-between` - Inhalt ausrichten: between auf Tablets
- `.tablet:align-content-center` - Inhalt ausrichten: Mitte auf Tablets
- `.tablet:align-content-end` - Inhalt ausrichten: Ende auf Tablets
- `.tablet:align-content-evenly` - Inhalt ausrichten: evenly auf Tablets
- `.tablet:align-content-start` - Inhalt ausrichten: Start auf Tablets
- `.tablet:align-content-stretch` - Inhalt ausrichten: stretch auf Tablets

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - Inhalt ausrichten: around beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-content-between` - Inhalt ausrichten: between beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-content-end` - Inhalt ausrichten: Ende beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-content-start` - Inhalt ausrichten: Start beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf Tablet-PCs
- `.tablet-pc:align-content-around` - Inhalt ausrichten: around auf Tablet-PCs
- `.tablet-pc:align-content-between` - Inhalt ausrichten: between auf Tablet-PCs
- `.tablet-pc:align-content-center` - Inhalt ausrichten: Mitte auf Tablet-PCs
- `.tablet-pc:align-content-end` - Inhalt ausrichten: Ende auf Tablet-PCs
- `.tablet-pc:align-content-evenly` - Inhalt ausrichten: evenly auf Tablet-PCs
- `.tablet-pc:align-content-start` - Inhalt ausrichten: Start auf Tablet-PCs
- `.tablet-pc:align-content-stretch` - Inhalt ausrichten: stretch auf Tablet-PCs

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - Inhalt ausrichten: around beim Hover auf dem PC
- `.hover:pc:align-content-between` - Inhalt ausrichten: between beim Hover auf dem PC
- `.hover:pc:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf dem PC
- `.hover:pc:align-content-end` - Inhalt ausrichten: Ende beim Hover auf dem PC
- `.hover:pc:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf dem PC
- `.hover:pc:align-content-start` - Inhalt ausrichten: Start beim Hover auf dem PC
- `.hover:pc:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf dem PC
- `.pc:align-content-around` - Inhalt ausrichten: around auf dem PC
- `.pc:align-content-between` - Inhalt ausrichten: between auf dem PC
- `.pc:align-content-center` - Inhalt ausrichten: Mitte auf dem PC
- `.pc:align-content-end` - Inhalt ausrichten: Ende auf dem PC
- `.pc:align-content-evenly` - Inhalt ausrichten: evenly auf dem PC
- `.pc:align-content-start` - Inhalt ausrichten: Start auf dem PC
- `.pc:align-content-stretch` - Inhalt ausrichten: stretch auf dem PC

##### Align content - Tv (>= 1200px)

- `.hover:tv:align-content-around` - Inhalt ausrichten: around beim Hover auf dem TV
- `.hover:tv:align-content-between` - Inhalt ausrichten: between beim Hover auf dem TV
- `.hover:tv:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf dem TV
- `.hover:tv:align-content-end` - Inhalt ausrichten: Ende beim Hover auf dem TV
- `.hover:tv:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf dem TV
- `.hover:tv:align-content-start` - Inhalt ausrichten: Start beim Hover auf dem TV
- `.hover:tv:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf dem TV
- `.tv:align-content-around` - Inhalt ausrichten: around auf dem TV
- `.tv:align-content-between` - Inhalt ausrichten: between auf dem TV
- `.tv:align-content-center` - Inhalt ausrichten: Mitte auf dem TV
- `.tv:align-content-end` - Inhalt ausrichten: Ende auf dem TV
- `.tv:align-content-evenly` - Inhalt ausrichten: evenly auf dem TV
- `.tv:align-content-start` - Inhalt ausrichten: Start auf dem TV
- `.tv:align-content-stretch` - Inhalt ausrichten: stretch auf dem TV

##### Align content - Tablet Max (<= 768px)

- `.hover:tablet-max:align-content-around` - Inhalt ausrichten: around beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-content-between` - Inhalt ausrichten: between beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-content-end` - Inhalt ausrichten: Ende beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-content-start` - Inhalt ausrichten: Start beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf Tablets (max.)
- `.tablet-max:align-content-around` - Inhalt ausrichten: around auf Tablets (max.)
- `.tablet-max:align-content-between` - Inhalt ausrichten: between auf Tablets (max.)
- `.tablet-max:align-content-center` - Inhalt ausrichten: Mitte auf Tablets (max.)
- `.tablet-max:align-content-end` - Inhalt ausrichten: Ende auf Tablets (max.)
- `.tablet-max:align-content-evenly` - Inhalt ausrichten: evenly auf Tablets (max.)
- `.tablet-max:align-content-start` - Inhalt ausrichten: Start auf Tablets (max.)
- `.tablet-max:align-content-stretch` - Inhalt ausrichten: stretch auf Tablets (max.)

##### Align content - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-content-around` - Inhalt ausrichten: around beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-content-between` - Inhalt ausrichten: between beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-content-end` - Inhalt ausrichten: Ende beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-content-start` - Inhalt ausrichten: Start beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-around` - Inhalt ausrichten: around auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-between` - Inhalt ausrichten: between auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-center` - Inhalt ausrichten: Mitte auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-end` - Inhalt ausrichten: Ende auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-evenly` - Inhalt ausrichten: evenly auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-start` - Inhalt ausrichten: Start auf Tablet-PCs (max.)
- `.tablet-pc-max:align-content-stretch` - Inhalt ausrichten: stretch auf Tablet-PCs (max.)

##### Align content - Pc Max (<= 1200px)

- `.hover:pc-max:align-content-around` - Inhalt ausrichten: around beim Hover auf dem PC (max.)
- `.hover:pc-max:align-content-between` - Inhalt ausrichten: between beim Hover auf dem PC (max.)
- `.hover:pc-max:align-content-center` - Inhalt ausrichten: Mitte beim Hover auf dem PC (max.)
- `.hover:pc-max:align-content-end` - Inhalt ausrichten: Ende beim Hover auf dem PC (max.)
- `.hover:pc-max:align-content-evenly` - Inhalt ausrichten: evenly beim Hover auf dem PC (max.)
- `.hover:pc-max:align-content-start` - Inhalt ausrichten: Start beim Hover auf dem PC (max.)
- `.hover:pc-max:align-content-stretch` - Inhalt ausrichten: stretch beim Hover auf dem PC (max.)
- `.pc-max:align-content-around` - Inhalt ausrichten: around auf dem PC (max.)
- `.pc-max:align-content-between` - Inhalt ausrichten: between auf dem PC (max.)
- `.pc-max:align-content-center` - Inhalt ausrichten: Mitte auf dem PC (max.)
- `.pc-max:align-content-end` - Inhalt ausrichten: Ende auf dem PC (max.)
- `.pc-max:align-content-evenly` - Inhalt ausrichten: evenly auf dem PC (max.)
- `.pc-max:align-content-start` - Inhalt ausrichten: Start auf dem PC (max.)
- `.pc-max:align-content-stretch` - Inhalt ausrichten: stretch auf dem PC (max.)

### Align items

- `.align-items-center` - Elemente ausrichten: Mitte
- `.align-items-end` - Elemente ausrichten: Ende
- `.align-items-start` - Elemente ausrichten: Start
- `.align-items-stretch` - Elemente ausrichten: stretch
- `.hover:align-items-center` - Elemente ausrichten: Mitte beim Hover
- `.hover:align-items-end` - Elemente ausrichten: Ende beim Hover
- `.hover:align-items-start` - Elemente ausrichten: Start beim Hover
- `.hover:align-items-stretch` - Elemente ausrichten: stretch beim Hover

##### Align items - Mobile (<= 480px)

- `.hover:mobile:align-items-center` - Elemente ausrichten: Mitte beim Hover auf Mobilgeräten
- `.hover:mobile:align-items-end` - Elemente ausrichten: Ende beim Hover auf Mobilgeräten
- `.hover:mobile:align-items-start` - Elemente ausrichten: Start beim Hover auf Mobilgeräten
- `.hover:mobile:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf Mobilgeräten
- `.mobile:align-items-center` - Elemente ausrichten: Mitte auf Mobilgeräten
- `.mobile:align-items-end` - Elemente ausrichten: Ende auf Mobilgeräten
- `.mobile:align-items-start` - Elemente ausrichten: Start auf Mobilgeräten
- `.mobile:align-items-stretch` - Elemente ausrichten: stretch auf Mobilgeräten

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - Elemente ausrichten: Mitte beim Hover auf Tablets
- `.hover:tablet:align-items-end` - Elemente ausrichten: Ende beim Hover auf Tablets
- `.hover:tablet:align-items-start` - Elemente ausrichten: Start beim Hover auf Tablets
- `.hover:tablet:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf Tablets
- `.tablet:align-items-center` - Elemente ausrichten: Mitte auf Tablets
- `.tablet:align-items-end` - Elemente ausrichten: Ende auf Tablets
- `.tablet:align-items-start` - Elemente ausrichten: Start auf Tablets
- `.tablet:align-items-stretch` - Elemente ausrichten: stretch auf Tablets

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - Elemente ausrichten: Mitte beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-items-end` - Elemente ausrichten: Ende beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-items-start` - Elemente ausrichten: Start beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf Tablet-PCs
- `.tablet-pc:align-items-center` - Elemente ausrichten: Mitte auf Tablet-PCs
- `.tablet-pc:align-items-end` - Elemente ausrichten: Ende auf Tablet-PCs
- `.tablet-pc:align-items-start` - Elemente ausrichten: Start auf Tablet-PCs
- `.tablet-pc:align-items-stretch` - Elemente ausrichten: stretch auf Tablet-PCs

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - Elemente ausrichten: Mitte beim Hover auf dem PC
- `.hover:pc:align-items-end` - Elemente ausrichten: Ende beim Hover auf dem PC
- `.hover:pc:align-items-start` - Elemente ausrichten: Start beim Hover auf dem PC
- `.hover:pc:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf dem PC
- `.pc:align-items-center` - Elemente ausrichten: Mitte auf dem PC
- `.pc:align-items-end` - Elemente ausrichten: Ende auf dem PC
- `.pc:align-items-start` - Elemente ausrichten: Start auf dem PC
- `.pc:align-items-stretch` - Elemente ausrichten: stretch auf dem PC

##### Align items - Tv (>= 1200px)

- `.hover:tv:align-items-center` - Elemente ausrichten: Mitte beim Hover auf dem TV
- `.hover:tv:align-items-end` - Elemente ausrichten: Ende beim Hover auf dem TV
- `.hover:tv:align-items-start` - Elemente ausrichten: Start beim Hover auf dem TV
- `.hover:tv:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf dem TV
- `.tv:align-items-center` - Elemente ausrichten: Mitte auf dem TV
- `.tv:align-items-end` - Elemente ausrichten: Ende auf dem TV
- `.tv:align-items-start` - Elemente ausrichten: Start auf dem TV
- `.tv:align-items-stretch` - Elemente ausrichten: stretch auf dem TV

##### Align items - Tablet Max (<= 768px)

- `.hover:tablet-max:align-items-center` - Elemente ausrichten: Mitte beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-items-end` - Elemente ausrichten: Ende beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-items-start` - Elemente ausrichten: Start beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf Tablets (max.)
- `.tablet-max:align-items-center` - Elemente ausrichten: Mitte auf Tablets (max.)
- `.tablet-max:align-items-end` - Elemente ausrichten: Ende auf Tablets (max.)
- `.tablet-max:align-items-start` - Elemente ausrichten: Start auf Tablets (max.)
- `.tablet-max:align-items-stretch` - Elemente ausrichten: stretch auf Tablets (max.)

##### Align items - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-items-center` - Elemente ausrichten: Mitte beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-items-end` - Elemente ausrichten: Ende beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-items-start` - Elemente ausrichten: Start beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:align-items-center` - Elemente ausrichten: Mitte auf Tablet-PCs (max.)
- `.tablet-pc-max:align-items-end` - Elemente ausrichten: Ende auf Tablet-PCs (max.)
- `.tablet-pc-max:align-items-start` - Elemente ausrichten: Start auf Tablet-PCs (max.)
- `.tablet-pc-max:align-items-stretch` - Elemente ausrichten: stretch auf Tablet-PCs (max.)

##### Align items - Pc Max (<= 1200px)

- `.hover:pc-max:align-items-center` - Elemente ausrichten: Mitte beim Hover auf dem PC (max.)
- `.hover:pc-max:align-items-end` - Elemente ausrichten: Ende beim Hover auf dem PC (max.)
- `.hover:pc-max:align-items-start` - Elemente ausrichten: Start beim Hover auf dem PC (max.)
- `.hover:pc-max:align-items-stretch` - Elemente ausrichten: stretch beim Hover auf dem PC (max.)
- `.pc-max:align-items-center` - Elemente ausrichten: Mitte auf dem PC (max.)
- `.pc-max:align-items-end` - Elemente ausrichten: Ende auf dem PC (max.)
- `.pc-max:align-items-start` - Elemente ausrichten: Start auf dem PC (max.)
- `.pc-max:align-items-stretch` - Elemente ausrichten: stretch auf dem PC (max.)

### Align self

- `.align-self-center` - Element selbst ausrichten: Mitte
- `.align-self-end` - Element selbst ausrichten: Ende
- `.align-self-start` - Element selbst ausrichten: Start
- `.align-self-stretch` - Element selbst ausrichten: stretch
- `.hover:align-self-center` - Element selbst ausrichten: Mitte beim Hover
- `.hover:align-self-end` - Element selbst ausrichten: Ende beim Hover
- `.hover:align-self-start` - Element selbst ausrichten: Start beim Hover
- `.hover:align-self-stretch` - Element selbst ausrichten: stretch beim Hover

##### Align self - Mobile (<= 480px)

- `.hover:mobile:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf Mobilgeräten
- `.hover:mobile:align-self-end` - Element selbst ausrichten: Ende beim Hover auf Mobilgeräten
- `.hover:mobile:align-self-start` - Element selbst ausrichten: Start beim Hover auf Mobilgeräten
- `.hover:mobile:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf Mobilgeräten
- `.mobile:align-self-center` - Element selbst ausrichten: Mitte auf Mobilgeräten
- `.mobile:align-self-end` - Element selbst ausrichten: Ende auf Mobilgeräten
- `.mobile:align-self-start` - Element selbst ausrichten: Start auf Mobilgeräten
- `.mobile:align-self-stretch` - Element selbst ausrichten: stretch auf Mobilgeräten

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf Tablets
- `.hover:tablet:align-self-end` - Element selbst ausrichten: Ende beim Hover auf Tablets
- `.hover:tablet:align-self-start` - Element selbst ausrichten: Start beim Hover auf Tablets
- `.hover:tablet:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf Tablets
- `.tablet:align-self-center` - Element selbst ausrichten: Mitte auf Tablets
- `.tablet:align-self-end` - Element selbst ausrichten: Ende auf Tablets
- `.tablet:align-self-start` - Element selbst ausrichten: Start auf Tablets
- `.tablet:align-self-stretch` - Element selbst ausrichten: stretch auf Tablets

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-self-end` - Element selbst ausrichten: Ende beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-self-start` - Element selbst ausrichten: Start beim Hover auf Tablet-PCs
- `.hover:tablet-pc:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf Tablet-PCs
- `.tablet-pc:align-self-center` - Element selbst ausrichten: Mitte auf Tablet-PCs
- `.tablet-pc:align-self-end` - Element selbst ausrichten: Ende auf Tablet-PCs
- `.tablet-pc:align-self-start` - Element selbst ausrichten: Start auf Tablet-PCs
- `.tablet-pc:align-self-stretch` - Element selbst ausrichten: stretch auf Tablet-PCs

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf dem PC
- `.hover:pc:align-self-end` - Element selbst ausrichten: Ende beim Hover auf dem PC
- `.hover:pc:align-self-start` - Element selbst ausrichten: Start beim Hover auf dem PC
- `.hover:pc:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf dem PC
- `.pc:align-self-center` - Element selbst ausrichten: Mitte auf dem PC
- `.pc:align-self-end` - Element selbst ausrichten: Ende auf dem PC
- `.pc:align-self-start` - Element selbst ausrichten: Start auf dem PC
- `.pc:align-self-stretch` - Element selbst ausrichten: stretch auf dem PC

##### Align self - Tv (>= 1200px)

- `.hover:tv:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf dem TV
- `.hover:tv:align-self-end` - Element selbst ausrichten: Ende beim Hover auf dem TV
- `.hover:tv:align-self-start` - Element selbst ausrichten: Start beim Hover auf dem TV
- `.hover:tv:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf dem TV
- `.tv:align-self-center` - Element selbst ausrichten: Mitte auf dem TV
- `.tv:align-self-end` - Element selbst ausrichten: Ende auf dem TV
- `.tv:align-self-start` - Element selbst ausrichten: Start auf dem TV
- `.tv:align-self-stretch` - Element selbst ausrichten: stretch auf dem TV

##### Align self - Tablet Max (<= 768px)

- `.hover:tablet-max:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-self-end` - Element selbst ausrichten: Ende beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-self-start` - Element selbst ausrichten: Start beim Hover auf Tablets (max.)
- `.hover:tablet-max:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf Tablets (max.)
- `.tablet-max:align-self-center` - Element selbst ausrichten: Mitte auf Tablets (max.)
- `.tablet-max:align-self-end` - Element selbst ausrichten: Ende auf Tablets (max.)
- `.tablet-max:align-self-start` - Element selbst ausrichten: Start auf Tablets (max.)
- `.tablet-max:align-self-stretch` - Element selbst ausrichten: stretch auf Tablets (max.)

##### Align self - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-self-end` - Element selbst ausrichten: Ende beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-self-start` - Element selbst ausrichten: Start beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:align-self-center` - Element selbst ausrichten: Mitte auf Tablet-PCs (max.)
- `.tablet-pc-max:align-self-end` - Element selbst ausrichten: Ende auf Tablet-PCs (max.)
- `.tablet-pc-max:align-self-start` - Element selbst ausrichten: Start auf Tablet-PCs (max.)
- `.tablet-pc-max:align-self-stretch` - Element selbst ausrichten: stretch auf Tablet-PCs (max.)

##### Align self - Pc Max (<= 1200px)

- `.hover:pc-max:align-self-center` - Element selbst ausrichten: Mitte beim Hover auf dem PC (max.)
- `.hover:pc-max:align-self-end` - Element selbst ausrichten: Ende beim Hover auf dem PC (max.)
- `.hover:pc-max:align-self-start` - Element selbst ausrichten: Start beim Hover auf dem PC (max.)
- `.hover:pc-max:align-self-stretch` - Element selbst ausrichten: stretch beim Hover auf dem PC (max.)
- `.pc-max:align-self-center` - Element selbst ausrichten: Mitte auf dem PC (max.)
- `.pc-max:align-self-end` - Element selbst ausrichten: Ende auf dem PC (max.)
- `.pc-max:align-self-start` - Element selbst ausrichten: Start auf dem PC (max.)
- `.pc-max:align-self-stretch` - Element selbst ausrichten: stretch auf dem PC (max.)

### Justify content

- `.hover:justify-content-around` - Inhalt verteilen: around beim Hover
- `.hover:justify-content-between` - Inhalt verteilen: between beim Hover
- `.hover:justify-content-center` - Inhalt verteilen: Mitte beim Hover
- `.hover:justify-content-end` - Inhalt verteilen: Ende beim Hover
- `.hover:justify-content-evenly` - Inhalt verteilen: evenly beim Hover
- `.hover:justify-content-start` - Inhalt verteilen: Start beim Hover
- `.hover:justify-content-stretch` - Inhalt verteilen: stretch beim Hover
- `.justify-content-around` - Inhalt verteilen: around
- `.justify-content-between` - Inhalt verteilen: between
- `.justify-content-center` - Inhalt verteilen: Mitte
- `.justify-content-end` - Inhalt verteilen: Ende
- `.justify-content-evenly` - Inhalt verteilen: evenly
- `.justify-content-start` - Inhalt verteilen: Start
- `.justify-content-stretch` - Inhalt verteilen: stretch

##### Justify content - Mobile (<= 480px)

- `.hover:mobile:justify-content-around` - Inhalt verteilen: around beim Hover auf Mobilgeräten
- `.hover:mobile:justify-content-between` - Inhalt verteilen: between beim Hover auf Mobilgeräten
- `.hover:mobile:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf Mobilgeräten
- `.hover:mobile:justify-content-end` - Inhalt verteilen: Ende beim Hover auf Mobilgeräten
- `.hover:mobile:justify-content-start` - Inhalt verteilen: Start beim Hover auf Mobilgeräten
- `.mobile:justify-content-around` - Inhalt verteilen: around auf Mobilgeräten
- `.mobile:justify-content-between` - Inhalt verteilen: between auf Mobilgeräten
- `.mobile:justify-content-center` - Inhalt verteilen: Mitte auf Mobilgeräten
- `.mobile:justify-content-end` - Inhalt verteilen: Ende auf Mobilgeräten
- `.mobile:justify-content-start` - Inhalt verteilen: Start auf Mobilgeräten

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - Inhalt verteilen: around beim Hover auf Tablets
- `.hover:tablet:justify-content-between` - Inhalt verteilen: between beim Hover auf Tablets
- `.hover:tablet:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf Tablets
- `.hover:tablet:justify-content-end` - Inhalt verteilen: Ende beim Hover auf Tablets
- `.hover:tablet:justify-content-start` - Inhalt verteilen: Start beim Hover auf Tablets
- `.tablet:justify-content-around` - Inhalt verteilen: around auf Tablets
- `.tablet:justify-content-between` - Inhalt verteilen: between auf Tablets
- `.tablet:justify-content-center` - Inhalt verteilen: Mitte auf Tablets
- `.tablet:justify-content-end` - Inhalt verteilen: Ende auf Tablets
- `.tablet:justify-content-start` - Inhalt verteilen: Start auf Tablets

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - Inhalt verteilen: around beim Hover auf Tablet-PCs
- `.hover:tablet-pc:justify-content-between` - Inhalt verteilen: between beim Hover auf Tablet-PCs
- `.hover:tablet-pc:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf Tablet-PCs
- `.hover:tablet-pc:justify-content-end` - Inhalt verteilen: Ende beim Hover auf Tablet-PCs
- `.hover:tablet-pc:justify-content-start` - Inhalt verteilen: Start beim Hover auf Tablet-PCs
- `.tablet-pc:justify-content-around` - Inhalt verteilen: around auf Tablet-PCs
- `.tablet-pc:justify-content-between` - Inhalt verteilen: between auf Tablet-PCs
- `.tablet-pc:justify-content-center` - Inhalt verteilen: Mitte auf Tablet-PCs
- `.tablet-pc:justify-content-end` - Inhalt verteilen: Ende auf Tablet-PCs
- `.tablet-pc:justify-content-start` - Inhalt verteilen: Start auf Tablet-PCs

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - Inhalt verteilen: around beim Hover auf dem PC
- `.hover:pc:justify-content-between` - Inhalt verteilen: between beim Hover auf dem PC
- `.hover:pc:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf dem PC
- `.hover:pc:justify-content-end` - Inhalt verteilen: Ende beim Hover auf dem PC
- `.hover:pc:justify-content-start` - Inhalt verteilen: Start beim Hover auf dem PC
- `.pc:justify-content-around` - Inhalt verteilen: around auf dem PC
- `.pc:justify-content-between` - Inhalt verteilen: between auf dem PC
- `.pc:justify-content-center` - Inhalt verteilen: Mitte auf dem PC
- `.pc:justify-content-end` - Inhalt verteilen: Ende auf dem PC
- `.pc:justify-content-start` - Inhalt verteilen: Start auf dem PC

##### Justify content - Tv (>= 1200px)

- `.hover:tv:justify-content-around` - Inhalt verteilen: around beim Hover auf dem TV
- `.hover:tv:justify-content-between` - Inhalt verteilen: between beim Hover auf dem TV
- `.hover:tv:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf dem TV
- `.hover:tv:justify-content-end` - Inhalt verteilen: Ende beim Hover auf dem TV
- `.hover:tv:justify-content-start` - Inhalt verteilen: Start beim Hover auf dem TV
- `.tv:justify-content-around` - Inhalt verteilen: around auf dem TV
- `.tv:justify-content-between` - Inhalt verteilen: between auf dem TV
- `.tv:justify-content-center` - Inhalt verteilen: Mitte auf dem TV
- `.tv:justify-content-end` - Inhalt verteilen: Ende auf dem TV
- `.tv:justify-content-start` - Inhalt verteilen: Start auf dem TV

##### Justify content - Tablet Max (<= 768px)

- `.hover:tablet-max:justify-content-around` - Inhalt verteilen: around beim Hover auf Tablets (max.)
- `.hover:tablet-max:justify-content-between` - Inhalt verteilen: between beim Hover auf Tablets (max.)
- `.hover:tablet-max:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf Tablets (max.)
- `.hover:tablet-max:justify-content-end` - Inhalt verteilen: Ende beim Hover auf Tablets (max.)
- `.hover:tablet-max:justify-content-start` - Inhalt verteilen: Start beim Hover auf Tablets (max.)
- `.tablet-max:justify-content-around` - Inhalt verteilen: around auf Tablets (max.)
- `.tablet-max:justify-content-between` - Inhalt verteilen: between auf Tablets (max.)
- `.tablet-max:justify-content-center` - Inhalt verteilen: Mitte auf Tablets (max.)
- `.tablet-max:justify-content-end` - Inhalt verteilen: Ende auf Tablets (max.)
- `.tablet-max:justify-content-start` - Inhalt verteilen: Start auf Tablets (max.)

##### Justify content - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:justify-content-around` - Inhalt verteilen: around beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:justify-content-between` - Inhalt verteilen: between beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:justify-content-end` - Inhalt verteilen: Ende beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:justify-content-start` - Inhalt verteilen: Start beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:justify-content-around` - Inhalt verteilen: around auf Tablet-PCs (max.)
- `.tablet-pc-max:justify-content-between` - Inhalt verteilen: between auf Tablet-PCs (max.)
- `.tablet-pc-max:justify-content-center` - Inhalt verteilen: Mitte auf Tablet-PCs (max.)
- `.tablet-pc-max:justify-content-end` - Inhalt verteilen: Ende auf Tablet-PCs (max.)
- `.tablet-pc-max:justify-content-start` - Inhalt verteilen: Start auf Tablet-PCs (max.)

##### Justify content - Pc Max (<= 1200px)

- `.hover:pc-max:justify-content-around` - Inhalt verteilen: around beim Hover auf dem PC (max.)
- `.hover:pc-max:justify-content-between` - Inhalt verteilen: between beim Hover auf dem PC (max.)
- `.hover:pc-max:justify-content-center` - Inhalt verteilen: Mitte beim Hover auf dem PC (max.)
- `.hover:pc-max:justify-content-end` - Inhalt verteilen: Ende beim Hover auf dem PC (max.)
- `.hover:pc-max:justify-content-start` - Inhalt verteilen: Start beim Hover auf dem PC (max.)
- `.pc-max:justify-content-around` - Inhalt verteilen: around auf dem PC (max.)
- `.pc-max:justify-content-between` - Inhalt verteilen: between auf dem PC (max.)
- `.pc-max:justify-content-center` - Inhalt verteilen: Mitte auf dem PC (max.)
- `.pc-max:justify-content-end` - Inhalt verteilen: Ende auf dem PC (max.)
- `.pc-max:justify-content-start` - Inhalt verteilen: Start auf dem PC (max.)

### Justify items

- `.hover:justify-items-center` - Elemente justieren: Mitte beim Hover
- `.hover:justify-items-end` - Elemente justieren: Ende beim Hover
- `.hover:justify-items-start` - Elemente justieren: Start beim Hover
- `.hover:justify-items-stretch` - Elemente justieren: stretch beim Hover
- `.justify-items-center` - Elemente justieren: Mitte
- `.justify-items-end` - Elemente justieren: Ende
- `.justify-items-start` - Elemente justieren: Start
- `.justify-items-stretch` - Elemente justieren: stretch

### Order

- `.hover:order-5` - Reihenfolge 5 beim Hover
- `.hover:order-4` - Reihenfolge 4 beim Hover
- `.hover:order-3` - Reihenfolge 3 beim Hover
- `.hover:order-2` - Reihenfolge 2 beim Hover
- `.hover:order-1` - Reihenfolge 1 beim Hover
- `.hover:order-0` - Reihenfolge 0 beim Hover
- `.hover:order-first` - Reihenfolge: erste beim Hover
- `.hover:order-last` - Reihenfolge: letzte beim Hover
- `.order-5` - Reihenfolge 5
- `.order-4` - Reihenfolge 4
- `.order-3` - Reihenfolge 3
- `.order-2` - Reihenfolge 2
- `.order-1` - Reihenfolge 1
- `.order-0` - Reihenfolge 0
- `.order-first` - Reihenfolge: erste
- `.order-last` - Reihenfolge: letzte

##### Negative Order

- `.-order-5` - Negative Reihenfolge 5
- `.-order-4` - Negative Reihenfolge 4
- `.-order-3` - Negative Reihenfolge 3
- `.-order-2` - Negative Reihenfolge 2
- `.-order-1` - Negative Reihenfolge 1
- `.hover:-order-5` - Negative Reihenfolge 5 beim Hover
- `.hover:-order-4` - Negative Reihenfolge 4 beim Hover
- `.hover:-order-3` - Negative Reihenfolge 3 beim Hover
- `.hover:-order-2` - Negative Reihenfolge 2 beim Hover
- `.hover:-order-1` - Negative Reihenfolge 1 beim Hover

##### Order - Mobile (<= 480px)

- `.hover:mobile:order-5` - Reihenfolge 5 beim Hover auf Mobilgeräten
- `.hover:mobile:order-4` - Reihenfolge 4 beim Hover auf Mobilgeräten
- `.hover:mobile:order-3` - Reihenfolge 3 beim Hover auf Mobilgeräten
- `.hover:mobile:order-2` - Reihenfolge 2 beim Hover auf Mobilgeräten
- `.hover:mobile:order-1` - Reihenfolge 1 beim Hover auf Mobilgeräten
- `.hover:mobile:order-0` - Reihenfolge 0 beim Hover auf Mobilgeräten
- `.hover:mobile:order-first` - Reihenfolge: erste beim Hover auf Mobilgeräten
- `.hover:mobile:order-last` - Reihenfolge: letzte beim Hover auf Mobilgeräten
- `.mobile:order-5` - Reihenfolge 5 auf Mobilgeräten
- `.mobile:order-4` - Reihenfolge 4 auf Mobilgeräten
- `.mobile:order-3` - Reihenfolge 3 auf Mobilgeräten
- `.mobile:order-2` - Reihenfolge 2 auf Mobilgeräten
- `.mobile:order-1` - Reihenfolge 1 auf Mobilgeräten
- `.mobile:order-0` - Reihenfolge 0 auf Mobilgeräten
- `.mobile:order-first` - Reihenfolge: erste auf Mobilgeräten
- `.mobile:order-last` - Reihenfolge: letzte auf Mobilgeräten

##### Negative Order - Mobile (<= 480px)

- `.hover:mobile:-order-5` - Negative Reihenfolge 5 beim Hover auf Mobilgeräten
- `.hover:mobile:-order-4` - Negative Reihenfolge 4 beim Hover auf Mobilgeräten
- `.hover:mobile:-order-3` - Negative Reihenfolge 3 beim Hover auf Mobilgeräten
- `.hover:mobile:-order-2` - Negative Reihenfolge 2 beim Hover auf Mobilgeräten
- `.hover:mobile:-order-1` - Negative Reihenfolge 1 beim Hover auf Mobilgeräten
- `.mobile:-order-5` - Negative Reihenfolge 5 auf Mobilgeräten
- `.mobile:-order-4` - Negative Reihenfolge 4 auf Mobilgeräten
- `.mobile:-order-3` - Negative Reihenfolge 3 auf Mobilgeräten
- `.mobile:-order-2` - Negative Reihenfolge 2 auf Mobilgeräten
- `.mobile:-order-1` - Negative Reihenfolge 1 auf Mobilgeräten

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - Reihenfolge 5 beim Hover auf Tablets
- `.hover:tablet:order-4` - Reihenfolge 4 beim Hover auf Tablets
- `.hover:tablet:order-3` - Reihenfolge 3 beim Hover auf Tablets
- `.hover:tablet:order-2` - Reihenfolge 2 beim Hover auf Tablets
- `.hover:tablet:order-1` - Reihenfolge 1 beim Hover auf Tablets
- `.hover:tablet:order-0` - Reihenfolge 0 beim Hover auf Tablets
- `.hover:tablet:order-first` - Reihenfolge: erste beim Hover auf Tablets
- `.hover:tablet:order-last` - Reihenfolge: letzte beim Hover auf Tablets
- `.tablet:order-5` - Reihenfolge 5 auf Tablets
- `.tablet:order-4` - Reihenfolge 4 auf Tablets
- `.tablet:order-3` - Reihenfolge 3 auf Tablets
- `.tablet:order-2` - Reihenfolge 2 auf Tablets
- `.tablet:order-1` - Reihenfolge 1 auf Tablets
- `.tablet:order-0` - Reihenfolge 0 auf Tablets
- `.tablet:order-first` - Reihenfolge: erste auf Tablets
- `.tablet:order-last` - Reihenfolge: letzte auf Tablets

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - Negative Reihenfolge 5 beim Hover auf Tablets
- `.hover:tablet:-order-4` - Negative Reihenfolge 4 beim Hover auf Tablets
- `.hover:tablet:-order-3` - Negative Reihenfolge 3 beim Hover auf Tablets
- `.hover:tablet:-order-2` - Negative Reihenfolge 2 beim Hover auf Tablets
- `.hover:tablet:-order-1` - Negative Reihenfolge 1 beim Hover auf Tablets
- `.tablet:-order-5` - Negative Reihenfolge 5 auf Tablets
- `.tablet:-order-4` - Negative Reihenfolge 4 auf Tablets
- `.tablet:-order-3` - Negative Reihenfolge 3 auf Tablets
- `.tablet:-order-2` - Negative Reihenfolge 2 auf Tablets
- `.tablet:-order-1` - Negative Reihenfolge 1 auf Tablets

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - Reihenfolge 5 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-4` - Reihenfolge 4 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-3` - Reihenfolge 3 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-2` - Reihenfolge 2 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-1` - Reihenfolge 1 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-0` - Reihenfolge 0 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-first` - Reihenfolge: erste beim Hover auf Tablet-PCs
- `.hover:tablet-pc:order-last` - Reihenfolge: letzte beim Hover auf Tablet-PCs
- `.tablet-pc:order-5` - Reihenfolge 5 auf Tablet-PCs
- `.tablet-pc:order-4` - Reihenfolge 4 auf Tablet-PCs
- `.tablet-pc:order-3` - Reihenfolge 3 auf Tablet-PCs
- `.tablet-pc:order-2` - Reihenfolge 2 auf Tablet-PCs
- `.tablet-pc:order-1` - Reihenfolge 1 auf Tablet-PCs
- `.tablet-pc:order-0` - Reihenfolge 0 auf Tablet-PCs
- `.tablet-pc:order-first` - Reihenfolge: erste auf Tablet-PCs
- `.tablet-pc:order-last` - Reihenfolge: letzte auf Tablet-PCs

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - Negative Reihenfolge 5 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:-order-4` - Negative Reihenfolge 4 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:-order-3` - Negative Reihenfolge 3 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:-order-2` - Negative Reihenfolge 2 beim Hover auf Tablet-PCs
- `.hover:tablet-pc:-order-1` - Negative Reihenfolge 1 beim Hover auf Tablet-PCs
- `.tablet-pc:-order-5` - Negative Reihenfolge 5 auf Tablet-PCs
- `.tablet-pc:-order-4` - Negative Reihenfolge 4 auf Tablet-PCs
- `.tablet-pc:-order-3` - Negative Reihenfolge 3 auf Tablet-PCs
- `.tablet-pc:-order-2` - Negative Reihenfolge 2 auf Tablet-PCs
- `.tablet-pc:-order-1` - Negative Reihenfolge 1 auf Tablet-PCs

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - Reihenfolge 5 beim Hover auf dem PC
- `.hover:pc:order-4` - Reihenfolge 4 beim Hover auf dem PC
- `.hover:pc:order-3` - Reihenfolge 3 beim Hover auf dem PC
- `.hover:pc:order-2` - Reihenfolge 2 beim Hover auf dem PC
- `.hover:pc:order-1` - Reihenfolge 1 beim Hover auf dem PC
- `.hover:pc:order-0` - Reihenfolge 0 beim Hover auf dem PC
- `.hover:pc:order-first` - Reihenfolge: erste beim Hover auf dem PC
- `.hover:pc:order-last` - Reihenfolge: letzte beim Hover auf dem PC
- `.pc:order-5` - Reihenfolge 5 auf dem PC
- `.pc:order-4` - Reihenfolge 4 auf dem PC
- `.pc:order-3` - Reihenfolge 3 auf dem PC
- `.pc:order-2` - Reihenfolge 2 auf dem PC
- `.pc:order-1` - Reihenfolge 1 auf dem PC
- `.pc:order-0` - Reihenfolge 0 auf dem PC
- `.pc:order-first` - Reihenfolge: erste auf dem PC
- `.pc:order-last` - Reihenfolge: letzte auf dem PC

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - Negative Reihenfolge 5 beim Hover auf dem PC
- `.hover:pc:-order-4` - Negative Reihenfolge 4 beim Hover auf dem PC
- `.hover:pc:-order-3` - Negative Reihenfolge 3 beim Hover auf dem PC
- `.hover:pc:-order-2` - Negative Reihenfolge 2 beim Hover auf dem PC
- `.hover:pc:-order-1` - Negative Reihenfolge 1 beim Hover auf dem PC
- `.pc:-order-5` - Negative Reihenfolge 5 auf dem PC
- `.pc:-order-4` - Negative Reihenfolge 4 auf dem PC
- `.pc:-order-3` - Negative Reihenfolge 3 auf dem PC
- `.pc:-order-2` - Negative Reihenfolge 2 auf dem PC
- `.pc:-order-1` - Negative Reihenfolge 1 auf dem PC

##### Order - Tv (>= 1200px)

- `.hover:tv:order-5` - Reihenfolge 5 beim Hover auf dem TV
- `.hover:tv:order-4` - Reihenfolge 4 beim Hover auf dem TV
- `.hover:tv:order-3` - Reihenfolge 3 beim Hover auf dem TV
- `.hover:tv:order-2` - Reihenfolge 2 beim Hover auf dem TV
- `.hover:tv:order-1` - Reihenfolge 1 beim Hover auf dem TV
- `.hover:tv:order-0` - Reihenfolge 0 beim Hover auf dem TV
- `.hover:tv:order-first` - Reihenfolge: erste beim Hover auf dem TV
- `.hover:tv:order-last` - Reihenfolge: letzte beim Hover auf dem TV
- `.tv:order-5` - Reihenfolge 5 auf dem TV
- `.tv:order-4` - Reihenfolge 4 auf dem TV
- `.tv:order-3` - Reihenfolge 3 auf dem TV
- `.tv:order-2` - Reihenfolge 2 auf dem TV
- `.tv:order-1` - Reihenfolge 1 auf dem TV
- `.tv:order-0` - Reihenfolge 0 auf dem TV
- `.tv:order-first` - Reihenfolge: erste auf dem TV
- `.tv:order-last` - Reihenfolge: letzte auf dem TV

##### Negative Order - Tv (>= 1200px)

- `.hover:tv:-order-5` - Negative Reihenfolge 5 beim Hover auf dem TV
- `.hover:tv:-order-4` - Negative Reihenfolge 4 beim Hover auf dem TV
- `.hover:tv:-order-3` - Negative Reihenfolge 3 beim Hover auf dem TV
- `.hover:tv:-order-2` - Negative Reihenfolge 2 beim Hover auf dem TV
- `.hover:tv:-order-1` - Negative Reihenfolge 1 beim Hover auf dem TV
- `.tv:-order-5` - Negative Reihenfolge 5 auf dem TV
- `.tv:-order-4` - Negative Reihenfolge 4 auf dem TV
- `.tv:-order-3` - Negative Reihenfolge 3 auf dem TV
- `.tv:-order-2` - Negative Reihenfolge 2 auf dem TV
- `.tv:-order-1` - Negative Reihenfolge 1 auf dem TV

##### Order - Tablet Max (<= 768px)

- `.hover:tablet-max:order-5` - Reihenfolge 5 beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-4` - Reihenfolge 4 beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-3` - Reihenfolge 3 beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-2` - Reihenfolge 2 beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-1` - Reihenfolge 1 beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-0` - Reihenfolge 0 beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-first` - Reihenfolge: erste beim Hover auf Tablets (max.)
- `.hover:tablet-max:order-last` - Reihenfolge: letzte beim Hover auf Tablets (max.)
- `.tablet-max:order-5` - Reihenfolge 5 auf Tablets (max.)
- `.tablet-max:order-4` - Reihenfolge 4 auf Tablets (max.)
- `.tablet-max:order-3` - Reihenfolge 3 auf Tablets (max.)
- `.tablet-max:order-2` - Reihenfolge 2 auf Tablets (max.)
- `.tablet-max:order-1` - Reihenfolge 1 auf Tablets (max.)
- `.tablet-max:order-0` - Reihenfolge 0 auf Tablets (max.)
- `.tablet-max:order-first` - Reihenfolge: erste auf Tablets (max.)
- `.tablet-max:order-last` - Reihenfolge: letzte auf Tablets (max.)

##### Negative Order - Tablet Max (<= 768px)

- `.hover:tablet-max:-order-5` - Negative Reihenfolge 5 beim Hover auf Tablets (max.)
- `.hover:tablet-max:-order-4` - Negative Reihenfolge 4 beim Hover auf Tablets (max.)
- `.hover:tablet-max:-order-3` - Negative Reihenfolge 3 beim Hover auf Tablets (max.)
- `.hover:tablet-max:-order-2` - Negative Reihenfolge 2 beim Hover auf Tablets (max.)
- `.hover:tablet-max:-order-1` - Negative Reihenfolge 1 beim Hover auf Tablets (max.)
- `.tablet-max:-order-5` - Negative Reihenfolge 5 auf Tablets (max.)
- `.tablet-max:-order-4` - Negative Reihenfolge 4 auf Tablets (max.)
- `.tablet-max:-order-3` - Negative Reihenfolge 3 auf Tablets (max.)
- `.tablet-max:-order-2` - Negative Reihenfolge 2 auf Tablets (max.)
- `.tablet-max:-order-1` - Negative Reihenfolge 1 auf Tablets (max.)

##### Order - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:order-5` - Reihenfolge 5 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-4` - Reihenfolge 4 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-3` - Reihenfolge 3 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-2` - Reihenfolge 2 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-1` - Reihenfolge 1 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-0` - Reihenfolge 0 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-first` - Reihenfolge: erste beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:order-last` - Reihenfolge: letzte beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:order-5` - Reihenfolge 5 auf Tablet-PCs (max.)
- `.tablet-pc-max:order-4` - Reihenfolge 4 auf Tablet-PCs (max.)
- `.tablet-pc-max:order-3` - Reihenfolge 3 auf Tablet-PCs (max.)
- `.tablet-pc-max:order-2` - Reihenfolge 2 auf Tablet-PCs (max.)
- `.tablet-pc-max:order-1` - Reihenfolge 1 auf Tablet-PCs (max.)
- `.tablet-pc-max:order-0` - Reihenfolge 0 auf Tablet-PCs (max.)
- `.tablet-pc-max:order-first` - Reihenfolge: erste auf Tablet-PCs (max.)
- `.tablet-pc-max:order-last` - Reihenfolge: letzte auf Tablet-PCs (max.)

##### Negative Order - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:-order-5` - Negative Reihenfolge 5 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:-order-4` - Negative Reihenfolge 4 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:-order-3` - Negative Reihenfolge 3 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:-order-2` - Negative Reihenfolge 2 beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:-order-1` - Negative Reihenfolge 1 beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:-order-5` - Negative Reihenfolge 5 auf Tablet-PCs (max.)
- `.tablet-pc-max:-order-4` - Negative Reihenfolge 4 auf Tablet-PCs (max.)
- `.tablet-pc-max:-order-3` - Negative Reihenfolge 3 auf Tablet-PCs (max.)
- `.tablet-pc-max:-order-2` - Negative Reihenfolge 2 auf Tablet-PCs (max.)
- `.tablet-pc-max:-order-1` - Negative Reihenfolge 1 auf Tablet-PCs (max.)

##### Order - Pc Max (<= 1200px)

- `.hover:pc-max:order-5` - Reihenfolge 5 beim Hover auf dem PC (max.)
- `.hover:pc-max:order-4` - Reihenfolge 4 beim Hover auf dem PC (max.)
- `.hover:pc-max:order-3` - Reihenfolge 3 beim Hover auf dem PC (max.)
- `.hover:pc-max:order-2` - Reihenfolge 2 beim Hover auf dem PC (max.)
- `.hover:pc-max:order-1` - Reihenfolge 1 beim Hover auf dem PC (max.)
- `.hover:pc-max:order-0` - Reihenfolge 0 beim Hover auf dem PC (max.)
- `.hover:pc-max:order-first` - Reihenfolge: erste beim Hover auf dem PC (max.)
- `.hover:pc-max:order-last` - Reihenfolge: letzte beim Hover auf dem PC (max.)
- `.pc-max:order-5` - Reihenfolge 5 auf dem PC (max.)
- `.pc-max:order-4` - Reihenfolge 4 auf dem PC (max.)
- `.pc-max:order-3` - Reihenfolge 3 auf dem PC (max.)
- `.pc-max:order-2` - Reihenfolge 2 auf dem PC (max.)
- `.pc-max:order-1` - Reihenfolge 1 auf dem PC (max.)
- `.pc-max:order-0` - Reihenfolge 0 auf dem PC (max.)
- `.pc-max:order-first` - Reihenfolge: erste auf dem PC (max.)
- `.pc-max:order-last` - Reihenfolge: letzte auf dem PC (max.)

##### Negative Order - Pc Max (<= 1200px)

- `.hover:pc-max:-order-5` - Negative Reihenfolge 5 beim Hover auf dem PC (max.)
- `.hover:pc-max:-order-4` - Negative Reihenfolge 4 beim Hover auf dem PC (max.)
- `.hover:pc-max:-order-3` - Negative Reihenfolge 3 beim Hover auf dem PC (max.)
- `.hover:pc-max:-order-2` - Negative Reihenfolge 2 beim Hover auf dem PC (max.)
- `.hover:pc-max:-order-1` - Negative Reihenfolge 1 beim Hover auf dem PC max
- `.pc-max:-order-5` - Negative Reihenfolge 5 auf dem PC (max.)
- `.pc-max:-order-4` - Negative Reihenfolge 4 auf dem PC (max.)
- `.pc-max:-order-3` - Negative Reihenfolge 3 auf dem PC (max.)
- `.pc-max:-order-2` - Negative Reihenfolge 2 auf dem PC (max.)
- `.pc-max:-order-1` - Negative Reihenfolge 1 auf dem PC (max.)

## Spacing

### Margin

#### Margin All

- `.first:m-0` - Außenabstand alle Seiten 0rem beim ersten Element
- `.hover:m-5` - Außenabstand alle Seiten 5rem beim Hover
- `.hover:m-4.5` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-4` - Außenabstand alle Seiten 4rem beim Hover
- `.hover:m-3.5` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-3` - Außenabstand alle Seiten 3rem beim Hover
- `.hover:m-2.5` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-2` - Außenabstand alle Seiten 2rem beim Hover
- `.hover:m-1.9` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.8` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.7` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.6` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.5` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.4` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.3` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.2` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1.1` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-1` - Außenabstand alle Seiten 1rem beim Hover
- `.hover:m-0.9` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.8` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.7` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.6` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.5` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.4` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.3` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-0.2` - Außenabstand alle Seiten 0.2rem beim Hover
- `.hover:m-0.1` - Außenabstand alle Seiten 0.1rem beim Hover
- `.hover:m-0` - Außenabstand alle Seiten 0rem beim Hover
- `.hover:m-auto` - Außenabstand alle Seiten auto beim Hover
- `.last:m-0` - Außenabstand alle Seiten 0rem beim letzten Element
- `.m-5` - Außenabstand alle Seiten 5rem
- `.m-4.5` - Außenabstand alle Seiten 0rem
- `.m-4` - Außenabstand alle Seiten 4rem
- `.m-3.5` - Außenabstand alle Seiten 0rem
- `.m-3` - Außenabstand alle Seiten 3rem
- `.m-2.5` - Außenabstand alle Seiten 0rem
- `.m-2` - Außenabstand alle Seiten 2rem
- `.m-1.9` - Außenabstand alle Seiten 0rem
- `.m-1.8` - Außenabstand alle Seiten 0rem
- `.m-1.7` - Außenabstand alle Seiten 0rem
- `.m-1.6` - Außenabstand alle Seiten 0rem
- `.m-1.5` - Außenabstand alle Seiten 0rem
- `.m-1.4` - Außenabstand alle Seiten 0rem
- `.m-1.3` - Außenabstand alle Seiten 0rem
- `.m-1.2` - Außenabstand alle Seiten 0rem
- `.m-1.1` - Außenabstand alle Seiten 0rem
- `.m-1` - Außenabstand alle Seiten 1rem
- `.m-0.9` - Außenabstand alle Seiten 0rem
- `.m-0.8` - Außenabstand alle Seiten 0rem
- `.m-0.7` - Außenabstand alle Seiten 0rem
- `.m-0.6` - Außenabstand alle Seiten 0rem
- `.m-0.5` - Außenabstand alle Seiten 0rem
- `.m-0.4` - Außenabstand alle Seiten 0rem
- `.m-0.3` - Außenabstand alle Seiten 0rem
- `.m-0.2` - Außenabstand alle Seiten 0.2rem
- `.m-0.1` - Außenabstand alle Seiten 0.1rem
- `.m-0` - Außenabstand alle Seiten 0rem
- `.m-auto` - Außenabstand alle Seiten auto

#### Margin Bottom

- `.first:mb-0` - Außenabstand unten 0rem beim ersten Element
- `.hover:mb-100` - Außenabstand unten 100 % beim Hover
- `.hover:mb-75` - Außenabstand unten 75 % beim Hover
- `.hover:mb-50` - Außenabstand unten 50 % beim Hover
- `.hover:mb-25` - Außenabstand unten 25 % beim Hover
- `.hover:mb-5` - Außenabstand unten 5rem beim Hover
- `.hover:mb-4.5` - Außenabstand unten 0rem beim Hover
- `.hover:mb-4` - Außenabstand unten 4rem beim Hover
- `.hover:mb-3.5` - Außenabstand unten 0rem beim Hover
- `.hover:mb-3` - Außenabstand unten 3rem beim Hover
- `.hover:mb-2.5` - Außenabstand unten 0rem beim Hover
- `.hover:mb-2` - Außenabstand unten 2rem beim Hover
- `.hover:mb-1.9` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.8` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.7` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.6` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.5` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.4` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.3` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.2` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1.1` - Außenabstand unten 0rem beim Hover
- `.hover:mb-1` - Außenabstand unten 1rem beim Hover
- `.hover:mb-0.9` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.8` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.7` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.6` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.5` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.4` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.3` - Außenabstand unten 0rem beim Hover
- `.hover:mb-0.2` - Außenabstand unten 0.2rem beim Hover
- `.hover:mb-0.1` - Außenabstand unten 0.1rem beim Hover
- `.hover:mb-0` - Außenabstand unten 0rem beim Hover
- `.hover:mb-auto` - Außenabstand unten auto beim Hover
- `.last:mb-0` - Außenabstand unten 0rem beim letzten Element
- `.mb-100` - Außenabstand unten 100 %
- `.mb-75` - Außenabstand unten 75 %
- `.mb-50` - Außenabstand unten 50 %
- `.mb-25` - Außenabstand unten 25 %
- `.mb-5` - Außenabstand unten 5rem
- `.mb-4.5` - Außenabstand unten 0rem
- `.mb-4` - Außenabstand unten 4rem
- `.mb-3.5` - Außenabstand unten 0rem
- `.mb-3` - Außenabstand unten 3rem
- `.mb-2.5` - Außenabstand unten 0rem
- `.mb-2` - Außenabstand unten 2rem
- `.mb-1.9` - Außenabstand unten 0rem
- `.mb-1.8` - Außenabstand unten 0rem
- `.mb-1.7` - Außenabstand unten 0rem
- `.mb-1.6` - Außenabstand unten 0rem
- `.mb-1.5` - Außenabstand unten 0rem
- `.mb-1.4` - Außenabstand unten 0rem
- `.mb-1.3` - Außenabstand unten 0rem
- `.mb-1.2` - Außenabstand unten 0rem
- `.mb-1.1` - Außenabstand unten 0rem
- `.mb-1` - Außenabstand unten 1rem
- `.mb-0.9` - Außenabstand unten 0rem
- `.mb-0.8` - Außenabstand unten 0rem
- `.mb-0.7` - Außenabstand unten 0rem
- `.mb-0.6` - Außenabstand unten 0rem
- `.mb-0.5` - Außenabstand unten 0rem
- `.mb-0.4` - Außenabstand unten 0rem
- `.mb-0.3` - Außenabstand unten 0rem
- `.mb-0.2` - Außenabstand unten 0.2rem
- `.mb-0.1` - Außenabstand unten 0.1rem
- `.mb-0` - Außenabstand unten 0rem
- `.mb-auto` - Außenabstand unten auto

#### Margin End

- `.hover:me-2` - Außenabstand Ende 2rem beim Hover
- `.hover:me-1.5` - Außenabstand Ende 1.5rem beim Hover
- `.hover:me-1` - Außenabstand Ende 1rem beim Hover
- `.hover:me-0.5` - Außenabstand Ende 0.5rem beim Hover
- `.hover:me-0` - Außenabstand Ende 0rem beim Hover
- `.me-2` - Außenabstand Ende 2rem
- `.me-1.5` - Außenabstand Ende 1.5rem
- `.me-1` - Außenabstand Ende 1rem
- `.me-0.5` - Außenabstand Ende 0.5rem
- `.me-0` - Außenabstand Ende 0rem

#### Margin Left

- `.first:ml-0` - Außenabstand links 0rem beim ersten Element
- `.hover:ml-100` - Außenabstand links 100 % beim Hover
- `.hover:ml-75` - Außenabstand links 75 % beim Hover
- `.hover:ml-50` - Außenabstand links 50 % beim Hover
- `.hover:ml-25` - Außenabstand links 25 % beim Hover
- `.hover:ml-5` - Außenabstand links 5rem beim Hover
- `.hover:ml-4.5` - Außenabstand links 0rem beim Hover
- `.hover:ml-4` - Außenabstand links 4rem beim Hover
- `.hover:ml-3.5` - Außenabstand links 0rem beim Hover
- `.hover:ml-3` - Außenabstand links 3rem beim Hover
- `.hover:ml-2.5` - Außenabstand links 0rem beim Hover
- `.hover:ml-2` - Außenabstand links 2rem beim Hover
- `.hover:ml-1.9` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.8` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.7` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.6` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.5` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.4` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.3` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.2` - Außenabstand links 0rem beim Hover
- `.hover:ml-1.1` - Außenabstand links 0rem beim Hover
- `.hover:ml-1` - Außenabstand links 1rem beim Hover
- `.hover:ml-0.9` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.8` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.7` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.6` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.5` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.4` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.3` - Außenabstand links 0rem beim Hover
- `.hover:ml-0.2` - Außenabstand links 0.2rem beim Hover
- `.hover:ml-0.1` - Außenabstand links 0.1rem beim Hover
- `.hover:ml-0` - Außenabstand links 0rem beim Hover
- `.hover:ml-auto` - Außenabstand links auto beim Hover
- `.last:ml-0` - Außenabstand links 0rem beim letzten Element
- `.ml-100` - Außenabstand links 100 %
- `.ml-75` - Außenabstand links 75 %
- `.ml-50` - Außenabstand links 50 %
- `.ml-25` - Außenabstand links 25 %
- `.ml-5` - Außenabstand links 5rem
- `.ml-4.5` - Außenabstand links 0rem
- `.ml-4` - Außenabstand links 4rem
- `.ml-3.5` - Außenabstand links 0rem
- `.ml-3` - Außenabstand links 3rem
- `.ml-2.5` - Außenabstand links 0rem
- `.ml-2` - Außenabstand links 2rem
- `.ml-1.9` - Außenabstand links 0rem
- `.ml-1.8` - Außenabstand links 0rem
- `.ml-1.7` - Außenabstand links 0rem
- `.ml-1.6` - Außenabstand links 0rem
- `.ml-1.5` - Außenabstand links 0rem
- `.ml-1.4` - Außenabstand links 0rem
- `.ml-1.3` - Außenabstand links 0rem
- `.ml-1.2` - Außenabstand links 0rem
- `.ml-1.1` - Außenabstand links 0rem
- `.ml-1` - Außenabstand links 1rem
- `.ml-0.9` - Außenabstand links 0rem
- `.ml-0.8` - Außenabstand links 0rem
- `.ml-0.7` - Außenabstand links 0rem
- `.ml-0.6` - Außenabstand links 0rem
- `.ml-0.5` - Außenabstand links 0rem
- `.ml-0.4` - Außenabstand links 0rem
- `.ml-0.3` - Außenabstand links 0rem
- `.ml-0.2` - Außenabstand links 0.2rem
- `.ml-0.1` - Außenabstand links 0.1rem
- `.ml-0` - Außenabstand links 0rem
- `.ml-auto` - Außenabstand links auto

#### Margin Right

- `.first:mr-0` - Außenabstand rechts 0rem beim ersten Element
- `.hover:mr-100` - Außenabstand rechts 100 % beim Hover
- `.hover:mr-75` - Außenabstand rechts 75 % beim Hover
- `.hover:mr-50` - Außenabstand rechts 50 % beim Hover
- `.hover:mr-25` - Außenabstand rechts 25 % beim Hover
- `.hover:mr-5` - Außenabstand rechts 5rem beim Hover
- `.hover:mr-4.5` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-4` - Außenabstand rechts 4rem beim Hover
- `.hover:mr-3.5` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-3` - Außenabstand rechts 3rem beim Hover
- `.hover:mr-2.5` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-2` - Außenabstand rechts 2rem beim Hover
- `.hover:mr-1.9` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.8` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.7` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.6` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.5` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.4` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.3` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.2` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1.1` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-1` - Außenabstand rechts 1rem beim Hover
- `.hover:mr-0.9` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.8` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.7` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.6` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.5` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.4` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.3` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-0.2` - Außenabstand rechts 0.2rem beim Hover
- `.hover:mr-0.1` - Außenabstand rechts 0.1rem beim Hover
- `.hover:mr-0` - Außenabstand rechts 0rem beim Hover
- `.hover:mr-auto` - Außenabstand rechts auto beim Hover
- `.last:mr-0` - Außenabstand rechts 0rem beim letzten Element
- `.mr-100` - Außenabstand rechts 100 %
- `.mr-75` - Außenabstand rechts 75 %
- `.mr-50` - Außenabstand rechts 50 %
- `.mr-25` - Außenabstand rechts 25 %
- `.mr-5` - Außenabstand rechts 5rem
- `.mr-4.5` - Außenabstand rechts 0rem
- `.mr-4` - Außenabstand rechts 4rem
- `.mr-3.5` - Außenabstand rechts 0rem
- `.mr-3` - Außenabstand rechts 3rem
- `.mr-2.5` - Außenabstand rechts 0rem
- `.mr-2` - Außenabstand rechts 2rem
- `.mr-1.9` - Außenabstand rechts 0rem
- `.mr-1.8` - Außenabstand rechts 0rem
- `.mr-1.7` - Außenabstand rechts 0rem
- `.mr-1.6` - Außenabstand rechts 0rem
- `.mr-1.5` - Außenabstand rechts 0rem
- `.mr-1.4` - Außenabstand rechts 0rem
- `.mr-1.3` - Außenabstand rechts 0rem
- `.mr-1.2` - Außenabstand rechts 0rem
- `.mr-1.1` - Außenabstand rechts 0rem
- `.mr-1` - Außenabstand rechts 1rem
- `.mr-0.9` - Außenabstand rechts 0rem
- `.mr-0.8` - Außenabstand rechts 0rem
- `.mr-0.7` - Außenabstand rechts 0rem
- `.mr-0.6` - Außenabstand rechts 0rem
- `.mr-0.5` - Außenabstand rechts 0rem
- `.mr-0.4` - Außenabstand rechts 0rem
- `.mr-0.3` - Außenabstand rechts 0rem
- `.mr-0.2` - Außenabstand rechts 0.2rem
- `.mr-0.1` - Außenabstand rechts 0.1rem
- `.mr-0` - Außenabstand rechts 0rem
- `.mr-auto` - Außenabstand rechts auto

#### Margin Start

- `.hover:ms-2` - Margin Start 2rem beim Hover
- `.hover:ms-1.5` - Margin Start 1,5rem beim Schweben
- `.hover:ms-1` - Margin Start 1rem beim Hover
- `.hover:ms-0.5` - Margin Start 0,5rem beim Schweben
- `.hover:ms-0` - Margin Start 0rem beim Hover
- `.ms-2` - Margin Start 2rem
- `.ms-1.5` - Margin Start 1.5rem
- `.ms-1` - Margin Start 1rem
- `.ms-0.5` - Margin Start 0.5rem
- `.ms-0` - Margin-Start 0rem

#### Margin Top

- `.first:mt-0` - Außenabstand oben 0rem beim ersten Element
- `.hover:mt-100` - Außenabstand oben 100 % beim Hover
- `.hover:mt-75` - Außenabstand oben 75 % beim Hover
- `.hover:mt-50` - Außenabstand oben 50 % beim Hover
- `.hover:mt-25` - Außenabstand oben 25 % beim Hover
- `.hover:mt-5` - Außenabstand oben 5rem beim Hover
- `.hover:mt-4.5` - Außenabstand oben 0rem beim Hover
- `.hover:mt-4` - Außenabstand oben 4rem beim Hover
- `.hover:mt-3.5` - Außenabstand oben 0rem beim Hover
- `.hover:mt-3` - Außenabstand oben 3rem beim Hover
- `.hover:mt-2.5` - Außenabstand oben 0rem beim Hover
- `.hover:mt-2` - Außenabstand oben 2rem beim Hover
- `.hover:mt-1.9` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.8` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.7` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.6` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.5` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.4` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.3` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.2` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1.1` - Außenabstand oben 0rem beim Hover
- `.hover:mt-1` - Außenabstand oben 1rem beim Hover
- `.hover:mt-0.9` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.8` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.7` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.6` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.5` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.4` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.3` - Außenabstand oben 0rem beim Hover
- `.hover:mt-0.2` - Außenabstand oben 0.2rem beim Hover
- `.hover:mt-0.1` - Außenabstand oben 0.1rem beim Hover
- `.hover:mt-0` - Außenabstand oben 0rem beim Hover
- `.hover:mt-auto` - Außenabstand oben auto beim Hover
- `.last:mt-0` - Außenabstand oben 0rem beim letzten Element
- `.mt-100` - Außenabstand oben 100 %
- `.mt-75` - Außenabstand oben 75 %
- `.mt-50` - Außenabstand oben 50 %
- `.mt-25` - Außenabstand oben 25 %
- `.mt-5` - Außenabstand oben 5rem
- `.mt-4.5` - Außenabstand oben 0rem
- `.mt-4` - Außenabstand oben 4rem
- `.mt-3.5` - Außenabstand oben 0rem
- `.mt-3` - Außenabstand oben 3rem
- `.mt-2.5` - Außenabstand oben 0rem
- `.mt-2` - Außenabstand oben 2rem
- `.mt-1.9` - Außenabstand oben 0rem
- `.mt-1.8` - Außenabstand oben 0rem
- `.mt-1.7` - Außenabstand oben 0rem
- `.mt-1.6` - Außenabstand oben 0rem
- `.mt-1.5` - Außenabstand oben 0rem
- `.mt-1.4` - Außenabstand oben 0rem
- `.mt-1.3` - Außenabstand oben 0rem
- `.mt-1.2` - Außenabstand oben 0rem
- `.mt-1.1` - Außenabstand oben 0rem
- `.mt-1` - Außenabstand oben 1rem
- `.mt-0.9` - Außenabstand oben 0rem
- `.mt-0.8` - Außenabstand oben 0rem
- `.mt-0.7` - Außenabstand oben 0rem
- `.mt-0.6` - Außenabstand oben 0rem
- `.mt-0.5` - Außenabstand oben 0rem
- `.mt-0.4` - Außenabstand oben 0rem
- `.mt-0.3` - Außenabstand oben 0rem
- `.mt-0.2` - Außenabstand oben 0.2rem
- `.mt-0.1` - Außenabstand oben 0.1rem
- `.mt-0` - Außenabstand oben 0rem
- `.mt-auto` - Außenabstand oben auto

#### Margin X-Axis

- `.hover:mx-100` - Außenabstand X-Achse 100 % beim Hover
- `.hover:mx-75` - Außenabstand X-Achse 75 % beim Hover
- `.hover:mx-50` - Außenabstand X-Achse 50 % beim Hover
- `.hover:mx-25` - Außenabstand X-Achse 25 % beim Hover
- `.hover:mx-5` - Außenabstand X-Achse 5rem beim Hover
- `.hover:mx-4.5` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-4` - Außenabstand X-Achse 4rem beim Hover
- `.hover:mx-3.5` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-3` - Außenabstand X-Achse 3rem beim Hover
- `.hover:mx-2.5` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-2` - Außenabstand X-Achse 2rem beim Hover
- `.hover:mx-1.9` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.8` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.7` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.6` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.5` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.4` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.3` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.2` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1.1` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-1` - Außenabstand X-Achse 1rem beim Hover
- `.hover:mx-0.9` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.8` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.7` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.6` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.5` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.4` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.3` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-0.2` - Außenabstand X-Achse 0.2rem beim Hover
- `.hover:mx-0.1` - Außenabstand X-Achse 0.1rem beim Hover
- `.hover:mx-0` - Außenabstand X-Achse 0rem beim Hover
- `.hover:mx-auto` - Außenabstand X-Achse auto beim Hover
- `.mx-100` - Außenabstand X-Achse 100 %
- `.mx-75` - Außenabstand X-Achse 75 %
- `.mx-50` - Außenabstand X-Achse 50 %
- `.mx-25` - Außenabstand X-Achse 25 %
- `.mx-5` - Außenabstand X-Achse 5rem
- `.mx-4.5` - Außenabstand X-Achse 0rem
- `.mx-4` - Außenabstand X-Achse 4rem
- `.mx-3.5` - Außenabstand X-Achse 0rem
- `.mx-3` - Außenabstand X-Achse 3rem
- `.mx-2.5` - Außenabstand X-Achse 0rem
- `.mx-2` - Außenabstand X-Achse 2rem
- `.mx-1.9` - Außenabstand X-Achse 0rem
- `.mx-1.8` - Außenabstand X-Achse 0rem
- `.mx-1.7` - Außenabstand X-Achse 0rem
- `.mx-1.6` - Außenabstand X-Achse 0rem
- `.mx-1.5` - Außenabstand X-Achse 0rem
- `.mx-1.4` - Außenabstand X-Achse 0rem
- `.mx-1.3` - Außenabstand X-Achse 0rem
- `.mx-1.2` - Außenabstand X-Achse 0rem
- `.mx-1.1` - Außenabstand X-Achse 0rem
- `.mx-1` - Außenabstand X-Achse 1rem
- `.mx-0.9` - Außenabstand X-Achse 0rem
- `.mx-0.8` - Außenabstand X-Achse 0rem
- `.mx-0.7` - Außenabstand X-Achse 0rem
- `.mx-0.6` - Außenabstand X-Achse 0rem
- `.mx-0.5` - Außenabstand X-Achse 0rem
- `.mx-0.4` - Außenabstand X-Achse 0rem
- `.mx-0.3` - Außenabstand X-Achse 0rem
- `.mx-0.2` - Außenabstand X-Achse 0.2rem
- `.mx-0.1` - Außenabstand X-Achse 0.1rem
- `.mx-0` - Außenabstand X-Achse 0rem
- `.mx-auto` - Außenabstand X-Achse auto

#### Margin Y-Axis

- `.hover:my-100` - Außenabstand Y-Achse 100 % beim Hover
- `.hover:my-75` - Außenabstand Y-Achse 75 % beim Hover
- `.hover:my-50` - Außenabstand Y-Achse 50 % beim Hover
- `.hover:my-25` - Außenabstand Y-Achse 25 % beim Hover
- `.hover:my-5` - Außenabstand Y-Achse 5rem beim Hover
- `.hover:my-4.5` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-4` - Außenabstand Y-Achse 4rem beim Hover
- `.hover:my-3.5` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-3` - Außenabstand Y-Achse 3rem beim Hover
- `.hover:my-2.5` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-2` - Außenabstand Y-Achse 2rem beim Hover
- `.hover:my-1.9` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.8` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.7` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.6` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.5` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.4` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.3` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.2` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1.1` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-1` - Außenabstand Y-Achse 1rem beim Hover
- `.hover:my-0.9` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.8` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.7` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.6` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.5` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.4` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.3` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-0.2` - Margin Y-Achse 0,2rem beim Schweben
- `.hover:my-0.1` - Margin Y-Achse 0,1rem beim Schweben
- `.hover:my-0` - Außenabstand Y-Achse 0rem beim Hover
- `.hover:my-auto` - Außenabstand Y-Achse auto beim Hover
- `.my-100` - Außenabstand Y-Achse 100 %
- `.my-75` - Außenabstand Y-Achse 75 %
- `.my-50` - Außenabstand Y-Achse 50 %
- `.my-25` - Außenabstand Y-Achse 25 %
- `.my-5` - Außenabstand Y-Achse 5rem
- `.my-4.5` - Außenabstand Y-Achse 0rem
- `.my-4` - Außenabstand Y-Achse 4rem
- `.my-3.5` - Außenabstand Y-Achse 0rem
- `.my-3` - Außenabstand Y-Achse 3rem
- `.my-2.5` - Außenabstand Y-Achse 0rem
- `.my-2` - Außenabstand Y-Achse 2rem
- `.my-1.9` - Außenabstand Y-Achse 0rem
- `.my-1.8` - Außenabstand Y-Achse 0rem
- `.my-1.7` - Außenabstand Y-Achse 0rem
- `.my-1.6` - Außenabstand Y-Achse 0rem
- `.my-1.5` - Außenabstand Y-Achse 0rem
- `.my-1.4` - Außenabstand Y-Achse 0rem
- `.my-1.3` - Außenabstand Y-Achse 0rem
- `.my-1.2` - Außenabstand Y-Achse 0rem
- `.my-1.1` - Außenabstand Y-Achse 0rem
- `.my-1` - Außenabstand Y-Achse 1rem
- `.my-0.9` - Außenabstand Y-Achse 0rem
- `.my-0.8` - Außenabstand Y-Achse 0rem
- `.my-0.7` - Außenabstand Y-Achse 0rem
- `.my-0.6` - Außenabstand Y-Achse 0rem
- `.my-0.5` - Außenabstand Y-Achse 0rem
- `.my-0.4` - Außenabstand Y-Achse 0rem
- `.my-0.3` - Außenabstand Y-Achse 0rem
- `.my-0.2` - Außenabstand Y-Achse 0.2rem
- `.my-0.1` - Außenabstand Y-Achse 0.1rem
- `.my-0` - Außenabstand Y-Achse 0rem
- `.my-auto` - Außenabstand Y-Achse auto

### Padding

#### Padding All

- `.first:p-0` - Zuerst alle 0rem auffüllen
- `.hover:p-5` - Alle 5rem beim Schweben auffüllen
- `.hover:p-4.5` - Alle 0rem beim Schweben auffüllen
- `.hover:p-4` - Alle 4rem beim Schweben auffüllen
- `.hover:p-3.5` - Alle 0rem beim Schweben auffüllen
- `.hover:p-3` - Alle 3rem beim Schweben auffüllen
- `.hover:p-2.5` - Alle 0rem beim Schweben auffüllen
- `.hover:p-2` - Alle 2rem beim Schweben auffüllen
- `.hover:p-1.9` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.8` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.7` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.6` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.5` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.4` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.3` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.2` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1.1` - Alle 0rem beim Schweben auffüllen
- `.hover:p-1` - Alle 1rem beim Schweben auffüllen
- `.hover:p-0.9` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.8` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.7` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.6` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.5` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.4` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.3` - Alle 0rem beim Schweben auffüllen
- `.hover:p-0.2` - Alle 0,2rem beim Schweben auffüllen
- `.hover:p-0.1` - Alle 0,1rem auffüllen beim Schweben
- `.hover:p-0` - Alle 0rem beim Schweben auffüllen
- `.last:p-0` - Füllen Sie alle 0rem zuletzt auf
- `.p-5` - Polsterung Alle 5rem
- `.p-4.5` - Polsterung Alle 0rem
- `.p-4` - Polsterung Alle 4rem
- `.p-3.5` - Polsterung Alle 0rem
- `.p-3` - Polsterung Alle 3rem
- `.p-2.5` - Polsterung Alle 0rem
- `.p-2` - Polsterung Alle 2rem
- `.p-1.9` - Polsterung Alle 0rem
- `.p-1.8` - Polsterung Alle 0rem
- `.p-1.7` - Polsterung Alle 0rem
- `.p-1.6` - Polsterung Alle 0rem
- `.p-1.5` - Polsterung Alle 0rem
- `.p-1.4` - Polsterung Alle 0rem
- `.p-1.3` - Polsterung Alle 0rem
- `.p-1.2` - Polsterung Alle 0rem
- `.p-1.1` - Polsterung Alle 0rem
- `.p-1` - Polsterung Alle 1rem
- `.p-0.9` - Polsterung Alle 0rem
- `.p-0.8` - Polsterung Alle 0rem
- `.p-0.7` - Polsterung Alle 0rem
- `.p-0.6` - Polsterung Alle 0rem
- `.p-0.5` - Polsterung Alle 0rem
- `.p-0.4` - Polsterung Alle 0rem
- `.p-0.3` - Polsterung Alle 0rem
- `.p-0.2` - Polsterung Alle 0,2rem
- `.p-0.1` - Polsterung Alle 0,1rem
- `.p-0` - Polsterung Alle 0rem

#### Padding Bottom

- `.first:pb-0` - Polsterung unten 0rem beim ersten Element
- `.hover:pb-100` - Polsterung unten 100 % beim Hover
- `.hover:pb-75` - Polsterung unten 75 % beim Hover
- `.hover:pb-50` - Polsterung unten 50 % beim Hover
- `.hover:pb-25` - Polsterung unten 25 % beim Hover
- `.hover:pb-5` - Polsterung unten 5rem beim Schweben
- `.hover:pb-4.5` - Polsterung unten 0rem beim Schweben
- `.hover:pb-4` - Polsterung unten 4rem beim Schweben
- `.hover:pb-3.5` - Polsterung unten 0rem beim Schweben
- `.hover:pb-3` - Polsterung unten 3rem beim Schweben
- `.hover:pb-2.5` - Polsterung unten 0rem beim Schweben
- `.hover:pb-2` - Polsterung unten 2rem beim Schweben
- `.hover:pb-1.9` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.8` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.7` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.6` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.5` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.4` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.3` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.2` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1.1` - Polsterung unten 0rem beim Schweben
- `.hover:pb-1` - Polsterung unten 1rem beim Schweben
- `.hover:pb-0.9` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.8` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.7` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.6` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.5` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.4` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.3` - Polsterung unten 0rem beim Schweben
- `.hover:pb-0.2` - Polsterung unten 0,2rem beim Schweben
- `.hover:pb-0.1` - Polsterung unten 0,1rem beim Schweben
- `.hover:pb-0` - Polsterung unten 0rem beim Schweben
- `.last:pb-0` - Polsterung unten 0rem am letzten
- `.pb-100` - Polsterung unten 100 %
- `.pb-75` - Polsterung unten 75 %
- `.pb-50` - Polsterung unten 50 %
- `.pb-25` - Polsterung unten 25 %
- `.pb-5` - Polsterung unten 5rem
- `.pb-4.5` - Polsterung unten 0rem
- `.pb-4` - Polsterung unten 4rem
- `.pb-3.5` - Polsterung unten 0rem
- `.pb-3` - Polsterung unten 3rem
- `.pb-2.5` - Polsterung unten 0rem
- `.pb-2` - Polsterung unten 2rem
- `.pb-1.9` - Polsterung unten 0rem
- `.pb-1.8` - Polsterung unten 0rem
- `.pb-1.7` - Polsterung unten 0rem
- `.pb-1.6` - Polsterung unten 0rem
- `.pb-1.5` - Polsterung unten 0rem
- `.pb-1.4` - Polsterung unten 0rem
- `.pb-1.3` - Polsterung unten 0rem
- `.pb-1.2` - Polsterung unten 0rem
- `.pb-1.1` - Polsterung unten 0rem
- `.pb-1` - Polsterung unten 1rem
- `.pb-0.9` - Polsterung unten 0rem
- `.pb-0.8` - Polsterung unten 0rem
- `.pb-0.7` - Polsterung unten 0rem
- `.pb-0.6` - Polsterung unten 0rem
- `.pb-0.5` - Polsterung unten 0rem
- `.pb-0.4` - Polsterung unten 0rem
- `.pb-0.3` - Polsterung unten 0rem
- `.pb-0.2` - Polsterung unten 0,2rem
- `.pb-0.1` - Polsterung unten 0,1rem
- `.pb-0` - Polsterung unten 0rem

#### Padding Left

- `.first:pl-0` - Polsterung links 0rem beim ersten Element
- `.hover:pl-5` - Polsterung links 5rem beim Schweben
- `.hover:pl-4.5` - Polsterung links 0rem beim Schweben
- `.hover:pl-4` - Polsterung links 4rem beim Schweben
- `.hover:pl-3.5` - Polsterung links 0rem beim Schweben
- `.hover:pl-3` - Polsterung links 3rem beim Schweben
- `.hover:pl-2.5` - Polsterung links 0rem beim Schweben
- `.hover:pl-2` - Polsterung links 2rem beim Schweben
- `.hover:pl-1.9` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.8` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.7` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.6` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.5` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.4` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.3` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.2` - Polsterung links 0rem beim Schweben
- `.hover:pl-1.1` - Polsterung links 0rem beim Schweben
- `.hover:pl-1` - Polsterung links 1rem beim Schweben
- `.hover:pl-0.9` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.8` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.7` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.6` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.5` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.4` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.3` - Polsterung links 0rem beim Schweben
- `.hover:pl-0.2` - Polsterung links 0,2rem beim Schweben
- `.hover:pl-0.1` - Polsterung links 0,1rem beim Schweben
- `.hover:pl-0` - Polsterung links 0rem beim Schweben
- `.last:pl-0` - Polsterung links 0rem zuletzt
- `.pl-5` - Polsterung links 5rem
- `.pl-4.5` - Polsterung links 0rem
- `.pl-4` - Polsterung links 4rem
- `.pl-3.5` - Polsterung links 0rem
- `.pl-3` - Polsterung links 3rem
- `.pl-2.5` - Polsterung links 0rem
- `.pl-2` - Polsterung links 2rem
- `.pl-1.9` - Polsterung links 0rem
- `.pl-1.8` - Polsterung links 0rem
- `.pl-1.7` - Polsterung links 0rem
- `.pl-1.6` - Polsterung links 0rem
- `.pl-1.5` - Polsterung links 0rem
- `.pl-1.4` - Polsterung links 0rem
- `.pl-1.3` - Polsterung links 0rem
- `.pl-1.2` - Polsterung links 0rem
- `.pl-1.1` - Polsterung links 0rem
- `.pl-1` - Polsterung links 1rem
- `.pl-0.9` - Polsterung links 0rem
- `.pl-0.8` - Polsterung links 0rem
- `.pl-0.7` - Polsterung links 0rem
- `.pl-0.6` - Polsterung links 0rem
- `.pl-0.5` - Polsterung links 0rem
- `.pl-0.4` - Polsterung links 0rem
- `.pl-0.3` - Polsterung links 0rem
- `.pl-0.2` - Polsterung links 0,2rem
- `.pl-0.1` - Polsterung links 0,1rem
- `.pl-0` - Polsterung links 0rem

#### Padding Right

- `.first:pr-0` - Polsterung rechts 0rem beim ersten Element
- `.hover:pr-100` - Polsterung rechts 100 % beim Hover
- `.hover:pr-75` - Polsterung rechts 75 % beim Hover
- `.hover:pr-50` - Polsterung rechts 50 % beim Hover
- `.hover:pr-25` - Polsterung rechts 25 % beim Hover
- `.hover:pr-5` - Polsterung rechts 5rem beim Hover
- `.hover:pr-4.5` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-4` - Polsterung rechts 4rem beim Hover
- `.hover:pr-3.5` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-3` - Polsterung rechts 3rem beim Schweben
- `.hover:pr-2.5` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-2` - Polsterung rechts 2rem beim Schweben
- `.hover:pr-1.9` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.8` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.7` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.6` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.5` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.4` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.3` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.2` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1.1` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-1` - Polsterung rechts 1rem beim Schweben
- `.hover:pr-0.9` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.8` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.7` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.6` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.5` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.4` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.3` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-0.2` - Polsterung nach rechts 0,2rem beim Schweben
- `.hover:pr-0.1` - Polsterung nach rechts 0,1rem beim Schweben
- `.hover:pr-0` - Polsterung nach rechts 0rem beim Schweben
- `.last:pr-0` - Polsterung Rechts 0rem zum Schluss
- `.pr-100` - Polsterung rechts 100 %
- `.pr-75` - Polsterung rechts 75 %
- `.pr-50` - Polsterung rechts 50 %
- `.pr-25` - Polsterung rechts 25 %
- `.pr-5` - Polsterung rechts 5rem
- `.pr-4.5` - Polsterung rechts 0rem
- `.pr-4` - Polsterung rechts 4rem
- `.pr-3.5` - Polsterung rechts 0rem
- `.pr-3` - Polsterung rechts 3rem
- `.pr-2.5` - Polsterung rechts 0rem
- `.pr-2` - Polsterung rechts 2rem
- `.pr-1.9` - Polsterung rechts 0rem
- `.pr-1.8` - Polsterung rechts 0rem
- `.pr-1.7` - Polsterung rechts 0rem
- `.pr-1.6` - Polsterung rechts 0rem
- `.pr-1.5` - Polsterung rechts 0rem
- `.pr-1.4` - Polsterung rechts 0rem
- `.pr-1.3` - Polsterung rechts 0rem
- `.pr-1.2` - Polsterung rechts 0rem
- `.pr-1.1` - Polsterung rechts 0rem
- `.pr-1` - Polsterung rechts 1rem
- `.pr-0.9` - Polsterung rechts 0rem
- `.pr-0.8` - Polsterung rechts 0rem
- `.pr-0.7` - Polsterung rechts 0rem
- `.pr-0.6` - Polsterung rechts 0rem
- `.pr-0.5` - Polsterung rechts 0rem
- `.pr-0.4` - Polsterung rechts 0rem
- `.pr-0.3` - Polsterung rechts 0rem
- `.pr-0.2` - Polsterung rechts 0,2rem
- `.pr-0.1` - Polsterung rechts 0,1rem
- `.pr-0` - Polsterung rechts 0rem

#### Padding Top

- `.first:pt-0` - Polsterung oben 0rem beim ersten Element
- `.hover:pt-100` - Polsterung oben 100 % beim Hover
- `.hover:pt-75` - Polsterung oben 75 % beim Hover
- `.hover:pt-50` - Polsterung oben 50 % beim Hover
- `.hover:pt-25` - Polsterung oben 25 % beim Hover
- `.hover:pt-5` - Polsterung oben 5rem beim Hover
- `.hover:pt-4.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-4` - Polsterung oben 4rem beim Hover
- `.hover:pt-3.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-3` - Polsterung oben 3rem beim Hover
- `.hover:pt-2.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-2` - Polsterung oben 2rem beim Hover
- `.hover:pt-1.9` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.8` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.7` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.6` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.4` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.3` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.2` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.1` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1` - Polsterung oben 1rem beim Hover
- `.hover:pt-0.9` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.8` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.7` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.6` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.4` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.3` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.2` - Polsterung oben 0.2rem beim Hover
- `.hover:pt-0.1` - Polsterung oben 0,1rem beim Schweben
- `.hover:pt-0` - Polsterung oben 0rem beim Schweben
- `.last:pt-0` - Polsterung oben 0rem am letzten
- `.pt-100` - Polsterung oben 100 %
- `.pt-75` - Polsterung oben 75 %
- `.pt-50` - Polsterung oben 50 %
- `.pt-25` - Polsterung oben 25 %
- `.pt-5` - Polsterung oben 5rem
- `.pt-4.5` - Polsterung oben 0rem
- `.pt-4` - Polsterung oben 4rem
- `.pt-3.5` - Polsterung oben 0rem
- `.pt-3` - Polsterung oben 3rem
- `.pt-2.5` - Polsterung oben 0rem
- `.pt-2` - Polsterung oben 2rem
- `.pt-1.9` - Polsterung oben 0rem
- `.pt-1.8` - Polsterung oben 0rem
- `.pt-1.7` - Polsterung oben 0rem
- `.pt-1.6` - Polsterung oben 0rem
- `.pt-1.5` - Polsterung oben 0rem
- `.pt-1.4` - Polsterung oben 0rem
- `.pt-1.3` - Polsterung oben 0rem
- `.pt-1.2` - Polsterung oben 0rem
- `.pt-1.1` - Polsterung oben 0rem
- `.pt-1` - Polsterung oben 1rem
- `.pt-0.9` - Polsterung oben 0rem
- `.pt-0.8` - Polsterung oben 0rem
- `.pt-0.7` - Polsterung oben 0rem
- `.pt-0.6` - Polsterung oben 0rem
- `.pt-0.5` - Polsterung oben 0rem
- `.pt-0.4` - Polsterung oben 0rem
- `.pt-0.3` - Polsterung oben 0rem
- `.pt-0.2` - Polsterung oben 0,2rem
- `.pt-0.1` - Polsterung oben 0,1rem
- `.pt-0` - Polsterung oben 0rem

#### Padding X-Axis

- `.hover:px-100` - Polsterung der X-Achse 100 % beim Schweben
- `.hover:px-75` - Polsterung der X-Achse 75 % beim Schweben
- `.hover:px-50` - Polsterung der X-Achse 50 % beim Schweben
- `.hover:px-25` - Polsterung der X-Achse 25 % beim Schweben
- `.hover:px-5` - Polsterung der X-Achse 5rem beim Schweben
- `.hover:px-4.5` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-4` - Polsterung der X-Achse 4rem beim Schweben
- `.hover:px-3.5` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-3` - Polsterung der X-Achse 3rem beim Schweben
- `.hover:px-2.5` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-2` - Polsterung der X-Achse 2rem beim Schweben
- `.hover:px-1.9` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.8` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.7` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.6` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.5` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.4` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.3` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.2` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1.1` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-1` - Polsterung der X-Achse 1rem beim Schweben
- `.hover:px-0.9` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.8` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.7` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.6` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.5` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.4` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.3` - Polsterung der X-Achse 0rem beim Schweben
- `.hover:px-0.2` - Polsterung der X-Achse 0,2rem beim Schweben
- `.hover:px-0.1` - Polsterung der X-Achse 0,1rem beim Schweben
- `.hover:px-0` - Polsterung der X-Achse 0rem beim Schweben
- `.px-100` - Polsterung X-Achse 100 %
- `.px-75` - Polsterung X-Achse 75 %
- `.px-50` - Polsterung X-Achse 50 %
- `.px-25` - Polsterung X-Achse 25 %
- `.px-5` - Polsterung X-Achse 5rem
- `.px-4.5` - Polsterung X-Achse 0rem
- `.px-4` - Polsterung X-Achse 4rem
- `.px-3.5` - Polsterung X-Achse 0rem
- `.px-3` - Polsterung X-Achse 3rem
- `.px-2.5` - Polsterung X-Achse 0rem
- `.px-2` - Polsterung X-Achse 2rem
- `.px-1.9` - Polsterung X-Achse 0rem
- `.px-1.8` - Polsterung X-Achse 0rem
- `.px-1.7` - Polsterung X-Achse 0rem
- `.px-1.6` - Polsterung X-Achse 0rem
- `.px-1.5` - Polsterung X-Achse 0rem
- `.px-1.4` - Polsterung X-Achse 0rem
- `.px-1.3` - Polsterung X-Achse 0rem
- `.px-1.2` - Polsterung X-Achse 0rem
- `.px-1.1` - Polsterung X-Achse 0rem
- `.px-1` - Polsterung X-Achse 1rem
- `.px-0.9` - Polsterung X-Achse 0rem
- `.px-0.8` - Polsterung X-Achse 0rem
- `.px-0.7` - Polsterung X-Achse 0rem
- `.px-0.6` - Polsterung X-Achse 0rem
- `.px-0.5` - Polsterung X-Achse 0rem
- `.px-0.4` - Polsterung X-Achse 0rem
- `.px-0.3` - Polsterung X-Achse 0rem
- `.px-0.2` - Polsterung X-Achse 0,2rem
- `.px-0.1` - Polsterung X-Achse 0,1rem
- `.px-0` - Polsterung X-Achse 0rem

#### Padding Y-Axis

- `.hover:py-100` - Polsterung der Y-Achse 100 % beim Schweben
- `.hover:py-75` - Polsterung der Y-Achse 75 % beim Schweben
- `.hover:py-50` - Polsterung der Y-Achse 50 % beim Schweben
- `.hover:py-25` - Polsterung der Y-Achse 25 % beim Schweben
- `.hover:py-5` - Polsterung der Y-Achse 5rem beim Schweben
- `.hover:py-4.5` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-4` - Polsterung der Y-Achse 4rem beim Schweben
- `.hover:py-3.5` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-3` - Polsterung der Y-Achse 3rem beim Schweben
- `.hover:py-2.5` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-2` - Polsterung der Y-Achse 2rem beim Schweben
- `.hover:py-1.9` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.8` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.7` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.6` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.5` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.4` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.3` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.2` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1.1` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-1` - Polsterung der Y-Achse 1rem beim Schweben
- `.hover:py-0.9` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.8` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.7` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.6` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.5` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.4` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.3` - Polsterung der Y-Achse 0rem beim Schweben
- `.hover:py-0.2` - Polsterung der Y-Achse 0,2rem beim Schweben
- `.hover:py-0.1` - Polsterung der Y-Achse 0,1rem beim Schweben
- `.hover:py-0` - Polsterung der Y-Achse 0rem beim Schweben
- `.py-100` - Polsterung Y-Achse 100 %
- `.py-75` - Polsterung Y-Achse 75 %
- `.py-50` - Polsterung Y-Achse 50 %
- `.py-25` - Polsterung Y-Achse 25 %
- `.py-5` - Polsterung Y-Achse 5rem
- `.py-4.5` - Polsterung Y-Achse 0rem
- `.py-4` - Polsterung Y-Achse 4rem
- `.py-3.5` - Polsterung Y-Achse 0rem
- `.py-3` - Polsterung Y-Achse 3rem
- `.py-2.5` - Polsterung Y-Achse 0rem
- `.py-2` - Polsterung Y-Achse 2rem
- `.py-1.9` - Polsterung Y-Achse 0rem
- `.py-1.8` - Polsterung Y-Achse 0rem
- `.py-1.7` - Polsterung Y-Achse 0rem
- `.py-1.6` - Polsterung Y-Achse 0rem
- `.py-1.5` - Polsterung Y-Achse 0rem
- `.py-1.4` - Polsterung Y-Achse 0rem
- `.py-1.3` - Polsterung Y-Achse 0rem
- `.py-1.2` - Polsterung Y-Achse 0rem
- `.py-1.1` - Polsterung Y-Achse 0rem
- `.py-1` - Polsterung Y-Achse 1rem
- `.py-0.9` - Polsterung Y-Achse 0rem
- `.py-0.8` - Polsterung Y-Achse 0rem
- `.py-0.7` - Polsterung Y-Achse 0rem
- `.py-0.6` - Polsterung Y-Achse 0rem
- `.py-0.5` - Polsterung Y-Achse 0rem
- `.py-0.4` - Polsterung Y-Achse 0rem
- `.py-0.3` - Polsterung Y-Achse 0rem
- `.py-0.2` - Polsterung Y-Achse 0,2rem
- `.py-0.1` - Polsterung Y-Achse 0,1rem
- `.py-0` - Polsterung Y-Achse 0rem

## Sizing

### Width

- `.hover:w-100` - Breite 100 % beim Schweben
- `.hover:w-95` - Breite 95 % beim Schweben
- `.hover:w-90` - Breite 90 % beim Schweben
- `.hover:w-85` - Breite 85 % beim Schweben
- `.hover:w-80` - Breite 80 % beim Schweben
- `.hover:w-75` - Breite 75 % beim Schweben
- `.hover:w-70` - Breite 70 % beim Schweben
- `.hover:w-65` - Breite 65 % beim Schweben
- `.hover:w-60` - Breite 60 % beim Schweben
- `.hover:w-55` - Breite 55 % beim Schweben
- `.hover:w-50` - Breite 50 % beim Schweben
- `.hover:w-45` - Breite 45 % beim Schweben
- `.hover:w-40` - Breite 40 % beim Schweben
- `.hover:w-35` - Breite 35 % beim Schweben
- `.hover:w-30` - Breite 30 % beim Schweben
- `.hover:w-25` - Breite 25 % beim Schweben
- `.hover:w-20` - Breite 20 % beim Schweben
- `.hover:w-15` - Breite 15 % beim Schweben
- `.hover:w-10` - Breite 10 % beim Schweben
- `.hover:w-5` - Breite 5 % beim Schweben
- `.hover:w-auto` - Breite automatisch % beim Hover
- `.w-100` - Breite 100 %
- `.w-95` - Breite 95 %
- `.w-90` - Breite 90 %
- `.w-85` - Breite 85 %
- `.w-80` - Breite 80 %
- `.w-75` - Breite 75 %
- `.w-70` - Breite 70 %
- `.w-65` - Breite 65 %
- `.w-60` - Breite 60 %
- `.w-55` - Breite 55 %
- `.w-50` - Breite 50 %
- `.w-45` - Breite 45 %
- `.w-40` - Breite 40 %
- `.w-35` - Breite 35 %
- `.w-30` - Breite 30 %
- `.w-25` - Breite 25 %
- `.w-20` - Breite 20 %
- `.w-15` - Breite 15 %
- `.w-10` - Breite 10 %
- `.w-5` - Breite 5 %
- `.w-auto` - Breite automatisch %

##### Width - Mobile (<= 480px)

- `.hover:mobile:w-100` - Breite 100 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-95` - Breite 95 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-90` - Breite 90 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-85` - Breite 85 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-80` - Breite 80 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-75` - Breite 75 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-70` - Breite 70 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-65` - Breite 65 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-60` - Breite 60 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-55` - Breite 55 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-50` - Breite 50 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-45` - Breite 45 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-40` - Breite 40 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-35` - Breite 35 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-30` - Breite 30 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-25` - Breite 25 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-20` - Breite 20 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-15` - Breite 15 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-10` - Breite 10 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-5` - Breite 5 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-auto` - Breite automatisch % beim Hover auf Mobilgeräten
- `.mobile:w-100` - Breite 100 % auf Mobilgeräten
- `.mobile:w-95` - Breite 95 % auf Mobilgeräten
- `.mobile:w-90` - Breite 90 % auf Mobilgeräten
- `.mobile:w-85` - Breite 85 % auf Mobilgeräten
- `.mobile:w-80` - Breite 80 % auf Mobilgeräten
- `.mobile:w-75` - Breite 75 % auf Mobilgeräten
- `.mobile:w-70` - Breite 70 % auf Mobilgeräten
- `.mobile:w-65` - Breite 65 % auf Mobilgeräten
- `.mobile:w-60` - Breite 60 % auf Mobilgeräten
- `.mobile:w-55` - Breite 55 % auf Mobilgeräten
- `.mobile:w-50` - Breite 50 % auf Mobilgeräten
- `.mobile:w-45` - Breite 45 % auf Mobilgeräten
- `.mobile:w-40` - Breite 40 % auf Mobilgeräten
- `.mobile:w-35` - Breite 35 % auf Mobilgeräten
- `.mobile:w-30` - Breite 30 % auf Mobilgeräten
- `.mobile:w-25` - Breite 25 % auf Mobilgeräten
- `.mobile:w-20` - Breite 20 % auf Mobilgeräten
- `.mobile:w-15` - Breite 15 % auf Mobilgeräten
- `.mobile:w-10` - Breite 10 % auf Mobilgeräten
- `.mobile:w-5` - Breite 5 % auf Mobilgeräten
- `.mobile:w-auto` - Breite automatisch % auf Mobilgeräten

##### Width - Tablet (480px - 768px)

- `.hover:tablet:w-100` - Breite 100 % beim Schweben auf dem Tablet
- `.hover:tablet:w-95` - Breite 95 % beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:w-90` - Breite 90 % beim Schweben auf dem Tablet
- `.hover:tablet:w-85` - Breite 85 % beim Schweben auf dem Tablet
- `.hover:tablet:w-80` - Breite 80 % beim Schweben auf dem Tablet
- `.hover:tablet:w-75` - Breite 75 % beim Schweben auf dem Tablet
- `.hover:tablet:w-70` - Breite 70 % beim Schweben auf dem Tablet
- `.hover:tablet:w-65` - Breite 65 % beim Schweben auf dem Tablet
- `.hover:tablet:w-60` - Breite 60 % beim Schweben auf dem Tablet
- `.hover:tablet:w-55` - Breite 55 % beim Schweben auf dem Tablet
- `.hover:tablet:w-50` - Breite 50 % beim Schweben auf dem Tablet
- `.hover:tablet:w-45` - Breite 45 % beim Schweben auf dem Tablet
- `.hover:tablet:w-40` - Breite 40 % beim Schweben auf dem Tablet
- `.hover:tablet:w-35` - Breite 35 % beim Schweben auf dem Tablet
- `.hover:tablet:w-30` - Breite 30 % beim Hovern auf dem Tablet
- `.hover:tablet:w-25` - Breite 25 % beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:w-20` - Breite 20 % beim Hovern auf dem Tablet
- `.hover:tablet:w-15` - Breite 15 % beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:w-10` - Breite 10 % beim Hovern auf dem Tablet
- `.hover:tablet:w-5` - Breite 5 % beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:w-auto` - Breite automatisch % beim Bewegen des Mauszeigers auf dem Tablet
- `.tablet:w-100` - Breite 100 % auf dem Tablet
- `.tablet:w-95` - Breite 95 % auf dem Tablet
- `.tablet:w-90` - Breite 90 % auf dem Tablet
- `.tablet:w-85` - Breite 85 % auf dem Tablet
- `.tablet:w-80` - Breite 80 % auf dem Tablet
- `.tablet:w-75` - Breite 75 % auf dem Tablet
- `.tablet:w-70` - Breite 70 % auf dem Tablet
- `.tablet:w-65` - Breite 65 % auf dem Tablet
- `.tablet:w-60` - Breite 60 % auf dem Tablet
- `.tablet:w-55` - Breite 55 % auf dem Tablet
- `.tablet:w-50` - Breite 50 % auf dem Tablet
- `.tablet:w-45` - Breite 45 % auf dem Tablet
- `.tablet:w-40` - Breite 40 % auf dem Tablet
- `.tablet:w-35` - Breite 35 % auf dem Tablet
- `.tablet:w-30` - Breite 30 % auf dem Tablet
- `.tablet:w-25` - Breite 25 % auf dem Tablet
- `.tablet:w-20` - Breite 20 % auf dem Tablet
- `.tablet:w-15` - Breite 15 % auf dem Tablet
- `.tablet:w-10` - Breite 10 % auf dem Tablet
- `.tablet:w-5` - Breite 5 % auf dem Tablet
- `.tablet:w-auto` - Breite automatisch % auf dem Tablet

##### Width - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:w-100` - Breite 100 % beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:w-95` - Breite 95 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-90` - Breite 90 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-85` - Breite 85 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-80` - Breite 80 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-75` - Breite 75 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-70` - Breite 70 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-65` - Breite 65 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-60` - Breite 60 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-55` - Breite 55 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-50` - Breite 50 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-45` - Breite 45 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-40` - Breite 40 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-35` - Breite 35 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-30` - Breite 30 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-25` - Breite 25 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-20` - Breite 20 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-15` - Breite 15 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-10` - Breite 10 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-5` - Breite 5 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:w-auto` - Breite automatisch % beim Hover auf dem Tablet-PC
- `.tablet-pc:w-100` - Breite 100 % auf Tablet-PC
- `.tablet-pc:w-95` - Breite 95 % auf Tablet-PC
- `.tablet-pc:w-90` - Breite 90 % auf Tablet-PC
- `.tablet-pc:w-85` - Breite 85 % auf Tablet-PC
- `.tablet-pc:w-80` - Breite 80 % auf Tablet-PC
- `.tablet-pc:w-75` - Breite 75 % auf Tablet-PC
- `.tablet-pc:w-70` - Breite 70 % auf Tablet-PC
- `.tablet-pc:w-65` - Breite 65 % auf Tablet-PC
- `.tablet-pc:w-60` - Breite 60 % auf Tablet-PC
- `.tablet-pc:w-55` - Breite 55 % auf Tablet-PC
- `.tablet-pc:w-50` - Breite 50 % auf Tablet-PC
- `.tablet-pc:w-45` - Breite 45 % auf Tablet-PC
- `.tablet-pc:w-40` - Breite 40 % auf Tablet-PC
- `.tablet-pc:w-35` - Breite 35 % auf Tablet-PC
- `.tablet-pc:w-30` - Breite 30 % auf Tablet-PC
- `.tablet-pc:w-25` - Breite 25 % auf Tablet-PC
- `.tablet-pc:w-20` - Breite 20 % auf Tablet-PC
- `.tablet-pc:w-15` - Breite 15 % auf Tablet-PC
- `.tablet-pc:w-10` - Breite 10 % auf Tablet-PC
- `.tablet-pc:w-5` - Breite 5 % auf Tablet-PC
- `.tablet-pc:w-auto` - Breite automatisch % auf Tablet-PC

##### Width - Pc (992px - 1200px)

- `.hover:pc:w-100` - Breite 100 % beim Hover auf dem PC
- `.hover:pc:w-95` - Breite 95 % beim Schweben auf dem PC
- `.hover:pc:w-90` - Breite 90 % beim Schweben auf dem PC
- `.hover:pc:w-85` - Breite 85 % beim Schweben auf dem PC
- `.hover:pc:w-80` - Breite 80 % beim Schweben auf dem PC
- `.hover:pc:w-75` - Breite 75 % beim Schweben auf dem PC
- `.hover:pc:w-70` - Breite 70 % beim Schweben auf dem PC
- `.hover:pc:w-65` - Breite 65 % beim Schweben auf dem PC
- `.hover:pc:w-60` - Breite 60 % beim Schweben auf dem PC
- `.hover:pc:w-55` - Breite 55 % beim Schweben auf dem PC
- `.hover:pc:w-50` - Breite 50 % beim Schweben auf dem PC
- `.hover:pc:w-45` - Breite 45 % beim Schweben auf dem PC
- `.hover:pc:w-40` - Breite 40 % beim Schweben auf dem PC
- `.hover:pc:w-35` - Breite 35 % beim Schweben auf dem PC
- `.hover:pc:w-30` - Breite 30 % beim Schweben auf dem PC
- `.hover:pc:w-25` - Breite 25 % beim Schweben auf dem PC
- `.hover:pc:w-20` - Breite 20 % beim Schweben auf dem PC
- `.hover:pc:w-15` - Breite 15 % beim Schweben auf dem PC
- `.hover:pc:w-10` - Breite 10 % beim Hover auf dem PC
- `.hover:pc:w-5` - Breite 5 % beim Hover auf dem PC
- `.hover:pc:w-auto` - Breite automatisch % beim Hover auf dem PC
- `.pc:w-100` - Breite 100 % auf PC
- `.pc:w-95` - Breite 95 % auf PC
- `.pc:w-90` - Breite 90 % auf PC
- `.pc:w-85` - Breite 85 % auf PC
- `.pc:w-80` - Breite 80 % auf PC
- `.pc:w-75` - Breite 75 % auf PC
- `.pc:w-70` - Breite 70 % auf PC
- `.pc:w-65` - Breite 65 % auf PC
- `.pc:w-60` - Breite 60 % auf PC
- `.pc:w-55` - Breite 55 % auf PC
- `.pc:w-50` - Breite 50 % auf PC
- `.pc:w-45` - Breite 45 % auf PC
- `.pc:w-40` - Breite 40 % auf PC
- `.pc:w-35` - Breite 35 % auf PC
- `.pc:w-30` - Breite 30 % auf PC
- `.pc:w-25` - Breite 25 % auf PC
- `.pc:w-20` - Breite 20 % auf PC
- `.pc:w-15` - Breite 15 % auf PC
- `.pc:w-10` - Breite 10 % auf PC
- `.pc:w-5` - Breite 5 % auf PC
- `.pc:w-auto` - Breite automatisch % auf dem PC

##### Width - Tv (>= 1200px)

- `.hover:tv:w-100` - Breite 100 % beim Schweben im Fernsehen
- `.hover:tv:w-95` - Breite 95 % beim Schweben im Fernsehen
- `.hover:tv:w-90` - Breite 90 % beim Schweben im Fernsehen
- `.hover:tv:w-85` - Breite 85 % beim Schweben im Fernsehen
- `.hover:tv:w-80` - Breite 80 % beim Schweben im Fernsehen
- `.hover:tv:w-75` - Breite 75 % beim Schweben im Fernsehen
- `.hover:tv:w-70` - Breite 70 % beim Schweben im Fernsehen
- `.hover:tv:w-65` - Breite 65 % beim Schweben im Fernsehen
- `.hover:tv:w-60` - Breite 60 % beim Schweben im Fernsehen
- `.hover:tv:w-55` - Breite 55 % beim Schweben im Fernsehen
- `.hover:tv:w-50` - Breite 50 % beim Schweben im Fernsehen
- `.hover:tv:w-45` - Breite 45 % beim Schweben im Fernsehen
- `.hover:tv:w-40` - Breite 40 % beim Schweben im Fernsehen
- `.hover:tv:w-35` - Breite 35 % beim Schweben im Fernsehen
- `.hover:tv:w-30` - Breite 30 % beim Schweben im Fernsehen
- `.hover:tv:w-25` - Breite 25 % beim Schweben im Fernsehen
- `.hover:tv:w-20` - Breite 20 % beim Schweben im Fernsehen
- `.hover:tv:w-15` - Breite 15 % beim Schweben im Fernsehen
- `.hover:tv:w-10` - Breite 10 % beim Schweben im Fernsehen
- `.hover:tv:w-5` - Breite 5 % beim Schweben im Fernsehen
- `.hover:tv:w-auto` - Breite automatisch % beim Hover auf dem Fernseher
- `.tv:w-100` - Breite 100 % im Fernsehen
- `.tv:w-95` - Breite 95 % im Fernsehen
- `.tv:w-90` - Breite 90 % im Fernsehen
- `.tv:w-85` - Breite 85 % im Fernsehen
- `.tv:w-80` - Breite 80 % im Fernsehen
- `.tv:w-75` - Breite 75 % im Fernsehen
- `.tv:w-70` - Breite 70 % im Fernsehen
- `.tv:w-65` - Breite 65 % im Fernsehen
- `.tv:w-60` - Breite 60 % im Fernsehen
- `.tv:w-55` - Breite 55 % im Fernsehen
- `.tv:w-50` - Breite 50 % im Fernsehen
- `.tv:w-45` - Breite 45 % im Fernsehen
- `.tv:w-40` - Breite 40 % im Fernsehen
- `.tv:w-35` - Breite 35 % im Fernsehen
- `.tv:w-30` - Breite 30 % im Fernsehen
- `.tv:w-25` - Breite 25 % im Fernsehen
- `.tv:w-20` - Breite 20 % im Fernsehen
- `.tv:w-15` - Breite 15 % im Fernsehen
- `.tv:w-10` - Breite 10 % im Fernsehen
- `.tv:w-5` - Breite 5 % im Fernsehen
- `.tv:w-auto` - Breite automatisch % im Fernsehen

##### Width - Tablet Max (<= 768px)

- `.hover:tablet-max:w-100` - Breite 100 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-95` - Breite 95 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-90` - Breite 90 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-85` - Breite 85 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-80` - Breite 80 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-75` - Breite 75 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-70` - Breite 70 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-65` - Breite 65 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-60` - Breite 60 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-55` - Breite 55 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-50` - Breite 50 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-45` - Breite 45 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-40` - Breite 40 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-35` - Breite 35 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-30` - Breite 30 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-25` - Breite 25 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-20` - Breite 20 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-15` - Breite 15 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-10` - Breite 10 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-5` - Breite 5 % beim Hover auf dem Tablet max
- `.hover:tablet-max:w-auto` - Breite automatisch % beim Hover auf dem Tablet max
- `.tablet-max:w-100` - Breite 100 % auf Tablet max
- `.tablet-max:w-95` - Breite 95 % auf Tablet max
- `.tablet-max:w-90` - Breite 90 % auf Tablet max
- `.tablet-max:w-85` - Breite 85 % auf Tablet max
- `.tablet-max:w-80` - Breite 80 % auf Tablet max
- `.tablet-max:w-75` - Breite 75 % auf Tablet max
- `.tablet-max:w-70` - Breite 70 % auf Tablet max
- `.tablet-max:w-65` - Breite 65 % auf Tablet max
- `.tablet-max:w-60` - Breite 60 % auf Tablet max
- `.tablet-max:w-55` - Breite 55 % auf Tablet max
- `.tablet-max:w-50` - Breite 50 % auf Tablet max
- `.tablet-max:w-45` - Breite 45 % auf Tablet max
- `.tablet-max:w-40` - Breite 40 % auf Tablet max
- `.tablet-max:w-35` - Breite 35 % auf Tablet max
- `.tablet-max:w-30` - Breite 30 % auf Tablet max
- `.tablet-max:w-25` - Breite 25 % auf Tablet max
- `.tablet-max:w-20` - Breite 20 % auf Tablet max
- `.tablet-max:w-15` - Breite 15 % auf Tablet max
- `.tablet-max:w-10` - Breite 10 % auf Tablet max
- `.tablet-max:w-5` - Breite 5 % auf Tablet max
- `.tablet-max:w-auto` - Breite automatisch % auf dem Tablet max

##### Width - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:w-100` - Breite 100 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-95` - Breite 95 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-90` - Breite 90 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-85` - Breite 85 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-80` - Breite 80 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-75` - Breite 75 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-70` - Breite 70 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-65` - Breite 65 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-60` - Breite 60 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-55` - Breite 55 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-50` - Breite 50 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-45` - Breite 45 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-40` - Breite 40 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-35` - Breite 35 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-30` - Breite 30 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-25` - Breite 25 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-20` - Breite 20 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-15` - Breite 15 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-10` - Breite 10 % beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:w-5` - Breite 5 % beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:w-auto` - Breite automatisch % beim Hover auf dem Tablet-PC max
- `.tablet-pc-max:w-100` - Breite 100 % auf Tablet-PC max
- `.tablet-pc-max:w-95` - Breite 95 % auf Tablet-PC max
- `.tablet-pc-max:w-90` - Breite 90 % auf Tablet-PC max
- `.tablet-pc-max:w-85` - Breite 85 % auf Tablet-PC max
- `.tablet-pc-max:w-80` - Breite 80 % auf Tablet-PC max
- `.tablet-pc-max:w-75` - Breite 75 % auf Tablet-PC max
- `.tablet-pc-max:w-70` - Breite 70 % auf Tablet-PC max
- `.tablet-pc-max:w-65` - Breite 65 % auf Tablet-PC max
- `.tablet-pc-max:w-60` - Breite 60 % auf Tablet-PC max
- `.tablet-pc-max:w-55` - Breite 55 % auf Tablet-PC max
- `.tablet-pc-max:w-50` - Breite 50 % auf Tablet-PC max
- `.tablet-pc-max:w-45` - Breite 45 % auf Tablet-PC max
- `.tablet-pc-max:w-40` - Breite 40 % auf Tablet-PC max
- `.tablet-pc-max:w-35` - Breite 35 % auf Tablet-PC max
- `.tablet-pc-max:w-30` - Breite 30 % auf Tablet-PC max
- `.tablet-pc-max:w-25` - Breite 25 % auf Tablet-PC max
- `.tablet-pc-max:w-20` - Breite 20 % auf Tablet-PC max
- `.tablet-pc-max:w-15` - Breite 15 % auf Tablet-PC max
- `.tablet-pc-max:w-10` - Breite 10 % auf Tablet-PC max
- `.tablet-pc-max:w-5` - Breite 5 % auf Tablet-PC max
- `.tablet-pc-max:w-auto` - Breite auto% auf Tablet-PC max

##### Width - Pc Max (<= 1200px)

- `.hover:pc-max:w-100` - Breite 100 % beim Hover auf dem PC max
- `.hover:pc-max:w-95` - Breite 95 % beim Hover auf dem PC max
- `.hover:pc-max:w-90` - Breite 90 % beim Hover auf dem PC max
- `.hover:pc-max:w-85` - Breite 85 % beim Hover auf dem PC max
- `.hover:pc-max:w-80` - Breite 80 % beim Hover auf dem PC max
- `.hover:pc-max:w-75` - Breite 75 % beim Hover auf dem PC max
- `.hover:pc-max:w-70` - Breite 70 % beim Hover auf dem PC max
- `.hover:pc-max:w-65` - Breite 65 % beim Hover auf dem PC max
- `.hover:pc-max:w-60` - Breite 60 % beim Hover auf dem PC max
- `.hover:pc-max:w-55` - Breite 55 % beim Hover auf dem PC max
- `.hover:pc-max:w-50` - Breite 50 % beim Hover auf dem PC max
- `.hover:pc-max:w-45` - Breite 45 % beim Hover auf dem PC max
- `.hover:pc-max:w-40` - Breite 40 % beim Hover auf dem PC max
- `.hover:pc-max:w-35` - Breite 35 % beim Hover auf dem PC max
- `.hover:pc-max:w-30` - Breite 30 % beim Hover auf dem PC max
- `.hover:pc-max:w-25` - Breite 25 % beim Hover auf dem PC max
- `.hover:pc-max:w-20` - Breite 20 % beim Hover auf dem PC max
- `.hover:pc-max:w-15` - Breite 15 % beim Hover auf dem PC max
- `.hover:pc-max:w-10` - Breite 10 % beim Hover auf dem PC max
- `.hover:pc-max:w-5` - Breite 5 % beim Hover auf dem PC max
- `.hover:pc-max:w-auto` - Breite automatisch % beim Hover auf dem PC max
- `.pc-max:w-100` - Breite 100 % auf PC max
- `.pc-max:w-95` - Breite 95 % auf PC max
- `.pc-max:w-90` - Breite 90 % auf PC max
- `.pc-max:w-85` - Breite 85 % auf PC max
- `.pc-max:w-80` - Breite 80 % auf PC max
- `.pc-max:w-75` - Breite 75 % auf PC max
- `.pc-max:w-70` - Breite 70 % auf PC max
- `.pc-max:w-65` - Breite 65 % auf PC max
- `.pc-max:w-60` - Breite 60 % auf PC max
- `.pc-max:w-55` - Breite 55 % auf PC max
- `.pc-max:w-50` - Breite 50 % auf PC max
- `.pc-max:w-45` - Breite 45 % auf PC max
- `.pc-max:w-40` - Breite 40 % auf PC max
- `.pc-max:w-35` - Breite 35 % auf PC max
- `.pc-max:w-30` - Breite 30 % auf PC max
- `.pc-max:w-25` - Breite 25 % auf PC max
- `.pc-max:w-20` - Breite 20 % auf PC max
- `.pc-max:w-15` - Breite 15 % auf PC max
- `.pc-max:w-10` - Breite 10 % auf PC max
- `.pc-max:w-5` - Breite 5 % auf PC max
- `.pc-max:w-auto` - Breite auto% auf PC max

#### Width vh

- `.hover:w-vh-100` - Breite vh 100vh beim Schweben
- `.hover:w-vh-75` - Breite vh 75vh beim Schweben
- `.hover:w-vh-50` - Breite vh 50vh beim Schweben
- `.hover:w-vh-25` - Breite vh 25vh beim Schweben
- `.w-vh-100` - Breite vh 100vh
- `.w-vh-75` - Breite vh 75vh
- `.w-vh-50` - Breite vh 50vh
- `.w-vh-25` - Breite vh 25vh

#### Width vw

- `.hover:w-vw-100` - Breite vw 100vw beim Schweben
- `.hover:w-vw-75` - Breite vw 75vw beim Hover
- `.hover:w-vw-50` - Breite vw 50vw beim Schweben
- `.hover:w-vw-25` - Breite vw 25vw beim Schweben
- `.w-vw-100` - Breite vw 100vw
- `.w-vw-75` - Breite vw 75vw
- `.w-vw-50` - Breite vw 50vw
- `.w-vw-25` - Breite vw 25vw

### Height

- `.h-100` - Höhe 100 %
- `.h-95` - Höhe 95 %
- `.h-90` - Höhe 90 %
- `.h-85` - Höhe 85 %
- `.h-80` - Höhe 80 %
- `.h-75` - Höhe 75 %
- `.h-70` - Höhe 70 %
- `.h-65` - Höhe 65 %
- `.h-60` - Höhe 60 %
- `.h-55` - Höhe 55 %
- `.h-50` - Höhe 50 %
- `.h-45` - Höhe 45 %
- `.h-40` - Höhe 40 %
- `.h-35` - Höhe 35 %
- `.h-30` - Höhe 30 %
- `.h-25` - Höhe 25 %
- `.h-20` - Höhe 20 %
- `.h-15` - Höhe 15 %
- `.h-10` - Höhe 10 %
- `.h-5` - Höhe 5 %
- `.h-auto` - Höhe automatisch %
- `.hover:h-100` - Höhe 100 % beim Schweben
- `.hover:h-95` - Höhe 95 % beim Hover
- `.hover:h-90` - Höhe 90 % beim Hover
- `.hover:h-85` - Höhe 85 % beim Hover
- `.hover:h-80` - Höhe 80 % beim Hover
- `.hover:h-75` - Höhe 75 % beim Hover
- `.hover:h-70` - Höhe 70 % beim Hover
- `.hover:h-65` - Höhe 65 % beim Hover
- `.hover:h-60` - Höhe 60 % beim Hover
- `.hover:h-55` - Höhe 55 % beim Schweben
- `.hover:h-50` - Höhe 50 % beim Schweben
- `.hover:h-45` - Höhe 45 % beim Schweben
- `.hover:h-40` - Höhe 40 % beim Schweben
- `.hover:h-35` - Höhe 35 % beim Schweben
- `.hover:h-30` - Höhe 30 % beim Schweben
- `.hover:h-25` - Höhe 25 % beim Schweben
- `.hover:h-20` - Höhe 20 % beim Schweben
- `.hover:h-15` - Höhe 15 % beim Schweben
- `.hover:h-10` - Höhe 10 % beim Schweben
- `.hover:h-5` - Höhe 5 % beim Schweben
- `.hover:h-auto` - Höhe automatisch % beim Schweben

##### Height - Mobile (<= 480px)

- `.hover:mobile:h-100` - Höhe 100 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-95` - Höhe 95 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-90` - Höhe 90 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-85` - Höhe 85 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-80` - Höhe 80 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-75` - Höhe 75 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-70` - Höhe 70 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-65` - Höhe 65 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-60` - Höhe 60 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-55` - Höhe 55 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-50` - Höhe 50 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-45` - Höhe 45 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-40` - Höhe 40 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-35` - Höhe 35 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-30` - Höhe 30 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-25` - Höhe 25 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-20` - Höhe 20 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-15` - Höhe 15 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-10` - Höhe 10 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-5` - Höhe 5 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-auto` - Höhe automatisch % beim Bewegen des Mauszeigers auf dem Mobilgerät
- `.mobile:h-100` - Höhe 100 % auf Mobilgeräten
- `.mobile:h-95` - Höhe 95 % auf dem Handy
- `.mobile:h-90` - Höhe 90 % auf Mobilgeräten
- `.mobile:h-85` - Höhe 85 % auf Mobilgeräten
- `.mobile:h-80` - Höhe 80 % auf Mobilgeräten
- `.mobile:h-75` - Höhe 75 % auf Mobilgeräten
- `.mobile:h-70` - Höhe 70 % auf Mobilgeräten
- `.mobile:h-65` - Höhe 65 % auf Mobilgeräten
- `.mobile:h-60` - Höhe 60 % auf Mobilgeräten
- `.mobile:h-55` - Höhe 55 % auf Mobilgeräten
- `.mobile:h-50` - Höhe 50 % auf Mobilgeräten
- `.mobile:h-45` - Höhe 45 % auf Mobilgeräten
- `.mobile:h-40` - Höhe 40 % auf Mobilgeräten
- `.mobile:h-35` - Höhe 35 % auf Mobilgeräten
- `.mobile:h-30` - Höhe 30 % auf Mobilgeräten
- `.mobile:h-25` - Höhe 25 % auf Mobilgeräten
- `.mobile:h-20` - Höhe 20 % auf Mobilgeräten
- `.mobile:h-15` - Höhe 15 % auf Mobilgeräten
- `.mobile:h-10` - Höhe 10 % auf Mobilgeräten
- `.mobile:h-5` - Höhe 5 % auf Mobilgeräten
- `.mobile:h-auto` - Höhe automatisch % auf Mobilgeräten

##### Height - Tablet (480px - 768px)

- `.hover:tablet:h-100` - Höhe 100 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-95` - Höhe 95 % beim Schweben auf dem Tablet
- `.hover:tablet:h-90` - Höhe 90 % beim Schweben auf dem Tablet
- `.hover:tablet:h-85` - Höhe 85 % beim Schweben über das Tablet
- `.hover:tablet:h-80` - Höhe 80 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-75` - Höhe 75 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-70` - Höhe 70 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-65` - Höhe 65 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-60` - Höhe 60 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-55` - Höhe 55 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-50` - Höhe 50 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-45` - Höhe 45 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-40` - Höhe 40 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-35` - Höhe 35 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-30` - Höhe 30 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-25` - Höhe 25 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-20` - Höhe 20 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-15` - Höhe 15 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-10` - Höhe 10 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-5` - Höhe 5 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-auto` - Höhe automatisch % beim Bewegen des Mauszeigers auf dem Tablet
- `.tablet:h-100` - Höhe 100 % auf dem Tablet
- `.tablet:h-95` - Höhe 95 % auf dem Tablet
- `.tablet:h-90` - Höhe 90 % auf dem Tablet
- `.tablet:h-85` - Höhe 85 % auf dem Tablet
- `.tablet:h-80` - Höhe 80 % auf dem Tablet
- `.tablet:h-75` - Höhe 75 % auf dem Tablet
- `.tablet:h-70` - Höhe 70 % auf dem Tablet
- `.tablet:h-65` - Höhe 65 % auf dem Tablet
- `.tablet:h-60` - Höhe 60 % auf dem Tablet
- `.tablet:h-55` - Höhe 55 % auf dem Tablet
- `.tablet:h-50` - Höhe 50 % auf dem Tablet
- `.tablet:h-45` - Höhe 45 % auf dem Tablet
- `.tablet:h-40` - Höhe 40 % auf dem Tablet
- `.tablet:h-35` - Höhe 35 % auf dem Tablet
- `.tablet:h-30` - Höhe 30 % auf dem Tablet
- `.tablet:h-25` - Höhe 25 % auf dem Tablet
- `.tablet:h-20` - Höhe 20 % auf dem Tablet
- `.tablet:h-15` - Höhe 15 % auf dem Tablet
- `.tablet:h-10` - Höhe 10 % auf dem Tablet
- `.tablet:h-5` - Höhe 5 % auf dem Tablet
- `.tablet:h-auto` - Höhe automatisch % auf dem Tablet

##### Height - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:h-100` - Höhe 100 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-95` - Höhe 95 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-90` - Höhe 90 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-85` - Höhe 85 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-75` - Höhe 75 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-70` - Höhe 70 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-65` - Höhe 65 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-60` - Höhe 60 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-55` - Höhe 55 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-50` - Höhe 50 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-45` - Höhe 45 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-40` - Höhe 40 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-35` - Höhe 35 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-30` - Höhe 30 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-25` - Höhe 25 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-20` - Höhe 20 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-15` - Höhe 15 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-10` - Höhe 10 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-5` - Höhe 5 % beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:h-auto` - Höhe automatisch % beim Hover auf dem Tablet-PC
- `.tablet-pc:h-100` - Höhe 100 % auf Tablet-PC
- `.tablet-pc:h-95` - Höhe 95 % auf Tablet-PC
- `.tablet-pc:h-90` - Höhe 90 % auf Tablet-PC
- `.tablet-pc:h-85` - Höhe 85 % auf Tablet-PC
- `.tablet-pc:h-80` - Höhe 80 % auf Tablet-PC
- `.tablet-pc:h-75` - Höhe 75 % auf Tablet-PC
- `.tablet-pc:h-70` - Höhe 70 % auf Tablet-PC
- `.tablet-pc:h-65` - Höhe 65 % auf dem Tablet-PC
- `.tablet-pc:h-60` - Höhe 60 % auf Tablet-PC
- `.tablet-pc:h-55` - Höhe 55 % auf Tablet-PC
- `.tablet-pc:h-50` - Höhe 50 % auf Tablet-PC
- `.tablet-pc:h-45` - Höhe 45 % auf Tablet-PC
- `.tablet-pc:h-40` - Höhe 40 % auf Tablet-PC
- `.tablet-pc:h-35` - Höhe 35 % auf Tablet-PC
- `.tablet-pc:h-30` - Höhe 30 % auf Tablet-PC
- `.tablet-pc:h-25` - Höhe 25 % auf Tablet-PC
- `.tablet-pc:h-20` - Höhe 20 % auf Tablet-PC
- `.tablet-pc:h-15` - Höhe 15 % auf Tablet-PC
- `.tablet-pc:h-10` - Höhe 10 % auf Tablet-PC
- `.tablet-pc:h-5` - Höhe 5 % auf Tablet-PC
- `.tablet-pc:h-auto` - Höhe automatisch % auf dem Tablet-PC

##### Height - Pc (992px - 1200px)

- `.hover:pc:h-100` - Höhe 100 % beim Schweben auf dem PC
- `.hover:pc:h-95` - Höhe 95 % beim Schweben auf dem PC
- `.hover:pc:h-90` - Höhe 90 % beim Schweben auf dem PC
- `.hover:pc:h-85` - Höhe 85 % beim Schweben auf dem PC
- `.hover:pc:h-80` - Höhe 80 % beim Schweben auf dem PC
- `.hover:pc:h-75` - Höhe 75 % beim Schweben auf dem PC
- `.hover:pc:h-70` - Höhe 70 % beim Schweben auf dem PC
- `.hover:pc:h-65` - Höhe 65 % beim Schweben auf dem PC
- `.hover:pc:h-60` - Höhe 60 % beim Schweben auf dem PC
- `.hover:pc:h-55` - Höhe 55 % beim Schweben auf dem PC
- `.hover:pc:h-50` - Höhe 50 % beim Schweben auf dem PC
- `.hover:pc:h-45` - Höhe 45 % beim Schweben auf dem PC
- `.hover:pc:h-40` - Höhe 40 % beim Schweben auf dem PC
- `.hover:pc:h-35` - Höhe 35 % beim Schweben auf dem PC
- `.hover:pc:h-30` - Höhe 30 % beim Schweben auf dem PC
- `.hover:pc:h-25` - Höhe 25 % beim Schweben auf dem PC
- `.hover:pc:h-20` - Höhe 20 % beim Schweben auf dem PC
- `.hover:pc:h-15` - Höhe 15 % beim Schweben auf dem PC
- `.hover:pc:h-10` - Höhe 10 % beim Schweben auf dem PC
- `.hover:pc:h-5` - Höhe 5 % beim Schweben auf dem PC
- `.hover:pc:h-auto` - Höhe automatisch % beim Hover auf dem PC
- `.pc:h-100` - Höhe 100 % auf PC
- `.pc:h-95` - Höhe 95 % auf PC
- `.pc:h-90` - Höhe 90 % auf PC
- `.pc:h-85` - Höhe 85 % auf PC
- `.pc:h-80` - Höhe 80 % auf PC
- `.pc:h-75` - Höhe 75 % auf dem PC
- `.pc:h-70` - Höhe 70 % auf PC
- `.pc:h-65` - Höhe 65 % auf PC
- `.pc:h-60` - Höhe 60 % auf PC
- `.pc:h-55` - Höhe 55 % auf PC
- `.pc:h-50` - Höhe 50 % auf PC
- `.pc:h-45` - Höhe 45 % auf PC
- `.pc:h-40` - Höhe 40 % am PC
- `.pc:h-35` - Höhe 35 % auf PC
- `.pc:h-30` - Höhe 30 % auf PC
- `.pc:h-25` - Höhe 25 % auf PC
- `.pc:h-20` - Höhe 20 % auf PC
- `.pc:h-15` - Höhe 15 % auf PC
- `.pc:h-10` - Höhe 10 % auf PC
- `.pc:h-5` - Höhe 5 % auf PC
- `.pc:h-auto` - Höhe automatisch % auf dem PC

##### Height - Tv (>= 1200px)

- `.hover:tv:h-100` - Höhe 100 % beim Schweben im Fernsehen
- `.hover:tv:h-95` - Höhe 95 % beim Schweben im Fernsehen
- `.hover:tv:h-90` - Höhe 90 % beim Schweben im Fernsehen
- `.hover:tv:h-85` - Höhe 85 % beim Schweben im Fernsehen
- `.hover:tv:h-80` - Höhe 80 % beim Schweben im Fernsehen
- `.hover:tv:h-75` - Höhe 75 % beim Schweben im Fernsehen
- `.hover:tv:h-70` - Höhe 70 % beim Schweben im Fernsehen
- `.hover:tv:h-65` - Höhe 65 % beim Schweben im Fernsehen
- `.hover:tv:h-60` - Höhe 60 % beim Schweben im Fernsehen
- `.hover:tv:h-55` - Höhe 55 % beim Schweben im Fernsehen
- `.hover:tv:h-50` - Höhe 50 % beim Schweben im Fernsehen
- `.hover:tv:h-45` - Höhe 45 % beim Schweben im Fernsehen
- `.hover:tv:h-40` - Höhe 40 % beim Schweben im Fernsehen
- `.hover:tv:h-35` - Höhe 35 % beim Schweben im Fernsehen
- `.hover:tv:h-30` - Höhe 30 % beim Schweben im Fernsehen
- `.hover:tv:h-25` - Höhe 25 % beim Schweben im Fernsehen
- `.hover:tv:h-20` - Höhe 20 % beim Schweben im Fernsehen
- `.hover:tv:h-15` - Höhe 15 % beim Schweben im Fernsehen
- `.hover:tv:h-10` - Höhe 10 % beim Schweben im Fernsehen
- `.hover:tv:h-5` - Höhe 5 % beim Schweben im Fernsehen
- `.hover:tv:h-auto` - Höhe automatisch % beim Schweben im Fernsehen
- `.tv:h-100` - Höhe 100 % im Fernsehen
- `.tv:h-95` - Größe 95 % im Fernsehen
- `.tv:h-90` - Größe 90 % im Fernsehen
- `.tv:h-85` - Größe 85 % im Fernsehen
- `.tv:h-80` - Größe 80 % im Fernsehen
- `.tv:h-75` - Größe 75 % im Fernsehen
- `.tv:h-70` - Größe 70 % im Fernsehen
- `.tv:h-65` - Größe 65 % im Fernsehen
- `.tv:h-60` - Größe 60 % im Fernsehen
- `.tv:h-55` - Größe 55 % im Fernsehen
- `.tv:h-50` - Größe 50 % im Fernsehen
- `.tv:h-45` - Größe 45 % im Fernsehen
- `.tv:h-40` - Größe 40 % im Fernsehen
- `.tv:h-35` - Größe 35 % im Fernsehen
- `.tv:h-30` - Größe 30 % im Fernsehen
- `.tv:h-25` - Größe 25 % im Fernsehen
- `.tv:h-20` - Höhe 20 % im Fernsehen
- `.tv:h-15` - Größe 15 % im Fernsehen
- `.tv:h-10` - Höhe 10 % im Fernsehen
- `.tv:h-5` - Höhe 5 % im Fernsehen
- `.tv:h-auto` - Höhe automatisch% im Fernsehen

##### Height - Tablet Max (<= 768px)

- `.hover:tablet-max:h-100` - Höhe 100 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-95` - Höhe 95 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-90` - Höhe 90 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-85` - Höhe 85 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-80` - Höhe 80 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-75` - Höhe 75 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-70` - Höhe 70 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-65` - Höhe 65 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-60` - Höhe 60 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-55` - Höhe 55 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-50` - Höhe 50 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-45` - Höhe 45 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-40` - Höhe 40 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-35` - Höhe 35 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-30` - Höhe 30 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-25` - Höhe 25 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-20` - Höhe 20 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-15` - Höhe 15 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-10` - Höhe 10 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-5` - Höhe 5 % beim Schweben auf dem Tablet max
- `.hover:tablet-max:h-auto` - Höhe automatisch % beim Schweben auf dem Tablet max
- `.tablet-max:h-100` - Höhe 100 % auf Tablet max
- `.tablet-max:h-95` - Höhe 95 % auf Tablet max
- `.tablet-max:h-90` - Höhe 90 % auf Tablet max
- `.tablet-max:h-85` - Höhe 85 % auf Tablet max
- `.tablet-max:h-80` - Höhe 80 % auf Tablet max
- `.tablet-max:h-75` - Höhe 75 % auf Tablet max
- `.tablet-max:h-70` - Höhe 70 % auf Tablet max
- `.tablet-max:h-65` - Höhe 65 % auf Tablet max
- `.tablet-max:h-60` - Höhe 60 % auf Tablet max
- `.tablet-max:h-55` - Höhe 55 % auf Tablet max
- `.tablet-max:h-50` - Höhe 50 % auf Tablet max
- `.tablet-max:h-45` - Höhe 45 % auf Tablet max
- `.tablet-max:h-40` - Höhe 40 % auf Tablet max
- `.tablet-max:h-35` - Höhe 35 % auf Tablet max
- `.tablet-max:h-30` - Höhe 30 % auf Tablet max
- `.tablet-max:h-25` - Höhe 25 % auf Tablet max
- `.tablet-max:h-20` - Höhe 20 % auf Tablet max
- `.tablet-max:h-15` - Höhe 15 % auf Tablet max
- `.tablet-max:h-10` - Höhe 10 % auf Tablet max
- `.tablet-max:h-5` - Höhe 5 % auf Tablet max
- `.tablet-max:h-auto` - Höhe automatisch % auf dem Tablet max

##### Height - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:h-100` - Höhe 100 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-95` - Höhe 95 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-90` - Höhe 90 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-85` - Höhe 85 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-80` - Höhe 80 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-75` - Höhe 75 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-70` - Höhe 70 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-65` - Höhe 65 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-60` - Höhe 60 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-55` - Höhe 55 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-50` - Höhe 50 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-45` - Höhe 45 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-40` - Höhe 40 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-35` - Höhe 35 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-30` - Höhe 30 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-25` - Höhe 25 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-20` - Höhe 20 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-15` - Höhe 15 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-10` - Höhe 10 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-5` - Höhe 5 % beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:h-auto` - Höhe automatisch % beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:h-100` - Höhe 100 % auf Tablet-PC max
- `.tablet-pc-max:h-95` - Höhe 95 % auf Tablet-PC max
- `.tablet-pc-max:h-90` - Höhe 90 % auf Tablet-PC max
- `.tablet-pc-max:h-85` - Höhe 85 % auf Tablet-PC max
- `.tablet-pc-max:h-80` - Höhe 80 % auf Tablet-PC max
- `.tablet-pc-max:h-75` - Höhe 75 % auf Tablet-PC max
- `.tablet-pc-max:h-70` - Höhe 70 % auf Tablet-PC max
- `.tablet-pc-max:h-65` - Höhe 65 % auf Tablet-PC max
- `.tablet-pc-max:h-60` - Höhe 60 % auf Tablet-PC max
- `.tablet-pc-max:h-55` - Höhe 55 % auf Tablet-PC max
- `.tablet-pc-max:h-50` - Höhe 50 % auf Tablet-PC max
- `.tablet-pc-max:h-45` - Höhe 45 % auf Tablet-PC max
- `.tablet-pc-max:h-40` - Höhe 40 % auf Tablet-PC max
- `.tablet-pc-max:h-35` - Höhe 35 % auf Tablet-PC max
- `.tablet-pc-max:h-30` - Höhe 30 % auf Tablet-PC max
- `.tablet-pc-max:h-25` - Höhe 25 % auf Tablet-PC max
- `.tablet-pc-max:h-20` - Höhe 20 % auf Tablet-PC max
- `.tablet-pc-max:h-15` - Höhe 15 % auf Tablet-PC max
- `.tablet-pc-max:h-10` - Höhe 10 % auf Tablet-PC max
- `.tablet-pc-max:h-5` - Höhe 5 % auf Tablet-PC max
- `.tablet-pc-max:h-auto` - Höhe automatisch % auf Tablet-PC max

##### Height - Pc Max (<= 1200px)

- `.hover:pc-max:h-100` - Höhe 100 % beim Schweben auf dem PC max
- `.hover:pc-max:h-95` - Höhe 95 % beim Schweben auf dem PC max
- `.hover:pc-max:h-90` - Höhe 90 % beim Schweben auf dem PC max
- `.hover:pc-max:h-85` - Höhe 85 % beim Schweben auf dem PC max
- `.hover:pc-max:h-80` - Höhe 80 % beim Schweben auf dem PC max
- `.hover:pc-max:h-75` - Höhe 75 % beim Schweben auf dem PC max
- `.hover:pc-max:h-70` - Höhe 70 % beim Schweben auf dem PC max
- `.hover:pc-max:h-65` - Höhe 65 % beim Schweben auf dem PC max
- `.hover:pc-max:h-60` - Höhe 60 % beim Schweben auf dem PC max
- `.hover:pc-max:h-55` - Höhe 55 % beim Schweben auf dem PC max
- `.hover:pc-max:h-50` - Höhe 50 % beim Schweben auf dem PC max
- `.hover:pc-max:h-45` - Höhe 45 % beim Hover auf dem PC max
- `.hover:pc-max:h-40` - Höhe 40 % beim Schweben auf dem PC max
- `.hover:pc-max:h-35` - Höhe 35 % beim Schweben auf dem PC max
- `.hover:pc-max:h-30` - Höhe 30 % beim Schweben auf dem PC max
- `.hover:pc-max:h-25` - Höhe 25 % beim Hover auf dem PC max
- `.hover:pc-max:h-20` - Höhe 20 % beim Schweben auf dem PC max
- `.hover:pc-max:h-15` - Höhe 15 % beim Schweben auf dem PC max
- `.hover:pc-max:h-10` - Höhe 10 % beim Schweben auf dem PC max
- `.hover:pc-max:h-5` - Höhe 5 % beim Schweben auf dem PC max
- `.hover:pc-max:h-auto` - Höhe automatisch % beim Schweben auf dem PC max
- `.pc-max:h-100` - Höhe 100 % auf PC max
- `.pc-max:h-95` - Höhe 95 % auf PC max
- `.pc-max:h-90` - Höhe 90 % auf PC max
- `.pc-max:h-85` - Höhe 85 % auf PC max
- `.pc-max:h-80` - Höhe 80 % auf PC max
- `.pc-max:h-75` - Höhe 75 % auf PC max
- `.pc-max:h-70` - Höhe 70 % auf PC max
- `.pc-max:h-65` - Höhe 65 % auf PC max
- `.pc-max:h-60` - Höhe 60 % auf PC max
- `.pc-max:h-55` - Höhe 55 % auf PC max
- `.pc-max:h-50` - Höhe 50 % auf PC max
- `.pc-max:h-45` - Höhe 45 % auf PC max
- `.pc-max:h-40` - Höhe 40 % auf PC max
- `.pc-max:h-35` - Höhe 35 % auf PC max
- `.pc-max:h-30` - Höhe 30 % auf PC max
- `.pc-max:h-25` - Höhe 25 % auf PC max
- `.pc-max:h-20` - Höhe 20 % auf PC max
- `.pc-max:h-15` - Höhe 15 % auf PC max
- `.pc-max:h-10` - Höhe 10 % auf PC max
- `.pc-max:h-5` - Höhe 5 % auf PC max
- `.pc-max:h-auto` - Höhe automatisch % auf PC max

#### Height vh

- `.h-vh-100` - Höhe vh 100vh
- `.h-vh-75` - Höhe vh 75vh
- `.h-vh-50` - Höhe vh 50vh
- `.h-vh-25` - Höhe vh 25vh
- `.hover:h-vh-100` - Höhe vh 100vh beim Schweben
- `.hover:h-vh-75` - Höhe vh 75vh beim Hover
- `.hover:h-vh-50` - Höhe vh 50vh beim Schweben
- `.hover:h-vh-25` - Höhe vh 25vh beim Schweben

#### Height vw

- `.h-vw-100` - Höhe vw 100vw
- `.h-vw-75` - Höhe vw 75vw
- `.h-vw-50` - Höhe vw 50vw
- `.h-vw-25` - Höhe vw 25vw
- `.hover:h-vw-100` - Höhe vw 100vw beim Hover
- `.hover:h-vw-75` - Höhe vw 75vw beim Hover
- `.hover:h-vw-50` - Höhe vw 50vw beim Hover
- `.hover:h-vw-25` - Höhe vw 25vw beim Hover

## Positioning

### Static

- `.hover:static` - Statisch beim Schweben
- `.static` - Statisch

### Relative

- `.hover:relative` - Relativ beim Hover
- `.relative` - Relativ

### Absolute

- `.absolute` - Absolut
- `.hover:absolute` - Absolut beim Hover

### Fixed

- `.fixed` - Behoben
- `.hover:fixed` - Beim Schweben behoben

### Sticky

- `.hover:sticky` - Klebrig beim Schweben
- `.sticky` - Klebrig

### Top

- `.hover:top-100` - Abstand oben 100 % beim Hover
- `.hover:top-75` - Abstand oben 75 % beim Hover
- `.hover:top-50` - Abstand oben 50 % beim Hover
- `.hover:top-25` - Abstand oben 25 % beim Hover
- `.hover:top-5` - Abstand oben 5rem beim Hover
- `.hover:top-4.5` - Abstand oben 0rem beim Hover
- `.hover:top-4` - Abstand oben 4rem beim Hover
- `.hover:top-3.5` - Abstand oben 0rem beim Hover
- `.hover:top-3` - Abstand oben 3rem beim Hover
- `.hover:top-2.5` - Abstand oben 0rem beim Hover
- `.hover:top-2` - Abstand oben 2rem beim Hover
- `.hover:top-1.9` - Abstand oben 0rem beim Hover
- `.hover:top-1.8` - Abstand oben 0rem beim Hover
- `.hover:top-1.7` - Abstand oben 0rem beim Hover
- `.hover:top-1.6` - Abstand oben 0rem beim Hover
- `.hover:top-1.5` - Abstand oben 0rem beim Hover
- `.hover:top-1.4` - Abstand oben 0rem beim Hover
- `.hover:top-1.3` - Abstand oben 0rem beim Hover
- `.hover:top-1.2` - Abstand oben 0rem beim Hover
- `.hover:top-1.1` - Abstand oben 0rem beim Hover
- `.hover:top-1` - Abstand oben 1rem beim Hover
- `.hover:top-0.9` - Abstand oben 0rem beim Hover
- `.hover:top-0.8` - Abstand oben 0rem beim Hover
- `.hover:top-0.7` - Abstand oben 0rem beim Hover
- `.hover:top-0.6` - Abstand oben 0rem beim Hover
- `.hover:top-0.5` - Abstand oben 0rem beim Hover
- `.hover:top-0.4` - Abstand oben 0rem beim Hover
- `.hover:top-0.3` - Abstand oben 0rem beim Hover
- `.hover:top-0.2` - Abstand oben 0.2rem beim Hover
- `.hover:top-0.1` - Abstand oben 0.1rem beim Hover
- `.hover:top-0` - Abstand oben 0rem beim Hover
- `.top-100` - Abstand oben 100 %
- `.top-75` - Abstand oben 75 %
- `.top-50` - Abstand oben 50 %
- `.top-25` - Abstand oben 25 %
- `.top-5` - Abstand oben 5rem
- `.top-4.5` - Abstand oben 0rem
- `.top-4` - Abstand oben 4rem
- `.top-3.5` - Abstand oben 0rem
- `.top-3` - Abstand oben 3rem
- `.top-2.5` - Abstand oben 0rem
- `.top-2` - Abstand oben 2rem
- `.top-1.9` - Abstand oben 0rem
- `.top-1.8` - Abstand oben 0rem
- `.top-1.7` - Abstand oben 0rem
- `.top-1.6` - Abstand oben 0rem
- `.top-1.5` - Abstand oben 0rem
- `.top-1.4` - Abstand oben 0rem
- `.top-1.3` - Abstand oben 0rem
- `.top-1.2` - Abstand oben 0rem
- `.top-1.1` - Abstand oben 0rem
- `.top-1` - Abstand oben 1rem
- `.top-0.9` - Abstand oben 0rem
- `.top-0.8` - Abstand oben 0rem
- `.top-0.7` - Abstand oben 0rem
- `.top-0.6` - Abstand oben 0rem
- `.top-0.5` - Abstand oben 0rem
- `.top-0.4` - Abstand oben 0rem
- `.top-0.3` - Abstand oben 0rem
- `.top-0.2` - Abstand oben 0.2rem
- `.top-0.1` - Abstand oben 0.1rem
- `.top-0` - Abstand oben 0rem

##### Negative Top

- `.-top-5` - Negativer Abstand oben 5rem
- `.-top-4.5` - Negativer Abstand oben 0rem
- `.-top-4` - Negativer Abstand oben 4rem
- `.-top-3.5` - Negativer Abstand oben 0rem
- `.-top-3` - Negativer Abstand oben 3rem
- `.-top-2.5` - Negativer Abstand oben 0rem
- `.-top-2` - Negativer Abstand oben 2rem
- `.-top-1.9` - Negativer Abstand oben 0rem
- `.-top-1.8` - Negativer Abstand oben 0rem
- `.-top-1.7` - Negativer Abstand oben 0rem
- `.-top-1.6` - Negativer Abstand oben 0rem
- `.-top-1.5` - Negativer Abstand oben 0rem
- `.-top-1.4` - Negativer Abstand oben 0rem
- `.-top-1.3` - Negativer Abstand oben 0rem
- `.-top-1.2` - Negativer Abstand oben 0rem
- `.-top-1.1` - Negativer Abstand oben 0rem
- `.-top-1` - Negativer Abstand oben 1rem
- `.-top-0.9` - Negativer Abstand oben 0rem
- `.-top-0.8` - Negativer Abstand oben 0rem
- `.-top-0.7` - Negativer Abstand oben 0rem
- `.-top-0.6` - Negativer Abstand oben 0rem
- `.-top-0.5` - Negativer Abstand oben 0rem
- `.-top-0.4` - Negativer Abstand oben 0rem
- `.-top-0.3` - Negativer Abstand oben 0.3rem
- `.-top-0.2` - Negativer Abstand oben 0.2rem
- `.-top-0.1` - Negativer Abstand oben 0.1rem
- `.hover:-top-5` - Negativer Abstand oben 5rem beim Hover
- `.hover:-top-4.5` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-4` - Negativer Abstand oben 4rem beim Hover
- `.hover:-top-3.5` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-3` - Negativer Abstand oben 3rem beim Hover
- `.hover:-top-2.5` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-2` - Negativer Abstand oben 2rem beim Hover
- `.hover:-top-1.9` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.8` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.7` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.6` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.5` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.4` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.3` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.2` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1.1` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-1` - Negativer Abstand oben 1rem beim Hover
- `.hover:-top-0.9` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-0.8` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-0.7` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-0.6` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-0.5` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-0.4` - Negativer Abstand oben 0rem beim Hover
- `.hover:-top-0.3` - Negativer Abstand oben 0.3rem beim Hover
- `.hover:-top-0.2` - Negativer Abstand oben 0.2rem beim Hover
- `.hover:-top-0.1` - Negativer Abstand oben 0.1rem beim Hover

### Right

- `.hover:right-100` - Abstand rechts 100 % beim Hover
- `.hover:right-75` - Abstand rechts 75 % beim Hover
- `.hover:right-50` - Abstand rechts 50 % beim Hover
- `.hover:right-25` - Abstand rechts 25 % beim Hover
- `.hover:right-5` - Abstand rechts 5rem beim Hover
- `.hover:right-4.5` - Abstand rechts 0rem beim Hover
- `.hover:right-4` - Abstand rechts 4rem beim Hover
- `.hover:right-3.5` - Abstand rechts 0rem beim Hover
- `.hover:right-3` - Abstand rechts 3rem beim Hover
- `.hover:right-2.5` - Abstand rechts 0rem beim Hover
- `.hover:right-2` - Abstand rechts 2rem beim Hover
- `.hover:right-1.9` - Abstand rechts 0rem beim Hover
- `.hover:right-1.8` - Abstand rechts 0rem beim Hover
- `.hover:right-1.7` - Abstand rechts 0rem beim Hover
- `.hover:right-1.6` - Abstand rechts 0rem beim Hover
- `.hover:right-1.5` - Abstand rechts 0rem beim Hover
- `.hover:right-1.4` - Abstand rechts 0rem beim Hover
- `.hover:right-1.3` - Abstand rechts 0rem beim Hover
- `.hover:right-1.2` - Abstand rechts 0rem beim Hover
- `.hover:right-1.1` - Abstand rechts 0rem beim Hover
- `.hover:right-1` - Abstand rechts 1rem beim Hover
- `.hover:right-0.9` - Abstand rechts 0rem beim Hover
- `.hover:right-0.8` - Abstand rechts 0rem beim Hover
- `.hover:right-0.7` - Abstand rechts 0rem beim Hover
- `.hover:right-0.6` - Abstand rechts 0rem beim Hover
- `.hover:right-0.5` - Abstand rechts 0rem beim Hover
- `.hover:right-0.4` - Abstand rechts 0rem beim Hover
- `.hover:right-0.3` - Abstand rechts 0rem beim Hover
- `.hover:right-0.2` - Abstand rechts 0.2rem beim Hover
- `.hover:right-0.1` - Abstand rechts 0.1rem beim Hover
- `.hover:right-0` - Abstand rechts 0rem beim Hover
- `.right-100` - Abstand rechts 100 %
- `.right-75` - Abstand rechts 75 %
- `.right-50` - Abstand rechts 50 %
- `.right-25` - Abstand rechts 25 %
- `.right-5` - Abstand rechts 5rem
- `.right-4.5` - Abstand rechts 0rem
- `.right-4` - Abstand rechts 4rem
- `.right-3.5` - Abstand rechts 0rem
- `.right-3` - Abstand rechts 3rem
- `.right-2.5` - Abstand rechts 0rem
- `.right-2` - Abstand rechts 2rem
- `.right-1.9` - Abstand rechts 0rem
- `.right-1.8` - Abstand rechts 0rem
- `.right-1.7` - Abstand rechts 0rem
- `.right-1.6` - Abstand rechts 0rem
- `.right-1.5` - Abstand rechts 0rem
- `.right-1.4` - Abstand rechts 0rem
- `.right-1.3` - Abstand rechts 0rem
- `.right-1.2` - Abstand rechts 0rem
- `.right-1.1` - Abstand rechts 0rem
- `.right-1` - Abstand rechts 1rem
- `.right-0.9` - Abstand rechts 0rem
- `.right-0.8` - Abstand rechts 0rem
- `.right-0.7` - Abstand rechts 0rem
- `.right-0.6` - Abstand rechts 0rem
- `.right-0.5` - Abstand rechts 0rem
- `.right-0.4` - Abstand rechts 0rem
- `.right-0.3` - Abstand rechts 0rem
- `.right-0.2` - Abstand rechts 0.2rem
- `.right-0.1` - Abstand rechts 0.1rem
- `.right-0` - Abstand rechts 0rem

##### Negative Right

- `.-right-5` - Negativer Abstand rechts 5rem
- `.-right-4.5` - Negativer Abstand rechts 0rem
- `.-right-4` - Negativer Abstand rechts 4rem
- `.-right-3.5` - Negativer Abstand rechts 0rem
- `.-right-3` - Negativer Abstand rechts 3rem
- `.-right-2.5` - Negativer Abstand rechts 0rem
- `.-right-2` - Negativer Abstand rechts 2rem
- `.-right-1.9` - Negativer Abstand rechts 0rem
- `.-right-1.8` - Negativer Abstand rechts 0rem
- `.-right-1.7` - Negativer Abstand rechts 0rem
- `.-right-1.6` - Negativer Abstand rechts 0rem
- `.-right-1.5` - Negativer Abstand rechts 0rem
- `.-right-1.4` - Negativer Abstand rechts 0rem
- `.-right-1.3` - Negativer Abstand rechts 0rem
- `.-right-1.2` - Negativer Abstand rechts 0rem
- `.-right-1.1` - Negativer Abstand rechts 0rem
- `.-right-1` - Negativer Abstand rechts 1rem
- `.-right-0.9` - Negativer Abstand rechts 0rem
- `.-right-0.8` - Negativer Abstand rechts 0rem
- `.-right-0.7` - Negativer Abstand rechts 0rem
- `.-right-0.6` - Negativer Abstand rechts 0rem
- `.-right-0.5` - Negativer Abstand rechts 0rem
- `.-right-0.4` - Negativer Abstand rechts 0rem
- `.-right-0.3` - Negativer Abstand rechts 0.3rem
- `.-right-0.2` - Negativer Abstand rechts 0.2rem
- `.-right-0.1` - Negativer Abstand rechts 0.1rem
- `.hover:-right-5` - Negativer Abstand rechts 5rem beim Hover
- `.hover:-right-4.5` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-4` - Negativer Abstand rechts 4rem beim Hover
- `.hover:-right-3.5` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-3` - Negativer Abstand rechts 3rem beim Hover
- `.hover:-right-2.5` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-2` - Negativer Abstand rechts 2rem beim Hover
- `.hover:-right-1.9` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.8` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.7` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.6` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.5` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.4` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.3` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.2` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1.1` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-1` - Negativer Abstand rechts 1rem beim Hover
- `.hover:-right-0.9` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-0.8` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-0.7` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-0.6` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-0.5` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-0.4` - Negativer Abstand rechts 0rem beim Hover
- `.hover:-right-0.3` - Negativer Abstand rechts 0.3rem beim Hover
- `.hover:-right-0.2` - Negativer Abstand rechts 0.2rem beim Hover
- `.hover:-right-0.1` - Negativer Abstand rechts 0.1rem beim Hover

### Bottom

- `.bottom-100` - Abstand unten 100 %
- `.bottom-75` - Abstand unten 75 %
- `.bottom-50` - Abstand unten 50 %
- `.bottom-25` - Abstand unten 25 %
- `.bottom-5` - Abstand unten 5rem
- `.bottom-4.5` - Abstand unten 0rem
- `.bottom-4` - Abstand unten 4rem
- `.bottom-3.5` - Abstand unten 0rem
- `.bottom-3` - Abstand unten 3rem
- `.bottom-2.5` - Abstand unten 0rem
- `.bottom-2` - Abstand unten 2rem
- `.bottom-1.9` - Abstand unten 0rem
- `.bottom-1.8` - Abstand unten 0rem
- `.bottom-1.7` - Abstand unten 0rem
- `.bottom-1.6` - Abstand unten 0rem
- `.bottom-1.5` - Abstand unten 0rem
- `.bottom-1.4` - Abstand unten 0rem
- `.bottom-1.3` - Abstand unten 0rem
- `.bottom-1.2` - Abstand unten 0rem
- `.bottom-1.1` - Abstand unten 0rem
- `.bottom-1` - Abstand unten 1rem
- `.bottom-0.9` - Abstand unten 0rem
- `.bottom-0.8` - Abstand unten 0rem
- `.bottom-0.7` - Abstand unten 0rem
- `.bottom-0.6` - Abstand unten 0rem
- `.bottom-0.5` - Abstand unten 0rem
- `.bottom-0.4` - Abstand unten 0rem
- `.bottom-0.3` - Abstand unten 0rem
- `.bottom-0.2` - Abstand unten 0.2rem
- `.bottom-0.1` - Abstand unten 0.1rem
- `.bottom-0` - Abstand unten 0rem
- `.hover:bottom-100` - Abstand unten 100 % beim Hover
- `.hover:bottom-75` - Abstand unten 75 % beim Hover
- `.hover:bottom-50` - Abstand unten 50 % beim Hover
- `.hover:bottom-25` - Abstand unten 25 % beim Hover
- `.hover:bottom-5` - Abstand unten 5rem beim Hover
- `.hover:bottom-4.5` - Abstand unten 0rem beim Hover
- `.hover:bottom-4` - Abstand unten 4rem beim Hover
- `.hover:bottom-3.5` - Abstand unten 0rem beim Hover
- `.hover:bottom-3` - Abstand unten 3rem beim Hover
- `.hover:bottom-2.5` - Abstand unten 0rem beim Hover
- `.hover:bottom-2` - Abstand unten 2rem beim Hover
- `.hover:bottom-1.9` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.8` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.7` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.6` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.5` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.4` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.3` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.2` - Abstand unten 0rem beim Hover
- `.hover:bottom-1.1` - Abstand unten 0rem beim Hover
- `.hover:bottom-1` - Abstand unten 1rem beim Hover
- `.hover:bottom-0.9` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.8` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.7` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.6` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.5` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.4` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.3` - Abstand unten 0rem beim Hover
- `.hover:bottom-0.2` - Abstand unten 0.2rem beim Hover
- `.hover:bottom-0.1` - Abstand unten 0.1rem beim Hover
- `.hover:bottom-0` - Abstand unten 0rem beim Hover

##### Negative Bottom

- `.-bottom-5` - Negativer Abstand unten 5rem
- `.-bottom-4.5` - Negativer Abstand unten 0rem
- `.-bottom-4` - Negativer Abstand unten 4rem
- `.-bottom-3.5` - Negativer Abstand unten 0rem
- `.-bottom-3` - Negativer Abstand unten 3rem
- `.-bottom-2.5` - Negativer Abstand unten 0rem
- `.-bottom-2` - Negativer Abstand unten 2rem
- `.-bottom-1.9` - Negativer Abstand unten 0rem
- `.-bottom-1.8` - Negativer Abstand unten 0rem
- `.-bottom-1.7` - Negativer Abstand unten 0rem
- `.-bottom-1.6` - Negativer Abstand unten 0rem
- `.-bottom-1.5` - Negativer Abstand unten 0rem
- `.-bottom-1.4` - Negativer Abstand unten 0rem
- `.-bottom-1.3` - Negativer Abstand unten 0rem
- `.-bottom-1.2` - Negativer Abstand unten 0rem
- `.-bottom-1.1` - Negativer Abstand unten 0rem
- `.-bottom-1` - Negativer Abstand unten 1rem
- `.-bottom-0.9` - Negativer Abstand unten 0rem
- `.-bottom-0.8` - Negativer Abstand unten 0rem
- `.-bottom-0.7` - Negativer Abstand unten 0rem
- `.-bottom-0.6` - Negativer Abstand unten 0rem
- `.-bottom-0.5` - Negativer Abstand unten 0rem
- `.-bottom-0.4` - Negativer Abstand unten 0rem
- `.-bottom-0.3` - Negativer Abstand unten 0.3rem
- `.-bottom-0.2` - Negativer Abstand unten 0.2rem
- `.-bottom-0.1` - Negativer Abstand unten 0.1rem
- `.hover:-bottom-5` - Negativer Abstand unten 5rem beim Hover
- `.hover:-bottom-4.5` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-4` - Negativer Abstand unten 4rem beim Hover
- `.hover:-bottom-3.5` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-3` - Negativer Abstand unten 3rem beim Hover
- `.hover:-bottom-2.5` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-2` - Negativer Abstand unten 2rem beim Hover
- `.hover:-bottom-1.9` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.8` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.7` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.6` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.5` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.4` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.3` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.2` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1.1` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-1` - Negativer Abstand unten 1rem beim Hover
- `.hover:-bottom-0.9` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-0.8` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-0.7` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-0.6` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-0.5` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-0.4` - Negativer Abstand unten 0rem beim Hover
- `.hover:-bottom-0.3` - Negativer Abstand unten 0.3rem beim Hover
- `.hover:-bottom-0.2` - Negativer Abstand unten 0.2rem beim Hover
- `.hover:-bottom-0.1` - Negativer Abstand unten 0.1rem beim Hover

### Left

- `.hover:left-100` - Abstand links 100 % beim Hover
- `.hover:left-75` - Abstand links 75 % beim Hover
- `.hover:left-50` - Abstand links 50 % beim Hover
- `.hover:left-25` - Abstand links 25 % beim Hover
- `.hover:left-5` - Abstand links 5rem beim Hover
- `.hover:left-4.5` - Abstand links 0rem beim Hover
- `.hover:left-4` - Abstand links 4rem beim Hover
- `.hover:left-3.5` - Abstand links 0rem beim Hover
- `.hover:left-3` - Abstand links 3rem beim Hover
- `.hover:left-2.5` - Abstand links 0rem beim Hover
- `.hover:left-2` - Abstand links 2rem beim Hover
- `.hover:left-1.9` - Abstand links 0rem beim Hover
- `.hover:left-1.8` - Abstand links 0rem beim Hover
- `.hover:left-1.7` - Abstand links 0rem beim Hover
- `.hover:left-1.6` - Abstand links 0rem beim Hover
- `.hover:left-1.5` - Abstand links 0rem beim Hover
- `.hover:left-1.4` - Abstand links 0rem beim Hover
- `.hover:left-1.3` - Abstand links 0rem beim Hover
- `.hover:left-1.2` - Abstand links 0rem beim Hover
- `.hover:left-1.1` - Abstand links 0rem beim Hover
- `.hover:left-1` - Abstand links 1rem beim Hover
- `.hover:left-0.9` - Abstand links 0rem beim Hover
- `.hover:left-0.8` - Abstand links 0rem beim Hover
- `.hover:left-0.7` - Abstand links 0rem beim Hover
- `.hover:left-0.6` - Abstand links 0rem beim Hover
- `.hover:left-0.5` - Abstand links 0rem beim Hover
- `.hover:left-0.4` - Abstand links 0rem beim Hover
- `.hover:left-0.3` - Abstand links 0rem beim Hover
- `.hover:left-0.2` - Abstand links 0.2rem beim Hover
- `.hover:left-0.1` - Abstand links 0.1rem beim Hover
- `.hover:left-0` - Abstand links 0rem beim Hover
- `.left-100` - Abstand links 100 %
- `.left-75` - Abstand links 75 %
- `.left-50` - Abstand links 50 %
- `.left-25` - Abstand links 25 %
- `.left-5` - Abstand links 5rem
- `.left-4.5` - Abstand links 0rem
- `.left-4` - Abstand links 4rem
- `.left-3.5` - Abstand links 0rem
- `.left-3` - Abstand links 3rem
- `.left-2.5` - Abstand links 0rem
- `.left-2` - Abstand links 2rem
- `.left-1.9` - Abstand links 0rem
- `.left-1.8` - Abstand links 0rem
- `.left-1.7` - Abstand links 0rem
- `.left-1.6` - Abstand links 0rem
- `.left-1.5` - Abstand links 0rem
- `.left-1.4` - Abstand links 0rem
- `.left-1.3` - Abstand links 0rem
- `.left-1.2` - Abstand links 0rem
- `.left-1.1` - Abstand links 0rem
- `.left-1` - Abstand links 1rem
- `.left-0.9` - Abstand links 0rem
- `.left-0.8` - Abstand links 0rem
- `.left-0.7` - Abstand links 0rem
- `.left-0.6` - Abstand links 0rem
- `.left-0.5` - Abstand links 0rem
- `.left-0.4` - Abstand links 0rem
- `.left-0.3` - Abstand links 0rem
- `.left-0.2` - Abstand links 0.2rem
- `.left-0.1` - Abstand links 0.1rem
- `.left-0` - Abstand links 0rem

##### Negative Left

- `.-left-5` - Negativer Abstand links 5rem
- `.-left-4.5` - Negativer Abstand links 0rem
- `.-left-4` - Negativer Abstand links 4rem
- `.-left-3.5` - Negativer Abstand links 0rem
- `.-left-3` - Negativer Abstand links 3rem
- `.-left-2.5` - Negativer Abstand links 0rem
- `.-left-2` - Negativer Abstand links 2rem
- `.-left-1.9` - Negativer Abstand links 0rem
- `.-left-1.8` - Negativer Abstand links 0rem
- `.-left-1.7` - Negativer Abstand links 0rem
- `.-left-1.6` - Negativer Abstand links 0rem
- `.-left-1.5` - Negativer Abstand links 0rem
- `.-left-1.4` - Negativer Abstand links 0rem
- `.-left-1.3` - Negativer Abstand links 0rem
- `.-left-1.2` - Negativer Abstand links 0rem
- `.-left-1.1` - Negativer Abstand links 0rem
- `.-left-1` - Negativer Abstand links 1rem
- `.-left-0.9` - Negativer Abstand links 0rem
- `.-left-0.8` - Negativer Abstand links 0rem
- `.-left-0.7` - Negativer Abstand links 0rem
- `.-left-0.6` - Negativer Abstand links 0rem
- `.-left-0.5` - Negativer Abstand links 0rem
- `.-left-0.4` - Negativer Abstand links 0rem
- `.-left-0.3` - Negativer Abstand links 0.3rem
- `.-left-0.2` - Negativer Abstand links 0.2rem
- `.-left-0.1` - Negativer Abstand links 0.1rem
- `.hover:-left-5` - Negativer Abstand links 5rem beim Hover
- `.hover:-left-4.5` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-4` - Negativer Abstand links 4rem beim Hover
- `.hover:-left-3.5` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-3` - Negativer Abstand links 3rem beim Hover
- `.hover:-left-2.5` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-2` - Negativer Abstand links 2rem beim Hover
- `.hover:-left-1.9` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.8` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.7` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.6` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.5` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.4` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.3` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.2` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1.1` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-1` - Negativer Abstand links 1rem beim Hover
- `.hover:-left-0.9` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-0.8` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-0.7` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-0.6` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-0.5` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-0.4` - Negativer Abstand links 0rem beim Hover
- `.hover:-left-0.3` - Negativer Abstand links 0.3rem beim Hover
- `.hover:-left-0.2` - Negativer Abstand links 0.2rem beim Hover
- `.hover:-left-0.1` - Negativer Abstand links 0.1rem beim Hover

### Z-Index

- `.hover:z-5` - Z-Index 1005 beim Schweben
- `.hover:z-4` - Z-Index 1004 beim Schweben
- `.hover:z-3` - Z-Index 1003 beim Schweben
- `.hover:z-2` - Z-Index 1002 beim Schweben
- `.hover:z-1` - Z-Index 1001 beim Schweben
- `.hover:z-0` - Z-Index 0 beim Schweben
- `.hover:z-auto` - Z-Index automatisch beim Schweben
- `.z-5` - Z-Index 1005
- `.z-4` - Z-Index 1004
- `.z-3` - Z-Index 1003
- `.z-2` - Z-Index 1002
- `.z-1` - Z-Index 1001
- `.z-0` - Z-Index 0
- `.z-auto` - Z-Index automatisch

##### Negative Z-Index

- `.-z-5` - Negativer Z-Index 5
- `.-z-4` - Negativer Z-Index 4
- `.-z-3` - Negativer Z-Index 3
- `.-z-2` - Negativer Z-Index 2
- `.-z-1` - Negativer Z-Index 1
- `.hover:-z-5` - Negativer Z-Index 5 beim Schweben
- `.hover:-z-4` - Negativer Z-Index 4 beim Schweben
- `.hover:-z-3` - Negativer Z-Index 3 beim Schweben
- `.hover:-z-2` - Negativer Z-Index 2 beim Schweben
- `.hover:-z-1` - Negativer Z-Index 1 beim Schweben

## Typography

### Font

- `.font-italic` - Schriftart kursiv
- `.font-normal` - Schriftart normal
- `.hover:font-italic` - Schriftart kursiv beim Hover
- `.hover:font-normal` - Schriftart beim Hover normal

### Font Size

- `.font-size-10` - Schriftgröße 10rem
- `.font-size-9.5` - Schriftgröße 0rem
- `.font-size-9` - Schriftgröße 9rem
- `.font-size-8.5` - Schriftgröße 0rem
- `.font-size-8` - Schriftgröße 8rem
- `.font-size-7.5` - Schriftgröße 0rem
- `.font-size-7` - Schriftgröße 7rem
- `.font-size-6.5` - Schriftgröße 0rem
- `.font-size-6` - Schriftgröße 6rem
- `.font-size-5.5` - Schriftgröße 0rem
- `.font-size-5` - Schriftgröße 5rem
- `.font-size-4.5` - Schriftgröße 0rem
- `.font-size-4` - Schriftgröße 4rem
- `.font-size-3.5` - Schriftgröße 0rem
- `.font-size-3` - Schriftgröße 3rem
- `.font-size-2.5` - Schriftgröße 0rem
- `.font-size-2` - Schriftgröße 2rem
- `.font-size-1.9` - Schriftgröße 0rem
- `.font-size-1.8` - Schriftgröße 0rem
- `.font-size-1.7` - Schriftgröße 0rem
- `.font-size-1.6` - Schriftgröße 0rem
- `.font-size-1.5` - Schriftgröße 0rem
- `.font-size-1.4` - Schriftgröße 0rem
- `.font-size-1.3` - Schriftgröße 0rem
- `.font-size-1.2` - Schriftgröße 0rem
- `.font-size-1.1` - Schriftgröße 0rem
- `.font-size-1` - Schriftgröße 1rem
- `.font-size-0.9` - Schriftgröße 0rem
- `.font-size-0.8` - Schriftgröße 0rem
- `.font-size-0.7` - Schriftgröße 0,7rem
- `.font-size-0.6` - Schriftgröße 0,6rem
- `.font-size-0.5` - Schriftgröße 0,5rem
- `.hover:font-size-10` - Schriftgröße 10rem beim Schweben
- `.hover:font-size-9.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-9` - Schriftgröße 9rem beim Hover
- `.hover:font-size-8.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-8` - Schriftgröße 8rem beim Schweben
- `.hover:font-size-7.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-7` - Schriftgröße 7rem beim Hover
- `.hover:font-size-6.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-6` - Schriftgröße 6rem beim Hover
- `.hover:font-size-5.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-5` - Schriftgröße 5rem beim Schweben
- `.hover:font-size-4.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-4` - Schriftgröße 4rem beim Schweben
- `.hover:font-size-3.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-3` - Schriftgröße 3rem beim Hover
- `.hover:font-size-2.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-2` - Schriftgröße 2rem beim Hover
- `.hover:font-size-1.9` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.8` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.7` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.6` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.5` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.4` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.3` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.2` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1.1` - Schriftgröße 0rem beim Hover
- `.hover:font-size-1` - Schriftgröße 1rem beim Hover
- `.hover:font-size-0.9` - Schriftgröße 0rem beim Hover
- `.hover:font-size-0.8` - Schriftgröße 0rem beim Hover
- `.hover:font-size-0.7` - Schriftgröße 0,7rem beim Schweben
- `.hover:font-size-0.6` - Schriftgröße 0,6rem beim Schweben
- `.hover:font-size-0.5` - Schriftgröße 0,5rem beim Schweben

### Font Weight

- `.font-weight-900` - Schriftstärke 900
- `.font-weight-800` - Schriftstärke 800
- `.font-weight-700` - Schriftstärke 700
- `.font-weight-600` - Schriftstärke 600
- `.font-weight-500` - Schriftstärke 500
- `.font-weight-400` - Schriftstärke 400
- `.font-weight-300` - Schriftstärke 300
- `.font-weight-200` - Schriftstärke 200
- `.font-weight-100` - Schriftstärke 100
- `.font-weight-bold` - Schriftstärke fett
- `.hover:font-weight-900` - Schriftstärke 900 beim Schweben
- `.hover:font-weight-800` - Schriftstärke 800 beim Schweben
- `.hover:font-weight-700` - Schriftstärke 700 beim Schweben
- `.hover:font-weight-600` - Schriftstärke 600 beim Schweben
- `.hover:font-weight-500` - Schriftstärke 500 beim Schweben
- `.hover:font-weight-400` - Schriftstärke 400 beim Schweben
- `.hover:font-weight-300` - Schriftstärke 300 beim Schweben
- `.hover:font-weight-200` - Schriftstärke 200 beim Schweben
- `.hover:font-weight-100` - Schriftstärke 100 beim Schweben
- `.hover:font-weight-bold` - Schriftstärke fett beim Schweben

### Letter spacing

- `.hover:letter-spacing-1` - Buchstabenabstand 1rem beim Schweben
- `.hover:letter-spacing-0.9` - Buchstabenabstand 0rem beim Schweben
- `.hover:letter-spacing-0.8` - Buchstabenabstand 0rem beim Schweben
- `.hover:letter-spacing-0.7` - Buchstabenabstand 0rem beim Schweben
- `.hover:letter-spacing-0.6` - Buchstabenabstand 0rem beim Schweben
- `.hover:letter-spacing-0.5` - Buchstabenabstand 0rem beim Schweben
- `.hover:letter-spacing-0.4` - Buchstabenabstand 0rem beim Schweben
- `.hover:letter-spacing-0.3` - Buchstabenabstand 0,3rem beim Schweben
- `.hover:letter-spacing-0.2` - Buchstabenabstand 0,2rem beim Schweben
- `.hover:letter-spacing-0.1` - Buchstabenabstand 0,1rem beim Schweben
- `.letter-spacing-1` - Buchstabenabstand 1rem
- `.letter-spacing-0.9` - Buchstabenabstand 0rem
- `.letter-spacing-0.8` - Buchstabenabstand 0rem
- `.letter-spacing-0.7` - Buchstabenabstand 0rem
- `.letter-spacing-0.6` - Buchstabenabstand 0rem
- `.letter-spacing-0.5` - Buchstabenabstand 0rem
- `.letter-spacing-0.4` - Buchstabenabstand 0rem
- `.letter-spacing-0.3` - Buchstabenabstand 0,3rem
- `.letter-spacing-0.2` - Buchstabenabstand 0,2rem
- `.letter-spacing-0.1` - Buchstabenabstand 0,1rem

### Line height

- `.hover:line-height-5` - Zeilenhöhe 5rem beim Hover
- `.hover:line-height-4` - Zeilenhöhe 4rem beim Hover
- `.hover:line-height-3` - Zeilenhöhe 3rem beim Hover
- `.hover:line-height-2` - Zeilenhöhe 2rem beim Hover
- `.hover:line-height-1` - Zeilenhöhe 1rem beim Hover
- `.line-height-5` - Zeilenhöhe 5rem
- `.line-height-4` - Zeilenhöhe 4rem
- `.line-height-3` - Zeilenhöhe 3rem
- `.line-height-2` - Zeilenhöhe 2rem
- `.line-height-1` - Zeilenhöhe 1rem

### Text

- `.hover:text-capitalize` - Text wird beim Schweben groß geschrieben
- `.hover:text-center` - Text zentriert beim Hover
- `.hover:text-end` - Text am Ende ausgerichtet beim Hover
- `.hover:text-justify` - Text im Blocksatz beim Hover
- `.hover:text-left` - Text linksbündig beim Hover
- `.hover:text-line-none` - Beim Hover gibt es keine Textzeile
- `.hover:text-line-overline` - Textzeile überstreicht beim Hover
- `.hover:text-line-through` - Durchgestrichener Text beim Hover
- `.hover:text-line-underline` - Text zeilenweise unterstreichen, wenn Sie den Mauszeiger darüber bewegen
- `.hover:text-lowercase` - Text beim Schweben in Kleinbuchstaben schreiben
- `.hover:text-right` - Text rechtsbündig beim Hover
- `.hover:text-start` - Text am Anfang ausgerichtet beim Hover
- `.hover:text-transparent` - Text beim Schweben transparent
- `.hover:text-uppercase` - Text beim Hover in Großbuchstaben schreiben
- `.text-break-all` - Text-Break-All
- `.text-break-keep-all` - Text Break-Keep-All
- `.text-break-normal` - Textunterbrechung normal
- `.text-break-word` - Textumbruchwort
- `.text-capitalize` - Text groß schreiben
- `.text-center` - Text zentriert
- `.text-end` - Text am Ende ausgerichtet
- `.text-justify` - Text im Blocksatz
- `.text-left` - Text linksbündig
- `.text-line-none` - Textzeile – keine
- `.text-line-overline` - Text zeilenweise überstreichen
- `.text-line-through` - Durchgestrichener Text
- `.text-line-underline` - Text zeilenweise unterstreichen
- `.text-lowercase` - Text in Kleinbuchstaben
- `.text-overflow-clip` - Textüberlauf-Clip
- `.text-overflow-ellipsis` - Textüberlauf-Auslassungspunkte
- `.text-right` - Text rechtsbündig
- `.text-start` - Text am Anfang ausgerichtet
- `.text-transparent` - Text transparent
- `.text-uppercase` - Text in Großbuchstaben

##### Text - Mobile (<= 480px)

- `.hover:mobile:text-center` - Text zentriert beim Hover auf Mobilgeräten
- `.hover:mobile:text-end` - Text am Ende ausgerichtet beim Hover auf Mobilgeräten
- `.hover:mobile:text-justify` - Text im Blocksatz beim Hover auf Mobilgeräten
- `.hover:mobile:text-left` - Text linksbündig beim Hover auf Mobilgeräten
- `.hover:mobile:text-right` - Text rechtsbündig beim Hover auf Mobilgeräten
- `.hover:mobile:text-start` - Text am Anfang ausgerichtet beim Hover auf Mobilgeräten
- `.mobile:text-center` - Text zentriert auf Mobilgeräten
- `.mobile:text-end` - Text am Ende ausgerichtet auf Mobilgeräten
- `.mobile:text-justify` - Text im Blocksatz auf Mobilgeräten
- `.mobile:text-left` - Text linksbündig auf Mobilgeräten
- `.mobile:text-right` - Text rechtsbündig auf Mobilgeräten
- `.mobile:text-start` - Text am Anfang ausgerichtet auf Mobilgeräten

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - Text zentriert beim Hover auf Tablets
- `.hover:tablet:text-end` - Text am Ende ausgerichtet beim Hover auf Tablets
- `.hover:tablet:text-justify` - Text im Blocksatz beim Hover auf Tablets
- `.hover:tablet:text-left` - Text linksbündig beim Hover auf Tablets
- `.hover:tablet:text-right` - Text rechtsbündig beim Hover auf Tablets
- `.hover:tablet:text-start` - Text am Anfang ausgerichtet beim Hover auf Tablets
- `.tablet:text-center` - Text zentriert auf Tablets
- `.tablet:text-end` - Text am Ende ausgerichtet auf Tablets
- `.tablet:text-justify` - Text im Blocksatz auf Tablets
- `.tablet:text-left` - Text linksbündig auf Tablets
- `.tablet:text-right` - Text rechtsbündig auf Tablets
- `.tablet:text-start` - Text am Anfang ausgerichtet auf Tablets

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - Text zentriert beim Hover auf Tablet-PCs
- `.hover:tablet-pc:text-end` - Text am Ende ausgerichtet beim Hover auf Tablet-PCs
- `.hover:tablet-pc:text-justify` - Text im Blocksatz beim Hover auf Tablet-PCs
- `.hover:tablet-pc:text-left` - Text linksbündig beim Hover auf Tablet-PCs
- `.hover:tablet-pc:text-right` - Text rechtsbündig beim Hover auf Tablet-PCs
- `.hover:tablet-pc:text-start` - Text am Anfang ausgerichtet beim Hover auf Tablet-PCs
- `.tablet-pc:text-center` - Text zentriert auf Tablet-PCs
- `.tablet-pc:text-end` - Text am Ende ausgerichtet auf Tablet-PCs
- `.tablet-pc:text-justify` - Text im Blocksatz auf Tablet-PCs
- `.tablet-pc:text-left` - Text linksbündig auf Tablet-PCs
- `.tablet-pc:text-right` - Text rechtsbündig auf Tablet-PCs
- `.tablet-pc:text-start` - Text am Anfang ausgerichtet auf Tablet-PCs

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - Text zentriert beim Hover auf dem PC
- `.hover:pc:text-end` - Text am Ende ausgerichtet beim Hover auf dem PC
- `.hover:pc:text-justify` - Text im Blocksatz beim Hover auf dem PC
- `.hover:pc:text-left` - Text linksbündig beim Hover auf dem PC
- `.hover:pc:text-right` - Text rechtsbündig beim Hover auf dem PC
- `.hover:pc:text-start` - Text am Anfang ausgerichtet beim Hover auf dem PC
- `.pc:text-center` - Text zentriert auf dem PC
- `.pc:text-end` - Text am Ende ausgerichtet auf dem PC
- `.pc:text-justify` - Text im Blocksatz auf dem PC
- `.pc:text-left` - Text linksbündig auf dem PC
- `.pc:text-right` - Text rechtsbündig auf dem PC
- `.pc:text-start` - Text am Anfang ausgerichtet auf dem PC

##### Text - Tv (>= 1200px)

- `.hover:tv:text-center` - Text zentriert beim Hover auf dem TV
- `.hover:tv:text-end` - Text am Ende ausgerichtet beim Hover auf dem TV
- `.hover:tv:text-justify` - Text im Blocksatz beim Hover auf dem TV
- `.hover:tv:text-left` - Text linksbündig beim Hover auf dem TV
- `.hover:tv:text-right` - Text rechtsbündig beim Hover auf dem TV
- `.hover:tv:text-start` - Text am Anfang ausgerichtet beim Hover auf dem TV
- `.tv:text-center` - Text zentriert auf dem TV
- `.tv:text-end` - Text am Ende ausgerichtet auf dem TV
- `.tv:text-justify` - Text im Blocksatz auf dem TV
- `.tv:text-left` - Text linksbündig auf dem TV
- `.tv:text-right` - Text rechtsbündig auf dem TV
- `.tv:text-start` - Text am Anfang ausgerichtet auf dem TV

##### Text - Tablet Max (<= 768px)

- `.hover:tablet-max:text-center` - Text zentriert beim Hover auf Tablets (max.)
- `.hover:tablet-max:text-end` - Text am Ende ausgerichtet beim Hover auf Tablets (max.)
- `.hover:tablet-max:text-justify` - Text im Blocksatz beim Hover auf Tablets (max.)
- `.hover:tablet-max:text-left` - Text linksbündig beim Hover auf Tablets (max.)
- `.hover:tablet-max:text-right` - Text rechtsbündig beim Hover auf Tablets (max.)
- `.hover:tablet-max:text-start` - Text am Anfang ausgerichtet beim Hover auf Tablets (max.)
- `.tablet-max:text-center` - Text zentriert auf Tablets (max.)
- `.tablet-max:text-end` - Text am Ende ausgerichtet auf Tablets (max.)
- `.tablet-max:text-justify` - Text im Blocksatz auf Tablets (max.)
- `.tablet-max:text-left` - Text linksbündig auf Tablets (max.)
- `.tablet-max:text-right` - Text rechtsbündig auf Tablets (max.)
- `.tablet-max:text-start` - Text am Anfang ausgerichtet auf Tablets (max.)

##### Text - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:text-center` - Text zentriert beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:text-end` - Text am Ende ausgerichtet beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:text-justify` - Text im Blocksatz beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:text-left` - Text linksbündig beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:text-right` - Text rechtsbündig beim Hover auf Tablet-PCs (max.)
- `.hover:tablet-pc-max:text-start` - Text am Anfang ausgerichtet beim Hover auf Tablet-PCs (max.)
- `.tablet-pc-max:text-center` - Text zentriert auf Tablet-PCs (max.)
- `.tablet-pc-max:text-end` - Text am Ende ausgerichtet auf Tablet-PCs (max.)
- `.tablet-pc-max:text-justify` - Text im Blocksatz auf Tablet-PCs (max.)
- `.tablet-pc-max:text-left` - Text linksbündig auf Tablet-PCs (max.)
- `.tablet-pc-max:text-right` - Text rechtsbündig auf Tablet-PCs (max.)
- `.tablet-pc-max:text-start` - Text am Anfang ausgerichtet auf Tablet-PCs (max.)

##### Text - Pc Max (<= 1200px)

- `.hover:pc-max:text-center` - Text zentriert beim Hover auf dem PC (max.)
- `.hover:pc-max:text-end` - Text am Ende ausgerichtet beim Hover auf dem PC (max.)
- `.hover:pc-max:text-justify` - Text im Blocksatz beim Hover auf dem PC (max.)
- `.hover:pc-max:text-left` - Text linksbündig beim Hover auf dem PC (max.)
- `.hover:pc-max:text-right` - Text rechtsbündig beim Hover auf dem PC (max.)
- `.hover:pc-max:text-start` - Text am Anfang ausgerichtet beim Hover auf dem PC (max.)
- `.pc-max:text-center` - Text zentriert auf dem PC (max.)
- `.pc-max:text-end` - Text am Ende ausgerichtet auf dem PC (max.)
- `.pc-max:text-justify` - Text im Blocksatz auf dem PC (max.)
- `.pc-max:text-left` - Text linksbündig auf dem PC (max.)
- `.pc-max:text-right` - Text rechtsbündig auf dem PC (max.)
- `.pc-max:text-start` - Text am Anfang ausgerichtet auf dem PC (max.)

### Whitespace

- `.hover:whitespace-normal` - Leerzeichen beim Schweben normal
- `.whitespace-normal` - Leerzeichen normal
- `.whitespace-nowrap` - Leerzeichen-Nowrap
- `.whitespace-pre` - Leerzeichen vor

### Whitespace break

- `.hover:whitespace-break-spaces` - Leerzeichen unterbrechen Leerzeichen beim Schweben
- `.whitespace-break-spaces` - Leerzeichen unterbrechen Leerzeichen

### Whitespace pre

- `.hover:whitespace-pre-line` - Leerzeichen vor der Zeile beim Schweben
- `.hover:whitespace-pre-wrap` - Leerzeichen vor dem Umbruch beim Hover
- `.whitespace-pre-line` - Leerzeichen vor der Zeile
- `.whitespace-pre-wrap` - Leerzeichen vor dem Umbruch

### Writing h

- `.writing-h-tb` - Schreiben h tb

### Writing v

- `.writing-v-lr` - Schreiben v lr
- `.writing-v-rl` - Schreiben v rl

## Backgrounds

### Background

- `.bg-transparent` - Hintergrund transparent
- `.hover:bg-transparent` - Hintergrund transparent beim Schweben

### Bg blur

- `.bg-blur-5` - Hintergrundunschärfe 24px
- `.bg-blur-4` - Hintergrundunschärfe 16px
- `.bg-blur-3` - Hintergrundunschärfe 12px
- `.bg-blur-2` - Hintergrundunschärfe 8px
- `.bg-blur-1` - Hintergrundunschärfe 4px
- `.bg-blur-0` - Hintergrundunschärfe 0px
- `.hover:bg-blur-5` - Hintergrundunschärfe 24px beim Schweben
- `.hover:bg-blur-4` - Hintergrundunschärfe 16px beim Schweben
- `.hover:bg-blur-3` - Hintergrundunschärfe 12px beim Schweben
- `.hover:bg-blur-2` - Hintergrundunschärfe 8px beim Schweben
- `.hover:bg-blur-1` - Hintergrundunschärfe 4px beim Schweben
- `.hover:bg-blur-0` - Hintergrundunschärfe 0px beim Schweben

## Borders

### Border

#### Border All

- `.border-2` - Rahmen alle Seiten 2rem
- `.border-1.5` - Rahmen alle Seiten 0rem
- `.border-1` - Rahmen alle Seiten 1rem
- `.border-0.9` - Rahmen alle Seiten 0rem
- `.border-0.8` - Rahmen alle Seiten 0rem
- `.border-0.7` - Rahmen alle Seiten 0rem
- `.border-0.6` - Rahmen alle Seiten 0rem
- `.border-0.5` - Rahmen alle Seiten 0rem
- `.border-0.4` - Rahmen alle Seiten 0.4rem
- `.border-0.3` - Rahmen alle Seiten 0rem
- `.border-0.2` - Rahmen alle Seiten 0.2rem
- `.border-0.1` - Rahmen alle Seiten 0.1rem
- `.border-0` - Rahmen alle Seiten 0rem
- `.hover:border-2` - Rahmen alle Seiten 2rem beim Hover
- `.hover:border-1.5` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-1` - Rahmen alle Seiten 1rem beim Hover
- `.hover:border-0.9` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.8` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.7` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.6` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.5` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.4` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.3` - Rahmen alle Seiten 0rem beim Hover
- `.hover:border-0.2` - Rahmen alle Seiten 0.2rem beim Hover
- `.hover:border-0.1` - Rahmen alle Seiten 0.1rem beim Hover
- `.hover:border-0` - Rahmen alle Seiten 0rem beim Hover

#### Border Bottom

- `.border-b-2` - Rahmen unten 2rem
- `.border-b-1.5` - Rahmen unten 0rem
- `.border-b-1` - Rahmen unten 1rem
- `.border-b-0.9` - Rahmen unten 0rem
- `.border-b-0.8` - Rahmen unten 0rem
- `.border-b-0.7` - Rahmen unten 0rem
- `.border-b-0.6` - Rahmen unten 0rem
- `.border-b-0.5` - Rahmen unten 0.5rem
- `.border-b-0.4` - Rahmen unten 0rem
- `.border-b-0.3` - Rahmen unten 0rem
- `.border-b-0.2` - Rahmen unten 0.2rem
- `.border-b-0.1` - Rahmen unten 0.1rem
- `.border-b-0` - Rahmen unten 0rem
- `.hover:border-b-2` - Rahmen unten 2rem beim Hover
- `.hover:border-b-1.5` - Rahmen unten 0rem beim Hover
- `.hover:border-b-1` - Rahmen unten 1rem beim Hover
- `.hover:border-b-0.9` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.8` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.7` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.6` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.5` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.4` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.3` - Rahmen unten 0rem beim Hover
- `.hover:border-b-0.2` - Rahmen unten 0.2rem beim Hover
- `.hover:border-b-0.1` - Rahmen unten 0.1rem beim Hover
- `.hover:border-b-0` - Rahmen unten 0rem beim Hover

#### Border Left

- `.border-l-2` - Rahmen links 2rem
- `.border-l-1.5` - Rahmen links 0rem
- `.border-l-1` - Rahmen links 1rem
- `.border-l-0.9` - Rahmen links 0rem
- `.border-l-0.8` - Rahmen links 0rem
- `.border-l-0.7` - Rahmen links 0rem
- `.border-l-0.6` - Rahmen links 0rem
- `.border-l-0.5` - Rahmen links 0rem
- `.border-l-0.4` - Rahmen links 0rem
- `.border-l-0.3` - Rahmen links 0rem
- `.border-l-0.2` - Rahmen links 0.2rem
- `.border-l-0.1` - Rahmen links 0.1rem
- `.border-l-0` - Rahmen links 0rem
- `.hover:border-l-2` - Rahmen links 2rem beim Hover
- `.hover:border-l-1.5` - Rahmen links 0rem beim Hover
- `.hover:border-l-1` - Rahmen links 1rem beim Hover
- `.hover:border-l-0.9` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.8` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.7` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.6` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.5` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.4` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.3` - Rahmen links 0rem beim Hover
- `.hover:border-l-0.2` - Rahmen links 0.2rem beim Hover
- `.hover:border-l-0.1` - Rahmen links 0.1rem beim Hover
- `.hover:border-l-0` - Rahmen links 0rem beim Hover

#### Border Right

- `.border-r-2` - Rahmen rechts 2rem
- `.border-r-1.5` - Rahmen rechts 0rem
- `.border-r-1` - Rahmen rechts 1rem
- `.border-r-0.9` - Rahmen rechts 0rem
- `.border-r-0.8` - Rahmen rechts 0rem
- `.border-r-0.7` - Rahmen rechts 0rem
- `.border-r-0.6` - Rahmen rechts 0rem
- `.border-r-0.5` - Rahmen rechts 0rem
- `.border-r-0.4` - Rahmen rechts 0rem
- `.border-r-0.3` - Rahmen rechts 0rem
- `.border-r-0.2` - Rahmen rechts 0.2rem
- `.border-r-0.1` - Rahmen rechts 0.1rem
- `.border-r-0` - Rahmen rechts 0rem
- `.hover:border-r-2` - Rahmen rechts 2rem beim Hover
- `.hover:border-r-1.5` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-1` - Rahmen rechts 1rem beim Hover
- `.hover:border-r-0.9` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.8` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.7` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.6` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.5` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.4` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.3` - Rahmen rechts 0rem beim Hover
- `.hover:border-r-0.2` - Rahmen rechts 0.2rem beim Hover
- `.hover:border-r-0.1` - Rahmen rechts 0.1rem beim Hover
- `.hover:border-r-0` - Rahmen rechts 0rem beim Hover

#### Border Top

- `.border-t-2` - Rahmen oben 2rem
- `.border-t-1.5` - Rahmen oben 0rem
- `.border-t-1` - Rahmen oben 1rem
- `.border-t-0.9` - Rahmen oben 0rem
- `.border-t-0.8` - Rahmen oben 0rem
- `.border-t-0.7` - Rahmen oben 0rem
- `.border-t-0.6` - Rahmen oben 0rem
- `.border-t-0.5` - Rahmen oben 0rem
- `.border-t-0.4` - Rahmen oben 0rem
- `.border-t-0.3` - Rahmen oben 0rem
- `.border-t-0.2` - Rahmen oben 0.2rem
- `.border-t-0.1` - Rahmen oben 0.1rem
- `.border-t-0` - Rahmen oben 0rem
- `.hover:border-t-2` - Rahmen oben 2rem beim Hover
- `.hover:border-t-1.5` - Rahmen oben 0rem beim Hover
- `.hover:border-t-1` - Rahmen oben 1rem beim Hover
- `.hover:border-t-0.9` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.8` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.7` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.6` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.5` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.4` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.3` - Rahmen oben 0rem beim Hover
- `.hover:border-t-0.2` - Rahmen oben 0.2rem beim Hover
- `.hover:border-t-0.1` - Rahmen oben 0.1rem beim Hover
- `.hover:border-t-0` - Rahmen oben 0rem beim Hover

#### Border X-Axis

- `.border-x-2` - Rahmen X-Achse 2rem
- `.border-x-1.5` - Rahmen X-Achse 0rem
- `.border-x-1` - Rahmen X-Achse 1rem
- `.border-x-0.9` - Rahmen X-Achse 0rem
- `.border-x-0.8` - Rahmen X-Achse 0rem
- `.border-x-0.7` - Rahmen X-Achse 0rem
- `.border-x-0.6` - Rahmen X-Achse 0rem
- `.border-x-0.5` - Rahmen X-Achse 0rem
- `.border-x-0.4` - Rahmen X-Achse 0rem
- `.border-x-0.3` - Rahmen X-Achse 0rem
- `.border-x-0.2` - Rahmen X-Achse 0.2rem
- `.border-x-0.1` - Rahmen X-Achse 0.1rem
- `.border-x-0` - Rahmen X-Achse 0rem
- `.hover:border-x-2` - Rahmen X-Achse 2rem beim Hover
- `.hover:border-x-1.5` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-1` - Rahmen X-Achse 1rem beim Hover
- `.hover:border-x-0.9` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.8` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.7` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.6` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.5` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.4` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.3` - Rahmen X-Achse 0rem beim Hover
- `.hover:border-x-0.2` - Rahmen X-Achse 0.2rem beim Hover
- `.hover:border-x-0.1` - Rahmen X-Achse 0.1rem beim Hover
- `.hover:border-x-0` - Rahmen X-Achse 0rem beim Hover

#### Border Y-Axis

- `.border-y-2` - Rahmen Y-Achse 2rem
- `.border-y-1.5` - Rahmen Y-Achse 0rem
- `.border-y-1` - Rahmen Y-Achse 1rem
- `.border-y-0.9` - Rahmen Y-Achse 0rem
- `.border-y-0.8` - Rahmen Y-Achse 0rem
- `.border-y-0.7` - Rahmen Y-Achse 0rem
- `.border-y-0.6` - Rahmen Y-Achse 0rem
- `.border-y-0.5` - Rahmen Y-Achse 0.5rem
- `.border-y-0.4` - Rahmen Y-Achse 0rem
- `.border-y-0.3` - Rahmen Y-Achse 0rem
- `.border-y-0.2` - Rahmen Y-Achse 0.2rem
- `.border-y-0.1` - Rahmen Y-Achse 0.1rem
- `.border-y-0` - Rahmen Y-Achse 0rem
- `.hover:border-y-2` - Rahmen Y-Achse 2rem beim Hover
- `.hover:border-y-1.5` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-1` - Rahmen Y-Achse 1rem beim Hover
- `.hover:border-y-0.9` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.8` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.7` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.6` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.5` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.4` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.3` - Rahmen Y-Achse 0rem beim Hover
- `.hover:border-y-0.2` - Rahmen Y-Achse 0.2rem beim Hover
- `.hover:border-y-0.1` - Rahmen Y-Achse 0.1rem beim Hover
- `.hover:border-y-0` - Rahmen Y-Achse 0rem beim Hover

### Border Radius

#### Border Radius All

- `.hover:rounded-5` - Grenzradius Alle 5rem beim Schweben
- `.hover:rounded-4.5` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-4` - Grenzradius Alle 4rem beim Schweben
- `.hover:rounded-3.5` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-3` - Grenzradius Alle 3rem beim Schweben
- `.hover:rounded-2.5` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-2` - Grenzradius Alle 2rem beim Schweben
- `.hover:rounded-1.5` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-1` - Grenzradius Alle 1rem beim Schweben
- `.hover:rounded-0.9` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.8` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.7` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.6` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.5` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.4` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.3` - Randradius Alle 0rem beim Schweben
- `.hover:rounded-0.2` - Randradius Alle 0,2rem beim Schweben
- `.hover:rounded-0.1` - Randradius Alle 0,1rem beim Schweben
- `.hover:rounded-0` - Randradius Alle 0rem beim Schweben
- `.rounded-5` - Randradius Alle 5rem
- `.rounded-4.5` - Randradius Alle 0rem
- `.rounded-4` - Randradius Alle 4rem
- `.rounded-3.5` - Randradius Alle 0rem
- `.rounded-3` - Randradius Alle 3rem
- `.rounded-2.5` - Randradius Alle 0rem
- `.rounded-2` - Randradius Alle 2rem
- `.rounded-1.5` - Randradius Alle 0rem
- `.rounded-1` - Randradius Alle 1rem
- `.rounded-0.9` - Randradius Alle 0rem
- `.rounded-0.8` - Randradius Alle 0rem
- `.rounded-0.7` - Randradius Alle 0rem
- `.rounded-0.6` - Randradius Alle 0rem
- `.rounded-0.5` - Randradius Alle 0rem
- `.rounded-0.4` - Randradius Alle 0rem
- `.rounded-0.3` - Randradius Alle 0rem
- `.rounded-0.2` - Randradius Alle 0,2rem
- `.rounded-0.1` - Randradius Alle 0,1rem
- `.rounded-0` - Randradius Alle 0rem

#### Border Radius Bottom Left

- `.hover:rounded-bl-5` - Randradius unten links 5rem beim Schweben
- `.hover:rounded-bl-4.5` - Randradius unten links 0rem beim Schweben
- `.hover:rounded-bl-4` - Randradius unten links 4rem beim Schweben
- `.hover:rounded-bl-3.5` - Randradius unten links 0rem beim Schweben
- `.hover:rounded-bl-3` - Randradius unten links 3rem beim Schweben
- `.hover:rounded-bl-2.5` - Randradius unten links 0rem beim Schweben
- `.hover:rounded-bl-2` - Randradius unten links 2rem beim Schweben
- `.hover:rounded-bl-1.5` - Randradius unten links 0rem beim Schweben
- `.hover:rounded-bl-1` - Randradius unten links 1rem beim Schweben
- `.hover:rounded-bl-0.5` - Randradius unten links 0,5rem beim Schweben
- `.hover:rounded-bl-0` - Randradius unten links 0rem beim Schweben
- `.rounded-bl-5` - Randradius unten links 5rem
- `.rounded-bl-4.5` - Randradius unten links 0rem
- `.rounded-bl-4` - Randradius unten links 4rem
- `.rounded-bl-3.5` - Randradius unten links 0rem
- `.rounded-bl-3` - Randradius unten links 3rem
- `.rounded-bl-2.5` - Randradius unten links 0rem
- `.rounded-bl-2` - Randradius unten links 2rem
- `.rounded-bl-1.5` - Randradius unten links 0rem
- `.rounded-bl-1` - Randradius unten links 1rem
- `.rounded-bl-0.5` - Randradius unten links 0,5rem
- `.rounded-bl-0` - Randradius unten links 0rem

#### Border Radius Bottom Right

- `.hover:rounded-br-5` - Randradius unten rechts 5rem beim Schweben
- `.hover:rounded-br-4.5` - Randradius unten rechts 0rem beim Schweben
- `.hover:rounded-br-4` - Randradius unten rechts 4rem beim Schweben
- `.hover:rounded-br-3.5` - Randradius unten rechts 0rem beim Schweben
- `.hover:rounded-br-3` - Randradius unten rechts 3rem beim Schweben
- `.hover:rounded-br-2.5` - Randradius unten rechts 0rem beim Schweben
- `.hover:rounded-br-2` - Randradius unten rechts 2rem beim Schweben
- `.hover:rounded-br-1.5` - Randradius unten rechts 0rem beim Schweben
- `.hover:rounded-br-1` - Randradius unten rechts 1rem beim Schweben
- `.hover:rounded-br-0.5` - Randradius unten rechts 0,5rem beim Schweben
- `.hover:rounded-br-0` - Randradius unten rechts 0rem beim Schweben
- `.rounded-br-5` - Randradius unten rechts 5rem
- `.rounded-br-4.5` - Randradius unten rechts 0rem
- `.rounded-br-4` - Randradius unten rechts 4rem
- `.rounded-br-3.5` - Randradius unten rechts 0rem
- `.rounded-br-3` - Randradius unten rechts 3rem
- `.rounded-br-2.5` - Randradius unten rechts 0rem
- `.rounded-br-2` - Randradius unten rechts 2rem
- `.rounded-br-1.5` - Randradius unten rechts 0rem
- `.rounded-br-1` - Randradius unten rechts 1rem
- `.rounded-br-0.5` - Randradius unten rechts 0,5rem
- `.rounded-br-0` - Randradius unten rechts 0rem

#### Border Radius Top Left

- `.hover:rounded-tl-5` - Randradius oben links 5rem beim Schweben
- `.hover:rounded-tl-4.5` - Randradius oben links 0rem beim Schweben
- `.hover:rounded-tl-4` - Randradius oben links 4rem beim Schweben
- `.hover:rounded-tl-3.5` - Randradius oben links 0rem beim Schweben
- `.hover:rounded-tl-3` - Randradius oben links 3rem beim Schweben
- `.hover:rounded-tl-2.5` - Randradius oben links 0rem beim Schweben
- `.hover:rounded-tl-2` - Randradius oben links 2rem beim Schweben
- `.hover:rounded-tl-1.5` - Randradius oben links 0rem beim Schweben
- `.hover:rounded-tl-1` - Randradius oben links 1rem beim Schweben
- `.hover:rounded-tl-0.5` - Randradius oben links 0,5rem beim Schweben
- `.hover:rounded-tl-0` - Randradius oben links 0rem beim Schweben
- `.rounded-tl-5` - Randradius oben links 5rem
- `.rounded-tl-4.5` - Randradius oben links 0rem
- `.rounded-tl-4` - Randradius oben links 4rem
- `.rounded-tl-3.5` - Randradius oben links 0rem
- `.rounded-tl-3` - Randradius oben links 3rem
- `.rounded-tl-2.5` - Randradius oben links 0rem
- `.rounded-tl-2` - Randradius oben links 2rem
- `.rounded-tl-1.5` - Randradius oben links 0rem
- `.rounded-tl-1` - Randradius oben links 1rem
- `.rounded-tl-0.5` - Randradius oben links 0,5rem
- `.rounded-tl-0` - Randradius oben links 0rem

#### Border Radius Top Right

- `.hover:rounded-tr-5` - Randradius oben rechts 5rem beim Schweben
- `.hover:rounded-tr-4.5` - Randradius oben rechts 0rem beim Schweben
- `.hover:rounded-tr-4` - Randradius oben rechts 4rem beim Schweben
- `.hover:rounded-tr-3.5` - Randradius oben rechts 0rem beim Schweben
- `.hover:rounded-tr-3` - Randradius oben rechts 3rem beim Schweben
- `.hover:rounded-tr-2.5` - Randradius oben rechts 0rem beim Schweben
- `.hover:rounded-tr-2` - Randradius oben rechts 2rem beim Schweben
- `.hover:rounded-tr-1.5` - Randradius oben rechts 0rem beim Schweben
- `.hover:rounded-tr-1` - Randradius oben rechts 1rem beim Schweben
- `.hover:rounded-tr-0.5` - Randradius oben rechts 0,5rem beim Schweben
- `.hover:rounded-tr-0` - Randradius oben rechts 0rem beim Schweben
- `.rounded-tr-5` - Randradius oben rechts 5rem
- `.rounded-tr-4.5` - Randradius oben rechts 0rem
- `.rounded-tr-4` - Randradius oben rechts 4rem
- `.rounded-tr-3.5` - Randradius oben rechts 0rem
- `.rounded-tr-3` - Randradius oben rechts 3rem
- `.rounded-tr-2.5` - Randradius oben rechts 0rem
- `.rounded-tr-2` - Randradius oben rechts 2rem
- `.rounded-tr-1.5` - Randradius oben rechts 0rem
- `.rounded-tr-1` - Randradius oben rechts 1rem
- `.rounded-tr-0.5` - Randradius oben rechts 0,5rem
- `.rounded-tr-0` - Randradius oben rechts 0rem

## Effects

### Box Shadow

#### Box Shadow All

- `.hover:shadow-5` - Box Shadow Alle 5rem beim Hover
- `.hover:shadow-5-1` - Box Shadow Alle 0 0 5rem 2rem beim Hover
- `.hover:shadow-4` - Box Shadow Alle 4rem beim Hover
- `.hover:shadow-4-1` - Box Shadow Alle 0 0 4rem 2rem beim Hover
- `.hover:shadow-3` - Box Shadow Alle 3rem beim Hover
- `.hover:shadow-3-1` - Box Shadow Alle 0 0 3rem 2rem beim Hover
- `.hover:shadow-2` - Box Shadow Alle 2rem beim Hover
- `.hover:shadow-2-1` - Box Shadow Alle 0 0 2rem 2rem beim Schweben
- `.hover:shadow-1` - Box Shadow Alle 1rem beim Hover
- `.hover:shadow-1-1` - Box Shadow Alle 0 0 1rem 2rem beim Schweben
- `.hover:shadow-none` - Box Shadow Alle keine beim Schweben
- `.shadow-5` - Box Shadow Alle 5rem
- `.shadow-5-1` - Box Shadow Alle 0 0 5rem 2rem
- `.shadow-4` - Box Shadow Alle 4rem
- `.shadow-4-1` - Box Shadow Alle 0 0 4rem 2rem
- `.shadow-3` - Box Shadow Alle 3rem
- `.shadow-3-1` - Box Shadow Alle 0 0 3rem 2rem
- `.shadow-2` - Box Shadow Alle 2rem
- `.shadow-2-1` - Box Shadow Alle 0 0 2rem 2rem
- `.shadow-1` - Box Shadow Alle 1rem
- `.shadow-1-1` - Box Shadow Alle 0 0 1rem 2rem
- `.shadow-none` - Box Shadow Alle keine

#### Box Shadow Bottom

- `.hover:shadow-b-10` - Box-Shadow unten 10rem beim Hover
- `.hover:shadow-b-9` - Box-Shadow unten 9rem beim Hover
- `.hover:shadow-b-8` - Box-Shadow unten 8rem beim Hover
- `.hover:shadow-b-7` - Box-Shadow unten 7rem beim Hover
- `.hover:shadow-b-6` - Box-Shadow unten 6rem beim Hover
- `.hover:shadow-b-5` - Box-Shadow unten 5rem beim Hover
- `.hover:shadow-b-4` - Box-Shadow unten 4rem beim Hover
- `.hover:shadow-b-3` - Box-Shadow unten 3rem beim Hover
- `.hover:shadow-b-2` - Box-Shadow unten 2rem beim Hover
- `.hover:shadow-b-1` - Box-Shadow unten 1rem beim Hover
- `.shadow-b-10` - Box-Shadow unten 10rem
- `.shadow-b-9` - Box-Shadow unten 9rem
- `.shadow-b-8` - Box-Shadow unten 8rem
- `.shadow-b-7` - Box-Shadow unten 7rem
- `.shadow-b-6` - Box-Shadow unten 6rem
- `.shadow-b-5` - Box-Shadow unten 5rem
- `.shadow-b-4` - Box-Shadow unten 4rem
- `.shadow-b-3` - Box-Shadow unten 3rem
- `.shadow-b-2` - Box-Shadow unten 2rem
- `.shadow-b-1` - Box-Shadow unten 1rem

#### Box Shadow Left

- `.hover:shadow-l-10` - Box Shadow links 10rem beim Schweben
- `.hover:shadow-l-9` - Box Shadow links 9rem beim Schweben
- `.hover:shadow-l-8` - Box-Shadow links 8rem beim Hover
- `.hover:shadow-l-7` - Box Shadow links 7rem beim Schweben
- `.hover:shadow-l-6` - Box Shadow links 6rem beim Schweben
- `.hover:shadow-l-5` - Box Shadow links 5rem beim Schweben
- `.hover:shadow-l-4` - Box-Shadow links 4rem beim Hover
- `.hover:shadow-l-3` - Box Shadow links 3rem beim Schweben
- `.hover:shadow-l-2` - Box-Shadow links 2rem beim Hover
- `.hover:shadow-l-1` - Box-Shadow links 1rem beim Hover
- `.shadow-l-10` - Box-Shadow links 10rem
- `.shadow-l-9` - Box-Shadow links 9rem
- `.shadow-l-8` - Box-Shadow links 8rem
- `.shadow-l-7` - Box-Shadow links 7rem
- `.shadow-l-6` - Box-Shadow links 6rem
- `.shadow-l-5` - Box-Shadow links 5rem
- `.shadow-l-4` - Box-Shadow links 4rem
- `.shadow-l-3` - Box-Shadow links 3rem
- `.shadow-l-2` - Box-Shadow links 2rem
- `.shadow-l-1` - Box-Shadow links 1rem

#### Box Shadow Right

- `.hover:shadow-r-10` - Box Shadow Rechts 10rem beim Hover
- `.hover:shadow-r-9` - Box Shadow Rechts 9rem beim Hover
- `.hover:shadow-r-8` - Box Shadow Rechts 8rem beim Hover
- `.hover:shadow-r-7` - Box Shadow Rechts 7rem beim Hover
- `.hover:shadow-r-6` - Box Shadow Rechts 6rem beim Hover
- `.hover:shadow-r-5` - Box Shadow Rechts 5rem beim Hover
- `.hover:shadow-r-4` - Box Shadow Rechts 4rem beim Hover
- `.hover:shadow-r-3` - Box Shadow Rechts 3rem beim Hover
- `.hover:shadow-r-2` - Box Shadow Rechts 2rem beim Hover
- `.hover:shadow-r-1` - Box Shadow Rechts 1rem beim Hover
- `.shadow-r-10` - Box Shadow Rechts 10rem
- `.shadow-r-9` - Box Shadow Rechts 9rem
- `.shadow-r-8` - Box Shadow Rechts 8rem
- `.shadow-r-7` - Box Shadow Rechts 7rem
- `.shadow-r-6` - Box Shadow Rechts 6rem
- `.shadow-r-5` - Box Shadow Rechts 5rem
- `.shadow-r-4` - Box Shadow Rechts 4rem
- `.shadow-r-3` - Box Shadow Rechts 3rem
- `.shadow-r-2` - Box Shadow Rechts 2rem
- `.shadow-r-1` - Box Shadow Rechts 1rem

#### Box Shadow Top

- `.hover:shadow-t-10` - Box-Shadow oben 10rem beim Hover
- `.hover:shadow-t-9` - Box-Shadow oben 9rem beim Hover
- `.hover:shadow-t-8` - Box-Shadow oben 8rem beim Hover
- `.hover:shadow-t-7` - Box-Shadow oben 7rem beim Hover
- `.hover:shadow-t-6` - Box-Shadow oben 6rem beim Hover
- `.hover:shadow-t-5` - Box-Shadow oben 5rem beim Hover
- `.hover:shadow-t-4` - Box-Shadow oben 4rem beim Hover
- `.hover:shadow-t-3` - Box-Shadow oben 3rem beim Hover
- `.hover:shadow-t-2` - Box-Shadow oben 2rem beim Hover
- `.hover:shadow-t-1` - Box-Shadow oben 1rem beim Hover
- `.shadow-t-10` - Box-Shadow oben 10rem
- `.shadow-t-9` - Box-Shadow oben 9rem
- `.shadow-t-8` - Box-Shadow oben 8rem
- `.shadow-t-7` - Box-Shadow oben 7rem
- `.shadow-t-6` - Box-Shadow oben 6rem
- `.shadow-t-5` - Box-Shadow oben 5rem
- `.shadow-t-4` - Box-Shadow oben 4rem
- `.shadow-t-3` - Box-Shadow oben 3rem
- `.shadow-t-2` - Box-Shadow oben 2rem
- `.shadow-t-1` - Box-Shadow oben 1rem

#### Box Shadow X-Axis

- `.hover:shadow-x-10` - Box Shadow X-Achse 10rem beim Schweben
- `.hover:shadow-x-9` - Box Shadow X-Achse 9rem beim Schweben
- `.hover:shadow-x-8` - Box Shadow X-Achse 8rem beim Schweben
- `.hover:shadow-x-7` - Box Shadow X-Achse 7rem beim Schweben
- `.hover:shadow-x-6` - Box Shadow X-Achse 6rem beim Schweben
- `.hover:shadow-x-5` - Box Shadow X-Achse 5rem beim Schweben
- `.hover:shadow-x-4` - Box Shadow X-Achse 4rem beim Schweben
- `.hover:shadow-x-3` - Box Shadow X-Achse 3rem beim Schweben
- `.hover:shadow-x-2` - Box Shadow X-Achse 2rem beim Schweben
- `.hover:shadow-x-1` - Box Shadow X-Achse 1rem beim Schweben
- `.shadow-x-10` - Box Shadow X-Achse 10rem
- `.shadow-x-9` - Box Shadow X-Achse 9rem
- `.shadow-x-8` - Box Shadow X-Achse 8rem
- `.shadow-x-7` - Box Shadow X-Achse 7rem
- `.shadow-x-6` - Box Shadow X-Achse 6rem
- `.shadow-x-5` - Box Shadow X-Achse 5rem
- `.shadow-x-4` - Box Shadow X-Achse 4rem
- `.shadow-x-3` - Box Shadow X-Achse 3rem
- `.shadow-x-2` - Box Shadow X-Achse 2rem
- `.shadow-x-1` - Box Shadow X-Achse 1rem

#### Box Shadow Y-Axis

- `.hover:shadow-y-10` - Box Shadow Y-Achse 10rem beim Schweben
- `.hover:shadow-y-9` - Box Shadow Y-Achse 9rem beim Schweben
- `.hover:shadow-y-8` - Box Shadow Y-Achse 8rem beim Schweben
- `.hover:shadow-y-7` - Box Shadow Y-Achse 7rem beim Schweben
- `.hover:shadow-y-6` - Box Shadow Y-Achse 6rem beim Schweben
- `.hover:shadow-y-5` - Box Shadow Y-Achse 5rem beim Schweben
- `.hover:shadow-y-4` - Box Shadow Y-Achse 4rem beim Schweben
- `.hover:shadow-y-3` - Box Shadow Y-Achse 3rem beim Schweben
- `.hover:shadow-y-2` - Box Shadow Y-Achse 2rem beim Schweben
- `.hover:shadow-y-1` - Box Shadow Y-Achse 1rem beim Schweben
- `.shadow-y-10` - Box Shadow Y-Achse 10rem
- `.shadow-y-9` - Box Shadow Y-Achse 9rem
- `.shadow-y-8` - Box Shadow Y-Achse 8rem
- `.shadow-y-7` - Box Shadow Y-Achse 7rem
- `.shadow-y-6` - Box Shadow Y-Achse 6rem
- `.shadow-y-5` - Box Shadow Y-Achse 5rem
- `.shadow-y-4` - Box Shadow Y-Achse 4rem
- `.shadow-y-3` - Box Shadow Y-Achse 3rem
- `.shadow-y-2` - Box Shadow Y-Achse 2rem
- `.shadow-y-1` - Box Shadow Y-Achse 1rem

### Blur

- `.blur-5` - Unschärfe 24px
- `.blur-4` - Unschärfe 16px
- `.blur-3` - Unschärfe 12px
- `.blur-2` - Unschärfe 8px
- `.blur-1` - Unschärfe 4px
- `.blur-0` - Unschärfe 0px
- `.hover:blur-5` - Unschärfe 24px beim Schweben
- `.hover:blur-4` - 16px beim Schweben verwischen
- `.hover:blur-3` - 12px beim Schweben verwischen
- `.hover:blur-2` - Beim Schweben 8px verwischen
- `.hover:blur-1` - 4px beim Schweben verwischen
- `.hover:blur-0` - Beim Schweben 0px verwischen

### Opacity

- `.hover:opacity-100` - Deckkraft 100 % beim Schweben
- `.hover:opacity-95` - Deckkraft 95 % beim Schweben
- `.hover:opacity-90` - Deckkraft 90 % beim Schweben
- `.hover:opacity-85` - Deckkraft 85 % beim Schweben
- `.hover:opacity-80` - Deckkraft 80 % beim Schweben
- `.hover:opacity-75` - Deckkraft 75 % beim Schweben
- `.hover:opacity-70` - Deckkraft 70 % beim Schweben
- `.hover:opacity-65` - Deckkraft 65 % beim Schweben
- `.hover:opacity-60` - Deckkraft 60 % beim Schweben
- `.hover:opacity-55` - Deckkraft 55 % beim Schweben
- `.hover:opacity-50` - Deckkraft 50 % beim Schweben
- `.hover:opacity-45` - Deckkraft 45 % beim Schweben
- `.hover:opacity-40` - Deckkraft 40 % beim Schweben
- `.hover:opacity-35` - Deckkraft 35 % beim Schweben
- `.hover:opacity-30` - Deckkraft 30 % beim Schweben
- `.hover:opacity-25` - Deckkraft 25 % beim Schweben
- `.hover:opacity-20` - Deckkraft 20 % beim Schweben
- `.hover:opacity-15` - Deckkraft 15 % beim Schweben
- `.hover:opacity-10` - Deckkraft 10 % beim Schweben
- `.hover:opacity-5` - Deckkraft 5 % beim Schweben
- `.hover:opacity-0` - Deckkraft 0 % beim Schweben
- `.opacity-100` - Deckkraft 100 %
- `.opacity-95` - Deckkraft 95 %
- `.opacity-90` - Deckkraft 90 %
- `.opacity-85` - Deckkraft 85 %
- `.opacity-80` - Deckkraft 80 %
- `.opacity-75` - Deckkraft 75 %
- `.opacity-70` - Deckkraft 70 %
- `.opacity-65` - Deckkraft 65 %
- `.opacity-60` - Deckkraft 60 %
- `.opacity-55` - Deckkraft 55 %
- `.opacity-50` - Deckkraft 50 %
- `.opacity-45` - Deckkraft 45 %
- `.opacity-40` - Deckkraft 40 %
- `.opacity-35` - Deckkraft 35 %
- `.opacity-30` - Deckkraft 30 %
- `.opacity-25` - Deckkraft 25 %
- `.opacity-20` - Deckkraft 20 %
- `.opacity-15` - Deckkraft 15 %
- `.opacity-10` - Deckkraft 10 %
- `.opacity-5` - Deckkraft 5 %
- `.opacity-0` - Deckkraft 0 %

## Transforms

### Rotate

- `.hover:rotate-180` - Beim Schweben um 180deg drehen
- `.hover:rotate-135` - Beim Schweben um 135deg drehen
- `.hover:rotate-90` - Beim Schweben um 90deg drehen
- `.hover:rotate-45` - Beim Schweben um 45deg drehen
- `.hover:rotate-12` - Beim Schweben um 12deg drehen
- `.hover:rotate-9` - Beim Schweben um 9deg drehen
- `.hover:rotate-6` - Beim Schweben um 6deg drehen
- `.hover:rotate-3` - Beim Schweben um 3deg drehen
- `.hover:rotate-0` - Beim Schweben um 0deg drehen
- `.rotate-180` - 180deg drehen
- `.rotate-135` - 135deg drehen
- `.rotate-90` - 90deg drehen
- `.rotate-45` - 45deg drehen
- `.rotate-12` - 12deg drehen
- `.rotate-9` - 9deg drehen
- `.rotate-6` - 6deg drehen
- `.rotate-3` - 3deg drehen
- `.rotate-0` - 0deg drehen

##### Negative Rotate

- `.-rotate-180` - Negativ 180deg drehen
- `.-rotate-135` - Negativ drehen 135deg
- `.-rotate-90` - Negativ drehen 90deg
- `.-rotate-45` - Negativ drehen 45deg
- `.-rotate-12` - Negativ drehen 12deg
- `.-rotate-9` - Negativ drehen 9deg
- `.-rotate-6` - Negativ drehen 6deg
- `.-rotate-3` - Negativ drehen 3deg
- `.hover:-rotate-180` - Negativ: Beim Schweben um 180deg drehen
- `.hover:-rotate-135` - Negativ: 135deg beim Schweben drehen
- `.hover:-rotate-90` - Negativ: 90deg beim Schweben drehen
- `.hover:-rotate-45` - Negativ: 45deg beim Schweben drehen
- `.hover:-rotate-12` - Negativ, 12deg drehen beim Schweben
- `.hover:-rotate-9` - Negativ: 9deg beim Schweben drehen
- `.hover:-rotate-6` - Negativ: 6deg beim Schweben drehen
- `.hover:-rotate-3` - Negativ 3deg drehen beim Schweben

### Skew

#### Skew X-Axis

- `.hover:skew-x-12` - Verzerren Sie die X-Achse um 12deg beim Schweben
- `.hover:skew-x-6` - X-Achse 6deg beim Schweben verzerren
- `.hover:skew-x-3` - X-Achse 3deg beim Schweben verzerren
- `.hover:skew-x-0` - Verzerre die X-Achse um 0deg beim Schweben
- `.skew-x-12` - Skew X-Achse 12deg
- `.skew-x-6` - Skew X-Achse 6deg
- `.skew-x-3` - Skew X-Achse 3deg
- `.skew-x-0` - Skew X-Achse 0deg

##### Negative Skew X-Axis

- `.-skew-x-12` - Negativer Skew X-Achse 12deg
- `.-skew-x-6` - Negativer Skew X-Achse 6deg
- `.-skew-x-3` - Negativer Skew X-Achse 3deg
- `.hover:-skew-x-12` - Negativer Skew X-Achse 12deg beim Schweben
- `.hover:-skew-x-6` - Negativer Skew X-Achse 6deg beim Schweben
- `.hover:-skew-x-3` - Negativer Skew X-Achse 3deg beim Schweben

#### Skew Y-Axis

- `.hover:skew-y-12` - Y-Achse 12deg beim Schweben verzerren
- `.hover:skew-y-6` - Y-Achse 6deg beim Schweben verzerren
- `.hover:skew-y-3` - Schräge Y-Achse 3deg beim Schweben
- `.hover:skew-y-0` - Y-Achse 0deg beim Schweben verzerren
- `.skew-y-12` - Skew Y-Achse 12deg
- `.skew-y-6` - Skew Y-Achse 6deg
- `.skew-y-3` - Skew Y-Achse 3deg
- `.skew-y-0` - Skew Y-Achse 0deg

##### Negative Skew Y-Axis

- `.-skew-y-12` - Negativer Skew Y-Achse 12deg
- `.-skew-y-6` - Negativer Skew Y-Achse 6deg
- `.-skew-y-3` - Negativer Skew Y-Achse 3deg
- `.hover:-skew-y-12` - Negativer Skew Y-Achse 12deg beim Schweben
- `.hover:-skew-y-6` - Negativer Skew Y-Achse 6deg beim Schweben
- `.hover:-skew-y-3` - Negativer Skew Y-Achse 3deg beim Schweben

### Translate

- `.hover:translate-50` - Übersetze 50 % beim Schweben
- `.hover:translate-25` - Übersetzen Sie 25 % beim Schweben
- `.translate-50` - Übersetzen Sie 50 %
- `.translate-25` - Übersetzen Sie 25 %

##### Negative Translate

- `.-translate-50` - Negativ übersetzen 50 %
- `.-translate-25` - Negativ übersetzen 25 %
- `.hover:-translate-50` - Negativ Übersetzen Sie 50 % beim Schweben
- `.hover:-translate-25` - Negativ Übersetzen Sie 25 % beim Schweben

#### Translate X-Axis

- `.hover:translate-x-50` - Verschieben Sie die X-Achse um 50 % beim Schweben
- `.hover:translate-x-25` - Verschieben Sie die X-Achse um 25 % beim Schweben
- `.hover:translate-x-2` - Verschieben Sie die X-Achse 2rem beim Schweben
- `.hover:translate-x-1.5` - Verschieben Sie die X-Achse 0rem beim Hover
- `.hover:translate-x-1` - Verschieben Sie die X-Achse 1rem beim Schweben
- `.hover:translate-x-0.5` - Verschieben Sie die X-Achse beim Schweben um 0,5rem
- `.hover:translate-x-0` - Verschieben Sie die X-Achse 0rem beim Hover
- `.translate-x-50` - X-Achse 50 % verschieben
- `.translate-x-25` - X-Achse um 25 % verschieben
- `.translate-x-2` - X-Achse 2rem verschieben
- `.translate-x-1.5` - X-Achse 0rem verschieben
- `.translate-x-1` - X-Achse 1rem verschieben
- `.translate-x-0.5` - Verschieben Sie die X-Achse um 0,5rem
- `.translate-x-0` - X-Achse 0rem verschieben

##### Negative Translate X-Axis

- `.-translate-x-50` - Negative Verschiebung der X-Achse 50 %
- `.-translate-x-25` - Negative Verschiebung der X-Achse 25 %
- `.-translate-x-2` - Negativ X-Achse verschieben 2rem
- `.-translate-x-1.5` - Negative Verschiebung der X-Achse 1,5rem
- `.-translate-x-1` - Negativ X-Achse verschieben 1rem
- `.-translate-x-0.5` - Negative Verschiebung der X-Achse 0,5rem
- `.hover:-translate-x-50` - Negative Verschiebung der X-Achse um 50 % beim Schweben
- `.hover:-translate-x-25` - Negativ X-Achse 25 % verschieben beim Schweben
- `.hover:-translate-x-2` - Negativ X-Achse 2rem verschieben beim Schweben
- `.hover:-translate-x-1.5` - Negative Verschiebung der X-Achse 1,5rem beim Schweben
- `.hover:-translate-x-1` - Negative Verschiebung der X-Achse 1rem beim Schweben
- `.hover:-translate-x-0.5` - Negative Verschiebung der X-Achse um 0,5rem beim Schweben

#### Translate Y-Axis

- `.hover:translate-y-50` - Verschieben Sie die Y-Achse um 50 % beim Schweben
- `.hover:translate-y-25` - Verschieben Sie die Y-Achse um 25 % beim Schweben
- `.hover:translate-y-2` - Übersetzen Sie die Y-Achse 2rem beim Schweben
- `.hover:translate-y-1.5` - Übersetzen Sie die Y-Achse 0rem beim Schweben
- `.hover:translate-y-1` - Verschieben Sie die Y-Achse 1rem beim Hover
- `.hover:translate-y-0.5` - Verschieben Sie die Y-Achse beim Schweben um 0,5rem
- `.hover:translate-y-0` - Übersetzen Sie die Y-Achse 0rem beim Schweben
- `.translate-y-50` - Y-Achse 50 % verschieben
- `.translate-y-25` - Y-Achse um 25 % verschieben
- `.translate-y-2` - Y-Achse 2rem verschieben
- `.translate-y-1.5` - Y-Achse 0rem verschieben
- `.translate-y-1` - Y-Achse 1rem verschieben
- `.translate-y-0.5` - Verschieben Sie die Y-Achse um 0,5rem
- `.translate-y-0` - Y-Achse 0rem verschieben

##### Negative Translate Y-Axis

- `.-translate-y-50` - Negative Verschiebung der Y-Achse 50 %
- `.-translate-y-25` - Negative Verschiebung der Y-Achse 25 %
- `.-translate-y-2` - Negativ Y-Achse verschieben 2rem
- `.-translate-y-1.5` - Negative Verschiebung der Y-Achse 1,5rem
- `.-translate-y-1` - Negativ Y-Achse verschieben 1rem
- `.-translate-y-0.5` - Negative Verschiebung der Y-Achse 0,5rem
- `.hover:-translate-y-50` - Negative Verschiebung der Y-Achse um 50 % beim Schweben
- `.hover:-translate-y-25` - Negativ Y-Achse 25 % verschieben beim Schweben
- `.hover:-translate-y-2` - Negativ Y-Achse 2rem verschieben beim Schweben
- `.hover:-translate-y-1.5` - Negative Verschiebung der Y-Achse 1,5rem beim Schweben
- `.hover:-translate-y-1` - Negativ Y-Achse 1rem verschieben beim Schweben
- `.hover:-translate-y-0.5` - Negative Verschiebung der Y-Achse um 0,5rem beim Schweben

### Zoom

- `.hover:zoom` - Beim Schweben zoomen
- `.hover:zoom-2` - Beim Schweben 2 zoomen
- `.hover:zoom-1.5` - Zoom 1,5 beim Schweben
- `.zoom` - Zoomen
- `.zoom-2` - Zoom 2
- `.zoom-1.5` - Zoom 1,5

## Colors

### Black

- `.black` - Schwarz

### Dark

- `.dark` - Dunkel

### Light

- `.light` - Licht

### Transparent

- `.transparent` - Transparent

## Interactivity

### Cursor

- `.cursor-alias` - Cursor-Alias
- `.cursor-all-scroll` - Cursor All-Scroll
- `.cursor-auto` - Cursor automatisch
- `.cursor-cell` - Cursorzelle
- `.cursor-col-resize` - Größenänderung der Cursorfarbe
- `.cursor-context-menu` - Cursor-Kontextmenü
- `.cursor-copy` - Cursorkopie
- `.cursor-crosshair` - Cursor-Fadenkreuz
- `.cursor-default` - Cursor
- `.cursor-e-resize` - Cursor-E-Größe ändern
- `.cursor-ew-resize` - Neue Größe des Cursors ändern
- `.cursor-grab` - Cursor greifen
- `.cursor-grabbing` - Cursor-Grabbing
- `.cursor-help` - Cursor-Hilfe
- `.cursor-move` - Cursorbewegung
- `.cursor-n-resize` - Cursor-N-Größe ändern
- `.cursor-ne-resize` - Cursorgröße nicht ändern
- `.cursor-nesw-resize` - Neue Größe des Cursors
- `.cursor-no-drop` - Cursor-No-Drop
- `.cursor-none` - Cursor keiner
- `.cursor-not-allowed` - Cursor nicht zulässig
- `.cursor-ns-resize` - Cursor NS-Größe ändern
- `.cursor-nw-resize` - Cursor neu verkleinern
- `.cursor-nwse-resize` - Cursor-Nwse-Resize
- `.cursor-pointer` - Cursorzeiger
- `.cursor-progress` - Cursorfortschritt
- `.cursor-row-resize` - Größe der Cursorzeile ändern
- `.cursor-s-resize` - Cursorgröße ändern
- `.cursor-se-resize` - Cursorgröße ändern
- `.cursor-sw-resize` - Cursor-SW-Größe ändern
- `.cursor-text` - Cursortext
- `.cursor-vertical-text` - Cursor vertikaler Text
- `.cursor-w-resize` - Cursor-W-Größe ändern
- `.cursor-wait` - Cursor warten
- `.cursor-zoom-in` - Vergrößern des Cursors
- `.cursor-zoom-out` - Verkleinern des Cursors

### Disabled

- `.disabled` - Deaktiviert

### Resize

- `.resize` - Größe ändern
- `.resize-none` - Keine Größe ändern
- `.resize-x` - Größe x ändern
- `.resize-y` - Größe ändern

### Select

- `.select-auto` - Wählen Sie „Automatisch“.
- `.select-none` - Wählen Sie „Keine“ aus

## Misc

### Content

- `.content-3` - Inhalt 3
- `.content-3-bg` - Inhalt 3-bg
- `.content-2` - Inhalt 2
- `.content-2-bg` - Inhalt 2-bg
- `.content-2-text` - Inhalt 2-text
- `.content-1` - Inhalt 1
- `.content-1-bg` - Inhalt 1-bg
- `.content-1-text` - Inhalt 1-text
- `.hover:content-3-bg` - Inhalt 3-bg beim Schweben
- `.hover:content-2-bg` - Inhalt 2-bg beim Schweben
- `.hover:content-2-text` - Inhalt 2-text beim Hover
- `.hover:content-1-bg` - Inhalt 1-bg beim Schweben
- `.hover:content-1-text` - Inhalt 1-text beim Hover

### Dir

- `.dir-ltr` - Dir ltr
- `.dir-rtl` - Dir rtl

### Mse

- `.hover:mse-2` - Mse 2rem beim Schweben
- `.hover:mse-1.5` - Mse 1.5rem beim Hover
- `.hover:mse-1` - Mse 1rem beim Schweben
- `.hover:mse-0.5` - Mse 0,5rem beim Schweben
- `.hover:mse-0` - Mse 0rem beim Schweben
- `.mse-2` - Mse 2rem
- `.mse-1.5` - Mse 1,5rem
- `.mse-1` - Mse 1rem
- `.mse-0.5` - Mse 0,5rem
- `.mse-0` - Mse 0rem

### Visibility

- `.hover:v-hide` - Sichtbarkeit beim Schweben ausgeblendet
- `.hover:v-show` - Sichtbarkeit beim Schweben sichtbar
- `.v-hide` - Sichtbarkeit verborgen
- `.v-show` - Sichtbarkeit sichtbar

##### Visibility - Mobile (<= 480px)

- `.hover:mobile:v-hide` - Sichtbarkeit beim Schweben auf Mobilgeräten ausgeblendet
- `.hover:mobile:v-show` - Sichtbarkeit beim Hover auf dem Mobilgerät sichtbar
- `.mobile:v-hide` - Sichtbarkeit auf Mobilgeräten ausgeblendet
- `.mobile:v-show` - Sichtbarkeit auf Mobilgeräten sichtbar

##### Visibility - Tablet (480px - 768px)

- `.hover:tablet:v-hide` - Sichtbarkeit beim Schweben auf dem Tablet ausgeblendet
- `.hover:tablet:v-show` - Sichtbarkeit beim Bewegen des Mauszeigers auf dem Tablet sichtbar
- `.tablet:v-hide` - Sichtbarkeit auf dem Tablet ausgeblendet
- `.tablet:v-show` - Sichtbarkeit auf dem Tablet sichtbar

##### Visibility - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:v-hide` - Sichtbarkeit beim Schweben auf dem Tablet-PC ausgeblendet
- `.hover:tablet-pc:v-show` - Sichtbarkeit beim Hover auf dem Tablet-PC sichtbar
- `.tablet-pc:v-hide` - Sichtbarkeit auf dem Tablet-PC ausgeblendet
- `.tablet-pc:v-show` - Sichtbarkeit auf Tablet-PC sichtbar

##### Visibility - Pc (992px - 1200px)

- `.hover:pc:v-hide` - Sichtbarkeit beim Schweben auf dem PC ausgeblendet
- `.hover:pc:v-show` - Sichtbarkeit beim Hover auf dem PC sichtbar
- `.pc:v-hide` - Sichtbarkeit auf dem PC ausgeblendet
- `.pc:v-show` - Sichtbarkeit auf dem PC sichtbar

##### Visibility - Tv (>= 1200px)

- `.hover:tv:v-hide` - Sichtbarkeit beim Schweben im Fernsehen ausgeblendet
- `.hover:tv:v-show` - Sichtbarkeit beim Schweben im Fernsehen sichtbar
- `.tv:v-hide` - Im Fernsehen verborgene Sichtbarkeit
- `.tv:v-show` - Sichtbarkeit im Fernsehen sichtbar

##### Visibility - Tablet Max (<= 768px)

- `.hover:tablet-max:v-hide` - Sichtbarkeit beim Hover auf dem Tablet max. ausgeblendet
- `.hover:tablet-max:v-show` - Sichtbarkeit beim Hover auf dem Tablet max
- `.tablet-max:v-hide` - Sichtbarkeit ausgeblendet auf dem Tablet max
- `.tablet-max:v-show` - Sichtbarkeit sichtbar auf dem Tablet max

##### Visibility - Tablet Pc Max (<= 992px)

- `.hover:tablet-pc-max:v-hide` - Sichtbarkeit ausgeblendet beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:v-show` - Sichtbarkeit beim Hover auf dem Tablet-PC max
- `.tablet-pc-max:v-hide` - Sichtbarkeit ausgeblendet auf Tablet-PC max
- `.tablet-pc-max:v-show` - Sichtbarkeit sichtbar auf Tablet-PC max

##### Visibility - Pc Max (<= 1200px)

- `.hover:pc-max:v-hide` - Sichtbarkeit ausgeblendet beim Hover auf dem PC max
- `.hover:pc-max:v-show` - Sichtbarkeit beim Hover auf dem PC max
- `.pc-max:v-hide` - Sichtbarkeit ausgeblendet auf dem PC max
- `.pc-max:v-show` - Sichtbarkeit auf dem PC sichtbar max

### Customization

bClass verwendet CSS-Variablen für die Themengestaltung:

- `--plainBg` - Einfache Hintergrundfarbe
- `--contentBg` - Hintergrundfarbe des Inhalts
- `--contentBgPrimary` - Hintergrund des primären Inhalts
- `--contentBgSecondary` - Sekundärer Inhaltshintergrund
- `--contentTextPrimary` - Primäre Textfarbe
- `--contentTextSecondary` - Sekundäre Textfarbe
- `--headerBg` - Hintergrundfarbe der Kopfzeile

### License

> Verteilt unter der Bik Public License 2.0-Lizenz. Weitere Informationen finden Sie unter [LICENSE](./../../../LICENSE).
