```js script
import { html, registerIconLibrary } from '~/md-layout';
```

# Progress Ring



Progress rings are used to show the progress of a determinate operation in a circular fashion.


```html:html
<sl-progress-ring percentage="50"></sl-progress-ring>
```

#### Code

```htm
<sl-progress-ring percentage="50"></sl-progress-ring>
```

## Examples

### Size

Use the `size` attribute to set the diameter of the progress ring.


```html:html
<sl-progress-ring percentage="50" size="200"></sl-progress-ring>
```

#### Code

```htm
<sl-progress-ring percentage="50" size="200"></sl-progress-ring>
```

### Stroke Width

Use the `stroke-width` attribute to set the width of the progress ring's indicator.


```html:html
<sl-progress-ring percentage="50" stroke-width="10"></sl-progress-ring>
```

#### Code

```htm
<sl-progress-ring percentage="50" stroke-width="10"></sl-progress-ring>
```

### Colors

To change the color, use the `--track-color` and `--indicator-color` custom properties.


```html:html
<sl-progress-ring 
  percentage="50" 
  style="--track-color: #ffe2c6; --indicator-color: tomato;"
></sl-progress-ring>
```

#### Code

```htm
<sl-progress-ring 
  percentage="50" 
  style="--track-color: #ffe2c6; --indicator-color: tomato;"
></sl-progress-ring>
```

### Labels

Use the default slot to show a label.


```html:html
<sl-progress-ring percentage="50" size="200" class="progress-ring-labels" style="margin-bottom: .5rem;">50%</sl-progress-ring>

<br>

<sl-button circle><sl-icon name="dash"></sl-icon></sl-button>
<sl-button circle><sl-icon name="plus"></sl-icon></sl-button>


```
```js script
window.addEventListener('load', () => {
  const progressRing = document.querySelector('.progress-ring-labels');
  const subtractButton = progressRing.nextElementSibling.nextElementSibling;
  const addButton = subtractButton.nextElementSibling;

  addButton.addEventListener('click', () => {
    const percentage = Math.min(100, progressRing.percentage + 10);
    progressRing.percentage = percentage;
    progressRing.textContent = `${percentage}%`;
  });

  subtractButton.addEventListener('click', () => {
    const percentage = Math.max(0, progressRing.percentage - 10)
    progressRing.percentage = percentage;
    progressRing.textContent = `${percentage}%`;
  });
});
```
#### Code

```htm
<sl-progress-ring percentage="50" size="200" class="progress-ring-labels" style="margin-bottom: .5rem;">50%</sl-progress-ring>

<br>

<sl-button circle><sl-icon name="dash"></sl-icon></sl-button>
<sl-button circle><sl-icon name="plus"></sl-icon></sl-button>

<script>
  const progressRing = document.querySelector('.progress-ring-labels');
  const subtractButton = progressRing.nextElementSibling.nextElementSibling;
  const addButton = subtractButton.nextElementSibling;

  addButton.addEventListener('click', () => {
    const percentage = Math.min(100, progressRing.percentage + 10);
    progressRing.percentage = percentage;
    progressRing.textContent = `${percentage}%`;
  });

  subtractButton.addEventListener('click', () => {
    const percentage = Math.max(0, progressRing.percentage - 10)
    progressRing.percentage = percentage;
    progressRing.textContent = `${percentage}%`;
  });
</script>
```


