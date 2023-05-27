```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Range



Ranges allow the user to select a single value within a given range using a slider.


```html:html
<sl-range min="0" max="100" step="1"></sl-range>
```

#### Code

```htm
<sl-range min="0" max="100" step="1"></sl-range>
```

?> This component doesn't work with standard forms. Use `<sl-form>` instead.

## Examples

### Disabled

Use the `disabled` prop to disable a slider.


```html:html
<sl-range min="0" max="100" step="1" disabled></sl-range>
```

#### Code

```htm
<sl-range min="0" max="100" step="1" disabled></sl-range>
```

### Tooltip Placement

By default, the tooltip is shown on top. Set `tooltip` to `bottom` to show it below the slider.


```html:html
<sl-range min="0" max="100" step="1" tooltip="bottom"></sl-range>
```

#### Code

```htm
<sl-range min="0" max="100" step="1" tooltip="bottom"></sl-range>
```

### Disable the Tooltip

To disable the tooltip, set `tooltip` to `none`.


```html:html
<sl-range min="0" max="100" step="1" tooltip="none"></sl-range>
```

#### Code

```htm
<sl-range min="0" max="100" step="1" tooltip="none"></sl-range>
```

### Custom Tooltip Formatter

You can change the tooltip's content by setting the `tooltipFormatter` prop to a function that accepts the range's value as an argument.


```html:html
<sl-range min="0" max="100" step="1" class="range-with-custom-formatter"></sl-range>


```
```js script
window.addEventListener('load', () => {
  const range = document.querySelector('.range-with-custom-formatter');
  range.tooltipFormatter = value => `Total - ${value}%`;
});
```
#### Code

```htm
<sl-range min="0" max="100" step="1" class="range-with-custom-formatter"></sl-range>

<script>
  const range = document.querySelector('.range-with-custom-formatter');
  range.tooltipFormatter = value => `Total - ${value}%`;
</script>
```

### Labels

Use the `label` attribute to give the range an accessible label. For labels that contain HTML, use the `label` slot instead.


```html:html
<sl-range label="Volume" min="0" max="100"></sl-input>
```

#### Code

```htm
<sl-range label="Volume" min="0" max="100"></sl-input>
```

### Help Text

Add descriptive help text to a range with the `help-text` attribute. For help texts that contain HTML, use the `help-text` slot instead.


```html:html
<sl-range 
  label="Volume" 
  help-text="Controls the volume of the current song."
  min="0"
  max="100"
></sl-input>
```

#### Code

```htm
<sl-range 
  label="Volume" 
  help-text="Controls the volume of the current song."
  min="0"
  max="100"
></sl-input>
```


