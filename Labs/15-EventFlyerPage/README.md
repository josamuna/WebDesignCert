# EventFlyerPage

Building an Event Flyer Page project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Build an Event Flyer Page</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <header class="carnival">
      <img
        src="https://cdn.freecodecamp.org/curriculum/labs/event.jpg"
        alt="A carnival view with beautiful colors."
      />
      <h1>Coding Carnival</h1>
      <p>
        Join us for the annual Coding Carnival, and enjoy working with pairs.
      </p>
      <p>
        <strong>Save the date:</strong> July 10th <strong>on:</strong> The
        Central City Space
      </p>
    </header>
    <hr />
    <main class="container">
      <section>
        <h2>Coding Challenges</h2>
        <ul>
          <li>Interactive problem-solving games</li>
          <li>Real-time coding competitions</li>
          <li>Beginner to advanced levels</li>
        </ul>
      </section><section>
        <h2>Creative Projects</h2>
        <ul>
          <li>Build fun apps and mini-games</li>
          <li>Collaborate with other developers</li>
          <li>Showcase your innovations</li>
        </ul>
      </section><section>
        <h2>Workshops & Learning</h2>
        <ul>
          <li>Hands-on coding sessions</li>
          <li>Mentorship from experts</li>
          <li>Latest tech trends and tools</li>
        </ul>
      </section>
      <hr class="low-separator" />
    </main>
    <footer class="footer">
      <p>&copy;2026 Coding Carnival</p>
    </footer>
  </body>
</html>
```

```css
body {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 50px;
  padding-bottom: 50px;
  font-family: arial, sans-serif;
  width: 80vw;
  min-height: calc(100vh - 100px);
  margin-left: auto;
  margin-right: auto;
  background-color: #fcfcfc;
  color: #333;
}

hr {
  width: 85%;
  border: 0.12em solid #333;
  margin-top: 1.8em;
  margin-bottom: 1.4em;
}

.low-separator {
  margin-top: 4.2em;
}

section {
  width: 33.3%;
  display: inline-block;
}

.container {
  padding-top: 2em;
}

h1 {
  font-size: 2rem;
}

h2 {
  font-size: 1.6rem;
  display: inlign-block;
  text-align: center;
}

.carnival {
  text-align: center;
}

.footer {
  text-align: center;
}
```

## Output

![Image](https://github.com/user-attachments/assets/49d3cdee-688d-4fb3-9fee-2738a2dbe59e)
