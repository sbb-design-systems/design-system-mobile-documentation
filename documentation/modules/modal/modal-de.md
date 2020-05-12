## 1. Was macht das Modul?
*   Dunkelt den aktuellen View ab und legt einen modalen Dialog darüber.

## 2. Wann soll das Modul eingesetzt werden?
*   Wenn die Aufmerksamkeit des Benutzer benötigt wird.
*   Wenn vom Benutzer eine Information/Input verlangt wird.
*   Wenn verwandter Inhalt dargestellt werden soll.
*   Wenn zusätzlicher Inhalt dargestellt werden soll.
*   Das Modul ist nicht geeignet für Fehlermeldung, Warnungen oder Ähnliches.

## 3. Regeln
*   Der Benutzer muss immer die Möglichkeit haben den modalen Dialog zu schliessen.
*   Jeder modale Dialog besteht aus einem Header (Schliessen-Icon und Titel) und Inhalt.
*   Der Inhalt muss mindestens ein Interaktionselement enthalten (z.B. «Speichern» oder «OK»).
*   Der modale Dialog darf nicht für Fehlermeldungen verwendet werden.
*   Die Breite und Höhe des Dialogs wird durch die Grösse des Inhalts bestimmt.
*   Ein Mindestabstand zum Bildschirmrand ist zu gewährleisten.
*   Bei Klick auf den abgedunkelten Bereich wird der modale Dialog geschlossen.
*   Ist der Inhalt zu gross, kann ein vollflächiger modaler Dialog gewählt werden: siehe Seitentypen.

## 4. Ausprägungen
<label class="switch" style="display:none"><input type="checkbox"><span class="slider round"></span></label>

### 4.1 Popup
![Darstellung eines modalen Dialogs als Popup](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/modules/modal/images/modal_popup_light.png 'class: image')
![Darstellung eines modalen Dialogs als Popup](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/modules/modal/images/modal_popup_dark.png 'class: image dark hide')

#### Design Spezifikation
* Default: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/JGPPoz#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/v/bLYoOZ/a/zJWmG4#Inspector)

### 4.2 Sheet
![Darstellung eines modalen Dialogs als Sheet](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/modules/modal/images/modal_sheet_light.png 'class: image')
![Darstellung eines modalen Dialogs als Sheet](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/modules/modal/images/modal_sheet_dark.png 'class: image dark hide')

#### Design Spezifikation
* Default: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/r2PmRK#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/v/bLYoOZ/a/ZZl1yY#Inspector)

### 4.3 Fullscreen
![Darstellung eines modalen Dialogs als Fullscreen](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/modules/modal/images/modal_fullscreen_light.png 'class: image')
![Darstellung eines modalen Dialogs als Fullscreen](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/modules/modal/images/modal_fullscreen_dark.png 'class: image dark hide')

#### Design Spezifikation
* Default: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/GaDjOY#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/v/bLYoOZ/a/JRoZD0#Inspector)
* Scrolled: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Op1Gb8#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/v/bLYoOZ/a/vjW4Je#Inspector)

## 5. Barrierefreiheit
*   Inhalte ausserhalb des geöffneten Dialogs sollen per Screen Reader nicht mehr erreichbar sein.
