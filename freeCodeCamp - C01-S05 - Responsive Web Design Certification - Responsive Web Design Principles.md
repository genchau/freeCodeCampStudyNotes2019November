C01-S05-L01 - Responsive Web Design Certification - Responsive Web Design Principles - Create a Media Query

```
@media (max-width: 100px) { /* CSS Rules */ }
@media (min-height: 350px) { /* CSS Rules */ }
```

```
<style>
  p {
    font-size: 20px;
  }

  /* Add media query below */
  @media (max-height: 800px) {
    p {
      font-size: 10px;
    }
  }
</style>
```

---
C01-S05-L02 - Responsive Web Design Certification - Responsive Web Design Principles - Make an Image Responsive

Don’t do this:
```
img { width: 720px; }
```

Do this instead:
```
img {
  max-width: 100%;
  display: block;
  height: auto;
}
```

display: block // this means that the picture will get its own line

```
<style>
    img {
        max-width: 100%;
        display: block;
        height: auto;
    }
</style>
```

---
C01-S05-L03 - Responsive Web Design Certification - Responsive Web Design Principles - Use a Retina Image for Higher Resolution Displays

```
<style>
  img { height: 250px; width: 250px; }
</style>
<img src="coolPic500x500" alt="A most excellent picture">
```

```
<style>
    img {
        width: 100px;
        height: 100px;
    }
</style>
```

We’re simply displaying the picture at 50% of original, so the pixels are crammed closer together.

---
C01-S05-L04 - Responsive Web Design Certification - Responsive Web Design Principles - Make Typography Responsive

```
<style>
    h2 {
        width: 80vw;
    }
    p {
        width: 75vmin;
    }
</style>
```

- vw (viewport width): 10vw would be 10% of the viewport's width.
- vh (viewport height): 3vh would be 3% of the viewport's height.
- vmin (viewport minimum): 70vmin would be 70% of the viewport's smaller dimension (height or width).
- vmax (viewport maximum): 100vmax would be 100% of the viewport's bigger dimension (height or width).

---

