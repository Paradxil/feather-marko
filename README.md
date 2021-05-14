# feather-marko
feather-marko provides a simple MarkoJS component to use Feather icons.

## Getting Started
Installation
```
npm i feather-marko
```
Demo
```
npm run demo
```

## Usage

### Component
Only one component is provided:
```
feather-icon
```
Drop the `feather-icon` tag into your Marko templates wherever you want to display an icon.

### Attributes
You can modify the look of the icon with the following attributes:

Attribute | Description | Examples
------------ | ------------- | -----------
icon | Set the icon. See the demo or Feather for a list of icons. | edit, image, chevron-up
color | Set the color. Default behavior also changes stroke color. | #444, red
stroke | Set the stroke color. Defaults to 'currentColor' so the stroke matches the color. | currentColor, green
fill | Set the fill color. | none, #fff, blue
size | Set the icon size. | 24px, 1em, 100%
strokewidth | Set the stroke width. | 2px, 1.5px
strokelinecap | Set the linecap type. | round, square, butt
strokelinejoin | Set the linejoin type. | round, bevel, miter

### Example
![Edit Icon Orange](./assets/edit-example.png)
```marko
feather-icon icon='edit' color='orange' size='48px'
```

### Defaults
You can use CSS variables to change the default icon attributes. Setting an attribute on an icon directly wil override the defaults.

```css
.feather-icon-svg {
        --feather-icon-color: inherit;
        --feather-icon-stroke: currentColor;
        --feather-icon-size: 1em;
        --feather-icon-fill: none;
        --feather-icon-stroke-width: 2px;
        --feather-icon-linecap: round;
        --feather-icon-linejoin: round;
}
```
You can also define the variables in `:root` if you add `!important`.

## License
MIT

## Author
Hunter Stratton