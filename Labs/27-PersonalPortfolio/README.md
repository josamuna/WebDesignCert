# PersonalPortfolio ([Available here](https://josueportfolio-profile.vercel.app/))

Designing a Personal Portfolio Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="./styles.css" />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
    />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
    />
  </head>
  <body>
    <main id="main">
      <nav id="navbar">
        <ul>
          <li><a href="#welcome-section">About</a></li>
          <li><a href="#project-section">Work</a></li>
          <li><a href="#profile-link">Contact</a></li>
        </ul>
      </nav>
      <section id="welcome-section">
        <h1>Hey! I am Josu&eacute; Isamuna Nkembo</h1>
        <p>a web developer</p>
      </section>
      <section id="project-section">
        <h2>These are some of my projects</h2>
        <div id="project-grid">
          <a
            href="https://github.com/josamuna/WebDesignCert/tree/main/Labs/18-FeatureSelectionPage"
            class="project"
            target="_blank"
          >
            <img
              class="project-img"
              src="https://cdn.corenexis.com/f/t6oBw70s1mx.png"
              alt="Feature Selection Page."
            />
            <p class="project-title">
              <span class="code">&lt;</span>
              Feature Selection Page
              <span class="code">/&gt;</span>
            </p>
          </a>
          <a
            href="https://github.com/josamuna/WebDesignCert/tree/main/Certification/3-BookInventoryApp"
            class="project"
            target="_blank"
          >
            <img
              class="project-img"
              src="https://cdn.corenexis.com/f/ECoxfsqWbYP.png"
              alt="Book Inventory App."
            />
            <p class="project-title">
              <span class="code">&lt;</span>
              Book Inventory App
              <span class="code">/&gt;</span>
            </p>
          </a>
          <a
            href="https://github.com/josamuna/WebDesignCert/tree/main/Certification/4-TechnicalDocumentationPage"
            class="project"
            target="_blank"
          >
            <img
              class="project-img"
              src="https://cdn.corenexis.com/f/U0FCxrLjhR5.png"
              alt="Technical Documentation Page."
            />
            <p class="project-title">
              <span class="code">&lt;</span>
              Technical Documentation Page
              <span class="code">/&gt;</span>
            </p>
          </a>
          <a
            href="https://github.com/josamuna/WebDesignCert/tree/main/Certification/5-ProductLandingPage"
            class="project"
            target="_blank"
          >
            <img
              class="project-img"
              src="https://cdn.corenexis.com/f/hFYaGrR6koe.png"
              alt="Product Landing Page."
            />
            <p class="project-title">
              <span class="code">&lt;</span>
              Product Landing Page
              <span class="code">/&gt;</span>
            </p>
          </a>
          <a
            href="https://github.com/josamuna/WebDesignCert/tree/main/Labs/19-ConfidentialEmailPage"
            class="project"
            target="_blank"
          >
            <img
              class="project-img"
              src="https://cdn.corenexis.com/f/aBJlFV7BwRX.png"
              alt="Confidential Email Page."
            />
            <p class="project-title">
              <span class="code">&lt;</span>
              Confidential Email Page
              <span class="code">/&gt;</span>
            </p>
          </a>
          <a
            href="https://github.com/josamuna/WebDesignCert/tree/main/Labs/20-PricingPlansLayoutPage"
            class="project"
            target="_blank"
          >
            <img
              class="project-img"
              src="https://cdn.corenexis.com/f/50IKnOZ7KAG.png"
              alt="Pricing Plans Layout Page."
            />
            <p class="project-title">
              <span class="code">&lt;</span>
              Pricing PlansLayout Page
              <span class="code">/&gt;</span>
            </p>
          </a>
        </div>
        <a
          href="https://github.com/josamuna/WebDesignCert/"
          class="all-project"
          target="_blank"
        >
          Show all <i class="fas fa-chevron-right"></i>
        </a>
      </section>
      <section id="profile-link">
        <div class="profile-header">
          <h2>Let's work together...</h2>
          <p>How do you take your coffee?</p>
        </div>
        <div class="profile-container">
          <a href="https://web.facebook.com/josamuna" target="_blank"
            ><i class="fab fa-facebook-square"></i> Facebook</a
          >
          <a href="https://github.com/josamuna" target="_blank"
            ><i class="fab fa-github"></i> GitHub</a
          >
          <a href="https://x.com/josamuna" target="_blank"
            ><i class="fab fa-twitter"></i> Twitter</a
          >
          <a href="mailto:josamuna2009@gmail.com"
            ><i class="fas fa-at"></i> Send a mail</a
          >
          <a href="tel:+243-972-727-527"
            ><i class="fas fa-mobile-alt"></i> Call me</a
          >
        </div>
      </section>
      <footer id="footer">
        <p>
          **This is my portfolio. All contact details given are real. Do not
          hesitateto reach me.
        </p>
        <p>
          © 2026. Created to gain a Responsive Web Design Certification on
          <a href="https://www.freecodecamp.org/" target="_blank"
            >freeCodeCamp&nbsp;<i class="fab fa-free-code-camp"></i
          ></a>
        </p>
      </footer>
    </main>
  </body>
