# BlogPostCard

Designing a Blog post Card project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Blog Post Card</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="blog-post-card">
      <img
        class="post-img"
        src="https://cdn.freecodecamp.org/curriculum/labs/cover-photo.jpg"
        alt="Person working on PC."
      />
      <div class="post-content">
        <h2 class="post-title">Learn Web Development in 2026</h2>
        <p class="post-excerpt">
          Stay ahead of the curve with the latest trends in web development.
          Discover what's new and exciting in 2026.
        </p>
        <a
          class="read-more"
          href="https://www.freecodecamp.org/"
          target="_blank"
          >Read More</a
        >
      </div>
    </div>
  </body>
</html>
```

```css
body {
  background-color: #f0f0f0;
  font-family: arial, sans-serif;
}
.blog-post-card {
  background-color: white;
  border-radius: 15px;
  width: 370px;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}
.post-img {
  width: 100%;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
  border-bottom: 3px solid #1b292a;
}
.post-content {
  padding: 10px;
}
.post-title {
  color: #1b292a;
  margin: 10px;
}
.post-excerpt {
  color: #415657;
  margin: 20px;
}
.read-more {
  color: white;
  background-color: #1b292a;
  margin: 5px;
  padding: 10px;
  border-radius: 5px;
  display: inline-block;
}
.read-more:link {
  text-decoration: none;
}
.read-more:hover {
  background-color: #49595a;
}
```

## Output

![Image](https://github.com/user-attachments/assets/933b4b2c-64b0-4d85-8bdf-e44b0ae1e78a)
