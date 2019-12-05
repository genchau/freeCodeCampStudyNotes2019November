C01-S06-L01 - Responsive Web Design Certification - CSS Flexbox - Use display: flex to Position Two Boxes

BEFORE:

![alt text][C01-S06-L01-I01]

```
  #box-container {
    height: 500px;
    display: flex;
  }
```
AFTER:

![alt text][C01-S06-L01-I02]

---
C01-S06-L02 - Responsive Web Design Certification - CSS Flexbox - Add Flex Superpowers to the Tweet Embed

```
display: flex;
```

BEFORE:

![alt text][C01-S06-L02-I01]

AFTER:

![alt text][C01-S06-L02-I02]

---
C01-S06-L03 - Responsive Web Design Certification - CSS Flexbox - Use the flex-direction Property to Make a Row

```
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: row-reverse;
  }
```

flex-direction:
- row
- column
- row-reverse
- column-reverse

`display: flex`: flex container

`flex-direction’: allows us to manipulate the direction

---
C01-S06-L04 - Responsive Web Design Certification - CSS Flexbox - Apply the flex-direction Property to Create Rows in the Tweet Embed

```
N/A
```

---
C01-S06-L05 - Responsive Web Design Certification - CSS Flexbox - Use the flex-direction Property to Make a Column

```
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: column;
  }
```

BEFORE:

![alt text][C01-S06-L01-I02]

AFTER:

![alt text][C01-S06-L01-I01]

---
C01-S06-L06 - Responsive Web Design Certification - CSS Flexbox - Apply the flex-direction Property to Create a Column in the Tweet Embed

```
N/A
```

---
C01-S06-L07 - Responsive Web Design Certification - CSS Flexbox - Align Elements Using the justify-content Property

```
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    justify-content: center;
    justify-content: flex-start;
    justify-content: flex-end;
    justify-content: space-between;
    justify-content: space-around;
    justify-content: space-evenly;
  }
```

    justify-content: center;

![alt text][C01-S06-L07-I01]

    justify-content: flex-start;

![alt text][C01-S06-L07-I02]

    justify-content: flex-end;

![alt text][C01-S06-L07-I03]

    justify-content: space-between;

![alt text][C01-S06-L07-I04]

    justify-content: space-around; // looks like the empty space is divided into 4, so there’s 1,2,1 space around.

![alt text][C01-S06-L07-I05]

    justify-content: space-evenly; // looks like the empty space is divided into 3, so there’s 1,1,1 space around.

![alt text][C01-S06-L07-I06]

---
C01-S06-L08 - Responsive Web Design Certification - CSS Flexbox - Use the justify-content Property in the Tweet Embed

```
  header .profile-name {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-left: 10px;
    background-color: hsl(50,50%,90%);
  }
```

BEFORE:

![alt text][C01-S06-L08-I01]

AFTER:

![alt text][C01-S06-L08-I02]

---
C01-S06-L09 - Responsive Web Design Certification - CSS Flexbox - Align Elements Using the align-items Property

```
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    align-items: flex-start;
    align-items: flex-end;
    align-items: center;
    align-items: stretch;
    align-items: baseline;
  }
```

not specified align-items:

![alt text][C01-S06-L09-I01]

    align-items: flex-start;

![alt text][C01-S06-L09-I02]

    align-items: flex-end;

![alt text][C01-S06-L09-I03]

    align-items: center;

![alt text][C01-S06-L09-I04]

    align-items: stretch; // also default

![alt text][C01-S06-L09-I05]

    align-items: baseline;

![alt text][C01-S06-L09-I06]

---
C01-S06-L10 - Responsive Web Design Certification - CSS Flexbox - Use the align-items Property in the Tweet Embed

```
  header .follow-btn {
    display: flex;
    align-items: center;
    margin: 0 0 0 auto;
  }
```

BEFORE:

![alt text][C01-S06-L10-I01]

AFTER:

![alt text][C01-S06-L10-I02]

---
C01-S06-L11 - Responsive Web Design Certification - CSS Flexbox - Use the flex-wrap Property to Wrap a Row or Column

```
  #box-container {
    background: gray;
    display: flex;
    height: 100%;
    flex-wrap: nowrap; //default
    flex-wrap: wrap;
    flex-wrap: wrap-reverse;
  }
```

    flex-wrap: nowrap; //default

![alt text][C01-S06-L11-I01]

    flex-wrap: wrap;

![alt text][C01-S06-L11-I02]

    flex-wrap: wrap-reverse;

![alt text][C01-S06-L11-I03]

---
C01-S06-L12 - Responsive Web Design Certification - CSS Flexbox - Use the flex-shrink Property to Shrink Items

```
  #box-1 {
    background-color: dodgerblue;
    width: 100%;
    height: 200px;
    flex-shrink: 1; // default
  }

  #box-2 {
    background-color: orangered;
    width: 100%;
    height: 200px;
    flex-shrink: 2;
  }
```

BEFORE:

![alt text][C01-S06-L12-I01]

AFTER with flex-shrink:

![alt text][C01-S06-L12-I02]

---
C01-S06-L13 - Responsive Web Design Certification - CSS Flexbox - Use the flex-grow Property to Expand Items

```
  #box-1 {
    background-color: dodgerblue;
    height: 200px;
    flex-grow: 1;
  }

  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-grow: 2;
  }