</html>
```

```css
/* 
  Fontsize Calculation:
  - Default fontsize = 16px = 1rem
  - 16px = 100%, 1px = 100 / 16 = 6.25% 
  - By considering 1rem = 10px => 1rem = 10px = 62.5%  
 */

:root {
  --bg-color1: #383b3e;
  --bg-color2: #28292c;
  --bg-color3: #1b1a1c;
  --bg-color4: #45567d;
  --bg-color5: #be3144;
  --bg-color6: #31beab;
  --text-color: #f0f0f0;
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

/* BASE STYLING */

html {
  font-size: 62.5%;
}

body {
  font-family: Arial, Geneva, Tahoma, sans-serif;
}

h1,
h2 {
  color: var(--text-color);
  text-align: center;
}

h1 {
  font-size: 5rem;
}

h2 {
  font-size: 4.5rem;
}

a {
  text-decoration: none;
  color: var(--text-color);
}

ul {
  list-style-type: none;
}

img {
  display: block;
  width: 100%;
}

p {
  color: var(--text-color);
  font-family:
    system-ui,
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    "Open Sans",
    "Helvetica Neue",
    sans-serif;
}

/* MAIN CONTAINER */

#main {
  position: relative;
  display: grid;
  grid-template-areas:
    "navbar navbar"
    "welcome-section welcome-section" "project-section project-section"
    "profile-link profile-link" "footer footer";
  grid-template-columns: repeat(2, 1fr);
  width: 100%;
  margin: 0 auto;
}

/* GRID SECTIONS */

/* NAVBAR */

#navbar {
  position: fixed;
  top: 0;
  left: 0;
  grid-area: navbar;
  grid-column: 1 / -1;
  width: 100%;
  background-color: var(--bg-color5);
  display: flex;
  justify-content: flex-end;
  box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
}

#navbar ul {
  display: flex;
  margin-right: 2em;
}

#navbar a {
  display: block;
  font-size: 2.5rem;
  padding: 1em 1em;
}

#navbar a:hover,
#navbar a:focus {
  background-color: var(--bg-color4);
}

/* WELCOME SECTION */

#welcome-section {
  grid-area: welcome-section;
  grid-column: 1 / -1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100vh;
  background: linear-gradient(
    45deg,
    var(--bg-color1) 20%,
    var(--bg-color2) 60%,
    var(--bg-color3) 80%
  );
  text-align: center;
  gap: 2em;
}

#welcome-section p {
  color: var(--bg-color5);
  font-size: 3rem;
  font-style: italic;
}

/* PROJECT SECTION */

#project-section {
  grid-area: project-section;
  grid-column: 1 / -1;
  background-color: var(--bg-color4);
  padding: 0 2em;
  text-align: center;
}

#project-section h2 {
  margin: 2.5em auto 1em;
  border-bottom: 1px solid var(--text-color);
  max-width: 640px;
  padding-bottom: 0.15em;
}

#project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 4em 4em;
  margin: 0 auto 4em;
  max-width: 1280px;
}

.project {
  box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
  border-radius: 0 0 0.5em 0.5em;
  overflow: hidden;
  background-color: var(--bg-color1);
}

.project-img {
  object-fit: cover;
  width: 100%;
  height: calc(100% - 7rem);
}

.project-title {
  display: block;
  background-color: var(--bg-color1);
  font-size: 2rem;
  padding: 1em 0 1em;
}

.code {
  color: var(--bg-color1);
}

.project:hover .code,
.project:focus .code {
  color: orange;
  transition: color 0.3s ease-out;
}

.all-project {
  display: inline-block;
  font-size: 2.2rem;
  background-color: var(--bg-color1);
  padding: 1em 2em;
  margin-bottom: 2em;
}

.all-project i {
  margin-left: 0.3em;
  transform: translateX(0);
  transition: transform 0.3s ease-in-out;
}

.all-project:hover,
.all-project:focus {
  background-color: var(--bg-color5);
}

.all-project:hover i,
.all-project:focus i {
  transform: translateX(5px);
  transition: transform 0.3s ease-in-out;
}

/* PROFILE SECTION */

