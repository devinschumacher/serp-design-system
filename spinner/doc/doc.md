```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Spinner



Spinners are used to show the progress of an indeterminate operation.


```html:html
<sl-spinner></sl-spinner>
```

#### Code

```htm
<sl-spinner></sl-spinner>
```

## Examples

### Size

Spinners are sized relative to the current font size. To change their size, set the `font-size` property on the spinner itself or on a parent element as shown below.


```html:html
<sl-spinner></sl-spinner>
<sl-spinner style="font-size: 2rem;"></sl-spinner>
<sl-spinner style="font-size: 3rem;"></sl-spinner>
```

#### Code

```htm
<sl-spinner></sl-spinner>
<sl-spinner style="font-size: 2rem;"></sl-spinner>
<sl-spinner style="font-size: 3rem;"></sl-spinner>
```

### Stroke Width

The width of the spinner can be changed by setting the `--stroke-width` custom property.


```html:html
<sl-spinner style="font-size: 2rem; --stroke-width: 6px;"></sl-spinner>
```

#### Code

```htm
<sl-spinner style="font-size: 2rem; --stroke-width: 6px;"></sl-spinner>
```

### Color

The spinner's colors can be changed by setting the `--indicator-color` and `--track-color` custom properties.


```html:html
<sl-spinner style="font-size: 2rem; --indicator-color: tomato;"></sl-spinner>
```

#### Code

```htm
<sl-spinner style="font-size: 2rem; --indicator-color: tomato;"></sl-spinner>
```


