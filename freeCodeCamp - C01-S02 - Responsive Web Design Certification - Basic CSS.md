C01-S02-L01 - Responsive Web Design Certification - Basic CSS - Change the Color of Text

```
<h2 style="color: red;">CatPhotoApp</h2>
```

---

C01-S02-L02 - Responsive Web Design Certification - Basic CSS - Use CSS Selectors to Style Elements

```
<style>
  h2 {
    color: blue;
  }
</style>
```

---

C01-S02-L03 - Responsive Web Design Certification - Basic CSS - Use a CSS Class to Style an Element

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
```

---

C01-S02-L04 - Responsive Web Design Certification - Basic CSS - Style Multiple Elements with a CSS Class

```
<p class="red-text">
```

---

C01-S02-L05 - Responsive Web Design Certification - Basic CSS - Change the Font Size of an Element

```
  p {
    font-size: 16px;
  }
```

---

C01-S02-L06 - Responsive Web Design Certification - Basic CSS - Set the Font Family of an Element

```
  p {
    font-size: 16px;
    font-family: monospace;
  }
```

---

C01-S02-L07 - Responsive Web Design Certification - Basic CSS - Import a Google Font

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

  h2 {
    font-family: lobster;
  }
```

---

C01-S02-L08 - Responsive Web Design Certification - Basic CSS - Specify How Fonts Should Degrade

```
font-family: Lobster, monospace;
```

---

C01-S02-L09 - Responsive Web Design Certification - Basic CSS - Size Your Images

```
  .smaller-image {
    width: 100px;
  }
```

---

C01-S02-L10 - Responsive Web Design Certification - Basic CSS - Add Borders Around Your Elements

```
  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
  }

class="smaller-image thick-green-border"
```

---

C01-S02-L11 - Responsive Web Design Certification - Basic CSS - Add Rounded Corners with border-radius

```
  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 10px;
  }
```

---

C01-S02-L12 - Responsive Web Design Certification - Basic CSS - Make Circular Images with a border-radius

```
border-radius: 50%;
```

---

C01-S02-L13 - Responsive Web Design Certification - Basic CSS - Give a Background Color to a div Element

```
  .silver-background {
    background-color: silver;
  }
```

---

C01-S02-L14 - Responsive Web Design Certification - Basic CSS - Set the id of an Element

```
  <form id="cat-photo-form" action="/submit-cat-photo">
```

---

C01-S02-L15 - Responsive Web Design Certification - Basic CSS - Use an id Attribute to Style an Element

```
  #cat-photo-form {
    background-color: green;
  }
```

---

C01-S02-L16 - Responsive Web Design Certification - Basic CSS - Adjust the Padding of an Element

```
  .blue-box {
    background-color: blue;
    color: #fff;
    padding: 20px;
  }
```

---

C01-S02-L17 - Responsive Web Design Certification - Basic CSS - Adjust the Margin of an Element

```
margin: 20px;
```

---

C01-S02-L18 - Responsive Web Design Certification - Basic CSS - Add a Negative Margin to an Element

```
margin: -15px;
```

---

C01-S02-L19 - Responsive Web Design Certification - Basic CSS - Add Different Padding to Each Side of an Element

```
    padding-top: 40px;
    padding-right: 20px;
    padding-bottom: 20px;
    padding-left: 40px;
```

---

C01-S02-L20 - Responsive Web Design Certification - Basic CSS - Add Different Margins to Each Side of an Element

```
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
    margin-left: 40px;
```

---

C01-S02-L21 - Responsive Web Design Certification - Basic CSS - Use Clockwise Notation to Specify the Padding of an Element

```
padding: 40px 20px 20px 40px;
```

These four values work like a clock: top, right, bottom, left.

---

C01-S02-L22 - Responsive Web Design Certification - Basic CSS - Use Clockwise Notation to Specify the Margin of an Element

```
margin: 40px 20px 20px 40px;
```

---

C01-S02-L23 - Responsive Web Design Certification - Basic CSS - Use Attribute Selectors to Style Elements

```
  [type="checkbox"] {
    margin: 10px 0px 15px 0px;
  }
```

---

C01-S02-L24 - Responsive Web Design Certification - Basic CSS - Understand Absolute versus Relative Units

```
padding: 1.5em;
```

Relative units, such as em or rem, are relative to another length value. For example, em is based on the size of an element's font. If you use it to set the font-size property itself, it's relative to the parent's font-size.

---

C01-S02-L25 - Responsive Web Design Certification - Basic CSS - Style the HTML Body Element

```
<style>
    body {
        background-color: black;
    }
</style>
```

We can prove that the body element exists here by giving it a background-color of black.

---

C01-S02-L26 - Responsive Web Design Certification - Basic CSS - Inherit Styles from the Body Element

```
<style>
  body {
    background-color: black;
    color: green;
    font-family: monospace;
  }

</style>

<h1>Hello World</h1>
```

---

C01-S02-L27 - Responsive Web Design Certification - Basic CSS - Prioritize One Style Over Another

```
NA
```

