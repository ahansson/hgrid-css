# hgrid-css

### WORK IN PROGRESS

⚠️ _Documentation may be incomplete or inaccurate._

### **A Lightweight and Practical CSS Utility Kit.**

### Zero Config. Flat Learning Curve

Hgrid is not a UI framework, but a starting point intended to make HTML work out of the box. It provides some sensible defaults so you can start prototyping without having to deal with browser quirks, unstyled elements and basic responsivity.

## Documentation

Website: [https://hgrid.io](https://hgrid.io)

## Versions

Latest: **0.5.0-beta**

See [releases](https://github.com/ahansson/hgrid-css/releases) on GitHub.
<br><br>

## How to install

**As a packet:**

```bash
npm install hgrid-css --save-dev
```

```
yarn add hgrid-css --dev
```

**From local file or CDN:**

```html
<head>
  <link rel="stylesheet" href="/path/to/hgrid-css/hgrid.min.css">
  <!-- CDN: <link rel="https://unpkg.com/hgrid-css@latest/dist/hgrid.min.css"> -->

  <!-- more css below -->
</head>
```
**@import into your stylesheet:**
```css
/* From node_modules */
@import './../etc./node_modules/hgrid-css/dist/hgrid.min.css';
```
```css
/* From CDN */
@import 'https://unpkg.com/hgrid-css@latest/dist/hgrid.min.css';
```

**@use with Sass**

```scss
@use 'hgrid-css/sass/hgrid' with (

  // example customization

  $link-color: #ffe88d,
  $link-color-hover: #fff0b4,
  $container-max-width: 1600px,
  $link-underline-color: #ffe88d
);
```
For detailed information on how to integrate **hgrid** in your Node driven frontend framework, please refer to [the documentation](https://hgrid.io/documentation/integrate/).

## Local development

_Requires nodejs with npm installed on your system._

Run `npm install`.

Start compiling `.scss` files to `.css` with the terminal command `npm run watch` from the root of the hgrid folder. Any changes you make to files in the `/sass` folder will result in css and map files being updated in the `/dist` folder.

To produce the minified **hgrid** file, use `npm run build`. It uses Autoprefixer to add some backwards compatibility before minifying the result as `hgrid.min.css`.

As always, see [hgrid.io](https://hgrid.io) for details on how to integrate **hgrid** as Sass or plain CSS in your projects.

## Author

Atle Hansson @ https://kubo.no