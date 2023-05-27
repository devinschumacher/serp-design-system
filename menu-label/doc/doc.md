```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Menu Label



Menu labels are used to describe a group of menu items.


```html:html
<sl-menu
  style="max-width: 200px; border: solid 1px var(--sl-panel-border-color); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-label>Fruits</sl-menu-label>
  <sl-menu-item value="apple">Apple</sl-menu-item>
  <sl-menu-item value="banana">Banana</sl-menu-item>
  <sl-menu-item value="orange">Orange</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-label>Vegetables</sl-menu-label>
  <sl-menu-item value="broccoli">Broccoli</sl-menu-item>
  <sl-menu-item value="carrot">Carrot</sl-menu-item>
  <sl-menu-item value="zucchini">Zucchini</sl-menu-item>
</sl-menu>
```

#### Code

```htm
<sl-menu
  style="max-width: 200px; border: solid 1px var(--sl-panel-border-color); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-label>Fruits</sl-menu-label>
  <sl-menu-item value="apple">Apple</sl-menu-item>
  <sl-menu-item value="banana">Banana</sl-menu-item>
  <sl-menu-item value="orange">Orange</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-label>Vegetables</sl-menu-label>
  <sl-menu-item value="broccoli">Broccoli</sl-menu-item>
  <sl-menu-item value="carrot">Carrot</sl-menu-item>
  <sl-menu-item value="zucchini">Zucchini</sl-menu-item>
</sl-menu>
```


