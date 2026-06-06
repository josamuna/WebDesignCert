# NewspaperLayout

Building and Designing a 25-Newspaper Layout Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Newspaper Layout</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <main class="newspaper-layout">
      <header class="title">
        <h1>The Daily Local News</h1>
      </header>
      <article class="feature-article">
        <h2>Breaking News: Volcano Eruption Disrupts Tourism</h2>
        <p>
          Recently, a volcano erupted in a popular tourist destination. The
          eruption has caused widespread panic and has disrupted tourism in the
          area. The volcano has been spewing lava and ash for several days now,
          and authorities are urging residents and tourists to evacuate the area
          immediately. The eruption has also caused a number of flights to be
          cancelled, leaving many tourists stranded. The situation is still
          developing, and authorities are working to contain the eruption and
          ensure the safety of everyone in the area.
        </p>
      </article>
      <article class="secondary-article">
        <h2>Technology: The Rise of AI</h2>
        <p>
          Artificial intelligence (AI) is changing the way we live and work.
          From self-driving cars to virtual assistants, AI is revolutionizing
          the world around us. But what exactly is AI, and how does it work? In
          this article, we'll explore the rise of AI and its impact on society.
        </p>
      </article>
      <article class="small-article1">
        <h3>Sports: Local Team Wins Championship</h3>
        <p>
          Hockey fans are celebrating today as the local team has won the
          championship. The team, which has been on a winning streak all season,
          clinched the title in a thrilling final match. Fans took to the
          streets to celebrate the victory, waving flags and chanting the team's
          name.
        </p>
      </article>
      <article class="small-article2">
        <h3>Health: Tips for a Balanced Diet</h3>
        <p>
          A diet high in calories, sugar, and unhealthy fats can lead to a
          variety of health problems, including obesity, diabetes, and heart
          disease. To maintain a healthy weight and reduce your risk of chronic
          diseases, it's important to eat a balanced diet that includes a
          variety of nutrient-rich foods. Here are some tips for eating a
          balanced diet:
        </p>
      </article>
      <article class="small-article3">
        <h3>Travel: Top 10 Destinations for 2025</h3>
        <p>
          Traveling is one of the best ways to experience new cultures, meet new
          people, and see the world. If you're looking for inspiration for your
          next trip, here are the top 10 destinations for 2025:
        </p>
      </article>
      <figure class="cover-image">
        <img
          src="https://cdn.freecodecamp.org/curriculum/labs/volcano.jpg"
          alt="Volcano in high activity."
          loading="lazy"
        />
      </figure>
    </main>
  </body>
</html>
```

```css
:root {
  --background-color1: #f9f9f9;
  --background-color2: #e9e9e9;
  --background-color3: #dddddd;
  --background-color4: #1b1b32;
  --normal-article-line-height: 1.3;
  --small-article-line-height: 1.3;
  --h1-font-size: 1.5rem;
  --h2-font-size: 1.1rem;
  --h3-font-size: 0.925rem;
  --h1-padding: 2rem 1rem;
  --h2-padding: 0.1rem 0rem 1rem;
  --h3-padding: 0.1rem 0rem 1rem;
  --small-border-radius: 0.5rem;
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  font-family: Georgia, serif;
}

.newspaper-layout {
  display: grid;
  grid-template-areas:
    "title title title"
    "feature-article feature-article cover-image"
    "secondary-article secondary-article cover-image"
    "small-article1 small-article2 small-article3";
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: auto 1fr 1fr 1fr;
  gap: 1.1rem 1.1rem;
  margin: 1.4rem;
}

h2,
h3 {
  color: var(--background-color4, #1b1b32);
}

h2 {
  padding: var(--h2-padding, 0.1rem 0rem 1rem);
}

h3 {
  padding: var(--h3-padding, 0.1rem 0rem 1rem);
}

.title {
  grid-area: title;
  background-color: var(--background-color4, #1b1b32);
  color: white;
  text-align: center;
  padding: var(--h1-padding, 2rem 1rem);
  font-size: var(--h1-font-size, 1.5rem);
}

.feature-article,
.secondary-article {
  background-color: var(--background-color1);
  line-height: var(--normal-article-line-height, 1.3);
}

.feature-article,
.secondary-article,
.small-article1,
.small-article2,
.small-article3 {
  border-radius: var(--small-border-radius, 0.5rem);
  padding: 2rem 1rem;
  text-align: justify;
}

.feature-article {
  grid-area: feature-article;
}

.cover-image {
  grid-area: cover-image;
  background-color: var(--background3, #dddddd);
  padding: 5rem 0.925rem 5rem;
  border-radius: var(--background3, #dddddd);
}

.secondary-article {
  grid-area: secondary-article;
}

.small-article1,
.small-article2,
.small-article3 {
  background-color: var(--background-color2, #e9e9e9);
  font-size: 0.9rem;
  line-height: var(--small-article-line-height, 1);
}

.small-article1 {
  grid-area: small-article1;
}

.small-article2 {
  grid-area: small-article2;
}

.small-article3 {
  grid-area: small-article3;
}

.cover-image img {
  max-width: 100%;
  border-radius: var(--small-border-radius, 0.5rem);
}
```

## Output

![Image](https://github.com/user-attachments/assets/69e234ca-ccf3-4312-9ba5-361079b78a4f)
