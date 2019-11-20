C01-S03-L01 - Responsive Web Design Certification - Applied Visual Design - Create Visual Balance Using the text-align Property
```css
text-align: justify;
text-align: center;
text-align: right;
text-align: left;
```
---
C01-S03-L02 - Responsive Web Design Certification - Applied Visual Design - Adjust the Width of an Element Using the width Property
```
width: 220px;
```
---
C01-S03-L03 - Responsive Web Design Certification - Applied Visual Design - Adjust the Height of an Element Using the height Property
```
height: 20px;
```
---
C01-S03-L04 - Responsive Web Design Certification - Applied Visual Design - Use the strong Tag to Make Text Bold
```
font-weight: bold;
<strong>Stanford University</strong>
```
---
C01-S03-L05 - Responsive Web Design Certification - Applied Visual Design - Use the u Tag to Underline Text
```
<u>”Ph.D. students”</u>
```
---
C01-S03-L06 - Responsive Web Design Certification - Applied Visual Design - Use the em Tag to Italicize Text
```
<em>Italicize</em>
```
---
C01-S03-L07 - Responsive Web Design Certification - Applied Visual Design - Use the s Tag to Strikethrough Text
```
<s>Google</s>Alphabet
```
---
C01-S03-L08 - Responsive Web Design Certification - Applied Visual Design - Create a Horizontal Line Using the hr Element
```
<hr>
```
---
C01-S03-L09 - Responsive Web Design Certification - Applied Visual Design - Adjust the background-color Property of Text
```
background-color: rgba(45, 45, 45, 0.1);
```

rgba stands for:
  r = red (0-255)
  g = green (0-255)
  b = blue (0-255)
  a = alpha/level of opacity(1-opaque to 0-transparent)
  
---
C01-S03-L10 - Responsive Web Design Certification - Applied Visual Design - Adjust the Size of a Header Versus a Paragraph Tag
```
font-size: 27px;
```
---
C01-S03-L11 - Responsive Web Design Certification - Applied Visual Design - Add a box-shadow to a Card-like Element
```
box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
```
box-shadow: offset-x offset-y blur-radius(optional) spread-radius(optional) color, add-additional-box-shadows-with-comma

---
C01-S03-L12 - Responsive Web Design Certification - Applied Visual Design - Decrease the Opacity of an Element
```
opacity: 0.7;
```
---
C01-S03-L13 - Responsive Web Design Certification - Applied Visual Design - Use the text-transform Property to Make Text Uppercase
```
text-transform: uppercase;
```
|Value|Result|
|---:|---|
|lowercase|	"transform me"|
|uppercase|	"TRANSFORM ME"|
|capitalize|	"Transform Me"|
|initial|	Use the default value|
|inherit|	Use the text-transform value from the parent element|
|none|	Default: Use the original text|

---
C01-S03-L14 - Responsive Web Design Certification - Applied Visual Design - Set the font-size for Multiple Heading Elements
```
    h1 {
        font-size: 68px;
    }
```
---
C01-S03-L15 - Responsive Web Design Certification - Applied Visual Design - Set the font-weight for Multiple Heading Elements
```
font-weight: 1000;
```
font-weight controls the thickness of characters. Try 0-1000. 

---
C01-S03-L16 - Responsive Web Design Certification - Applied Visual Design - Set the font-size of Paragraph Text
N/A

---
C01-S03-L17 - Responsive Web Design Certification - Applied Visual Design - Set the line-height of Paragraphs
```
line-height: 25px;
```
It seems to affect the height from bottom only. Meaning it’s adding padding to bottom.

---
C01-S03-L18 - Responsive Web Design Certification - Applied Visual Design - Adjust the Hover State of an Anchor Tag
```
  a:hover {
    color: blue;
  }
```
With the pseudo-class hover we can change things as they are hovered over.

---
C01-S03-L19 - Responsive Web Design Certification - Applied Visual Design - Change an Element's Relative Position
```
  h2 {
    position: relative;
    top: 15px;
  }
```
CSS Box Model. 
Block-level item starts on new line. ie headings, paragraphs, divs.
Inline item sit within surrounding content. ie images, spans.

position:
top:
bottom:
left:
right:

---
C01-S03-L20 - Responsive Web Design Certification - Applied Visual Design - Move a Relatively Positioned Element with CSS Offsets
```
  h2 {
    position: relative;
    bottom: 10px;
    left: 15px;

  }
```

---
C01-S03-L21 - Responsive Web Design Certification - Applied Visual Design - Lock an Element to its Parent with Absolute Positioning
```
  #searchbar {
    position: absolute;
    top: 50px;
    right: 50px;
  }
```

---
C01-S03-L22 - Responsive Web Design Certification - Applied Visual Design - Lock an Element to the Browser Window with Fixed Positioning
```
  #navbar {
    position: fixed;
    top: 0px;
    left: 0px;
  }
```

