# 5-ProductLandingPage

Building a Product Landing Page Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=content-width, initial-scale=1.0" />
    <title>Product Landing Page</title>
    <link rel="stylesheet" href="./styles.css" />
    <!-- Awersone custome icones -->
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
    />
  </head>
  <body>
    <main id="container">
      <header id="header">
        <img
          src="https://cdn.freecodecamp.org/testable-projects-fcc/images/product-landing-page-logo.png"
          alt="Original Trombones Logo."
          id="header-img"
        />

        <nav id="nav-bar">
          <ul>
            <li><a href="#features" class="nav-link">Features</a></li>
            <li><a href="#how_it_works" class="nav-link">How It Works</a></li>
            <li><a href="#pricing" class="nav-link">Pricing</a></li>
          </ul>
        </nav>
      </header>
      <section id="form-started">
        <h2>Handcrafted, home-made masterpieces</h2>
        <div>
          <form
            id="form"
            method="POST"
            action="https://www.freecodecamp.org/email-submit"
          >
            <label aria-hidden="true" for="email"></label>
            <input
              id="email"
              type="email"
              name="email"
              placeholder="Enter your email address"
            />
            <input id="submit" type="submit" value="get started" />
          </form>
        </div>
      </section>

      <section id="features">
        <div class="features-item">
          <div class="icon">
            <i class="fa fa-3x fa-fire"></i>
          </div>
          <div class="description">
            <h2>Premium Materials</h2>
            <p>
              Our trombones use the shiniest brass which is sourced locally.
              This will increase the longevity of your purchase.
            </p>
          </div>
        </div>
        <div class="features-item">
          <div class="icon">
            <i class="fa fa-3x fa-truck"></i>
          </div>
          <div class="description">
            <h2>Fast Shipping</h2>
            <p>
              We make sure you receive your trombone as soon as we have finished
              making it. We also provide free returns if you are not satisfied.
            </p>
          </div>
        </div>
        <div class="features-item">
          <div class="icon">
            <i class="fa fa-3x fa-battery-full" aria-hidden="true"></i>
          </div>
          <div class="description">
            <h2>Quality Assurance</h2>
            <p>
              For every purchase you make, we will ensure there are no damages
              or faults and we will check and test the pitch of your instrument.
            </p>
          </div>
        </div>
      </section>

      <section id="how_it_works">
        <iframe
          id="video"
          width="650"
          height="400"
          src="https://www.youtube-nocookie.com/embed/y8Yv4pnO7qc?rel=0&controls=0&showinfo=0"
          title="Peoples who playing musical instruments"
          frameborder="0"
          allow="
            accelerometer clipboard-write encrypted-media gyroscope picture-in-picture web-share;
          "
          referrerpolicy="strict-origin-when-cross-origin"
          allowfullscreen
        ></iframe>
      </section>

      <section id="pricing">
        <div class="product">
          <div class="level" id="tenor">Tenor Trombone</div>
          <h2>$600</h2>
          <ul>
            <li>Good for beginners</li>
            <li>Excellent sound quality</li>
            <li>Great for Jazz Bands</li>
            <li>Nice and shiny</li>
          </ul>
          <button class="btn-level">select</button>
        </div>
        <div class="product">
          <div class="level" id="bass">Bass Trombone</div>
          <h2>$900</h2>
          <ul>
            <li>Sound quality is unmatched</li>
            <li>Best for professionals</li>
            <li>Absolutely stunning</li>
            <li>Durable and long lasting</li>
          </ul>
          <button class="btn-level">select</button>
        </div>
        <div class="product">
          <div class="level" id="bass">Valve Trombone</div>
          <h2>$1200</h2>
          <ul>
            <li>Plays similar to a Trumpet</li>
            <li>Great for Jazz Bands</li>
            <li>Beautiful in sound and appearance</li>
            <li>Just amazing</li>
          </ul>
          <button class="btn-level">select</button>
        </div>
      </section>
      <footer id="footer">
        <ul>
          <li class="foot-link"><a href="#">Privacy</a></li>
          <li class="foot-link"><a href="#">Terms</a></li>
          <li class="foot-link"><a href="#">Contact</a></li>
        </ul>
        <p>Copyright 2016, Original Trombones</p>
      </footer>
    </main>
  </body>
</html>
```

```css
:root {
  --h2-font-size-2000: 1.5rem;
  --h2-font-size-1200: 1.3rem;
  --h2-font-size-1024: 1.2rem;
  --h2-font-size-720: 1.1rem;
  --h2-font-size-600: 1rem;
  --h2-font-size-550: 0.95rem;
  --h2-font-size-420: 0.75rem;
  --button-size: 1.1rem;
  --bg-color1: #eee;
  --bg-color2: #f1c40f;
  --bg-color3: #ff8c00;
  --bg-color4: #ddd;
  --text-color1: #4a4141;
  --text-color2: #625f5f;
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  font-family: Verdana, sans-serif;
  background-color: var(--bg-color1, #eee);
  /* font-size: 0.9rem; */
}

main {
  position: relative;
  display: grid;
  grid-template-areas:
    "header header header"
    "form-started form-started form-started"
    "features features features"
    "how_it_works how_it_works how_it_works"
    "pricing pricing pricing"
    "footer footer footer";
  grid-template-columns: repeat(3, 1fr);
  margin: 0 auto;
}

#header {
  grid-area: header;
  grid-column: 1 / -1;
  position: fixed;
  top: 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  margin: 0 auto;
  background-color: var(--bg-color1, #eee);
}

#form-started {
  grid-area: form-started;
  grid-column: 1 / -1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.8rem;
  margin-top: 5rem;
}

