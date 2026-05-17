# FlexboxPhotoGallery

Designing a Flexbox Photo Gallery project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Photo Gallery</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <header class="header">
      <h1>css flexbox photo gallery</h1>
    </header>
    <div class="gallery">
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg"
        alt="A black and write Cat."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/2.jpg"
        alt="A Cat that relaxes his body."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/3.jpg"
        alt="A brown Cat above a table."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/4.jpg"
        alt="A curious Cat Cat."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/5.jpg"
        alt="A too black Cat."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/6.jpg"
        alt="A Cat who takes a rest."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/7.jpg"
        alt="A too write Cat."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/8.jpg"
        alt="A Cat that seeing thought a transparent door."
      />
      <img
        src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/9.jpg"
        alt="A Cat under the table."
      />
    </div>
  </body>
</html>
```

```css
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: sans-serif;
  background: #f5f6f7;
}

.header {
  text-align: center;
  text-transform: uppercase;
  padding: 32px;
  background-color: #0a0a23;
  color: #fff;
  border-bottom: 4px solid #fdb347;
}

.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 16px;
  max-width: 1400px;
  margin: 0 auto;
  padding: 20px 10px;
}

.gallery img {
  width: 100%;
  max-width: 350px;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

/* Add an empty space to simulate an empty img */
.gallery::after {
  content: '';
  width: 350px;
}
```

## Output

![Image](https://github.com/user-attachments/assets/03ade43a-d69d-4559-b838-ae298462327a)
