# Interface: Toggle Icon

Same like [Toggle](../toggle/README.md) interface but offers more customization.

## ⚙️ Options

Checkout common interface options(passed via `props`) [here.](../README.md)

| Option        | Default         | Interface                         | Desc                                                |
| ------------- | --------------- | --------------------------------- | --------------------------------------------------- |
| textInactive  |                 | [text-input](../text-input)       | Text to display when value is falsy                 |
| iconInactive  | favorite_border | [icon](../text-input)             | Icon to display when value is falsy                 |
| colorInactive | blue-grey       | [color-palette](../color-palette) | Color to use for icon and text when value is falsy  |
| textActive    |                 | [text-input](../text-input)       | Text to display when value is truthy                |
| iconActive    | favorite        | [icon](../text-input)             | Icon to display when value is truthy                |
| colorActive   | pink-500        | [color-palette](../color-palette) | Color to use for icon and text when value is truthy |

## 🗂️ Datatypes

- boolean

<!-- ## 🚧 Known Issues -->

## ⚡ Enhancements

- Can we merge this interface with [toggle](../toggle)? We can add extra configurations to it to achieve same features.
- Add option to hide labels in listing.
