# Coding Cheatsheet

<details>
  <summary>HTML template with CSS and JS files</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Deferred JS file -->
    <script defer src="./main.js"></script>
    <!-- CSS file -->
    <link rel="stylesheet" href="./style.css" />
    <title>Document</title>
  </head>

  <body></body>
</html>
```

</details>

<details>
  <summary>CSS reset</summary>

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

</details>

<details>
  <summary>Center elements with CSS</summary>

[CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

```html
<div id="parent">
  <div class="child"></div>
  <div class="child"></div>
  <div class="child"></div>
</div>
```

```css
#parent {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

</details>

<details>
  <summary>Class vs ID element selector</summary>
  
[Different types of selectors
](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics#different_types_of_selectors)

```html
<div id="i-am-id"></div>
<div class="i-am-class"></div>
```

```css
#i-am-id {
  background-color: red;
}

.i-am-class {
  background-color: blue;
}
```

</details>

<details>
  <summary>CSS functions</summary>

[CSS functions documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions)

Example:

```css
#element {
  /* 
    Between 100px and 5vw select maximum.

    If 5vw will be equal to 530px (or anything greater than 100px) then width will be 5vw(530ppx)
    If 5vw will be equal to 98px (or anything less than 100px) then width will be 100px
  */
  width: max(100px, 5vw);

  /* 
    Between 50vh and 50vw select minimum.
    Same as with maximum. It will check what is smaller in the current viewport and set height to the minimum of both
  */
  height: min(50vh, 50vw);
}
```

</details>

<details>
  <summary>Image cover vs contain</summary>

[Background-size documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/background-size)

Example:

```html
<img src="https://some-image-url.com" />
```

```css
/*
  Stretches the shorter side of the image to fit the container.
  Cuts out the longer side if it's outside the container
*/
img {
  background-size: cover;
}
```

![Image](./assets/cover.png)

```css
/*
  Stretches the longer side of the image to fit the container.
  Proportionally scale down the shorter size (keeps image proportions)
*/
img {
  background-size: contain;
}
```

![Image](./assets/contain.png)

</details>

<details>
  <summary>Where to look for help</summary>

[Google](https://www.google.com/search?q=How+to+%3Cask+your+question+here%3E&sca_esv=ba63e9e5b9d099c8&ei=0yjiZeSfCYbL0PEP3qeuyAM&ved=0ahUKEwik1b_b4tOEAxWGJTQIHd6TCzkQ4dUDCBA&uact=5&oq=How+to+%3Cask+your+question+here%3E&gs_lp=Egxnd3Mtd2l6LXNlcnAiH0hvdyB0byA8YXNrIHlvdXIgcXVlc3Rpb24gaGVyZT5I4C1QAFiFKXAAeAGQAQGYAWqgAZYOqgEEMzAuMbgBA8gBAPgBAZgCD6ACjgjCAgsQLhiABBjHARjRA8ICBRAAGIAEwgIFEC4YgATCAhoQLhiABBjHARjRAxiXBRjcBBjeBBjgBNgBAcICCBAuGIAEGNQCwgIKEAAYgAQYRhj7AcICFhAAGIAEGEYY-wEYlwUYjAUY3QTYAQLCAiMQLhiABBjUAhiXBRjcBBjeBBjgBBj0AxjxAxj1Axj2A9gBAcICBxAAGIAEGAqYAwC6BgYIARABGBS6BgYIAhABGBOSBwQxMy4yoAeHvwE&sclient=gws-wiz-serp)

[CSS Trick](https://css-tricks.com/almanac/)

[MDN Web Docs](https://developer.mozilla.org/en-US/)

[Stack overflow](https://stackoverflow.com/)

</details>
