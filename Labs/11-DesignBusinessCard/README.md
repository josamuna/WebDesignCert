# DesignBusinessCard

Designing a BusinessCard project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Business Card</title>
    <link rel="stylesheet" href="styles.css" />
  </head>

  <body>
    <div class="business-card">
      <img
        class="profile-image"
        src="https://i.postimg.cc/2y6KnZVd/josue-profile.jpg"
        alt="Josue Isamuna Nkembo's profile image."
      />
      <p class="full-name">Josue Isamuna Nkembo</p>
      <p class="designation">Software Engineer</p>
      <p class="company">Africa Builder Limited</p>
      <hr />
      <p>Email: josamuna2009gmail.com</p>
      <p>Phone: (+243) 972-727-527</p>
      <a
        class="portfolio-link"
        href="https://github.com/josamuna/"
        target="_blank"
        >Portfolio</a
      >
      <hr />
      <div class="social-media">
        <h2>Connect with me</h2>
        <a href="https://x.com/josamuna">Twitter</a>
        <a href="https://www.linkedin.com/in/josue-isamuna-nkembo/">LinkedIn</a>
        <a href="https://github.com/josamuna">GitHub</a>
      </div>
    </div>
  </body>
</html>
```

```css
body {
  background-color: rosybrown;
  font-family: Arial, sans-serif;
}
.business-card {
  width: 300px;
  background-color: #f8efef;
  padding: 20px;
  margin-top: 100px;
  text-align: center;
  font-size: 16px;
  margin-left: auto;
  margin-right: auto;
  border: solid 3px #2f4f4f;
}
p {
  margin: 5px;
}
.profile-image {
  max-width: 100%;
  border: 1px solid #c7c7c7;
}
.full-name {
  color: #2f4f4f;
  font-size: 24px;
  margin-top: 10px;
}
.designation {
  color: gray;
  font-size: 18px;
}
.company {
  color: #b8b8b8;
}
a {
  text-decoration: none;
  color: brown;
}
.portfolio-link {
  color: blue;
}
.social-media a {
  margin: 10px;
}
hr {
  margin-top: 15px;
  margin-bottom: 15px;
}
h2 {
  margin-top: 10px;
}
```

## Output

![Image](https://github.com/user-attachments/assets/7231f868-5ea3-4dd1-8729-6838bc51fadf)
