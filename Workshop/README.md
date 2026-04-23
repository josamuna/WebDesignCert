# All Workshop

Worshop projects.

## 1. CatPhoto Project

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CatPhotoApp</title>
  </head>
  <body>
    <main>
      <h1>CatPhotoApp</h1>
      <section>
        <h2>Cat Photos</h2>
        <p>
          Everyone loves
          <a
            href="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg"
            >cute cats</a
          >
          online!
        </p>
        <p>
          See more
          <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>
          in our gallery.
        </p>
        <a href="https://freecatphotoapp.com"
          ><img
            src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg"
            alt="A cute orange cat lying on its back."
        /></a>
      </section>
      <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>catnip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
          <img
            src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg"
            alt="A slice of lasagna on a plate."
          />
          <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img
            src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"
            alt="Two tabby kittens sleeping together on a couch."
          />
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
      </section>
    </main>
    <footer>
      <p>
        No Copyright -
        <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
      </p>
    </footer>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/ae09d3c9-c4e4-4ef4-a851-f48577374535)

![Image](https://github.com/user-attachments/assets/12ac7fde-7ee1-4e8c-87b5-ca431185c043)

## 2. Bookstore Project

`Source code`

```html
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>XYZ Bookstore Page</title>
  </head>

  <body>
    <h1>XYZ Bookstore</h1>
    <p>Browse our collection of amazing books!</p>

    <div class="card-container">
      <div class="card" id="sally-adventure-book">
        <h2>Sally's SciFi Adventure</h2>
        <p>
          This is an epic story of Sally and her dog Rex as they navigate
          through other worlds.
        </p>
        <button class="btn">Buy Now</button>
      </div>

      <div class="card" id="dave-cooking-book">
        <h2>Dave's Cooking Adventure</h2>
        <p>
          This is the story of Dave as he learns to cook everything from
          pancakes to pasta, one recipe at a time.
        </p>
        <button class="btn">Buy Now</button>
      </div>
    </div>

    <p>Review your selections and continue to checkout.</p>

    <div class="btn-container">
      <button class="btn" id="view-cart-btn">View Cart</button>
      <button class="btn" id="checkout-btn">Checkout</button>
    </div>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/063869c9-a696-47bb-88e8-ee63faac75ed)

## 3. MusicPlayer Project

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Working with the HTML Audio Element</title>
  </head>
  <body>
    <h1>freeCodeCamp Tunes</h1>

    <h2>Can't Stay Down</h2>
    <p>Artist: Quincy Larson</p>

    <audio
      src="https://cdn.freecodecamp.org/curriculum/js-music-player/can't-stay-down.mp3"
      loop
      controls
    ></audio>

    <h2>Cruising for a Musing</h2>
    <p>Artist: Quincy Larson</p>

    <audio
      src="https://cdn.freecodecamp.org/curriculum/js-music-player/cruising-for-a-musing.mp3"
      loop
      controls
    ></audio>

    <h2>Scratching the Surface</h2>
    <p>Artist: Quincy Larson</p>
    <audio
      src="https://cdn.freecodecamp.org/curriculum/js-music-player/scratching-the-surface.mp3"
      loop
      controls
    ></audio>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/f7f61f38-6d7c-4390-b91e-e3ed0ba72a66)

## 4. VideoPlayer Project

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Working with the HTML Video Element</title>
  </head>
  <body>
    <h1>Working with the HTML Video Element</h1>
    <video
      width="640"
      loop
      controls
      muted
      poster="https://cdn.freecodecamp.org/curriculum/labs/past-event2.jpg"
    >
      <source
        src="https://cdn.freecodecamp.org/curriculum/labs/what-is-the-map-method-and-how-does-it-work.mp4"
        type="video/mp4"
      />
      <source
        src="https://cdn.freecodecamp.org/curriculum/labs/mapmethod.webm"
        type="video/webm"
      />
      <source
        src="https://cdn.freecodecamp.org/curriculum/labs/mapmethod.ogg"
        type="video/ogg"
      />
      <source
        src="https://cdn.freecodecamp.org/curriculum/labs/mapmethod.mov"
        type="video/quicktime"
      />
    </video>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/e3d019ae-7fcc-4c3e-9b61-afbd36bbd12e)

## 5. EartBeat Project

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Heart Icon</title>
  </head>
  <body>
    <svg width="24" height="24" viewBox="0 0 24 24" fill="red">
      <path
        d="M12 21s-6-4.35-9.33-8.22C-.5 7.39 3.24 1 8.4 4.28 10.08 5.32 12 7.5 12 7.5s1.92-2.18 3.6-3.22C20.76 1 24.5 7.39 21.33 12.78 18 16.65 12 21 12 21z"
      ></path>
    </svg>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/8d5a6c38-0fd2-4650-bce6-3b6004786e06)

## 6. VideoPlaying Project with iframe

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Display Videos in an iframe</title>
  </head>
  <body>
    <h1>iframe Video Display</h1>
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/I0_951_MPE0"
      allow="accelerometer autoplay clipboard-write encrypted-media gyroscope web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen
    >
    </iframe>
  </body>
</html>
```

## 7. MajorWebBrowser

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>List of Browsers and Descriptions</title>
  </head>
  <body>
    <h1>List of Major Web Browsers</h1>
    <dl>
      <dt>Google Chrome</dt>
      <dd>
        This is a free web browser developed by Google and first released in
        2008.
      </dd>

      <dt>Firefox</dt>
      <dd>
        This is a free web browser developed by the Mozilla Corporation and
        first created in 2004.
      </dd>

      <dt>Safari</dt>
      <dd>
        This browser was developed by Apple and is the default browser for
        iPhone, iPad and Mac devices.
      </dd>

      <dt>Brave</dt>
      <dd>
        This is a free web browser first released in 2016 that is based on the
        Chromium web browser.
      </dd>

      <dt>Arc</dt>
      <dd>
        This is a free Chromium based web browser first released in 2023 by The
        Browser Company.
      </dd>
    </dl>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/a94651e0-df18-43a1-875d-d7c2b51da7e4)

