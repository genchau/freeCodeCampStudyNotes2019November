C01-S07-L01 - Responsive Web Design Certification - CSS Grid - Create Your First CSS Grid

```
display: grid;
```

Note: In CSS Grid, the parent element is referred to as the container and its children are called items.

---

C01-S07-L02 - Responsive Web Design Certification - CSS Grid - Add Columns with grid-template-columns

```
.container {
  display: grid;
  grid-template-columns: 100px 100px 100px;
}
```

![alt text][C01-S07-L02-I01]

---

C01-S07-L03 - Responsive Web Design Certification - CSS Grid - Add Rows with grid-template-rows

```
grid-template-rows: 100px 100px;
```

![alt text][C01-S07-L03-I01]

---

C01-S07-L04 - Responsive Web Design Certification - CSS Grid - Use CSS Grid units to Change the Size of Columns and Rows

```
grid-template-columns: auto 50px 10% 2fr 1fr;
```

![alt text][C01-S07-L04-I01]

fr: sets the column or row to a fraction of the available space,

auto: sets the column or row to the width or height of its content automatically,

%: adjusts the column or row to the percent width of its container.

This snippet creates five columns. The first column is as wide as its content, the second column is 50px, the third column is 10% of its container, and for the last two columns; the remaining space is divided into three sections, two are allocated for the fourth column, and one for the fifth.

---

C01-S07-L05 - Responsive Web Design Certification - CSS Grid - Create a Column Gap Using grid-column-gap

```
grid-column-gap: 20px;
```

![alt text][C01-S07-L05-I01]

---

C01-S07-L06 - Responsive Web Design Certification - CSS Grid - Create a Row Gap using grid-row-gap

```
grid-row-gap: 5px;
```

![alt text][C01-S07-L06-I01]

---

C01-S07-L07 - Responsive Web Design Certification - CSS Grid - Add Gaps Faster with grid-gap

```
grid-gap: 10px 20px;
```

![alt text][C01-S07-L07-I01]

---

C01-S07-L08 - Responsive Web Design Certification - CSS Grid - Use grid-column to Control Spacing

```
  .item5 {
    background: PaleGreen;
    grid-column: 2 / 4;
  }
```

![alt text][C01-S07-L08-I01]

![alt text][C01-S07-L08-I02]

grid-column: “START” / “END”;

---

C01-S07-L09 - Responsive Web Design Certification - CSS Grid - Use grid-row to Control Spacing

```
grid-row: 2 / 4;
```

![alt text][C01-S07-L09-I01]

---

C01-S07-L10 - Responsive Web Design Certification - CSS Grid - Align an Item Horizontally using justify-self

```
justify-self: center;
```

![alt text][C01-S07-L10-I01]

start: aligns the content at the left of the cell,

center: aligns the content in the center of the cell,

end: aligns the content at the right of the cell.

stretch: default.

---

C01-S07-L11 - Responsive Web Design Certification - CSS Grid - Align an Item Vertically using align-self

```
align-self: end;
```

![alt text][C01-S07-L11-I01]

---

C01-S07-L12 - Responsive Web Design Certification - CSS Grid - Align All Items Horizontally using justify-items

```
justify-items: center;
```

![alt text][C01-S07-L12-I01]

---

C01-S07-L13 - Responsive Web Design Certification - CSS Grid - Align All Items Vertically using align-items

```
align-items: end;
```

![alt text][C01-S07-L13-I01]

---

C01-S07-L14 - Responsive Web Design Certification - CSS Grid - Divide the Grid Into an Area Template

```
    grid-template-areas:
      "header header header"
      "advert content content"
      "footer footer footer";
```

See next lesson for example. The template won’t work without grid-area.

The code above merges the top three cells together into an area named header, the bottom three cells into a footer area, and it makes two areas in the middle row; advert and content. Note: Every word in the code represents a cell and every pair of quotation marks represent a row. In addition to custom labels, you can use a period (.) to designate an empty cell in the grid.

---

C01-S07-L15 - Responsive Web Design Certification - CSS Grid - Place Items in Grid Areas Using the grid-area Property

```
  .item5 {
    background: PaleGreen;
    grid-area: footer;
```

Use `grid-area` to assign an item into the `grid-template-area`

![alt text][C01-S07-L15-I01]

---

C01-S07-L16 - Responsive Web Design Certification - CSS Grid - Use grid-area Without Creating an Areas Template

```
grid-area: 3/1/4/4;
```

![alt text][C01-S07-L15-I01]

