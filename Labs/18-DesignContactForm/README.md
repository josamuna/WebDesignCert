# DesignContactForm

Designing a Contact Form Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Registration Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Registration Form</h1>
    <p>Please fill out this form with the required information</p>
    <form method="post" action="https://register-demo.freecodecamp.org">
      <fieldset>
        <label for="first-name"
          >Enter Your First Name:
          <input id="first-name" name="first-name" type="text" required
        /></label>
        <label for="last-name"
          >Enter Your Last Name:
          <input id="last-name" name="last-name" type="text" required
        /></label>
        <label for="email"
          >Enter Your Email:
          <input id="email" name="email" type="email" required
        /></label>
        <label for="new-password"
          >Create a New Password:
          <input
            id="new-password"
            name="new-password"
            type="password"
            pattern="[a-z0-5]{8,}"
            required
        /></label>
      </fieldset>
      <fieldset>
        <legend>Account type (required)</legend>
        <label for="personal-account"
          ><input
            id="personal-account"
            type="radio"
            name="account-type"
            value="personal"
            class="inline"
            checked
          />
          Personal</label
        >
        <label for="business-account"
          ><input
            id="business-account"
            type="radio"
            name="account-type"
            value="business"
            class="inline"
          />
          Business</label
        >
      </fieldset>
      <fieldset>
        <label for="profile-picture"
          >Upload a profile picture:
          <input id="profile-picture" type="file" name="file"
        /></label>
        <label for="age"
          >Input your age (years):
          <input id="age" type="number" name="age" min="13" max="120"
        /></label>
        <label for="referrer"
          >How did you hear about us?
          <select id="referrer" name="referrer">
            <option value="">(select one)</option>
            <option value="1">freeCodeCamp News</option>
            <option value="2">freeCodeCamp YouTube Channel</option>
            <option value="3">freeCodeCamp Forum</option>
            <option value="4">Other</option>
          </select>
        </label>
        <label for="bio"
          >Provide a bio:
          <textarea
            id="bio"
            name="bio"
            rows="3"
            cols="30"
            placeholder="I like coding on the beach..."
          ></textarea>
        </label>
      </fieldset>
      <a href="https://www.freecodecamp.org/news/terms-of-service"
        >Read our terms and conditions</a
      >
      <label for="terms-and-conditions">
        <input
          class="inline"
          name="terms"
          id="terms-and-conditions"
          type="checkbox"
          required
        />
        I accept the terms and conditions
      </label>
      <input type="submit" value="Submit" />
    </form>
  </body>
</html>
```

```css
* {
  margin: 0;
  padding: 0;
}

body {
  background: linear-gradient(to right, #8bb2db, #b4f8fd);
  font-family: Arial, Tahoma, sans-serif;
  font-size: 1rem;
}

h2 {
  margin: 1em auto;
  text-align: center;
}

.form-container {
  background-color: white;
  border-radius: 0.8em;
  margin: 4em auto;
  padding: 1.5em 1.5em;
  max-width: 400px;
  min-width: 300px;
  width: 60vw;
}

label {
  display: block;
  margin: 0.5em 0;
  color: #433;
  text-align: center;
  font-size: 1.1rem;
}

input,
textarea {
  width: 100%;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 0.8em;
  padding: 0; /* Delete later*/
  min-height: 3em;
  border-radius: 0.4em;
  border: 1px solid #ccc;
}

button {
  background-color: #45a049;
  font-size: 1.05em;
  color: #fffefe;
  margin-bottom: 0.4em;
  margin-top: 0.4em;
  margin-left: auto;
  margin-right: auto;
  display: block;
  padding: 0.6em 0.1em;
  width: 20%;
  border: none;
  border-radius: 0.3em;
}

button:hover {
  background-color: #3e8f42;
}

/* TOBE DELETED*/
```

## Output

![Image](https://github.com/user-attachments/assets/b45ebd95-2c26-4ba9-829f-151684fbf500)
