```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Radio



Radios allow the user to select one option from a group of many.

Radios are designed to be used with radio groups. As such, all of the examples on this page utilize them to demonstrate their correct usage.


```html:html
<sl-radio-group label="Select an option" no-fieldset>
  <sl-radio value="1" checked>Option 1</sl-radio>
  <sl-radio value="2">Option 2</sl-radio>
  <sl-radio value="3">Option 3</sl-radio>
</sl-radio-group>
```

#### Code

```htm
<sl-radio-group label="Select an option" no-fieldset>
  <sl-radio value="1" checked>Option 1</sl-radio>
  <sl-radio value="2">Option 2</sl-radio>
  <sl-radio value="3">Option 3</sl-radio>
</sl-radio-group>
```

?> This component doesn't work with standard forms. Use `<sl-form>` instead.

## Examples

### Disabled

Use the `disabled` attribute to disable a radio.


```html:html
<sl-radio-group label="Select an option" no-fieldset>
  <sl-radio value="1" checked>Option 1</sl-radio>
  <sl-radio value="2">Option 2</sl-radio>
  <sl-radio value="3">Option 3</sl-radio>
  <sl-radio value="4" disabled>Disabled</sl-radio>
</sl-radio-group>
```

#### Code

```htm
<sl-radio-group label="Select an option" no-fieldset>
  <sl-radio value="1" checked>Option 1</sl-radio>
  <sl-radio value="2">Option 2</sl-radio>
  <sl-radio value="3">Option 3</sl-radio>
  <sl-radio value="4" disabled>Disabled</sl-radio>
</sl-radio-group>
```


