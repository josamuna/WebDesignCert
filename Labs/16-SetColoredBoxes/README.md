# SetColoredBoxes

Building Colored Boxes project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Colored Boxes</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="color-grid">
      <h1 class="center">Colored Boxes</h1>
      <div class="color-box color1"></div>
      <div class="color-box color2"></div>
      <div class="color-box color3"></div>
      <div class="color-box color4"></div>
      <div class="color-box color5"></div>
    </div>
  </body>
</html>
```

```css
body {
  background-color: #f4f4f4;
}

.center {
  text-align: center;
}

.color-grid {
  margin: 0 auto;
  padding: 20px;
}

.color-box {
  display: inline-block;
  width: 13vw;
  height: 13vw;
  border-radius: 8px;
}

.color1,
.color2,
.color3,
.color4,
.color5 {
  margin: 5px 40px;
}

.color1 {
  background-color: #33ff57;
}

.color2 {
  background-color: rgb(120, 0, 128);
}

.color3 {
  background-color: orange;
}

.color4 {
  background-color: hsl(58.52deg 60.9% 26.08%);
}

.color5 {
  background-color: red;
}
```

## Output

![Image](https://github.com/user-attachments/assets/834bfd6d-c8fc-41c4-a5f9-c711e25b186e)
