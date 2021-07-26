![Logo](https://github.com/markocupic/markocupic/blob/main/logo.png)

# Contao Component Bootstrap
Stores the Bootstrap Package in `assets/contao-component-bootstrap`

## Embed bootstrap in your custom sass file
f.ex if your main.scss is located in `files/mytheme/scss/main.scss` you can import bootstrap like this:

```
/**
 files/mytheme/scss/main.scss
 **/

// Import the bootstrap component from the assets directory
@import "../../../assets/contao-component-bootstrap/bootstrap/scss/bootstrap.scss";

// Import some other custom style definitions
@import "base/page";
@import "base/layout";
@import "base/type";
// etc.

```
