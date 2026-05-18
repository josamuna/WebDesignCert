# ConfidentialEmailPage

Building a Confidential Email Page Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Confidential Email</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <main id="email">
      <div id="confidential">CONFIDENTIAL</div>
      <div id="top-secret">TOP SECRET</div>
      <p>Dear Agent <span class="blurred">S'more,</span></p>
      <p>
        We have an emergency. The secret formula for our
        <span class="blurred">Mega Marshmallow</span> has been compromised. This
        formula is what makes our marshmallows the fluffiest and most delicious.
      </p>
      <p>
        We suspect that <span class="blurred">Professor Puff</span> is behind
        this. He has taken the formula to his hidden laboratory. Your mission is
        to infiltrate the lab and secure the formula before it's too late.
      </p>
      <p>
        Be sure to keep the lab's location confidential. Any leak of this
        information could jeopardize the entire operation.
      </p>
    </main>
  </body>
</html>
```

### CSS Code to Pass the Challenge ❎

```css
#email {
  padding: 50px;
  margin: 50px auto;
  width: 500px;
  border: 2px solid #000000;
  box-sizing: border-box;
  background-color: #fff5ee;
  box-shadow: 2px 2px 2px 1px #aca8a8;
}

#confidential,
#top-secret {
  display: inline-block;
  padding: 20px;
  margin-left: 10px;
  border: 2px solid red;
  font-weight: 600;
  color: red;
}

#confidential {
  transform: rotate(-25deg) translate(80px, 50px);
  font-size: 1.3rem;
}

#top-secret {
  transform: rotate(10deg) translate(90px, 260px);
  font-size: 1.12rem;
}

.blurred {
  filter: blur(3px);
}
```

### CSS Code for the Proper Output ✅

```css
#email {
  padding: 50px 50px 120px;
  margin: 50px auto;
  width: 500px;
  border: 2px solid #000000;
  box-sizing: border-box;
  background-color: #fff5ee;
  box-shadow: 2px 2px 2px 1px #aca8a8;
}

#confidential,
#top-secret {
  display: inline-block;
  padding: 10px 20px;
  margin-left: 10px;
  border: 4px solid red;
  font-weight: 600;
  color: red;
}

#confidential {
  transform: rotate(-25deg) translate(80px, 50px);
  font-size: 1.3rem;
}

#top-secret {
  transform: rotate(20deg) translate(130px, 290px);
  font-size: 1.12rem;
}

.blurred {
  filter: blur(3px);
}
```

## Output with Code Pass ❎

![Image](https://github.com/user-attachments/assets/d7bdd3f9-34b3-4813-bdc5-96b67ed0bd81)

## Output with the Proper view ✅

![Image](https://github.com/user-attachments/assets/c2b73911-9ea3-4182-b2eb-c55f900657be)
