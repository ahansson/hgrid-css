<div align="center">
<br>
<img src="https://hgrid.io/assets/img/icon.png" alt="hgrid logo icon" title="hgrid logo icon" width="270">
<br>

# hgrid-css

## **A Lightweight and Practical CSS Utility Kit.**

### Zero Config. Flat Learning Curve.

**Hgrid** is a starting point intended to make HTML work out of the box. It's not a UI framework, but provides sensible defaults so you can start prototyping without having to deal with browser quirks, unstyled elements and basic responsivity.

</div>

## Documentation

Website: [https://hgrid.io](https://hgrid.io)

## Versions

Latest: **0.6.1-beta**

See [releases](https://github.com/ahansson/hgrid-css/releases) on GitHub.
<br><br>

## How to install

### **As a node module:**

```bash
npm install hgrid-css --save-dev
```

```bash
yarn add hgrid-css --dev
```

### **Then, @use as Sass in your project:**

```scss
@use 'hgrid-css/sass/hgrid' with (

  // example customization

  $link-color: #ffe88d,
  $link-color-hover: #fff0b4,
  $container-max-width: 1600px,
  $link-underline-color: #ffe88d
);
```
For detailed information with step by step recipes on how to integrate **hgrid** in different JS frameworks, please refer to [the documentation](https://hgrid.io/documentation/integrate/).

### **From local file or CDN:**

```html
<head>
  <link rel="stylesheet" href="/path/to/hgrid-css/hgrid.min.css">
  <!-- CDN: <link rel="stylesheet" href="https://unpkg.com/hgrid-css@latest/dist/hgrid.min.css"> -->

  <!-- more css below -->
</head>
```
### **@import into your stylesheet:**
```css
/* From node_modules */
@import './../etc./node_modules/hgrid-css/dist/hgrid.min.css';
```
```css
/* From CDN */
@import 'https://unpkg.com/hgrid-css@latest/dist/hgrid.min.css';
```

## Local development

_Requires Node.js installed on your system._

Run `npm install`.

Start compiling **hgrid's** `.scss` files to `.css` with the command `npm run watch` from the root of the **hgrid** folder. Any changes you make to files in the `/sass` folder will result in css and map files being updated in the `/dist` folder.

To produce the compiled, prefixed and minified **hgrid** output, use `npm run build`. It uses Autoprefixer to add some backwards compatibility before minifying the result as `hgrid.min.css`.

See [hgrid.io/documentation/](https://hgrid.io/documentation/) for complete usage instructions.

## Author

Atle Hansson @ https://kubo.no

## License

MIT