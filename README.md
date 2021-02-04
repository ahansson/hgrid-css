# hgrid-css

### TEST UPLOAD. THIS INFO IS NOT UP TO DATE

### A lightweight desktop-first css utility kit.

Import hgrid.scss at the top of your main.scss file in order to use hgrid in a custom project, or import the minified css file in your html (link below). Changes to hgrid must be pushed back to this repository by way of a pull request. Only improvements that are non-specific and can be reused in any project will be accepted.

## Demo

[Demo page for reference](https://kubo.no/hgrid/demo/index.html)

_May not be accurate at all times_


## Versions

### v1.3.0

Revisioned version

### v1.2.x

[Minified CSS](https://kubo.no/hgrid/dist/css/hgrid-1.2.min.css)

[Minified FULL CSS](https://kubo.no/hgrid/dist/css/hgrid-full-1.2.min.css) (includes page loader and mobile menu/hamburger icon)

*Changelog:*

29.05.2020: Add utility class for flex-wrap


### v1.1.

[Minified CSS](https://kubo.no/hgrid/dist/css/hgrid.min.css)

[Minified FULL CSS](https://kubo.no/hgrid/dist/css/hgrid-full.min.css) (includes page loader and mobile menu/hamburger icon)

## How to run

Point your terminal to the hgrid folder and start compiling the .scss files in the hgrid module with this command: `npm run compile:sass` (will call the corresponding script in package.json). Changes will compile to CSS automatically or on file save, depending on your setup. 

Minify each regular CSS file and place the end result in the `dist/css` folder with the minify-scripts found in `package.json`. Or build everything at once with `npm run build:css`.

Concatenate the modules you want into one minified file with variations of `npm run concat-full-dist`. Upload the relevant files to `kubo.no/hgrid/demo/` and `/dist/` (use versioning!).

## Author

Atle Hansson @ https://kubo.no