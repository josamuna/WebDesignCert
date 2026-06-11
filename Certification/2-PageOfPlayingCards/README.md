# PageOfPlayingCards

Building a Page of Playing Cards Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Playing Cards</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <main id="playing-cards">
      <div class="card">
        <div class="left">
          <div>A</div>
          <div>♠</div>
        </div>
        <div class="middle">
          <div>♠</div>
        </div>
        <div class="right">
          <div class="reverse">♠</div>
          <div class="reverse">A</div>
        </div>
      </div>
      <div class="card">
        <div class="left">
          <div>2</div>
          <div>♣</div>
        </div>
        <div class="middle">
          <div>♣</div>
          <div class="reverse">♣</div>
        </div>
        <div class="right">
          <div class="reverse">♣</div>
          <div class="reverse">2</div>
        </div>
      </div>
      <div class="card red-colored">
        <div class="left">
          <div>3</div>
          <div>♥</div>
        </div>
        <div class="middle">
          <div>♥</div>
          <div>♥</div>
          <div class="reverse">♥</div>
        </div>
        <div class="right">
          <div class="reverse">♥</div>
          <div class="reverse">3</div>
        </div>
      </div>
      <div class="card">
        <div class="left">
          <div>4</div>
          <div>♣</div>
        </div>
        <div class="middle">
          <div>♣♣</div>
          <div class="reverse">♣♣</div>
        </div>
        <div class="right">
          <div class="reverse">♣</div>
          <div class="reverse">4</div>
        </div>
      </div>
      <div class="card red-colored">
        <div class="left">
          <div>5</div>
          <div>♦</div>
        </div>
        <div class="middle">
          <div>♦♦</div>
          <div>♦</div>
          <div>♦♦</div>
        </div>
        <div class="right">
          <div>♦</div>
          <div class="reverse">5</div>
        </div>
      </div>
    </main>
  </body>
</html>
```

```css
body {
  background-color: #d8bfd8;
}

#playing-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  width: 90%;
  margin: 0 auto;
  padding: 20px;
}

.card {
  display: flex;
  justify-content: space-between;
  padding: 10px 5px;
  width: 250px;
  height: 350px;
  background-color: white;
  border: 1px solid #261526;
  border-radius: 10px;
  font-size: 2rem;
  font-weight: 600;
  box-shadow: 1px 1px 3px 1px #5a4956;
}

.left {
  align-self: flex-start;
  text-align: center;
}

.middle {
  display: flex;
  flex-direction: column;
  align-self: center;
  align-items: center;
  font-size: 5.5rem;
}

.right {
  align-self: flex-end;
  text-align: center;
}

.reverse {
  transform: rotate(180deg);
}

.red-colored {
  color: red;
}
```

## Output

### Output With Maximixed Window

![Image](https://github.com/user-attachments/assets/3e306577-3566-46fb-b5a1-78ce970eb9e2)

### Output With Reduced Window

![Image](https://github.com/user-attachments/assets/7b3cbe8e-32dc-4c06-ad95-97f35f18c546)
