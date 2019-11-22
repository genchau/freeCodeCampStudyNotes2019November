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

```

---
C01-S06-L11 - Responsive Web Design Certification - CSS Flexbox - Use the flex-wrap Property to Wrap a Row or Column

```

```

---
C01-S06-L12 - Responsive Web Design Certification - CSS Flexbox - Use the flex-shrink Property to Shrink Items

```

```

---
C01-S06-L13 - Responsive Web Design Certification - CSS Flexbox - Use the flex-grow Property to Expand Items

```

```

---
C01-S06-L14 - Responsive Web Design Certification - CSS Flexbox - Use the flex-basis Property to Set the Initial Size of an Item

```

```

---
C01-S06-L15 - Responsive Web Design Certification - CSS Flexbox - Use the flex Shorthand Property

```

```

---
C01-S06-L16 - Responsive Web Design Certification - CSS Flexbox - Use the order Property to Rearrange Items

```

```

---
C01-S06-L17 - Responsive Web Design Certification - CSS Flexbox - Use the align-self Property

```

```

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