#profile-link {
  grid-area: profile-link;
  grid-column: 1 / -1;
  background: linear-gradient(
    45deg,
    var(--bg-color1) 20%,
    var(--bg-color2) 60%,
    var(--bg-color3) 80%
  );
  height: 82vh;
  border-bottom: 5px solid var(--bg-color5);

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 3em;
}

.profile-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 3em;
  padding: 2em 0;
}

.profile-container a {
  transform: translateY(0);
  transition: transform 0.3s ease-out;
  font-size: 2.5rem;
}

.profile-container a:hover,
.profile-container a:focus {
  transform: translateY(10px);
  transition: transform 0.3s ease-out;
}

.profile-header h2 {
  font-size: 6.5rem;
  padding-bottom: 0.2em;
}

.profile-header p {
  font-size: 2rem;
  font-style: italic;
  text-align: center;
}

/* FOOTER SECTION */

#footer {
  grid-area: footer;
  grid-column: 1 / -1;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  padding: 2.5em 1.5em;
  gap: 1em;
  align-items: center;
  font-size: 1.8rem;

  background: linear-gradient(
    45deg,
    var(--bg-color1) 20%,
    var(--bg-color2) 60%,
    var(--bg-color3) 80%
  );
}

#footer p {
  line-height: 1.5;
}

#footer i {
  vertical-align: middle;
}

#footer a:hover {
  color: var(--bg-color6);
}

/* Devices with max width of 640px and smaller - Small devices */
@media only screen and (max-width: 40em) {
  /* 
    Font calculation from screen size,
    Max screen size / Base Font size => 640px / 16px = 40em 
   */
  html {
    font-size: 60%;
  }

  #navbar {
    justify-content: center;
  }
}

@media only screen and (orientation: portrait) {
  html {
    font-size: 60%;
  }

  #navbar {
    justify-content: center;
  }
}

/* Devices with the width between 641px and 1024px - Medium devices. */
@media only screen and (max-width: 64em) {
  /* 
    Max screen size / Base Font size => 1024px / 16px = 64em
  */
  html {
    font-size: 58%;
  }
}

/* Devices with the width from 1025px and greather - Big devices. */
@media only screen and (min-width: 64.0625em) {
  /* 
    Max screen size / Base Font size => 1025px / 16px = 64em
  */
  html {
    font-size: 55%;
  }
}

@media (prefers-reduced-motion: no-preference) {
  * {
    scroll-behavior: smooth;
  }
}
```

## Output

### Very Small Screens (Width ~ 500px)

![Image](https://github.com/user-attachments/assets/a996ffa0-2400-4471-9a68-eec7ace629d3)

![Image](https://github.com/user-attachments/assets/1c828e4e-34ec-4a60-b2fb-d5972dfe4506)

![Image](https://github.com/user-attachments/assets/5fd9e4f3-ce11-4e6d-87c0-8e01066bd4de)

### Small Screens (With max width of 640px)

![Image](https://github.com/user-attachments/assets/04c7bbde-95b9-4f85-a39a-653ba5851e04)

![Image](https://github.com/user-attachments/assets/694e41be-ea83-4705-9690-32feba5a931e)

![Image](https://github.com/user-attachments/assets/212ea166-db06-49de-a49d-e83b2ff90185)

![Image](https://github.com/user-attachments/assets/337a4420-a283-4ffd-b254-c1f4dd42b43f)

![Image](https://github.com/user-attachments/assets/2418c44c-3208-4d8f-b006-16d3372ca799)

![Image](https://github.com/user-attachments/assets/38e14461-ec39-4f42-b549-6e715124548d)

### Medium Screens (With witdh between 641px and 1024px)

![Image](https://github.com/user-attachments/assets/5d58f467-d3e9-47aa-a135-d067f25bbed0)

![Image](https://github.com/user-attachments/assets/8025070b-732a-4658-bf2f-04c844a0755b)

![Image](https://github.com/user-attachments/assets/530be08b-ac95-463a-9b9b-cb23074cd786)

![Image](https://github.com/user-attachments/assets/8242e543-5cf6-47f2-af3c-0d6d7c08a08a)

### Big Screens (With width from 1025px and greather)

![Image](https://github.com/user-attachments/assets/5dac9921-0b9e-47e4-b638-c2825ea7239f)

![Image](https://github.com/user-attachments/assets/6d794e27-6ff0-4905-ab2b-f59febf8bfc9)

![Image](https://github.com/user-attachments/assets/89bc721a-7e6c-4ab3-b5bf-ad690be2ed7b)

![Image](https://github.com/user-attachments/assets/170aac72-2f41-49e2-a556-40a812dc7230)
