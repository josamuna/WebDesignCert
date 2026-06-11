# DesignContactForm

Designing a Contact Form Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Form</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <div class="form-container">
      <form>
        <h2>Contact Us</h2>
        <label for="name">Name: </label>
        <input type="text" id="name" name="name" required />
        <label for="email">Email: </label>
        <input type="email" id="email" name="email" required />
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </div>
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
  padding-top: 1.5em;
  padding-bottom: 1.5em;
  padding-left: 1.5em;
  padding-right: 2.9em;
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
  padding: 0.4em 0.8em 0.4em;
  min-height: 2.4em;
  border-radius: 0.4em;
  border: 1px solid #ccc;
  font-size: 0.95rem;
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
  cursor: pointer;
}
```

## Output

### Initial State

![Image](https://github.com/user-attachments/assets/b45ebd95-2c26-4ba9-829f-151684fbf500)

### Try Submitting The Form With Invalid Name

![Image](https://github.com/user-attachments/assets/bffb404f-0637-4107-8367-aa274d54fdd4)

### Try Submitting The Form With Invalid Email

![Image](https://github.com/user-attachments/assets/cf2442d8-e3a6-45ad-814d-396bc0d28792)

### Try Submitting The Form With Invalid Message

![Image](https://github.com/user-attachments/assets/9739a728-c08d-49ff-b967-cb5fad509ac2)

### Valid Data To Submit The Form

![Image](https://github.com/user-attachments/assets/8dd364fa-1843-41f7-a393-aa8407eccb61)
