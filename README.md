# yadi.css

Yet Another Drop-In CSS file.

## Installation

### via CDN

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/yadi.css/dist/index.css"
/>
```

### via npm

`npm install yadi.css` or
`yarn add yadi.css`

## Customization

Yadi.css can be customized by overriding several CSS variables. The default light theme is shown below.

```html
<style>
  :root {
    --white: #fbfbff;
    --black: #181827;

    --text: #484554;
    --textSecondary: #646381;
    --border: #ebebf5;
    --primary: #4958df;
    --focus: #4958df80;
    --background: var(--white);
    --backgroundSecondary: #f2f2f7;

    --pink: #d6337f;
    --green: #29ab6a;
    --blue: #1379ed;
    --orange: #f19f07;
    --red: #ed153d;
  }
</style>
```

If you override CSS variables to create your own theme, then you will have to implement your own light (or dark) mode using the `prefers-color-scheme` query.

## Development

- `yarn dev` -- serves example page on `localhost:8000` and watches for changes
- `yarn build` -- compiles and minifies into one file
- `yarn serve` -- serves example page
- `yarn watch` -- rebuilds on change in /src
