```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Tag



Tags are used as labels to organize things or to indicate a selection.


```html:html
<sl-tag type="primary">Primary</sl-tag>
<sl-tag type="success">Success</sl-tag>
<sl-tag type="info">Info</sl-tag>
<sl-tag type="warning">Warning</sl-tag>
<sl-tag type="danger">Danger</sl-tag>
```

#### Code

```htm
<sl-tag type="primary">Primary</sl-tag>
<sl-tag type="success">Success</sl-tag>
<sl-tag type="info">Info</sl-tag>
<sl-tag type="warning">Warning</sl-tag>
<sl-tag type="danger">Danger</sl-tag>
```

## Examples

### Sizes

Use the `size` prop to change a tab's size.


```html:html
<sl-tag size="small">Small</sl-tag>
<sl-tag size="medium">Medium</sl-tag>
<sl-tag size="large">Large</sl-tag>
```

#### Code

```htm
<sl-tag size="small">Small</sl-tag>
<sl-tag size="medium">Medium</sl-tag>
<sl-tag size="large">Large</sl-tag>
```

### Pill

Use the `pill` prop to give tabs rounded edges.


```html:html
<sl-tag size="small" pill>Small</sl-tag>
<sl-tag size="medium" pill>Medium</sl-tag>
<sl-tag size="large" pill>Large</sl-tag>
```

#### Code

```htm
<sl-tag size="small" pill>Small</sl-tag>
<sl-tag size="medium" pill>Medium</sl-tag>
<sl-tag size="large" pill>Large</sl-tag>
```

### Clearable

Use the `clearable` attribute to add a clear button to the tag.


```html:html
<div class="tags-clearable">
  <sl-tag size="small" clearable>Small</sl-tag>
  <sl-tag size="medium" clearable>Medium</sl-tag>
  <sl-tag size="large" clearable>Large</sl-tag>
</div>



<style>
  .tags-clearable sl-tag {
    transition: var(--sl-transition-medium) opacity;
  }
</style>
```
```js script
window.addEventListener('load', () => {
  const div = document.querySelector('.tags-clearable');

  div.addEventListener('sl-clear', event => {
    const tag = event.target;
    tag.style.opacity = '0';
    setTimeout(() => tag.style.opacity = '1', 2000);
  });
});
```
#### Code

```htm
<div class="tags-clearable">
  <sl-tag size="small" clearable>Small</sl-tag>
  <sl-tag size="medium" clearable>Medium</sl-tag>
  <sl-tag size="large" clearable>Large</sl-tag>
</div>

<script>
  const div = document.querySelector('.tags-clearable');

  div.addEventListener('sl-clear', event => {
    const tag = event.target;
    tag.style.opacity = '0';
    setTimeout(() => tag.style.opacity = '1', 2000);
  });
</script>

<style>
  .tags-clearable sl-tag {
    transition: var(--sl-transition-medium) opacity;
  }
</style>
```


