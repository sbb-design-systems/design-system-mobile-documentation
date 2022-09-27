## 1. Was macht das Element?
*   Darstellung von Informationen in einer Liste.

## 2. Wann soll das Element eingesetzt werden?
*   Innerhalb von Listen. 

## 3. Regeln
*   Ein Listen-Eintrag kann als Darstellungsobjekt oder zur Navigation verwendet werden.
*   Auf Listen-Einträgen können neben Klick- auch Swipe-Interaktionen definiert werden.
*   Erste Funktion wird auf Swipe-to-left gelegt, zweite Funktion auf Swipe-to-right.

## 4. Ausprägungen und Zustände
Das Element hat folgende Zustände:
*   Default
*   Pressed
*   Disabled
*   Loading
*   Swipe left (optional)
*   Swipe right (optional)

Das Element hat folgende Ausprägungen:
*   listed / boxed
*   mit Icon / ohne Icon
*   mit Subtext / ohne Subtext
*   mit Icon rechts / ohne Icon rechts
*   mit Button / ohne Button

<label class="switch" style="display:none"><input type="checkbox"><span class="slider round"></span></label>

### 4.1 Listed
#### 4.1.1 Default
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-dark.png 'class: image dark hide')

#### 4.1.2 ohne Icon
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-without-icon-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-without-icon-dark.png 'class: image dark hide')

#### 4.1.3 mit Subtext
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-with-subtext-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-with-subtext-dark.png 'class: image dark hide')

#### 4.1.4 mit Icon rechts
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-with-icon-right-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-with-icon-right-dark.png 'class: image dark hide')

#### 4.1.5 mit Button
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-with-button-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-default-with-button-dark.png 'class: image dark hide')

### 4.2 Boxed
#### 4.2.1 Default
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-dark.png 'class: image dark hide')

#### 4.2.2 ohne Icon
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-without-icon-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-without-icon-dark.png 'class: image dark hide')

#### 4.2.3 mit Subtext
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-with-subtext-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-with-subtext-dark.png 'class: image dark hide')

#### 4.2.4 mit Icon rechts
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-with-icon-right-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-with-icon-right-dark.png 'class: image dark hide')

#### 4.2.5 mit Button
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-with-button-light.png 'class: image light')
![Darstellung des List-Items](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/list-item/images/list-item-boxed-with-button-dark.png 'class: image dark hide')

### Design Spezifikation
[Figma-Link](https://www.figma.com/file/WOtLIam1xwrqcgnAITsEhV/Design-System-Mobile?node-id=28%3A2540)

## 5. Barrierefreiheit
* Wenn die Funktion des Eintrages nur über ein Icon Dargestellt wird, muss diese zusätzlich als Alternativtext hinterlegt werden.