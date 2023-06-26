# JoneCSS

![Cloudflare](https://img.shields.io/website/https/jonecss.pages.dev?logo=cloudflarepages&label=CloudflarePages)
[![JsDelivr](https://badgen.net/badge/icon/jsdelivr?icon=jsdelivr&label)](https://www.jsdelivr.com/)
[![jsDelivr CDN](https://img.shields.io/jsdelivr/gh/hy/jonasfroeller/JoneCSS)](https://cdn.jsdelivr.net/gh/jonasfroeller/JoneCSS/jonecss.css)
[![gitHub license](https://badgen.net/github/license/jonasfroeller/JoneCSS)](https://github.com/jonasfroeller/JoneCSS/blob/master/LICENSE)
[![Buymeacoffee](https://badgen.net/badge/icon/buymeacoffee?icon=buymeacoffee&label)](https://buymeacoffee.com/jonasfroeller)

## Quick Start

Add the following css `<link>` to the `<head>` of your HTML document:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jonasfroeller/JoneCSS/jonecss.css">
```

Or download the file `./jonecss.css` and add it to your project:

```html
<link rel="stylesheet" href="./jonecss.css">
```

To prevent **jonecss.css** from overwriting your own styles, make sure to import it as the very first CSS import.

## Customization

You can customize the look and feel of **jonecss.css** by overwriting the CSS variables. For example, to change the primary color, add the following code to your own CSS file, or if you downloaded **jonecss.css**, just change the value in the file itself:

```css
:root {
    --primary-color: orange;
}
```
