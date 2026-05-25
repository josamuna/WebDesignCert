# TributePage

Building a Tribute Page Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=content-width, initial-scale=1.0" />
    <title>Tribute Page</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <main id="main">
      <h1 id="title">Dr. Norman Borlaug</h1>

      <p>The man who saved a billion lives</p>
      <figure id="img-div">
        <img
          src="https://c2.staticflickr.com/4/3689/10613180113_fdf7bcd316_b.jpg"
          alt="Dr. Norman Borlaug"
          id="image"
        />
        <figcaption id="img-caption">
          Dr. Norman Borlaug, third from the left, trains biologists in Mexico
          on how to increase wheat yields - part of his life-long war on hunger.
        </figcaption>
      </figure>
      <div id="tribute-info">
        <p class="hihlight">Here's a time line of Dr. Borlaug's life:</p>
        <ul>
          <li><strong>1914</strong> &dash; Born in Cresco, Iowa.</li>
          <li>
            <strong>1933</strong> &dash; Leaves his family's farm to attend the
            University of Minnesota, thanks to a Depression era program known as
            the "National Youth Administration".
          </li>
          <li>
            <strong>1935</strong> &dash; Has to stop school and save up more
            money. Works in the Civilian Conservation Corps, helping starving
            Americans. "I saw how food changed them", he said. "All of this left
            scars on me."
          </li>
          <li>
            <strong>1937</strong> &dash; Finishes university and takes a job in
            the US Fores-try Service.
          </li>
          <li>
            <strong>1938</strong> &dash; Marries wife of 69 years Margret
            Gibson. Gets laid off due to budget cuts. Inspired by Elvin Charles
            Stakman, he returns to school study under Stakman, who teaches him
            about breeding pest-resistant plants.
          </li>
          <li>
            <strong>1941</strong> &dash; Tries to enroll in the military after
            the Pearl Harbor attack, but is rejected. Instead, the military
            asked his lab to work on waterproof glue, DDT to control malaria,
            disinfectants, and other applied science.
          </li>
          <li>
            <strong>1942</strong> &dash; Receives a Ph.D. in Genetics and Plant
            Pathology.
          </li>
          <li>
            <strong>1944</strong> &dash; Rejects a 100% salary increase from
            Dupont, leaves behind his pregnant wife, and flies to Mexico to head
            a new plant pathology program. Over the next 16 years, his team
            breeds 6,000 different strains of disease resistant wheat -
            including different varieties for each major climate on Earth.
          </li>
          <li>
            <strong>1945</strong> &dash; Discovers a way to grown wheat twice
            each season, doubling wheat yields.
          </li>
          <li>
            <strong>1953</strong> &dash; crosses a short, sturdy dwarf breed of
            wheat with a high-yielding American breed, creating a strain that
            responds well to fertilizer. It goes on to provide 95% of Mexico's
            wheat.
          </li>
          <li>
            <strong>1962</strong> &dash; Visits Delhi and brings his
            high-yielding strains of wheat to the Indian subcontinent in time to
            help mitigate mass starvation due to a rapidly expanding population.
          </li>
          <li><strong>1970</strong> &dash; receives the Nobel Peace Prize.</li>
          <li>
            <strong>1983</strong> &dash; helps seven African countries
            dramatically increase their maize and sorghum yields.
          </li>
          <li>
            <strong>1984</strong> &dash; becomes a distinguished professor at
            Texas A&M University.
          </li>
          <li>
            <strong>2005</strong> &dash; states "we will have to double the
            world food supply by 2050." Argues that genetically modified crops
            are the only way we can meet the demand, as we run out of arable
            land. Says that GM crops are not inherently dangerous because "we've
            been genetically modifying plants and animals for a long time. Long
            before we called it science, people were selecting the best breeds."
          </li>
          <li><strong>2009</strong> &dash; dies at the age of 95.</li>
        </ul>
        <blockquote
          cite="http://news.rediff.com/report/2009/sep/14/pm-pays-tribute-to-father-of-green-revolution-borlaug.htm"
        >
          <p>
            "Borlaug's life and achievement are testimony to the far-reaching
            contribution that one man's towering intellect, persistence and
            scientific vision can make to human peace and progress."
          </p>
          <cite>-- Indian Prime Minister Manmohan Singh</cite>
        </blockquote>
      </div>
      <div>
        <h3>
          If you have time, you should read more about this incredible human
          being on his
          <a
            id="tribute-link"
            href="https://en.wikipedia.org/wiki/Norman_Borlaug"
            target="_blank"
            >Wikipedia entry</a
          >.
        </h3>
      </div>
    </main>
  </body>
</html>
```

```css
body {
  font-family: Arial, sans-serif;
  color: #333;
}

main {
  background-color: #eee;
  margin: 20px auto;
  padding: 15px;
}

.hihlight {
  font-weight: bold;
  font-size: 1.2rem;
  text-align: center;
  padding: 20px 5px;
}

cite {
  line-height: 2;
}

blockquote {
  line-height: 2;
  margin: 40px 100px 40px 100px;
  font-style: italic;
}

#img-div {
  background-color: white;
  padding: 20px 10px;
}

#img-caption {
  text-align: center;
  padding: 10px 5px 0;
  line-height: 1.3;
}

h3 {
  text-align: center;
  margin: 20px auto;
}

#title {
  text-align: center;
  font-size: 2.5rem;
}

#main > p {
  text-align: center;
  margin-bottom: 20px;
}

#image {
  display: block;
  height: auto;
  max-width: 100%;
  margin: 10px auto;
}

#tribute-info li {
  line-height: 2;
  margin: 10px 100px 10px 100px;
}

#tribute-link:link {
  color: #477ca7;
}
```

## Output

### Small View

![Image](https://github.com/user-attachments/assets/5aed9d67-bf5b-45c8-a031-5b5c3a80736d)

### Big View

![Image](https://github.com/user-attachments/assets/0f2a171d-1b74-4a8b-8842-5949b7e04208)
