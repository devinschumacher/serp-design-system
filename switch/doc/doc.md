```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Switch



Switches allow the user to toggle an option on or off. 


```html:html
<sl-switch>Switch</sl-switch>
```

#### Code

```htm
<sl-switch>Switch</sl-switch>
```

?> This component doesn't work with standard forms. Use `<sl-form>` instead.

## Examples

### Checked

Use the `checked` attribute to activate the switch.


```html:html
<sl-switch checked>Checked</sl-switch>
```

#### Code

```htm
<sl-switch checked>Checked</sl-switch>
```

### Disabled

Use the `disabled` attribute to disable the switch.


```html:html
<sl-switch disabled>Disabled</sl-switch>
```

#### Code

```htm
<sl-switch disabled>Disabled</sl-switch>
```

### Custom Size

Use the available custom properties to make the switch a different size.


```html:html
<sl-switch style="--width: 80px; --height: 32px; --thumb-size: 26px;"></sl-switch>
```

#### Code

```htm
<sl-switch style="--width: 80px; --height: 32px; --thumb-size: 26px;"></sl-switch>
```