#form {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
  align-items: center;
}

#form input {
  padding: 0.2rem 0.5rem;
}

input#email {
  width: 20rem;
}

input#submit {
  background-color: var(--bg-color2);
  border: none;
  width: 10rem;
  border-radius: 0.125rem;
  text-transform: uppercase;
  font-weight: 600;
  font-size: var(--button-size);
  cursor: pointer;
}

input#submit:hover {
  background-color: var(--bg-color3);
}

#features {
  grid-area: features;
  grid-column: 1 / -1;
  margin-top: 5rem;
  padding: 0 1rem 0;
}

.features-item {
  display: flex;
  gap: 2rem;
}

.icon i {
  display: flex;
  width: 6rem;
  height: 6rem;
  justify-content: center;
  align-items: center;
  color: var(--bg-color3);
}

.description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 0.25rem;
}

#how_it_works {
  grid-area: how_it_works;
  grid-column: 1 / -1;
  display: flex;
  justify-content: center;
  margin-top: 5rem;
}

#pricing {
  grid-area: pricing;
  grid-column: 1 / -1;
}

#footer {
  grid-area: footer;
  grid-column: 1 / -1;
  background-color: var(--bg-color4);
  display: grid;
  grid-template-columns: repeat(3, fr);

  display: flex;
  flex-direction: column;
  align-items: end;
  gap: 0.5rem;
  padding: 1rem 0.5rem;
}

#footer p {
  font-size: 0.945rem;
  color: var(--text-color2, #625f5f);
}

#nav-bar ul,
#footer ul {
  display: flex;
  list-style-type: none;
  gap: 2.5rem;
  padding: 0 0.5rem 0 0.5rem;
}

a.nav-link,
.foot-link a {
  display: inline-block;
  text-decoration: none;
  color: var(--text-color1);
  font-size: 0.945rem;
  padding: 0.3rem;
}

a.nav-link:hover,
.foot-link a:hover {
  background-color: var(--bg-color3);
  color: white;
  transform: scale(1.2, 1.2);
}

#pricing {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  gap: 2rem;
  margin: 5rem 0 3rem;
  padding: 0 1rem 0;
}

.product {
  display: flex;
  flex-direction: column;
  width: 30rem;
  border: 1px solid var(--text-color1);
  border-radius: 0.125rem;
}

.product ul {
  list-style-type: none;
}

.product ul > li {
  line-height: 2.5;
  text-align: center;
}

.product h2 {
  text-align: center;
}

.level {
  display: flex;
  justify-content: center;
  align-content: center;
  padding: 1.3rem 0 1.3rem;
  text-transform: uppercase;
  font-weight: 600;
  color: var(--text-color1);
  margin-bottom: 1.5rem;
  background-color: var(--bg-color4);
}

.btn-level {
  display: block;
  width: 8.25rem;
  margin: 0 auto;
  border: none;
  border-radius: 0.125rem;
  text-transform: uppercase;
  font-size: var(--button-size);
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
  padding: 1rem 1.25rem 1rem;
  background-color: var(--bg-color2);
  cursor: pointer;
}

.btn-level:hover {
  background-color: var(--bg-color3);
}

@media only screen and (max-width: 420px) {
  h2 {
    font-size: var(--h2-font-size-420);
  }

  #header {
    grid-template-columns: 1fr;
  }
}

@media only screen and (max-width: 550px) {
  h2 {
    font-size: var(--h2-font-size-550);
  }

  #header-img {
    max-width: 75rem;
    margin-left: 1rem;
  }
}

@media only screen and (max-width: 600px) {
  h2 {
    font-size: var(--h2-font-size-600);
  }

  #header-img {
    max-width: 65rem;
    margin-left: 1rem;
  }
}

@media only screen and (max-width: 720px) {
  h2 {
    font-size: var(--h2-font-size-720);
  }

  #header-img {
    max-width: 55rem;
    margin-left: 1rem;
  }
}

@media only screen and (max-width: 1024px) {
  h2 {
    font-size: var(--h2-font-size-1024);
  }

  #header-img {
    max-width: 45rem;
    margin-left: 2rem;
  }
}

@media only screen and (max-width: 1200px) {
  h2 {
    font-size: var(--h2-font-size-1200);
  }

  #header-img {
    max-width: 35rem;
    margin-left: 2rem;
  }
}

@media only screen and (max-width: 2000px) {
  h2 {
    font-size: var(--h2-font-size-2000);
  }

  #header-img {
    max-width: 20rem;
    margin-left: 2rem;
  }
}
```

## Output

### View On Big Screen Size >= 1200px (1920px)

![Image](https://github.com/user-attachments/assets/71635942-7e9e-44e1-9c79-68e4745ee2e6)

![Image](https://github.com/user-attachments/assets/120b6338-1919-4399-b02f-ac63467ac438)
