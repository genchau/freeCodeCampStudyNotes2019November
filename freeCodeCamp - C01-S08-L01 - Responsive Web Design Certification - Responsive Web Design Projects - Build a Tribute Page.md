C01-S08-L01 - Responsive Web Design Certification - Responsive Web Design Projects - Build a Tribute Page

[Link to Code Pen Project 2019-12-04](https://codepen.io/genchau/pen/BayymvX)

HTML:

```
<!-- Starts with main -->
<main id="main"> <!-- User Story #1 -->
  <h1 id="title">Dr. Norman Borlaug</h1> <!-- User Story #2 -->
  <p>The man who saved a billion lives</p>

  <!-- Figure is used which allows image and figcaption -->
  <figure id="img-div"> <!-- User Story #3 -->
    <img
      id="image"
      src="https://c2.staticflickr.com/4/3689/10613180113_fdf7bcd316_b.jpg"
      alt="Dr. Norman Borlaug seen standing in Mexican wheat field with a group of biologists"
    /> <!-- User Story #4 -->
    <figcaption id="img-caption">
      Dr. Norman Borlaug, third from the left, trains biologists in Mexico on how
      to increase wheat yields - part of his life-long war on hunger.
    </figcaption> <!-- User Story #5 -->
  </figure>

  <!-- Using a section tag. -->
  <section id="tribute-info"> <!-- User Story #6 -->
    <h3 id="headline">Here's a time line of Dr. Borlaug's life:</h3>
    <ul>
      <li><strong>1914</strong> - Born in Cresco, Iowa</li>
      <li><strong>2009</strong> - dies at the age of 95.</li>
    </ul>

    <!-- blockquote -->
    <blockquote
      cite="http://news.rediff.com/report/2009/sep/14/pm-pays-tribute-to-father-of-green-revolution-borlaug.htm"
    >
      <p>
        "Borlaug's life and achievement are testimony to the far-reaching
        contribution that one man's towering intellect, persistence and
        scientific vision can make to human peace and progress."
      </p>
      <cite>-- Indian Prime Minister Manmohan Singh</cite>
    </blockquote>

    <!-- incorrect usage of h3, this looks more like a footer-->
    <h3>
      If you have time, you should read more about this incredible human being
      on his
      <a
        id="tribute-link"
        href="https://en.wikipedia.org/wiki/Norman_Borlaug"
        target="_blank"
        >Wikipedia entry</a
      >. <!-- User Story #7 -->
    </h3>

  </section>

</main>
```

CSS:

```
html {
  /* Setting a base font size of 10px give us easier rem calculations
     Info: 1rem === 10px, 1.5rem === 15px, 2rem === 20px and so forth
   */
  font-size: 10px;
}

body {
  /* Native font stack https://getbootstrap.com/docs/4.2/content/reboot/#native-font-stack */
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Helvetica Neue", Arial, sans-serif;
  font-size: 1.6rem;
  line-height: 1.5;
  text-align: center;
  color: #333;
  margin: 0;
}

h1 {
  font-size: 4rem;
  margin-bottom: 0;
}

@media (max-width: 460px) {
  h1 {
    font-size: 3.5rem;
    line-height: 1.2;
  }
}

h2 {
  font-size: 3.25rem;
}

a {
  color: #477ca7;
}

a:visited {
  color: #74638f;
}

#main {
  margin: 30px 8px;
  padding: 15px;
  border-radius: 5px;
  background: #eee;
}

@media (max-width: 460px) {
  #main {
    margin: 0;
  }
}

img { 
  max-width: 100%;
  display: block;
  height: auto;
  margin: 0 auto;
} // User Story #8 and 9

#img-div {
  background: white;
  padding: 10px;
  margin: 0;
}

#img-caption {
  margin: 15px 0 5px 0;
}

@media (max-width: 460px) {
  #img-caption {
    font-size: 1.4rem;
  }
}

#headline {
  margin: 50px 0;
  text-align: center;
}

ul {
  max-width: 550px;
  margin: 0 auto 50px auto;
  text-align: left;
  line-height: 1.6;
}

li {
  margin: 16px 0;
}

blockquote {
  font-style: italic;
  max-width: 545px;
  margin: 0 auto 50px auto;
  text-align: left;
}

```


