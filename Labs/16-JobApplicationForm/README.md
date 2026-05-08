# JobApplicationForm

Building a Job Application Form project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Job Application Form</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="container">
      <h1 class="center">Job Application Form</h1>
      <form>
        <label for="name" class="label-view">Full Name:</label>
        <input
          type="text"
          id="name"
          name="full-name"
          placeholder="Enter your name"
          autocomplete="cc-given-name"
          required
        />
        <label for="email" class="label-view">Email:</label>
        <input
          type="email"
          id="email"
          name="email"
          placeholder="Enter your email"
          autocomplete="email"
          required
        />
        <label for="position" class="label-view">Position:</label>
        <select id="position" name="position" required>
          <option value="" selected disabled>Select a position</option>
          <option value="developer">Developer</option>
          <option value="designer">Designer</option>
          <option value="Manager">Manager</option>
        </select>
        <fieldset class="radio-group">
          <legend>Availability:</legend>
          <input
            type="radio"
            id="full-time"
            name="availability"
            value="full-time"
            checked
          />
          <label for="full-time" class="radio-label">Full-Time</label>
          <input
            type="radio"
            id="part-time"
            name="availability"
            value="part-time"
          />
          <label for="part-time" class="radio-label">Part-Time</label>
        </fieldset>
        <label for="message" class="label-view"
          >Why do you want this job?</label
        >
        <textarea
          id="message"
          placeholder="Write your motivation"
          rows="5"
          required
        ></textarea>
        <button type="submit">Submit Application</button>
      </form>
    </div>
  </body>
</html>
```

```css
body {
  font-family: Arial, sans-serif;
}

.container {
  margin: 50px auto;
  max-width: 700px;
  width: 85%;
  padding: 50px 20px 15px 20px;
  box-shadow: 0 5px 15px gray;
  border-radius: 10px;
}

h1 {
  text-align: center;
  color: darkgreen;
}

input:not([type='radio']),
select,
textarea {
  display: block;
  width: calc(100% - 10px);
  padding: 10px 4px;
  font-size: 0.9rem;
  margin: 10px auto;
  border-radius: 5px;
}

select {
  width: 100%;
}

fieldset {
  margin: 10px auto;
  padding: 20px 5px;
  border-radius: 5px;
}

.label-view {
  font-size: 1rem;
  font-weight: 600;
  display: block;
  width: 100%;
  padding: 5px 0px;
}

input:focus,
textarea:focus {
  border: 1px solid red;
}

input:invalid,
select:invalid,
textarea:invalid {
  border: 1px solid red;
}

input:valid,
select:valid,
textarea:valid {
  border: 1px solid green;
}

.radio-label {
  font-size: 1rem;
}

.radio-group input[type='radio'] {
  appearance: none;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  border: 2px solid gray;
}

.radio-group input[type='radio']::before {
  display: block;
  content: ' ';
  width: 10px;
  height: 10px;
  border-radius: 50%;
  transform: translate(3px, 3px) scale(0);
  transition: all 0.1s ease-in;
}

.radio-group input[type='radio']:checked::before {
  transform: translate(3px, 3px) scale(1);
  background-color: green;
}

.radio-group input[type='radio']:checked {
  border: 2px solid green;
  background-color: white;
  box-shadow: 0 1px 5px green;
}

input[type='radio']:checked + label {
  color: #008000;
}

button {
  background-color: #008000;
  border: none;
  border-radius: 5px;
  color: whitesmoke;
  display: block;
  margin: 10px auto;
  padding: 12px 20px;
  width: 100%;
  font-size: 1rem;
}

button:hover {
  background-color: #000000;
  cursor: pointer;
}

input:first-of-type {
  border-radius: 5px;
}
```

## Output

### Initial State

![Image](https://github.com/user-attachments/assets/ec781980-439a-4ea6-9218-609ce78173e7)

### State with submit button hover

![Image](https://github.com/user-attachments/assets/55189995-928f-49ba-9bd7-2f18eca721e1)

### State with invalid field

![Image](https://github.com/user-attachments/assets/b7215e72-94ad-402c-86c1-bf963300d858)

### State with all valids fields

![Image](https://github.com/user-attachments/assets/c554714f-fb68-48d9-8af6-951263230465)
