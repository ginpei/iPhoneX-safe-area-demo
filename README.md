# iPhone X - Safe Area Demo

- [https://ginpei.github.io/iPhoneX-safe-area-demo/](https://ginpei.github.io/iPhoneX-safe-area-demo/)

# Screenshots

`<body>` is red, `<div>` under `<body>` is blue.

## Default + `padding: 5px`

![Portrait](./doc/default-portrait.png)

![Landscape](./doc/default-landscape.png)

## Viewport Fit

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
```

![Portrait](./doc/viewport-fit-portrait.png)

![Landscape](./doc/viewport-fit-landscape.png)

## Safe Area

```css
body {
  padding:
    constant(safe-area-inset-top)
    constant(safe-area-inset-right)
    constant(safe-area-inset-bottom)
    constant(safe-area-inset-left);
}
```

![Portrait](./doc/safe-area-portrait.png)

![Landscape](./doc/safe-area-portrait.png)
