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
- [Other](#other)
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

##### Display - Mobile (< 480px)

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

##### Display - Tv (> 1200px)

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

##### Display - Tablet Max (< 768px)

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

##### Display - Tablet Pc Max (< 992px)

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

##### Display - Pc Max (< 1200px)

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

- `.float-end` - Float-Ende
- `.float-left` - Nach links schweben
- `.float-none` - Float keine
- `.float-right` - Nach rechts schweben
- `.float-start` - Schwimmstart
- `.hover:float-end` - Schwebeende beim Schweben
- `.hover:float-left` - Beim Schweben nach links schweben
- `.hover:float-none` - Schweben Sie nicht beim Schweben
- `.hover:float-right` - Schwebe direkt im Schwebeflug
- `.hover:float-start` - Schwebestart im Schwebeflug

##### Float - Mobile (< 480px)

- `.hover:mobile:float-end` - Float-Ende beim Hover auf dem Handy
- `.hover:mobile:float-left` - Beim Schweben auf dem Handy nach links schweben
- `.hover:mobile:float-none` - Schweben Sie nicht, wenn Sie den Mauszeiger auf dem Mobilgerät bewegen
- `.hover:mobile:float-right` - Schweben Sie beim Hover auf dem Handy nach rechts
- `.hover:mobile:float-start` - Float-Start beim Schweben auf dem Handy
- `.mobile:float-end` - Float-Ende auf dem Handy
- `.mobile:float-left` - Auf dem Handy nach links schweben
- `.mobile:float-none` - Float none auf Mobilgeräten
- `.mobile:float-right` - Schweben Sie direkt auf dem Handy
- `.mobile:float-start` - Float-Start auf dem Handy

##### Float - Tablet (480px - 768px)

- `.hover:tablet:float-end` - Float-Ende beim Schweben auf dem Tablet
- `.hover:tablet:float-left` - Beim Schweben auf dem Tablet nach links schweben
- `.hover:tablet:float-none` - Schweben Sie nicht, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet:float-right` - Schweben Sie nach rechts, wenn Sie auf dem Tablet schweben
- `.hover:tablet:float-start` - Float-Start beim Hover auf dem Tablet
- `.tablet:float-end` - Ende auf dem Tablet schweben lassen
- `.tablet:float-left` - Auf dem Tablet nach links schweben
- `.tablet:float-none` - Keine auf dem Tablet schweben lassen
- `.tablet:float-right` - Schweben Sie direkt auf dem Tablet
- `.tablet:float-start` - Float-Start auf dem Tablet

##### Float - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:float-end` - Float-Ende beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:float-left` - Beim Hover auf dem Tablet-PC nach links schweben
- `.hover:tablet-pc:float-none` - Schweben Sie nicht, wenn Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.hover:tablet-pc:float-right` - Beim Hover auf dem Tablet-PC nach rechts schweben
- `.hover:tablet-pc:float-start` - Float-Start beim Hover auf dem Tablet-PC
- `.tablet-pc:float-end` - Float-Ende auf Tablet-PC
- `.tablet-pc:float-left` - Auf dem Tablet-PC nach links schweben
- `.tablet-pc:float-none` - Float keine auf dem Tablet-PC
- `.tablet-pc:float-right` - Schweben Sie direkt auf dem Tablet-PC
- `.tablet-pc:float-start` - Float-Start auf dem Tablet-PC

##### Float - Pc (992px - 1200px)

- `.hover:pc:float-end` - Float-Ende beim Hover auf dem PC
- `.hover:pc:float-left` - Beim Hover auf dem PC nach links schweben
- `.hover:pc:float-none` - Schweben Sie nicht, wenn Sie den Mauszeiger auf dem PC bewegen
- `.hover:pc:float-right` - Beim Hover auf dem PC nach rechts schweben
- `.hover:pc:float-start` - Float-Start beim Schweben auf dem PC
- `.pc:float-end` - Float-Ende am PC
- `.pc:float-left` - Auf dem PC nach links schweben
- `.pc:float-none` - Keine auf dem PC schweben lassen
- `.pc:float-right` - Schweben Sie direkt auf dem PC
- `.pc:float-start` - Float-Start auf dem PC

##### Float - Tv (> 1200px)

- `.hover:tv:float-end` - Float-Ende beim Hover im Fernsehen
- `.hover:tv:float-left` - Beim Schweben im Fernsehen nach links schweben
- `.hover:tv:float-none` - Schweben Sie nicht, schweben Sie im Fernsehen
- `.hover:tv:float-right` - Schweben Sie direkt beim Schweben im Fernsehen
- `.hover:tv:float-start` - Schwebestart im Schwebeflug im Fernsehen
- `.tv:float-end` - Float End im Fernsehen
- `.tv:float-left` - Nach links schweben im Fernsehen
- `.tv:float-none` - Schweben Sie nichts im Fernsehen
- `.tv:float-right` - Schweben Sie direkt im Fernsehen
- `.tv:float-start` - Float Start im Fernsehen

##### Float - Tablet Max (< 768px)

- `.hover:tablet-max:float-end` - Float-Ende beim Schweben auf dem Tablet max
- `.hover:tablet-max:float-left` - Beim Schweben auf dem Tablet nach links schweben, max
- `.hover:tablet-max:float-none` - Float keine beim Schweben auf dem Tablet max
- `.hover:tablet-max:float-right` - Beim Schweben auf dem Tablet nach rechts schweben, max
- `.hover:tablet-max:float-start` - Float-Start beim Schweben auf dem Tablet max
- `.tablet-max:float-end` - Float-Ende am Tablet max
- `.tablet-max:float-left` - Nach links auf dem Tablet schweben max
- `.tablet-max:float-none` - Float keine auf dem Tablet max
- `.tablet-max:float-right` - Direkt auf dem Tablet schweben max
- `.tablet-max:float-start` - Float-Start auf Tablet max

##### Float - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:float-end` - Float-Ende beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:float-left` - Beim Hover auf dem Tablet-PC nach links schweben, max
- `.hover:tablet-pc-max:float-none` - Float keine beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:float-right` - Beim Hover auf dem Tablet-PC nach rechts schweben, max
- `.hover:tablet-pc-max:float-start` - Float-Start beim Hover auf Tablet-PC max
- `.tablet-pc-max:float-end` - Float-Ende am Tablet-PC max
- `.tablet-pc-max:float-left` - Float links auf Tablet-PC max
- `.tablet-pc-max:float-none` - Float keine auf Tablet-PC max
- `.tablet-pc-max:float-right` - Rechts auf dem Tablet-PC schweben max
- `.tablet-pc-max:float-start` - Float-Start auf Tablet-PC max

##### Float - Pc Max (< 1200px)

- `.hover:pc-max:float-end` - Float-Ende beim Hover auf dem PC max
- `.hover:pc-max:float-left` - Beim Hover auf dem PC nach links schweben, max
- `.hover:pc-max:float-none` - Float keine beim Hover auf dem PC max
- `.hover:pc-max:float-right` - Beim Hover auf dem PC nach rechts schweben, max
- `.hover:pc-max:float-start` - Float-Start beim Schweben auf dem PC max
- `.pc-max:float-end` - Float-Ende am PC max
- `.pc-max:float-left` - Float links auf dem PC max
- `.pc-max:float-none` - Float keine auf dem PC max
- `.pc-max:float-right` - Direkt auf dem PC schweben max
- `.pc-max:float-start` - Float-Start am PC max

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

##### Object - Mobile (< 480px)

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

##### Object - Tv (> 1200px)

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

##### Object - Tablet Max (< 768px)

- `.hover:tablet-max:object-contain` - Objekt enthält beim Hover auf dem Tablet max
- `.hover:tablet-max:object-cover` - Objektabdeckung beim Schweben auf dem Tablet max
- `.hover:tablet-max:object-fill` - Objektfüllung beim Schweben auf dem Tablet max
- `.hover:tablet-max:object-none` - Kein Objekt beim Hovern auf dem Tablet, max
- `.hover:tablet-max:object-scale` - Objektskalierung beim Schweben auf dem Tablet max
- `.tablet-max:object-contain` - Objekt enthält max
- `.tablet-max:object-cover` - Objektabdeckung auf Tablet max
- `.tablet-max:object-fill` - Objektfüllung auf Tablett max
- `.tablet-max:object-none` - Objekt keines auf Tablet max
- `.tablet-max:object-scale` - Objektskalierung auf Tablet max

##### Object - Tablet Pc Max (< 992px)

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

##### Object - Pc Max (< 1200px)

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

##### Flex - Mobile (< 480px)

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

##### Flex - Tv (> 1200px)

- `.hover:tv:flex-col` - Flex Col beim Schweben im Fernsehen
- `.hover:tv:flex-nowrap` - Flex Nowrap im Hover im Fernsehen
- `.hover:tv:flex-row` - Flexreihe beim Schweben im Fernsehen
- `.hover:tv:flex-wrap` - Flex Wrap beim Schweben im Fernsehen
- `.tv:flex-col` - Flex Col im Fernsehen
- `.tv:flex-nowrap` - Flex Nowrap im Fernsehen
- `.tv:flex-row` - Flex Row im Fernsehen
- `.tv:flex-wrap` - Flexfolie im Fernsehen

##### Flex - Tablet Max (< 768px)

- `.hover:tablet-max:flex-col` - Flex Col beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-nowrap` - Flex Nowrap beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-row` - Flexreihe beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-wrap` - Flexfolie beim Schweben auf dem Tablet max
- `.tablet-max:flex-col` - Flex-Farbe auf Tablet max
- `.tablet-max:flex-nowrap` - Flex Nowrap auf Tablet max
- `.tablet-max:flex-row` - Flexreihe auf Tablet max
- `.tablet-max:flex-wrap` - Flexfolie am Tablet max

##### Flex - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-col` - Flex Col beim Hover auf Tablet PC max
- `.hover:tablet-pc-max:flex-nowrap` - Flex Nowrap beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:flex-row` - Flexreihe beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-wrap` - Flexfolie beim Hover auf Tablet-PC max
- `.tablet-pc-max:flex-col` - Flex-Farbe auf Tablet-PC max
- `.tablet-pc-max:flex-nowrap` - Flex Nowrap auf Tablet-PC max
- `.tablet-pc-max:flex-row` - Flexreihe am Tablet-PC max
- `.tablet-pc-max:flex-wrap` - Flexfolie am Tablet-PC max

##### Flex - Pc Max (< 1200px)

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

##### Flex col - Mobile (< 480px)

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

##### Flex col - Tv (> 1200px)

- `.hover:tv:flex-col-reverse` - Flex-Col-Reverse beim Schweben im Fernsehen
- `.tv:flex-col-reverse` - Flex Col Reverse im Fernsehen

##### Flex col - Tablet Max (< 768px)

- `.hover:tablet-max:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem Tablet max
- `.tablet-max:flex-col-reverse` - Flex Col Reverse auf Tablet max

##### Flex col - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:flex-col-reverse` - Flex Col Reverse auf Tablet-PC max

##### Flex col - Pc Max (< 1200px)

- `.hover:pc-max:flex-col-reverse` - Flex Col Reverse beim Schweben auf dem PC max
- `.pc-max:flex-col-reverse` - Flex Col Reverse auf PC max

### Flex row

- `.flex-row-reverse` - Flexreihe umgekehrt
- `.hover:flex-row-reverse` - Beuge die Reihe beim Schweben rückwärts

##### Flex row - Mobile (< 480px)

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

##### Flex row - Tv (> 1200px)

- `.hover:tv:flex-row-reverse` - Flexreihe umkehren beim Schweben im Fernsehen
- `.tv:flex-row-reverse` - Flex Row Reverse im Fernsehen

##### Flex row - Tablet Max (< 768px)

- `.hover:tablet-max:flex-row-reverse` - Flexreihe rückwärts beim Schweben auf dem Tablet max
- `.tablet-max:flex-row-reverse` - Flexreihenumkehr auf dem Tablet max

##### Flex row - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-row-reverse` - Flexreihe umkehren beim Schweben auf Tablet-PC max
- `.tablet-pc-max:flex-row-reverse` - Flexreihe rückwärts auf Tablet-PC max

##### Flex row - Pc Max (< 1200px)

- `.hover:pc-max:flex-row-reverse` - Flexreihe umkehren beim Schweben auf dem PC max
- `.pc-max:flex-row-reverse` - Flex-Reihenumkehr am PC max

### Flex grow

- `.flex-grow-3` - Flex wachsen 3rem
- `.flex-grow-2` - Flex wachsen 2rem
- `.flex-grow-1` - Flex wächst 1rem
- `.flex-grow-0` - Flex wächst 0rem
- `.hover:flex-grow-3` - Flex wächst 3rem beim Schweben
- `.hover:flex-grow-2` - Flex wächst beim Schweben um 2 Rem
- `.hover:flex-grow-1` - Flex wächst beim Schweben um 1 Rem
- `.hover:flex-grow-0` - Flex wächst beim Schweben um 0rem

##### Flex grow - Mobile (< 480px)

- `.hover:mobile:flex-grow-3` - Flex wächst 3rem beim Hover auf dem Handy
- `.hover:mobile:flex-grow-2` - Flex wächst 2rem beim Hover auf dem Handy
- `.hover:mobile:flex-grow-1` - Flex wächst um 1 Rem beim Schweben auf dem Handy
- `.hover:mobile:flex-grow-0` - Flex wächst um 0rem beim Hover auf Mobilgeräten
- `.mobile:flex-grow-3` - Flex Grow 3rem auf dem Handy
- `.mobile:flex-grow-2` - Flex wachsen 2rem auf dem Handy
- `.mobile:flex-grow-1` - Flex wachsen 1rem auf dem Handy
- `.mobile:flex-grow-0` - Flex wächst 0rem auf Mobilgeräten

##### Flex grow - Tablet (480px - 768px)

- `.hover:tablet:flex-grow-3` - Flex wachsen 3rem beim Schweben auf dem Tablet
- `.hover:tablet:flex-grow-2` - Flex wachsen 2rem beim Schweben auf dem Tablet
- `.hover:tablet:flex-grow-1` - Flex wachsen 1rem beim Schweben auf dem Tablet
- `.hover:tablet:flex-grow-0` - Flex wächst 0rem beim Schweben auf dem Tablet
- `.tablet:flex-grow-3` - Flex wachsen 3rem auf dem Tablet
- `.tablet:flex-grow-2` - Flex wachsen 2rem auf dem Tablet
- `.tablet:flex-grow-1` - Flex wachsen 1rem auf dem Tablet
- `.tablet:flex-grow-0` - Flex wachsen 0rem auf dem Tablet

##### Flex grow - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:flex-grow-3` - Flex Grow 3rem beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-grow-2` - Flex wachsen 2rem beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-grow-1` - Flex wachsen 1rem beim Schweben auf dem Tablet-PC
- `.hover:tablet-pc:flex-grow-0` - Flex wächst 0rem beim Schweben auf dem Tablet-PC
- `.tablet-pc:flex-grow-3` - Flex Grow 3rem auf dem Tablet-PC
- `.tablet-pc:flex-grow-2` - Flex wachsen 2rem auf dem Tablet-PC
- `.tablet-pc:flex-grow-1` - Flex wachsen 1rem auf dem Tablet-PC
- `.tablet-pc:flex-grow-0` - Flex wachsen 0rem auf Tablet-PC

##### Flex grow - Pc (992px - 1200px)

- `.hover:pc:flex-grow-3` - Flex Grow 3rem beim Schweben auf dem PC
- `.hover:pc:flex-grow-2` - Flex wächst 2rem beim Hover auf dem PC
- `.hover:pc:flex-grow-1` - Flex wächst 1rem beim Hover auf dem PC
- `.hover:pc:flex-grow-0` - Flex wächst 0rem beim Schweben auf dem PC
- `.pc:flex-grow-3` - Flex Grow 3rem auf dem PC
- `.pc:flex-grow-2` - Flex wachsen 2rem auf dem PC
- `.pc:flex-grow-1` - Flex wachsen 1rem auf dem PC
- `.pc:flex-grow-0` - Flex wachsen 0rem auf dem PC

##### Flex grow - Tv (> 1200px)

- `.hover:tv:flex-grow-3` - Flex wachsen 3rem beim Schweben im Fernsehen
- `.hover:tv:flex-grow-2` - Flex wächst 2rem beim Schweben im Fernsehen
- `.hover:tv:flex-grow-1` - Flex wachsen 1rem beim Schweben im Fernsehen
- `.hover:tv:flex-grow-0` - Flex wächst 0rem beim Schweben im Fernsehen
- `.tv:flex-grow-3` - Flex Grow 3rem im Fernsehen
- `.tv:flex-grow-2` - Flex Grow 2rem im Fernsehen
- `.tv:flex-grow-1` - Flex wachsen 1rem im Fernsehen
- `.tv:flex-grow-0` - Flex wachsen 0rem im Fernsehen

##### Flex grow - Tablet Max (< 768px)

- `.hover:tablet-max:flex-grow-3` - Flex wachsen 3rem beim Schweben auf dem Tablet max
- `.hover:tablet-max:flex-grow-2` - Flex wächst 2rem beim Hover auf dem Tablet max
- `.hover:tablet-max:flex-grow-1` - Flex wächst 1 Rem beim Hover auf dem Tablet max
- `.hover:tablet-max:flex-grow-0` - Flex wächst um 0 rem beim Schweben auf dem Tablet, max
- `.tablet-max:flex-grow-3` - Flex wachsen 3rem auf Tablet max
- `.tablet-max:flex-grow-2` - Flex wachsen 2rem auf Tablet max
- `.tablet-max:flex-grow-1` - Flex wachsen 1rem auf Tablet max
- `.tablet-max:flex-grow-0` - Flex wachsen 0rem auf Tablet max

##### Flex grow - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-grow-3` - Flex wachsen 3rem beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-grow-2` - Flex wachsen 2rem beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-grow-1` - Flex wachsen 1rem beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:flex-grow-0` - Flex wächst 0rem beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:flex-grow-3` - Flex Grow 3rem auf Tablet-PC max
- `.tablet-pc-max:flex-grow-2` - Flex Grow 2rem auf Tablet-PC max
- `.tablet-pc-max:flex-grow-1` - Flex wachsen 1rem auf Tablet-PC max
- `.tablet-pc-max:flex-grow-0` - Flex wachsen 0rem auf Tablet-PC max

##### Flex grow - Pc Max (< 1200px)

- `.hover:pc-max:flex-grow-3` - Flex wachsen 3rem beim Schweben auf dem PC max
- `.hover:pc-max:flex-grow-2` - Flex wächst 2rem beim Hover auf dem PC max
- `.hover:pc-max:flex-grow-1` - Flex wächst 1 Rem beim Hover auf dem PC max
- `.hover:pc-max:flex-grow-0` - Flex wächst 0rem beim Schweben auf dem PC max
- `.pc-max:flex-grow-3` - Flex wachsen 3rem auf dem PC max
- `.pc-max:flex-grow-2` - Flex wachsen 2rem auf dem PC max
- `.pc-max:flex-grow-1` - Flex wachsen 1rem auf dem PC max
- `.pc-max:flex-grow-0` - Flex wachsen 0rem auf dem PC max

### Flex wrap

- `.flex-wrap-reverse` - Flex-Wrap-Rückseite
- `.hover:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben

##### Flex wrap - Mobile (< 480px)

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

##### Flex wrap - Tv (> 1200px)

- `.hover:tv:flex-wrap-reverse` - Flex-Wickel rückwärts beim Schweben im Fernsehen
- `.tv:flex-wrap-reverse` - Flex Wrap umgekehrt im Fernsehen

##### Flex wrap - Tablet Max (< 768px)

- `.hover:tablet-max:flex-wrap-reverse` - Flex-Wickel umgekehrt beim Schweben auf dem Tablet max
- `.tablet-max:flex-wrap-reverse` - Flexfolie rückwärts am Tablet max

##### Flex wrap - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:flex-wrap-reverse` - Flex-Wickel umgekehrt beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:flex-wrap-reverse` - Flex Wrap umgekehrt auf Tablet-PC max

##### Flex wrap - Pc Max (< 1200px)

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
- `.hover:gap-5` - Gap All 5rem beim Schweben
- `.hover:gap-4.5` - Gap All 0rem beim Hover
- `.hover:gap-4` - Gap All 4rem beim Schweben
- `.hover:gap-3.5` - Gap All 0rem beim Hover
- `.hover:gap-3` - Gap All 3rem beim Hover
- `.hover:gap-2.5` - Gap All 0rem beim Hover
- `.hover:gap-2` - Gap All 2rem beim Schweben
- `.hover:gap-1.9` - Gap All 0rem beim Hover
- `.hover:gap-1.8` - Gap All 0rem beim Hover
- `.hover:gap-1.7` - Gap All 0rem beim Hover
- `.hover:gap-1.6` - Gap All 0rem beim Hover
- `.hover:gap-1.5` - Gap All 0rem beim Hover
- `.hover:gap-1.4` - Gap All 0rem beim Hover
- `.hover:gap-1.3` - Gap All 0rem beim Hover
- `.hover:gap-1.2` - Gap All 0rem beim Hover
- `.hover:gap-1.1` - Gap All 0rem beim Hover
- `.hover:gap-1` - Gap All 1rem beim Schweben
- `.hover:gap-0.9` - Gap All 0rem beim Hover
- `.hover:gap-0.8` - Gap All 0rem beim Hover
- `.hover:gap-0.7` - Gap All 0rem beim Hover
- `.hover:gap-0.6` - Gap All 0rem beim Hover
- `.hover:gap-0.5` - Gap All 0rem beim Hover
- `.hover:gap-0.4` - Gap All 0rem beim Hover
- `.hover:gap-0.3` - Gap All 0rem beim Hover
- `.hover:gap-0.2` - Lücke Alle 0,2rem beim Schweben
- `.hover:gap-0.1` - Lücke Alle 0,1rem beim Schweben
- `.hover:gap-0` - Gap All 0rem beim Hover

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

- `.align-content-around` - Richten Sie den Inhalt rundherum aus
- `.align-content-between` - Inhalte dazwischen ausrichten
- `.align-content-center` - Inhaltscenter ausrichten
- `.align-content-end` - Inhalt am Ende ausrichten
- `.align-content-evenly` - Inhalte gleichmäßig ausrichten
- `.align-content-start` - Inhaltsanfang ausrichten
- `.align-content-stretch` - Inhaltsdehnung ausrichten
- `.hover:align-content-around` - Richten Sie den Inhalt beim Schweben rundherum aus
- `.hover:align-content-between` - Richten Sie den Inhalt beim Hover aus
- `.hover:align-content-center` - Inhaltscenter beim Hover ausrichten
- `.hover:align-content-end` - Richten Sie den Inhalt beim Hover am Ende aus
- `.hover:align-content-evenly` - Richten Sie den Inhalt beim Schweben gleichmäßig aus
- `.hover:align-content-start` - Richten Sie den Inhalt beim Hover aus
- `.hover:align-content-stretch` - Richten Sie die Inhaltsdehnung beim Hover aus

##### Align content - Mobile (< 480px)

- `.hover:mobile:align-content-around` - Richten Sie den Inhalt beim Hover auf Mobilgeräten aus
- `.hover:mobile:align-content-between` - Richten Sie Inhalte beim Hover auf Mobilgeräten aus
- `.hover:mobile:align-content-center` - Richten Sie das Inhaltscenter beim Hover auf Mobilgeräten aus
- `.hover:mobile:align-content-end` - Richten Sie den Inhalt am Ende aus, wenn Sie den Mauszeiger auf dem Mobilgerät bewegen
- `.hover:mobile:align-content-evenly` - Richten Sie den Inhalt beim Hover auf Mobilgeräten gleichmäßig aus
- `.hover:mobile:align-content-start` - Richten Sie den Inhalt beim Hover auf Mobilgeräten aus
- `.hover:mobile:align-content-stretch` - Richten Sie die Inhaltsausdehnung beim Hover auf Mobilgeräten aus
- `.mobile:align-content-around` - Richten Sie Inhalte auf Mobilgeräten aus
- `.mobile:align-content-between` - Inhalte auf Mobilgeräten ausrichten
- `.mobile:align-content-center` - Inhaltscenter auf Mobilgeräten ausrichten
- `.mobile:align-content-end` - Inhalte auf Mobilgeräten ausrichten
- `.mobile:align-content-evenly` - Richten Sie Inhalte auf Mobilgeräten gleichmäßig aus
- `.mobile:align-content-start` - Richten Sie den Content-Start auf Mobilgeräten aus
- `.mobile:align-content-stretch` - Passen Sie die Inhaltsausdehnung auf Mobilgeräten an

##### Align content - Tablet (480px - 768px)

- `.hover:tablet:align-content-around` - Richten Sie den Inhalt beim Bewegen des Mauszeigers auf dem Tablet aus
- `.hover:tablet:align-content-between` - Richten Sie den Inhalt beim Bewegen des Mauszeigers auf dem Tablet aus
- `.hover:tablet:align-content-center` - Richten Sie das Inhaltscenter aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet:align-content-end` - Richten Sie den Inhalt am Ende aus, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet:align-content-evenly` - Richten Sie den Inhalt gleichmäßig aus, wenn Sie den Mauszeiger über das Tablet bewegen
- `.hover:tablet:align-content-start` - Richten Sie den Inhalt aus, wenn Sie den Mauszeiger auf dem Tablet bewegen
- `.hover:tablet:align-content-stretch` - Richten Sie den Inhalt beim Bewegen des Mauszeigers auf dem Tablet aus
- `.tablet:align-content-around` - Richten Sie Inhalte auf dem Tablet aus
- `.tablet:align-content-between` - Inhalte auf dem Tablet ausrichten
- `.tablet:align-content-center` - Richten Sie das Inhaltscenter auf dem Tablet aus
- `.tablet:align-content-end` - Richten Sie den Inhalt am Ende des Tablets aus
- `.tablet:align-content-evenly` - Richten Sie Inhalte gleichmäßig auf dem Tablet aus
- `.tablet:align-content-start` - Richten Sie den Inhalt auf dem Tablet aus
- `.tablet:align-content-stretch` - Richten Sie den Inhalt auf dem Tablet aus

##### Align content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-content-around` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC rundherum aus
- `.hover:tablet-pc:align-content-between` - Richten Sie den Inhalt beim Bewegen des Mauszeigers auf dem Tablet-PC aus
- `.hover:tablet-pc:align-content-center` - Richten Sie das Inhaltscenter beim Hover auf dem Tablet-PC aus
- `.hover:tablet-pc:align-content-end` - Richten Sie den Inhalt am Ende aus, wenn Sie den Mauszeiger auf dem Tablet-PC halten
- `.hover:tablet-pc:align-content-evenly` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC gleichmäßig aus
- `.hover:tablet-pc:align-content-start` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC aus
- `.hover:tablet-pc:align-content-stretch` - Richten Sie die Inhaltsdehnung aus, wenn Sie den Mauszeiger auf dem Tablet-PC halten
- `.tablet-pc:align-content-around` - Richten Sie Inhalte auf dem Tablet-PC aus
- `.tablet-pc:align-content-between` - Inhalte auf dem Tablet-PC ausrichten
- `.tablet-pc:align-content-center` - Richten Sie das Inhaltscenter auf dem Tablet-PC aus
- `.tablet-pc:align-content-end` - Richten Sie den Inhalt am Ende des Tablet-PCs aus
- `.tablet-pc:align-content-evenly` - Inhalte gleichmäßig auf dem Tablet-PC ausrichten
- `.tablet-pc:align-content-start` - Richten Sie den Inhalt auf dem Tablet-PC aus
- `.tablet-pc:align-content-stretch` - Richten Sie den Inhalt auf dem Tablet-PC aus

##### Align content - Pc (992px - 1200px)

- `.hover:pc:align-content-around` - Richten Sie den Inhalt beim Hover auf dem PC aus
- `.hover:pc:align-content-between` - Inhalte beim Hover auf dem PC ausrichten
- `.hover:pc:align-content-center` - Richten Sie das Inhaltscenter beim Hover auf dem PC aus
- `.hover:pc:align-content-end` - Richten Sie den Inhalt beim Hover auf dem PC am Ende aus
- `.hover:pc:align-content-evenly` - Richten Sie den Inhalt beim Hover auf dem PC gleichmäßig aus
- `.hover:pc:align-content-start` - Richten Sie den Inhalt beim Hover auf dem PC aus
- `.hover:pc:align-content-stretch` - Richten Sie die Inhaltsdehnung beim Hover auf dem PC aus
- `.pc:align-content-around` - Inhalte rund um den PC ausrichten
- `.pc:align-content-between` - Inhalte auf dem PC ausrichten
- `.pc:align-content-center` - Inhaltscenter am PC ausrichten
- `.pc:align-content-end` - Inhalt am PC ausrichten
- `.pc:align-content-evenly` - Inhalte gleichmäßig auf dem PC ausrichten
- `.pc:align-content-start` - Richten Sie den Inhalt auf dem PC aus
- `.pc:align-content-stretch` - Richten Sie den Inhalt auf dem PC aus

##### Align content - Tv (> 1200px)

- `.hover:tv:align-content-around` - Richten Sie den Inhalt beim Hover auf dem Fernseher aus
- `.hover:tv:align-content-between` - Richten Sie den Inhalt beim Hover auf dem Fernseher aus
- `.hover:tv:align-content-center` - Richten Sie das Inhaltscenter beim Bewegen des Mauszeigers auf dem Fernseher aus
- `.hover:tv:align-content-end` - Richten Sie den Inhalt am Ende aus, wenn Sie mit der Maus über den Fernseher fahren
- `.hover:tv:align-content-evenly` - Richten Sie den Inhalt gleichmäßig aus, wenn Sie den Mauszeiger über den Fernseher bewegen
- `.hover:tv:align-content-start` - Richten Sie den Inhalt aus, indem Sie ihn mit der Maus über den Fernseher bewegen
- `.hover:tv:align-content-stretch` - Richten Sie die Inhaltsausdehnung aus, wenn Sie den Mauszeiger auf dem Fernseher bewegen
- `.tv:align-content-around` - Richten Sie Inhalte im Fernsehen aus
- `.tv:align-content-between` - Richten Sie Inhalte im Fernsehen aus
- `.tv:align-content-center` - Inhaltscenter auf dem Fernseher ausrichten
- `.tv:align-content-end` - Richten Sie den Inhalt am Ende des Fernsehers aus
- `.tv:align-content-evenly` - Richten Sie Inhalte gleichmäßig auf dem Fernseher aus
- `.tv:align-content-start` - Richten Sie den Inhaltsstart im Fernsehen aus
- `.tv:align-content-stretch` - Richten Sie den Inhalt auf dem Fernseher aus

##### Align content - Tablet Max (< 768px)

- `.hover:tablet-max:align-content-around` - Richten Sie den Inhalt beim Hover auf dem Tablet maximal aus
- `.hover:tablet-max:align-content-between` - Richten Sie den Inhalt beim Hover auf dem Tablet max. aus
- `.hover:tablet-max:align-content-center` - Richten Sie den Inhalt beim Hover auf dem Tablet maximal zentriert aus
- `.hover:tablet-max:align-content-end` - Richten Sie den Inhalt am Ende aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet-max:align-content-evenly` - Richten Sie den Inhalt gleichmäßig aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet-max:align-content-start` - Inhalte ausrichten, beginnend beim Hover auf dem Tablet max
- `.hover:tablet-max:align-content-stretch` - Richten Sie den Inhalt beim Hover auf dem Tablet maximal aus
- `.tablet-max:align-content-around` - Richten Sie den Inhalt maximal auf dem Tablet aus
- `.tablet-max:align-content-between` - Inhalte auf dem Tablet max. ausrichten
- `.tablet-max:align-content-center` - Richten Sie das Inhaltscenter maximal auf dem Tablet aus
- `.tablet-max:align-content-end` - Richten Sie den Inhalt maximal auf dem Tablet aus
- `.tablet-max:align-content-evenly` - Richten Sie den Inhalt gleichmäßig auf dem Tablet aus, max
- `.tablet-max:align-content-start` - Inhalte ab Beginn auf Tablet ausrichten max
- `.tablet-max:align-content-stretch` - Inhalt auf dem Tablet maximal ausrichten

##### Align content - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:align-content-around` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC max. aus
- `.hover:tablet-pc-max:align-content-between` - Inhalte beim Hover auf Tablet-PC max. ausrichten
- `.hover:tablet-pc-max:align-content-center` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC max. zentriert aus
- `.hover:tablet-pc-max:align-content-end` - Richten Sie den Inhalt am Ende des Hovers auf dem Tablet-PC aus
- `.hover:tablet-pc-max:align-content-evenly` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC gleichmäßig aus
- `.hover:tablet-pc-max:align-content-start` - Inhalte ausrichten, beginnend beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:align-content-stretch` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC maximal aus
- `.tablet-pc-max:align-content-around` - Richten Sie Inhalte maximal auf dem Tablet-PC aus
- `.tablet-pc-max:align-content-between` - Inhalte auf Tablet-PC max. ausrichten
- `.tablet-pc-max:align-content-center` - Inhaltscenter auf Tablet-PC max. ausrichten
- `.tablet-pc-max:align-content-end` - Inhalt am Tablet-PC max. ausrichten
- `.tablet-pc-max:align-content-evenly` - Inhalte gleichmäßig auf dem Tablet-PC ausrichten max
- `.tablet-pc-max:align-content-start` - Inhalt auf Tablet-PC starten max
- `.tablet-pc-max:align-content-stretch` - Inhalt auf Tablet-PC maximal ausrichten

##### Align content - Pc Max (< 1200px)

- `.hover:pc-max:align-content-around` - Richten Sie den Inhalt beim Hover auf dem PC max. aus
- `.hover:pc-max:align-content-between` - Inhalte beim Hover auf dem PC max. ausrichten
- `.hover:pc-max:align-content-center` - Richten Sie das Inhaltscenter beim Hover auf dem PC max. aus
- `.hover:pc-max:align-content-end` - Richten Sie den Inhalt am Ende des Hovers auf dem PC aus
- `.hover:pc-max:align-content-evenly` - Richten Sie den Inhalt beim Hover auf dem PC gleichmäßig aus
- `.hover:pc-max:align-content-start` - Richten Sie den Inhalt beim Hover auf dem PC aus, max
- `.hover:pc-max:align-content-stretch` - Inhaltsdehnung beim Hover auf PC max. ausrichten
- `.pc-max:align-content-around` - Richten Sie den Inhalt maximal auf dem PC aus
- `.pc-max:align-content-between` - Inhalte auf PC max. ausrichten
- `.pc-max:align-content-center` - Richten Sie das Inhaltscenter maximal auf dem PC aus
- `.pc-max:align-content-end` - Inhalt am PC max. ausrichten
- `.pc-max:align-content-evenly` - Inhalte gleichmäßig auf dem PC ausrichten, max
- `.pc-max:align-content-start` - Inhalte ab Anfang am PC ausrichten max
- `.pc-max:align-content-stretch` - Inhaltsdehnung auf PC max. ausrichten

### Align items

- `.align-items-center` - Elemente zentriert ausrichten
- `.align-items-end` - Elemente am Ende ausrichten
- `.align-items-start` - Elemente ausrichten beginnen
- `.align-items-stretch` - Richten Sie die Elemente streckend aus
- `.hover:align-items-center` - Elemente beim Schweben zentriert ausrichten
- `.hover:align-items-end` - Elemente ausrichten enden beim Schweben
- `.hover:align-items-start` - Das Ausrichten von Elementen beginnt beim Schweben
- `.hover:align-items-stretch` - Richten Sie die gestreckten Elemente beim Schweben aus

##### Align items - Mobile (< 480px)

- `.hover:mobile:align-items-center` - Richten Sie Elemente beim Bewegen des Mauszeigers auf dem Mobilgerät zentriert aus
- `.hover:mobile:align-items-end` - Richten Sie Elemente am Ende aus, wenn Sie den Mauszeiger auf dem Mobilgerät bewegen
- `.hover:mobile:align-items-start` - Das Ausrichten von Elementen beginnt beim Hover auf Mobilgeräten
- `.hover:mobile:align-items-stretch` - Richten Sie Elemente aus, wenn Sie den Mauszeiger auf dem Mobilgerät bewegen
- `.mobile:align-items-center` - Richten Sie Elemente auf dem Mobilgerät zentriert aus
- `.mobile:align-items-end` - Elemente am Ende auf Mobilgeräten ausrichten
- `.mobile:align-items-start` - Das Ausrichten von Elementen beginnt auf Mobilgeräten
- `.mobile:align-items-stretch` - Richten Sie die gestreckten Elemente auf dem Mobilgerät aus

##### Align items - Tablet (480px - 768px)

- `.hover:tablet:align-items-center` - Richten Sie Elemente beim Bewegen des Mauszeigers auf dem Tablet zentriert aus
- `.hover:tablet:align-items-end` - Richten Sie die Enden der Elemente aus, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet:align-items-start` - Das Ausrichten von Elementen beginnt, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet:align-items-stretch` - Richten Sie Elemente aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.tablet:align-items-center` - Richten Sie die Elemente mittig auf dem Tablet aus
- `.tablet:align-items-end` - Richten Sie die Enden der Elemente auf dem Tablet aus
- `.tablet:align-items-start` - Richten Sie Elemente beginnend auf dem Tablet aus
- `.tablet:align-items-stretch` - Richten Sie die Elemente auf dem Tablet aus

##### Align items - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-items-center` - Richten Sie Elemente beim Bewegen des Mauszeigers auf dem Tablet-PC zentriert aus
- `.hover:tablet-pc:align-items-end` - Richten Sie die Enden der Elemente aus, wenn Sie den Mauszeiger auf dem Tablet-PC halten
- `.hover:tablet-pc:align-items-start` - Das Ausrichten von Elementen beginnt beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:align-items-stretch` - Richten Sie die gestreckten Elemente beim Schweben auf dem Tablet-PC aus
- `.tablet-pc:align-items-center` - Richten Sie die Elemente auf dem Tablet-PC zentriert aus
- `.tablet-pc:align-items-end` - Richten Sie die Enden der Elemente auf dem Tablet-PC aus
- `.tablet-pc:align-items-start` - Ausrichten von Elementen beginnt auf dem Tablet-PC
- `.tablet-pc:align-items-stretch` - Richten Sie die gestreckten Elemente auf dem Tablet-PC aus

##### Align items - Pc (992px - 1200px)

- `.hover:pc:align-items-center` - Richten Sie die Elemente beim Bewegen des Mauszeigers auf dem PC zentriert aus
- `.hover:pc:align-items-end` - Richten Sie die Enden der Elemente aus, wenn Sie den Mauszeiger auf dem PC halten
- `.hover:pc:align-items-start` - Das Ausrichten von Elementen beginnt beim Hover auf dem PC
- `.hover:pc:align-items-stretch` - Richten Sie die gestreckten Elemente beim Schweben auf dem PC aus
- `.pc:align-items-center` - Richten Sie die Elemente auf dem PC zentriert aus
- `.pc:align-items-end` - Richten Sie die Enden der Elemente am PC aus
- `.pc:align-items-start` - Richten Sie die Elemente auf dem PC aus
- `.pc:align-items-stretch` - Richten Sie die gestreckten Elemente am PC aus

##### Align items - Tv (> 1200px)

- `.hover:tv:align-items-center` - Richten Sie die Elemente beim Bewegen des Mauszeigers auf dem Fernseher zentriert aus
- `.hover:tv:align-items-end` - Richten Sie Elemente aus, wenn Sie mit der Maus über den Fernseher fahren
- `.hover:tv:align-items-start` - Das Ausrichten von Elementen beginnt, wenn Sie mit der Maus über den Fernseher fahren
- `.hover:tv:align-items-stretch` - Richten Sie die gestreckten Elemente beim Schweben auf dem Fernseher aus
- `.tv:align-items-center` - Richten Sie die Gegenstände auf dem Fernseher zentriert aus
- `.tv:align-items-end` - Richten Sie die Elemente am Ende des Fernsehers aus
- `.tv:align-items-start` - Richten Sie die Elemente auf dem Fernseher aus
- `.tv:align-items-stretch` - Richten Sie die gestreckten Gegenstände auf dem Fernseher aus

##### Align items - Tablet Max (< 768px)

- `.hover:tablet-max:align-items-center` - Elemente beim Hovern auf dem Tablet zentriert ausrichten, max
- `.hover:tablet-max:align-items-end` - Richten Sie Elemente bis zum Ende aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet-max:align-items-start` - Ausrichten von Elementen beginnt beim Hover auf dem Tablet max
- `.hover:tablet-max:align-items-stretch` - Elemente ausrichten, wenn man den Mauszeiger auf dem Tablet hält, max
- `.tablet-max:align-items-center` - Richten Sie Gegenstände max. mittig auf dem Tablet aus
- `.tablet-max:align-items-end` - Richten Sie die Gegenstände maximal auf dem Tablet aus
- `.tablet-max:align-items-start` - Elemente ausrichten, beginnend auf dem Tablet max
- `.tablet-max:align-items-stretch` - Richten Sie Gegenstände maximal auf dem Tablet aus

##### Align items - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:align-items-center` - Elemente beim Hovern auf dem Tablet-PC zentriert ausrichten, max
- `.hover:tablet-pc-max:align-items-end` - Richten Sie Elemente bis zum Ende aus, wenn Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.hover:tablet-pc-max:align-items-start` - Ausrichten von Elementen beginnt beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:align-items-stretch` - Ausrichten von Elementen beim Schweben auf dem Tablet-PC max
- `.tablet-pc-max:align-items-center` - Richten Sie Elemente maximal auf dem Tablet-PC mittig aus
- `.tablet-pc-max:align-items-end` - Richten Sie die Elemente maximal auf dem Tablet-PC aus
- `.tablet-pc-max:align-items-start` - Elemente ausrichten beginnend auf Tablet-PC max
- `.tablet-pc-max:align-items-stretch` - Ausrichten von Gegenständen auf dem Tablet-PC max

##### Align items - Pc Max (< 1200px)

- `.hover:pc-max:align-items-center` - Elemente beim Hover auf dem PC zentriert ausrichten, max
- `.hover:pc-max:align-items-end` - Richten Sie Elemente bis zum Ende aus, wenn Sie den Mauszeiger auf dem PC halten
- `.hover:pc-max:align-items-start` - Ausrichten von Elementen beginnt beim Hover auf dem PC max
- `.hover:pc-max:align-items-stretch` - Ausrichten von Elementen beim Schweben auf dem PC max
- `.pc-max:align-items-center` - Richten Sie die Elemente max. mittig auf dem PC aus
- `.pc-max:align-items-end` - Richten Sie die Elemente maximal auf dem PC aus
- `.pc-max:align-items-start` - Elemente ausrichten beginnend auf dem PC max
- `.pc-max:align-items-stretch` - Ausrichten von Gegenständen auf dem PC max

### Align self

- `.align-self-center` - Selbstzentriert ausrichten
- `.align-self-end` - Selbstende ausrichten
- `.align-self-start` - Selbststart ausrichten
- `.align-self-stretch` - Selbstdehnung ausrichten
- `.hover:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben aus
- `.hover:align-self-end` - Richten Sie das Selbstende beim Schweben aus
- `.hover:align-self-start` - Selbststart beim Schweben ausrichten
- `.hover:align-self-stretch` - Richten Sie die Selbstdehnung beim Schweben aus

##### Align self - Mobile (< 480px)

- `.hover:mobile:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben auf dem Mobilgerät aus
- `.hover:mobile:align-self-end` - Richten Sie das Selbstende beim Hover auf dem Mobilgerät aus
- `.hover:mobile:align-self-start` - Richten Sie den Selbststart beim Hover auf Mobilgeräten aus
- `.hover:mobile:align-self-stretch` - Richten Sie die Selbstdehnung beim Hover auf dem Mobilgerät aus
- `.mobile:align-self-center` - Richten Sie die Selbstzentrierung auf Mobilgeräten aus
- `.mobile:align-self-end` - Selbstende am Mobilgerät ausrichten
- `.mobile:align-self-start` - Richten Sie den Selbststart auf Mobilgeräten aus
- `.mobile:align-self-stretch` - Richten Sie die Selbstdehnung auf dem Mobilgerät aus

##### Align self - Tablet (480px - 768px)

- `.hover:tablet:align-self-center` - Richten Sie die Selbstzentrierung aus, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet:align-self-end` - Richten Sie das Selbstende aus, wenn Sie den Mauszeiger über das Tablet halten
- `.hover:tablet:align-self-start` - Richten Sie den Selbststart beim Schweben auf dem Tablet aus
- `.hover:tablet:align-self-stretch` - Richten Sie die Selbstdehnung aus, wenn Sie mit der Maus über das Tablet fahren
- `.tablet:align-self-center` - Richten Sie die Selbstzentrierung auf dem Tablet aus
- `.tablet:align-self-end` - Richten Sie das Ende am Tablet aus
- `.tablet:align-self-start` - Richten Sie den Selbststart am Tablet aus
- `.tablet:align-self-stretch` - Richten Sie die Selbstdehnung am Tablet aus

##### Align self - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:align-self-center` - Richten Sie sich beim Schweben auf dem Tablet-PC selbstzentriert aus
- `.hover:tablet-pc:align-self-end` - Richten Sie das Selbstende beim Hover auf dem Tablet-PC aus
- `.hover:tablet-pc:align-self-start` - Richten Sie den Selbststart beim Schweben auf dem Tablet-PC aus
- `.hover:tablet-pc:align-self-stretch` - Richten Sie die Selbstdehnung beim Schweben auf dem Tablet-PC aus
- `.tablet-pc:align-self-center` - Richten Sie die Selbstzentrierung auf dem Tablet-PC aus
- `.tablet-pc:align-self-end` - Richten Sie das Selbstende am Tablet-PC aus
- `.tablet-pc:align-self-start` - Richten Sie den Selbststart auf dem Tablet-PC aus
- `.tablet-pc:align-self-stretch` - Richten Sie die Selbstdehnung auf dem Tablet-PC aus

##### Align self - Pc (992px - 1200px)

- `.hover:pc:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben auf dem PC aus
- `.hover:pc:align-self-end` - Richten Sie das Selbstende beim Hover auf dem PC aus
- `.hover:pc:align-self-start` - Richten Sie den Selbststart beim Hover auf dem PC aus
- `.hover:pc:align-self-stretch` - Richten Sie die Selbstdehnung beim Schweben auf dem PC aus
- `.pc:align-self-center` - Richten Sie die Selbstzentrierung am PC aus
- `.pc:align-self-end` - Selbstende am PC ausrichten
- `.pc:align-self-start` - Selbststart am PC ausrichten
- `.pc:align-self-stretch` - Richten Sie die Selbstdehnung am PC aus

##### Align self - Tv (> 1200px)

- `.hover:tv:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben auf dem Fernseher aus
- `.hover:tv:align-self-end` - Richten Sie das Selbstende aus, wenn Sie mit der Maus über den Fernseher schweben
- `.hover:tv:align-self-start` - Richten Sie den Selbststart beim Schweben auf dem Fernseher aus
- `.hover:tv:align-self-stretch` - Richten Sie die Selbstdehnung beim Schweben im Fernsehen aus
- `.tv:align-self-center` - Richten Sie Ihre Selbstzentrierung im Fernsehen aus
- `.tv:align-self-end` - Richten Sie das Selbstende am Fernseher aus
- `.tv:align-self-start` - Richten Sie den Selbststart am Fernseher aus
- `.tv:align-self-stretch` - Richten Sie die Selbstdehnung im Fernsehen aus

##### Align self - Tablet Max (< 768px)

- `.hover:tablet-max:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben auf dem Tablet maximal aus
- `.hover:tablet-max:align-self-end` - Richten Sie das Selbstende aus, wenn Sie den Mauszeiger auf dem Tablet halten, max
- `.hover:tablet-max:align-self-start` - Selbststart beim Hover auf dem Tablet max. ausrichten
- `.hover:tablet-max:align-self-stretch` - Richten Sie die Selbstdehnung beim Schweben auf dem Tablet maximal aus
- `.tablet-max:align-self-center` - Selbstzentriert auf dem Tablet max. ausrichten
- `.tablet-max:align-self-end` - Selbstende am Tablet max. ausrichten
- `.tablet-max:align-self-start` - Selbststart am Tablet max. ausrichten
- `.tablet-max:align-self-stretch` - Richten Sie die Selbstdehnung am Tablet max. aus

##### Align self - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben auf dem Tablet-PC max. aus
- `.hover:tablet-pc-max:align-self-end` - Richten Sie das Selbstende beim Hover auf dem Tablet-PC aus, max
- `.hover:tablet-pc-max:align-self-start` - Selbststart beim Schweben auf Tablet-PC max. ausrichten
- `.hover:tablet-pc-max:align-self-stretch` - Selbstdehnung beim Schweben auf dem Tablet-PC max. ausrichten
- `.tablet-pc-max:align-self-center` - Selbstzentrierung am Tablet-PC max
- `.tablet-pc-max:align-self-end` - Selbstende am Tablet-PC ausrichten max
- `.tablet-pc-max:align-self-start` - Selbststart am Tablet-PC ausrichten max
- `.tablet-pc-max:align-self-stretch` - Selbstdehnung am Tablet-PC max. ausrichten

##### Align self - Pc Max (< 1200px)

- `.hover:pc-max:align-self-center` - Richten Sie die Selbstzentrierung beim Schweben auf dem PC max. aus
- `.hover:pc-max:align-self-end` - Selbstende beim Schweben auf dem PC ausrichten, max
- `.hover:pc-max:align-self-start` - Selbststart beim Hover auf PC max. ausrichten
- `.hover:pc-max:align-self-stretch` - Selbstdehnung beim Schweben auf dem PC ausrichten, max
- `.pc-max:align-self-center` - Selbstzentriert am PC max. ausrichten
- `.pc-max:align-self-end` - Selbstende am PC ausrichten max
- `.pc-max:align-self-start` - Selbststart am PC ausrichten max
- `.pc-max:align-self-stretch` - Selbstdehnung am PC max. ausrichten

### Justify content

- `.hover:justify-content-around` - Richten Sie den Inhalt beim Hover aus
- `.hover:justify-content-between` - Richten Sie den Inhalt beim Hover aus
- `.hover:justify-content-center` - Richten Sie den Inhalt im Center aus, wenn Sie den Mauszeiger darüber bewegen
- `.hover:justify-content-end` - Inhalt ausrichten, Ende beim Hover
- `.hover:justify-content-evenly` - Richten Sie den Inhalt beim Schweben gleichmäßig aus
- `.hover:justify-content-start` - Begründen Sie den Start des Inhalts beim Hover
- `.hover:justify-content-stretch` - Begründen Sie die Ausdehnung des Inhalts beim Hover
- `.justify-content-around` - Begründen Sie den Inhalt
- `.justify-content-between` - Begründen Sie den Inhalt zwischen
- `.justify-content-center` - Begründen Sie das Inhaltscenter
- `.justify-content-end` - Begründen Sie den Inhalt am Ende
- `.justify-content-evenly` - Begründen Sie Inhalte gleichmäßig
- `.justify-content-start` - Begründen Sie den Beginn des Inhalts
- `.justify-content-stretch` - Begründen Sie die Ausdehnung des Inhalts

##### Justify content - Mobile (< 480px)

- `.hover:mobile:justify-content-around` - Richten Sie Inhalte aus, wenn Sie den Mauszeiger auf Mobilgeräten bewegen
- `.hover:mobile:justify-content-between` - Richten Sie den Inhalt beim Bewegen des Mauszeigers auf dem Mobilgerät aus
- `.hover:mobile:justify-content-center` - Begründen Sie das Inhaltscenter beim Hover auf Mobilgeräten
- `.hover:mobile:justify-content-end` - Begründen Sie das Ende des Inhalts, wenn Sie den Mauszeiger auf dem Mobilgerät bewegen
- `.hover:mobile:justify-content-start` - Begründen Sie den Start des Inhalts beim Hover auf Mobilgeräten
- `.mobile:justify-content-around` - Begründen Sie Inhalte auf Mobilgeräten
- `.mobile:justify-content-between` - Begründen Sie Inhalte zwischen Mobilgeräten
- `.mobile:justify-content-center` - Begründen Sie das Content Center auf Mobilgeräten
- `.mobile:justify-content-end` - Begründen Sie das Ende des Inhalts auf Mobilgeräten
- `.mobile:justify-content-start` - Begründen Sie den Start von Inhalten auf Mobilgeräten

##### Justify content - Tablet (480px - 768px)

- `.hover:tablet:justify-content-around` - Richten Sie den Inhalt aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet:justify-content-between` - Richten Sie den Inhalt aus, indem Sie den Mauszeiger auf das Tablet bewegen
- `.hover:tablet:justify-content-center` - Richten Sie das Inhaltscenter aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet:justify-content-end` - Begründen Sie das Ende des Inhalts, indem Sie den Mauszeiger auf das Tablet bewegen
- `.hover:tablet:justify-content-start` - Begründen Sie den Start des Inhalts, wenn Sie den Mauszeiger auf dem Tablet halten
- `.tablet:justify-content-around` - Richten Sie Inhalte auf dem Tablet aus
- `.tablet:justify-content-between` - Richten Sie Inhalte auf dem Tablet aus
- `.tablet:justify-content-center` - Inhaltscenter auf dem Tablet ausrichten
- `.tablet:justify-content-end` - Begründen Sie das Ende des Inhalts auf dem Tablet
- `.tablet:justify-content-start` - Begründen Sie den Beginn des Inhalts auf dem Tablet

##### Justify content - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:justify-content-around` - Richten Sie Inhalte aus, wenn Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.hover:tablet-pc:justify-content-between` - Begründen Sie den Inhalt zwischen dem Hover auf dem Tablet-PC
- `.hover:tablet-pc:justify-content-center` - Richten Sie das Inhaltscenter aus, wenn Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.hover:tablet-pc:justify-content-end` - Begründen Sie das Ende des Inhalts, wenn Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.hover:tablet-pc:justify-content-start` - Begründen Sie den Start des Inhalts, indem Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.tablet-pc:justify-content-around` - Richten Sie Inhalte auf dem Tablet-PC aus
- `.tablet-pc:justify-content-between` - Begründen Sie den Inhalt zwischen auf dem Tablet-PC
- `.tablet-pc:justify-content-center` - Begründen Sie das Inhaltscenter auf dem Tablet-PC
- `.tablet-pc:justify-content-end` - Begründen Sie das Ende des Inhalts auf dem Tablet-PC
- `.tablet-pc:justify-content-start` - Begründen Sie den Beginn des Inhalts auf dem Tablet-PC

##### Justify content - Pc (992px - 1200px)

- `.hover:pc:justify-content-around` - Richten Sie den Inhalt beim Hover auf dem PC aus
- `.hover:pc:justify-content-between` - Richten Sie den Inhalt aus, indem Sie den Mauszeiger auf den PC bewegen
- `.hover:pc:justify-content-center` - Richten Sie das Inhaltscenter aus, wenn Sie den Mauszeiger auf dem PC bewegen
- `.hover:pc:justify-content-end` - Begründen Sie das Ende des Inhalts, indem Sie den Mauszeiger auf den PC bewegen
- `.hover:pc:justify-content-start` - Begründen Sie den Start des Inhalts beim Hover auf dem PC
- `.pc:justify-content-around` - Richten Sie Inhalte auf dem PC aus
- `.pc:justify-content-between` - Begründen Sie den Inhalt zwischen auf dem PC
- `.pc:justify-content-center` - Begründen Sie das Content Center auf dem PC
- `.pc:justify-content-end` - Begründen Sie das Ende des Inhalts am PC
- `.pc:justify-content-start` - Begründen Sie den Beginn des Inhalts auf dem PC

##### Justify content - Tv (> 1200px)

- `.hover:tv:justify-content-around` - Richten Sie Inhalte aus, indem Sie den Mauszeiger auf dem Fernseher bewegen
- `.hover:tv:justify-content-between` - Begründen Sie den Inhalt zwischen dem Schweben im Fernsehen
- `.hover:tv:justify-content-center` - Begründen Sie das Inhaltscenter, indem Sie den Mauszeiger über den Fernseher bewegen
- `.hover:tv:justify-content-end` - Begründen Sie das Ende des Inhalts, indem Sie den Mauszeiger auf dem Fernseher bewegen
- `.hover:tv:justify-content-start` - Begründen Sie den Start des Inhalts, indem Sie den Mauszeiger über den Fernseher bewegen
- `.tv:justify-content-around` - Begründen Sie Inhalte im Fernsehen
- `.tv:justify-content-between` - Begründen Sie Inhalte im Fernsehen
- `.tv:justify-content-center` - Begründen Sie das Content Center im Fernsehen
- `.tv:justify-content-end` - Begründen Sie das Ende des Inhalts im Fernsehen
- `.tv:justify-content-start` - Begründen Sie den Start von Inhalten im Fernsehen

##### Justify content - Tablet Max (< 768px)

- `.hover:tablet-max:justify-content-around` - Richten Sie den Inhalt beim Hover auf dem Tablet max. aus
- `.hover:tablet-max:justify-content-between` - Inhalt ausrichten zwischen beim Hovern auf dem Tablet max
- `.hover:tablet-max:justify-content-center` - Richten Sie den Inhalt im Mittelpunkt aus, wenn Sie den Mauszeiger auf dem Tablet halten
- `.hover:tablet-max:justify-content-end` - Inhalt ausrichten, Ende bei Hover auf dem Tablet max
- `.hover:tablet-max:justify-content-start` - Begründen Sie den Beginn des Inhalts beim Bewegen des Mauszeigers auf dem Tablet max
- `.tablet-max:justify-content-around` - Richten Sie Inhalte auf dem Tablet maximal aus
- `.tablet-max:justify-content-between` - Inhalt zwischen auf dem Tablet max. ausrichten
- `.tablet-max:justify-content-center` - Inhaltscenter auf Tablet max. ausrichten
- `.tablet-max:justify-content-end` - Inhalt rechtfertigen, Ende auf Tablet max
- `.tablet-max:justify-content-start` - Inhaltsbeginn auf Tablet max. begründen

##### Justify content - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:justify-content-around` - Richten Sie den Inhalt beim Hover auf dem Tablet-PC max. aus
- `.hover:tablet-pc-max:justify-content-between` - Inhalt ausrichten zwischen beim Bewegen des Mauszeigers auf dem Tablet-PC max
- `.hover:tablet-pc-max:justify-content-center` - Inhaltscenter bei Hover auf Tablet-PC ausrichten max
- `.hover:tablet-pc-max:justify-content-end` - Inhalt ausrichten Ende bei Hover auf Tablet-PC max
- `.hover:tablet-pc-max:justify-content-start` - Inhalt rechtfertigen, Start beim Hover auf Tablet-PC max
- `.tablet-pc-max:justify-content-around` - Richten Sie Inhalte auf dem Tablet-PC max. aus
- `.tablet-pc-max:justify-content-between` - Inhalt ausrichten zwischen auf Tablet-PC max
- `.tablet-pc-max:justify-content-center` - Inhaltscenter auf Tablet-PC max. ausrichten
- `.tablet-pc-max:justify-content-end` - Inhalt ausrichten Ende auf Tablet-PC max
- `.tablet-pc-max:justify-content-start` - Inhalt rechtfertigen Start auf Tablet-PC max

##### Justify content - Pc Max (< 1200px)

- `.hover:pc-max:justify-content-around` - Richten Sie den Inhalt beim Hover auf dem PC max. aus
- `.hover:pc-max:justify-content-between` - Inhalt ausrichten zwischen beim Hover auf dem PC max
- `.hover:pc-max:justify-content-center` - Inhaltscenter beim Hover auf dem PC ausrichten, max
- `.hover:pc-max:justify-content-end` - Inhalt ausrichten, Ende bei Hover auf PC max
- `.hover:pc-max:justify-content-start` - Begründen Sie den Start des Inhalts beim Hover auf dem PC max
- `.pc-max:justify-content-around` - Inhalte auf dem PC max. ausrichten
- `.pc-max:justify-content-between` - Inhalt zwischen auf PC max. ausrichten
- `.pc-max:justify-content-center` - Inhaltscenter auf PC max. ausrichten
- `.pc-max:justify-content-end` - Inhalt rechtfertigen Ende auf PC max
- `.pc-max:justify-content-start` - Inhaltsbeginn auf PC max. begründen

### Justify items

- `.hover:justify-items-center` - Richten Sie die Elemente beim Schweben zentriert aus
- `.hover:justify-items-end` - Elemente ausrichten, die beim Hover enden
- `.hover:justify-items-start` - Elemente ausrichten beginnen beim Hover
- `.hover:justify-items-stretch` - Richten Sie Elemente aus, die beim Schweben gedehnt werden
- `.justify-items-center` - Richten Sie Elemente in der Mitte aus
- `.justify-items-end` - Begründen Sie das Ende der Elemente
- `.justify-items-start` - Artikelanfang ausrichten
- `.justify-items-stretch` - Richten Sie die Dehnung von Elementen aus

### Order

- `.hover:order-5` - Bestellen Sie 5 beim Schweben
- `.hover:order-4` - Bestellen Sie 4 beim Schweben
- `.hover:order-3` - Bestellen Sie 3 beim Schweben
- `.hover:order-2` - Bestellen Sie 2 beim Schweben
- `.hover:order-1` - Bestellen Sie 1 beim Schweben
- `.hover:order-0` - Bestellen Sie 0 beim Schweben
- `.hover:order-first` - Bestellen Sie zuerst mit der Maus
- `.hover:order-last` - Bestellen Sie zuletzt, wenn Sie mit der Maus darüber fahren
- `.order-5` - Bestellen Sie 5
- `.order-4` - Bestellen Sie 4
- `.order-3` - Bestellung 3
- `.order-2` - Bestellung 2
- `.order-1` - Bestellung 1
- `.order-0` - Bestellen Sie 0
- `.order-first` - Zuerst bestellen
- `.order-last` - Zuletzt bestellen

##### Negative Order

- `.-order-5` - Negative Anordnung 5
- `.-order-4` - Negative Anordnung 4
- `.-order-3` - Negative Anordnung 3
- `.-order-2` - Negativer Befehl 2
- `.-order-1` - Negativer Befehl 1
- `.hover:-order-5` - Negativer Befehl 5 beim Schweben
- `.hover:-order-4` - Negativer Befehl 4 beim Schweben
- `.hover:-order-3` - Negativer Befehl 3 beim Schweben
- `.hover:-order-2` - Negativer Befehl 2 beim Schweben
- `.hover:-order-1` - Negativer Befehl 1 beim Schweben

##### Order - Mobile (< 480px)

- `.hover:mobile:order-5` - Bestellen Sie 5, indem Sie den Mauszeiger auf dem Handy bewegen
- `.hover:mobile:order-4` - Bestellen Sie 4, indem Sie den Mauszeiger auf dem Handy bewegen
- `.hover:mobile:order-3` - Bestellen Sie 3, indem Sie den Mauszeiger auf dem Handy bewegen
- `.hover:mobile:order-2` - Bestellen Sie 2, indem Sie den Mauszeiger auf dem Handy bewegen
- `.hover:mobile:order-1` - Bestellen Sie 1, indem Sie den Mauszeiger auf dem Handy bewegen
- `.hover:mobile:order-0` - Bestellen Sie 0, wenn Sie den Mauszeiger auf dem Mobilgerät bewegen
- `.hover:mobile:order-first` - Bestellen Sie zuerst, indem Sie den Mauszeiger auf dem Handy bewegen
- `.hover:mobile:order-last` - Bestellen Sie zuletzt, wenn Sie den Mauszeiger auf dem Handy bewegen
- `.mobile:order-5` - Bestellen Sie 5 Stück auf dem Handy
- `.mobile:order-4` - Bestellen Sie 4 auf dem Handy
- `.mobile:order-3` - Bestellen Sie 3 auf dem Handy
- `.mobile:order-2` - Bestellen Sie 2 auf dem Handy
- `.mobile:order-1` - Bestellen Sie 1 auf dem Handy
- `.mobile:order-0` - Bestellen Sie 0 auf dem Handy
- `.mobile:order-first` - Bestellen Sie zuerst auf dem Handy
- `.mobile:order-last` - Bestellen Sie zuletzt auf dem Handy

##### Negative Order - Mobile (< 480px)

- `.hover:mobile:-order-5` - Negative Order 5 beim Hover auf dem Handy
- `.hover:mobile:-order-4` - Negative Order 4 beim Hover auf dem Handy
- `.hover:mobile:-order-3` - Negative Order 3 beim Hover auf dem Handy
- `.hover:mobile:-order-2` - Negative Order 2 beim Hover auf dem Handy
- `.hover:mobile:-order-1` - Negative Bestellung 1 beim Hover auf dem Handy
- `.mobile:-order-5` - Negative Order 5 auf dem Handy
- `.mobile:-order-4` - Negative Order 4 auf dem Handy
- `.mobile:-order-3` - Negative Order 3 auf dem Handy
- `.mobile:-order-2` - Negative Order 2 auf dem Handy
- `.mobile:-order-1` - Negative Bestellung 1 auf dem Handy

##### Order - Tablet (480px - 768px)

- `.hover:tablet:order-5` - Bestellen Sie 5, indem Sie mit der Maus über das Tablet fahren
- `.hover:tablet:order-4` - Bestellen Sie 4, indem Sie mit der Maus über das Tablet fahren
- `.hover:tablet:order-3` - Bestellen Sie 3, indem Sie mit der Maus über das Tablet fahren
- `.hover:tablet:order-2` - Bestellen Sie 2, indem Sie mit der Maus über das Tablet fahren
- `.hover:tablet:order-1` - Bestellen Sie 1, indem Sie mit der Maus über das Tablet fahren
- `.hover:tablet:order-0` - Bestellen Sie 0, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet:order-first` - Bestellen Sie zuerst, indem Sie den Mauszeiger auf das Tablet halten
- `.hover:tablet:order-last` - Bestellen Sie zuletzt, wenn Sie mit der Maus über das Tablet fahren
- `.tablet:order-5` - Bestellen Sie 5 auf dem Tablet
- `.tablet:order-4` - Bestellen Sie 4 auf dem Tablet
- `.tablet:order-3` - Bestellen Sie 3 auf dem Tablet
- `.tablet:order-2` - Bestellen Sie 2 auf dem Tablet
- `.tablet:order-1` - Bestellen Sie 1 auf dem Tablet
- `.tablet:order-0` - Bestellen Sie 0 auf dem Tablet
- `.tablet:order-first` - Bestellen Sie zuerst auf dem Tablet
- `.tablet:order-last` - Bestellen Sie zuletzt auf dem Tablet

##### Negative Order - Tablet (480px - 768px)

- `.hover:tablet:-order-5` - Negativbefehl 5 beim Hovern auf dem Tablet
- `.hover:tablet:-order-4` - Negativbefehl 4 beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:-order-3` - Negative Bestellung 3 beim Hovern auf dem Tablet
- `.hover:tablet:-order-2` - Negative Bestellung 2 beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:-order-1` - Negative Bestellung 1 beim Bewegen des Mauszeigers auf dem Tablet
- `.tablet:-order-5` - Negativer Auftrag 5 auf dem Tablet
- `.tablet:-order-4` - Negativer Auftrag 4 auf dem Tablet
- `.tablet:-order-3` - Negativer Auftrag 3 auf dem Tablet
- `.tablet:-order-2` - Negativer Auftrag 2 auf dem Tablet
- `.tablet:-order-1` - Negativauftrag 1 auf Tablet

##### Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:order-5` - Bestellen Sie 5 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:order-4` - Bestellen Sie 4 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:order-3` - Bestellen Sie 3 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:order-2` - Bestellen Sie 2, indem Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.hover:tablet-pc:order-1` - Bestellen Sie 1, indem Sie den Mauszeiger auf den Tablet-PC bewegen
- `.hover:tablet-pc:order-0` - Bestellen Sie 0 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:order-first` - Bestellen Sie zuerst, indem Sie den Mauszeiger auf den Tablet-PC bewegen
- `.hover:tablet-pc:order-last` - Bestellen Sie zuletzt, wenn Sie den Mauszeiger auf dem Tablet-PC bewegen
- `.tablet-pc:order-5` - Bestellen Sie 5 auf dem Tablet-PC
- `.tablet-pc:order-4` - Bestellen Sie 4 auf dem Tablet-PC
- `.tablet-pc:order-3` - Bestellen Sie 3 auf dem Tablet-PC
- `.tablet-pc:order-2` - Bestellen Sie 2 auf dem Tablet-PC
- `.tablet-pc:order-1` - Bestellen Sie 1 auf dem Tablet-PC
- `.tablet-pc:order-0` - Bestellen Sie 0 auf dem Tablet-PC
- `.tablet-pc:order-first` - Bestellen Sie zuerst auf dem Tablet-PC
- `.tablet-pc:order-last` - Bestellen Sie zuletzt auf dem Tablet-PC

##### Negative Order - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:-order-5` - Negativauftrag 5 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:-order-4` - Negativauftrag 4 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:-order-3` - Negativauftrag 3 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:-order-2` - Negative Bestellung 2 beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:-order-1` - Negative Bestellung 1 beim Hover auf dem Tablet-PC
- `.tablet-pc:-order-5` - Negativer Auftrag 5 auf Tablet-PC
- `.tablet-pc:-order-4` - Negativauftrag 4 auf Tablet-PC
- `.tablet-pc:-order-3` - Negativauftrag 3 auf Tablet-PC
- `.tablet-pc:-order-2` - Negativer Auftrag 2 auf Tablet-PC
- `.tablet-pc:-order-1` - Negativauftrag 1 auf Tablet-PC

##### Order - Pc (992px - 1200px)

- `.hover:pc:order-5` - Bestellen Sie 5 beim Hover auf dem PC
- `.hover:pc:order-4` - Bestellen Sie 4 beim Hover auf dem PC
- `.hover:pc:order-3` - Bestellen Sie 3 beim Hover auf dem PC
- `.hover:pc:order-2` - Bestellen Sie 2 beim Hover auf dem PC
- `.hover:pc:order-1` - Bestellen Sie 1, indem Sie den Mauszeiger auf den PC bewegen
- `.hover:pc:order-0` - Bestellen Sie 0, wenn Sie mit der Maus über den PC fahren
- `.hover:pc:order-first` - Bestellen Sie zuerst, indem Sie den Mauszeiger auf den PC bewegen
- `.hover:pc:order-last` - Bestellen Sie zuletzt, wenn Sie mit der Maus über den PC fahren
- `.pc:order-5` - Bestellen Sie 5 Stück pro Stück
- `.pc:order-4` - Bestellen Sie 4 auf PC
- `.pc:order-3` - Bestellen Sie 3 auf dem PC
- `.pc:order-2` - Bestellen Sie 2 auf PC
- `.pc:order-1` - Bestellen Sie 1 auf PC
- `.pc:order-0` - Bestellen Sie 0 auf dem PC
- `.pc:order-first` - Bestellen Sie zuerst am PC
- `.pc:order-last` - Zuletzt auf dem PC bestellen

##### Negative Order - Pc (992px - 1200px)

- `.hover:pc:-order-5` - Negative Ordnung 5 beim Hover auf dem PC
- `.hover:pc:-order-4` - Negative Ordnung 4 beim Hover auf dem PC
- `.hover:pc:-order-3` - Negative Ordnung 3 beim Hover auf dem PC
- `.hover:pc:-order-2` - Negative Ordnung 2 beim Hover auf dem PC
- `.hover:pc:-order-1` - Negative Ordnung 1 beim Hover auf dem PC
- `.pc:-order-5` - Negative Ordnung 5 auf PC
- `.pc:-order-4` - Negative Ordnung 4 auf PC
- `.pc:-order-3` - Negative Ordnung 3 auf PC
- `.pc:-order-2` - Negative Ordnung 2 auf PC
- `.pc:-order-1` - Negativauftrag 1 auf PC

##### Order - Tv (> 1200px)

- `.hover:tv:order-5` - Bestellen Sie 5 per Hover im Fernsehen
- `.hover:tv:order-4` - Bestellen Sie 4 per Hover im Fernsehen
- `.hover:tv:order-3` - Bestellen Sie 3 per Hover im Fernsehen
- `.hover:tv:order-2` - Bestellen Sie 2 per Hover im Fernsehen
- `.hover:tv:order-1` - Bestellen Sie 1 per Hover im Fernsehen
- `.hover:tv:order-0` - Bestellen Sie 0 beim Hover im Fernsehen
- `.hover:tv:order-first` - Bestellen Sie zuerst per Hover im Fernsehen
- `.hover:tv:order-last` - Bestellen Sie zuletzt, indem Sie im Fernsehen darüber schweben
- `.tv:order-5` - Bestellen Sie 5 im Fernsehen
- `.tv:order-4` - Bestellen Sie 4 im Fernsehen
- `.tv:order-3` - Bestellen Sie 3 im Fernsehen
- `.tv:order-2` - Bestellen Sie 2 im Fernsehen
- `.tv:order-1` - Bestellen Sie 1 im Fernsehen
- `.tv:order-0` - Bestellen Sie 0 im Fernsehen
- `.tv:order-first` - Bestellen Sie zuerst im Fernsehen
- `.tv:order-last` - Zuletzt im Fernsehen bestellen

##### Negative Order - Tv (> 1200px)

- `.hover:tv:-order-5` - Negative Order 5 beim Hover im Fernsehen
- `.hover:tv:-order-4` - Negative Order 4 im Hover im Fernsehen
- `.hover:tv:-order-3` - Negative Order 3 im Hover im Fernsehen
- `.hover:tv:-order-2` - Negative Order 2 im Hover im Fernsehen
- `.hover:tv:-order-1` - Negative Order 1 beim Hover im Fernsehen
- `.tv:-order-5` - Negative Order 5 im Fernsehen
- `.tv:-order-4` - Negative Order 4 im Fernsehen
- `.tv:-order-3` - Negative Order 3 im Fernsehen
- `.tv:-order-2` - Negative Order 2 im Fernsehen
- `.tv:-order-1` - Negative Order 1 im Fernsehen

##### Order - Tablet Max (< 768px)

- `.hover:tablet-max:order-5` - Bestellen Sie maximal 5 Stück, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet-max:order-4` - Bestellen Sie maximal 4, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet-max:order-3` - Bestellen Sie maximal 3, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet-max:order-2` - Bestellen Sie maximal 2, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet-max:order-1` - Bestellen Sie 1 Stück, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet-max:order-0` - Bestellen Sie 0, wenn Sie mit der Maus über das Tablet fahren
- `.hover:tablet-max:order-first` - Bestellen Sie zuerst, indem Sie den Mauszeiger auf das Tablet halten
- `.hover:tablet-max:order-last` - Bestellen Sie zuletzt, wenn Sie mit der Maus über das Tablet fahren
- `.tablet-max:order-5` - Bestellen Sie maximal 5 Stück auf dem Tablet
- `.tablet-max:order-4` - Bestellen Sie maximal 4 Stück auf dem Tablet
- `.tablet-max:order-3` - Bestellen Sie maximal 3 Stück auf dem Tablet
- `.tablet-max:order-2` - Bestellen Sie maximal 2 Stück auf dem Tablet
- `.tablet-max:order-1` - Bestellen Sie maximal 1 Tablette
- `.tablet-max:order-0` - Bestellen Sie 0 auf dem Tablet max
- `.tablet-max:order-first` - Bestellen Sie zuerst auf dem Tablet max
- `.tablet-max:order-last` - Bestellen Sie zuletzt auf dem Tablet max

##### Negative Order - Tablet Max (< 768px)

- `.hover:tablet-max:-order-5` - Negative Bestellung 5 beim Hover auf dem Tablet max
- `.hover:tablet-max:-order-4` - Negative Bestellung 4 beim Hover auf dem Tablet max
- `.hover:tablet-max:-order-3` - Negative Bestellung 3 beim Hover auf dem Tablet max
- `.hover:tablet-max:-order-2` - Negative Bestellung 2 beim Hover auf dem Tablet max
- `.hover:tablet-max:-order-1` - Negative Bestellung 1 beim Hover auf dem Tablet max
- `.tablet-max:-order-5` - Negative Bestellung 5 auf Tablet max
- `.tablet-max:-order-4` - Negative Bestellung 4 auf Tablet max
- `.tablet-max:-order-3` - Negativbestellung 3 auf Tablet max
- `.tablet-max:-order-2` - Negativbestellung 2 auf Tablet max
- `.tablet-max:-order-1` - Negativbestellung 1 auf Tablet max

##### Order - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:order-5` - Bestellen Sie maximal 5 Stück beim Hover auf dem Tablet-PC
- `.hover:tablet-pc-max:order-4` - Bestellen Sie 4 beim Hover auf dem Tablet-PC, max
- `.hover:tablet-pc-max:order-3` - Bestellen Sie 3 beim Hover auf dem Tablet-PC, max
- `.hover:tablet-pc-max:order-2` - Bestellen Sie 2 beim Hover auf dem Tablet-PC, max
- `.hover:tablet-pc-max:order-1` - Bestellen Sie 1 beim Hover auf dem Tablet-PC, max
- `.hover:tablet-pc-max:order-0` - Bestellen Sie 0 beim Hover auf dem Tablet-PC, max
- `.hover:tablet-pc-max:order-first` - Bestellen Sie zuerst beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:order-last` - Bestellen Sie zuletzt bei Hover auf dem Tablet-PC max
- `.tablet-pc-max:order-5` - Bestellen Sie maximal 5 Stück auf dem Tablet-PC
- `.tablet-pc-max:order-4` - Bestellen Sie maximal 4 Stück auf dem Tablet-PC
- `.tablet-pc-max:order-3` - Bestellen Sie maximal 3 Stück auf dem Tablet-PC
- `.tablet-pc-max:order-2` - Bestellen Sie maximal 2 Stück auf dem Tablet-PC
- `.tablet-pc-max:order-1` - Bestellen Sie maximal 1 Tablet-PC
- `.tablet-pc-max:order-0` - Bestellen Sie 0 auf Tablet-PC max
- `.tablet-pc-max:order-first` - Bestellen Sie zuerst auf dem Tablet-PC max
- `.tablet-pc-max:order-last` - Bestellen Sie zuletzt am Tablet-PC max

##### Negative Order - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:-order-5` - Negativbestellung 5 beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:-order-4` - Negative Bestellung 4 beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:-order-3` - Negative Bestellung 3 beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:-order-2` - Negative Bestellung 2 beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:-order-1` - Negative Bestellung 1 beim Hover auf dem Tablet-PC max
- `.tablet-pc-max:-order-5` - Negativbestellung 5 auf Tablet-PC max
- `.tablet-pc-max:-order-4` - Negativbestellung 4 auf Tablet-PC max
- `.tablet-pc-max:-order-3` - Negativbestellung 3 auf Tablet-PC max
- `.tablet-pc-max:-order-2` - Negativbestellung 2 auf Tablet-PC max
- `.tablet-pc-max:-order-1` - Negativbestellung 1 auf Tablet-PC max

##### Order - Pc Max (< 1200px)

- `.hover:pc-max:order-5` - Bestellen Sie maximal 5 beim Hover auf dem PC
- `.hover:pc-max:order-4` - Bestellen Sie maximal 4 beim Hover auf dem PC
- `.hover:pc-max:order-3` - Bestellen Sie maximal 3 beim Hover auf dem PC
- `.hover:pc-max:order-2` - Bestellen Sie maximal 2 beim Hover auf dem PC
- `.hover:pc-max:order-1` - Bestellen Sie 1 beim Hover auf dem PC, max
- `.hover:pc-max:order-0` - Bestellen Sie 0 beim Hover auf dem PC, max
- `.hover:pc-max:order-first` - Bestellen Sie zuerst mit der Maus über den PC, max
- `.hover:pc-max:order-last` - Bestellen Sie zuletzt beim Hover auf dem PC max
- `.pc-max:order-5` - Bestellen Sie maximal 5 Stück pro PC
- `.pc-max:order-4` - Bestellen Sie maximal 4 Stück pro PC
- `.pc-max:order-3` - Bestellen Sie maximal 3 Stück pro PC
- `.pc-max:order-2` - Bestellen Sie maximal 2 Stück pro PC
- `.pc-max:order-1` - Bestellen Sie max. 1 Stück pro PC
- `.pc-max:order-0` - Bestellen Sie max. 0 Stück pro PC
- `.pc-max:order-first` - Bestellen Sie zuerst auf dem PC max
- `.pc-max:order-last` - Bestellen Sie zuletzt auf dem PC max

##### Negative Order - Pc Max (< 1200px)

- `.hover:pc-max:-order-5` - Negative Ordnung 5 beim Hover auf dem PC max
- `.hover:pc-max:-order-4` - Negative Ordnung 4 beim Hover auf dem PC max
- `.hover:pc-max:-order-3` - Negative Ordnung 3 beim Hover auf dem PC max
- `.hover:pc-max:-order-2` - Negative Ordnung 2 beim Hover auf dem PC max
- `.hover:pc-max:-order-1` - Negative Reihenfolge 1 beim Hover auf dem PC max
- `.pc-max:-order-5` - Negativauftrag 5 auf PC max
- `.pc-max:-order-4` - Negativauftrag 4 auf PC max
- `.pc-max:-order-3` - Negativauftrag 3 auf PC max
- `.pc-max:-order-2` - Negativauftrag 2 auf PC max
- `.pc-max:-order-1` - Negativauftrag 1 auf PC max

## Spacing

### Margin

#### Margin All

- `.first:m-0` - Margin All 0rem zuerst
- `.hover:m-5` - Margin All 5rem beim Hover
- `.hover:m-4.5` - Margin All 0rem bei Hover
- `.hover:m-4` - Margin All 4rem beim Hover
- `.hover:m-3.5` - Margin All 0rem bei Hover
- `.hover:m-3` - Margin All 3rem beim Hover
- `.hover:m-2.5` - Margin All 0rem bei Hover
- `.hover:m-2` - Margin All 2rem beim Hover
- `.hover:m-1.9` - Margin All 0rem bei Hover
- `.hover:m-1.8` - Margin All 0rem bei Hover
- `.hover:m-1.7` - Margin All 0rem bei Hover
- `.hover:m-1.6` - Margin All 0rem bei Hover
- `.hover:m-1.5` - Margin All 0rem bei Hover
- `.hover:m-1.4` - Margin All 0rem bei Hover
- `.hover:m-1.3` - Margin All 0rem bei Hover
- `.hover:m-1.2` - Margin All 0rem bei Hover
- `.hover:m-1.1` - Margin All 0rem bei Hover
- `.hover:m-1` - Margin All 1rem beim Hover
- `.hover:m-0.9` - Margin All 0rem bei Hover
- `.hover:m-0.8` - Margin All 0rem bei Hover
- `.hover:m-0.7` - Margin All 0rem bei Hover
- `.hover:m-0.6` - Margin All 0rem bei Hover
- `.hover:m-0.5` - Margin All 0rem bei Hover
- `.hover:m-0.4` - Margin All 0rem bei Hover
- `.hover:m-0.3` - Margin All 0rem bei Hover
- `.hover:m-0.2` - Marge Alle 0,2rem beim Schweben
- `.hover:m-0.1` - Marge Alle 0,1rem beim Schweben
- `.hover:m-0` - Margin All 0rem bei Hover
- `.hover:m-auto` - Marge Alles automatisch beim Schweben
- `.last:m-0` - Margin All 0rem zuletzt
- `.m-5` - Rand Alle 5rem
- `.m-4.5` - Marge Alle 0rem
- `.m-4` - Rand Alle 4rem
- `.m-3.5` - Marge Alle 0rem
- `.m-3` - Rand Alle 3rem
- `.m-2.5` - Marge Alle 0rem
- `.m-2` - Rand Alle 2rem
- `.m-1.9` - Marge Alle 0rem
- `.m-1.8` - Marge Alle 0rem
- `.m-1.7` - Marge Alle 0rem
- `.m-1.6` - Marge Alle 0rem
- `.m-1.5` - Marge Alle 0rem
- `.m-1.4` - Marge Alle 0rem
- `.m-1.3` - Marge Alle 0rem
- `.m-1.2` - Marge Alle 0rem
- `.m-1.1` - Marge Alle 0rem
- `.m-1` - Marge Alle 1rem
- `.m-0.9` - Marge Alle 0rem
- `.m-0.8` - Marge Alle 0rem
- `.m-0.7` - Marge Alle 0rem
- `.m-0.6` - Marge Alle 0rem
- `.m-0.5` - Marge Alle 0rem
- `.m-0.4` - Marge Alle 0rem
- `.m-0.3` - Marge Alle 0rem
- `.m-0.2` - Marge Alle 0,2rem
- `.m-0.1` - Marge Alle 0,1rem
- `.m-0` - Marge Alle 0rem
- `.m-auto` - Rand Alles automatisch

#### Margin Bottom

- `.first:mb-0` - Rand unten 0rem zuerst anlegen
- `.hover:mb-100` - Rand unten 100rem beim Schweben
- `.hover:mb-75` - Rand unten 75rem beim Schweben
- `.hover:mb-50` - Rand unten 50rem beim Schweben
- `.hover:mb-25` - Rand unten 25rem beim Schweben
- `.hover:mb-5` - Rand unten 5rem beim Schweben
- `.hover:mb-4.5` - Rand unten 0rem beim Schweben
- `.hover:mb-4` - Rand unten 4rem beim Schweben
- `.hover:mb-3.5` - Rand unten 0rem beim Schweben
- `.hover:mb-3` - Rand unten 3rem beim Schweben
- `.hover:mb-2.5` - Rand unten 0rem beim Schweben
- `.hover:mb-2` - Rand unten 2rem beim Schweben
- `.hover:mb-1.9` - Rand unten 0rem beim Schweben
- `.hover:mb-1.8` - Rand unten 0rem beim Schweben
- `.hover:mb-1.7` - Rand unten 0rem beim Schweben
- `.hover:mb-1.6` - Rand unten 0rem beim Schweben
- `.hover:mb-1.5` - Rand unten 0rem beim Schweben
- `.hover:mb-1.4` - Rand unten 0rem beim Schweben
- `.hover:mb-1.3` - Rand unten 0rem beim Schweben
- `.hover:mb-1.2` - Rand unten 0rem beim Schweben
- `.hover:mb-1.1` - Rand unten 0rem beim Schweben
- `.hover:mb-1` - Rand unten 1rem beim Schweben
- `.hover:mb-0.9` - Rand unten 0rem beim Schweben
- `.hover:mb-0.8` - Rand unten 0rem beim Schweben
- `.hover:mb-0.7` - Rand unten 0rem beim Schweben
- `.hover:mb-0.6` - Rand unten 0rem beim Schweben
- `.hover:mb-0.5` - Rand unten 0rem beim Schweben
- `.hover:mb-0.4` - Rand unten 0rem beim Schweben
- `.hover:mb-0.3` - Rand unten 0rem beim Schweben
- `.hover:mb-0.2` - Rand unten 0,2rem beim Schweben
- `.hover:mb-0.1` - Rand unten 0,1rem beim Schweben
- `.hover:mb-0` - Rand unten 0rem beim Schweben
- `.hover:mb-auto` - Rand unten automatisch beim Schweben
- `.last:mb-0` - Rand unten 0rem zuletzt
- `.mb-100` - Rand unten 100rem
- `.mb-75` - Rand unten 75rem
- `.mb-50` - Rand unten 50rem
- `.mb-25` - Rand unten 25rem
- `.mb-5` - Rand unten 5rem
- `.mb-4.5` - Rand unten 0rem
- `.mb-4` - Rand unten 4rem
- `.mb-3.5` - Rand unten 0rem
- `.mb-3` - Rand unten 3rem
- `.mb-2.5` - Rand unten 0rem
- `.mb-2` - Rand unten 2rem
- `.mb-1.9` - Rand unten 0rem
- `.mb-1.8` - Rand unten 0rem
- `.mb-1.7` - Rand unten 0rem
- `.mb-1.6` - Rand unten 0rem
- `.mb-1.5` - Rand unten 0rem
- `.mb-1.4` - Rand unten 0rem
- `.mb-1.3` - Rand unten 0rem
- `.mb-1.2` - Rand unten 0rem
- `.mb-1.1` - Rand unten 0rem
- `.mb-1` - Rand unten 1rem
- `.mb-0.9` - Rand unten 0rem
- `.mb-0.8` - Rand unten 0rem
- `.mb-0.7` - Rand unten 0rem
- `.mb-0.6` - Rand unten 0rem
- `.mb-0.5` - Rand unten 0rem
- `.mb-0.4` - Rand unten 0rem
- `.mb-0.3` - Rand unten 0rem
- `.mb-0.2` - Rand unten 0,2rem
- `.mb-0.1` - Rand unten 0,1rem
- `.mb-0` - Rand unten 0rem
- `.mb-auto` - Rand unten automatisch

#### Margin End

- `.hover:me-2` - Randende 2rem beim Schweben
- `.hover:me-1.5` - Randende 1,5rem beim Schweben
- `.hover:me-1` - Randende 1rem beim Schweben
- `.hover:me-0.5` - Randende 0,5rem beim Schweben
- `.hover:me-0` - Randende 0rem beim Schweben
- `.me-2` - Rand Ende 2rem
- `.me-1.5` - Randende 1,5rem
- `.me-1` - Rand Ende 1rem
- `.me-0.5` - Randende 0,5rem
- `.me-0` - Rand Ende 0rem

#### Margin Left

- `.first:ml-0` - Rand links 0rem zuerst
- `.hover:ml-100` - Beim Hover beträgt der verbleibende Rand 100 rem
- `.hover:ml-75` - Beim Schweben beträgt der verbleibende Rand 75 rem
- `.hover:ml-50` - Beim Hover beträgt der verbleibende Rand 50 rem
- `.hover:ml-25` - Beim Hover beträgt der verbleibende Rand 25 rem
- `.hover:ml-5` - Rand links 5rem beim Schweben
- `.hover:ml-4.5` - Rand links 0rem beim Schweben
- `.hover:ml-4` - Rand links 4rem beim Schweben
- `.hover:ml-3.5` - Rand links 0rem beim Schweben
- `.hover:ml-3` - Rand links 3rem beim Schweben
- `.hover:ml-2.5` - Rand links 0rem beim Schweben
- `.hover:ml-2` - Rand links 2rem beim Schweben
- `.hover:ml-1.9` - Rand links 0rem beim Schweben
- `.hover:ml-1.8` - Rand links 0rem beim Schweben
- `.hover:ml-1.7` - Rand links 0rem beim Schweben
- `.hover:ml-1.6` - Rand links 0rem beim Schweben
- `.hover:ml-1.5` - Rand links 0rem beim Schweben
- `.hover:ml-1.4` - Rand links 0rem beim Schweben
- `.hover:ml-1.3` - Rand links 0rem beim Schweben
- `.hover:ml-1.2` - Rand links 0rem beim Schweben
- `.hover:ml-1.1` - Rand links 0rem beim Schweben
- `.hover:ml-1` - Rand links 1 Rem beim Schweben
- `.hover:ml-0.9` - Rand links 0rem beim Schweben
- `.hover:ml-0.8` - Rand links 0rem beim Schweben
- `.hover:ml-0.7` - Rand links 0rem beim Schweben
- `.hover:ml-0.6` - Rand links 0rem beim Schweben
- `.hover:ml-0.5` - Rand links 0rem beim Schweben
- `.hover:ml-0.4` - Rand links 0rem beim Schweben
- `.hover:ml-0.3` - Rand links 0rem beim Schweben
- `.hover:ml-0.2` - Beim Schweben beträgt der verbleibende Rand 0,2 Rem
- `.hover:ml-0.1` - Beim Schweben beträgt der verbleibende Rand 0,1 Rem
- `.hover:ml-0` - Rand links 0rem beim Schweben
- `.hover:ml-auto` - Beim Hover wird der linke Rand automatisch angezeigt
- `.last:ml-0` - Rand links 0rem am letzten
- `.ml-100` - Rand links 100rem
- `.ml-75` - Rand links 75rem
- `.ml-50` - Rand links 50rem
- `.ml-25` - Rand links 25rem
- `.ml-5` - Rand links 5rem
- `.ml-4.5` - Rand links 0rem
- `.ml-4` - Rand links 4rem
- `.ml-3.5` - Rand links 0rem
- `.ml-3` - Rand links 3rem
- `.ml-2.5` - Rand links 0rem
- `.ml-2` - Rand links 2rem
- `.ml-1.9` - Rand links 0rem
- `.ml-1.8` - Rand links 0rem
- `.ml-1.7` - Rand links 0rem
- `.ml-1.6` - Rand links 0rem
- `.ml-1.5` - Rand links 0rem
- `.ml-1.4` - Rand links 0rem
- `.ml-1.3` - Rand links 0rem
- `.ml-1.2` - Rand links 0rem
- `.ml-1.1` - Rand links 0rem
- `.ml-1` - Rand links 1rem
- `.ml-0.9` - Rand links 0rem
- `.ml-0.8` - Rand links 0rem
- `.ml-0.7` - Rand links 0rem
- `.ml-0.6` - Rand links 0rem
- `.ml-0.5` - Rand links 0rem
- `.ml-0.4` - Rand links 0rem
- `.ml-0.3` - Rand links 0rem
- `.ml-0.2` - Rand links 0,2rem
- `.ml-0.1` - Rand links 0,1rem
- `.ml-0` - Rand links 0rem
- `.ml-auto` - Rand links automatisch

#### Margin Right

- `.first:mr-0` - Rand rechts 0rem zuerst anbringen
- `.hover:mr-100` - Rand rechts 100rem beim Schweben
- `.hover:mr-75` - Rand rechts 75rem beim Schweben
- `.hover:mr-50` - Rand rechts 50rem beim Schweben
- `.hover:mr-25` - Rand rechts 25rem beim Schweben
- `.hover:mr-5` - Rand rechts 5rem beim Schweben
- `.hover:mr-4.5` - Rand rechts 0rem beim Schweben
- `.hover:mr-4` - Rand rechts 4rem beim Schweben
- `.hover:mr-3.5` - Rand rechts 0rem beim Schweben
- `.hover:mr-3` - Rand rechts 3rem beim Schweben
- `.hover:mr-2.5` - Rand rechts 0rem beim Schweben
- `.hover:mr-2` - Rand rechts 2rem beim Schweben
- `.hover:mr-1.9` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.8` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.7` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.6` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.5` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.4` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.3` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.2` - Rand rechts 0rem beim Schweben
- `.hover:mr-1.1` - Rand rechts 0rem beim Schweben
- `.hover:mr-1` - Rand rechts 1rem beim Schweben
- `.hover:mr-0.9` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.8` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.7` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.6` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.5` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.4` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.3` - Rand rechts 0rem beim Schweben
- `.hover:mr-0.2` - Rand rechts 0,2rem beim Schweben
- `.hover:mr-0.1` - Rand rechts 0,1rem beim Schweben
- `.hover:mr-0` - Rand rechts 0rem beim Schweben
- `.hover:mr-auto` - Rand rechts automatisch beim Schweben
- `.last:mr-0` - Rand rechts 0rem zuletzt
- `.mr-100` - Rand rechts 100rem
- `.mr-75` - Rand rechts 75rem
- `.mr-50` - Rand rechts 50rem
- `.mr-25` - Rand rechts 25rem
- `.mr-5` - Rand rechts 5rem
- `.mr-4.5` - Rand rechts 0rem
- `.mr-4` - Rand rechts 4rem
- `.mr-3.5` - Rand rechts 0rem
- `.mr-3` - Rand rechts 3rem
- `.mr-2.5` - Rand rechts 0rem
- `.mr-2` - Rand rechts 2rem
- `.mr-1.9` - Rand rechts 0rem
- `.mr-1.8` - Rand rechts 0rem
- `.mr-1.7` - Rand rechts 0rem
- `.mr-1.6` - Rand rechts 0rem
- `.mr-1.5` - Rand rechts 0rem
- `.mr-1.4` - Rand rechts 0rem
- `.mr-1.3` - Rand rechts 0rem
- `.mr-1.2` - Rand rechts 0rem
- `.mr-1.1` - Rand rechts 0rem
- `.mr-1` - Rand rechts 1rem
- `.mr-0.9` - Rand rechts 0rem
- `.mr-0.8` - Rand rechts 0rem
- `.mr-0.7` - Rand rechts 0rem
- `.mr-0.6` - Rand rechts 0rem
- `.mr-0.5` - Rand rechts 0rem
- `.mr-0.4` - Rand rechts 0rem
- `.mr-0.3` - Rand rechts 0rem
- `.mr-0.2` - Rand rechts 0,2rem
- `.mr-0.1` - Rand rechts 0,1rem
- `.mr-0` - Rand rechts 0rem
- `.mr-auto` - Rand rechts automatisch

#### Margin Start

- `.hover:ms-2` - Margin Start 2rem beim Hover
- `.hover:ms-1.5` - Margin Start 1,5rem beim Schweben
- `.hover:ms-1` - Margin Start 1rem beim Hover
- `.hover:ms-0.5` - Margin Start 0,5rem beim Schweben
- `.hover:ms-0` - Margin Start 0rem beim Hover
- `.ms-2` - Margin Start 2rem
- `.ms-1.5` - Marge Start 1,5rem
- `.ms-1` - Margin Start 1rem
- `.ms-0.5` - Randanfang 0,5rem
- `.ms-0` - Margin-Start 0rem

#### Margin Top

- `.first:mt-0` - Margin Top 0rem zuerst anlegen
- `.hover:mt-100` - Margin Top 100rem beim Schweben
- `.hover:mt-75` - Rand oben 75rem beim Schweben
- `.hover:mt-50` - Rand Top 50rem beim Schweben
- `.hover:mt-25` - Rand oben 25rem beim Schweben
- `.hover:mt-5` - Rand oben 5rem beim Schweben
- `.hover:mt-4.5` - Rand oben 0rem beim Schweben
- `.hover:mt-4` - Rand oben 4rem beim Schweben
- `.hover:mt-3.5` - Rand oben 0rem beim Schweben
- `.hover:mt-3` - Rand oben 3rem beim Schweben
- `.hover:mt-2.5` - Rand oben 0rem beim Schweben
- `.hover:mt-2` - Rand oben 2rem beim Schweben
- `.hover:mt-1.9` - Rand oben 0rem beim Schweben
- `.hover:mt-1.8` - Rand oben 0rem beim Schweben
- `.hover:mt-1.7` - Rand oben 0rem beim Schweben
- `.hover:mt-1.6` - Rand oben 0rem beim Schweben
- `.hover:mt-1.5` - Rand oben 0rem beim Schweben
- `.hover:mt-1.4` - Rand oben 0rem beim Schweben
- `.hover:mt-1.3` - Rand oben 0rem beim Schweben
- `.hover:mt-1.2` - Rand oben 0rem beim Schweben
- `.hover:mt-1.1` - Rand oben 0rem beim Schweben
- `.hover:mt-1` - Rand oben 1rem beim Schweben
- `.hover:mt-0.9` - Rand oben 0rem beim Schweben
- `.hover:mt-0.8` - Rand oben 0rem beim Schweben
- `.hover:mt-0.7` - Rand oben 0rem beim Schweben
- `.hover:mt-0.6` - Rand oben 0rem beim Schweben
- `.hover:mt-0.5` - Rand oben 0rem beim Schweben
- `.hover:mt-0.4` - Rand oben 0rem beim Schweben
- `.hover:mt-0.3` - Rand oben 0rem beim Schweben
- `.hover:mt-0.2` - Rand oben 0,2rem beim Schweben
- `.hover:mt-0.1` - Rand oben 0,1rem beim Schweben
- `.hover:mt-0` - Rand oben 0rem beim Schweben
- `.hover:mt-auto` - Rand Oben automatisch beim Schweben
- `.last:mt-0` - Rand oben 0rem zuletzt
- `.mt-100` - Rand oben 100rem
- `.mt-75` - Rand oben 75rem
- `.mt-50` - Rand oben 50rem
- `.mt-25` - Rand oben 25rem
- `.mt-5` - Rand oben 5rem
- `.mt-4.5` - Rand oben 0rem
- `.mt-4` - Rand oben 4rem
- `.mt-3.5` - Rand oben 0rem
- `.mt-3` - Rand oben 3rem
- `.mt-2.5` - Rand oben 0rem
- `.mt-2` - Rand oben 2rem
- `.mt-1.9` - Rand oben 0rem
- `.mt-1.8` - Rand oben 0rem
- `.mt-1.7` - Rand oben 0rem
- `.mt-1.6` - Rand oben 0rem
- `.mt-1.5` - Rand oben 0rem
- `.mt-1.4` - Rand oben 0rem
- `.mt-1.3` - Rand oben 0rem
- `.mt-1.2` - Rand oben 0rem
- `.mt-1.1` - Rand oben 0rem
- `.mt-1` - Rand oben 1
- `.mt-0.9` - Rand oben 0rem
- `.mt-0.8` - Rand oben 0rem
- `.mt-0.7` - Rand oben 0rem
- `.mt-0.6` - Rand oben 0rem
- `.mt-0.5` - Rand oben 0rem
- `.mt-0.4` - Rand oben 0rem
- `.mt-0.3` - Rand oben 0rem
- `.mt-0.2` - Rand oben 0,2rem
- `.mt-0.1` - Rand oben 0,1rem
- `.mt-0` - Rand oben 0rem
- `.mt-auto` - Marge Top-Auto

#### Margin X-Axis

- `.hover:mx-100` - Rand X-Achse 100rem beim Schweben
- `.hover:mx-75` - Rand X-Achse 75rem beim Schweben
- `.hover:mx-50` - Rand X-Achse 50rem beim Schweben
- `.hover:mx-25` - Rand X-Achse 25rem beim Schweben
- `.hover:mx-5` - Rand X-Achse 5rem beim Schweben
- `.hover:mx-4.5` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-4` - Rand X-Achse 4rem beim Schweben
- `.hover:mx-3.5` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-3` - Rand X-Achse 3rem beim Schweben
- `.hover:mx-2.5` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-2` - Rand X-Achse 2rem beim Schweben
- `.hover:mx-1.9` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.8` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.7` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.6` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.5` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.4` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.3` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.2` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1.1` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-1` - Rand X-Achse 1rem beim Schweben
- `.hover:mx-0.9` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.8` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.7` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.6` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.5` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.4` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.3` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-0.2` - Rand X-Achse 0,2rem beim Schweben
- `.hover:mx-0.1` - Rand X-Achse 0,1rem beim Schweben
- `.hover:mx-0` - Rand X-Achse 0rem beim Schweben
- `.hover:mx-auto` - Rand der X-Achse automatisch beim Schweben
- `.mx-100` - Rand X-Achse 100rem
- `.mx-75` - Rand X-Achse 75rem
- `.mx-50` - Rand X-Achse 50rem
- `.mx-25` - Rand X-Achse 25rem
- `.mx-5` - Rand X-Achse 5rem
- `.mx-4.5` - Rand X-Achse 0rem
- `.mx-4` - Rand X-Achse 4rem
- `.mx-3.5` - Rand X-Achse 0rem
- `.mx-3` - Rand X-Achse 3rem
- `.mx-2.5` - Rand X-Achse 0rem
- `.mx-2` - Rand X-Achse 2rem
- `.mx-1.9` - Rand X-Achse 0rem
- `.mx-1.8` - Rand X-Achse 0rem
- `.mx-1.7` - Rand X-Achse 0rem
- `.mx-1.6` - Rand X-Achse 0rem
- `.mx-1.5` - Rand X-Achse 0rem
- `.mx-1.4` - Rand X-Achse 0rem
- `.mx-1.3` - Rand X-Achse 0rem
- `.mx-1.2` - Rand X-Achse 0rem
- `.mx-1.1` - Rand X-Achse 0rem
- `.mx-1` - Rand X-Achse 1rem
- `.mx-0.9` - Rand X-Achse 0rem
- `.mx-0.8` - Rand X-Achse 0rem
- `.mx-0.7` - Rand X-Achse 0rem
- `.mx-0.6` - Rand X-Achse 0rem
- `.mx-0.5` - Rand X-Achse 0rem
- `.mx-0.4` - Rand X-Achse 0rem
- `.mx-0.3` - Rand X-Achse 0rem
- `.mx-0.2` - Rand X-Achse 0,2rem
- `.mx-0.1` - Rand X-Achse 0,1rem
- `.mx-0` - Rand X-Achse 0rem
- `.mx-auto` - Rand X-Achse automatisch

#### Margin Y-Axis

- `.hover:my-100` - Rand Y-Achse 100rem beim Schweben
- `.hover:my-75` - Rand Y-Achse 75rem beim Schweben
- `.hover:my-50` - Rand Y-Achse 50rem beim Schweben
- `.hover:my-25` - Rand Y-Achse 25rem beim Schweben
- `.hover:my-5` - Rand Y-Achse 5rem beim Schweben
- `.hover:my-4.5` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-4` - Rand Y-Achse 4rem beim Schweben
- `.hover:my-3.5` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-3` - Rand Y-Achse 3rem beim Schweben
- `.hover:my-2.5` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-2` - Rand Y-Achse 2rem beim Schweben
- `.hover:my-1.9` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.8` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.7` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.6` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.5` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.4` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.3` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.2` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1.1` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-1` - Rand Y-Achse 1rem beim Schweben
- `.hover:my-0.9` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.8` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.7` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.6` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.5` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.4` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.3` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-0.2` - Margin Y-Achse 0,2rem beim Schweben
- `.hover:my-0.1` - Margin Y-Achse 0,1rem beim Schweben
- `.hover:my-0` - Rand Y-Achse 0rem beim Schweben
- `.hover:my-auto` - Rand der Y-Achse automatisch beim Schweben
- `.my-100` - Rand Y-Achse 100rem
- `.my-75` - Rand Y-Achse 75rem
- `.my-50` - Rand Y-Achse 50rem
- `.my-25` - Rand Y-Achse 25rem
- `.my-5` - Rand Y-Achse 5rem
- `.my-4.5` - Rand Y-Achse 0rem
- `.my-4` - Rand Y-Achse 4rem
- `.my-3.5` - Rand Y-Achse 0rem
- `.my-3` - Rand Y-Achse 3rem
- `.my-2.5` - Rand Y-Achse 0rem
- `.my-2` - Rand Y-Achse 2rem
- `.my-1.9` - Rand Y-Achse 0rem
- `.my-1.8` - Rand Y-Achse 0rem
- `.my-1.7` - Rand Y-Achse 0rem
- `.my-1.6` - Rand Y-Achse 0rem
- `.my-1.5` - Rand Y-Achse 0rem
- `.my-1.4` - Rand Y-Achse 0rem
- `.my-1.3` - Rand Y-Achse 0rem
- `.my-1.2` - Rand Y-Achse 0rem
- `.my-1.1` - Rand Y-Achse 0rem
- `.my-1` - Rand Y-Achse 1rem
- `.my-0.9` - Rand Y-Achse 0rem
- `.my-0.8` - Rand Y-Achse 0rem
- `.my-0.7` - Rand Y-Achse 0rem
- `.my-0.6` - Rand Y-Achse 0rem
- `.my-0.5` - Rand Y-Achse 0rem
- `.my-0.4` - Rand Y-Achse 0rem
- `.my-0.3` - Rand Y-Achse 0rem
- `.my-0.2` - Rand Y-Achse 0,2rem
- `.my-0.1` - Rand Y-Achse 0,1rem
- `.my-0` - Rand Y-Achse 0rem
- `.my-auto` - Rand Y-Achse automatisch

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

- `.first:pb-0` - Polstern Sie zuerst den Boden 0rem auf
- `.hover:pb-100` - Polsterung unten 100rem im Schwebeflug
- `.hover:pb-75` - Polsterung unten 75rem im Schwebeflug
- `.hover:pb-50` - Polsterung unten 50rem im Schwebeflug
- `.hover:pb-25` - Polsterung unten 25rem im Schwebeflug
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
- `.pb-100` - Polsterung unten 100rem
- `.pb-75` - Polsterung unten 75rem
- `.pb-50` - Polsterung unten 50rem
- `.pb-25` - Polsterung unten 25rem
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

- `.first:pl-0` - Padding Left 0rem zuerst
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
- `.hover:pl-1` - Polsterung links 1 Rem beim Schweben
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

- `.first:pr-0` - Padding Right 0rem zuerst auf
- `.hover:pr-100` - Padding Right 100rem beim Schweben
- `.hover:pr-75` - Polsterung rechts 75rem im Schwebeflug
- `.hover:pr-50` - Polsterung rechts 50rem im Schwebeflug
- `.hover:pr-25` - Polsterung rechts 25rem im Schwebeflug
- `.hover:pr-5` - Padding Right 5rem im Schwebeflug
- `.hover:pr-4.5` - Polsterung nach rechts 0rem beim Schweben
- `.hover:pr-4` - Padding Right 4rem beim Schweben
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
- `.pr-100` - Polsterung rechts 100rem
- `.pr-75` - Polsterung rechts 75rem
- `.pr-50` - Polsterung rechts 50rem
- `.pr-25` - Polsterung rechts 25rem
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

- `.first:pt-0` - Zuerst Top 0rem aufpolstern
- `.hover:pt-100` - Polsterung Top 100rem im Schwebeflug
- `.hover:pt-75` - Polsterung oben 75rem im Schwebeflug
- `.hover:pt-50` - Polsterung Top 50rem im Schwebeflug
- `.hover:pt-25` - Polsterung oben 25rem im Schwebeflug
- `.hover:pt-5` - Polsterung Top 5rem im Schwebeflug
- `.hover:pt-4.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-4` - Polsterung Top 4rem im Schwebeflug
- `.hover:pt-3.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-3` - Polsterung Top 3rem beim Schweben
- `.hover:pt-2.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-2` - Polsterung oben 2rem im Schwebeflug
- `.hover:pt-1.9` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.8` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.7` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.6` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.4` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.3` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.2` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1.1` - Polsterung oben 0rem beim Schweben
- `.hover:pt-1` - Polsterung Top 1rem im Schwebeflug
- `.hover:pt-0.9` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.8` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.7` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.6` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.5` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.4` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.3` - Polsterung oben 0rem beim Schweben
- `.hover:pt-0.2` - Polsterung oben 0,2rem im Schwebeflug
- `.hover:pt-0.1` - Polsterung oben 0,1rem beim Schweben
- `.hover:pt-0` - Polsterung oben 0rem beim Schweben
- `.last:pt-0` - Polsterung oben 0rem am letzten
- `.pt-100` - Polsterung oben 100rem
- `.pt-75` - Polsterung oben 75rem
- `.pt-50` - Polsterung oben 50rem
- `.pt-25` - Polsterung oben 25rem
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

- `.hover:px-100` - Polsterung der X-Achse 100rem beim Schweben
- `.hover:px-75` - Polsterung der X-Achse 75rem beim Schweben
- `.hover:px-50` - Polsterung der X-Achse 50rem beim Schweben
- `.hover:px-25` - Polsterung der X-Achse 25rem beim Schweben
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
- `.px-100` - Polsterung X-Achse 100rem
- `.px-75` - Polsterung X-Achse 75rem
- `.px-50` - Polsterung X-Achse 50rem
- `.px-25` - Polsterung X-Achse 25rem
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

- `.hover:py-100` - Polsterung der Y-Achse 100rem beim Schweben
- `.hover:py-75` - Polsterung der Y-Achse 75rem beim Schweben
- `.hover:py-50` - Polsterung der Y-Achse 50rem beim Schweben
- `.hover:py-25` - Polsterung der Y-Achse 25rem beim Schweben
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
- `.py-100` - Polsterung Y-Achse 100rem
- `.py-75` - Polsterung Y-Achse 75rem
- `.py-50` - Polsterung Y-Achse 50rem
- `.py-25` - Polsterung Y-Achse 25rem
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

##### Width - Mobile (< 480px)

- `.hover:mobile:w-100` - Breite 100 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-95` - Breite 95 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-90` - Breite 90 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-85` - Breite 85 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-80` - Breite 80 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-75` - Breite 75 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-70` - Breite 70 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-65` - Breite 65 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-60` - Breite 60 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-55` - Breite 55 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-50` - Breite 50 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-45` - Breite 45 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-40` - Breite 40 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-35` - Breite 35 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-30` - Breite 30 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-25` - Breite 25 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-20` - Breite 20 % beim Hover auf Mobilgeräten
- `.hover:mobile:w-15` - Breite 15 % beim Hover auf Mobilgeräten
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

- `.hover:tablet:w-100` - Breite 100 % beim Schweben auf dem Tablet
- `.hover:tablet:w-95` - Breite 95 % beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:w-90` - Breite 90 % beim Schweben auf dem Tablet
- `.hover:tablet:w-85` - Breite 85 % beim Schweben auf dem Tablet
- `.hover:tablet:w-80` - Breite 80 % beim Schweben auf dem Tablet
- `.hover:tablet:w-75` - Breite 75 % beim Schweben auf dem Tablet
- `.hover:tablet:w-70` - Breite 70 % beim Schweben auf dem Tablet
- `.hover:tablet:w-65` - Breite 65 % beim Schweben auf dem Tablet
- `.hover:tablet:w-60` - Breite 60 % beim Schweben auf dem Tablet
- `.hover:tablet:w-55` - Breite 55 % beim Schweben auf dem Tablet
- `.hover:tablet:w-50` - Breite 50 % beim Schweben auf dem Tablet
- `.hover:tablet:w-45` - Breite 45 % beim Schweben auf dem Tablet
- `.hover:tablet:w-40` - Breite 40 % beim Schweben auf dem Tablet
- `.hover:tablet:w-35` - Breite 35 % beim Schweben auf dem Tablet
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

##### Width - Tv (> 1200px)

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

##### Width - Tablet Max (< 768px)

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

##### Width - Tablet Pc Max (< 992px)

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

##### Width - Pc Max (< 1200px)

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

- `.hover:w-vh-100` - Breite vh 100 % beim Schweben
- `.hover:w-vh-75` - Breite vh 75 % beim Schweben
- `.hover:w-vh-50` - Breite vh 50 % beim Schweben
- `.hover:w-vh-25` - Breite vh 25 % beim Schweben
- `.w-vh-100` - Breite vh 100 %
- `.w-vh-75` - Breite vh 75 %
- `.w-vh-50` - Breite vh 50 %
- `.w-vh-25` - Breite vh 25 %

#### Width vw

- `.hover:w-vw-100` - Breite vw 100 % beim Schweben
- `.hover:w-vw-75` - Breite vw 75 % im Schwebeflug
- `.hover:w-vw-50` - Breite vw 50 % beim Schweben
- `.hover:w-vw-25` - Breite vw 25 % beim Schweben
- `.w-vw-100` - Breite vw 100 %
- `.w-vw-75` - Breite vw 75 %
- `.w-vw-50` - Breite vw 50 %
- `.w-vw-25` - Breite vw 25 %

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
- `.hover:h-95` - Höhe 95 % im Schwebeflug
- `.hover:h-90` - Höhe 90 % im Schwebeflug
- `.hover:h-85` - Höhe 85 % im Schwebeflug
- `.hover:h-80` - Höhe 80 % im Schwebeflug
- `.hover:h-75` - Höhe 75 % im Schwebeflug
- `.hover:h-70` - Höhe 70 % im Schwebeflug
- `.hover:h-65` - Höhe 65 % im Schwebeflug
- `.hover:h-60` - Höhe 60 % im Schwebeflug
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

##### Height - Mobile (< 480px)

- `.hover:mobile:h-100` - Höhe 100 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-95` - Höhe 95 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-90` - Höhe 90 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-85` - Höhe 85 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-80` - Höhe 80 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-75` - Höhe 75 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-70` - Höhe 70 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-65` - Höhe 65 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-60` - Höhe 60 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-55` - Höhe 55 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-50` - Höhe 50 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-45` - Höhe 45 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-40` - Höhe 40 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-35` - Höhe 35 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-30` - Höhe 30 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-25` - Höhe 25 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-20` - Höhe 20 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-15` - Höhe 15 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-10` - Höhe 10 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-5` - Höhe 5 % beim Schweben auf dem Mobilgerät
- `.hover:mobile:h-auto` - Höhe automatisch % beim Bewegen des Mauszeigers auf dem Mobilgerät
- `.mobile:h-100` - Höhe 100 % auf Mobilgeräten
- `.mobile:h-95` - Höhe 95 % auf dem Handy
- `.mobile:h-90` - Höhe 90 % auf Mobilgeräten
- `.mobile:h-85` - Höhe 85 % auf Mobilgeräten
- `.mobile:h-80` - Höhe 80 % auf Mobilgeräten
- `.mobile:h-75` - Höhe 75 % auf Mobilgeräten
- `.mobile:h-70` - Höhe 70 % auf Mobilgeräten
- `.mobile:h-65` - Höhe 65 % auf Mobilgeräten
- `.mobile:h-60` - Höhe 60 % auf Mobilgeräten
- `.mobile:h-55` - Höhe 55 % auf Mobilgeräten
- `.mobile:h-50` - Höhe 50 % auf Mobilgeräten
- `.mobile:h-45` - Höhe 45 % auf Mobilgeräten
- `.mobile:h-40` - Höhe 40 % auf Mobilgeräten
- `.mobile:h-35` - Höhe 35 % auf Mobilgeräten
- `.mobile:h-30` - Höhe 30 % auf Mobilgeräten
- `.mobile:h-25` - Höhe 25 % auf Mobilgeräten
- `.mobile:h-20` - Höhe 20 % auf Mobilgeräten
- `.mobile:h-15` - Höhe 15 % auf Mobilgeräten
- `.mobile:h-10` - Höhe 10 % auf Mobilgeräten
- `.mobile:h-5` - Höhe 5 % auf Mobilgeräten
- `.mobile:h-auto` - Höhe automatisch % auf Mobilgeräten

##### Height - Tablet (480px - 768px)

- `.hover:tablet:h-100` - Höhe 100 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-95` - Höhe 95 % beim Schweben auf dem Tablet
- `.hover:tablet:h-90` - Höhe 90 % beim Schweben auf dem Tablet
- `.hover:tablet:h-85` - Höhe 85 % beim Schweben über das Tablet
- `.hover:tablet:h-80` - Höhe 80 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-75` - Höhe 75 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-70` - Höhe 70 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-65` - Höhe 65 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-60` - Höhe 60 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-55` - Höhe 55 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-50` - Höhe 50 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-45` - Höhe 45 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-40` - Höhe 40 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-35` - Höhe 35 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-30` - Höhe 30 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-25` - Höhe 25 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-20` - Höhe 20 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-15` - Höhe 15 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-10` - Höhe 10 % beim Bewegen des Mauszeigers über das Tablet
- `.hover:tablet:h-5` - Höhe 5 % beim Bewegen des Mauszeigers über das Tablet
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

##### Height - Tv (> 1200px)

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

##### Height - Tablet Max (< 768px)

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

##### Height - Tablet Pc Max (< 992px)

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

##### Height - Pc Max (< 1200px)

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

- `.h-vh-100` - Höhe vh 100 %
- `.h-vh-75` - Höhe vh 75 %
- `.h-vh-50` - Höhe vh 50 %
- `.h-vh-25` - Höhe vh 25 %
- `.hover:h-vh-100` - Höhe vh 100 % beim Schweben
- `.hover:h-vh-75` - Höhe vh 75 % im Schwebeflug
- `.hover:h-vh-50` - Höhe vh 50 % beim Schweben
- `.hover:h-vh-25` - Höhe vh 25 % beim Schweben

#### Height vw

- `.h-vw-100` - Höhe vw 100 %
- `.h-vw-75` - Höhe vw 75 %
- `.h-vw-50` - Höhe vw 50 %
- `.h-vw-25` - Höhe vw 25 %
- `.hover:h-vw-100` - Höhe vw 100 % im Schwebeflug
- `.hover:h-vw-75` - Höhe vw 75 % im Schwebeflug
- `.hover:h-vw-50` - Höhe vw 50 % im Schwebeflug
- `.hover:h-vw-25` - Höhe vw 25 % im Schwebeflug

## Positioning

### Static

- `.hover:static` - Statisch beim Schweben
- `.static` - Statisch

### Relative

- `.hover:relative` - Relativ im Schwebeflug
- `.relative` - Relativ

### Absolute

- `.absolute` - Absolut
- `.hover:absolute` - Absolut im Schwebeflug

### Fixed

- `.fixed` - Behoben
- `.hover:fixed` - Beim Schweben behoben

### Sticky

- `.hover:sticky` - Klebrig beim Schweben
- `.sticky` - Klebrig

### Top

- `.hover:top-100` - Top 100rem im Schwebeflug
- `.hover:top-75` - Top 75rem im Schwebeflug
- `.hover:top-50` - Top 50rem im Schwebeflug
- `.hover:top-25` - Top 25rem im Schwebeflug
- `.hover:top-5` - Top 5rem im Schwebeflug
- `.hover:top-4.5` - Top 0rem beim Schweben
- `.hover:top-4` - Top 4rem im Schwebeflug
- `.hover:top-3.5` - Top 0rem beim Schweben
- `.hover:top-3` - Top 3rem im Schwebeflug
- `.hover:top-2.5` - Top 0rem beim Schweben
- `.hover:top-2` - Top 2rem im Schwebeflug
- `.hover:top-1.9` - Top 0rem beim Schweben
- `.hover:top-1.8` - Top 0rem beim Schweben
- `.hover:top-1.7` - Top 0rem beim Schweben
- `.hover:top-1.6` - Top 0rem beim Schweben
- `.hover:top-1.5` - Top 0rem beim Schweben
- `.hover:top-1.4` - Top 0rem beim Schweben
- `.hover:top-1.3` - Top 0rem beim Schweben
- `.hover:top-1.2` - Top 0rem beim Schweben
- `.hover:top-1.1` - Top 0rem beim Schweben
- `.hover:top-1` - Top 1rem im Schwebeflug
- `.hover:top-0.9` - Top 0rem beim Schweben
- `.hover:top-0.8` - Top 0rem beim Schweben
- `.hover:top-0.7` - Top 0rem beim Schweben
- `.hover:top-0.6` - Top 0rem beim Schweben
- `.hover:top-0.5` - Top 0rem beim Schweben
- `.hover:top-0.4` - Top 0rem beim Schweben
- `.hover:top-0.3` - Top 0rem beim Schweben
- `.hover:top-0.2` - Top 0,2rem beim Schweben
- `.hover:top-0.1` - Top 0,1rem beim Schweben
- `.hover:top-0` - Top 0rem beim Schweben
- `.top-100` - Top 100rem
- `.top-75` - Top 75rem
- `.top-50` - Top 50rem
- `.top-25` - Top 25rem
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
- `.top-0.2` - Oben 0,2rem
- `.top-0.1` - Oben 0,1rem
- `.top-0` - Top 0rem

##### Negative Top

- `.-top-5` - Negativ Top 5rem
- `.-top-4.5` - Negativ Top 0rem
- `.-top-4` - Negativ Top 4rem
- `.-top-3.5` - Negativ Top 0rem
- `.-top-3` - Negativ Top 3rem
- `.-top-2.5` - Negativ Top 0rem
- `.-top-2` - Negativ Top 2rem
- `.-top-1.9` - Negativ Top 0rem
- `.-top-1.8` - Negativ Top 0rem
- `.-top-1.7` - Negativ Top 0rem
- `.-top-1.6` - Negativ Top 0rem
- `.-top-1.5` - Negativ Top 0rem
- `.-top-1.4` - Negativ Top 0rem
- `.-top-1.3` - Negativ Top 0rem
- `.-top-1.2` - Negativ Top 0rem
- `.-top-1.1` - Negativ Top 0rem
- `.-top-1` - Negativ Top 1rem
- `.-top-0.9` - Negativ Top 0rem
- `.-top-0.8` - Negativ Top 0rem
- `.-top-0.7` - Negativ Top 0rem
- `.-top-0.6` - Negativ Top 0rem
- `.-top-0.5` - Negativ Top 0rem
- `.-top-0.4` - Negativ Top 0rem
- `.-top-0.3` - Negativ oben 0,3rem
- `.-top-0.2` - Negativ Oben 0,2rem
- `.-top-0.1` - Negativ Oben 0,1rem
- `.hover:-top-5` - Negative Top 5rem beim Schweben
- `.hover:-top-4.5` - Negatives Top 0rem beim Hover
- `.hover:-top-4` - Negative Top 4rem beim Hover
- `.hover:-top-3.5` - Negatives Top 0rem beim Hover
- `.hover:-top-3` - Negative Top 3rem beim Schweben
- `.hover:-top-2.5` - Negatives Top 0rem beim Hover
- `.hover:-top-2` - Negativ Top 2rem beim Hover
- `.hover:-top-1.9` - Negatives Top 0rem beim Hover
- `.hover:-top-1.8` - Negatives Top 0rem beim Hover
- `.hover:-top-1.7` - Negatives Top 0rem beim Hover
- `.hover:-top-1.6` - Negatives Top 0rem beim Hover
- `.hover:-top-1.5` - Negatives Top 0rem beim Hover
- `.hover:-top-1.4` - Negatives Top 0rem beim Hover
- `.hover:-top-1.3` - Negatives Top 0rem beim Hover
- `.hover:-top-1.2` - Negatives Top 0rem beim Hover
- `.hover:-top-1.1` - Negatives Top 0rem beim Hover
- `.hover:-top-1` - Negativ Top 1rem beim Schweben
- `.hover:-top-0.9` - Negatives Top 0rem beim Hover
- `.hover:-top-0.8` - Negatives Top 0rem beim Hover
- `.hover:-top-0.7` - Negatives Top 0rem beim Hover
- `.hover:-top-0.6` - Negatives Top 0rem beim Hover
- `.hover:-top-0.5` - Negatives Top 0rem beim Hover
- `.hover:-top-0.4` - Negatives Top 0rem beim Hover
- `.hover:-top-0.3` - Negativ Top 0,3rem beim Schweben
- `.hover:-top-0.2` - Negativ Top 0,2rem beim Schweben
- `.hover:-top-0.1` - Negativ Top 0,1rem beim Schweben

### Right

- `.hover:right-100` - Rechts 100rem im Schwebeflug
- `.hover:right-75` - Rechts 75rem im Schwebeflug
- `.hover:right-50` - Rechts 50rem im Schwebeflug
- `.hover:right-25` - Rechts 25rem im Schwebeflug
- `.hover:right-5` - Rechts 5rem im Schwebeflug
- `.hover:right-4.5` - Rechts 0rem im Schwebeflug
- `.hover:right-4` - Rechts 4rem im Schwebeflug
- `.hover:right-3.5` - Rechts 0rem im Schwebeflug
- `.hover:right-3` - Rechts 3rem im Schwebeflug
- `.hover:right-2.5` - Rechts 0rem im Schwebeflug
- `.hover:right-2` - Rechts 2rem im Schwebeflug
- `.hover:right-1.9` - Rechts 0rem im Schwebeflug
- `.hover:right-1.8` - Rechts 0rem im Schwebeflug
- `.hover:right-1.7` - Rechts 0rem im Schwebeflug
- `.hover:right-1.6` - Rechts 0rem im Schwebeflug
- `.hover:right-1.5` - Rechts 0rem im Schwebeflug
- `.hover:right-1.4` - Rechts 0rem im Schwebeflug
- `.hover:right-1.3` - Rechts 0rem im Schwebeflug
- `.hover:right-1.2` - Rechts 0rem im Schwebeflug
- `.hover:right-1.1` - Rechts 0rem im Schwebeflug
- `.hover:right-1` - Rechts 1rem im Schwebeflug
- `.hover:right-0.9` - Rechts 0rem im Schwebeflug
- `.hover:right-0.8` - Rechts 0rem im Schwebeflug
- `.hover:right-0.7` - Rechts 0rem im Schwebeflug
- `.hover:right-0.6` - Rechts 0rem im Schwebeflug
- `.hover:right-0.5` - Rechts 0rem im Schwebeflug
- `.hover:right-0.4` - Rechts 0rem im Schwebeflug
- `.hover:right-0.3` - Rechts 0rem im Schwebeflug
- `.hover:right-0.2` - Rechts 0,2rem beim Schweben
- `.hover:right-0.1` - Rechts 0,1rem beim Schweben
- `.hover:right-0` - Rechts 0rem im Schwebeflug
- `.right-100` - Richtig 100rem
- `.right-75` - Rechts 75rem
- `.right-50` - Richtig 50rem
- `.right-25` - Rechts 25rem
- `.right-5` - Rechts 5rem
- `.right-4.5` - Richtig 0rem
- `.right-4` - Rechts 4rem
- `.right-3.5` - Richtig 0rem
- `.right-3` - Rechts 3rem
- `.right-2.5` - Richtig 0rem
- `.right-2` - Rechts 2rem
- `.right-1.9` - Richtig 0rem
- `.right-1.8` - Richtig 0rem
- `.right-1.7` - Richtig 0rem
- `.right-1.6` - Richtig 0rem
- `.right-1.5` - Richtig 0rem
- `.right-1.4` - Richtig 0rem
- `.right-1.3` - Richtig 0rem
- `.right-1.2` - Richtig 0rem
- `.right-1.1` - Richtig 0rem
- `.right-1` - Rechts 1rem
- `.right-0.9` - Richtig 0rem
- `.right-0.8` - Richtig 0rem
- `.right-0.7` - Richtig 0rem
- `.right-0.6` - Richtig 0rem
- `.right-0.5` - Richtig 0rem
- `.right-0.4` - Richtig 0rem
- `.right-0.3` - Richtig 0rem
- `.right-0.2` - Rechts 0,2rem
- `.right-0.1` - Rechts 0,1rem
- `.right-0` - Richtig 0rem

##### Negative Right

- `.-right-5` - Negativ rechts 5rem
- `.-right-4.5` - Negativ Rechts 0rem
- `.-right-4` - Negativ rechts 4rem
- `.-right-3.5` - Negativ Rechts 0rem
- `.-right-3` - Negativ rechts 3rem
- `.-right-2.5` - Negativ Rechts 0rem
- `.-right-2` - Negativ rechts 2rem
- `.-right-1.9` - Negativ Rechts 0rem
- `.-right-1.8` - Negativ Rechts 0rem
- `.-right-1.7` - Negativ Rechts 0rem
- `.-right-1.6` - Negativ Rechts 0rem
- `.-right-1.5` - Negativ Rechts 0rem
- `.-right-1.4` - Negativ Rechts 0rem
- `.-right-1.3` - Negativ Rechts 0rem
- `.-right-1.2` - Negativ Rechts 0rem
- `.-right-1.1` - Negativ Rechts 0rem
- `.-right-1` - Negativ rechts 1rem
- `.-right-0.9` - Negativ Rechts 0rem
- `.-right-0.8` - Negativ Rechts 0rem
- `.-right-0.7` - Negativ Rechts 0rem
- `.-right-0.6` - Negativ Rechts 0rem
- `.-right-0.5` - Negativ Rechts 0rem
- `.-right-0.4` - Negativ Rechts 0rem
- `.-right-0.3` - Negativ rechts 0,3rem
- `.-right-0.2` - Negativ rechts 0,2rem
- `.-right-0.1` - Negativ rechts 0,1rem
- `.hover:-right-5` - Negativ rechts 5rem beim Schweben
- `.hover:-right-4.5` - Negativ rechts 0rem beim Schweben
- `.hover:-right-4` - Negativ rechts 4rem beim Schweben
- `.hover:-right-3.5` - Negativ rechts 0rem beim Schweben
- `.hover:-right-3` - Negativ rechts 3rem beim Schweben
- `.hover:-right-2.5` - Negativ rechts 0rem beim Schweben
- `.hover:-right-2` - Negativ rechts 2rem beim Schweben
- `.hover:-right-1.9` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.8` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.7` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.6` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.5` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.4` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.3` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.2` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1.1` - Negativ rechts 0rem beim Schweben
- `.hover:-right-1` - Negativ rechts 1rem beim Schweben
- `.hover:-right-0.9` - Negativ rechts 0rem beim Schweben
- `.hover:-right-0.8` - Negativ rechts 0rem beim Schweben
- `.hover:-right-0.7` - Negativ rechts 0rem beim Schweben
- `.hover:-right-0.6` - Negativ rechts 0rem beim Schweben
- `.hover:-right-0.5` - Negativ rechts 0rem beim Schweben
- `.hover:-right-0.4` - Negativ rechts 0rem beim Schweben
- `.hover:-right-0.3` - Negativ rechts 0,3rem beim Schweben
- `.hover:-right-0.2` - Negativ rechts 0,2rem beim Schweben
- `.hover:-right-0.1` - Negativ rechts 0,1rem beim Schweben

### Bottom

- `.bottom-100` - Unten 100rem
- `.bottom-75` - Unten 75rem
- `.bottom-50` - Unten 50rem
- `.bottom-25` - Unten 25rem
- `.bottom-5` - Unten 5rem
- `.bottom-4.5` - Unten 0rem
- `.bottom-4` - Unten 4rem
- `.bottom-3.5` - Unten 0rem
- `.bottom-3` - Unten 3rem
- `.bottom-2.5` - Unten 0rem
- `.bottom-2` - Unten 2rem
- `.bottom-1.9` - Unten 0rem
- `.bottom-1.8` - Unten 0rem
- `.bottom-1.7` - Unten 0rem
- `.bottom-1.6` - Unten 0rem
- `.bottom-1.5` - Unten 0rem
- `.bottom-1.4` - Unten 0rem
- `.bottom-1.3` - Unten 0rem
- `.bottom-1.2` - Unten 0rem
- `.bottom-1.1` - Unten 0rem
- `.bottom-1` - Unten 1rem
- `.bottom-0.9` - Unten 0rem
- `.bottom-0.8` - Unten 0rem
- `.bottom-0.7` - Unten 0rem
- `.bottom-0.6` - Unten 0rem
- `.bottom-0.5` - Unten 0rem
- `.bottom-0.4` - Unten 0rem
- `.bottom-0.3` - Unten 0rem
- `.bottom-0.2` - Unten 0,2rem
- `.bottom-0.1` - Unten 0,1rem
- `.bottom-0` - Unten 0rem
- `.hover:bottom-100` - Untere 100rem im Schwebeflug
- `.hover:bottom-75` - Unten 75rem im Schwebeflug
- `.hover:bottom-50` - Unten 50rem im Schwebeflug
- `.hover:bottom-25` - Unten 25rem im Schwebeflug
- `.hover:bottom-5` - Unten 5rem im Schwebeflug
- `.hover:bottom-4.5` - Unten 0rem beim Schweben
- `.hover:bottom-4` - Unten 4rem im Schwebeflug
- `.hover:bottom-3.5` - Unten 0rem beim Schweben
- `.hover:bottom-3` - Unten 3rem im Schwebeflug
- `.hover:bottom-2.5` - Unten 0rem beim Schweben
- `.hover:bottom-2` - Unten 2rem im Schwebeflug
- `.hover:bottom-1.9` - Unten 0rem beim Schweben
- `.hover:bottom-1.8` - Unten 0rem beim Schweben
- `.hover:bottom-1.7` - Unten 0rem beim Schweben
- `.hover:bottom-1.6` - Unten 0rem beim Schweben
- `.hover:bottom-1.5` - Unten 0rem beim Schweben
- `.hover:bottom-1.4` - Unten 0rem beim Schweben
- `.hover:bottom-1.3` - Unten 0rem beim Schweben
- `.hover:bottom-1.2` - Unten 0rem beim Schweben
- `.hover:bottom-1.1` - Unten 0rem beim Schweben
- `.hover:bottom-1` - Unten 1rem im Schwebeflug
- `.hover:bottom-0.9` - Unten 0rem beim Schweben
- `.hover:bottom-0.8` - Unten 0rem beim Schweben
- `.hover:bottom-0.7` - Unten 0rem beim Schweben
- `.hover:bottom-0.6` - Unten 0rem beim Schweben
- `.hover:bottom-0.5` - Unten 0rem beim Schweben
- `.hover:bottom-0.4` - Unten 0rem beim Schweben
- `.hover:bottom-0.3` - Unten 0rem beim Schweben
- `.hover:bottom-0.2` - Unten 0,2rem beim Schweben
- `.hover:bottom-0.1` - Unten 0,1rem beim Schweben
- `.hover:bottom-0` - Unten 0rem beim Schweben

##### Negative Bottom

- `.-bottom-5` - Negativer Boden 5rem
- `.-bottom-4.5` - Negativer Boden 0rem
- `.-bottom-4` - Negativer Boden 4rem
- `.-bottom-3.5` - Negativer Boden 0rem
- `.-bottom-3` - Negativ unten 3rem
- `.-bottom-2.5` - Negativer Boden 0rem
- `.-bottom-2` - Negativer Boden 2rem
- `.-bottom-1.9` - Negativer Boden 0rem
- `.-bottom-1.8` - Negativer Boden 0rem
- `.-bottom-1.7` - Negativer Boden 0rem
- `.-bottom-1.6` - Negativer Boden 0rem
- `.-bottom-1.5` - Negativer Boden 0rem
- `.-bottom-1.4` - Negativer Boden 0rem
- `.-bottom-1.3` - Negativer Boden 0rem
- `.-bottom-1.2` - Negativer Boden 0rem
- `.-bottom-1.1` - Negativer Boden 0rem
- `.-bottom-1` - Negativer Boden 1rem
- `.-bottom-0.9` - Negativer Boden 0rem
- `.-bottom-0.8` - Negativer Boden 0rem
- `.-bottom-0.7` - Negativer Boden 0rem
- `.-bottom-0.6` - Negativer Boden 0rem
- `.-bottom-0.5` - Negativer Boden 0rem
- `.-bottom-0.4` - Negativer Boden 0rem
- `.-bottom-0.3` - Negativer Boden 0,3rem
- `.-bottom-0.2` - Negativer Boden 0,2rem
- `.-bottom-0.1` - Negativer Boden 0,1rem
- `.hover:-bottom-5` - Negativer Boden 5rem beim Schweben
- `.hover:-bottom-4.5` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-4` - Negativer Boden 4rem beim Schweben
- `.hover:-bottom-3.5` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-3` - Negativer Boden 3rem beim Schweben
- `.hover:-bottom-2.5` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-2` - Negativer Boden 2rem beim Schweben
- `.hover:-bottom-1.9` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.8` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.7` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.6` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.5` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.4` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.3` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.2` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1.1` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-1` - Negativer Boden 1rem beim Schweben
- `.hover:-bottom-0.9` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-0.8` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-0.7` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-0.6` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-0.5` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-0.4` - Negativer Boden 0rem beim Schweben
- `.hover:-bottom-0.3` - Negativer Boden 0,3rem beim Schweben
- `.hover:-bottom-0.2` - Negativer Boden 0,2rem beim Schweben
- `.hover:-bottom-0.1` - Negativer Boden 0,1rem beim Schweben

### Left

- `.hover:left-100` - 100 Minuten im Schwebeflug übrig geblieben
- `.hover:left-75` - 75 Minuten im Schwebeflug übrig
- `.hover:left-50` - 50 Minuten im Schwebeflug übrig
- `.hover:left-25` - 25 Minuten im Schwebeflug übrig
- `.hover:left-5` - 5 Minuten im Schwebeflug übrig
- `.hover:left-4.5` - 0rem im Schwebezustand verlassen
- `.hover:left-4` - 4 Minuten im Schwebeflug übrig
- `.hover:left-3.5` - 0rem im Schwebezustand verlassen
- `.hover:left-3` - 3 Minuten im Schwebeflug übrig
- `.hover:left-2.5` - 0rem im Schwebezustand verlassen
- `.hover:left-2` - 2 Minuten im Schwebeflug übrig
- `.hover:left-1.9` - 0rem im Schwebezustand verlassen
- `.hover:left-1.8` - 0rem im Schwebezustand verlassen
- `.hover:left-1.7` - 0rem im Schwebezustand verlassen
- `.hover:left-1.6` - 0rem im Schwebezustand verlassen
- `.hover:left-1.5` - 0rem im Schwebezustand verlassen
- `.hover:left-1.4` - 0rem im Schwebezustand verlassen
- `.hover:left-1.3` - 0rem im Schwebezustand verlassen
- `.hover:left-1.2` - 0rem im Schwebezustand verlassen
- `.hover:left-1.1` - 0rem im Schwebezustand verlassen
- `.hover:left-1` - 1 Rem im Schwebezustand gelassen
- `.hover:left-0.9` - 0rem im Schwebezustand verlassen
- `.hover:left-0.8` - 0rem im Schwebezustand verlassen
- `.hover:left-0.7` - 0rem im Schwebezustand verlassen
- `.hover:left-0.6` - 0rem im Schwebezustand verlassen
- `.hover:left-0.5` - 0rem im Schwebezustand verlassen
- `.hover:left-0.4` - 0rem im Schwebezustand verlassen
- `.hover:left-0.3` - 0rem im Schwebezustand verlassen
- `.hover:left-0.2` - 0,2 Rem beim Schweben übrig
- `.hover:left-0.1` - Beim Schweben 0,1 Rem übrig
- `.hover:left-0` - 0rem im Schwebezustand verlassen
- `.left-100` - 100rem übrig
- `.left-75` - Links 75rem
- `.left-50` - Links 50rem
- `.left-25` - Links 25rem
- `.left-5` - Links 5rem
- `.left-4.5` - Links 0rem
- `.left-4` - Links 4rem
- `.left-3.5` - Links 0rem
- `.left-3` - Links 3rem
- `.left-2.5` - Links 0rem
- `.left-2` - Links 2rem
- `.left-1.9` - Links 0rem
- `.left-1.8` - Links 0rem
- `.left-1.7` - Links 0rem
- `.left-1.6` - Links 0rem
- `.left-1.5` - Links 0rem
- `.left-1.4` - Links 0rem
- `.left-1.3` - Links 0rem
- `.left-1.2` - Links 0rem
- `.left-1.1` - Links 0rem
- `.left-1` - Links 1rem
- `.left-0.9` - Links 0rem
- `.left-0.8` - Links 0rem
- `.left-0.7` - Links 0rem
- `.left-0.6` - Links 0rem
- `.left-0.5` - Links 0rem
- `.left-0.4` - Links 0rem
- `.left-0.3` - Links 0rem
- `.left-0.2` - Links 0,2rem
- `.left-0.1` - Links 0,1rem
- `.left-0` - Links 0rem

##### Negative Left

- `.-left-5` - Negativ links 5rem
- `.-left-4.5` - Negativ links 0rem
- `.-left-4` - Negativ links 4rem
- `.-left-3.5` - Negativ links 0rem
- `.-left-3` - Negativ links 3rem
- `.-left-2.5` - Negativ links 0rem
- `.-left-2` - Negativ links 2rem
- `.-left-1.9` - Negativ links 0rem
- `.-left-1.8` - Negativ links 0rem
- `.-left-1.7` - Negativ links 0rem
- `.-left-1.6` - Negativ links 0rem
- `.-left-1.5` - Negativ links 0rem
- `.-left-1.4` - Negativ links 0rem
- `.-left-1.3` - Negativ links 0rem
- `.-left-1.2` - Negativ links 0rem
- `.-left-1.1` - Negativ links 0rem
- `.-left-1` - Negative Linke 1rem
- `.-left-0.9` - Negativ links 0rem
- `.-left-0.8` - Negativ links 0rem
- `.-left-0.7` - Negativ links 0rem
- `.-left-0.6` - Negativ links 0rem
- `.-left-0.5` - Negativ links 0rem
- `.-left-0.4` - Negativ links 0rem
- `.-left-0.3` - Negativ links 0,3rem
- `.-left-0.2` - Negativ links 0,2rem
- `.-left-0.1` - Negativ links 0,1rem
- `.hover:-left-5` - Negativ links 5rem beim Schweben
- `.hover:-left-4.5` - Negativ links 0rem beim Schweben
- `.hover:-left-4` - Negativ links 4rem beim Schweben
- `.hover:-left-3.5` - Negativ links 0rem beim Schweben
- `.hover:-left-3` - Negativ links 3rem beim Schweben
- `.hover:-left-2.5` - Negativ links 0rem beim Schweben
- `.hover:-left-2` - Negativ links 2rem beim Schweben
- `.hover:-left-1.9` - Negativ links 0rem beim Schweben
- `.hover:-left-1.8` - Negativ links 0rem beim Schweben
- `.hover:-left-1.7` - Negativ links 0rem beim Schweben
- `.hover:-left-1.6` - Negativ links 0rem beim Schweben
- `.hover:-left-1.5` - Negativ links 0rem beim Schweben
- `.hover:-left-1.4` - Negativ links 0rem beim Schweben
- `.hover:-left-1.3` - Negativ links 0rem beim Schweben
- `.hover:-left-1.2` - Negativ links 0rem beim Schweben
- `.hover:-left-1.1` - Negativ links 0rem beim Schweben
- `.hover:-left-1` - Negativ links 1rem beim Schweben
- `.hover:-left-0.9` - Negativ links 0rem beim Schweben
- `.hover:-left-0.8` - Negativ links 0rem beim Schweben
- `.hover:-left-0.7` - Negativ links 0rem beim Schweben
- `.hover:-left-0.6` - Negativ links 0rem beim Schweben
- `.hover:-left-0.5` - Negativ links 0rem beim Schweben
- `.hover:-left-0.4` - Negativ links 0rem beim Schweben
- `.hover:-left-0.3` - Negativ links 0,3rem beim Schweben
- `.hover:-left-0.2` - Negativ links 0,2rem beim Schweben
- `.hover:-left-0.1` - Negativ links 0,1rem beim Schweben

### Z-Index

- `.hover:z-5` - Z-Index 5 beim Schweben
- `.hover:z-4` - Z-Index 4 beim Schweben
- `.hover:z-3` - Z-Index 3 beim Schweben
- `.hover:z-2` - Z-Index 2 beim Schweben
- `.hover:z-1` - Z-Index 1 beim Schweben
- `.hover:z-0` - Z-Index 0 beim Schweben
- `.hover:z-auto` - Z-Index automatisch beim Schweben
- `.z-5` - Z-Index 5
- `.z-4` - Z-Index 4
- `.z-3` - Z-Index 3
- `.z-2` - Z-Index 2
- `.z-1` - Z-Index 1
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

- `.hover:line-height-5` - Linienhöhe 5rem beim Schweben
- `.hover:line-height-4` - Linienhöhe 4rem beim Schweben
- `.hover:line-height-3` - Linienhöhe 3rem beim Schweben
- `.hover:line-height-2` - Linienhöhe 2rem beim Schweben
- `.hover:line-height-1` - Linienhöhe 1rem beim Schweben
- `.line-height-5` - Strichhöhe 5rem
- `.line-height-4` - Strichhöhe 4rem
- `.line-height-3` - Strichhöhe 3rem
- `.line-height-2` - Strichhöhe 2rem
- `.line-height-1` - Strichhöhe 1rem

### Text

- `.hover:text-capitalize` - Text wird beim Schweben groß geschrieben
- `.hover:text-center` - Textmitte beim Schweben
- `.hover:text-end` - Der Text endet beim Hover
- `.hover:text-justify` - Text beim Schweben ausrichten
- `.hover:text-left` - Der Text bleibt beim Schweben übrig
- `.hover:text-line-none` - Beim Hover gibt es keine Textzeile
- `.hover:text-line-overline` - Textzeile überstreicht beim Hover
- `.hover:text-line-through` - Durchgestrichener Text beim Hover
- `.hover:text-line-underline` - Text zeilenweise unterstreichen, wenn Sie den Mauszeiger darüber bewegen
- `.hover:text-lowercase` - Text beim Schweben in Kleinbuchstaben schreiben
- `.hover:text-right` - Direkt beim Hover Text schreiben
- `.hover:text-start` - Text beginnt beim Hover
- `.hover:text-transparent` - Text beim Schweben transparent
- `.hover:text-uppercase` - Text beim Hover in Großbuchstaben schreiben
- `.text-break-all` - Text-Break-All
- `.text-break-keep-all` - Text Break-Keep-All
- `.text-break-normal` - Textunterbrechung normal
- `.text-break-word` - Textumbruchwort
- `.text-capitalize` - Text groß schreiben
- `.text-center` - Textmitte
- `.text-end` - Textende
- `.text-justify` - Text rechtfertigen
- `.text-left` - Text übrig
- `.text-line-none` - Textzeile – keine
- `.text-line-overline` - Text zeilenweise überstreichen
- `.text-line-through` - Durchgestrichener Text
- `.text-line-underline` - Text zeilenweise unterstreichen
- `.text-lowercase` - Text in Kleinbuchstaben
- `.text-overflow-clip` - Textüberlauf-Clip
- `.text-overflow-ellipsis` - Textüberlauf-Auslassungspunkte
- `.text-right` - Text richtig
- `.text-start` - Textanfang
- `.text-transparent` - Text transparent
- `.text-uppercase` - Text in Großbuchstaben

##### Text - Mobile (< 480px)

- `.hover:mobile:text-center` - Textmitte beim Hover auf dem Mobilgerät
- `.hover:mobile:text-end` - Der Text endet, wenn man auf dem Handy mit der Maus darüber fährt
- `.hover:mobile:text-justify` - Text beim Hover auf Mobilgeräten ausrichten
- `.hover:mobile:text-left` - Beim Bewegen des Mauszeigers auf dem Mobilgerät bleibt Text übrig
- `.hover:mobile:text-right` - Direkt beim Hover auf dem Handy Text schreiben
- `.hover:mobile:text-start` - Der Text beginnt beim Hover auf dem Mobilgerät
- `.mobile:text-center` - Textcenter auf dem Handy
- `.mobile:text-end` - Textende auf dem Handy
- `.mobile:text-justify` - Textausrichtung auf Mobilgeräten
- `.mobile:text-left` - Text auf dem Handy hinterlassen
- `.mobile:text-right` - Text direkt auf dem Handy
- `.mobile:text-start` - Textstart auf dem Handy

##### Text - Tablet (480px - 768px)

- `.hover:tablet:text-center` - Textmitte beim Schweben auf dem Tablet
- `.hover:tablet:text-end` - Der Text endet, wenn man mit der Maus über das Tablet fährt
- `.hover:tablet:text-justify` - Text ausrichten, wenn man den Mauszeiger auf dem Tablet hält
- `.hover:tablet:text-left` - Der Text bleibt beim Schweben auf dem Tablet übrig
- `.hover:tablet:text-right` - Text direkt beim Bewegen des Mauszeigers auf dem Tablet
- `.hover:tablet:text-start` - Der Text beginnt, wenn Sie mit der Maus über das Tablet fahren
- `.tablet:text-center` - Textzentrum auf dem Tablet
- `.tablet:text-end` - Text endet auf dem Tablet
- `.tablet:text-justify` - Text auf dem Tablet ausrichten
- `.tablet:text-left` - Text auf dem Tablet hinterlassen
- `.tablet:text-right` - Text direkt auf dem Tablet
- `.tablet:text-start` - Text beginnt auf dem Tablet

##### Text - Tablet Pc (768px - 992px)

- `.hover:tablet-pc:text-center` - Textmitte beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:text-end` - Der Text endet beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:text-justify` - Text ausrichten, wenn Sie den Mauszeiger auf dem Tablet-PC halten
- `.hover:tablet-pc:text-left` - Text bleibt beim Schweben auf dem Tablet-PC übrig
- `.hover:tablet-pc:text-right` - Text direkt beim Hover auf dem Tablet-PC
- `.hover:tablet-pc:text-start` - Text beginnt beim Hover auf dem Tablet-PC
- `.tablet-pc:text-center` - Textcenter auf dem Tablet-PC
- `.tablet-pc:text-end` - Textende auf Tablet-PC
- `.tablet-pc:text-justify` - Text auf dem Tablet-PC ausrichten
- `.tablet-pc:text-left` - Auf dem Tablet-PC hinterlassener Text
- `.tablet-pc:text-right` - Text direkt auf dem Tablet-PC
- `.tablet-pc:text-start` - Textanfang auf Tablet-PC

##### Text - Pc (992px - 1200px)

- `.hover:pc:text-center` - Text zentriert beim Hover auf dem PC
- `.hover:pc:text-end` - Textende beim Hover auf dem PC
- `.hover:pc:text-justify` - Text ausrichten, wenn man den Mauszeiger auf dem PC hält
- `.hover:pc:text-left` - Der Text bleibt beim Hover auf dem PC übrig
- `.hover:pc:text-right` - Text direkt beim Hover auf dem PC
- `.hover:pc:text-start` - Text beginnt beim Hover auf dem PC
- `.pc:text-center` - Textmitte auf dem PC
- `.pc:text-end` - Textende auf dem PC
- `.pc:text-justify` - Text auf dem PC ausrichten
- `.pc:text-left` - Text bleibt auf dem PC
- `.pc:text-right` - Text direkt auf dem PC
- `.pc:text-start` - Textanfang am PC

##### Text - Tv (> 1200px)

- `.hover:tv:text-center` - Textmitte beim Schweben auf dem Fernseher
- `.hover:tv:text-end` - Der Text endet, wenn man mit der Maus über den Fernseher fährt
- `.hover:tv:text-justify` - Text ausrichten, wenn man den Mauszeiger im Fernsehen hält
- `.hover:tv:text-left` - Der Text bleibt beim Schweben im Fernsehen
- `.hover:tv:text-right` - Text direkt beim Hover auf dem Fernseher
- `.hover:tv:text-start` - Der Text beginnt beim Schweben im Fernsehen
- `.tv:text-center` - Textcenter im Fernsehen
- `.tv:text-end` - Text endet im Fernsehen
- `.tv:text-justify` - Textausrichtung im Fernsehen
- `.tv:text-left` - Text im Fernsehen hinterlassen
- `.tv:text-right` - Text direkt im Fernsehen
- `.tv:text-start` - Textanfang im Fernsehen

##### Text - Tablet Max (< 768px)

- `.hover:tablet-max:text-center` - Textmitte beim Hover auf dem Tablet max
- `.hover:tablet-max:text-end` - Textende bei Hover auf dem Tablet max
- `.hover:tablet-max:text-justify` - Text beim Hover auf dem Tablet ausrichten, max
- `.hover:tablet-max:text-left` - Verbleibender Text beim Hovern auf dem Tablet max
- `.hover:tablet-max:text-right` - Text direkt beim Hover auf dem Tablet max
- `.hover:tablet-max:text-start` - Textbeginn beim Hover auf dem Tablet max
- `.tablet-max:text-center` - Textmitte auf dem Tablet max
- `.tablet-max:text-end` - Textende auf dem Tablet max
- `.tablet-max:text-justify` - Text im Blocksatz auf dem Tablet max
- `.tablet-max:text-left` - Auf dem Tablet verbleibender Text max
- `.tablet-max:text-right` - Text direkt auf dem Tablet max
- `.tablet-max:text-start` - Textanfang auf Tablet max

##### Text - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:text-center` - Textmitte beim Hover auf Tablet-PC max
- `.hover:tablet-pc-max:text-end` - Textende bei Hover auf Tablet-PC max
- `.hover:tablet-pc-max:text-justify` - Text ausrichten bei Hover auf Tablet-PC max
- `.hover:tablet-pc-max:text-left` - Verbleibender Text beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:text-right` - Text direkt beim Hover auf dem Tablet-PC max
- `.hover:tablet-pc-max:text-start` - Textbeginn beim Hover auf Tablet-PC max
- `.tablet-pc-max:text-center` - Textmitte auf Tablet-PC max
- `.tablet-pc-max:text-end` - Textende auf Tablet-PC max
- `.tablet-pc-max:text-justify` - Textausrichtung auf Tablet-PC max
- `.tablet-pc-max:text-left` - Verbleibender Text auf dem Tablet-PC max
- `.tablet-pc-max:text-right` - Text direkt auf dem Tablet-PC max
- `.tablet-pc-max:text-start` - Textanfang auf Tablet-PC max

##### Text - Pc Max (< 1200px)

- `.hover:pc-max:text-center` - Textmitte beim Hover auf dem PC max
- `.hover:pc-max:text-end` - Textende bei Hover auf PC max
- `.hover:pc-max:text-justify` - Text beim Hover auf dem PC ausrichten, max
- `.hover:pc-max:text-left` - Verbleibender Text beim Hover auf dem PC max
- `.hover:pc-max:text-right` - Text direkt beim Hover auf dem PC max
- `.hover:pc-max:text-start` - Textbeginn beim Hover auf PC max
- `.pc-max:text-center` - Textmitte am PC max
- `.pc-max:text-end` - Textende am PC max
- `.pc-max:text-justify` - Textausrichtung am PC max
- `.pc-max:text-left` - Verbleibender Text auf dem PC max
- `.pc-max:text-right` - Text direkt am PC max
- `.pc-max:text-start` - Textanfang auf PC max

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

- `.bg-blur-5` - Hintergrundunschärfe 5rem
- `.bg-blur-4` - Hintergrundunschärfe 4rem
- `.bg-blur-3` - Hintergrundunschärfe 3rem
- `.bg-blur-2` - Hintergrundunschärfe 2rem
- `.bg-blur-1` - Hintergrundunschärfe 1rem
- `.bg-blur-0` - Hintergrundunschärfe 0rem
- `.hover:bg-blur-5` - Hintergrundunschärfe 5rem beim Schweben
- `.hover:bg-blur-4` - Hintergrundunschärfe 4rem beim Schweben
- `.hover:bg-blur-3` - Hintergrundunschärfe 3rem beim Schweben
- `.hover:bg-blur-2` - Hintergrundunschärfe 2rem beim Schweben
- `.hover:bg-blur-1` - Hintergrundunschärfe 1 Rem beim Schweben
- `.hover:bg-blur-0` - Hintergrundunschärfe 0rem beim Schweben

## Borders

### Border

#### Border All

- `.border-2` - Rand Alle 2rem
- `.border-1.5` - Rand Alle 0rem
- `.border-1` - Rand Alle 1rem
- `.border-0.9` - Rand Alle 0rem
- `.border-0.8` - Rand Alle 0rem
- `.border-0.7` - Rand Alle 0rem
- `.border-0.6` - Rand Alle 0rem
- `.border-0.5` - Rand Alle 0rem
- `.border-0.4` - Rand Alle 0,4rem
- `.border-0.3` - Rand Alle 0rem
- `.border-0.2` - Rand Alle 0,2rem
- `.border-0.1` - Rand Alle 0,1rem
- `.border-0` - Rand Alle 0rem
- `.hover:border-2` - Grenze Alle 2rem beim Schweben
- `.hover:border-1.5` - Rand Alle 0rem beim Schweben
- `.hover:border-1` - Grenze Alle 1rem beim Schweben
- `.hover:border-0.9` - Rand Alle 0rem beim Schweben
- `.hover:border-0.8` - Rand Alle 0rem beim Schweben
- `.hover:border-0.7` - Rand Alle 0rem beim Schweben
- `.hover:border-0.6` - Rand Alle 0rem beim Schweben
- `.hover:border-0.5` - Rand Alle 0rem beim Schweben
- `.hover:border-0.4` - Rand Alle 0rem beim Schweben
- `.hover:border-0.3` - Rand Alle 0rem beim Schweben
- `.hover:border-0.2` - Rand Alle 0,2rem beim Schweben
- `.hover:border-0.1` - Rand Alle 0,1rem beim Schweben
- `.hover:border-0` - Rand Alle 0rem beim Schweben

#### Border Bottom

- `.border-b-2` - Rand unten 2rem
- `.border-b-1.5` - Rand unten 0rem
- `.border-b-1` - Rand unten 1rem
- `.border-b-0.9` - Rand unten 0rem
- `.border-b-0.8` - Rand unten 0rem
- `.border-b-0.7` - Rand unten 0rem
- `.border-b-0.6` - Rand unten 0rem
- `.border-b-0.5` - Rand unten 0,5rem
- `.border-b-0.4` - Rand unten 0rem
- `.border-b-0.3` - Rand unten 0rem
- `.border-b-0.2` - Rand unten 0,2rem
- `.border-b-0.1` - Rand unten 0,1rem
- `.border-b-0` - Rand unten 0rem
- `.hover:border-b-2` - Rand unten 2rem beim Schweben
- `.hover:border-b-1.5` - Rand unten 0rem beim Schweben
- `.hover:border-b-1` - Rand unten 1rem beim Schweben
- `.hover:border-b-0.9` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.8` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.7` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.6` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.5` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.4` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.3` - Rand unten 0rem beim Schweben
- `.hover:border-b-0.2` - Rand unten 0,2rem beim Schweben
- `.hover:border-b-0.1` - Rand unten 0,1rem beim Schweben
- `.hover:border-b-0` - Rand unten 0rem beim Schweben

#### Border Left

- `.border-l-2` - Rand links 2rem
- `.border-l-1.5` - Rand links 0rem
- `.border-l-1` - Rand links 1rem
- `.border-l-0.9` - Rand links 0rem
- `.border-l-0.8` - Rand links 0rem
- `.border-l-0.7` - Rand links 0rem
- `.border-l-0.6` - Rand links 0rem
- `.border-l-0.5` - Rand links 0rem
- `.border-l-0.4` - Rand links 0rem
- `.border-l-0.3` - Rand links 0rem
- `.border-l-0.2` - Rand links 0,2rem
- `.border-l-0.1` - Rand links 0,1rem
- `.border-l-0` - Rand links 0rem
- `.hover:border-l-2` - Rand links 2rem beim Schweben
- `.hover:border-l-1.5` - Rand links 0rem beim Schweben
- `.hover:border-l-1` - Rand links 1rem beim Schweben
- `.hover:border-l-0.9` - Rand links 0rem beim Schweben
- `.hover:border-l-0.8` - Rand links 0rem beim Schweben
- `.hover:border-l-0.7` - Rand links 0rem beim Schweben
- `.hover:border-l-0.6` - Rand links 0rem beim Schweben
- `.hover:border-l-0.5` - Rand links 0rem beim Schweben
- `.hover:border-l-0.4` - Rand links 0rem beim Schweben
- `.hover:border-l-0.3` - Rand links 0rem beim Schweben
- `.hover:border-l-0.2` - Rand links 0,2rem beim Schweben
- `.hover:border-l-0.1` - Rand links 0,1rem beim Schweben
- `.hover:border-l-0` - Rand links 0rem beim Schweben

#### Border Right

- `.border-r-2` - Rand rechts 2rem
- `.border-r-1.5` - Rand rechts 0rem
- `.border-r-1` - Rand rechts 1rem
- `.border-r-0.9` - Rand rechts 0rem
- `.border-r-0.8` - Rand rechts 0rem
- `.border-r-0.7` - Rand rechts 0rem
- `.border-r-0.6` - Rand rechts 0rem
- `.border-r-0.5` - Rand rechts 0rem
- `.border-r-0.4` - Rand rechts 0rem
- `.border-r-0.3` - Rand rechts 0rem
- `.border-r-0.2` - Rand rechts 0,2rem
- `.border-r-0.1` - Rand rechts 0,1rem
- `.border-r-0` - Rand rechts 0rem
- `.hover:border-r-2` - Rand rechts 2rem beim Schweben
- `.hover:border-r-1.5` - Rand rechts 0rem beim Schweben
- `.hover:border-r-1` - Rand rechts 1rem beim Schweben
- `.hover:border-r-0.9` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.8` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.7` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.6` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.5` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.4` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.3` - Rand rechts 0rem beim Schweben
- `.hover:border-r-0.2` - Rand rechts 0,2rem beim Schweben
- `.hover:border-r-0.1` - Rand rechts 0,1rem beim Schweben
- `.hover:border-r-0` - Rand rechts 0rem beim Schweben

#### Border Top

- `.border-t-2` - Rand oben 2rem
- `.border-t-1.5` - Rand Oben 0rem
- `.border-t-1` - Rand oben 1rem
- `.border-t-0.9` - Rand Oben 0rem
- `.border-t-0.8` - Rand Oben 0rem
- `.border-t-0.7` - Rand Oben 0rem
- `.border-t-0.6` - Rand Oben 0rem
- `.border-t-0.5` - Rand Oben 0rem
- `.border-t-0.4` - Rand Oben 0rem
- `.border-t-0.3` - Rand Oben 0rem
- `.border-t-0.2` - Rand oben 0,2rem
- `.border-t-0.1` - Rand oben 0,1rem
- `.border-t-0` - Rand Oben 0rem
- `.hover:border-t-2` - Border Top 2rem beim Schweben
- `.hover:border-t-1.5` - Rand oben 0rem beim Hover
- `.hover:border-t-1` - Border Top 1rem beim Schweben
- `.hover:border-t-0.9` - Rand oben 0rem beim Hover
- `.hover:border-t-0.8` - Rand oben 0rem beim Hover
- `.hover:border-t-0.7` - Rand oben 0rem beim Hover
- `.hover:border-t-0.6` - Rand oben 0rem beim Hover
- `.hover:border-t-0.5` - Rand oben 0rem beim Hover
- `.hover:border-t-0.4` - Rand oben 0rem beim Hover
- `.hover:border-t-0.3` - Rand oben 0rem beim Hover
- `.hover:border-t-0.2` - Rand oben 0,2rem beim Schweben
- `.hover:border-t-0.1` - Rand oben 0,1rem beim Schweben
- `.hover:border-t-0` - Rand oben 0rem beim Hover

#### Border X-Axis

- `.border-x-2` - Rand X-Achse 2rem
- `.border-x-1.5` - Rand X-Achse 0rem
- `.border-x-1` - Rand X-Achse 1rem
- `.border-x-0.9` - Rand X-Achse 0rem
- `.border-x-0.8` - Rand X-Achse 0rem
- `.border-x-0.7` - Rand X-Achse 0rem
- `.border-x-0.6` - Rand X-Achse 0rem
- `.border-x-0.5` - Rand X-Achse 0rem
- `.border-x-0.4` - Rand X-Achse 0rem
- `.border-x-0.3` - Rand X-Achse 0rem
- `.border-x-0.2` - Rand X-Achse 0,2rem
- `.border-x-0.1` - Rand X-Achse 0,1rem
- `.border-x-0` - Rand X-Achse 0rem
- `.hover:border-x-2` - Rand X-Achse 2rem beim Schweben
- `.hover:border-x-1.5` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-1` - Rand X-Achse 1rem beim Schweben
- `.hover:border-x-0.9` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.8` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.7` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.6` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.5` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.4` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.3` - Rand X-Achse 0rem beim Schweben
- `.hover:border-x-0.2` - Rand-X-Achse 0,2rem beim Schweben
- `.hover:border-x-0.1` - Rand-X-Achse 0,1rem beim Schweben
- `.hover:border-x-0` - Rand X-Achse 0rem beim Schweben

#### Border Y-Axis

- `.border-y-2` - Rand Y-Achse 2rem
- `.border-y-1.5` - Rand Y-Achse 0rem
- `.border-y-1` - Rand Y-Achse 1rem
- `.border-y-0.9` - Rand Y-Achse 0rem
- `.border-y-0.8` - Rand Y-Achse 0rem
- `.border-y-0.7` - Rand Y-Achse 0rem
- `.border-y-0.6` - Rand Y-Achse 0rem
- `.border-y-0.5` - Rand Y-Achse 0,5rem
- `.border-y-0.4` - Rand Y-Achse 0rem
- `.border-y-0.3` - Rand Y-Achse 0rem
- `.border-y-0.2` - Rand Y-Achse 0,2rem
- `.border-y-0.1` - Rand Y-Achse 0,1rem
- `.border-y-0` - Rand Y-Achse 0rem
- `.hover:border-y-2` - Grenze Y-Achse 2rem beim Schweben
- `.hover:border-y-1.5` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-1` - Grenze Y-Achse 1rem beim Schweben
- `.hover:border-y-0.9` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.8` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.7` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.6` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.5` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.4` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.3` - Grenze Y-Achse 0rem beim Schweben
- `.hover:border-y-0.2` - Grenze Y-Achse 0,2rem beim Schweben
- `.hover:border-y-0.1` - Grenze Y-Achse 0,1rem beim Schweben
- `.hover:border-y-0` - Grenze Y-Achse 0rem beim Schweben

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

- `.hover:shadow-5` - Box Shadow Alle 5rem im Schwebeflug
- `.hover:shadow-5-1` - Box Shadow Alle 5-1rem im Schwebeflug
- `.hover:shadow-4` - Box Shadow Alle 4rem im Schwebeflug
- `.hover:shadow-4-1` - Box Shadow Alle 4-1rem im Schwebeflug
- `.hover:shadow-3` - Box Shadow Alle 3rem im Schwebeflug
- `.hover:shadow-3-1` - Box Shadow Alle 3-1rem im Schwebeflug
- `.hover:shadow-2` - Box Shadow Alle 2rem im Schwebeflug
- `.hover:shadow-2-1` - Box Shadow Alle 2-1rem beim Schweben
- `.hover:shadow-1` - Box Shadow All 1rem beim Schweben
- `.hover:shadow-1-1` - Box Shadow Alle 1-1rem beim Schweben
- `.hover:shadow-none` - Box Shadow Alle keine beim Schweben
- `.shadow-5` - Box Shadow Alle 5rem
- `.shadow-5-1` - Box Shadow Alle 5-1rem
- `.shadow-4` - Box Shadow Alle 4rem
- `.shadow-4-1` - Box Shadow Alle 4-1rem
- `.shadow-3` - Box Shadow Alle 3rem
- `.shadow-3-1` - Box Shadow Alle 3-1rem
- `.shadow-2` - Box Shadow Alle 2rem
- `.shadow-2-1` - Box Shadow Alle 2-1rem
- `.shadow-1` - Box Shadow Alle 1rem
- `.shadow-1-1` - Box Shadow Alle 1-1rem
- `.shadow-none` - Box Shadow Alle keine

#### Box Shadow Bottom

- `.hover:shadow-b-10` - Box Shadow Bottom 10rem beim Schweben
- `.hover:shadow-b-9` - Box Shadow Bottom 9rem beim Schweben
- `.hover:shadow-b-8` - Box Shadow Bottom 8rem beim Schweben
- `.hover:shadow-b-7` - Box Shadow Bottom 7rem beim Schweben
- `.hover:shadow-b-6` - Box Shadow Bottom 6rem beim Schweben
- `.hover:shadow-b-5` - Box Shadow Bottom 5rem beim Schweben
- `.hover:shadow-b-4` - Box Shadow Bottom 4rem beim Schweben
- `.hover:shadow-b-3` - Box Shadow Bottom 3rem beim Schweben
- `.hover:shadow-b-2` - Box Shadow Bottom 2rem beim Schweben
- `.hover:shadow-b-1` - Box Shadow Bottom 1rem beim Schweben
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

- `.hover:shadow-l-10` - Box Shadow links 10rem beim Schweben
- `.hover:shadow-l-9` - Box Shadow links 9rem beim Schweben
- `.hover:shadow-l-8` - Box Shadow Left 8rem beim Schweben
- `.hover:shadow-l-7` - Box Shadow links 7rem beim Schweben
- `.hover:shadow-l-6` - Box Shadow links 6rem beim Schweben
- `.hover:shadow-l-5` - Box Shadow links 5rem beim Schweben
- `.hover:shadow-l-4` - Box Shadow Left 4rem beim Schweben
- `.hover:shadow-l-3` - Box Shadow links 3rem beim Schweben
- `.hover:shadow-l-2` - Box Shadow Left 2rem beim Schweben
- `.hover:shadow-l-1` - Box Shadow Left 1rem beim Schweben
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

- `.hover:shadow-r-10` - Box Shadow Right 10rem beim Schweben
- `.hover:shadow-r-9` - Box Shadow Right 9rem beim Schweben
- `.hover:shadow-r-8` - Box Shadow Right 8rem beim Schweben
- `.hover:shadow-r-7` - Box Shadow Right 7rem beim Schweben
- `.hover:shadow-r-6` - Box Shadow Right 6rem beim Schweben
- `.hover:shadow-r-5` - Box Shadow Right 5rem beim Schweben
- `.hover:shadow-r-4` - Box Shadow Right 4rem beim Schweben
- `.hover:shadow-r-3` - Box Shadow Right 3rem beim Schweben
- `.hover:shadow-r-2` - Box Shadow Right 2rem beim Schweben
- `.hover:shadow-r-1` - Box Shadow Right 1rem beim Schweben
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

- `.hover:shadow-t-10` - Box Shadow Top 10rem beim Schweben
- `.hover:shadow-t-9` - Box Shadow Top 9rem beim Schweben
- `.hover:shadow-t-8` - Box Shadow Top 8rem beim Schweben
- `.hover:shadow-t-7` - Box Shadow Top 7rem im Schwebeflug
- `.hover:shadow-t-6` - Box Shadow Top 6rem beim Schweben
- `.hover:shadow-t-5` - Box Shadow Top 5rem beim Schweben
- `.hover:shadow-t-4` - Box Shadow Top 4rem im Schwebeflug
- `.hover:shadow-t-3` - Box Shadow Top 3rem beim Schweben
- `.hover:shadow-t-2` - Box Shadow Top 2rem beim Schweben
- `.hover:shadow-t-1` - Box Shadow Top 1rem beim Schweben
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

- `.blur-5` - Unschärfe 5rem
- `.blur-4` - Unschärfe 4rem
- `.blur-3` - Unschärfe 3rem
- `.blur-2` - Unschärfe 2rem
- `.blur-1` - Unschärfe 1rem
- `.blur-0` - Unschärfe 0rem
- `.hover:blur-5` - Unschärfe 5rem beim Schweben
- `.hover:blur-4` - 4rem beim Schweben verwischen
- `.hover:blur-3` - 3rem beim Schweben verwischen
- `.hover:blur-2` - Beim Schweben 2rem verwischen
- `.hover:blur-1` - 1 Rem beim Schweben verwischen
- `.hover:blur-0` - Beim Schweben 0rem verwischen

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

- `.hover:rotate-180` - Beim Schweben um 180 rem drehen
- `.hover:rotate-135` - Beim Schweben um 135 rem drehen
- `.hover:rotate-90` - Beim Schweben um 90 rem drehen
- `.hover:rotate-45` - Beim Schweben um 45 rem drehen
- `.hover:rotate-12` - Beim Schweben um 12 Rem drehen
- `.hover:rotate-9` - Beim Schweben um 9 rem drehen
- `.hover:rotate-6` - Beim Schweben um 6 Rem drehen
- `.hover:rotate-3` - Beim Schweben um 3 Rem drehen
- `.hover:rotate-0` - Beim Schweben um 0 rem drehen
- `.rotate-180` - 180° drehen
- `.rotate-135` - 135rem drehen
- `.rotate-90` - 90° drehen
- `.rotate-45` - 45rem drehen
- `.rotate-12` - 12rem drehen
- `.rotate-9` - 9rem drehen
- `.rotate-6` - 6rem drehen
- `.rotate-3` - 3rem drehen
- `.rotate-0` - 0rem drehen

##### Negative Rotate

- `.-rotate-180` - Negativ 180rem drehen
- `.-rotate-135` - Negativ drehen 135rem
- `.-rotate-90` - Negativ drehen 90rem
- `.-rotate-45` - Negativ drehen 45rem
- `.-rotate-12` - Negativ drehen 12rem
- `.-rotate-9` - Negativ drehen 9rem
- `.-rotate-6` - Negativ drehen 6rem
- `.-rotate-3` - Negativ drehen 3rem
- `.hover:-rotate-180` - Negativ: Beim Schweben um 180 rem drehen
- `.hover:-rotate-135` - Negativ: 135 rem beim Schweben drehen
- `.hover:-rotate-90` - Negativ: 90 rem beim Schweben drehen
- `.hover:-rotate-45` - Negativ: 45 rem beim Schweben drehen
- `.hover:-rotate-12` - Negativ, 12 Rem drehen beim Schweben
- `.hover:-rotate-9` - Negativ: 9 rem beim Schweben drehen
- `.hover:-rotate-6` - Negativ: 6 rem beim Schweben drehen
- `.hover:-rotate-3` - Negativ 3 Rem drehen beim Schweben

### Skew

#### Skew X-Axis

- `.hover:skew-x-12` - Verzerren Sie die X-Achse um 12 rem beim Schweben
- `.hover:skew-x-6` - X-Achse 6rem beim Schweben verzerren
- `.hover:skew-x-3` - X-Achse 3rem beim Schweben verzerren
- `.hover:skew-x-0` - Verzerre die X-Achse um 0rem beim Schweben
- `.skew-x-12` - Skew X-Achse 12rem
- `.skew-x-6` - Skew X-Achse 6rem
- `.skew-x-3` - Skew X-Achse 3rem
- `.skew-x-0` - Skew X-Achse 0rem

##### Negative Skew X-Axis

- `.-skew-x-12` - Negativer Skew X-Achse 12rem
- `.-skew-x-6` - Negativer Skew X-Achse 6rem
- `.-skew-x-3` - Negativer Skew X-Achse 3rem
- `.hover:-skew-x-12` - Negativer Skew X-Achse 12rem beim Schweben
- `.hover:-skew-x-6` - Negativer Skew X-Achse 6rem beim Schweben
- `.hover:-skew-x-3` - Negativer Skew X-Achse 3rem beim Schweben

#### Skew Y-Axis

- `.hover:skew-y-12` - Y-Achse 12rem beim Schweben verzerren
- `.hover:skew-y-6` - Y-Achse 6rem beim Schweben verzerren
- `.hover:skew-y-3` - Schräge Y-Achse 3rem beim Schweben
- `.hover:skew-y-0` - Y-Achse 0rem beim Schweben verzerren
- `.skew-y-12` - Skew Y-Achse 12rem
- `.skew-y-6` - Skew Y-Achse 6rem
- `.skew-y-3` - Skew Y-Achse 3rem
- `.skew-y-0` - Skew Y-Achse 0rem

##### Negative Skew Y-Axis

- `.-skew-y-12` - Negativer Skew Y-Achse 12rem
- `.-skew-y-6` - Negativer Skew Y-Achse 6rem
- `.-skew-y-3` - Negativer Skew Y-Achse 3rem
- `.hover:-skew-y-12` - Negativer Skew Y-Achse 12rem beim Schweben
- `.hover:-skew-y-6` - Negativer Skew Y-Achse 6rem beim Schweben
- `.hover:-skew-y-3` - Negativer Skew Y-Achse 3rem beim Schweben

### Translate

- `.hover:translate-50` - Übersetze 50rem beim Schweben
- `.hover:translate-25` - Übersetzen Sie 25rem beim Schweben
- `.translate-50` - Übersetzen Sie 50rem
- `.translate-25` - Übersetzen Sie 25rem

##### Negative Translate

- `.-translate-50` - Negativ übersetzen 50rem
- `.-translate-25` - Negativ übersetzen 25rem
- `.hover:-translate-50` - Negativ Übersetzen Sie 50 rem beim Schweben
- `.hover:-translate-25` - Negativ Übersetzen Sie 25rem beim Schweben

#### Translate X-Axis

- `.hover:translate-x-50` - Verschieben Sie die X-Achse um 50 rem beim Schweben
- `.hover:translate-x-25` - Verschieben Sie die X-Achse um 25 rem beim Schweben
- `.hover:translate-x-2` - Verschieben Sie die X-Achse 2rem beim Schweben
- `.hover:translate-x-1.5` - Verschieben Sie die X-Achse 0rem beim Hover
- `.hover:translate-x-1` - Verschieben Sie die X-Achse 1rem beim Schweben
- `.hover:translate-x-0.5` - Verschieben Sie die X-Achse beim Schweben um 0,5 rem
- `.hover:translate-x-0` - Verschieben Sie die X-Achse 0rem beim Hover
- `.translate-x-50` - X-Achse 50rem verschieben
- `.translate-x-25` - X-Achse um 25rem verschieben
- `.translate-x-2` - X-Achse 2rem verschieben
- `.translate-x-1.5` - X-Achse 0rem verschieben
- `.translate-x-1` - X-Achse 1rem verschieben
- `.translate-x-0.5` - Verschieben Sie die X-Achse um 0,5 rem
- `.translate-x-0` - X-Achse 0rem verschieben

##### Negative Translate X-Axis

- `.-translate-x-50` - Negative Verschiebung der X-Achse 50rem
- `.-translate-x-25` - Negative Verschiebung der X-Achse 25rem
- `.-translate-x-2` - Negativ X-Achse verschieben 2rem
- `.-translate-x-1.5` - Negative Verschiebung der X-Achse 1,5rem
- `.-translate-x-1` - Negativ X-Achse verschieben 1rem
- `.-translate-x-0.5` - Negative Verschiebung der X-Achse 0,5rem
- `.hover:-translate-x-50` - Negative Verschiebung der X-Achse um 50 rem beim Schweben
- `.hover:-translate-x-25` - Negativ X-Achse 25rem verschieben beim Schweben
- `.hover:-translate-x-2` - Negativ X-Achse 2rem verschieben beim Schweben
- `.hover:-translate-x-1.5` - Negative Verschiebung der X-Achse 1,5rem beim Schweben
- `.hover:-translate-x-1` - Negative Verschiebung der X-Achse 1rem beim Schweben
- `.hover:-translate-x-0.5` - Negative Verschiebung der X-Achse um 0,5 Rem beim Schweben

#### Translate Y-Axis

- `.hover:translate-y-50` - Verschieben Sie die Y-Achse um 50 rem beim Schweben
- `.hover:translate-y-25` - Verschieben Sie die Y-Achse um 25 rem beim Schweben
- `.hover:translate-y-2` - Übersetzen Sie die Y-Achse 2rem beim Schweben
- `.hover:translate-y-1.5` - Übersetzen Sie die Y-Achse 0rem beim Schweben
- `.hover:translate-y-1` - Verschieben Sie die Y-Achse 1rem beim Hover
- `.hover:translate-y-0.5` - Verschieben Sie die Y-Achse beim Schweben um 0,5 rem
- `.hover:translate-y-0` - Übersetzen Sie die Y-Achse 0rem beim Schweben
- `.translate-y-50` - Y-Achse 50rem verschieben
- `.translate-y-25` - Y-Achse um 25rem verschieben
- `.translate-y-2` - Y-Achse 2rem verschieben
- `.translate-y-1.5` - Y-Achse 0rem verschieben
- `.translate-y-1` - Y-Achse 1rem verschieben
- `.translate-y-0.5` - Verschieben Sie die Y-Achse um 0,5 rem
- `.translate-y-0` - Y-Achse 0rem verschieben

##### Negative Translate Y-Axis

- `.-translate-y-50` - Negative Verschiebung der Y-Achse 50rem
- `.-translate-y-25` - Negative Verschiebung der Y-Achse 25rem
- `.-translate-y-2` - Negativ Y-Achse verschieben 2rem
- `.-translate-y-1.5` - Negative Verschiebung der Y-Achse 1,5rem
- `.-translate-y-1` - Negativ Y-Achse verschieben 1rem
- `.-translate-y-0.5` - Negative Verschiebung der Y-Achse 0,5rem
- `.hover:-translate-y-50` - Negative Verschiebung der Y-Achse um 50 rem beim Schweben
- `.hover:-translate-y-25` - Negativ Y-Achse 25rem verschieben beim Schweben
- `.hover:-translate-y-2` - Negativ Y-Achse 2rem verschieben beim Schweben
- `.hover:-translate-y-1.5` - Negative Verschiebung der Y-Achse 1,5rem beim Schweben
- `.hover:-translate-y-1` - Negativ Y-Achse 1rem verschieben beim Schweben
- `.hover:-translate-y-0.5` - Negative Verschiebung der Y-Achse um 0,5 Rem beim Schweben

### Zoom

- `.hover:zoom` - Beim Schweben zoomen
- `.hover:zoom-2` - Beim Schweben 2rem zoomen
- `.hover:zoom-1.5` - Zoom 1,5rem beim Schweben
- `.zoom` - Zoomen
- `.zoom-2` - Zoom 2rem
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

- `.content-3` - Inhalt 3rem
- `.content-3-bg` - Inhalt 3-bgrem
- `.content-2` - Inhalt 2rem
- `.content-2-bg` - Inhalt 2-bgrem
- `.content-2-text` - Inhalt 2-textrem
- `.content-1` - Inhalt 1rem
- `.content-1-bg` - Inhalt 1-bgrem
- `.content-1-text` - Inhalt 1-textrem
- `.hover:content-3-bg` - Inhalt 3-bgrem beim Schweben
- `.hover:content-2-bg` - Inhalt 2-bgrem beim Schweben
- `.hover:content-2-text` - Inhalt 2-Text beim Hover
- `.hover:content-1-bg` - Inhalt 1-bgrem beim Schweben
- `.hover:content-1-text` - Inhalt 1-Textrem beim Hover

### Dir

- `.dir-ltr` - Dir ltr
- `.dir-rtl` - Dir rtl

### Mse

- `.hover:mse-2` - Mse 2rem beim Schweben
- `.hover:mse-1.5` - Mse 1,5rem im Schwebeflug
- `.hover:mse-1` - Mse 1rem beim Schweben
- `.hover:mse-0.5` - Mse 0,5rem beim Schweben
- `.hover:mse-0` - Mse 0rem beim Schweben
- `.mse-2` - Mse 2rem
- `.mse-1.5` - Mse 1,5rem
- `.mse-1` - Mse 1rem
- `.mse-0.5` - Mse 0,5rem
- `.mse-0` - Mse 0rem

### Other

##### Other - undefined

- `.hover:px-3.5` - Anderes beim Hover auf px 3.5

### Visibility

- `.hover:v-hide` - Sichtbarkeit beim Schweben ausgeblendet
- `.hover:v-show` - Sichtbarkeit beim Schweben sichtbar
- `.v-hide` - Sichtbarkeit verborgen
- `.v-show` - Sichtbarkeit sichtbar

##### Visibility - Mobile (< 480px)

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

##### Visibility - Tv (> 1200px)

- `.hover:tv:v-hide` - Sichtbarkeit beim Schweben im Fernsehen ausgeblendet
- `.hover:tv:v-show` - Sichtbarkeit beim Schweben im Fernsehen sichtbar
- `.tv:v-hide` - Im Fernsehen verborgene Sichtbarkeit
- `.tv:v-show` - Sichtbarkeit im Fernsehen sichtbar

##### Visibility - Tablet Max (< 768px)

- `.hover:tablet-max:v-hide` - Sichtbarkeit beim Hover auf dem Tablet max. ausgeblendet
- `.hover:tablet-max:v-show` - Sichtbarkeit beim Hover auf dem Tablet max
- `.tablet-max:v-hide` - Sichtbarkeit ausgeblendet auf dem Tablet max
- `.tablet-max:v-show` - Sichtbarkeit sichtbar auf dem Tablet max

##### Visibility - Tablet Pc Max (< 992px)

- `.hover:tablet-pc-max:v-hide` - Sichtbarkeit ausgeblendet beim Schweben auf dem Tablet-PC max
- `.hover:tablet-pc-max:v-show` - Sichtbarkeit beim Hover auf dem Tablet-PC max
- `.tablet-pc-max:v-hide` - Sichtbarkeit ausgeblendet auf Tablet-PC max
- `.tablet-pc-max:v-show` - Sichtbarkeit sichtbar auf Tablet-PC max

##### Visibility - Pc Max (< 1200px)

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
