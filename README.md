# style-prefix
provide a mixin that adds a prefix to component 

you need to import ``prefix-mixin.scss`` in your target **.scss**.

then just use like: 

```scss
@include addPrefix("my-prefix-") {
  &disabled {
    pointer-events: none;
    color: gray;
    background-color: transparent;
  }
}
```

let's see the result:

```css
.my-prefix-disabled { /* prefix added */
  pointer-events: none;
  color: gray;
  background-color: transparent;
}
```