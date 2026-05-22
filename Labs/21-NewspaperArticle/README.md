# NewspaperArticle

Building a Newspaper Article Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Newspaper Article</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <main class="newspaper">
      <header class="headline">
        <h1>Daily Chuckles</h1>
      </header>
      <div class="date">
        <p>July 5, 2024</p>
      </div>
      <div class="name">
        <h2>Breaking: Grandma Edna Saves Earth</h2>
      </div>
      <div class="sub-headline">
        <p>Alien Invasion Foiled by Tech-Savvy Grandma's Wi-Fi Password</p>
      </div>
      <div class="author">
        <p>By Jane Doe</p>
      </div>
      <p class="text">
        In an extraordinary twist of fate, Grandma Edna found herself at the
        forefront of a potential crisis when her clever Wi-Fi security measures
        unexpectedly thwarted an alien invasion. As alien spacecraft descended
        upon the town, panic spread until Grandma Edna calmly intervened,
        resetting her router with a cryptic passphrase known only to her.
      </p>
      <p class="text">
        The aliens, encountering unforeseen technological barriers, struggled to
        breach Grandma Edna's fortified network. Frustrated and bewildered, they
        eventually retreated to reassess their invasion strategy, leaving
        residents both relieved and amazed at Grandma Edna's resourcefulness.
      </p>
    </main>
  </body>
</html>
```

```css
* {
  box-sizing: border-box;
}
html {
  font-size: 24px;
}

body {
  background-color: #f5fffa;
}

.newspaper {
  font-size: 16px;
  font-family: 'Open Sans', sans-serif;
  width: 90%;
  max-width: 800px;
  min-width: 400px;
  margin: 10px auto;
  background-color: white;
  border-radius: 10px;
  padding: 20px 30px;
  box-shadow: 2px 2px 20px 3px gray;
}

.name {
  /* font-size: 2rem; To passe the Challenge */
  font-family: 'Times New Roman', serif;
  font-size: 1.1rem; /* For better view */
}

.name h2 {
  margin: 5px 0;
}

.name,
.author {
  text-transform: uppercase;
}

.author {
  font-weight: bold;
}

.headline {
  font-size: 2em;
  font-weight: bold;
  text-align: center;
}

.headline h1 {
  margin-bottom: 5px;
}

.sub-headline {
  font-weight: 100;
  font-size: 1.5em;
  font-style: italic;
}

.text {
  text-indent: 20px;
  line-height: 2em;
  text-align: justify;
}

.text::first-letter {
  font-size: 2em;
  font-weight: bold;
}

.date {
  text-align: center;
}
```

## Output

![Image](https://github.com/user-attachments/assets/3ee82216-42fa-4bf6-a015-c4e8a301d09d)
