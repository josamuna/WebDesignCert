# GreetingCard

Greeting card workshop project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Greeting Card</title>
    <link href="styles.css" rel="stylesheet" />
  </head>
  <body>
    <div class="card" id="greeting-card">
      <h1>Happy Birthday!</h1>
      <p class="message">
        Wishing you all the happiness and joy on your special day!
      </p>
      <div class="card-links">
        <a href="#send" class="send-link">Send Card</a>
        <a href="#share" class="share-link">Share on Social Media</a>
      </div>
    </div>
    <section id="send">
      <h2>Sending your card...</h2>
      <p>Card successfully sent to your recipient!</p>
    </section>
    <section id="share">
      <h2>Sharing your card...</h2>
      <p>Your card was shared on social media!</p>
    </section>
  </body>
</html>
```

```css
body {
  font-family: Arial, sans-serif;
  padding: 40px;
  text-align: center;
  background-color: brown;
}

.card {
  background-color: white;
  max-width: 400px;
  padding: 40px;
  margin: 0 auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px gray;
  transition:
    transform 0.3s,
    background-color 0.3s ease;
}

.card:hover {
  background-color: khaki;
  transform: scale(1.1);
}

h1::before {
  content: '🥳 ';
}

h1::after {
  content: ' 🥳';
}

.message {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.card-links {
  margin-top: 20px;
  display: flex;
  justify-content: space-around;
}

.card-links a {
  text-decoration: none;
  font-size: 1em;
  padding: 10px 20px;
  border-radius: 5px;
  color: white;
  background-color: midnightblue;
  transition: background-color 0.3s ease;
}

.card-links a:hover {
  background-color: orangered;
}

.card-links a:active {
  background-color: midnightblue;
}

.card-links a:focus {
  outline: 2px solid yellow;
}

.card-links a:visited {
  color: white;
}

section {
  margin: 20px auto;
  max-width: 600px;
  background-color: whitesmoke;
  padding: 20px;
  border-radius: 10px;
  display: none;
}

section:hover {
  transform: skewX(10deg);
}

section:target {
  display: block;
}
```

## Output

### Initial state

![Image](https://github.com/user-attachments/assets/a03af152-0ae6-4979-8726-b15d71fc7540)

### On hover state

![Image](https://github.com/user-attachments/assets/9ed3062a-5665-43a1-8f10-bcaa5911cb19)

### State when a link is clicked

![Image](https://github.com/user-attachments/assets/2d2a7fb4-4a81-4dbe-bcbc-1418df4580c3)

### State after clicked the link

![Image](https://github.com/user-attachments/assets/c1a6e6d6-c622-4e85-b901-f3d669f7ccdd)
