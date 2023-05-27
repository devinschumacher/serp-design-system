```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Textarea



Textareas collect data from the user and allow multiple lines of text.


```html:html
<sl-textarea></sl-textarea>
```

#### Code

```htm
<sl-textarea></sl-textarea>
```

?> This component doesn't work with standard forms. Use `<sl-form>` instead.

?> Please refer to the section on form control validation to learn how to do client-side validation.

## Examples

### Rows

Use the `rows` attribute to change the number of text rows that get shown.


```html:html
<sl-textarea rows="2"></sl-textarea>
```

#### Code

```htm
<sl-textarea rows="2"></sl-textarea>
```

### Placeholders

Use the `placeholder` attribute to add a placeholder.


```html:html
<sl-textarea placeholder="Type something"></sl-textarea>
```

#### Code

```htm
<sl-textarea placeholder="Type something"></sl-textarea>
```

### Disabled

Use the `disabled` attribute to disable an input.


```html:html
<sl-textarea placeholder="Textarea" disabled></sl-textarea>
```

#### Code

```htm
<sl-textarea placeholder="Textarea" disabled></sl-textarea>
```

### Sizes

Use the `size` attribute to change a textarea's size.


```html:html
<sl-textarea placeholder="Small" size="small"></sl-textarea>
<br>
<sl-textarea placeholder="Medium" size="medium"></sl-textarea>
<br>
<sl-textarea placeholder="Large" size="large"></sl-textarea>
```

#### Code

```htm
<sl-textarea placeholder="Small" size="small"></sl-textarea>
<br>
<sl-textarea placeholder="Medium" size="medium"></sl-textarea>
<br>
<sl-textarea placeholder="Large" size="large"></sl-textarea>
```

### Labels

Use the `label` attribute to give the textarea an accessible label. For labels that contain HTML, use the `label` slot instead.


```html:html
<sl-textarea label="Comments"></sl-textarea>
```

#### Code

```htm
<sl-textarea label="Comments"></sl-textarea>
```

### Help Text

Add descriptive help text to a textarea with the `help-text` attribute. For help texts that contain HTML, use the `help-text` slot instead.


```html:html
<sl-textarea 
  label="Feedback" 
  help-text="Please tell us what you think."
>
</sl-textarea>
```

#### Code

```htm
<sl-textarea 
  label="Feedback" 
  help-text="Please tell us what you think."
>
</sl-textarea>
```

### Prevent Resizing

By default, textareas can be resized vertically by the user. To prevent resizing, set the `resize` attribute to `none`.


```html:html
<sl-textarea resize="none"></sl-textarea>
```

#### Code

```htm
<sl-textarea resize="none"></sl-textarea>
```

### Expand with Content

Textareas will automatically resize to expand to fit their content when `resize` is set to `auto`.


```html:html
<sl-textarea resize="auto"></sl-textarea>
```

#### Code

```htm
<sl-textarea resize="auto"></sl-textarea>
```


