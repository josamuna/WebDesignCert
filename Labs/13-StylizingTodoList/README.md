# StylizingTodoList

Designing a Todo list project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Styled To-Do List</title>
    <link rel="stylesheet" href="styles.css" />
  </head>

  <body>
    <div class="container">
      <h1>My To-Do List</h1>
      <ul class="todo-list">
        <li class="item">
          <input
            type="checkbox"
            id="gaming"
            name="gaming"
            value="gaming-task"
          />
          <label for="gaming">Explore gaming keyboards</label>
          <ul class="sub-item">
            <li>
              <a
                href="https://www.amazon.com/PC-Gaming-Keyboards/b?node=402051011"
                class="sub-item-link"
                target="_blank"
                >Store link</a
              >
            </li>
          </ul>
        </li>
        <li class="item">
          <input
            type="checkbox"
            id="report"
            name="report"
            value="report-task"
          />
          <label for="report">Finish the report</label>
          <ul class="sub-item">
            <li>
              <a
                href="https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-request-access"
                class="sub-item-link"
                target="_blank"
                >Request Access</a
              >
            </li>
          </ul>
        </li>
        <li class="item">
          <input type="checkbox" id="phone" name="phone" value="phone-task" />
          <label for="phone">View Phone's Warranty</label>
          <ul class="sub-item">
            <li>
              <a
                href="https://support.google.com/pixelphone/answer/6160400?hl=en"
                class="sub-item-link"
                target="_blank"
                >View Receipts</a
              >
            </li>
          </ul>
        </li>
        <li class="item">
          <input type="checkbox" id="model" name="model" value="model-task" />
          <label for="model">Check Processor Specs</label>
          <ul class="sub-item">
            <li>
              <a
                href="https://www.apple.com/newsroom/2023/10/apple-unveils-m3-m3-pro-and-m3-max-the-most-advanced-chips-for-a-personal-computer/"
                class="sub-item-link"
                target="_blank"
                >View Model Number</a
              >
            </li>
          </ul>
        </li>
      </ul>
    </div>
  </body>
</html>
```

```css
body {
  background-color: #f0f0f0;
  font-family: arial, sans-serif;
}

.container {
  margin-left: auto;
  margin-right: auto;
  background-color: white;
  border-radius: 15px;
  padding: 20px 5px;
  width: 90%;
  min-width: 300px;
}

.container h1 {
  text-align: center;
}

ul.todo-list {
  list-style-type: none;
  list-style-position: outside;
  margin-left: -20px;
  margin-right: 15px;
}

ul.todo-list li.item {
  line-height: 2;
  padding: 10px 10px 30px 10px;
  margin-bottom: 15px;
  border-radius: 10px;
}

.item {
  background-color: #e5f1e5;
}

.sub-item {
  list-style-type: square;
}

a {
  text-decoration: none;
}

a:link {
  color: blue;
}

a:hover {
  color: fuchsia;
}

a:focus {
  color: blue;
  border: 2px solid blue;
}

a:visited {
  color: blue;
  border: 2px solid blue;
}

a:active {
  border: 2px solid green;
  color: #570607;
}
```

## Output

![Image](https://github.com/user-attachments/assets/f4e02d90-afc8-4ec9-a60e-a213ccb3fac7)