grid-area: horizontal line to start at / vertical line to start at / horizontal line to end at / vertical line to end at;

---

C01-S07-L17 - Responsive Web Design Certification - CSS Grid - Reduce Repetition Using the repeat Function

```
grid-template-columns: 1fr 1fr 1fr;
grid-template-columns: repeat(3, 1fr);
```

Both are the same. Repeat as the name implies, repeats stuff.

---

C01-S07-L18 - Responsive Web Design Certification - CSS Grid - Limit Item Size Using the minmax Function

```
grid-template-columns: repeat(3, minmax(90px, 1fr) );
```

---

C01-S07-L19 - Responsive Web Design Certification - CSS Grid - Create Flexible Layouts Using auto-fill

```
grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
```

![alt text][C01-S07-L19-I01]

When the container changes size, this setup keeps inserting 60px columns and stretching them until it can insert another one. Note: If your container can't fit all your items on one row, it will move them down to a new one.

---

C01-S07-L20 - Responsive Web Design Certification - CSS Grid - Create Flexible Layouts Using auto-fit

```
grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
```

![alt text][C01-S07-L20-I01]

`auto-fill` on top, `auto-fit` on bottom.

auto-fit works almost identically to auto-fill. The only difference is that when the container's size exceeds the size of all the items combined, auto-fill keeps inserting empty rows or columns and pushes your items to the side, while auto-fit collapses those empty rows or columns and stretches your items to fit the size of the container.

---

C01-S07-L21 - Responsive Web Design Certification - CSS Grid - Use Media Queries to Create Responsive Layouts

```
      grid-template-areas:
        "header header"
        "advert content"
        "footer footer";
```

![alt text][C01-S07-L21-I01]

less than 300px

```
    grid-template-areas:
      "header"
      "advert"
      "content"
      "footer";

```

![alt text][C01-S07-L21-I02]

300px to 400px

```
      grid-template-areas:
        "advert header"
        "advert content"
        "advert footer";
```

![alt text][C01-S07-L21-I03]

greater than 400px

```
      grid-template-areas:
        "header header"
        "advert content"
        "footer footer";
```

---

C01-S07-L22 - Responsive Web Design Certification - CSS Grid - Create Grids within Grids

```
  .item3 {
    background: PaleTurquoise;
    grid-area: content;
    /* enter your code below this line */
    display: grid;
    grid-template-columns: auto 1fr;
    /* enter your code above this line */
  }

```

BEFORE:

![alt text][C01-S07-L22-I01]

AFTER:

![alt text][C01-S07-L22-I02]

---

[Table Of Contents](https://github.com/genchau/freeCodeCampStudyNotes2019November/blob/master/tableOfContents.md)

---

[C01-S07-L02-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L02-I01.png "C01-S07-L02-I01"
[C01-S07-L03-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L03-I01.png "C01-S07-L03-I01"
[C01-S07-L04-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L04-I01.png "C01-S07-L04-I01"
[C01-S07-L05-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L05-I01.png "C01-S07-L05-I01"
[C01-S07-L06-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L06-I01.png "C01-S07-L06-I01"
[C01-S07-L07-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L07-I01.png "C01-S07-L07-I01"
[C01-S07-L08-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L08-I01.png "C01-S07-L08-I01"
[C01-S07-L08-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L08-I02.png "C01-S07-L08-I02"
[C01-S07-L09-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L09-I01.png "C01-S07-L09-I01"
[C01-S07-L10-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L10-I01.png "C01-S07-L10-I01"
[C01-S07-L11-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L11-I01.png "C01-S07-L11-I01"
[C01-S07-L12-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L12-I01.png "C01-S07-L12-I01"
[C01-S07-L13-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L13-I01.png "C01-S07-L13-I01"
[C01-S07-L15-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L15-I01.png "C01-S07-L15-I01"
[C01-S07-L19-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L19-I01.png "C01-S07-L19-I01"
[C01-S07-L20-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L20-I01.png "C01-S07-L20-I01"
[C01-S07-L21-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L21-I01.png "C01-S07-L21-I01"
[C01-S07-L21-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L21-I02.png "C01-S07-L21-I02"
[C01-S07-L21-I03]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L21-I03.png "C01-S07-L21-I03"
[C01-S07-L22-I01]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L22-I01.png "C01-S07-L22-I01"
[C01-S07-L22-I02]: https://raw.githubusercontent.com/genchau/freeCodeCampStudyNotes2019November/master/images/C01-S07-L22-I02.png "C01-S07-L22-I02"