Our "pink-text" class overrode our body element's CSS declaration!

---

C01-S02-L28 - Responsive Web Design Certification - Basic CSS - Override Styles in Subsequent CSS

```
<h1 class="pink-text blue-text">Hello World!</h1>
```

blue-text wins out because it’s declared last in the style section.

Note: It doesn't matter which order the classes are listed in the HTML element.

However, the order of the class declarations in the <style> section are what is important. The second declaration will always take precedence over the first. Because .blue-text is declared second, it overrides the attributes of .pink-text

---

C01-S02-L29 - Responsive Web Design Certification - Basic CSS - Override Class Declarations by Styling ID Attributes

```
  #orange-text {
    color: orange;
  }

```

Note: It doesn't matter whether you declare this CSS above or below pink-text class, since id attribute will always take precedence.

---

C01-S02-L30 - Responsive Web Design Certification - Basic CSS - Override Class Declarations with Inline Styles

```
NA
```

Inline styles override CSS.

---

C01-S02-L31 - Responsive Web Design Certification - Basic CSS - Override All Other Styles by using Important

```
  .pink-text {
    color: pink !important;
  }
```

---

C01-S02-L32 - Responsive Web Design Certification - Basic CSS - Use Hex Code for Specific Colors

```
background-color: #000000; // black
```

---

C01-S02-L33 - Responsive Web Design Certification - Basic CSS - Use Hex Code to Mix Colors

```
NA
```

To review, hex codes use 6 hexadecimal digits to represent colors, two each for red (R), green (G), and blue (B) components.

From these three pure colors (red, green, and blue), we can vary the amounts of each to create over 16 million other colors!

For example, orange is pure red, mixed with some green, and no blue. In hex code, this translates to being #FFA500.

The digit 0 is the lowest number in hex code, and represents a complete absence of color.

The digit F is the highest number in hex code, and represents the maximum possible brightness.

---

C01-S02-L34 - Responsive Web Design Certification - Basic CSS - Use Abbreviated Hex Code

```
NA
```

For example, red's hex code #FF0000 can be shortened to #F00. This shortened form gives one digit for red, one digit for green, and one digit for blue.

---

C01-S02-L35 - Responsive Web Design Certification - Basic CSS - Use RGB values to Color Elements

```
NA
```

Another way you can represent colors in CSS is by using RGB values.

The RGB value for black looks like this:

rgb(0, 0, 0)

The RGB value for white looks like this:

rgb(255, 255, 255)

---

C01-S02-L36 - Responsive Web Design Certification - Basic CSS - Use RGB to Mix Colors

```
<style>
  .red-text {
    color: rgb(255, 0, 0);
  }
  .orchid-text {
    color: rgb(218, 112, 214);
  }
  .sienna-text {
    color: rgb(160, 82, 45);
  }
  .blue-text {
    color: rgb(0, 0, 255);
  }
</style>
```

---

C01-S02-L37 - Responsive Web Design Certification - Basic CSS - Use CSS Variables to change several elements at once

```
    /* change code below */
    --penguin-skin: gray;
    --penguin-belly: white;
    --penguin-beak: orange;
    /* change code above */

background: var(--penguin-skin, gray);
background: var(--penguin-belly, white);
background: var(--penguin-beak, orange);
```

---

C01-S02-L38 - Responsive Web Design Certification - Basic CSS - Create a custom CSS Variable

```
--penguin-skin: gray;
```

---

C01-S02-L39 - Responsive Web Design Certification - Basic CSS - Use a custom CSS Variable

```
background: var(--penguin-skin, gray);
```

---

C01-S02-L40 - Responsive Web Design Certification - Basic CSS - Attach a Fallback value to a CSS Variable

```
background: var(--pengiun-skin, black);
```

---

C01-S02-L41 - Responsive Web Design Certification - Basic CSS - Improve Compatibility with Browser Fallbacks

```
  .red-box {
    background: red;
    background: var(--red-color);
    height: 200px;
    width:200px;
  }
```

Not all browser supports CSS variables. It’s good practice to incorporate compatibility.

---

C01-S02-L42 - Responsive Web Design Certification - Basic CSS - Inherit CSS Variables

```
  :root {
    --penguin-belly: pink;
  }
```

When you create a variable, it is available for you to use inside the selector in which you create it. It also is available in any of that selector's descendants. This happens because CSS variables are inherited, just like ordinary properties.

To make use of inheritance, CSS variables are often defined in the :root element.

---

C01-S02-L43 - Responsive Web Design Certification - Basic CSS - Change a variable for a specific area

```
NA
```

When you create your variables in :root they will set the value of that variable for the whole page.

You can then over-write these variables by setting them again within a specific element.

---

C01-S02-L44 - Responsive Web Design Certification - Basic CSS - Use a media query to change a variable

```
  @media (max-width: 350px) {
    :root {
      --penguin-size: 200px;
      --penguin-skin: black;
    }
  }
```

---

[Table Of Contents](https://github.com/genchau/freeCodeCampStudyNotes2019November/blob/master/tableOfContents.md)

---