## 8-JobTipsPage

`Source code`

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Quincy's Tips for Getting a Developer Job</title>
  </head>
  <body>
    <h1>Quincy's Tips for Getting a Developer Job</h1>
    <p>
      Learning to code is hard, but as Quincy Larson says,
      <q cite="https://www.freecodecamp.org/news/learn-to-code-book/"
        >You can become a developer.</q
      >
    </p>

    <main>
      <section>
        <h2>Envisioning Success</h2>
        <blockquote
          cite="https://www.freecodecamp.org/news/learn-to-code-book/"
        >
          Can you imagine what it would be like to be a successful developer? To
          have built software systems that people rely upon?
        </blockquote>
        <p>
          &mdash;Quincy Larson,
          <cite>How to Learn to Code and Get a Developer Job [Full Book]</cite>
        </p>
      </section>
      <section>
        <h2>Importance of Networking</h2>
        <blockquote
          cite="https://www.freecodecamp.org/news/learn-to-code-book/"
        >
          <p>So much of getting a job is who you know.</p>
          <p>
            It's OK to be an introvert, but you do need to push your boundaries.
          </p>
          <p>Create GitHub, Twitter, LinkedIn, and Discord accounts.</p>
          <p>Go to tech meetups and conferences. Travel if you have to.</p>
        </blockquote>
      </section>
      <section>
        <h2>Importance of Building a Reputation</h2>
        <blockquote
          cite="https://www.freecodecamp.org/news/learn-to-code-book/"
        >
          <p>Share short video demos of your projects.</p>
          <p>Keep applying to speak at bigger and bigger conferences.</p>
          <p>
            Hang out at hackerspaces and help people who are even newer to
            coding than you.
          </p>
        </blockquote>
      </section>
    </main>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/a41fb6c5-2831-4936-bec9-b332f7f9e93f)

## 9. CatBlogPage

`Source code`

