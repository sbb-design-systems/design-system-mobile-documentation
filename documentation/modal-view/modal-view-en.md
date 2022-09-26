## 1. What does the module do?
*   It dims the current view and puts a modal dialogue over it.

## 2. When should the module be used?
*   When the user’s attention is required.
*   When information/input is required from the user.
*   When related content is to be displayed.
*   When additional content is to be displayed.
*   The module is not suitable for error messages, warnings or similar notifications.

## 3. Rules
*   The user must always have the option of closing the modal dialogue.
*   Any modal dialogue consists of a header (close icon and title) and content.
*   The content must contain at least an interaction element (e.g. ‘save’ or ‘OK’).
*   The modal dialogue cannot be used for error messages.
*   The width and height of the dialogue is determined by the size of the content.
*   A minimum space from the screen edge must be kept.
*   The modal dialogue is closed if the dimmed section is clicked on.
*   If the content is too big, a full-screen modal dialogue can be selected: see page types.

## 4. Variants
*   With and without close button
*   With and without back button

<label class="switch" style="display:none"><input type="checkbox"><span class="slider round"></span></label>

### 4.1 With close button and without back button
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-default-light.png 'class: image light')
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-default-dark.png 'class: image dark hide')

### 4.2 Wiht close and back button
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-back-light.png 'class: image light')
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-back-dark.png 'class: image dark hide')

### 4.3 wihtout close and back button
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-without-close-button-light.png 'class: image light')
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-without-close-button-dark.png 'class: image dark hide')

### 4.4 without close button and wiht back button
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-without-close-button-back-light.png 'class: image light')
![Darstellung eines modalen Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-mobile-documentation/doku-update/documentation/modal-view/images/modal-without-close-button-back-dark.png 'class: image dark hide')

### Design Specification
[Figma-Link](https://www.figma.com/file/WOtLIam1xwrqcgnAITsEhV/Design-System-Mobile?node-id=25%3A8074)

## 5. Accessibility
*   Content outside of the open dialogue should no longer be reachable via the screen reader.