---
C01-S03-L23 - Responsive Web Design Certification - Applied Visual Design - Push Elements Left or Right with the float Property
```
    #left {
      float: left;
      width: 50%;
    }
    #right {
      float: right;
      width: 40%;
    }
```

---
C01-S03-L24 - Responsive Web Design Certification - Applied Visual Design - Change the Position of Overlapping Elements with the z-index Property
```
  .first {
    background-color: red;
    position: absolute;
    z-index: 2;
  }
```
higher the z-index the higher it goes on the viewing stack.

---
C01-S03-L25 - Responsive Web Design Certification - Applied Visual Design - Center an Element Horizontally Using the margin Property
```
margin: auto;
```

---
C01-S03-L26 - Responsive Web Design Certification - Applied Visual Design - Learn about Complementary Colors
```
N/A
```
red (#FF0000) and cyan (#00FFFF)
green (#00FF00) and magenta (#FF00FF)
blue (#0000FF) and yellow (#FFFF00)

---
C01-S03-L27 - Responsive Web Design Certification - Applied Visual Design - Learn about Tertiary Colors
```
N/A
```
orange	#FF7F00
cyan	#00FFFF
raspberry	#FF007F

---
C01-S03-L28 - Responsive Web Design Certification - Applied Visual Design - Adjust the Color of Various Elements to Complementary Colors
```
N/A
```
teal (#09A7A1) as the dominant color, 
orange (#FF790E) as the complement color.

![alt text][C01-S03-L28-I01]

---
C01-S03-L29 - Responsive Web Design Certification - Applied Visual Design - Adjust the Hue of a Color
```
hsl(140,50%,50%);
```
hue: 0-360
saturation: amount of gray. 0 to 100%. 100% (no gray)
lightness: amount of white or black. 0%(black), 50%(normal), 100%(white)

![alt text][C01-S03-L29-I01]

---
C01-S03-L30 - Responsive Web Design Certification - Applied Visual Design - Adjust the Tone of a Color
```
  header {
    background-color: hsl(180, 90%, 35%);
    color: #FFFFFF;
  }

  nav {
    background-color: hsl(180,80%,25%);
  }
```
We can adjust color schemes with the hsl() option by using the same hue, but changing saturation and lightness for tone adjustment.

---
C01-S03-L31 - Responsive Web Design Certification - Applied Visual Design - Create a Gradual CSS Linear Gradient
```
background: linear-gradient(90deg, red, yellow, rgb(204, 204, 255));
```
background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);

![alt text][C01-S03-L31-I01]

---
C01-S03-L32 - Responsive Web Design Certification - Applied Visual Design - Use a CSS Linear Gradient to Create a Striped Element
```css
background: repeating-linear-gradient(
      45deg,
      yellow 0px,
      yellow 40px,
      black 40px,
      black 80px
    );
```

![alt text][C01-S03-L32-I01]

---
C01-S03-L33 - Responsive Web Design Certification - Applied Visual Design - Create Texture by Adding a Subtle Pattern as a Background Image
```
<style>
  body {
    background: url(https://cdn-media-1.freecodecamp.org/imgr/MJAkxbh.png);
  }
</style>
```

![alt text][C01-S03-L33-I01]

---
C01-S03-L34 - Responsive Web Design Certification - Applied Visual Design - Use the CSS Transform scale Property to Change the Size of an Element
```
  #ball2 {
    left: 65%;
    transform: scale(1.5);
  }
```

---
C01-S03-L35 - Responsive Web Design Certification - Applied Visual Design - Use the CSS Transform scale Property to Scale an Element on Hover
```
p:hover {
  transform: scale(2.1);
}
```

---
C01-S03-L36 - Responsive Web Design Certification - Applied Visual Design - Use the CSS Transform Property skewX to Skew an Element Along the X-Axis
```
p {
  transform: skewX(-32deg);
}
```

---
C01-S03-L37 - Responsive Web Design Certification - Applied Visual Design - Use the CSS Transform Property skewY to Skew an Element Along the Y-Axis
```
  #top {
    background-color: red;
    transform: skewY(-10deg);
  }
```

![alt text][C01-S03-L37-I01]

---
C01-S03-L38 - Responsive Web Design Certification - Applied Visual Design - Create a Graphic Using CSS
```
  .center {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100px;
    height: 100px;
    background-color: transparent;
    border-radius: 50%;
    box-shadow: 25px 10px 0 0 blue;
  }
```

![alt text][C01-S03-L38-I01]

---
C01-S03-L39 - Responsive Web Design Certification - Applied Visual Design - Create a More Complex Shape Using CSS and HTML
```
<style>
  .heart {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background-color: pink;
    height: 50px;
    width: 50px;
    transform: rotate(-45deg);
  }
  .heart::after {
    background-color: red;
    content: "after";
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: 0px;
    left: 25px;
  }
  .heart::before {
    content: "before";
    background-color: blue;
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: -25px;
    left: 0px;
  }
</style>
<div class="heart"></div>
```

![alt text][C01-S03-L39-I01]

---
C01-S03-L40 - Responsive Web Design Certification - Applied Visual Design - Learn How the CSS @keyframes and animation Properties Work
```
#anim {
  animation-name: colorful;
  animation-duration: 3s;
}

@keyframes colorful {
  0% {
    background-color: blue;
  }
  100% {
    background-color: yellow;
  }
}
```

---
C01-S03-L41 - Responsive Web Design Certification - Applied Visual Design - Use CSS Animation to Change the Hover State of a Button
```
  button:hover {
    animation-name: background-color;
    animation-duration: 500ms;
  }

  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }
```

---
C01-S03-L42 - Responsive Web Design Certification - Applied Visual Design - Modify Fill Mode of an Animation
```
  button:hover {
    animation-name: background-color;
    animation-duration: 500ms;
    animation-fill-mode: forwards;
  }
  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }
```

---
C01-S03-L43 - Responsive Web Design Certification - Applied Visual Design - Create Movement Using CSS Animation
```
  #rect {
    animation-name: rainbow;
    animation-duration: 4s;
    animation-fill-mode: forwards;
  }

  @keyframes rainbow {
    0% {
      background-color: blue;
      top: 0px;

    }
    50% {
      background-color: green;
      top: 50px;

    }
    100% {
      background-color: yellow;
      top: 0px;

    }
  }
```

---
C01-S03-L44 - Responsive Web Design Certification - Applied Visual Design - Create Visual Direction by Fading an Element from Left to Right
```
  @keyframes fade {
    50% {
      left: 60%;
      opacity: 0.1;
    }
  }
```

---
C01-S03-L45 - Responsive Web Design Certification - Applied Visual Design - Animate Elements Continually Using an Infinite Animation Count
```
animation-iteration-count: 3;
animation-iteration-count: infinite;
```

---
C01-S03-L46 - Responsive Web Design Certification - Applied Visual Design - Make a CSS Heartbeat using an Infinite Animation Count
```
N/A
```

---
C01-S03-L47 - Responsive Web Design Certification - Applied Visual Design - Animate Elements at Variable Rates
```
  @keyframes twinkle-1 {
    50% {
      transform: scale(0.5);
      opacity: 0.5;
    }
  }

  @keyframes twinkle-2 {
    20% {
      transform: scale(0.5);
      opacity: 0.5;
    }
  }
```

---
C01-S03-L48 - Responsive Web Design Certification - Applied Visual Design - Animate Multiple Elements at Variable Rates
```
  .star-1 {
    margin-top: 15%;
    margin-left: 60%;
    animation-duration: 1s;
    animation-name: twinkle;
  }

  .star-2 {
    margin-top: 25%;
    margin-left: 25%;
    animation-duration: 0.9s;
    animation-name: twinkle;
  }

  .star-3 {
    margin-top: 10%;
    margin-left: 50%;
    animation-duration: 1.1s;
    animation-name: twinkle;
  }
```

---
C01-S03-L49 - Responsive Web Design Certification - Applied Visual Design - Change Animation Timing with Keywords
```
  #ball1 {
    left:27%;
    animation-timing-function: linear;
  }
  #ball2 {
    left:56%;
    animation-timing-function: ease-out;
  }
```
option: ease, ease-out, ease-in, linear.

---
C01-S03-L50 - Responsive Web Design Certification - Applied Visual Design - Learn How Bezier Curves Work
```
animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
```

![alt text][C01-S03-L50-I01]

---
C01-S03-L51 - Responsive Web Design Certification - Applied Visual Design - Use a Bezier Curve to Move a Graphic
```
animation-timing-function: cubic-bezier(0, 0, 0.58, 1);
animation-timing-function: ease-out;
```

---
C01-S03-L52 - Responsive Web Design Certification - Applied Visual Design - Make Motion More Natural Using a Bezier Curve
```
animation-timing-function: cubic-bezier(0.311, 0.441, 0.444, 1.649); //juggling motion
```

---
[C01-S03-L28-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L28-I01.png "C01-S03-L28-I01"
[C01-S03-L29-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L29-I01.png "C01-S03-L29-I01"
[C01-S03-L31-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L31-I01.png "C01-S03-L31-I01"
[C01-S03-L32-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L32-I01.png "C01-S03-L32-I01"
[C01-S03-L33-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L33-I01.png "C01-S03-L33-I01"
[C01-S03-L37-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L37-I01.png "C01-S03-L37-I01"
[C01-S03-L38-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L38-I01.png "C01-S03-L38-I01"
[C01-S03-L39-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L39-I01.png "C01-S03-L39-I01"
[C01-S03-L50-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S03-L50-I01.png "C01-S03-L50-I01"