```

flex-grow was not specified, width was also not specified, that’s why it was just a white background:

![alt text][C01-S06-L13-I01]

flex-grow, with orangered twice the size:

![alt text][C01-S06-L13-I02]

---
C01-S06-L14 - Responsive Web Design Certification - CSS Flexbox - Use the flex-basis Property to Set the Initial Size of an Item

```
  #box-1 {
    background-color: dodgerblue;
    height: 200px;
    flex-basis: 10em;
  }

  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-basis: 20em;
  }
```

The flex-basis property specifies the initial size of the item before CSS makes adjustments with flex-shrink or flex-grow.

The units used by the flex-basis property are the same as other size properties (px, em, %, etc.). The value auto sizes items based on the content.

![alt text][C01-S06-L13-I02]

---
C01-S06-L15 - Responsive Web Design Certification - CSS Flexbox - Use the flex Shorthand Property

```
  #box-1 {
    background-color: dodgerblue;
    flex: 2 2 150px;
    height: 200px;
  }

  #box-2 {
    background-color: orangered;
    flex: 1 1 150px;
    height: 200px;
  }
```

There is a shortcut available to set several flex properties at once. The flex-grow, flex-shrink, and flex-basis properties can all be set together by using the flex property.

For example, flex: 1 0 10px; will set the item to flex-grow: 1;, flex-shrink: 0;, and flex-basis: 10px;.

The default property settings are flex: 0 1 auto;.

These values will cause #box-1 to grow to fill the extra space at twice the rate of #box-2 when the container is greater than 300px and shrink at twice the rate of #box-2 when the container is less than 300px. 300px is the combined size of the flex-basis values of the two boxes.

![alt text][C01-S06-L15-I01]

![alt text][C01-S06-L15-I02]

![alt text][C01-S06-L15-I03]

---
C01-S06-L16 - Responsive Web Design Certification - CSS Flexbox - Use the order Property to Rearrange Items

```
  #box-1 {
    background-color: dodgerblue;
    order: 2;
    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;
    order: 1;
    height: 200px;
    width: 200px;
  } 
```

The property takes numbers as values, and negative numbers can be used.

---
C01-S06-L17 - Responsive Web Design Certification - CSS Flexbox - Use the align-self Property

```
  #box-1 {
    background-color: dodgerblue;
    align-self: center;
    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;
    align-self: flex-end;
    height: 200px;
    width: 200px;
  }
```

align-self and similar to align-items, except we are only aligning the one item “self”.

![alt text][C01-S06-L17-I01]

---

[Table Of Contents](https://github.com/genchau/freeCodeCampStudyNotes2019November/blob/master/tableOfContents.md)

---

[C01-S06-L01-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L01-I01.png "C01-S06-L01-I01"
[C01-S06-L01-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L01-I02.png "C01-S06-L01-I02"
[C01-S06-L02-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L02-I01.png "C01-S06-L02-I01"
[C01-S06-L02-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L02-I02.png "C01-S06-L02-I02"
[C01-S06-L07-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L07-I01.png "C01-S06-L07-I01"
[C01-S06-L07-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L07-I02.png "C01-S06-L07-I02"
[C01-S06-L07-I03]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L07-I03.png "C01-S06-L07-I03"
[C01-S06-L07-I04]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L07-I04.png "C01-S06-L07-I04"
[C01-S06-L07-I05]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L07-I05.png "C01-S06-L07-I05"
[C01-S06-L07-I06]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L07-I06.png "C01-S06-L07-I06"
[C01-S06-L08-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L08-I01.png "C01-S06-L08-I01"
[C01-S06-L08-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L08-I02.png "C01-S06-L08-I02"
[C01-S06-L09-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L09-I01.png "C01-S06-L09-I01"
[C01-S06-L09-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L09-I02.png "C01-S06-L09-I02"
[C01-S06-L09-I03]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L09-I03.png "C01-S06-L09-I03"
[C01-S06-L09-I04]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L09-I04.png "C01-S06-L09-I04"
[C01-S06-L09-I05]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L09-I05.png "C01-S06-L09-I05"
[C01-S06-L09-I06]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L09-I06.png "C01-S06-L09-I06"
[C01-S06-L10-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L10-I01.png "C01-S06-L10-I01"
[C01-S06-L10-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L10-I02.png "C01-S06-L10-I02"
[C01-S06-L11-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L11-I01.png "C01-S06-L11-I01"
[C01-S06-L11-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L11-I02.png "C01-S06-L11-I02"
[C01-S06-L11-I03]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L11-I03.png "C01-S06-L11-I03"
[C01-S06-L12-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L12-I01.png "C01-S06-L12-I01"
[C01-S06-L12-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L12-I02.png "C01-S06-L12-I02"
[C01-S06-L13-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L13-I01.png "C01-S06-L13-I01"
[C01-S06-L13-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L13-I02.png "C01-S06-L13-I02"
[C01-S06-L15-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L15-I01.png "C01-S06-L15-I01"
[C01-S06-L15-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L15-I02.png "C01-S06-L15-I02"
[C01-S06-L15-I03]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L15-I03.png "C01-S06-L15-I03"
[C01-S06-L17-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S06-L17-I01.png "C01-S06-L17-I01"

