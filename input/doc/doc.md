```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Input



Inputs collect data from the user.


```html:html
<sl-input></sl-input>
```

#### Code

```htm
<sl-input></sl-input>
```

?> This component doesn't work with standard forms. Use `<sl-form>` instead.

?> Please refer to the section on form control validation to learn how to do client-side validation.

## Examples

### Placeholders

Use the `placeholder` attribute to add a placeholder.


```html:html
<sl-input placeholder="Type something"></sl-input>
```

#### Code

```htm
<sl-input placeholder="Type something"></sl-input>
```

### Clearable

Add the `clearable` prop to add a clear button when the input has content.


```html:html
<sl-input placeholder="Clearable" clearable></sl-input>
```

#### Code

```htm
<sl-input placeholder="Clearable" clearable></sl-input>
```

### Toggle Password

Add the `toggle-password` prop to add a toggle button that will show the password when activated.


```html:html
<sl-input type="password" placeholder="Password Toggle" size="small" toggle-password></sl-input>
<br>
<sl-input type="password" placeholder="Password Toggle" size="medium" toggle-password></sl-input>
<br>
<sl-input type="password" placeholder="Password Toggle" size="large" toggle-password></sl-input>
```

#### Code

```htm
<sl-input type="password" placeholder="Password Toggle" size="small" toggle-password></sl-input>
<br>
<sl-input type="password" placeholder="Password Toggle" size="medium" toggle-password></sl-input>
<br>
<sl-input type="password" placeholder="Password Toggle" size="large" toggle-password></sl-input>
```

### Pill

Use the `pill` prop to give inputs rounded edges.


```html:html
<sl-input placeholder="Small" size="small" pill></sl-input>
<br>
<sl-input placeholder="Medium" size="medium" pill></sl-input>
<br>
<sl-input placeholder="Large" size="large" pill></sl-input>
```

#### Code

```htm
<sl-input placeholder="Small" size="small" pill></sl-input>
<br>
<sl-input placeholder="Medium" size="medium" pill></sl-input>
<br>
<sl-input placeholder="Large" size="large" pill></sl-input>
```

### Disabled

Use the `disabled` attribute to disable an input.


```html:html
<sl-input placeholder="Disabled" size="small" disabled></sl-input>
<br>
<sl-input placeholder="Disabled" size="medium" disabled></sl-input>
<br>
<sl-input placeholder="Disabled" size="large" disabled></sl-input>
```

#### Code

```htm
<sl-input placeholder="Disabled" size="small" disabled></sl-input>
<br>
<sl-input placeholder="Disabled" size="medium" disabled></sl-input>
<br>
<sl-input placeholder="Disabled" size="large" disabled></sl-input>
```

### Sizes

Use the `size` attribute to change an input's size.


```html:html
<sl-input placeholder="Small" size="small"></sl-input>
<br>
<sl-input placeholder="Medium" size="medium"></sl-input>
<br>
<sl-input placeholder="Large" size="large"></sl-input>
```

#### Code

```htm
<sl-input placeholder="Small" size="small"></sl-input>
<br>
<sl-input placeholder="Medium" size="medium"></sl-input>
<br>
<sl-input placeholder="Large" size="large"></sl-input>
```

### Prefix & Suffix Icons

Use the `prefix` and `suffix` slots to add icons.


```html:html
<sl-input placeholder="Small" size="small">
  <sl-icon name="tag" slot="prefix"></sl-icon>
  <sl-icon name="gear" slot="suffix"></sl-icon>
</sl-input>
<br>
<sl-input placeholder="Medium" size="medium">
  <sl-icon name="tag" slot="prefix"></sl-icon>
  <sl-icon name="gear" slot="suffix"></sl-icon>
</sl-input>
<br>
<sl-input placeholder="Large" size="large">
  <sl-icon name="tag" slot="prefix"></sl-icon>
  <sl-icon name="gear" slot="suffix"></sl-icon>
</sl-input>
```

#### Code

```htm
<sl-input placeholder="Small" size="small">
  <sl-icon name="tag" slot="prefix"></sl-icon>
  <sl-icon name="gear" slot="suffix"></sl-icon>
</sl-input>
<br>
<sl-input placeholder="Medium" size="medium">
  <sl-icon name="tag" slot="prefix"></sl-icon>
  <sl-icon name="gear" slot="suffix"></sl-icon>
</sl-input>
<br>
<sl-input placeholder="Large" size="large">
  <sl-icon name="tag" slot="prefix"></sl-icon>
  <sl-icon name="gear" slot="suffix"></sl-icon>
</sl-input>
```

### Labels

Use the `label` attribute to give the input an accessible label. For labels that contain HTML, use the `label` slot instead.


```html:html
<sl-input label="What is your name?"></sl-input>
```

#### Code

```htm
<sl-input label="What is your name?"></sl-input>
```

### Help Text

Add descriptive help text to an input with the `help-text` attribute. For help texts that contain HTML, use the `help-text` slot instead.


```html:html
<sl-input 
  label="Nickname" 
  help-text="What would you like people to call you?"
></sl-input>
```

#### Code

```htm
<sl-input 
  label="Nickname" 
  help-text="What would you like people to call you?"
></sl-input>
```


