## BASIC THEORY:

### Connect files (index, style, main)

Create a folder with:

- index.html
- style.css
- main.js

Add this HTML template into the HTML file

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- JS link will go here-->
    <!-- CSS link will go here -->
    <title>Document</title>
  </head>
  <body></body>
</html>
```

To link CSS file to the HTML file add this line above the title tag

```html
<link rel="stylesheet" href="./style.css" />
```

To link JS file to the HTML file add this line above the CSS link

```html
<script defer src="./main.js"></script>
```

<details>
  <summary>See the end result:</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script defer src="./main.js"></script>
    <link rel="stylesheet" href="./style.css" />
    <title>Document</title>
  </head>

  <body></body>
</html>
```

</details>

### Basic HTML tags

### Inline vs block

### Class vs ID vs inline style

### Shape changing (border radius)

### px vs v-units

### absolute position

### css functions

### image cover vs contain
