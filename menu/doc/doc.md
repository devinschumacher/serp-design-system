```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Menu



Menus provide a list of options for the user to choose from.

You can use menu items, menu dividers, and menu labels to compose a menu.


```html:html
<sl-menu style="max-width: 200px; border: solid 1px var(--sl-panel-border-color); border-radius: var(--sl-border-radius-medium);">
  <sl-menu-item value="undo">Undo</sl-menu-item>
  <sl-menu-item value="redo">Redo</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item value="cut">Cut</sl-menu-item>
  <sl-menu-item value="copy">Copy</sl-menu-item>
  <sl-menu-item value="paste">Paste</sl-menu-item>
  <sl-menu-item value="delete">Delete</sl-menu-item>
</sl-menu>
```

#### Code

```htm
<sl-menu style="max-width: 200px; border: solid 1px var(--sl-panel-border-color); border-radius: var(--sl-border-radius-medium);">
  <sl-menu-item value="undo">Undo</sl-menu-item>
  <sl-menu-item value="redo">Redo</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item value="cut">Cut</sl-menu-item>
  <sl-menu-item value="copy">Copy</sl-menu-item>
  <sl-menu-item value="paste">Paste</sl-menu-item>
  <sl-menu-item value="delete">Delete</sl-menu-item>
</sl-menu>
```

?> Menus are intended for system menus (dropdown menus, select menus, context menus, etc.). They should not be mistaken for navigation menus which serve a different purpose and have a different semantic meaning. If you're building navigation, use `<nav>` and `<a>` elements instead.


