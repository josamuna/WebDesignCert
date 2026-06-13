# MoonOrbit

Building a Moon Orbit Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Moon Orbit</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="space">
      <div class="earth"></div>
      <div class="orbit">
        <div class="moon"></div>
      </div>
    </div>
  </body>
</html>
```

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #000;
}

.space {
  position: relative;
  width: 200px;
  height: 200px;
}

.earth {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: #0000ff;
  transform: translate(-50%, -50%);
}

.orbit {
  position: absolute;
  width: 200px;
  height: 200px;
  transform: translate(-50%, -50%);
  border-radius: 50%;
  animation: orbit 5s linear infinite;
}

.moon {
  position: absolute;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  top: 0;
  left: 50%;
  transform: translate(-50%);
  background-color: #808080;
}

@keyframes orbit {
  0% {
    transform: rotate(0deg) translate(-50%, -50%);
  }

  100% {
    transform: rotate(360deg) translate(-50%, -50%);
  }
}
```

## Output

![Image](https://github.com/user-attachments/assets/a310dcc0-f704-4e2d-81b5-ca6a06ab4f28)
