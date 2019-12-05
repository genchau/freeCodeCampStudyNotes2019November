C01-S04-L01 - Responsive Web Design Certification - Applied Accessibility - Add a Text Alternative to Images for Visually Impaired Accessibility

```
<img src="doingKarateWow.jpeg" alt="Camper Cat is doing karate">
```

---

C01-S04-L02 - Responsive Web Design Certification - Applied Accessibility - Know When Alt Text Should be Left Blank

```
<img src="visualDecoration.jpeg" alt="">
```

Use empty string for decorative images or are described by contextual text.

---

C01-S04-L03 - Responsive Web Design Certification - Applied Accessibility - Use Headings to Show Hierarchical Relationships of Content

```

```

It is important for the heading tags in your markup to have semantic meaning and relate to each other.

h1: Only 1 per page, mainly as a title.
h2 >> h3 >> h4 >> h5 >> h6. Do not skip headings, it’s confusing to other a11y users.

---

C01-S04-L04 - Responsive Web Design Certification - Applied Accessibility - Jump Straight to the Content Using the main Element

```

```

These tags include main, header, footer, nav, article, and section, among others. Different tags carry semantic values which can help assistive technology users.

"Jump to Main Content" link at the top of a page,

---

C01-S04-L05 - Responsive Web Design Certification - Applied Accessibility - Wrap Content in the article Element

```
<div> - groups content
<section> - groups related content
<article> - groups independent, self-contained content
```

---

C01-S04-L06 - Responsive Web Design Certification - Applied Accessibility - Make Screen Reader Navigation Easier with the header Landmark

```
NA
```

The next HTML5 element that adds semantic meaning and improves accessibility is the header tag. It's used to wrap introductory information or navigation links for its parent tag and works well around content that's repeated at the top on multiple pages.

---

C01-S04-L07 - Responsive Web Design Certification - Applied Accessibility - Make Screen Reader Navigation Easier with the nav Landmark

```
NA
```

The nav element is another HTML5 item with the embedded landmark feature for easy screen reader navigation. This tag is meant to wrap around the main navigation links in your page.

---

C01-S04-L08 - Responsive Web Design Certification - Applied Accessibility - Make Screen Reader Navigation Easier with the footer Landmark

```
NA
```

 It's primarily used to contain copyright information or links to related documents that usually sit at the bottom of a page.

---

C01-S04-L09 - Responsive Web Design Certification - Applied Accessibility - Improve Accessibility of Audio Content with the audio Element

```
  <audio controls>
    <source src="https://s3.amazonaws.com/freecodecamp/screen-reader.mp3" type="audio/mpeg" />
  </audio>
```

---

C01-S04-L10 - Responsive Web Design Certification - Applied Accessibility - Improve Chart Accessibility with the figure Element

```
<figure>
  <img src="roundhouseDestruction.jpeg" alt="Photo of Camper Cat executing a roundhouse kick">
  <br>
  <figcaption>
    Master Camper Cat demonstrates proper form of a roundhouse kick.
  </figcaption>
</figure>
```

---

C01-S04-L11 - Responsive Web Design Certification - Applied Accessibility - Improve Form Field Accessibility with the label Element

```
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
</form>
```

The value of the for attribute must be the same as the value of the id attribute of the form control. 

---

C01-S04-L12 - Responsive Web Design Certification - Applied Accessibility - Wrap Radio Buttons in a fieldset Element for Better Accessibility

```
<form>
  <fieldset>
    <legend>Choose one of these three items:</legend>
    <input id="one" type="radio" name="items" value="one">
    <label for="one">Choice One</label><br>
    <input id="two" type="radio" name="items" value="two">
    <label for="two">Choice Two</label><br>
    <input id="three" type="radio" name="items" value="three">
    <label for="three">Choice Three</label>
  </fieldset>
</form>
```

![alt text][C01-S04-L12-I01]

---

C01-S04-L13 - Responsive Web Design Certification - Applied Accessibility - Add an Accessible Date Picker

```
<label for="input1">Enter a date:</label>
<input type="date" id="input1" name="input1">
```

---

C01-S04-L14 - Responsive Web Design Certification - Applied Accessibility - Standardize Times with the HTML5 datetime Attribute

```
The best day to host the vaunted Mortal Kombat tournament is <time datetime="2016-09-15">Thursday, September 15<sup>th</sup></time>.
```

---

C01-S04-L15 - Responsive Web Design Certification - Applied Accessibility - Make Elements Only Visible to a Screen Reader by Using Custom CSS

```
.sr-only {
  position: absolute;
  left: -10000px;
  width: 1px;
  height: 1px;
  top: auto;
  overflow: hidden;
}
```

---

C01-S04-L16 - Responsive Web Design Certification - Applied Accessibility - Improve Readability with High Contrast Text

```
NA
```

The Web Content Accessibility Guidelines (WCAG) recommend at least a 4.5 to 1 contrast ratio for normal text.

---

C01-S04-L17 - Responsive Web Design Certification - Applied Accessibility - Avoid Colorblindness Issues by Using Sufficient Contrast

```
NA
```

---

C01-S04-L18 - Responsive Web Design Certification - Applied Accessibility - Avoid Colorblindness Issues by Carefully Choosing Colors that Convey Information

```
NA
```

---

C01-S04-L19 - Responsive Web Design Certification - Applied Accessibility - Give Links Meaning by Using Descriptive Link Text

```
<a href="">Click here</a> for information about batteries
Click here for <a href="">information about batteries</a>
```

---

C01-S04-L20 - Responsive Web Design Certification - Applied Accessibility - Make Links Navigable with HTML Access Keys

```
<button accesskey="b">Important Button</button>
<a accesskey="g" id="first" href="#">
```

HTML offers the accesskey attribute to specify a shortcut key to activate or bring focus to an element. This can make navigation more efficient for keyboard-only users.

---

C01-S04-L21 - Responsive Web Design Certification - Applied Accessibility - Use tabindex to Add Keyboard Focus to an Element

```
  p:focus {
    background-color: yellow;
  }

tabindex="0"

```

This same functionality can be given to other elements, such as div, span, and p, by placing a tabindex="0"
Note: A negative tabindex value (typically -1) indicates that an element is focusable, but is not reachable by the keyboard. 
Bonus - using tabindex also enables the CSS pseudo-class :focus to work on the p tag.

![alt text][C01-S04-L21-I01]

---

C01-S04-L22 - Responsive Web Design Certification - Applied Accessibility - Use tabindex to Specify the Order of Keyboard Focus for Several Elements

```
<div tabindex="1">I get keyboard focus, and I get it first!</div>
<div tabindex="2">I get keyboard focus, and I get it second!</div>
```

Setting a tabindex="1" will bring keyboard focus to that element first. Then it cycles through the sequence of specified tabindex values (2, 3, etc.), before moving to default and tabindex="0" items.

---

[Table Of Contents](https://github.com/genchau/freeCodeCampStudyNotes2019November/blob/master/tableOfContents.md)

---

[C01-S04-L12-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S04-L12-I01.png "C01-S04-L12-I01"
[C01-S04-L21-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S04-L21-I01.png "C01-S04-L21-I01"

