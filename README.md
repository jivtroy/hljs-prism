# Highlight.js Prism

Prism.js theme for Highlight.js library.

### Contents

1. [Compatibility](#compatibility)
2. [Installation](#installation)
   1. [NPM](#npm)
3. [Usage](#usage)
   1. [CDN](#cdn)
   2. [Local](#local)
4. [Author](#author)
5. [License](#license)

## Compatibility

Library | Version
------- | -------
Highlight.js | >= 11

## Installation

### NPM

```bash
npm install hljs-prism
```

## Usage

### CDN

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Highlight.js Prism</title>

    <!-- CSS -->
    <link href="https://cdn.jsdelivr.net/npm/hljs-prism/hljs-prism.css" rel="stylesheet">
  </head>
  <body>
    <pre>
      <code class="language-css">body { color: green; }</code>
    </pre>

    <!-- JS -->
    <script src="https://cdn.jsdelivr.net/gh/highlightjs/cdn-release@11.11.1/build/highlight.min.js"></script>
    <script>hljs.highlightAll();</script>
  </body>
</html>
```

### Local

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Highlight.js Prism</title>

    <!-- CSS -->
    <link href="css/hljs-prism.css" rel="stylesheet">
  </head>
  <body>
    <pre>
      <code class="language-css">body { color: green; }</code>
    </pre>

    <!-- JS -->
    <script src="js/highlight.min.js"></script>
    <script>hljs.highlightAll();</script>
  </body>
</html>
```

## Author

* [Dev](https://dev.to/jivtroy)
* [Medium](https://medium.com/@jivtroy)
* [YouTube](https://www.youtube.com/@jivtroy)

## License

This project is licensed under the **MIT License** - see the `LICENSE` file for details.
