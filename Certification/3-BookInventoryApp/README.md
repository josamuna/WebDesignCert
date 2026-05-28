# BookInventoryApp

Building a Book Inventory App Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Book Inventory</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <h1>Book Inventory</h1>
    <table>
      <thead>
        <tr>
          <th>Title</th>
          <th>Author</th>
          <th>Category</th>
          <th>Status</th>
          <th>Rate</th>
        </tr>
      </thead>
      <tbody>
        <tr class="read">
          <td>The Three Musketeers</td>
          <td>Alexandre Dumas</td>
          <td>Historical Novel</td>
          <td>
            <span class="status">Read</span>
          </td>
          <td>
            <span class="rate three">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </td>
        </tr>
        <tr class="to-read">
          <td>The Plague</td>
          <td>Albert Camus</td>
          <td>Philosophical Novel</td>
          <td>
            <span class="status">To Read</span>
          </td>
          <td>
            <span class="rate">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </td>
        </tr>
        <tr class="read">
          <td>The Metamorphosis</td>
          <td>Franz Kafka</td>
          <td>Novella</td>
          <td>
            <span class="status">Read</span>
          </td>
          <td>
            <span class="rate one">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </td>
        </tr>
        <tr class="read">
          <td>Dead Souls</td>
          <td>Nikolai Gogol</td>
          <td>Picaresque</td>
          <td>
            <span class="status">Read</span>
          </td>
          <td>
            <span class="rate two">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </td>
        </tr>
        <tr class="in-progress">
          <td>Lord of the Flies</td>
          <td>William Golding</td>
          <td>Allegorical Novel</td>
          <td>
            <span class="status">In Progress</span>
          </td>
          <td>
            <span class="rate">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </td>
        </tr>
        <tr class="read">
          <td>Do Androids Dream of Electric Sheep?</td>
          <td>Philip K. Dick</td>
          <td>Science Fiction</td>
          <td>
            <span class="status">Read</span>
          </td>
          <td>
            <span class="rate two">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

```css
body {
  font-family: Arial, sans-serif;
}

h1 {
  text-align: center;
}

table {
  border-collapse: collapse;
  margin: 20px auto;
}

td {
  text-align: center;
  vertical-align: center;
  padding: 4px 20px;
}

thead tr {
  background-image: linear-gradient(to top, #80d7fa, #b2e9ff, #dff6ff);
  height: 35px;
}

tr[class="read"] {
  background-image: linear-gradient(to top, #9fff9f, #d1ffd1, #edfded);
}

tr[class="to-read"] {
  background-image: linear-gradient(to top, #d7e4d7, #e2e7e2, #fafafa);
}

tr[class="in-progress"] {
  background-image: linear-gradient(to top, #ffdf9f, #ffeecc, #f0f0f0);
}

span {
  display: inline-block;
}

tr[class="read"] span[class="status"] {
  background-image: linear-gradient(to top, #59d659, #7ce57c, #b1efb1);
  border: 1px solid #31d131;
  border-radius: 50px 50px 50px 50px;
}

tr[class="to-read"] span[class="status"] {
  background-image: linear-gradient(to top, #ff2815, #fe695d, #ff968e);
  border: 1px solid #f64838;
  border-radius: 50px 50px 50px 50px;
}

tr[class="in-progress"] span[class="status"] {
  background-image: linear-gradient(to top, #f4b12d, #fcd07a, #fcebc9);
  border: 1px solid #ffbf41;
  border-radius: 50px 50px 50px 50px;
}

span[class="status"],
span[class^="rate"] {
  width: 90px;
  height: 20px;
  padding: 5px 15px;
}

span[class^="rate"] > span {
  border: 1px solid #a19f9a;
  border-radius: 50%;
  width: 18px;
  height: 18px;
  margin: 5px 0;
  background-color: #fcfcf8;
}

span[class~="one"] span:first-of-type {
  background-image: linear-gradient(#ffdf3c);
}

span[class~="two"] span:nth-of-type(-n + 2) {
  background-image: linear-gradient(#ffdf3c);
}

span[class~="three"] span {
  background-image: linear-gradient(#ffdf3c);
}
```

## Output

![Image](https://github.com/user-attachments/assets/52dd86d0-ae76-41fa-b81d-dc877b95e093)
