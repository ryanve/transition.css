# transition.css
Functional CSS transition module with sensible defaults for good UX

## install
```
npm install transition.css --save
```

```
yarn add transition.css
```

## import
```scss
@import './node_modules/transition.css/transition';
@import './node_modules/property.css/property';
@import './node_modules/property.css/ease';
```

## usage

```html
<figure class="Example transition transition-opacity">
  Example
</figure>
```

```css
.Example {
  opacity: 0;
}

.Example-active {
  opacity: 1;
}
```

## UX
- Uses optimal transition duration [based on research](https://ux.stackexchange.com/a/76212/100660)
- Easing defaults to `ease`
