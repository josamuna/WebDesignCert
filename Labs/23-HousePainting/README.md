# HousePainting

Building a House Painting Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>House Painting</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div id="house">
      <div id="chimney"></div>
      <div id="roof"></div>
      <div id="window-1"></div>
      <div id="window-2"></div>
      <div id="door">
        <div class="door-knob"></div>
      </div>
      <div id="welcome">Welcome</div>
    </div>
  </body>
</html>
```

```css
* {
  box-sizing: border-box;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(#b3e6ff, #b3e6ff 60%, green 60%);
  height: 100vh;
}

#house {
  position: relative;
  flex: 0 0 auto;
  width: 500px;
  height: 400px;
  background-color: #ff9980;
  border: 6px solid #b35900;
}

#chimney {
  position: absolute;
  width: 90px;
  height: 100px;
  border: 2px solid #000;
  background: repeating-linear-gradient(
    #e6e6e6,
    #e6e6e6 10%,
    black 10%,
    black 12%
  );
  top: -100px;
  left: 310px;
  z-index: -1;
}

#roof {
  position: absolute;
  width: 100%;
  height: 100px;
  top: 0;
  border: 2px solid #b35900;
  background:
    repeating-linear-gradient(
      45deg,
      #b35900,
      #b35900 2%,
      transparent 2%,
      transparent 5%
    ),
    repeating-linear-gradient(
      -45deg,
      #b35900,
      #b35900 2%,
      #ff9980 2%,
      #ff9980 5%
    );
  border-bottom: none;
}

#window-1 {
  position: absolute;
  background: linear-gradient(
    to right,
    #ffffb3,
    #ffffb3 48%,
    #b35900 48%,
    #b35900 52%,
    #ffffb3 52%,
    #ffffb3 100%
  );
  border: 6px solid #b35900;
  width: 100px;
  height: 100px;
  left: 8%;
  top: 120px;
}

#window-2 {
  position: absolute;
  background: linear-gradient(
    to right,
    #ffffb3,
    #ffffb3 48%,
    #b35900 48%,
    #b35900 52%,
    #ffffb3 52%,
    #ffffb3 100%
  );
  border: 6px solid #b35900;
  width: 100px;
  height: 100px;
  right: 8%;
  top: 120px;
}

#door {
  position: absolute;
  width: 130px;
  height: 180px;
  background-color: #e6e6e6;
  border: 6px solid #b35900;
  left: 175px;
  bottom: 0px;
}

.door-knob {
  position: absolute;
  width: 20px;
  height: 20px;
  background-color: #b35900;
  border-radius: 50%;
  top: 85px;
  left: 95px;
}

#welcome {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 400px;
  left: 160px;
  border: 2px solid #000;
  width: 145px;
  height: 50px;
  font-size: 1.1rem;
  font-weight: bold;
  transform: skew(148deg);
  background-color: #85e085;
  font-family: Arial, sans-serif;
  text-transform: uppercase;
}
```

## Output

![Image](https://github.com/user-attachments/assets/5c169cae-df91-40a7-a06e-aeeaf9da256a)
