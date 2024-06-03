# Standard CSS Project

This repository contains a standard CSS file that can be reused in various projects. It defines some basic styles and best practices that help maintain consistency and performance across your web pages.

## Contents of CSS File

The included CSS file in the repository contains the following styles:

### Basic Reset

```css
* {
    padding: 0;
    margin: 0;
    border: 0;
    outline: none;
    box-sizing: border-box;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

This block of code applies a basic reset to all elements (*):

* padding: 0; and margin: 0;: Removes default padding and margins from all elements.
* border: 0; and outline: none;: Removes default borders and outlines.
* box-sizing: border-box;: Sets the box model to include padding and border in the element's total width and height, facilitating layout control.
* -webkit-font-smoothing: antialiased; and -moz-osx-font-smoothing: grayscale;: Improves font rendering across different operating systems.

### Root Definitions

```css
:root {
    font-size: 65.5%;
}
```

The :root selector defines global variables for the document:

* font-size: 65.5%;: Sets the base font size to 10px, making it easier to use rems for font sizes and spacing.

### Body Styles

```css
body {
    font-size: 1.6rem;
}
```
The body selector defines basic styles for the document body:

* font-size: 1.6rem;: Sets the font size to 16px, which is a common choice to ensure readability.

## How to Use

To use this CSS file in your projects:

1. Clone this repository or download the CSS file.
2. nclude the CSS file in the <head> of your HTML document:

```html
<link rel="stylesheet" href="path/to/your/file.css">
```

## Contribution
Contributions are welcome! Feel free to open issues or pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.


## Browser Support
![Chrome](https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Firefox](https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Samsung Internet](https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png)
--- | --- | --- | --- | --- | --- |
88+ ✔ | 88+ ✔ | 84+ ✔ | 14+ ✔ | 75+ ✔ | 15+ ✔ |
