## 1. Was macht das Element?
*   Dient zur Eingabe von Ja/Nein-Werten.

## 2. Wann soll das Element eingesetzt werden?
*   Beim Auswählen einer oder mehrerer, zueinander unabhängigen Optionen.

## 3. Regeln
*   Eine Vorauswahl ist Pflicht (aktiv oder inaktiv, kein Tristate).
*   Mehrere Checkboxen können vertikal oder horizontal angeordnet werden. Bei vertikaler Anordnung soll die Variante "volle Breite" oder "mit Preis" genutzt werden. Für die horizontale Anordung soll die Variante "dynamische Breite" genutzt werden.
*   Horizontale Anordnung nur bei zwei bis drei Auswahlmöglichkeiten und kurzen Bezeichnungen.
*   Der Text kann mehrzeilig sein.
*   Nebst der eigentlich Checkbox dient auch der gesamte Text als Click-Target.
* Checkboxen werden immer mit einer Form-Group (Link) gruppiert und sind somit immer auf einem weissen Hintergrund gesetzt.
* Das letzte Element (Checkbox, volle Breite) innerhalb einer Form-Group hat jeweils keinen Boarder.

## 4. Ausprägungen und Zustände
Das Element hat folgende Zustände:
* Checked
* Unchecked
* Tristate
* Disabled Checked
* Disbaled Unchecked
* Disabled Tristate

Das Element hat folgende Ausprägungen:
* volle Breite
* mit Preis
* dynamische Breite

<label class="switch" style="display:none"><input type="checkbox"><span class="slider round"></span></label>

### 4.1 Volle Breite

#### 4.1.1 Default
![Darstellung der Checkboxen, volle Breite, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_default_light.png 'class: image')
![Darstellung der Checkboxen, volle Breite, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_default_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/KOGGby#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/2qrGYe#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/A7qwJ1#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/MVaGLl#Inspector)
* Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/0EqeGW#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/5yzAYP#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/l0jqA7#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/bDWboo#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/kA9wVl#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/WjLg4g#Inspector)
* Disabled Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/ooZy80#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/3LjlbD#Inspector)

#### 4.1.2 Ohne Icon (vor Label)
![Darstellung der Checkboxen, volle Breite, ohne Icon](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_without_icon_light.png 'class: image')
![Darstellung der Checkboxen, volle Breite, ohne Icon](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_without_icon_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/RkEQle#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/r7ewlx#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/1DrGx8#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/nKZLgW#Inspector)
* Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/pRJ98J#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/QqMxj8#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Vp5Z0q#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/xzA2yA#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/YKbEMQ#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/EAJjKY#Inspector)
* Disabled Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/KO5MG2#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/j1pPo0#Inspector)

#### 4.1.3 Ohne Call to Action
![Darstellung der Checkboxen, volle Breite, ohne Call to Action](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_without_call_to_action_light.png 'class: image')
![Darstellung der Checkboxen, volle Breite, ohne Call to Action](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_without_call_to_action_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/wqDbrl#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/dAMb1Z#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/q1vP8n#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/zJ5QqW#Inspector)
* Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Lmx5lE#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/ZZLgd7#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/7o90nL#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/JROvM5#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/yEA3lE#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/vjD1xb#Inspector)
* Disabled Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/91qkoQ#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/47dE9Z#Inspector)

#### 4.1.4 Nur Checkbox und Label
![Darstellung der Checkboxen, volle Breite, nur Checkbox und Label](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_label_only_light.png 'class: image')
![Darstellung der Checkboxen, volle Breite, nur Checkbox und Label](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_full_width_label_only_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/P05rxj#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/e0Mboj#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/gOWpAk#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Gl4z87#Inspector)
* Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/8RqlWD#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/OKL2n4#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/2agOxy#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/mYzMOJ#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/MD5bl9#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/DaZV0W#Inspector)
* Disabled Tristate:  [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/5lqa1E#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/amQbqZ#Inspector)

### 4.2 Mit Preis
#### 4.2.1 Default
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_default_light.png 'class: image')
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_default_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/bJ9lAz#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/7PDjkL#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/WVrJoA#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/yZbjWE#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/3AqmGd#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/9dAzjQ#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/rp4gMK#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/PwJqvj#Inspector)

#### 4.2.2 Ohne Icon (vor Label)
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_without_icon_light.png 'class: image')
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_without_icon_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/nkz78a#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/gkD3Yk#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Ql5n0m#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/8jadoD#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/xLaWVW#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/2q4yDy#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/EZ5yzO#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/MVdYz9#Inspector)

#### 4.2.3 Ohne Spar-Icon
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_without_supersaver_icon_light.png 'class: image')
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_without_supersaver_icon_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/jaWKj7#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/5yOg0E#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/d4QoDl#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/bD43Yz#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/zj0rzy#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/WjD8aA#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Zw9evJ#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/3Le9ad#Inspector)

#### 4.2.4 Nur Checkbox, Label und Preis
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_label_only_light.png 'class: image')
![Darstellung der Checkboxen, mit Preis, default](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_with_price_label_only_dark.png 'class: image dark hide')

##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/JG52az#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/r7Y3WK#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/vwm5aQ#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/nKp39a#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/40LD2m#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/QqvL4m#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/ee9Rpp#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/xzp3xW#Inspector)

### 4.3 Dynamische Breite
![Darstellung der Checkboxen, dynamische Breite](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_dynamic_width_light.png 'class: image')
![Darstellung der Checkboxen, dynamische Breite](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/redesign/documentation/elements/checkbox/images/Checkbox_dynamic_width_dark.png 'class: image dark hide')


##### Design Spezifikation
* Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Gv5P98#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/EAb0aO#Inspector)
* Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/OA53O2#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/j103J7#Inspector)
* Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/mldLEw#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/dAG37l#Inspector)
* Disabled Checked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/Dz57ny#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/zJpd2y#Inspector)
* Disabled Unchecked: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/jaWKjD#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/ZZ0r7J#Inspector)
* Disabled Tristate: [Light](https://sketch.cloud/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/d4QoDm#Inspector), [Dark](https://www.sketch.com/s/2fde3a36-55c2-4a07-bf8a-d986ae1eb67d/a/JRbEmz#Inspector)