```html
<!doctype html>
<html lang="en">
  <head>
    <title>Mr. Whiskers' Blog</title>
    <meta charset="UTF-8" />
  </head>
  <body>
    <header>
      <h1>Welcome to Mr. Whiskers' Blog Page!</h1>
      <figure>
        <img
          src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg"
          alt="a cat in the garden"
        />
        <figcaption>Mr. Whiskers in the Garden</figcaption>
      </figure>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#posts">Posts</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About</h2>
        <p>
          Hi there! I'm Jane Doe, a passionate writer who finds endless
          inspiration in the antics of my beloved cat, Mr. Whiskers.
        </p>
        <p>
          His playful nature and boundless energy keeps me on my toes. I love
          him so much.
        </p>
      </section>
      <section id="posts">
        <h2>Posts</h2>

        <article>
          <h3>Mr. Whiskers' First Day Home</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
            quod, voluptates, quae, quos quibusdam dolorum quia nemo repudiandae
            quidem voluptatum quas. Quisquam quod, voluptates, quae, quos
            quibusdam dolorum quia nemo repudiandae quidem voluptatum quas.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
            quod, voluptates, quae, quos quibusdam dolorum quia nemo repudiandae
            quidem voluptatum quas. Quisquam quod, voluptates, quae, quos
            quibusdam dolorum quia nemo repudiandae quidem voluptatum quas.
          </p>
        </article>
        <article>
          <h3>Mr. Whiskers' First Bath</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
            quod, voluptates, quae, quos quibusdam dolorum quia nemo repudiandae
            quidem voluptatum quas. Quisquam quod, voluptates, quae, quos
            quibusdam dolorum quia nemo repudiandae quidem voluptatum quas.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
            quod, voluptates, quae, quos quibusdam dolorum quia nemo repudiandae
            quidem voluptatum quas. Quisquam quod, voluptates, quae, quos
            quibusdam dolorum quia nemo repudiandae quidem voluptatum quas.
          </p>
        </article>
        <article>
          <h3>Mr. Whiskers' First Birthday Party</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
            quod, voluptates, quae, quos quibusdam dolorum quia nemo repudiandae
            quidem voluptatum quas. Quisquam quod, voluptates, quae, quos
            quibusdam dolorum quia nemo repudiandae quidem voluptatum quas.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
            quod, voluptates, quae, quos quibusdam dolorum quia nemo repudiandae
            quidem voluptatum quas. Quisquam quod, voluptates, quae, quos
            quibusdam dolorum quia nemo repudiandae quidem voluptatum quas.
          </p>
        </article>
      </section>
    </main>
    <footer>
      <section id="contact">
        <h2>Contact</h2>
        <address>
          <p>Phone: <a href="tel:5555555555">555-555-5555</a></p>
          <p>Email: <a href="mailto:fake@email.com">fake@email.com</a></p>
        </address>
      </section>
    </footer>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/cb5ab5e1-31ea-45d7-9e3d-a1a65a3cb17d)

## 10. HotelFeedbackForm

`Source code`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Hotel Feedback Form</title>
  </head>
  <body>
    <header>
      <h1>Hotel Feedback Form</h1>
      <p>
        Thank you for staying with us. Please provide feedback on your recent
        stay.
      </p>
    </header>
    <main>
      <form method="POST" action="https://hotel-feedback.freecodecamp.org">
        <fieldset>
          <legend>Personal Information</legend>
          <label for="full-name">Name (required):</label>
          <input
            type="text"
            id="full-name"
            name="name"
            placeholder="e.g., John Doe"
            required
            size="20"
          />

          <label for="email">Email address (required):</label>
          <input
            placeholder="example@email.com"
            required
            id="email"
            type="email"
            name="email"
            size="20"
          />
          <label for="age">Age (optional):</label>
          <input type="number" name="age" id="age" min="3" max="100" />
        </fieldset>

        <fieldset>
          <legend>Was this your first time at our hotel?</legend>
          <input id="yes-option" type="radio" name="hotel-stay" value="yes" />
          <label for="yes-option">Yes</label>
          <input id="no-option" type="radio" name="hotel-stay" value="no" />
          <label for="no-option">No</label>
        </fieldset>

        <fieldset>
          <legend>
            Why did you choose to stay at our hotel? (Check all that apply)
          </legend>

          <input type="checkbox" id="ads" name="choice" value="ads" />
          <label for="ads">Social Media Ads</label>

          <input
            type="checkbox"
            id="recommendation"
            name="choice"
            value="recommendation"
          />
          <label for="recommendation">Personal Recommendation</label>

          <input type="checkbox" id="location" name="choice" value="location" />
          <label for="location">Location</label>

          <input
            checked
            type="checkbox"
            id="reputation"
            name="choice"
            value="reputation"
          />
          <label for="reputation">Reputation</label>

          <input type="checkbox" id="price" name="choice" value="price" />
          <label for="price">Price</label>
        </fieldset>

        <fieldset>
          <legend>Ratings</legend>

          <label for="service">How was the service?</label>

          <select name="service" id="service">
            <option value="poor">Poor</option>
            <option value="satisfactory">Satisfactory</option>
            <option value="good">Good</option>
            <option value="very-good">Very Good</option>
            <option selected value="excellent">Excellent</option>
          </select>

          <label for="food">How was the food?</label>

          <select name="food" id="food">
            <option value="poor">Poor</option>
            <option value="satisfactory">Satisfactory</option>
            <option value="good">Good</option>
            <option value="very-good">Very Good</option>
            <option selected value="excellent">Excellent</option>
          </select>
        </fieldset>

        <label for="comments">Other Comments?</label>
        <textarea cols="30" rows="10" name="comments" id="comments"></textarea>

        <button type="submit">Submit</button>
      </form>
    </main>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/e5b6f1e3-07db-4776-82ee-24945f3cf35c)
