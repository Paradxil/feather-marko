# feather-marko
feather-marko provides a simple MarkoJS component to use Feather icons.

## Getting Started
```
npm i feather-marko
```

## Usage

### Component
Only one component is provided:
```
feather-icon
```
Drop `feather-icon` tag into your Marko templates wherever you want to display an icon.

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
```
feather-icon icon='edit' color='orange' size='48px'
```

## Demo
```
npm run demo
```
Running the demo will automatically open a browser window. The demo shows all icons and lets you search them.

In addition you can modify the settings for an icon and the appropriate Marko tag code will be generated making it easy to copy and paste icons into your Marko templates.