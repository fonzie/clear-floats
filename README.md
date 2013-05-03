# Clear Floats

Clear floated child elements. 

## Installation

```
bower install fonzie-clear-floats
```

## Usage

You have access to mixins and classes:

```scss
ul {
  @include fz-clearFloats;
}
```

To access the classes, you need to first include them:

```scss
@include fz-ClearFloats;
```

Then you can use them

```html
<ul class="fz-cf">
  <li>Floated Item</li>
</ul>
```