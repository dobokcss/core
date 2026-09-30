# DobokCSS

[![Maintainer](http://img.shields.io/badge/maintainer-@estefanionsantos-blue.svg?style=flat-square)](https://estefanionsantos.github.io/)
[![Latest Version](https://img.shields.io/github/release/dobokcss/dobokcss.svg?style=flat-square)](https://github.com/dobokcss/dobokcss/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

# DobokCSS
Micro framework HTML for developing responsive, mobile project

#### Quick start
Looking to quickly add DobokCSS to your project? Use jsDelivr, a free open source CDN. Using a package manager or need to download the source files? [Head to the downloads page](https://github.com/dobokcss/core/releases).

#### CSS
Copy-paste the stylesheet `<link>` into your `<head>` before all other stylesheets to load our CSS architecture (Tokens, Reset, and Main Bundle).

```html
<!DOCTYPE HTML>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        
        <!-- Design Tokens (Legível para customização) -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dobokcss/core@2.0.0/dist/tokens.css" />
        
        <!-- Reset Module -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dobokcss/core@2.0.0/dist/reset.min.css" />
        
        <!-- DobokCSS Main Bundle -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dobokcss/core@2.0.0/dist/style.min.css" type="text/css" media="all" />

        <title>Dobok CSS</title>
    </head>
<body>

    <!-- content here -->

</body>
</html>
