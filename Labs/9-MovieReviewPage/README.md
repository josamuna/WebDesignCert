# MovieReviewPage

A Movie review page project supporting accessibility purposes.

> This website was useful for this Project to get [Emojis](https://www.htmlsymbols.xyz/) for free, mainely [the yellow and white emoji stars](https://www.htmlsymbols.xyz/star-symbols).

## Source Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Movie Review</title>
  </head>
  aria-describedby attribute: Used to provide additional information about an
  element by associating it with another element that contains the information.
  This gives people using screen readers immediate access to the additional
  information when they navigate to the element. Common usage would include
  associating formatting instructions to a text input or an error message to an
  input after an invalid form submission.
  <body>
    <main>
      <h1>Movie Review: Rise Beyond</h1>
      <img
        src="https://cdn.freecodecamp.org/curriculum/labs/rise-beyond-2.png"
        alt="Cover page of the movie Rise Beyond for Ethan Carter."
      />
      <p>
        Rise Beyond is an uplifting drama that tells the story of Ethan Carter,
        a young man from a small town who dreams of becoming a world-class
        musician. Facing financial struggles and self-doubt, Ethan embarks on a
        journey of resilience, guided by his mentor Professor Adams and
        childhood friend Lena Mitchell. Through setbacks, failures, and moments
        of triumph, Rise Beyond reminds us that our greatest potential lies
        beyond our fears
      </p>
      <p>
        <strong>Movie Rating: </strong
        ><span aria-hidden="true"
          >&#11088;&#11088;&#11088;&#11088;&#11088;&#11088;&#11088;&#11088;&#11088;&#9734;</span
        >(9.2/10)
      </p>
      <h2>Cast Members</h2>
      <ul>
        <li><strong>James Holloway</strong> as Ethan Carter</li>
        <li><strong>Olivia Sterling</strong> as Lena Mitchell</li>
        <li><strong>William Lancaster</strong> as Professor Adams</li>
        <li>
          <strong>Maria Collins</strong> as Evelyn Carter (Ethan’s Mother)
        </li>
      </ul>
    </main>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/8bdcd6b0-1e50-42d4-a50e-1c6af672ba07)
